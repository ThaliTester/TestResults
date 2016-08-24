#### Test 82337235c6facd5_thali03_samsung-SM-A300FU Logs


```
--------- beginning of main
08-24 14:31:03.366   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 590us total 24.665ms
08-24 14:31:03.386   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 764us total 17.725ms
--------- beginning of system
08-24 14:31:03.386  1018  1449 D PowerManagerService: [api] handleWakeLockDeath : release WakeLock : PARTIAL_WAKE_LOCK              'AlarmReceiver' (uid=10081, pid=6696, ws=null) (elapsedTime=2615)
08-24 14:31:03.446  1018  3813 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-24 14:31:03.446  1018  3813 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:03.446  1018  3813 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:03.446  1018  3813 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,08-24 14:31:03.456  1018  1439 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-24 14:31:03.456  1018  1439 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-24 14:31:03.456  1018  1439 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:03.456  1018  1439 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:03.456  1018  1439 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-24 14:31:03.466  7096  7096 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-24 14:31:03.536  7096  7096 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-24 14:31:03.556  1018  1508 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-24 14:31:03.556  1018  1508 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4187, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 14:31:03.556  1018  1508 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 14:31:03.566  1018  1508 D BatteryService: stay LED for charging
08-24 14:31:03.566  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-24 14:31:03.566  1018  1018 I MotionRecognitionService: Plugged
08-24 14:31:03.566  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
08-24 14:31:03.566  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-24 14:31:03.566  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
08-24 14:31:03.576  1424  1424 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-24 14:31:03.576  1424  1424 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-24 14:31:03.586  3217  3217 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-24 14:31:03.586  3217  3356 D HeadsetStateMachine: Disconnected process message: 10
08-24 14:31:03.596  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-24 14:31:03.596  1179  1179 D SViewCoverView: level :100 plugged : 2
08-24 14:31:03.596  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-24 14:31:03.596  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-24 14:31:03.596  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-24 14:31:03.616  7061  7061 W art     : Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 201.803ms
08-24 14:31:03.706  1018  1030 I art     : Explicit concurrent mark sweep GC freed 143510(8MB) AllocSpace objects, 3(1847KB) LOS objects, 33% free, 23MB/34MB, paused 2.639ms total 221.439ms
08-24 14:31:03.706  1018  1441 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
08-24 14:31:03.706  1018  1441 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
08-24 14:31:03.706  1018  1441 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:03.706  1018  1441 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:03.706  1018  1441 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
08-24 14:31:03.716  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-24 14:31:03.716  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:03.716  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:03.716  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-24 14:31:03.726  7124  7124 D AndroidRuntime: 
08-24 14:31:03.726  7124  7124 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-24 14:31:03.726  1018  1137 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-24 14:31:03.726  1018  1137 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-24 14:31:03.726  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:03.726  1018  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:03.726  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-24 14:31:03.726  7124  7124 D AndroidRuntime: CheckJNI is OFF
08-24 14:31:03.726  7124  7124 D AndroidRuntime: readGMSProperty: start
08-24 14:31:03.726  7124  7124 D AndroidRuntime: readGMSProperty: already setted!!
08-24 14:31:03.726  7124  7124 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-24 14:31:03.726  7124  7124 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-24 14:31:03.726  7124  7124 D AndroidRuntime: readGMSProperty: end
08-24 14:31:03.726  7124  7124 D AndroidRuntime: addProductProperty: start
08-24 14:31:03.756  1018  1439 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
08-24 14:31:03.756  1018  1439 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
08-24 14:31:03.756  1018  1439 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:03.756  1018  1439 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:03.756  1018  1439 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
08-24 14:31:03.766  1938  7035 W BaseAppContext: Using Auth Proxy for data requests.
08-24 14:31:03.766  1938  7035 W BaseAppContext: Using Auth Proxy for data requests.
08-24 14:31:03.776  7061  7061 W art     : Verification of com.sec.android.touchwiz.animator.TwDndHorizontalListAnimator com.android.mms.ArtClassLoader.createTwDndHorizontalListAnimator(android.content.Context) took 155.172ms
08-24 14:31:03.786  7061  7134 D Mms/ArtClassLoader: init before art
08-24 14:31:03.796  7061  7061 D Mms/TelephonyPermission: start operation mode monitor
08-24 14:31:03.826  7061  7061 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-24 14:31:03.836  7061  7061 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
08-24 14:31:03.836  7061  7061 D Mms/TelephonyPermission: isDefault true
08-24 14:31:03.836  2653  2698 I art     : Explicit concurrent mark sweep GC freed 20172(971KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 8MB/13MB, paused 1.094ms total 60.237ms
08-24 14:31:03.836  7061  7061 D Mms/MmsApp: onCreate() com.android.mms
08-24 14:31:03.846  1018  3813 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-24 14:31:03.856  1018  3813 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:03.856  1018  3813 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:03.856  1018  3813 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-24 14:31:03.856  7096  7096 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
08-24 14:31:03.866  1018  1439 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
08-24 14:31:03.876  1018  1439 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:03.876  1018  1439 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:03.876  1018  1439 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:03.876  1018  1439 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:03.876  7096  7096 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-24 14:31:03.886  7137  7137 E Zygote  : MountEmulatedStorage()
08-24 14:31:03.886  7137  7137 E Zygote  : v2
08-24 14:31:03.886  7137  7137 I libpersona: KNOX_SDCARD checking this for 10148
08-24 14:31:03.886  7137  7137 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 14:31:03.886  7137  7137 I libpersona: KNOX_SDCARD not a persona
08-24 14:31:03.886  1018  1439 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7137 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
08-24 14:31:03.896  7137  7137 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 14:31:03.896  7137  7137 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-24 14:31:03.896  1018  1449 I ActivityManager: Killing 6711:com.sec.esdk.elm/u0a90 (adj 15): empty #21
08-24 14:31:03.896  7124  7124 E AffinityControl: AffinityControl: registerfunction enter
08-24 14:31:03.916  6891  6933 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 837 ms] updated apps [took 837 ms] 
08-24 14:31:03.926  7137  7137 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:31:03.926  1018  3812 I ActivityManager: Killing 6474:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
08-24 14:31:03.926  7124  7124 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-24 14:31:03.926  7137  7137 D ActivityThread: Added TimaKeyStore provider
08-24 14:31:03.936  1018  1491 E PersonaManagerService: inState():  stateMachine is null !!
08-24 14:31:03.936  7061  7061 D Mms/MmsApp: [start]    initCountryIso consume time = 618.035468
08-24 14:31:03.936  1018  1031 D CountryDetector: The first listener is added
08-24 14:31:03.946  1018  1491 I PersonaManagerService: PersonaId don't exist
08-24 14:31:03.946  1018  1491 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-24 14:31:03.946  7061  7061 D Mms/MmsApp: [end]    initCountryIso consume time = 9.841719
08-24 14:31:03.946  7061  7061 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.106719
08-24 14:31:03.956  1018  1491 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-24 14:31:03.966  7061  7061 D Mms/MmsConfig: before partial update
08-24 14:31:03.966  1018  1491 W ActivityManager: mDVFSHelper.acquire()
08-24 14:31:03.966  1018  1491 D FocusedStackFrame: Set to : 0
08-24 14:31:03.976  1018  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:03.976  1018  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:03.976  1018  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:03.976  1018  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:03.976  1018  1049 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-24 14:31:03.976  1018  1049 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-24 14:31:03.986  7137  7137 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
08-24 14:31:03.986  7162  7162 E Zygote  : MountEmulatedStorage()
08-24 14:31:03.986  7162  7162 E Zygote  : v2
08-24 14:31:03.986  7162  7162 I libpersona: KNOX_SDCARD checking this for 10170
08-24 14:31:03.986  7162  7162 I libpersona: KNOX_SDCARD not a persona
08-24 14:31:03.986  1018  1491 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7162 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-24 14:31:03.996  1018  1491 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-24 14:31:03.996  1018  1491 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-24 14:31:03.996  7162  7162 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 14:31:03.996  1018  1491 D InputDispatcher: Focused application set to: xxxx
08-24 14:31:03.996  1018  1491 D InputDispatcher: Focus left window: 1493
08-24 14:31:03.996  7124  7124 D AndroidRuntime: Shutting down VM
08-24 14:31:03.996  7162  7162 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 14:31:03.996  7162  7162 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-24 14:31:04.006  1018  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-24 14:31:04.006  1018  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-24 14:31:04.006  7061  7061 D Mms/MmsConfig: Load Resize quality : 80
08-24 14:31:04.006   258   258 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
08-24 14:31:04.016  7061  7061 D EasySignUpManager_1.0.1: serviceId : 1, features : -1
08-24 14:31:04.016  1938  7035 W BaseAppContext: Using Auth Proxy for data requests.
08-24 14:31:04.026  7061  7061 D EasySignUpManager_1.0.1: isAuth is false
08-24 14:31:04.026  7061  7061 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
08-24 14:31:04.026  1018  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-24 14:31:04.026  1018  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
08-24 14:31:04.036  1018  1492 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
08-24 14:31:04.036  1018  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:04.036  1018  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:04.036  1018  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:04.036  1018  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:04.056  1466  1488 D TP/MmsSmsProvider: query,matched:2117, calling pid = 7061
08-24 14:31:04.056  1466  1488 D TP/MmsSmsProvider: match 2117:Elapsed time : 1.492 ms
08-24 14:31:04.066  7179  7179 E Zygote  : MountEmulatedStorage()
08-24 14:31:04.066  7179  7179 E Zygote  : v2
08-24 14:31:04.066  7179  7179 I libpersona: KNOX_SDCARD checking this for 1000
08-24 14:31:04.066  7179  7179 I libpersona: KNOX_SDCARD not a persona
08-24 14:31:04.066  7179  7179 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 14:31:04.066  7179  7179 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 14:31:04.066  1018  1492 I ActivityManager: Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=7179 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-24 14:31:04.076  7179  7179 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-24 14:31:04.076  1018  1492 I ActivityManager: Killing 6489:com.android.calendar/u0a131 (adj 15): empty #21
08-24 14:31:04.076  7162  7162 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:31:04.076  7162  7162 D ActivityThread: Added TimaKeyStore provider
08-24 14:31:04.086  7061  7061 D EasySignUpManager_1.0.1: isAuth is false
08-24 14:31:04.086  7061  7061 D EasySignUpManager_1.0.1: getServiceStatus : serviceId (1) is OFF
08-24 14:31:04.086  7061  7061 E CscParser: mps_code.dat does not exist
08-24 14:31:04.086  7061  7061 E CscParser: customer_path =/system/csc/customer.xml
08-24 14:31:04.086  7061  7061 E CscParser: fileName + /system/csc/customer.xml
08-24 14:31:04.096  1018  1491 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-24 14:31:04.096  1018  1489 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-24 14:31:04.106  1018  1049 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
08-24 14:31:04.106  1018  1018 V ActivityManager: Display changed displayId=0
08-24 14:31:04.106  7179  7179 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:31:04.106  1018  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-24 14:31:04.106  7179  7179 D ActivityThread: Added TimaKeyStore provider
08-24 14:31:04.106  1018  1049 W DisplayManagerService: Failed to notify process 6489 that displays changed, assuming it died.
08-24 14:31:04.106  1018  1049 W DisplayManagerService: android.os.TransactionTooLargeException
08-24 14:31:04.106  1018  1049 W DisplayManagerService: 	at android.os.BinderProxy.transactNative(Native Method)
08-24 14:31:04.106  1018  1049 W DisplayManagerService: 	at android.os.BinderProxy.transact(Binder.java:496)
08-24 14:31:04.106  1018  1049 W DisplayManagerService: 	at android.hardware.display.IDisplayManagerCallback$Stub$Proxy.onDisplayEvent(IDisplayManagerCallback.java:81)
08-24 14:31:04.106  1018  1049 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService$CallbackRecord.notifyDisplayEventAsync(DisplayManagerService.java:1372)
08-24 14:31:04.106  1018  1049 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService.deliverDisplayEvent(DisplayManagerService.java:1170)
08-24 14:31:04.106  1018  1049 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService.access$500(DisplayManagerService.java:146)
08-24 14:31:04.106  1018  1049 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService$DisplayManagerHandler.handleMessage(DisplayManagerService.java:1305)
08-24 14:31:04.106  1018  1049 W DisplayManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:31:04.106  1018  1049 W DisplayManagerService: 	at android.os.Looper.loop(Looper.java:145)
08-24 14:31:04.106  1018  1049 W DisplayManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-24 14:31:04.106  1018  1049 W DisplayManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-24 14:31:04.116  7096  7096 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-24 14:31:04.116  7096  7096 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-24 14:31:04.116  7061  7061 E CscParser: mps_code.dat does not exist
08-24 14:31:04.116  7061  7061 E CscParser: customer_path =/system/csc/customer.xml
08-24 14:31:04.116  7061  7061 E CscParser: fileName + /system/csc/customer.xml
08-24 14:31:04.126  1938  7029 I qtaguid : Untagging socket 97
08-24 14:31:04.126  1018  1489 D PersonaManager: isKioskContainerExistOnDevice
08-24 14:31:04.126  7061  7061 D CscParser: getInstance fileName =/system/csc/customer.xml
08-24 14:31:04.146  1938  1938 I ConfigFetchService: fetch service done; releasing wakelock
08-24 14:31:04.146  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-24 14:31:04.156  1938  1938 I ConfigFetchService: stopping self
08-24 14:31:04.166  1938  7035 W BaseAppContext: Using Auth Proxy for data requests.
08-24 14:31:04.186  1938  7035 W BaseAppContext: Using Auth Proxy for data requests.
08-24 14:31:04.186  7096  7096 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-24 14:31:04.196  7061  7061 D Mms/MmsConfig:  enable multiwindow = false
08-24 14:31:04.196  7096  7096 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-24 14:31:04.196  7179  7179 W ResourcesManager: Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
08-24 14:31:04.196   258  1099 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
08-24 14:31:04.196   258  1890 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
08-24 14:31:04.206  7124  7124 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-24 14:31:04.206  1493  1493 V ActivityThread: updateVisibility : ActivityRecord{1b4461a2 token=android.os.BinderProxy@22414b1b {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-24 14:31:04.206  1493  1493 D Launcher: onTrimMemory. Level: 20
,08-24 14:31:04.206  7061  7061 E Mms/MessageUtils: setCountryDetector : update country detector info 
08-24 14:31:04.206  7061  7061 E Mms/MessageUtils: updateCountryIso : update country iso info 
,08-24 14:31:04.226  7061  7061 D Mms/MmsConfig: [end]    init() consume time = 277.462395
,08-24 14:31:04.226  7061  7061 D Mms/Contact: [start]    init() consume time = 1.454271
,08-24 14:31:04.236  7096  7096 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 14:31:04.236  1938  7035 W BaseAppContext: Using Auth Proxy for data requests.
,08-24 14:31:04.236  7096  7096 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 14:31:04.236  7096  7096 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 14:31:04.236  7096  7096 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 14:31:04.236  7096  7096 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 14:31:04.236  7096  7096 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 14:31:04.236  7096  7096 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 14:31:04.246  7096  7096 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 14:31:04.246  7096  7096 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 14:31:04.246  7096  7096 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 14:31:04.246  7096  7096 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 14:31:04.256  7096  7096 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 14:31:04.256  7096  7096 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-24 14:31:04.276  1466  1898 D TP/MmsSmsProvider: query,matched:13, calling pid = 7061
,08-24 14:31:04.276  1466  1898 D TP/MmsSmsProvider: match 13:Elapsed time : 2.880 ms
,08-24 14:31:04.286  1018  1044 W ProcessCpuTracker: Skipping unknown process pid 7124
,08-24 14:31:04.306  7096  7096 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-24 14:31:04.306  7061  7061 D Mms/Contact: [end]    init consume time = 81.706094
,08-24 14:31:04.326  1018  1217 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,08-24 14:31:04.326  1018  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:04.326  1018  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:04.326  1018  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:04.326  1018  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:04.336  7061  7209 D Mms/DraftCache: [start]    rebuildCache consume time = 22.904063,
08-24 14:31:04.336  7096  7096 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-24 14:31:04.336  1466  1490 D TP/MmsSmsProvider: query,matched:12, calling pid = 7061
,08-24 14:31:04.336  1466  1490 D TP/MmsSmsProvider: match 12:Elapsed time : 5.199 ms
,08-24 14:31:04.346  7210  7210 E Zygote  : MountEmulatedStorage()
08-24 14:31:04.346  7210  7210 E Zygote  : v2
08-24 14:31:04.346  7210  7210 I libpersona: KNOX_SDCARD checking this for 10152
08-24 14:31:04.346  7210  7210 I libpersona: KNOX_SDCARD not a persona
08-24 14:31:04.346  7210  7210 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 14:31:04.346  7210  7210 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 14:31:04.356  1018  1217 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7210 uid=10152 gids={50152, 9997} abi=armeabi-v7a
,08-24 14:31:04.356  1018  1217 I ActivityManager: Killing 6731:com.samsung.android.securitylogagent/1000 (adj 15): empty #21
,08-24 14:31:04.356  7210  7210 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 14:31:04.356  7061  7209 D Mms/DraftCache: [end]    rebuildCache consume time = 28.418489
,08-24 14:31:04.366  7061  7061 D Mms/MethodReflector: getSubId is called
08-24 14:31:04.366  7061  7061 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,08-24 14:31:04.366  7061  7061 D Mms/MethodReflector: getTelephonyProperty is called
08-24 14:31:04.366  7061  7061 D Mms/DownloadManager: roaming -> false (slotId = 0)
08-24 14:31:04.366  7061  7061 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-24 14:31:04.366  7061  7061 D Mms/DownloadManager: auto download without roaming -> true
08-24 14:31:04.366  7061  7061 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
08-24 14:31:04.366  7061  7061 D Mms/MethodReflector: getSubId is called
,08-24 14:31:04.376  7061  7061 D Mms/MethodReflector: getDefaultSmsSubId is called
08-24 14:31:04.376  7061  7061 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
08-24 14:31:04.376  7061  7061 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
08-24 14:31:04.376  7061  7061 D Mms/MethodReflector: getTelephonyProperty is called
08-24 14:31:04.376  7061  7061 D Mms/DownloadManager: roaming -> false (slotId = 1)
08-24 14:31:04.376  7061  7061 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
08-24 14:31:04.376  7061  7061 D Mms/DownloadManager: auto download without roaming -> true
08-24 14:31:04.376  7061  7061 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
08-24 14:31:04.376  7061  7061 D Mms/DownloadManager: auto download during roaming secondary -> false
08-24 14:31:04.376  7061  7061 D Mms/DownloadManager: mAutoDownload ------> true
,08-24 14:31:04.396  7162  7162 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-24 14:31:04.406  7210  7210 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:31:04.406  7210  7210 D ActivityThread: Added TimaKeyStore provider
,08-24 14:31:04.406  7096  7096 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 14:31:04.416  7096  7096 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 14:31:04.416  7096  7096 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-24 14:31:04.436  7162  7162 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 6754-6756)
,08-24 14:31:04.436  7162  7162 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-24 14:31:04.476  7210  7210 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
,08-24 14:31:04.476  7210  7210 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
08-24 14:31:04.476  7061  7061 D ComposerPerformance: 1472041864489 ms / [DONE] Composer constructor
08-24 14:31:04.476  7061  7061 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
08-24 14:31:04.476  7061  7061 I Mms/ReservationManager: ReservationManager()
08-24 14:31:04.476  7061  7061 I Mms/ReservationManager: resetAfterConnected()
08-24 14:31:04.486  7011  7054 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
08-24 14:31:04.486  7011  7054 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-24 14:31:04.486  7011  7054 I GAv4    :   adb logcat -s GAv4
,08-24 14:31:04.486  7061  7229 D Mms/Conversation: [start]    init() consume time = 125.650469,
,08-24 14:31:04.486  1018  1508 I ActivityManager: Killing 6550:com.android.defcontainer/u0a3 (adj 15): empty #21
,08-24 14:31:04.496  7162  7162 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {abca706}
,08-24 14:31:04.506  7210  7210 I TapandpayWidget:Utils: Clear T&P info.
,08-24 14:31:04.506  7162  7162 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-24 14:31:04.506  7162  7162 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-24 14:31:04.506  1466  1490 D TP/MmsSmsProvider: query,matched:7, calling pid = 7061
,08-24 14:31:04.516  1466  1490 D TP/MmsSmsProvider: match 7:Elapsed time : 3.401 ms
,08-24 14:31:04.516  1466  7004 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
,08-24 14:31:04.516  1466  7004 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
,08-24 14:31:04.516  1466  7004 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,08-24 14:31:04.516  1466  7004 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
,08-24 14:31:04.526  7061  7061 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,08-24 14:31:04.526  7061  7061 D Mms/MmsApp: [end]    onCreate() consume time = 40.208906
,08-24 14:31:04.526  1466  7004 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
,08-24 14:31:04.526  1466  7004 D TP/MmsSmsProvider: need read changed broadcast:false
,08-24 14:31:04.536  7061  7229 D Mms/Conversation: [end]    init consume time = 6.205313
,08-24 14:31:04.536  7061  7229 D Mms/MessagingNotification: [start]    init() consume time = 3.393281
,08-24 14:31:04.546  7061  7061 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=760]
,08-24 14:31:04.546  7061  7061 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
,08-24 14:31:04.556  7061  7061 D Mms/MethodReflector: getSubId is called
08-24 14:31:04.556  7061  7061 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,08-24 14:31:04.556  7061  7061 D Mms/MethodReflector: getTelephonyProperty is called
08-24 14:31:04.556  7061  7061 D Mms/DownloadManager: roaming -> false (slotId = 0)
08-24 14:31:04.556  7061  7061 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-24 14:31:04.556  7061  7061 D Mms/DownloadManager: auto download without roaming -> true
08-24 14:31:04.556  7061  7061 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
08-24 14:31:04.556  7061  7061 D Mms/DownloadManager: mAutoDownload ------> true
,08-24 14:31:04.556  7061  7229 D Mms/MessagingNotification: [end]    init consume time = 20.584948
,08-24 14:31:04.566  1466  1490 D TP/MmsSmsProvider: query,matched:0, calling pid = 7061
,08-24 14:31:04.566  1466  1490 V TP/MmsSmsProvider: getSimpleConversations entered.
,08-24 14:31:04.566  7061  7233 D Mms/Synchronizer: [start]    doSync consume time = 8.834896
,08-24 14:31:04.566  7162  7162 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-24 14:31:04.576  1466  1490 D TP/MmsSmsProvider: match 0:Elapsed time : 9.566 ms
,08-24 14:31:04.576  7061  7061 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_ADDED
,08-24 14:31:04.576  1466  1898 D TP/MmsSmsProvider: update, matched:300, calling pid = 7061
,08-24 14:31:04.576  7162  7162 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-24 14:31:04.576  1466  1898 V TP/MmsSmsProvider: syncDBData start
,08-24 14:31:04.576  7061  7232 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 9.567916
08-24 14:31:04.576  7210  7210 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
,08-24 14:31:04.576  1466  1898 V TP/MmsSmsProvider: syncDBData sms end
,08-24 14:31:04.576  1466  1898 V TP/MmsSmsProvider: syncDBData mms end
,08-24 14:31:04.576  1018  1449 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
08-24 14:31:04.576  1466  1898 V TP/MmsSmsProvider: syncDBData end
,08-24 14:31:04.576  1018  1449 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
,08-24 14:31:04.586  1018  1449 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:04.586  7061  7233 D Mms/Synchronizer: [end]    doSync consume time = 6.62125
,08-24 14:31:04.586  1018  1449 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:04.586  1018  1449 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,08-24 14:31:04.586  7162  7162 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-24 14:31:04.586  1018  1492 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,08-24 14:31:04.586  1018  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:04.586  1018  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:04.586  1018  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:04.586  1018  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:04.596  7238  7238 E Zygote  : MountEmulatedStorage(),
08-24 14:31:04.596  7238  7238 E Zygote  : v2
08-24 14:31:04.606  7238  7238 I libpersona: KNOX_SDCARD checking this for 10009
08-24 14:31:04.606  7238  7238 I libpersona: KNOX_SDCARD not a persona
,08-24 14:31:04.606  7238  7238 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 14:31:04.606  1018  1492 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=7238 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
08-24 14:31:04.606  1018  1492 I ActivityManager: Killing 6743:com.android.providers.calendar/u0a37 (adj 15): empty #21
,08-24 14:31:04.606  7238  7238 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 14:31:04.606  1018  1492 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
,08-24 14:31:04.616  1018  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:04.616  1018  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:04.616  1018  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:04.616  1018  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:04.616  7011  7054 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
08-24 14:31:04.616  1018  1137 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-24 14:31:04.616  7162  7162 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-24 14:31:04.616  7162  7162 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-24 14:31:04.616  7162  7162 I Adreno-EGL: Build Date: 04/06/15 Mon
08-24 14:31:04.616  7162  7162 I Adreno-EGL: Local Branch: 
08-24 14:31:04.616  7162  7162 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-24 14:31:04.616  7162  7162 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-24 14:31:04.616  7162  7162 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
08-24 14:31:04.616  7096  7096 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-24 14:31:04.626  7238  7238 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-24 14:31:04.636  7250  7250 E Zygote  : MountEmulatedStorage()
08-24 14:31:04.636  7250  7250 I libpersona: KNOX_SDCARD checking this for 10042
08-24 14:31:04.636  7250  7250 E Zygote  : v2
08-24 14:31:04.636  7250  7250 I libpersona: KNOX_SDCARD not a persona
08-24 14:31:04.636  7250  7250 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 14:31:04.646  1018  1492 I ActivityManager: Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=7250 uid=10042 gids={50042, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
,08-24 14:31:04.646  7250  7250 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 14:31:04.646  7250  7250 E SELinux : [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
,08-24 14:31:04.646  7096  7237 D Ads     : Skipping gmscore version check
08-24 14:31:04.646  1018  1044 W ActivityManager: Activity pause timeout for ActivityRecord{3abb9e4c u0 com.test.thalitest/.MainActivity t163}
08-24 14:31:04.646  1018  1031 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
08-24 14:31:04.646  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,08-24 14:31:04.666  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:04.666  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:04.666  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,08-24 14:31:04.676  7238  7238 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:31:04.676  7238  7238 D ActivityThread: Added TimaKeyStore provider
,08-24 14:31:04.676  1018  3813 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
,08-24 14:31:04.686  7061  7235 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_ADDED
08-24 14:31:04.686  7061  7235 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_ADDED
,08-24 14:31:04.686  1018  3813 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:04.686  1018  3813 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:04.686  1018  3813 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:04.686  1018  3813 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:04.686  7250  7250 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:31:04.686  1466  1488 D TP/MmsSmsProvider: query,matched:400, calling pid = 7061
,08-24 14:31:04.686  7250  7250 D ActivityThread: Added TimaKeyStore provider
,08-24 14:31:04.706  7280  7280 E Zygote  : MountEmulatedStorage(),
08-24 14:31:04.706  7280  7280 I libpersona: KNOX_SDCARD checking this for 10068
08-24 14:31:04.706  7280  7280 E Zygote  : v2
08-24 14:31:04.706  7280  7280 I libpersona: KNOX_SDCARD not a persona
08-24 14:31:04.706  7280  7280 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 14:31:04.706  7280  7280 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-24 14:31:04.706  7280  7280 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-24 14:31:04.706  1018  3813 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7280 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,08-24 14:31:04.726  1018  3812 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 14:31:04.726  1018  3812 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:04.726  1018  3812 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:04.726  1018  3812 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,08-24 14:31:04.736  7011  7054 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-24 14:31:04.746  7096  7096 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-24 14:31:04.746  7162  7162 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-24 14:31:04.746  1018  1491 I ActivityManager: Killing 6769:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,08-24 14:31:04.746  7061  7232 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 166.546146
,08-24 14:31:04.756  7280  7280 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:31:04.756  7280  7280 D ActivityThread: Added TimaKeyStore provider
,08-24 14:31:04.766  1018  1449 I ActivityManager: Killing 6787:com.qualcomm.timeservice/1000 (adj 15): empty #21
,08-24 14:31:04.766  7250  7250 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-24 14:31:04.766  7250  7250 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-24 14:31:04.766  7250  7250 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-24 14:31:04.776  7162  7162 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-24 14:31:04.776  7162  7162 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-24 14:31:04.786  7162  7162 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-24 14:31:04.786  7162  7162 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-24 14:31:04.796  1938  7035 W art     : Verification of void com.google.android.gms.games.broker.GameAgent.addGameBadgeOps(com.google.android.gms.common.internal.ClientContext, com.google.android.gms.games.server.api.MarketInstance, java.lang.String, java.util.ArrayList, int) took 174.849ms
,08-24 14:31:04.806  7061  7134 W art     : Verification of void com.android.mms.util.HandleComposerAttachment.processingActivityResult(int, int, android.content.Intent) took 213.567ms
,08-24 14:31:04.816  7096  7096 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 14:31:04.826  7280  7280 D BadgeProvider: onCreate
,08-24 14:31:04.826  7280  7280 D BadgeProvider: DatabaseHelper
,08-24 14:31:04.836  7011  7054 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.357.23.33
,08-24 14:31:04.846  7061  7229 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,08-24 14:31:04.856  7061  7134 D Mms/ArtClassLoader: init [DONE] art
,08-24 14:31:04.856  1466  1490 D TP/SmsProvider: query,matched:26, calling pid = 7061
,08-24 14:31:04.856  1466  1490 D TP/SmsProvider: match 26:Elapsed time : 1.853 ms
,08-24 14:31:04.866  7011  7300 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-24 14:31:04.866  1466  7004 D TP/MmsSmsProvider: query,matched:6, calling pid = 7061
,08-24 14:31:04.876  1466  7004 D TP/MmsSmsProvider: match 6:Elapsed time : 1.393 ms
,08-24 14:31:04.886  1018  1449 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,08-24 14:31:04.886  1018  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:04.886  1018  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:04.886  1018  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:04.886  1018  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:04.886   272   272 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb743b7c8
08-24 14:31:04.886   272   272 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
08-24 14:31:04.886   272   272 I rmt_storage: wakelock acquired: 1, error no: 42
08-24 14:31:04.896   272   371 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1220298616)
,08-24 14:31:04.906  7301  7301 E Zygote  : MountEmulatedStorage(),
08-24 14:31:04.906  7301  7301 E Zygote  : v2
08-24 14:31:04.906  7301  7301 I libpersona: KNOX_SDCARD checking this for 10023
08-24 14:31:04.906  7301  7301 I libpersona: KNOX_SDCARD not a persona
,08-24 14:31:04.906  7301  7301 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 14:31:04.906  7301  7301 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-24 14:31:04.906  7301  7301 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 14:31:04.916  1018  1449 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=7301 uid=10023 gids={50023, 9997} abi=armeabi-v7a,
,08-24 14:31:04.936  7301  7301 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:31:04.936  7301  7301 D ActivityThread: Added TimaKeyStore provider
,08-24 14:31:04.946  1018  1137 I ActivityManager: Killing 6807:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
,08-24 14:31:04.956   272   371 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
08-24 14:31:04.956   272   371 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
08-24 14:31:04.956   272   371 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1220298616) wakelock released: 1, error no: 0
08-24 14:31:04.956   272   371 I rmt_storage: 
,08-24 14:31:04.966   272   272 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb743b7c8
,08-24 14:31:04.966  1018  3813 I ActivityManager: Killing 6816:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
08-24 14:31:04.976  1938  4349 I Icing   : Indexing D0AE1F45F393341DA3213A207506F1C2E721F1A9 from com.google.android.googlequicksearchbox
,08-24 14:31:05.016  7301  7301 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,08-24 14:31:05.026  7250  7250 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,08-24 14:31:05.026  1938  4349 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,08-24 14:31:05.026  1018  1058 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
08-24 14:31:05.026  1018  1058 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-24 14:31:05.046  1018  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:05.046  1018  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:05.046  1018  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:05.046  1018  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:05.056  7061  7229 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,08-24 14:31:05.066  7301  7301 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
08-24 14:31:05.066  7301  7301 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
08-24 14:31:05.066  7301  7301 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,08-24 14:31:05.066  7320  7320 E Zygote  : MountEmulatedStorage()
08-24 14:31:05.066  7320  7320 E Zygote  : v2
08-24 14:31:05.066  7320  7320 I libpersona: KNOX_SDCARD checking this for 10003
08-24 14:31:05.066  7301  7301 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
08-24 14:31:05.066  7320  7320 I libpersona: KNOX_SDCARD not a persona
,08-24 14:31:05.066  7301  7301 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,08-24 14:31:05.066  1018  1058 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7320 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-24 14:31:05.066  7320  7320 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 14:31:05.066  7301  7301 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,08-24 14:31:05.076  7301  7301 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,08-24 14:31:05.076  7301  7301 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,08-24 14:31:05.076  7320  7320 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 14:31:05.076  7301  7301 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,08-24 14:31:05.076  7320  7320 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-24 14:31:05.076  7301  7301 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,08-24 14:31:05.076  7301  7301 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,08-24 14:31:05.076  7301  7301 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
08-24 14:31:05.076  7301  7301 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,08-24 14:31:05.116  7320  7320 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:31:05.116  7320  7320 D ActivityThread: Added TimaKeyStore provider
08-24 14:31:05.136  7162  7162 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-24 14:31:05.146   284   284 E installd: system dir 0 : /system/app/
08-24 14:31:05.146   284   284 E installd: system dir 1 : /system/priv-app/
08-24 14:31:05.146   284   284 E installd: system dir 2 : /vendor/app/
08-24 14:31:05.146   284   284 E installd: system dir 3 : /oem/app/
08-24 14:31:05.166  7162  7162 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-24 14:31:05.176  1018  1449 I ActivityManager: Killing 6835:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
08-24 14:31:05.186  1938  4349 I Icing   : Indexing done D0AE1F45F393341DA3213A207506F1C2E721F1A9
08-24 14:31:05.186  7162  7162 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-24 14:31:05.196  7162  7162 D PhoneWindow: *FMB* installDecor flags : -2139027200
08-24 14:31:05.196  7162  7162 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
08-24 14:31:05.206  1018  1449 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.filterinstaller, hostingType: broadcast
08-24 14:31:05.206  1018  1058 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
08-24 14:31:05.206  1018  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:05.206  1018  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:05.206  1018  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:05.206  1018  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:05.226  7344  7344 E Zygote  : MountEmulatedStorage()
08-24 14:31:05.226  7344  7344 I libpersona: KNOX_SDCARD checking this for 1000
08-24 14:31:05.226  7344  7344 E Zygote  : v2
08-24 14:31:05.226  7344  7344 I libpersona: KNOX_SDCARD not a persona
08-24 14:31:05.226  7344  7344 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 14:31:05.226  1018  1449 I ActivityManager: Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=7344 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-24 14:31:05.226  7344  7344 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 14:31:05.226  1018  1449 I ActivityManager: Killing 6856:com.sec.spp.push/u0a32 (adj 15): empty #21
08-24 14:31:05.226  7344  7344 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-24 14:31:05.226  1018  1439 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-24 14:31:05.226  1018  1439 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:05.236  1018  1439 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:05.236  1018  1439 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-24 14:31:05.236  7162  7162 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-24 14:31:05.236  7162  7162 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-24 14:31:05.256  7344  7344 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:31:05.256  7344  7344 D ActivityThread: Added TimaKeyStore provider
08-24 14:31:05.286  7344  7344 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
08-24 14:31:05.286  7344  7344 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
08-24 14:31:05.286  1018  1441 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
08-24 14:31:05.286  1018  1441 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
08-24 14:31:05.286  1018  1441 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:05.286  1018  1441 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:05.286  1018  1441 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
08-24 14:31:05.296  1018  1031 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
08-24 14:31:05.296  1018  1044 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
08-24 14:31:05.296  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:05.296  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:05.296  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:05.296  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:05.306  7344  7344 I FilterInstaller: FilterPackageService : ACTION_CHANGED
08-24 14:31:05.316  7365  7365 E Zygote  : MountEmulatedStorage()
08-24 14:31:05.316  7365  7365 E Zygote  : v2
08-24 14:31:05.316  7365  7365 I libpersona: KNOX_SDCARD checking this for 10130
08-24 14:31:05.316  7365  7365 I libpersona: KNOX_SDCARD not a persona
08-24 14:31:05.316  7365  7365 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 14:31:05.316  7365  7365 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 14:31:05.316  1018  1044 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=7365 uid=10130 gids={50130, 9997} abi=armeabi-v7a
08-24 14:31:05.316  7365  7365 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
08-24 14:31:05.326  7344  7363 E FilterInstaller: installFilters
08-24 14:31:05.326  7011  7341 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-24 14:31:05.326  7011  7341 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-24 14:31:05.336   305   305 I art     : Explicit concurrent mark sweep GC freed 8688(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 608us total 24.808ms
08-24 14:31:05.356  7162  7378 D OpenGLRenderer: Render dirty regions requested: true
08-24 14:31:05.356  1018  1031 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-24 14:31:05.356  1018  1031 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-24 14:31:05.356  1018  1031 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-24 14:31:05.356  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-24 14:31:05.356  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
08-24 14:31:05.356   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 787us total 18.009ms
08-24 14:31:05.366  7365  7365 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:31:05.366  7365  7365 D ActivityThread: Added TimaKeyStore provider
08-24 14:31:05.366  7162  7162 V ActivityThread: updateVisibility : ActivityRecord{1b4410c1 token=android.os.BinderProxy@341021cb {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-24 14:31:05.366  7162  7277 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
08-24 14:31:05.376   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 778us total 18.195ms
08-24 14:31:05.386  7162  7162 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-24 14:31:05.386  7162  7162 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-24 14:31:05.386  7344  7363 E FilterInstaller: There is no requred permission
08-24 14:31:05.396  1018  1489 I ActivityManager: Killing 6865:com.samsung.helphub/1000 (adj 15): empty #21
08-24 14:31:05.406   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
08-24 14:31:05.406  7011  7341 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
08-24 14:31:05.406  7365  7365 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-24 14:31:05.406  7365  7365 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
08-24 14:31:05.416  1018  1492 D InputDispatcher: Focus entered window: 7162
08-24 14:31:05.416  1018  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-24 14:31:05.416  1018  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
08-24 14:31:05.416  7162  7162 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-24 14:31:05.416  7162  7378 I OpenGLRenderer: Initialized EGL, version 1.4
08-24 14:31:05.426  1018  1489 D ActivityManager: startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
08-24 14:31:05.426  7162  7378 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-24 14:31:05.426  7162  7378 D OpenGLRenderer: Enabling debug mode 0
08-24 14:31:05.426  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:05.426  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:05.426  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:05.426  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:05.436  7385  7385 E Zygote  : MountEmulatedStorage()
08-24 14:31:05.436  7385  7385 E Zygote  : v2
08-24 14:31:05.436  7385  7385 I libpersona: KNOX_SDCARD checking this for 10131
08-24 14:31:05.436  7385  7385 I libpersona: KNOX_SDCARD not a persona
08-24 14:31:05.446  7385  7385 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 14:31:05.446  7385  7385 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 14:31:05.446  7385  7385 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-24 14:31:05.446  1018  1489 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=7385 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
08-24 14:31:05.456  1018  1489 I ActivityManager: Killing 5115:com.google.android.gms.wearable/u0a11 (adj 15): empty #21
08-24 14:31:05.456  1018  1489 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-24 14:31:05.466  1179  1179 D PanelView: There is/are notification(s) 
08-24 14:31:05.466  1018  7393 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-24 14:31:05.486  1018  1049 I ActivityManager: Displayed Component not be shown by security: +1s349ms (total +1s508ms)
08-24 14:31:05.486  1018  1049 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3abb9e4c u0 com.test.thalitest/.MainActivity t163} time:97802
08-24 14:31:05.486  1018  1049 W ActivityManager: mDVFSHelper.release()
08-24 14:31:05.486  7011  7341 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-24 14:31:05.486   258   441 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
08-24 14:31:05.486  7011  7341 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2b74baac: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-24 14:31:05.486  7011  7341 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
08-24 14:31:05.496   258  1890 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
08-24 14:31:05.496  7162  7162 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-24 14:31:05.496  7162  7162 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@341021cb time:97815
08-24 14:31:05.496  7385  7385 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:31:05.506  7385  7385 D ActivityThread: Added TimaKeyStore provider
08-24 14:31:05.516  7385  7385 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-24 14:31:05.516  7385  7385 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 14:31:05.516  7385  7385 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-24 14:31:05.556  2634  5298 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
08-24 14:31:05.556  1018  1030 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
08-24 14:31:05.556  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
08-24 14:31:05.556  1874  1874 I SamsungIME: getCurrentCandidateView
08-24 14:31:05.566  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:05.566  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:05.566  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
08-24 14:31:05.576  1018  1489 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
08-24 14:31:05.576  1018  1489 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
08-24 14:31:05.576  1018  1489 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:05.576  1018  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:05.576  1018  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
08-24 14:31:05.586  1018  1492 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:05.586  1018  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:05.586  1018  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-24 14:31:05.596  1018  1439 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-24 14:31:05.596  1018  1439 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:05.596  1018  1439 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
08-24 14:31:05.596  1018  1439 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:05.596  1018  1439 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-24 14:31:05.606  1018  1217 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
08-24 14:31:05.606  2653  5112 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-24 14:31:05.606  1018  1217 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
08-24 14:31:05.606  1018  1217 I splitIntent: other index=5, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
08-24 14:31:05.606  1018  1217 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
08-24 14:31:05.606  1018  1217 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:05.606  1018  1217 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:05.606  1018  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-24 14:31:05.606  1018  1489 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:05.616  1018  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:05.616  1018  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-24 14:31:05.616  2653  2653 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-24 14:31:05.616  1018  1492 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:05.616  1018  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:05.616  1018  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-24 14:31:05.626  1018  1439 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-24 14:31:05.626  1018  1439 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
08-24 14:31:05.626  1018  1439 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:05.626  1018  1439 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:05.626  1018  1439 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-24 14:31:05.636  7162  7162 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7162
08-24 14:31:05.636  2653  2653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-24 14:31:05.636  1018  1492 I ActivityManager: Killing 6891:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
08-24 14:31:05.636  2653  2653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-24 14:31:05.646  1018  1492 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:05.646  1018  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:05.646  1018  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-24 14:31:05.646  1018  1217 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:05.646  1018  1217 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:05.646  1018  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-24 14:31:05.646  1938  1938 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
08-24 14:31:05.646  1018  1137 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-24 14:31:05.646  1018  1137 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
08-24 14:31:05.656  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:05.656  1018  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:05.656  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-24 14:31:05.656  1018  1489 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:05.656  1018  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:05.656  1018  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-24 14:31:05.656  1018  1441 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:05.656  1018  1441 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:05.656  1018  1441 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-24 14:31:05.666  1018  1508 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:05.666  1018  1508 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:05.666  1018  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-24 14:31:05.676  1018  1491 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-24 14:31:05.676  1018  1491 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:05.676  1018  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:05.676  1018  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-24 14:31:05.676  1018  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:05.676  1018  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:05.676  1018  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:05.676  1018  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:05.686   288   288 E SMD     : DCD OFF
08-24 14:31:05.696  7413  7413 E Zygote  : MountEmulatedStorage()
08-24 14:31:05.696  7413  7413 I libpersona: KNOX_SDCARD checking this for 10011
08-24 14:31:05.696  7413  7413 E Zygote  : v2
08-24 14:31:05.696  7413  7413 I libpersona: KNOX_SDCARD not a persona
08-24 14:31:05.696  7413  7413 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 14:31:05.696  7413  7413 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 14:31:05.696  7413  7413 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-24 14:31:05.696  1018  1491 I ActivityManager: Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=7413 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
08-24 14:31:05.706  1018  3813 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:05.706  1018  3813 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:05.706  1018  3813 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-24 14:31:05.706  1874  1874 D SamsungIME: Dismiss ExpandCandiate
08-24 14:31:05.716  1018  1489 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:05.716  1018  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:05.716  1018  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-24 14:31:05.716  7413  7413 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:31:05.716  7413  7413 D ActivityThread: Added TimaKeyStore provider
08-24 14:31:05.726  6910  6959 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
08-24 14:31:05.736  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:05.736  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:05.736  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-24 14:31:05.746  7413  7413 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-24 14:31:05.746  6910  6959 I AcmsKeyStoreHelper: Key Store exist
08-24 14:31:05.746  6910  6959 I AcmsKeyStoreHelper: Hence loading the keystore file
08-24 14:31:05.746  7413  7413 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-24 14:31:05.756  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:05.756  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:05.756  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-24 14:31:05.756  1018  1449 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-24 14:31:05.766  1018  1449 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:05.766  1018  1449 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:05.766  1018  1449 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-24 14:31:05.776  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:05.776  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:05.776  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-24 14:31:05.786  7413  7413 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
08-24 14:31:05.786  7413  7413 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
08-24 14:31:05.796  1018  3812 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-24 14:31:05.796  1018  3812 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
08-24 14:31:05.796  7413  7413 I MultiDex: VM with version 2.1.0 has multidex support
08-24 14:31:05.796  7413  7413 I MultiDex: install
08-24 14:31:05.796  7413  7413 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-24 14:31:05.796  1018  3812 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:05.796  1018  3812 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:05.796  1018  3812 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:05.796  1938  7430 D LocationInitializer: Restart initialization of location
08-24 14:31:05.796  1018  1508 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-24 14:31:05.796  1018  1508 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
08-24 14:31:05.806  1018  1508 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:05.806  1018  1508 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:05.806  1018  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:05.816  1018  1217 I ActivityManager: Killing 6923:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
,08-24 14:31:05.826  7413  7413 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-24 14:31:05.836  1018  1492 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 14:31:05.836  1018  1492 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:05.836  1018  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-24 14:31:05.836  1018  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-24 14:31:05.836  6910  6959 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
,08-24 14:31:05.846  6910  6959 I AcmsCertificateMngr: getKeyStoreForApplication success 
08-24 14:31:05.846  6910  6959 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
08-24 14:31:05.846  6910  6959 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-24 14:31:05.846  6910  6959 D AcmsServiceMonitor: Decrementing - Counter value: 1
08-24 14:31:05.846  6910  6959 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
,08-24 14:31:05.856  6910  6959 D AcmsCore: This is NOT a valid MirrorLink app
08-24 14:31:05.856  6910  6959 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
08-24 14:31:05.856  6910  6959 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-24 14:31:05.856  6910  6959 D AcmsServiceMonitor: Decrementing - Counter value: 0
08-24 14:31:05.856  6910  6959 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
,08-24 14:31:05.856  6910  6910 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
08-24 14:31:05.856  6910  6910 D AcmsService: Enter onDestroy
08-24 14:31:05.856  6910  6910 I AcmsService: cleanUp(): inside service clean up
08-24 14:31:05.856  6910  6910 D AcmsCore: AcmsCore: inside DeInit
08-24 14:31:05.856  6910  6910 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
08-24 14:31:05.856  6910  6910 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
08-24 14:31:05.856  6910  6910 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
08-24 14:31:05.856  6910  6910 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
08-24 14:31:05.856  6910  6910 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
,08-24 14:31:05.866  6910  6910 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
08-24 14:31:05.866  6910  6910 D AcmsService: killing acms process
08-24 14:31:05.866  6910  6910 I Process : Sending signal. PID: 6910 SIG: 9
,08-24 14:31:05.876  7162  7162 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-24 14:31:05.906  7413  7413 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-24 14:31:05.906  7413  7413 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@175f66a2: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-24 14:31:05.906  7413  7413 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-24 14:31:05.916  1018  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:05.916  1018  1044 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-24 14:31:05.916  1018  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:05.916  1018  1217 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-24 14:31:05.916  1018  1217 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-24 14:31:05.916  1018  1217 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:05.916  1018  1217 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-24 14:31:05.926  1018  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:05.926  1018  1030 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,08-24 14:31:05.926  1018  1030 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
,08-24 14:31:05.926  1018  1030 I splitIntent: other index=5, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
08-24 14:31:05.926  1018  1030 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,08-24 14:31:05.926  2653  5171 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-24 14:31:05.926  1874  1874 I SamsungIME: getDebugLevel  : 0x4f4c
,08-24 14:31:05.926  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:05.926  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:05.926  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:05.936  1018  1441 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:05.936  1018  1441 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:05.936  1018  1441 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:05.936  2653  2653 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-24 14:31:05.936  7413  7413 D WearableService: callingUid 10011, callindPid: 7413
,08-24 14:31:05.946  1018  1489 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:05.946  1018  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:05.946  1018  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:05.946  1018  1030 I ActivityManager: Process ACMS.Process (pid 6910)(adj 0) has died(36,759)
,08-24 14:31:05.956  1018  3812 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-24 14:31:05.956  1018  3812 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,08-24 14:31:05.956  1018  3812 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:05.956  1018  3812 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:05.956  1018  3812 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:05.966  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:05.966  1018  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:05.966  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:05.966  7413  7434 D NativeLibraryUtils: Install completed successfully. count=0 extracted=0
,08-24 14:31:05.966  2653  2653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 14:31:05.976  1018  1441 W ActivityManager: userId = 0, bbcId = -10000,
08-24 14:31:05.976  1018  1441 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:05.976  1018  1441 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,08-24 14:31:05.976  1938  1938 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,08-24 14:31:05.976  1018  1217 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-24 14:31:05.976  1018  1217 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,08-24 14:31:05.976  1018  1217 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:05.976  1018  1217 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:05.976  1018  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:05.976  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:05.976  1018  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-24 14:31:05.976  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:05.986  1018  1439 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:05.986  1018  1439 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:05.986  1018  1439 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:05.986  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:05.986  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:05.986  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:05.996  7162  7402 D jxcore_app_log: JniHelper::setJavaVM(0xb8db32b0), pthread_self() = -1187780192
,08-24 14:31:05.996  7162  7402 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-24 14:31:05.996  7162  7402 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-24 14:31:05.996  7162  7402 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-24 14:31:05.996  7162  7402 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-24 14:31:05.996  7162  7402 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-24 14:31:05.996  7162  7402 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@323541ec added. We now have 1 listener(s)
,08-24 14:31:06.006  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:06.006  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-24 14:31:06.006  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:06.006  7162  7402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
,08-24 14:31:06.006  7162  7402 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-24 14:31:06.016  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:06.016  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:06.016  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:06.016  7162  7402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 14:31:06.016  7162  7402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 14:31:06.016  1874  1874 I SamsungIME: getDebugLevel  : 0x4f4c
,08-24 14:31:06.016  7162  7402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-24 14:31:06.016  7162  7402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-24 14:31:06.016  7162  7402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-24 14:31:06.016  7162  7402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
08-24 14:31:06.016  7162  7402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-24 14:31:06.016  7162  7402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-24 14:31:06.016  7162  7402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-24 14:31:06.016  7162  7402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-24 14:31:06.016  7162  7402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-24 14:31:06.016  7162  7402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-24 14:31:06.016  7162  7402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-24 14:31:06.016  7162  7402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-24 14:31:06.016  7162  7402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-24 14:31:06.016  7162  7402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-24 14:31:06.016  7162  7402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@335113bb added. We now have 1 listener(s)
,08-24 14:31:06.016  7162  7402 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 14:31:06.026  1874  1874 I SamsungIME: KeybaordView init() : load resources
08-24 14:31:06.026  7162  7402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 14:31:06.026  7162  7402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-24 14:31:06.026  7162  7402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-24 14:31:06.026  7162  7402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-24 14:31:06.026  7162  7402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-24 14:31:06.036  1018  1439 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:06.036  1018  1439 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:06.036  1018  1439 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-24 14:31:06.036  7162  7402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 14:31:06.046  7162  7402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
08-24 14:31:06.046  1018  1439 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:06.046  1018  1439 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:06.046  1018  1439 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:06.056  7162  7402 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-24 14:31:06.056  7162  7402 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:31:06.056  7162  7402 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:06.056  7162  7402 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:31:06.056  7162  7402 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:31:06.056  7162  7402 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:31:06.056  7162  7402 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 14:31:06.056  7162  7402 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 14:31:06.056  7162  7402 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 14:31:06.056  7162  7402 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-24 14:31:06.056  7162  7402 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 14:31:06.056  7162  7402 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-24 14:31:06.056  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:31:06.056  1874  1874 I SamsungIME: getCurrentKeyboard
08-24 14:31:06.056  1874  1874 I SamsungIME: getTextKeyboard
,08-24 14:31:06.056  1018  1492 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 14:31:06.056  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:06.076  1018  1492 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:06.076  1018  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:06.076  1018  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:06.076  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:06.076  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:06.076  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:06.076  1018  1449 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-24 14:31:06.076  1018  1449 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,08-24 14:31:06.086  1018  1449 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:06.086  1018  1449 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:06.086  1018  1449 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:06.086  1938  7438 D LocationInitializer: Restart initialization of location
,08-24 14:31:06.086  1018  1441 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-24 14:31:06.086  1018  1441 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,08-24 14:31:06.086  1018  1441 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:06.086  1018  1441 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:06.086  1018  1441 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:06.106  7162  7162 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-24 14:31:06.116  1874  1874 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-24 14:31:06.146  1018  1491 I art     : Explicit concurrent mark sweep GC freed 26368(1452KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.488ms total 147.742ms
,08-24 14:31:06.156  1755  3161 E MDM     : [182] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-24 14:31:06.166  1755  3161 E MDM     : [182] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-24 14:31:06.196  1018  3413 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 14:31:06.526  7061  7061 I Mms/MmsApp:  start initViewCache mms
,08-24 14:31:06.526  7061  7061 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1779.21401
08-24 14:31:06.526  7061  7061 D Mms/ComposeMessageFragment: fillCache, easy = false
,08-24 14:31:06.566  7061  7090 W art     : Suspending all threads took: 6.960ms
,08-24 14:31:06.616  7061  7061 D AbsListView: Get MotionRecognitionManager
,08-24 14:31:06.626  1018  1491 D MotionRecognitionService:  ssp status : false
,08-24 14:31:06.626  7061  7061 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 100.128541
,08-24 14:31:06.706  7162  7437 W jxcore-log: Initializing JXcore engine
08-24 14:31:06.706  7162  7437 W jxcore-log: JXcore engine is ready
,08-24 14:31:06.706  7061  7061 D Mms/BubbleViewCache: fillCache bubble = 1
,08-24 14:31:06.756  2016  2016 E audit   : type=1400 msg=audit(1472041866.756:205): avc:  denied  { ioctl } for  pid=7437 comm="Thread-1360" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2071 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-24 14:31:06.756  2016  2016 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-24 14:31:06.766  2016  2016 E audit   : type=1300 msg=audit(1472041866.756:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9f5fb8f8 items=0 ppid=305 ppcomm=main pid=7437 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1360" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-24 14:31:06.766  2016  2016 E audit   : type=1320 msg=audit(1472041866.756:205): 
,08-24 14:31:06.776  7162  7437 W jxcore-log: Starting JXcore engine
,08-24 14:31:06.876  7162  7437 W jxcore-log: Platform android
08-24 14:31:06.876  7162  7437 W jxcore-log: 
08-24 14:31:06.876  7162  7437 W jxcore-log: Process ARCH arm
08-24 14:31:06.876  7162  7437 W jxcore-log: 
,08-24 14:31:07.086  7162  7437 I jxcore-log: JXcore Cordova bridge is ready!
08-24 14:31:07.086  7162  7437 I jxcore-log: 
,08-24 14:31:07.086  7162  7437 W jxcore-log: JXcore engine is started
,08-24 14:31:07.096  7162  7402 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-24 14:31:07.096  7162  7162 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-24 14:31:08.686   288   288 E SMD     : DCD OFF
,08-24 14:31:09.166  2653  2653 I ConfigService: onDestroy
,08-24 14:31:09.296  1018  3385 D SSRM:n  : SIOP:: AP = 410
,08-24 14:31:11.166  1018  1030 I ActivityManager: Killing 6147:com.samsung.android.sm/1000 (adj 15): empty #21
,08-24 14:31:11.196  1018  3413 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 14:31:11.686   288   288 E SMD     : DCD OFF,
,08-24 14:31:12.586  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:12.586  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:12.586  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:12.586  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:12.596  7444  7444 E Zygote  : MountEmulatedStorage(),
08-24 14:31:12.596  7444  7444 E Zygote  : v2
08-24 14:31:12.596  7444  7444 I libpersona: KNOX_SDCARD checking this for 1000
08-24 14:31:12.596  7444  7444 I libpersona: KNOX_SDCARD not a persona
,08-24 14:31:12.596  7444  7444 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-24 14:31:12.606  1018  1044 I ActivityManager: Start proc com.samsung.aasaservice for service com.samsung.aasaservice/.AASAService: pid=7444 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-24 14:31:12.606  7444  7444 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-24 14:31:12.606  7444  7444 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 14:31:12.626  7444  7444 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:31:12.626  7444  7444 D ActivityThread: Added TimaKeyStore provider
,08-24 14:31:12.656  7444  7444 D AASAservice: onCreate()
,08-24 14:31:12.656  7444  7444 E AASAservice: getConfirmRuleVersion() : Version File is not exist.
,08-24 14:31:12.656  2786  2786 I DBG_POLICYDM: [com.sec.android.policydm.aasa.AASAUpdater$1(72/onServiceConnected)] AASA: onServiceConnected
,08-24 14:31:13.606  1018  1508 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 14:31:13.606  1018  1508 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4252, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 14:31:13.606  1018  1508 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-24 14:31:13.606  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 14:31:13.606  1018  1018 I MotionRecognitionService: Plugged
,08-24 14:31:13.606  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-24 14:31:13.606  1018  1508 D BatteryService: stay LED for charging
,08-24 14:31:13.616  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 14:31:13.616  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 14:31:13.616  1424  1424 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-24 14:31:13.616  1424  1424 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 14:31:13.626  3217  3217 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 14:31:13.626  3217  3356 D HeadsetStateMachine: Disconnected process message: 10
,08-24 14:31:13.646  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-24 14:31:13.646  1179  1179 D SViewCoverView: level :100 plugged : 2
,08-24 14:31:13.646  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 14:31:13.646  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 14:31:13.646  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 14:31:14.016  1018  1058 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-24 14:31:14.686   288   288 E SMD     : DCD OFF
,08-24 14:31:15.216  1018  1058 D PackageManager: [MSG] MCS_UNBIND
,08-24 14:31:15.216  1018  1449 I ActivityManager: Killing 6985:com.google.android.gms:car/u0a11 (adj 15): empty #21
,08-24 14:31:15.276  1018  1441 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.car.InCallServiceImpl in 1000ms
,08-24 14:31:15.816  1018  1330 E Watchdog: !@Sync 3
,08-24 14:31:16.286  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:16.286  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:16.286  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:16.286  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:16.296  7461  7461 E Zygote  : MountEmulatedStorage(),
,08-24 14:31:16.296  7461  7461 E Zygote  : v2,
08-24 14:31:16.296  7461  7461 I libpersona: KNOX_SDCARD checking this for 10011
08-24 14:31:16.296  7461  7461 I libpersona: KNOX_SDCARD not a persona
,08-24 14:31:16.306  7461  7461 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 14:31:16.306  1018  1044 I ActivityManager: Start proc com.google.android.gms:car for service com.google.android.gms/.car.InCallServiceImpl: pid=7461 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,08-24 14:31:16.306  7461  7461 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-24 14:31:16.306  7461  7461 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-24 14:31:16.326  7461  7461 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:31:16.326  7461  7461 D ActivityThread: Added TimaKeyStore provider
,08-24 14:31:16.346  7461  7461 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-24 14:31:16.346  7461  7461 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-24 14:31:16.376  7461  7461 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,08-24 14:31:16.376  7461  7461 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,08-24 14:31:16.376  7461  7461 I MultiDex: VM with version 2.1.0 has multidex support
08-24 14:31:16.376  7461  7461 I MultiDex: install
08-24 14:31:16.376  7461  7461 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-24 14:31:16.396  7461  7461 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-24 14:31:16.466  7461  7461 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-24 14:31:16.466  7461  7461 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@175f66a2: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-24 14:31:16.466  7461  7461 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-24 14:31:16.466  1018  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:16.466  1018  1044 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:16.466  1018  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:16.476  1018  1491 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-24 14:31:16.476  1018  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-24 14:31:16.476  1018  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:16.476  1018  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:16.476  1018  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:16.476  1018  1489 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
08-24 14:31:16.476  1018  1489 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
08-24 14:31:16.476  1018  1489 I splitIntent: other index=5, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
08-24 14:31:16.476  1018  1489 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,08-24 14:31:16.476  2653  2679 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-24 14:31:16.476  1018  1489 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:16.476  1018  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-24 14:31:16.476  1018  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:16.486  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:16.486  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:16.486  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:16.486  2653  2653 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-24 14:31:16.496  1018  1441 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:16.496  1018  1441 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:16.496  1018  1441 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:16.496  1018  3813 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-24 14:31:16.496  1018  3813 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,08-24 14:31:16.496  1018  3813 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:16.496  1018  3813 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:16.496  1018  3813 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:16.496  1018  1441 I ActivityManager: Killing 6969:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
,08-24 14:31:16.506  1018  1441 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:16.506  1018  1441 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:16.506  1018  1441 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:16.506  2653  2653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 14:31:16.516  1018  1217 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:16.516  1018  1217 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:16.516  1018  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:16.516  1938  1938 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,08-24 14:31:16.516  1018  1449 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-24 14:31:16.516  1018  1449 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,08-24 14:31:16.516  1018  1449 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:16.516  1018  1449 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-24 14:31:16.516  1018  1449 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:16.526  1018  1441 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:16.526  1018  1441 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:16.526  1018  1441 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:16.526  1018  1441 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:16.526  1018  1441 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:16.526  1018  1441 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-24 14:31:16.526  7461  7478 D NativeLibraryUtils: Install completed successfully. count=0 extracted=0
,08-24 14:31:16.536  1018  1508 W ActivityManager: userId = 0, bbcId = -10000,
08-24 14:31:16.536  1018  1508 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:16.536  1018  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:16.536  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:16.536  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:16.536  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:16.536  1018  1491 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 14:31:16.546  1018  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:16.546  1018  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:16.546  1018  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:16.546  7413  7413 D WearableService: callingUid 10011, callindPid: 7413
,08-24 14:31:16.546  1018  1217 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:16.546  1018  1217 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:16.546  1018  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:16.556  1755  5173 E MDM     : [189] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null},
,08-24 14:31:16.566  1018  1449 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:16.566  1018  1449 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:16.566  1018  1449 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:16.566  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:16.566  1018  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:16.576  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:16.576  1018  1491 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 14:31:16.576  1018  1491 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:16.576  1018  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:16.576  1018  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:16.586  1018  1489 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:16.586  1018  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:16.586  1018  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:16.586  1018  1439 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-24 14:31:16.586  1018  1439 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,08-24 14:31:16.596  1018  1439 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:16.596  1018  1439 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-24 14:31:16.596  1018  1439 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:16.596  1938  7480 D LocationInitializer: Restart initialization of location
,08-24 14:31:16.596  1018  3813 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-24 14:31:16.596  1018  3813 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,08-24 14:31:16.596  1018  3813 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:16.596  1018  3813 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:16.596  1018  3813 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:16.606  1018  1439 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 14:31:16.606  1018  1439 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:16.606  1018  1439 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:16.606  1018  1439 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:16.796   315   315 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-24 14:31:16.796   315   315 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-24 14:31:17.686   288   288 E SMD     : DCD OFF,
,08-24 14:31:18.906  1018  1051 I PowerManagerService: [PWL] Off : 50s ago
,08-24 14:31:19.316  1018  3385 D SSRM:n  : SIOP:: AP = 390
,08-24 14:31:19.416  1018  1097 V AlarmManager: waitForAlarm result :4
08-24 14:31:19.416  1018  1097 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,08-24 14:31:19.426  1018  1018 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,08-24 14:31:19.426  1018  1018 V AlarmManagerEXT: <AppSync3 Whitelist>,
08-24 14:31:19.426  1018  1018 V AlarmManagerEXT: (AppSync) ### 0 added ###
,08-24 14:31:19.436  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
08-24 14:31:19.436  1179  1179 D KeyguardUpdateMonitor: handleTimeUpdate
,08-24 14:31:19.456  1179  1179 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-24 14:31:19.456  1179  1179 D SecKeyguardClockView: HomeTimezone(): 1
,08-24 14:31:19.456  1179  1179 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-24 14:31:19.456  1179  1179 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
08-24 14:31:19.456  1179  1179 I KeyguardEffectViewController: *** don't update sliding image ***
,08-24 14:31:19.466  1179  1179 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,08-24 14:31:19.496  1179  1179 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-24 14:31:19.506  1179  1179 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-24 14:31:19.506  1179  1179 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-24 14:31:19.526  1179  1179 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-24 14:31:19.676  7096  7207 D Finsky  : [1344] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,08-24 14:31:19.676  7096  7096 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-24 14:31:20.696   288   288 E SMD     : DCD OFF
,08-24 14:31:21.176  7162  7437 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-24 14:31:21.176  7162  7437 I jxcore-log: 
,08-24 14:31:21.796   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-24 14:31:22.796   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-24 14:31:23.426  7162  7437 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js,
08-24 14:31:23.426  7162  7437 I jxcore-log: 
,08-24 14:31:23.456  7162  7437 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js,
08-24 14:31:23.456  7162  7437 I jxcore-log: 
,08-24 14:31:23.486  7162  7437 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js,
08-24 14:31:23.486  7162  7437 I jxcore-log: 
,08-24 14:31:23.506  7162  7437 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js,
08-24 14:31:23.506  7162  7437 I jxcore-log: 
,08-24 14:31:23.516  7162  7437 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js,
08-24 14:31:23.516  7162  7437 I jxcore-log: 
,08-24 14:31:23.646  1018  1217 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 14:31:23.646  1018  1217 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4256, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 14:31:23.646  1018  1217 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-24 14:31:23.656  1018  1217 D BatteryService: stay LED for charging
,08-24 14:31:23.656  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-24 14:31:23.656  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-24 14:31:23.656  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 14:31:23.656  1424  1424 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
08-24 14:31:23.656  1424  1424 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 14:31:23.656  1018  1018 I MotionRecognitionService: Plugged
,08-24 14:31:23.656  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-24 14:31:23.666  3217  3217 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 14:31:23.666  3217  3356 D HeadsetStateMachine: Disconnected process message: 10
,08-24 14:31:23.676  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-24 14:31:23.676  1179  1179 D SViewCoverView: level :100 plugged : 2
,08-24 14:31:23.686  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 14:31:23.686  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 14:31:23.686  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 14:31:23.696   288   288 E SMD     : DCD OFF
,08-24 14:31:23.796   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 14:31:24.796   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-24 14:31:25.796   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-24 14:31:26.696   288   288 E SMD     : DCD OFF
,08-24 14:31:26.796   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,08-24 14:31:27.296  7162  7437 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-24 14:31:27.296  7162  7437 I jxcore-log: 
,08-24 14:31:27.306  7162  7437 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-24 14:31:27.306  7162  7437 I jxcore-log: 
,08-24 14:31:27.306  7162  7437 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:31:27.306  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:27.306  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:31:27.306  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:31:27.306  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:31:27.306  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 14:31:27.306  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 14:31:27.306  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 14:31:27.316  7162  7437 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 14:31:27.316  7162  7437 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-24 14:31:27.316  7162  7437 I jxcore-log: 
,08-24 14:31:27.316  7162  7437 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native,
08-24 14:31:27.316  7162  7437 I jxcore-log: 
,08-24 14:31:27.846  6047  6047 D FactoryTest: Not factory mode
,08-24 14:31:27.846  6047  6047 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-24 14:31:27.846  6047  6047 D MTPRx   : DRIVER_TIME_OUT 60s lapsed,
08-24 14:31:27.846  6047  6047 D MTPRx   : still no open session command from host, so toast,
,08-24 14:31:27.856  6047  6047 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 ,
,08-24 14:31:27.856  6047  6047 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:120172,
08-24 14:31:27.856  6047  6047 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-24 14:31:27.856  1018  1492 E PersonaManagerService: inState():  stateMachine is null !!
08-24 14:31:27.856  1018  1492 I PersonaManagerService: PersonaId don't exist
,08-24 14:31:27.856  1018  1492 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-24 14:31:27.856  1018  1492 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
,08-24 14:31:27.866  1018  1492 W ActivityManager: userId = 0, bbcId = -10000,
08-24 14:31:27.866  1018  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:27.866  1018  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-24 14:31:27.866  1018  1492 W ActivityManager: mDVFSHelper.acquire()
,08-24 14:31:27.876  1018  1492 D PersonaManager: isKioskContainerExistOnDevice
,08-24 14:31:27.896  1018  1492 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest,
08-24 14:31:27.896  1018  1492 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
08-24 14:31:27.896  1018  1492 D InputDispatcher: Focused application set to: xxxx,
08-24 14:31:27.896  1018  1492 D InputDispatcher: Focus left window: 7162
,08-24 14:31:27.896  6047  6047 E MTPRx   : started activity for popup
,08-24 14:31:27.906  1018  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-24 14:31:27.916  1018  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-24 14:31:27.926  6047  6047 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
08-24 14:31:27.926  6047  6047 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-24 14:31:27.926  6047  6047 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-24 14:31:27.926  6047  6047 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-24 14:31:27.926  6047  6047 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-24 14:31:27.926  6047  6047 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-24 14:31:27.946  6047  6047 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-24 14:31:27.946  1018  1508 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-24 14:31:27.946  1018  1508 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-24 14:31:27.946  1018  1508 D InputDispatcher: Focused application set to: xxxx
,08-24 14:31:27.956  1018  1508 D InputDispatcher: Focus entered window: 7162
,08-24 14:31:27.956  1018  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-24 14:31:27.956  1018  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-24 14:31:27.956  1018  3813 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-24 14:31:27.956  1018  3813 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@32c34c96 attribute=null, token = android.os.BinderProxy@14f3ae3
,08-24 14:31:27.996  6047  6047 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-24 14:31:27.996  6047  6047 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-24 14:31:27.996  6047  6047 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-24 14:31:28.016  7162  7162 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-24 14:31:28.016  7162  7162 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
08-24 14:31:28.016  7162  7162 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-24 14:31:28.016  7162  7162 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-24 14:31:28.026  1018  1439 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-24 14:31:28.026  1018  1439 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-24 14:31:28.026  1018  1439 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-24 14:31:28.026  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-24 14:31:28.026  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
,08-24 14:31:28.036  7162  7162 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-24 14:31:28.036  7162  7162 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-24 14:31:28.046  7162  7162 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@c0a0ab7 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@127ce18c, 16908290=android.view.AbsSavedState$1@127ce18c}, android:focusedViewId=100}]}]
08-24 14:31:28.046  7162  7162 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-24 14:31:28.046  7162  7162 V ActivityThread: updateVisibility : ActivityRecord{1b4410c1 token=android.os.BinderProxy@341021cb {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-24 14:31:28.046  7162  7162 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-24 14:31:28.046  7162  7162 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-24 14:31:28.046  7162  7162 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@341021cb time:120361
,08-24 14:31:28.056  1018  1137 D PersonaManager: isKioskContainerExistOnDevice
,08-24 14:31:29.336  1018  3385 D SSRM:n  : SIOP:: AP = 380
,08-24 14:31:29.696   288   288 E SMD     : DCD OFF
,08-24 14:31:30.866  1018  1044 W ActivityManager: mDVFSHelper.release()
,08-24 14:31:31.196  1018  3413 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 14:31:31.796   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-24 14:31:32.176  7162  7437 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js,
08-24 14:31:32.176  7162  7437 I jxcore-log: 
,08-24 14:31:32.186  7162  7437 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js,
08-24 14:31:32.186  7162  7437 I jxcore-log: 
,08-24 14:31:32.196  7162  7437 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js,
08-24 14:31:32.196  7162  7437 I jxcore-log: 
,08-24 14:31:32.406  7162  7437 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js,
08-24 14:31:32.406  7162  7437 I jxcore-log: 
,08-24 14:31:32.696   288   288 E SMD     : DCD OFF,
,08-24 14:31:32.796   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-24 14:31:33.466  7162  7437 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js,
08-24 14:31:33.466  7162  7437 I jxcore-log: 
,08-24 14:31:33.536  7162  7437 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js,
08-24 14:31:33.536  7162  7437 I jxcore-log: 
,08-24 14:31:33.546  7162  7437 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js,
08-24 14:31:33.546  7162  7437 I jxcore-log: 
,08-24 14:31:33.696  1018  1491 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-24 14:31:33.696  1018  1491 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4257, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 14:31:33.696  1018  1491 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-24 14:31:33.696  1018  1491 D BatteryService: stay LED for charging
08-24 14:31:33.696  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 14:31:33.706  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 14:31:33.706  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 14:31:33.706  1424  1424 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-24 14:31:33.706  1424  1424 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 14:31:33.716  1018  1018 I MotionRecognitionService: Plugged
08-24 14:31:33.716  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-24 14:31:33.716  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-24 14:31:33.716  1179  1179 D SViewCoverView: level :100 plugged : 2
,08-24 14:31:33.716  3217  3217 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-24 14:31:33.716  3217  3356 D HeadsetStateMachine: Disconnected process message: 10
,08-24 14:31:33.736  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 14:31:33.736  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 14:31:33.736  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 14:31:33.796   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 14:31:33.806  7162  7437 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-24 14:31:33.806  7162  7437 I jxcore-log: 
,08-24 14:31:33.826  7162  7437 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-24 14:31:33.826  7162  7437 I jxcore-log: 
,08-24 14:31:33.836  7162  7437 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-24 14:31:33.836  7162  7437 I jxcore-log: 
,08-24 14:31:33.846  7162  7437 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js,
08-24 14:31:33.846  7162  7437 I jxcore-log: 
,08-24 14:31:33.866  7162  7437 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js,
08-24 14:31:33.866  7162  7437 I jxcore-log: 
,08-24 14:31:33.886  7162  7437 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js,
08-24 14:31:33.886  7162  7437 I jxcore-log: 
,08-24 14:31:33.996  7162  7437 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js,
08-24 14:31:33.996  7162  7437 I jxcore-log: 
,08-24 14:31:34.006  7162  7437 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js,
08-24 14:31:34.006  7162  7437 I jxcore-log: 
,08-24 14:31:34.016  7162  7437 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js,
08-24 14:31:34.016  7162  7437 I jxcore-log: 
,08-24 14:31:34.026  7162  7437 D ExecuteNativeTests: Running unit tests,
,08-24 14:31:34.116  7162  7437 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 14:31:34.116  7162  7437 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1028a945 added. We now have 2 listener(s)
,08-24 14:31:34.116  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-24 14:31:34.116  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 14:31:34.116  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 14:31:34.116  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:31:34.116  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3541489a added. We now have 2 listener(s)
08-24 14:31:34.116  7162  7437 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 14:31:34.116  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 14:31:34.126  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 14:31:34.126  7162  7437 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:31:34.126  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:34.126  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:31:34.126  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:31:34.126  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:31:34.126  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 14:31:34.126  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 14:31:34.126  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 14:31:34.126  7162  7437 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 14:31:34.126  7162  7437 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 14:31:34.136  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:34.136  7162  7437 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-24 14:31:34.136  7162  7437 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-24 14:31:34.136  7162  7437 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-24 14:31:34.136  7162  7437 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-24 14:31:34.136  7162  7437 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-24 14:31:34.136  7162  7437 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-24 14:31:34.136  7162  7437 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-24 14:31:34.136  7162  7437 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-24 14:31:34.136  7162  7437 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:31:34.136  7162  7437 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:31:34.136  7162  7437 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 14:31:34.136  7162  7437 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:34.136  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.136  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 14:31:34.136  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 14:31:34.136  7162  7437 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1028a945 removed from the list
08-24 14:31:34.136  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:34.136  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3541489a removed from the list
,08-24 14:31:34.136  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:34.136  7162  7437 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:31:34.136  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:31:34.136  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.136  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:31:34.136  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 14:31:34.136  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:31:34.136  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 14:31:34.136  7162  7437 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3541489a not in the list
08-24 14:31:34.136  7162  7437 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-24 14:31:34.146  7162  7437 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:31:34.146  7162  7437 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:31:34.146  7162  7437 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:31:34.146  7162  7437 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:34.146  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.146  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:34.146  7162  7437 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1028a945 not in the list
,08-24 14:31:34.146  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:34.146  7162  7437 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3541489a not in the list
08-24 14:31:34.146  7162  7437 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:31:34.146  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.146  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:34.146  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.146  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:34.146  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:31:34.146  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:31:34.146  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:34.146  7162  7437 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3541489a not in the list
08-24 14:31:34.146  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-24 14:31:34.146  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-24 14:31:34.146  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-24 14:31:34.146  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-24 14:31:34.146  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-24 14:31:34.146  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-24 14:31:34.146  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-24 14:31:34.146  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-24 14:31:34.146  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-24 14:31:34.146  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-24 14:31:34.146  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-24 14:31:34.146  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-24 14:31:34.146  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-24 14:31:34.146  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-24 14:31:34.146  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-24 14:31:34.146  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-24 14:31:34.146  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-24 14:31:34.146  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-24 14:31:34.146  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-24 14:31:34.146  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-24 14:31:34.146  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-24 14:31:34.146  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-24 14:31:34.146  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-24 14:31:34.146  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-24 14:31:34.146  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-24 14:31:34.146  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-24 14:31:34.146  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-24 14:31:34.146  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-24 14:31:34.146  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-24 14:31:34.146  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-24 14:31:34.146  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-24 14:31:34.146  7162  7437 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:31:34.146  7162  7437 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:31:34.146  7162  7437 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:31:34.146  7162  7437 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:34.146  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.146  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:34.146  7162  7437 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1028a945 not in the list
08-24 14:31:34.146  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:34.146  7162  7437 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3541489a not in the list
08-24 14:31:34.146  7162  7437 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:31:34.146  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.146  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:34.146  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.146  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:34.146  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:31:34.146  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:31:34.146  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:34.146  7162  7437 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3541489a not in the list
08-24 14:31:34.146  7162  7437 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-24 14:31:34.156  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 14:31:34.156  7162  7437 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:31:34.156  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:34.156  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:31:34.156  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:31:34.156  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:31:34.156  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 14:31:34.156  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 14:31:34.156  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 14:31:34.156  7162  7437 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 14:31:34.156  7162  7437 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 14:31:34.156  7162  7437 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 14:31:34.156  7162  7437 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 14:31:34.156  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 14:31:34.156  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 14:31:34.156  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-24 14:31:34.166  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:31:34.166  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-24 14:31:34.166  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:31:34.166  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-24 14:31:34.176  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-24 14:31:34.176  7162  7437 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-24 14:31:34.176  7162  7437 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-24 14:31:34.176  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-24 14:31:34.176  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-24 14:31:34.176  7162  7437 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-24 14:31:34.186  3217  3228 D BtGatt.GattService: registerClient() - UUID=6a2a27a4-1343-422d-a664-b99de21581d7
,08-24 14:31:34.226  3217  3295 D BtGatt.GattService: onClientRegistered() - UUID=6a2a27a4-1343-422d-a664-b99de21581d7, clientIf=6
08-24 14:31:34.226  7162  7175 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-24 14:31:34.226  3217  3226 D BtGatt.GattService: start scan with filters
,08-24 14:31:34.236  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-24 14:31:34.236  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-24 14:31:34.236  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-24 14:31:34.236  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-24 14:31:34.236  3217  3354 D BtGatt.ScanManager: handling starting scan
,08-24 14:31:34.236  3217  3354 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8e0de1
,08-24 14:31:34.236  7162  7437 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 14:31:34.236  7162  7437 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-24 14:31:34.236  7162  7162 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 14:31:34.236  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-24 14:31:34.246  7162  7437 I io.jxcore.node.ConnectionHelper: start: OK
,08-24 14:31:34.246  3217  3295 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
08-24 14:31:34.246  3217  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-24 14:31:34.246  3217  3354 D BtGatt.ScanManager: allow scan with filters
08-24 14:31:34.246  3217  3354 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-24 14:31:34.246  7162  7437 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:31:34.246  7162  7437 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-24 14:31:34.246  7162  7437 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-24 14:31:34.246  7162  7437 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-24 14:31:34.246  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.246  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 14:31:34.246  7162  7437 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-24 14:31:34.246  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 14:31:34.246  7162  7437 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-24 14:31:34.246  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-24 14:31:34.246  3217  3354 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
08-24 14:31:34.246  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-24 14:31:34.246  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-24 14:31:34.246  3217  3351 D BtGatt.GattService: stopScan() - queue size =1
,08-24 14:31:34.246  3217  3226 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-24 14:31:34.246  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-24 14:31:34.246  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-24 14:31:34.246  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-24 14:31:34.246  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-24 14:31:34.246  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-24 14:31:34.256  3217  3295 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-24 14:31:34.256  3217  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 14:31:34.256  3217  3354 D BtGatt.ScanManager: Starting BLE batch scan
08-24 14:31:34.256  3217  3354 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-24 14:31:34.256  7162  7437 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-24 14:31:34.256  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-24 14:31:34.256  7162  7437 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-24 14:31:34.256  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-24 14:31:34.256  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 14:31:34.256  7162  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
08-24 14:31:34.256  7162  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 14:31:34.256  7162  7162 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 14:31:34.256  3217  3295 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-24 14:31:34.256  3217  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 14:31:34.256  7162  7437 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:34.256  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.266  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 14:31:34.266  7162  7437 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1028a945 not in the list
08-24 14:31:34.266  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 14:31:34.266  7162  7437 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3541489a not in the list
08-24 14:31:34.266  7162  7437 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:31:34.266  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:31:34.266  7162  7437 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-24 14:31:34.266  3217  3295 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-24 14:31:34.266  3217  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 14:31:34.266  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 14:31:34.276  7162  7437 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:31:34.276  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:34.276  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:31:34.276  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:31:34.276  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:31:34.276  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 14:31:34.276  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 14:31:34.276  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 14:31:34.276  7162  7437 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 14:31:34.276  7162  7437 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 14:31:34.276  7162  7437 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 14:31:34.276  7162  7437 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 14:31:34.276  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 14:31:34.276  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 14:31:34.276  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-24 14:31:34.276  3217  3354 D BtGatt.ScanManager: filter size is 1
08-24 14:31:34.276  3217  3354 D BtGatt.ScanManager: delete FilterIndex - 3
,08-24 14:31:34.276  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:34.286  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:34.286  3217  3295 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-24 14:31:34.286  3217  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-24 14:31:34.286  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-24 14:31:34.286  3217  3354 D BtGatt.ScanManager: stopping BLe Batch
,08-24 14:31:34.286  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-24 14:31:34.296  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-24 14:31:34.296  3217  3295 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-24 14:31:34.296  3217  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 14:31:34.296  3217  3354 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-24 14:31:34.296  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-24 14:31:34.296  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-24 14:31:34.296  7162  7437 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-24 14:31:34.296  3217  3295 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-24 14:31:34.296  3217  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 14:31:34.306  3217  3228 D BtGatt.GattService: registerClient() - UUID=acd8d02e-9157-4a99-9682-60432eaa10d9
,08-24 14:31:34.346  3217  3295 D BtGatt.GattService: onClientRegistered() - UUID=acd8d02e-9157-4a99-9682-60432eaa10d9, clientIf=6
,08-24 14:31:34.346  7162  7177 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-24 14:31:34.346  3217  3351 D BtGatt.GattService: start scan with filters,
08-24 14:31:34.346  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-24 14:31:34.346  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-24 14:31:34.346  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-24 14:31:34.346  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
08-24 14:31:34.346  7162  7437 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-24 14:31:34.346  7162  7437 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-24 14:31:34.356  7162  7162 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-24 14:31:34.356  3217  3354 D BtGatt.ScanManager: handling starting scan
,08-24 14:31:34.356  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-24 14:31:34.356  3217  3295 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-24 14:31:34.356  3217  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 14:31:34.366  3217  3354 D BtGatt.ScanManager: allow scan with filters,
08-24 14:31:34.366  3217  3354 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-24 14:31:34.366  3217  3354 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-24 14:31:34.366  3217  3295 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-24 14:31:34.366  3217  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-24 14:31:34.366  3217  3354 D BtGatt.ScanManager: Starting BLE batch scan
08-24 14:31:34.366  3217  3354 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-24 14:31:34.366  7162  7437 I io.jxcore.node.ConnectionHelper: start: OK
,08-24 14:31:34.366  3217  3295 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-24 14:31:34.366  3217  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 14:31:34.376  7162  7437 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 14:31:34.376  7162  7437 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-24 14:31:34.376  7162  7437 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-24 14:31:34.376  7162  7437 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-24 14:31:34.376  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.376  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 14:31:34.376  7162  7437 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-24 14:31:34.376  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 14:31:34.376  7162  7437 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-24 14:31:34.376  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-24 14:31:34.376  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-24 14:31:34.376  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-24 14:31:34.376  3217  3351 D BtGatt.GattService: stopScan() - queue size =1
,08-24 14:31:34.376  3217  3295 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-24 14:31:34.376  3217  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-24 14:31:34.376  3217  3228 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-24 14:31:34.376  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 14:31:34.376  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-24 14:31:34.376  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-24 14:31:34.376  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-24 14:31:34.376  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-24 14:31:34.376  7162  7437 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-24 14:31:34.376  3217  3354 D BtGatt.ScanManager: filter size is 1
08-24 14:31:34.376  3217  3354 D BtGatt.ScanManager: delete FilterIndex - 4
08-24 14:31:34.386  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-24 14:31:34.386  7162  7437 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-24 14:31:34.386  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-24 14:31:34.386  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 14:31:34.386  7162  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-24 14:31:34.386  7162  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 14:31:34.386  7162  7162 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-24 14:31:34.386  7162  7437 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:34.386  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.386  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 14:31:34.386  7162  7437 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1028a945 not in the list
08-24 14:31:34.386  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:34.386  7162  7437 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3541489a not in the list
08-24 14:31:34.386  7162  7437 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:31:34.386  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:31:34.386  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.386  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:31:34.386  3217  3295 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-24 14:31:34.386  3217  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-24 14:31:34.386  3217  3354 D BtGatt.ScanManager: stopping BLe Batch
,08-24 14:31:34.386  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:31:34.386  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-24 14:31:34.386  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:34.386  7162  7437 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3541489a not in the list
,08-24 14:31:34.386  7162  7437 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-24 14:31:34.396  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 14:31:34.396  3217  3295 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-24 14:31:34.396  3217  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-24 14:31:34.396  3217  3354 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-24 14:31:34.396  7162  7437 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:31:34.396  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:34.396  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:31:34.396  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:31:34.396  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:31:34.396  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 14:31:34.396  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 14:31:34.396  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 14:31:34.396  7162  7437 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 14:31:34.406  7162  7437 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 14:31:34.406  7162  7437 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 14:31:34.406  7162  7437 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 14:31:34.406  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 14:31:34.406  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 14:31:34.406  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-24 14:31:34.406  3217  3295 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-24 14:31:34.406  3217  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 14:31:34.406  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:34.406  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-24 14:31:34.406  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:34.416  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-24 14:31:34.416  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-24 14:31:34.416  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-24 14:31:34.416  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-24 14:31:34.416  7162  7437 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-24 14:31:34.426  3217  3352 D BtGatt.GattService: registerClient() - UUID=b91b4ffd-1255-44d6-80d2-4d971f14043c
,08-24 14:31:34.466  3217  3295 D BtGatt.GattService: onClientRegistered() - UUID=b91b4ffd-1255-44d6-80d2-4d971f14043c, clientIf=6
,08-24 14:31:34.466  7162  7175 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-24 14:31:34.466  3217  3351 D BtGatt.GattService: start scan with filters
08-24 14:31:34.466  3217  3354 D BtGatt.ScanManager: handling starting scan
08-24 14:31:34.466  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-24 14:31:34.466  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-24 14:31:34.466  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-24 14:31:34.466  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-24 14:31:34.466  7162  7437 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 14:31:34.476  7162  7437 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-24 14:31:34.476  7162  7162 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-24 14:31:34.476  3217  3295 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-24 14:31:34.476  3217  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 14:31:34.476  3217  3354 D BtGatt.ScanManager: allow scan with filters
08-24 14:31:34.476  3217  3354 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-24 14:31:34.476  3217  3354 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-24 14:31:34.476  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-24 14:31:34.476  3217  3295 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-24 14:31:34.476  3217  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 14:31:34.476  3217  3354 D BtGatt.ScanManager: Starting BLE batch scan
,08-24 14:31:34.476  3217  3354 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-24 14:31:34.486  7162  7437 I io.jxcore.node.ConnectionHelper: start: OK
,08-24 14:31:34.486  7162  7437 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 14:31:34.486  7162  7437 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-24 14:31:34.486  7162  7437 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-24 14:31:34.486  7162  7437 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-24 14:31:34.486  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 14:31:34.486  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 14:31:34.486  7162  7437 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-24 14:31:34.486  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-24 14:31:34.486  3217  3295 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-24 14:31:34.486  3217  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 14:31:34.486  7162  7437 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-24 14:31:34.486  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-24 14:31:34.496  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-24 14:31:34.496  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-24 14:31:34.496  3217  3352 D BtGatt.GattService: stopScan() - queue size =1
,08-24 14:31:34.496  3217  3351 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-24 14:31:34.496  3217  3295 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-24 14:31:34.496  3217  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 14:31:34.496  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 14:31:34.496  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-24 14:31:34.496  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-24 14:31:34.496  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-24 14:31:34.496  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-24 14:31:34.506  7162  7437 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-24 14:31:34.506  3217  3354 D BtGatt.ScanManager: filter size is 1
,08-24 14:31:34.506  3217  3354 D BtGatt.ScanManager: delete FilterIndex - 5,
08-24 14:31:34.506  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-24 14:31:34.506  7162  7437 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-24 14:31:34.506  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-24 14:31:34.506  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
,08-24 14:31:34.506  3217  3295 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-24 14:31:34.506  3217  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-24 14:31:34.506  3217  3354 D BtGatt.ScanManager: stopping BLe Batch
,08-24 14:31:34.506  7162  7437 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:31:34.506  7162  7437 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-24 14:31:34.506  7162  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 14:31:34.506  7162  7437 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-24 14:31:34.506  7162  7437 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:31:34.506  7162  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 14:31:34.506  7162  7437 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-24 14:31:34.506  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.506  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 14:31:34.506  7162  7162 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 14:31:34.506  7162  7437 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1028a945 not in the list
,08-24 14:31:34.506  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:34.506  7162  7437 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3541489a not in the list
,08-24 14:31:34.506  7162  7437 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:31:34.506  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:31:34.506  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.506  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:34.506  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:31:34.506  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:31:34.506  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:34.506  7162  7437 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3541489a not in the list
08-24 14:31:34.506  7162  7437 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-24 14:31:34.516  7162  7437 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:31:34.516  7162  7437 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-24 14:31:34.516  7162  7437 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:31:34.516  7162  7437 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:34.516  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.516  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:34.516  7162  7437 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1028a945 not in the list
08-24 14:31:34.516  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:34.516  7162  7437 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3541489a not in the list
08-24 14:31:34.516  7162  7437 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:31:34.516  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.516  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:34.516  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.516  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:34.516  3217  3295 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-24 14:31:34.516  3217  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-24 14:31:34.516  3217  3354 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-24 14:31:34.516  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:31:34.516  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:31:34.516  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:34.516  7162  7437 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3541489a not in the list
08-24 14:31:34.516  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming],
08-24 14:31:34.516  7162  7437 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:31:34.516  7162  7437 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:31:34.516  7162  7437 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:31:34.516  7162  7437 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 14:31:34.516  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.516  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:34.516  7162  7437 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1028a945 not in the list
08-24 14:31:34.516  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:34.516  7162  7437 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3541489a not in the list
08-24 14:31:34.516  7162  7437 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:31:34.516  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.516  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:34.516  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.516  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:34.516  3217  3295 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-24 14:31:34.516  3217  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-24 14:31:34.526  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:31:34.526  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:31:34.526  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:34.526  7162  7437 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3541489a not in the list
,08-24 14:31:34.526  7162  7437 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-24 14:31:34.526  7162  7437 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:31:34.526  7162  7437 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:31:34.526  7162  7437 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:31:34.526  7162  7437 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:34.526  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.526  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:31:34.526  7162  7437 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1028a945 not in the list
08-24 14:31:34.526  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:34.526  7162  7437 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3541489a not in the list
08-24 14:31:34.526  7162  7437 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:31:34.526  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.526  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:34.526  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.526  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:34.526  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:31:34.526  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-24 14:31:34.526  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:34.526  7162  7437 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3541489a not in the list
08-24 14:31:34.526  7162  7437 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-24 14:31:34.526  7162  7437 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 14:31:34.526  7162  7437 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:31:34.526  7162  7437 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:31:34.526  7162  7437 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:34.526  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.526  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:31:34.526  7162  7437 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1028a945 not in the list
08-24 14:31:34.526  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:34.526  7162  7437 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3541489a not in the list
08-24 14:31:34.526  7162  7437 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:31:34.526  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.526  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:34.526  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.526  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:31:34.526  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 14:31:34.526  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:31:34.526  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:34.526  7162  7437 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3541489a not in the list
,08-24 14:31:34.526  7162  7437 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-24 14:31:34.526  7162  7437 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-24 14:31:34.526  7162  7437 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-24 14:31:34.526  7162  7437 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-24 14:31:34.526  7162  7437 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-24 14:31:34.526  7162  7437 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-24 14:31:34.526  7162  7437 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:31:34.526  7162  7437 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:31:34.526  7162  7437 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:31:34.526  7162  7437 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:34.526  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.526  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:34.526  7162  7437 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1028a945 not in the list
08-24 14:31:34.526  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:34.526  7162  7437 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3541489a not in the list
08-24 14:31:34.526  7162  7437 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:31:34.526  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.526  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:34.526  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.526  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:31:34.536  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 14:31:34.536  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:31:34.536  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 14:31:34.536  7162  7437 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3541489a not in the list
,08-24 14:31:34.536  7162  7437 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-24 14:31:34.536  7162  7437 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-24 14:31:34.536  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-24 14:31:34.536  7162  7437 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-24 14:31:34.536  7162  7437 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-24 14:31:34.536  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-24 14:31:34.536  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-24 14:31:34.536  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-24 14:31:34.536  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-24 14:31:34.536  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-24 14:31:34.536  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-24 14:31:34.536  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-24 14:31:34.536  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-24 14:31:34.536  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-24 14:31:34.536  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-24 14:31:34.536  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-24 14:31:34.536  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-24 14:31:34.536  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-24 14:31:34.536  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-24 14:31:34.536  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-24 14:31:34.536  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-24 14:31:34.536  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-24 14:31:34.536  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-24 14:31:34.536  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-24 14:31:34.536  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-24 14:31:34.536  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-24 14:31:34.536  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-24 14:31:34.536  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-24 14:31:34.536  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-24 14:31:34.536  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-24 14:31:34.536  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-24 14:31:34.536  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-24 14:31:34.536  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710],
08-24 14:31:34.536  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-24 14:31:34.536  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-24 14:31:34.536  7162  7437 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-24 14:31:34.536  7162  7437 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-24 14:31:34.536  7162  7437 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-24 14:31:34.546  7162  7437 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 14:31:34.546  7162  7437 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-24 14:31:34.546  7162  7437 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,08-24 14:31:34.546  7162  7437 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 14:31:34.546  7162  7437 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-24 14:31:34.546  7162  7437 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-24 14:31:34.546  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-24 14:31:34.546  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,08-24 14:31:34.546  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-24 14:31:34.546  7162  7437 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-24 14:31:34.546  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-24 14:31:34.546  7162  7437 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,08-24 14:31:34.546  7162  7437 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 14:31:34.546  7162  7437 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-24 14:31:34.546  7162  7437 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:31:34.546  7162  7437 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-24 14:31:34.546  7162  7437 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:31:34.556  7162  7437 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:34.556  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.556  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:34.556  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-24 14:31:34.556  7162  7495 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1424)
,08-24 14:31:34.556  7162  7437 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1028a945 not in the list,
08-24 14:31:34.556  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:34.556  7162  7437 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3541489a not in the list
08-24 14:31:34.556  7162  7437 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:31:34.556  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.556  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:34.556  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.556  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:31:34.556  7162  7496 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1424,
,08-24 14:31:34.556  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 14:31:34.556  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-24 14:31:34.556  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:34.556  7162  7437 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3541489a not in the list
08-24 14:31:34.556  7162  7437 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,08-24 14:31:34.556  7162  7437 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:31:34.556  7162  7437 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:31:34.556  7162  7437 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:31:34.556  7162  7437 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:34.556  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.556  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:34.556  7162  7437 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1028a945 not in the list
08-24 14:31:34.556  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:34.556  7162  7437 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3541489a not in the list
08-24 14:31:34.556  7162  7437 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:31:34.556  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.556  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:34.556  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.556  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:34.556  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:31:34.556  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:31:34.556  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 14:31:34.556  7162  7437 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3541489a not in the list
08-24 14:31:34.556  7162  7437 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-24 14:31:34.556  7162  7437 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:31:34.566  7162  7495 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
08-24 14:31:34.566  7162  7437 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:31:34.566  7162  7437 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:31:34.566  7162  7437 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:34.566  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.566  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:34.566  7162  7437 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1028a945 not in the list
08-24 14:31:34.566  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:34.566  7162  7437 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3541489a not in the list
08-24 14:31:34.566  7162  7437 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:31:34.566  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.566  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:34.566  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.566  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:31:34.566  7162  7495 D BluetoothSocket: connect(): myUserId = 0
08-24 14:31:34.566  7162  7495 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 14:31:34.566  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:31:34.566  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:31:34.566  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:34.566  7162  7437 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3541489a not in the list
08-24 14:31:34.566  7162  7437 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-24 14:31:34.566  7162  7437 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-24 14:31:34.566  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-24 14:31:34.566  7162  7437 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-24 14:31:34.566  7162  7437 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-24 14:31:34.566  7162  7437 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
,08-24 14:31:34.566  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-24 14:31:34.566  7162  7437 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-24 14:31:34.566  7162  7437 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-24 14:31:34.566  7162  7437 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-24 14:31:34.566  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-24 14:31:34.566  7162  7437 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-24 14:31:34.566  7162  7437 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:31:34.566  7162  7437 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:31:34.566  7162  7437 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:31:34.566  7162  7437 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:34.566  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.566  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:34.566  7162  7437 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1028a945 not in the list
,08-24 14:31:34.566  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:34.566  7162  7437 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3541489a not in the list
08-24 14:31:34.566  7162  7437 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:31:34.566  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.566  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:34.566  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.566  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:34.566  3217  3228 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 14:31:34.566  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:31:34.566  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-24 14:31:34.566  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:34.566  7162  7437 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3541489a not in the list
08-24 14:31:34.566  7162  7437 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:34.566  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.566  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:34.566  7162  7437 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1028a945 not in the list
08-24 14:31:34.566  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:34.566  7162  7437 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3541489a not in the list
08-24 14:31:34.566  7162  7437 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:31:34.566  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.566  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:34.566  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:34.566  7162  7437 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3541489a not in the list
08-24 14:31:34.566  7162  7437 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:34.566  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.566  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:34.566  7162  7437 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1028a945 not in the list
08-24 14:31:34.566  7162  7437 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:31:34.566  7162  7437 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:31:34.566  7162  7437 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:31:34.566  7162  7437 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:34.566  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.566  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:34.566  7162  7437 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1028a945 not in the list
08-24 14:31:34.566  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:34.566  7162  7437 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3541489a not in the list
08-24 14:31:34.566  7162  7437 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:31:34.566  7162  7437 W org.thali,project.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.566  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:34.566  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.566  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:34.566  7162  7495 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
08-24 14:31:34.566  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:31:34.566  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:31:34.566  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:34.566  7162  7437 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3541489a not in the list
08-24 14:31:34.576  7162  7437 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-24 14:31:34.576  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 14:31:34.576  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-24 14:31:34.576  7162  7437 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-24 14:31:34.576  7162  7437 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-24 14:31:34.576  7162  7437 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-24 14:31:34.576  7162  7437 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-24 14:31:34.576  7162  7162 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-24 14:31:34.576  7162  7437 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:34.576  7162  7437 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-24 14:31:34.576  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-24 14:31:34.576  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-24 14:31:34.576  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:34.576  7162  7437 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-24 14:31:34.576  7162  7497 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-24 14:31:34.576  7162  7437 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1028a945 not in the list
08-24 14:31:34.576  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:34.576  7162  7162 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-24 14:31:34.576  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 14:31:34.576  7162  7437 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-24 14:31:34.576  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-24 14:31:34.576  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.576  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:34.576  7162  7497 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-24 14:31:34.576  7162  7437 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 14:31:34.576  7162  7437 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3541489a not in the list
08-24 14:31:34.576  7162  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 14:31:34.576  7162  7437 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:31:34.576  7162  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 14:31:34.576  7162  7437 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:31:34.576  7162  7162 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
08-24 14:31:34.576  7162  7437 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:31:34.576  7162  7437 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:34.576  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.576  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:34.576  7162  7437 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1028a945 not in the list
08-24 14:31:34.576  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:34.576  7162  7437 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3541489a not in the list
08-24 14:31:34.576  7162  7437 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:31:34.576  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 14:31:34.576  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:34.576  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.576  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:34.576  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:31:34.576  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:31:34.576  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:34.576  7162  7437 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3541489a not in the list
08-24 14:31:34.576  7162  7162 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-24 14:31:34.576  7162  7437 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-24 14:31:34.576  7162  7437 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-24 14:31:34.576  7162  7437 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-24 14:31:34.576  7162  7437 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-24 14:31:34.576  7162  7437 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 14:31:34.576  7162  7437 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:31:34.576  7162  7437 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:31:34.576  7162  7437 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:34.576  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.576  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:34.576  7162  7437 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1028a945 not in the list
08-24 14:31:34.576  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:34.576  7162  7437 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3541489a not in the list
08-24 14:31:34.576  7162  7437 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:31:34.576  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.576  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-24 14:31:34.576  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.576  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:34.586  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:31:34.586  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:31:34.586  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:34.586  7162  7437 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3541489a not in the list
,08-24 14:31:34.586  7162  7437 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:31:34.586  7162  7437 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:31:34.586  7162  7437 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 14:31:34.586  7162  7437 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:34.586  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.586  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:34.586  7162  7437 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1028a945 not in the list
08-24 14:31:34.586  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:34.586  7162  7437 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3541489a not in the list
08-24 14:31:34.586  7162  7437 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:31:34.586  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.586  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:34.586  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.586  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:31:34.586  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:31:34.586  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:31:34.586  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:34.586  7162  7437 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3541489a not in the list
,08-24 14:31:34.586  7162  7437 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:31:34.586  7162  7437 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:31:34.586  7162  7437 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:31:34.586  7162  7437 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:34.586  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.586  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:34.586  7162  7437 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1028a945 not in the list
08-24 14:31:34.586  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:34.586  7162  7437 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3541489a not in the list
08-24 14:31:34.586  7162  7437 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:31:34.586  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.586  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:34.586  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:34.586  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:31:34.586  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:31:34.586  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:31:34.586  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:34.586  7162  7437 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3541489a not in the list
,08-24 14:31:34.586  7162  7437 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-24 14:31:34.586  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-24 14:31:34.586  7162  7437 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-24 14:31:34.586  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-24 14:31:34.586  7162  7437 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-24 14:31:34.586  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-24 14:31:34.586  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-24 14:31:34.586  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-24 14:31:34.596  7162  7437 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-24 14:31:34.596  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-24 14:31:34.596  7162  7437 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-24 14:31:34.596  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-24 14:31:34.596  7162  7437 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,08-24 14:31:34.596  7162  7437 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-24 14:31:34.596  7162  7437 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-24 14:31:34.596  7162  7437 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-24 14:31:34.596  7162  7437 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-24 14:31:34.596  7162  7437 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,08-24 14:31:34.596  7162  7437 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-24 14:31:34.596  7162  7437 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-24 14:31:34.596  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:31:34.596  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1e015ec added. We now have 2 listener(s)
08-24 14:31:34.596  7162  7437 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 14:31:34.596  7162  7437 D BluetoothAdapter: enable()
,08-24 14:31:34.596  7162  7437 D BluetoothAdapter: enable(): BT is already enabled..!
,08-24 14:31:34.596  1018  1031 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-24 14:31:34.596  1018  1031 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-24 14:31:34.596  1018  1031 D SecContentProvider2: mCursor = null
,08-24 14:31:34.596  1018  1031 D WifiService: setWifiEnabled: true pid=7162, uid=10170
08-24 14:31:34.596  1018  1031 W ActivityManager: Permission Denial: getCurrentUser() from pid=7162, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-24 14:31:34.606  1018  1031 W WifiService: Failed getting userId using ActivityManagerNative
08-24 14:31:34.606  1018  1031 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7162, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-24 14:31:34.606  1018  1031 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-24 14:31:34.606  1018  1031 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-24 14:31:34.606  1018  1031 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-24 14:31:34.606  1018  1031 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-24 14:31:34.606  1018  1031 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-24 14:31:34.606  1018  1031 D SettingsProvider: name = wifi_on
,08-24 14:31:34.606  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:31:34.606  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@339f6db5 added. We now have 3 listener(s)
08-24 14:31:34.606  7162  7437 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 14:31:34.606  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:31:34.606  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1d4d0c4a added. We now have 4 listener(s)
08-24 14:31:34.606  7162  7437 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 14:31:34.616  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:31:34.616  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3ec8f7bb added. We now have 5 listener(s)
08-24 14:31:34.616  7162  7437 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 14:31:34.616  1018  1449 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-24 14:31:34.616  1018  1449 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-24 14:31:34.616  1018  1449 D SecContentProvider2: mCursor = null
,08-24 14:31:34.616  1018  1449 D WifiService: setWifiEnabled: false pid=7162, uid=10170
,08-24 14:31:34.616  1018  1449 D SettingsProvider: name = wifi_on
,08-24 14:31:34.626  7162  7437 D BluetoothAdapter: disable()
,08-24 14:31:34.626  1018  1129 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-24 14:31:34.626  1018  3812 D SettingsProvider: name = bluetooth_on
,08-24 14:31:34.626  1353  1353 I wpa_supplicant: reset timer : RESET_TIMER 0,
08-24 14:31:34.626  1353  1353 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-24 14:31:34.626  1353  1353 I wpa_supplicant: P2P: Current p2p state = IDLE
08-24 14:31:34.626  1353  1353 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-24 14:31:34.636  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 14:31:34.636  3217  3290 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
08-24 14:31:34.636  3217  3290 D BluetoothAdapterProperties: Setting state to 13
08-24 14:31:34.636  3217  3290 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-24 14:31:34.636  3217  3290 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-24 14:31:34.636  3217  3290 D BluetoothAdapterService: updateAdapterState state is 13
,08-24 14:31:34.636  1018  1449 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:34.636  1018  1449 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 14:31:34.636  1018  1449 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:34.636  1018  1449 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0,
08-24 14:31:34.636  1018  1449 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 14:31:34.636  1018  1217 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-24 14:31:34.636  1353  1353 I wpa_supplicant: Scan aborted because the firmware maybe busy.
08-24 14:31:34.636  1353  1353 I wpa_supplicant: Therefore we will repeat the scan command after 1 seconds.
08-24 14:31:34.636  1353  1353 I wpa_supplicant: wlan0: Setting scan request: 1 sec 0 usec
08-24 14:31:34.636  3217  3217 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
08-24 14:31:34.636  3217  3290 D BluetoothAdapterService: Autoconnection is available 
,08-24 14:31:34.636  3217  3290 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-24 14:31:34.636  3217  3290 D BluetoothAdapterService: terminating service from this receiver
08-24 14:31:34.636  3217  3217 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@7503a1, channel: 19, state: LISTENING
08-24 14:31:34.636  3217  3217 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@7503a1, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@19f0b069, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@873c9c6mSocket: android.net.LocalSocket@35eb6d87 impl:android.net.LocalSocketImpl@2e06f4b4 fd:FileDescriptor[80]
08-24 14:31:34.636  3217  3217 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@35eb6d87 impl:android.net.LocalSocketImpl@2e06f4b4 fd:FileDescriptor[80],
08-24 14:31:34.636  1018  1129 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-24 14:31:34.636  1018  1217 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:34.636  1018  1217 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:34.636  1018  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-24 14:31:34.646  3217  3290 D BluetoothAdapterProperties: onBluetoothDisable()
08-24 14:31:34.646  3217  3290 D BluetoothAdapterProperties: mDiscovering is false
,08-24 14:31:34.646  1018  3813 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-24 14:31:34.646  3217  3290 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-24 14:31:34.646  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:34.646  1018  1018 I InputMethodManagerService: [BT Setting State] State =13
,08-24 14:31:34.646  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:31:34.646  7162  7437 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:31:34.646  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:34.646  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:31:34.646  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:31:34.646  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:31:34.646  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 14:31:34.646  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 14:31:34.646  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 14:31:34.656  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 14:31:34.656  7162  7437 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 14:31:34.656  7162  7437 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 14:31:34.656  1179  1179 D BluetoothTile:  onBluetoothStateChange:
,08-24 14:31:34.656  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:34.656  1179  1179 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-24 14:31:34.656  1179  1179 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:34.656  1179  1179 D BluetoothTile:  getBluetoothState : 13
,08-24 14:31:34.656  1874  1874 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
08-24 14:31:34.656  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:34.666  1018  1031 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-24 14:31:34.666  1179  1753 D BluetoothTile:  handleUpdatestate:false name:null
,08-24 14:31:34.666  1018  3813 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-24 14:31:34.666  1179  1179 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-24 14:31:34.666  1018  1129 E WifiNative-wlan0: do suspend true
08-24 14:31:34.666  4761  4761 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:34.666  1179  1753 D BluetoothTile:  handleUpdatestate:false name:null
,08-24 14:31:34.666  1179  1753 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-24 14:31:34.676  7162  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-24 14:31:34.676  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:31:34.676  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:34.676  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:31:34.676  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:31:34.676  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:31:34.676  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 14:31:34.676  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 14:31:34.676  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 14:31:34.676  3217  3295 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-24 14:31:34.676  7162  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 14:31:34.676  7162  7162 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 14:31:34.686  3217  3295 D BluetoothAdapterProperties: Scan Mode:20
08-24 14:31:34.686  3217  3290 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-24 14:31:34.686  3217  3290 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-24 14:31:34.686  3217  3290 E bt-btif : cmd socket is not created
08-24 14:31:34.686  3217  3298 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
08-24 14:31:34.686  3217  5372 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-24 14:31:34.686  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:31:34.686  4761  4761 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-24 14:31:34.686  7162  7495 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@33a63031, channel: -1, state: INIT
08-24 14:31:34.686  3217  3290 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-24 14:31:34.686  7162  7495 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@33a63031, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1757a316, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1d055497mSocket: android.net.LocalSocket@3ed53684 impl:android.net.LocalSocketImpl@257c9e6d fd:FileDescriptor[106]
08-24 14:31:34.686  7162  7495 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3ed53684 impl:android.net.LocalSocketImpl@257c9e6d fd:FileDescriptor[106]
08-24 14:31:34.686  7162  7495 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1424)
,08-24 14:31:34.686  3217  3217 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2ebd38dd, channel: 5, state: LISTENING
08-24 14:31:34.686  1018  1449 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-24 14:31:34.686  3217  3217 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2ebd38dd, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3b714aee, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@25d2bc52mSocket: android.net.LocalSocket@9875b23 impl:android.net.LocalSocketImpl@2c78a820 fd:FileDescriptor[82]
08-24 14:31:34.686  1018  1449 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
08-24 14:31:34.686  3217  3217 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@9875b23 impl:android.net.LocalSocketImpl@2c78a820 fd:FileDescriptor[82]
08-24 14:31:34.686  1018  1449 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:34.686  1018  1449 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:34.686  1018  1449 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
08-24 14:31:34.686  3217  3217 I BtOppRfcommListener: stopping Accept Thread
08-24 14:31:34.686  3217  3217 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1b5985d9, channel: 12, state: LISTENING
08-24 14:31:34.686  3217  3217 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1b5985d9, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@224fe008, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@abc4b9emSocket: android.net.LocalSocket@b6a867f impl:android.net.LocalSocketImpl@1690264c fd:FileDescriptor[85]
08-24 14:31:34.686  3217  3217 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@b6a867f impl:android.net.LocalSocketImpl@1690264c fd:FileDescriptor[85]
08-24 14:31:34.686  3217  5372 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-24 14:31:34.696  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:34.696  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:34.696  4761  4761 D BluetoothPbap: Proxy object disconnected
08-24 14:31:34.696  4761  4761 D PbapServerProfile: Bluetooth service disconnected
,08-24 14:31:34.696  3217  3298 W bt-sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
08-24 14:31:34.696  3217  3298 E bt-btif : DISCOVERY_COMP_EVT slot id:4, failed to find channle,                                       status:1, scn:0
08-24 14:31:34.696  3217  3298 W bt-btif : invalid rfc slot id: 4
,08-24 14:31:34.696  2653  2653 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 14:31:34.696  3217  3217 V BluetoothOppManager: cleanUp...
,08-24 14:31:34.706  3217  3298 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-24 14:31:34.706  3217  3298 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 14:31:34.706  3217  3298 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-24 14:31:34.706  3217  3298 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-24 14:31:34.706  3217  3298 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 14:31:34.706  3217  3298 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-24 14:31:34.706  4761  4761 D DockEventReceiver: finishStartingService: stopping service
,08-24 14:31:34.706  4761  4761 D BluetoothNotiBroadcastReceiver: onReceive
,08-24 14:31:34.716  1179  1179 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-24 14:31:34.716  1179  1179 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-24 14:31:34.716  1018  1491 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-24 14:31:34.716  1018  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:34.716  1018  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:34.716  1018  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:34.716  1018  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-24 14:31:34.716  1018  1128 D WifiP2pService: InactiveState{ what=143375 }
,08-24 14:31:34.716  1018  1128 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-24 14:31:34.726  7504  7504 E Zygote  : MountEmulatedStorage()
,08-24 14:31:34.726  7504  7504 E Zygote  : v2
08-24 14:31:34.726  7504  7504 I libpersona: KNOX_SDCARD checking this for 10055
08-24 14:31:34.726  7504  7504 I libpersona: KNOX_SDCARD not a persona
,08-24 14:31:34.726  1018  1491 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7504 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-24 14:31:34.726  7504  7504 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 14:31:34.736   278   983 D CommandListener: Clearing all IP addresses on wlan0
,08-24 14:31:34.736  7504  7504 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 14:31:34.736  7504  7504 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-24 14:31:34.736  2653  2689 V NativeCrypto: Read error: ssl=0xb92bebe0: I/O error during system call, Connection timed out
,08-24 14:31:34.736  1179  1179 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 14:31:34.736  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-24 14:31:34.736  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:34.736  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:34.736  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:34.736  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:34.736  2653  2689 V NativeCrypto: SSL shutdown failed: ssl=0xb92bebe0: I/O error during system call, Broken pipe
,08-24 14:31:34.746  1018  1131 E ConnectivityService: updateNetworkInfo()
08-24 14:31:34.746  1018  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-24 14:31:34.746  1018  1131 E ConnectivityService: updateNetworkInfo()
08-24 14:31:34.746  1018  1489 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
08-24 14:31:34.746  1018  1719 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:34.746  1018  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
08-24 14:31:34.746  1018  1719 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:34.746  1018  1719 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-24 14:31:34.746  1018  1719 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:34.746  1018  1719 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,08-24 14:31:34.756  1018  1719 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-24 14:31:34.756  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-24 14:31:34.756  1018  1719 I qtaguid : Tagging socket 328 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1018, getuid(): 1000
,08-24 14:31:34.756  1018  1719 I qtaguid : Untagging socket 328
08-24 14:31:34.756  1018  1719 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 14:31:34.766  1018  1129 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-24 14:31:34.766  1018  1018 D WifiScanningService: SCAN_AVAILABLE : 1
08-24 14:31:34.766  1018  1153 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:34.766  1018  1128 D WifiP2pService: InactiveState{ what=131204 }
08-24 14:31:34.766  1018  1128 D WifiP2pService: P2pEnabledState{ what=131204 }
,08-24 14:31:34.766  1018  1018 D RttService: SCAN_AVAILABLE : 1,
08-24 14:31:34.766  1018  1154 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:34.766  1018  1128 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-24 14:31:34.776  1018  1049 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 14:31:34.776  1018  1049 D WifiDisplayAdapter: onP2pDisconnected
,08-24 14:31:34.776  1018  1128 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-24 14:31:34.776  1018  1018 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED,
08-24 14:31:34.786  1018  1128 D WifiP2pService: P2pDisablingState
08-24 14:31:34.786  1018  1128 D WifiP2pService: P2pDisablingState{ what=147458 }
08-24 14:31:34.786  1018  1128 D WifiP2pService: p2p socket connection lost
08-24 14:31:34.786  1018  1129 E WifiNative-wlan0: do suspend true
08-24 14:31:34.786  1018  1128 D WifiP2pService: P2pDisabledState
,08-24 14:31:34.786  1018  1049 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-24 14:31:34.786  1018  1049 D IpRemoteDisplayController: WfdBridgeServer is already null
08-24 14:31:34.786  7504  7504 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:31:34.786  1018  1049 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false,
08-24 14:31:34.786  1179  1179 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-24 14:31:34.786  1018  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-24 14:31:34.786  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 14:31:34.786  1018  1049 D WifiDisplayController: disconnect
08-24 14:31:34.786  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-24 14:31:34.786  1018  1049 D WifiDisplayController: updateConnection
08-24 14:31:34.786  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:34.786  1018  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-24 14:31:34.786  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:34.786  1018  1049 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0},
08-24 14:31:34.786  7504  7504 D ActivityThread: Added TimaKeyStore provider
08-24 14:31:34.786  1018  1049 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-24 14:31:34.786  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:34.786  1018  1049 D WifiDisplayAdapter: onP2pDisconnected
08-24 14:31:34.786  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:34.786  1018  1049 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-24 14:31:34.786  1018  1049 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-24 14:31:34.796   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 14:31:34.806  1179  1179 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-24 14:31:34.816  1018  1137 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-24 14:31:34.816  1179  1179 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-24 14:31:34.816  1018  1128 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-24 14:31:34.816  1018  1128 D WifiP2pService: DefaultState{ what=143375 }
,08-24 14:31:34.826  7504  7504 D UserAnalysis.PlaceProvider: PlaceProvider onCreate(),
08-24 14:31:34.826  1179  1179 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-24 14:31:34.826  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 14:31:34.826  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-24 14:31:34.826  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:34.826  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:34.826  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:34.826  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 14:31:34.846   278   979 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
08-24 14:31:34.846   278   979 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,08-24 14:31:34.846  1018  1131 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 14:31:34.846  1018  1131 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-24 14:31:34.846  1018  1131 D NetworkStatsFactory: UpdateStatsForKnox updated
08-24 14:31:34.846  1018  1131 V NetworkStats: updateIfacesLocked()
08-24 14:31:34.846  1018  1131 D NetworkStatsFactory: UpdateStatsForKnox main else ---,
08-24 14:31:34.846  1018  1131 V NetworkStats: performPollLocked(flags=0x1)
08-24 14:31:34.846   278   983 D CommandListener: Clearing all IP addresses on wlan0
,08-24 14:31:34.846  1018  1131 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 14:31:34.846  1018  1131 V NetworkStats: performPollLocked() took 5ms
08-24 14:31:34.846  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 14:31:34.846  1018  1131 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
08-24 14:31:34.846  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 14:31:34.856  1179  1728 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,08-24 14:31:34.856  1018  1048 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-24 14:31:34.856  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling,
08-24 14:31:34.856  1353  1353 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
08-24 14:31:34.856  7504  7504 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
08-24 14:31:34.856  1018  1719 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
08-24 14:31:34.856  1018  1719 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-24 14:31:34.856  1018  1719 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,08-24 14:31:34.856  7504  7504 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
,08-24 14:31:34.856  1018  1131 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 14:31:34.856  7504  7504 D UserAnalysis: Create SecureDbHelper
08-24 14:31:34.856  1018  1128 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-24 14:31:34.856  1466  1466 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-24 14:31:34.856  1466  1466 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-24 14:31:34.866  1018  1131 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-24 14:31:34.866  1018  1131 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-24 14:31:34.866  1018  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-24 14:31:34.866  1018  1129 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-24 14:31:34.876  1018  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-24 14:31:34.876  1018  1129 D SecContentProvider2: mCursor = null
,08-24 14:31:34.876  1179  1179 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-24 14:31:34.876  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 14:31:34.876  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-24 14:31:34.876  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:34.876  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:34.876  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:34.876  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 14:31:34.876  1179  1179 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-24 14:31:34.876  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 14:31:34.886  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-24 14:31:34.886  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:34.886  4761  4761 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-24 14:31:34.886  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:34.886  1018  1131 D ConnectivityService: nai.networkMonitor.doQuit()
08-24 14:31:34.886  1018  1131 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-24 14:31:34.886  1018  1131 E ConnectivityService: updateNetworkInfo()
08-24 14:31:34.886  1018  1131 E ConnectivityService: updateNetworkInfo()
08-24 14:31:34.886  1018  1131 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-24 14:31:34.886  7504  7504 D IntelligenceServiceApplication: onCreate()
,08-24 14:31:34.886  1018  1048 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-24 14:31:34.886  7162  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:31:34.886  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:31:34.886  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:34.886  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:31:34.886  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 14:31:34.886  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:31:34.886  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:31:34.886  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:31:34.886  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 14:31:34.886  1018  1018 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,08-24 14:31:34.886  1018  1132 D Tethering: MasterInitialState.processMessage what=3
,08-24 14:31:34.886  7162  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:31:34.886  7162  7162 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 14:31:34.886  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:34.886  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 14:31:34.886  1179  1179 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-24 14:31:34.886  1179  1179 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-24 14:31:34.886  1179  1179 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-24 14:31:34.886  1179  1753 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-24 14:31:34.896  1179  1179 D HotspotTile: onReceive : 0, 0
,08-24 14:31:34.896  1018  1126 V NetworkStats: updateIfacesLocked()
08-24 14:31:34.896  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 14:31:34.896  1018  1126 V NetworkStats: performPollLocked(flags=0x1)
,08-24 14:31:34.896  1018  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-24 14:31:34.896  1018  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-24 14:31:34.896  1018  1126 V NetworkStats: performPollLocked() took 5ms
,08-24 14:31:34.896  7162  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 14:31:34.896  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 14:31:34.896  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:31:34.896  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:34.896  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:31:34.896  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 14:31:34.896  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:31:34.896  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:31:34.896  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:31:34.896  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 14:31:34.896  1179  1179 D StatusBar.NetworkController: EthernetConnected: false
08-24 14:31:34.896  1179  1179 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-24 14:31:34.896  1179  1179 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-24 14:31:34.896  1179  1179 D StatusBar.NetworkController: updateDataNetType()
,08-24 14:31:34.896  7162  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:31:34.896  7162  7162 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 14:31:34.896  7504  7504 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-24 14:31:34.896  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 14:31:34.906  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 14:31:34.906  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 14:31:34.906  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 14:31:34.906  1018  1127 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,08-24 14:31:34.906  1179  1179 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-24 14:31:34.906  1179  1179 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-24 14:31:34.906  1179  1179 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,08-24 14:31:34.906  1179  1179 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 15 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
08-24 14:31:34.906  1179  1179 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
,08-24 14:31:34.906  1179  1179 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
08-24 14:31:34.906  3217  3290 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-24 14:31:34.906  3217  3290 D BtConfig.SecureMode: isSecureModeOn:false
08-24 14:31:34.906  3217  3290 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-24 14:31:34.906  3217  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
08-24 14:31:34.906  3217  3290 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
08-24 14:31:34.906  3217  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-24 14:31:34.906  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-24 14:31:34.906  3217  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-24 14:31:34.906  1018  1439 I ActivityManager: Killing 7011:com.google.android.apps.docs/u0a87 (adj 15): empty #21
,08-24 14:31:34.906  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-24 14:31:34.916  1179  1179 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-24 14:31:34.916  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 14:31:34.916  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-24 14:31:34.916  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:34.916  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:34.916  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:34.916  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 14:31:34.916  1018  1508 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 14:31:34.916  1018  1508 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-24 14:31:34.916  1018  1508 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:34.916  1018  1508 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:34.916  1018  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-24 14:31:34.916  3217  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-24 14:31:34.916  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-24 14:31:34.916  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 14:31:34.916  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 14:31:34.916  3217  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-24 14:31:34.916  3217  3217 D HeadsetService: Received stop request...Stopping profile...
08-24 14:31:34.916  1018  1441 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-24 14:31:34.916  7504  7504 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-24 14:31:34.916  1018  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:34.916  1018  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:34.916  1018  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:34.916  1018  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:34.926  7504  7504 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-24 14:31:34.936  7526  7526 E Zygote  : MountEmulatedStorage()
,08-24 14:31:34.936  7526  7526 E Zygote  : v2
08-24 14:31:34.936  7526  7526 I libpersona: KNOX_SDCARD checking this for 10105
08-24 14:31:34.936  7526  7526 I libpersona: KNOX_SDCARD not a persona
08-24 14:31:34.936  7526  7526 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 14:31:34.936  1018  1441 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7526 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-24 14:31:34.936  7526  7526 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 14:31:34.936  3217  3217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8e0de1
08-24 14:31:34.936  7526  7526 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-24 14:31:34.946  1353  1353 I wpa_supplicant: Blacklist: Clear (all) 
08-24 14:31:34.946  1018  1489 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 14:31:34.946  1018  1489 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-24 14:31:34.946  1018  1489 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:34.946  1018  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:34.946  1018  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 14:31:34.946  1018  1018 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-24 14:31:34.946  3217  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-24 14:31:34.946  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-24 14:31:34.946  3217  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-24 14:31:34.946  4761  4761 D HeadsetProfile: Bluetooth service disconnected
,08-24 14:31:34.946  1018  3812 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 14:31:34.946  1018  3812 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-24 14:31:34.946  1018  3812 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:34.946  1018  3812 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:34.946  1018  3812 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 14:31:34.946  3217  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-24 14:31:34.946  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-24 14:31:34.956  3217  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-24 14:31:34.956  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:34.956  1018  1137 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 14:31:34.956  1018  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:34.956  1018  1137 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-24 14:31:34.956  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 14:31:34.956  3217  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-24 14:31:34.956  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-24 14:31:34.956  3217  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-24 14:31:34.956  1018  1217 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 14:31:34.956  1018  1217 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-24 14:31:34.956  1018  1217 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:34.956  1018  1217 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:34.956  1018  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 14:31:34.956  3217  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-24 14:31:34.956  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-24 14:31:34.956  3217  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-24 14:31:34.966  7526  7526 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:31:34.966  7526  7526 D ActivityThread: Added TimaKeyStore provider
,08-24 14:31:34.966  1018  1449 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 14:31:34.966  1018  1449 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-24 14:31:34.966  1018  1449 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:34.966  1018  1449 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:34.966  1018  1449 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 14:31:34.966  3217  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-24 14:31:34.966  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-24 14:31:34.966  3217  3290 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-24 14:31:34.976  1018  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-24 14:31:34.976  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-24 14:31:34.976  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:34.976  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-24 14:31:34.976  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-24 14:31:34.976  3217  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-24 14:31:34.976  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-24 14:31:34.976  3217  3290 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-24 14:31:34.976  3217  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService,
08-24 14:31:34.976  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-24 14:31:34.986  3217  3290 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-24 14:31:34.986  3217  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-24 14:31:34.986  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-24 14:31:34.986  3217  3290 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,08-24 14:31:34.986  3217  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-24 14:31:34.986  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-24 14:31:34.986  3217  3290 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,08-24 14:31:34.986  3217  3290 D BluetoothAdapterState: Stopping profile services that were post enabled
08-24 14:31:34.986  3217  3217 E BluetoothAdapterService(764284385): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-24 14:31:34.986  3217  3217 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-24 14:31:34.986  3217  3217 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-24 14:31:34.986  3217  3217 D A2dpService: Received stop request...Stopping profile...
08-24 14:31:34.986  3217  3373 D A2dpStateMachine: Exit Disconnected: -1
,08-24 14:31:34.986  3217  3217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8e0de1
,08-24 14:31:34.996  1018  1018 D BluetoothA2dp: Proxy object disconnected
08-24 14:31:34.996  1018  1018 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-24 14:31:34.996  4761  4761 D BluetoothA2dp: Proxy object disconnected
08-24 14:31:34.996  4761  4761 D A2dpProfile: Bluetooth service disconnected
,08-24 14:31:34.996  3217  3217 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-24 14:31:34.996  3217  3217 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-24 14:31:34.996  3217  3217 D HidService: Received stop request...Stopping profile...
08-24 14:31:34.996  3217  3217 D HidService: Stopping Bluetooth HidService
08-24 14:31:34.996  3217  3217 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-24 14:31:34.996  3217  3217 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-24 14:31:34.996  3217  3217 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-24 14:31:34.996  3217  3217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8e0de1
,08-24 14:31:34.996  3217  3217 D HealthService: Received stop request...Stopping profile...
08-24 14:31:34.996  3217  3217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8e0de1
,08-24 14:31:35.006  4761  4761 D BluetoothInputDevice: Proxy object disconnected
,08-24 14:31:35.006  4761  4761 D HidProfile: Bluetooth service disconnected
,08-24 14:31:35.006  3217  3217 D PanService: Received stop request...Stopping profile...
08-24 14:31:35.006  3217  3217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8e0de1
,08-24 14:31:35.006  1018  1018 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-24 14:31:35.006  4761  4761 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-24 14:31:35.006  4761  4761 D PanProfile: Bluetooth service disconnected
,08-24 14:31:35.006  3217  3217 D BluetoothMapService: Received stop request...Stopping profile...
,08-24 14:31:35.006  3217  3217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8e0de1
,08-24 14:31:35.006  4761  4761 D BluetoothMap: Proxy object disconnected
08-24 14:31:35.006  4761  4761 D MapProfile: Bluetooth service disconnected
,08-24 14:31:35.016  3217  3217 D SapService: Received stop request...Stopping profile...
08-24 14:31:35.016  3217  3217 D SapService: Stopping Bluetooth SapService
08-24 14:31:35.016  3217  3217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8e0de1
,08-24 14:31:35.016  1353  1353 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-24 14:31:35.016  3217  3217 E BluetoothAdapterService(764284385): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,08-24 14:31:35.016  3217  3217 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-24 14:31:35.016  1018  1046 D Tethering: interfaceLinkStateChanged p2p0, false
08-24 14:31:35.016  3217  3217 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-24 14:31:35.016  3217  3217 D BluetoothA2dp: Proxy object disconnected
08-24 14:31:35.016  3217  3217 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-24 14:31:35.016  1018  1046 D Tethering: interfaceStatusChanged p2p0, false
08-24 14:31:35.016  3217  3374 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-24 14:31:35.016  3217  3217 I GKI_LINUX: GKI_exit_task 2 done
,08-24 14:31:35.016  3217  3217 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-24 14:31:35.016  3217  3217 E BluetoothAdapterService(764284385): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-24 14:31:35.016  3217  3217 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-24 14:31:35.016  3217  3217 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-24 14:31:35.016  3217  3217 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-24 14:31:35.016  3217  3217 E BluetoothAdapterService(764284385): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-24 14:31:35.016  3217  3217 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-24 14:31:35.016  3217  3217 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-24 14:31:35.016  3217  3217 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-24 14:31:35.016  3217  3217 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-24 14:31:35.016  3217  3217 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-24 14:31:35.016  3217  3217 E BluetoothAdapterService(764284385): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-24 14:31:35.016  3217  3217 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-24 14:31:35.016  3217  3217 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-24 14:31:35.016  3217  3217 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-24 14:31:35.016  3217  3217 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-24 14:31:35.016  3217  3217 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-24 14:31:35.016  4761  4761 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-24 14:31:35.016  4761  4761 D SapProfile: Bluetooth service disconnected
,08-24 14:31:35.026  1018  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-24 14:31:35.026  3217  3217 E BluetoothAdapterService(764284385): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-24 14:31:35.026  3217  3217 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-24 14:31:35.026  3217  3217 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-24 14:31:35.026  3217  3217 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-24 14:31:35.026  3217  3217 E BluetoothAdapterService(764284385): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-24 14:31:35.026  3217  3217 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,08-24 14:31:35.026  3217  3217 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-24 14:31:35.026  3217  3217 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-24 14:31:35.026  3217  3290 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-24 14:31:35.026  3217  3290 D BluetoothAdapterProperties: Setting state to 10
08-24 14:31:35.026  3217  3290 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-24 14:31:35.026  3217  3290 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-24 14:31:35.026  3217  3290 D BluetoothAdapterService: updateAdapterState state is 10
,08-24 14:31:35.026  3217  3290 D BluetoothAdapterService: Autoconnection is available 
,08-24 14:31:35.026  3217  3290 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-24 14:31:35.026  3217  3290 I BluetoothAdapterState: Entering OffState
,08-24 14:31:35.036  1466  7004 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-24 14:31:35.036  1466  7004 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-24 14:31:35.036  4761  4773 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-24 14:31:35.046  3217  7500 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-24 14:31:35.046  3217  7500 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-24 14:31:35.046  4761  4770 D BluetoothPbap: onBluetoothStateChange: up=false
,08-24 14:31:35.046  1442  1462 D BluetoothAdapter: onBluetoothStateChange: up=false
08-24 14:31:35.046  1442  1462 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-24 14:31:35.046  1179  1896 D BluetoothAdapter: onBluetoothStateChange: up=false
08-24 14:31:35.046  1179  1896 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-24 14:31:35.046  1353  1353 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,08-24 14:31:35.046  1353  1353 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-24 14:31:35.046  1353  1353 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-24 14:31:35.046  1353  1353 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-24 14:31:35.046  1353  1353 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-24 14:31:35.046  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false
08-24 14:31:35.046  1018  1046 D Tethering: interfaceStatusChanged wlan0, false
08-24 14:31:35.046  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-24 14:31:35.046  1018  1132 D Tethering: InitialState.processMessage what=4
,08-24 14:31:35.046  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false
,08-24 14:31:35.046  1018  1046 D Tethering: interfaceStatusChanged wlan0, false
,08-24 14:31:35.056  1018  1132 E Tethering: No numeric data
,08-24 14:31:35.056  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-24 14:31:35.056  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false
08-24 14:31:35.056  1018  1046 D Tethering: interfaceStatusChanged wlan0, false
,08-24 14:31:35.056  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-24 14:31:35.056  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false
,08-24 14:31:35.056  4761  4773 D Bluetoothsap: onBluetoothStateChange: up=false
08-24 14:31:35.056  4761  4773 D Bluetoothsap: Unbinding service...
,08-24 14:31:35.056  1018  1046 D Tethering: interfaceStatusChanged wlan0, false
08-24 14:31:35.056  1018  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-24 14:31:35.056  1018  1132 D Tethering: clearTetheredNotification()
,08-24 14:31:35.056  4761  4770 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-24 14:31:35.056  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-24 14:31:35.066  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit,
08-24 14:31:35.066  1018  1126 V NetworkStats: performPollLocked(flags=0x1)
,08-24 14:31:35.066  1018  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-24 14:31:35.066  1018  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-24 14:31:35.066  1179  1179 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-24 14:31:35.066  1179  1179 D HotspotTile: updateTetherState():false, false
,08-24 14:31:35.066  4761  4773 D BluetoothAdapter: onBluetoothStateChange: up=false
08-24 14:31:35.066  4761  4773 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-24 14:31:35.066  1018  1126 V NetworkStats: performPollLocked() took 7ms
08-24 14:31:35.066  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 14:31:35.066  1755  1774 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-24 14:31:35.066  1755  1774 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-24 14:31:35.076  1453  6235 D BluetoothAdapter: onBluetoothStateChange: up=false
08-24 14:31:35.076  1453  6235 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-24 14:31:35.076  1466  1466 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-24 14:31:35.076  1018  1048 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-24 14:31:35.076  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 14:31:35.076  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 14:31:35.076  7162  7162 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-24 14:31:35.076  3217  3351 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-24 14:31:35.076  1466  1466 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-24 14:31:35.076  4761  4770 D BluetoothMap: onBluetoothStateChange: up=false
08-24 14:31:35.076  1466  1466 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-24 14:31:35.076  2653  2711 D BluetoothAdapter: onBluetoothStateChange: up=false
08-24 14:31:35.076  2653  2711 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-24 14:31:35.076  1466  1466 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-24 14:31:35.076  1466  1466 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-24 14:31:35.086  7162  7177 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-24 14:31:35.086  7162  7177 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-24 14:31:35.086  1466  1466 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-24 14:31:35.086  7162  7177 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-24 14:31:35.086  7162  7177 D BluetoothLeAdvertiser: Exit stop advertising
08-24 14:31:35.086  7162  7177 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-24 14:31:35.086  7162  7177 D BluetoothLeScanner: Exiting stopAllScan
08-24 14:31:35.086  1018  1048 D BluetoothAdapter: onBluetoothStateChange: up=false
08-24 14:31:35.086  1018  1048 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-24 14:31:35.086  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-24 14:31:35.086  1018  1018 I InputMethodManagerService: [BT Setting State] State =10
08-24 14:31:35.086  1018  1018 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-24 14:31:35.086  1466  1466 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-24 14:31:35.096  1179  1179 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-24 14:31:35.096  1179  1179 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:35.096  1179  1179 D BluetoothTile:  getBluetoothState : 10
,08-24 14:31:35.096  1466  1466 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-24 14:31:35.096  1466  1466 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-24 14:31:35.096  1874  1874 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-24 14:31:35.096  1466  1466 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-24 14:31:35.096  1466  1466 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-24 14:31:35.096  4761  4761 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-24 14:31:35.096  1466  1466 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-24 14:31:35.096  1018  1137 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-24 14:31:35.096  1466  1466 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-24 14:31:35.106  1018  3812 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-24 14:31:35.106  1466  1466 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-24 14:31:35.106  1466  1466 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-24 14:31:35.106  1179  1179 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-24 14:31:35.106  7162  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 14:31:35.106  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:31:35.106  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:35.106  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:31:35.106  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 14:31:35.106  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:31:35.106  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:31:35.106  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:31:35.106  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 14:31:35.106  1466  1466 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-24 14:31:35.106  1466  1466 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-24 14:31:35.106  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:35.106  1466  1466 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-24 14:31:35.106  1466  1466 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-24 14:31:35.116  1466  1466 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-24 14:31:35.116  1466  1466 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-24 14:31:35.116  1466  1466 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-24 14:31:35.116  1466  1466 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-24 14:31:35.116  1466  1466 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-24 14:31:35.116  1466  1466 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-24 14:31:35.116  1466  1466 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-24 14:31:35.116  1466  1466 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-24 14:31:35.126  1179  1179 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-24 14:31:35.126   257   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-24 14:31:35.126  1466  1466 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-24 14:31:35.126   257   518 W Vold    : Returning OperationFailed - no handler for errno 0
08-24 14:31:35.126  1466  1466 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-24 14:31:35.126  7526  7550 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-24 14:31:35.126  1466  1466 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-24 14:31:35.136   257   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-24 14:31:35.136   257   518 W Vold    : Returning OperationFailed - no handler for errno 0
,08-24 14:31:35.136  7526  7550 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-24 14:31:35.166  1353  1353 I wpa_supplicant: Blacklist: Clear (all) 
,08-24 14:31:35.246  1353  1353 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-24 14:31:35.246  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false,
08-24 14:31:35.246  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-24 14:31:35.246  1018  1046 D Tethering: interfaceStatusChanged wlan0, false
,08-24 14:31:35.296  7526  7526 D StrictMode: StrictMode policy violation; ~duration=157 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at java.io.File.exists(File.java:363)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-24 14:31:35.296  7526  7526 D StrictMode: StrictMode policy violation; ~duration=156 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-24 14:31:35.296  7526  7526 D StrictMode: StrictMode policy violation; ~duration=154 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-24 14:31:35.296  7526  7526 D StrictMode: StrictMode policy violation; ~duration=153 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.q.e.b(PG:170)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-24 14:31:35.296  7526  7526 D StrictMode: StrictMode policy violation; ~duration=150 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.q.k.d(PG:583)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.q.e.b(PG:170)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-24 14:31:35.296  7526  7526 D StrictMode: StrictMode policy violation; ~duration=130 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at java.io.File.exists(File.java:363)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-24 14:31:35.296  7526  7526 D StrictMode: StrictMode policy violation; ~duration=129 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at java.io.File.exists(File.java:363)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-24 14:31:35.296  7526  7526 D StrictMode: StrictMode policy violation; ~duration=129 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 14:31:35.296  7526  7526 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-24 14:31:35.306  1018  1449 I ActivityManager: Killing 7037:com.google.android.partnersetup/u0a14 (adj 15): empty #21
08-24 14:31:35.306  1018  1031 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-24 14:31:35.306  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:35.306  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-24 14:31:35.306  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:35.306  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-24 14:31:35.316  1628  1628 I Hs20UtilService: Starting #8
08-24 14:31:35.316  4761  4761 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-24 14:31:35.316  1628  1673 I Hs20UtilService: Message received 5007
08-24 14:31:35.326  4761  4761 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-24 14:31:35.326  4761  4761 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-24 14:31:35.326  4761  4761 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-24 14:31:35.326  4761  4761 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-24 14:31:35.326  4761  4761 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-24 14:31:35.326  4761  4844 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-24 14:31:35.346  4761  4761 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-24 14:31:35.346  4761  4761 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-24 14:31:35.346  4761  4761 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-24 14:31:35.346  4761  4761 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-24 14:31:35.346  4761  4761 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-24 14:31:35.346  4761  4761 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-24 14:31:35.346  4761  4844 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-24 14:31:35.346  1018  3812 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
08-24 14:31:35.356  1018  3812 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:35.356  1018  3812 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:35.356  1018  3812 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:35.356  1018  3812 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:35.366  7526  7568 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
08-24 14:31:35.366  7571  7571 I libpersona: KNOX_SDCARD checking this for 10064
08-24 14:31:35.366  7571  7571 E Zygote  : MountEmulatedStorage()
08-24 14:31:35.366  7571  7571 I libpersona: KNOX_SDCARD not a persona
08-24 14:31:35.366  7571  7571 E Zygote  : v2
08-24 14:31:35.366  1018  3812 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7571 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-24 14:31:35.366  7571  7571 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 14:31:35.366  7571  7571 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-24 14:31:35.376  7571  7571 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-24 14:31:35.376  1018  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-24 14:31:35.376  1018  1129 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-24 14:31:35.376  1179  1179 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-24 14:31:35.376  1179  1179 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-24 14:31:35.376  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 14:31:35.376  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-24 14:31:35.376  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:35.376  1179  1179 D HotspotTile: onReceive : 1, 0
08-24 14:31:35.376  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:35.376  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:35.376  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:35.376  1179  1179 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-24 14:31:35.376  1179  1179 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-24 14:31:35.386  1179  1753 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-24 14:31:35.386  1018  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-24 14:31:35.386  4761  4761 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-24 14:31:35.386  1755  2188 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 14:31:35.396  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:35.396  1018  1018 I ApplicationPolicy: updateDataUsageMap
,08-24 14:31:35.396  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:35.406  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:35.406  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:35.416  7571  7571 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:31:35.416  7571  7571 D ActivityThread: Added TimaKeyStore provider
,08-24 14:31:35.416  1018  1491 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 14:31:35.416  1018  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:35.416  1018  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:35.416  1018  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-24 14:31:35.436  7571  7571 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-24 14:31:35.446  7571  7571 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-24 14:31:35.456  7571  7571 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-24 14:31:35.466  1018  1043 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-24 14:31:35.486  7571  7571 D FileShare-Client: Outbound.stopDelayTimer - 
,08-24 14:31:35.486  1018  1449 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-24 14:31:35.486  1018  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:35.486  1018  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:35.486  1018  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:35.486  1018  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:35.496  7588  7588 E Zygote  : MountEmulatedStorage(),
08-24 14:31:35.496  1018  1449 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7588 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-24 14:31:35.496  7588  7588 E Zygote  : v2
08-24 14:31:35.496  7588  7588 I libpersona: KNOX_SDCARD checking this for 10065
08-24 14:31:35.496  7588  7588 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 14:31:35.496  7588  7588 I libpersona: KNOX_SDCARD not a persona
,08-24 14:31:35.496  1018  1449 I ActivityManager: Killing 7074:com.sec.pcw.device/1000 (adj 15): empty #21
,08-24 14:31:35.506  7588  7588 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-24 14:31:35.506  7588  7588 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 14:31:35.516  7588  7588 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:31:35.516  7588  7588 D ActivityThread: Added TimaKeyStore provider
,08-24 14:31:35.536  7588  7588 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-24 14:31:35.536  1018  3812 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:35.536  1018  3812 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:35.536  1018  3812 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
08-24 14:31:35.536  1018  3812 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,08-24 14:31:35.546  1018  3812 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-24 14:31:35.546  1018  3812 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:35.546  1018  3812 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:35.546  1018  3812 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:35.556  7603  7603 E Zygote  : MountEmulatedStorage()
,08-24 14:31:35.556  7603  7603 E Zygote  : v2
08-24 14:31:35.556  7603  7603 I libpersona: KNOX_SDCARD checking this for 10102
08-24 14:31:35.556  7603  7603 I libpersona: KNOX_SDCARD not a persona
,08-24 14:31:35.556  7603  7603 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 14:31:35.556  7603  7603 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 14:31:35.556  1018  3812 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7603 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
08-24 14:31:35.556  7603  7603 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-24 14:31:35.556  1018  3812 I ActivityManager: Killing 6949:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,08-24 14:31:35.576  7603  7603 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:31:35.576  7603  7603 D ActivityThread: Added TimaKeyStore provider
,08-24 14:31:35.596  7603  7603 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-24 14:31:35.696   288   288 E SMD     : DCD OFF
,08-24 14:31:35.806   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
08-24 14:31:35.806  7603  7623 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
08-24 14:31:35.806  7603  7623 I Babel_SMS: MmsConfig.loadMmsSettings
08-24 14:31:35.806  7603  7623 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
08-24 14:31:35.806  7603  7623 I Babel_SMS: MmsConfig.loadFromDatabase
,08-24 14:31:35.826  7603  7623 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-24 14:31:35.826  7603  7623 I Babel_SMS: MmsConfig.loadFromResources
,08-24 14:31:35.826  7603  7623 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-24 14:31:35.826  7603  7623 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-24 14:31:35.846  1018  1030 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-24 14:31:35.846  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-24 14:31:35.846  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:35.846  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-24 14:31:35.846  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-24 14:31:35.866  7603  7603 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 14:31:35.866  7603  7603 I Babel_Crash: startup - clean
,08-24 14:31:35.896  1018  3812 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
08-24 14:31:35.896  1018  3812 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-24 14:31:35.906  1018  3812 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:35.906  1018  3812 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-24 14:31:35.906  1018  3812 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-24 14:31:35.906  4761  4761 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-24 14:31:35.906  4761  4761 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-24 14:31:35.906  1628  1628 I Hs20UtilService: Starting #9
08-24 14:31:35.906  1628  1673 I Hs20UtilService: Message received 5007
,08-24 14:31:35.906  4761  4761 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-24 14:31:35.906  4761  4761 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-24 14:31:35.906  4761  4761 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-24 14:31:35.906  4761  4761 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-24 14:31:35.916  4761  4844 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-24 14:31:35.916  1018  1046 D Tethering: interfaceRemoved wlan0
,08-24 14:31:35.916  1018  1046 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-24 14:31:35.926  7603  7603 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-24 14:31:35.926  1018  1217 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-24 14:31:35.926  1018  1217 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-24 14:31:35.926  1018  1217 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:35.926  1018  1217 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:35.926  1018  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-24 14:31:35.926  1628  1628 I Hs20UtilService: Starting #10
08-24 14:31:35.926  1628  1673 I Hs20UtilService: Message received 5011
,08-24 14:31:35.926  7603  7603 W AudioCapabilities: Unsupported mime audio/evrc
,08-24 14:31:35.926  7603  7603 W AudioCapabilities: Unsupported mime audio/qcelp
,08-24 14:31:35.936  1018  1030 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,08-24 14:31:35.936  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:35.936  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:35.936  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:35.936  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:35.936  7603  7603 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-24 14:31:35.936  7603  7603 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-24 14:31:35.946  7603  7603 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-24 14:31:35.946  7626  7626 E Zygote  : MountEmulatedStorage()
,08-24 14:31:35.956  7626  7626 E Zygote  : v2
08-24 14:31:35.956  7626  7626 I libpersona: KNOX_SDCARD checking this for 1000
08-24 14:31:35.956  7626  7626 I libpersona: KNOX_SDCARD not a persona
,08-24 14:31:35.956  7626  7626 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 14:31:35.956  7626  7626 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-24 14:31:35.956  1018  1030 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=7626 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-24 14:31:35.956  7626  7626 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 14:31:35.956  7603  7603 W AudioCapabilities: Unsupported mime audio/x-ima
,08-24 14:31:35.966  7603  7603 W AudioCapabilities: Unsupported mime audio/qcelp
,08-24 14:31:35.966  7603  7603 W AudioCapabilities: Unsupported mime audio/evrc
,08-24 14:31:35.996  7603  7603 W VideoCapabilities: Unsupported mime video/wvc1
08-24 14:31:35.996  7626  7626 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:31:35.996  7626  7626 D ActivityThread: Added TimaKeyStore provider
08-24 14:31:35.996  7603  7603 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-24 14:31:36.016  7603  7603 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-24 14:31:36.016  7603  7603 W VideoCapabilities: Unsupported mime video/wvc1
,08-24 14:31:36.016  7603  7603 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-24 14:31:36.016  7603  7603 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-24 14:31:36.026  7603  7603 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-24 14:31:36.026  7603  7603 W VideoCapabilities: Unsupported mime video/mp43
,08-24 14:31:36.026  7603  7603 W VideoCapabilities: Unsupported mime video/sorenson
,08-24 14:31:36.036  7626  7626 D SecurityLogAgent: KnoxConfiguration : Current State = 1,
08-24 14:31:36.036  7626  7626 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-24 14:31:36.036  7626  7626 D SecurityLogAgent: StateMachine : Current State = 1
08-24 14:31:36.036  7603  7603 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-24 14:31:36.036  1018  1046 D Tethering: interfaceRemoved p2p0
08-24 14:31:36.036  1018  1046 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-24 14:31:36.036  7626  7626 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-24 14:31:36.036  1018  1031 I ActivityManager: Killing 7137:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
,08-24 14:31:36.046  1018  1449 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:36.046  1018  1449 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:36.046  1018  1449 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-24 14:31:36.046  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:36.046  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:36.046  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-24 14:31:36.056  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:36.056  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:36.056  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-24 14:31:36.056  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:36.056  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-24 14:31:36.056  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-24 14:31:36.056  7603  7603 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-24 14:31:36.056  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:36.056  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:36.056  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-24 14:31:36.066  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:36.066  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-24 14:31:36.066  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-24 14:31:36.066  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:36.066  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:36.066  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-24 14:31:36.076  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:36.076  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:36.076  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-24 14:31:36.076  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:36.076  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:36.076  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-24 14:31:36.076  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:36.076  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:36.076  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-24 14:31:36.086  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:36.086  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:36.086  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-24 14:31:36.086  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:36.086  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:36.086  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-24 14:31:36.086  7603  7603 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-24 14:31:36.086  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:36.086  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:36.086  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-24 14:31:36.086  7603  7603 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-24 14:31:36.086  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:36.086  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:36.086  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-24 14:31:36.096  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:36.096  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:36.096  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-24 14:31:36.096  7603  7603 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-24 14:31:36.096  4761  4761 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-24 14:31:36.096  1018  1030 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-24 14:31:36.096  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-24 14:31:36.096  7603  7603 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-24 14:31:36.106  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:36.106  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:36.106  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-24 14:31:36.106  4761  4761 D DockEventReceiver: finishStartingService: stopping service
,08-24 14:31:36.106  1018  3813 I ActivityManager: Killing 7179:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21,
,08-24 14:31:36.116  7603  7603 I vclib   : onServiceConnected
,08-24 14:31:36.116  2653  2653 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 14:31:36.116  4761  4761 D BluetoothNotiBroadcastReceiver: onReceive
,08-24 14:31:36.116  1179  1179 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-24 14:31:36.116  1179  1179 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-24 14:31:36.136  1018  1031 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-24 14:31:36.136  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-24 14:31:36.136  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:36.136  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:36.136  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-24 14:31:36.136  1628  1628 I Hs20UtilService: Starting #11
08-24 14:31:36.136  1628  1673 I Hs20UtilService: Message received 5011
,08-24 14:31:36.136  7626  7626 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-24 14:31:36.136  7626  7626 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-24 14:31:36.136  7626  7626 D SecurityLogAgent: StateMachine : Current State = 1
08-24 14:31:36.136  7626  7626 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-24 14:31:36.146  1018  1492 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-24 14:31:36.146  1018  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:36.146  1018  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:36.146  1018  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:36.146  1018  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:36.156  7644  7644 E Zygote  : MountEmulatedStorage()
08-24 14:31:36.156  7644  7644 I libpersona: KNOX_SDCARD checking this for 1000
08-24 14:31:36.156  7644  7644 E Zygote  : v2
08-24 14:31:36.156  7644  7644 I libpersona: KNOX_SDCARD not a persona
08-24 14:31:36.156  7644  7644 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 14:31:36.166  1018  1492 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7644 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-24 14:31:36.166  7644  7644 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 14:31:36.166  7644  7644 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 14:31:36.176  7644  7644 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:31:36.176  7644  7644 D ActivityThread: Added TimaKeyStore provider
,08-24 14:31:36.186   305   305 I art     : Explicit concurrent mark sweep GC freed 8741(372KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 896us total 25.152ms
,08-24 14:31:36.206   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 683us total 17.158ms
,08-24 14:31:36.206  7644  7644 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-24 14:31:36.206  7644  7644 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-24 14:31:36.206  7644  7644 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-24 14:31:36.216  7644  7644 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-24 14:31:36.216  7644  7644 I PCWCLIENTTRACE_PushUtil: sales region : global
08-24 14:31:36.216  7644  7644 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-24 14:31:36.216  7644  7644 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-24 14:31:36.216   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 683us total 17.611ms
,08-24 14:31:36.226  1018  1137 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
,08-24 14:31:36.226  1018  1137 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
08-24 14:31:36.226  1018  1137 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
08-24 14:31:36.226  1018  1137 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,08-24 14:31:36.226  1018  1137 I ActivityManager: Killing 7210:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
,08-24 14:31:36.226  7644  7659 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,08-24 14:31:36.226  1018  1018 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
08-24 14:31:36.236  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:36.236  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:36.236  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:36.236  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:36.246  7661  7661 E Zygote  : MountEmulatedStorage()
08-24 14:31:36.246  7661  7661 E Zygote  : v2
08-24 14:31:36.246  7661  7661 I libpersona: KNOX_SDCARD checking this for 10001
,08-24 14:31:36.246  7661  7661 I libpersona: KNOX_SDCARD not a persona
,08-24 14:31:36.246  7661  7661 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 14:31:36.246  1018  1018 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7661 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-24 14:31:36.246  7661  7661 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-24 14:31:36.246  7661  7661 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 14:31:36.266  7661  7661 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:31:36.266  7661  7661 D ActivityThread: Added TimaKeyStore provider
,08-24 14:31:36.326  1018  1441 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-24 14:31:36.336  1018  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:36.336  1018  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:36.336  1018  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:36.336  1018  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:36.346  1018  1441 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7678 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-24 14:31:36.346  1018  1441 I ActivityManager: Killing 7061:com.android.mms/u0a41 (adj 15): empty #21
08-24 14:31:36.346  7678  7678 E Zygote  : MountEmulatedStorage()
08-24 14:31:36.346  7678  7678 E Zygote  : v2
08-24 14:31:36.346  7678  7678 I libpersona: KNOX_SDCARD checking this for 1000
08-24 14:31:36.346  7678  7678 I libpersona: KNOX_SDCARD not a persona
08-24 14:31:36.346  7678  7678 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 14:31:36.346  7678  7678 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 14:31:36.356  7678  7678 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 14:31:36.366  7678  7678 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:31:36.366  7678  7678 D ActivityThread: Added TimaKeyStore provider
,08-24 14:31:36.396  7678  7678 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-24 14:31:36.486  1018  1137 D CountryDetector: No listener is left
,08-24 14:31:36.516  7678  7678 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-24 14:31:36.526  7678  7678 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-24 14:31:36.526  7678  7678 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-24 14:31:36.526  7678  7678 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-24 14:31:36.526  7678  7678 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-24 14:31:36.526  7678  7678 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-24 14:31:36.536  1018  3813 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-24 14:31:36.536  1018  3813 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:36.536  1018  3813 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:36.536  1018  3813 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:36.536  1018  3813 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:36.546  7693  7693 E Zygote  : MountEmulatedStorage()
08-24 14:31:36.546  1018  3813 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7693 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-24 14:31:36.546  7693  7693 E Zygote  : v2
08-24 14:31:36.546  7693  7693 I libpersona: KNOX_SDCARD checking this for 10008
08-24 14:31:36.546  7693  7693 I libpersona: KNOX_SDCARD not a persona
08-24 14:31:36.546  1018  3813 I ActivityManager: Killing 7238:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,08-24 14:31:36.546  7693  7693 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 14:31:36.556  7693  7693 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 14:31:36.556  7693  7693 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-24 14:31:36.566  7693  7693 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:31:36.576  7693  7693 D ActivityThread: Added TimaKeyStore provider
,08-24 14:31:36.636  1018  3812 I ActivityManager: Killing 7250:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
,08-24 14:31:36.636  1018  1137 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-24 14:31:36.636  1018  1137 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-24 14:31:36.636  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:36.636  1018  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:36.636  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:36.656  1938  1938 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-24 14:31:36.656  1938  2846 I iu.UploadsManager: num queued entries: 0
,08-24 14:31:36.656  1938  2846 I iu.UploadsManager: num updated entries: 0
,08-24 14:31:36.656  1018  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-24 14:31:36.656  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,08-24 14:31:36.656  1938  2846 I iu.SyncManager: NEXT; no task
,08-24 14:31:36.656  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:36.656  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:36.656  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:36.666  1938  1938 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-24 14:31:36.676  1938  1938 I Kids    : [GCoreUtils] Current gmscore version, 8115234 is smaller than the required version 8400000
,08-24 14:31:36.676  2850  2850 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Aug 24 14:31:36 GMT+02:00 2016
,08-24 14:31:36.676  1018  1030 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-24 14:31:36.686  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-24 14:31:36.686  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:36.686  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:36.686  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-24 14:31:36.686  2850  2850 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-24 14:31:36.696  2850  2850 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-24 14:31:36.696  1018  1439 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-24 14:31:36.696  1018  1439 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:36.696  1018  1439 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:36.696  1018  1439 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:36.696  1018  1439 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:36.716  2850  2850 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-24 14:31:36.716  7710  7710 E Zygote  : MountEmulatedStorage()
08-24 14:31:36.716  7710  7710 E Zygote  : v2
,08-24 14:31:36.716  7710  7710 I libpersona: KNOX_SDCARD checking this for 10031
08-24 14:31:36.716  7710  7710 I libpersona: KNOX_SDCARD not a persona
08-24 14:31:36.716  7710  7710 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 14:31:36.716  1018  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-24 14:31:36.716  7710  7710 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-24 14:31:36.716  7710  7710 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-24 14:31:36.716  1018  1439 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7710 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,08-24 14:31:36.726  2850  2850 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-24 14:31:36.726  2850  7709 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-24 14:31:36.726  2850  7709 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-24 14:31:36.736  2850  7709 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-24 14:31:36.736  2850  7709 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-24 14:31:36.746  7710  7710 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:31:36.746  2850  2850 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
08-24 14:31:36.746  7710  7710 D ActivityThread: Added TimaKeyStore provider
,08-24 14:31:36.776  7710  7710 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-24 14:31:36.786  1018  1439 I ActivityManager: Killing 7280:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,08-24 14:31:36.796  1018  1217 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-24 14:31:36.796  1018  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:36.796  1018  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:36.796  1018  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:36.796  1018  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:36.796  2786  7725 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,08-24 14:31:36.796  2786  7725 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-24 14:31:36.806   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-24 14:31:36.806  2786  7725 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,08-24 14:31:36.806  2786  7725 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,08-24 14:31:36.806  2786  7725 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... ,
,08-24 14:31:36.816  1018  1217 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7726 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-24 14:31:36.816  7726  7726 E Zygote  : MountEmulatedStorage(),
,08-24 14:31:36.816  7726  7726 E Zygote  : v2,
08-24 14:31:36.816  7726  7726 I libpersona: KNOX_SDCARD checking this for 10032
08-24 14:31:36.816  7726  7726 I libpersona: KNOX_SDCARD not a persona
,08-24 14:31:36.816  7726  7726 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-24 14:31:36.816  7726  7726 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-24 14:31:36.826  7726  7726 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
,08-24 14:31:36.846  7726  7726 D TimaKeyStoreProvider: TimaSignature is unavailable,
,08-24 14:31:36.846  7726  7726 D ActivityThread: Added TimaKeyStore provider
,08-24 14:31:36.886  7726  7741 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-24 14:31:36.896  7726  7741 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-24 14:31:36.896  7726  7741 D SPPClientService: PushLog.txt file is not deleted.
,08-24 14:31:36.896  7726  7726 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
08-24 14:31:36.896  7726  7741 D SPPClientService: PushLog.txt file is not deleted.
,08-24 14:31:36.896  7726  7741 D SPPClientService: ============PushLog. stop!
,08-24 14:31:36.906  1018  3813 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-24 14:31:36.906  1018  3813 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:36.906  1018  3813 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:36.906  1018  3813 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:36.906  1018  3813 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:36.916  7743  7743 E Zygote  : MountEmulatedStorage()
08-24 14:31:36.916  7743  7743 E Zygote  : v2
08-24 14:31:36.916  7743  7743 I libpersona: KNOX_SDCARD checking this for 10036
08-24 14:31:36.916  7743  7743 I libpersona: KNOX_SDCARD not a persona
,08-24 14:31:36.916  1018  3813 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7743 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-24 14:31:36.916  7743  7743 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 14:31:36.926  1018  3813 I ActivityManager: Killing 7301:com.wsomacp/u0a23 (adj 15): empty #21
,08-24 14:31:36.926  7743  7743 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 14:31:36.926  7743  7743 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-24 14:31:36.926  1018  1137 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
08-24 14:31:36.926  1018  1137 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
08-24 14:31:36.936  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:36.936  1018  1137 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-24 14:31:36.936  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push,
,08-24 14:31:36.966  7743  7743 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:31:36.966  7743  7743 D ActivityThread: Added TimaKeyStore provider
,08-24 14:31:36.976  7726  7751 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-24 14:31:37.026  7743  7743 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@3768c02e
,08-24 14:31:37.036  1018  1097 V AlarmManager: waitForAlarm result :4
,08-24 14:31:37.036  7743  7743 I SA      : [SSP] onCreated
,08-24 14:31:37.056  7743  7743 I SA      : [TPM] There is no property file
,08-24 14:31:37.056  7743  7743 I SA      : [SCU] isHaveSA() - false
,08-24 14:31:37.056  7743  7743 I SA      : [TPM] getModelProperty : null
,08-24 14:31:37.066  7743  7743 I SA      : [TPM] getCSCProperty : null
,08-24 14:31:37.066  7743  7743 I SA      : [DM] FLOATING AMOLED FEATURE: true
,08-24 14:31:37.066  7743  7743 I SA      : [DM] PRODUCT AMOLED FEATURE: false
,08-24 14:31:37.066  7743  7743 I SA      : [DM] TFT FEATURE: false
,08-24 14:31:37.066  7743  7743 I SA      : [DM] init START
,08-24 14:31:37.076  7743  7743 I SA      : [DM] This device is not a Vodafone
,08-24 14:31:37.076  7743  7743 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,08-24 14:31:37.086  7743  7743 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,08-24 14:31:37.086  7743  7743 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,08-24 14:31:37.086  7743  7743 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,08-24 14:31:37.086  7743  7743 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,08-24 14:31:37.086  7743  7743 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,08-24 14:31:37.086  7743  7743 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-24 14:31:37.086  7743  7743 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-24 14:31:37.096  7743  7743 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,08-24 14:31:37.096  7743  7743 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,08-24 14:31:37.096  7743  7743 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,08-24 14:31:37.096  7743  7743 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,08-24 14:31:37.096  7743  7743 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,08-24 14:31:37.096  7743  7743 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
,08-24 14:31:37.096  7743  7743 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
,08-24 14:31:37.096  7743  7743 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,08-24 14:31:37.106  7743  7743 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
,08-24 14:31:37.106  7743  7743 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,08-24 14:31:37.106  7743  7743 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,08-24 14:31:37.106  7743  7743 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,08-24 14:31:37.106  7743  7743 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,08-24 14:31:37.106  7743  7743 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,08-24 14:31:37.106  7743  7743 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,08-24 14:31:37.106  7743  7743 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,08-24 14:31:37.106  7743  7743 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,08-24 14:31:37.116  7743  7743 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,08-24 14:31:37.116  7743  7743 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
,08-24 14:31:37.116  7743  7743 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-24 14:31:37.116  7743  7743 I SA      : [SCU] isHaveSA() - false
,08-24 14:31:37.116  7743  7743 I SA      : support phone number id : false
,08-24 14:31:37.116  7743  7743 I SA      : [DM] Supports Ref Jpn : true
,08-24 14:31:37.116  7743  7743 I SA      : [DM] init END
08-24 14:31:37.116  7743  7743 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-24 14:31:37.126  7743  7743 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,08-24 14:31:37.126  7743  7743 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-24 14:31:37.136  7743  7743 I SA      : [SLFUCHKMGR] constructor called
,08-24 14:31:37.136  7743  7743 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-24 14:31:37.136  7743  7743 I SA      : [OR] == isSIMCardReady false ==
,08-24 14:31:37.136  7743  7743 I SA      : [SCU] == networkStateCheck == false
,08-24 14:31:37.146  7743  7743 I SA      : [OR] onReceive END
,08-24 14:31:37.146  1018  1439 I ActivityManager: Killing 7344:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
,08-24 14:31:37.146  1231  1231 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-24 14:31:37.156  1803  1803 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-24 14:31:37.166  2634  2642 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,08-24 14:31:37.166  1803  1803 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,08-24 14:31:37.166  1803  1803 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,08-24 14:31:37.166  1803  1803 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
08-24 14:31:37.166  1803  1803 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-24 14:31:37.176  1803  1803 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-24 14:31:37.176  1803  1803 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-24 14:31:37.176  1018  1492 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-24 14:31:37.176  1018  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:37.176  1018  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:37.176  1018  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:37.176  1018  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:37.196  1018  1492 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7765 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-24 14:31:37.196  7765  7765 E Zygote  : MountEmulatedStorage()
08-24 14:31:37.196  7765  7765 E Zygote  : v2
08-24 14:31:37.196  7765  7765 I libpersona: KNOX_SDCARD checking this for 10077
08-24 14:31:37.196  7765  7765 I libpersona: KNOX_SDCARD not a persona
,08-24 14:31:37.196  7765  7765 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 14:31:37.206  7765  7765 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-24 14:31:37.206  7765  7765 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL,
,08-24 14:31:37.216  7765  7765 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:31:37.216  7765  7765 D ActivityThread: Added TimaKeyStore provider
,08-24 14:31:37.396  1018  1217 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-24 14:31:37.396  1018  1217 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-24 14:31:37.396  1018  1217 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:37.396  1018  1217 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:37.396  1018  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-24 14:31:37.396  1018  3812 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-24 14:31:37.396  1018  3812 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:37.396  1018  3812 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:37.396  1018  3812 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:37.396  1018  3812 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:37.416  7783  7783 E Zygote  : MountEmulatedStorage(),
,08-24 14:31:37.416  7783  7783 E Zygote  : v2
08-24 14:31:37.416  7783  7783 I libpersona: KNOX_SDCARD checking this for 10110
08-24 14:31:37.416  7783  7783 I libpersona: KNOX_SDCARD not a persona
,08-24 14:31:37.416  7783  7783 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 14:31:37.416  1018  3812 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7783 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-24 14:31:37.416  7783  7783 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 14:31:37.416  1018  1492 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-24 14:31:37.416  1018  1492 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-24 14:31:37.416  1018  1492 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:37.416  1018  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:37.416  1018  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
08-24 14:31:37.416  7783  7783 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-24 14:31:37.426  7603  7782 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-24 14:31:37.436  1018  1030 I ActivityManager: Killing 7365:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,08-24 14:31:37.446  7783  7783 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:31:37.446  7783  7783 D ActivityThread: Added TimaKeyStore provider
,08-24 14:31:37.576  1018  1449 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-24 14:31:37.656  1018  3812 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-24 14:31:37.656  1018  3812 D WifiService: setWifiEnabled: true pid=7162, uid=10170
08-24 14:31:37.656  1018  3812 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-24 14:31:37.656  1018  3812 W ActivityManager: Permission Denial: getCurrentUser() from pid=7162, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-24 14:31:37.656  1018  3812 D SecContentProvider2: mCursor = null
08-24 14:31:37.656  1018  3812 W WifiService: Failed getting userId using ActivityManagerNative
08-24 14:31:37.656  1018  3812 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7162, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-24 14:31:37.656  1018  3812 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-24 14:31:37.656  1018  3812 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-24 14:31:37.656  1018  3812 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-24 14:31:37.656  1018  3812 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-24 14:31:37.656  1018  3812 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-24 14:31:37.656  1018  3812 D SettingsProvider: name = wifi_on
,08-24 14:31:37.666  1018  1129 E WifiHW  : ##################### set firmware type 0 #####################,
,08-24 14:31:37.696   257   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-24 14:31:37.696   257   518 W Vold    : Returning OperationFailed - no handler for errno 0
,08-24 14:31:37.696  7783  7802 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-24 14:31:37.696   257   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-24 14:31:37.696   257   518 W Vold    : Returning OperationFailed - no handler for errno 0
,08-24 14:31:37.706  7783  7802 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-24 14:31:37.716   257   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-24 14:31:37.716   257   518 W Vold    : Returning OperationFailed - no handler for errno 0
,08-24 14:31:37.716  7783  7803 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-24 14:31:37.716   257   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-24 14:31:37.716   257   518 W Vold    : Returning OperationFailed - no handler for errno 0
,08-24 14:31:37.716  7783  7803 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-24 14:31:37.756  7783  7783 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-24 14:31:37.756  7783  7783 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-24 14:31:37.756  7783  7783 I GAv4    :   adb logcat -s GAv4
,08-24 14:31:37.786  7783  7783 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-24 14:31:37.786  1018  1439 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-24 14:31:37.806  7783  7783 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-24 14:31:37.816  7783  7805 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-24 14:31:38.056  1018  1441 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 14:31:38.066  1018  1441 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:38.066  1018  1441 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:38.066  1018  1441 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-24 14:31:38.096  7783  7783 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-24 14:31:38.116  1018  1046 D Tethering: interfaceAdded wlan0
,08-24 14:31:38.116  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false
08-24 14:31:38.116  1018  1046 D Tethering: interfaceStatusChanged wlan0, false
08-24 14:31:38.116  7783  7783 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 432-434)
08-24 14:31:38.116  7783  7783 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-24 14:31:38.116  1018  1132 E Tethering: No numeric data
,08-24 14:31:38.116  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-24 14:31:38.116  1018  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-24 14:31:38.126  1018  1126 V NetworkStats: performPollLocked(flags=0x1)
08-24 14:31:38.126  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 14:31:38.126  1179  1179 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-24 14:31:38.126  1179  1179 D HotspotTile: updateTetherState():false, false
,08-24 14:31:38.126  1018  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-24 14:31:38.126  1018  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-24 14:31:38.126  1018  1046 D Tethering: interfaceAdded p2p0
,08-24 14:31:38.126  1018  1046 D Tethering: p2p0 is not a tetherable iface, ignoring
08-24 14:31:38.126  1018  1132 D Tethering: clearTetheredNotification()
,08-24 14:31:38.126  1018  1132 D Tethering: InitialState.processMessage what=4
08-24 14:31:38.126  1018  1126 V NetworkStats: performPollLocked() took 4ms
,08-24 14:31:38.126  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 14:31:38.126  1018  1132 E Tethering: No numeric data
,08-24 14:31:38.126  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 14:31:38.126  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 14:31:38.126  1018  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-24 14:31:38.126  1018  1132 D Tethering: clearTetheredNotification()
,08-24 14:31:38.126  1018  1046 D Tethering: interfaceLinkStateChanged p2p0, false
08-24 14:31:38.126  1018  1046 D Tethering: interfaceStatusChanged p2p0, false
08-24 14:31:38.126  1018  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-24 14:31:38.136  1018  1126 V NetworkStats: performPollLocked(flags=0x1)
08-24 14:31:38.136  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 14:31:38.136   278   983 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,08-24 14:31:38.136   278   983 D SoftapController: Softap fwReload - Ok
,08-24 14:31:38.136  1179  1179 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-24 14:31:38.136  1179  1179 D HotspotTile: updateTetherState():false, false
,08-24 14:31:38.136  1018  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-24 14:31:38.136  1018  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-24 14:31:38.136   278   983 D CommandListener: Setting iface cfg
08-24 14:31:38.136   278   983 D CommandListener: Trying to bring down wlan0
,08-24 14:31:38.136   278   983 D CommandListener: Clearing all IP addresses on wlan0
,08-24 14:31:38.136  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 14:31:38.136  1018  1126 V NetworkStats: performPollLocked() took 5ms
08-24 14:31:38.136  7783  7783 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {7503a1}
,08-24 14:31:38.136  7783  7783 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-24 14:31:38.136  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 14:31:38.136  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 14:31:38.136  7783  7783 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
08-24 14:31:38.136  1018  1129 E WifiHW  : supplicant_name : p2p_supplicant
,08-24 14:31:38.146  1018  1129 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-24 14:31:38.146  1018  1129 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,08-24 14:31:38.146  4761  4761 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-24 14:31:38.156  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-24 14:31:38.156  1179  1179 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-24 14:31:38.156  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 14:31:38.156  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-24 14:31:38.156  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:38.156  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:38.156  1179  1179 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-24 14:31:38.156  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:38.156  1179  1753 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-24 14:31:38.156  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:38.156  1179  1179 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-24 14:31:38.156  1179  1179 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-24 14:31:38.166  1179  1179 D HotspotTile: onReceive : 2, 0
08-24 14:31:38.166  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:38.166  7783  7783 I cr.BrowserStartup: Initializing chromium process, singleProcess=true,
,08-24 14:31:38.166  7783  7783 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-24 14:31:38.176  7783  7783 E SysUtils: ApplicationContext is null in ApplicationStatus,
,08-24 14:31:38.196  7783  7783 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-24 14:31:38.196  7783  7783 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-24 14:31:38.196  7783  7783 I Adreno-EGL: Build Date: 04/06/15 Mon
08-24 14:31:38.196  7783  7783 I Adreno-EGL: Local Branch: 
08-24 14:31:38.196  7783  7783 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-24 14:31:38.196  7783  7783 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-24 14:31:38.196  7783  7783 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-24 14:31:38.196  7829  7829 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-24 14:31:38.196  7829  7829 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-24 14:31:38.196  7829  7829 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-24 14:31:38.236  7829  7829 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
08-24 14:31:38.236   338   338 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7829
08-24 14:31:38.236   338   338 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
08-24 14:31:38.236  7829  7829 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running,
08-24 14:31:38.236  7829  7829 I wpa_supplicant: ssSupport state is = 1
08-24 14:31:38.236  7829  7829 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-24 14:31:38.236  7829  7829 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-24 14:31:38.236   338   338 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7829,
08-24 14:31:38.236   338   338 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,08-24 14:31:38.266  7783  7783 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-24 14:31:38.266  7783  7842 W cr.media: Requires BLUETOOTH permission,
,08-24 14:31:38.276  7783  7783 I NSApplication: Starting up...
,08-24 14:31:38.276  1018  3812 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-24 14:31:38.276  1018  1489 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output,
,08-24 14:31:38.286  1018  1449 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast,
,08-24 14:31:38.286  1018  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-24 14:31:38.286  1018  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:38.286  1018  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:38.286  1018  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:38.306  7847  7847 E Zygote  : MountEmulatedStorage()
,08-24 14:31:38.306  1018  1449 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7847 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-24 14:31:38.306  7847  7847 E Zygote  : v2
08-24 14:31:38.306  7847  7847 I libpersona: KNOX_SDCARD checking this for 10117
08-24 14:31:38.306  7847  7847 I libpersona: KNOX_SDCARD not a persona
,08-24 14:31:38.306  1018  1449 I ActivityManager: Killing 7385:com.android.calendar/u0a131 (adj 15): empty #21,
,08-24 14:31:38.306  7847  7847 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 14:31:38.306  7847  7847 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-24 14:31:38.306  7847  7847 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-24 14:31:38.336  7847  7847 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:31:38.336  7847  7847 D ActivityThread: Added TimaKeyStore provider
,08-24 14:31:38.356  7847  7847 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-24 14:31:38.426   338   338 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
08-24 14:31:38.426  7829  7829 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,08-24 14:31:38.476  7829  7829 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-24 14:31:38.476  7829  7829 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-24 14:31:38.486  7829  7829 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-24 14:31:38.486   338   338 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7829
08-24 14:31:38.486   338   338 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-24 14:31:38.486  7829  7829 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-24 14:31:38.486  7829  7829 I wpa_supplicant: ssSupport state is = 1,
08-24 14:31:38.486  7829  7829 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-24 14:31:38.486  7829  7829 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-24 14:31:38.486  7829  7829 E wpa_supplicant: SIM READ ERROR
08-24 14:31:38.486  7829  7829 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-24 14:31:38.486  7829  7829 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-24 14:31:38.486  7829  7829 E wpa_supplicant: SIM READ ERROR
08-24 14:31:38.486  7829  7829 I wpa_supplicant: Blacklist: Clear (all) 
,08-24 14:31:38.496  7829  7829 I wpa_supplicant: wpa_default_ap_write_once
08-24 14:31:38.496  7829  7829 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-24 14:31:38.496  7829  7829 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-24 14:31:38.496  7829  7829 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-24 14:31:38.496  7829  7829 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-24 14:31:38.496  7829  7829 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-24 14:31:38.496  7829  7829 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-24 14:31:38.496  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false
08-24 14:31:38.496  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-24 14:31:38.496  1018  1046 D Tethering: interfaceStatusChanged wlan0, false
,08-24 14:31:38.556  7829  7829 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-24 14:31:38.696  1018  1449 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-24 14:31:38.696   288   288 E SMD     : DCD OFF
,08-24 14:31:38.696  1018  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:38.696  1018  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:38.696  1018  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:38.696  1018  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:38.716  7869  7869 E Zygote  : MountEmulatedStorage()
,08-24 14:31:38.716  7869  7869 E Zygote  : v2
08-24 14:31:38.716  7869  7869 I libpersona: KNOX_SDCARD checking this for 10121
08-24 14:31:38.716  7869  7869 I libpersona: KNOX_SDCARD not a persona
,08-24 14:31:38.716  7869  7869 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 14:31:38.716  1018  1449 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7869 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a,
08-24 14:31:38.716  1018  1449 I ActivityManager: Killing 7320:com.android.defcontainer/u0a3 (adj 15): empty #21
,08-24 14:31:38.716  7869  7869 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 14:31:38.716  7869  7869 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 14:31:38.736  7869  7869 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:31:38.736  7869  7869 D ActivityThread: Added TimaKeyStore provider
,08-24 14:31:38.756  7869  7869 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 14:31:38.756  7869  7869 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-24 14:31:38.756  7869  7869 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-24 14:31:38.766  7869  7869 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE,
,08-24 14:31:38.766  7829  7829 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
08-24 14:31:38.766  7869  7869 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
08-24 14:31:38.776  7829  7829 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-24 14:31:38.776  7869  7869 I QuickConnect: PeriphStartReceiver.onReceive - no need to start,
08-24 14:31:38.776  1018  1217 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,08-24 14:31:38.776  1018  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:38.776  1018  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-24 14:31:38.776  1018  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:38.776  1018  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:38.796  7829  7829 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-24 14:31:38.796   338   338 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7829
08-24 14:31:38.796   338   338 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-24 14:31:38.796  7829  7829 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-24 14:31:38.796  7829  7829 I wpa_supplicant: ssSupport state is = 1
,08-24 14:31:38.796  7829  7829 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-24 14:31:38.796  7829  7829 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-24 14:31:38.806  1018  1217 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7887 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,08-24 14:31:38.806  7887  7887 E Zygote  : MountEmulatedStorage()
08-24 14:31:38.806  7887  7887 I libpersona: KNOX_SDCARD checking this for 10141
08-24 14:31:38.806  7887  7887 E Zygote  : v2
08-24 14:31:38.806  7887  7887 I libpersona: KNOX_SDCARD not a persona
08-24 14:31:38.806  1018  1217 I ActivityManager: Killing 7461:com.google.android.gms:car/u0a11 (adj 15): empty #21
08-24 14:31:38.806  7887  7887 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 14:31:38.806  7887  7887 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 14:31:38.806  7829  7829 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
08-24 14:31:38.806   338   338 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7829
08-24 14:31:38.806   338   338 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-24 14:31:38.806  7829  7829 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
,08-24 14:31:38.806  7829  7829 I wpa_supplicant: ssSupport state is = 1
08-24 14:31:38.806  7829  7829 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-24 14:31:38.806  7829  7829 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-24 14:31:38.806  7829  7829 E wpa_supplicant: SIM READ ERROR
08-24 14:31:38.806  7829  7829 I wpa_supplicant: wpa_default_ap_write_once
08-24 14:31:38.806  7829  7829 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-24 14:31:38.816  1018  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-24 14:31:38.806  7829  7829 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-24 14:31:38.806  7887  7887 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-24 14:31:38.816  1018  1046 D Tethering: interfaceLinkStateChanged p2p0, false
08-24 14:31:38.816  1018  1046 D Tethering: interfaceStatusChanged p2p0, false
08-24 14:31:38.816  1018  1046 D Tethering: interfaceLinkStateChanged p2p0, false
08-24 14:31:38.816  1018  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-24 14:31:38.816  1018  1046 D Tethering: interfaceStatusChanged p2p0, false
,08-24 14:31:38.816   305   305 I art     : Explicit concurrent mark sweep GC freed 8718(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 701us total 23.731ms
,08-24 14:31:38.826  7887  7887 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:31:38.826  7887  7887 D ActivityThread: Added TimaKeyStore provider
,08-24 14:31:38.846   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 836us total 21.017ms
,08-24 14:31:38.846  7829  7829 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
08-24 14:31:38.846  7829  7829 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-24 14:31:38.846  7887  7887 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
08-24 14:31:38.846  7887  7887 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 14:31:38.846  7887  7887 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-24 14:31:38.846  7887  7887 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-24 14:31:38.856   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 565us total 16.433ms
,08-24 14:31:38.896  1018  1491 D RCPManagerService: exchangeData() failure , invalid userId
,08-24 14:31:38.906  7829  7829 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-24 14:31:38.906  7829  7829 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-24 14:31:38.906  7829  7829 I wpa_supplicant: Skip scan - bUseNetwork false
08-24 14:31:38.906  1018  1439 D RCPManagerService: exchangeData() failure , invalid userId
,08-24 14:31:38.916  1018  1492 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.car.InCallServiceImpl in 1000ms
,08-24 14:31:38.936  1018  1508 D RCPManagerService: exchangeData() failure , invalid userId
,08-24 14:31:38.946  1018  1491 D RCPManagerService: exchangeData() failure , invalid userId
,08-24 14:31:38.976  1018  1217 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-24 14:31:38.986  1018  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-24 14:31:38.986  1018  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:38.986  1018  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:38.986  1018  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:38.986  1018  3812 D RCPManagerService: exchangeData() failure , invalid userId
,08-24 14:31:38.996  7910  7910 E Zygote  : MountEmulatedStorage()
08-24 14:31:38.996  7910  7910 E Zygote  : v2
08-24 14:31:38.996  7910  7910 I libpersona: KNOX_SDCARD checking this for 10068
08-24 14:31:38.996  7910  7910 I libpersona: KNOX_SDCARD not a persona
,08-24 14:31:38.996  1018  1491 D RCPManagerService: exchangeData() failure , invalid userId,
08-24 14:31:38.996  7910  7910 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-24 14:31:38.996  7910  7910 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-24 14:31:38.996  7910  7910 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-24 14:31:39.006  1018  1217 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7910 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,08-24 14:31:39.026  1018  1137 D RCPManagerService: exchangeData() failure , invalid userId
,08-24 14:31:39.026  1018  1492 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,08-24 14:31:39.026  1018  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:39.026  7910  7910 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:31:39.026  1018  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:39.026  1018  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:39.026  7910  7910 D ActivityThread: Added TimaKeyStore provider
08-24 14:31:39.026  1018  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:39.036  7926  7926 E Zygote  : MountEmulatedStorage(),
08-24 14:31:39.036  7926  7926 E Zygote  : v2
08-24 14:31:39.036  7926  7926 I libpersona: KNOX_SDCARD checking this for 10009,
08-24 14:31:39.036  7926  7926 I libpersona: KNOX_SDCARD not a persona
,08-24 14:31:39.046  7926  7926 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-24 14:31:39.046  1018  1492 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7926 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
08-24 14:31:39.046  7926  7926 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 14:31:39.046  1018  1492 I ActivityManager: Killing 7096:com.android.vending/u0a26 (adj 15): empty #21
,08-24 14:31:39.046  7926  7926 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-24 14:31:39.046  1018  1491 I ActivityManager: Killing 7413:com.google.android.gms.wearable/u0a11 (adj 15): empty #21
,08-24 14:31:39.076  7926  7926 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:31:39.076  7926  7926 D ActivityThread: Added TimaKeyStore provider
,08-24 14:31:39.116  1018  1046 D Tethering: interfaceLinkStateChanged p2p0, false
,08-24 14:31:39.116  1018  1046 D Tethering: interfaceStatusChanged p2p0, false
08-24 14:31:39.116  1018  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-24 14:31:39.146  1018  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
,08-24 14:31:39.146  1018  1129 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-24 14:31:39.146  7829  7829 I wpa_supplicant: HOTSPOT20_ENABLE called
08-24 14:31:39.146  7829  7829 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-24 14:31:39.146  7829  7829 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-24 14:31:39.146  7829  7829 E wpa_supplicant: SIM READ ERROR
08-24 14:31:39.146  7829  7829 I wpa_supplicant: Blacklist: Clear (all) 
,08-24 14:31:39.186  7829  7829 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-24 14:31:39.196  7829  7829 I wpa_supplicant: Skip scan - bUseNetwork false
,08-24 14:31:39.216  1018  1129 D WifiConfigStore: Loading config and enabling all networks ,
,08-24 14:31:39.226  1179  1179 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-24 14:31:39.226  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 14:31:39.226  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-24 14:31:39.226  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 14:31:39.226  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:39.226  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 14:31:39.226  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:39.226  1179  1179 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-24 14:31:39.226  1179  1179 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-24 14:31:39.226  1179  1179 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-24 14:31:39.226  1179  1753 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-24 14:31:39.226  1179  1179 D HotspotTile: onReceive : 3, 0
,08-24 14:31:39.226  4761  4761 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-24 14:31:39.236  7162  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:31:39.236  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:31:39.236  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:39.236  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:31:39.236  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:31:39.236  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:31:39.236  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:31:39.236  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:31:39.236  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 14:31:39.236  7162  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 14:31:39.236  7162  7162 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 14:31:39.236  7162  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 14:31:39.236  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:31:39.236  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:39.236  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:31:39.236  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:31:39.236  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:31:39.236  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:31:39.236  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:31:39.236  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 14:31:39.236  7162  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:31:39.236  1018  1129 E WifiConfigStore: Not a HS20
,08-24 14:31:39.236  7162  7162 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 14:31:39.246  1018  1129 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-24 14:31:39.256  1018  1449 I art     : Explicit concurrent mark sweep GC freed 68136(3MB) AllocSpace objects, 18(336KB) LOS objects, 33% free, 23MB/34MB, paused 13.742ms total 189.815ms
,08-24 14:31:39.256  1018  1129 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-24 14:31:39.256  7829  7829 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-24 14:31:39.256  7829  7829 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-24 14:31:39.256  7829  7829 I wpa_supplicant: reset timer : RESET_TIMER 0
08-24 14:31:39.256  7829  7829 I wpa_supplicant: P2P: Current p2p state = IDLE
08-24 14:31:39.256  7829  7829 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-24 14:31:39.256  7829  7829 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-24 14:31:39.256  7829  7829 I wpa_supplicant: First Scan Start
,08-24 14:31:39.256  7829  7829 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds,
,08-24 14:31:39.266  1018  1129 D WifiNative-wlan0: Setting external_sim to 1
,08-24 14:31:39.266  1018  1129 D WifiStateMachine: Setting OUI to DA-A1-19
08-24 14:31:39.266  1018  1129 I WifiNative-HAL: startHal
08-24 14:31:39.266  1018  1129 E wifi    : getStaticLongField sWifiHalHandle 0x9f31f88c
08-24 14:31:39.266  1018  1129 I WifiNative-HAL: Could not start hal
,08-24 14:31:39.276  1018  1129 E WifiNative-wlan0: do suspend true
,08-24 14:31:39.276  1018  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-24 14:31:39.276  1018  1128 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-24 14:31:39.276   278   983 D CommandListener: Setting iface cfg
08-24 14:31:39.276   278   983 D CommandListener: Trying to bring up p2p0
,08-24 14:31:39.276  1018  1128 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-24 14:31:39.276  1018  1128 D WifiP2pService: P2pEnablingState
,08-24 14:31:39.276  1018  1128 D WifiP2pService: P2pEnablingState{ what=147457 }
08-24 14:31:39.276  1018  1128 D WifiP2pService: P2p socket connection successful
08-24 14:31:39.276  1018  1128 D WifiP2pService: P2pEnabledState
,08-24 14:31:39.276  1018  1128 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-24 14:31:39.286  1018  1131 E ConnectivityService: updateNetworkInfo()
,08-24 14:31:39.286  1018  1128 D WifiNative-p2p0: p2pGetDeviceAddress
,08-24 14:31:39.286  1018  1128 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
08-24 14:31:39.286  1018  1129 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-24 14:31:39.286  1018  1129 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-24 14:31:39.286  1018  1129 E WifiNative-wlan0: invaild command id : 215
,08-24 14:31:39.286  1018  1128 D WifiP2pService: DeviceAddress: 0a:75:42
,08-24 14:31:39.296  7910  7910 D BadgeProvider: onCreate
,08-24 14:31:39.296  7910  7910 D BadgeProvider: DatabaseHelper
,08-24 14:31:39.316  1018  1128 D WifiP2pService: sending p2p persistent groups changed broadcast
08-24 14:31:39.316  1018  1128 D WifiP2pService: InactiveState
08-24 14:31:39.316  7829  7829 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-24 14:31:39.316  1018  1128 D WifiP2pService: InactiveState{ what=143376 },
,08-24 14:31:39.316  7829  7829 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-24 14:31:39.316  1018  1128 D WifiP2pService: P2pEnabledState{ what=143376 }
08-24 14:31:39.316  7910  7921 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-24 14:31:39.316  7829  7829 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-24 14:31:39.326  7829  7829 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,08-24 14:31:39.326  1018  1128 D WifiP2pService: InactiveState{ what=143376 }
08-24 14:31:39.326  1018  1129 E WifiStateMachine: Failed to set frequency band 0
08-24 14:31:39.326  1018  1128 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-24 14:31:39.326  1018  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-24 14:31:39.326  1018  1129 D SecContentProvider2: mCursor = null
,08-24 14:31:39.326  1018  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-24 14:31:39.326  1018  1129 D SecContentProvider2: mCursor = null
,08-24 14:31:39.336  1018  1018 D WifiScanningService: SCAN_AVAILABLE : 3
,08-24 14:31:39.336  7910  7921 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-24 14:31:39.336  1018  1018 D RttService: SCAN_AVAILABLE : 3
08-24 14:31:39.336  7910  7921 D BadgeProvider: sendNotify, [notify] : null
08-24 14:31:39.336  7910  7921 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-24 14:31:39.336  7603  7603 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:31:39.336  7910  7921 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-24 14:31:39.336  7910  7921 D BadgeProvider: update, [UpdateCount] : 1
,08-24 14:31:39.336  1018  1018 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-24 14:31:39.336  1018  1153 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,08-24 14:31:39.336  1018  1153 I WifiNative-HAL: startHal
08-24 14:31:39.336  1018  1154 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:39.336  1018  1153 E wifi    : getStaticLongField sWifiHalHandle 0x9e1e19bc
08-24 14:31:39.336  1018  1153 I WifiNative-HAL: Could not start hal
,08-24 14:31:39.336  1018  1153 E WifiScanningService: could not start HAL
08-24 14:31:39.336  1018  1049 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-24 14:31:39.336  1018  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-24 14:31:39.336  1018  1049 D WifiDisplayController: disconnect
08-24 14:31:39.336  1018  1049 D WifiDisplayController: updateConnection
08-24 14:31:39.336  1018  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-24 14:31:39.336  1018  1049 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-24 14:31:39.336  1493  1493 D Launcher.Model: reloadBadges entered.
,08-24 14:31:39.346  1018  1049 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 14:31:39.346  1018  1049 D WifiDisplayAdapter: onP2pDisconnected
08-24 14:31:39.346  1018  1049 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-24 14:31:39.346  1018  1049 D IpRemoteDisplayController: WfdBridgeServer is already null
08-24 14:31:39.346  1018  1049 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
08-24 14:31:39.346  1018  1049 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
08-24 14:31:39.346  1018  1049 D WifiDisplayController:  primary type: 10-0050F204-5
08-24 14:31:39.346  1018  1049 D WifiDisplayController:  secondary type: null
08-24 14:31:39.346  1018  1049 D WifiDisplayController:  wps: 0
08-24 14:31:39.346  1018  1049 D WifiDisplayController:  grpcapab: 0
08-24 14:31:39.346  1018  1049 D WifiDisplayController:  devcapab: 0
08-24 14:31:39.346  1018  1049 D WifiDisplayController:  status: 3
08-24 14:31:39.346  1018  1049 D WifiDisplayController:  wfdInfo: null
08-24 14:31:39.346  1018  1049 D WifiDisplayController:  groupownerAddress: null
08-24 14:31:39.346  1018  1049 D WifiDisplayController:  GOdeviceName: null
08-24 14:31:39.346  1018  1049 D WifiDisplayController:  interfaceAddress: 
08-24 14:31:39.346  1018  1049 D WifiDisplayController:  SConnectInfo : null
,08-24 14:31:39.356  1018  3385 D SSRM:n  : SIOP:: AP = 380
,08-24 14:31:39.356  1018  1449 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,08-24 14:31:39.356  1179  1179 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-24 14:31:39.356  1018  1449 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-24 14:31:39.356  1018  1137 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-24 14:31:39.356  1179  1179 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-24 14:31:39.356  1018  1441 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-24 14:31:39.356  1018  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-24 14:31:39.376   278   979 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-24 14:31:39.376   278   979 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-24 14:31:39.376  1018  1441 I ActivityManager: Killing 7571:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,08-24 14:31:39.376  1018  1492 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-24 14:31:39.376  1018  1492 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-24 14:31:39.376  1018  1492 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:39.376  1018  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:39.376  1018  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-24 14:31:39.386  7626  7626 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-24 14:31:39.386  7626  7626 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-24 14:31:39.386  7626  7626 D SecurityLogAgent: StateMachine : Current State = 1
08-24 14:31:39.386  7626  7626 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-24 14:31:39.386  1628  1628 I Hs20UtilService: Starting #12
,08-24 14:31:39.386  1628  1673 I Hs20UtilService: Message received 5011
,08-24 14:31:39.396  1018  3813 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-24 14:31:39.396  1018  3813 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-24 14:31:39.396  1018  3813 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:39.396  1018  3813 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:39.396  1018  3813 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-24 14:31:39.396  1628  1628 I Hs20UtilService: Starting #13
,08-24 14:31:39.396  1628  1673 I Hs20UtilService: Message received 5011
,08-24 14:31:39.396  1018  1129 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-24 14:31:39.396  1018  1129 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-24 14:31:39.396  1018  1129 E WifiNative-wlan0: invaild command id : 215
,08-24 14:31:39.396  7626  7626 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-24 14:31:39.406  7626  7626 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-24 14:31:39.406  7626  7626 D SecurityLogAgent: StateMachine : Current State = 1
,08-24 14:31:39.406  7626  7626 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-24 14:31:39.406  4761  4761 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-24 14:31:39.416  4761  4761 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-24 14:31:39.416  4761  4761 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-24 14:31:39.416  4761  4761 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-24 14:31:39.416  4761  4761 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-24 14:31:39.416  4761  4761 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-24 14:31:39.416  4761  4844 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-24 14:31:39.416  1018  1449 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-24 14:31:39.416  1018  1449 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.samsung.android.app.FileShareClient/com.samsung.android.app.FileShareClient.ClientBroadcastReceiver}
08-24 14:31:39.416  1018  1449 W BroadcastQueue: android.os.TransactionTooLargeException
08-24 14:31:39.416  1018  1449 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-24 14:31:39.416  1018  1449 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-24 14:31:39.416  1018  1449 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-24 14:31:39.416  1018  1449 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-24 14:31:39.416  1018  1449 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-24 14:31:39.416  1018  1449 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
08-24 14:31:39.416  1018  1449 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-24 14:31:39.416  1018  1449 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
08-24 14:31:39.416  1018  1449 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,08-24 14:31:39.416  1018  1449 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-24 14:31:39.416  1018  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:39.416  1018  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:39.416  1018  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:39.416  1018  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:39.436  7949  7949 E Zygote  : MountEmulatedStorage()
,08-24 14:31:39.436  7949  7949 E Zygote  : v2
08-24 14:31:39.436  7949  7949 I libpersona: KNOX_SDCARD checking this for 10064
08-24 14:31:39.436  7949  7949 I libpersona: KNOX_SDCARD not a persona
,08-24 14:31:39.436  7949  7949 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 14:31:39.436  1018  1449 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7949 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-24 14:31:39.436  7949  7949 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 14:31:39.436  7949  7949 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 14:31:39.446  7949  7949 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:31:39.456  7949  7949 D ActivityThread: Added TimaKeyStore provider,
,08-24 14:31:39.466  7949  7949 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-24 14:31:39.476  7949  7949 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-24 14:31:39.476  7949  7949 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-24 14:31:39.486  1018  1043 W libprocessgroup: failed to open /acct/uid_10064/pid_7571/cgroup.procs: No such file or directory
,08-24 14:31:39.506  7949  7949 D FileShare-Client: Outbound.stopDelayTimer - 
,08-24 14:31:39.506  7588  7588 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-24 14:31:39.516  1018  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:39.516  1018  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:39.516  1018  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk,
,08-24 14:31:39.516  1018  1491 I ActivityManager: Killing 7504:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,08-24 14:31:39.916  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-24 14:31:39.916  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:39.916  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:39.916  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-24 14:31:39.936  7964  7964 E Zygote  : MountEmulatedStorage(),
,08-24 14:31:39.936  7964  7964 E Zygote  : v2,
08-24 14:31:39.936  7964  7964 I libpersona: KNOX_SDCARD checking this for 10011
,08-24 14:31:39.936  1018  1044 I ActivityManager: Start proc com.google.android.gms:car for service com.google.android.gms/.car.InCallServiceImpl: pid=7964 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a,
08-24 14:31:39.936  7964  7964 I libpersona: KNOX_SDCARD not a persona
,08-24 14:31:39.936  7964  7964 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-24 14:31:39.946  7964  7964 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-24 14:31:39.946  7964  7964 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,08-24 14:31:39.966  7964  7964 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:31:39.966  7964  7964 D ActivityThread: Added TimaKeyStore provider
,08-24 14:31:39.996  7964  7964 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-24 14:31:39.996  7964  7964 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-24 14:31:40.036  7964  7964 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,08-24 14:31:40.036  7964  7964 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,08-24 14:31:40.046  7964  7964 I MultiDex: VM with version 2.1.0 has multidex support
,08-24 14:31:40.046  7964  7964 I MultiDex: install
,08-24 14:31:40.046  7964  7964 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-24 14:31:40.066  7964  7964 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-24 14:31:40.136  7964  7964 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-24 14:31:40.136  7964  7964 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@175f66a2: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-24 14:31:40.136  7964  7964 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-24 14:31:40.146  1018  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:40.146  1018  1044 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:40.146  1018  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:40.146  1018  3813 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-24 14:31:40.146  1018  3813 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-24 14:31:40.146  1018  3813 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:40.146  1018  3813 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-24 14:31:40.146  1018  3813 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:40.156  1018  1492 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
08-24 14:31:40.156  1018  1492 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
08-24 14:31:40.156  1018  1492 I splitIntent: other index=5, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
08-24 14:31:40.156  1018  1492 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,08-24 14:31:40.156  2653  3159 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-24 14:31:40.156  1018  1492 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:40.156  1018  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-24 14:31:40.156  1018  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:40.166  1018  1441 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:40.166  1018  1441 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:40.166  1018  1441 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:40.166  2653  2653 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-24 14:31:40.176  1018  3813 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:40.176  1018  3813 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:40.176  1018  3813 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:40.176  1018  3813 I ActivityManager: Killing 7526:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,08-24 14:31:40.176  1018  1439 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-24 14:31:40.176  1018  1439 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,08-24 14:31:40.186  1018  1439 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:40.186  1018  1439 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:40.186  1018  1439 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:40.186  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:40.186  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:40.186  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:40.186  2653  2653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 14:31:40.196  1018  1492 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:40.196  1018  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:40.196  1018  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:40.196  1938  1938 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,08-24 14:31:40.196  1018  1031 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-24 14:31:40.196  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,08-24 14:31:40.196  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:40.196  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:40.196  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:40.206  1018  1489 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:40.206  1018  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:40.206  1018  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:40.206  7964  7982 D NativeLibraryUtils: Install completed successfully. count=0 extracted=0
,08-24 14:31:40.206  1018  1489 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:40.206  1018  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-24 14:31:40.206  1018  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:40.216  1018  1441 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:40.216  1018  1441 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-24 14:31:40.216  1018  1441 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:40.216  1018  1508 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:40.216  1018  1508 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-24 14:31:40.216  1018  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:40.226  1018  1492 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 14:31:40.226  1018  1492 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:40.226  1018  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:40.226  1018  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:40.226  1018  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:40.226  1018  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:40.226  1018  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:40.226  1018  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:40.246  7984  7984 E Zygote  : MountEmulatedStorage()
,08-24 14:31:40.246  7984  7984 E Zygote  : v2
,08-24 14:31:40.246  7984  7984 I libpersona: KNOX_SDCARD checking this for 10011
,08-24 14:31:40.246  7984  7984 I libpersona: KNOX_SDCARD not a persona
,08-24 14:31:40.246  7984  7984 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 14:31:40.246  1018  1492 I ActivityManager: Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=7984 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,08-24 14:31:40.256  1018  1439 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:40.256  1018  1439 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:40.256  1018  1439 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:40.256  7984  7984 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 14:31:40.256  7984  7984 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-24 14:31:40.276  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:40.276  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:40.276  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:40.276  7984  7984 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:31:40.276  7984  7984 D ActivityThread: Added TimaKeyStore provider
,08-24 14:31:40.286  1018  3813 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:40.286  1018  3813 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:40.286  1018  3813 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:40.296  1018  1508 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 14:31:40.296  1018  1508 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:40.296  1018  1508 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:40.296  1018  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:40.306  1018  1441 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:40.306  1018  1441 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:40.306  1018  1441 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:40.306  7984  7984 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-24 14:31:40.306  7984  7984 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-24 14:31:40.316  1018  1492 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-24 14:31:40.316  1018  1492 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,08-24 14:31:40.316  1018  1492 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:40.316  1018  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:40.316  1018  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:40.316  1938  7999 D LocationInitializer: Restart initialization of location
,08-24 14:31:40.316  1018  1031 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-24 14:31:40.316  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,08-24 14:31:40.316  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:40.316  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:40.316  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:40.336  1018  1508 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 14:31:40.336  1018  1508 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:40.336  1018  1508 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:40.336  1018  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:40.346  7984  7984 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>,
08-24 14:31:40.346  7984  7984 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,08-24 14:31:40.356  7984  7984 I MultiDex: VM with version 2.1.0 has multidex support
08-24 14:31:40.356  7984  7984 I MultiDex: install
08-24 14:31:40.356  7984  7984 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-24 14:31:40.376  7984  7984 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-24 14:31:40.426  7829  7829 I wpa_supplicant: nl80211: Received scan results (24 BSSes),
,08-24 14:31:40.426  7829  7829 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-24 14:31:40.426  7829  7829 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-24 14:31:40.426  7829  7829 I wpa_supplicant: Trying to associate with  'G700'
08-24 14:31:40.426  7829  7829 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-24 14:31:40.426  7829  7829 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-24 14:31:40.436  1018  7942 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-24 14:31:40.446  1018  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-24 14:31:40.446  1018  1129 D SecContentProvider2: mCursor = null
,08-24 14:31:40.456  7984  7984 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-24 14:31:40.456  7984  7984 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@175f66a2: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-24 14:31:40.456  7984  7984 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-24 14:31:40.466  1018  1044 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:40.466  1018  1044 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:40.466  1018  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:40.466  1018  1441 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms,
,08-24 14:31:40.466  1018  1441 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:40.466  1018  1441 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
08-24 14:31:40.466  1018  1441 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:40.466  1018  1489 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,08-24 14:31:40.466  1018  1441 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-24 14:31:40.466  1018  1489 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
08-24 14:31:40.466  2653  4319 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-24 14:31:40.466  1018  1489 I splitIntent: other index=5, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
08-24 14:31:40.466  1018  1489 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,08-24 14:31:40.466  1018  1489 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:40.466  1018  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-24 14:31:40.466  1018  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:40.476  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:40.476  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:40.476  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:40.476  2653  2653 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-24 14:31:40.486  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:40.486  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-24 14:31:40.486  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:40.486  1018  1031 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-24 14:31:40.486  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,08-24 14:31:40.486  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:40.486  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:40.486  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:40.496  2653  2653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 14:31:40.496  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:40.496  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:40.496  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:40.506  1018  1508 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:40.506  1018  1508 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:40.506  1018  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:40.506  7984  7984 D WearableService: callingUid 10011, callindPid: 7984
,08-24 14:31:40.516  1938  1938 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,08-24 14:31:40.516  1018  3813 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-24 14:31:40.516  1018  3813 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,08-24 14:31:40.516  1018  3813 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:40.516  1018  3813 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-24 14:31:40.516  1018  3813 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:40.516  1018  1492 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:40.526  1018  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:40.526  1018  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:40.526  1018  1492 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:40.526  1018  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-24 14:31:40.526  1018  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:40.536  1018  1439 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:40.536  1018  1439 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:40.536  1018  1439 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:40.546  1018  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:40.546  1018  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:40.546  1018  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:40.546  7984  8004 D NativeLibraryUtils: Install completed successfully. count=0 extracted=0
,08-24 14:31:40.546  1018  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:40.546  1018  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:40.546  1018  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:40.566  1018  1508 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:40.566  1018  1508 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:40.566  1018  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:40.566  1755  5234 E MDM     : [190] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-24 14:31:40.576  1018  3812 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:40.576  1018  3812 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-24 14:31:40.576  1018  3812 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:40.576  1755  5234 E MDM     : [190] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-24 14:31:40.586  1018  1031 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 14:31:40.586  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:40.586  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:40.586  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:40.586  1018  1217 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:40.586  1018  1217 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:40.586  1018  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:40.596  1018  1508 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-24 14:31:40.596  1018  1508 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,08-24 14:31:40.596  1018  1508 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:40.596  1018  1508 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:40.596  1018  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:40.596  1938  8006 D LocationInitializer: Restart initialization of location
,08-24 14:31:40.596  1018  1489 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-24 14:31:40.596  1018  1489 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,08-24 14:31:40.596  1018  1489 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:40.596  1018  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:40.596  1018  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 14:31:40.666  1018  1217 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-24 14:31:40.666  1018  1217 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-24 14:31:40.666  1018  1217 D SecContentProvider2: mCursor = null
,08-24 14:31:40.666  1018  1217 D WifiService: setWifiEnabled: false pid=7162, uid=10170
,08-24 14:31:40.666  1018  1217 D SettingsProvider: name = wifi_on
,08-24 14:31:40.676  1018  1018 D WifiScanningService: SCAN_AVAILABLE : 1
,08-24 14:31:40.676  1018  1153 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-24 14:31:40.676  1018  1128 D WifiP2pService: InactiveState{ what=131204 }
08-24 14:31:40.676  1018  1128 D WifiP2pService: P2pEnabledState{ what=131204 }
,08-24 14:31:40.676  1018  1018 D RttService: SCAN_AVAILABLE : 1
,08-24 14:31:40.686  1018  1128 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-24 14:31:40.686  1018  1154 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:40.686  1018  1131 E ConnectivityService: updateNetworkInfo()
,08-24 14:31:40.686  1018  1049 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-24 14:31:40.686  1018  1049 D WifiDisplayAdapter: onP2pDisconnected
,08-24 14:31:40.686  1018  1049 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-24 14:31:40.686  1018  1049 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-24 14:31:40.696  1018  1128 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-24 14:31:40.696  1018  1131 E ConnectivityService: updateNetworkInfo()
,08-24 14:31:40.696  1018  1128 D WifiP2pService: P2pDisablingState
08-24 14:31:40.696  1018  1128 D WifiP2pService: P2pDisablingState{ what=147458 }
,08-24 14:31:40.696  1018  1128 D WifiP2pService: p2p socket connection lost
08-24 14:31:40.696  1018  1128 D WifiP2pService: P2pDisabledState
,08-24 14:31:40.696   278   983 D CommandListener: Clearing all IP addresses on wlan0
08-24 14:31:40.696  4761  4761 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-24 14:31:40.696  4761  4761 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-24 14:31:40.696  4761  4761 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-24 14:31:40.696  1018  1018 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-24 14:31:40.696  1018  1049 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-24 14:31:40.696  1018  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-24 14:31:40.696  1018  1049 D WifiDisplayController: disconnect
08-24 14:31:40.696  1018  1049 D WifiDisplayController: updateConnection
08-24 14:31:40.696  1018  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-24 14:31:40.696  1018  1049 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-24 14:31:40.696  4761  4761 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-24 14:31:40.696  4761  4761 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-24 14:31:40.696  4761  4761 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-24 14:31:40.696  7829  7829 E wpa_supplicant: Cmd 35605 not handled
08-24 14:31:40.696  7829  7829 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-24 14:31:40.696  7829  7829 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-24 14:31:40.696  7829  7829 I wpa_supplicant: Associated with F4.99.3E
08-24 14:31:40.696  7829  7829 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-24 14:31:40.696  7829  7829 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-24 14:31:40.696  7829  7829 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-24 14:31:40.706  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false
,08-24 14:31:40.706  1018  1046 D Tethering: interfaceStatusChanged wlan0, false
08-24 14:31:40.706  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-24 14:31:40.706  4761  4844 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-24 14:31:40.706  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false
08-24 14:31:40.706  1018  1046 D Tethering: interfaceStatusChanged wlan0, false
08-24 14:31:40.706  1018  1049 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-24 14:31:40.706  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-24 14:31:40.706  1018  1049 D WifiDisplayAdapter: onP2pDisconnected
08-24 14:31:40.706  1018  1049 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-24 14:31:40.706  1018  1049 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-24 14:31:40.706  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false
08-24 14:31:40.706  1018  1046 D Tethering: interfaceStatusChanged wlan0, false
,08-24 14:31:40.706  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-24 14:31:40.706  1179  1179 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-24 14:31:40.706  7829  7829 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-24 14:31:40.706  1018  1439 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-24 14:31:40.706  7829  7829 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-24 14:31:40.706  1179  1179 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-24 14:31:40.706  7829  7829 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-24 14:31:40.706  7829  7829 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,08-24 14:31:40.706  7829  7829 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-24 14:31:40.716  7829  7829 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-24 14:31:40.716  7829  7829 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-24 14:31:40.716  7829  7829 I wpa_supplicant: Blacklist: Clear (temp) 
08-24 14:31:40.716  7829  7829 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,08-24 14:31:40.716  7949  7949 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
08-24 14:31:40.716  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, true
,08-24 14:31:40.716  1018  1046 D Tethering: interfaceStatusChanged wlan0, true
08-24 14:31:40.716  7949  7949 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-24 14:31:40.716  7949  7949 D FileShare-Client: Outbound.stopDelayTimer - 
,08-24 14:31:40.716  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-24 14:31:40.716  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, true
,08-24 14:31:40.716  1018  1046 D Tethering: interfaceStatusChanged wlan0, true
,08-24 14:31:40.716  7829  7829 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-24 14:31:40.716  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-24 14:31:40.726  1018  1132 E Tethering: No numeric data
,08-24 14:31:40.726  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-24 14:31:40.726  1018  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-24 14:31:40.726  1018  1132 D Tethering: clearTetheredNotification()
,08-24 14:31:40.726  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 14:31:40.726  1018  1126 V NetworkStats: performPollLocked(flags=0x1)
,08-24 14:31:40.726  1018  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-24 14:31:40.736  1018  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-24 14:31:40.736  1179  1179 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-24 14:31:40.736  1018  1126 V NetworkStats: performPollLocked() took 5ms
08-24 14:31:40.736  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 14:31:40.736  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-24 14:31:40.736  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-24 14:31:40.736  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:40.736  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:40.736  1179  1179 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-24 14:31:40.736  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:40.736  1179  1179 D HotspotTile: updateTetherState():false, false
08-24 14:31:40.736  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 14:31:40.736  7588  7588 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null,
08-24 14:31:40.736  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 14:31:40.736  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 14:31:40.746  1179  1179 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-24 14:31:40.746  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 14:31:40.746  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-24 14:31:40.746  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 14:31:40.746  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:40.746  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 14:31:40.746  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:40.746  1179  1179 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-24 14:31:40.746  1179  1179 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-24 14:31:40.746  1179  1179 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-24 14:31:40.746  1179  1753 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-24 14:31:40.756  1179  1179 D HotspotTile: onReceive : 0, 0
,08-24 14:31:40.756  4761  4761 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-24 14:31:40.756  7162  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 14:31:40.756  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:31:40.756  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:40.756  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:31:40.756  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 14:31:40.756  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:31:40.756  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:31:40.756  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:31:40.756  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 14:31:40.766  7162  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 14:31:40.766  7162  7162 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 14:31:40.766  7162  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 14:31:40.766  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:31:40.766  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:40.766  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:31:40.766  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 14:31:40.766  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:31:40.766  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:31:40.766  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:31:40.766  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 14:31:40.766  7162  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 14:31:40.766  7162  7162 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 14:31:40.766  4761  4761 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-24 14:31:40.766  4761  4761 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-24 14:31:40.776  4761  4761 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-24 14:31:40.776  4761  4761 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-24 14:31:40.776  4761  4761 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-24 14:31:40.776  4761  4761 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-24 14:31:40.776  4761  4844 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-24 14:31:40.776  7949  7949 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-24 14:31:40.776  7949  7949 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-24 14:31:40.776  7949  7949 D FileShare-Client: Outbound.stopDelayTimer - 
,08-24 14:31:40.786  7588  7588 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-24 14:31:40.786  1018  1492 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-24 14:31:40.786  1018  1492 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-24 14:31:40.786  1018  1492 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:40.786  1018  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:40.786  1018  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-24 14:31:40.796  1628  1628 I Hs20UtilService: Starting #14
,08-24 14:31:40.796  1628  1673 I Hs20UtilService: Message received 5007
,08-24 14:31:40.796  4761  4761 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-24 14:31:40.796  4761  4761 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-24 14:31:40.796  4761  4761 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-24 14:31:40.796  4761  4761 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-24 14:31:40.796  4761  4761 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-24 14:31:40.796  4761  4761 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-24 14:31:40.796  4761  4844 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-24 14:31:40.806  1018  1439 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-24 14:31:40.806  1018  1439 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-24 14:31:40.806  1018  1439 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:40.806  1018  1439 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-24 14:31:40.806  1018  1439 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-24 14:31:40.806  1628  1628 I Hs20UtilService: Starting #15
,08-24 14:31:40.806  1628  1673 I Hs20UtilService: Message received 5011
,08-24 14:31:40.816  7626  7626 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-24 14:31:40.816  7626  7626 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-24 14:31:40.816  7626  7626 D SecurityLogAgent: StateMachine : Current State = 1
,08-24 14:31:40.816  7626  7626 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-24 14:31:40.946  7829  7829 I wpa_supplicant: Blacklist: Clear (all) 
,08-24 14:31:41.076  7829  7829 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-24 14:31:41.076  1018  1046 D Tethering: interfaceLinkStateChanged p2p0, false
,08-24 14:31:41.076  1018  1046 D Tethering: interfaceStatusChanged p2p0, false
,08-24 14:31:41.076  1018  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-24 14:31:41.096  7829  7829 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,08-24 14:31:41.096  7829  7829 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED,
08-24 14:31:41.096  7829  7829 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-24 14:31:41.096  7829  7829 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-24 14:31:41.096  7829  7829 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-24 14:31:41.096  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false
,08-24 14:31:41.096  1018  1046 D Tethering: interfaceStatusChanged wlan0, false
,08-24 14:31:41.106  1018  1132 D Tethering: InitialState.processMessage what=4
,08-24 14:31:41.106  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-24 14:31:41.106  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false
08-24 14:31:41.106  1018  1132 E Tethering: No numeric data
08-24 14:31:41.106  1018  1046 D Tethering: interfaceStatusChanged wlan0, false
08-24 14:31:41.106  1018  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-24 14:31:41.106  1018  1132 D Tethering: clearTetheredNotification()
08-24 14:31:41.106  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-24 14:31:41.106  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 14:31:41.106  1018  1126 V NetworkStats: performPollLocked(flags=0x1)
08-24 14:31:41.106  1018  1126 D NetworkStatsFactory: UpdateStatsForKnox updated,
,08-24 14:31:41.106  1179  1179 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-24 14:31:41.106  1018  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-24 14:31:41.106  1179  1179 D HotspotTile: updateTetherState():false, false,
08-24 14:31:41.116  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 14:31:41.116  1018  1126 V NetworkStats: performPollLocked() took 5ms
08-24 14:31:41.116  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false
,08-24 14:31:41.116  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-24 14:31:41.116  1018  1046 D Tethering: interfaceStatusChanged wlan0, false
,08-24 14:31:41.116  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 14:31:41.116  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 14:31:41.396  7829  7829 I wpa_supplicant: Blacklist: Clear (all) ,
,08-24 14:31:41.476  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false,
08-24 14:31:41.476  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-24 14:31:41.476  1018  1046 D Tethering: interfaceStatusChanged wlan0, false
,08-24 14:31:41.476  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-24 14:31:41.476  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false
08-24 14:31:41.476  1018  1046 D Tethering: interfaceStatusChanged wlan0, false
,08-24 14:31:41.476  7829  7829 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-24 14:31:41.586  1018  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-24 14:31:41.586  1018  1129 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-24 14:31:41.596  7603  7603 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 14:31:41.596  1179  1179 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-24 14:31:41.596  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-24 14:31:41.596  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-24 14:31:41.596  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 14:31:41.596  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:41.596  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 14:31:41.596  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 14:31:41.606  1179  1179 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-24 14:31:41.606  1179  1179 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-24 14:31:41.606  1179  1753 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-24 14:31:41.606  1179  1179 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-24 14:31:41.606  1179  1179 D HotspotTile: onReceive : 1, 0
,08-24 14:31:41.606  4761  4761 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-24 14:31:41.616  1755  2188 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 14:31:41.616  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:41.616  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:41.616  1018  1030 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-24 14:31:41.616  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-24 14:31:41.616  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:41.616  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-24 14:31:41.616  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-24 14:31:41.626  1628  1628 I Hs20UtilService: Starting #16
,08-24 14:31:41.626  1628  1673 I Hs20UtilService: Message received 5011
,08-24 14:31:41.626  7626  7626 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-24 14:31:41.626  7626  7626 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-24 14:31:41.626  7626  7626 D SecurityLogAgent: StateMachine : Current State = 1
,08-24 14:31:41.626  7626  7626 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-24 14:31:41.706   288   288 E SMD     : DCD OFF
,08-24 14:31:42.246  1018  1046 D Tethering: interfaceRemoved wlan0
,08-24 14:31:42.246  1018  1046 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-24 14:31:42.396  1018  1046 D Tethering: interfaceRemoved p2p0
,08-24 14:31:42.396  1018  1046 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-24 14:31:43.076  1018  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-24 14:31:43.686  7162  7437 D BluetoothAdapter: enable()
,08-24 14:31:43.686  1018  1031 W ActivityManager: Permission Denial: getCurrentUser() from pid=7162, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-24 14:31:43.686  1018  1031 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-24 14:31:43.686  1018  1031 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7162, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-24 14:31:43.686  1018  1031 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-24 14:31:43.686  1018  1031 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-24 14:31:43.686  1018  1031 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-24 14:31:43.686  1018  1031 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-24 14:31:43.686  1018  1031 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-24 14:31:43.696  1018  1031 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-24 14:31:43.696  1018  1031 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-24 14:31:43.706  1018  1031 D SettingsProvider: name = bluetooth_on
,08-24 14:31:43.716  1018  1048 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-24 14:31:43.716  1018  1048 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-24 14:31:43.716  1018  1048 D SecContentProvider: uri = 3 selection = isBluetoothEnabled,
08-24 14:31:43.716  3217  3290 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
08-24 14:31:43.716  3217  3290 D BluetoothAdapterProperties: Setting state to 11,
08-24 14:31:43.716  3217  3290 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-24 14:31:43.716  3217  3290 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-24 14:31:43.726  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:43.716  3217  3290 D BluetoothAdapterService: updateAdapterState state is 11
08-24 14:31:43.726  1018  1018 I InputMethodManagerService: [BT Setting State] State =11
08-24 14:31:43.716  3217  3290 D BluetoothAdapterService: Autoconnection is available 
,08-24 14:31:43.716  3217  3290 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
08-24 14:31:43.716  3217  3290 D BtConfig.SecureMode: isSecureModeOn:false
08-24 14:31:43.716  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-24 14:31:43.716  3217  3290 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
08-24 14:31:43.716  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-24 14:31:43.716  3217  3290 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
08-24 14:31:43.716  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-24 14:31:43.716  3217  3290 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
08-24 14:31:43.716  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-24 14:31:43.716  3217  3290 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
,08-24 14:31:43.726  1179  1179 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-24 14:31:43.716  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-24 14:31:43.716  3217  3290 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
08-24 14:31:43.716  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-24 14:31:43.716  3217  3290 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
08-24 14:31:43.716  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-24 14:31:43.716  3217  3290 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
08-24 14:31:43.716  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-24 14:31:43.716  3217  3290 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
08-24 14:31:43.716  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-24 14:31:43.716  3217  3290 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-24 14:31:43.716  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-24 14:31:43.716  3217  3290 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-24 14:31:43.716  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-24 14:31:43.716  3217  3290 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-24 14:31:43.726  1179  1179 D BluetoothTile:  getBluetoothState : 11
08-24 14:31:43.716  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-24 14:31:43.726  3217  3290 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-24 14:31:43.726  3217  3290 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
08-24 14:31:43.726  3217  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
,08-24 14:31:43.726  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-24 14:31:43.726  3217  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-24 14:31:43.726  1179  1179 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-24 14:31:43.726  1874  1874 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-24 14:31:43.736  4761  4761 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-24 14:31:43.736  1018  1137 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-24 14:31:43.736  1018  1137 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-24 14:31:43.736  1179  1753 D BluetoothTile:  handleUpdatestate:false name:null
08-24 14:31:43.736  1179  1753 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-24 14:31:43.736  1018  1491 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-24 14:31:43.736  1018  1439 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-24 14:31:43.736  1179  1179 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-24 14:31:43.736  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:43.736  1018  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:43.736  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 14:31:43.746  3217  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,08-24 14:31:43.746  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-24 14:31:43.746  3217  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-24 14:31:43.746  1018  1492 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 14:31:43.746  1018  1492 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-24 14:31:43.746  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:43.746  1018  1492 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:43.746  1018  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:43.746  1018  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-24 14:31:43.746  3217  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-24 14:31:43.746  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-24 14:31:43.746  3217  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-24 14:31:43.746  3217  3217 D HeadsetService: Received start request. Starting profile...
08-24 14:31:43.746  1018  1491 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 14:31:43.746  3217  3217 D HeadsetService: start()
08-24 14:31:43.746  1018  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-24 14:31:43.746  3217  3217 D HeadsetStateMachine: make
,08-24 14:31:43.746  1018  1491 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:43.746  1018  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:43.746  1018  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-24 14:31:43.756  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:31:43.756  3217  3217 E HeadsetStateMachine: # of Max HF connection is 2
,08-24 14:31:43.766  3217  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-24 14:31:43.766  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-24 14:31:43.766  3217  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-24 14:31:43.766  2653  2653 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 14:31:43.766  1018  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 14:31:43.766  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-24 14:31:43.766  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:43.766  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:43.766  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 14:31:43.766  1018  1508 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 14:31:43.766  3217  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-24 14:31:43.766  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-24 14:31:43.766  3217  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-24 14:31:43.776  1018  1508 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4283, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 14:31:43.776  1018  1508 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 14:31:43.776  1018  1508 D BatteryService: stay LED for charging
08-24 14:31:43.776  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 14:31:43.776  4761  4761 D BluetoothNotiBroadcastReceiver: onReceive
,08-24 14:31:43.776  1018  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 14:31:43.776  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-24 14:31:43.776  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:43.776  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:43.776  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 14:31:43.776  3217  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-24 14:31:43.776  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-24 14:31:43.776  3217  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-24 14:31:43.776  1018  1018 I MotionRecognitionService: Plugged
,08-24 14:31:43.776  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-24 14:31:43.786  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-24 14:31:43.786  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 14:31:43.786  1424  1424 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-24 14:31:43.786  1424  1424 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 14:31:43.796  1018  1217 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone,
08-24 14:31:43.796  1018  1217 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
08-24 14:31:43.796  1018  1217 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:43.796  1018  1217 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:43.796  1018  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-24 14:31:43.796  1018  1492 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 14:31:43.796  1018  1492 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-24 14:31:43.796  1018  1492 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:43.796  1018  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:43.796  1018  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 14:31:43.796  3217  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService,
08-24 14:31:43.796  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-24 14:31:43.796  3217  3290 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-24 14:31:43.806  1018  3813 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-24 14:31:43.806  1018  3813 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-24 14:31:43.806  1018  3813 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:43.806  1018  3813 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:43.806  1018  3813 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-24 14:31:43.806  3217  3217 I bluedroid: get_profile_interface handsfree
08-24 14:31:43.806  1018  1489 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 14:31:43.806  1018  1489 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-24 14:31:43.806  1018  1489 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:43.806  1018  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:43.806  1018  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 14:31:43.816  3217  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-24 14:31:43.816  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-24 14:31:43.816  3217  3290 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-24 14:31:43.816  3217  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-24 14:31:43.816  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-24 14:31:43.816  3217  3290 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-24 14:31:43.816  3217  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-24 14:31:43.816  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-24 14:31:43.816  3217  3290 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-24 14:31:43.816  3217  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-24 14:31:43.816  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-24 14:31:43.816  3217  3290 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-24 14:31:43.816  3217  3290 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-24 14:31:43.816  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-24 14:31:43.816  1179  1179 D SViewCoverView: level :100 plugged : 2
,08-24 14:31:43.816  3217  3217 E DualScoManager: Dual Sco Manager already instantiated
08-24 14:31:43.816  3217  3217 I DualScoManager: Set HeadsetServiceHelper
08-24 14:31:43.816  3217  3217 D BluetoothAtMessage: createCMTIContentObservers
,08-24 14:31:43.816  1018  1137 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-24 14:31:43.816  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 14:31:43.816  1018  1137 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 14:31:43.816  1018  1137 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-24 14:31:43.816  1018  1137 D SettingsProvider: selectionArgs: false
08-24 14:31:43.816  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-24 14:31:43.816  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-24 14:31:43.816  1018  1137 D SettingsProvider: selectionArgs: 1002
,08-24 14:31:43.816  1179  1179 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:43.816  1179  1179 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
08-24 14:31:43.816  1018  1137 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-24 14:31:43.816  1018  1137 D SettingsProvider: ret = -1
,08-24 14:31:43.826  1018  1508 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-24 14:31:43.826  3217  8012 D HeadsetStateMachine: Enter Disconnected: -2
,08-24 14:31:43.826  1018  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:43.826  1018  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:43.826  1018  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:43.826  1018  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:43.836  1018  1508 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=8013 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
08-24 14:31:43.836  8013  8013 E Zygote  : MountEmulatedStorage()
08-24 14:31:43.836  8013  8013 I libpersona: KNOX_SDCARD checking this for 10055
08-24 14:31:43.836  8013  8013 E Zygote  : v2
08-24 14:31:43.836  8013  8013 I libpersona: KNOX_SDCARD not a persona
,08-24 14:31:43.836  3217  3217 D HeadsetService: mStartError = false
08-24 14:31:43.836  3217  3217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8e0de1
,08-24 14:31:43.836  3217  3217 D A2dpService: Received start request. Starting profile...
08-24 14:31:43.836  3217  3217 D A2dpService: start()
08-24 14:31:43.836  3217  3217 I bluedroid: get_profile_interface avrcp
08-24 14:31:43.846  8013  8013 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 14:31:43.846  8013  8013 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 14:31:43.846  8013  8013 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 14:31:43.846  3217  3217 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-24 14:31:43.846  3217  3217 D Avrcp   : Initialize Media Controller
08-24 14:31:43.846  3217  3217 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-24 14:31:43.846  3217  3217 E Avrcp   : getActiveSessions
08-24 14:31:43.846  3217  3217 D Avrcp   : pick active media Controller
08-24 14:31:43.846  3217  3217 D Avrcp   : Get the active Media Controller 
,08-24 14:31:43.856  3217  8012 D HeadsetStateMachine: Clear mHeadsetBrsf
08-24 14:31:43.856  3217  8012 D HeadsetStateMachine: map size, before remove : 0
08-24 14:31:43.856  3217  8012 D HeadsetStateMachine: map size, after remove: 0
,08-24 14:31:43.866  3217  3217 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-24 14:31:43.866  3217  8019 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
08-24 14:31:43.866  3217  3217 D A2dpStateMachine: make
,08-24 14:31:43.866  3217  3217 I bluedroid: get_profile_interface a2dp
,08-24 14:31:43.866  3217  8029 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-24 14:31:43.866  3217  3217 E bt-btif : warning : media task started media_task_refcnt 1 
,08-24 14:31:43.866  3217  3217 D A2dpService: mStartError = false
08-24 14:31:43.866  3217  3217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8e0de1
,08-24 14:31:43.866  3217  8028 D A2dpStateMachine: Enter Disconnected: -2
08-24 14:31:43.876  3217  3217 D HidService: Received start request. Starting profile...
08-24 14:31:43.876  3217  3217 D HidService: start()
08-24 14:31:43.876  3217  3217 I bluedroid: get_profile_interface hidhost
08-24 14:31:43.876  3217  3217 D HidService: setHidService(): set to: null
08-24 14:31:43.876  3217  3217 D HidService: mStartError = false
08-24 14:31:43.876  3217  3217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8e0de1
,08-24 14:31:43.876  3217  3217 D HealthService: Received start request. Starting profile...
08-24 14:31:43.876  3217  3217 D HealthService: start()
,08-24 14:31:43.876  3217  3217 I bluedroid: get_profile_interface health
08-24 14:31:43.876  3217  3217 D HealthService: mStartError = false
08-24 14:31:43.876  3217  3217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8e0de1
,08-24 14:31:43.876  8013  8013 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 14:31:43.876  8013  8013 D ActivityThread: Added TimaKeyStore provider
,08-24 14:31:43.876  3217  3217 D PanService: Received start request. Starting profile...
08-24 14:31:43.876  3217  3217 D PanService: start()
08-24 14:31:43.876  3217  3217 D BluetoothPanServiceJni: initializeNative(L110): pan
08-24 14:31:43.876  3217  3217 I bluedroid: get_profile_interface pan
08-24 14:31:43.876  3217  3217 D PanService: mStartError = false
08-24 14:31:43.876  3217  3217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8e0de1
,08-24 14:31:43.876  3217  3217 D HeadsetStateMachine: Try to query the phonestate on bind
,08-24 14:31:43.876  1442  1475 I Telecom : BluetoothPhoneService: queryPhoneState
,08-24 14:31:43.886  1442  1442 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-24 14:31:43.886  1442  1442 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-24 14:31:43.886  1442  1475 I Telecom : BluetoothPhoneService: Result of Message : true
,08-24 14:31:43.886  3217  8019 D BluetoothMediaBrowser: no now playing list
08-24 14:31:43.886  3217  8019 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-24 14:31:43.886  3217  3217 D BluetoothMapService: Received start request. Starting profile...
08-24 14:31:43.886  3217  3217 D BluetoothMapService: start()
,08-24 14:31:43.886  3217  3217 D BluetoothMapService: mStartError = false
08-24 14:31:43.886  3217  3217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8e0de1
08-24 14:31:43.886  3217  3217 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
08-24 14:31:43.886  3217  8012 D HeadsetStateMachine: Disconnected process message: 11
08-24 14:31:43.886  3217  3217 D HeadsetStateMachine: Proxy object connected
,08-24 14:31:43.886  3217  3217 D SapService: Received start request. Starting profile...
08-24 14:31:43.886  3217  3217 D SapService: start()
08-24 14:31:43.886  3217  3217 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-24 14:31:43.886  3217  3217 I bluedroid: get_profile_interface sap
08-24 14:31:43.886  3217  3217 D SapService: mStartError = false
,08-24 14:31:43.886  3217  3217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8e0de1
08-24 14:31:43.886  3217  3217 D HeadsetPhoneState: sendDeviceDataStateChanged
08-24 14:31:43.886  3217  3217 D HeadsetPhoneState: Signal level : previous=0 curr=4
08-24 14:31:43.886  3217  3217 E BluetoothAdapterService(764284385): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-24 14:31:43.886  3217  3217 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-24 14:31:43.896  3217  3217 E BluetoothAdapterService(764284385): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-24 14:31:43.896  3217  8012 D HeadsetStateMachine: Disconnected process message: 18
08-24 14:31:43.896  3217  3217 E BluetoothAdapterService(764284385): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-24 14:31:43.896  3217  8012 D HeadsetStateMachine: Disconnected process message: 10
08-24 14:31:43.896  3217  3217 E BluetoothAdapterService(764284385): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-24 14:31:43.896  3217  3217 E BluetoothAdapterService(764284385): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
08-24 14:31:43.896  3217  8012 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-24 14:31:43.896  3217  8012 D HeadsetStateMachine: Disconnected process message: 11
,08-24 14:31:43.906  3217  3217 E BluetoothAdapterService(764284385): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-24 14:31:43.906  3217  3217 E BluetoothAdapterService(764284385): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-24 14:31:43.906  3217  3290 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-24 14:31:43.906  3217  3290 I bluedroid: enable
08-24 14:31:43.916  1018  1051 I PowerManagerService: [PWL] Off : 75s ago
08-24 14:31:43.916  1018  1051 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
08-24 14:31:43.916  1018  1051 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
08-24 14:31:43.916  1018  1051 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1018, ws=null) (elapsedTime=9029)
,08-24 14:31:43.916  8013  8013 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-24 14:31:43.916  3217  3295 E bt-btif : Calling BTA_HhEnable
08-24 14:31:43.916  3217  3295 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-24 14:31:43.916  3217  3295 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-24 14:31:43.916  3217  3295 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
08-24 14:31:43.916  3217  3295 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
08-24 14:31:43.916  3217  3295 E BluetoothServiceJni: populateRssiValuesNative
08-24 14:31:43.916  3217  3295 I bluedroid: getModelRssiValues
08-24 14:31:43.916  3217  3295 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-24 14:31:43.916  3217  3295 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-24 14:31:43.916  1018  1018 D SettingsProvider: name = bluetooth_name
08-24 14:31:43.916  3217  3295 D BluetoothAdapterProperties: Name is: Galaxy A3
,08-24 14:31:43.926  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:43.926  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:43.926  3217  3295 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-24 14:31:43.926  3217  3295 D BluetoothAdapterProperties: Scan Mode:20
08-24 14:31:43.926  3217  3295 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-24 14:31:43.926  3217  3295 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
,08-24 14:31:43.926  3217  3295 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
08-24 14:31:43.926  3217  3295 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
08-24 14:31:43.936  3217  3295 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,08-24 14:31:43.936  3217  3295 E bt-btif : JVenable fails
,08-24 14:31:43.936  3217  3295 D bte_conf: Device ID record 1 : primary
,08-24 14:31:43.936  3217  3295 D bte_conf:   vendorId            = 0075
08-24 14:31:43.936  3217  3295 D bte_conf:   vendorIdSource      = 0001
08-24 14:31:43.936  3217  3295 D bte_conf:   product             = 0100
08-24 14:31:43.936  3217  3295 D bte_conf:   version             = 0200
,08-24 14:31:43.936  3217  3295 D bte_conf:   clientExecutableURL = 
08-24 14:31:43.936  3217  3295 D bte_conf:   serviceDescription  = 
08-24 14:31:43.936  3217  3295 D bte_conf:   documentationURL    = 
,08-24 14:31:43.936  3217  3295 D bte_conf: bte_load_did_conf no section named DID2.
,08-24 14:31:43.936  1018  1097 V AlarmManager: waitForAlarm result :4
,08-24 14:31:43.936  3217  3295 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-24 14:31:43.936  3217  3295 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-24 14:31:43.936  3217  3290 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-24 14:31:43.936  3217  3290 D BluetoothAdapterProperties: ScanMode =  20
,08-24 14:31:43.936  3217  3290 D BluetoothAdapterProperties: State =  11
,08-24 14:31:43.936  1018  1489 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-24 14:31:43.936  3217  3290 D BluetoothAdapterProperties: Setting state to 12
,08-24 14:31:43.936  3217  3290 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-24 14:31:43.946  3217  3295 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-24 14:31:43.946  3217  3295 D BluetoothAdapterProperties: Scan Mode:21
08-24 14:31:43.946  3217  3295 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-24 14:31:43.946  1018  1030 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-24 14:31:43.946  1018  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 14:31:43.946  1018  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-24 14:31:43.946  1018  1030 D SettingsProvider: selectionArgs: false
08-24 14:31:43.946  1018  1030 D SettingsProvider: selectionArgs: 1002
08-24 14:31:43.946  1018  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-24 14:31:43.946  1018  1030 D SettingsProvider: ret = -1
,08-24 14:31:43.946  3217  3290 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-24 14:31:43.946  3217  3290 D BluetoothAdapterService: updateAdapterState state is 12
,08-24 14:31:43.946  1018  1441 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 14:31:43.946  1018  1441 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-24 14:31:43.946  1018  1441 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:43.946  1018  1441 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-24 14:31:43.946  1018  1441 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 14:31:43.956  3217  3290 D BluetoothAdapterService: Autoconnection is available 
08-24 14:31:43.956  3217  3290 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-24 14:31:43.956  3217  3290 D BluetoothAdapterService: starting service from this receiver
,08-24 14:31:43.956  4761  4770 D BluetoothPan: Binding service...
08-24 14:31:43.956  8013  8013 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
08-24 14:31:43.956  1018  1491 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 14:31:43.956  1018  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-24 14:31:43.956  8013  8013 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-24 14:31:43.956  8013  8013 D UserAnalysis: Create SecureDbHelper
08-24 14:31:43.956  1018  1491 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:43.956  1018  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:43.956  1018  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 14:31:43.956  3217  3290 I BluetoothAdapterState: Entering On State from state = 11
08-24 14:31:43.956  3217  3217 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
08-24 14:31:43.956  3217  3217 I BluetoothPbapService: Handler(): got msg=1
,08-24 14:31:43.956  1018  1449 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-24 14:31:43.956  1018  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-24 14:31:43.956  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-24 14:31:43.956  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:31:43.956  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:43.956  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:31:43.956  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 14:31:43.956  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:31:43.956  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:31:43.956  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:31:43.956  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 14:31:43.966  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:43.966  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:43.966  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-24 14:31:43.966  1466  1670 D BluetoothAdapter: onBluetoothStateChange: up=true
08-24 14:31:43.966  1466  1670 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-24 14:31:43.966  8013  8013 D IntelligenceServiceApplication: onCreate()
,08-24 14:31:43.966  3217  8035 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-24 14:31:43.966  4761  4773 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-24 14:31:43.966  4761  4773 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-24 14:31:43.966  7162  7162 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 14:31:43.966  1018  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-24 14:31:43.966  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-24 14:31:43.966  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:43.966  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:43.966  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-24 14:31:43.976  3217  3226 D BluetoothAdapter: onBluetoothStateChange: up=true
08-24 14:31:43.976  3217  3226 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-24 14:31:43.976  4761  4770 D BluetoothPbap: onBluetoothStateChange: up=true
,08-24 14:31:43.976  1018  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-24 14:31:43.976  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-24 14:31:43.976  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:43.976  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:43.976  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-24 14:31:43.976  8013  8013 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-24 14:31:43.976  3217  8035 D BluetoothSocket: bindListen(): myUserId = 0
08-24 14:31:43.976  1018  1137 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
08-24 14:31:43.976  3217  8035 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 14:31:43.976  1442  1462 D BluetoothAdapter: onBluetoothStateChange: up=true
08-24 14:31:43.976  1442  1462 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-24 14:31:43.976  1179  1191 D BluetoothAdapter: onBluetoothStateChange: up=true
08-24 14:31:43.976  1179  1191 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-24 14:31:43.976  8013  8013 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
08-24 14:31:43.976  3217  8035 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-24 14:31:43.976  3217  8035 D BluetoothSocket: bindListen(), new LocalSocket 
08-24 14:31:43.976  3217  8035 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-24 14:31:43.976  3217  8035 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3dad8562
08-24 14:31:43.976  3217  8035 D BluetoothSocket: channel: 19
08-24 14:31:43.976  3217  8035 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-24 14:31:43.986  1018  1048 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-24 14:31:43.986  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:31:43.986  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:43.986  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:31:43.986  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 14:31:43.986  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:31:43.986  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:31:43.986  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:31:43.986  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 14:31:43.986  1018  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-24 14:31:43.986  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-24 14:31:43.986  1018  1048 E BluetoothHeadset: BluetoothHeadset service is binded
08-24 14:31:43.986  4761  4761 D BluetoothPan: BluetoothPAN Proxy object connected
08-24 14:31:43.986  4761  4761 D PanProfile: Bluetooth service connected
,08-24 14:31:43.986  4761  4770 D Bluetoothsap: onBluetoothStateChange: up=true
08-24 14:31:43.986  4761  4770 D Bluetoothsap: Binding service...
,08-24 14:31:43.986  1018  1439 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-24 14:31:43.986  7162  7162 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 14:31:43.986  4761  4770 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-24 14:31:43.986  1018  1439 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:43.986  1018  1439 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:43.986  1018  1439 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:43.986  1018  1439 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:43.996  8013  8013 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.,
,08-24 14:31:43.996  8038  8038 E Zygote  : MountEmulatedStorage()
,08-24 14:31:43.996  8038  8038 E Zygote  : v2
08-24 14:31:43.996  8038  8038 I libpersona: KNOX_SDCARD checking this for 10105
08-24 14:31:43.996  8038  8038 I libpersona: KNOX_SDCARD not a persona
08-24 14:31:44.006  8038  8038 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 14:31:44.006  8038  8038 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-24 14:31:44.006  1018  1439 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=8038 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-24 14:31:44.006  8038  8038 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-24 14:31:44.006  1018  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-24 14:31:44.006  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-24 14:31:44.006  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:44.006  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:44.006  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-24 14:31:44.006  4761  4770 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-24 14:31:44.006  4761  8037 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-24 14:31:44.016  1018  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-24 14:31:44.016  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-24 14:31:44.016  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:44.016  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:44.016  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-24 14:31:44.016  4761  4761 D BluetoothA2dp: Proxy object connected,
08-24 14:31:44.016  4761  4761 D A2dpProfile: Bluetooth service connected
08-24 14:31:44.016  1442  1475 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-24 14:31:44.016  1018  1048 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-24 14:31:44.016  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-24 14:31:44.016  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:44.016  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:44.016  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-24 14:31:44.016  1442  1475 E BluetoothHeadset: BluetoothHeadset service is binded
08-24 14:31:44.016  4761  4773 D BluetoothAdapter: onBluetoothStateChange: up=true
08-24 14:31:44.016  4761  4773 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-24 14:31:44.026  1755  1969 D BluetoothAdapter: onBluetoothStateChange: up=true
08-24 14:31:44.026  1755  1969 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-24 14:31:44.026  4761  4761 D BluetoothPbap: Proxy object connected
08-24 14:31:44.026  4761  4761 D PbapServerProfile: Bluetooth service connected
08-24 14:31:44.026  4761  4761 D Bluetoothsap: BluetoothSAP Proxy object connected
08-24 14:31:44.026  4761  4761 D SapProfile: Bluetooth service connected
08-24 14:31:44.026  4761  4761 D Bluetoothsap: getConnectedDevices()
08-24 14:31:44.026  8038  8038 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:31:44.026  8038  8038 D ActivityThread: Added TimaKeyStore provider
08-24 14:31:44.026  1453  1479 D BluetoothAdapter: onBluetoothStateChange: up=true
08-24 14:31:44.026  1453  1479 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-24 14:31:44.026  1442  1475 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-24 14:31:44.026  1018  1048 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-24 14:31:44.026  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-24 14:31:44.026  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:44.026  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-24 14:31:44.026  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-24 14:31:44.026  1442  1475 E BluetoothHeadset: BluetoothHeadset service is binded,
08-24 14:31:44.026  1018  1048 D BluetoothA2dp: onBluetoothStateChange: up=true
08-24 14:31:44.026  4761  4761 D BluetoothInputDevice: Proxy object connected
08-24 14:31:44.026  4761  4761 D HidProfile: Bluetooth service connected
08-24 14:31:44.026  1018  1048 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-24 14:31:44.026  1018  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-24 14:31:44.036  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-24 14:31:44.036  1018  1018 D BluetoothA2dp: Proxy object connected
,08-24 14:31:44.036  1442  1462 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-24 14:31:44.036  1018  1048 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-24 14:31:44.036  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-24 14:31:44.036  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:44.036  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:44.036  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-24 14:31:44.036  1442  1462 E BluetoothHeadset: BluetoothHeadset service is binded
,08-24 14:31:44.036  3217  3351 D BluetoothA2dp: onBluetoothStateChange: up=true
08-24 14:31:44.036  1018  1048 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-24 14:31:44.036  3217  3351 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-24 14:31:44.036  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-24 14:31:44.036  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:44.036  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:44.036  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 14:31:44.036  3217  3217 D BluetoothA2dp: Proxy object connected
08-24 14:31:44.036  3217  3217 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-24 14:31:44.036  1466  1490 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-24 14:31:44.036  1018  1048 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-24 14:31:44.036  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-24 14:31:44.036  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:44.036  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:44.036  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
08-24 14:31:44.046  1466  1490 E BluetoothHeadset: BluetoothHeadset service is binded
08-24 14:31:44.046  4761  8037 D BluetoothMap: onBluetoothStateChange: up=true
,08-24 14:31:44.046  1018  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-24 14:31:44.046  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-24 14:31:44.046  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:44.046  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:44.046  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-24 14:31:44.046  4761  4761 D BluetoothMap: Proxy object connected
08-24 14:31:44.046  4761  4761 D MapProfile: Bluetooth service connected
08-24 14:31:44.046  4761  4761 D BluetoothMap: getConnectedDevices()
,08-24 14:31:44.046  4761  4773 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-24 14:31:44.046  1018  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-24 14:31:44.046  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-24 14:31:44.046  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:44.046  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:44.046  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-24 14:31:44.046  4761  4773 E BluetoothHeadset: BluetoothHeadset service is binded
,08-24 14:31:44.046  2653  2666 D BluetoothAdapter: onBluetoothStateChange: up=true
08-24 14:31:44.046  2653  2666 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-24 14:31:44.046  7162  7175 D BluetoothAdapter: onBluetoothStateChange: up=true
08-24 14:31:44.046  7162  7175 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-24 14:31:44.046  1018  1048 D BluetoothAdapter: onBluetoothStateChange: up=true
08-24 14:31:44.046  1018  1048 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-24 14:31:44.046  1018  1048 D BluetoothPan: Binding service...
08-24 14:31:44.046  1018  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-24 14:31:44.046  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-24 14:31:44.046  1018  1018 D BluetoothPan: BluetoothPAN Proxy object connected
08-24 14:31:44.046  1018  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-24 14:31:44.046  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
08-24 14:31:44.046  4761  4761 D HeadsetProfile: Bluetooth service connected
,08-24 14:31:44.056  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:44.056  1018  1018 I InputMethodManagerService: [BT Setting State] State =12
08-24 14:31:44.056  1018  1018 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-24 14:31:44.056  1442  1442 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@323541ec, true
08-24 14:31:44.056  1179  1179 D BluetoothTile:  onBluetoothStateChange:
,08-24 14:31:44.056  1442  1442 D BluetoothHeadset: registerMessageListener
,08-24 14:31:44.066  1179  1179 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-24 14:31:44.066  1179  1179 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:44.066  1179  1179 D BluetoothTile:  getBluetoothState : 12
,08-24 14:31:44.066  1874  1874 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-24 14:31:44.066  1179  1753 D BluetoothTile:  handleUpdatestate:false name:null
,08-24 14:31:44.066  3217  3226 D HeadsetService: registerMessageListener
,08-24 14:31:44.076  3217  3226 D HeadsetService: registerMessageListener
08-24 14:31:44.076  1442  1442 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-24 14:31:44.076  3217  8012 D HeadsetStateMachine: Disconnected process message: 70
08-24 14:31:44.076  1442  1442 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-24 14:31:44.076  3217  8012 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@2d51d6f3
08-24 14:31:44.076  1018  1491 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-24 14:31:44.076  1018  1508 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
08-24 14:31:44.076  1179  1179 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-24 14:31:44.076  3217  8054 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-24 14:31:44.076  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:44.076  1179  1753 D BluetoothTile:  handleUpdatestate:false name:null
08-24 14:31:44.076  1442  1442 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-24 14:31:44.076  1442  1442 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-24 14:31:44.076  1442  1442 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
08-24 14:31:44.076  4761  4761 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-24 14:31:44.086  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:44.086  1179  1753 D BluetoothTile:  handleUpdatestate:false name:null
,08-24 14:31:44.086  3217  8012 D HeadsetStateMachine: Disconnected process message: 9
,08-24 14:31:44.086  3217  8012 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-24 14:31:44.086  4761  4761 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,08-24 14:31:44.086  3217  8054 D BluetoothSocket: bindListen(): myUserId = 0
08-24 14:31:44.086  3217  8054 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 14:31:44.086  4761  4761 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-24 14:31:44.086  4761  4761 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-24 14:31:44.086  4761  4761 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-24 14:31:44.086  3217  8054 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]},
08-24 14:31:44.086  3217  8054 D BluetoothSocket: bindListen(), new LocalSocket 
08-24 14:31:44.086  3217  8054 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-24 14:31:44.086  3217  8054 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2e48bfb0
08-24 14:31:44.086  3217  8054 D BluetoothSocket: channel: 5,
,08-24 14:31:44.096   283  1016 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-24 14:31:44.096   283  1016 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-24 14:31:44.096   283  1016 V voice   : voice_set_parameters: exit with code(-2)
08-24 14:31:44.096   283  1016 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-24 14:31:44.096   283  1016 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-24 14:31:44.096   283  1016 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-24 14:31:44.096   283  1016 V audio_hw_primary: adev_set_parameters: exit
,08-24 14:31:44.096  3217  8012 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-24 14:31:44.146   257   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-24 14:31:44.146   257   518 W Vold    : Returning OperationFailed - no handler for errno 0
,08-24 14:31:44.146  8038  8060 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-24 14:31:44.146   257   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-24 14:31:44.146   257   518 W Vold    : Returning OperationFailed - no handler for errno 0
,08-24 14:31:44.146  8038  8060 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-24 14:31:44.306  8038  8038 D StrictMode: StrictMode policy violation; ~duration=146 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at java.io.File.exists(File.java:363)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-24 14:31:44.306  8038  8038 D StrictMode: StrictMode policy violation; ~duration=145 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-24 14:31:44.306  8038  8038 D StrictMode: StrictMode policy violation; ~duration=144 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-24 14:31:44.306  8038  8038 D StrictMode: StrictMode policy violation; ~duration=143 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.q.e.b(PG:170)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-24 14:31:44.306  8038  8038 D StrictMode: StrictMode policy violation; ~duration=141 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.q.k.d(PG:583)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.q.e.b(PG:170)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-24 14:31:44.306  8038  8038 D StrictMode: StrictMode policy violation; ~duration=121 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at java.io.File.exists(File.java:363)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-24 14:31:44.306  1018  1449 I ActivityManager: Killing 7644:com.sec.pcw.device/1000 (adj 15): empty #21
08-24 14:31:44.306  8038  8038 D StrictMode: StrictMode policy violation; ~duration=121 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at java.io.File.exists(File.java:363)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-24 14:31:44.306  8038  8038 D StrictMode: StrictMode policy violation; ~duration=120 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 14:31:44.306  8038  8038 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-24 14:31:44.316   278   979 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-24 14:31:44.316   278   979 D Netd    : getNetworkForDns: using netid 0 for uid 10011
08-24 14:31:44.316  4761  4761 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-24 14:31:44.316  1018  3813 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-24 14:31:44.316  1018  3813 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
08-24 14:31:44.316  1018  3813 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:44.316  1018  3813 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:44.316  1018  3813 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
08-24 14:31:44.326  2653  2653 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-24 14:31:44.326  4761  4761 D DockEventReceiver: finishStartingService: stopping service
08-24 14:31:44.336  4761  4761 D BluetoothNotiBroadcastReceiver: onReceive
08-24 14:31:44.336  1179  1179 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:44.336  1179  1179 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-24 14:31:44.346  3217  3217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8e0de1
08-24 14:31:44.346  3217  3217 D BtConfig.SecureMode: isSecureModeOn:false
08-24 14:31:44.346  1018  1491 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 14:31:44.346  1018  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
08-24 14:31:44.346  1018  1491 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:44.346  1018  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:44.346  1018  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-24 14:31:44.356  1018  1441 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:44.356  1018  1441 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 14:31:44.356  1018  1441 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
08-24 14:31:44.366  1018  1492 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
08-24 14:31:44.366  8038  8069 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
08-24 14:31:44.376  3217  8076 D BluetoothSocket: bindListen(): myUserId = 0
08-24 14:31:44.376  3217  8076 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 14:31:44.376  3217  8076 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[87]}
08-24 14:31:44.376  3217  8076 D BluetoothSocket: bindListen(), new LocalSocket 
08-24 14:31:44.376  3217  8076 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-24 14:31:44.376  3217  8076 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1e7226dc
08-24 14:31:44.376  3217  8076 D BluetoothSocket: channel: 12
08-24 14:31:44.376  3217  8076 I BtOppRfcommListener: Accept thread started.
,08-24 14:31:44.396  1018  1217 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 14:31:44.396  1018  1217 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:44.396  1018  1217 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-24 14:31:44.396  1018  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-24 14:31:44.706   288   288 E SMD     : DCD OFF,
,08-24 14:31:45.586  1018  1441 I ActivityManager: Killing 7661:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,08-24 14:31:45.626  1018  1137 I ActivityManager: Killing 7678:com.sec.android.diagmonagent/1000 (adj 15): empty #21
,08-24 14:31:45.826  1018  1330 E Watchdog: !@Sync 4
,08-24 14:31:46.716  7162  7437 D BluetoothAdapter: disable()
,08-24 14:31:46.716  1018  1439 D SettingsProvider: name = bluetooth_on
,08-24 14:31:46.726  3217  3290 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
08-24 14:31:46.726  3217  3290 D BluetoothAdapterProperties: Setting state to 13
08-24 14:31:46.726  3217  3290 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-24 14:31:46.726  3217  3290 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-24 14:31:46.726  3217  3290 D BluetoothAdapterService: updateAdapterState state is 13
,08-24 14:31:46.726  1018  1449 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 14:31:46.726  1018  1449 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-24 14:31:46.736  1018  1449 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:46.736  1018  1449 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:46.736  1018  1449 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 14:31:46.736  3217  3217 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-24 14:31:46.736  3217  3290 D BluetoothAdapterService: Autoconnection is available 
08-24 14:31:46.736  3217  3290 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-24 14:31:46.736  3217  3290 D BluetoothAdapterService: terminating service from this receiver
,08-24 14:31:46.736  1018  3812 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-24 14:31:46.736  3217  3217 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2899c3e5, channel: 19, state: LISTENING
08-24 14:31:46.736  3217  3217 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2899c3e5, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3dad8562, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@b465ebamSocket: android.net.LocalSocket@3baf316b impl:android.net.LocalSocketImpl@2e68d4c8 fd:FileDescriptor[80]
08-24 14:31:46.736  3217  3217 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3baf316b impl:android.net.LocalSocketImpl@2e68d4c8 fd:FileDescriptor[80]
,08-24 14:31:46.736  1018  3812 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:46.736  1018  3812 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-24 14:31:46.736  1018  3812 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 14:31:46.736  3217  3290 D BluetoothAdapterProperties: onBluetoothDisable()
,08-24 14:31:46.746  3217  3290 D BluetoothAdapterProperties: mDiscovering is false
,08-24 14:31:46.746  1018  1030 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-24 14:31:46.746  3217  3290 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-24 14:31:46.746  4761  4761 D BluetoothPbap: Proxy object disconnected
08-24 14:31:46.746  4761  4761 D PbapServerProfile: Bluetooth service disconnected
,08-24 14:31:46.756  3217  3295 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-24 14:31:46.756  3217  3295 D BluetoothAdapterProperties: Scan Mode:20
,08-24 14:31:46.756  3217  3290 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-24 14:31:46.756  3217  3290 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-24 14:31:46.756  3217  3290 E bt-btif : cmd socket is not created
,08-24 14:31:46.756  3217  3290 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-24 14:31:46.756  3217  8076 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-24 14:31:46.766  3217  3298 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,08-24 14:31:46.766  7162  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:31:46.766  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:31:46.766  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:46.766  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:31:46.766  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 14:31:46.766  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:31:46.766  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:31:46.766  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:31:46.766  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 14:31:46.766  7162  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 14:31:46.766  7162  7162 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 14:31:46.766  7162  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 14:31:46.766  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:31:46.766  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:46.766  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:31:46.766  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 14:31:46.766  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 14:31:46.766  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:31:46.766  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:31:46.766  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 14:31:46.776  7162  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 14:31:46.776  7162  7162 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 14:31:46.776  3217  3298 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 14:31:46.776  3217  3298 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 14:31:46.776  3217  3298 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-24 14:31:46.776  3217  3298 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 14:31:46.776  3217  3298 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 14:31:46.776  3217  3298 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-24 14:31:46.786  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-24 14:31:46.786  1018  1018 I InputMethodManagerService: [BT Setting State] State =13
,08-24 14:31:46.786  1179  1179 D BluetoothTile:  onBluetoothStateChange:
,08-24 14:31:46.786  1179  1179 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-24 14:31:46.786  1179  1179 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:46.796  1179  1179 D BluetoothTile:  getBluetoothState : 13
,08-24 14:31:46.796  1179  1753 D BluetoothTile:  handleUpdatestate:false name:null
,08-24 14:31:46.796  1179  1753 D BluetoothTile:  handleUpdatestate:false name:null
,08-24 14:31:46.796  1179  1753 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-24 14:31:46.796  1018  3812 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-24 14:31:46.796  1018  1030 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-24 14:31:46.796  1179  1179 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-24 14:31:46.806   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-24 14:31:46.806  1874  1874 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-24 14:31:46.806  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:46.816  4761  4761 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-24 14:31:46.816  3217  3217 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@236bac86, channel: 5, state: LISTENING
08-24 14:31:46.816  3217  3217 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@236bac86, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2e48bfb0, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@190d7947mSocket: android.net.LocalSocket@199a7574 impl:android.net.LocalSocketImpl@2458a9d fd:FileDescriptor[82]
08-24 14:31:46.816  3217  3217 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@199a7574 impl:android.net.LocalSocketImpl@2458a9d fd:FileDescriptor[82]
,08-24 14:31:46.816  3217  3217 I BtOppRfcommListener: stopping Accept Thread
08-24 14:31:46.816  3217  3217 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3a460b12, channel: 12, state: LISTENING
08-24 14:31:46.816  3217  3217 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3a460b12, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1e7226dc, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@91e62e3mSocket: android.net.LocalSocket@2a374e0 impl:android.net.LocalSocketImpl@32753399 fd:FileDescriptor[87]
08-24 14:31:46.816  3217  3217 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2a374e0 impl:android.net.LocalSocketImpl@32753399 fd:FileDescriptor[87]
,08-24 14:31:46.816  3217  8076 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-24 14:31:46.816  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:46.826  3217  3217 V BluetoothOppManager: cleanUp...
,08-24 14:31:46.826  4761  4761 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-24 14:31:46.826  1018  1031 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-24 14:31:46.826  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-24 14:31:46.826  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:46.826  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-24 14:31:46.826  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-24 14:31:46.836  2653  2653 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 14:31:46.846  4761  4761 D DockEventReceiver: finishStartingService: stopping service
,08-24 14:31:46.846  4761  4761 D BluetoothNotiBroadcastReceiver: onReceive
,08-24 14:31:46.846  1179  1179 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-24 14:31:46.846  1179  1179 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-24 14:31:46.966  3217  3290 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-24 14:31:46.966  3217  3290 D BtConfig.SecureMode: isSecureModeOn:false
08-24 14:31:46.966  3217  3290 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-24 14:31:46.966  3217  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
08-24 14:31:46.966  3217  3290 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
08-24 14:31:46.966  3217  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-24 14:31:46.966  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-24 14:31:46.966  3217  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-24 14:31:46.966  1018  1449 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 14:31:46.966  1018  1449 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-24 14:31:46.966  1018  1449 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:46.966  1018  1449 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:46.966  1018  1449 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 14:31:46.966  3217  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,08-24 14:31:46.966  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-24 14:31:46.966  3217  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-24 14:31:46.966  1018  1441 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-24 14:31:46.966  1018  1441 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-24 14:31:46.966  1018  1441 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:46.966  1018  1441 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:46.966  1018  1441 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 14:31:46.976  3217  3217 D HeadsetService: Received stop request...Stopping profile...
,08-24 14:31:46.976  3217  3217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8e0de1
,08-24 14:31:46.976  3217  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-24 14:31:46.976  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-24 14:31:46.976  3217  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-24 14:31:46.976  1018  1018 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-24 14:31:46.976  1018  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 14:31:46.976  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-24 14:31:46.976  4761  4761 D HeadsetProfile: Bluetooth service disconnected
,08-24 14:31:46.976  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:46.976  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:46.976  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 14:31:46.976  3217  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-24 14:31:46.976  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-24 14:31:46.976  3217  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-24 14:31:46.976  1018  1508 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-24 14:31:46.976  1018  1508 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-24 14:31:46.976  1018  1508 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:46.976  1018  1508 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:46.976  1018  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 14:31:46.986  3217  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,08-24 14:31:46.986  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-24 14:31:46.986  3217  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-24 14:31:46.986  1018  1439 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-24 14:31:46.986  1018  1439 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-24 14:31:46.986  1018  1439 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:46.986  1018  1439 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:46.986  1018  1439 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 14:31:46.986  3217  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,08-24 14:31:46.986  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-24 14:31:46.986  3217  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-24 14:31:46.986  1018  1489 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 14:31:46.986  1018  1489 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-24 14:31:46.986  1018  1489 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:46.986  1018  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:46.986  1018  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 14:31:46.986  3217  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
,08-24 14:31:46.986  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-24 14:31:46.986  3217  3290 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-24 14:31:46.986  1018  1449 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 14:31:46.996  1018  1449 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-24 14:31:46.996  1018  1449 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:46.996  1018  1449 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:46.996  1018  1449 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-24 14:31:46.996  3217  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-24 14:31:46.996  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-24 14:31:46.996  3217  3290 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,08-24 14:31:46.996  3217  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-24 14:31:46.996  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-24 14:31:46.996  3217  3290 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-24 14:31:46.996  3217  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService,
08-24 14:31:46.996  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-24 14:31:46.996  3217  3290 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-24 14:31:46.996  3217  3290 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
,08-24 14:31:46.996  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-24 14:31:46.996  3217  3290 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-24 14:31:46.996  3217  3290 D BluetoothAdapterState: Stopping profile services that were post enabled
08-24 14:31:46.996  3217  3217 E BluetoothAdapterService(764284385): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-24 14:31:46.996  3217  3217 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-24 14:31:46.996  3217  3217 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-24 14:31:46.996  3217  3217 D A2dpService: Received stop request...Stopping profile...
,08-24 14:31:46.996  3217  8028 D A2dpStateMachine: Exit Disconnected: -1
,08-24 14:31:46.996  3217  3217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8e0de1
,08-24 14:31:46.996  1018  1018 D BluetoothA2dp: Proxy object disconnected
08-24 14:31:46.996  1018  1018 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-24 14:31:46.996  4761  4761 D BluetoothA2dp: Proxy object disconnected
08-24 14:31:46.996  4761  4761 D A2dpProfile: Bluetooth service disconnected
,08-24 14:31:46.996  3217  3217 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-24 14:31:46.996  3217  3217 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-24 14:31:47.006  3217  3217 D HidService: Received stop request...Stopping profile...
,08-24 14:31:47.006  3217  3217 D HidService: Stopping Bluetooth HidService
08-24 14:31:47.006  3217  3217 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-24 14:31:47.006  3217  3217 W bt-btif : cleanup: HH disabling or disabled already, status = 0
,08-24 14:31:47.006  3217  3217 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-24 14:31:47.006  3217  3217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8e0de1
,08-24 14:31:47.006  3217  3217 D HealthService: Received stop request...Stopping profile...
,08-24 14:31:47.006  3217  3217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8e0de1
,08-24 14:31:47.006  4761  4761 D BluetoothInputDevice: Proxy object disconnected
08-24 14:31:47.006  4761  4761 D HidProfile: Bluetooth service disconnected
,08-24 14:31:47.006  3217  3217 D PanService: Received stop request...Stopping profile...
,08-24 14:31:47.006  3217  3217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8e0de1
,08-24 14:31:47.006  1018  1018 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-24 14:31:47.006  3217  3217 D BluetoothMapService: Received stop request...Stopping profile...
,08-24 14:31:47.016  3217  3217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8e0de1
,08-24 14:31:47.016  3217  3217 D SapService: Received stop request...Stopping profile...
,08-24 14:31:47.016  3217  3217 D SapService: Stopping Bluetooth SapService
08-24 14:31:47.016  4761  4761 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-24 14:31:47.016  4761  4761 D PanProfile: Bluetooth service disconnected
,08-24 14:31:47.016  3217  3217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8e0de1
08-24 14:31:47.016  4761  4761 D BluetoothMap: Proxy object disconnected
08-24 14:31:47.016  4761  4761 D MapProfile: Bluetooth service disconnected
,08-24 14:31:47.016  3217  3217 E BluetoothAdapterService(764284385): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-24 14:31:47.016  3217  3217 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-24 14:31:47.016  3217  3217 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-24 14:31:47.016  3217  3217 D BluetoothA2dp: Proxy object disconnected
08-24 14:31:47.016  3217  3217 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-24 14:31:47.016  3217  8029 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-24 14:31:47.016  4761  4761 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-24 14:31:47.016  3217  3217 I GKI_LINUX: GKI_exit_task 2 done
08-24 14:31:47.016  3217  3217 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-24 14:31:47.016  4761  4761 D SapProfile: Bluetooth service disconnected
08-24 14:31:47.016  3217  3217 E BluetoothAdapterService(764284385): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-24 14:31:47.016  3217  3217 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-24 14:31:47.016  3217  3217 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-24 14:31:47.016  3217  3217 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-24 14:31:47.016  3217  3217 E BluetoothAdapterService(764284385): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
,08-24 14:31:47.016  3217  3217 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-24 14:31:47.026  3217  3217 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-24 14:31:47.026  3217  3217 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-24 14:31:47.026  3217  3217 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-24 14:31:47.026  3217  3217 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-24 14:31:47.026  3217  3217 E BluetoothAdapterService(764284385): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-24 14:31:47.026  3217  3217 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,08-24 14:31:47.026  3217  3217 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-24 14:31:47.026  3217  3217 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-24 14:31:47.026  3217  3217 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-24 14:31:47.026  3217  3217 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-24 14:31:47.026  3217  3217 E BluetoothAdapterService(764284385): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true,
08-24 14:31:47.026  3217  3217 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-24 14:31:47.026  3217  3217 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-24 14:31:47.026  3217  3217 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-24 14:31:47.026  3217  3217 E BluetoothAdapterService(764284385): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,08-24 14:31:47.026  3217  3217 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-24 14:31:47.026  3217  3217 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-24 14:31:47.026  3217  3217 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-24 14:31:47.026  3217  3290 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-24 14:31:47.026  3217  3290 D BluetoothAdapterProperties: Setting state to 10
08-24 14:31:47.026  3217  3290 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-24 14:31:47.026  3217  3290 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-24 14:31:47.026  3217  3290 D BluetoothAdapterService: updateAdapterState state is 10
,08-24 14:31:47.026  3217  3290 D BluetoothAdapterService: Autoconnection is available 
,08-24 14:31:47.026  3217  3290 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-24 14:31:47.026  3217  3290 I BluetoothAdapterState: Entering OffState
,08-24 14:31:47.026  1466  1490 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-24 14:31:47.026  1466  1490 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-24 14:31:47.026  4761  4773 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-24 14:31:47.036  3217  8055 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-24 14:31:47.036  3217  8055 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-24 14:31:47.036  4761  8037 D BluetoothPbap: onBluetoothStateChange: up=false
,08-24 14:31:47.036  1442  8048 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-24 14:31:47.036  1442  8048 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-24 14:31:47.036  1179  1191 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-24 14:31:47.036  1179  1191 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-24 14:31:47.036  4761  4770 D Bluetoothsap: onBluetoothStateChange: up=false
,08-24 14:31:47.036  4761  4770 D Bluetoothsap: Unbinding service...
,08-24 14:31:47.036  8038  8046 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-24 14:31:47.036  8038  8046 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-24 14:31:47.036  4761  4773 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-24 14:31:47.036  4761  8037 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-24 14:31:47.046  4761  8037 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-24 14:31:47.046  1755  1774 D BluetoothAdapter: onBluetoothStateChange: up=false
08-24 14:31:47.046  1755  1774 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-24 14:31:47.046  1453  1465 D BluetoothAdapter: onBluetoothStateChange: up=false
08-24 14:31:47.046  1453  1465 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-24 14:31:47.046  1018  1048 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-24 14:31:47.046  3217  3226 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-24 14:31:47.046  4761  4770 D BluetoothMap: onBluetoothStateChange: up=false
,08-24 14:31:47.046  2653  2666 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-24 14:31:47.046  2653  2666 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-24 14:31:47.046  7162  7175 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-24 14:31:47.046  7162  7175 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-24 14:31:47.046  7162  7175 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
,08-24 14:31:47.046  7162  7175 D BluetoothLeAdvertiser: Exit stop advertising
08-24 14:31:47.046  7162  7175 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
,08-24 14:31:47.046  7162  7175 D BluetoothLeScanner: Exiting stopAllScan
,08-24 14:31:47.056  1018  1048 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-24 14:31:47.056  1018  1048 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-24 14:31:47.056  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-24 14:31:47.056  1018  1018 I InputMethodManagerService: [BT Setting State] State =10
,08-24 14:31:47.056  1018  1018 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-24 14:31:47.056  1179  1179 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-24 14:31:47.066  1179  1179 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:47.066  1179  1179 D BluetoothTile:  getBluetoothState : 10
,08-24 14:31:47.066  1018  1449 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-24 14:31:47.066  1018  1492 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-24 14:31:47.066  1179  1179 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-24 14:31:47.076  4761  4761 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-24 14:31:47.076  1874  1874 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-24 14:31:47.076  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:47.076  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:47.076  4761  4761 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-24 14:31:47.086  1018  1449 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-24 14:31:47.086  1018  1449 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-24 14:31:47.086  1018  1449 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:47.086  1018  1449 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:47.086  1018  1449 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-24 14:31:47.086  2653  2653 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 14:31:47.096  4761  4761 D DockEventReceiver: finishStartingService: stopping service
,08-24 14:31:47.096  4761  4761 D BluetoothNotiBroadcastReceiver: onReceive
,08-24 14:31:47.096  1179  1179 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-24 14:31:47.096  1179  1179 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-24 14:31:47.706   288   288 E SMD     : DCD OFF
,08-24 14:31:47.806   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 14:31:48.806   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 14:31:49.366  1018  3385 D SSRM:n  : SIOP:: AP = 340
,08-24 14:31:49.736  7162  7437 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 14:31:49.736  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:31:49.806   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 14:31:50.336  1018  2070 V SAMP_SPCM_test: CSC File load.. 
,08-24 14:31:50.346  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,08-24 14:31:50.346  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
,08-24 14:31:50.346  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
08-24 14:31:50.346  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
,08-24 14:31:50.346  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
08-24 14:31:50.346  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
,08-24 14:31:50.346  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
08-24 14:31:50.346  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
,08-24 14:31:50.346  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
08-24 14:31:50.346  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
,08-24 14:31:50.356  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
08-24 14:31:50.356  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
08-24 14:31:50.356  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
08-24 14:31:50.356  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
08-24 14:31:50.356  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
08-24 14:31:50.356  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
08-24 14:31:50.356  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
08-24 14:31:50.356  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
08-24 14:31:50.356  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
08-24 14:31:50.356  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
08-24 14:31:50.356  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,08-24 14:31:50.386  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
,08-24 14:31:50.386  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
08-24 14:31:50.386  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory,
08-24 14:31:50.386  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
,08-24 14:31:50.386  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
08-24 14:31:50.386  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
08-24 14:31:50.386  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
,08-24 14:31:50.386  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
08-24 14:31:50.386  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
08-24 14:31:50.386  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
,08-24 14:31:50.386  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
08-24 14:31:50.386  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
08-24 14:31:50.386  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling,
08-24 14:31:50.386  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
08-24 14:31:50.386  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
,08-24 14:31:50.386  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
08-24 14:31:50.386  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
,08-24 14:31:50.386  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
08-24 14:31:50.386  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
,08-24 14:31:50.386  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
08-24 14:31:50.386  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,08-24 14:31:50.396  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
08-24 14:31:50.396  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
08-24 14:31:50.396  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
08-24 14:31:50.396  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
08-24 14:31:50.396  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
08-24 14:31:50.396  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
08-24 14:31:50.396  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
08-24 14:31:50.396  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
08-24 14:31:50.396  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
08-24 14:31:50.396  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
08-24 14:31:50.396  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
08-24 14:31:50.396  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
08-24 14:31:50.396  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
08-24 14:31:50.396  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
08-24 14:31:50.396  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
08-24 14:31:50.396  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
08-24 14:31:50.396  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
08-24 14:31:50.396  1018  2070 W DeviceAdminInfo: Unknown tag under, uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
08-24 14:31:50.396  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
08-24 14:31:50.396  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
08-24 14:31:50.396  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
08-24 14:31:50.396  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
08-24 14:31:50.396  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
08-24 14:31:50.396  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
08-24 14:31:50.396  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
08-24 14:31:50.396  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
08-24 14:31:50.396  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
08-24 14:31:50.396  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
08-24 14:31:50.396  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
08-24 14:31:50.396  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
08-24 14:31:50.396  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
08-24 14:31:50.396  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
08-24 14:31:50.396  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
08-24 14:31:50.396  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
08-24 14:31:50.396  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
,08-24 14:31:50.396  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
08-24 14:31:50.396  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
08-24 14:31:50.396  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
08-24 14:31:50.396  1018  2070 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,08-24 14:31:50.406  1018  2070 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
,08-24 14:31:50.406  1018  2070 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:50.406  1018  2070 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:50.406  1018  2070 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:50.406  1018  2070 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:50.426  1018  2070 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=8087 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-24 14:31:50.426  8087  8087 E Zygote  : MountEmulatedStorage(),
,08-24 14:31:50.426  8087  8087 E Zygote  : v2
08-24 14:31:50.426  8087  8087 I libpersona: KNOX_SDCARD checking this for 1000
08-24 14:31:50.426  8087  8087 I libpersona: KNOX_SDCARD not a persona,
,08-24 14:31:50.436  8087  8087 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-24 14:31:50.436  8087  8087 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-24 14:31:50.436  8087  8087 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-24 14:31:50.466  8087  8087 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:31:50.466  8087  8087 D ActivityThread: Added TimaKeyStore provider
,08-24 14:31:50.486  8087  8087 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-24 14:31:50.526  1018  1018 I ActivityManager: Killing 7693:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-24 14:31:50.526  1018  2070 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,08-24 14:31:50.706   288   288 E SMD     : DCD OFF,
,08-24 14:31:50.806   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 14:31:51.206  1018  3413 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 14:31:51.816   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-24 14:31:52.736  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 14:31:52.736  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@23a2daa2 added. We now have 6 listener(s)
,08-24 14:31:52.736  7162  7437 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 14:31:52.736  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 14:31:52.746  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@640a333 added. We now have 7 listener(s)
,08-24 14:31:52.746  7162  7437 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 14:31:52.746  7162  7437 I System.out: IsBluetoothEnabled
,08-24 14:31:52.746  7162  7437 D BluetoothAdapter: disable()
,08-24 14:31:52.746  1018  1441 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-24 14:31:52.756  7162  7437 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:52.756  7162  7437 D BluetoothAdapter: enable()
,08-24 14:31:52.756  1018  1217 W ActivityManager: Permission Denial: getCurrentUser() from pid=7162, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-24 14:31:52.756  1018  1217 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-24 14:31:52.756  1018  1217 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7162, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-24 14:31:52.756  1018  1217 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-24 14:31:52.756  1018  1217 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-24 14:31:52.756  1018  1217 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-24 14:31:52.756  1018  1217 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-24 14:31:52.756  1018  1217 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-24 14:31:52.756  1018  1217 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-24 14:31:52.756  1018  1217 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-24 14:31:52.766  1018  1217 D SettingsProvider: name = bluetooth_on
,08-24 14:31:52.766  1018  1048 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-24 14:31:52.766  1018  1048 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-24 14:31:52.776  1018  1048 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-24 14:31:52.776  3217  3290 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-24 14:31:52.776  3217  3290 D BluetoothAdapterProperties: Setting state to 11
,08-24 14:31:52.776  3217  3290 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-24 14:31:52.776  3217  3290 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-24 14:31:52.776  3217  3290 D BluetoothAdapterService: updateAdapterState state is 11
,08-24 14:31:52.776  3217  3290 D BluetoothAdapterService: Autoconnection is available 
,08-24 14:31:52.776  3217  3290 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
08-24 14:31:52.776  3217  3290 D BtConfig.SecureMode: isSecureModeOn:false
,08-24 14:31:52.776  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-24 14:31:52.776  3217  3290 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
08-24 14:31:52.776  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-24 14:31:52.776  3217  3290 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
08-24 14:31:52.776  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-24 14:31:52.776  3217  3290 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
,08-24 14:31:52.776  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-24 14:31:52.786  3217  3290 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
,08-24 14:31:52.786  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-24 14:31:52.786  3217  3290 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
08-24 14:31:52.786  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-24 14:31:52.786  3217  3290 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
08-24 14:31:52.786  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-24 14:31:52.786  3217  3290 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
08-24 14:31:52.786  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-24 14:31:52.786  3217  3290 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
08-24 14:31:52.786  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-24 14:31:52.786  3217  3290 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-24 14:31:52.786  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-24 14:31:52.786  3217  3290 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-24 14:31:52.786  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-24 14:31:52.786  3217  3290 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-24 14:31:52.786  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-24 14:31:52.786  3217  3290 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-24 14:31:52.786  3217  3290 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
08-24 14:31:52.786  3217  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-24 14:31:52.786  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-24 14:31:52.786  3217  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-24 14:31:52.786  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-24 14:31:52.786  1018  1018 I InputMethodManagerService: [BT Setting State] State =11
,08-24 14:31:52.786  1179  1179 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-24 14:31:52.796  1179  1179 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-24 14:31:52.796  1179  1179 D BluetoothTile:  getBluetoothState : 11
,08-24 14:31:52.796  1179  1753 D BluetoothTile:  handleUpdatestate:false name:null
,08-24 14:31:52.796  1179  1753 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-24 14:31:52.796  1874  1874 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-24 14:31:52.806  1018  1489 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-24 14:31:52.806  4761  4761 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-24 14:31:52.806  1018  1508 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-24 14:31:52.806  1179  1179 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-24 14:31:52.806  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:52.816  1018  1491 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-24 14:31:52.816  1018  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-24 14:31:52.816  1018  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:52.816  1018  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:52.816  1018  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 14:31:52.816  3217  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-24 14:31:52.816  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-24 14:31:52.816  3217  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-24 14:31:52.816  1018  1492 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 14:31:52.816  1018  1492 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-24 14:31:52.816  1018  1492 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:52.816  1018  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:52.816  1018  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 14:31:52.816  3217  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-24 14:31:52.816  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-24 14:31:52.816  3217  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-24 14:31:52.826  3217  3217 D HeadsetService: Received start request. Starting profile...
08-24 14:31:52.826  1018  1441 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 14:31:52.826  3217  3217 D HeadsetService: start()
08-24 14:31:52.826  1018  1441 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-24 14:31:52.826  3217  3217 D HeadsetStateMachine: make
08-24 14:31:52.826  1018  1441 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:52.826  1018  1441 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:52.826  1018  1441 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 14:31:52.826  3217  3217 E HeadsetStateMachine: # of Max HF connection is 2
,08-24 14:31:52.826  3217  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService,
08-24 14:31:52.826  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-24 14:31:52.826  3217  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-24 14:31:52.836  2653  2653 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 14:31:52.836  1018  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-24 14:31:52.836  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-24 14:31:52.836  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:52.836  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:52.836  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 14:31:52.836  1018  1439 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-24 14:31:52.836  3217  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,08-24 14:31:52.836  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-24 14:31:52.836  1018  1439 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-24 14:31:52.836  3217  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-24 14:31:52.836  1018  1439 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:52.836  1018  1439 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:52.836  1018  1439 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-24 14:31:52.846  1018  3812 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-24 14:31:52.846  1018  3812 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-24 14:31:52.846  1018  3812 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:52.846  1018  3812 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:52.846  1018  3812 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 14:31:52.846  1018  1489 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-24 14:31:52.846  1018  1489 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-24 14:31:52.846  3217  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,08-24 14:31:52.846  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-24 14:31:52.846  1018  1489 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:52.846  1018  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-24 14:31:52.846  3217  3290 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-24 14:31:52.856  1018  1217 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 14:31:52.846  1018  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-24 14:31:52.856  1018  1217 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-24 14:31:52.856  3217  3217 I bluedroid: get_profile_interface handsfree
,08-24 14:31:52.856  1018  1217 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:52.856  1018  1217 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:52.856  1018  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 14:31:52.856  3217  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-24 14:31:52.856  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-24 14:31:52.856  3217  3290 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-24 14:31:52.866  1018  1137 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-24 14:31:52.866  1018  1137 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-24 14:31:52.866  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:52.866  1018  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:52.866  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 14:31:52.866  3217  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-24 14:31:52.866  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-24 14:31:52.866  3217  3290 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-24 14:31:52.866  3217  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-24 14:31:52.866  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-24 14:31:52.866  3217  3290 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-24 14:31:52.866  3217  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-24 14:31:52.866  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-24 14:31:52.866  3217  3290 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-24 14:31:52.866  3217  3290 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-24 14:31:52.866  3217  3290 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-24 14:31:52.866  3217  3290 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-24 14:31:52.866  3217  3290 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-24 14:31:52.866  4761  4761 D BluetoothNotiBroadcastReceiver: onReceive
,08-24 14:31:52.876  3217  3217 E DualScoManager: Dual Sco Manager already instantiated
08-24 14:31:52.876  3217  3217 I DualScoManager: Set HeadsetServiceHelper
08-24 14:31:52.876  3217  3217 D BluetoothAtMessage: createCMTIContentObservers
08-24 14:31:52.876  1018  1030 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-24 14:31:52.876  1018  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 14:31:52.876  1018  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-24 14:31:52.876  1018  1030 D SettingsProvider: selectionArgs: false
08-24 14:31:52.876  1018  1030 D SettingsProvider: selectionArgs: 1002
08-24 14:31:52.876  1018  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-24 14:31:52.876  1018  1030 D SettingsProvider: ret = -1
08-24 14:31:52.876  3217  8106 D HeadsetStateMachine: Enter Disconnected: -2
,08-24 14:31:52.876  3217  3217 D HeadsetService: mStartError = false
08-24 14:31:52.876  3217  3217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8e0de1
08-24 14:31:52.876  1179  1179 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:52.876  1179  1179 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-24 14:31:52.876  3217  3217 D A2dpService: Received start request. Starting profile...
08-24 14:31:52.876  3217  3217 D A2dpService: start()
08-24 14:31:52.876  3217  3217 I bluedroid: get_profile_interface avrcp
,08-24 14:31:52.876  3217  8106 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-24 14:31:52.876  3217  8106 D HeadsetStateMachine: map size, before remove : 0
08-24 14:31:52.876  3217  8106 D HeadsetStateMachine: map size, after remove: 0
,08-24 14:31:52.886  3217  3217 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-24 14:31:52.886  3217  3217 D Avrcp   : Initialize Media Controller
08-24 14:31:52.886  3217  3217 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-24 14:31:52.886  3217  3217 E Avrcp   : getActiveSessions
,08-24 14:31:52.886  3217  3217 D Avrcp   : pick active media Controller
08-24 14:31:52.886  3217  3217 D Avrcp   : Get the active Media Controller 
,08-24 14:31:52.886  3217  3217 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-24 14:31:52.896  3217  8107 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-24 14:31:52.896  3217  3217 D A2dpStateMachine: make
,08-24 14:31:52.896  3217  3217 I bluedroid: get_profile_interface a2dp
,08-24 14:31:52.896  3217  8109 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-24 14:31:52.896  3217  3217 E bt-btif : warning : media task started media_task_refcnt 1 
,08-24 14:31:52.906  3217  3217 D A2dpService: mStartError = false
08-24 14:31:52.906  3217  3217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8e0de1
,08-24 14:31:52.906  3217  8108 D A2dpStateMachine: Enter Disconnected: -2
,08-24 14:31:52.906  3217  3217 D HidService: Received start request. Starting profile...
08-24 14:31:52.906  3217  3217 D HidService: start()
08-24 14:31:52.906  3217  3217 I bluedroid: get_profile_interface hidhost
08-24 14:31:52.906  3217  3217 D HidService: setHidService(): set to: null
08-24 14:31:52.906  3217  3217 D HidService: mStartError = false
08-24 14:31:52.906  3217  3217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8e0de1
,08-24 14:31:52.906  3217  3217 D HealthService: Received start request. Starting profile...
08-24 14:31:52.906  3217  3217 D HealthService: start()
,08-24 14:31:52.906  3217  8107 D BluetoothMediaBrowser: no now playing list
08-24 14:31:52.906  3217  8107 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-24 14:31:52.906  3217  3217 I bluedroid: get_profile_interface health
,08-24 14:31:52.906  3217  3217 D HealthService: mStartError = false
08-24 14:31:52.906  3217  3217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8e0de1
,08-24 14:31:52.906  3217  3217 D HeadsetStateMachine: Try to query the phonestate on bind
,08-24 14:31:52.906  1442  1462 I Telecom : BluetoothPhoneService: queryPhoneState
,08-24 14:31:52.906  1442  1442 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-24 14:31:52.906  1442  1442 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-24 14:31:52.906  1442  1462 I Telecom : BluetoothPhoneService: Result of Message : true
,08-24 14:31:52.916  3217  3217 D HeadsetStateMachine: Proxy object connected
,08-24 14:31:52.916  3217  3217 D PanService: Received start request. Starting profile...,
08-24 14:31:52.916  3217  3217 D PanService: start()
08-24 14:31:52.916  3217  3217 D BluetoothPanServiceJni: initializeNative(L110): pan
08-24 14:31:52.916  3217  3217 I bluedroid: get_profile_interface pan
08-24 14:31:52.916  3217  3217 D PanService: mStartError = false
08-24 14:31:52.916  3217  3217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8e0de1
08-24 14:31:52.916  3217  3217 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-24 14:31:52.916  3217  3217 D BluetoothMapService: Received start request. Starting profile...
08-24 14:31:52.916  3217  3217 D BluetoothMapService: start()
08-24 14:31:52.916  3217  8106 D HeadsetStateMachine: Disconnected process message: 11
,08-24 14:31:52.916  3217  3217 D BluetoothMapService: mStartError = false
,08-24 14:31:52.916  3217  3217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8e0de1
08-24 14:31:52.916  3217  3217 D HeadsetPhoneState: sendDeviceDataStateChanged
08-24 14:31:52.916  3217  3217 D HeadsetPhoneState: Signal level : previous=0 curr=4
,08-24 14:31:52.916  3217  8106 D HeadsetStateMachine: Disconnected process message: 18
,08-24 14:31:52.916  3217  3217 D SapService: Received start request. Starting profile...
08-24 14:31:52.916  3217  3217 D SapService: start()
08-24 14:31:52.916  3217  3217 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-24 14:31:52.916  3217  3217 I bluedroid: get_profile_interface sap
08-24 14:31:52.916  3217  3217 D SapService: mStartError = false
08-24 14:31:52.916  3217  3217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8e0de1
08-24 14:31:52.916  3217  3217 E BluetoothAdapterService(764284385): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-24 14:31:52.916  3217  3217 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 14:31:52.916  3217  3217 E BluetoothAdapterService(764284385): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-24 14:31:52.916  3217  3217 E BluetoothAdapterService(764284385): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,08-24 14:31:52.916  3217  8106 D HeadsetStateMachine: Disconnected process message: 10
08-24 14:31:52.916  3217  8106 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-24 14:31:52.916  3217  8106 D HeadsetStateMachine: Disconnected process message: 11
,08-24 14:31:52.926  3217  3217 E BluetoothAdapterService(764284385): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-24 14:31:52.926  3217  3217 E BluetoothAdapterService(764284385): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-24 14:31:52.936  3217  3217 E BluetoothAdapterService(764284385): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-24 14:31:52.936  3217  3217 E BluetoothAdapterService(764284385): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-24 14:31:52.936  3217  3290 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-24 14:31:52.936  3217  3290 I bluedroid: enable
,08-24 14:31:52.946  3217  3295 E bt-btif : Calling BTA_HhEnable
08-24 14:31:52.946  3217  3295 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-24 14:31:52.946  3217  3295 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-24 14:31:52.946  3217  3295 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
08-24 14:31:52.946  3217  3295 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
08-24 14:31:52.946  3217  3295 E BluetoothServiceJni: populateRssiValuesNative
08-24 14:31:52.946  3217  3295 I bluedroid: getModelRssiValues
08-24 14:31:52.946  3217  3295 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-24 14:31:52.946  3217  3295 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-24 14:31:52.946  3217  3295 D BluetoothAdapterProperties: Name is: Galaxy A3
,08-24 14:31:52.946  1018  1018 D SettingsProvider: name = bluetooth_name
,08-24 14:31:52.956  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:52.956  3217  3295 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-24 14:31:52.956  3217  3295 D BluetoothAdapterProperties: Scan Mode:20
08-24 14:31:52.956  3217  3295 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-24 14:31:52.956  3217  3295 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
,08-24 14:31:52.956  3217  3295 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
08-24 14:31:52.956  3217  3295 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,08-24 14:31:52.956  3217  3295 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,08-24 14:31:52.956  3217  3295 E bt-btif : JVenable fails
,08-24 14:31:52.956  3217  3295 D bte_conf: Device ID record 1 : primary
,08-24 14:31:52.956  3217  3295 D bte_conf:   vendorId            = 0075
08-24 14:31:52.956  3217  3295 D bte_conf:   vendorIdSource      = 0001
,08-24 14:31:52.956  3217  3295 D bte_conf:   product             = 0100
08-24 14:31:52.956  3217  3295 D bte_conf:   version             = 0200
08-24 14:31:52.956  3217  3295 D bte_conf:   clientExecutableURL = 
08-24 14:31:52.956  3217  3295 D bte_conf:   serviceDescription  = 
,08-24 14:31:52.956  3217  3295 D bte_conf:   documentationURL    = 
,08-24 14:31:52.966  3217  3295 D bte_conf: bte_load_did_conf no section named DID2.
,08-24 14:31:52.966  3217  3290 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-24 14:31:52.966  3217  3290 D BluetoothAdapterProperties: ScanMode =  20
08-24 14:31:52.966  3217  3290 D BluetoothAdapterProperties: State =  11
,08-24 14:31:52.966  1018  1441 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-24 14:31:52.966  3217  3290 D BluetoothAdapterProperties: Setting state to 12
,08-24 14:31:52.966  3217  3290 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-24 14:31:52.966  3217  3295 E bt-btif : BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
08-24 14:31:52.966  3217  3295 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-24 14:31:52.966  1018  3813 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-24 14:31:52.966  1018  3813 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 14:31:52.966  1018  3813 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-24 14:31:52.966  1018  3813 D SettingsProvider: selectionArgs: false
08-24 14:31:52.966  1018  3813 D SettingsProvider: selectionArgs: 1002
08-24 14:31:52.966  1018  3813 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-24 14:31:52.966  1018  3813 D SettingsProvider: ret = -1
,08-24 14:31:52.966  3217  3290 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-24 14:31:52.966  3217  3290 D BluetoothAdapterService: updateAdapterState state is 12
,08-24 14:31:52.966  1018  1217 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-24 14:31:52.966  1018  1217 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-24 14:31:52.976  1018  1217 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:52.976  1018  1217 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-24 14:31:52.976  1018  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 14:31:52.976  3217  3290 D BluetoothAdapterService: Autoconnection is available 
08-24 14:31:52.976  3217  3290 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-24 14:31:52.976  3217  3290 D BluetoothAdapterService: starting service from this receiver
,08-24 14:31:52.976  4761  8037 D BluetoothPan: Binding service...
,08-24 14:31:52.976  3217  3295 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-24 14:31:52.976  3217  3295 D BluetoothAdapterProperties: Scan Mode:21
08-24 14:31:52.976  3217  3295 D BluetoothAdapterProperties: Discoverable Timeout:120
08-24 14:31:52.976  1018  3812 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-24 14:31:52.976  1018  3812 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-24 14:31:52.976  1018  3812 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:52.976  1018  3812 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:52.976  1018  3812 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 14:31:52.986  3217  3217 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
08-24 14:31:52.986  3217  3217 I BluetoothPbapService: Handler(): got msg=1
,08-24 14:31:52.986  1018  1489 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-24 14:31:52.986  3217  3290 I BluetoothAdapterState: Entering On State from state = 11
,08-24 14:31:52.996  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:31:52.996  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:52.996  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:31:52.996  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 14:31:52.996  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:31:52.996  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:31:52.996  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:31:52.996  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 14:31:52.996  3217  8114 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-24 14:31:53.006  7162  7162 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 14:31:53.006  3217  8114 D BluetoothSocket: bindListen(): myUserId = 0
,08-24 14:31:53.006  3217  8114 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 14:31:53.006  3217  8114 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
,08-24 14:31:53.006  3217  8114 D BluetoothSocket: bindListen(), new LocalSocket 
08-24 14:31:53.006  3217  8114 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,08-24 14:31:53.006  3217  8114 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@29ccbd35
08-24 14:31:53.006  3217  8114 D BluetoothSocket: channel: 19
08-24 14:31:53.006  3217  8114 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-24 14:31:53.136  1018  1048 I art     : Explicit concurrent mark sweep GC freed 65780(3MB) AllocSpace objects, 9(145KB) LOS objects, 33% free, 23MB/34MB, paused 2.341ms total 151.878ms
08-24 14:31:53.136  1018  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-24 14:31:53.136  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-24 14:31:53.136  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:53.136  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:53.136  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-24 14:31:53.136  1466  7004 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-24 14:31:53.136  1466  7004 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-24 14:31:53.136  4761  4770 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-24 14:31:53.136  4761  4770 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-24 14:31:53.146  1018  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-24 14:31:53.146  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-24 14:31:53.146  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:53.146  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:53.146  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-24 14:31:53.146  3217  3226 D BluetoothAdapter: onBluetoothStateChange: up=true
08-24 14:31:53.146  3217  3226 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-24 14:31:53.146  4761  8037 D BluetoothPbap: onBluetoothStateChange: up=true
,08-24 14:31:53.146  4761  4761 D BluetoothPan: BluetoothPAN Proxy object connected
,08-24 14:31:53.146  4761  4761 D PanProfile: Bluetooth service connected
,08-24 14:31:53.146  1018  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-24 14:31:53.146  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-24 14:31:53.146  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:53.146  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:53.146  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-24 14:31:53.156  1442  8048 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-24 14:31:53.156  1442  8048 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-24 14:31:53.156  4761  4761 D BluetoothA2dp: Proxy object connected
,08-24 14:31:53.156  1179  1896 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-24 14:31:53.156  1179  1896 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-24 14:31:53.156  4761  4761 D A2dpProfile: Bluetooth service connected
08-24 14:31:53.156  1018  1048 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-24 14:31:53.156  1018  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-24 14:31:53.156  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-24 14:31:53.156  1018  1048 E BluetoothHeadset: BluetoothHeadset service is binded
08-24 14:31:53.156  4761  4770 D Bluetoothsap: onBluetoothStateChange: up=true
08-24 14:31:53.156  4761  4770 D Bluetoothsap: Binding service...
,08-24 14:31:53.156  4761  4770 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-24 14:31:53.156  1018  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-24 14:31:53.156  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-24 14:31:53.156  4761  4761 D BluetoothPbap: Proxy object connected
08-24 14:31:53.156  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:53.156  4761  4761 D PbapServerProfile: Bluetooth service connected
08-24 14:31:53.156  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:53.156  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-24 14:31:53.156  4761  4770 D Bluetoothsap: bindService called to Bluetooth SAP Service
08-24 14:31:53.156  8038  8047 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-24 14:31:53.156  8038  8047 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-24 14:31:53.166  4761  4761 D Bluetoothsap: BluetoothSAP Proxy object connected
08-24 14:31:53.166  4761  4761 D SapProfile: Bluetooth service connected
08-24 14:31:53.166  4761  4761 D Bluetoothsap: getConnectedDevices()
,08-24 14:31:53.166  4761  4773 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-24 14:31:53.166  1018  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-24 14:31:53.166  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-24 14:31:53.166  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:53.166  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:53.166  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-24 14:31:53.166  4761  4761 D BluetoothInputDevice: Proxy object connected
08-24 14:31:53.166  4761  4761 D HidProfile: Bluetooth service connected
,08-24 14:31:53.166  1442  1475 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-24 14:31:53.166  1018  1048 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-24 14:31:53.166  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-24 14:31:53.176  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:53.176  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:53.176  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-24 14:31:53.176  1442  1475 E BluetoothHeadset: BluetoothHeadset service is binded
,08-24 14:31:53.176  4761  8037 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-24 14:31:53.176  4761  8037 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-24 14:31:53.176  1755  2216 D BluetoothAdapter: onBluetoothStateChange: up=true
08-24 14:31:53.176  1755  2216 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-24 14:31:53.176  1453  1479 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-24 14:31:53.176  1453  1479 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-24 14:31:53.176  1442  8048 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-24 14:31:53.176  1018  1048 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-24 14:31:53.176  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-24 14:31:53.176  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:53.176  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:53.176  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-24 14:31:53.186  1442  8048 E BluetoothHeadset: BluetoothHeadset service is binded
,08-24 14:31:53.186  1018  1048 D BluetoothA2dp: onBluetoothStateChange: up=true
08-24 14:31:53.186  1018  1048 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-24 14:31:53.186  1018  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-24 14:31:53.186  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-24 14:31:53.186  1018  1018 D BluetoothA2dp: Proxy object connected
,08-24 14:31:53.186  1442  1475 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0,
08-24 14:31:53.186  1018  1048 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-24 14:31:53.186  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-24 14:31:53.186  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:53.186  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:53.186  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-24 14:31:53.186  1442  1475 E BluetoothHeadset: BluetoothHeadset service is binded
08-24 14:31:53.186  3217  3226 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-24 14:31:53.186  3217  3226 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-24 14:31:53.186  1018  1048 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-24 14:31:53.186  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-24 14:31:53.186  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:53.186  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:53.186  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 14:31:53.186  3217  3217 D BluetoothA2dp: Proxy object connected
08-24 14:31:53.186  3217  3217 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-24 14:31:53.196  1466  1670 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0,
,08-24 14:31:53.196  1018  1048 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-24 14:31:53.196  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-24 14:31:53.196  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:53.196  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:53.196  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-24 14:31:53.196  1466  1670 E BluetoothHeadset: BluetoothHeadset service is binded
,08-24 14:31:53.196  4761  4770 D BluetoothMap: onBluetoothStateChange: up=true
,08-24 14:31:53.196  1018  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-24 14:31:53.196  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-24 14:31:53.196  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:53.196  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:53.196  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-24 14:31:53.196  4761  4761 D BluetoothMap: Proxy object connected
,08-24 14:31:53.196  4761  4773 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-24 14:31:53.206  4761  4761 D MapProfile: Bluetooth service connected
,08-24 14:31:53.206  1018  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-24 14:31:53.206  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-24 14:31:53.206  4761  4761 D BluetoothMap: getConnectedDevices()
,08-24 14:31:53.206  1018  1048 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:53.206  1018  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:53.206  1018  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-24 14:31:53.206  4761  4773 E BluetoothHeadset: BluetoothHeadset service is binded
,08-24 14:31:53.206  2653  2711 D BluetoothAdapter: onBluetoothStateChange: up=true
08-24 14:31:53.206  2653  2711 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-24 14:31:53.206  7162  7177 D BluetoothAdapter: onBluetoothStateChange: up=true
08-24 14:31:53.206  7162  7177 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-24 14:31:53.206  1018  1048 D BluetoothAdapter: onBluetoothStateChange: up=true
08-24 14:31:53.206  1018  1048 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-24 14:31:53.206  1018  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-24 14:31:53.206  1018  1048 D BluetoothPan: Binding service...
08-24 14:31:53.206  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-24 14:31:53.206  1018  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-24 14:31:53.206  1018  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-24 14:31:53.206  1018  1018 D BluetoothPan: BluetoothPAN Proxy object connected
08-24 14:31:53.206  4761  4761 D HeadsetProfile: Bluetooth service connected
,08-24 14:31:53.206  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-24 14:31:53.206  1018  1018 I InputMethodManagerService: [BT Setting State] State =12
,08-24 14:31:53.206  1018  1018 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-24 14:31:53.206  1442  1442 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@34b29b5, true
,08-24 14:31:53.216  1442  1442 D BluetoothHeadset: registerMessageListener
,08-24 14:31:53.216  1179  1179 D BluetoothTile:  onBluetoothStateChange:
,08-24 14:31:53.216  1179  1179 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-24 14:31:53.216  1179  1753 D BluetoothTile:  handleUpdatestate:false name:null
,08-24 14:31:53.216  1179  1753 D BluetoothTile:  handleUpdatestate:false name:null
,08-24 14:31:53.226  1179  1179 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-24 14:31:53.226  1179  1179 D BluetoothTile:  getBluetoothState : 12
,08-24 14:31:53.226  1179  1753 D BluetoothTile:  handleUpdatestate:false name:null
,08-24 14:31:53.226  1874  1874 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-24 14:31:53.236  3217  7500 D HeadsetService: registerMessageListener
,08-24 14:31:53.236  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:53.236  1018  1492 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-24 14:31:53.236  3217  7500 D HeadsetService: registerMessageListener
,08-24 14:31:53.236  3217  8106 D HeadsetStateMachine: Disconnected process message: 70
,08-24 14:31:53.236  3217  8106 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@3dff9496
,08-24 14:31:53.236  1442  1442 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
,08-24 14:31:53.236  1442  1442 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-24 14:31:53.236  1018  1031 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-24 14:31:53.246  1179  1179 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-24 14:31:53.246  1442  1442 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-24 14:31:53.246  1442  1442 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-24 14:31:53.246  1442  1442 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-24 14:31:53.246  4761  4761 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-24 14:31:53.246  3217  8106 D HeadsetStateMachine: Disconnected process message: 9
08-24 14:31:53.246  3217  8106 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-24 14:31:53.246  3217  8115 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-24 14:31:53.246  4761  4761 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-24 14:31:53.246   283   283 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-24 14:31:53.246   283   283 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-24 14:31:53.246   283   283 V voice   : voice_set_parameters: exit with code(-2)
08-24 14:31:53.246   283   283 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-24 14:31:53.246   283   283 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-24 14:31:53.246   283   283 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-24 14:31:53.246   283   283 V audio_hw_primary: adev_set_parameters: exit
08-24 14:31:53.246  3217  8106 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-24 14:31:53.246  4761  4761 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-24 14:31:53.246  4761  4761 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-24 14:31:53.246  4761  4761 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-24 14:31:53.256  3217  8115 D BluetoothSocket: bindListen(): myUserId = 0
08-24 14:31:53.256  3217  8115 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 14:31:53.256  3217  8115 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
08-24 14:31:53.256  3217  8115 D BluetoothSocket: bindListen(), new LocalSocket 
08-24 14:31:53.256  3217  8115 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-24 14:31:53.256  3217  8115 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@71c2817
,08-24 14:31:53.256  3217  8115 D BluetoothSocket: channel: 5
,08-24 14:31:53.256  4761  4761 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-24 14:31:53.256  1018  1439 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-24 14:31:53.256  1018  1439 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-24 14:31:53.256  1018  1439 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:53.256  1018  1439 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-24 14:31:53.256  1018  1439 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-24 14:31:53.266  2653  2653 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 14:31:53.276  4761  4761 D DockEventReceiver: finishStartingService: stopping service
,08-24 14:31:53.276  4761  4761 D BluetoothNotiBroadcastReceiver: onReceive
,08-24 14:31:53.276  1179  1179 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-24 14:31:53.276  1179  1179 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-24 14:31:53.286  3217  3217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d8e0de1
,08-24 14:31:53.286  3217  3217 D BtConfig.SecureMode: isSecureModeOn:false,
08-24 14:31:53.286  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:53.286  1018  1137 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 14:31:53.286  1018  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:53.286  1018  1137 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0,
08-24 14:31:53.286  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
,08-24 14:31:53.296  1018  1449 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-24 14:31:53.306  3217  8120 D BluetoothSocket: bindListen(): myUserId = 0
08-24 14:31:53.306  3217  8120 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 14:31:53.306  3217  8120 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[87]}
,08-24 14:31:53.316  3217  8120 D BluetoothSocket: bindListen(), new LocalSocket 
08-24 14:31:53.316  3217  8120 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-24 14:31:53.316  3217  8120 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@19b12eb3
08-24 14:31:53.316  3217  8120 D BluetoothSocket: channel: 12
08-24 14:31:53.316  3217  8120 I BtOppRfcommListener: Accept thread started.
,08-24 14:31:53.426  1018  1097 V AlarmManager: waitForAlarm result :4
,08-24 14:31:53.436   278   979 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-24 14:31:53.436   278   979 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-24 14:31:53.446  1018  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:53.446  1018  1044 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-24 14:31:53.446  1018  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,08-24 14:31:53.716   288   288 E SMD     : DCD OFF,
,08-24 14:31:53.786  7162  7437 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:31:53.786  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:53.786  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:31:53.786  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 14:31:53.786  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:31:53.786  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:31:53.786  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:31:53.786  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 14:31:53.786  7162  7437 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null,
08-24 14:31:53.786  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-24 14:31:53.786  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7b136f0 added. We now have 8 listener(s)
08-24 14:31:53.786  7162  7437 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 14:31:53.796  1018  1030 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-24 14:31:53.796  1018  1030 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-24 14:31:53.796  1018  1030 D SecContentProvider2: mCursor = null
,08-24 14:31:53.796  1018  1030 D WifiService: setWifiEnabled: false pid=7162, uid=10170
,08-24 14:31:53.796  1018  1030 D SettingsProvider: name = wifi_on
,08-24 14:31:53.816  7162  7437 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:53.816  1018  1217 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-24 14:31:53.816  1018  1217 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-24 14:31:53.816  1018  1217 D SecContentProvider2: mCursor = null
,08-24 14:31:53.816  1018  1217 D WifiService: setWifiEnabled: true pid=7162, uid=10170
08-24 14:31:53.816  1018  1217 W ActivityManager: Permission Denial: getCurrentUser() from pid=7162, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-24 14:31:53.816  1018  1217 W WifiService: Failed getting userId using ActivityManagerNative
08-24 14:31:53.816  1018  1217 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7162, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-24 14:31:53.816  1018  1217 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-24 14:31:53.816  1018  1217 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-24 14:31:53.816  1018  1217 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-24 14:31:53.816  1018  1217 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-24 14:31:53.816  1018  1217 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-24 14:31:53.816  1018  1217 D SettingsProvider: name = wifi_on
,08-24 14:31:53.826  1018  1129 E WifiHW  : ##################### set firmware type 0 #####################
,08-24 14:31:53.826  1018  1489 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 14:31:53.826  1018  1489 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4255, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
08-24 14:31:53.826  1018  1489 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
08-24 14:31:53.826  1018  1489 D BatteryService: stay LED for charging
08-24 14:31:53.826  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 14:31:53.836  1018  1018 I MotionRecognitionService: Plugged
08-24 14:31:53.836  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-24 14:31:53.836  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 14:31:53.836  1424  1424 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-24 14:31:53.836  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
08-24 14:31:53.836  1424  1424 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 14:31:53.856  3217  3217 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 14:31:53.856  3217  8106 D HeadsetStateMachine: Disconnected process message: 10
,08-24 14:31:53.856  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-24 14:31:53.856  1179  1179 D SViewCoverView: level :100 plugged : 2
,08-24 14:31:53.866  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-24 14:31:53.866  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 14:31:53.866  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 14:31:54.166  1018  1046 D Tethering: interfaceAdded wlan0
,08-24 14:31:54.166  1018  1132 E Tethering: No numeric data
,08-24 14:31:54.166  1018  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-24 14:31:54.166  1018  1132 D Tethering: clearTetheredNotification()
,08-24 14:31:54.166  1179  1179 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-24 14:31:54.176  1179  1179 D HotspotTile: updateTetherState():false, false
08-24 14:31:54.176  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 14:31:54.176  1018  1126 V NetworkStats: performPollLocked(flags=0x1)
,08-24 14:31:54.176  1018  1126 D NetworkStatsFactory: UpdateStatsForKnox updated,
,08-24 14:31:54.176  1018  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-24 14:31:54.176  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit,
08-24 14:31:54.176  1018  1126 V NetworkStats: performPollLocked() took 5ms
,08-24 14:31:54.176  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false
,08-24 14:31:54.186  1018  1046 D Tethering: interfaceStatusChanged wlan0, false,
08-24 14:31:54.186  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-24 14:31:54.186  1018  1132 D Tethering: InitialState.processMessage what=4
,08-24 14:31:54.186  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 14:31:54.186  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 14:31:54.186  1018  1046 D Tethering: interfaceAdded p2p0
,08-24 14:31:54.196  1018  1132 E Tethering: No numeric data
,08-24 14:31:54.196   278   983 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-24 14:31:54.196   278   983 D SoftapController: Softap fwReload - Ok
,08-24 14:31:54.196  1018  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-24 14:31:54.196  1018  1132 D Tethering: clearTetheredNotification()
,08-24 14:31:54.196  1018  1046 D Tethering: p2p0 is not a tetherable iface, ignoring
08-24 14:31:54.196  1179  1179 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-24 14:31:54.196  1018  1046 D Tethering: interfaceLinkStateChanged p2p0, false
08-24 14:31:54.196  1179  1179 D HotspotTile: updateTetherState():false, false
08-24 14:31:54.196  1018  1046 D Tethering: interfaceStatusChanged p2p0, false
08-24 14:31:54.206  1018  1126 V NetworkStats: performPollLocked(flags=0x1)
08-24 14:31:54.196   278   983 D CommandListener: Setting iface cfg
08-24 14:31:54.206  1018  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-24 14:31:54.196   278   983 D CommandListener: Trying to bring down wlan0
08-24 14:31:54.206  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 14:31:54.206   278   983 D CommandListener: Clearing all IP addresses on wlan0
08-24 14:31:54.206  1018  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-24 14:31:54.206  1018  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-24 14:31:54.206  1018  1126 V NetworkStats: performPollLocked() took 5ms
08-24 14:31:54.206  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 14:31:54.206  1018  1129 E WifiHW  : supplicant_name : p2p_supplicant
08-24 14:31:54.206  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 14:31:54.206  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 14:31:54.256  8134  8134 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL,
08-24 14:31:54.256  8134  8134 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-24 14:31:54.256  8134  8134 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage,
,08-24 14:31:54.266  8134  8134 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
08-24 14:31:54.266   338   338 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 8134
08-24 14:31:54.266   338   338 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-24 14:31:54.266  8134  8134 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-24 14:31:54.266  8134  8134 I wpa_supplicant: ssSupport state is = 1
08-24 14:31:54.266  8134  8134 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-24 14:31:54.266  8134  8134 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-24 14:31:54.266   338   338 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 8134
08-24 14:31:54.266   338   338 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-24 14:31:54.316  1018  1129 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-24 14:31:54.326  4761  4761 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-24 14:31:54.336  1179  1179 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-24 14:31:54.336  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 14:31:54.336  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-24 14:31:54.336  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:54.336  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:54.336  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:54.336  1179  1179 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-24 14:31:54.336  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:54.336  1179  1179 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-24 14:31:54.336  1179  1179 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-24 14:31:54.336  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:31:54.336  1179  1753 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-24 14:31:54.336  1179  1179 D HotspotTile: onReceive : 2, 0
08-24 14:31:54.336  1018  1030 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-24 14:31:54.336  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-24 14:31:54.336  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:54.336  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:54.336  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-24 14:31:54.346  1628  1628 I Hs20UtilService: Starting #17
08-24 14:31:54.346  1628  1673 I Hs20UtilService: Message received 5011
08-24 14:31:54.346  7626  7626 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-24 14:31:54.346  7626  7626 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-24 14:31:54.346  7626  7626 D SecurityLogAgent: StateMachine : Current State = 1
08-24 14:31:54.346  7626  7626 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-24 14:31:54.436   338   338 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,08-24 14:31:54.436  8134  8134 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,08-24 14:31:54.486  8134  8134 I wpa_supplicant: Ctrl_iface: loading cred from phone
,08-24 14:31:54.486  8134  8134 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-24 14:31:54.496  8134  8134 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
,08-24 14:31:54.496   338   338 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 8134
,08-24 14:31:54.496   338   338 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-24 14:31:54.496  8134  8134 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-24 14:31:54.496  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-24 14:31:54.496  8134  8134 I wpa_supplicant: ssSupport state is = 1
,08-24 14:31:54.496  8134  8134 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-24 14:31:54.496  8134  8134 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-24 14:31:54.496  8134  8134 E wpa_supplicant: SIM READ ERROR
,08-24 14:31:54.496  8134  8134 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-24 14:31:54.496  8134  8134 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-24 14:31:54.496  8134  8134 E wpa_supplicant: SIM READ ERROR,
08-24 14:31:54.496  8134  8134 I wpa_supplicant: Blacklist: Clear (all) 
08-24 14:31:54.496  8134  8134 I wpa_supplicant: wpa_default_ap_write_once
,08-24 14:31:54.496  8134  8134 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-24 14:31:54.496  8134  8134 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-24 14:31:54.496  8134  8134 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
,08-24 14:31:54.496  8134  8134 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-24 14:31:54.496  8134  8134 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-24 14:31:54.496  8134  8134 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-24 14:31:54.496  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false
08-24 14:31:54.496  1018  1046 D Tethering: interfaceStatusChanged wlan0, false
,08-24 14:31:54.596  8134  8134 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-24 14:31:54.726  8134  8134 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-24 14:31:54.726  8134  8134 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,08-24 14:31:54.736  8134  8134 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
,08-24 14:31:54.736   338   338 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 8134
,08-24 14:31:54.746   338   338 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-24 14:31:54.746  8134  8134 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-24 14:31:54.746  8134  8134 I wpa_supplicant: ssSupport state is = 1
,08-24 14:31:54.746  8134  8134 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-24 14:31:54.746  8134  8134 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-24 14:31:54.756  8134  8134 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-24 14:31:54.756   338   338 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 8134
,08-24 14:31:54.756   338   338 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,08-24 14:31:54.756  8134  8134 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-24 14:31:54.756  8134  8134 I wpa_supplicant: ssSupport state is = 1
08-24 14:31:54.756  8134  8134 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-24 14:31:54.756  8134  8134 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-24 14:31:54.756  8134  8134 E wpa_supplicant: SIM READ ERROR
08-24 14:31:54.756  8134  8134 I wpa_supplicant: wpa_default_ap_write_once,
08-24 14:31:54.756  8134  8134 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-24 14:31:54.756  8134  8134 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-24 14:31:54.766  1018  1046 D Tethering: interfaceLinkStateChanged p2p0, false,
08-24 14:31:54.766  1018  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-24 14:31:54.766  1018  1046 D Tethering: interfaceStatusChanged p2p0, false,
,08-24 14:31:54.766  1018  1046 D Tethering: interfaceLinkStateChanged p2p0, false,
08-24 14:31:54.766  1018  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-24 14:31:54.766  1018  1046 D Tethering: interfaceStatusChanged p2p0, false,
,08-24 14:31:54.806  8134  8134 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-24 14:31:54.806  8134  8134 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-24 14:31:54.916  8134  8134 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-24 14:31:54.916  8134  8134 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=,
08-24 14:31:54.916  8134  8134 I wpa_supplicant: Skip scan - bUseNetwork false,
,08-24 14:31:54.926  1018  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
08-24 14:31:54.926  1018  1129 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-24 14:31:54.926  8134  8134 I wpa_supplicant: HOTSPOT20_ENABLE called,
08-24 14:31:54.936  8134  8134 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-24 14:31:54.936  8134  8134 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-24 14:31:54.936  8134  8134 E wpa_supplicant: SIM READ ERROR
,08-24 14:31:54.936  8134  8134 I wpa_supplicant: Blacklist: Clear (all) ,
,08-24 14:31:54.956  8134  8134 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-24 14:31:54.966  8134  8134 I wpa_supplicant: Skip scan - bUseNetwork false,
08-24 14:31:54.966  1018  1129 D WifiConfigStore: Loading config and enabling all networks 
,08-24 14:31:54.976  1179  1179 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-24 14:31:54.976  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 14:31:54.976  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-24 14:31:54.976  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 14:31:54.976  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:54.976  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 14:31:54.976  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:54.976  1179  1179 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-24 14:31:54.976  1179  1179 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-24 14:31:54.976  4761  4761 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-24 14:31:54.976  1179  1753 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-24 14:31:54.976  1179  1179 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-24 14:31:54.976  1179  1179 D HotspotTile: onReceive : 3, 0
,08-24 14:31:54.986  1018  1217 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-24 14:31:54.986  1018  1217 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-24 14:31:54.986  1018  1217 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:54.986  1018  1129 E WifiConfigStore: Not a HS20
,08-24 14:31:54.986  1018  1217 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-24 14:31:54.986  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:31:54.986  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:54.986  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:31:54.986  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:31:54.986  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:31:54.986  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:31:54.986  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:31:54.986  7162  7162 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 14:31:54.986  1018  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-24 14:31:54.986  1018  1129 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-24 14:31:54.986  7162  7162 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 14:31:54.996  1628  1628 I Hs20UtilService: Starting #18
,08-24 14:31:54.996  1628  1673 I Hs20UtilService: Message received 5011
,08-24 14:31:54.996  1018  1129 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-24 14:31:54.996  8134  8134 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-24 14:31:54.996  8134  8134 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-24 14:31:54.996  8134  8134 I wpa_supplicant: reset timer : RESET_TIMER 0
08-24 14:31:54.996  8134  8134 I wpa_supplicant: P2P: Current p2p state = IDLE
08-24 14:31:54.996  8134  8134 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-24 14:31:54.996  8134  8134 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-24 14:31:54.996  8134  8134 I wpa_supplicant: First Scan Start
,08-24 14:31:54.996  8134  8134 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-24 14:31:54.996  1018  1129 D WifiNative-wlan0: Setting external_sim to 1
,08-24 14:31:54.996  1018  1129 D WifiStateMachine: Setting OUI to DA-A1-19
,08-24 14:31:54.996  1018  1129 I WifiNative-HAL: startHal
08-24 14:31:54.996  1018  1129 E wifi    : getStaticLongField sWifiHalHandle 0x9f31f88c
08-24 14:31:54.996  1018  1129 I WifiNative-HAL: Could not start hal
,08-24 14:31:55.006  7626  7626 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-24 14:31:55.006  7626  7626 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-24 14:31:55.006  7626  7626 D SecurityLogAgent: StateMachine : Current State = 1
08-24 14:31:55.006  7626  7626 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-24 14:31:55.006  7603  7603 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 14:31:55.006  1018  1129 E WifiNative-wlan0: do suspend true
,08-24 14:31:55.006  1018  1128 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-24 14:31:55.006   278   983 D CommandListener: Setting iface cfg
,08-24 14:31:55.006   278   983 D CommandListener: Trying to bring up p2p0
08-24 14:31:55.006  1018  1128 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-24 14:31:55.006  1018  1128 D WifiP2pService: P2pEnablingState
08-24 14:31:55.006  1018  1128 D WifiP2pService: P2pEnablingState{ what=147457 }
08-24 14:31:55.006  1018  1128 D WifiP2pService: P2p socket connection successful,
,08-24 14:31:55.006  1018  1128 D WifiP2pService: P2pEnabledState
08-24 14:31:55.016  1018  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-24 14:31:55.016  1018  1018 D WifiScanningService: SCAN_AVAILABLE : 3
08-24 14:31:55.016  1018  1153 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:55.016  1018  1153 I WifiNative-HAL: startHal
08-24 14:31:55.016  1018  1153 E wifi    : getStaticLongField sWifiHalHandle 0x9e1e19bc
08-24 14:31:55.016  1018  1153 I WifiNative-HAL: Could not start hal
08-24 14:31:55.016  1018  1153 E WifiScanningService: could not start HAL,
08-24 14:31:55.016  1018  1018 D RttService: SCAN_AVAILABLE : 3
08-24 14:31:55.016  1018  1128 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-24 14:31:55.016  1018  1154 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-24 14:31:55.016  1018  1129 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-24 14:31:55.016  1018  1129 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-24 14:31:55.016  1018  1129 E WifiNative-wlan0: invaild command id : 215
08-24 14:31:55.016  1018  1129 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-24 14:31:55.016  1018  1129 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-24 14:31:55.016  1018  1129 E WifiNative-wlan0: invaild command id : 215
08-24 14:31:55.016  8134  8134 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-24 14:31:55.016  8134  8134 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-24 14:31:55.016  1018  1131 E ConnectivityService: updateNetworkInfo()
,08-24 14:31:55.026  1018  1018 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-24 14:31:55.026  8134  8134 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-24 14:31:55.026  1018  1129 E WifiStateMachine: Failed to set frequency band 0
,08-24 14:31:55.026  1018  1049 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-24 14:31:55.026  1018  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-24 14:31:55.026  1018  1049 D WifiDisplayController: disconnect
08-24 14:31:55.026  1018  1049 D WifiDisplayController: updateConnection
08-24 14:31:55.026  1018  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-24 14:31:55.026  1018  1049 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-24 14:31:55.026  1018  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-24 14:31:55.026  1018  1129 D SecContentProvider2: mCursor = null
,08-24 14:31:55.026  1018  1128 D WifiNative-p2p0: p2pGetDeviceAddress
,08-24 14:31:55.026  1018  1128 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
08-24 14:31:55.026  1179  1179 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-24 14:31:55.026  1018  1030 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-24 14:31:55.026  1179  1179 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-24 14:31:55.026  1018  1049 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 14:31:55.026  1018  1049 D WifiDisplayAdapter: onP2pDisconnected
08-24 14:31:55.026  1018  1049 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-24 14:31:55.026  1018  1049 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-24 14:31:55.036  1018  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-24 14:31:55.036  4761  4761 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-24 14:31:55.036  1018  1129 D SecContentProvider2: mCursor = null
,08-24 14:31:55.036  4761  4761 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-24 14:31:55.036  4761  4761 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-24 14:31:55.036  1018  1128 D WifiP2pService: DeviceAddress: 0a:75:42
,08-24 14:31:55.036  4761  4761 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-24 14:31:55.036  4761  4761 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-24 14:31:55.036  4761  4761 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-24 14:31:55.036  1018  1049 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
08-24 14:31:55.036  1018  1049 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
08-24 14:31:55.036  1018  1049 D WifiDisplayController:  primary type: 10-0050F204-5
08-24 14:31:55.036  1018  1049 D WifiDisplayController:  secondary type: null
08-24 14:31:55.036  1018  1049 D WifiDisplayController:  wps: 0
08-24 14:31:55.036  1018  1049 D WifiDisplayController:  grpcapab: 0
08-24 14:31:55.036  1018  1049 D WifiDisplayController:  devcapab: 0
08-24 14:31:55.036  1018  1049 D WifiDisplayController:  status: 3
08-24 14:31:55.036  1018  1049 D WifiDisplayController:  wfdInfo: null
08-24 14:31:55.036  1018  1049 D WifiDisplayController:  groupownerAddress: null
08-24 14:31:55.036  1018  1049 D WifiDisplayController:  GOdeviceName: null
08-24 14:31:55.036  1018  1049 D WifiDisplayController:  interfaceAddress: 
08-24 14:31:55.036  1018  1049 D WifiDisplayController:  SConnectInfo : null
,08-24 14:31:55.036  4761  4844 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-24 14:31:55.046  7949  7949 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-24 14:31:55.046  7949  7949 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-24 14:31:55.046  7949  7949 D FileShare-Client: Outbound.stopDelayTimer - 
,08-24 14:31:55.056  1018  1128 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-24 14:31:55.056  1018  1128 D WifiP2pService: InactiveState
,08-24 14:31:55.056  1018  1128 D WifiP2pService: InactiveState{ what=143376 }
,08-24 14:31:55.056  1018  1128 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-24 14:31:55.056  8134  8134 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-24 14:31:55.056  7588  7588 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-24 14:31:55.056  1018  1128 D WifiP2pService: InactiveState{ what=143376 }
,08-24 14:31:55.056  1018  1128 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-24 14:31:55.176  1018  1046 D Tethering: interfaceLinkStateChanged p2p0, false
,08-24 14:31:55.176  1018  1046 D Tethering: interfaceStatusChanged p2p0, false
,08-24 14:31:55.176  1018  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-24 14:31:55.846  7162  7437 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 14:31:55.846  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:55.846  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:31:55.846  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:31:55.846  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:31:55.846  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:31:55.846  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:31:55.846  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 14:31:55.846  7162  7437 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 14:31:55.856  7162  7437 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-24 14:31:55.856  7162  7437 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-24 14:31:55.856  7162  7437 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@c0a0ab7 Bundle[{}]
,08-24 14:31:55.856  7162  7437 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-24 14:31:55.856  7162  7437 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-24 14:31:55.856  7162  7437 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-24 14:31:55.856  7162  7437 D io.jxcore.node.LifeCycleMonitor: onActivityStopped,
08-24 14:31:55.856  7162  7437 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-24 14:31:55.856  7162  7437 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-24 14:31:55.866  7162  7437 I System.out: Running OutgoingSocketThread
,08-24 14:31:55.866  7162  8144 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1454),
08-24 14:31:55.866  7162  8144 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 60384,
08-24 14:31:55.866  7162  8144 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-24 14:31:56.266  8134  8134 I wpa_supplicant: nl80211: Received scan results (29 BSSes),
,08-24 14:31:56.266  8134  8134 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-24 14:31:56.276  1018  8140 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700',
08-24 14:31:56.276  8134  8134 I wpa_supplicant: Trying to associate with SSID '4E47373030'
,08-24 14:31:56.276  8134  8134 I wpa_supplicant: Trying to associate with  'G700'
,08-24 14:31:56.276  8134  8134 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,08-24 14:31:56.276  8134  8134 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030,
,08-24 14:31:56.286  1018  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-24 14:31:56.296  1018  1129 D SecContentProvider2: mCursor = null
,08-24 14:31:56.396  8134  8134 E wpa_supplicant: Cmd 35605 not handled
,08-24 14:31:56.396  8134  8134 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-24 14:31:56.396  8134  8134 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-24 14:31:56.396  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false
08-24 14:31:56.396  8134  8134 I wpa_supplicant: Associated with F4.99.3E
08-24 14:31:56.396  1018  1046 D Tethering: interfaceStatusChanged wlan0, false
08-24 14:31:56.396  8134  8134 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-24 14:31:56.396  8134  8134 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-24 14:31:56.396  8134  8134 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-24 14:31:56.396  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, false
08-24 14:31:56.396  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-24 14:31:56.396  1018  1046 D Tethering: interfaceStatusChanged wlan0, false
08-24 14:31:56.396  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-24 14:31:56.396  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, true,
08-24 14:31:56.396  1018  1046 D Tethering: interfaceStatusChanged wlan0, true,
08-24 14:31:56.396  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-24 14:31:56.396  1018  1132 E Tethering: No numeric data
08-24 14:31:56.396  1018  1126 V NetworkStats: performPollLocked(flags=0x1)
08-24 14:31:56.396  1018  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-24 14:31:56.396  1179  1179 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-24 14:31:56.396  1018  1132 D Tethering: clearTetheredNotification()
08-24 14:31:56.396  1179  1179 D HotspotTile: updateTetherState():false, false
08-24 14:31:56.396  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 14:31:56.396  1018  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-24 14:31:56.396  1018  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-24 14:31:56.406  8134  8134 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-24 14:31:56.406  8134  8134 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-24 14:31:56.406  8134  8134 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-24 14:31:56.406  1018  1126 V NetworkStats: performPollLocked() took 7ms
08-24 14:31:56.406  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 14:31:56.406  8134  8134 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-24 14:31:56.406  8134  8134 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-24 14:31:56.406  8134  8134 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-24 14:31:56.406  8134  8134 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
,08-24 14:31:56.406  8134  8134 I wpa_supplicant: Blacklist: Clear (temp) 
08-24 14:31:56.406  8134  8134 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-24 14:31:56.406  1018  1046 D Tethering: interfaceLinkStateChanged wlan0, true
08-24 14:31:56.406  1018  1046 D Tethering: interfaceStatusChanged wlan0, true
08-24 14:31:56.406  1018  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-24 14:31:56.406  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 14:31:56.406  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 14:31:56.416  1018  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-24 14:31:56.416  1018  1129 D SecContentProvider2: mCursor = null
,08-24 14:31:56.416  1018  1129 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-24 14:31:56.426  1018  1129 E WifiConfigStore: setLastSelectedConfiguration -1
,08-24 14:31:56.426  1018  1129 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-24 14:31:56.426  1018  1131 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-24 14:31:56.426  1018  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-24 14:31:56.426  1018  1131 E ConnectivityService: updateNetworkInfo()
,08-24 14:31:56.426  1179  1179 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-24 14:31:56.426  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-24 14:31:56.426  1018  1129 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-24 14:31:56.426  1018  1491 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-24 14:31:56.426  1018  1491 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-24 14:31:56.436  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-24 14:31:56.436  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:56.436  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:56.436  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:56.436  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:56.436  1018  1491 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:56.436  1018  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:56.436  1018  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-24 14:31:56.436  1628  1628 I Hs20UtilService: Starting #19,
,08-24 14:31:56.436  1628  1673 I Hs20UtilService: Message received 5007
,08-24 14:31:56.436  4761  4761 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
08-24 14:31:56.436  4761  4761 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-24 14:31:56.436  4761  4761 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-24 14:31:56.436  4761  4761 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-24 14:31:56.436  4761  4761 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-24 14:31:56.436  4761  4761 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-24 14:31:56.446  4761  4844 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-24 14:31:56.446  1018  1129 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-24 14:31:56.466   278   983 D CommandListener: Setting iface cfg
,08-24 14:31:56.466  1018  1129 E WifiStateMachine: Start Dhcp Watchdog 2
,08-24 14:31:56.466  1018  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-24 14:31:56.466  1018  1129 D SecContentProvider2: mCursor = null
,08-24 14:31:56.476  1018  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-24 14:31:56.476  1018  1129 D SecContentProvider2: mCursor = null
,08-24 14:31:56.486  1179  1179 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-24 14:31:56.486  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-24 14:31:56.486  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-24 14:31:56.486  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 14:31:56.486  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 14:31:56.486  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 14:31:56.486  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 14:31:56.496  1018  1129 E WifiNative-wlan0: do suspend false
,08-24 14:31:56.496  1018  1128 D WifiP2pService: InactiveState{ what=143375 },
08-24 14:31:56.496  1018  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-24 14:31:56.496  1018  1128 D WifiP2pService: P2pEnabledState{ what=143375 }
08-24 14:31:56.496  1018  1129 D SecContentProvider2: mCursor = null
,08-24 14:31:56.706   288   288 E SMD     : DCD OFF
,08-24 14:31:56.716  8147  8147 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-24 14:31:56.716  8147  8147 I dhcpcd  : version 5.5.6 starting,
,08-24 14:31:56.726  8147  8147 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-24 14:31:56.776  8147  8147 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-24 14:31:56.776  8147  8147 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-24 14:31:56.776  8147  8147 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E),
,08-24 14:31:56.776  8147  8147 I dhcpcd  : bssid match
,08-24 14:31:56.786  8147  8147 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
,08-24 14:31:56.856  8147  8147 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1,
,08-24 14:31:56.866  7162  7437 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1455)
,08-24 14:31:56.866  7162  7437 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1455)
08-24 14:31:56.866  7162  7437 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1460)
08-24 14:31:56.866  7162  7437 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-24 14:31:56.866  7162  7437 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1461)
,08-24 14:31:56.876  7162  7437 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 14:31:56.876  7162  7437 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32d1b469 added. We now have 2 listener(s)
08-24 14:31:56.876  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41",
08-24 14:31:56.876  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 14:31:56.876  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 14:31:56.876  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:31:56.876  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a77feee added. We now have 9 listener(s)
08-24 14:31:56.876  7162  7437 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 14:31:56.876  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 14:31:56.886  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 14:31:56.886  7162  7437 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:31:56.886  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:56.886  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:31:56.886  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:31:56.886  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:31:56.886  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:31:56.886  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:31:56.886  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 14:31:56.886  7162  7437 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 14:31:56.886  7162  7437 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 14:31:56.896  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:56.896  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:56.896  7162  7437 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 14:31:56.896  7162  7437 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d0ad21c added. We now have 3 listener(s)
,08-24 14:31:56.896  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-24 14:31:56.896  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 14:31:56.896  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 14:31:56.896  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:31:56.896  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17482e25 added. We now have 10 listener(s)
08-24 14:31:56.896  7162  7437 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 14:31:56.896  7162  7437 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:31:56.896  7162  7437 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:31:56.896  7162  7437 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:31:56.896  7162  7437 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:56.896  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:56.896  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 14:31:56.896  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 14:31:56.896  7162  7437 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32d1b469 removed from the list
08-24 14:31:56.896  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:56.896  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a77feee removed from the list
08-24 14:31:56.896  7162  7437 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:31:56.896  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:56.896  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:56.896  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:31:56.896  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 14:31:56.896  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:31:56.896  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:56.896  7162  7437 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a77feee not in the list
08-24 14:31:56.896  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:56.896  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:31:56.906  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:31:56.906  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:31:56.906  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:56.906  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17482e25 removed from the list
08-24 14:31:56.906  7162  7437 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:56.906  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:56.906  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:56.906  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 14:31:56.906  7162  7437 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d0ad21c removed from the list
,08-24 14:31:56.906  7162  7437 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 14:31:56.906  7162  7437 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d691bfa added. We now have 2 listener(s)
,08-24 14:31:56.906  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-24 14:31:56.906  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 14:31:56.906  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 14:31:56.906  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 14:31:56.906  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a345ab added. We now have 9 listener(s)
08-24 14:31:56.906  7162  7437 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 14:31:56.906  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 14:31:56.916  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 14:31:56.916  7162  7437 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:31:56.916  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:56.916  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:31:56.916  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:31:56.916  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:31:56.916  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:31:56.916  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:31:56.916  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 14:31:56.916  7162  7437 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 14:31:56.916  7162  7437 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 14:31:56.916  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:56.916  7162  7437 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 14:31:56.916  7162  7437 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bf287a1 added. We now have 3 listener(s)
,08-24 14:31:56.926  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:56.926  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-24 14:31:56.926  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 14:31:56.926  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 14:31:56.926  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 14:31:56.926  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@231cfdc6 added. We now have 10 listener(s)
08-24 14:31:56.926  7162  7437 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 14:31:56.926  7162  7437 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 14:31:56.926  7162  7437 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-24 14:31:56.926  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 14:31:56.926  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 14:31:56.926  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-24 14:31:56.926  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-24 14:31:56.936  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-24 14:31:56.936  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
,08-24 14:31:56.936  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-24 14:31:56.936  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-24 14:31:56.936  7162  7437 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-24 14:31:56.946  3217  3352 D BtGatt.GattService: registerClient() - UUID=efe269fe-a4f9-4caa-9570-8a6bf1acc600
,08-24 14:31:56.946  8147  8147 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds
,08-24 14:31:56.986  3217  3295 D BtGatt.GattService: onClientRegistered() - UUID=efe269fe-a4f9-4caa-9570-8a6bf1acc600, clientIf=6
,08-24 14:31:56.986  7162  7175 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-24 14:31:56.986  3217  7500 D BtGatt.GattService: start scan with filters
08-24 14:31:56.986  3217  3354 D BtGatt.ScanManager: handling starting scan
08-24 14:31:56.986  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-24 14:31:56.986  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-24 14:31:56.986  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-24 14:31:56.986  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-24 14:31:56.996  7162  7437 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 14:31:56.996  7162  7437 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-24 14:31:56.996  7162  7162 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-24 14:31:56.996  3217  3295 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-24 14:31:56.996  3217  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-24 14:31:56.996  3217  3354 D BtGatt.ScanManager: allow scan with filters
08-24 14:31:56.996  3217  3354 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-24 14:31:56.996  3217  3354 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
,08-24 14:31:57.006  3217  3295 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-24 14:31:57.006  3217  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-24 14:31:57.006  3217  3354 D BtGatt.ScanManager: Starting BLE batch scan
08-24 14:31:57.006  3217  3354 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-24 14:31:57.006  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
,08-24 14:31:57.016  3217  3295 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-24 14:31:57.016  3217  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-24 14:31:57.016  7162  7437 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-24 14:31:57.016  7162  7437 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-24 14:31:57.016  7162  7437 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-24 14:31:57.016  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:57.016  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 14:31:57.016  7162  7437 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-24 14:31:57.016  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 14:31:57.016  7162  7437 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-24 14:31:57.016  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-24 14:31:57.016  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-24 14:31:57.016  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-24 14:31:57.016  3217  8055 D BtGatt.GattService: stopScan() - queue size =1
,08-24 14:31:57.016  3217  3226 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-24 14:31:57.016  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-24 14:31:57.016  3217  3295 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-24 14:31:57.016  3217  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 14:31:57.026  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-24 14:31:57.026  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-24 14:31:57.026  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-24 14:31:57.026  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-24 14:31:57.026  3217  3354 D BtGatt.ScanManager: filter size is 1
,08-24 14:31:57.026  3217  3354 D BtGatt.ScanManager: delete FilterIndex - 6
,08-24 14:31:57.026  7162  7437 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
08-24 14:31:57.026  3217  3295 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
08-24 14:31:57.026  3217  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-24 14:31:57.026  3217  3354 D BtGatt.ScanManager: stopping BLe Batch
,08-24 14:31:57.036  3217  3295 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-24 14:31:57.036  3217  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-24 14:31:57.036  3217  3354 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-24 14:31:57.036  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-24 14:31:57.036  7162  7437 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-24 14:31:57.036  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-24 14:31:57.036  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 14:31:57.046  3217  3295 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
08-24 14:31:57.046  3217  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 14:31:57.046  7162  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
08-24 14:31:57.046  7162  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 14:31:57.046  7162  7162 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
,08-24 14:31:57.056  7162  7437 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-24 14:31:57.056  7162  7437 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:31:57.056  7162  7437 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-24 14:31:57.056  7162  7437 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:57.056  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:57.056  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 14:31:57.056  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
08-24 14:31:57.056  7162  7437 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d691bfa removed from the list
08-24 14:31:57.056  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:57.056  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a345ab removed from the list
08-24 14:31:57.056  7162  7437 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 14:31:57.056  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:57.056  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:57.056  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,08-24 14:31:57.056  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:31:57.056  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-24 14:31:57.056  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:57.056  7162  7437 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a345ab not in the list
08-24 14:31:57.056  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-24 14:31:57.056  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:57.056  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-24 14:31:57.056  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:31:57.056  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 14:31:57.056  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@231cfdc6 removed from the list
08-24 14:31:57.056  7162  7437 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 14:31:57.056  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:57.056  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:57.056  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 14:31:57.056  7162  7437 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bf287a1 removed from the list
08-24 14:31:57.056  7162  7437 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 14:31:57.056  7162  7437 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13db3052 added. We now have 2 listener(s)
,08-24 14:31:57.066  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41",
08-24 14:31:57.066  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 14:31:57.066  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 14:31:57.066  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 14:31:57.066  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e78bf23 added. We now have 9 listener(s)
08-24 14:31:57.066  7162  7437 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 14:31:57.076  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 14:31:57.076  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 14:31:57.086  7162  7437 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:31:57.086  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:57.086  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:31:57.086  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:31:57.086  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:31:57.086  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:31:57.086  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:31:57.086  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 14:31:57.086  7162  7437 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
08-24 14:31:57.086  7162  7437 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 14:31:57.086  7162  7437 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 14:31:57.096  7162  7437 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8389d9 added. We now have 3 listener(s)
,08-24 14:31:57.096  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:57.096  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:57.096  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-24 14:31:57.096  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 14:31:57.096  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 14:31:57.096  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:31:57.096  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d7ff9e added. We now have 10 listener(s)
08-24 14:31:57.096  7162  7437 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 14:31:57.096  7162  7437 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 14:31:57.096  7162  7437 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 14:31:57.096  7162  7437 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 14:31:57.096  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 14:31:57.096  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 14:31:57.096  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-24 14:31:57.106  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,08-24 14:31:57.106  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-24 14:31:57.116  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-24 14:31:57.116  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-24 14:31:57.116  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-24 14:31:57.116  7162  7437 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-24 14:31:57.126  3217  3226 D BtGatt.GattService: registerClient() - UUID=792c0f80-8bb1-4ecf-b2a6-454e51576e98
,08-24 14:31:57.166  3217  3295 D BtGatt.GattService: onClientRegistered() - UUID=792c0f80-8bb1-4ecf-b2a6-454e51576e98, clientIf=6
,08-24 14:31:57.166  7162  7177 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-24 14:31:57.166  3217  3351 D BtGatt.GattService: start scan with filters
08-24 14:31:57.166  3217  3354 D BtGatt.ScanManager: handling starting scan
08-24 14:31:57.166  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-24 14:31:57.166  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-24 14:31:57.166  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-24 14:31:57.166  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-24 14:31:57.166  3217  3295 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-24 14:31:57.166  3217  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-24 14:31:57.166  3217  3354 D BtGatt.ScanManager: allow scan with filters
08-24 14:31:57.166  3217  3354 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-24 14:31:57.166  3217  3354 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
,08-24 14:31:57.166  3217  3295 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-24 14:31:57.166  3217  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-24 14:31:57.166  3217  3354 D BtGatt.ScanManager: Starting BLE batch scan
08-24 14:31:57.166  3217  3354 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-24 14:31:57.176  3217  3295 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-24 14:31:57.176  3217  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 14:31:57.176  7162  7437 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 14:31:57.176  7162  7162 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-24 14:31:57.176  7162  7437 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-24 14:31:57.176  3217  3295 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-24 14:31:57.176  3217  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 14:31:57.176  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-24 14:31:57.186  7162  7437 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-24 14:31:57.186  7162  7437 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-24 14:31:57.186  7162  7437 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 14:31:57.186  7162  7437 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-24 14:31:57.186  7162  7437 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 14:31:57.186  7162  7437 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:57.186  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:57.186  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-24 14:31:57.186  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 14:31:57.186  7162  7437 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13db3052 removed from the list
08-24 14:31:57.186  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:57.186  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e78bf23 removed from the list
,08-24 14:31:57.186  7162  7437 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:31:57.186  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 14:31:57.186  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:57.186  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-24 14:31:57.186  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 14:31:57.186  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 14:31:57.186  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 14:31:57.186  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:31:57.186  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 14:31:57.186  7162  7437 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e78bf23 not in the list
08-24 14:31:57.186  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 14:31:57.186  7162  7437 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-24 14:31:57.186  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-24 14:31:57.186  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-24 14:31:57.186  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-24 14:31:57.196  3217  7500 D BtGatt.GattService: stopScan() - queue size =1
,08-24 14:31:57.196  3217  3228 D BtGatt.GattService: unregisterClient() - clientIf=6,
08-24 14:31:57.196  3217  3354 D BtGatt.ScanManager: filter size is 1
08-24 14:31:57.196  3217  3354 D BtGatt.ScanManager: delete FilterIndex - 7
,08-24 14:31:57.196  3217  3295 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-24 14:31:57.196  3217  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-24 14:31:57.196  3217  3354 D BtGatt.ScanManager: stopping BLe Batch
,08-24 14:31:57.196  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 14:31:57.196  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-24 14:31:57.196  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-24 14:31:57.196  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-24 14:31:57.196  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-24 14:31:57.196  7162  7437 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-24 14:31:57.196  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-24 14:31:57.196  7162  7437 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-24 14:31:57.196  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-24 14:31:57.196  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:31:57.196  3217  3295 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-24 14:31:57.196  3217  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-24 14:31:57.196  3217  3354 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-24 14:31:57.196  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-24 14:31:57.196  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:31:57.196  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:57.196  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d7ff9e removed from the list
,08-24 14:31:57.196  7162  7437 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:57.196  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:57.196  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:57.196  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
08-24 14:31:57.196  7162  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 14:31:57.196  7162  7437 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8389d9 removed from the list
08-24 14:31:57.196  7162  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 14:31:57.196  7162  7162 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 14:31:57.196  7162  7437 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-24 14:31:57.196  7162  7437 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@104077aa added. We now have 2 listener(s)
08-24 14:31:57.206  3217  3295 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-24 14:31:57.206  3217  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 14:31:57.206  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-24 14:31:57.206  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 14:31:57.206  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 14:31:57.206  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:31:57.206  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@764ef9b added. We now have 9 listener(s)
08-24 14:31:57.206  7162  7437 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 14:31:57.206  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 14:31:57.206  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 14:31:57.216  7162  7437 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:31:57.216  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:57.216  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:31:57.216  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:31:57.216  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:31:57.216  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:31:57.216  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:31:57.216  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 14:31:57.216  7162  7437 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-24 14:31:57.216  7162  7437 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 14:31:57.216  7162  7437 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 14:31:57.216  7162  7437 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a7b9b11 added. We now have 3 listener(s)
,08-24 14:31:57.216  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:57.216  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-24 14:31:57.216  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 14:31:57.216  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 14:31:57.216  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:31:57.216  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66476 added. We now have 10 listener(s)
08-24 14:31:57.216  7162  7437 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 14:31:57.216  7162  7437 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 14:31:57.216  7162  7437 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 14:31:57.216  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 14:31:57.216  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 14:31:57.216  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-24 14:31:57.216  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:57.216  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-24 14:31:57.226  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-24 14:31:57.226  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-24 14:31:57.226  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-24 14:31:57.226  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-24 14:31:57.226  7162  7437 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-24 14:31:57.226  3217  3351 D BtGatt.GattService: registerClient() - UUID=eb0f2ee5-47b3-457d-9b21-08133052ade3
,08-24 14:31:57.276  3217  3295 D BtGatt.GattService: onClientRegistered() - UUID=eb0f2ee5-47b3-457d-9b21-08133052ade3, clientIf=6
,08-24 14:31:57.276  7162  7175 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-24 14:31:57.276  3217  3352 D BtGatt.GattService: start scan with filters
,08-24 14:31:57.276  3217  3354 D BtGatt.ScanManager: handling starting scan
,08-24 14:31:57.276  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-24 14:31:57.276  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-24 14:31:57.276  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-24 14:31:57.276  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-24 14:31:57.276  3217  3295 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-24 14:31:57.276  3217  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-24 14:31:57.276  3217  3354 D BtGatt.ScanManager: allow scan with filters
08-24 14:31:57.276  3217  3354 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-24 14:31:57.276  3217  3354 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6
,08-24 14:31:57.276  3217  3295 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-24 14:31:57.276  3217  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 14:31:57.276  3217  3354 D BtGatt.ScanManager: Starting BLE batch scan
08-24 14:31:57.276  7162  7437 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-24 14:31:57.276  7162  7162 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-24 14:31:57.276  7162  7437 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-24 14:31:57.276  3217  3354 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-24 14:31:57.286  3217  3295 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-24 14:31:57.286  3217  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 14:31:57.286  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-24 14:31:57.286  3217  3295 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-24 14:31:57.286  3217  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 14:31:57.296  7162  7437 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 14:31:57.296  7162  7437 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-24 14:31:57.296  7162  7437 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 14:31:57.296  7162  7437 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:57.296  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:57.296  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-24 14:31:57.296  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 14:31:57.296  7162  7437 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@104077aa removed from the list
08-24 14:31:57.296  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 14:31:57.296  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@764ef9b removed from the list
08-24 14:31:57.296  7162  7437 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:31:57.296  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 14:31:57.296  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-24 14:31:57.296  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-24 14:31:57.296  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:57.296  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 14:31:57.296  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 14:31:57.296  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:31:57.296  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 14:31:57.296  7162  7437 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@764ef9b not in the list
08-24 14:31:57.296  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 14:31:57.296  7162  7437 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-24 14:31:57.296  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-24 14:31:57.296  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-24 14:31:57.296  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-24 14:31:57.306  3217  3351 D BtGatt.GattService: stopScan() - queue size =1
,08-24 14:31:57.306  3217  3352 D BtGatt.GattService: unregisterClient() - clientIf=6
08-24 14:31:57.306  1018  1129 E WifiNative-wlan0: do suspend true
,08-24 14:31:57.306  3217  3354 D BtGatt.ScanManager: filter size is 1
,08-24 14:31:57.306  3217  3354 D BtGatt.ScanManager: delete FilterIndex - 8
,08-24 14:31:57.306  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-24 14:31:57.306  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-24 14:31:57.306  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-24 14:31:57.306  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-24 14:31:57.306  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-24 14:31:57.306  3217  3295 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-24 14:31:57.306  3217  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 14:31:57.306  3217  3354 D BtGatt.ScanManager: stopping BLe Batch
,08-24 14:31:57.306  7162  7437 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-24 14:31:57.306  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-24 14:31:57.306  7162  7437 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-24 14:31:57.306  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-24 14:31:57.306  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:31:57.306  3217  3295 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-24 14:31:57.306  3217  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 14:31:57.306  3217  3354 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-24 14:31:57.316  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:31:57.316  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:31:57.316  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:57.316  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66476 removed from the list
08-24 14:31:57.316  7162  7437 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:57.316  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:57.316  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:57.316  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 14:31:57.316  7162  7437 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a7b9b11 removed from the list
,08-24 14:31:57.316  7162  7437 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 14:31:57.316  7162  7437 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@116c5202 added. We now have 2 listener(s)
08-24 14:31:57.316  7162  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 14:31:57.316  7162  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 14:31:57.316  7162  7162 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-24 14:31:57.316  3217  3295 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-24 14:31:57.316  3217  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 14:31:57.316  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-24 14:31:57.316  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 14:31:57.316  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 14:31:57.316  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:31:57.316  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ba7b713 added. We now have 9 listener(s)
08-24 14:31:57.316  7162  7437 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 14:31:57.316  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 14:31:57.326  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 14:31:57.326  7162  7437 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:31:57.326  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:31:57.326  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:31:57.326  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:31:57.326  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:31:57.326  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 14:31:57.326  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 14:31:57.326  7162  7437 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 14:31:57.326  7162  7437 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 14:31:57.326  7162  7437 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 14:31:57.326  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:57.326  7162  7437 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 14:31:57.326  7162  7437 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fcd9b49 added. We now have 3 listener(s)
,08-24 14:31:57.326  7162  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:31:57.336  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-24 14:31:57.336  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 14:31:57.336  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 14:31:57.336  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 14:31:57.336  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3518c4e added. We now have 10 listener(s)
08-24 14:31:57.336  7162  7437 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 14:31:57.336  7162  7437 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 14:31:57.336  7162  7437 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 14:31:57.336  7162  7437 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 14:31:57.336  7162  7437 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:57.336  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:57.336  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 14:31:57.336  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 14:31:57.336  7162  7437 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@116c5202 removed from the list
08-24 14:31:57.336  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:57.336  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ba7b713 removed from the list
08-24 14:31:57.336  7162  7437 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:31:57.336  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:31:57.336  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:57.336  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:31:57.336  1018  1128 D WifiP2pService: InactiveState{ what=143375 }
,08-24 14:31:57.336  1018  1129 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,08-24 14:31:57.336  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:31:57.336  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:31:57.336  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:57.336  7162  7437 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ba7b713 not in the list
08-24 14:31:57.336  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:57.336  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 14:31:57.336  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 14:31:57.336  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 14:31:57.336  7162  7437 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:31:57.336  1018  1128 D WifiP2pService: P2pEnabledState{ what=143375 }
08-24 14:31:57.336  7162  7437 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3518c4e removed from the list
08-24 14:31:57.336  7162  7437 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:31:57.336  7162  7437 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:31:57.336  7162  7437 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:31:57.336  7162  7437 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 14:31:57.336  7162  7437 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fcd9b49 removed from the list
08-24 14:31:57.336  1018  1129 E WifiStateMachine: VerifyingLinkState enter
,08-24 14:31:57.336  7162  7437 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-24 14:31:57.336  7162  7437 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-24 14:31:57.336  7162  7437 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-24 14:31:57.346  7162  7437 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 14:31:57.346  7162  7437 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-24 14:31:57.346  7162  7437 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-24 14:31:57.346  1018  1131 E ConnectivityService: updateNetworkInfo()
,08-24 14:31:57.346  1018  1131 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,08-24 14:31:57.346  1018  1131 D ConnectivityService: Adding iface wlan0 to network 503
,08-24 14:31:57.346  1179  1179 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-24 14:31:57.346  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-24 14:31:57.346  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-24 14:31:57.356  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:57.356  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:57.356  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:57.356  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 14:31:57.356  7162  8178 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1468, name: My test thread name)
,08-24 14:31:57.356  7162  8178 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1468, thread name: My test thread name)
08-24 14:31:57.356  7162  8178 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1468, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-24 14:31:57.356  1018  1147 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,08-24 14:31:57.356  1018  1147 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-24 14:31:57.356  1018  1147 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-24 14:31:57.356  1018  1147 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-24 14:31:57.356  1018  1147 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-24 14:31:57.356  7162  8180 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1470, name: My test thread name)
08-24 14:31:57.356  7162  8180 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1470, thread name: My test thread name)
,08-24 14:31:57.356  7162  8180 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1470, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-24 14:31:57.356  7162  7437 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-24 14:31:57.356  7162  7437 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-24 14:31:57.356  7162  7437 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
,08-24 14:31:57.356  7162  7437 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-24 14:31:57.356  7162  7437 D com.test.thalitest.ThaliTestRunner: Total duration: 23245 ms
08-24 14:31:57.356  7162  7437 I jxcore-log: Total number of executed tests:  80
08-24 14:31:57.356  7162  7437 I jxcore-log: 
08-24 14:31:57.356  7162  7437 I jxcore-log: Number of passed tests:  80
08-24 14:31:57.356  7162  7437 I jxcore-log: 
,08-24 14:31:57.366  7162  7437 I jxcore-log: Number of failed tests:  0
08-24 14:31:57.366  7162  7437 I jxcore-log: 
08-24 14:31:57.366  7162  7437 I jxcore-log: Number of ignored tests:  0
08-24 14:31:57.366  7162  7437 I jxcore-log: 
08-24 14:31:57.366  7162  7437 I jxcore-log: Total duration:  23245
08-24 14:31:57.366  7162  7437 I jxcore-log: 
08-24 14:31:57.366  7162  7437 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-24 14:31:57.366  7162  7437 I jxcore-log: 
,08-24 14:31:57.366  7162  7437 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 14:31:57.366  7162  7437 I jxcore-log: 
08-24 14:31:57.366  7162  7437 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 14:31:57.366  7162  7437 I jxcore-log: 
08-24 14:31:57.366  7162  7437 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 14:31:57.366  7162  7437 I jxcore-log: 
08-24 14:31:57.366  7162  7437 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 14:31:57.366  7162  7437 I jxcore-log: 
08-24 14:31:57.366  7162  7437 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 14:31:57.366  7162  7437 I jxcore-log: 
08-24 14:31:57.376  7162  7437 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 14:31:57.376  7162  7437 I jxcore-log: 
08-24 14:31:57.376  7162  7437 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 14:31:57.376  7162  7437 I jxcore-log: 
08-24 14:31:57.376  7162  7437 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 14:31:57.376  7162  7437 I jxcore-log: 
08-24 14:31:57.376  7162  7437 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 14:31:57.376  7162  7437 I jxcore-log: 
08-24 14:31:57.376  7162  7437 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-24 14:31:57.376  7162  7437 I jxcore-log: 
08-24 14:31:57.386  1018  1131 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 503
08-24 14:31:57.386  7162  7437 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-24 14:31:57.386  7162  7437 I jxcore-log: 
08-24 14:31:57.386  7162  7162 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-24 14:31:57.386  7162  7437 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-24 14:31:57.386  7162  7437 I jxcore-log: 
08-24 14:31:57.386  1018  1131 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
08-24 14:31:57.386  7162  7437 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 14:31:57.386  7162  7437 I jxcore-log: 
08-24 14:31:57.386  7162  7437 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 14:31:57.386  7162  7437 I jxcore-log: 
08-24 14:31:57.386  1018  1131 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
08-24 14:31:57.386  7162  7437 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-24 14:31:57.386  7162  7437 I jxcore-log: 
08-24 14:31:57.386  1018  1131 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-24 14:31:57.386  1018  1131 D ConnectivityService: Setting Dns servers for network 503 to [/192.168.1.1]
08-24 14:31:57.386  7162  7437 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-24 14:31:57.386  7162  7437 I jxcore-log: 
08-24 14:31:57.386  1018  1131 D ConnectivityService: LTETest block dns file not exists
08-24 14:31:57.386  7162  7437 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 14:31:57.386  7162  7437 I jxcore-log: 
08-24 14:31:57.386  1018  1131 V NetworkStats: updateIfacesLocked()
08-24 14:31:57.386  1018  1131 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 14:31:57.386  1018  1131 V NetworkStats: performPollLocked(flags=0x1)
08-24 14:31:57.386  7162  7437 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 14:31:57.386  7162  7437 I jxcore-log: 
08-24 14:31:57.386  1018  1131 D NetworkStatsFactory: UpdateStatsForKnox updated
08-24 14:31:57.386  7162  7437 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-24 14:31:57.386  7162  7437 I jxcore-log: 
08-24 14:31:57.386  1018  1131 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-24 14:31:57.386  7162  7437 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-24 14:31:57.386  7162  7437 I jxcore-log: 
08-24 14:31:57.396  1179  1179 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-24 14:31:57.396  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 14:31:57.396  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-24 14:31:57.396  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:57.396  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:57.396  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:57.396  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:57.396  7162  7437 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-24 14:31:57.396  7162  7437 I jxcore-log: 
,08-24 14:31:57.396  1018  1131 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 14:31:57.396  1018  1131 V NetworkStats: performPollLocked() took 4ms
08-24 14:31:57.396  7162  7437 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-24 14:31:57.396  7162  7437 I jxcore-log: 
08-24 14:31:57.396  7162  7437 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-24 14:31:57.396  7162  7437 I jxcore-log: 
08-24 14:31:57.396  7162  7437 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-24 14:31:57.396  7162  7437 I jxcore-log: 
,08-24 14:31:57.396  7162  7437 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-24 14:31:57.396  7162  7437 I jxcore-log: 
,08-24 14:31:57.396  7162  7437 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-24 14:31:57.396  7162  7437 I jxcore-log: 
,08-24 14:31:57.396  7162  7437 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-24 14:31:57.396  7162  7437 I jxcore-log: 
,08-24 14:31:57.396  1018  1129 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
08-24 14:31:57.396  1018  1449 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-24 14:31:57.396  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 14:31:57.396  1018  1449 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-24 14:31:57.396  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 14:31:57.396  1018  1131 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,08-24 14:31:57.406  1018  1449 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:57.406  1018  1449 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:57.406  1018  1449 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-24 14:31:57.406  1628  1628 I Hs20UtilService: Starting #20
,08-24 14:31:57.406  1628  1673 I Hs20UtilService: Message received 5007
,08-24 14:31:57.416  1018  1131 E ConnectivityService: updateNetworkInfo()
,08-24 14:31:57.416  4761  4761 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-24 14:31:57.416  1018  1131 E ConnectivityService: updateNetworkInfo()
08-24 14:31:57.416  1018  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-24 14:31:57.416  1018  1131 V NetworkStats: updateIfacesLocked()
08-24 14:31:57.416  1018  1131 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 14:31:57.416  1018  1131 V NetworkStats: performPollLocked(flags=0x1)
,08-24 14:31:57.416  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-24 14:31:57.416  1018  1131 D NetworkStatsFactory: UpdateStatsForKnox updated
08-24 14:31:57.416  1018  1131 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-24 14:31:57.426  1018  1131 V NetworkStats: performPollLocked() took 6ms
08-24 14:31:57.426  1018  1131 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 14:31:57.426  1018  1129 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-24 14:31:57.426  1018  1129 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-24 14:31:57.426  1179  1179 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-24 14:31:57.426  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 14:31:57.426  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-24 14:31:57.426  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:57.426  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:57.426  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:57.426  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 14:31:57.426  4761  4761 I NearbySettings: MountReceiver.onReceive - Keep current state
08-24 14:31:57.426  1018  1131 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
,08-24 14:31:57.426  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-24 14:31:57.426  1018  1018 I WifiTrafficPoller: mBoosterFLAG : 0
08-24 14:31:57.426  1018  1018 I WifiTrafficPoller: current booster mode : FullMode
,08-24 14:31:57.426  1018  1131 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
,08-24 14:31:57.426  1018  8145 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,08-24 14:31:57.426  1018  8145 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
,08-24 14:31:57.426  1018  8145 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-24 14:31:57.426  1018  1131 D ConnectivityService:    accepting network in place of null
,08-24 14:31:57.436  1018  1128 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-24 14:31:57.436  1018  1129 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-24 14:31:57.436  1018  1131 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-24 14:31:57.436  1018  1131 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
08-24 14:31:57.436  1018  8145 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
08-24 14:31:57.436  1018  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-24 14:31:57.436  1466  1466 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-24 14:31:57.436  1466  1466 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-24 14:31:57.436  1018  8145 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 14:31:57.436   278   979 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-24 14:31:57.436   278   979 D Netd    : getNetworkForDns: using netid 503 for uid 1000
,08-24 14:31:57.436  1179  1179 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 14:31:57.436  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-24 14:31:57.436  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 14:31:57.436  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:57.436  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:57.436  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 14:31:57.436  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 14:31:57.436  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 14:31:57.446  1018  1131 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,08-24 14:31:57.446  1018  1018 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-24 14:31:57.446  1018  1132 D Tethering: MasterInitialState.processMessage what=3
,08-24 14:31:57.446  1018  1131 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,08-24 14:31:57.446  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 14:31:57.446  1018  1126 V NetworkStats: updateIfacesLocked()
08-24 14:31:57.446  1018  1126 V NetworkStats: performPollLocked(flags=0x1)
,08-24 14:31:57.446  1018  1048 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-24 14:31:57.446  1018  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-24 14:31:57.446  1018  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-24 14:31:57.446  1179  1728 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-24 14:31:57.446  1018  1126 V NetworkStats: performPollLocked() took 5ms
08-24 14:31:57.446  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 14:31:57.446  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 14:31:57.456  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 14:31:57.456  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 14:31:57.456  1018  1127 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-24 14:31:57.456  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 14:31:57.456  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 14:31:57.456  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 14:31:57.466  1179  1179 D StatusBar.NetworkController: EthernetConnected: false
08-24 14:31:57.466  1179  1179 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-24 14:31:57.466  1179  1179 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-24 14:31:57.466  1179  1179 D StatusBar.NetworkController: updateDataNetType()
08-24 14:31:57.466  1018  1031 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-24 14:31:57.466  1179  1179 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
08-24 14:31:57.466  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-24 14:31:57.466  1179  1179 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-24 14:31:57.466  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-24 14:31:57.466  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:57.466  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-24 14:31:57.466  1628  1628 I Hs20UtilService: Starting #21
,08-24 14:31:57.466  1628  1673 I Hs20UtilService: Message received 5007
,08-24 14:31:57.466  1179  1179 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-24 14:31:57.466  1179  1179 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 15 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
08-24 14:31:57.466  1179  1179 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
,08-24 14:31:57.476  1179  1179 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,08-24 14:31:57.476  1179  1179 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 14:31:57.476  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-24 14:31:57.476  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:57.476  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:57.476  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:57.476  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:57.476  4761  4761 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-24 14:31:57.476  4761  4761 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-24 14:31:57.476  4761  4761 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
08-24 14:31:57.476  4761  4761 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-24 14:31:57.476  4761  4761 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
08-24 14:31:57.476  4761  4761 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-24 14:31:57.486  1018  1439 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-24 14:31:57.486  1018  1439 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-24 14:31:57.486  1018  1439 W ActivityManager: userId = 0, bbcId = -10000
08-24 14:31:57.486  1018  1439 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 14:31:57.486  1018  1439 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-24 14:31:57.486  1628  1628 I Hs20UtilService: Starting #22
,08-24 14:31:57.486  1628  1673 I Hs20UtilService: Message received 5007
08-24 14:31:57.486  4761  4761 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-24 14:31:57.486  4761  4761 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-24 14:31:57.496  1018  1217 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-24 14:31:57.496  1018  1030 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
08-24 14:31:57.496  1018  1030 D SecContentProvider2: mCursor = null
,08-24 14:31:57.496  1018  1489 D SecContentProvider2: uri = 15 selection = getToastGravity
08-24 14:31:57.496  1018  1489 D SecContentProvider2: mCursor = null
,08-24 14:31:57.496  1018  1441 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
08-24 14:31:57.496  1018  1441 D SecContentProvider2: mCursor = null
,08-24 14:31:57.496  1018  1439 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
,08-24 14:31:57.496  1018  1439 D SecContentProvider2: mCursor = null
,08-24 14:31:57.506  1018  1491 D SecContentProvider2: uri = 15 selection = getToastEnabledState
08-24 14:31:57.506  1018  1491 D SecContentProvider2: mCursor = null
,08-24 14:31:57.506  1018  1492 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
08-24 14:31:57.506  1018  1492 D SecContentProvider2: mCursor = null
,08-24 14:31:57.526  1018  8145 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-24 14:31:57.526   258   258 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,08-24 14:31:57.546  7162  7162 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-24 14:31:57.546  1018  1030 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1018
,08-24 14:31:57.546  7162  7437 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-24 14:31:57.546  7162  7437 I jxcore-log: 
,08-24 14:31:57.556  1179  1179 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-24 14:31:57.586  1018  8145 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 24 Aug 2016 12:31:57 GMT], X-Android-Received-Millis=[1472041917599], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472041917560]}
,08-24 14:31:57.586  1018  8145 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
,08-24 14:31:57.586  1018  8145 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,08-24 14:31:57.586  1018  1131 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 503]
,08-24 14:31:57.586  1018  1131 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
08-24 14:31:57.586  1018  1131 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
08-24 14:31:57.596  1018  1131 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,08-24 14:31:57.596  1018  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-24 14:31:57.596  1179  1728 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-24 14:31:57.596  1179  1179 D StatusBar.NetworkController: EthernetConnected: false
,08-24 14:31:57.596  1179  1179 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-24 14:31:57.596  1179  1179 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-24 14:31:57.596  1179  1179 D StatusBar.NetworkController: updateDataNetType(),
08-24 14:31:57.606  1179  1179 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
08-24 14:31:57.606  1179  1179 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-24 14:31:57.606  1179  1179 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false,
08-24 14:31:57.606  1179  1179 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 15 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
,08-24 14:31:57.606  1179  1179 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
08-24 14:31:57.606  1179  1179 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,08-24 14:31:57.606  1179  1179 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-24 14:31:57.606  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-24 14:31:57.606  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:57.606  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 14:31:57.606  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 14:31:57.606  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 14:31:57.666  8185  8185 D AndroidRuntime: ,
08-24 14:31:57.666  8185  8185 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-24 14:31:57.666  8185  8185 D AndroidRuntime: CheckJNI is OFF,
08-24 14:31:57.666  8185  8185 D AndroidRuntime: readGMSProperty: start,
08-24 14:31:57.666  8185  8185 D AndroidRuntime: readGMSProperty: already setted!!
08-24 14:31:57.666  8185  8185 D AndroidRuntime: propertySet: couldn't set property (it is from app),
08-24 14:31:57.666  8185  8185 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-24 14:31:57.666  8185  8185 D AndroidRuntime: readGMSProperty: end
,08-24 14:31:57.666  8185  8185 D AndroidRuntime: addProductProperty: start
,08-24 14:31:57.696  7162  7162 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-24 14:31:57.706  7162  7437 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
08-24 14:31:57.706  7162  7437 I jxcore-log: 
,08-24 14:31:57.806  8185  8185 E AffinityControl: AffinityControl: registerfunction enter,
,08-24 14:31:57.816  7162  7162 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-24 14:31:57.816  7162  7437 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-24 14:31:57.816  7162  7437 I jxcore-log: 
,08-24 14:31:57.836  1018  1131 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-24 14:31:57.836  8185  8185 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-24 14:31:57.836  1018  1131 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 14:31:57.836  1018  1131 V NetworkStats: updateIfacesLocked()
08-24 14:31:57.836  1018  1131 D NetworkStatsFactory: UpdateStatsForKnox updated
08-24 14:31:57.836  1018  1131 V NetworkStats: performPollLocked(flags=0x1)
08-24 14:31:57.836  1018  1131 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-24 14:31:57.846  1018  1131 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 14:31:57.846  1018  1131 V NetworkStats: performPollLocked() took 3ms
08-24 14:31:57.846  1018  1131 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,08-24 14:31:57.846  1179  1728 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-24 14:31:57.846  1018  1131 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,08-24 14:31:57.846  1179  1728 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-24 14:31:57.856  1018  1217 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
08-24 14:31:57.856  1018  1217 D PackageManager: START PACKAGE DELETE: observer{860848164}
08-24 14:31:57.856  1018  1217 D PackageManager: pkg{<packageName>}
08-24 14:31:57.856  1018  1217 D PackageManager: user{0}
08-24 14:31:57.856  1018  1217 D PackageManager: caller{2000}
08-24 14:31:57.856  1018  1217 D PackageManager: flags{2}
08-24 14:31:57.856  1018  1217 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
,08-24 14:31:57.856  1018  1058 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-24 14:31:57.856  1018  1217 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-24 14:31:57.856  1018  1217 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-24 14:31:57.856  1018  1217 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2,
08-24 14:31:57.856  1018  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-24 14:31:57.856  1018  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-24 14:31:57.856  1018  1058 D ApplicationPolicy: getApplicationUninstallationEnabled
,08-24 14:31:57.856  1018  1058 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-24 14:31:57.856  1018  1058 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
,08-24 14:31:57.866  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 14:31:57.866  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 14:31:57.866  1018  1044 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
,08-24 14:31:57.866  1018  1044 I ActivityManager: Killing 7162:com.test.thalitest/u0a170 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-24 14:31:57.946  1018  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-24 14:31:57.966  1018  1044 I ActivityManager:   Force finishing activity ActivityRecord{3abb9e4c u0 com.test.thalitest/.MainActivity t163}
,08-24 14:31:57.966  1018  1044 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-24 14:31:57.976  1018  1044 D InputDispatcher: Focus left window: 7162,
08-24 14:31:57.976   258  1040 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
,08-24 14:31:57.996  1018  1044 D InputDispatcher: Focused application released
08-24 14:31:57.996  1018  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-24 14:31:57.996  1018  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-24 14:31:57.996  1018  3813 W WindowManager: Failed looking up window
08-24 14:31:57.996  1018  3813 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@14f3ae3 does not exist
08-24 14:31:57.996  1018  3813 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:11074)
08-24 14:31:57.996  1018  3813 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:11065)
08-24 14:31:57.996  1018  3813 W WindowManager: 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1644)
08-24 14:31:57.996  1018  3813 W WindowManager: 	at android.os.BinderProxy.sendDeathNotice(Binder.java:551)
,08-24 14:31:57.996  1018  3813 I WindowState: WIN DEATH: null
,08-24 14:31:58.006  1018  1043 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-24 14:31:58.006  1018  1044 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-24 14:31:58.016  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:58.016  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:58.016  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:58.016  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:58.026  8196  8196 E Zygote  : MountEmulatedStorage(),
08-24 14:31:58.026  8196  8196 E Zygote  : v2
08-24 14:31:58.026  8196  8196 I libpersona: KNOX_SDCARD checking this for 1000
08-24 14:31:58.026  8196  8196 I libpersona: KNOX_SDCARD not a persona
,08-24 14:31:58.026  1018  1044 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=8196 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-24 14:31:58.026  1018  1058 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,08-24 14:31:58.026  8196  8196 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 14:31:58.036  8196  8196 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 14:31:58.036  8196  8196 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 14:31:58.046  1018  1058 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-24 14:31:58.076  2866  2866 I art     : Explicit concurrent mark sweep GC freed 18186(1058KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 830us total 31.166ms
,08-24 14:31:58.096  8196  8196 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:31:58.096  8196  8196 D ActivityThread: Added TimaKeyStore provider
,08-24 14:31:58.096  1874  1874 E SamsungIME: mOCRHelper is null
,08-24 14:31:58.106  1755  1997 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-24 14:31:58.106  1018  1101 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-24 14:31:58.126  1018  1126 V NetworkStats: removeUidsLocked() for UIDs [10170]
08-24 14:31:58.126  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 14:31:58.126  1018  1126 V NetworkStats: performPollLocked(flags=0x3)
,08-24 14:31:58.126  1018  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-24 14:31:58.126  1018  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-24 14:31:58.136  1018  1126 V NetworkStats: performPollLocked() took 10ms
,08-24 14:31:58.136  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 14:31:58.146  1453  1453 D PersonaManager: isKioskContainerExistOnDevice
,08-24 14:31:58.156  1453  1453 D RegisteredServicesCache: empty dynamic service
,08-24 14:31:58.176  1018  1018 D RCPManagerService: PackageReceiver onReceive()
,08-24 14:31:58.176  1453  1453 D RegisteredComponentCache: Collect Tech packages for Knox
,08-24 14:31:58.176  1453  1453 D PersonaManager: isKioskContainerExistOnDevice
,08-24 14:31:58.196  1018  1018 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-24 14:31:58.196  8196  8196 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-24 14:31:58.196  8196  8196 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-24 14:31:58.196  8196  8196 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-24 14:31:58.196  1018  1018 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-24 14:31:58.196  1018  1018 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-24 14:31:58.196  1018  1018 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,08-24 14:31:58.206  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 14:31:58.206  1018  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 14:31:58.216  1018  1018 I OTPFW   : ProvisionData::getAllEntries Enter
,08-24 14:31:58.216  1018  1018 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-24 14:31:58.236  8196  8196 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-24 14:31:58.236  8196  8196 I PCWCLIENTTRACE_PushUtil: sales region : global
08-24 14:31:58.236  8196  8196 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-24 14:31:58.236  8196  8196 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-24 14:31:58.236  1018  1508 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
,08-24 14:31:58.236  1018  1508 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
08-24 14:31:58.236  1018  1508 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
08-24 14:31:58.236  1018  1508 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,08-24 14:31:58.246  1018  1508 I ActivityManager: Killing 7710:com.sec.android.soagent/u0a31 (adj 15): empty #21
,08-24 14:31:58.256  1018  1441 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-24 14:31:58.256  1018  1441 D SecContentProvider2: mCursor = null
,08-24 14:31:58.256  1018  1043 D EnterpriseDeviceManagerService: Package has changed for user 0
08-24 14:31:58.256  1018  1043 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
08-24 14:31:58.256  1018  1043 W TextServicesManagerService: no available spell checker services found
,08-24 14:31:58.266  1018  1058 I art     : Explicit concurrent mark sweep GC freed 70446(4MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 23MB/35MB, paused 9.305ms total 210.134ms
,08-24 14:31:58.266  1018  1028 I art     : WaitForGcToComplete blocked for 129.506ms for cause HeapTrim
,08-24 14:31:58.276  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 14:31:58.286  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 14:31:58.286  1018  1058 D PackageManager: delete codoeFile: 
,08-24 14:31:58.296  1018  1058 I AASA_removePackage: UID=10170 Target=com.test.thalitest
,08-24 14:31:58.296  1018  1058 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
,08-24 14:31:58.296  1018  1058 D PackageManager: result of delete: 1{860848164}
,08-24 14:31:58.306  8185  8185 D AndroidRuntime: Shutting down VM
,08-24 14:31:58.306  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 14:31:58.316  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 14:31:58.406  1018  1043 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-24 14:31:58.406  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 14:31:58.416  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 14:31:58.416  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 14:31:58.436  1018  1043 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-24 14:31:58.436  1018  1043 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 14:31:58.436  1018  1043 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-24 14:31:58.436  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 14:31:58.446  1018  1131 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-24 14:31:58.446  1018  1018 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-24 14:31:58.446  1018  1018 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-24 14:31:58.446  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
,08-24 14:31:58.446  1018  1018 V EnterpriseBillingPolicy: uID is 10170
08-24 14:31:58.446  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
08-24 14:31:58.446  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-24 14:31:58.446  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-24 14:31:58.446  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-24 14:31:58.446  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-24 14:31:58.446  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-24 14:31:58.446  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-24 14:31:58.456  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-24 14:31:58.456  1018  1164 D TaskPersister: removeObsoleteFile: deleting file=163_task.xml
,08-24 14:31:58.456  1018  3385 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,08-24 14:31:58.456  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
,08-24 14:31:58.456  1018  1018 V EnterpriseBillingPolicy: uID is 10170
08-24 14:31:58.456  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
08-24 14:31:58.456  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-24 14:31:58.456  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
,08-24 14:31:58.456  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-24 14:31:58.456  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
,08-24 14:31:58.456  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-24 14:31:58.456  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-24 14:31:58.456  1018  1018 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
08-24 14:31:58.456  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 14:31:58.466  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 14:31:58.466  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 14:31:58.466  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-24 14:31:58.466  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 14:31:58.476  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 14:31:58.476  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-24 14:31:58.476  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 14:31:58.476  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-24 14:31:58.476  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 14:31:58.486  1018  1043 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-24 14:31:58.486  1018  1043 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-24 14:31:58.516  8185  8185 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-24 14:31:58.526  1018  1058 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-24 14:31:58.526  1018  1058 D PackageManager: userId{-1}
08-24 14:31:58.526  1018  1058 D PackageManager: andCode{true}
,08-24 14:31:58.526  1018  1058 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-24 14:31:58.526  1018  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:58.526  1018  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:58.526  1018  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:58.526  1018  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:58.536  8213  8213 E Zygote  : MountEmulatedStorage(),
08-24 14:31:58.536  8213  8213 E Zygote  : v2,
08-24 14:31:58.536  8213  8213 I libpersona: KNOX_SDCARD checking this for 10003
08-24 14:31:58.536  8213  8213 I libpersona: KNOX_SDCARD not a persona
,08-24 14:31:58.546  8213  8213 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-24 14:31:58.546  8213  8213 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-24 14:31:58.546  8213  8213 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 14:31:58.546  1018  1058 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8213 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-24 14:31:58.546  1018  1018 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-24 14:31:58.546  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:58.546  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:58.546  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:58.546  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:58.566  8213  8213 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:31:58.566  8213  8213 D ActivityThread: Added TimaKeyStore provider
,08-24 14:31:58.566  8229  8229 E Zygote  : MountEmulatedStorage(),
08-24 14:31:58.566  8229  8229 E Zygote  : v2
08-24 14:31:58.566  8229  8229 I libpersona: KNOX_SDCARD checking this for 10001,
08-24 14:31:58.566  8229  8229 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 14:31:58.566  8229  8229 I libpersona: KNOX_SDCARD not a persona
,08-24 14:31:58.576  8229  8229 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 14:31:58.576  8229  8229 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 14:31:58.576  1018  1018 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=8229 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-24 14:31:58.596   305   305 I art     : Explicit concurrent mark sweep GC freed 8686(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 620us total 20.378ms
,08-24 14:31:58.606  8229  8229 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:31:58.616  8229  8229 D ActivityThread: Added TimaKeyStore provider
,08-24 14:31:58.616   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 576us total 16.503ms
,08-24 14:31:58.626  1018  1491 I ActivityManager: Killing 7726:com.sec.spp.push/u0a32 (adj 15): empty #21
,08-24 14:31:58.636   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 585us total 16.556ms
,08-24 14:31:58.676  1018  3813 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-24 14:31:58.676  1018  3813 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:58.676  1018  3813 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:58.676  1018  3813 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 14:31:58.676  1018  3813 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 14:31:58.696  8248  8248 E Zygote  : MountEmulatedStorage(),
,08-24 14:31:58.696  8248  8248 E Zygote  : v2
,08-24 14:31:58.696  8248  8248 I libpersona: KNOX_SDCARD checking this for 1000
08-24 14:31:58.696  8248  8248 I libpersona: KNOX_SDCARD not a persona
,08-24 14:31:58.696  1018  3813 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=8248 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-24 14:31:58.696  1018  3813 I ActivityManager: Killing 7743:com.osp.app.signin/u0a36 (adj 15): empty #21,
,08-24 14:31:58.706  8248  8248 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-24 14:31:58.706  8248  8248 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 14:31:58.706  8248  8248 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 14:31:58.726  8248  8248 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 14:31:58.726  8248  8248 D ActivityThread: Added TimaKeyStore provider

```
