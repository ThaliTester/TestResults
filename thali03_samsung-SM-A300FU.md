#### Test 808075738e7a0be_thali03_samsung-SM-A300FU Logs


```
--------- beginning of main
08-17 19:16:20.671  6986  6986 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
--------- beginning of system
08-17 19:16:20.781  1020  1525 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-17 19:16:20.781  1020  1525 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4181, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-17 19:16:20.781  1020  1525 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-17 19:16:20.781  1020  1525 D BatteryService: stay LED for charging
08-17 19:16:20.781  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-17 19:16:20.791  1020  1020 I MotionRecognitionService: Plugged
08-17 19:16:20.791  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
08-17 19:16:20.791  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-17 19:16:20.791  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
08-17 19:16:20.791  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-17 19:16:20.801  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-17 19:16:20.811  6949  6949 W art     : Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 125.287ms
08-17 19:16:20.821  3213  3213 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-17 19:16:20.821  3213  3366 D HeadsetStateMachine: Disconnected process message: 10
08-17 19:16:20.821  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-17 19:16:20.831  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-17 19:16:20.831  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-17 19:16:20.851  1020  1506 I art     : Explicit concurrent mark sweep GC freed 175233(9MB) AllocSpace objects, 3(2MB) LOS objects, 33% free, 23MB/34MB, paused 2.977ms total 184.067ms
08-17 19:16:20.851  1020  1494 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-17 19:16:20.851  1020  1494 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:20.851  1020  1494 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:20.851  1020  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
08-17 19:16:20.861  1020  1340 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 19:16:20.861  1020  1340 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-17 19:16:20.861  1020  1340 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:20.861  1020  1340 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:20.861  1020  1340 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-17 19:16:20.871  1020  4295 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
08-17 19:16:20.871  1020  4295 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:20.871  1020  4295 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:20.871  1020  4295 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:20.871  1020  4295 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:20.891  7024  7024 E Zygote  : MountEmulatedStorage()
08-17 19:16:20.891  7024  7024 E Zygote  : v2
08-17 19:16:20.891  7024  7024 I libpersona: KNOX_SDCARD checking this for 1000
08-17 19:16:20.891  7024  7024 I libpersona: KNOX_SDCARD not a persona
08-17 19:16:20.891  7024  7024 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 19:16:20.891  1020  4295 I ActivityManager: Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=7024 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-17 19:16:20.891  1020  4295 I ActivityManager: Killing 6588:com.sec.esdk.elm/u0a90 (adj 15): empty #21
08-17 19:16:20.891  1020  1747 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-17 19:16:20.901  1020  1747 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:20.901  1020  1747 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:20.901  1020  1747 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-17 19:16:20.901  7024  7024 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 19:16:20.901  7024  7024 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-17 19:16:20.921  1020  1494 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 19:16:20.921  7024  7024 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 19:16:20.921  1020  1494 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-17 19:16:20.921  6949  6949 D Mms/TelephonyPermission: start operation mode monitor
08-17 19:16:20.921  7024  7024 D ActivityThread: Added TimaKeyStore provider
08-17 19:16:20.931  1020  1494 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:20.931  1020  1494 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:20.931  1020  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-17 19:16:20.931  6949  7033 D Mms/ArtClassLoader: init before art
08-17 19:16:20.941  1020  1747 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-17 19:16:20.941  1020  1747 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:20.941  1020  1747 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:20.941  1020  1747 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-17 19:16:20.951  6949  6949 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-17 19:16:20.961  6949  6949 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
08-17 19:16:20.961  6949  6949 D Mms/TelephonyPermission: isDefault true
08-17 19:16:20.961  6949  6949 D Mms/MmsApp: onCreate() com.android.mms
08-17 19:16:20.961  1020  1506 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-17 19:16:20.961  1020  1506 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:20.961  1020  1506 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:20.961  1020  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
08-17 19:16:20.971  7024  7024 W ResourcesManager: Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
08-17 19:16:20.971  6997  6997 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-17 19:16:20.981  1882  6896 W BaseAppContext: Using Auth Proxy for data requests.
08-17 19:16:21.011  6997  6997 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-17 19:16:21.031  1020  1033 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
08-17 19:16:21.031  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:21.031  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:21.031  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:21.031  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:21.051  7047  7047 E Zygote  : MountEmulatedStorage()
08-17 19:16:21.051  7047  7047 I libpersona: KNOX_SDCARD checking this for 10152
08-17 19:16:21.051  7047  7047 E Zygote  : v2
08-17 19:16:21.051  7047  7047 I libpersona: KNOX_SDCARD not a persona
08-17 19:16:21.051  7047  7047 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 19:16:21.051  7047  7047 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 19:16:21.051  7047  7047 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-17 19:16:21.061  1020  1033 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7047 uid=10152 gids={50152, 9997} abi=armeabi-v7a
08-17 19:16:21.061  1020  1033 I ActivityManager: Killing 6608:com.samsung.android.securitylogagent/1000 (adj 15): empty #21
08-17 19:16:21.061  1020  1266 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-17 19:16:21.071  6949  6949 D Mms/MmsApp: [start]    initCountryIso consume time = 469.544323
08-17 19:16:21.071  1020  1266 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:21.071  1020  1266 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:21.071  1020  1266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-17 19:16:21.081  1020  1509 D CountryDetector: The first listener is added
08-17 19:16:21.081  6997  6997 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
08-17 19:16:21.081  6949  6949 D Mms/MmsApp: [end]    initCountryIso consume time = 14.402917
08-17 19:16:21.081  6949  6949 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.112812
08-17 19:16:21.081  7047  7047 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 19:16:21.081  7047  7047 D ActivityThread: Added TimaKeyStore provider
08-17 19:16:21.081  1020  1494 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 19:16:21.091  1020  1494 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-17 19:16:21.091  1882  6896 W BaseAppContext: Using Auth Proxy for data requests.
08-17 19:16:21.091  1020  1494 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:21.091  1020  1494 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:21.091  1020  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-17 19:16:21.101  6997  6997 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-17 19:16:21.111  1882  6896 W BaseAppContext: Using Auth Proxy for data requests.
08-17 19:16:21.111  6949  6949 D Mms/MmsConfig: before partial update
08-17 19:16:21.111  6793  6845 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 825 ms] updated apps [took 825 ms] 
08-17 19:16:21.121  1020  1341 I ActivityManager: Killing 6639:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
08-17 19:16:21.141  7047  7047 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
08-17 19:16:21.141  7047  7047 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
08-17 19:16:21.151  1882  6896 W BaseAppContext: Using Auth Proxy for data requests.
08-17 19:16:21.151  6949  6949 D Mms/MmsConfig: Load Resize quality : 80
08-17 19:16:21.151  6949  6949 D EasySignUpManager_1.0.1: serviceId : 1, features : -1
08-17 19:16:21.161  6949  6949 D EasySignUpManager_1.0.1: isAuth is false
08-17 19:16:21.161  6949  6949 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
08-17 19:16:21.161  1882  6873 I qtaguid : Untagging socket 98
08-17 19:16:21.161  1882  1882 I ConfigFetchService: fetch service done; releasing wakelock
08-17 19:16:21.171  1882  1882 I ConfigFetchService: stopping self
08-17 19:16:21.181  7047  7047 I TapandpayWidget:Utils: Clear T&P info.
08-17 19:16:21.201  1477  1686 D TP/MmsSmsProvider: query,matched:2117, calling pid = 6949
08-17 19:16:21.201  1477  1686 D TP/MmsSmsProvider: match 2117:Elapsed time : 2.434 ms
08-17 19:16:21.211  1020  1139 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-17 19:16:21.211  6949  6949 D EasySignUpManager_1.0.1: isAuth is false
08-17 19:16:21.211  6949  6949 D EasySignUpManager_1.0.1: getServiceStatus : serviceId (1) is OFF
08-17 19:16:21.211  6949  6949 E CscParser: mps_code.dat does not exist
08-17 19:16:21.211  6949  6949 E CscParser: customer_path =/system/csc/customer.xml
08-17 19:16:21.211  6949  6949 E CscParser: fileName + /system/csc/customer.xml
08-17 19:16:21.221  6949  6949 E CscParser: mps_code.dat does not exist
08-17 19:16:21.221  6949  6949 E CscParser: customer_path =/system/csc/customer.xml
08-17 19:16:21.221  6949  6949 E CscParser: fileName + /system/csc/customer.xml
08-17 19:16:21.231  7047  7047 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
08-17 19:16:21.231  1020  3827 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
08-17 19:16:21.231  1020  3827 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:21.231  1020  3827 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:21.231  1020  3827 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:21.231  1020  3827 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:21.241  7069  7069 E Zygote  : MountEmulatedStorage()
08-17 19:16:21.241  7069  7069 E Zygote  : v2
08-17 19:16:21.241  7069  7069 I libpersona: KNOX_SDCARD checking this for 10009
08-17 19:16:21.241  7069  7069 I libpersona: KNOX_SDCARD not a persona
08-17 19:16:21.241  7069  7069 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 19:16:21.251  1020  3827 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=7069 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
08-17 19:16:21.251  7069  7069 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 19:16:21.251  1020  3827 I ActivityManager: Killing 6655:com.qualcomm.timeservice/1000 (adj 15): empty #21
08-17 19:16:21.251  7069  7069 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
08-17 19:16:21.251  6949  6949 D CscParser: getInstance fileName =/system/csc/customer.xml
08-17 19:16:21.271  6949  6949 D Mms/MmsConfig:  enable multiwindow = false
08-17 19:16:21.281  7069  7069 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 19:16:21.281  7069  7069 D ActivityThread: Added TimaKeyStore provider
08-17 19:16:21.291  6949  6949 E Mms/MessageUtils: setCountryDetector : update country detector info 
08-17 19:16:21.291  6949  6949 E Mms/MessageUtils: updateCountryIso : update country iso info 
08-17 19:16:21.291  6949  6949 D Mms/MmsConfig: [end]    init() consume time = 213.353542
08-17 19:16:21.301  6949  6949 D Mms/Contact: [start]    init() consume time = 0.889062
08-17 19:16:21.321  1477  1986 D TP/MmsSmsProvider: query,matched:13, calling pid = 6949
08-17 19:16:21.331  1477  1986 D TP/MmsSmsProvider: match 13:Elapsed time : 1.650 ms
08-17 19:16:21.341  6949  6949 D Mms/Contact: [end]    init consume time = 41.12875
08-17 19:16:21.351  6997  6997 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-17 19:16:21.351  6997  6997 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-17 19:16:21.361  6949  7090 D Mms/DraftCache: [start]    rebuildCache consume time = 18.617917
08-17 19:16:21.361  1477  1686 D TP/MmsSmsProvider: query,matched:12, calling pid = 6949
08-17 19:16:21.361  1477  1686 D TP/MmsSmsProvider: match 12:Elapsed time : 0.917 ms
08-17 19:16:21.371  6949  7090 D Mms/DraftCache: [end]    rebuildCache consume time = 9.89599
08-17 19:16:21.371  6949  6949 D Mms/MethodReflector: getSubId is called
08-17 19:16:21.371  6949  6949 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
08-17 19:16:21.381  6997  6997 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-17 19:16:21.381  6997  6997 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-17 19:16:21.381  6949  6949 D Mms/MethodReflector: getTelephonyProperty is called
08-17 19:16:21.381  6949  6949 D Mms/DownloadManager: roaming -> false (slotId = 0)
08-17 19:16:21.381  6949  6949 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-17 19:16:21.381  6949  6949 D Mms/DownloadManager: auto download without roaming -> true
08-17 19:16:21.381  6949  6949 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
08-17 19:16:21.381  6949  6949 D Mms/MethodReflector: getSubId is called
08-17 19:16:21.381  6949  6949 D Mms/MethodReflector: getDefaultSmsSubId is called
08-17 19:16:21.381  6949  6949 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
08-17 19:16:21.381  6949  6949 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
08-17 19:16:21.381  6949  6949 D Mms/MethodReflector: getTelephonyProperty is called
08-17 19:16:21.381  6949  6949 D Mms/DownloadManager: roaming -> false (slotId = 1)
08-17 19:16:21.381  6949  6949 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
08-17 19:16:21.381  6949  6949 D Mms/DownloadManager: auto download without roaming -> true
08-17 19:16:21.381  6949  6949 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
08-17 19:16:21.381  6949  6949 D Mms/DownloadManager: auto download during roaming secondary -> false
08-17 19:16:21.381  6949  6949 D Mms/DownloadManager: mAutoDownload ------> true
08-17 19:16:21.401  6997  6997 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-17 19:16:21.401  1020  1509 I ActivityManager: Killing 6623:com.android.providers.calendar/u0a37 (adj 15): empty #21
08-17 19:16:21.401  6997  6997 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-17 19:16:21.401  6997  6997 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-17 19:16:21.401  6997  6997 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-17 19:16:21.411  6997  6997 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-17 19:16:21.411  6997  6997 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-17 19:16:21.411  6997  6997 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-17 19:16:21.411  6997  6997 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-17 19:16:21.421  6997  6997 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-17 19:16:21.421  6997  6997 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-17 19:16:21.421  6997  6997 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-17 19:16:21.421  6997  6997 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-17 19:16:21.421  6997  6997 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
08-17 19:16:21.441  6949  6949 D ComposerPerformance: 1471454181445 ms / [DONE] Composer constructor
08-17 19:16:21.441  6949  6949 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
08-17 19:16:21.441  6949  6949 I Mms/ReservationManager: ReservationManager()
08-17 19:16:21.441  6949  6949 I Mms/ReservationManager: resetAfterConnected()
08-17 19:16:21.441  1477  1686 D TP/MmsSmsProvider: query,matched:7, calling pid = 6949
08-17 19:16:21.441  1477  1686 D TP/MmsSmsProvider: match 7:Elapsed time : 1.817 ms
08-17 19:16:21.461  6997  6997 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-17 19:16:21.461  6997  6997 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-17 19:16:21.471  6949  6949 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
08-17 19:16:21.481  6949  7101 D Mms/Conversation: [start]    init() consume time = 109.596614
08-17 19:16:21.491  1477  1502 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
08-17 19:16:21.491  1477  1502 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
08-17 19:16:21.491  1477  1502 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
08-17 19:16:21.491  1477  1502 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
08-17 19:16:21.491  1477  1502 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
08-17 19:16:21.491  1477  1502 D TP/MmsSmsProvider: need read changed broadcast:false
08-17 19:16:21.501  6949  6949 D Mms/MmsApp: [end]    onCreate() consume time = 26.297865
08-17 19:16:21.511  6949  7101 D Mms/Conversation: [end]    init consume time = 5.149375
08-17 19:16:21.511  6997  6997 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-17 19:16:21.511  6949  6949 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=760]
08-17 19:16:21.521  6949  6949 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
08-17 19:16:21.521  6997  6997 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-17 19:16:21.521  6997  6997 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-17 19:16:21.521  6949  7101 D Mms/MessagingNotification: [start]    init() consume time = 16.195573
08-17 19:16:21.531  6949  6949 D Mms/MethodReflector: getSubId is called
08-17 19:16:21.531  6949  6949 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
08-17 19:16:21.531  6949  6949 D Mms/MethodReflector: getTelephonyProperty is called
08-17 19:16:21.531  6949  6949 D Mms/DownloadManager: roaming -> false (slotId = 0)
08-17 19:16:21.531  6949  6949 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-17 19:16:21.531  6949  6949 D Mms/DownloadManager: auto download without roaming -> true
08-17 19:16:21.531  6949  6949 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
08-17 19:16:21.531  6949  6949 D Mms/DownloadManager: mAutoDownload ------> true
08-17 19:16:21.531  6949  7101 D Mms/MessagingNotification: [end]    init consume time = 7.683593
08-17 19:16:21.531  6949  6949 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_ADDED
08-17 19:16:21.531  1882  1904 W art     : Suspending all threads took: 21.842ms
08-17 19:16:21.541  1020  1747 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
08-17 19:16:21.541  1020  1747 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
08-17 19:16:21.541  1020  1747 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:21.541  1020  1747 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:21.541  1477  1686 D TP/MmsSmsProvider: query,matched:0, calling pid = 6949
08-17 19:16:21.541  1477  1686 V TP/MmsSmsProvider: getSimpleConversations entered.
08-17 19:16:21.541  1020  1747 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
08-17 19:16:21.541  1477  1686 D TP/MmsSmsProvider: match 0:Elapsed time : 2.921 ms
08-17 19:16:21.551  1020  1506 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
08-17 19:16:21.551  1020  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:21.551  1020  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:21.551  1020  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:21.551  1020  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:21.561  6949  7106 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 27.761667
08-17 19:16:21.561  6949  7107 D Mms/Synchronizer: [start]    doSync consume time = 2.548646
08-17 19:16:21.571  7109  7109 E Zygote  : MountEmulatedStorage()
08-17 19:16:21.571  7109  7109 E Zygote  : v2
08-17 19:16:21.571  7109  7109 I libpersona: KNOX_SDCARD checking this for 10042
08-17 19:16:21.571  7109  7109 I libpersona: KNOX_SDCARD not a persona
08-17 19:16:21.581  7109  7109 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 19:16:21.581  6949  7108 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_ADDED
08-17 19:16:21.581  1020  1506 I ActivityManager: Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=7109 uid=10042 gids={50042, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
08-17 19:16:21.581  6949  7108 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_ADDED
08-17 19:16:21.581  1020  1506 I ActivityManager: Killing 6323:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
08-17 19:16:21.591  7109  7109 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 19:16:21.591  7109  7109 E SELinux : [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
08-17 19:16:21.591  1020  1747 I ActivityManager: Killing 6341:com.android.calendar/u0a131 (adj 15): empty #21
08-17 19:16:21.611  1477  3321 D TP/MmsSmsProvider: update, matched:300, calling pid = 6949
08-17 19:16:21.611  1477  3321 V TP/MmsSmsProvider: syncDBData start
08-17 19:16:21.611  1477  1491 D TP/MmsSmsProvider: query,matched:400, calling pid = 6949
08-17 19:16:21.611  1477  3321 V TP/MmsSmsProvider: syncDBData sms end
08-17 19:16:21.611  1477  3321 V TP/MmsSmsProvider: syncDBData mms end
08-17 19:16:21.611  1477  3321 V TP/MmsSmsProvider: syncDBData end
08-17 19:16:21.621  6949  7107 D Mms/Synchronizer: [end]    doSync consume time = 61.963646
08-17 19:16:21.621  7109  7109 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 19:16:21.621  7109  7109 D ActivityThread: Added TimaKeyStore provider
08-17 19:16:21.631  1020  4295 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
08-17 19:16:21.641  1020  4295 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:21.641  1020  4295 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:21.641  1020  4295 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:21.641  1020  4295 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:21.651  7109  7109 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-17 19:16:21.651  7109  7109 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-17 19:16:21.651  7109  7109 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-17 19:16:21.661  6880  6940 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
08-17 19:16:21.661  6880  6940 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-17 19:16:21.661  6880  6940 I GAv4    :   adb logcat -s GAv4
08-17 19:16:21.671  7126  7126 E Zygote  : MountEmulatedStorage()
08-17 19:16:21.671  7126  7126 I libpersona: KNOX_SDCARD checking this for 10068
08-17 19:16:21.671  7126  7126 E Zygote  : v2
08-17 19:16:21.671  7126  7126 I libpersona: KNOX_SDCARD not a persona
08-17 19:16:21.671  7126  7126 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 19:16:21.671  6949  7033 D Mms/ArtClassLoader: init [DONE] art
08-17 19:16:21.681  1020  4295 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7126 uid=10068 gids={50068, 9997} abi=armeabi-v7a
08-17 19:16:21.681  7126  7126 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 19:16:21.681  6949  7106 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 54.290312
08-17 19:16:21.681  7126  7126 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-17 19:16:21.701   310   310 I art     : Explicit concurrent mark sweep GC freed 8696(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 616us total 22.915ms
08-17 19:16:21.701  6997  6997 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-17 19:16:21.701  1020  3827 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
08-17 19:16:21.701  7126  7126 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 19:16:21.701  1020  3827 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
08-17 19:16:21.711  7126  7126 D ActivityThread: Added TimaKeyStore provider
08-17 19:16:21.711  1020  3827 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:21.711  1020  3827 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:21.711  1020  3827 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
08-17 19:16:21.721  7103  7103 D AndroidRuntime: 
08-17 19:16:21.721  7103  7103 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-17 19:16:21.721  7103  7103 D AndroidRuntime: CheckJNI is OFF
08-17 19:16:21.721  7103  7103 D AndroidRuntime: readGMSProperty: start
08-17 19:16:21.721  7103  7103 D AndroidRuntime: readGMSProperty: already setted!!
08-17 19:16:21.721  7103  7103 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-17 19:16:21.721  7103  7103 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-17 19:16:21.721  7103  7103 D AndroidRuntime: readGMSProperty: end
08-17 19:16:21.721  7103  7103 D AndroidRuntime: addProductProperty: start
08-17 19:16:21.721   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 607us total 23.991ms
08-17 19:16:21.741  7126  7126 D BadgeProvider: onCreate
08-17 19:16:21.741   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 614us total 19.043ms
08-17 19:16:21.741  7126  7126 D BadgeProvider: DatabaseHelper
08-17 19:16:21.761  6949  7101 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
08-17 19:16:21.761  1477  1986 D TP/SmsProvider: query,matched:26, calling pid = 6949
08-17 19:16:21.761  1477  1986 D TP/SmsProvider: match 26:Elapsed time : 1.256 ms
08-17 19:16:21.761  6997  6997 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-17 19:16:21.771  1020  1341 I ActivityManager: Killing 6430:com.android.defcontainer/u0a3 (adj 15): empty #21
08-17 19:16:21.781  6880  6940 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
08-17 19:16:21.781  1020  1508 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-17 19:16:21.791  1477  1491 D TP/MmsSmsProvider: query,matched:6, calling pid = 6949
08-17 19:16:21.791  1477  1491 D TP/MmsSmsProvider: match 6:Elapsed time : 1.084 ms
08-17 19:16:21.791   291   291 E SMD     : DCD OFF
08-17 19:16:21.801  6880  6940 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
08-17 19:16:21.811  1020  1341 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
08-17 19:16:21.811  1020  1341 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:21.811  1020  1341 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:21.811  1020  1341 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:21.811  1020  1341 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:21.831  1020  1341 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=7148 uid=10023 gids={50023, 9997} abi=armeabi-v7a
08-17 19:16:21.841  7148  7148 E Zygote  : MountEmulatedStorage()
08-17 19:16:21.841  7148  7148 I libpersona: KNOX_SDCARD checking this for 10023
08-17 19:16:21.841  7148  7148 E Zygote  : v2
08-17 19:16:21.841  7148  7148 I libpersona: KNOX_SDCARD not a persona
08-17 19:16:21.841  6880  6940 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.357.23.33
08-17 19:16:21.841  6880  7147 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
08-17 19:16:21.851  6997  7146 D Ads     : Skipping gmscore version check
08-17 19:16:21.871  7109  7109 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
08-17 19:16:21.871  1020  1060 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
08-17 19:16:21.871  1020  1060 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
08-17 19:16:21.871  1020  1060 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:21.871  1020  1060 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:21.871  1020  1060 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:21.871  1020  1060 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:21.871  1882  6896 W art     : Verification of void com.google.android.gms.games.broker.GameAgent.addGameBadgeOps(com.google.android.gms.common.internal.ClientContext, com.google.android.gms.games.server.api.MarketInstance, java.lang.String, java.util.ArrayList, int) took 229.765ms
08-17 19:16:21.901  7148  7148 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 19:16:21.901  7148  7148 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 19:16:21.901  7148  7148 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-17 19:16:21.911  7161  7161 E Zygote  : MountEmulatedStorage()
08-17 19:16:21.911  1020  1060 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7161 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-17 19:16:21.911  1020  3827 I ActivityManager: Killing 6694:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
08-17 19:16:21.911  1020  1340 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-17 19:16:21.921  7161  7161 E Zygote  : v2
08-17 19:16:21.921  7161  7161 I libpersona: KNOX_SDCARD checking this for 10003
08-17 19:16:21.931  7161  7161 I libpersona: KNOX_SDCARD not a persona
08-17 19:16:21.931  7161  7161 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 19:16:21.931  7161  7161 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 19:16:21.931  1020  1340 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:21.931  1020  1340 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:21.931  1020  1340 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
08-17 19:16:21.941  7161  7161 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-17 19:16:21.941  7103  7103 E AffinityControl: AffinityControl: registerfunction enter
08-17 19:16:21.961  7148  7148 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 19:16:21.961  7148  7148 D ActivityThread: Added TimaKeyStore provider
08-17 19:16:21.961  1020  1266 I ActivityManager: Killing 6708:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
08-17 19:16:21.971  7161  7161 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 19:16:21.971  7161  7161 D ActivityThread: Added TimaKeyStore provider
08-17 19:16:21.971  7103  7103 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-17 19:16:21.981  6997  6997 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-17 19:16:21.991  1020  1033 E PersonaManagerService: inState():  stateMachine is null !!
08-17 19:16:21.991  1020  1033 I PersonaManagerService: PersonaId don't exist
08-17 19:16:21.991  1020  1033 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-17 19:16:22.001  1020  1033 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-17 19:16:22.021  1020  1033 W ActivityManager: mDVFSHelper.acquire()
08-17 19:16:22.021  1020  1033 D FocusedStackFrame: Set to : 0
08-17 19:16:22.031  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:22.031  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:22.031  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:22.031  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:22.031  1020  1050 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-17 19:16:22.031  1020  1050 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-17 19:16:22.051  1020  1050 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-17 19:16:22.051  1020  1033 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-17 19:16:22.051  1020  1033 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7190 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-17 19:16:22.051  1020  1033 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-17 19:16:22.051  7190  7190 I libpersona: KNOX_SDCARD checking this for 10170
08-17 19:16:22.051  1020  1033 D InputDispatcher: Focused application set to: xxxx
08-17 19:16:22.051  7190  7190 I libpersona: KNOX_SDCARD not a persona
08-17 19:16:22.051  1020  1033 D InputDispatcher: Focus left window: 1510
08-17 19:16:22.051  7190  7190 E Zygote  : MountEmulatedStorage()
08-17 19:16:22.051  7190  7190 E Zygote  : v2
08-17 19:16:22.051  1020  1050 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-17 19:16:22.051  7190  7190 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 19:16:22.051   258   258 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
08-17 19:16:22.051  7103  7103 D AndroidRuntime: Shutting down VM
08-17 19:16:22.061   284   284 E installd: system dir 0 : /system/app/
08-17 19:16:22.061   284   284 E installd: system dir 1 : /system/priv-app/
08-17 19:16:22.061   284   284 E installd: system dir 2 : /vendor/app/
08-17 19:16:22.061   284   284 E installd: system dir 3 : /oem/app/
08-17 19:16:22.061  7190  7190 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 19:16:22.061  7190  7190 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-17 19:16:22.061  7148  7148 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
08-17 19:16:22.081  1020  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-17 19:16:22.081  1020  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
08-17 19:16:22.081  1020  1508 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.filterinstaller, hostingType: broadcast
08-17 19:16:22.081  7190  7190 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 19:16:22.081  7190  7190 D ActivityThread: Added TimaKeyStore provider
08-17 19:16:22.081  1020  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:22.091  1020  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:22.091  1020  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:22.091  1020  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:22.091  6949  7101 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
08-17 19:16:22.101  7207  7207 E Zygote  : MountEmulatedStorage()
08-17 19:16:22.101  7207  7207 E Zygote  : v2
08-17 19:16:22.101  7207  7207 I libpersona: KNOX_SDCARD checking this for 1000
08-17 19:16:22.101  7207  7207 I libpersona: KNOX_SDCARD not a persona
08-17 19:16:22.101  7207  7207 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 19:16:22.111  7148  7148 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
08-17 19:16:22.111  7148  7148 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
08-17 19:16:22.111  7148  7148 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
08-17 19:16:22.111  7148  7148 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
08-17 19:16:22.111  7148  7148 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
08-17 19:16:22.121  7148  7148 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
08-17 19:16:22.121  7148  7148 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
08-17 19:16:22.121  7148  7148 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
08-17 19:16:22.121  7148  7148 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
08-17 19:16:22.121  7148  7148 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
08-17 19:16:22.121  1020  1060 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
08-17 19:16:22.121  7148  7148 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
08-17 19:16:22.121  7207  7207 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 19:16:22.121  7148  7148 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
08-17 19:16:22.121  7207  7207 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-17 19:16:22.131  7148  7148 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
08-17 19:16:22.131  1882  4304 I Icing   : Indexing D0AE1F45F393341DA3213A207506F1C2E721F1A9 from com.google.android.googlequicksearchbox
08-17 19:16:22.131  1020  1508 I ActivityManager: Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=7207 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-17 19:16:22.131  1020  1508 I ActivityManager: Killing 5108:com.google.android.gms.wearable/u0a11 (adj 15): empty #21
08-17 19:16:22.141  1020  1266 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-17 19:16:22.141  1020  1020 V ActivityManager: Display changed displayId=0
08-17 19:16:22.141  1020  1048 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-17 19:16:22.161  1020  1266 D PersonaManager: isKioskContainerExistOnDevice
08-17 19:16:22.171  7207  7207 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 19:16:22.171  7207  7207 D ActivityThread: Added TimaKeyStore provider
08-17 19:16:22.191  1020  1020 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-17 19:16:22.201   258  1100 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
08-17 19:16:22.201   258   452 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
08-17 19:16:22.221  1510  1510 V ActivityThread: updateVisibility : ActivityRecord{39a59044 token=android.os.BinderProxy@2b5ec990 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-17 19:16:22.221  1510  1510 D Launcher: onTrimMemory. Level: 20
08-17 19:16:22.231  7207  7207 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
08-17 19:16:22.241  7207  7207 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
08-17 19:16:22.241  1020  1266 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
08-17 19:16:22.241  1020  1266 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
08-17 19:16:22.241  1020  1266 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:22.241  1020  1266 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:22.241  1020  1266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
08-17 19:16:22.241  1020  1525 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
08-17 19:16:22.251  7207  7207 I FilterInstaller: FilterPackageService : ACTION_CHANGED
08-17 19:16:22.261  7103  7103 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-17 19:16:22.281  1882  4304 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,08-17 19:16:22.291  7207  7225 E FilterInstaller: installFilters
,08-17 19:16:22.291  7207  7225 E FilterInstaller: There is no requred permission
,08-17 19:16:22.311  6880  7196 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-17 19:16:22.311  6880  7196 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-17 19:16:22.331  7190  7190 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-17 19:16:22.351  7190  7190 I cr.library_loader: Time to load native libraries: 4 ms (timestamps 7498-7502)
,08-17 19:16:22.351  7190  7190 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-17 19:16:22.361  6880  7196 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-17 19:16:22.371  1020  1341 I ActivityManager: Killing 6741:com.samsung.helphub/1000 (adj 15): empty #21
,08-17 19:16:22.371  7190  7190 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2264edaa}
,08-17 19:16:22.371  7190  7190 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-17 19:16:22.371  7190  7190 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-17 19:16:22.421  7190  7190 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-17 19:16:22.421  7190  7190 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-17 19:16:22.431  7190  7190 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-17 19:16:22.441  1882  4304 I Icing   : Indexing done D0AE1F45F393341DA3213A207506F1C2E721F1A9
,08-17 19:16:22.451  1020  1506 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,08-17 19:16:22.451  1020  1506 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:22.451  1020  1506 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:22.451  1020  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:22.451  6880  7196 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-17 19:16:22.451  6880  7196 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@23f05670: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-17 19:16:22.451  6880  7196 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-17 19:16:22.491  7190  7190 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-17 19:16:22.491  7190  7190 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-17 19:16:22.491  7190  7190 I Adreno-EGL: Build Date: 04/06/15 Mon
08-17 19:16:22.491  7190  7190 I Adreno-EGL: Local Branch: 
08-17 19:16:22.491  7190  7190 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-17 19:16:22.491  7190  7190 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-17 19:16:22.491  7190  7190 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-17 19:16:22.551  7190  7190 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-17 19:16:22.571  7190  7190 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-17 19:16:22.571  7190  7190 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-17 19:16:22.571  7190  7190 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-17 19:16:22.581  7190  7190 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-17 19:16:22.671  1020  1045 W ActivityManager: Activity pause timeout for ActivityRecord{da0c8c3 u0 com.test.thalitest/.MainActivity t163}
,08-17 19:16:22.701  7190  7190 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-17 19:16:22.711  7190  7190 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-17 19:16:22.721  7190  7190 D PhoneWindow: *FMB* installDecor mIsFloating : false
,08-17 19:16:22.721  7190  7190 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-17 19:16:22.731  7190  7190 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-17 19:16:22.731  7190  7190 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-17 19:16:22.741  7190  7190 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-17 19:16:22.781  7190  7253 D OpenGLRenderer: Render dirty regions requested: true
,08-17 19:16:22.791  1020  1340 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-17 19:16:22.791  1020  1340 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-17 19:16:22.791  1020  1340 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-17 19:16:22.791  1020  1020 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-17 19:16:22.791  1020  1020 D PersonaManagerService: getPersonasForUser(): returning null!
,08-17 19:16:22.791  1020  1309 E Watchdog: !@Sync 3
,08-17 19:16:22.791  7190  7240 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,08-17 19:16:22.801  7190  7190 V ActivityThread: updateVisibility : ActivityRecord{1e24890a token=android.os.BinderProxy@30ac325f {com.test.thalitest/com.test.thalitest.MainActivity}} show : true,
,08-17 19:16:22.801  7190  7190 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-17 19:16:22.801  7190  7190 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-17 19:16:22.811   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,08-17 19:16:22.821  1020  1508 D InputDispatcher: Focus entered window: 7190
,08-17 19:16:22.831  1020  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-17 19:16:22.831  1020  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-17 19:16:22.831  7190  7190 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-17 19:16:22.831  7190  7253 I OpenGLRenderer: Initialized EGL, version 1.4
,08-17 19:16:22.831  7190  7253 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,08-17 19:16:22.831  7190  7253 D OpenGLRenderer: Enabling debug mode 0
,08-17 19:16:22.861  1020  4295 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-17 19:16:22.861  1180  1180 D PanelView: There is/are notification(s) 
,08-17 19:16:22.871  1020  7257 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-17 19:16:22.881  1020  1050 I ActivityManager: Displayed Component not be shown by security: +712ms (total +852ms)
,08-17 19:16:22.881  1020  1050 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{da0c8c3 u0 com.test.thalitest/.MainActivity t163} time:108031
08-17 19:16:22.881  1020  1050 W ActivityManager: mDVFSHelper.release()
,08-17 19:16:22.881  7190  7190 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-17 19:16:22.881  7190  7190 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@30ac325f time:108036
,08-17 19:16:22.881   258   450 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,08-17 19:16:22.881   258  1890 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,08-17 19:16:22.961  1894  1894 I SamsungIME: getCurrentCandidateView
,08-17 19:16:22.981  1020  1525 I ActivityManager: Killing 6759:com.sec.spp.push/u0a32 (adj 15): empty #21
,08-17 19:16:22.991  7190  7190 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7190
,08-17 19:16:23.051  1894  1894 D SamsungIME: Dismiss ExpandCandiate
,08-17 19:16:23.181  7190  7190 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-17 19:16:23.201  1894  1894 I SamsungIME: getDebugLevel  : 0x4f4c
,08-17 19:16:23.241  1894  1894 I SamsungIME: getDebugLevel  : 0x4f4c
,08-17 19:16:23.251  1894  1894 I SamsungIME: KeybaordView init() : load resources
,08-17 19:16:23.271  7190  7259 D jxcore_app_log: JniHelper::setJavaVM(0xb74d42b0), pthread_self() = -1213854968
,08-17 19:16:23.281  7190  7259 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-17 19:16:23.281  7190  7259 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
,08-17 19:16:23.281  7190  7259 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-17 19:16:23.281  7190  7259 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-17 19:16:23.281  7190  7259 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-17 19:16:23.281  7190  7259 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fd179b0 added. We now have 1 listener(s)
,08-17 19:16:23.281  1894  1894 I SamsungIME: getCurrentKeyboard,
08-17 19:16:23.281  1894  1894 I SamsungIME: getTextKeyboard
,08-17 19:16:23.291  7190  7259 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
,08-17 19:16:23.291  7190  7259 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-17 19:16:23.291  7190  7259 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 19:16:23.291  7190  7259 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 19:16:23.301  7190  7259 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-17 19:16:23.301  7190  7259 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-17 19:16:23.301  7190  7259 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-17 19:16:23.301  7190  7259 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
08-17 19:16:23.301  7190  7259 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-17 19:16:23.301  7190  7259 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-17 19:16:23.301  7190  7259 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-17 19:16:23.301  7190  7259 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-17 19:16:23.301  7190  7259 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-17 19:16:23.301  7190  7259 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-17 19:16:23.301  7190  7259 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-17 19:16:23.301  7190  7259 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-17 19:16:23.301  7190  7259 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-17 19:16:23.301  7190  7259 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-17 19:16:23.301  7190  7259 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66c714f added. We now have 1 listener(s)
,08-17 19:16:23.301  7190  7259 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 19:16:23.311  7190  7259 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 19:16:23.311  7190  7259 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-17 19:16:23.311  7190  7259 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-17 19:16:23.311  7190  7259 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-17 19:16:23.311  7190  7259 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-17 19:16:23.311  1894  1894 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-17 19:16:23.311  7190  7259 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:16:23.321  7190  7259 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
,08-17 19:16:23.321  7190  7259 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-17 19:16:23.321  7190  7259 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:16:23.321  7190  7259 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:23.321  7190  7259 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:23.321  7190  7259 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:23.321  7190  7259 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:23.321  7190  7259 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:16:23.321  7190  7259 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:16:23.321  7190  7259 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 19:16:23.321  7190  7259 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-17 19:16:23.321  7190  7259 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 19:16:23.321  7190  7259 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-17 19:16:23.331  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:23.331  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:23.361  7190  7190 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-17 19:16:23.491  6949  6949 I Mms/MmsApp:  start initViewCache mms
,08-17 19:16:23.491  6949  6949 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1813.402343
,08-17 19:16:23.491  6949  6949 D Mms/ComposeMessageFragment: fillCache, easy = false
,08-17 19:16:23.591  6949  6949 D AbsListView: Get MotionRecognitionManager
,08-17 19:16:23.591  1020  1747 D MotionRecognitionService:  ssp status : false
,08-17 19:16:23.601  6949  6949 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 108.248438
,08-17 19:16:23.611  6774  6802 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
,08-17 19:16:23.631  6774  6802 I AcmsKeyStoreHelper: Key Store exist
08-17 19:16:23.631  6774  6802 I AcmsKeyStoreHelper: Hence loading the keystore file
,08-17 19:16:23.681  6774  6802 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
08-17 19:16:23.681  6774  6802 I AcmsCertificateMngr: getKeyStoreForApplication success 
08-17 19:16:23.681  6774  6802 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
08-17 19:16:23.681  6774  6802 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-17 19:16:23.681  6774  6802 D AcmsServiceMonitor: Decrementing - Counter value: 1
08-17 19:16:23.681  6774  6802 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
,08-17 19:16:23.681  6949  6949 D Mms/BubbleViewCache: fillCache bubble = 1
08-17 19:16:23.681  6774  6802 D AcmsCore: This is NOT a valid MirrorLink app
08-17 19:16:23.681  6774  6802 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
08-17 19:16:23.681  6774  6802 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-17 19:16:23.681  6774  6802 D AcmsServiceMonitor: Decrementing - Counter value: 0
08-17 19:16:23.681  6774  6802 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
,08-17 19:16:23.681  6774  6774 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
,08-17 19:16:23.681  6774  6774 D AcmsService: Enter onDestroy
08-17 19:16:23.681  6774  6774 I AcmsService: cleanUp(): inside service clean up
,08-17 19:16:23.681  6774  6774 D AcmsCore: AcmsCore: inside DeInit
08-17 19:16:23.681  6774  6774 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
,08-17 19:16:23.691  6774  6774 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
08-17 19:16:23.691  6774  6774 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
,08-17 19:16:23.691  6774  6774 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
08-17 19:16:23.691  6774  6774 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
,08-17 19:16:23.691  6774  6774 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
,08-17 19:16:23.691  6774  6774 D AcmsService: killing acms process
,08-17 19:16:23.691  6774  6774 I Process : Sending signal. PID: 6774 SIG: 9
,08-17 19:16:23.771  1020  1341 I ActivityManager: Process ACMS.Process (pid 6774)(adj 0) has died(26,769)
,08-17 19:16:23.771   324   324 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-17 19:16:23.771   324   324 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-17 19:16:24.231  7190  7267 W jxcore-log: Initializing JXcore engine
08-17 19:16:24.231  7190  7267 W jxcore-log: JXcore engine is ready
,08-17 19:16:24.291  1998  1998 E audit   : type=1400 msg=audit(1471454184.291:205): avc:  denied  { ioctl } for  pid=7267 comm="Thread-1366" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2071 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-17 19:16:24.291  1998  1998 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-17 19:16:24.291  1998  1998 E audit   : type=1300 msg=audit(1471454184.291:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=3 a3=9f0fb8f8 items=0 ppid=310 ppcomm=main pid=7267 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1366" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-17 19:16:24.291  1998  1998 E audit   : type=1320 msg=audit(1471454184.291:205): 
,08-17 19:16:24.311  7190  7267 W jxcore-log: Starting JXcore engine
,08-17 19:16:24.411  7190  7267 W jxcore-log: Platform android
08-17 19:16:24.411  7190  7267 W jxcore-log: 
08-17 19:16:24.421  7190  7267 W jxcore-log: Process ARCH arm
08-17 19:16:24.421  7190  7267 W jxcore-log: 
,08-17 19:16:24.701  7190  7267 I jxcore-log: JXcore Cordova bridge is ready!
08-17 19:16:24.701  7190  7267 I jxcore-log: 
,08-17 19:16:24.701  7190  7267 W jxcore-log: JXcore engine is started
,08-17 19:16:24.711  7190  7259 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-17 19:16:24.711  7190  7190 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-17 19:16:24.791   291   291 E SMD     : DCD OFF
,08-17 19:16:26.171  1662  1662 I ConfigService: onDestroy
,08-17 19:16:27.511  1020  1052 I PowerManagerService: [PWL] Off : 50s ago
,08-17 19:16:27.611  1020  3378 D SSRM:n  : SIOP:: AP = 400
,08-17 19:16:27.791   291   291 E SMD     : DCD OFF,
,08-17 19:16:28.771   324   324 I ServiceManager: Waiting for service AtCmdFwd...,
,08-17 19:16:29.771   324   324 I ServiceManager: Waiting for service AtCmdFwd...,
,08-17 19:16:30.771   324   324 I ServiceManager: Waiting for service AtCmdFwd...
,08-17 19:16:30.801   291   291 E SMD     : DCD OFF
,08-17 19:16:30.831  1020  1266 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-17 19:16:30.831  1020  1266 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4255, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-17 19:16:30.831  1020  1266 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-17 19:16:30.831  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-17 19:16:30.831  1020  1266 D BatteryService: stay LED for charging
,08-17 19:16:30.841  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-17 19:16:30.841  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-17 19:16:30.841  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-17 19:16:30.841  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-17 19:16:30.841  1020  1020 I MotionRecognitionService: Plugged
08-17 19:16:30.841  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,08-17 19:16:30.851  3213  3213 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-17 19:16:30.851  3213  3366 D HeadsetStateMachine: Disconnected process message: 10
,08-17 19:16:30.871  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-17 19:16:30.871  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-17 19:16:30.871  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-17 19:16:31.771   324   324 I ServiceManager: Waiting for service AtCmdFwd...,
,08-17 19:16:32.071  1020  1060 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-17 19:16:32.121  1020  1060 D PackageManager: [MSG] MCS_UNBIND
,08-17 19:16:32.131  1020  1525 I ActivityManager: Killing 6724:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
,08-17 19:16:32.771   324   324 I ServiceManager: Waiting for service AtCmdFwd...,
,08-17 19:16:32.921  5992  5992 D FactoryTest: Not factory mode
,08-17 19:16:32.931  5992  5992 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-17 19:16:32.931  5992  5992 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-17 19:16:32.931  5992  5992 D MTPRx   : still no open session command from host, so toast
,08-17 19:16:32.931  5992  5992 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 ,
08-17 19:16:32.931  5992  5992 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-17 19:16:32.931  5992  5992 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:118087
08-17 19:16:32.931  1020  1340 E PersonaManagerService: inState():  stateMachine is null !!
08-17 19:16:32.931  1020  1340 I PersonaManagerService: PersonaId don't exist
08-17 19:16:32.931  1020  1340 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-17 19:16:32.941  1020  1340 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-17 19:16:32.941  1020  1340 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:32.941  1020  1340 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:32.941  1020  1340 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-17 19:16:32.941  1020  1340 W ActivityManager: mDVFSHelper.acquire()
,08-17 19:16:32.961  1020  1340 D PersonaManager: isKioskContainerExistOnDevice
,08-17 19:16:32.971  1020  1340 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-17 19:16:32.971  1020  1340 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
08-17 19:16:32.971  1020  1340 D InputDispatcher: Focused application set to: xxxx
,08-17 19:16:32.971  1020  1340 D InputDispatcher: Focus left window: 7190
,08-17 19:16:32.971  5992  5992 E MTPRx   : started activity for popup
,08-17 19:16:32.971  1020  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-17 19:16:32.981  1020  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-17 19:16:32.991  5992  5992 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,08-17 19:16:32.991  5992  5992 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-17 19:16:32.991  5992  5992 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-17 19:16:32.991  5992  5992 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 19:16:32.991  5992  5992 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-17 19:16:32.991  5992  5992 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-17 19:16:33.021  5992  5992 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-17 19:16:33.021  1020  1494 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-17 19:16:33.021  1020  1494 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-17 19:16:33.021  1020  1494 D InputDispatcher: Focused application set to: xxxx
08-17 19:16:33.021  1020  1494 D InputDispatcher: Focus entered window: 7190
,08-17 19:16:33.021  1020  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-17 19:16:33.031  1020  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-17 19:16:33.031  1020  1266 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-17 19:16:33.031  1020  1266 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@6250eef attribute=null, token = android.os.BinderProxy@3ce1831e
,08-17 19:16:33.061  5992  5992 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-17 19:16:33.071  5992  5992 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-17 19:16:33.071  5992  5992 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-17 19:16:33.091  7190  7190 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-17 19:16:33.091  7190  7190 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED,
08-17 19:16:33.091  7190  7190 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-17 19:16:33.091  7190  7190 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
08-17 19:16:33.101  1020  1506 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-17 19:16:33.101  1020  1506 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-17 19:16:33.101  1020  1506 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-17 19:16:33.101  1020  1020 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-17 19:16:33.101  1020  1020 D PersonaManagerService: getPersonasForUser(): returning null!
,08-17 19:16:33.111  7190  7190 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-17 19:16:33.111  7190  7190 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-17 19:16:33.111  7190  7190 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@30ac325f time:118268
,08-17 19:16:33.111  7190  7190 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@222b38b Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@34fb8cbe, 16908290=android.view.AbsSavedState$1@34fb8cbe}, android:focusedViewId=100}]}]
08-17 19:16:33.111  7190  7190 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-17 19:16:33.111  7190  7190 V ActivityThread: updateVisibility : ActivityRecord{1e24890a token=android.os.BinderProxy@30ac325f {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-17 19:16:33.121  7190  7190 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-17 19:16:33.121  7190  7190 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-17 19:16:33.121  1020  1508 D PersonaManager: isKioskContainerExistOnDevice
,08-17 19:16:33.771   324   324 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-17 19:16:33.801   291   291 E SMD     : DCD OFF
,08-17 19:16:35.951  1020  1045 W ActivityManager: mDVFSHelper.release()
,08-17 19:16:36.531  1020  1098 V AlarmManager: waitForAlarm result :4
08-17 19:16:36.531  1020  1098 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,08-17 19:16:36.751  6997  7100 D Finsky  : [1319] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,08-17 19:16:36.751  6997  6997 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-17 19:16:36.801   291   291 E SMD     : DCD OFF
,08-17 19:16:37.631  7190  7267 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-17 19:16:37.631  7190  7267 I jxcore-log: 
,08-17 19:16:37.631  7190  7267 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-17 19:16:37.631  7190  7267 I jxcore-log: 
,08-17 19:16:37.641  1020  3378 D SSRM:n  : SIOP:: AP = 360,
,08-17 19:16:37.641  7190  7267 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-17 19:16:37.641  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:37.641  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:37.641  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:37.641  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:37.641  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:16:37.641  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:16:37.641  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 19:16:37.641  7190  7267 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 19:16:37.641  7190  7267 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-17 19:16:37.641  7190  7267 I jxcore-log: 
,08-17 19:16:37.651  7190  7267 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-17 19:16:37.651  7190  7267 I jxcore-log: 
,08-17 19:16:37.691  1020  3407 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-17 19:16:38.091  7190  7267 D ExecuteNativeTests: Running unit tests,
,08-17 19:16:38.171  7190  7267 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
08-17 19:16:38.171  7190  7267 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13e2700f added. We now have 2 listener(s),
,08-17 19:16:38.171  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41",
08-17 19:16:38.171  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:16:38.171  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 19:16:38.171  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:16:38.171  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3028789c added. We now have 2 listener(s)
08-17 19:16:38.171  7190  7267 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:16:38.171  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 19:16:38.181  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:16:38.181  7190  7267 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:16:38.181  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:38.181  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:38.181  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:38.181  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:38.181  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:16:38.181  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:16:38.181  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 19:16:38.181  7190  7267 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 19:16:38.181  7190  7267 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 19:16:38.191  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:38.191  7190  7267 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-17 19:16:38.191  7190  7267 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 19:16:38.191  7190  7267 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-17 19:16:38.191  7190  7267 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-17 19:16:38.191  7190  7267 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-17 19:16:38.191  7190  7267 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 19:16:38.191  7190  7267 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 19:16:38.191  7190  7267 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-17 19:16:38.191  7190  7267 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 19:16:38.191  7190  7267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:38.191  7190  7267 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:38.191  7190  7267 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:38.191  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.191  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:16:38.191  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 19:16:38.191  7190  7267 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13e2700f removed from the list
08-17 19:16:38.191  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.191  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3028789c removed from the list
,08-17 19:16:38.191  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:38.191  7190  7267 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:38.191  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.191  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.191  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:38.201  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:38.201  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 19:16:38.201  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.201  7190  7267 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3028789c not in the list,
,08-17 19:16:38.201  7190  7267 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-17 19:16:38.201  7190  7267 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:38.201  7190  7267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:38.201  7190  7267 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:38.201  7190  7267 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 19:16:38.201  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.201  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.201  7190  7267 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13e2700f not in the list
08-17 19:16:38.201  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.201  7190  7267 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3028789c not in the list
08-17 19:16:38.201  7190  7267 D io.jxcore.node.ConnectivityMonitor: stop,
08-17 19:16:38.201  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.201  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.201  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:16:38.201  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.201  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:38.201  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-17 19:16:38.201  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.201  7190  7267 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3028789c not in the list
,08-17 19:16:38.201  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-17 19:16:38.201  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-17 19:16:38.201  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-17 19:16:38.201  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210],
08-17 19:16:38.201  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-17 19:16:38.201  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-17 19:16:38.201  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-17 19:16:38.201  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-17 19:16:38.201  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-17 19:16:38.201  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-17 19:16:38.201  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-17 19:16:38.201  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-17 19:16:38.201  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-17 19:16:38.201  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-17 19:16:38.201  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-17 19:16:38.201  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-17 19:16:38.201  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-17 19:16:38.201  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-17 19:16:38.201  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-17 19:16:38.201  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-17 19:16:38.201  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-17 19:16:38.201  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-17 19:16:38.201  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-17 19:16:38.201  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-17 19:16:38.201  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-17 19:16:38.201  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-17 19:16:38.201  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-17 19:16:38.201  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-17 19:16:38.201  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-17 19:16:38.201  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-17 19:16:38.201  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnectio,ns: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-17 19:16:38.201  7190  7267 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:38.201  7190  7267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:38.201  7190  7267 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:38.201  7190  7267 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:38.201  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.201  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.201  7190  7267 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13e2700f not in the list
08-17 19:16:38.201  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.201  7190  7267 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3028789c not in the list
08-17 19:16:38.201  7190  7267 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:38.201  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.201  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.201  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.201  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.211  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:38.211  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:38.211  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.211  7190  7267 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3028789c not in the list
08-17 19:16:38.211  7190  7267 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-17 19:16:38.211  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:16:38.211  7190  7267 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:16:38.211  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:38.211  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:38.211  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:38.211  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:38.211  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:16:38.211  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:16:38.211  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 19:16:38.211  7190  7267 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 19:16:38.211  7190  7267 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 19:16:38.211  7190  7267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 19:16:38.211  7190  7267 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 19:16:38.211  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 19:16:38.211  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:16:38.211  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 19:16:38.221  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:16:38.221  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-17 19:16:38.221  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:16:38.221  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-17 19:16:38.231  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-17 19:16:38.231  7190  7267 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-17 19:16:38.231  7190  7267 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-17 19:16:38.231  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-17 19:16:38.231  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 19:16:38.231  7190  7267 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-17 19:16:38.241  3213  3375 D BtGatt.GattService: registerClient() - UUID=8634ee68-fad6-47f2-b954-534517a9a3a9
,08-17 19:16:38.281  3213  3287 D BtGatt.GattService: onClientRegistered() - UUID=8634ee68-fad6-47f2-b954-534517a9a3a9, clientIf=6
08-17 19:16:38.291  7190  7200 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-17 19:16:38.291  3213  3223 D BtGatt.GattService: start scan with filters
,08-17 19:16:38.291  3213  3365 D BtGatt.ScanManager: handling starting scan
,08-17 19:16:38.291  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-17 19:16:38.291  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-17 19:16:38.291  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-17 19:16:38.291  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 19:16:38.301  3213  3365 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e7895
,08-17 19:16:38.301  7190  7267 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 19:16:38.301  7190  7267 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 19:16:38.301  7190  7190 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 19:16:38.301  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 19:16:38.301  3213  3287 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-17 19:16:38.311  3213  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:16:38.311  3213  3365 D BtGatt.ScanManager: allow scan with filters
08-17 19:16:38.311  3213  3365 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-17 19:16:38.311  3213  3365 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-17 19:16:38.311  7190  7267 I io.jxcore.node.ConnectionHelper: start: OK
,08-17 19:16:38.311  3213  3287 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-17 19:16:38.311  3213  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:38.311  7190  7267 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:38.311  7190  7267 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-17 19:16:38.311  7190  7267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:38.311  7190  7267 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-17 19:16:38.311  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.311  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 19:16:38.311  7190  7267 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 19:16:38.311  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 19:16:38.311  7190  7267 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 19:16:38.311  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-17 19:16:38.311  3213  3365 D BtGatt.ScanManager: Starting BLE batch scan
,08-17 19:16:38.311  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 19:16:38.311  3213  3365 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-17 19:16:38.311  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 19:16:38.321  3213  3362 D BtGatt.GattService: stopScan() - queue size =1
,08-17 19:16:38.321  3213  3375 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-17 19:16:38.321  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-17 19:16:38.321  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 19:16:38.321  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-17 19:16:38.321  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 19:16:38.321  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 19:16:38.321  7190  7267 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 19:16:38.321  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 19:16:38.321  7190  7267 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 19:16:38.321  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 19:16:38.321  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 19:16:38.321  7190  7190 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 19:16:38.321  7190  7267 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:38.321  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.321  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:16:38.321  7190  7190 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:16:38.321  7190  7267 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13e2700f not in the list
08-17 19:16:38.321  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.321  7190  7190 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 19:16:38.321  7190  7267 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3028789c not in the list
08-17 19:16:38.321  7190  7267 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:38.321  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.321  7190  7267 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-17 19:16:38.321  3213  3287 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-17 19:16:38.321  3213  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:16:38.331  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:16:38.331  7190  7267 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:16:38.331  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:38.331  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:38.331  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:38.331  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:38.331  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:16:38.331  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:16:38.331  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 19:16:38.331  7190  7267 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 19:16:38.331  7190  7267 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 19:16:38.331  7190  7267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 19:16:38.331  7190  7267 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 19:16:38.331  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 19:16:38.331  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:16:38.331  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 19:16:38.331  3213  3287 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-17 19:16:38.331  3213  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:38.341  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 19:16:38.341  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:38.341  3213  3365 D BtGatt.ScanManager: filter size is 1
,08-17 19:16:38.341  3213  3365 D BtGatt.ScanManager: delete FilterIndex - 3
,08-17 19:16:38.341  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:38.341  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 19:16:38.341  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 19:16:38.351  3213  3287 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-17 19:16:38.351  3213  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:16:38.351  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-17 19:16:38.351  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 19:16:38.351  7190  7267 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-17 19:16:38.351  3213  3365 D BtGatt.ScanManager: stopping BLe Batch
,08-17 19:16:38.351  3213  3375 D BtGatt.GattService: registerClient() - UUID=e53a283f-e733-42e1-9d2e-5262973d9410,
,08-17 19:16:38.351  3213  3287 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-17 19:16:38.351  3213  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:38.351  3213  3365 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-17 19:16:38.361  3213  3287 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-17 19:16:38.361  3213  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:38.391  3213  3287 D BtGatt.GattService: onClientRegistered() - UUID=e53a283f-e733-42e1-9d2e-5262973d9410, clientIf=6
,08-17 19:16:38.391  7190  7199 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-17 19:16:38.391  3213  3223 D BtGatt.GattService: start scan with filters
,08-17 19:16:38.391  3213  3365 D BtGatt.ScanManager: handling starting scan
,08-17 19:16:38.391  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-17 19:16:38.391  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 19:16:38.391  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-17 19:16:38.401  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 19:16:38.401  7190  7267 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 19:16:38.401  3213  3287 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-17 19:16:38.401  3213  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:38.401  3213  3365 D BtGatt.ScanManager: allow scan with filters
08-17 19:16:38.401  3213  3365 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-17 19:16:38.401  3213  3365 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-17 19:16:38.401  7190  7190 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 19:16:38.401  7190  7267 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 19:16:38.401  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 19:16:38.411  3213  3287 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-17 19:16:38.411  3213  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:38.411  3213  3365 D BtGatt.ScanManager: Starting BLE batch scan
,08-17 19:16:38.411  3213  3365 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-17 19:16:38.411  7190  7267 I io.jxcore.node.ConnectionHelper: start: OK
,08-17 19:16:38.411  7190  7267 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 19:16:38.411  7190  7267 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-17 19:16:38.411  7190  7267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-17 19:16:38.411  7190  7267 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-17 19:16:38.411  3213  3287 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
08-17 19:16:38.411  3213  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:16:38.411  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.411  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 19:16:38.411  7190  7267 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 19:16:38.411  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 19:16:38.411  7190  7267 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 19:16:38.411  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-17 19:16:38.411  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 19:16:38.421  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-17 19:16:38.421  3213  3362 D BtGatt.GattService: stopScan() - queue size =1
08-17 19:16:38.421  3213  3375 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-17 19:16:38.421  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-17 19:16:38.421  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 19:16:38.421  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 19:16:38.421  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 19:16:38.421  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-17 19:16:38.421  3213  3287 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-17 19:16:38.421  7190  7267 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 19:16:38.421  3213  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:38.421  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
08-17 19:16:38.421  7190  7267 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 19:16:38.421  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 19:16:38.421  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:16:38.421  7190  7267 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 19:16:38.421  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.421  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:16:38.421  7190  7267 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13e2700f not in the list
08-17 19:16:38.421  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.421  7190  7267 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3028789c not in the list
08-17 19:16:38.421  7190  7267 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 19:16:38.421  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.421  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.421  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.421  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:38.421  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:38.421  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 19:16:38.421  7190  7267 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3028789c not in the list
08-17 19:16:38.421  7190  7267 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-17 19:16:38.421  7190  7190 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 19:16:38.421  7190  7190 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 19:16:38.431  3213  3365 D BtGatt.ScanManager: filter size is 1
08-17 19:16:38.431  3213  3365 D BtGatt.ScanManager: delete FilterIndex - 4
08-17 19:16:38.431  7190  7190 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 19:16:38.431  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:16:38.431  3213  3287 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-17 19:16:38.431  3213  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:38.431  3213  3365 D BtGatt.ScanManager: stopping BLe Batch
,08-17 19:16:38.431  7190  7267 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:16:38.431  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:38.431  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:38.431  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:38.431  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:38.431  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:16:38.431  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:16:38.431  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 19:16:38.431  7190  7267 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 19:16:38.431  7190  7267 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 19:16:38.431  7190  7267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 19:16:38.431  7190  7267 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 19:16:38.431  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 19:16:38.431  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:16:38.431  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 19:16:38.431  3213  3287 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-17 19:16:38.431  3213  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:38.441  3213  3365 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-17 19:16:38.441  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:38.441  3213  3287 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-17 19:16:38.441  3213  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:38.441  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:38.441  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 19:16:38.441  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 19:16:38.451  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 19:16:38.451  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-17 19:16:38.451  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-17 19:16:38.451  7190  7267 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-17 19:16:38.451  3213  3222 D BtGatt.GattService: registerClient() - UUID=73763986-8b55-41de-99ac-29912595d7f4
,08-17 19:16:38.491  3213  3287 D BtGatt.GattService: onClientRegistered() - UUID=73763986-8b55-41de-99ac-29912595d7f4, clientIf=6
,08-17 19:16:38.491  7190  7199 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6,
,08-17 19:16:38.501  3213  3362 D BtGatt.GattService: start scan with filters
,08-17 19:16:38.501  3213  3365 D BtGatt.ScanManager: handling starting scan
,08-17 19:16:38.501  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-17 19:16:38.501  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-17 19:16:38.501  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 19:16:38.501  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 19:16:38.501  7190  7267 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 19:16:38.501  7190  7190 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 19:16:38.511  7190  7267 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-17 19:16:38.511  3213  3287 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-17 19:16:38.511  3213  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:38.511  3213  3365 D BtGatt.ScanManager: allow scan with filters
08-17 19:16:38.511  3213  3365 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-17 19:16:38.511  3213  3365 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-17 19:16:38.511  3213  3287 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-17 19:16:38.511  3213  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:38.511  3213  3365 D BtGatt.ScanManager: Starting BLE batch scan
,08-17 19:16:38.511  3213  3365 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-17 19:16:38.511  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 19:16:38.521  3213  3287 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-17 19:16:38.521  3213  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:38.521  7190  7267 I io.jxcore.node.ConnectionHelper: start: OK
,08-17 19:16:38.521  7190  7267 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 19:16:38.521  7190  7267 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-17 19:16:38.521  7190  7267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:38.521  7190  7267 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-17 19:16:38.521  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:16:38.521  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 19:16:38.521  7190  7267 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-17 19:16:38.521  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-17 19:16:38.531  7190  7267 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 19:16:38.531  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-17 19:16:38.531  3213  3287 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-17 19:16:38.531  3213  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:16:38.531  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 19:16:38.531  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 19:16:38.531  3213  3222 D BtGatt.GattService: stopScan() - queue size =1
,08-17 19:16:38.531  3213  3365 D BtGatt.ScanManager: filter size is 1
,08-17 19:16:38.531  3213  3365 D BtGatt.ScanManager: delete FilterIndex - 5
,08-17 19:16:38.531  3213  3362 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-17 19:16:38.541  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 19:16:38.541  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 19:16:38.541  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 19:16:38.541  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 19:16:38.541  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 19:16:38.541  7190  7267 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 19:16:38.541  3213  3287 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
08-17 19:16:38.541  3213  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
08-17 19:16:38.541  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 19:16:38.541  7190  7267 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 19:16:38.541  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 19:16:38.541  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:16:38.541  3213  3365 D BtGatt.ScanManager: stopping BLe Batch
,08-17 19:16:38.541  7190  7190 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 19:16:38.541  7190  7190 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 19:16:38.541  7190  7190 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 19:16:38.541  7190  7267 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 19:16:38.541  7190  7267 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-17 19:16:38.541  7190  7267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:38.541  7190  7267 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 19:16:38.551  7190  7267 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:38.551  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.551  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:16:38.551  7190  7267 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13e2700f not in the list
,08-17 19:16:38.551  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.551  7190  7267 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3028789c not in the list
08-17 19:16:38.551  7190  7267 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:38.551  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.551  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.551  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.551  3213  3287 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-17 19:16:38.551  3213  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:16:38.551  3213  3365 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-17 19:16:38.551  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 19:16:38.551  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:38.551  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 19:16:38.551  7190  7267 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3028789c not in the list
,08-17 19:16:38.551  7190  7267 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-17 19:16:38.551  7190  7267 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 19:16:38.551  7190  7267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:38.551  7190  7267 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 19:16:38.551  7190  7267 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:38.551  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.551  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.551  7190  7267 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13e2700f not in the list
08-17 19:16:38.551  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.551  7190  7267 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3028789c not in the list
08-17 19:16:38.551  7190  7267 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:38.551  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.551  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.551  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.551  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:38.551  3213  3287 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-17 19:16:38.551  3213  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:38.561  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:38.561  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:38.561  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.561  7190  7267 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3028789c not in the list
,08-17 19:16:38.561  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-17 19:16:38.561  7190  7267 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 19:16:38.561  7190  7267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:38.561  7190  7267 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 19:16:38.561  7190  7267 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 19:16:38.561  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.561  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:38.561  7190  7267 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13e2700f not in the list
08-17 19:16:38.561  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 19:16:38.561  7190  7267 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3028789c not in the list
08-17 19:16:38.561  7190  7267 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 19:16:38.561  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.561  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:38.561  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.561  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:38.561  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 19:16:38.561  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:38.561  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 19:16:38.561  7190  7267 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3028789c not in the list
,08-17 19:16:38.571  7190  7267 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-17 19:16:38.571  7190  7267 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 19:16:38.571  7190  7267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 19:16:38.571  7190  7267 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:38.571  7190  7267 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 19:16:38.571  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.571  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.571  7190  7267 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13e2700f not in the list
08-17 19:16:38.571  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.571  7190  7267 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3028789c not in the list
08-17 19:16:38.571  7190  7267 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:38.571  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.571  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.571  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.571  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:38.571  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-17 19:16:38.571  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:38.571  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.571  7190  7267 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3028789c not in the list
,08-17 19:16:38.571  7190  7267 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted,
08-17 19:16:38.571  7190  7267 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:38.571  7190  7267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:38.571  7190  7267 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:38.571  7190  7267 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 19:16:38.571  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.571  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.571  7190  7267 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13e2700f not in the list
08-17 19:16:38.571  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.571  7190  7267 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3028789c not in the list
08-17 19:16:38.571  7190  7267 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:38.571  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.571  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:38.571  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.571  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.571  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:38.571  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:38.571  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.571  7190  7267 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3028789c not in the list
,08-17 19:16:38.571  7190  7267 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-17 19:16:38.581  7190  7267 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 19:16:38.581  7190  7267 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-17 19:16:38.581  7190  7267 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 19:16:38.581  7190  7267 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-17 19:16:38.581  7190  7267 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 19:16:38.581  7190  7267 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:38.581  7190  7267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:38.581  7190  7267 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:38.581  7190  7267 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:38.581  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.581  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.581  7190  7267 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13e2700f not in the list
08-17 19:16:38.581  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.581  7190  7267 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3028789c not in the list
08-17 19:16:38.581  7190  7267 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:38.581  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.581  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.581  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.581  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:38.581  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:38.581  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 19:16:38.581  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.581  7190  7267 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3028789c not in the list
,08-17 19:16:38.581  7190  7267 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55,
08-17 19:16:38.581  7190  7267 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-17 19:16:38.581  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-17 19:16:38.581  7190  7267 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55,
08-17 19:16:38.581  7190  7267 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-17 19:16:38.581  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-17 19:16:38.581  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-17 19:16:38.581  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-17 19:16:38.581  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-17 19:16:38.581  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-17 19:16:38.581  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-17 19:16:38.581  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-17 19:16:38.581  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-17 19:16:38.581  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-17 19:16:38.581  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-17 19:16:38.581  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-17 19:16:38.581  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-17 19:16:38.581  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-17 19:16:38.581  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-17 19:16:38.581  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-17 19:16:38.581  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-17 19:16:38.581  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-17 19:16:38.581  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-17 19:16:38.581  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-17 19:16:38.581  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-17 19:16:38.581  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-17 19:16:38.581  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-17 19:16:38.581  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-17 19:16:38.581  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-17 19:16:38.581  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-17 19:16:38.581  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-17 19:16:38.581  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-17 19:16:38.581  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-17 19:16:38.581  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-17 19:16:38.581  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-17 19:16:38.581  7190  7267 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-17 19:16:38.581  7190  7267 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 19:16:38.581  7190  7267 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-17 19:16:38.581  7190  7267 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 19:16:38.581  7190  7267 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-17 19:16:38.581  7190  7267 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-17 19:16:38.581  7190  7267 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-17 19:16:38.581  7190  7267 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 19:16:38.581  7190  7267 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-17 19:16:38.591  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-17 19:16:38.591  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-17 19:16:38.591  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-17 19:16:38.591  7190  7267 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-17 19:16:38.591  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-17 19:16:38.591  7190  7267 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-17 19:16:38.591  7190  7267 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 19:16:38.591  7190  7267 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-17 19:16:38.591  7190  7267 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:38.591  7190  7267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:38.591  7190  7267 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:38.591  7190  7267 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:38.591  7190  7281 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1430)
08-17 19:16:38.591  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.591  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.591  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-17 19:16:38.591  7190  7267 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13e2700f not in the list
08-17 19:16:38.591  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.591  7190  7267 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3028789c not in the list
08-17 19:16:38.591  7190  7267 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:38.591  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.591  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.591  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.591  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.591  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:38.591  7190  ,7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:38.591  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.591  7190  7267 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3028789c not in the list
08-17 19:16:38.591  7190  7267 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-17 19:16:38.591  7190  7282 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1430
,08-17 19:16:38.591  7190  7267 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:38.591  7190  7267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:38.591  7190  7267 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:38.591  7190  7267 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:38.591  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.591  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.591  7190  7267 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13e2700f not in the list
08-17 19:16:38.591  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 19:16:38.591  7190  7267 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3028789c not in the list
08-17 19:16:38.591  7190  7267 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:38.591  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.591  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.591  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.591  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:38.591  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:38.591  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:38.591  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.591  7190  7267 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3028789c not in the list
,08-17 19:16:38.591  7190  7267 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-17 19:16:38.591  7190  7267 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:38.591  7190  7267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:38.591  7190  7267 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 19:16:38.591  7190  7267 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:38.591  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.591  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.591  7190  7267 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13e2700f not in the list
,08-17 19:16:38.591  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.591  7190  7267 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3028789c not in the list
08-17 19:16:38.591  7190  7267 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:38.591  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.591  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.591  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.591  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:38.601  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 19:16:38.601  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:38.601  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.601  7190  7267 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3028789c not in the list
08-17 19:16:38.601  7190  7267 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-17 19:16:38.601  7190  7267 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-17 19:16:38.601  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 19:16:38.601  7190  7267 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-17 19:16:38.601  7190  7267 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-17 19:16:38.601  7190  7267 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-17 19:16:38.601  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 19:16:38.601  7190  7267 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-17 19:16:38.601  7190  7267 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-17 19:16:38.601  7190  7281 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
08-17 19:16:38.601  7190  7267 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-17 19:16:38.601  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 19:16:38.601  7190  7267 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-17 19:16:38.601  7190  7267 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:38.601  7190  7267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:38.601  7190  7267 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:38.601  7190  7267 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:38.601  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.601  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.601  7190  7267 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13e2700f not in the list
08-17 19:16:38.601  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.601  7190  7267 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3028789c not in the list
08-17 19:16:38.601  7190  7267 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:38.601  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given lis,tener does not exist in the list - probably already removed
08-17 19:16:38.601  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.601  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.601  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.601  7190  7281 D BluetoothSocket: connect(): myUserId = 0
08-17 19:16:38.601  7190  7281 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 19:16:38.601  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:38.601  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:38.601  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.601  7190  7267 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3028789c not in the list
,08-17 19:16:38.601  7190  7267 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:38.601  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.601  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.601  7190  7267 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13e2700f not in the list
08-17 19:16:38.601  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.601  7190  7267 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3028789c not in the list
08-17 19:16:38.601  7190  7267 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:38.601  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.601  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.601  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.601  7190  7267 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3028789c not in the list
08-17 19:16:38.601  7190  7267 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:38.601  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.601  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.601  7190  7267 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13e2700f not in the list
,08-17 19:16:38.601  7190  7267 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:38.601  7190  7267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:38.601  7190  7267 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:38.601  7190  7267 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 19:16:38.601  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.601  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.601  7190  7267 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13e2700f not in the list
08-17 19:16:38.601  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.601  7190  7267 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3028789c not in the list
,08-17 19:16:38.601  7190  7267 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:38.601  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.601  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.601  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.601  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.601  3213  3223 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 19:16:38.601  7190  7281 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
08-17 19:16:38.601  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:38.601  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 19:16:38.601  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.601  7190  7267 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3028789c not in the list
,08-17 19:16:38.611  7190  7267 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-17 19:16:38.611  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:16:38.611  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-17 19:16:38.611  7190  7267 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-17 19:16:38.611  7190  7267 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-17 19:16:38.611  7190  7267 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-17 19:16:38.611  7190  7267 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 19:16:38.611  7190  7190 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-17 19:16:38.611  7190  7267 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:38.611  7190  7267 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-17 19:16:38.611  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-17 19:16:38.611  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-17 19:16:38.611  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.611  7190  7267 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-17 19:16:38.611  7190  7267 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13e2700f not in the list
08-17 19:16:38.611  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.611  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 19:16:38.611  7190  7267 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 19:16:38.611  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 19:16:38.611  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.611  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.611  7190  7190 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-17 19:16:38.611  7190  7267 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 19:16:38.611  7190  7267 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3028789c not in the list
08-17 19:16:38.611  7190  7267 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:38.611  7190  7267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:38.611  7190  7267 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:38.611  7190  7267 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:38.611  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.611  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.611  7190  7267 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13e2700f not in the list
08-17 19:16:38.611  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.611  7190  7267 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3028789c not in the list
08-17 19:16:38.611  7190  7267 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:38.611  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.611  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.611  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.611  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:38.611  7190  7283 D BluetoothSocket: bindListen(): myUserId = 0
08-17 19:16:38.611  7190  7283 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 19:16:38.611  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:38.611  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:38.611  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.611  7190  7267 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3028789c not in the list
08-17 19:16:38.611  7190  7190 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:16:38.611  7190  7190 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:16:38.611  7190  7190 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 19:16:38.611  7190  7267 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-17 19:16:38.611  7190  7267 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-17 19:16:38.611  7190  7267 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 19:16:38.611  7190  7267 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 19:16:38.611  7190  7267 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:38.611  7190  7267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:38.611  7190  7267 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:38.611  7190  7267 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 19:16:38.611  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.611  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.611  7190  7267 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13e2700f not in the list
08-17 19:16:38.611  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.611  7190  7267 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3028789c not in the list
08-17 19:16:38.611  7190  7267 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:38.611  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.611  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.611  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:16:38.611  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:38.621  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:38.621  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:38.621  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.621  7190  7267 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3028789c not in the list
,08-17 19:16:38.621  7190  7283 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[107]}
08-17 19:16:38.621  7190  7283 D BluetoothSocket: bindListen(), new LocalSocket 
08-17 19:16:38.621  7190  7283 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-17 19:16:38.621  7190  7283 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3210421e
08-17 19:16:38.621  7190  7283 D BluetoothSocket: channel: 6
08-17 19:16:38.621  7190  7283 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@6457aff, channel: 6, state: LISTENING
08-17 19:16:38.621  7190  7283 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@6457aff, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3210421e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@374940ccmSocket: android.net.LocalSocket@5b6ef15 impl:android.net.LocalSocketImpl@2afa622a fd:FileDescriptor[107]
08-17 19:16:38.621  7190  7283 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@5b6ef15 impl:android.net.LocalSocketImpl@2afa622a fd:FileDescriptor[107]
08-17 19:16:38.621  7190  7283 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-17 19:16:38.621  7190  7283 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-17 19:16:38.621  7190  7283 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-17 19:16:38.621  7190  7190 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-17 19:16:38.621  7190  7267 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:38.621  7190  7267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:38.621  7190  7267 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 19:16:38.621  7190  7267 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:38.621  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.621  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.621  7190  7267 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13e2700f not in the list
08-17 19:16:38.621  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.621  7190  7267 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3028789c not in the list
08-17 19:16:38.621  7190  7267 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:38.621  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.621  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.621  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.621  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:38.621  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:38.621  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:38.621  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.621  7190  7267 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3028789c not in the list
08-17 19:16:38.621  7190  7267 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:38.621  7190  7267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:38.621  7190  7267 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:38.621  7190  7267 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:38.621  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:16:38.621  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.621  7190  7267 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13e2700f not in the list
08-17 19:16:38.621  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.621  7190  7267 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3028789c not in the list
08-17 19:16:38.621  7190  7267 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:38.621  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.621  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.621  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:38.621  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:38.621  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:38.621  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:38.621  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:38.621  7190  7267 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3028789c not in the list
,08-17 19:16:38.631  7190  7267 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-17 19:16:38.631  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 19:16:38.631  7190  7267 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-17 19:16:38.631  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 19:16:38.631  7190  7267 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-17 19:16:38.631  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-17 19:16:38.631  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-17 19:16:38.631  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-17 19:16:38.631  7190  7267 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-17 19:16:38.631  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-17 19:16:38.631  7190  7267 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-17 19:16:38.631  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-17 19:16:38.631  7190  7267 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-17 19:16:38.631  7190  7267 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-17 19:16:38.631  7190  7267 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-17 19:16:38.631  7190  7267 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-17 19:16:38.631  7190  7267 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-17 19:16:38.631  7190  7267 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-17 19:16:38.631  7190  7267 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-17 19:16:38.631  7190  7267 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-17 19:16:38.631  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:16:38.631  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2d00c81b added. We now have 2 listener(s),
08-17 19:16:38.631  7190  7267 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:16:38.631  7190  7267 D BluetoothAdapter: enable()
08-17 19:16:38.631  7190  7267 D BluetoothAdapter: enable(): BT is already enabled..!
,08-17 19:16:38.631  1020  3827 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-17 19:16:38.631  1020  3827 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-17 19:16:38.631  1020  3827 D SecContentProvider2: mCursor = null
,08-17 19:16:38.641  1020  3827 D WifiService: setWifiEnabled: true pid=7190, uid=10170
08-17 19:16:38.641  1020  3827 W ActivityManager: Permission Denial: getCurrentUser() from pid=7190, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-17 19:16:38.641  1020  3827 W WifiService: Failed getting userId using ActivityManagerNative
08-17 19:16:38.641  1020  3827 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7190, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-17 19:16:38.641  1020  3827 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-17 19:16:38.641  1020  3827 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-17 19:16:38.641  1020  3827 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-17 19:16:38.641  1020  3827 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-17 19:16:38.641  1020  3827 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-17 19:16:38.641  1020  3827 D SettingsProvider: name = wifi_on
,08-17 19:16:38.641  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:16:38.641  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@62f9db8 added. We now have 3 listener(s)
08-17 19:16:38.641  7190  7267 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 19:16:38.641  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:16:38.641  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@18a46791 added. We now have 4 listener(s)
08-17 19:16:38.641  7190  7267 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 19:16:38.651  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:16:38.651  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b476f6 added. We now have 5 listener(s)
08-17 19:16:38.651  7190  7267 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 19:16:38.651  1020  1032 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-17 19:16:38.651  1020  1032 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-17 19:16:38.651  1020  1032 D SecContentProvider2: mCursor = null
,08-17 19:16:38.651  1020  1032 D WifiService: setWifiEnabled: false pid=7190, uid=10170
,08-17 19:16:38.651  1020  1032 D SettingsProvider: name = wifi_on
,08-17 19:16:38.661  1020  1129 E WifiStateMachine: WifiStateMachine: Leaving Connected state,
08-17 19:16:38.661  7190  7267 D BluetoothAdapter: disable()
,08-17 19:16:38.661  1389  1389 I wpa_supplicant: reset timer : RESET_TIMER 0
08-17 19:16:38.661  1389  1389 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-17 19:16:38.661  1389  1389 I wpa_supplicant: P2P: Current p2p state = IDLE
08-17 19:16:38.661  1020  1033 D SettingsProvider: name = bluetooth_on
08-17 19:16:38.661  1389  1389 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-17 19:16:38.661  1020  1129 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,08-17 19:16:38.671  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:16:38.671  3213  3284 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
08-17 19:16:38.671  3213  3284 D BluetoothAdapterProperties: Setting state to 13
08-17 19:16:38.671  3213  3284 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-17 19:16:38.671  3213  3284 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-17 19:16:38.671  3213  3284 D BluetoothAdapterService: updateAdapterState state is 13
,08-17 19:16:38.671  1020  1747 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:38.671  1020  1747 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-17 19:16:38.681  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
,08-17 19:16:38.681  7190  7267 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:16:38.681  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:38.681  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:38.681  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:38.681  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:16:38.681  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:16:38.681  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:16:38.681  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 19:16:38.681  1020  1747 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:38.681  1020  1747 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 19:16:38.681  1020  1747 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 19:16:38.681  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:38.681  7190  7267 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 19:16:38.681  3213  3213 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
08-17 19:16:38.681  3213  3284 D BluetoothAdapterService: Autoconnection is available 
08-17 19:16:38.681  3213  3284 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-17 19:16:38.681  3213  3284 D BluetoothAdapterService: terminating service from this receiver
08-17 19:16:38.681  7190  7267 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 19:16:38.681  3213  3213 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@36f94255, channel: 19, state: LISTENING
08-17 19:16:38.681  3213  3213 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@36f94255, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@8221c9d, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3d15546amSocket: android.net.LocalSocket@35c96d5b impl:android.net.LocalSocketImpl@357779f8 fd:FileDescriptor[80]
08-17 19:16:38.681  3213  3213 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@35c96d5b impl:android.net.LocalSocketImpl@357779f8 fd:FileDescriptor[80]
,08-17 19:16:38.681  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:38.681  1020  1020 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-17 19:16:38.681  1020  1020 I InputMethodManagerService: [BT Setting State] State =13
,08-17 19:16:38.681  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:38.691  1389  1389 I wpa_supplicant: Scan aborted because the firmware maybe busy.,
08-17 19:16:38.691  1389  1389 I wpa_supplicant: Therefore we will repeat the scan command after 1 seconds.
08-17 19:16:38.691  1389  1389 I wpa_supplicant: wlan0: Setting scan request: 1 sec 0 usec
,08-17 19:16:38.691  1020  1129 E WifiNative-wlan0: do suspend true
,08-17 19:16:38.691  1180  1180 D BluetoothTile:  onBluetoothStateChange:
,08-17 19:16:38.691  1180  1772 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 19:16:38.701  1180  1180 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-17 19:16:38.701  1180  1180 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-17 19:16:38.701  1180  1180 D BluetoothTile:  getBluetoothState : 13
,08-17 19:16:38.701  1894  1894 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-17 19:16:38.701  1180  1772 D BluetoothTile:  handleUpdatestate:false name:null,
08-17 19:16:38.701  1180  1772 D STATUSBAR-QSTileView: onStateChanged: Bluetooth,
,08-17 19:16:38.711  4844  4844 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:38.711  1020  1033 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 19:16:38.721  1020  1747 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-17 19:16:38.721  1020  1139 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-17 19:16:38.721  1020  1139 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:38.721  1020  1139 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:38.721  1020  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:38.721  3213  3284 D BluetoothAdapterProperties: onBluetoothDisable()
,08-17 19:16:38.721  3213  3284 D BluetoothAdapterProperties: mDiscovering is false
,08-17 19:16:38.731  7190  7190 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:38.731  1180  1180 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-17 19:16:38.731  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:38.731  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:38.731  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:38.731  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:38.731  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:16:38.731  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:16:38.731  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:16:38.731  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 19:16:38.731  7190  7190 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 19:16:38.731  7190  7190 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 19:16:38.731  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:38.771   324   324 I ServiceManager: Waiting for service AtCmdFwd...
,08-17 19:16:38.841  1020  1128 D WifiP2pService: InactiveState{ what=143375 }
,08-17 19:16:38.841  1020  1128 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-17 19:16:38.841   278   988 D CommandListener: Clearing all IP addresses on wlan0
,08-17 19:16:38.851  1180  1180 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:16:38.851  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-17 19:16:38.851  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:38.851  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:38.851  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:38.851  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:38.851  1662  2550 V NativeCrypto: Read error: ssl=0xb7a0ef18: I/O error during system call, Connection timed out
,08-17 19:16:38.861  1020  1131 E ConnectivityService: updateNetworkInfo()
08-17 19:16:38.861  1020  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 19:16:38.861  1020  1131 E ConnectivityService: updateNetworkInfo()
08-17 19:16:38.861  1020  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,08-17 19:16:38.861  1020  1020 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-17 19:16:38.861  1020  1525 I art     : Explicit concurrent mark sweep GC freed 29117(1631KB) AllocSpace objects, 12(192KB) LOS objects, 33% free, 23MB/34MB, paused 2.661ms total 157.190ms
,08-17 19:16:38.861  1020  1266 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-17 19:16:38.861  3213  3284 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-17 19:16:38.861  1662  2550 V NativeCrypto: SSL shutdown failed: ssl=0xb7a0ef18: I/O error during system call, Broken pipe
,08-17 19:16:38.871  1020  1341 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,08-17 19:16:38.871  1020  1745 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-17 19:16:38.871  1020  1745 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-17 19:16:38.871  1020  1745 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-17 19:16:38.871  1020  1745 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-17 19:16:38.871  1020  1745 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,08-17 19:16:38.871  1020  1128 D WifiP2pService: InactiveState{ what=131204 }
,08-17 19:16:38.871  1020  1745 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-17 19:16:38.871  1020  1745 I qtaguid : Tagging socket 353 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1020, getuid(): 1000
08-17 19:16:38.881  1020  1129 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-17 19:16:38.881  1020  1128 D WifiP2pService: P2pEnabledState{ what=131204 }
,08-17 19:16:38.881  1020  1020 D WifiScanningService: SCAN_AVAILABLE : 1
08-17 19:16:38.881  1020  1154 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-17 19:16:38.881  1020  1128 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-17 19:16:38.881  1020  1020 D RttService: SCAN_AVAILABLE : 1
08-17 19:16:38.881  1020  1155 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-17 19:16:38.881  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-17 19:16:38.881  1020  1745 I qtaguid : Untagging socket 353
08-17 19:16:38.881  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:16:38.881  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 19:16:38.881  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:38.881  1020  1745 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 19:16:38.891  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:38.891  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:38.891  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:38.891  1020  1050 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 19:16:38.891  1020  1050 D WifiDisplayAdapter: onP2pDisconnected
,08-17 19:16:38.891  3213  3213 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@38d8aed1, channel: 5, state: LISTENING
,08-17 19:16:38.891  3213  3213 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@38d8aed1, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@19ac3512, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2c4d36mSocket: android.net.LocalSocket@278437 impl:android.net.LocalSocketImpl@14a63da4 fd:FileDescriptor[82]
08-17 19:16:38.891  3213  3213 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@278437 impl:android.net.LocalSocketImpl@14a63da4 fd:FileDescriptor[82]
08-17 19:16:38.891  3213  3213 I BtOppRfcommListener: stopping Accept Thread
08-17 19:16:38.891  3213  3213 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@268670d, channel: 12, state: LISTENING
08-17 19:16:38.891  3213  3213 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@268670d, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@321fd90c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@16e806c2mSocket: android.net.LocalSocket@2ee62cd3 impl:android.net.LocalSocketImpl@17db9010 fd:FileDescriptor[86]
,08-17 19:16:38.891  3213  3213 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2ee62cd3 impl:android.net.LocalSocketImpl@17db9010 fd:FileDescriptor[86]
08-17 19:16:38.891  3213  5337 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1,
08-17 19:16:38.891  3213  5337 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-17 19:16:38.901  7190  7190 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:38.901  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:38.901  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:38.901  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:38.901  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:38.901  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:16:38.901  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:38.901  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:38.901  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 19:16:38.901  3213  3287 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-17 19:16:38.901  3213  3287 D BluetoothAdapterProperties: Scan Mode:20
08-17 19:16:38.901  3213  3213 V BluetoothOppManager: cleanUp...
08-17 19:16:38.901  7190  7190 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:38.901  7190  7190 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:16:38.901  1020  1128 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-17 19:16:38.901  1020  1050 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-17 19:16:38.901  1020  1050 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-17 19:16:38.911  1020  1050 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-17 19:16:38.911  1020  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-17 19:16:38.911  1020  1050 D WifiDisplayController: disconnect
08-17 19:16:38.911   278   984 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-17 19:16:38.911  1020  1050 D WifiDisplayController: updateConnection
08-17 19:16:38.911   278   984 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-17 19:16:38.911  1020  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-17 19:16:38.911  3213  3284 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-17 19:16:38.911  1020  1050 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-17 19:16:38.911  1020  1020 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-17 19:16:38.911  3213  3284 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-17 19:16:38.911  3213  3284 E bt-btif : cmd socket is not created
08-17 19:16:38.911  3213  3288 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
08-17 19:16:38.911  7190  7281 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@211cdd64, channel: -1, state: INIT
08-17 19:16:38.911  7190  7281 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@211cdd64, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@416ebcd, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@27290c82mSocket: android.net.LocalSocket@1cd61f93 impl:android.net.LocalSocketImpl@37c6bd0 fd:FileDescriptor[106]
08-17 19:16:38.911  7190  7281 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1cd61f93 impl:android.net.LocalSocketImpl@37c6bd0 fd:FileDescriptor[106]
08-17 19:16:38.911  7190  7281 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1430)
08-17 19:16:38.911  3213  3284 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-17 19:16:38.911  7190  7190 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:38.911  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:38.911  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:38.911  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:38.911  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:38.911  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:16:38.911  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:38.911  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:38.911  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 19:16:38.911  1020  1745 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
08-17 19:16:38.911  1020  1745 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-17 19:16:38.911  1020  1131 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,08-17 19:16:38.911  1020  1131 V NetworkStats: updateIfacesLocked()
08-17 19:16:38.911  1020  1131 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:38.911  1020  1131 V NetworkStats: performPollLocked(flags=0x1)
,08-17 19:16:38.911  1020  1131 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 19:16:38.911  1020  1131 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 19:16:38.911  7190  7190 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:38.911  7190  7190 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:16:38.921  1180  1180 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-17 19:16:38.921  4844  4844 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 19:16:38.921  1020  1509 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-17 19:16:38.921  1020  1509 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-17 19:16:38.921  1020  1509 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:38.921  1020  1128 D WifiP2pService: P2pDisablingState
08-17 19:16:38.921  1020  1509 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:38.921  1020  1128 D WifiP2pService: P2pDisablingState{ what=147458 }
08-17 19:16:38.921  1020  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
08-17 19:16:38.921  1020  1128 D WifiP2pService: p2p socket connection lost
08-17 19:16:38.921  3213  3288 W bt-sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
08-17 19:16:38.921  1020  1128 D WifiP2pService: P2pDisabledState
08-17 19:16:38.921  3213  3288 E bt-btif : DISCOVERY_COMP_EVT slot id:4, failed to find channle,                                       status:1, scn:0
08-17 19:16:38.921  3213  3288 W bt-btif : invalid rfc slot id: 4
08-17 19:16:38.921  1020  1129 E WifiNative-wlan0: do suspend true
,08-17 19:16:38.921  4844  4844 D BluetoothPbap: Proxy object disconnected
08-17 19:16:38.921  4844  4844 D PbapServerProfile: Bluetooth service disconnected
,08-17 19:16:38.921  1020  1050 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,08-17 19:16:38.921  1020  1050 D WifiDisplayAdapter: onP2pDisconnected
08-17 19:16:38.921  1020  1050 D IpRemoteDisplayController: disconnectWfdBridgeServer
,08-17 19:16:38.931  1020  1050 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-17 19:16:38.931  1020  1131 V NetworkStats: performPollLocked() took 15ms
08-17 19:16:38.931  1020  1131 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:38.931  1662  1662 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 19:16:38.931  1020  1341 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-17 19:16:38.931  1180  1180 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-17 19:16:38.931  1020  1131 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
08-17 19:16:38.931  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:38.931  1020  1131 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 19:16:38.931  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:38.931  1020  1128 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-17 19:16:38.931  1020  1131 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-17 19:16:38.931  1180  1743 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-17 19:16:38.931  1020  1131 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-17 19:16:38.931  1020  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-17 19:16:38.931  1477  1477 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-17 19:16:38.931  1477  1477 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-17 19:16:38.931  1020  1745 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,08-17 19:16:38.931  1020  1049 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-17 19:16:38.941  1020  1131 D ConnectivityService: nai.networkMonitor.doQuit()
08-17 19:16:38.941  1020  1131 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-17 19:16:38.941  1020  1131 E ConnectivityService: updateNetworkInfo()
08-17 19:16:38.941  1020  1131 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 19:16:38.941  1020  1131 E ConnectivityService: updateNetworkInfo()
08-17 19:16:38.941  4844  4844 D DockEventReceiver: finishStartingService: stopping service
,08-17 19:16:38.941  1020  1020 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-17 19:16:38.941  1020  1134 D Tethering: MasterInitialState.processMessage what=3
,08-17 19:16:38.941  3213  3288 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 19:16:38.941  3213  3288 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 19:16:38.941  3213  3288 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 19:16:38.941  3213  3288 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 19:16:38.941  3213  3288 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 19:16:38.941  3213  3288 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-17 19:16:38.941  4844  4844 D BluetoothNotiBroadcastReceiver: onReceive
08-17 19:16:38.941  1020  1126 V NetworkStats: updateIfacesLocked()
08-17 19:16:38.951  1020  1126 V NetworkStats: performPollLocked(flags=0x1)
08-17 19:16:38.951  1020  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:38.951  1180  1180 D StatusBar.NetworkController: EthernetConnected: false
,08-17 19:16:38.951  1180  1180 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-17 19:16:38.951  1180  1180 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-17 19:16:38.951  1180  1180 D StatusBar.NetworkController: updateDataNetType()
08-17 19:16:38.951  1020  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 19:16:38.951  1020  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 19:16:38.951  1020  1049 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-17 19:16:38.951  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:38.951  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:38.951  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:38.951  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:38.951  1020  1127 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,08-17 19:16:38.951  1020  1126 V NetworkStats: performPollLocked() took 4ms
08-17 19:16:38.951  1020  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:38.951  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-17 19:16:38.951  1180  1180 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-17 19:16:38.951  1180  1180 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-17 19:16:38.961  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 19 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
08-17 19:16:38.961  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
08-17 19:16:38.961  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,08-17 19:16:38.961  1020  1128 D WifiP2pService: P2pDisabledState{ what=143375 }
08-17 19:16:38.961  1020  1128 D WifiP2pService: DefaultState{ what=143375 }
,08-17 19:16:38.961   278   988 D CommandListener: Clearing all IP addresses on wlan0
,08-17 19:16:38.961  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-17 19:16:38.961  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:16:38.961  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-17 19:16:38.961  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:38.961  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:38.961  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:38.961  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:38.971  1180  1180 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-17 19:16:38.971  1180  1180 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
08-17 19:16:38.971  1389  1389 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
08-17 19:16:38.971  1020  1020 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-17 19:16:38.971  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:38.971  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:38.971  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-17 19:16:38.971  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:16:38.971  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-17 19:16:38.971  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:38.971  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:38.971  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:38.971  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:38.981  1020  1509 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-17 19:16:38.981  1020  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:38.981  1020  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:38.981  1020  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:38.981  1020  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:38.981  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-17 19:16:38.981  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:16:38.981  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 19:16:38.981  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:38.981  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:38.981  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:38.981  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:38.991  7294  7294 E Zygote  : MountEmulatedStorage()
08-17 19:16:38.991  7294  7294 I libpersona: KNOX_SDCARD checking this for 10055
,08-17 19:16:38.991  7294  7294 E Zygote  : v2
08-17 19:16:38.991  7294  7294 I libpersona: KNOX_SDCARD not a persona
08-17 19:16:38.991  7294  7294 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 19:16:38.991  1020  1509 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7294 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
08-17 19:16:39.001  7294  7294 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:16:39.001  1020  1129 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false,
,08-17 19:16:39.001  7294  7294 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:16:39.001  1020  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 19:16:39.001  1020  1129 D SecContentProvider2: mCursor = null
,08-17 19:16:39.001  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-17 19:16:39.001  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 19:16:39.001  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-17 19:16:39.001  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:39.001  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:39.011  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:39.011  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:39.011  1180  1180 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 19:16:39.011  1180  1180 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-17 19:16:39.011  1180  1180 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-17 19:16:39.011  1180  1772 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-17 19:16:39.011  1180  1180 D HotspotTile: onReceive : 0, 0
,08-17 19:16:39.011  4844  4844 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-17 19:16:39.011  7190  7190 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:39.011  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:39.011  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:39.011  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:39.011  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:16:39.011  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:16:39.011  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:39.011  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:39.011  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:16:39.011  7190  7190 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:39.011  7190  7190 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:16:39.021  7190  7190 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:39.021  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:39.021  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:39.021  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:39.021  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:16:39.021  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:16:39.021  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:39.021  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:39.021  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:16:39.021  7190  7190 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:39.021  7190  7190 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:16:39.031  7294  7294 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:39.041  7294  7294 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:39.061  1389  1389 I wpa_supplicant: Blacklist: Clear (all) 
,08-17 19:16:39.061  1477  1477 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 19:16:39.061  1477  1477 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 19:16:39.071  1477  1477 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 19:16:39.071  1477  1477 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 19:16:39.071  1477  1477 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 19:16:39.071  1477  1477 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 19:16:39.071  1477  1477 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 19:16:39.071  1477  1477 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 19:16:39.071  1477  1477 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 19:16:39.071  1477  1477 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 19:16:39.071  1477  1477 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 19:16:39.081  1477  1477 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 19:16:39.081  1477  1477 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 19:16:39.081  1477  1477 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 19:16:39.081  1477  1477 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 19:16:39.081  1477  1477 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 19:16:39.081  1477  1477 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 19:16:39.081  1477  1477 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 19:16:39.081  1477  1477 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 19:16:39.091  1477  1477 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 19:16:39.091  1477  1477 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 19:16:39.091  1477  1477 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-17 19:16:39.091  7294  7294 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-17 19:16:39.091  1477  1477 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 19:16:39.091  1477  1477 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 19:16:39.091  1477  1477 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 19:16:39.091  1477  1477 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 19:16:39.091  1477  1477 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 19:16:39.101  1477  1477 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 19:16:39.101  1477  1477 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 19:16:39.101  1477  1477 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 19:16:39.111  3213  3284 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true,
08-17 19:16:39.111  1020  1340 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:39.111  3213  3284 D BtConfig.SecureMode: isSecureModeOn:false
08-17 19:16:39.111  1020  1340 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-17 19:16:39.111  3213  3284 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
,08-17 19:16:39.111  3213  3284 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
08-17 19:16:39.111  3213  3284 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
08-17 19:16:39.111  1020  1747 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:39.111  3213  3284 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-17 19:16:39.111  1020  1747 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-17 19:16:39.111  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-17 19:16:39.111  3213  3284 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-17 19:16:39.111  1020  1340 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:39.111  1020  1340 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:39.111  1020  1340 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
,08-17 19:16:39.111  3213  3284 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-17 19:16:39.111  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-17 19:16:39.111  3213  3284 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-17 19:16:39.111  3213  3213 D HeadsetService: Received stop request...Stopping profile...,
08-17 19:16:39.111  7190  7190 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-17 19:16:39.121  3213  3213 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e7895
08-17 19:16:39.121  1020  1747 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:39.121  1020  1747 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:39.121  1020  1747 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 19:16:39.121  3213  3284 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-17 19:16:39.121  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService,
08-17 19:16:39.121  3213  3284 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-17 19:16:39.121  1020  1033 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:39.121  7294  7294 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
08-17 19:16:39.121  1020  1033 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-17 19:16:39.121  1020  1020 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-17 19:16:39.121  7294  7294 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-17 19:16:39.121  7294  7294 D UserAnalysis: Create SecureDbHelper
08-17 19:16:39.121  4844  4844 D HeadsetProfile: Bluetooth service disconnected
,08-17 19:16:39.121  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:39.121  1020  1033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:39.121  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 19:16:39.121  3213  3284 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-17 19:16:39.121  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-17 19:16:39.131  1389  1389 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-17 19:16:39.131  3213  3284 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-17 19:16:39.131  1020  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-17 19:16:39.131  1020  1047 D Tethering: interfaceLinkStateChanged p2p0, false
08-17 19:16:39.131  1020  1032 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:39.131  1020  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-17 19:16:39.131  1020  1047 D Tethering: interfaceStatusChanged p2p0, false
,08-17 19:16:39.131  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:39.131  1020  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:39.131  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:39.131  3213  3284 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-17 19:16:39.131  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-17 19:16:39.131  3213  3284 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-17 19:16:39.131  1020  1506 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:16:39.131  7294  7294 D IntelligenceServiceApplication: onCreate()
,08-17 19:16:39.131  1020  1506 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-17 19:16:39.131  1020  1506 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:39.131  1020  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:39.131  1020  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:39.141  3213  3284 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-17 19:16:39.141  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-17 19:16:39.141  3213  3284 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-17 19:16:39.141  1020  3827 I ActivityManager: Killing 6829:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
,08-17 19:16:39.141  1020  1508 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:39.141  1020  1508 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-17 19:16:39.141  1020  1508 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:39.141  1020  1508 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:39.141  1020  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:39.141  3213  3284 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-17 19:16:39.141  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-17 19:16:39.141  3213  3284 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-17 19:16:39.141  1020  1341 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:39.141  7294  7294 D IntelligenceServiceApplication: no applications having user consent for prediction
08-17 19:16:39.141  1020  1341 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-17 19:16:39.141  1020  1341 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:39.141  1020  1341 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:39.141  1020  1341 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 19:16:39.151  3213  3284 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:16:39.151  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-17 19:16:39.151  3213  3284 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:16:39.151  3213  3284 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:16:39.151  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:16:39.151  1020  1033 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
08-17 19:16:39.151  3213  3284 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:16:39.151  3213  3284 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-17 19:16:39.151  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-17 19:16:39.151  3213  3284 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-17 19:16:39.151  3213  3284 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-17 19:16:39.151  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-17 19:16:39.151  3213  3284 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-17 19:16:39.151  7294  7294 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
08-17 19:16:39.151  3213  3284 D BluetoothAdapterState: Stopping profile services that were post enabled
08-17 19:16:39.151  3213  3213 E BluetoothAdapterService(5142677): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-17 19:16:39.151  3213  3213 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-17 19:16:39.151  3213  3213 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-17 19:16:39.151  3213  3213 D A2dpService: Received stop request...Stopping profile...
,08-17 19:16:39.151  3213  3368 D A2dpStateMachine: Exit Disconnected: -1
,08-17 19:16:39.151  1389  1389 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-17 19:16:39.151  3213  3213 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e7895
08-17 19:16:39.151  1389  1389 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-17 19:16:39.151  1020  1020 D BluetoothA2dp: Proxy object disconnected
08-17 19:16:39.151  1389  1389 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-17 19:16:39.151  1389  1389 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-17 19:16:39.151  1389  1389 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-17 19:16:39.151  1020  1020 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-17 19:16:39.151  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:16:39.151  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:16:39.151  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
,08-17 19:16:39.151  1020  1134 D Tethering: InitialState.processMessage what=4
,08-17 19:16:39.151  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:16:39.151  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:16:39.151  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
,08-17 19:16:39.161  4844  4844 D BluetoothA2dp: Proxy object disconnected
08-17 19:16:39.161  4844  4844 D A2dpProfile: Bluetooth service disconnected
,08-17 19:16:39.161  3213  3213 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-17 19:16:39.161  3213  3213 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-17 19:16:39.161  3213  3213 D HidService: Received stop request...Stopping profile...
08-17 19:16:39.161  3213  3213 D HidService: Stopping Bluetooth HidService
08-17 19:16:39.161  3213  3213 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-17 19:16:39.161  3213  3213 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-17 19:16:39.161  3213  3213 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-17 19:16:39.161  3213  3213 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e7895
08-17 19:16:39.161  7294  7294 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-17 19:16:39.161  1020  1134 E Tethering: No numeric data
08-17 19:16:39.161  3213  3213 D HealthService: Received stop request...Stopping profile...
08-17 19:16:39.161  1020  1134 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-17 19:16:39.161  1020  1134 D Tethering: clearTetheredNotification()
,08-17 19:16:39.161  4844  4844 D BluetoothInputDevice: Proxy object disconnected
08-17 19:16:39.161  4844  4844 D HidProfile: Bluetooth service disconnected
,08-17 19:16:39.161  1020  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:39.161  1020  1126 V NetworkStats: performPollLocked(flags=0x1)
,08-17 19:16:39.161  1020  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 19:16:39.161  1020  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 19:16:39.161  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:16:39.161  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:16:39.161  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
08-17 19:16:39.171  3213  3213 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e7895
,08-17 19:16:39.171  1180  1180 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-17 19:16:39.171  1180  1180 D HotspotTile: updateTetherState():false, false
08-17 19:16:39.171  1020  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:39.171  1020  1126 V NetworkStats: performPollLocked() took 4ms
,08-17 19:16:39.171  3213  3213 D PanService: Received stop request...Stopping profile...
08-17 19:16:39.171  3213  3213 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e7895
,08-17 19:16:39.171  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:39.171  1020  1020 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-17 19:16:39.171  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:39.171  4844  4844 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-17 19:16:39.171  4844  4844 D PanProfile: Bluetooth service disconnected
,08-17 19:16:39.171  3213  3213 D BluetoothMapService: Received stop request...Stopping profile...
,08-17 19:16:39.171  1020  1508 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-17 19:16:39.171  1020  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:39.171  1020  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:39.171  1020  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:39.171  1020  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:39.191  7326  7326 E Zygote  : MountEmulatedStorage(),
08-17 19:16:39.191  7326  7326 I libpersona: KNOX_SDCARD checking this for 10105
08-17 19:16:39.191  7326  7326 E Zygote  : v2
,08-17 19:16:39.191  7326  7326 I libpersona: KNOX_SDCARD not a persona
08-17 19:16:39.191  7326  7326 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:16:39.191  7326  7326 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:16:39.191  7326  7326 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-17 19:16:39.191  1020  1508 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7326 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-17 19:16:39.191  3213  3213 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e7895
,08-17 19:16:39.201  3213  3213 D SapService: Received stop request...Stopping profile...
08-17 19:16:39.201  3213  3213 D SapService: Stopping Bluetooth SapService
08-17 19:16:39.201  3213  3213 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e7895
,08-17 19:16:39.201  3213  3213 E BluetoothAdapterService(5142677): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-17 19:16:39.201  3213  3213 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-17 19:16:39.201  3213  3213 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-17 19:16:39.201  3213  3213 D BluetoothA2dp: Proxy object disconnected
08-17 19:16:39.201  3213  3213 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-17 19:16:39.201  4844  4844 D BluetoothMap: Proxy object disconnected
08-17 19:16:39.201  4844  4844 D MapProfile: Bluetooth service disconnected
08-17 19:16:39.201  3213  3369 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-17 19:16:39.201  3213  3213 I GKI_LINUX: GKI_exit_task 2 done
08-17 19:16:39.201  3213  3213 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-17 19:16:39.201  4844  4844 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-17 19:16:39.201  4844  4844 D SapProfile: Bluetooth service disconnected
08-17 19:16:39.201  3213  3213 E BluetoothAdapterService(5142677): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
,08-17 19:16:39.201  3213  3213 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-17 19:16:39.201  3213  3213 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 19:16:39.201  3213  3213 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-17 19:16:39.201  3213  3213 E BluetoothAdapterService(5142677): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-17 19:16:39.201  3213  3213 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-17 19:16:39.201  3213  3213 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 19:16:39.201  3213  3213 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-17 19:16:39.201  3213  3213 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-17 19:16:39.201  3213  3213 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-17 19:16:39.201  3213  3213 E BluetoothAdapterService(5142677): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-17 19:16:39.201  3213  3213 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-17 19:16:39.201  3213  3213 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 19:16:39.201  3213  3213 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-17 19:16:39.201  3213  3213 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-17 19:16:39.201  3213  3213 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-17 19:16:39.201  3213  3213 E BluetoothAdapterService(5142677): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-17 19:16:39.201  3213  3213 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-17 19:16:39.201  3213  3213 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-17 19:16:39.201  3213  3213 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-17 19:16:39.201  3213  3213 E BluetoothAdapterService(5142677): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-17 19:16:39.201  3213  3213 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-17 19:16:39.201  3213  3213 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-17 19:16:39.201  3213  3213 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-17 19:16:39.201  3213  3284 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-17 19:16:39.201  3213  3284 D BluetoothAdapterProperties: Setting state to 10
08-17 19:16:39.201  3213  3284 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-17 19:16:39.201  3213  3284 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-17 19:16:39.201  3213  3284 D BluetoothAdapterService: updateAdapterState state is 10
08-17 19:16:39.201  3213  3284 D BluetoothAdapterService: Autoconnection is available 
08-17 19:16:39.201  3213  3284 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-17 19:16:39.211  3213  3284 I BluetoothAdapterState: Entering OffState
08-17 19:16:39.211  4844  4855 D Bluetoothsap: onBluetoothStateChange: up=false
08-17 19:16:39.211  4844  4855 D Bluetoothsap: Unbinding service...
,08-17 19:16:39.211  1020  1049 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 19:16:39.211  4844  4852 D BluetoothMap: onBluetoothStateChange: up=false
,08-17 19:16:39.211  1764  2306 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 19:16:39.211  1764  2306 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:16:39.211  4844  4855 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 19:16:39.211  4844  4855 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:16:39.211  3213  3223 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-17 19:16:39.211  1453  7324 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 19:16:39.211  1453  7324 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:16:39.211  1020  1049 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 19:16:39.211  1020  1049 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-17 19:16:39.211  1465  1483 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 19:16:39.211  1465  1483 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:16:39.211  4844  4855 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-17 19:16:39.221  7190  7200 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 19:16:39.221  7190  7200 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-17 19:16:39.221  7190  7200 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-17 19:16:39.221  7190  7200 D BluetoothLeAdvertiser: Exit stop advertising
08-17 19:16:39.221  7190  7200 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-17 19:16:39.221  7190  7200 D BluetoothLeScanner: Exiting stopAllScan
,08-17 19:16:39.221  1662  1672 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 19:16:39.221  1662  1672 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-17 19:16:39.221  1477  1491 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 19:16:39.221  1477  1491 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:16:39.221  1180  1201 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 19:16:39.221  1180  1201 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-17 19:16:39.221  4844  4855 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-17 19:16:39.221  4844  4852 D BluetoothPbap: onBluetoothStateChange: up=false
,08-17 19:16:39.221  3213  3375 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 19:16:39.221  3213  3375 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:16:39.221  7326  7326 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 19:16:39.221  7326  7326 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:39.221  1020  1020 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-17 19:16:39.221  1020  1020 I InputMethodManagerService: [BT Setting State] State =10
08-17 19:16:39.221  1020  1020 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-17 19:16:39.231  1180  1180 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-17 19:16:39.231  1180  1180 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:39.231  1180  1180 D BluetoothTile:  getBluetoothState : 10
,08-17 19:16:39.231  1894  1894 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-17 19:16:39.241  4844  4844 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:39.241  1020  3827 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 19:16:39.241  1020  1525 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-17 19:16:39.241  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:16:39.241  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:39.241  1180  1180 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 19:16:39.261  1180  1180 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-17 19:16:39.341  1389  1389 I wpa_supplicant: Blacklist: Clear (all) 
,08-17 19:16:39.361   257   523 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-17 19:16:39.361   257   523 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 19:16:39.361  7326  7344 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-17 19:16:39.361   257   523 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-17 19:16:39.371   257   523 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 19:16:39.371  7326  7344 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-17 19:16:39.421  1389  1389 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
,08-17 19:16:39.431  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false,
08-17 19:16:39.431  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:16:39.431  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
,08-17 19:16:39.441  1020  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,08-17 19:16:39.441  1020  1020 I ApplicationPolicy: updateDataUsageMap
,08-17 19:16:39.451  1020  1044 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-17 19:16:39.471  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:39.471  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:39.531  1020  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-17 19:16:39.531  1020  1129 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-17 19:16:39.531  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-17 19:16:39.541  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:16:39.541  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-17 19:16:39.541  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:39.541  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:39.541  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:39.541  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:39.541  1180  1180 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 19:16:39.541  1180  1180 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 19:16:39.541  1180  1180 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-17 19:16:39.541  1180  1772 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-17 19:16:39.541  1180  1180 D HotspotTile: onReceive : 1, 0
,08-17 19:16:39.541  4844  4844 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-17 19:16:39.541  1764  2200 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 19:16:39.541  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:39.551  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:39.561  7326  7326 D StrictMode: StrictMode policy violation; ~duration=177 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at java.io.File.exists(File.java:363)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:16:39.561  7326  7326 D StrictMode: StrictMode policy violation; ~duration=176 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:16:39.561  7326  7326 D StrictMode: StrictMode policy violation; ~duration=175 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:16:39.561  7326  7326 D StrictMode: StrictMode policy violation; ~duration=173 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.q.e.b(PG:170)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:16:39.561  7326  7326 D StrictMode: StrictMode policy violation; ~duration=169 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.q.k.d(PG:583)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.q.e.b(PG:170)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:16:39.561  7326  7326 D StrictMode: StrictMode policy violation; ~duration=145 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at java.io.File.exists(File.java:363)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:16:39.561  7326  7326 D StrictMode: StrictMode policy violation; ~duration=144 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at java.io.File.exists(File.java:363)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:16:39.561  7326  7326 D StrictMode: StrictMode policy violation; ~duration=143 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:16:39.561  7326  7326 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:16:39.561  1020  1525 I ActivityManager: Killing 6793:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
08-17 19:16:39.571  1020  1747 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 19:16:39.571  1020  1747 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-17 19:16:39.571  1020  1747 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:39.571  1020  1747 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:39.571  1020  1747 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-17 19:16:39.571  1640  1640 I Hs20UtilService: Starting #8
08-17 19:16:39.581  4844  4844 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-17 19:16:39.581  1640  1699 I Hs20UtilService: Message received 5007
08-17 19:16:39.581  4844  4844 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-17 19:16:39.581  4844  4844 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-17 19:16:39.581  4844  4844 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-17 19:16:39.581  4844  4844 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 19:16:39.581  4844  4844 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-17 19:16:39.581  4844  4897 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-17 19:16:39.591  4844  4844 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-17 19:16:39.591  4844  4844 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-17 19:16:39.591  4844  4844 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-17 19:16:39.591  4844  4844 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-17 19:16:39.591  4844  4844 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 19:16:39.591  4844  4844 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-17 19:16:39.591  4844  4897 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-17 19:16:39.601  1020  3827 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-17 19:16:39.601  1020  3827 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:39.601  1020  3827 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:39.601  1020  3827 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:39.601  1020  3827 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:39.611  7355  7355 E Zygote  : MountEmulatedStorage()
08-17 19:16:39.611  7355  7355 I libpersona: KNOX_SDCARD checking this for 10064
08-17 19:16:39.611  7355  7355 E Zygote  : v2
08-17 19:16:39.611  7355  7355 I libpersona: KNOX_SDCARD not a persona
08-17 19:16:39.611  7355  7355 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 19:16:39.611  1020  3827 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7355 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-17 19:16:39.621  7355  7355 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 19:16:39.621  7355  7355 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:16:39.641  7355  7355 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:39.651  7355  7355 D ActivityThread: Added TimaKeyStore provider
08-17 19:16:39.651  7326  7354 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-17 19:16:39.661  7355  7355 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-17 19:16:39.671  1020  1508 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:16:39.671  1020  1508 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:39.671  1020  1508 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:39.671  1020  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-17 19:16:39.681  7355  7355 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-17 19:16:39.681  7355  7355 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-17 19:16:39.711  7355  7355 D FileShare-Client: Outbound.stopDelayTimer - 
,08-17 19:16:39.721  1020  1509 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-17 19:16:39.721  1020  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:39.721  1020  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:39.721  1020  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:39.721  1020  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:39.731  7372  7372 E Zygote  : MountEmulatedStorage(),
,08-17 19:16:39.731  7372  7372 E Zygote  : v2
08-17 19:16:39.731  7372  7372 I libpersona: KNOX_SDCARD checking this for 10065
08-17 19:16:39.731  7372  7372 I libpersona: KNOX_SDCARD not a persona
,08-17 19:16:39.731  7372  7372 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:16:39.731  1020  1509 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7372 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-17 19:16:39.741  7372  7372 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 19:16:39.741  1020  1509 I ActivityManager: Killing 6220:com.samsung.android.sm/1000 (adj 15): empty #21
08-17 19:16:39.741  7372  7372 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:16:39.761  7372  7372 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:39.761  7372  7372 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:39.771   324   324 I ServiceManager: Waiting for service AtCmdFwd...
,08-17 19:16:39.781  7372  7372 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-17 19:16:39.781  1020  1340 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:39.781  1020  1340 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:39.781  1020  1340 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
08-17 19:16:39.781  1020  1340 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,08-17 19:16:39.791  1020  1340 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:39.791  1020  1340 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:39.791  1020  1340 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:39.791  1020  1340 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:39.801   291   291 E SMD     : DCD OFF
,08-17 19:16:39.811  7388  7388 E Zygote  : MountEmulatedStorage(),
,08-17 19:16:39.811  7388  7388 E Zygote  : v2
08-17 19:16:39.811  7388  7388 I libpersona: KNOX_SDCARD checking this for 10102
,08-17 19:16:39.811  7388  7388 I libpersona: KNOX_SDCARD not a persona
,08-17 19:16:39.811  7388  7388 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 19:16:39.811  1020  1340 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7388 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
08-17 19:16:39.811  1020  1340 I ActivityManager: Killing 6849:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
,08-17 19:16:39.821  7388  7388 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:16:39.821  7388  7388 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-17 19:16:39.841  7388  7388 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:39.841  7388  7388 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:39.851  7388  7388 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-17 19:16:40.081  7388  7408 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-17 19:16:40.081  7388  7408 I Babel_SMS: MmsConfig.loadMmsSettings
,08-17 19:16:40.081  7388  7408 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
08-17 19:16:40.081  7388  7408 I Babel_SMS: MmsConfig.loadFromDatabase
,08-17 19:16:40.101  7388  7408 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-17 19:16:40.101  7388  7408 I Babel_SMS: MmsConfig.loadFromResources
,08-17 19:16:40.101  7388  7408 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-17 19:16:40.101  7388  7408 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-17 19:16:40.131  1020  1139 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-17 19:16:40.131  1020  1139 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-17 19:16:40.131  1020  1139 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:40.131  1020  1139 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:40.131  1020  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-17 19:16:40.151  7388  7388 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 19:16:40.151  1020  1047 D Tethering: interfaceRemoved wlan0
08-17 19:16:40.151  1020  1047 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-17 19:16:40.151  7388  7388 I Babel_Crash: startup - clean
,08-17 19:16:40.181  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:40.181  1020  1033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:40.181  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:16:40.181  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:40.181  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:40.181  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:16:40.181  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:40.191  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:40.191  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:16:40.191  1020  1508 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-17 19:16:40.191  1020  1508 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 19:16:40.191  1020  1508 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:40.191  1020  1508 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:40.191  1020  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 19:16:40.201  1640  1640 I Hs20UtilService: Starting #9
,08-17 19:16:40.201  1640  1699 I Hs20UtilService: Message received 5007
,08-17 19:16:40.201  4844  4844 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-17 19:16:40.201  4844  4844 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-17 19:16:40.201  4844  4844 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-17 19:16:40.201  4844  4844 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-17 19:16:40.201  4844  4844 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 19:16:40.201  4844  4844 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-17 19:16:40.201  4844  4897 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 19:16:40.211  7388  7388 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-17 19:16:40.211  7388  7388 W AudioCapabilities: Unsupported mime audio/evrc
,08-17 19:16:40.211  7388  7388 W AudioCapabilities: Unsupported mime audio/qcelp,
08-17 19:16:40.211  7388  7388 W AudioCapabilities: Unsupported mime audio/mpeg-L1
08-17 19:16:40.221  1020  1506 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-17 19:16:40.221  1020  1506 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 19:16:40.221  1020  1506 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:40.221  1020  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:40.221  1020  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 19:16:40.221  1640  1640 I Hs20UtilService: Starting #10
08-17 19:16:40.221  1640  1699 I Hs20UtilService: Message received 5011
,08-17 19:16:40.221  1020  3827 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,08-17 19:16:40.221  1020  3827 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:40.221  1020  3827 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:40.221  1020  3827 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:40.221  1020  3827 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:40.231  7411  7411 E Zygote  : MountEmulatedStorage()
,08-17 19:16:40.231  7411  7411 E Zygote  : v2
08-17 19:16:40.231  7411  7411 I libpersona: KNOX_SDCARD checking this for 1000
,08-17 19:16:40.241  7411  7411 I libpersona: KNOX_SDCARD not a persona
,08-17 19:16:40.241  7411  7411 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:16:40.241  7388  7388 W AudioCapabilities: Unsupported mime audio/mpeg-L2
08-17 19:16:40.241  1020  3827 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=7411 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-17 19:16:40.241  7388  7388 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-17 19:16:40.241  7411  7411 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 19:16:40.241  7388  7388 W AudioCapabilities: Unsupported mime audio/x-ima
,08-17 19:16:40.241  7411  7411 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:16:40.241  7388  7388 W AudioCapabilities: Unsupported mime audio/qcelp
08-17 19:16:40.241  7388  7388 W AudioCapabilities: Unsupported mime audio/evrc
,08-17 19:16:40.271  7388  7388 W VideoCapabilities: Unsupported mime video/wvc1
,08-17 19:16:40.271  7388  7388 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-17 19:16:40.271  7411  7411 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 19:16:40.271  7411  7411 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:40.281  7388  7388 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-17 19:16:40.281  7388  7388 W VideoCapabilities: Unsupported mime video/wvc1
,08-17 19:16:40.281  7388  7388 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-17 19:16:40.291  7388  7388 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
08-17 19:16:40.291  1020  1047 D Tethering: interfaceRemoved p2p0
08-17 19:16:40.291  1020  1047 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-17 19:16:40.291  7388  7388 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-17 19:16:40.291  7388  7388 W VideoCapabilities: Unsupported mime video/mp43
,08-17 19:16:40.301  7388  7388 W VideoCapabilities: Unsupported mime video/sorenson
,08-17 19:16:40.301  7388  7388 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-17 19:16:40.311  7411  7411 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-17 19:16:40.311  7411  7411 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-17 19:16:40.311  7411  7411 D SecurityLogAgent: StateMachine : Current State = 1
,08-17 19:16:40.321  7411  7411 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 19:16:40.321  1020  1341 I ActivityManager: Killing 6880:com.google.android.apps.docs/u0a87 (adj 15): empty #21
,08-17 19:16:40.331  1020  1340 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:40.331  1020  1340 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:40.331  1020  1340 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:16:40.331  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:40.331  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:40.331  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:16:40.331  7388  7388 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-17 19:16:40.341  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:40.341  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:40.341  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:16:40.341  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:40.341  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:40.341  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:16:40.351  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:40.351  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 19:16:40.351  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:16:40.351  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:40.351  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:40.351  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:16:40.361  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:40.361  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:40.361  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:16:40.361  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:40.361  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:40.361  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:16:40.361  7388  7388 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-17 19:16:40.361  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:40.361  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:40.361  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:16:40.361  7388  7388 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-17 19:16:40.361  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:40.361  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:40.361  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:16:40.371  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:40.371  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:40.371  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:16:40.371  7388  7388 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc,
,08-17 19:16:40.371  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:40.371  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-17 19:16:40.371  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:16:40.371  7388  7388 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-17 19:16:40.371  4844  4844 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 19:16:40.371  1020  4295 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-17 19:16:40.371  1020  4295 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-17 19:16:40.381  1020  4295 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:40.381  1020  4295 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:40.381  1020  4295 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-17 19:16:40.381  1020  1266 I ActivityManager: Killing 6902:com.google.android.partnersetup/u0a14 (adj 15): empty #21
,08-17 19:16:40.391  7388  7388 I vclib   : onServiceConnected
,08-17 19:16:40.391  1662  1662 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 19:16:40.391  4844  4844 D DockEventReceiver: finishStartingService: stopping service
,08-17 19:16:40.391  4844  4844 D BluetoothNotiBroadcastReceiver: onReceive
,08-17 19:16:40.391  1180  1180 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:40.391  1180  1180 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-17 19:16:40.421  6969  6969 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-17 19:16:40.421  6969  6969 I PCWCLIENTTRACE_PushUtil: sales region : global
08-17 19:16:40.421  6969  6969 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-17 19:16:40.421  6969  6969 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-17 19:16:40.421  6969  7429 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,08-17 19:16:40.421  1020  1032 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
08-17 19:16:40.421  1020  1032 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
08-17 19:16:40.421  1020  1032 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
08-17 19:16:40.421  1020  1032 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,08-17 19:16:40.431  1020  1020 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-17 19:16:40.431  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:40.431  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:40.431  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:40.431  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:40.441  7431  7431 E Zygote  : MountEmulatedStorage(),
08-17 19:16:40.441  7431  7431 E Zygote  : v2
,08-17 19:16:40.441  7431  7431 I libpersona: KNOX_SDCARD checking this for 10001
,08-17 19:16:40.441  7431  7431 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 19:16:40.441  7431  7431 I libpersona: KNOX_SDCARD not a persona
08-17 19:16:40.441  1020  1020 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7431 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-17 19:16:40.451  7431  7431 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-17 19:16:40.451  7431  7431 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:16:40.461  7431  7431 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 19:16:40.461  7431  7431 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:40.471   310   310 I art     : Explicit concurrent mark sweep GC freed 8719(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 608us total 29.167ms
,08-17 19:16:40.491   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 563us total 16.659ms
,08-17 19:16:40.511   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 573us total 16.071ms
,08-17 19:16:40.531  1020  1032 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-17 19:16:40.531  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:40.531  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:40.531  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:40.531  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:40.551  7448  7448 E Zygote  : MountEmulatedStorage()
,08-17 19:16:40.551  7448  7448 E Zygote  : v2
08-17 19:16:40.551  7448  7448 I libpersona: KNOX_SDCARD checking this for 1000
08-17 19:16:40.551  7448  7448 I libpersona: KNOX_SDCARD not a persona
,08-17 19:16:40.551  7448  7448 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:16:40.551  1020  1032 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7448 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-17 19:16:40.551  1020  1032 I ActivityManager: Killing 6807:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,08-17 19:16:40.551  7448  7448 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:16:40.551  7448  7448 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:16:40.571  7448  7448 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 19:16:40.571  7448  7448 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:40.611  7448  7448 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-17 19:16:40.731  7448  7448 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-17 19:16:40.741  7448  7448 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-17 19:16:40.741  7448  7448 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-17 19:16:40.751  7448  7448 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-17 19:16:40.751  7448  7448 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-17 19:16:40.751  7448  7448 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-17 19:16:40.751  1020  1033 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-17 19:16:40.751  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:40.751  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:40.751  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:40.751  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:40.761  7463  7463 E Zygote  : MountEmulatedStorage(),
,08-17 19:16:40.761  1020  1033 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7463 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-17 19:16:40.771  7463  7463 E Zygote  : v2
,08-17 19:16:40.771  7463  7463 I libpersona: KNOX_SDCARD checking this for 10008
08-17 19:16:40.771  1020  1033 I ActivityManager: Killing 6986:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
08-17 19:16:40.771  7463  7463 I libpersona: KNOX_SDCARD not a persona
,08-17 19:16:40.771  7463  7463 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:16:40.771  7463  7463 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:16:40.771  7463  7463 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-17 19:16:40.781   324   324 I ServiceManager: Waiting for service AtCmdFwd...
,08-17 19:16:40.791  7463  7463 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:40.791  7463  7463 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:40.861  1020  1509 I ActivityManager: Killing 7024:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
,08-17 19:16:40.861  1020  1525 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,08-17 19:16:40.861  1020  1525 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-17 19:16:40.861  1020  1525 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:40.861  1020  1525 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:40.861  1020  1525 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-17 19:16:40.881  1882  1882 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-17 19:16:40.881  1882  2827 I iu.UploadsManager: num queued entries: 0
,08-17 19:16:40.881  1882  2827 I iu.UploadsManager: num updated entries: 0
,08-17 19:16:40.881  1882  2827 I iu.SyncManager: NEXT; no task
,08-17 19:16:40.891  1020  3827 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-17 19:16:40.891  1020  3827 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4252, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-17 19:16:40.891  1020  3827 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-17 19:16:40.891  1020  3827 D BatteryService: stay LED for charging
08-17 19:16:40.891  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-17 19:16:40.901  1020  1020 I MotionRecognitionService: Plugged
08-17 19:16:40.901  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,08-17 19:16:40.901  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-17 19:16:40.901  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-17 19:16:40.901  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-17 19:16:40.901  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-17 19:16:40.911  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-17 19:16:40.911  1020  1340 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-17 19:16:40.911  1020  1340 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,08-17 19:16:40.911  1020  1340 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:40.911  1020  1340 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:40.911  1020  1340 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:40.921  1882  1882 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-17 19:16:40.921  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-17 19:16:40.931  1882  1882 I Kids    : [GCoreUtils] Current gmscore version, 8115234 is smaller than the required version 8400000
,08-17 19:16:40.931  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-17 19:16:40.931  2831  2831 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Aug 17 19:16:40 GMT+02:00 2016
,08-17 19:16:40.931  1020  1266 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-17 19:16:40.931  1020  1266 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-17 19:16:40.941  1020  1266 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:40.941  1020  1266 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:40.941  1020  1266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-17 19:16:40.941  2831  2831 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-17 19:16:40.941  2831  2831 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-17 19:16:40.941  1020  1033 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-17 19:16:40.951  2831  2831 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-17 19:16:40.951  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:40.951  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:40.951  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:40.951  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:40.951  2831  2831 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-17 19:16:40.961  2831  7479 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
08-17 19:16:40.961  7480  7480 I libpersona: KNOX_SDCARD checking this for 10031
08-17 19:16:40.961  2831  7479 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
08-17 19:16:40.961  7480  7480 I libpersona: KNOX_SDCARD not a persona
08-17 19:16:40.961  7480  7480 E Zygote  : MountEmulatedStorage()
08-17 19:16:40.961  7480  7480 E Zygote  : v2
,08-17 19:16:40.961  7480  7480 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:16:40.971  1020  1033 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7480 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,08-17 19:16:40.971  7480  7480 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:16:40.971  7480  7480 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:16:40.971  2831  7479 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-17 19:16:40.971  2831  7479 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-17 19:16:40.981  2831  2831 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-17 19:16:40.981  7480  7480 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:40.991  7480  7480 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:41.021  7480  7480 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-17 19:16:41.031  1020  1340 I ActivityManager: Killing 7047:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
,08-17 19:16:41.041  1020  1747 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-17 19:16:41.041  1020  1747 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:41.041  1020  1747 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:41.041  1020  1747 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:41.041  1020  1747 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:41.041  2769  7495 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,08-17 19:16:41.051  1020  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-17 19:16:41.061  2769  7495 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
08-17 19:16:41.061  2769  7495 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable,
,08-17 19:16:41.061  7496  7496 E Zygote  : MountEmulatedStorage(),
08-17 19:16:41.061  2769  7495 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
08-17 19:16:41.061  7496  7496 E Zygote  : v2,
08-17 19:16:41.061  2769  7495 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
08-17 19:16:41.061  7496  7496 I libpersona: KNOX_SDCARD checking this for 10032,
08-17 19:16:41.061  7496  7496 I libpersona: KNOX_SDCARD not a persona
,08-17 19:16:41.061  7496  7496 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:16:41.071  7496  7496 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-17 19:16:41.071  1020  1747 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7496 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-17 19:16:41.071  7496  7496 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
,08-17 19:16:41.101  7496  7496 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:41.101  7496  7496 D ActivityThread: Added TimaKeyStore provider,
,08-17 19:16:41.151  7496  7511 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-17 19:16:41.151  7496  7511 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-17 19:16:41.151  7496  7496 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-17 19:16:41.161  7496  7511 D SPPClientService: PushLog.txt file is not deleted.
,08-17 19:16:41.161  1020  1139 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-17 19:16:41.161  7496  7511 D SPPClientService: PushLog.txt file is not deleted.
08-17 19:16:41.161  7496  7511 D SPPClientService: ============PushLog. stop!
,08-17 19:16:41.161  1020  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:41.161  1020  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:41.161  1020  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:41.161  1020  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:41.171  7513  7513 E Zygote  : MountEmulatedStorage()
,08-17 19:16:41.171  7513  7513 E Zygote  : v2
08-17 19:16:41.171  7513  7513 I libpersona: KNOX_SDCARD checking this for 10036
08-17 19:16:41.171  7513  7513 I libpersona: KNOX_SDCARD not a persona
,08-17 19:16:41.171  7513  7513 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:16:41.181  7513  7513 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-17 19:16:41.181  1020  1139 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7513 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-17 19:16:41.181  7513  7513 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-17 19:16:41.181  1020  1506 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
08-17 19:16:41.181  1020  1506 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:41.181  1020  1506 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
08-17 19:16:41.181  1020  1506 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-17 19:16:41.181  1020  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,08-17 19:16:41.201  7513  7513 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:41.201  7513  7513 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:41.221  7496  7521 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-17 19:16:41.241  1020  1032 I ActivityManager: Killing 7069:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,08-17 19:16:41.251  7513  7513 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@27fee652
,08-17 19:16:41.271  7513  7513 I SA      : [SSP] onCreated
,08-17 19:16:41.281  7513  7513 I SA      : [TPM] There is no property file
,08-17 19:16:41.281  7513  7513 I SA      : [SCU] isHaveSA() - false
,08-17 19:16:41.281  7513  7513 I SA      : [TPM] getModelProperty : null
,08-17 19:16:41.281  7513  7513 I SA      : [TPM] getCSCProperty : null
,08-17 19:16:41.291  7513  7513 I SA      : [DM] FLOATING AMOLED FEATURE: true
,08-17 19:16:41.291  7513  7513 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-17 19:16:41.291  7513  7513 I SA      : [DM] TFT FEATURE: false
,08-17 19:16:41.291  7513  7513 I SA      : [DM] init START
,08-17 19:16:41.291  7513  7513 I SA      : [DM] This device is not a Vodafone
,08-17 19:16:41.301  7513  7513 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,08-17 19:16:41.301  7513  7513 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,08-17 19:16:41.301  7513  7513 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,08-17 19:16:41.301  7513  7513 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
08-17 19:16:41.301  7513  7513 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
08-17 19:16:41.301  7513  7513 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,08-17 19:16:41.301  7513  7513 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-17 19:16:41.301  7513  7513 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-17 19:16:41.301  7513  7513 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75),
08-17 19:16:41.301  7513  7513 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,08-17 19:16:41.301  7513  7513 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,08-17 19:16:41.301  7513  7513 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,08-17 19:16:41.301  7513  7513 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,08-17 19:16:41.301  7513  7513 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
,08-17 19:16:41.301  7513  7513 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
08-17 19:16:41.301  7513  7513 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
08-17 19:16:41.301  7513  7513 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
,08-17 19:16:41.301  7513  7513 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,08-17 19:16:41.311  7513  7513 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
08-17 19:16:41.311  7513  7513 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,08-17 19:16:41.311  7513  7513 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,08-17 19:16:41.311  7513  7513 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
08-17 19:16:41.311  7513  7513 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,08-17 19:16:41.311  7513  7513 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
08-17 19:16:41.311  7513  7513 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,08-17 19:16:41.311  7513  7513 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
08-17 19:16:41.311  7513  7513 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
,08-17 19:16:41.311  7513  7513 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-17 19:16:41.311  7513  7513 I SA      : [SCU] isHaveSA() - false,
08-17 19:16:41.311  7513  7513 I SA      : support phone number id : false
08-17 19:16:41.311  7513  7513 I SA      : [DM] Supports Ref Jpn : true
,08-17 19:16:41.311  7513  7513 I SA      : [DM] init END
08-17 19:16:41.311  7513  7513 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-17 19:16:41.311  7513  7513 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ],
08-17 19:16:41.311  7513  7513 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-17 19:16:41.321  7513  7513 I SA      : [SLFUCHKMGR] constructor called
,08-17 19:16:41.331  7513  7513 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
08-17 19:16:41.331  7513  7513 I SA      : [OR] == isSIMCardReady false ==
,08-17 19:16:41.331  7513  7513 I SA      : [SCU] == networkStateCheck == false
08-17 19:16:41.331  7513  7513 I SA      : [OR] onReceive END
,08-17 19:16:41.331  1020  4295 I ActivityManager: Killing 6949:com.android.mms/u0a41 (adj 15): empty #21
,08-17 19:16:41.331  1234  1234 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-17 19:16:41.341  1793  1793 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-17 19:16:41.351  2551  2565 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,08-17 19:16:41.351  1793  1793 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,08-17 19:16:41.351  1793  1793 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
08-17 19:16:41.351  1793  1793 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,08-17 19:16:41.351  1793  1793 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-17 19:16:41.361  1793  1793 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-17 19:16:41.361  1793  1793 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-17 19:16:41.361  1020  1032 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-17 19:16:41.361  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:41.361  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:41.361  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:41.361  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:41.381  7536  7536 E Zygote  : MountEmulatedStorage(),
08-17 19:16:41.381  1020  1032 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7536 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-17 19:16:41.381  7536  7536 E Zygote  : v2
08-17 19:16:41.381  7536  7536 I libpersona: KNOX_SDCARD checking this for 10077
08-17 19:16:41.381  7536  7536 I libpersona: KNOX_SDCARD not a persona
,08-17 19:16:41.381  7536  7536 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-17 19:16:41.381  7536  7536 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:16:41.391  7536  7536 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL,
,08-17 19:16:41.401  7536  7536 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:41.401  7536  7536 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:41.461  1020  1340 D CountryDetector: No listener is left
,08-17 19:16:41.631  1020  1506 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,08-17 19:16:41.631  1020  1506 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-17 19:16:41.631  1020  1506 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:41.631  1020  1506 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:41.631  1020  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-17 19:16:41.641  1020  1494 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-17 19:16:41.641  1020  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:41.641  1020  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:41.641  1020  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:41.641  1020  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:41.651  7556  7556 E Zygote  : MountEmulatedStorage()
08-17 19:16:41.651  7556  7556 E Zygote  : v2
08-17 19:16:41.651  7556  7556 I libpersona: KNOX_SDCARD checking this for 10110
08-17 19:16:41.651  7556  7556 I libpersona: KNOX_SDCARD not a persona
,08-17 19:16:41.651  1020  1494 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7556 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-17 19:16:41.651  7556  7556 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:16:41.651  1020  1508 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,08-17 19:16:41.661  1020  1508 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-17 19:16:41.661  1020  1508 W ActivityManager: userId = 0, bbcId = -10000,
08-17 19:16:41.661  1020  1508 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:41.661  1020  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
08-17 19:16:41.661  7556  7556 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:16:41.661  7556  7556 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,08-17 19:16:41.661  7388  7555 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-17 19:16:41.671  1020  1139 I ActivityManager: Killing 7109:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
,08-17 19:16:41.681  7556  7556 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:41.681  7556  7556 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:41.691  1020  1341 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-17 19:16:41.691  1020  1341 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-17 19:16:41.691  1020  1341 D SecContentProvider2: mCursor = null
,08-17 19:16:41.691  1020  1341 D WifiService: setWifiEnabled: true pid=7190, uid=10170
,08-17 19:16:41.691  1020  1341 W ActivityManager: Permission Denial: getCurrentUser() from pid=7190, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-17 19:16:41.691  1020  1341 W WifiService: Failed getting userId using ActivityManagerNative
08-17 19:16:41.691  1020  1341 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7190, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-17 19:16:41.691  1020  1341 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-17 19:16:41.691  1020  1341 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-17 19:16:41.691  1020  1341 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-17 19:16:41.691  1020  1341 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-17 19:16:41.691  1020  1341 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-17 19:16:41.691  1020  1341 D SettingsProvider: name = wifi_on
,08-17 19:16:41.691  1020  1129 E WifiHW  : ##################### set firmware type 0 #####################
,08-17 19:16:41.781   324   324 I ServiceManager: Waiting for service AtCmdFwd...
,08-17 19:16:41.861  1020  3827 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-17 19:16:41.991  7556  7556 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-17 19:16:41.991  7556  7556 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-17 19:16:41.991  7556  7556 I GAv4    :   adb logcat -s GAv4
,08-17 19:16:42.001   257   523 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-17 19:16:42.001   257   523 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 19:16:42.001  7556  7581 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-17 19:16:42.011   257   523 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-17 19:16:42.011   257   523 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 19:16:42.011  7556  7581 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-17 19:16:42.011  7556  7556 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
08-17 19:16:42.011  1020  1509 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-17 19:16:42.021  7556  7556 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-17 19:16:42.021   257   523 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-17 19:16:42.021   257   523 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 19:16:42.031  7556  7583 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-17 19:16:42.031   257   523 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-17 19:16:42.031   257   523 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 19:16:42.031  7556  7583 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-17 19:16:42.031  7556  7584 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-17 19:16:42.091  1020  1047 D Tethering: interfaceAdded wlan0
,08-17 19:16:42.091  1020  1134 E Tethering: No numeric data
,08-17 19:16:42.091  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-17 19:16:42.091  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:16:42.091  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
08-17 19:16:42.091  1020  1134 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-17 19:16:42.091  1020  1134 D Tethering: clearTetheredNotification()
08-17 19:16:42.091  1020  1134 D Tethering: InitialState.processMessage what=4
,08-17 19:16:42.101  1020  1126 V NetworkStats: performPollLocked(flags=0x1)
08-17 19:16:42.101  1020  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:42.101  1180  1180 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-17 19:16:42.101  1180  1180 D HotspotTile: updateTetherState():false, false
,08-17 19:16:42.101  1020  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 19:16:42.101  1020  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-17 19:16:42.101  1020  1134 E Tethering: No numeric data
,08-17 19:16:42.101   278   988 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,08-17 19:16:42.101   278   988 D SoftapController: Softap fwReload - Ok
08-17 19:16:42.101  1020  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-17 19:16:42.101  1020  1134 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-17 19:16:42.101  1020  1126 V NetworkStats: performPollLocked() took 5ms
08-17 19:16:42.101  1020  1134 D Tethering: clearTetheredNotification()
08-17 19:16:42.101  1020  1047 D Tethering: interfaceLinkStateChanged p2p0, false
08-17 19:16:42.101  1020  1047 D Tethering: interfaceStatusChanged p2p0, false
08-17 19:16:42.101  1020  1126 D NtpTrustedTime: currentTimeMillis() cache hit,
08-17 19:16:42.101  1020  1047 D Tethering: interfaceAdded p2p0
08-17 19:16:42.101   278   988 D CommandListener: Setting iface cfg
08-17 19:16:42.101   278   988 D CommandListener: Trying to bring down wlan0
08-17 19:16:42.101  1020  1047 D Tethering: p2p0 is not a tetherable iface, ignoring,
08-17 19:16:42.111   278   988 D CommandListener: Clearing all IP addresses on wlan0
,08-17 19:16:42.111  1180  1180 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-17 19:16:42.111  1180  1180 D HotspotTile: updateTetherState():false, false
,08-17 19:16:42.111  1020  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:42.111  1020  1126 V NetworkStats: performPollLocked(flags=0x1)
,08-17 19:16:42.111  1020  1129 E WifiHW  : supplicant_name : p2p_supplicant
08-17 19:16:42.111  1020  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 19:16:42.111  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:42.111  1020  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-17 19:16:42.111  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:42.111  1020  1126 V NetworkStats: performPollLocked() took 4ms
08-17 19:16:42.111  1020  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:42.111  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:42.111  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:42.171  7587  7587 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-17 19:16:42.171  7587  7587 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-17 19:16:42.171  7587  7587 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-17 19:16:42.201  7587  7587 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-17 19:16:42.211   409   409 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7587,
08-17 19:16:42.211   409   409 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
08-17 19:16:42.211  7587  7587 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-17 19:16:42.211  7587  7587 I wpa_supplicant: ssSupport state is = 1
,08-17 19:16:42.211  7587  7587 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-17 19:16:42.211  7587  7587 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,08-17 19:16:42.211   409   409 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7587
08-17 19:16:42.211   409   409 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,08-17 19:16:42.211  1020  1129 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
,08-17 19:16:42.221  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-17 19:16:42.231  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:16:42.231  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-17 19:16:42.231  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:42.231  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:42.231  1180  1180 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 19:16:42.231  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:42.231  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:42.231  1180  1180 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 19:16:42.231  1180  1180 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-17 19:16:42.231  1180  1772 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-17 19:16:42.231  1180  1180 D HotspotTile: onReceive : 2, 0
08-17 19:16:42.231  4844  4844 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-17 19:16:42.231  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:42.231  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:42.291  1020  1494 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:16:42.301  1020  1494 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:42.301  1020  1494 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:42.301  1020  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-17 19:16:42.361  7556  7556 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-17 19:16:42.381  7556  7556 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 7534-7536)
,08-17 19:16:42.381  7556  7556 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-17 19:16:42.391  7556  7556 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {36f94255}
08-17 19:16:42.391  7556  7556 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-17 19:16:42.391  7556  7556 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-17 19:16:42.411   409   409 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0,
,08-17 19:16:42.411  7556  7556 I cr.BrowserStartup: Initializing chromium process, singleProcess=true,
,08-17 19:16:42.411  7587  7587 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed,
08-17 19:16:42.411  7556  7556 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,08-17 19:16:42.421  7556  7556 E SysUtils: ApplicationContext is null in ApplicationStatus,
,08-17 19:16:42.431  7556  7556 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-17 19:16:42.431  7556  7556 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-17 19:16:42.431  7556  7556 I Adreno-EGL: Build Date: 04/06/15 Mon
08-17 19:16:42.431  7556  7556 I Adreno-EGL: Local Branch: 
08-17 19:16:42.431  7556  7556 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-17 19:16:42.431  7556  7556 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-17 19:16:42.431  7556  7556 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-17 19:16:42.461  7587  7587 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-17 19:16:42.461  7587  7587 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-17 19:16:42.471  7587  7587 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-17 19:16:42.481   409   409 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7587
,08-17 19:16:42.481   409   409 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-17 19:16:42.481  7587  7587 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-17 19:16:42.481  7587  7587 I wpa_supplicant: ssSupport state is = 1,
08-17 19:16:42.481  7587  7587 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-17 19:16:42.481  7587  7587 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 19:16:42.481  7587  7587 E wpa_supplicant: SIM READ ERROR
08-17 19:16:42.481  7587  7587 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 19:16:42.481  7587  7587 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 19:16:42.481  7587  7587 E wpa_supplicant: SIM READ ERROR
08-17 19:16:42.481  7587  7587 I wpa_supplicant: Blacklist: Clear (all) 
08-17 19:16:42.481  7587  7587 I wpa_supplicant: wpa_default_ap_write_once
08-17 19:16:42.481  7587  7587 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-17 19:16:42.481  7587  7587 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 19:16:42.481  7587  7587 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-17 19:16:42.481  7587  7587 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 19:16:42.481  7587  7587 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-17 19:16:42.481  7587  7587 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-17 19:16:42.481  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:16:42.481  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:16:42.481  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
,08-17 19:16:42.491  7556  7616 W cr.media: Requires BLUETOOTH permission
,08-17 19:16:42.501  7556  7556 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-17 19:16:42.511  7556  7556 I NSApplication: Starting up...
,08-17 19:16:42.511  1020  1032 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-17 19:16:42.511  1020  1525 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-17 19:16:42.521  1020  1033 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
08-17 19:16:42.521  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:42.521  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:42.521  7587  7587 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-17 19:16:42.521  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:42.521  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:42.531  7621  7621 E Zygote  : MountEmulatedStorage()
,08-17 19:16:42.531  7621  7621 E Zygote  : v2
08-17 19:16:42.531  7621  7621 I libpersona: KNOX_SDCARD checking this for 10117
08-17 19:16:42.531  7621  7621 I libpersona: KNOX_SDCARD not a persona
,08-17 19:16:42.531  1020  1033 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7621 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a,
08-17 19:16:42.531  1020  1033 I ActivityManager: Killing 7126:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,08-17 19:16:42.541  7621  7621 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-17 19:16:42.541  7621  7621 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:16:42.541  7621  7621 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-17 19:16:42.581  7621  7621 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:42.581  7621  7621 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:42.601  7621  7621 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-17 19:16:42.681  7587  7587 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-17 19:16:42.681  7587  7587 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-17 19:16:42.691  7587  7587 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-17 19:16:42.691   409   409 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7587
08-17 19:16:42.691   409   409 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-17 19:16:42.701  7587  7587 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-17 19:16:42.701  7587  7587 I wpa_supplicant: ssSupport state is = 1
,08-17 19:16:42.701  7587  7587 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-17 19:16:42.701  7587  7587 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-17 19:16:42.711  7587  7587 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-17 19:16:42.711   409   409 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7587
08-17 19:16:42.711   409   409 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C,
,08-17 19:16:42.711  7587  7587 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-17 19:16:42.711  7587  7587 I wpa_supplicant: ssSupport state is = 1
08-17 19:16:42.711  7587  7587 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 19:16:42.711  7587  7587 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-17 19:16:42.711  7587  7587 E wpa_supplicant: SIM READ ERROR
08-17 19:16:42.711  7587  7587 I wpa_supplicant: wpa_default_ap_write_once
08-17 19:16:42.711  7587  7587 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-17 19:16:42.711  7587  7587 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-17 19:16:42.711  1020  1047 D Tethering: interfaceLinkStateChanged p2p0, false
08-17 19:16:42.711  1020  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-17 19:16:42.711  1020  1047 D Tethering: interfaceStatusChanged p2p0, false
,08-17 19:16:42.711  1020  1047 D Tethering: interfaceLinkStateChanged p2p0, false
08-17 19:16:42.711  1020  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-17 19:16:42.721  1020  1047 D Tethering: interfaceStatusChanged p2p0, false
,08-17 19:16:42.781   324   324 I ServiceManager: Waiting for service AtCmdFwd...,
,08-17 19:16:42.801   291   291 E SMD     : DCD OFF,
,08-17 19:16:42.831  7587  7587 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-17 19:16:42.831  7587  7587 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-17 19:16:42.911  7587  7587 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-17 19:16:42.911  7587  7587 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-17 19:16:42.911  7587  7587 I wpa_supplicant: Skip scan - bUseNetwork false
08-17 19:16:42.911  1020  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-17 19:16:42.921  1020  1129 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-17 19:16:42.921  7587  7587 I wpa_supplicant: HOTSPOT20_ENABLE called
08-17 19:16:42.921  7587  7587 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 19:16:42.921  7587  7587 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 19:16:42.921  7587  7587 E wpa_supplicant: SIM READ ERROR
08-17 19:16:42.921  7587  7587 I wpa_supplicant: Blacklist: Clear (all) 
,08-17 19:16:42.991  1020  1494 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-17 19:16:42.991  1020  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:42.991  1020  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:42.991  1020  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:42.991  1020  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:43.001  7587  7587 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-17 19:16:43.001  7645  7645 E Zygote  : MountEmulatedStorage(),
08-17 19:16:43.001  7645  7645 E Zygote  : v2
08-17 19:16:43.001  7645  7645 I libpersona: KNOX_SDCARD checking this for 10121
08-17 19:16:43.001  7645  7645 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 19:16:43.001  7645  7645 I libpersona: KNOX_SDCARD not a persona
08-17 19:16:43.001  1020  1494 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7645 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,08-17 19:16:43.011  1020  1494 I ActivityManager: Killing 7148:com.wsomacp/u0a23 (adj 15): empty #21
,08-17 19:16:43.011  7587  7587 I wpa_supplicant: Skip scan - bUseNetwork false
,08-17 19:16:43.011  7645  7645 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:16:43.011  7645  7645 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-17 19:16:43.011  1020  1129 D WifiConfigStore: Loading config and enabling all networks 
,08-17 19:16:43.021  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-17 19:16:43.021  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:16:43.021  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 19:16:43.021  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:43.021  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:43.021  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:43.021  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:43.021  1180  1180 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 19:16:43.021  1180  1180 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-17 19:16:43.021  1180  1772 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-17 19:16:43.021  1180  1180 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-17 19:16:43.021  1180  1180 D HotspotTile: onReceive : 3, 0
08-17 19:16:43.031  4844  4844 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-17 19:16:43.031  7190  7190 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:43.031  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:43.031  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:43.031  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:43.031  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:43.031  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:16:43.031  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:43.031  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:43.031  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:16:43.031  7190  7190 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:43.031  7190  7190 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:16:43.041  7190  7190 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 19:16:43.041  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:43.041  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:43.041  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:43.041  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:43.041  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
,08-17 19:16:43.041  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:43.041  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:43.041  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 19:16:43.041  1020  1129 E WifiConfigStore: Not a HS20
08-17 19:16:43.041  7190  7190 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:43.041  7190  7190 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
,08-17 19:16:43.041  7645  7645 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:43.041  7645  7645 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:43.061  7645  7645 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-17 19:16:43.061  7645  7645 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-17 19:16:43.061  7645  7645 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-17 19:16:43.071  1020  1129 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-17 19:16:43.071  1020  1129 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,08-17 19:16:43.071  7587  7587 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-17 19:16:43.071  7587  7587 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-17 19:16:43.071  7587  7587 I wpa_supplicant: reset timer : RESET_TIMER 0
08-17 19:16:43.071  7587  7587 I wpa_supplicant: P2P: Current p2p state = IDLE
08-17 19:16:43.071  7587  7587 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-17 19:16:43.071  7587  7587 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-17 19:16:43.071  7587  7587 I wpa_supplicant: First Scan Start
08-17 19:16:43.071  7587  7587 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-17 19:16:43.071  7645  7645 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-17 19:16:43.071  1020  1129 D WifiNative-wlan0: Setting external_sim to 1
08-17 19:16:43.071  7388  7388 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 19:16:43.071  1020  1129 D WifiStateMachine: Setting OUI to DA-A1-19
08-17 19:16:43.071  1020  1129 I WifiNative-HAL: startHal
08-17 19:16:43.071  1020  1129 E wifi    : getStaticLongField sWifiHalHandle 0x9f3f188c
08-17 19:16:43.071  1020  1129 I WifiNative-HAL: Could not start hal
,08-17 19:16:43.081  1020  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-17 19:16:43.081  1020  1047 D Tethering: interfaceLinkStateChanged p2p0, false
,08-17 19:16:43.081  1020  1047 D Tethering: interfaceStatusChanged p2p0, false
,08-17 19:16:43.081  1020  1129 E WifiNative-wlan0: do suspend true
,08-17 19:16:43.081  1020  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-17 19:16:43.081  1020  1128 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-17 19:16:43.081  7645  7645 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-17 19:16:43.081  1020  1020 D WifiScanningService: SCAN_AVAILABLE : 3
,08-17 19:16:43.081  1020  1129 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-17 19:16:43.081  1020  1129 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-17 19:16:43.081  1020  1129 E WifiNative-wlan0: invaild command id : 215
08-17 19:16:43.081  1020  1154 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-17 19:16:43.081  1020  1154 I WifiNative-HAL: startHal
08-17 19:16:43.081  1020  1154 E wifi    : getStaticLongField sWifiHalHandle 0x9e2b39bc
08-17 19:16:43.081  1020  1154 I WifiNative-HAL: Could not start hal
08-17 19:16:43.081  1020  1154 E WifiScanningService: could not start HAL
,08-17 19:16:43.091  1020  1020 D RttService: SCAN_AVAILABLE : 3
,08-17 19:16:43.091  1020  1155 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-17 19:16:43.091  7587  7587 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-17 19:16:43.091   278   988 D CommandListener: Setting iface cfg
08-17 19:16:43.091  7587  7587 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-17 19:16:43.091   278   988 D CommandListener: Trying to bring up p2p0
08-17 19:16:43.091  1020  1128 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-17 19:16:43.091  1020  1128 D WifiP2pService: P2pEnablingState
08-17 19:16:43.091  1020  1128 D WifiP2pService: P2pEnablingState{ what=147457 }
,08-17 19:16:43.091  1020  1128 D WifiP2pService: P2p socket connection successful
08-17 19:16:43.091  7587  7587 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,08-17 19:16:43.091  1020  1128 D WifiP2pService: P2pEnabledState
08-17 19:16:43.091  1020  1129 E WifiStateMachine: Failed to set frequency band 0
08-17 19:16:43.091  1020  1128 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-17 19:16:43.091  1020  1131 E ConnectivityService: updateNetworkInfo()
,08-17 19:16:43.091  1020  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 19:16:43.091  1020  1129 D SecContentProvider2: mCursor = null
,08-17 19:16:43.091  1020  1020 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-17 19:16:43.091  1020  1050 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-17 19:16:43.091  1020  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-17 19:16:43.091  1020  1050 D WifiDisplayController: disconnect
08-17 19:16:43.091  1020  1050 D WifiDisplayController: updateConnection
08-17 19:16:43.091  1020  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-17 19:16:43.091  1020  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 19:16:43.091  1020  1129 D SecContentProvider2: mCursor = null
,08-17 19:16:43.091  1020  1050 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-17 19:16:43.101  1020  1128 D WifiNative-p2p0: p2pGetDeviceAddress
,08-17 19:16:43.101  1020  1050 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 19:16:43.101  1020  1050 D WifiDisplayAdapter: onP2pDisconnected
08-17 19:16:43.101  1020  1050 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-17 19:16:43.101  1020  1050 D IpRemoteDisplayController: WfdBridgeServer is already null
08-17 19:16:43.101  1020  1128 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,08-17 19:16:43.101  1180  1180 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-17 19:16:43.101  7645  7645 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
08-17 19:16:43.101  1020  1506 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-17 19:16:43.101  1020  1128 D WifiP2pService: DeviceAddress: 0a:75:42
08-17 19:16:43.101  1180  1180 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-17 19:16:43.101  1020  1050 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
08-17 19:16:43.101  1020  1050 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
08-17 19:16:43.101  1020  1050 D WifiDisplayController:  primary type: 10-0050F204-5
08-17 19:16:43.101  1020  1050 D WifiDisplayController:  secondary type: null
08-17 19:16:43.101  1020  1050 D WifiDisplayController:  wps: 0
08-17 19:16:43.101  1020  1050 D WifiDisplayController:  grpcapab: 0
08-17 19:16:43.101  1020  1050 D WifiDisplayController:  devcapab: 0
08-17 19:16:43.101  1020  1050 D WifiDisplayController:  status: 3
08-17 19:16:43.101  1020  1050 D WifiDisplayController:  wfdInfo: null
08-17 19:16:43.101  1020  1050 D WifiDisplayController:  groupownerAddress: null
08-17 19:16:43.101  1020  1050 D WifiDisplayController:  GOdeviceName: null
08-17 19:16:43.101  1020  1050 D WifiDisplayController:  interfaceAddress: 
08-17 19:16:43.101  1020  1050 D WifiDisplayController:  SConnectInfo : null
,08-17 19:16:43.101  1020  1139 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,08-17 19:16:43.111  1020  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:43.111  1020  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:43.111  1020  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:43.111  1020  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:43.121  7664  7664 E Zygote  : MountEmulatedStorage()
08-17 19:16:43.121  7664  7664 E Zygote  : v2
08-17 19:16:43.121  7664  7664 I libpersona: KNOX_SDCARD checking this for 10141
08-17 19:16:43.121  7664  7664 I libpersona: KNOX_SDCARD not a persona
,08-17 19:16:43.121  1020  1139 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7664 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
08-17 19:16:43.121  1020  1139 I ActivityManager: Killing 7207:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
,08-17 19:16:43.121  7664  7664 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:16:43.131  7664  7664 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:16:43.131  7664  7664 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:16:43.131  1020  1128 D WifiP2pService: sending p2p persistent groups changed broadcast
08-17 19:16:43.131  1020  1128 D WifiP2pService: InactiveState
08-17 19:16:43.131  1020  1128 D WifiP2pService: InactiveState{ what=143376 }
08-17 19:16:43.131  1020  1128 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-17 19:16:43.141  7587  7587 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-17 19:16:43.141  1020  1128 D WifiP2pService: InactiveState{ what=143376 }
08-17 19:16:43.141  1020  1128 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-17 19:16:43.141  7664  7664 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:43.141  7664  7664 D ActivityThread: Added TimaKeyStore provider,
,08-17 19:16:43.161  7664  7664 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-17 19:16:43.161  7664  7664 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-17 19:16:43.161  7664  7664 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-17 19:16:43.161  7664  7664 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-17 19:16:43.211  1020  1525 D RCPManagerService: exchangeData() failure , invalid userId,
,08-17 19:16:43.231  1020  1341 D RCPManagerService: exchangeData() failure , invalid userId
,08-17 19:16:43.251  1020  3827 D RCPManagerService: exchangeData() failure , invalid userId
,08-17 19:16:43.261  1020  4295 D RCPManagerService: exchangeData() failure , invalid userId
,08-17 19:16:43.301  1020  1494 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-17 19:16:43.301  1020  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:43.301  1020  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:43.301  1020  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:43.301  1020  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:43.311  1020  1266 D RCPManagerService: exchangeData() failure , invalid userId
08-17 19:16:43.311  7686  7686 E Zygote  : MountEmulatedStorage()
08-17 19:16:43.311  7686  7686 E Zygote  : v2
08-17 19:16:43.311  7686  7686 I libpersona: KNOX_SDCARD checking this for 10068
08-17 19:16:43.311  7686  7686 I libpersona: KNOX_SDCARD not a persona
,08-17 19:16:43.321  1020  1494 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7686 uid=10068 gids={50068, 9997} abi=armeabi-v7a,
,08-17 19:16:43.321  7686  7686 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:16:43.321  1020  1525 D RCPManagerService: exchangeData() failure , invalid userId
,08-17 19:16:43.321  7686  7686 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:16:43.331  7686  7686 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-17 19:16:43.351   310   310 I art     : Explicit concurrent mark sweep GC freed 8689(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 598us total 28.672ms
,08-17 19:16:43.371   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 595us total 18.234ms
,08-17 19:16:43.371  7686  7686 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:43.371  7686  7686 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:43.371  1020  1032 D RCPManagerService: exchangeData() failure , invalid userId
,08-17 19:16:43.381  1020  1747 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,08-17 19:16:43.381  1020  1747 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:43.381  1020  1747 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:43.381  1020  1747 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:43.381  1020  1747 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:43.381   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 589us total 17.797ms
,08-17 19:16:43.391  7686  7686 D BadgeProvider: onCreate
,08-17 19:16:43.391  7686  7686 D BadgeProvider: DatabaseHelper
,08-17 19:16:43.401  7702  7702 E Zygote  : MountEmulatedStorage(),
,08-17 19:16:43.401  7702  7702 E Zygote  : v2
08-17 19:16:43.411  7702  7702 I libpersona: KNOX_SDCARD checking this for 10009
08-17 19:16:43.411  7702  7702 I libpersona: KNOX_SDCARD not a persona
,08-17 19:16:43.411  7702  7702 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-17 19:16:43.411  1020  1747 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7702 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,08-17 19:16:43.411  1020  1747 I ActivityManager: Killing 6997:com.android.vending/u0a26 (adj 15): empty #21,
,08-17 19:16:43.411  1020  1747 I ActivityManager: Killing 7161:com.android.defcontainer/u0a3 (adj 15): empty #22
,08-17 19:16:43.411  7702  7702 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:16:43.411  7702  7702 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-17 19:16:43.431  7686  7700 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-17 19:16:43.461  7702  7702 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:43.461  7702  7702 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:43.531  1020  1494 I ActivityManager: Killing 7355:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,08-17 19:16:43.541  1020  1032 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-17 19:16:43.541  1020  1032 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 19:16:43.541  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:43.541  1020  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:43.541  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 19:16:43.541  1640  1640 I Hs20UtilService: Starting #11
,08-17 19:16:43.541  1640  1699 I Hs20UtilService: Message received 5011
,08-17 19:16:43.551  7411  7411 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-17 19:16:43.551  7411  7411 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-17 19:16:43.551  7411  7411 D SecurityLogAgent: StateMachine : Current State = 1
,08-17 19:16:43.551  7411  7411 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 19:16:43.561  1020  4295 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-17 19:16:43.571  1020  4295 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 19:16:43.571  1020  4295 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:43.571  1020  4295 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:43.571  1020  4295 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 19:16:43.581  1640  1640 I Hs20UtilService: Starting #12
,08-17 19:16:43.581  1640  1699 I Hs20UtilService: Message received 5011
,08-17 19:16:43.581  7411  7411 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-17 19:16:43.581  7411  7411 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-17 19:16:43.581  7411  7411 D SecurityLogAgent: StateMachine : Current State = 1
08-17 19:16:43.581  7411  7411 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 19:16:43.591  1020  1266 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,08-17 19:16:43.591  1020  1266 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-17 19:16:43.591  1020  1525 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-17 19:16:43.591  1020  1525 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 19:16:43.601  1020  1525 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:43.601  1020  1525 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:43.601  1020  1525 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 19:16:43.601  1640  1640 I Hs20UtilService: Starting #13
,08-17 19:16:43.601  1640  1699 I Hs20UtilService: Message received 5011
,08-17 19:16:43.601  1020  1508 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-17 19:16:43.601  1020  1129 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-17 19:16:43.601  1020  1129 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-17 19:16:43.601  1020  1129 E WifiNative-wlan0: invaild command id : 215
,08-17 19:16:43.601  1020  1139 I art     : Explicit concurrent mark sweep GC freed 58601(3MB) AllocSpace objects, 1(64KB) LOS objects, 33% free, 23MB/34MB, paused 4.361ms total 167.733ms
,08-17 19:16:43.611  1020  1509 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-17 19:16:43.611  7411  7411 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-17 19:16:43.611  7411  7411 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-17 19:16:43.611  7411  7411 D SecurityLogAgent: StateMachine : Current State = 1
08-17 19:16:43.611  7411  7411 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 19:16:43.611  7686  7697 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-17 19:16:43.611  7686  7697 D BadgeProvider: sendNotify, [notify] : null
08-17 19:16:43.611  7686  7697 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-17 19:16:43.611  7686  7697 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-17 19:16:43.611  7686  7697 D BadgeProvider: update, [UpdateCount] : 1
,08-17 19:16:43.611  1510  1510 D Launcher.Model: reloadBadges entered.
,08-17 19:16:43.621  4844  4844 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-17 19:16:43.621  4844  4844 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-17 19:16:43.631  4844  4844 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-17 19:16:43.631  4844  4844 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-17 19:16:43.631  4844  4844 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-17 19:16:43.631  4844  4844 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-17 19:16:43.631  4844  4897 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 19:16:43.631  1020  1139 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-17 19:16:43.631  1020  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:43.631  1020  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:43.631  1020  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:43.631  1020  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:43.641  1020  1139 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7720 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-17 19:16:43.641  7720  7720 E Zygote  : MountEmulatedStorage()
08-17 19:16:43.641  7720  7720 E Zygote  : v2
08-17 19:16:43.641  7720  7720 I libpersona: KNOX_SDCARD checking this for 10064
08-17 19:16:43.641  7720  7720 I libpersona: KNOX_SDCARD not a persona
,08-17 19:16:43.641  7720  7720 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 19:16:43.651  7720  7720 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:16:43.651  7720  7720 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:16:43.661  7720  7720 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:43.661  7720  7720 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:43.681  7720  7720 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-17 19:16:43.681  7720  7720 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-17 19:16:43.691  7720  7720 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-17 19:16:43.711  7720  7720 D FileShare-Client: Outbound.stopDelayTimer - 
,08-17 19:16:43.721  7372  7372 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-17 19:16:43.721  1020  3827 I ActivityManager: Killing 7294:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,08-17 19:16:43.781   324   324 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-17 19:16:44.181  7587  7587 I wpa_supplicant: nl80211: Received scan results (30 BSSes)
08-17 19:16:44.181  7587  7587 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec,
08-17 19:16:44.181  7587  7587 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-17 19:16:44.181  7587  7587 I wpa_supplicant: Trying to associate with  'G700'
,08-17 19:16:44.181  7587  7587 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-17 19:16:44.181  7587  7587 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-17 19:16:44.181  1020  7643 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-17 19:16:44.201  1020  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 19:16:44.201  1020  1129 D SecContentProvider2: mCursor = null
,08-17 19:16:44.301  7587  7587 E wpa_supplicant: Cmd 35605 not handled
08-17 19:16:44.301  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:16:44.301  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:16:44.301  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
,08-17 19:16:44.301  7587  7587 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-17 19:16:44.301  7587  7587 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-17 19:16:44.301  7587  7587 I wpa_supplicant: Associated with F4.99.3E
08-17 19:16:44.301  7587  7587 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-17 19:16:44.301  7587  7587 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-17 19:16:44.301  7587  7587 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-17 19:16:44.301  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:16:44.301  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:16:44.301  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
,08-17 19:16:44.301  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:16:44.301  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:16:44.301  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
,08-17 19:16:44.301  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-17 19:16:44.301  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, true
08-17 19:16:44.301  1020  1047 D Tethering: interfaceStatusChanged wlan0, true
,08-17 19:16:44.301  1020  1134 E Tethering: No numeric data
08-17 19:16:44.301  1020  1134 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-17 19:16:44.301  1020  1134 D Tethering: clearTetheredNotification()
,08-17 19:16:44.311  1020  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 19:16:44.311  1020  1126 V NetworkStats: performPollLocked(flags=0x1)
08-17 19:16:44.311  1020  1129 D SecContentProvider2: mCursor = null
08-17 19:16:44.311  1020  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:44.311  7587  7587 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-17 19:16:44.311  7587  7587 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-17 19:16:44.311  7587  7587 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,08-17 19:16:44.311  7587  7587 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,08-17 19:16:44.311  7587  7587 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-17 19:16:44.311  7587  7587 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-17 19:16:44.311  7587  7587 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-17 19:16:44.311  1020  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 19:16:44.311  7587  7587 I wpa_supplicant: Blacklist: Clear (temp) 
08-17 19:16:44.311  1020  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-17 19:16:44.311  7587  7587 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,08-17 19:16:44.311  1180  1180 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-17 19:16:44.311  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-17 19:16:44.311  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, true
08-17 19:16:44.311  1020  1047 D Tethering: interfaceStatusChanged wlan0, true
08-17 19:16:44.311  1180  1180 D HotspotTile: updateTetherState():false, false
08-17 19:16:44.311  1020  1126 V NetworkStats: performPollLocked() took 6ms
08-17 19:16:44.311  1020  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:44.311  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:44.311  1020  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 19:16:44.311  1020  1129 D SecContentProvider2: mCursor = null
,08-17 19:16:44.311  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:44.321  1020  1129 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-17 19:16:44.331  1020  1129 E WifiConfigStore: setLastSelectedConfiguration -1
,08-17 19:16:44.331  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-17 19:16:44.331  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-17 19:16:44.331  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 19:16:44.331  1020  1129 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} },
,08-17 19:16:44.331  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-17 19:16:44.331  1020  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-17 19:16:44.331  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:44.331  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:44.331  1020  1509 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 19:16:44.331  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:44.331  1020  1509 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-17 19:16:44.331  1020  1131 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-17 19:16:44.331  1020  1131 E ConnectivityService: updateNetworkInfo()
08-17 19:16:44.331  1020  1129 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-17 19:16:44.341  1020  1509 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:44.341  1020  1509 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 19:16:44.341  1020  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 19:16:44.341  1640  1640 I Hs20UtilService: Starting #14
08-17 19:16:44.341  1640  1699 I Hs20UtilService: Message received 5007
,08-17 19:16:44.341  4844  4844 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-17 19:16:44.341  1020  1129 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-17 19:16:44.341  4844  4844 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-17 19:16:44.341  4844  4844 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-17 19:16:44.351  4844  4844 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-17 19:16:44.351  4844  4844 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-17 19:16:44.351  4844  4844 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-17 19:16:44.351  4844  4897 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 19:16:44.351   278   988 D CommandListener: Setting iface cfg,
,08-17 19:16:44.361  1020  1129 E WifiStateMachine: Start Dhcp Watchdog 2
,08-17 19:16:44.361  1020  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 19:16:44.361  1020  1129 D SecContentProvider2: mCursor = null
,08-17 19:16:44.361  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-17 19:16:44.361  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:16:44.361  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 19:16:44.361  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:44.371  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:44.371  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:44.371  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:44.371  1020  1129 E WifiNative-wlan0: do suspend false
,08-17 19:16:44.371  1020  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-17 19:16:44.371  1020  1129 D SecContentProvider2: mCursor = null
,08-17 19:16:44.371  1020  1128 D WifiP2pService: InactiveState{ what=143375 },
08-17 19:16:44.371  1020  1128 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-17 19:16:44.591  7737  7737 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-17 19:16:44.591  7737  7737 I dhcpcd  : version 5.5.6 starting,
,08-17 19:16:44.601  7737  7737 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-17 19:16:44.651  7737  7737 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-17 19:16:44.651  7737  7737 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-17 19:16:44.651  7737  7737 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E),
,08-17 19:16:44.651  7737  7737 I dhcpcd  : bssid match
,08-17 19:16:44.661  7737  7737 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
,08-17 19:16:44.701  1020  1032 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-17 19:16:44.701  1020  1032 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-17 19:16:44.701  1020  1032 D SecContentProvider2: mCursor = null
,08-17 19:16:44.701  1020  1032 D WifiService: setWifiEnabled: false pid=7190, uid=10170
,08-17 19:16:44.701  1020  1032 D SettingsProvider: name = wifi_on
,08-17 19:16:44.711  1020  1129 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 19:16:44.721  1020  1129 E WifiNative-wlan0: do suspend true,
,08-17 19:16:44.731  1020  1128 D WifiP2pService: InactiveState{ what=143375 },
08-17 19:16:44.731  1020  1128 D WifiP2pService: P2pEnabledState{ what=143375 }
08-17 19:16:44.741   278   988 D CommandListener: Clearing all IP addresses on wlan0
,08-17 19:16:44.741  7737  7737 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1
,08-17 19:16:44.741  7737  7737 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds
08-17 19:16:44.741  1020  1131 E ConnectivityService: updateNetworkInfo()
08-17 19:16:44.741  1020  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps],
08-17 19:16:44.741  1020  1131 E ConnectivityService: updateNetworkInfo()
08-17 19:16:44.741  1020  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
08-17 19:16:44.751   278   988 E Netd    : no such netId 503
,08-17 19:16:44.751  1020  1131 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '78 network destroy 503' failed with '400 78 destroyNetwork() failed (Machine is not on the network)'
08-17 19:16:44.751  1020  1131 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,08-17 19:16:44.751  1020  1131 V NetworkStats: updateIfacesLocked()
08-17 19:16:44.751  1020  1131 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:44.751  1020  1131 V NetworkStats: performPollLocked(flags=0x1)
08-17 19:16:44.751  1020  1020 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-17 19:16:44.761  1020  1131 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 19:16:44.761  1020  1131 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 19:16:44.761  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-17 19:16:44.761  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-17 19:16:44.761  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-17 19:16:44.771  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:44.771  1020  1131 V NetworkStats: performPollLocked() took 12ms
08-17 19:16:44.771  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:44.771  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:44.771  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:44.771  1020  1131 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:44.781  1020  1129 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-17 19:16:44.781  1020  1128 D WifiP2pService: InactiveState{ what=131204 }
08-17 19:16:44.781  1020  7735 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-17 19:16:44.781  1020  1128 D WifiP2pService: P2pEnabledState{ what=131204 }
08-17 19:16:44.781  1020  1131 D ConnectivityService: nai.networkMonitor.doQuit()
08-17 19:16:44.781  1020  1131 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
08-17 19:16:44.781  1020  1131 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-17 19:16:44.781  1020  1131 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-17 19:16:44.781  1020  7735 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-17 19:16:44.781  1020  1020 D WifiScanningService: SCAN_AVAILABLE : 1
08-17 19:16:44.781  1020  1154 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-17 19:16:44.791  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-17 19:16:44.791  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:16:44.791  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 19:16:44.791  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:44.791  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:44.791  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:44.791  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:44.791  1020  1020 D RttService: SCAN_AVAILABLE : 1
08-17 19:16:44.791  1020  1155 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-17 19:16:44.791  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:44.791  1020  1128 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-17 19:16:44.791  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:44.791  1020  1131 E ConnectivityService: updateNetworkInfo()
,08-17 19:16:44.791  1020  1050 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-17 19:16:44.791  1020  1050 D WifiDisplayAdapter: onP2pDisconnected
08-17 19:16:44.791  1020  1050 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-17 19:16:44.791  1020  1050 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-17 19:16:44.801  1020  1033 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 19:16:44.801  1020  1033 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-17 19:16:44.801  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:44.801  1020  1033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:44.801  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-17 19:16:44.801  1020  1128 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-17 19:16:44.801  1640  1640 I Hs20UtilService: Starting #15
08-17 19:16:44.801  1020  1131 E ConnectivityService: updateNetworkInfo()
,08-17 19:16:44.801  1020  1020 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-17 19:16:44.801  1020  1050 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-17 19:16:44.801  1020  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-17 19:16:44.801  1020  1050 D WifiDisplayController: disconnect
08-17 19:16:44.801  1020  1050 D WifiDisplayController: updateConnection
08-17 19:16:44.801  1020  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-17 19:16:44.801  1020  1050 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-17 19:16:44.801  1640  1699 I Hs20UtilService: Message received 5007
08-17 19:16:44.801  4844  4844 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-17 19:16:44.801  4844  4844 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-17 19:16:44.801  4844  4844 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-17 19:16:44.801  1020  1128 D WifiP2pService: P2pDisablingState
08-17 19:16:44.801  1020  1128 D WifiP2pService: P2pDisablingState{ what=147458 }
08-17 19:16:44.801  1020  1128 D WifiP2pService: p2p socket connection lost
,08-17 19:16:44.801  1020  1128 D WifiP2pService: P2pDisabledState
,08-17 19:16:44.811  1020  1129 E WifiNative-wlan0: do suspend true
,08-17 19:16:44.811  1020  1050 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,08-17 19:16:44.811  1020  1050 D WifiDisplayAdapter: onP2pDisconnected
08-17 19:16:44.811  1020  1050 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-17 19:16:44.811  1020  1050 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-17 19:16:44.811  1180  1180 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-17 19:16:44.811  4844  4844 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-17 19:16:44.811  4844  4844 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 19:16:44.811  4844  4844 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-17 19:16:44.811  1020  1525 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-17 19:16:44.811  4844  4897 V NearbySettings: MountReceiver.mPrefHandler - 7002,
08-17 19:16:44.811  1180  1180 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-17 19:16:44.821  4844  4844 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-17 19:16:44.821  4844  4844 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-17 19:16:44.821  4844  4844 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-17 19:16:44.831  4844  4844 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-17 19:16:44.831  4844  4844 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 19:16:44.831  4844  4844 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-17 19:16:44.831  4844  4897 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 19:16:44.831  7720  7720 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-17 19:16:44.831  7720  7720 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-17 19:16:44.831  7720  7720 D FileShare-Client: Outbound.stopDelayTimer - 
,08-17 19:16:44.831  1020  1128 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-17 19:16:44.831  1020  1128 D WifiP2pService: DefaultState{ what=143375 }
,08-17 19:16:44.841   278   988 D CommandListener: Clearing all IP addresses on wlan0
,08-17 19:16:44.841  7372  7372 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null,
,08-17 19:16:44.841  7587  7587 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-17 19:16:44.851  1020  1020 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-17 19:16:44.851  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-17 19:16:44.851  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:16:44.851  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 19:16:44.851  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:44.851  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:44.851  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:44.851  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,08-17 19:16:44.851  1020  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 19:16:44.851  1020  1129 D SecContentProvider2: mCursor = null,
,08-17 19:16:44.861  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-17 19:16:44.861  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:16:44.861  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 19:16:44.861  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:44.861  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:44.861  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:44.861  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:44.871  4844  4844 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-17 19:16:44.871  7190  7190 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 19:16:44.871  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:44.871  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:44.871  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:44.871  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:16:44.871  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:16:44.871  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:44.871  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:44.871  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:16:44.871  7190  7190 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-17 19:16:44.871  1020  1033 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 19:16:44.871  7190  7190 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 19:16:44.871  1020  1033 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 19:16:44.881  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-17 19:16:44.881  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:16:44.881  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-17 19:16:44.881  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:44.881  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:44.881  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:44.881  1020  1033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:44.881  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-17 19:16:44.881  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:44.881  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:44.881  1180  1180 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 19:16:44.881  1180  1180 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-17 19:16:44.881  1180  1180 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-17 19:16:44.881  1180  1772 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-17 19:16:44.881  1640  1640 I Hs20UtilService: Starting #16
08-17 19:16:44.881  7190  7190 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:44.881  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:44.881  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:44.881  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:44.881  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:16:44.881  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:16:44.881  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:44.881  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:44.881  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 19:16:44.881  1180  1180 D HotspotTile: onReceive : 0, 0
,08-17 19:16:44.881  7190  7190 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:44.881  7190  7190 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 19:16:44.881  1640  1699 I Hs20UtilService: Message received 5007
,08-17 19:16:44.891  4844  4844 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-17 19:16:44.891  4844  4844 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-17 19:16:44.891  4844  4844 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-17 19:16:44.891  4844  4844 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-17 19:16:44.891  4844  4844 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 19:16:44.891  4844  4844 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-17 19:16:44.891  4844  4897 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 19:16:44.911  1020  1509 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-17 19:16:44.911  1020  1509 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-17 19:16:44.921  1020  1509 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:44.921  1020  1509 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:44.921  1020  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 19:16:44.921  1640  1640 I Hs20UtilService: Starting #17
,08-17 19:16:44.921  1640  1699 I Hs20UtilService: Message received 5011
,08-17 19:16:44.921  7411  7411 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-17 19:16:44.921  7411  7411 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-17 19:16:44.921  7411  7411 D SecurityLogAgent: StateMachine : Current State = 1
,08-17 19:16:44.921  7411  7411 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 19:16:44.981  7587  7587 I wpa_supplicant: Blacklist: Clear (all) 
,08-17 19:16:45.091  1020  1047 D Tethering: interfaceLinkStateChanged p2p0, false,
08-17 19:16:45.091  1020  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-17 19:16:45.091  1020  1047 D Tethering: interfaceStatusChanged p2p0, false,
,08-17 19:16:45.091  7587  7587 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-17 19:16:45.121  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false,
08-17 19:16:45.121  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:16:45.121  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
08-17 19:16:45.121  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:16:45.121  1020  1134 D Tethering: InitialState.processMessage what=4
08-17 19:16:45.121  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:16:45.121  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
08-17 19:16:45.121  1020  1134 E Tethering: No numeric data
08-17 19:16:45.121  1020  1134 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-17 19:16:45.121  1020  1134 D Tethering: clearTetheredNotification()
08-17 19:16:45.131  7587  7587 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,08-17 19:16:45.131  7587  7587 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-17 19:16:45.131  1020  1126 V NetworkStats: performPollLocked(flags=0x1)
08-17 19:16:45.131  7587  7587 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-17 19:16:45.131  1020  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:45.131  7587  7587 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-17 19:16:45.131  7587  7587 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-17 19:16:45.131  1020  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 19:16:45.131  1020  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 19:16:45.131  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:16:45.131  1180  1180 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-17 19:16:45.131  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
08-17 19:16:45.131  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:16:45.131  1180  1180 D HotspotTile: updateTetherState():false, false
,08-17 19:16:45.141  1020  1126 V NetworkStats: performPollLocked() took 7ms
,08-17 19:16:45.141  1020  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:45.141  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit,
08-17 19:16:45.141  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:45.281  1020  1098 V AlarmManager: waitForAlarm result :4,
,08-17 19:16:45.291  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:16:45.291  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:16:45.291  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
,08-17 19:16:45.291   278   984 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-17 19:16:45.291   278   984 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-17 19:16:45.311  1020  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:45.311  1020  1045 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-17 19:16:45.311  1020  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,08-17 19:16:45.441  7587  7587 I wpa_supplicant: Blacklist: Clear (all) 
,08-17 19:16:45.551  7587  7587 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-17 19:16:45.551  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:16:45.551  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:16:45.551  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
,08-17 19:16:45.661  1020  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-17 19:16:45.661  1020  1129 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-17 19:16:45.661  7388  7388 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 19:16:45.671  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-17 19:16:45.671  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:16:45.671  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-17 19:16:45.671  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:45.671  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:45.671  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:45.671  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:45.681  1180  1180 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 19:16:45.681  1180  1180 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-17 19:16:45.681  1180  1180 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 19:16:45.681  1180  1772 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-17 19:16:45.681  1180  1180 D HotspotTile: onReceive : 1, 0
,08-17 19:16:45.681  1764  2200 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 19:16:45.681  4844  4844 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-17 19:16:45.681  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:45.691  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:45.691  1020  1508 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-17 19:16:45.691  1020  1508 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 19:16:45.691  1020  1508 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:45.691  1020  1508 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 19:16:45.691  1020  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 19:16:45.701  1640  1640 I Hs20UtilService: Starting #18
,08-17 19:16:45.701  1640  1699 I Hs20UtilService: Message received 5011
,08-17 19:16:45.701  7411  7411 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-17 19:16:45.701  7411  7411 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-17 19:16:45.701  7411  7411 D SecurityLogAgent: StateMachine : Current State = 1
,08-17 19:16:45.701  7411  7411 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 19:16:45.801   291   291 E SMD     : DCD OFF,
,08-17 19:16:46.321  1020  1047 D Tethering: interfaceRemoved wlan0
,08-17 19:16:46.321  1020  1047 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-17 19:16:46.481  1020  1047 D Tethering: interfaceRemoved p2p0
,08-17 19:16:46.481  1020  1047 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-17 19:16:47.251  1020  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-17 19:16:47.661  1020  3378 D SSRM:n  : SIOP:: AP = 350
,08-17 19:16:47.701  7190  7267 D BluetoothAdapter: enable()
,08-17 19:16:47.711  1020  1747 W ActivityManager: Permission Denial: getCurrentUser() from pid=7190, uid=10170 requires android.permission.INTERACT_ACROSS_USERS,
,08-17 19:16:47.721  1020  1747 W BluetoothManagerService: Failed getting userId using ActivityManagerNative,
08-17 19:16:47.721  1020  1747 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7190, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-17 19:16:47.721  1020  1747 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-17 19:16:47.721  1020  1747 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
,08-17 19:16:47.721  1020  1747 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-17 19:16:47.721  1020  1747 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-17 19:16:47.721  1020  1747 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-17 19:16:47.721  1020  1747 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-17 19:16:47.721  1020  1747 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 19:16:47.721  1020  1747 D SettingsProvider: name = bluetooth_on,
,08-17 19:16:47.731  1020  1049 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
08-17 19:16:47.731  1020  1049 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 19:16:47.741  1020  1049 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-17 19:16:47.741  3213  3284 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-17 19:16:47.741  3213  3284 D BluetoothAdapterProperties: Setting state to 11
,08-17 19:16:47.741  3213  3284 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-17 19:16:47.741  3213  3284 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-17 19:16:47.741  3213  3284 D BluetoothAdapterService: updateAdapterState state is 11
,08-17 19:16:47.741  3213  3284 D BluetoothAdapterService: Autoconnection is available 
,08-17 19:16:47.741  3213  3284 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
08-17 19:16:47.741  3213  3284 D BtConfig.SecureMode: isSecureModeOn:false
,08-17 19:16:47.741  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-17 19:16:47.741  3213  3284 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
,08-17 19:16:47.741  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-17 19:16:47.741  3213  3284 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
08-17 19:16:47.751  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-17 19:16:47.751  3213  3284 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
08-17 19:16:47.751  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService,
08-17 19:16:47.751  3213  3284 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
08-17 19:16:47.751  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-17 19:16:47.751  3213  3284 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
08-17 19:16:47.751  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-17 19:16:47.751  3213  3284 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
,08-17 19:16:47.751  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 19:16:47.751  3213  3284 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
08-17 19:16:47.751  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-17 19:16:47.751  3213  3284 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
,08-17 19:16:47.751  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:16:47.751  3213  3284 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:16:47.751  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-17 19:16:47.751  3213  3284 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:16:47.751  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService,
08-17 19:16:47.751  3213  3284 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-17 19:16:47.751  1020  1020 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-17 19:16:47.751  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-17 19:16:47.751  1020  1020 I InputMethodManagerService: [BT Setting State] State =11
,08-17 19:16:47.751  3213  3284 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-17 19:16:47.751  3213  3284 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
08-17 19:16:47.751  3213  3284 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-17 19:16:47.751  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-17 19:16:47.751  3213  3284 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-17 19:16:47.761  1180  1180 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-17 19:16:47.761  1180  1180 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:47.761  1180  1180 D BluetoothTile:  getBluetoothState : 11
,08-17 19:16:47.761  1894  1894 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-17 19:16:47.771  4844  4844 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:47.771  1020  1032 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 19:16:47.771  1020  4295 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:47.771  1020  4295 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-17 19:16:47.771  1020  1340 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-17 19:16:47.771  1020  4295 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:47.771  1020  4295 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:47.771  1020  4295 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 19:16:47.781  1180  1772 D BluetoothTile:  handleUpdatestate:false name:null
08-17 19:16:47.781  1180  1772 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-17 19:16:47.781  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:47.781  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:16:47.781  1180  1180 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-17 19:16:47.781  3213  3284 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-17 19:16:47.781  1020  1341 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:47.781  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-17 19:16:47.781  1020  1341 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-17 19:16:47.781  3213  3284 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-17 19:16:47.781  3213  3213 D HeadsetService: Received start request. Starting profile...
08-17 19:16:47.781  1020  1341 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:47.781  3213  3213 D HeadsetService: start()
08-17 19:16:47.781  1020  1341 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:47.781  3213  3213 D HeadsetStateMachine: make
08-17 19:16:47.781  1020  1341 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:47.791  3213  3284 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-17 19:16:47.791  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-17 19:16:47.791  3213  3284 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-17 19:16:47.791  1020  1494 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:47.791  1020  1494 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-17 19:16:47.791  1020  1494 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:47.791  1020  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:47.791  1020  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:47.791  3213  3213 E HeadsetStateMachine: # of Max HF connection is 2
,08-17 19:16:47.791  3213  3284 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-17 19:16:47.791  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-17 19:16:47.791  3213  3284 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-17 19:16:47.801  1662  1662 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 19:16:47.801  1020  1747 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:47.801  1020  1747 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-17 19:16:47.801  1020  1747 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:47.801  1020  1747 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 19:16:47.801  1020  1747 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:47.811  1020  1032 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-17 19:16:47.811  1020  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
08-17 19:16:47.811  3213  3284 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-17 19:16:47.811  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-17 19:16:47.811  3213  3284 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-17 19:16:47.811  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:47.811  1020  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 19:16:47.811  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-17 19:16:47.811  1020  1340 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:16:47.811  1020  1340 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-17 19:16:47.811  1020  1340 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:47.811  1020  1340 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:47.811  1020  1340 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:47.821  1020  1506 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-17 19:16:47.821  1020  1506 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-17 19:16:47.821  3213  3284 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,08-17 19:16:47.821  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-17 19:16:47.821  3213  3284 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-17 19:16:47.821  1020  1506 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:47.821  1020  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:47.821  1020  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-17 19:16:47.821  3213  3213 I bluedroid: get_profile_interface handsfree,
,08-17 19:16:47.821  1020  1139 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:47.821  1020  1139 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-17 19:16:47.831  1020  1139 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:47.831  1020  1139 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:47.831  1020  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 19:16:47.831  4844  4844 D BluetoothNotiBroadcastReceiver: onReceive
,08-17 19:16:47.831  3213  3284 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
,08-17 19:16:47.831  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-17 19:16:47.831  3213  3284 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-17 19:16:47.841  1180  1180 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:47.841  1180  1180 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-17 19:16:47.841  1020  1494 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:16:47.841  1020  1494 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-17 19:16:47.841  1020  1494 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:47.841  1020  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:47.841  1020  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:47.841  3213  3284 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService,
08-17 19:16:47.841  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:16:47.841  3213  3284 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:16:47.841  3213  3284 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:16:47.841  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:16:47.841  3213  3284 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,08-17 19:16:47.841  3213  3284 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-17 19:16:47.841  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-17 19:16:47.841  3213  3284 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService,
08-17 19:16:47.841  3213  3284 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-17 19:16:47.841  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-17 19:16:47.841  3213  3284 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-17 19:16:47.841  3213  3284 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-17 19:16:47.851  3213  3213 E DualScoManager: Dual Sco Manager already instantiated,
08-17 19:16:47.851  3213  3213 I DualScoManager: Set HeadsetServiceHelper
08-17 19:16:47.851  3213  3213 D BluetoothAtMessage: createCMTIContentObservers
08-17 19:16:47.851  1020  1508 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-17 19:16:47.851  1020  1508 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-17 19:16:47.851  1020  1508 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:47.851  1020  1508 D SettingsProvider: selectionArgs: false
08-17 19:16:47.851  1020  1508 D SettingsProvider: selectionArgs: 1002
08-17 19:16:47.851  1020  1508 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:47.851  1020  1508 D SettingsProvider: ret = -1
08-17 19:16:47.851  3213  7771 D HeadsetStateMachine: Enter Disconnected: -2
,08-17 19:16:47.851  1020  1032 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-17 19:16:47.851  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:47.851  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:47.851  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:47.851  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:47.861  7772  7772 E Zygote  : MountEmulatedStorage()
,08-17 19:16:47.871  7772  7772 E Zygote  : v2
08-17 19:16:47.871  1020  1032 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7772 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
08-17 19:16:47.871  7772  7772 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 19:16:47.871  7772  7772 I libpersona: KNOX_SDCARD checking this for 10055
08-17 19:16:47.871  7772  7772 I libpersona: KNOX_SDCARD not a persona
08-17 19:16:47.871  3213  3213 D HeadsetService: mStartError = false
08-17 19:16:47.871  3213  3213 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e7895
,08-17 19:16:47.871  3213  3213 D A2dpService: Received start request. Starting profile...
08-17 19:16:47.871  3213  3213 D A2dpService: start()
08-17 19:16:47.871  3213  3213 I bluedroid: get_profile_interface avrcp
,08-17 19:16:47.871  7772  7772 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:16:47.871  3213  7771 D HeadsetStateMachine: Clear mHeadsetBrsf
08-17 19:16:47.871  3213  7771 D HeadsetStateMachine: map size, before remove : 0
08-17 19:16:47.871  3213  7771 D HeadsetStateMachine: map size, after remove: 0
,08-17 19:16:47.871  3213  3213 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-17 19:16:47.871  3213  3213 D Avrcp   : Initialize Media Controller
08-17 19:16:47.871  3213  3213 D Avrcp   : Get the Context Package Name: com.android.bluetooth
08-17 19:16:47.871  7772  7772 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-17 19:16:47.871  3213  3213 E Avrcp   : getActiveSessions
08-17 19:16:47.871  3213  3213 D Avrcp   : pick active media Controller
08-17 19:16:47.871  3213  3213 D Avrcp   : Get the active Media Controller 
,08-17 19:16:47.881  3213  3213 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-17 19:16:47.881  3213  7778 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-17 19:16:47.891  3213  3213 D A2dpStateMachine: make
,08-17 19:16:47.891  3213  3213 I bluedroid: get_profile_interface a2dp
,08-17 19:16:47.891  3213  7783 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-17 19:16:47.891  3213  3213 E bt-btif : warning : media task started media_task_refcnt 1 
,08-17 19:16:47.891  3213  3213 D A2dpService: mStartError = false
08-17 19:16:47.891  3213  3213 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e7895
08-17 19:16:47.891  3213  7782 D A2dpStateMachine: Enter Disconnected: -2
08-17 19:16:47.891  3213  3213 D HidService: Received start request. Starting profile...
08-17 19:16:47.891  3213  3213 D HidService: start()
08-17 19:16:47.891  3213  3213 I bluedroid: get_profile_interface hidhost
08-17 19:16:47.891  3213  3213 D HidService: setHidService(): set to: null
08-17 19:16:47.891  3213  3213 D HidService: mStartError = false
08-17 19:16:47.891  3213  3213 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e7895
,08-17 19:16:47.891  3213  3213 D HealthService: Received start request. Starting profile...
08-17 19:16:47.891  3213  3213 D HealthService: start()
,08-17 19:16:47.901  3213  3213 I bluedroid: get_profile_interface health
08-17 19:16:47.901  3213  3213 D HealthService: mStartError = false
08-17 19:16:47.901  3213  3213 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e7895
,08-17 19:16:47.901  3213  3213 D HeadsetStateMachine: Try to query the phonestate on bind
,08-17 19:16:47.901  1453  1496 I Telecom : BluetoothPhoneService: queryPhoneState
,08-17 19:16:47.901  1453  1453 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
08-17 19:16:47.901  1453  1453 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-17 19:16:47.901  1453  1496 I Telecom : BluetoothPhoneService: Result of Message : true
,08-17 19:16:47.901  3213  3213 D HeadsetStateMachine: Proxy object connected
08-17 19:16:47.901  3213  3213 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
08-17 19:16:47.901  3213  7771 D HeadsetStateMachine: Disconnected process message: 11
08-17 19:16:47.901  3213  3213 D PanService: Received start request. Starting profile...
08-17 19:16:47.901  3213  3213 D PanService: start()
08-17 19:16:47.901  3213  3213 D BluetoothPanServiceJni: initializeNative(L110): pan
08-17 19:16:47.901  3213  3213 I bluedroid: get_profile_interface pan
08-17 19:16:47.901  7772  7772 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 19:16:47.901  3213  3213 D PanService: mStartError = false
08-17 19:16:47.901  3213  3213 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e7895
,08-17 19:16:47.901  3213  3213 D BluetoothMapService: Received start request. Starting profile...
08-17 19:16:47.901  3213  3213 D BluetoothMapService: start()
08-17 19:16:47.901  7772  7772 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:47.901  3213  3213 D BluetoothMapService: mStartError = false
08-17 19:16:47.901  3213  3213 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e7895
08-17 19:16:47.901  3213  3213 D HeadsetPhoneState: sendDeviceDataStateChanged
08-17 19:16:47.901  3213  7778 D BluetoothMediaBrowser: no now playing list
08-17 19:16:47.901  3213  7778 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
08-17 19:16:47.901  3213  3213 D HeadsetPhoneState: Signal level : previous=0 curr=4
08-17 19:16:47.901  3213  7771 D HeadsetStateMachine: Disconnected process message: 18
,08-17 19:16:47.911  3213  3213 D SapService: Received start request. Starting profile...
08-17 19:16:47.911  3213  3213 D SapService: start()
08-17 19:16:47.911  3213  3213 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-17 19:16:47.911  3213  3213 I bluedroid: get_profile_interface sap
08-17 19:16:47.911  3213  3213 D SapService: mStartError = false
08-17 19:16:47.911  3213  3213 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e7895
08-17 19:16:47.911  3213  3213 E BluetoothAdapterService(5142677): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-17 19:16:47.911  3213  3213 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-17 19:16:47.911  3213  3213 E BluetoothAdapterService(5142677): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-17 19:16:47.911  3213  3213 E BluetoothAdapterService(5142677): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-17 19:16:47.911  3213  3213 E BluetoothAdapterService(5142677): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-17 19:16:47.911  3213  3213 E BluetoothAdapterService(5142677): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-17 19:16:47.911  3213  7771 D HeadsetStateMachine: Disconnected process message: 10
08-17 19:16:47.911  3213  7771 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-17 19:16:47.911  3213  7771 D HeadsetStateMachine: Disconnected process message: 11
,08-17 19:16:47.921  3213  3213 E BluetoothAdapterService(5142677): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-17 19:16:47.931  3213  3213 E BluetoothAdapterService(5142677): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-17 19:16:47.931  3213  3284 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-17 19:16:47.931  3213  3284 I bluedroid: enable
,08-17 19:16:47.931  3213  3287 E bt-btif : Calling BTA_HhEnable
,08-17 19:16:47.931  7772  7772 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-17 19:16:47.941  3213  3287 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,08-17 19:16:47.941  3213  3287 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,08-17 19:16:47.941  3213  3287 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-17 19:16:47.941  3213  3287 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
,08-17 19:16:47.941  3213  3287 E BluetoothServiceJni: populateRssiValuesNative
08-17 19:16:47.941  3213  3287 I bluedroid: getModelRssiValues
,08-17 19:16:47.941  3213  3287 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-17 19:16:47.941  3213  3287 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-17 19:16:47.941  1020  1020 D SettingsProvider: name = bluetooth_name
,08-17 19:16:47.951  3213  3287 D BluetoothAdapterProperties: Name is: Galaxy A3
,08-17 19:16:47.951  3213  3287 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-17 19:16:47.951  3213  3287 D BluetoothAdapterProperties: Scan Mode:20
08-17 19:16:47.951  3213  3287 D BluetoothAdapterProperties: Discoverable Timeout:120
08-17 19:16:47.951  3213  3287 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
08-17 19:16:47.951  3213  3287 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
08-17 19:16:47.951  3213  3287 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
08-17 19:16:47.951  3213  3287 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-17 19:16:47.951  3213  3287 E bt-btif : JVenable fails
,08-17 19:16:47.951  3213  3287 D bte_conf: Device ID record 1 : primary
,08-17 19:16:47.951  3213  3287 D bte_conf:   vendorId            = 0075
08-17 19:16:47.951  3213  3287 D bte_conf:   vendorIdSource      = 0001
,08-17 19:16:47.951  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:47.951  3213  3287 D bte_conf:   product             = 0100
,08-17 19:16:47.951  3213  3287 D bte_conf:   version             = 0200
,08-17 19:16:47.951  3213  3287 D bte_conf:   clientExecutableURL = 
,08-17 19:16:47.951  3213  3287 D bte_conf:   serviceDescription  = ,
08-17 19:16:47.951  3213  3287 D bte_conf:   documentationURL    = 
08-17 19:16:47.951  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:47.961  3213  3287 D bte_conf: bte_load_did_conf no section named DID2.
,08-17 19:16:47.961  3213  3284 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-17 19:16:47.961  3213  3284 D BluetoothAdapterProperties: ScanMode =  20
08-17 19:16:47.961  3213  3284 D BluetoothAdapterProperties: State =  11
,08-17 19:16:47.961  3213  3287 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-17 19:16:47.961  3213  3287 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-17 19:16:47.961  1020  1747 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-17 19:16:47.961  3213  3284 D BluetoothAdapterProperties: Setting state to 12
,08-17 19:16:47.961  3213  3284 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-17 19:16:47.971  7772  7772 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
08-17 19:16:47.971  3213  3287 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-17 19:16:47.971  3213  3287 D BluetoothAdapterProperties: Scan Mode:21
08-17 19:16:47.971  3213  3287 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-17 19:16:47.971  7772  7772 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-17 19:16:47.971  7772  7772 D UserAnalysis: Create SecureDbHelper
,08-17 19:16:47.971  1020  1033 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-17 19:16:47.971  1020  1033 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-17 19:16:47.971  1020  1033 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-17 19:16:47.971  1020  1033 D SettingsProvider: selectionArgs: false
,08-17 19:16:47.971  1020  1033 D SettingsProvider: selectionArgs: 1002
,08-17 19:16:47.971  1020  1033 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:47.971  1020  1033 D SettingsProvider: ret = -1
,08-17 19:16:47.971  3213  3284 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-17 19:16:47.971  3213  3284 D BluetoothAdapterService: updateAdapterState state is 12
,08-17 19:16:47.971  7772  7772 D IntelligenceServiceApplication: onCreate()
08-17 19:16:47.971  1020  1747 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:16:47.971  1020  1747 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-17 19:16:47.981  1020  1747 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:47.981  1020  1747 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:47.981  1020  1747 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:47.981  3213  3284 D BluetoothAdapterService: Autoconnection is available 
,08-17 19:16:47.981  4844  4852 D Bluetoothsap: onBluetoothStateChange: up=true
08-17 19:16:47.981  3213  3284 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-17 19:16:47.981  4844  4852 D Bluetoothsap: Binding service...
08-17 19:16:47.981  3213  3284 D BluetoothAdapterService: starting service from this receiver
,08-17 19:16:47.981  3213  3213 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
08-17 19:16:47.981  1020  1032 I ActivityManager: Killing 7326:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,08-17 19:16:47.981  3213  3213 I BluetoothPbapService: Handler(): got msg=1
08-17 19:16:47.981  7772  7772 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-17 19:16:47.991  1020  1340 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-17 19:16:47.991  1020  1509 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:47.991  1020  1509 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-17 19:16:47.991  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:47.991  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:47.991  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:47.991  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:16:47.991  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:47.991  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:47.991  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:47.991  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:16:47.991  4844  4852 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-17 19:16:47.991  7190  7190 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:16:47.991  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:47.991  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:47.991  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:47.991  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:16:47.991  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:47.991  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:47.991  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:47.991  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:16:47.991  7190  7190 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:16:48.001  1020  1509 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:48.001  1020  1509 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:48.001  1020  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:48.001  3213  3284 I BluetoothAdapterState: Entering On State from state = 11
,08-17 19:16:48.001  1020  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-17 19:16:48.001  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-17 19:16:48.001  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:48.001  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:48.001  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:48.001  1020  1525 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-17 19:16:48.001  4844  4852 D Bluetoothsap: bindService called to Bluetooth SAP Service
08-17 19:16:48.001  1020  1049 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 19:16:48.001  1020  1049 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-17 19:16:48.011  7772  7772 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-17 19:16:48.011  3213  7796 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-17 19:16:48.011  1020  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-17 19:16:48.011  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 19:16:48.011  4844  4855 D BluetoothMap: onBluetoothStateChange: up=true
,08-17 19:16:48.011  1020  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-17 19:16:48.011  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-17 19:16:48.011  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:48.011  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:48.011  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:48.011  3213  7796 D BluetoothSocket: bindListen(): myUserId = 0
08-17 19:16:48.011  3213  7796 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 19:16:48.021  7772  7772 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-17 19:16:48.021  1764  1773 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-17 19:16:48.021  1764  1773 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:16:48.021  1020  1049 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-17 19:16:48.021  1020  1020 D BluetoothA2dp: Proxy object connected
08-17 19:16:48.021  4844  4844 D Bluetoothsap: BluetoothSAP Proxy object connected
08-17 19:16:48.021  4844  4844 D SapProfile: Bluetooth service connected
08-17 19:16:48.021  4844  4844 D Bluetoothsap: getConnectedDevices()
,08-17 19:16:48.021  3213  7796 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
,08-17 19:16:48.021  3213  7796 D BluetoothSocket: bindListen(), new LocalSocket 
08-17 19:16:48.021  3213  7796 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-17 19:16:48.021  3213  7796 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2075d946
08-17 19:16:48.021  3213  7796 D BluetoothSocket: channel: 19
08-17 19:16:48.021  3213  7796 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-17 19:16:48.031  1020  1049 E BluetoothManagerService: Unable to call onBluetoothStateChange() on callback #4
08-17 19:16:48.031  1020  1049 E BluetoothManagerService: android.os.TransactionTooLargeException
08-17 19:16:48.031  1020  1049 E BluetoothManagerService: 	at android.os.BinderProxy.transactNative(Native Method)
08-17 19:16:48.031  1020  1049 E BluetoothManagerService: 	at android.os.BinderProxy.transact(Binder.java:496)
08-17 19:16:48.031  1020  1049 E BluetoothManagerService: 	at android.bluetooth.IBluetoothStateChangeCallback$Stub$Proxy.onBluetoothStateChange(IBluetoothStateChangeCallback.java:84)
08-17 19:16:48.031  1020  1049 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.sendBluetoothStateCallback(BluetoothManagerService.java:1053)
08-17 19:16:48.031  1020  1049 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.bluetoothStateChangeHandler(BluetoothManagerService.java:2007)
08-17 19:16:48.031  1020  1049 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.access$3900(BluetoothManagerService.java:105)
08-17 19:16:48.031  1020  1049 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService$BluetoothHandler.handleMessage(BluetoothManagerService.java:1576)
08-17 19:16:48.031  1020  1049 E BluetoothManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:16:48.031  1020  1049 E BluetoothManagerService: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:16:48.031  1020  1049 E BluetoothManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-17 19:16:48.031  1020  1049 E BluetoothManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-17 19:16:48.031  4844  4844 D BluetoothMap: Proxy object connected
08-17 19:16:48.031  4844  4844 D MapProfile: Bluetooth service connected
08-17 19:16:48.031  4844  4844 D BluetoothMap: getConnectedDevices()
,08-17 19:16:48.031  4844  4855 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-17 19:16:48.031  4844  4855 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:16:48.031  1477  1502 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:16:48.031  1020  1049 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-17 19:16:48.031  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 19:16:48.031  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:48.031  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:48.031  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:48.031  1477  1502 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 19:16:48.041  1453  1478 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:16:48.041  1020  1049 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-17 19:16:48.041  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 19:16:48.041  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:48.041  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:48.041  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:48.041  1453  1478 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 19:16:48.041  1453  1496 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:16:48.041  1020  1049 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-17 19:16:48.041  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 19:16:48.051  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:48.051  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:48.051  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:48.051  1453  1496 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 19:16:48.051  3213  3223 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 19:16:48.051  3213  3223 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:16:48.051  1020  1049 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-17 19:16:48.051  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 19:16:48.051  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:48.051  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:48.051  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:48.051  3213  3213 D BluetoothA2dp: Proxy object connected
08-17 19:16:48.051  3213  3213 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-17 19:16:48.051  4844  7719 D BluetoothPan: Binding service...
,08-17 19:16:48.051  1020  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-17 19:16:48.051  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-17 19:16:48.051  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:48.051  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:48.051  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:48.061  1020  1049 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:16:48.061  1020  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 19:16:48.061  1020  1049 E BluetoothHeadset: BluetoothHeadset service is binded
08-17 19:16:48.061  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-17 19:16:48.061  1020  1049 D BluetoothPan: Binding service...
08-17 19:16:48.061  1020  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-17 19:16:48.061  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-17 19:16:48.061  1453  1478 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:16:48.061  1453  1478 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-17 19:16:48.061  1020  1049 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:16:48.061  1020  1049 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:16:48.061  1020  1020 D BluetoothPan: BluetoothPAN Proxy object connected
,08-17 19:16:48.061  1465  1483 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:16:48.061  1465  1483 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:16:48.061  4844  4855 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-17 19:16:48.061  4844  4844 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 19:16:48.061  4844  4844 D PanProfile: Bluetooth service connected
,08-17 19:16:48.061  1020  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-17 19:16:48.061  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-17 19:16:48.061  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:48.061  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:48.061  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:48.071  4844  7719 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:16:48.071  1020  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 19:16:48.071  4844  4844 D BluetoothInputDevice: Proxy object connected
08-17 19:16:48.071  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-17 19:16:48.071  4844  4844 D HidProfile: Bluetooth service connected
,08-17 19:16:48.071  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:48.071  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:48.071  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:48.071  4844  7719 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 19:16:48.071  7190  7200 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-17 19:16:48.071  7190  7200 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-17 19:16:48.071  1662  1763 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:16:48.071  1662  1763 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:16:48.071  4844  4844 D HeadsetProfile: Bluetooth service connected
08-17 19:16:48.071  1477  1686 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:16:48.071  1477  1686 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:16:48.071  1180  3561 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:16:48.071  1180  3561 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:16:48.071  4844  4852 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 19:16:48.071  4844  4852 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:16:48.081  1020  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-17 19:16:48.081  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 19:16:48.081  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:48.081  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:48.081  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:48.081  4844  7719 D BluetoothPbap: onBluetoothStateChange: up=true
,08-17 19:16:48.081  4844  4844 D BluetoothA2dp: Proxy object connected
08-17 19:16:48.081  4844  4844 D A2dpProfile: Bluetooth service connected
,08-17 19:16:48.081  1020  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-17 19:16:48.081  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-17 19:16:48.081  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:48.081  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:48.081  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:48.081  3213  3222 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:16:48.081  3213  3222 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:16:48.081  1453  7324 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-17 19:16:48.081  1020  1049 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 19:16:48.081  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 19:16:48.091  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:48.091  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:48.091  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-17 19:16:48.091  4844  4844 D BluetoothPbap: Proxy object connected
08-17 19:16:48.091  4844  4844 D PbapServerProfile: Bluetooth service connected
,08-17 19:16:48.091  1453  7324 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 19:16:48.091  1020  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt,
08-17 19:16:48.091  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-17 19:16:48.091  1020  1020 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-17 19:16:48.091  1020  1020 I InputMethodManagerService: [BT Setting State] State =12
08-17 19:16:48.091  1020  1020 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-17 19:16:48.091  1453  1453 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@3fd179b0, true
,08-17 19:16:48.091  1453  1453 D BluetoothHeadset: registerMessageListener
,08-17 19:16:48.101  1180  1180 D BluetoothTile:  onBluetoothStateChange:
,08-17 19:16:48.101  1180  1180 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-17 19:16:48.101  1180  1180 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-17 19:16:48.101  1180  1180 D BluetoothTile:  getBluetoothState : 12
,08-17 19:16:48.101  1180  1772 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 19:16:48.101  1180  1772 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 19:16:48.101  1180  1772 D BluetoothTile:  handleUpdatestate:false name:null,
,08-17 19:16:48.101  1020  1747 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 19:16:48.111  1020  1508 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-17 19:16:48.111  1180  1180 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-17 19:16:48.111  1894  1894 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-17 19:16:48.111  4844  4844 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:48.111  3213  3223 D HeadsetService: registerMessageListener
,08-17 19:16:48.111  3213  7798 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-17 19:16:48.111  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:16:48.111  3213  3223 D HeadsetService: registerMessageListener
08-17 19:16:48.111  3213  7771 D HeadsetStateMachine: Disconnected process message: 70
08-17 19:16:48.111  3213  7771 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@c850707
,08-17 19:16:48.111  1453  1453 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-17 19:16:48.111  1453  1453 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-17 19:16:48.121  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:48.121  3213  7798 D BluetoothSocket: bindListen(): myUserId = 0,
08-17 19:16:48.121  3213  7798 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 19:16:48.121  1453  1453 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-17 19:16:48.121  4844  4844 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-17 19:16:48.121  1453  1453 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-17 19:16:48.121  4844  4844 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-17 19:16:48.121  1453  1453 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
08-17 19:16:48.121  4844  4844 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-17 19:16:48.121  4844  4844 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
08-17 19:16:48.121  3213  7798 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
08-17 19:16:48.121  3213  7798 D BluetoothSocket: bindListen(), new LocalSocket 
08-17 19:16:48.121  3213  7798 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-17 19:16:48.121  3213  7798 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@13325034
08-17 19:16:48.121  3213  7798 D BluetoothSocket: channel: 5
,08-17 19:16:48.131  3213  7771 D HeadsetStateMachine: Disconnected process message: 9
,08-17 19:16:48.131  3213  7771 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-17 19:16:48.131   283   670 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-17 19:16:48.131   283   670 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-17 19:16:48.131   283   670 V voice   : voice_set_parameters: exit with code(-2)
08-17 19:16:48.131   283   670 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-17 19:16:48.131   283   670 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-17 19:16:48.131   283   670 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-17 19:16:48.131   283   670 V audio_hw_primary: adev_set_parameters: exit
,08-17 19:16:48.131  3213  7771 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate,
08-17 19:16:48.131  4844  4844 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 19:16:48.131  1020  4295 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-17 19:16:48.131  1020  4295 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-17 19:16:48.131  1020  4295 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:48.131  1020  4295 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:48.131  1020  4295 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-17 19:16:48.141  1662  1662 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 19:16:48.151  4844  4844 D DockEventReceiver: finishStartingService: stopping service
,08-17 19:16:48.151  4844  4844 D BluetoothNotiBroadcastReceiver: onReceive
,08-17 19:16:48.151  1180  1180 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:48.151  1180  1180 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-17 19:16:48.161  3213  3213 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e7895
,08-17 19:16:48.161  3213  3213 D BtConfig.SecureMode: isSecureModeOn:false
,08-17 19:16:48.161  1020  1340 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:48.161  1020  1340 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-17 19:16:48.161  1020  1340 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:48.161  1020  1340 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:48.161  1020  1340 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:48.171  1020  1506 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-17 19:16:48.171  1020  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:48.171  1020  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:48.171  1020  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:48.171  1020  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:48.181  7801  7801 E Zygote  : MountEmulatedStorage()
08-17 19:16:48.181  7801  7801 E Zygote  : v2
,08-17 19:16:48.181  7801  7801 I libpersona: KNOX_SDCARD checking this for 10105
08-17 19:16:48.181  7801  7801 I libpersona: KNOX_SDCARD not a persona
,08-17 19:16:48.191  1020  1506 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7801 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-17 19:16:48.191  7801  7801 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-17 19:16:48.191  1020  1509 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy,
08-17 19:16:48.191  7801  7801 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 19:16:48.191  7801  7801 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-17 19:16:48.201  3213  7811 D BluetoothSocket: bindListen(): myUserId = 0
08-17 19:16:48.201  3213  7811 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 19:16:48.201  3213  7811 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[85]}
08-17 19:16:48.201  3213  7811 D BluetoothSocket: bindListen(), new LocalSocket 
08-17 19:16:48.201  3213  7811 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-17 19:16:48.201  3213  7811 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@bbe3ba0
,08-17 19:16:48.201  3213  7811 D BluetoothSocket: channel: 12
08-17 19:16:48.201  3213  7811 I BtOppRfcommListener: Accept thread started.
,08-17 19:16:48.211  7801  7801 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:48.211  7801  7801 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:48.311   257   523 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-17 19:16:48.311   257   523 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 19:16:48.311  7801  7822 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-17 19:16:48.321   257   523 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-17 19:16:48.321   257   523 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 19:16:48.321  7801  7822 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-17 19:16:48.531  7801  7801 D StrictMode: StrictMode policy violation; ~duration=207 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:16:48.531  7801  7801 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:16:48.531  7801  7801 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 19:16:48.531  7801  7801 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-17 19:16:48.531  7801  7801 D StrictMode: 	at java.io.File.exists(File.java:363)
08-17 19:16:48.531  7801  7801 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-17 19:16:48.531  7801  7801 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-17 19:16:48.531  7801  7801 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-17 19:16:48.531  7801  7801 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-17 19:16:48.531  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-17 19:16:48.531  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-17 19:16:48.531  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:16:48.531  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 19:16:48.531  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:16:48.531  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:16:48.531  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 19:16:48.531  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 19:16:48.531  7801  7801 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:16:48.531  7801  7801 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:16:48.531  7801  7801 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:16:48.531  7801  7801 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:16:48.531  7801  7801 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:16:48.531  7801  7801 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:16:48.531  7801  7801 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:16:48.531  7801  7801 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:16:48.531  7801  7801 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:16:48.531  7801  7801 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:16:48.531  7801  7801 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-17 19:16:48.541  7801  7801 D StrictMode: StrictMode policy violation; ~duration=206 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-17 19:16:48.541  7801  7801 D StrictMode: StrictMode policy violation; ~duration=205 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-17 19:16:48.541  7801  7801 D StrictMode: StrictMode policy violation; ~duration=203 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.q.e.b(PG:170)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-17 19:16:48.541  7801  7801 D StrictMode: StrictMode policy violation; ~duration=200 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.q.k.d(PG:583)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.q.e.b(PG:170)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-17 19:16:48.541  7801  7801 D StrictMode: StrictMode policy violation; ~duration=175 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-17 19:16:48.541  7801  7801 D StrictMode: ,	at java.io.File.exists(File.java:363)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206),
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:16:48.541  7801  7801 D StrictMode: StrictMode policy violation; ~duration=174 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at java.io.File.exists(File.java:363)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:16:48.541  7801  7801 D StrictMode: 	,at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:16:48.541  7801  7801 D StrictMode: StrictMode policy violation; ~duration=173 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:16:48.541  7801  7801 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:16:48.541  1020  1139 I ActivityManager: Killing 6969:com.sec.pcw.device/1000 (adj 15): empty #21
,08-17 19:16:48.611  7801  7826 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-17 19:16:48.641  1020  1494 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:16:48.641  1020  1494 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:48.641  1020  1494 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:48.641  1020  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-17 19:16:48.801   291   291 E SMD     : DCD OFF
,08-17 19:16:50.731  7190  7267 D BluetoothAdapter: disable()
,08-17 19:16:50.731  1020  1341 D SettingsProvider: name = bluetooth_on
,08-17 19:16:50.741  3213  3284 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-17 19:16:50.741  3213  3284 D BluetoothAdapterProperties: Setting state to 13
,08-17 19:16:50.741  3213  3284 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-17 19:16:50.751  3213  3284 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-17 19:16:50.751  3213  3284 D BluetoothAdapterService: updateAdapterState state is 13
,08-17 19:16:50.751  1020  1033 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:50.751  1020  1033 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-17 19:16:50.751  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:50.751  1020  1033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:50.751  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:50.751  3213  3284 D BluetoothAdapterService: Autoconnection is available 
08-17 19:16:50.751  3213  3284 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-17 19:16:50.751  3213  3284 D BluetoothAdapterService: terminating service from this receiver
08-17 19:16:50.751  1020  4295 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-17 19:16:50.751  3213  3213 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-17 19:16:50.751  1020  4295 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:50.751  1020  4295 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 19:16:50.751  3213  3213 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@33ea5359, channel: 19, state: LISTENING
08-17 19:16:50.751  3213  3213 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@33ea5359, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2075d946, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1000cb1emSocket: android.net.LocalSocket@56dcfff impl:android.net.LocalSocketImpl@235b71cc fd:FileDescriptor[80]
08-17 19:16:50.751  3213  3213 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@56dcfff impl:android.net.LocalSocketImpl@235b71cc fd:FileDescriptor[80]
,08-17 19:16:50.751  1020  4295 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:50.751  3213  3284 D BluetoothAdapterProperties: onBluetoothDisable()
08-17 19:16:50.751  3213  3284 D BluetoothAdapterProperties: mDiscovering is false
,08-17 19:16:50.761  1020  1525 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-17 19:16:50.761  4844  4844 D BluetoothPbap: Proxy object disconnected
08-17 19:16:50.761  4844  4844 D PbapServerProfile: Bluetooth service disconnected
,08-17 19:16:50.761  3213  3284 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-17 19:16:50.761  3213  3287 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-17 19:16:50.761  1020  1020 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-17 19:16:50.761  3213  3287 D BluetoothAdapterProperties: Scan Mode:20
08-17 19:16:50.761  1020  1020 I InputMethodManagerService: [BT Setting State] State =13
,08-17 19:16:50.771  1180  1180 D BluetoothTile:  onBluetoothStateChange:
,08-17 19:16:50.771  1180  1180 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-17 19:16:50.771  1180  1180 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-17 19:16:50.771  1180  1180 D BluetoothTile:  getBluetoothState : 13
,08-17 19:16:50.771  1180  1772 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 19:16:50.771  1180  1772 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 19:16:50.781  1180  1772 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-17 19:16:50.781  1894  1894 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-17 19:16:50.781  4844  4844 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:50.781  1020  1506 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 19:16:50.781  1020  1494 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-17 19:16:50.781  1180  1180 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-17 19:16:50.791  7190  7190 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 19:16:50.791  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:50.791  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:50.791  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:50.791  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:16:50.791  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:16:50.791  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:50.791  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:50.791  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:16:50.791  7190  7190 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:50.791  7190  7190 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:16:50.791  3213  3284 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-17 19:16:50.791  3213  3284 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-17 19:16:50.791  3213  3284 E bt-btif : cmd socket is not created
08-17 19:16:50.791  3213  7811 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-17 19:16:50.791  3213  3284 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-17 19:16:50.791  3213  3288 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,08-17 19:16:50.791  7190  7190 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:50.791  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:50.791  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:50.791  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:50.791  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:16:50.791  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:16:50.791  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:50.791  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:50.791  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 19:16:50.791  4844  4844 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 19:16:50.801  1020  1525 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-17 19:16:50.801  1020  1525 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-17 19:16:50.801  1020  1525 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:50.801  7190  7190 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:50.801  7190  7190 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:16:50.801  1020  1525 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:50.801  1020  1525 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-17 19:16:50.801  3213  3288 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 19:16:50.801  3213  3288 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 19:16:50.801  3213  3288 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 19:16:50.801  3213  3288 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 19:16:50.801  3213  3288 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 19:16:50.801  3213  3288 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-17 19:16:50.801  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:50.801  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:50.811  1662  1662 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-17 19:16:50.811  3213  3213 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@31ea7b2a, channel: 5, state: LISTENING
08-17 19:16:50.811  3213  3213 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@31ea7b2a, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@13325034, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1ed96d1bmSocket: android.net.LocalSocket@1fb3deb8 impl:android.net.LocalSocketImpl@7c21491 fd:FileDescriptor[82]
08-17 19:16:50.811  3213  3213 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1fb3deb8 impl:android.net.LocalSocketImpl@7c21491 fd:FileDescriptor[82]
08-17 19:16:50.811  3213  3213 I BtOppRfcommListener: stopping Accept Thread
08-17 19:16:50.811  3213  3213 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@290d1ff6, channel: 12, state: LISTENING
08-17 19:16:50.811  3213  3213 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@290d1ff6, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@bbe3ba0, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2897bff7mSocket: android.net.LocalSocket@35242e64 impl:android.net.LocalSocketImpl@2be268cd fd:FileDescriptor[85]
08-17 19:16:50.811  3213  3213 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@35242e64 impl:android.net.LocalSocketImpl@2be268cd fd:FileDescriptor[85]
,08-17 19:16:50.811  4844  4844 D DockEventReceiver: finishStartingService: stopping service
08-17 19:16:50.811  3213  7811 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-17 19:16:50.821  4844  4844 D BluetoothNotiBroadcastReceiver: onReceive
,08-17 19:16:50.821  3213  3213 V BluetoothOppManager: cleanUp...
,08-17 19:16:50.821  1180  1180 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:50.821  1180  1180 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-17 19:16:50.931  1020  3827 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-17 19:16:50.941  1020  3827 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4288, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-17 19:16:50.941  1020  3827 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-17 19:16:50.941  1020  3827 D BatteryService: stay LED for charging
08-17 19:16:50.941  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-17 19:16:50.941  1020  1020 I MotionRecognitionService: Plugged
,08-17 19:16:50.941  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,08-17 19:16:50.941  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-17 19:16:50.941  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-17 19:16:50.941  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-17 19:16:50.941  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-17 19:16:50.951  3213  3213 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-17 19:16:50.951  3213  7771 D HeadsetStateMachine: Disconnected process message: 10
,08-17 19:16:50.961  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-17 19:16:50.971  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-17 19:16:50.971  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-17 19:16:50.991  3213  3284 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-17 19:16:50.991  3213  3284 D BtConfig.SecureMode: isSecureModeOn:false
08-17 19:16:50.991  3213  3284 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-17 19:16:50.991  3213  3284 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
08-17 19:16:50.991  3213  3284 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
08-17 19:16:50.991  3213  3284 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-17 19:16:50.991  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-17 19:16:50.991  1020  4295 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:50.991  3213  3284 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-17 19:16:50.991  1020  4295 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-17 19:16:51.001  1020  4295 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:51.001  1020  4295 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:51.001  1020  4295 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:51.001  3213  3284 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,08-17 19:16:51.001  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-17 19:16:51.001  3213  3284 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-17 19:16:51.001  1020  1525 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:16:51.001  1020  1525 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-17 19:16:51.001  1020  1525 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:51.001  1020  1525 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:51.001  1020  1525 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:51.001  3213  3284 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,08-17 19:16:51.001  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-17 19:16:51.001  3213  3284 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService,
08-17 19:16:51.001  1020  1494 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:51.001  3213  3213 D HeadsetService: Received stop request...Stopping profile...
,08-17 19:16:51.001  1020  1494 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-17 19:16:51.001  3213  3213 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e7895
08-17 19:16:51.001  1020  1494 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:51.001  1020  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 19:16:51.001  1020  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
08-17 19:16:51.011  3213  3284 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-17 19:16:51.011  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-17 19:16:51.011  3213  3284 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-17 19:16:51.011  1020  1266 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:51.011  1020  1020 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-17 19:16:51.011  1020  1266 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-17 19:16:51.011  4844  4844 D HeadsetProfile: Bluetooth service disconnected
,08-17 19:16:51.011  1020  1266 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:51.011  1020  1266 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:51.011  1020  1266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:51.011  3213  3213 D A2dpService: Received stop request...Stopping profile...
,08-17 19:16:51.011  3213  7782 D A2dpStateMachine: Exit Disconnected: -1
,08-17 19:16:51.011  3213  3284 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,08-17 19:16:51.021  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-17 19:16:51.021  3213  3284 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-17 19:16:51.021  1020  4295 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:51.021  1020  4295 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-17 19:16:51.021  1020  4295 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:51.021  1020  4295 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:51.021  1020  4295 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 19:16:51.021  3213  3213 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e7895
,08-17 19:16:51.021  3213  3284 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,08-17 19:16:51.021  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 19:16:51.021  3213  3284 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-17 19:16:51.021  1020  1020 D BluetoothA2dp: Proxy object disconnected
08-17 19:16:51.021  1020  1020 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-17 19:16:51.021  1020  1033 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:51.021  1020  1033 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-17 19:16:51.031  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:51.031  4844  4844 D BluetoothA2dp: Proxy object disconnected
08-17 19:16:51.031  4844  4844 D A2dpProfile: Bluetooth service disconnected
,08-17 19:16:51.031  1020  1033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:51.031  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:51.031  3213  3284 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-17 19:16:51.031  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-17 19:16:51.031  3213  3284 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-17 19:16:51.031  1020  1341 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:51.031  1020  1341 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-17 19:16:51.031  1020  1341 W ActivityManager: userId = 0, bbcId = -10000,
08-17 19:16:51.031  1020  1341 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 19:16:51.031  1020  1341 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:51.031  3213  3284 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:16:51.031  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:16:51.031  3213  3284 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:16:51.031  3213  3284 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:16:51.031  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:16:51.031  3213  3284 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:16:51.031  3213  3284 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-17 19:16:51.031  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-17 19:16:51.031  3213  3284 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-17 19:16:51.031  3213  3284 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-17 19:16:51.031  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-17 19:16:51.031  3213  3284 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-17 19:16:51.031  3213  3284 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-17 19:16:51.031  3213  3213 E BluetoothAdapterService(5142677): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-17 19:16:51.031  3213  3213 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-17 19:16:51.031  3213  3213 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-17 19:16:51.031  3213  3213 D HidService: Received stop request...Stopping profile...
,08-17 19:16:51.031  3213  3213 D HidService: Stopping Bluetooth HidService
08-17 19:16:51.031  3213  3213 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-17 19:16:51.041  3213  3213 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-17 19:16:51.041  3213  3213 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-17 19:16:51.041  3213  3213 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e7895
,08-17 19:16:51.041  4844  4844 D BluetoothInputDevice: Proxy object disconnected
,08-17 19:16:51.041  3213  3213 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-17 19:16:51.041  3213  3213 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-17 19:16:51.041  3213  3213 D HealthService: Received stop request...Stopping profile...
08-17 19:16:51.041  4844  4844 D HidProfile: Bluetooth service disconnected
08-17 19:16:51.041  3213  3213 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e7895
,08-17 19:16:51.041  3213  3213 E BluetoothAdapterService(5142677): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,08-17 19:16:51.041  3213  3213 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-17 19:16:51.041  3213  3213 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-17 19:16:51.041  3213  3213 D PanService: Received stop request...Stopping profile...
08-17 19:16:51.041  3213  3213 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e7895
,08-17 19:16:51.051  1020  1020 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-17 19:16:51.051  3213  3213 D BluetoothA2dp: Proxy object disconnected
,08-17 19:16:51.051  3213  3213 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-17 19:16:51.051  3213  7783 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-17 19:16:51.051  3213  3213 I GKI_LINUX: GKI_exit_task 2 done
08-17 19:16:51.051  3213  3213 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-17 19:16:51.051  3213  3213 D BluetoothMapService: Received stop request...Stopping profile...
,08-17 19:16:51.051  4844  4844 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-17 19:16:51.051  4844  4844 D PanProfile: Bluetooth service disconnected
,08-17 19:16:51.051  3213  3213 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e7895
,08-17 19:16:51.061  3213  3213 D SapService: Received stop request...Stopping profile...
,08-17 19:16:51.061  3213  3213 D SapService: Stopping Bluetooth SapService
,08-17 19:16:51.061  3213  3213 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e7895
,08-17 19:16:51.061  3213  3213 E BluetoothAdapterService(5142677): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-17 19:16:51.061  3213  3213 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-17 19:16:51.061  3213  3213 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 19:16:51.061  3213  3213 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-17 19:16:51.061  3213  3213 E BluetoothAdapterService(5142677): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-17 19:16:51.061  3213  3213 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-17 19:16:51.061  3213  3213 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 19:16:51.061  3213  3213 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-17 19:16:51.061  3213  3213 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-17 19:16:51.061  3213  3213 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-17 19:16:51.061  3213  3213 E BluetoothAdapterService(5142677): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-17 19:16:51.061  3213  3213 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-17 19:16:51.061  3213  3213 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 19:16:51.061  3213  3213 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-17 19:16:51.061  3213  3213 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-17 19:16:51.061  3213  3213 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-17 19:16:51.061  4844  4844 D BluetoothMap: Proxy object disconnected
08-17 19:16:51.061  3213  3213 E BluetoothAdapterService(5142677): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-17 19:16:51.061  3213  3213 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-17 19:16:51.061  3213  3213 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-17 19:16:51.061  3213  3213 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-17 19:16:51.061  3213  3213 E BluetoothAdapterService(5142677): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-17 19:16:51.061  3213  3213 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-17 19:16:51.071  3213  3213 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-17 19:16:51.071  3213  3213 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-17 19:16:51.071  4844  4844 D MapProfile: Bluetooth service disconnected
08-17 19:16:51.071  4844  4844 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-17 19:16:51.071  4844  4844 D SapProfile: Bluetooth service disconnected
,08-17 19:16:51.071  3213  3284 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,08-17 19:16:51.071  3213  3284 D BluetoothAdapterProperties: Setting state to 10
,08-17 19:16:51.071  3213  3284 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
,08-17 19:16:51.071  3213  3284 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-17 19:16:51.071  3213  3284 D BluetoothAdapterService: updateAdapterState state is 10
,08-17 19:16:51.071  3213  3284 D BluetoothAdapterService: Autoconnection is available 
,08-17 19:16:51.071  3213  3284 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
,08-17 19:16:51.071  3213  3284 I BluetoothAdapterState: Entering OffState
,08-17 19:16:51.071  4844  4852 D Bluetoothsap: onBluetoothStateChange: up=false
,08-17 19:16:51.071  4844  4852 D Bluetoothsap: Unbinding service...
,08-17 19:16:51.081  1020  1049 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-17 19:16:51.081  4844  4855 D BluetoothMap: onBluetoothStateChange: up=false
,08-17 19:16:51.081  1764  2306 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 19:16:51.081  1764  2306 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:16:51.081  4844  7719 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 19:16:51.081  4844  7719 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:16:51.081  7801  7815 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 19:16:51.081  7801  7815 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:16:51.081  3213  3223 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-17 19:16:51.081  1453  1478 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 19:16:51.091  1453  1478 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:16:51.091  1020  1049 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 19:16:51.091  1020  1049 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:16:51.091  1465  1476 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 19:16:51.091  1465  1476 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:16:51.091  4844  4855 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-17 19:16:51.091  7190  7200 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 19:16:51.091  7190  7200 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:16:51.091  7190  7200 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-17 19:16:51.091  7190  7200 D BluetoothLeAdvertiser: Exit stop advertising
,08-17 19:16:51.091  7190  7200 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-17 19:16:51.091  7190  7200 D BluetoothLeScanner: Exiting stopAllScan
,08-17 19:16:51.091  1662  4174 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 19:16:51.091  1662  4174 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:16:51.091  1477  1686 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 19:16:51.091  1477  1686 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:16:51.091  1180  1926 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 19:16:51.091  1180  1926 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:16:51.101  4844  4852 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-17 19:16:51.101  4844  4855 D BluetoothPbap: onBluetoothStateChange: up=false
,08-17 19:16:51.101  3213  3362 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 19:16:51.101  3213  3362 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:16:51.101  1020  1020 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:51.101  1020  1020 I InputMethodManagerService: [BT Setting State] State =10
08-17 19:16:51.101  1020  1020 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-17 19:16:51.111  1180  1180 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-17 19:16:51.111  1180  1180 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:51.111  1180  1180 D BluetoothTile:  getBluetoothState : 10
,08-17 19:16:51.111  1894  1894 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-17 19:16:51.111  4844  4844 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:51.121  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:51.121  1020  1340 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 19:16:51.121  1020  1341 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-17 19:16:51.121  1180  1180 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 19:16:51.121  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:51.121  4844  4844 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 19:16:51.121  1020  1525 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-17 19:16:51.121  1020  1525 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-17 19:16:51.121  1020  1525 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:51.121  1020  1525 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 19:16:51.131  1020  1525 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-17 19:16:51.131  1662  1662 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 19:16:51.141  1180  1180 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-17 19:16:51.141  4844  4844 D DockEventReceiver: finishStartingService: stopping service
,08-17 19:16:51.141  4844  4844 D BluetoothNotiBroadcastReceiver: onReceive
,08-17 19:16:51.151  1180  1180 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:51.151  1180  1180 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-17 19:16:51.811   291   291 E SMD     : DCD OFF,
,08-17 19:16:52.511  1020  1052 I PowerManagerService: [PWL] Off : 75s ago,
08-17 19:16:52.511  1020  1052 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
08-17 19:16:52.511  1020  1052 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1,
08-17 19:16:52.511  1020  1052 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1020, ws=null) (elapsedTime=13571)
,08-17 19:16:52.791  1020  1309 E Watchdog: !@Sync 4
,08-17 19:16:53.751  7190  7267 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 19:16:53.761  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:53.781   324   324 I ServiceManager: Waiting for service AtCmdFwd...,
,08-17 19:16:54.781   324   324 I ServiceManager: Waiting for service AtCmdFwd...,
,08-17 19:16:54.811   291   291 E SMD     : DCD OFF
,08-17 19:16:55.781   324   324 I ServiceManager: Waiting for service AtCmdFwd...,
,08-17 19:16:56.761  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 19:16:56.761  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@17b377c9 added. We now have 6 listener(s),
08-17 19:16:56.761  7190  7267 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
,08-17 19:16:56.761  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 19:16:56.761  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@345f6ece added. We now have 7 listener(s)
,08-17 19:16:56.761  7190  7267 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 19:16:56.771  7190  7267 I System.out: IsBluetoothEnabled
,08-17 19:16:56.771  7190  7267 D BluetoothAdapter: disable()
,08-17 19:16:56.771  1020  1509 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-17 19:16:56.781  7190  7267 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:56.781  7190  7267 D BluetoothAdapter: enable()
,08-17 19:16:56.781  1020  1525 W ActivityManager: Permission Denial: getCurrentUser() from pid=7190, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-17 19:16:56.781  1020  1525 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-17 19:16:56.781  1020  1525 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7190, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-17 19:16:56.781  1020  1525 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-17 19:16:56.781  1020  1525 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-17 19:16:56.781  1020  1525 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-17 19:16:56.781  1020  1525 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-17 19:16:56.781  1020  1525 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-17 19:16:56.781  1020  1525 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-17 19:16:56.781  1020  1525 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 19:16:56.781   324   324 I ServiceManager: Waiting for service AtCmdFwd...,
,08-17 19:16:56.791  1020  1525 D SettingsProvider: name = bluetooth_on,
,08-17 19:16:56.791  1020  1049 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-17 19:16:56.791  1020  1049 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 19:16:56.801  1020  1049 D SecContentProvider: uri = 3 selection = isBluetoothEnabled,
,08-17 19:16:56.801  3213  3284 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
08-17 19:16:56.811  1020  4295 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:16:56.801  3213  3284 D BluetoothAdapterProperties: Setting state to 11
08-17 19:16:56.811  1020  4295 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-17 19:16:56.801  3213  3284 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-17 19:16:56.801  3213  3284 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-17 19:16:56.801  3213  3284 D BluetoothAdapterService: updateAdapterState state is 11
08-17 19:16:56.801  3213  3284 D BluetoothAdapterService: Autoconnection is available ,
08-17 19:16:56.801  3213  3284 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
08-17 19:16:56.801  3213  3284 D BtConfig.SecureMode: isSecureModeOn:false
08-17 19:16:56.801  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-17 19:16:56.801  3213  3284 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
,08-17 19:16:56.801  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-17 19:16:56.801  3213  3284 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
08-17 19:16:56.801  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-17 19:16:56.801  3213  3284 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10,
,08-17 19:16:56.801  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-17 19:16:56.801  3213  3284 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
08-17 19:16:56.801  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-17 19:16:56.801  3213  3284 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
08-17 19:16:56.801  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-17 19:16:56.801  3213  3284 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
08-17 19:16:56.801  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 19:16:56.801  3213  3284 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
08-17 19:16:56.801  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-17 19:16:56.801  3213  3284 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
08-17 19:16:56.801  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:16:56.801  3213  3284 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
,08-17 19:16:56.801  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:16:56.801  3213  3284 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:16:56.801  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-17 19:16:56.801  3213  3284 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-17 19:16:56.801  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-17 19:16:56.801  3213  3284 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-17 19:16:56.801  3213  3284 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
08-17 19:16:56.801  3213  3284 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-17 19:16:56.801  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-17 19:16:56.801  3213  3284 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-17 19:16:56.811  1020  4295 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:56.811  1020  4295 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:56.811  1020  4295 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 19:16:56.811  3213  3284 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-17 19:16:56.811  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-17 19:16:56.811  3213  3284 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-17 19:16:56.811  3213  3213 D HeadsetService: Received start request. Starting profile...
08-17 19:16:56.811  3213  3213 D HeadsetService: start()
08-17 19:16:56.811  3213  3213 D HeadsetStateMachine: make
,08-17 19:16:56.811  3213  3213 E HeadsetStateMachine: # of Max HF connection is 2
,08-17 19:16:56.821  1020  1033 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:16:56.821  1020  1033 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 19:16:56.821  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:56.821  1020  1033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 19:16:56.821  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:56.821  3213  3284 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService,
08-17 19:16:56.821  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-17 19:16:56.821  3213  3284 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-17 19:16:56.831  1020  1020 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-17 19:16:56.831  1020  1020 I InputMethodManagerService: [BT Setting State] State =11
,08-17 19:16:56.831  1180  1180 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-17 19:16:56.831  1180  1180 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-17 19:16:56.831  1180  1180 D BluetoothTile:  getBluetoothState : 11
08-17 19:16:56.841  1894  1894 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-17 19:16:56.841  4844  4844 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:56.841  1020  1494 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-17 19:16:56.841  1180  1772 D BluetoothTile:  handleUpdatestate:false name:null
08-17 19:16:56.841  1180  1772 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-17 19:16:56.851  1020  1494 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-17 19:16:56.851  1020  1494 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:56.851  1020  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:56.851  1020  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-17 19:16:56.851  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:16:56.851  1020  3827 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:56.851  1020  3827 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-17 19:16:56.851  1020  3827 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:56.851  1020  3827 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:56.851  1020  3827 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:56.851  1020  1506 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 19:16:56.851  3213  3284 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService,
08-17 19:16:56.851  1020  1341 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-17 19:16:56.851  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-17 19:16:56.851  3213  3284 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-17 19:16:56.851  1180  1180 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-17 19:16:56.861  1662  1662 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 19:16:56.861  1020  1266 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-17 19:16:56.861  1020  1266 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-17 19:16:56.861  1020  1266 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:56.861  1020  1266 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:56.861  1020  1266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-17 19:16:56.861  1020  1033 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:16:56.861  1020  1033 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-17 19:16:56.861  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:56.861  1020  1033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:56.861  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:56.871  3213  3284 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-17 19:16:56.871  3213  3213 I bluedroid: get_profile_interface handsfree
,08-17 19:16:56.871  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-17 19:16:56.871  3213  3284 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-17 19:16:56.871  1020  1525 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:56.871  1020  1525 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-17 19:16:56.871  1020  1525 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:56.871  1020  1525 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:56.871  1020  1525 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:56.871  3213  3284 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-17 19:16:56.871  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 19:16:56.871  3213  3284 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-17 19:16:56.881  1020  1494 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:56.881  1020  1494 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-17 19:16:56.881  4844  4844 D BluetoothNotiBroadcastReceiver: onReceive
08-17 19:16:56.881  1020  1494 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:56.881  1020  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:56.881  1020  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:56.881  3213  3213 E DualScoManager: Dual Sco Manager already instantiated
08-17 19:16:56.881  3213  3213 I DualScoManager: Set HeadsetServiceHelper
08-17 19:16:56.881  3213  3213 D BluetoothAtMessage: createCMTIContentObservers
,08-17 19:16:56.881  1020  1139 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,08-17 19:16:56.881  1020  1139 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:56.881  1020  1139 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:56.881  1020  1139 D SettingsProvider: selectionArgs: false
08-17 19:16:56.881  1020  1139 D SettingsProvider: selectionArgs: 1002
08-17 19:16:56.881  1020  1139 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:56.881  1020  1139 D SettingsProvider: ret = -1
,08-17 19:16:56.881  3213  3284 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-17 19:16:56.881  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-17 19:16:56.881  3213  3284 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-17 19:16:56.881  3213  7847 D HeadsetStateMachine: Enter Disconnected: -2
,08-17 19:16:56.891  1180  1180 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:56.891  1180  1180 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-17 19:16:56.891  1020  1506 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:16:56.891  1020  1506 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-17 19:16:56.891  3213  3213 D HeadsetService: mStartError = false
08-17 19:16:56.891  1020  1506 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:56.891  3213  7847 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-17 19:16:56.891  1020  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:56.891  3213  3213 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e7895
08-17 19:16:56.891  1020  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 19:16:56.891  3213  7847 D HeadsetStateMachine: map size, before remove : 0
08-17 19:16:56.891  3213  7847 D HeadsetStateMachine: map size, after remove: 0
,08-17 19:16:56.891  3213  3284 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-17 19:16:56.901  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-17 19:16:56.901  3213  3284 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:16:56.901  3213  3284 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
,08-17 19:16:56.901  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:16:56.901  3213  3284 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:16:56.901  3213  3284 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
,08-17 19:16:56.901  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-17 19:16:56.901  3213  3284 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,08-17 19:16:56.901  3213  3213 D A2dpService: Received start request. Starting profile...
08-17 19:16:56.901  3213  3284 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-17 19:16:56.901  3213  3284 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-17 19:16:56.901  3213  3284 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-17 19:16:56.901  3213  3284 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-17 19:16:56.901  3213  3213 D A2dpService: start()
08-17 19:16:56.901  3213  3213 I bluedroid: get_profile_interface avrcp
,08-17 19:16:56.901  3213  3213 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-17 19:16:56.901  3213  3213 D Avrcp   : Initialize Media Controller
08-17 19:16:56.901  3213  3213 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-17 19:16:56.901  3213  3213 E Avrcp   : getActiveSessions
,08-17 19:16:56.901  3213  3213 D Avrcp   : pick active media Controller
08-17 19:16:56.901  3213  3213 D Avrcp   : Get the active Media Controller 
,08-17 19:16:56.911  3213  3213 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-17 19:16:56.911  3213  7848 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-17 19:16:56.911  3213  3213 D A2dpStateMachine: make
,08-17 19:16:56.921  3213  3213 I bluedroid: get_profile_interface a2dp
,08-17 19:16:56.921  3213  7850 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-17 19:16:56.921  3213  3213 E bt-btif : warning : media task started media_task_refcnt 1 
08-17 19:16:56.921  3213  3213 D A2dpService: mStartError = false
08-17 19:16:56.921  3213  3213 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e7895
08-17 19:16:56.921  3213  3213 D HeadsetStateMachine: Try to query the phonestate on bind
,08-17 19:16:56.921  3213  7849 D A2dpStateMachine: Enter Disconnected: -2
,08-17 19:16:56.921  1453  1478 I Telecom : BluetoothPhoneService: queryPhoneState
,08-17 19:16:56.921  1453  1453 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
08-17 19:16:56.921  1453  1453 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-17 19:16:56.921  1453  1478 I Telecom : BluetoothPhoneService: Result of Message : true
08-17 19:16:56.921  3213  3213 D HidService: Received start request. Starting profile...
,08-17 19:16:56.921  3213  3213 D HidService: start()
08-17 19:16:56.921  3213  3213 I bluedroid: get_profile_interface hidhost
08-17 19:16:56.921  3213  3213 D HidService: setHidService(): set to: null
08-17 19:16:56.921  3213  3213 D HidService: mStartError = false
08-17 19:16:56.921  3213  3213 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e7895
,08-17 19:16:56.921  3213  3213 D HeadsetStateMachine: Proxy object connected
,08-17 19:16:56.921  3213  3213 D HealthService: Received start request. Starting profile...
08-17 19:16:56.921  3213  3213 D HealthService: start()
,08-17 19:16:56.931  3213  3213 I bluedroid: get_profile_interface health
,08-17 19:16:56.931  3213  3213 D HealthService: mStartError = false
08-17 19:16:56.931  3213  3213 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e7895
08-17 19:16:56.931  3213  3213 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-17 19:16:56.931  3213  7847 D HeadsetStateMachine: Disconnected process message: 11
08-17 19:16:56.931  3213  3213 D PanService: Received start request. Starting profile...
08-17 19:16:56.931  3213  3213 D PanService: start()
08-17 19:16:56.931  3213  3213 D BluetoothPanServiceJni: initializeNative(L110): pan
08-17 19:16:56.931  3213  3213 I bluedroid: get_profile_interface pan
08-17 19:16:56.931  3213  3213 D PanService: mStartError = false
08-17 19:16:56.931  3213  3213 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e7895
08-17 19:16:56.931  3213  3213 D HeadsetPhoneState: sendDeviceDataStateChanged
08-17 19:16:56.931  3213  3213 D HeadsetPhoneState: Signal level : previous=0 curr=4
08-17 19:16:56.931  3213  7847 D HeadsetStateMachine: Disconnected process message: 18
,08-17 19:16:56.931  3213  3213 D BluetoothMapService: Received start request. Starting profile...
08-17 19:16:56.931  3213  3213 D BluetoothMapService: start()
,08-17 19:16:56.931  3213  7848 D BluetoothMediaBrowser: no now playing list
08-17 19:16:56.931  3213  7848 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-17 19:16:56.931  3213  3213 D BluetoothMapService: mStartError = false
08-17 19:16:56.931  3213  3213 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e7895
,08-17 19:16:56.931  3213  3213 E BluetoothAdapterService(5142677): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,08-17 19:16:56.931  3213  3213 D SapService: Received start request. Starting profile...
08-17 19:16:56.931  3213  3213 D SapService: start()
08-17 19:16:56.931  3213  3213 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-17 19:16:56.931  3213  3213 I bluedroid: get_profile_interface sap
08-17 19:16:56.931  3213  3213 D SapService: mStartError = false
08-17 19:16:56.931  3213  3213 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e7895
08-17 19:16:56.931  3213  3213 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-17 19:16:56.931  3213  3213 E BluetoothAdapterService(5142677): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-17 19:16:56.931  3213  3213 E BluetoothAdapterService(5142677): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-17 19:16:56.931  3213  3213 E BluetoothAdapterService(5142677): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-17 19:16:56.931  3213  3213 E BluetoothAdapterService(5142677): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-17 19:16:56.931  3213  7847 D HeadsetStateMachine: Disconnected process message: 10
,08-17 19:16:56.931  3213  7847 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-17 19:16:56.931  3213  7847 D HeadsetStateMachine: Disconnected process message: 11
,08-17 19:16:56.951  3213  3213 E BluetoothAdapterService(5142677): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-17 19:16:56.951  3213  3213 E BluetoothAdapterService(5142677): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-17 19:16:56.951  3213  3284 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-17 19:16:56.951  3213  3284 I bluedroid: enable
,08-17 19:16:56.961  3213  3287 E bt-btif : Calling BTA_HhEnable
,08-17 19:16:56.961  3213  3287 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-17 19:16:56.961  3213  3287 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-17 19:16:56.961  3213  3287 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
08-17 19:16:56.961  3213  3287 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
08-17 19:16:56.961  3213  3287 E BluetoothServiceJni: populateRssiValuesNative
08-17 19:16:56.961  3213  3287 I bluedroid: getModelRssiValues
08-17 19:16:56.961  3213  3287 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-17 19:16:56.961  3213  3287 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-17 19:16:56.961  1020  1020 D SettingsProvider: name = bluetooth_name
,08-17 19:16:56.961  3213  3287 D BluetoothAdapterProperties: Name is: Galaxy A3
,08-17 19:16:56.961  3213  3287 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-17 19:16:56.961  3213  3287 D BluetoothAdapterProperties: Scan Mode:20
08-17 19:16:56.961  3213  3287 D BluetoothAdapterProperties: Discoverable Timeout:120
08-17 19:16:56.961  3213  3287 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
08-17 19:16:56.961  3213  3287 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
08-17 19:16:56.961  3213  3287 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,08-17 19:16:56.961  3213  3287 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-17 19:16:56.961  3213  3287 E bt-btif : JVenable fails
,08-17 19:16:56.961  3213  3287 D bte_conf: Device ID record 1 : primary
08-17 19:16:56.961  3213  3287 D bte_conf:   vendorId            = 0075
08-17 19:16:56.961  3213  3287 D bte_conf:   vendorIdSource      = 0001
08-17 19:16:56.961  3213  3287 D bte_conf:   product             = 0100
08-17 19:16:56.961  3213  3287 D bte_conf:   version             = 0200
08-17 19:16:56.961  3213  3287 D bte_conf:   clientExecutableURL = 
08-17 19:16:56.961  3213  3287 D bte_conf:   serviceDescription  = 
08-17 19:16:56.961  3213  3287 D bte_conf:   documentationURL    = 
08-17 19:16:56.961  3213  3287 D bte_conf: bte_load_did_conf no section named DID2.
,08-17 19:16:56.971  3213  3287 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-17 19:16:56.971  3213  3287 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-17 19:16:56.971  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:56.971  3213  3284 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-17 19:16:56.971  3213  3284 D BluetoothAdapterProperties: ScanMode =  20
08-17 19:16:56.971  3213  3284 D BluetoothAdapterProperties: State =  11
,08-17 19:16:56.971  1020  1506 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-17 19:16:56.971  3213  3284 D BluetoothAdapterProperties: Setting state to 12
,08-17 19:16:56.971  3213  3284 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-17 19:16:56.971  3213  3287 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-17 19:16:56.971  3213  3287 D BluetoothAdapterProperties: Scan Mode:21
08-17 19:16:56.971  3213  3287 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-17 19:16:56.971  1020  1341 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-17 19:16:56.971  1020  1341 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:56.971  1020  1341 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:56.971  1020  1341 D SettingsProvider: selectionArgs: false
08-17 19:16:56.971  1020  1341 D SettingsProvider: selectionArgs: 1002
08-17 19:16:56.971  1020  1341 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:56.971  1020  1341 D SettingsProvider: ret = -1
,08-17 19:16:56.971  3213  3284 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-17 19:16:56.971  3213  3284 D BluetoothAdapterService: updateAdapterState state is 12
,08-17 19:16:56.971  1020  1341 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:16:56.981  1020  1341 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-17 19:16:56.981  1020  1341 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:56.981  1020  1341 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:56.981  1020  1341 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:56.981  4844  7719 D Bluetoothsap: onBluetoothStateChange: up=true
,08-17 19:16:56.981  4844  7719 D Bluetoothsap: Binding service...
,08-17 19:16:56.981  3213  3284 D BluetoothAdapterService: Autoconnection is available 
08-17 19:16:56.981  3213  3284 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
,08-17 19:16:56.981  3213  3284 D BluetoothAdapterService: starting service from this receiver
,08-17 19:16:56.981  1020  1506 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:56.981  1020  1506 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-17 19:16:56.981  3213  3213 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
08-17 19:16:56.981  3213  3213 I BluetoothPbapService: Handler(): got msg=1
,08-17 19:16:56.981  1020  1506 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:56.981  1020  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:56.981  1020  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:56.991  3213  3284 I BluetoothAdapterState: Entering On State from state = 11
,08-17 19:16:56.991  1020  4295 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-17 19:16:56.991  4844  7719 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-17 19:16:56.991  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:56.991  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:56.991  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:56.991  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:16:56.991  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:56.991  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:56.991  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:56.991  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:16:57.001  3213  7855 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-17 19:16:57.001  3213  7855 D BluetoothSocket: bindListen(): myUserId = 0
,08-17 19:16:57.001  7190  7190 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:16:57.001  3213  7855 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 19:16:57.001  3213  7855 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
,08-17 19:16:57.001  3213  7855 D BluetoothSocket: bindListen(), new LocalSocket 
08-17 19:16:57.001  3213  7855 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-17 19:16:57.001  3213  7855 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@20c55ba9
,08-17 19:16:57.001  3213  7855 D BluetoothSocket: channel: 19
08-17 19:16:57.001  3213  7855 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-17 19:16:57.131  1020  1049 I art     : Explicit concurrent mark sweep GC freed 49641(2MB) AllocSpace objects, 6(97KB) LOS objects, 33% free, 22MB/34MB, paused 2.379ms total 140.938ms
08-17 19:16:57.131  1020  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-17 19:16:57.131  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-17 19:16:57.131  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:57.131  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:57.131  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:57.131  4844  7719 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-17 19:16:57.131  1020  1049 D BluetoothA2dp: onBluetoothStateChange: up=true
08-17 19:16:57.131  1020  1049 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:16:57.131  1020  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-17 19:16:57.131  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 19:16:57.141  4844  4852 D BluetoothMap: onBluetoothStateChange: up=true
,08-17 19:16:57.141  1020  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-17 19:16:57.141  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-17 19:16:57.141  4844  4844 D Bluetoothsap: BluetoothSAP Proxy object connected
08-17 19:16:57.141  4844  4844 D SapProfile: Bluetooth service connected
08-17 19:16:57.141  4844  4844 D Bluetoothsap: getConnectedDevices()
,08-17 19:16:57.141  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:57.141  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:57.141  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:57.151  1764  2306 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:16:57.151  1020  1020 D BluetoothA2dp: Proxy object connected
08-17 19:16:57.151  1764  2306 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:16:57.151  4844  4852 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:16:57.151  4844  4852 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:16:57.151  4844  4844 D BluetoothMap: Proxy object connected
08-17 19:16:57.151  4844  4844 D MapProfile: Bluetooth service connected
08-17 19:16:57.151  4844  4844 D BluetoothMap: getConnectedDevices()
08-17 19:16:57.151  1477  1986 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:16:57.151  1020  1049 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 19:16:57.151  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 19:16:57.151  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:57.151  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:57.151  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:57.151  1477  1986 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 19:16:57.151  1453  7324 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0,
08-17 19:16:57.151  1020  1049 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset,
08-17 19:16:57.151  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-17 19:16:57.161  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:57.161  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:57.161  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-17 19:16:57.161  1453  7324 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 19:16:57.161  1453  1496 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:16:57.161  1020  1049 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-17 19:16:57.161  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 19:16:57.161  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:57.161  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:57.161  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:57.161  1453  1496 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 19:16:57.161  7801  7818 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-17 19:16:57.161  7801  7818 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:16:57.161  3213  3223 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 19:16:57.161  3213  3223 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:16:57.161  1020  1049 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-17 19:16:57.161  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 19:16:57.171  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:57.171  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:57.171  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:57.171  3213  3213 D BluetoothA2dp: Proxy object connected,
08-17 19:16:57.171  3213  3213 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-17 19:16:57.171  4844  4855 D BluetoothPan: Binding service...
,08-17 19:16:57.171  1020  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-17 19:16:57.171  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-17 19:16:57.171  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:57.171  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:57.171  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:57.171  1020  1049 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0,
08-17 19:16:57.171  1020  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 19:16:57.171  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-17 19:16:57.171  1020  1049 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 19:16:57.171  1020  1049 D BluetoothPan: Binding service...
08-17 19:16:57.171  1020  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-17 19:16:57.171  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-17 19:16:57.171  4844  4844 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 19:16:57.171  4844  4844 D PanProfile: Bluetooth service connected
08-17 19:16:57.181  1453  7324 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:16:57.181  1453  7324 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-17 19:16:57.181  1020  1049 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:16:57.181  1020  1049 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:16:57.181  1465  1483 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:16:57.181  1465  1483 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-17 19:16:57.181  4844  4852 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-17 19:16:57.181  1020  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-17 19:16:57.181  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-17 19:16:57.181  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:57.181  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:57.181  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-17 19:16:57.181  1020  1020 D BluetoothPan: BluetoothPAN Proxy object connected
,08-17 19:16:57.181  4844  7719 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:16:57.181  1020  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 19:16:57.181  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 19:16:57.181  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:57.181  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:57.181  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:57.181  4844  7719 E BluetoothHeadset: BluetoothHeadset service is binded
08-17 19:16:57.181  4844  4844 D BluetoothInputDevice: Proxy object connected
08-17 19:16:57.181  4844  4844 D HidProfile: Bluetooth service connected
,08-17 19:16:57.181  7190  7199 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:16:57.181  7190  7199 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-17 19:16:57.181  1662  1671 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:16:57.181  1662  1671 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:16:57.181  1477  1502 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:16:57.181  1477  1502 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-17 19:16:57.191  1180  1201 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-17 19:16:57.191  1180  1201 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-17 19:16:57.191  4844  4852 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 19:16:57.191  4844  4852 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:16:57.191  1020  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-17 19:16:57.191  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 19:16:57.191  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:57.191  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:57.191  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:57.191  4844  4855 D BluetoothPbap: onBluetoothStateChange: up=true
08-17 19:16:57.191  4844  4844 D HeadsetProfile: Bluetooth service connected
,08-17 19:16:57.191  1020  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-17 19:16:57.191  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-17 19:16:57.191  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:57.191  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:57.191  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:57.191  3213  3375 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-17 19:16:57.191  3213  3375 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:16:57.191  1453  1478 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:16:57.191  1020  1049 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 19:16:57.191  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 19:16:57.201  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:57.201  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:57.201  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-17 19:16:57.201  1453  1478 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 19:16:57.201  4844  4844 D BluetoothA2dp: Proxy object connected
08-17 19:16:57.201  4844  4844 D A2dpProfile: Bluetooth service connected
,08-17 19:16:57.201  1020  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-17 19:16:57.201  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-17 19:16:57.201  1020  1020 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-17 19:16:57.201  1020  1020 I InputMethodManagerService: [BT Setting State] State =12
08-17 19:16:57.201  1020  1020 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-17 19:16:57.201  4844  4844 D BluetoothPbap: Proxy object connected
08-17 19:16:57.201  4844  4844 D PbapServerProfile: Bluetooth service connected
,08-17 19:16:57.201  1180  1180 D BluetoothTile:  onBluetoothStateChange:
,08-17 19:16:57.201  1453  1453 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@d64a029, true
,08-17 19:16:57.211  1180  1180 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-17 19:16:57.211  1453  1453 D BluetoothHeadset: registerMessageListener
,08-17 19:16:57.211  1180  1180 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-17 19:16:57.211  1180  1180 D BluetoothTile:  getBluetoothState : 12
,08-17 19:16:57.211  1894  1894 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-17 19:16:57.211  1180  1772 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 19:16:57.211  1180  1772 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 19:16:57.211  4844  4844 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:57.221  1020  1525 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 19:16:57.221  1020  1033 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-17 19:16:57.221  1180  1180 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 19:16:57.221  1180  1772 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 19:16:57.221  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:57.221  1020  2058 V SAMP_SPCM_test: CSC File load.. 
,08-17 19:16:57.231  3213  7856 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-17 19:16:57.241  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,08-17 19:16:57.241  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
,08-17 19:16:57.241  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
08-17 19:16:57.241  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
08-17 19:16:57.241  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
,08-17 19:16:57.241  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
08-17 19:16:57.241  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
08-17 19:16:57.241  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
08-17 19:16:57.241  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
08-17 19:16:57.241  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
08-17 19:16:57.241  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
08-17 19:16:57.241  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
08-17 19:16:57.241  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
08-17 19:16:57.241  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
08-17 19:16:57.241  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
08-17 19:16:57.241  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
08-17 19:16:57.241  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
08-17 19:16:57.241  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
08-17 19:16:57.241  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
08-17 19:16:57.241  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
08-17 19:16:57.241  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,08-17 19:16:57.271  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
08-17 19:16:57.271  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
08-17 19:16:57.271  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
08-17 19:16:57.271  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
08-17 19:16:57.271  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
08-17 19:16:57.271  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
08-17 19:16:57.271  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
08-17 19:16:57.271  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
08-17 19:16:57.271  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
08-17 19:16:57.271  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
08-17 19:16:57.271  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
08-17 19:16:57.271  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
08-17 19:16:57.271  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
08-17 19:16:57.271  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
08-17 19:16:57.271  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
08-17 19:16:57.271  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
08-17 19:16:57.271  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
08-17 19:16:57.271  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
08-17 19:16:57.271  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
08-17 19:16:57.271  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
08-17 19:16:57.271  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,08-17 19:16:57.281  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
,08-17 19:16:57.281  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
08-17 19:16:57.281  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
,08-17 19:16:57.281  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
08-17 19:16:57.281  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
08-17 19:16:57.281  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
08-17 19:16:57.281  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
08-17 19:16:57.281  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage,
08-17 19:16:57.281  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
08-17 19:16:57.281  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
08-17 19:16:57.281  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
08-17 19:16:57.281  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
08-17 19:16:57.281  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages,
08-17 19:16:57.281  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
08-17 19:16:57.281  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
08-17 19:16:57.281  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
08-17 19:16:57.281  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
08-17 19:16:57.281  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
,08-17 19:16:57.281  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
08-17 19:16:57.281  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
08-17 19:16:57.281  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
08-17 19:16:57.281  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
08-17 19:16:57.281  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
,08-17 19:16:57.281  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
08-17 19:16:57.281  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
08-17 19:16:57.281  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
08-17 19:16:57.281  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
08-17 19:16:57.281  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
,08-17 19:16:57.281  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
08-17 19:16:57.281  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
08-17 19:16:57.281  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
08-17 19:16:57.281  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
08-17 19:16:57.281  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
,08-17 19:16:57.281  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
08-17 19:16:57.281  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
08-17 19:16:57.281  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
08-17 19:16:57.281  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
08-17 19:16:57.281  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn,
08-17 19:16:57.281  1020  2058 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,08-17 19:16:57.291  3213  3362 D HeadsetService: registerMessageListener
08-17 19:16:57.291  1453  1453 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-17 19:16:57.291  3213  3362 D HeadsetService: registerMessageListener
,08-17 19:16:57.291  1453  1453 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-17 19:16:57.291  3213  7847 D HeadsetStateMachine: Disconnected process message: 70
08-17 19:16:57.291  3213  7847 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@26c1f63a
08-17 19:16:57.291  4844  4844 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-17 19:16:57.291  4844  4844 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-17 19:16:57.291  4844  4844 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-17 19:16:57.291  4844  4844 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-17 19:16:57.291  1453  1453 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1,
08-17 19:16:57.291  3213  7856 D BluetoothSocket: bindListen(): myUserId = 0
08-17 19:16:57.291  1453  1453 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-17 19:16:57.291  3213  7856 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 19:16:57.291  1453  1453 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-17 19:16:57.291  3213  7856 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
08-17 19:16:57.291  3213  7856 D BluetoothSocket: bindListen(), new LocalSocket 
08-17 19:16:57.291  3213  7856 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-17 19:16:57.291  3213  7856 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@477b2eb
,08-17 19:16:57.291  3213  7856 D BluetoothSocket: channel: 5
08-17 19:16:57.291  3213  7847 D HeadsetStateMachine: Disconnected process message: 9
08-17 19:16:57.291  3213  7847 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
08-17 19:16:57.291  1020  2058 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
,08-17 19:16:57.291  1020  2058 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:57.291  1020  2058 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:57.291  1020  2058 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:57.291  1020  2058 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:57.301  4844  4844 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 19:16:57.311  7857  7857 E Zygote  : MountEmulatedStorage()
,08-17 19:16:57.311  7857  7857 E Zygote  : v2
08-17 19:16:57.311  1020  2058 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=7857 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-17 19:16:57.311  7857  7857 I libpersona: KNOX_SDCARD checking this for 1000
08-17 19:16:57.311  7857  7857 I libpersona: KNOX_SDCARD not a persona
08-17 19:16:57.311   283   283 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-17 19:16:57.311  1020  1032 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-17 19:16:57.311   283   283 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-17 19:16:57.311   283   283 V voice   : voice_set_parameters: exit with code(-2)
08-17 19:16:57.311   283   283 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-17 19:16:57.311   283   283 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-17 19:16:57.311   283   283 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-17 19:16:57.311   283   283 V audio_hw_primary: adev_set_parameters: exit
08-17 19:16:57.311  7857  7857 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 19:16:57.311  3213  7847 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-17 19:16:57.311  1020  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-17 19:16:57.311  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:57.311  1020  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:57.311  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-17 19:16:57.321  7857  7857 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-17 19:16:57.321  1662  1662 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-17 19:16:57.321  7857  7857 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:16:57.321  4844  4844 D DockEventReceiver: finishStartingService: stopping service
,08-17 19:16:57.331  4844  4844 D BluetoothNotiBroadcastReceiver: onReceive
,08-17 19:16:57.331  1180  1180 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-17 19:16:57.331  1180  1180 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-17 19:16:57.341  3213  3213 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4e7895
,08-17 19:16:57.341  3213  3213 D BtConfig.SecureMode: isSecureModeOn:false
,08-17 19:16:57.341  1020  1032 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:57.341  1020  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-17 19:16:57.341  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:57.341  1020  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:57.341  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:57.351  7857  7857 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:57.351  7857  7857 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:57.351  1020  1525 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-17 19:16:57.361  3213  7876 D BluetoothSocket: bindListen(): myUserId = 0
,08-17 19:16:57.361  3213  7876 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 19:16:57.361  3213  7876 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[86]}
08-17 19:16:57.361  3213  7876 D BluetoothSocket: bindListen(), new LocalSocket 
08-17 19:16:57.361  3213  7876 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-17 19:16:57.371  3213  7876 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2f9c92c7
,08-17 19:16:57.371  3213  7876 D BluetoothSocket: channel: 12
,08-17 19:16:57.371  3213  7876 I BtOppRfcommListener: Accept thread started.
,08-17 19:16:57.371  7857  7857 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-17 19:16:57.411  1020  2058 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,08-17 19:16:57.411  1020  1020 I ActivityManager: Killing 7431:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,08-17 19:16:57.691  1020  3407 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-17 19:16:57.691  1020  3378 D SSRM:n  : SIOP:: AP = 320
,08-17 19:16:57.791   324   324 I ServiceManager: Waiting for service AtCmdFwd...,
,08-17 19:16:57.801  7190  7267 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:57.801  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:57.801  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:57.801  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:16:57.801  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:57.801  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:57.801  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:57.801  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:16:57.801  7190  7267 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:16:57.811  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 19:16:57.811  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@21b921ef added. We now have 8 listener(s)
,08-17 19:16:57.811  7190  7267 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 19:16:57.811   291   291 E SMD     : DCD OFF
,08-17 19:16:57.811  1020  1494 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-17 19:16:57.811  1020  1494 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-17 19:16:57.811  1020  1494 D SecContentProvider2: mCursor = null
,08-17 19:16:57.821  1020  1494 D WifiService: setWifiEnabled: false pid=7190, uid=10170
,08-17 19:16:57.821  1020  1494 D SettingsProvider: name = wifi_on
,08-17 19:16:57.821  7190  7267 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:57.821  1020  3827 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-17 19:16:57.821  1020  3827 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-17 19:16:57.831  1020  3827 D SecContentProvider2: mCursor = null
,08-17 19:16:57.831  1020  3827 W WifiService: Failed getting userId using ActivityManagerNative
08-17 19:16:57.831  1020  3827 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7190, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-17 19:16:57.831  1020  3827 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-17 19:16:57.831  1020  3827 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-17 19:16:57.831  1020  3827 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-17 19:16:57.831  1020  3827 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-17 19:16:57.831  1020  3827 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-17 19:16:57.831  1020  3827 D WifiService: setWifiEnabled: true pid=7190, uid=10170
08-17 19:16:57.831  1020  3827 D SettingsProvider: name = wifi_on
08-17 19:16:57.831  1020  3827 W ActivityManager: Permission Denial: getCurrentUser() from pid=7190, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-17 19:16:57.841  1020  1129 E WifiHW  : ##################### set firmware type 0 #####################,
,08-17 19:16:58.111  1020  1098 V AlarmManager: waitForAlarm result :4
,08-17 19:16:58.121   278   984 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-17 19:16:58.121   278   984 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-17 19:16:58.141  1020  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:58.141  1020  1045 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-17 19:16:58.141  1020  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,08-17 19:16:58.181  1020  1047 D Tethering: interfaceAdded wlan0
,08-17 19:16:58.181  1020  1134 E Tethering: No numeric data
,08-17 19:16:58.181  1020  1134 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-17 19:16:58.191  1020  1126 D NtpTrustedTime: currentTimeMillis() cache hit,
08-17 19:16:58.191  1020  1126 V NetworkStats: performPollLocked(flags=0x1),
,08-17 19:16:58.191  1020  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 19:16:58.191  1180  1180 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED,
08-17 19:16:58.191  1020  1134 D Tethering: clearTetheredNotification()
08-17 19:16:58.191  1180  1180 D HotspotTile: updateTetherState():false, false
08-17 19:16:58.191  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:16:58.191  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:16:58.191  1020  1047 D Tethering: interfaceStatusChanged wlan0, false,
08-17 19:16:58.191  1020  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 19:16:58.201  1020  1126 V NetworkStats: performPollLocked() took 14ms
08-17 19:16:58.191  1020  1134 D Tethering: InitialState.processMessage what=4
08-17 19:16:58.201  1020  1134 E Tethering: No numeric data
08-17 19:16:58.201  1020  1134 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-17 19:16:58.201  1020  1134 D Tethering: clearTetheredNotification()
08-17 19:16:58.201  1020  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:58.201  1020  1047 D Tethering: interfaceAdded p2p0
,08-17 19:16:58.211  1180  1180 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-17 19:16:58.211  1180  1180 D HotspotTile: updateTetherState():false, false
,08-17 19:16:58.211  1020  1047 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-17 19:16:58.211   278   988 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-17 19:16:58.211   278   988 D SoftapController: Softap fwReload - Ok
08-17 19:16:58.211  1020  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-17 19:16:58.221  1020  1047 D Tethering: interfaceLinkStateChanged p2p0, false
08-17 19:16:58.221  1020  1047 D Tethering: interfaceStatusChanged p2p0, false
,08-17 19:16:58.221  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:58.221  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:58.221  1020  1126 V NetworkStats: performPollLocked(flags=0x1)
08-17 19:16:58.221  1020  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:58.221   278   988 D CommandListener: Setting iface cfg
08-17 19:16:58.221   278   988 D CommandListener: Trying to bring down wlan0
,08-17 19:16:58.221   278   988 D CommandListener: Clearing all IP addresses on wlan0
,08-17 19:16:58.221  1020  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 19:16:58.221  1020  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 19:16:58.231  1020  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:58.231  1020  1126 V NetworkStats: performPollLocked() took 8ms
08-17 19:16:58.231  1020  1129 E WifiHW  : supplicant_name : p2p_supplicant
,08-17 19:16:58.231  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:58.231  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:58.231  1020  1129 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-17 19:16:58.251  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:58.251  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-17 19:16:58.251  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:16:58.251  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-17 19:16:58.251  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:58.251  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:58.251  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:58.251  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:58.251  1180  1180 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 19:16:58.251  1180  1180 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-17 19:16:58.251  1180  1180 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-17 19:16:58.251  1020  1494 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 19:16:58.251  4844  4844 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-17 19:16:58.251  1180  1772 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-17 19:16:58.251  1020  1494 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-17 19:16:58.251  1180  1180 D HotspotTile: onReceive : 2, 0
08-17 19:16:58.251  1020  1494 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:58.251  1020  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:58.251  1020  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 19:16:58.251  1640  1640 I Hs20UtilService: Starting #19
08-17 19:16:58.251  1640  1699 I Hs20UtilService: Message received 5011
,08-17 19:16:58.261  7411  7411 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-17 19:16:58.261  7411  7411 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-17 19:16:58.261  7411  7411 D SecurityLogAgent: StateMachine : Current State = 1
08-17 19:16:58.261  7411  7411 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 19:16:58.271  7891  7891 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,08-17 19:16:58.271  7891  7891 I wpa_supplicant: Successfully initialized wpa_supplicant
08-17 19:16:58.281  7891  7891 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-17 19:16:58.291  7891  7891 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-17 19:16:58.291   409   409 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7891
,08-17 19:16:58.291   409   409 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-17 19:16:58.291  7891  7891 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-17 19:16:58.291  7891  7891 I wpa_supplicant: ssSupport state is = 1
,08-17 19:16:58.291  7891  7891 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-17 19:16:58.291  7891  7891 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,08-17 19:16:58.291   409   409 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7891,
08-17 19:16:58.291   409   409 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-17 19:16:58.431   409   409 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,08-17 19:16:58.431  7891  7891 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,08-17 19:16:58.481  7891  7891 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-17 19:16:58.481  7891  7891 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-17 19:16:58.491  7891  7891 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,08-17 19:16:58.491   409   409 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7891
08-17 19:16:58.491   409   409 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-17 19:16:58.491  7891  7891 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-17 19:16:58.491  7891  7891 I wpa_supplicant: ssSupport state is = 1
08-17 19:16:58.491  7891  7891 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-17 19:16:58.491  7891  7891 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 19:16:58.491  7891  7891 E wpa_supplicant: SIM READ ERROR
,08-17 19:16:58.491  7891  7891 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 19:16:58.491  7891  7891 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 19:16:58.491  7891  7891 E wpa_supplicant: SIM READ ERROR,
08-17 19:16:58.491  7891  7891 I wpa_supplicant: Blacklist: Clear (all) 
,08-17 19:16:58.491  7891  7891 I wpa_supplicant: wpa_default_ap_write_once,
08-17 19:16:58.491  7891  7891 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-17 19:16:58.491  7891  7891 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-17 19:16:58.491  7891  7891 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-17 19:16:58.491  7891  7891 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 19:16:58.491  7891  7891 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-17 19:16:58.501  7891  7891 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-17 19:16:58.501  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false,
08-17 19:16:58.501  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:16:58.501  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
,08-17 19:16:58.541  7891  7891 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-17 19:16:58.691  7891  7891 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-17 19:16:58.691  7891  7891 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,08-17 19:16:58.701  7891  7891 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-17 19:16:58.701   409   409 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7891
08-17 19:16:58.701   409   409 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
,08-17 19:16:58.711  7891  7891 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-17 19:16:58.711  7891  7891 I wpa_supplicant: ssSupport state is = 1
08-17 19:16:58.711  7891  7891 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-17 19:16:58.711  7891  7891 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-17 19:16:58.721  7891  7891 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-17 19:16:58.721   409   409 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7891
08-17 19:16:58.721   409   409 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
08-17 19:16:58.721  7891  7891 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-17 19:16:58.721  7891  7891 I wpa_supplicant: ssSupport state is = 1
08-17 19:16:58.721  7891  7891 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 19:16:58.721  7891  7891 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 19:16:58.721  7891  7891 E wpa_supplicant: SIM READ ERROR
08-17 19:16:58.721  7891  7891 I wpa_supplicant: wpa_default_ap_write_once
08-17 19:16:58.721  7891  7891 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-17 19:16:58.721  7891  7891 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-17 19:16:58.731  1020  1047 D Tethering: interfaceLinkStateChanged p2p0, false,
08-17 19:16:58.731  1020  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-17 19:16:58.731  1020  1047 D Tethering: interfaceStatusChanged p2p0, false
,08-17 19:16:58.731  1020  1047 D Tethering: interfaceLinkStateChanged p2p0, false,
08-17 19:16:58.731  1020  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-17 19:16:58.731  1020  1047 D Tethering: interfaceStatusChanged p2p0, false
,08-17 19:16:58.771  7891  7891 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-17 19:16:58.771  7891  7891 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-17 19:16:58.791   324   324 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,08-17 19:16:58.831  7891  7891 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-17 19:16:58.831  7891  7891 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,08-17 19:16:58.831  7891  7891 I wpa_supplicant: Skip scan - bUseNetwork false
,08-17 19:16:58.841  1020  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-17 19:16:58.841  1020  1129 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-17 19:16:58.841  7891  7891 I wpa_supplicant: HOTSPOT20_ENABLE called
08-17 19:16:58.841  7891  7891 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 19:16:58.841  7891  7891 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
,08-17 19:16:58.841  7891  7891 E wpa_supplicant: SIM READ ERROR,
08-17 19:16:58.841  7891  7891 I wpa_supplicant: Blacklist: Clear (all) ,
,08-17 19:16:58.861  7891  7891 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-17 19:16:58.871  7891  7891 I wpa_supplicant: Skip scan - bUseNetwork false,
08-17 19:16:58.871  1020  1129 D WifiConfigStore: Loading config and enabling all networks 
,08-17 19:16:58.881  4844  4844 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-17 19:16:58.891  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
08-17 19:16:58.891  1020  4295 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 19:16:58.891  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:16:58.891  1020  4295 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-17 19:16:58.891  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-17 19:16:58.891  1180  1180 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 19:16:58.891  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:58.891  1180  1772 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-17 19:16:58.891  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:58.891  1180  1180 D HotspotTile: onReceive : 3, 0
08-17 19:16:58.891  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-17 19:16:58.891  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:58.891  1180  1180 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 19:16:58.891  1180  1180 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-17 19:16:58.891  1020  4295 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:58.891  1020  4295 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:58.891  1020  4295 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 19:16:58.891  1020  1129 E WifiConfigStore: Not a HS20
08-17 19:16:58.891  1640  1640 I Hs20UtilService: Starting #20
08-17 19:16:58.891  1640  1699 I Hs20UtilService: Message received 5011
,08-17 19:16:58.891  1020  1129 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-17 19:16:58.901  7411  7411 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-17 19:16:58.901  7411  7411 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-17 19:16:58.901  7411  7411 D SecurityLogAgent: StateMachine : Current State = 1
08-17 19:16:58.901  7411  7411 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 19:16:58.901  1020  1129 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,08-17 19:16:58.901  7891  7891 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-17 19:16:58.901  7891  7891 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-17 19:16:58.901  7891  7891 I wpa_supplicant: reset timer : RESET_TIMER 0
08-17 19:16:58.901  7891  7891 I wpa_supplicant: P2P: Current p2p state = IDLE
08-17 19:16:58.901  7891  7891 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-17 19:16:58.901  7891  7891 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-17 19:16:58.901  7891  7891 I wpa_supplicant: First Scan Start
,08-17 19:16:58.901  7891  7891 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-17 19:16:58.901  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:58.901  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:58.901  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:58.901  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:58.901  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:58.901  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:58.901  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:58.901  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:16:58.901  7190  7190 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:16:58.911  7388  7388 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 19:16:58.911  1020  1129 D WifiNative-wlan0: Setting external_sim to 1
,08-17 19:16:58.921  1020  1129 D WifiStateMachine: Setting OUI to DA-A1-19
,08-17 19:16:58.921  1020  1129 I WifiNative-HAL: startHal
08-17 19:16:58.921  1020  1129 E wifi    : getStaticLongField sWifiHalHandle 0x9f3f188c
,08-17 19:16:58.921  1020  1129 I WifiNative-HAL: Could not start hal
,08-17 19:16:58.921  1020  1129 E WifiNative-wlan0: do suspend true
,08-17 19:16:58.921  1020  1128 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-17 19:16:58.921  1020  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3,
,08-17 19:16:58.921  1020  1020 D WifiScanningService: SCAN_AVAILABLE : 3
,08-17 19:16:58.931  1020  1154 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-17 19:16:58.931   278   988 D CommandListener: Setting iface cfg
08-17 19:16:58.931   278   988 D CommandListener: Trying to bring up p2p0
,08-17 19:16:58.931  1020  1154 I WifiNative-HAL: startHal
,08-17 19:16:58.931  1020  1154 E wifi    : getStaticLongField sWifiHalHandle 0x9e2b39bc
08-17 19:16:58.931  1020  1154 I WifiNative-HAL: Could not start hal
08-17 19:16:58.931  1020  1154 E WifiScanningService: could not start HAL
,08-17 19:16:58.931  1020  1020 D RttService: SCAN_AVAILABLE : 3
08-17 19:16:58.931  1020  1129 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-17 19:16:58.931  1020  1129 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-17 19:16:58.931  1020  1129 E WifiNative-wlan0: invaild command id : 215
08-17 19:16:58.931  1020  1155 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-17 19:16:58.931  1020  1128 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-17 19:16:58.931  1020  1129 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-17 19:16:58.931  1020  1128 D WifiP2pService: P2pEnablingState
08-17 19:16:58.931  1020  1129 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-17 19:16:58.931  1020  1129 E WifiNative-wlan0: invaild command id : 215
08-17 19:16:58.931  1020  1128 D WifiP2pService: P2pEnablingState{ what=147457 }
08-17 19:16:58.931  1020  1128 D WifiP2pService: P2p socket connection successful
,08-17 19:16:58.931  1020  1128 D WifiP2pService: P2pEnabledState
08-17 19:16:58.931  1020  1128 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-17 19:16:58.931  1020  1131 E ConnectivityService: updateNetworkInfo()
,08-17 19:16:58.931  1020  1020 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED,
08-17 19:16:58.931  7891  7891 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-17 19:16:58.931  1020  1050 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true,
08-17 19:16:58.931  7891  7891 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-17 19:16:58.931  1020  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-17 19:16:58.931  1020  1050 D WifiDisplayController: disconnect
08-17 19:16:58.931  1020  1050 D WifiDisplayController: updateConnection
,08-17 19:16:58.931  1020  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-17 19:16:58.931  1020  1050 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-17 19:16:58.941  7891  7891 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-17 19:16:58.941  1180  1180 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-17 19:16:58.941  1020  1129 E WifiStateMachine: Failed to set frequency band 0
08-17 19:16:58.941  1020  4295 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-17 19:16:58.941  1180  1180 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-17 19:16:58.941  1020  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 19:16:58.941  1020  1129 D SecContentProvider2: mCursor = null
,08-17 19:16:58.941  1020  1050 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 19:16:58.941  1020  1128 D WifiNative-p2p0: p2pGetDeviceAddress
08-17 19:16:58.941  1020  1050 D WifiDisplayAdapter: onP2pDisconnected
08-17 19:16:58.941  1020  1050 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-17 19:16:58.941  1020  1128 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
08-17 19:16:58.941  1020  1050 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-17 19:16:58.941  4844  4844 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-17 19:16:58.941  1020  1128 D WifiP2pService: DeviceAddress: 0a:75:42
,08-17 19:16:58.941  4844  4844 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-17 19:16:58.941  1020  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 19:16:58.941  1020  1129 D SecContentProvider2: mCursor = null
,08-17 19:16:58.941  4844  4844 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-17 19:16:58.941  1020  1050 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
08-17 19:16:58.941  1020  1050 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
08-17 19:16:58.941  1020  1050 D WifiDisplayController:  primary type: 10-0050F204-5
08-17 19:16:58.941  1020  1050 D WifiDisplayController:  secondary type: null
08-17 19:16:58.941  1020  1050 D WifiDisplayController:  wps: 0
08-17 19:16:58.941  1020  1050 D WifiDisplayController:  grpcapab: 0
08-17 19:16:58.941  1020  1050 D WifiDisplayController:  devcapab: 0
08-17 19:16:58.941  1020  1050 D WifiDisplayController:  status: 3
08-17 19:16:58.941  1020  1050 D WifiDisplayController:  wfdInfo: null
08-17 19:16:58.941  1020  1050 D WifiDisplayController:  groupownerAddress: null
08-17 19:16:58.941  1020  1050 D WifiDisplayController:  GOdeviceName: null
08-17 19:16:58.941  1020  1050 D WifiDisplayController:  interfaceAddress: 
08-17 19:16:58.941  1020  1050 D WifiDisplayController:  SConnectInfo : null
,08-17 19:16:58.951  4844  4844 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-17 19:16:58.951  4844  4844 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 19:16:58.951  4844  4844 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-17 19:16:58.951  4844  4897 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 19:16:58.951  7720  7720 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-17 19:16:58.951  7720  7720 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-17 19:16:58.951  7720  7720 D FileShare-Client: Outbound.stopDelayTimer - 
,08-17 19:16:58.961  7372  7372 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-17 19:16:58.971  1020  1128 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-17 19:16:58.971  1020  1128 D WifiP2pService: InactiveState
,08-17 19:16:58.971  1020  1128 D WifiP2pService: InactiveState{ what=143376 }
,08-17 19:16:58.971  1020  1128 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-17 19:16:58.971  7891  7891 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
,08-17 19:16:58.971  1020  1128 D WifiP2pService: InactiveState{ what=143376 }
,08-17 19:16:58.971  1020  1128 D WifiP2pService: P2pEnabledState{ what=143376 },
,08-17 19:16:59.191  1020  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-17 19:16:59.191  1020  1047 D Tethering: interfaceLinkStateChanged p2p0, false
,08-17 19:16:59.191  1020  1047 D Tethering: interfaceStatusChanged p2p0, false
,08-17 19:16:59.851  7190  7267 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-17 19:16:59.851  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:59.851  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:59.851  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:59.851  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:59.851  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
,08-17 19:16:59.851  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:59.851  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:16:59.851  7190  7267 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 19:16:59.851  7190  7267 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-17 19:16:59.851  7190  7267 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-17 19:16:59.861  7190  7267 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@222b38b Bundle[{}]
,08-17 19:16:59.861  7190  7267 I io.jxcore.node.LifeCycleMonitor: start: OK,
08-17 19:16:59.861  7190  7267 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-17 19:16:59.861  7190  7267 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-17 19:16:59.861  7190  7267 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-17 19:16:59.861  7190  7267 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-17 19:16:59.861  7190  7267 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-17 19:16:59.861  7190  7267 I System.out: Running OutgoingSocketThread
,08-17 19:16:59.871  7190  7900 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1460)
08-17 19:16:59.871  7190  7900 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 42524
,08-17 19:16:59.871  7190  7900 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-17 19:16:59.991  1020  1098 V AlarmManager: waitForAlarm result :8
,08-17 19:17:00.151  7891  7891 I wpa_supplicant: nl80211: Received scan results (25 BSSes),
,08-17 19:17:00.151  7891  7891 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-17 19:17:00.151  1020  7897 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700',
,08-17 19:17:00.151  7891  7891 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-17 19:17:00.151  7891  7891 I wpa_supplicant: Trying to associate with  'G700',
08-17 19:17:00.151  7891  7891 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,08-17 19:17:00.161  7891  7891 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030,
,08-17 19:17:00.181  1020  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-17 19:17:00.181  1020  1129 D SecContentProvider2: mCursor = null
,08-17 19:17:00.271  7891  7891 E wpa_supplicant: Cmd 35605 not handled
08-17 19:17:00.271  7891  7891 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-17 19:17:00.271  7891  7891 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
08-17 19:17:00.271  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:17:00.271  7891  7891 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-17 19:17:00.271  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:17:00.271  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
08-17 19:17:00.271  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:17:00.271  7891  7891 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-17 19:17:00.271  7891  7891 I wpa_supplicant: Associated with F4.99.3E
08-17 19:17:00.271  7891  7891 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-17 19:17:00.271  7891  7891 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-17 19:17:00.271  7891  7891 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
08-17 19:17:00.271  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:17:00.271  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
08-17 19:17:00.271  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:17:00.271  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:17:00.271  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
08-17 19:17:00.281  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-17 19:17:00.281  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, true
08-17 19:17:00.281  1020  1047 D Tethering: interfaceStatusChanged wlan0, true
08-17 19:17:00.281  7891  7891 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-17 19:17:00.281  7891  7891 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-17 19:17:00.281  7891  7891 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-17 19:17:00.281  7891  7891 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-17 19:17:00.281  7891  7891 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-17 19:17:00.281  7891  7891 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-17 19:17:00.281  7891  7891 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-17 19:17:00.281  1020  1134 E Tethering: No numeric data
08-17 19:17:00.281  7891  7891 I wpa_supplicant: Blacklist: Clear (temp) 
08-17 19:17:00.281  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-17 19:17:00.281  7891  7891 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-17 19:17:00.291  1020  1126 V NetworkStats: performPollLocked(flags=0x1)
08-17 19:17:00.281  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, true
08-17 19:17:00.291  1180  1180 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-17 19:17:00.281  1020  1047 D Tethering: interfaceStatusChanged wlan0, true
08-17 19:17:00.291  1180  1180 D HotspotTile: updateTetherState():false, false
08-17 19:17:00.281  1020  1134 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-17 19:17:00.281  1020  1134 D Tethering: clearTetheredNotification()
08-17 19:17:00.291  1020  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 19:17:00.291  1020  1129 D SecContentProvider2: mCursor = null
08-17 19:17:00.291  1020  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:17:00.291  1020  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 19:17:00.291  1020  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-17 19:17:00.301  1020  1126 V NetworkStats: performPollLocked() took 9ms
08-17 19:17:00.301  1020  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:17:00.301  1020  1129 D WifiNative-wlan0: callSECApiVoid - ID [50]
08-17 19:17:00.301  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:17:00.301  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:17:00.301  1020  1129 E WifiConfigStore: setLastSelectedConfiguration -1
08-17 19:17:00.311  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-17 19:17:00.311  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:17:00.311  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 19:17:00.311  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:17:00.311  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:17:00.311  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:17:00.311  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:17:00.321  1020  1129 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-17 19:17:00.321  1020  1129 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-17 19:17:00.321  1020  1131 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-17 19:17:00.321  1020  1131 E ConnectivityService: updateNetworkInfo()
08-17 19:17:00.321  1020  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 19:17:00.321  1020  1747 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 19:17:00.321  1020  1747 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-17 19:17:00.331  1020  1129 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-17 19:17:00.331  1020  1747 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:17:00.331  1020  1747 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:17:00.331  1020  1747 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-17 19:17:00.331  1640  1640 I Hs20UtilService: Starting #21
08-17 19:17:00.331  1640  1699 I Hs20UtilService: Message received 5007
08-17 19:17:00.331  4844  4844 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-17 19:17:00.331  4844  4844 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-17 19:17:00.331  4844  4844 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-17 19:17:00.331  4844  4844 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-17 19:17:00.331  4844  4844 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 19:17:00.331  4844  4844 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-17 19:17:00.331  4844  4897 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-17 19:17:00.341   278   988 D CommandListener: Setting iface cfg
,08-17 19:17:00.341  1020  1129 E WifiStateMachine: Start Dhcp Watchdog 3
,08-17 19:17:00.351  1020  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 19:17:00.351  1020  1129 D SecContentProvider2: mCursor = null
,08-17 19:17:00.351  1020  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-17 19:17:00.351  1020  1129 D SecContentProvider2: mCursor = null
,08-17 19:17:00.361  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-17 19:17:00.361  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 19:17:00.361  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-17 19:17:00.361  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:17:00.361  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:17:00.361  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:17:00.361  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:17:00.371  1020  1129 E WifiNative-wlan0: do suspend false
,08-17 19:17:00.371  1020  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-17 19:17:00.371  1020  1128 D WifiP2pService: InactiveState{ what=143375 }
,08-17 19:17:00.371  1020  1129 D SecContentProvider2: mCursor = null
,08-17 19:17:00.371  1020  1128 D WifiP2pService: P2pEnabledState{ what=143375 },
,08-17 19:17:00.591  7903  7903 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-17 19:17:00.591  7903  7903 I dhcpcd  : version 5.5.6 starting,
,08-17 19:17:00.601  7903  7903 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-17 19:17:00.651  7903  7903 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-17 19:17:00.651  7903  7903 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-17 19:17:00.651  7903  7903 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E),
08-17 19:17:00.651  7903  7903 I dhcpcd  : bssid match
08-17 19:17:00.651  7903  7903 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116,
,08-17 19:17:00.721  7903  7903 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1,
,08-17 19:17:00.791  7903  7903 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds,
,08-17 19:17:00.811   291   291 E SMD     : DCD OFF,
,08-17 19:17:00.871  7190  7267 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1461),
08-17 19:17:00.871  7190  7267 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1461)
08-17 19:17:00.871  7190  7267 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1466)
08-17 19:17:00.871  7190  7267 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-17 19:17:00.871  7190  7267 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1467)
08-17 19:17:00.871  7190  7267 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 19:17:00.871  7190  7267 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@320474fc added. We now have 2 listener(s)
,08-17 19:17:00.881  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-17 19:17:00.881  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:17:00.881  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 19:17:00.881  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-17 19:17:00.881  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e72c785 added. We now have 9 listener(s)
08-17 19:17:00.881  7190  7267 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
,08-17 19:17:00.881  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 19:17:00.891  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:17:00.891  7190  7267 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:17:00.891  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:17:00.891  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:17:00.891  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
,08-17 19:17:00.891  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:17:00.891  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:17:00.891  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:17:00.891  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:17:00.891  7190  7267 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:17:00.891  7190  7267 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 19:17:00.891  7190  7267 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 19:17:00.891  7190  7267 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@291fee0b added. We now have 3 listener(s)
08-17 19:17:00.901  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:17:00.901  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:17:00.901  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-17 19:17:00.901  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:17:00.901  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 19:17:00.901  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:17:00.901  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24a1e4e8 added. We now have 10 listener(s)
08-17 19:17:00.901  7190  7267 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:17:00.901  7190  7267 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:17:00.901  7190  7267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:17:00.901  7190  7267 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:17:00.901  7190  7267 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:17:00.901  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:17:00.901  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:17:00.901  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 19:17:00.901  7190  7267 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@320474fc removed from the list
08-17 19:17:00.901  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:17:00.901  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e72c785 removed from the list
08-17 19:17:00.901  7190  7267 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:17:00.901  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:17:00.901  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:17:00.901  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:17:00.901  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:17:00.901  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:17:00.901  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 19:17:00.901  7190  7267 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e72c785 not in the list
08-17 19:17:00.901  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:17:00.901  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:17:00.901  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:17:00.901  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:17:00.901  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 19:17:00.901  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24a1e4e8 removed from the list
08-17 19:17:00.901  7190  7267 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:17:00.901  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:17:00.901  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:17:00.901  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-17 19:17:00.901  7190  7267 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@291fee0b removed from the list
08-17 19:17:00.901  7190  7267 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 19:17:00.901  7190  7267 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@201d5701 added. We now have 2 listener(s)
,08-17 19:17:00.911  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-17 19:17:00.911  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:17:00.911  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 19:17:00.911  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:17:00.911  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28c689a6 added. We now have 9 listener(s)
08-17 19:17:00.911  7190  7267 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:17:00.911  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 19:17:00.911  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:17:00.921  7190  7267 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-17 19:17:00.921  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:17:00.921  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:17:00.921  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:17:00.921  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:17:00.921  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:17:00.921  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:17:00.921  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 19:17:00.921  7190  7267 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 19:17:00.921  7190  7267 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 19:17:00.921  7190  7267 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 19:17:00.921  7190  7267 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23246794 added. We now have 3 listener(s)
08-17 19:17:00.921  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:17:00.921  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:17:00.921  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-17 19:17:00.921  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:17:00.921  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 19:17:00.921  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:17:00.921  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e87623d added. We now have 10 listener(s),
08-17 19:17:00.921  7190  7267 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:17:00.921  7190  7267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 19:17:00.921  7190  7267 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 19:17:00.921  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 19:17:00.921  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:17:00.921  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 19:17:00.931  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 19:17:00.941  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-17 19:17:00.941  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-17 19:17:00.941  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-17 19:17:00.941  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 19:17:00.941  7190  7267 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-17 19:17:00.951  3213  3223 D BtGatt.GattService: registerClient() - UUID=7cfe8321-1ca6-4338-9db3-f018a964c9e3
,08-17 19:17:00.991  1020  3827 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-17 19:17:00.991  1020  3827 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4277, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-17 19:17:00.991  1020  3827 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-17 19:17:00.991  1020  3827 D BatteryService: stay LED for charging
08-17 19:17:00.991  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-17 19:17:00.991  3213  3287 D BtGatt.GattService: onClientRegistered() - UUID=7cfe8321-1ca6-4338-9db3-f018a964c9e3, clientIf=6
,08-17 19:17:01.001  7190  7199 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-17 19:17:01.001  3213  3375 D BtGatt.GattService: start scan with filters
,08-17 19:17:01.001  1020  1020 I MotionRecognitionService: Plugged
08-17 19:17:01.001  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,08-17 19:17:01.001  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-17 19:17:01.001  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 19:17:01.001  3213  3365 D BtGatt.ScanManager: handling starting scan
08-17 19:17:01.001  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 19:17:01.001  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 19:17:01.001  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-17 19:17:01.001  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
08-17 19:17:01.011  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-17 19:17:01.011  3213  3287 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-17 19:17:01.011  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
08-17 19:17:01.011  3213  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:17:01.011  3213  3365 D BtGatt.ScanManager: allow scan with filters
,08-17 19:17:01.011  3213  3365 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-17 19:17:01.011  3213  3365 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
,08-17 19:17:01.011  3213  3287 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-17 19:17:01.011  3213  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:17:01.011  3213  3365 D BtGatt.ScanManager: Starting BLE batch scan
,08-17 19:17:01.011  3213  3365 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-17 19:17:01.011  3213  3287 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-17 19:17:01.011  3213  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:17:01.021  3213  3287 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-17 19:17:01.021  3213  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:17:01.031  3213  3213 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-17 19:17:01.031  3213  7847 D HeadsetStateMachine: Disconnected process message: 10
,08-17 19:17:01.031  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-17 19:17:01.031  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-17 19:17:01.031  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-17 19:17:01.031  7190  7267 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 19:17:01.031  7190  7190 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 19:17:01.031  7190  7267 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 19:17:01.041  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 19:17:01.051  7190  7267 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-17 19:17:01.051  7190  7267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-17 19:17:01.051  7190  7267 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-17 19:17:01.051  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:17:01.051  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 19:17:01.051  7190  7267 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 19:17:01.051  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 19:17:01.051  7190  7267 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-17 19:17:01.051  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 19:17:01.051  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 19:17:01.051  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...,
,08-17 19:17:01.051  3213  3375 D BtGatt.GattService: stopScan() - queue size =1
08-17 19:17:01.051  3213  3362 D BtGatt.GattService: unregisterClient() - clientIf=6,
08-17 19:17:01.051  3213  3365 D BtGatt.ScanManager: filter size is 1
,08-17 19:17:01.051  3213  3365 D BtGatt.ScanManager: delete FilterIndex - 6
08-17 19:17:01.051  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
,08-17 19:17:01.051  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 19:17:01.051  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-17 19:17:01.051  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 19:17:01.051  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 19:17:01.051  3213  3287 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-17 19:17:01.051  3213  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
08-17 19:17:01.051  3213  3365 D BtGatt.ScanManager: stopping BLe Batch
08-17 19:17:01.061  7190  7267 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 19:17:01.061  3213  3287 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-17 19:17:01.061  3213  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:17:01.061  3213  3365 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-17 19:17:01.061  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 19:17:01.061  7190  7267 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-17 19:17:01.061  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 19:17:01.061  3213  3287 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-17 19:17:01.061  3213  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:17:01.061  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 19:17:01.061  7190  7190 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 19:17:01.061  7190  7190 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 19:17:01.061  7190  7190 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 19:17:01.071  7190  7267 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 19:17:01.071  7190  7267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 19:17:01.071  7190  7267 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 19:17:01.071  7190  7267 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 19:17:01.071  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:17:01.071  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:17:01.071  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-17 19:17:01.071  7190  7267 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@201d5701 removed from the list
08-17 19:17:01.071  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 19:17:01.071  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28c689a6 removed from the list
08-17 19:17:01.071  7190  7267 D io.jxcore.node.ConnectivityMonitor: stop,
08-17 19:17:01.071  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:17:01.071  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:17:01.071  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:17:01.071  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 19:17:01.071  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:17:01.071  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 19:17:01.071  7190  7267 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28c689a6 not in the list
08-17 19:17:01.071  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:17:01.071  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:17:01.071  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 19:17:01.071  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 19:17:01.081  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 19:17:01.081  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e87623d removed from the list
08-17 19:17:01.081  7190  7267 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 19:17:01.081  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:17:01.081  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:17:01.081  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-17 19:17:01.081  7190  7267 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23246794 removed from the list
,08-17 19:17:01.081  7190  7267 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 19:17:01.081  7190  7267 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a8ce539 added. We now have 2 listener(s)
,08-17 19:17:01.081  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41",
08-17 19:17:01.081  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 19:17:01.081  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 19:17:01.081  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 19:17:01.081  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eeb277e added. We now have 9 listener(s)
08-17 19:17:01.081  7190  7267 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:17:01.081  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 19:17:01.081  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:17:01.091  7190  7267 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-17 19:17:01.091  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:17:01.091  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:17:01.091  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:17:01.091  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:17:01.091  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:17:01.091  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:17:01.091  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:17:01.091  7190  7267 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:17:01.091  7190  7267 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 19:17:01.091  7190  7267 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 19:17:01.091  7190  7267 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21cd152c added. We now have 3 listener(s)
,08-17 19:17:01.091  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:17:01.091  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:17:01.091  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-17 19:17:01.091  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:17:01.091  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 19:17:01.091  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:17:01.091  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ccd9bf5 added. We now have 10 listener(s)
08-17 19:17:01.091  7190  7267 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:17:01.091  7190  7267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 19:17:01.091  7190  7267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 19:17:01.091  7190  7267 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 19:17:01.091  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 19:17:01.091  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:17:01.091  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 19:17:01.101  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 19:17:01.101  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 19:17:01.101  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 19:17:01.101  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-17 19:17:01.101  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-17 19:17:01.101  7190  7267 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-17 19:17:01.111  3213  3222 D BtGatt.GattService: registerClient() - UUID=a36b3037-9b30-44b7-81e5-0c2dfb4c99de
,08-17 19:17:01.151  3213  3287 D BtGatt.GattService: onClientRegistered() - UUID=a36b3037-9b30-44b7-81e5-0c2dfb4c99de, clientIf=6,
08-17 19:17:01.151  7190  7200 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6,
08-17 19:17:01.151  3213  3223 D BtGatt.GattService: start scan with filters,
08-17 19:17:01.151  3213  3365 D BtGatt.ScanManager: handling starting scan
,08-17 19:17:01.151  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-17 19:17:01.151  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 19:17:01.151  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 19:17:01.151  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-17 19:17:01.161  3213  3287 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-17 19:17:01.161  3213  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:17:01.161  3213  3365 D BtGatt.ScanManager: allow scan with filters
08-17 19:17:01.161  3213  3365 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-17 19:17:01.161  3213  3365 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
,08-17 19:17:01.161  3213  3287 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-17 19:17:01.161  7190  7267 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 19:17:01.161  3213  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:17:01.161  7190  7267 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-17 19:17:01.161  7190  7190 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 19:17:01.161  3213  3365 D BtGatt.ScanManager: Starting BLE batch scan
08-17 19:17:01.161  3213  3365 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-17 19:17:01.161  3213  3287 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-17 19:17:01.161  3213  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:17:01.161  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 19:17:01.171  3213  3287 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-17 19:17:01.171  3213  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:17:01.171  7190  7267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-17 19:17:01.171  7190  7267 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-17 19:17:01.171  7190  7267 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 19:17:01.171  7190  7267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 19:17:01.171  7190  7267 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 19:17:01.181  7190  7267 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 19:17:01.181  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:17:01.181  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-17 19:17:01.181  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-17 19:17:01.181  7190  7267 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a8ce539 removed from the list
,08-17 19:17:01.181  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:17:01.181  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eeb277e removed from the list
,08-17 19:17:01.181  7190  7267 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 19:17:01.181  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 19:17:01.181  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:17:01.181  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-17 19:17:01.181  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:17:01.181  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 19:17:01.181  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 19:17:01.181  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 19:17:01.181  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:17:01.181  7190  7267 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eeb277e not in the list
08-17 19:17:01.181  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-17 19:17:01.181  7190  7267 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-17 19:17:01.191  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-17 19:17:01.191  1020  1129 E WifiNative-wlan0: do suspend true
,08-17 19:17:01.191  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-17 19:17:01.191  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 19:17:01.191  3213  3223 D BtGatt.GattService: stopScan() - queue size =1
,08-17 19:17:01.191  3213  3365 D BtGatt.ScanManager: filter size is 1
,08-17 19:17:01.201  3213  3365 D BtGatt.ScanManager: delete FilterIndex - 7
,08-17 19:17:01.201  3213  3362 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-17 19:17:01.201  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 19:17:01.201  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 19:17:01.201  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 19:17:01.201  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 19:17:01.201  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 19:17:01.201  3213  3287 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-17 19:17:01.201  3213  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:17:01.201  3213  3365 D BtGatt.ScanManager: stopping BLe Batch
08-17 19:17:01.201  7190  7267 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 19:17:01.201  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-17 19:17:01.201  7190  7267 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-17 19:17:01.201  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 19:17:01.201  3213  3287 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-17 19:17:01.201  3213  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:17:01.201  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:17:01.201  3213  3365 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-17 19:17:01.211  7190  7190 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 19:17:01.211  7190  7190 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 19:17:01.211  7190  7190 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 19:17:01.211  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:17:01.211  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:17:01.211  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:17:01.211  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ccd9bf5 removed from the list
08-17 19:17:01.211  7190  7267 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:17:01.211  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:17:01.211  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:17:01.211  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 19:17:01.211  7190  7267 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21cd152c removed from the list
08-17 19:17:01.211  7190  7267 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 19:17:01.211  7190  7267 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e290271 added. We now have 2 listener(s)
,08-17 19:17:01.211  3213  3287 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-17 19:17:01.211  3213  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:17:01.211  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-17 19:17:01.211  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:17:01.211  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 19:17:01.211  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:17:01.211  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a9aa856 added. We now have 9 listener(s)
08-17 19:17:01.211  7190  7267 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 19:17:01.211  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 19:17:01.221  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:17:01.221  7190  7267 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:17:01.221  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:17:01.221  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:17:01.221  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:17:01.221  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:17:01.221  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:17:01.221  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:17:01.221  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:17:01.221  1020  1128 D WifiP2pService: InactiveState{ what=143375 }
,08-17 19:17:01.221  1020  1129 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-17 19:17:01.221  1020  1129 E WifiStateMachine: VerifyingLinkState enter
,08-17 19:17:01.231  1020  1128 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-17 19:17:01.231  7190  7267 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:17:01.231  7190  7267 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 19:17:01.231  7190  7267 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 19:17:01.231  7190  7267 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28faddc4 added. We now have 3 listener(s)
,08-17 19:17:01.231  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:17:01.231  1020  1131 E ConnectivityService: updateNetworkInfo()
,08-17 19:17:01.231  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:17:01.231  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-17 19:17:01.231  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:17:01.231  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 19:17:01.231  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:17:01.231  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2bfa54ad added. We now have 10 listener(s)
08-17 19:17:01.231  7190  7267 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:17:01.231  7190  7267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 19:17:01.231  7190  7267 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 19:17:01.231  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 19:17:01.231  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:17:01.231  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 19:17:01.231  1020  1131 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
08-17 19:17:01.231  1020  1131 D ConnectivityService: Adding iface wlan0 to network 504
,08-17 19:17:01.241  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-17 19:17:01.241  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 19:17:01.241  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-17 19:17:01.241  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:17:01.241  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:17:01.241  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:17:01.241  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-17 19:17:01.241  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 19:17:01.241  1020  1148 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,08-17 19:17:01.241  1020  1148 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-17 19:17:01.241  1020  1148 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-17 19:17:01.241  1020  1148 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-17 19:17:01.241  1020  1148 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-17 19:17:01.251  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
08-17 19:17:01.251  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:17:01.251  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-17 19:17:01.251  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:17:01.251  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:17:01.251  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:17:01.251  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:17:01.261  1020  1129 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,08-17 19:17:01.261  1020  1340 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 19:17:01.261  1020  1340 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-17 19:17:01.261  1020  1131 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,08-17 19:17:01.261  1020  1340 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:17:01.261  1020  1131 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
08-17 19:17:01.261  1020  1340 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:17:01.261  1020  1340 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-17 19:17:01.261  1020  1131 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
08-17 19:17:01.261  1020  1131 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-17 19:17:01.261  1020  1131 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
08-17 19:17:01.271  1640  1640 I Hs20UtilService: Starting #22,
,08-17 19:17:01.271  1020  1131 D ConnectivityService: LTETest block dns file not exists
08-17 19:17:01.271  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-17 19:17:01.271  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-17 19:17:01.271  4844  4844 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-17 19:17:01.271  1020  1020 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-17 19:17:01.271  4844  4844 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-17 19:17:01.271  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
08-17 19:17:01.271  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 19:17:01.271  7190  7267 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-17 19:17:01.281  1020  1131 V NetworkStats: updateIfacesLocked()
08-17 19:17:01.281  1020  1131 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:17:01.281  1020  1131 V NetworkStats: performPollLocked(flags=0x1)
,08-17 19:17:01.281  1020  1129 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-17 19:17:01.281  1020  1131 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 19:17:01.281  1020  1131 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 19:17:01.281  1640  1699 I Hs20UtilService: Message received 5007
,08-17 19:17:01.281  3213  3223 D BtGatt.GattService: registerClient() - UUID=05ae90ab-198f-4401-8280-215715a5862b
08-17 19:17:01.281  1020  1131 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:17:01.281  1020  1131 V NetworkStats: performPollLocked() took 3ms
,08-17 19:17:01.281  1020  1129 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-17 19:17:01.281  1020  1020 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-17 19:17:01.281  1020  1020 I WifiTrafficPoller: mBoosterFLAG : 0
,08-17 19:17:01.281  1020  1020 I WifiTrafficPoller: current booster mode : FullMode
08-17 19:17:01.291  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-17 19:17:01.291  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:17:01.291  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 19:17:01.291  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:17:01.291  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:17:01.291  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:17:01.291  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:17:01.301  1020  1131 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,08-17 19:17:01.301  1020  1131 E ConnectivityService: updateNetworkInfo()
08-17 19:17:01.301  1020  1131 E ConnectivityService: updateNetworkInfo()
08-17 19:17:01.301  1020  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-17 19:17:01.301  1180  1180 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:17:01.301  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-17 19:17:01.301  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:17:01.301  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:17:01.301  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:17:01.301  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:17:01.301  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:17:01.301  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:17:01.301  1020  1131 V NetworkStats: updateIfacesLocked()
08-17 19:17:01.301  1020  1131 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:17:01.301  1020  1131 V NetworkStats: performPollLocked(flags=0x1)
,08-17 19:17:01.301  1020  1131 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-17 19:17:01.311  1020  1131 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 19:17:01.311  1020  1131 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:17:01.311  1020  1131 V NetworkStats: performPollLocked() took 5ms
,08-17 19:17:01.311  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:17:01.311  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:17:01.311  1020  1131 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504],
08-17 19:17:01.311  1020  7901 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-17 19:17:01.311  1020  1131 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-17 19:17:01.311  1020  7901 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected,
08-17 19:17:01.311  1020  1131 D ConnectivityService:    accepting network in place of null
08-17 19:17:01.311  1020  7901 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-17 19:17:01.311  1020  7901 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
08-17 19:17:01.311  1020  7901 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-17 19:17:01.311   278   984 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-17 19:17:01.311   278   984 D Netd    : getNetworkForDns: using netid 504 for uid 1000
08-17 19:17:01.311  1020  1128 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-17 19:17:01.311  1477  1477 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-17 19:17:01.311  1477  1477 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 19:17:01.311  1020  1129 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,08-17 19:17:01.321  1020  1131 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-17 19:17:01.321  1020  1131 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
08-17 19:17:01.321  1020  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-17 19:17:01.321  1020  1131 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,08-17 19:17:01.321  3213  3287 D BtGatt.GattService: onClientRegistered() - UUID=05ae90ab-198f-4401-8280-215715a5862b, clientIf=6,
08-17 19:17:01.321  1020  1131 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-17 19:17:01.321  7190  7200 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-17 19:17:01.321  1020  1020 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,08-17 19:17:01.321  1020  1134 D Tethering: MasterInitialState.processMessage what=3
08-17 19:17:01.321  3213  3375 D BtGatt.GattService: start scan with filters
08-17 19:17:01.321  1020  1126 V NetworkStats: updateIfacesLocked()
08-17 19:17:01.321  1020  1049 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-17 19:17:01.321  1020  1126 V NetworkStats: performPollLocked(flags=0x1)
08-17 19:17:01.321  1020  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:17:01.321  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
08-17 19:17:01.321  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 19:17:01.321  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 19:17:01.321  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-17 19:17:01.321  1180  1743 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-17 19:17:01.321  1020  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 19:17:01.321  1020  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 19:17:01.331  3213  3365 D BtGatt.ScanManager: handling starting scan
,08-17 19:17:01.331  1020  1126 D NtpTrustedTime: currentTimeMillis() cache hit,
08-17 19:17:01.331  1020  1126 V NetworkStats: performPollLocked() took 4ms
08-17 19:17:01.331  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:17:01.331  3213  3287 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-17 19:17:01.331  3213  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:17:01.331  3213  3365 D BtGatt.ScanManager: allow scan with filters
08-17 19:17:01.331  3213  3365 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-17 19:17:01.331  3213  3365 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6
08-17 19:17:01.331  3213  3287 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-17 19:17:01.331  3213  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:17:01.331  3213  3365 D BtGatt.ScanManager: Starting BLE batch scan
08-17 19:17:01.331  3213  3365 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-17 19:17:01.331  1180  1180 D StatusBar.NetworkController: EthernetConnected: false
08-17 19:17:01.331  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:17:01.331  1180  1180 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-17 19:17:01.331  1020  1127 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-17 19:17:01.331  1180  1180 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-17 19:17:01.331  1180  1180 D StatusBar.NetworkController: updateDataNetType()
08-17 19:17:01.331  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:17:01.331  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:17:01.331  3213  3287 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-17 19:17:01.331  3213  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:17:01.331  7190  7267 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
,08-17 19:17:01.331  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-17 19:17:01.331  1180  1180 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-17 19:17:01.341  7190  7267 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-17 19:17:01.341  7190  7190 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 19:17:01.341  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:17:01.341  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:17:01.341  3213  3287 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-17 19:17:01.341  3213  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:17:01.341  1180  1180 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-17 19:17:01.341  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 19 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
,08-17 19:17:01.341  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
08-17 19:17:01.341  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,08-17 19:17:01.341  1180  1180 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:17:01.341  1020  1506 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 19:17:01.341  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-17 19:17:01.341  1020  1506 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-17 19:17:01.341  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:17:01.341  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:17:01.341  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:17:01.341  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:17:01.341  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 19:17:01.341  1020  1506 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:17:01.341  1020  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:17:01.341  1020  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 19:17:01.341  1640  1640 I Hs20UtilService: Starting #23
,08-17 19:17:01.341  1640  1699 I Hs20UtilService: Message received 5007
,08-17 19:17:01.351  4844  4844 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-17 19:17:01.351  4844  4844 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-17 19:17:01.351  4844  4844 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,08-17 19:17:01.351  7190  7267 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:17:01.351  7190  7267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:17:01.351  7190  7267 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:17:01.351  7190  7267 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:17:01.351  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:17:01.351  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 19:17:01.351  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 19:17:01.351  7190  7267 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e290271 removed from the list
08-17 19:17:01.351  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:17:01.351  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a9aa856 removed from the list
08-17 19:17:01.351  7190  7267 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:17:01.351  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:17:01.351  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-17 19:17:01.351  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-17 19:17:01.351  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:17:01.351  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 19:17:01.351  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:17:01.351  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:17:01.351  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:17:01.351  7190  7267 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a9aa856 not in the list
,08-17 19:17:01.351  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 19:17:01.351  7190  7267 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
08-17 19:17:01.351  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
08-17 19:17:01.351  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 19:17:01.351  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-17 19:17:01.351  4844  4844 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-17 19:17:01.351  4844  4844 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
08-17 19:17:01.351  4844  4844 I NearbySettings: MountReceiver.onReceive - Keep current state
08-17 19:17:01.351  3213  3375 D BtGatt.GattService: stopScan() - queue size =1,
08-17 19:17:01.351  3213  3365 D BtGatt.ScanManager: filter size is 1
08-17 19:17:01.351  3213  3365 D BtGatt.ScanManager: delete FilterIndex - 8
08-17 19:17:01.351  3213  3362 D BtGatt.GattService: unregisterClient() - clientIf=6
08-17 19:17:01.351  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 19:17:01.351  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 19:17:01.351  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 19:17:01.351  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 19:17:01.351  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 19:17:01.351  3213  3287 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-17 19:17:01.351  3213  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:17:01.351  3213  3365 D BtGatt.ScanManager: stopping BLe Batch
08-17 19:17:01.361  7190  7267 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 19:17:01.361  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-17 19:17:01.361  7190  7267 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 19:17:01.361  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 19:17:01.361  3213  3287 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-17 19:17:01.361  3213  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:17:01.361  3213  3365 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-17 19:17:01.361  3213  3287 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-17 19:17:01.361  3213  3287 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:17:01.361  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:17:01.361  7190  7190 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:17:01.371  7190  7190 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:17:01.371  7190  7190 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 19:17:01.371  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:17:01.371  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:17:01.371  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:17:01.371  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2bfa54ad removed from the list
,08-17 19:17:01.371  7190  7267 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:17:01.371  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:17:01.371  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:17:01.371  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 19:17:01.371  7190  7267 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28faddc4 removed from the list
,08-17 19:17:01.371  7190  7267 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 19:17:01.371  7190  7267 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4148ea9 added. We now have 2 listener(s)
,08-17 19:17:01.371  1020  1506 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-17 19:17:01.371  1020  1506 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-17 19:17:01.371  1020  1506 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:17:01.371  1020  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:17:01.371  1020  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-17 19:17:01.371  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-17 19:17:01.371  1640  1640 I Hs20UtilService: Starting #24
08-17 19:17:01.371  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:17:01.371  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 19:17:01.371  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:17:01.371  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fee6c2e added. We now have 9 listener(s)
08-17 19:17:01.371  7190  7267 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:17:01.371  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 19:17:01.371  4844  4844 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-17 19:17:01.371  1640  1699 I Hs20UtilService: Message received 5007
,08-17 19:17:01.371  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:17:01.371  4844  4844 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-17 19:17:01.381  7190  7267 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:17:01.381  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:17:01.381  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:17:01.381  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:17:01.381  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:17:01.381  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:17:01.381  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:17:01.381  7190  7267 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 19:17:01.381  7190  7267 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 19:17:01.381  7190  7267 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 19:17:01.381  7190  7267 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 19:17:01.381  7190  7267 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ad6215c added. We now have 3 listener(s)
,08-17 19:17:01.391  1020  3827 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-17 19:17:01.391  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:17:01.391  1020  1266 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
,08-17 19:17:01.391  1020  1266 D SecContentProvider2: mCursor = null
,08-17 19:17:01.391  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-17 19:17:01.391  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:17:01.391  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 19:17:01.391  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:17:01.391  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47e6c65 added. We now have 10 listener(s)
08-17 19:17:01.391  7190  7267 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:17:01.391  7190  7267 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:17:01.391  7190  7267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:17:01.391  7190  7267 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:17:01.391  7190  7267 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:17:01.391  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:17:01.391  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:17:01.391  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 19:17:01.391  7190  7267 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4148ea9 removed from the list
08-17 19:17:01.391  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:17:01.391  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fee6c2e removed from the list
,08-17 19:17:01.391  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:17:01.391  7190  7267 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:17:01.391  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:17:01.391  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:17:01.391  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:17:01.391  1020  3827 D SecContentProvider2: uri = 15 selection = getToastGravity
08-17 19:17:01.391  1020  3827 D SecContentProvider2: mCursor = null
,08-17 19:17:01.391  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:17:01.391  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:17:01.391  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:17:01.391  7190  7267 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fee6c2e not in the list
08-17 19:17:01.391  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:17:01.391  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:17:01.391  1020  1139 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
08-17 19:17:01.391  1020  1139 D SecContentProvider2: mCursor = null
,08-17 19:17:01.401  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-17 19:17:01.401  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:17:01.401  7190  7267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:17:01.401  7190  7267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47e6c65 removed from the list,
08-17 19:17:01.401  7190  7267 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:17:01.401  7190  7267 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:17:01.401  7190  7267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:17:01.401  7190  7267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 19:17:01.401  7190  7267 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ad6215c removed from the list
08-17 19:17:01.401  7190  7267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-17 19:17:01.401  7190  7267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-17 19:17:01.401  7190  7267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-17 19:17:01.401  7190  7267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 19:17:01.401  7190  7267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-17 19:17:01.401  7190  7267 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-17 19:17:01.401  1020  7901 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-17 19:17:01.401  1020  1341 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
,08-17 19:17:01.401  1020  1341 D SecContentProvider2: mCursor = null
,08-17 19:17:01.401  1020  1509 D SecContentProvider2: uri = 15 selection = getToastEnabledState
,08-17 19:17:01.401  1020  1509 D SecContentProvider2: mCursor = null
08-17 19:17:01.401  1020  1032 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
08-17 19:17:01.401  1020  1032 D SecContentProvider2: mCursor = null
,08-17 19:17:01.411  7190  7941 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1474, name: My test thread name)
,08-17 19:17:01.411  7190  7941 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1474, thread name: My test thread name)
08-17 19:17:01.411  7190  7941 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1474, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-17 19:17:01.411  7190  7942 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1476, name: My test thread name)
08-17 19:17:01.411  7190  7942 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1476, thread name: My test thread name)
08-17 19:17:01.411  7190  7942 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1476, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-17 19:17:01.411  7190  7267 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-17 19:17:01.411  7190  7267 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-17 19:17:01.411  7190  7267 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-17 19:17:01.411  7190  7267 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-17 19:17:01.421  7190  7267 D com.test.thalitest.ThaliTestRunner: Total duration: 23246 ms
,08-17 19:17:01.421  7190  7267 I jxcore-log: Total number of executed tests:  80
08-17 19:17:01.421  7190  7267 I jxcore-log: 
08-17 19:17:01.421  7190  7267 I jxcore-log: Number of passed tests:  80
08-17 19:17:01.421  7190  7267 I jxcore-log: 
08-17 19:17:01.421  7190  7267 I jxcore-log: Number of failed tests:  0
08-17 19:17:01.421  7190  7267 I jxcore-log: 
,08-17 19:17:01.421  7190  7267 I jxcore-log: Number of ignored tests:  0
08-17 19:17:01.421  7190  7267 I jxcore-log: 
08-17 19:17:01.421  7190  7267 I jxcore-log: Total duration:  23246
,08-17 19:17:01.421  7190  7267 I jxcore-log: 
08-17 19:17:01.421  7190  7267 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-17 19:17:01.421  7190  7267 I jxcore-log: 
,08-17 19:17:01.421  7190  7267 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:17:01.421  7190  7267 I jxcore-log: 
08-17 19:17:01.421  7190  7267 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:17:01.421  7190  7267 I jxcore-log: 
08-17 19:17:01.431  7190  7267 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:17:01.431  7190  7267 I jxcore-log: 
08-17 19:17:01.431  7190  7267 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:17:01.431  7190  7267 I jxcore-log: 
08-17 19:17:01.431  7190  7267 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:17:01.431  7190  7267 I jxcore-log: 
08-17 19:17:01.431  7190  7267 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:17:01.431  7190  7267 I jxcore-log: 
,08-17 19:17:01.431  7190  7190 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-17 19:17:01.431  7190  7267 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:17:01.431  7190  7267 I jxcore-log: 
08-17 19:17:01.431   258   258 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
08-17 19:17:01.431  7190  7267 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 19:17:01.431  7190  7267 I jxcore-log: 
,08-17 19:17:01.431  7190  7267 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 19:17:01.431  7190  7267 I jxcore-log: 
,08-17 19:17:01.441  7190  7267 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 19:17:01.441  7190  7267 I jxcore-log: 
,08-17 19:17:01.441  7190  7267 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 19:17:01.441  7190  7267 I jxcore-log: 
,08-17 19:17:01.441  7190  7267 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 19:17:01.441  7190  7267 I jxcore-log: 
08-17 19:17:01.441  7190  7267 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 19:17:01.441  7190  7267 I jxcore-log: 
,08-17 19:17:01.441  7190  7267 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 19:17:01.441  7190  7267 I jxcore-log: 
,08-17 19:17:01.441  7190  7267 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 19:17:01.441  7190  7267 I jxcore-log: 
,08-17 19:17:01.441  7190  7267 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 19:17:01.441  7190  7267 I jxcore-log: 
,08-17 19:17:01.441  7190  7267 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 19:17:01.441  7190  7267 I jxcore-log: 
,08-17 19:17:01.441  7190  7267 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 19:17:01.441  7190  7267 I jxcore-log: 
,08-17 19:17:01.441  7190  7267 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"},
08-17 19:17:01.441  7190  7267 I jxcore-log: 
,08-17 19:17:01.451  7190  7267 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 19:17:01.451  7190  7267 I jxcore-log: 
,08-17 19:17:01.451  7190  7267 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"},
08-17 19:17:01.451  7190  7267 I jxcore-log: 
,08-17 19:17:01.451  7190  7267 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 19:17:01.451  7190  7267 I jxcore-log: 
,08-17 19:17:01.451  7190  7267 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
08-17 19:17:01.451  7190  7267 I jxcore-log: 
,08-17 19:17:01.451  7190  7267 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 19:17:01.451  7190  7267 I jxcore-log: 
,08-17 19:17:01.451  7190  7267 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 19:17:01.451  7190  7267 I jxcore-log: 
,08-17 19:17:01.451  7190  7267 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 19:17:01.451  7190  7267 I jxcore-log: 
,08-17 19:17:01.451  7190  7267 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 19:17:01.451  7190  7267 I jxcore-log: 
,08-17 19:17:01.451  1020  1747 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1020,
08-17 19:17:01.451  7190  7267 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 19:17:01.451  7190  7267 I jxcore-log: 
,08-17 19:17:01.451  7190  7267 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:17:01.451  7190  7267 I jxcore-log: 
,08-17 19:17:01.461  1180  1180 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-17 19:17:01.461  1020  7901 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 17 Aug 2016 17:17:01 GMT], X-Android-Received-Millis=[1471454221466], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471454221435]}
,08-17 19:17:01.461  1020  7901 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-17 19:17:01.461  1020  7901 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,08-17 19:17:01.461  1020  1131 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
08-17 19:17:01.461  1020  1131 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-17 19:17:01.461  1020  1131 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
08-17 19:17:01.461  1020  1131 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,08-17 19:17:01.461  1020  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-17 19:17:01.461  1180  1743 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-17 19:17:01.471  1180  1180 D StatusBar.NetworkController: EthernetConnected: false
,08-17 19:17:01.471  1180  1180 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-17 19:17:01.471  1180  1180 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-17 19:17:01.471  1180  1180 D StatusBar.NetworkController: updateDataNetType()
,08-17 19:17:01.471  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-17 19:17:01.471  1180  1180 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-17 19:17:01.471  1180  1180 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,08-17 19:17:01.471  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 19 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
,08-17 19:17:01.471  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
08-17 19:17:01.471  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
08-17 19:17:01.471  1180  1180 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 19:17:01.481  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-17 19:17:01.481  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:17:01.481  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:17:01.481  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:17:01.481  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:17:01.561  7190  7190 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 19:17:01.571  7190  7267 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
08-17 19:17:01.571  7190  7267 I jxcore-log: 
,08-17 19:17:01.701  7944  7944 D AndroidRuntime: 
08-17 19:17:01.701  7944  7944 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-17 19:17:01.701  7944  7944 D AndroidRuntime: CheckJNI is OFF
,08-17 19:17:01.701  7944  7944 D AndroidRuntime: readGMSProperty: start
08-17 19:17:01.701  7944  7944 D AndroidRuntime: readGMSProperty: already setted!!
08-17 19:17:01.701  7944  7944 D AndroidRuntime: propertySet: couldn't set property (it is from app),
08-17 19:17:01.701  7944  7944 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-17 19:17:01.701  7944  7944 D AndroidRuntime: readGMSProperty: end
08-17 19:17:01.701  7944  7944 D AndroidRuntime: addProductProperty: start,
,08-17 19:17:01.711  7190  7190 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-17 19:17:01.711  7190  7267 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
08-17 19:17:01.711  7190  7267 I jxcore-log: 
,08-17 19:17:01.821  1020  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 19:17:01.821  7944  7944 E AffinityControl: AffinityControl: registerfunction enter
,08-17 19:17:01.831  1020  1044 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-17 19:17:01.841  1020  1045 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-17 19:17:01.841  7190  7190 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:17:01.841  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:17:01.841  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:17:01.841  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:17:01.841  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:17:01.841  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:17:01.841  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:17:01.841  7190  7190 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 19:17:01.851  7190  7190 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 19:17:01.851  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:17:01.851  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:17:01.851  7944  7944 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-17 19:17:01.851  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:17:01.851  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:17:01.851  7190  7267 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:17:01.851  7190  7267 I jxcore-log: 
,08-17 19:17:01.861  1020  1341 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
08-17 19:17:01.861  1020  1341 D PackageManager: START PACKAGE DELETE: observer{1039227818}
08-17 19:17:01.861  1020  1341 D PackageManager: pkg{<packageName>}
08-17 19:17:01.861  1020  1341 D PackageManager: user{0},
08-17 19:17:01.861  1020  1341 D PackageManager: caller{2000}
08-17 19:17:01.861  1020  1341 D PackageManager: flags{2}
08-17 19:17:01.861  1020  1341 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-17 19:17:01.861  1020  1341 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true,
,08-17 19:17:01.871  1020  1341 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-17 19:17:01.871  1020  1341 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-17 19:17:01.871  7190  7190 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-17 19:17:01.871  7190  7267 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 19:17:01.871  7190  7267 I jxcore-log: 
,08-17 19:17:01.871  7954  7954 E Zygote  : MountEmulatedStorage()
08-17 19:17:01.871  1020  1045 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7954 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-17 19:17:01.871  7954  7954 E Zygote  : v2
08-17 19:17:01.871  7954  7954 I libpersona: KNOX_SDCARD checking this for 1000
08-17 19:17:01.871  7954  7954 I libpersona: KNOX_SDCARD not a persona
08-17 19:17:01.871  7954  7954 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:17:01.871  1020  1060 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0,
08-17 19:17:01.871  1020  1060 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-17 19:17:01.871  1020  1060 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-17 19:17:01.871  1020  1060 D ApplicationPolicy: getApplicationUninstallationEnabled
08-17 19:17:01.871  1020  1060 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
08-17 19:17:01.871  7954  7954 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:17:01.881  7954  7954 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:17:01.881  1020  1060 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
,08-17 19:17:01.911  7954  7954 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:17:01.911  7954  7954 D ActivityThread: Added TimaKeyStore provider
,08-17 19:17:02.001  1020  1045 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
08-17 19:17:02.001  1020  1045 I ActivityManager: Killing 7190:com.test.thalitest/u0a170 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-17 19:17:02.011  1020  1045 I ActivityManager:   Force finishing activity ActivityRecord{da0c8c3 u0 com.test.thalitest/.MainActivity t163}
,08-17 19:17:02.011  1020  1045 D InputDispatcher: Focus left window: 7190
,08-17 19:17:02.011   258   452 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
,08-17 19:17:02.011  7954  7954 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-17 19:17:02.011  7954  7954 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-17 19:17:02.011  7954  7954 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-17 19:17:02.021   258  1100 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,08-17 19:17:02.031  1020  1045 D InputDispatcher: Focused application released
,08-17 19:17:02.041  1020  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-17 19:17:02.041  1020  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-17 19:17:02.041  1020  1060 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,08-17 19:17:02.061  1020  1060 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-17 19:17:02.081  7954  7954 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-17 19:17:02.081  7954  7954 I PCWCLIENTTRACE_PushUtil: sales region : global
08-17 19:17:02.081  7954  7954 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-17 19:17:02.081  7954  7954 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-17 19:17:02.091  2847  2847 I art     : Explicit concurrent mark sweep GC freed 17386(1024KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 820us total 30.788ms
,08-17 19:17:02.091  1020  1102 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-17 19:17:02.101  1894  1894 E SamsungIME: mOCRHelper is null
08-17 19:17:02.101  1020  1020 D RCPManagerService: PackageReceiver onReceive()
,08-17 19:17:02.101  1020  1020 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-17 19:17:02.101  1764  1958 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-17 19:17:02.101  1020  1020 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-17 19:17:02.101  1020  1020 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-17 19:17:02.101  1020  1020 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,08-17 19:17:02.111  1020  1266 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
08-17 19:17:02.111  1020  1266 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
08-17 19:17:02.111  1020  1266 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
08-17 19:17:02.111  1020  1266 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,08-17 19:17:02.121  1020  1266 I ActivityManager: Killing 7448:com.sec.android.diagmonagent/1000 (adj 15): empty #21
,08-17 19:17:02.121  1020  1020 I OTPFW   : ProvisionData::getAllEntries Enter
,08-17 19:17:02.121  1020  1020 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-17 19:17:02.131  1465  1465 D PersonaManager: isKioskContainerExistOnDevice,
,08-17 19:17:02.151  1465  1465 D RegisteredServicesCache: empty dynamic service
,08-17 19:17:02.171  1020  1044 D EnterpriseDeviceManagerService: Package has changed for user 0
08-17 19:17:02.171  1020  1044 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
08-17 19:17:02.171  1020  1044 W TextServicesManagerService: no available spell checker services found
,08-17 19:17:02.181  1020  1126 D NtpTrustedTime: currentTimeMillis() cache hit,
08-17 19:17:02.181  1020  1126 V NetworkStats: removeUidsLocked() for UIDs [10170]
08-17 19:17:02.181  1020  1126 V NetworkStats: performPollLocked(flags=0x3)
08-17 19:17:02.181  1465  1465 D RegisteredComponentCache: Collect Tech packages for Knox
,08-17 19:17:02.181  1020  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 19:17:02.181  1020  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 19:17:02.191  1020  1126 V NetworkStats: performPollLocked() took 7ms
,08-17 19:17:02.191  1020  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:17:02.191  1465  1465 D PersonaManager: isKioskContainerExistOnDevice
,08-17 19:17:02.201  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 19:17:02.201  1020  1508 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,08-17 19:17:02.201  1020  1508 D SecContentProvider2: mCursor = null
,08-17 19:17:02.211  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:17:02.211  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:17:02.231  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 19:17:02.251  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 19:17:02.251  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 19:17:02.261  1020  1020 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-17 19:17:02.261  1020  1020 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-17 19:17:02.261  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-17 19:17:02.261  1020  1020 V EnterpriseBillingPolicy: uID is 10170
08-17 19:17:02.261  1020  1020 V EnterpriseBillingPolicy: Removed Packageuid is0
08-17 19:17:02.261  1020  1020 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-17 19:17:02.261  1020  1020 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-17 19:17:02.261  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-17 19:17:02.261  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-17 19:17:02.261  1020  1020 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-17 19:17:02.261  1020  1020 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-17 19:17:02.261  1020  1020 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-17 19:17:02.261  1020  1020 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
,08-17 19:17:02.271  1020  1165 D TaskPersister: removeObsoleteFile: deleting file=163_task.xml
,08-17 19:17:02.311  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-17 19:17:02.311  1020  1020 V EnterpriseBillingPolicy: uID is 10170
08-17 19:17:02.311  1020  1020 V EnterpriseBillingPolicy: Removed Packageuid is0
08-17 19:17:02.311  1020  1020 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-17 19:17:02.311  1020  1020 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-17 19:17:02.311  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-17 19:17:02.311  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-17 19:17:02.311  1020  3378 D SSRM:bc : MSG_TYPE_APP_REMOVED::
08-17 19:17:02.311  1020  1020 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-17 19:17:02.311  1020  1020 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-17 19:17:02.321  1020  1131 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-17 19:17:02.331  1020  1020 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-17 19:17:02.331  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:17:02.331  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:17:02.331  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:17:02.331  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:17:02.341  7971  7971 E Zygote  : MountEmulatedStorage(),
08-17 19:17:02.341  7971  7971 I libpersona: KNOX_SDCARD checking this for 10001
08-17 19:17:02.341  7971  7971 E Zygote  : v2
,08-17 19:17:02.341  7971  7971 I libpersona: KNOX_SDCARD not a persona
08-17 19:17:02.341  7971  7971 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:17:02.351  1020  1020 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7971 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-17 19:17:02.351  1020  1044 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-17 19:17:02.351  7971  7971 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:17:02.351  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
08-17 19:17:02.351  7971  7971 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-17 19:17:02.351  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 19:17:02.361  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 19:17:02.371  7971  7971 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:17:02.381  7971  7971 D ActivityThread: Added TimaKeyStore provider
,08-17 19:17:02.381  1020  1044 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-17 19:17:02.381  1020  1044 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 19:17:02.381  1020  1044 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-17 19:17:02.381  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 19:17:02.391  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 19:17:02.391  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 19:17:02.391  1020  1060 I art     : Explicit concurrent mark sweep GC freed 84553(5MB) AllocSpace objects, 15(240KB) LOS objects, 33% free, 23MB/35MB, paused 3.138ms total 257.433ms
,08-17 19:17:02.401  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-17 19:17:02.401  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-17 19:17:02.401  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 19:17:02.411  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-17 19:17:02.411  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-17 19:17:02.411  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-17 19:17:02.411  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-17 19:17:02.411  1020  1060 D PackageManager: delete codoeFile: 
,08-17 19:17:02.421  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 19:17:02.421  1020  1044 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-17 19:17:02.431  1020  1044 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-17 19:17:02.431  1020  1060 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
08-17 19:17:02.431  1020  1060 I AASA_removePackage: UID=10170 Target=com.test.thalitest
08-17 19:17:02.431  1020  1060 D PackageManager: result of delete: 1{1039227818}
,08-17 19:17:02.431  7944  7944 D AndroidRuntime: Shutting down VM
,08-17 19:17:02.441  1020  1060 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-17 19:17:02.441  1020  1060 D PackageManager: userId{-1}
08-17 19:17:02.441  1020  1060 D PackageManager: andCode{true}
,08-17 19:17:02.441  1020  1060 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-17 19:17:02.441  1020  1060 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:17:02.441  1020  1060 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:17:02.441  1020  1060 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:17:02.441  1020  1060 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:17:02.451  7988  7988 E Zygote  : MountEmulatedStorage()
08-17 19:17:02.451  7988  7988 E Zygote  : v2
08-17 19:17:02.451  7988  7988 I libpersona: KNOX_SDCARD checking this for 10003
08-17 19:17:02.451  7988  7988 I libpersona: KNOX_SDCARD not a persona
08-17 19:17:02.451  7988  7988 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:17:02.461  7988  7988 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:17:02.461  7988  7988 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:17:02.461  1020  1060 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7988 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-17 19:17:02.481  1020  1509 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-17 19:17:02.481  1020  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:17:02.481  1020  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:17:02.481  7988  7988 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 19:17:02.481  1020  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:17:02.481  1020  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:17:02.491  7988  7988 D ActivityThread: Added TimaKeyStore provider
,08-17 19:17:02.501  8003  8003 E Zygote  : MountEmulatedStorage()
,08-17 19:17:02.501  8003  8003 E Zygote  : v2
08-17 19:17:02.501  8003  8003 I libpersona: KNOX_SDCARD checking this for 1000
08-17 19:17:02.501  8003  8003 I libpersona: KNOX_SDCARD not a persona,
08-17 19:17:02.501  8003  8003 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:17:02.501  1020  1509 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=8003 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-17 19:17:02.501  8003  8003 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 19:17:02.501  8003  8003 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:17:02.501  1020  1509 I ActivityManager: Killing 7463:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-17 19:17:02.521  8003  8003 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:17:02.521  8003  8003 D ActivityThread: Added TimaKeyStore provider
,08-17 19:17:02.541  1020  1509 I ActivityManager: Killing 7480:com.sec.android.soagent/u0a31 (adj 15): empty #21
,08-17 19:17:02.561  8003  8003 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-17 19:17:02.571  1020  1131 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-17 19:17:02.571  1020  1131 V NetworkStats: updateIfacesLocked()
,08-17 19:17:02.571  1020  1131 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:17:02.571  1020  1131 V NetworkStats: performPollLocked(flags=0x1)
,08-17 19:17:02.571  1020  1131 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 19:17:02.571  1020  1131 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 19:17:02.571  1020  1131 V NetworkStats: performPollLocked() took 3ms
,08-17 19:17:02.571  1020  1131 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:17:02.581  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:17:02.581  1020  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:17:02.581  1020  1131 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,08-17 19:17:02.581  1020  1131 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,08-17 19:17:02.581  1180  1743 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-17 19:17:02.581  1180  1743 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-17 19:17:02.641  7944  7944 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-17 19:17:02.691  8003  8003 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-17 19:17:02.701  8003  8003 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !,
,08-17 19:17:02.701  8003  8003 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-17 19:17:02.701  8003  8003 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:,
08-17 19:17:02.701  8003  8003 I DIAGMON_AGENT: ./extraInfo: "NG700"
08-17 19:17:02.701  8003  8003 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,08-17 19:17:02.791  1020  1494 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,08-17 19:17:02.801  1020  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:17:02.801  1020  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:17:02.801  1020  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:17:02.801  1020  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:17:02.811  1020  1494 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=8021 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-17 19:17:02.811  8021  8021 E Zygote  : MountEmulatedStorage(),
08-17 19:17:02.811  8021  8021 E Zygote  : v2
08-17 19:17:02.811  8021  8021 I libpersona: KNOX_SDCARD checking this for 10008
08-17 19:17:02.811  8021  8021 I libpersona: KNOX_SDCARD not a persona
,08-17 19:17:02.821  8021  8021 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 19:17:02.821  8021  8021 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-17 19:17:02.821  8021  8021 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,08-17 19:17:02.841  8021  8021 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:17:02.841  8021  8021 D ActivityThread: Added TimaKeyStore provider

```
