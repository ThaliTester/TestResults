#### Test 82337235c858ce8_thali03_samsung-SM-A300FU Logs


```
--------- beginning of system
08-23 15:43:18.875  1019  1543 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
08-23 15:43:18.875  1019  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:18.875  1019  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:18.875  1019  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:18.875  1019  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:18.875  1019  3377 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
--------- beginning of main
08-23 15:43:18.895  6997  6997 E Zygote  : MountEmulatedStorage()
08-23 15:43:18.895  6997  6997 E Zygote  : v2
08-23 15:43:18.895  6997  6997 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 15:43:18.895  6997  6997 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 15:43:18.895  6997  6997 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-23 15:43:18.895  6997  6997 I libpersona: KNOX_SDCARD checking this for 10148
08-23 15:43:18.895  6997  6997 I libpersona: KNOX_SDCARD not a persona
08-23 15:43:18.895  1019  1543 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=6997 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
08-23 15:43:18.905  1019  1762 I ActivityManager: Killing 6558:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
08-23 15:43:18.915  6997  6997 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 15:43:18.915  6997  6997 D ActivityThread: Added TimaKeyStore provider
08-23 15:43:18.925  6967  6967 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
08-23 15:43:18.935  6967  6967 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-23 15:43:18.935  1019  1544 E EdmStorageProvider: Admin not in database, something went wrong
08-23 15:43:18.955  3774  6851 I qtaguid : Untagging socket 97
08-23 15:43:18.955  3774  3774 I ConfigFetchService: fetch service done; releasing wakelock
08-23 15:43:18.955  3774  3774 I ConfigFetchService: stopping self
,08-23 15:43:18.965   274   274 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb78e77c8
08-23 15:43:18.965   274   274 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
08-23 15:43:18.965   274   274 I rmt_storage: wakelock acquired: 1, error no: 42
08-23 15:43:18.965   274   341 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1215399800)
08-23 15:43:19.005  6997  6997 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
08-23 15:43:19.015   274   341 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
08-23 15:43:19.015  1019  4305 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
08-23 15:43:19.015   274   341 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
08-23 15:43:19.015  1019  4305 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:19.015   274   341 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1215399800) wakelock released: 1, error no: 0
08-23 15:43:19.015   274   341 I rmt_storage: 
08-23 15:43:19.015  1019  4305 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:19.015  1019  4305 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:19.025   274   274 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb78e77c8
08-23 15:43:19.015  1019  4305 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:19.035  7021  7021 E Zygote  : MountEmulatedStorage()
08-23 15:43:19.035  7021  7021 E Zygote  : v2
08-23 15:43:19.035  7021  7021 I libpersona: KNOX_SDCARD checking this for 1000
08-23 15:43:19.035  7021  7021 I libpersona: KNOX_SDCARD not a persona
08-23 15:43:19.035  1019  4305 I ActivityManager: Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=7021 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-23 15:43:19.035  1019  4305 I ActivityManager: Killing 6574:com.wsomacp/u0a23 (adj 15): empty #21
08-23 15:43:19.045  1019  4305 D ActivityManager: startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
08-23 15:43:19.045  1019  4305 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:19.045  1019  4305 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:19.045  1019  4305 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:19.045  1019  4305 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:19.055  7021  7021 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 15:43:19.055  7021  7021 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 15:43:19.055  7021  7021 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-23 15:43:19.065  7029  7029 E Zygote  : MountEmulatedStorage()
08-23 15:43:19.065  7029  7029 E Zygote  : v2
08-23 15:43:19.065  7029  7029 I libpersona: KNOX_SDCARD checking this for 10041
08-23 15:43:19.065  7029  7029 I libpersona: KNOX_SDCARD not a persona
08-23 15:43:19.065  7029  7029 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 15:43:19.065  1019  4305 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.smishing.PackageInstallReceiver: pid=7029 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
08-23 15:43:19.065  1019  4305 I ActivityManager: Killing 6581:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
08-23 15:43:19.075  7029  7029 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 15:43:19.075  7029  7029 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-23 15:43:19.105  7021  7021 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 15:43:19.105  7021  7021 D ActivityThread: Added TimaKeyStore provider
08-23 15:43:19.105  7029  7029 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 15:43:19.115  7029  7029 D ActivityThread: Added TimaKeyStore provider
08-23 15:43:19.135  7021  7021 W ResourcesManager: Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
08-23 15:43:19.135  7029  7029 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
08-23 15:43:19.135  7029  7029 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 15:43:19.135  7029  7029 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-23 15:43:19.135  7029  7029 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-23 15:43:19.135  7029  7029 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
08-23 15:43:19.155  1019  1137 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-23 15:43:19.155  6967  6967 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-23 15:43:19.155  1019  1137 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:19.155  1019  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:19.155  1019  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
08-23 15:43:19.155  6967  6967 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-23 15:43:19.155  1019  1031 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-23 15:43:19.155  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-23 15:43:19.155  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:19.155  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:19.155  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-23 15:43:19.175  6967  6967 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-23 15:43:19.175  6967  6967 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-23 15:43:19.175  1019  1514 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-23 15:43:19.185  1019  1514 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:19.185  1019  1514 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:19.185  1019  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-23 15:43:19.185  1019  1032 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-23 15:43:19.185  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-23 15:43:19.185  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:19.185  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:19.185  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-23 15:43:19.185   289   289 E SMD     : DCD OFF
08-23 15:43:19.235  6967  6967 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-23 15:43:19.235  6967  6967 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-23 15:43:19.235  6967  6967 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-23 15:43:19.235  6967  6967 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-23 15:43:19.235  6967  6967 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-23 15:43:19.235  6967  6967 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-23 15:43:19.235  6967  6967 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-23 15:43:19.235  6967  6967 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-23 15:43:19.245  6967  6967 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-23 15:43:19.245  6967  6967 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-23 15:43:19.245  6967  6967 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-23 15:43:19.245  6967  6967 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-23 15:43:19.245  6967  6967 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
08-23 15:43:19.255  7019  7019 D AndroidRuntime: 
08-23 15:43:19.255  7019  7019 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-23 15:43:19.255  7019  7019 D AndroidRuntime: CheckJNI is OFF
08-23 15:43:19.255  7019  7019 D AndroidRuntime: readGMSProperty: start
08-23 15:43:19.255  7019  7019 D AndroidRuntime: readGMSProperty: already setted!!
08-23 15:43:19.255  7019  7019 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-23 15:43:19.255  7019  7019 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-23 15:43:19.255  7019  7019 D AndroidRuntime: readGMSProperty: end
08-23 15:43:19.255  7019  7019 D AndroidRuntime: addProductProperty: start
08-23 15:43:19.265  6967  6967 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-23 15:43:19.265  6967  6967 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-23 15:43:19.295  6967  6967 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-23 15:43:19.295  6967  6967 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-23 15:43:19.295  6967  6967 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-23 15:43:19.355  1019  1544 I art     : Explicit concurrent mark sweep GC freed 19320(1131KB) AllocSpace objects, 1(22KB) LOS objects, 33% free, 22MB/34MB, paused 2.534ms total 147.412ms
08-23 15:43:19.355  1019  1544 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-23 15:43:19.355  1019  1544 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:19.355  1019  1544 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:19.355  1019  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-23 15:43:19.355  1019  1031 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
08-23 15:43:19.365  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:19.365  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:19.365  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:19.365  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:19.375  1019  1031 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7071 uid=10152 gids={50152, 9997} abi=armeabi-v7a
08-23 15:43:19.385  1019  1031 I ActivityManager: Killing 6604:com.sec.esdk.elm/u0a90 (adj 15): empty #21
08-23 15:43:19.395  7071  7071 E Zygote  : MountEmulatedStorage()
08-23 15:43:19.395  7071  7071 I libpersona: KNOX_SDCARD checking this for 10152
08-23 15:43:19.395  7071  7071 E Zygote  : v2
08-23 15:43:19.395  7071  7071 I libpersona: KNOX_SDCARD not a persona
08-23 15:43:19.395  7071  7071 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 15:43:19.395  7071  7071 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 15:43:19.395  7071  7071 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-23 15:43:19.395  7029  7029 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
08-23 15:43:19.405  1019  1031 I ActivityManager: Killing 6623:com.samsung.android.securitylogagent/1000 (adj 15): empty #21
08-23 15:43:19.405  7019  7019 E AffinityControl: AffinityControl: registerfunction enter
08-23 15:43:19.425  7019  7019 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-23 15:43:19.445  7071  7071 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 15:43:19.445  7071  7071 D ActivityThread: Added TimaKeyStore provider
08-23 15:43:19.455  6967  6967 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-23 15:43:19.455  1019  1137 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-23 15:43:19.455  1019  1545 E PersonaManagerService: inState():  stateMachine is null !!
08-23 15:43:19.455  1019  1545 I PersonaManagerService: PersonaId don't exist
08-23 15:43:19.455  1019  1545 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-23 15:43:19.455  1019  1137 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:19.455  1019  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:19.455  1019  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
08-23 15:43:19.465  1019  1545 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-23 15:43:19.475  1019  1545 W ActivityManager: mDVFSHelper.acquire()
08-23 15:43:19.485  1019  1545 D FocusedStackFrame: Set to : 0
08-23 15:43:19.495  1019  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:19.495  1019  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:19.495  1019  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:19.495  1019  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:19.495  1019  1050 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-23 15:43:19.495  1019  1050 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-23 15:43:19.505  1019  1545 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7092 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-23 15:43:19.505  1019  1545 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-23 15:43:19.515  1019  1545 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-23 15:43:19.515  7092  7092 I libpersona: KNOX_SDCARD checking this for 10170
08-23 15:43:19.515  1019  1545 D InputDispatcher: Focused application set to: xxxx
08-23 15:43:19.515  7092  7092 I libpersona: KNOX_SDCARD not a persona
08-23 15:43:19.515  7092  7092 E Zygote  : MountEmulatedStorage()
08-23 15:43:19.515  7092  7092 E Zygote  : v2
08-23 15:43:19.515  1019  1545 D InputDispatcher: Focus left window: 1507
08-23 15:43:19.515  7092  7092 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 15:43:19.515  7092  7092 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 15:43:19.515  7071  7071 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
08-23 15:43:19.515  7071  7071 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
08-23 15:43:19.515  7092  7092 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-23 15:43:19.515  1019  1050 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-23 15:43:19.515  1019  1050 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-23 15:43:19.515   258   258 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
08-23 15:43:19.525  7019  7019 D AndroidRuntime: Shutting down VM
08-23 15:43:19.545  6967  7090 D Ads     : Skipping gmscore version check
08-23 15:43:19.545  7071  7071 I TapandpayWidget:Utils: Clear T&P info.
08-23 15:43:19.545  7092  7092 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 15:43:19.545  7092  7092 D ActivityThread: Added TimaKeyStore provider
08-23 15:43:19.565  1019  4305 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
08-23 15:43:19.565  1019  4305 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
08-23 15:43:19.565  1019  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-23 15:43:19.565  1019  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
08-23 15:43:19.565  1019  4305 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:19.565  1019  4305 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:19.565  1019  4305 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
08-23 15:43:19.585  1019  1545 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-23 15:43:19.585  1019  1019 V ActivityManager: Display changed displayId=0
08-23 15:43:19.595  1019  1031 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-23 15:43:19.595  7071  7071 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
08-23 15:43:19.595  1019  1048 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-23 15:43:19.615  6967  6967 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-23 15:43:19.615  1019  1545 D PersonaManager: isKioskContainerExistOnDevice
08-23 15:43:19.625  3774  6853 W art     : Verification of void com.google.android.gms.games.broker.GameAgent.addGameBadgeOps(com.google.android.gms.common.internal.ClientContext, com.google.android.gms.games.server.api.MarketInstance, java.lang.String, java.util.ArrayList, int) took 187.773ms
08-23 15:43:19.635  1019  1137 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
08-23 15:43:19.635  1019  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:19.635  1019  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:19.635  1019  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:19.635  1019  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:19.655  7109  7109 E Zygote  : MountEmulatedStorage()
08-23 15:43:19.655  7109  7109 E Zygote  : v2
08-23 15:43:19.655  7109  7109 I libpersona: KNOX_SDCARD checking this for 10009
08-23 15:43:19.655  7109  7109 I libpersona: KNOX_SDCARD not a persona
08-23 15:43:19.655  7109  7109 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 15:43:19.665  7109  7109 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 15:43:19.665  7109  7109 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
08-23 15:43:19.665  1019  1137 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=7109 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
08-23 15:43:19.675  1019  1505 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-23 15:43:19.675  1019  1505 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:19.675  1019  1505 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:19.675  1019  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
08-23 15:43:19.675   258   451 I SurfaceFlinger: id=9 Removed Mauncher (5/9)
08-23 15:43:19.675   258   448 I SurfaceFlinger: id=9 Removed Mauncher (-2/9)
08-23 15:43:19.685  1019  1762 I ActivityManager: Killing 6654:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
08-23 15:43:19.685  1019  1019 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-23 15:43:19.695  1507  1507 V ActivityThread: updateVisibility : ActivityRecord{36279d79 token=android.os.BinderProxy@177826fa {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-23 15:43:19.695  1507  1507 D Launcher: onTrimMemory. Level: 20
08-23 15:43:19.705  7029  7029 W art     : Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 210.810ms
08-23 15:43:19.715  6781  6850 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 1026 ms] updated apps [took 1026 ms] 
08-23 15:43:19.725  1019  1514 I ActivityManager: Killing 6670:com.qualcomm.timeservice/1000 (adj 15): empty #21
08-23 15:43:19.725  7019  7019 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-23 15:43:19.735  7109  7109 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 15:43:19.735  7109  7109 D ActivityThread: Added TimaKeyStore provider
08-23 15:43:19.745  6967  6967 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-23 15:43:19.805  7092  7092 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-23 15:43:19.825  7092  7092 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 8704-8706)
08-23 15:43:19.825  7092  7092 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-23 15:43:19.835  1019  1514 I ActivityManager: Killing 6632:com.android.providers.calendar/u0a37 (adj 15): empty #21
08-23 15:43:19.855  7092  7092 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8a965f1}
08-23 15:43:19.855  7092  7092 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-23 15:43:19.855  7092  7092 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
08-23 15:43:19.865  6910  6986 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
08-23 15:43:19.865  6910  6986 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-23 15:43:19.865  6910  6986 I GAv4    :   adb logcat -s GAv4
08-23 15:43:19.895  6910  6986 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
08-23 15:43:19.895  1019  1545 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-23 15:43:19.905  7092  7092 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
08-23 15:43:19.905  7092  7092 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-23 15:43:19.915  7029  7029 W art     : Verification of com.sec.android.touchwiz.animator.TwDndHorizontalListAnimator com.android.mms.ArtClassLoader.createTwDndHorizontalListAnimator(android.content.Context) took 209.162ms
08-23 15:43:19.915  7029  7131 D Mms/ArtClassLoader: init before art
08-23 15:43:19.915  7029  7029 D Mms/TelephonyPermission: start operation mode monitor
08-23 15:43:19.925  6910  6986 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
08-23 15:43:19.935  7029  7029 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-23 15:43:19.935  7092  7092 E SysUtils: ApplicationContext is null in ApplicationStatus
08-23 15:43:19.945  7029  7029 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
08-23 15:43:19.945  7029  7029 D Mms/TelephonyPermission: isDefault true
08-23 15:43:19.945  7029  7029 D Mms/MmsApp: onCreate() com.android.mms
08-23 15:43:19.945  6910  6986 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.357.23.33
08-23 15:43:19.985  6910  7133 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
08-23 15:43:20.005  7092  7092 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-23 15:43:20.005  7092  7092 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-23 15:43:20.005  7092  7092 I Adreno-EGL: Build Date: 04/06/15 Mon
08-23 15:43:20.005  7092  7092 I Adreno-EGL: Local Branch: 
08-23 15:43:20.005  7092  7092 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-23 15:43:20.005  7092  7092 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-23 15:43:20.005  7092  7092 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
08-23 15:43:20.015  6910  6927 W art     : Suspending all threads took: 32.942ms
08-23 15:43:20.045  7029  7029 D Mms/MmsApp: [start]    initCountryIso consume time = 645.469739
08-23 15:43:20.045  1019  1514 D CountryDetector: The first listener is added
08-23 15:43:20.055  7029  7029 D Mms/MmsApp: [end]    initCountryIso consume time = 6.181875
08-23 15:43:20.055  7029  7029 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.102864
08-23 15:43:20.065  7029  7029 D Mms/MmsConfig: before partial update
08-23 15:43:20.105  7029  7029 D Mms/MmsConfig: Load Resize quality : 80
08-23 15:43:20.105  7029  7029 D EasySignUpManager_1.0.1: serviceId : 1, features : -1
08-23 15:43:20.105  7029  7029 D EasySignUpManager_1.0.1: isAuth is false
08-23 15:43:20.105  7029  7029 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
08-23 15:43:20.125  1019  1045 W ActivityManager: Activity pause timeout for ActivityRecord{322f56a3 u0 com.test.thalitest/.MainActivity t163}
08-23 15:43:20.145  7092  7092 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-23 15:43:20.145  1480  3290 D TP/MmsSmsProvider: query,matched:2117, calling pid = 7029
08-23 15:43:20.145  1480  3290 D TP/MmsSmsProvider: match 2117:Elapsed time : 4.142 ms
08-23 15:43:20.155  7029  7029 D EasySignUpManager_1.0.1: isAuth is false
08-23 15:43:20.155  7029  7029 D EasySignUpManager_1.0.1: getServiceStatus : serviceId (1) is OFF
08-23 15:43:20.155  7092  7092 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-23 15:43:20.155  7092  7092 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-23 15:43:20.155  7029  7029 E CscParser: mps_code.dat does not exist
08-23 15:43:20.155  7029  7029 E CscParser: customer_path =/system/csc/customer.xml
08-23 15:43:20.155  7029  7029 E CscParser: fileName + /system/csc/customer.xml
08-23 15:43:20.165  7092  7092 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-23 15:43:20.165  7092  7092 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-23 15:43:20.205  7029  7029 E CscParser: mps_code.dat does not exist
08-23 15:43:20.205  7029  7029 E CscParser: customer_path =/system/csc/customer.xml
08-23 15:43:20.205  7029  7029 E CscParser: fileName + /system/csc/customer.xml
08-23 15:43:20.215  7029  7029 D CscParser: getInstance fileName =/system/csc/customer.xml
08-23 15:43:20.215  7029  7029 D Mms/MmsConfig:  enable multiwindow = false
08-23 15:43:20.225  7029  7029 E Mms/MessageUtils: setCountryDetector : update country detector info 
08-23 15:43:20.225  7029  7029 E Mms/MessageUtils: updateCountryIso : update country iso info 
08-23 15:43:20.235  7029  7029 D Mms/MmsConfig: [end]    init() consume time = 180.527188
08-23 15:43:20.235  7029  7029 D Mms/Contact: [start]    init() consume time = 0.669114
08-23 15:43:20.235  1480  3290 D TP/MmsSmsProvider: query,matched:13, calling pid = 7029
08-23 15:43:20.235  1480  3290 D TP/MmsSmsProvider: match 13:Elapsed time : 1.054 ms
08-23 15:43:20.245  7029  7029 D Mms/Contact: [end]    init consume time = 13.037448
08-23 15:43:20.245  7029  7157 D Mms/DraftCache: [start]    rebuildCache consume time = 4.451719
08-23 15:43:20.265  7029  7029 D Mms/MethodReflector: getSubId is called
08-23 15:43:20.265  7029  7029 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
08-23 15:43:20.265  7029  7029 D Mms/MethodReflector: getTelephonyProperty is called
08-23 15:43:20.265  7029  7029 D Mms/DownloadManager: roaming -> false (slotId = 0)
08-23 15:43:20.265  7029  7029 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-23 15:43:20.265  7029  7029 D Mms/DownloadManager: auto download without roaming -> true
08-23 15:43:20.265  7029  7029 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
08-23 15:43:20.265  7029  7029 D Mms/MethodReflector: getSubId is called
08-23 15:43:20.265  1480  1495 D TP/MmsSmsProvider: query,matched:12, calling pid = 7029
08-23 15:43:20.265  7029  7029 D Mms/MethodReflector: getDefaultSmsSubId is called
08-23 15:43:20.265  7029  7029 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
08-23 15:43:20.265  7029  7029 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
08-23 15:43:20.265  7029  7029 D Mms/MethodReflector: getTelephonyProperty is called
08-23 15:43:20.265  7029  7029 D Mms/DownloadManager: roaming -> false (slotId = 1)
08-23 15:43:20.265  7029  7029 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
08-23 15:43:20.265  7029  7029 D Mms/DownloadManager: auto download without roaming -> true
08-23 15:43:20.265  7029  7029 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
08-23 15:43:20.265  7029  7029 D Mms/DownloadManager: auto download during roaming secondary -> false
08-23 15:43:20.265  7029  7029 D Mms/DownloadManager: mAutoDownload ------> true
08-23 15:43:20.265  1480  1495 D TP/MmsSmsProvider: match 12:Elapsed time : 2.321 ms
08-23 15:43:20.275  7029  7157 D Mms/DraftCache: [end]    rebuildCache consume time = 22.14724
08-23 15:43:20.305  7029  7029 D ComposerPerformance: 1471959800319 ms / [DONE] Composer constructor
08-23 15:43:20.305  7029  7029 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
08-23 15:43:20.315  7029  7029 I Mms/ReservationManager: ReservationManager()
08-23 15:43:20.315  7029  7029 I Mms/ReservationManager: resetAfterConnected()
08-23 15:43:20.315  1480  3596 D TP/MmsSmsProvider: query,matched:7, calling pid = 7029
08-23 15:43:20.325  1480  3596 D TP/MmsSmsProvider: match 7:Elapsed time : 4.541 ms
08-23 15:43:20.325  7029  7160 D Mms/Conversation: [start]    init() consume time = 50.765
08-23 15:43:20.325  7029  7029 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
08-23 15:43:20.325  1480  1703 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
08-23 15:43:20.325  1480  1703 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
08-23 15:43:20.335  1480  1703 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
08-23 15:43:20.335  1019  1544 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.filterinstaller, hostingType: broadcast
08-23 15:43:20.335  1480  1703 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
08-23 15:43:20.335  1019  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:20.335  1019  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:20.335  1019  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:20.335  1019  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:20.345  1480  1703 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
08-23 15:43:20.345  1480  1703 D TP/MmsSmsProvider: need read changed broadcast:false
08-23 15:43:20.345  7029  7029 D Mms/MmsApp: [end]    onCreate() consume time = 24.689323
08-23 15:43:20.355  7165  7165 E Zygote  : MountEmulatedStorage()
08-23 15:43:20.355  7165  7165 E Zygote  : v2
08-23 15:43:20.355  1019  1544 I ActivityManager: Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=7165 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-23 15:43:20.355  7165  7165 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 15:43:20.355  7165  7165 I libpersona: KNOX_SDCARD checking this for 1000
08-23 15:43:20.355  7165  7165 I libpersona: KNOX_SDCARD not a persona
08-23 15:43:20.355  1019  1544 I ActivityManager: Killing 6327:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
08-23 15:43:20.355  7029  7160 D Mms/Conversation: [end]    init consume time = 10.851041
08-23 15:43:20.365  7029  7160 D Mms/MessagingNotification: [start]    init() consume time = 3.434427
08-23 15:43:20.365  7029  7160 D Mms/MessagingNotification: [end]    init consume time = 2.524375
08-23 15:43:20.365  7092  7092 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-23 15:43:20.365  7165  7165 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 15:43:20.365  7029  7171 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 4.449532
08-23 15:43:20.365  7165  7165 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-23 15:43:20.375  1480  3596 D TP/MmsSmsProvider: query,matched:400, calling pid = 7029
08-23 15:43:20.375  1480  3290 D TP/MmsSmsProvider: query,matched:0, calling pid = 7029
08-23 15:43:20.375  1480  3290 V TP/MmsSmsProvider: getSimpleConversations entered.
08-23 15:43:20.375  1480  3290 D TP/MmsSmsProvider: match 0:Elapsed time : 1.147 ms
08-23 15:43:20.375  7029  7029 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=760]
08-23 15:43:20.375  7029  7029 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
08-23 15:43:20.385  7029  7131 D Mms/ArtClassLoader: init [DONE] art
08-23 15:43:20.385  7029  7172 D Mms/Synchronizer: [start]    doSync consume time = 15.729895
08-23 15:43:20.385  7029  7171 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 2.88974
08-23 15:43:20.385  1019  1762 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
08-23 15:43:20.385  7029  7029 D Mms/MethodReflector: getSubId is called
08-23 15:43:20.385  7029  7029 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
08-23 15:43:20.385  1019  1762 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:20.385  1019  1762 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:20.385  1019  1762 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:20.385  1019  1762 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:20.395  1480  1703 D TP/MmsSmsProvider: update, matched:300, calling pid = 7029
08-23 15:43:20.395  1480  1703 V TP/MmsSmsProvider: syncDBData start
08-23 15:43:20.395  1480  1703 V TP/MmsSmsProvider: syncDBData sms end
08-23 15:43:20.395  7029  7029 D Mms/MethodReflector: getTelephonyProperty is called
08-23 15:43:20.395  7029  7029 D Mms/DownloadManager: roaming -> false (slotId = 0)
08-23 15:43:20.395  7029  7029 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-23 15:43:20.395  7029  7029 D Mms/DownloadManager: auto download without roaming -> true
08-23 15:43:20.395  7029  7029 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
08-23 15:43:20.395  7029  7029 D Mms/DownloadManager: mAutoDownload ------> true
08-23 15:43:20.395  1480  1703 V TP/MmsSmsProvider: syncDBData mms end
08-23 15:43:20.395  1480  1703 V TP/MmsSmsProvider: syncDBData end
08-23 15:43:20.405  7165  7165 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 15:43:20.405  7165  7165 D ActivityThread: Added TimaKeyStore provider
08-23 15:43:20.405  7182  7182 E Zygote  : MountEmulatedStorage()
08-23 15:43:20.405  7182  7182 E Zygote  : v2
08-23 15:43:20.405  7182  7182 I libpersona: KNOX_SDCARD checking this for 10068
08-23 15:43:20.405  7182  7182 I libpersona: KNOX_SDCARD not a persona
08-23 15:43:20.405  7182  7182 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 15:43:20.415  7182  7182 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 15:43:20.415  1019  1762 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7182 uid=10068 gids={50068, 9997} abi=armeabi-v7a
08-23 15:43:20.415  7029  7172 D Mms/Synchronizer: [end]    doSync consume time = 24.357292
08-23 15:43:20.415  7182  7182 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-23 15:43:20.415  7029  7029 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_ADDED
08-23 15:43:20.415  1019  1266 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
08-23 15:43:20.415  1019  1266 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
08-23 15:43:20.415  7092  7092 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-23 15:43:20.415  1019  1266 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:20.425  1019  1266 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:20.425  1019  1266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,08-23 15:43:20.435  1019  1546 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
,08-23 15:43:20.435  1019  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:20.435  1019  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:20.435  1019  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:20.435  1019  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:20.435  7092  7092 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-23 15:43:20.435  7092  7092 D PhoneWindow: *FMB* installDecor flags : -2139027200
08-23 15:43:20.435   314   314 I art     : Explicit concurrent mark sweep GC freed 8716(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 610us total 30.802ms
,08-23 15:43:20.445  7182  7182 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 15:43:20.445  7182  7182 D ActivityThread: Added TimaKeyStore provider
,08-23 15:43:20.445  7092  7092 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-23 15:43:20.455   314   314 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 585us total 16.738ms,
08-23 15:43:20.455  7165  7165 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
,08-23 15:43:20.455  7165  7165 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
,08-23 15:43:20.475  6910  7163 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-23 15:43:20.475  6910  7163 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-23 15:43:20.475   314   314 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 577us total 16.196ms
,08-23 15:43:20.485  7198  7198 E Zygote  : MountEmulatedStorage(),
08-23 15:43:20.485  7198  7198 E Zygote  : v2
08-23 15:43:20.485  7198  7198 I libpersona: KNOX_SDCARD checking this for 10042
,08-23 15:43:20.485  7198  7198 I libpersona: KNOX_SDCARD not a persona
,08-23 15:43:20.485  7198  7198 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 15:43:20.485  1019  1546 I ActivityManager: Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=7198 uid=10042 gids={50042, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
,08-23 15:43:20.485  7198  7198 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 15:43:20.485  7198  7198 E SELinux : [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
,08-23 15:43:20.495  1019  1137 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
08-23 15:43:20.495  1019  1137 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
08-23 15:43:20.495  1019  1137 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:20.495  1019  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:20.495  1019  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
08-23 15:43:20.495  7092  7092 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-23 15:43:20.495  7092  7092 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-23 15:43:20.505  7165  7165 I FilterInstaller: FilterPackageService : ACTION_CHANGED
08-23 15:43:20.515  7029  7213 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_ADDED
08-23 15:43:20.515  1019  1546 I ActivityManager: Killing 6441:com.android.defcontainer/u0a3 (adj 15): empty #21
08-23 15:43:20.515  7029  7213 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_ADDED
08-23 15:43:20.515  1019  1546 I ActivityManager: Killing 6342:com.android.calendar/u0a131 (adj 15): empty #22
,08-23 15:43:20.535  7165  7206 E FilterInstaller: installFilters
,08-23 15:43:20.535  7198  7198 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 15:43:20.535  7198  7198 D ActivityThread: Added TimaKeyStore provider
,08-23 15:43:20.535  7165  7206 E FilterInstaller: There is no requred permission
,08-23 15:43:20.545  1019  1504 I ActivityManager: Killing 6700:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
,08-23 15:43:20.545  7182  7182 D BadgeProvider: onCreate
,08-23 15:43:20.545  7182  7182 D BadgeProvider: DatabaseHelper
,08-23 15:43:20.555  7198  7198 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-23 15:43:20.555  7198  7198 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-23 15:43:20.555  7198  7198 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-23 15:43:20.565  7029  7160 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,08-23 15:43:20.575  1480  1497 D TP/SmsProvider: query,matched:26, calling pid = 7029
,08-23 15:43:20.575  1480  1497 D TP/SmsProvider: match 26:Elapsed time : 1.386 ms
08-23 15:43:20.585  1480  3290 D TP/MmsSmsProvider: query,matched:6, calling pid = 7029
,08-23 15:43:20.585  1480  3290 D TP/MmsSmsProvider: match 6:Elapsed time : 1.648 ms
,08-23 15:43:20.605  1019  4305 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,08-23 15:43:20.605  1019  4305 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:20.605  1019  4305 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:20.605  1019  4305 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:20.605  1019  4305 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:20.625  1019  4305 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=7219 uid=10023 gids={50023, 9997} abi=armeabi-v7a,
,08-23 15:43:20.625  7219  7219 E Zygote  : MountEmulatedStorage()
08-23 15:43:20.625  7219  7219 E Zygote  : v2
08-23 15:43:20.625  7219  7219 I libpersona: KNOX_SDCARD checking this for 10023
,08-23 15:43:20.625  7219  7219 I libpersona: KNOX_SDCARD not a persona
08-23 15:43:20.625  7219  7219 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 15:43:20.625  7219  7219 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 15:43:20.625  7219  7219 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 15:43:20.645  7219  7219 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 15:43:20.645  7219  7219 D ActivityThread: Added TimaKeyStore provider
,08-23 15:43:20.655  1019  1504 I ActivityManager: Killing 6715:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
,08-23 15:43:20.675  7092  7234 D OpenGLRenderer: Render dirty regions requested: true
,08-23 15:43:20.675  6910  7163 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-23 15:43:20.675  1019  1761 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-23 15:43:20.675  1019  1761 D KnoxTimeoutHandler: postActiveUserChange for user 0
,08-23 15:43:20.675  1019  1761 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-23 15:43:20.685  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-23 15:43:20.685  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
,08-23 15:43:20.685  7092  7146 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,08-23 15:43:20.685  7092  7092 V ActivityThread: updateVisibility : ActivityRecord{359243f8 token=android.os.BinderProxy@235c8e6a {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-23 15:43:20.695  7092  7092 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-23 15:43:20.695  7092  7092 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-23 15:43:20.705   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,08-23 15:43:20.715  7219  7219 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,08-23 15:43:20.735  1019  1505 D InputDispatcher: Focus entered window: 7092
,08-23 15:43:20.735  1019  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-23 15:43:20.735  1019  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-23 15:43:20.735  7092  7092 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-23 15:43:20.735  7092  7234 I OpenGLRenderer: Initialized EGL, version 1.4
,08-23 15:43:20.745  7029  7160 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,08-23 15:43:20.755  7092  7234 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-23 15:43:20.755  7092  7234 D OpenGLRenderer: Enabling debug mode 0
,08-23 15:43:20.755  6910  7163 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-23 15:43:20.755  6910  7163 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2dd3c8ef: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-23 15:43:20.755  6910  7163 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-23 15:43:20.765  7219  7219 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,08-23 15:43:20.765  7219  7219 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
08-23 15:43:20.765  7219  7219 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
08-23 15:43:20.765  7219  7219 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
08-23 15:43:20.775  7219  7219 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
08-23 15:43:20.775  7219  7219 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,08-23 15:43:20.775  7219  7219 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,08-23 15:43:20.775  7219  7219 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,08-23 15:43:20.775  7219  7219 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,08-23 15:43:20.775  7219  7219 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,08-23 15:43:20.785  7219  7219 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,08-23 15:43:20.785  1019  1761 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-23 15:43:20.785  7219  7219 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,08-23 15:43:20.785  7219  7219 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,08-23 15:43:20.785  7198  7198 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,08-23 15:43:20.785  1178  1178 D PanelView: There is/are notification(s) 
,08-23 15:43:20.785  1019  7239 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 15:43:20.785  1019  1059 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
08-23 15:43:20.785  1019  1059 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-23 15:43:20.795  1019  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:20.795  1019  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:20.795  1019  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:20.795  1019  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:20.795  3774  4318 I Icing   : Indexing D0AE1F45F393341DA3213A207506F1C2E721F1A9 from com.google.android.googlequicksearchbox
,08-23 15:43:20.805  7242  7242 E Zygote  : MountEmulatedStorage(),
08-23 15:43:20.805  7242  7242 I libpersona: KNOX_SDCARD checking this for 10003
08-23 15:43:20.805  7242  7242 E Zygote  : v2,
08-23 15:43:20.805  7242  7242 I libpersona: KNOX_SDCARD not a persona
08-23 15:43:20.805  7092  7092 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-23 15:43:20.805  7092  7092 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@235c8e6a time:99685,
08-23 15:43:20.805  7242  7242 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 15:43:20.805  7242  7242 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 15:43:20.805  7242  7242 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-23 15:43:20.815  1019  1059 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7242 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-23 15:43:20.815  1019  1545 I splitIntent: Queue : backgroundsplit_0 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-23 15:43:20.815  1019  1545 I ActivityManager: Killing 6747:com.samsung.helphub/1000 (adj 15): empty #21,
,08-23 15:43:20.815  1019  1045 D ActivityManager: startProcessLocked calleePkgName: com.android.providers.calendar, hostingType: broadcast
,08-23 15:43:20.815  1838  1838 I SamsungIME: getCurrentCandidateView
08-23 15:43:20.815  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:20.815  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:20.815  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:20.815  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:20.835  1019  1050 I ActivityManager: Displayed Component not be shown by security: +1s207ms (total +1s342ms)
08-23 15:43:20.835  1019  1045 I ActivityManager: Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=7253 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-23 15:43:20.835  1019  1050 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{322f56a3 u0 com.test.thalitest/.MainActivity t163} time:99715
,08-23 15:43:20.835  1019  1050 W ActivityManager: mDVFSHelper.release()
,08-23 15:43:20.845  7253  7253 E Zygote  : MountEmulatedStorage()
08-23 15:43:20.845  7253  7253 E Zygote  : v2
08-23 15:43:20.845  7253  7253 I libpersona: KNOX_SDCARD checking this for 10037
08-23 15:43:20.845  7253  7253 I libpersona: KNOX_SDCARD not a persona,
08-23 15:43:20.845   258   448 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,08-23 15:43:20.845  7253  7253 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 15:43:20.845   258   451 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,08-23 15:43:20.845  7242  7242 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 15:43:20.845  7242  7242 D ActivityThread: Added TimaKeyStore provider,
,08-23 15:43:20.855  7253  7253 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-23 15:43:20.865  7253  7253 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-23 15:43:20.875  7092  7092 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7092
,08-23 15:43:20.885  7253  7253 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 15:43:20.885  7253  7253 D ActivityThread: Added TimaKeyStore provider
,08-23 15:43:20.915   285   285 E installd: system dir 0 : /system/app/
08-23 15:43:20.915   285   285 E installd: system dir 1 : /system/priv-app/
08-23 15:43:20.915   285   285 E installd: system dir 2 : /vendor/app/
08-23 15:43:20.915   285   285 E installd: system dir 3 : /oem/app/
,08-23 15:43:20.925  7253  7253 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,08-23 15:43:20.935  1019  1059 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
08-23 15:43:20.935  3774  4318 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,08-23 15:43:20.955  7253  7253 I CalendarProvider2: CalendarProvider2.onCreate() called
,08-23 15:43:20.985  1838  1838 D SamsungIME: Dismiss ExpandCandiate
,08-23 15:43:21.045  1019  1505 D ActivityManager: startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
08-23 15:43:21.045  1019  1505 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.CalendarProviderIntentService; callingUser = 0; userId(target) = 0
,08-23 15:43:21.045  1019  1505 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:21.045  1019  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:21.045  1019  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,08-23 15:43:21.055  3774  4318 I Icing   : Indexing done D0AE1F45F393341DA3213A207506F1C2E721F1A9
,08-23 15:43:21.065  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,08-23 15:43:21.075  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:21.075  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:21.075  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:21.075  1019  1137 I ActivityManager: Killing 6730:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
,08-23 15:43:21.075  1019  1514 D ActivityManager: startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
,08-23 15:43:21.075  1019  1514 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,08-23 15:43:21.075  1019  1514 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:21.075  1019  1514 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:21.075  1019  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,08-23 15:43:21.085  7253  7282 E SQLiteLog: (284) automatic index on view_events(_id)
,08-23 15:43:21.105  7253  7282 D CalendarAlarmManager: sys current time:1471959801095
,08-23 15:43:21.105  7092  7092 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-23 15:43:21.115  7253  7282 D CalendarAlarmManager: reminder amount:0
,08-23 15:43:21.165  1838  1838 I SamsungIME: getDebugLevel  : 0x4f4c
,08-23 15:43:21.195  1838  1838 I SamsungIME: getDebugLevel  : 0x4f4c
,08-23 15:43:21.205  7092  7238 D jxcore_app_log: JniHelper::setJavaVM(0xb71dd2b0), pthread_self() = -1216972776
,08-23 15:43:21.205  7092  7238 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-23 15:43:21.205  7092  7238 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-23 15:43:21.205  7092  7238 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-23 15:43:21.205  7092  7238 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-23 15:43:21.205  7092  7238 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-23 15:43:21.205  1838  1838 I SamsungIME: KeybaordView init() : load resources
,08-23 15:43:21.205  7092  7238 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e2dd52f added. We now have 1 listener(s)
,08-23 15:43:21.215  7092  7238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
,08-23 15:43:21.215  7092  7238 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-23 15:43:21.215  7092  7238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-23 15:43:21.215  7092  7238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-23 15:43:21.225  7092  7238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-23 15:43:21.225  7092  7238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-23 15:43:21.225  7092  7238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-23 15:43:21.225  7092  7238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
08-23 15:43:21.225  7092  7238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-23 15:43:21.225  7092  7238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-23 15:43:21.225  7092  7238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-23 15:43:21.225  7092  7238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-23 15:43:21.225  7092  7238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-23 15:43:21.225  7092  7238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-23 15:43:21.225  7092  7238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-23 15:43:21.225  7092  7238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-23 15:43:21.225  7092  7238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-23 15:43:21.225  7092  7238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-23 15:43:21.225  7092  7238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ded661a added. We now have 1 listener(s)
,08-23 15:43:21.225  7092  7238 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 15:43:21.225  7092  7238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-23 15:43:21.225  7092  7238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-23 15:43:21.225  7092  7238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-23 15:43:21.225  7092  7238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-23 15:43:21.225  7092  7238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-23 15:43:21.235  7092  7238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 15:43:21.235  7092  7238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
,08-23 15:43:21.245  7092  7238 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-23 15:43:21.245  7092  7238 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 15:43:21.245  7092  7238 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 15:43:21.245  7092  7238 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 15:43:21.245  7092  7238 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 15:43:21.245  7092  7238 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 15:43:21.245  7092  7238 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 15:43:21.245  7092  7238 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 15:43:21.245  7092  7238 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 15:43:21.245  7092  7238 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-23 15:43:21.245  7092  7238 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 15:43:21.245  1838  1838 I SamsungIME: getCurrentKeyboard
08-23 15:43:21.245  1838  1838 I SamsungIME: getTextKeyboard
,08-23 15:43:21.245  7092  7238 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-23 15:43:21.245  7092  7092 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 15:43:21.255  7092  7092 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 15:43:21.265  1838  1838 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-23 15:43:21.285  7092  7092 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-23 15:43:21.765  7092  7284 W jxcore-log: Initializing JXcore engine
08-23 15:43:21.765  7092  7284 W jxcore-log: JXcore engine is ready
,08-23 15:43:21.825  1958  1958 E audit   : type=1400 msg=audit(1471959801.825:205): avc:  denied  { ioctl } for  pid=7284 comm="Thread-1336" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3080 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-23 15:43:21.825  1958  1958 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-23 15:43:21.825  1958  1958 E audit   : type=1300 msg=audit(1471959801.825:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9f9d98f8 items=0 ppid=314 ppcomm=main pid=7284 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1336" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-23 15:43:21.825  1958  1958 E audit   : type=1320 msg=audit(1471959801.825:205): 
,08-23 15:43:21.835  7092  7284 W jxcore-log: Starting JXcore engine
,08-23 15:43:21.945  7092  7284 W jxcore-log: Platform android
08-23 15:43:21.945  7092  7284 W jxcore-log: 
08-23 15:43:21.945  7092  7284 W jxcore-log: Process ARCH arm
08-23 15:43:21.945  7092  7284 W jxcore-log: 
,08-23 15:43:22.105  7253  7253 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,08-23 15:43:22.105  1019  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:22.105  1019  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:22.105  1019  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,08-23 15:43:22.105  1019  1045 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
,08-23 15:43:22.105  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:22.105  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:22.105  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:22.105  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:22.125  7285  7285 E Zygote  : MountEmulatedStorage(),
08-23 15:43:22.125  7285  7285 I libpersona: KNOX_SDCARD checking this for 10130
08-23 15:43:22.125  7285  7285 E Zygote  : v2
08-23 15:43:22.125  7285  7285 I libpersona: KNOX_SDCARD not a persona
08-23 15:43:22.125  7285  7285 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-23 15:43:22.125  1019  1045 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=7285 uid=10130 gids={50130, 9997} abi=armeabi-v7a,
08-23 15:43:22.125  1019  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
08-23 15:43:22.125  1019  1504 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:22.125  1019  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:22.125  1019  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,08-23 15:43:22.125  7285  7285 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 15:43:22.125  7285  7285 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL,
08-23 15:43:22.125  1019  1546 I ActivityManager: Killing 6763:com.sec.spp.push/u0a32 (adj 15): empty #21
,08-23 15:43:22.145  7285  7285 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 15:43:22.155  7285  7285 D ActivityThread: Added TimaKeyStore provider
,08-23 15:43:22.155  7092  7284 I jxcore-log: JXcore Cordova bridge is ready!
08-23 15:43:22.155  7092  7284 I jxcore-log: 
,08-23 15:43:22.155  7092  7284 W jxcore-log: JXcore engine is started
,08-23 15:43:22.165  7092  7238 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-23 15:43:22.165  7092  7092 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-23 15:43:22.175  7285  7285 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-23 15:43:22.175  7285  7285 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,08-23 15:43:22.185  1019  1762 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:22.185  1019  1762 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:22.185  1019  1762 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
08-23 15:43:22.185  1019  1762 D ActivityManager: startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,08-23 15:43:22.185   289   289 E SMD     : DCD OFF
,08-23 15:43:22.195  1019  1762 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:22.195  1019  1762 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:22.195  1019  1762 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:22.195  1019  1762 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:22.205  7300  7300 E Zygote  : MountEmulatedStorage(),
08-23 15:43:22.205  7300  7300 E Zygote  : v2
08-23 15:43:22.205  7300  7300 I libpersona: KNOX_SDCARD checking this for 10131
08-23 15:43:22.205  7300  7300 I libpersona: KNOX_SDCARD not a persona,
08-23 15:43:22.205  7300  7300 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 15:43:22.205  1019  1762 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=7300 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
08-23 15:43:22.205  1019  1762 I ActivityManager: Killing 6835:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
08-23 15:43:22.215  7300  7300 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 15:43:22.215  7300  7300 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 15:43:22.235  7300  7300 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 15:43:22.235  7300  7300 D ActivityThread: Added TimaKeyStore provider
,08-23 15:43:22.255  7300  7300 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-23 15:43:22.255  7300  7300 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-23 15:43:22.255  7300  7300 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-23 15:43:22.285  2904  3106 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-23 15:43:22.295  1019  1546 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-23 15:43:22.295  1019  1546 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,08-23 15:43:22.295  1019  1546 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:22.295  1019  1546 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:22.295  1019  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
08-23 15:43:22.305  1019  1505 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:22.305  1019  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:22.305  1019  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
08-23 15:43:22.315  1019  1032 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
08-23 15:43:22.315  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
08-23 15:43:22.315  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:22.315  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:22.315  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
08-23 15:43:22.335  1019  1545 I ActivityManager: Killing 6781:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,08-23 15:43:22.345  7029  7029 I Mms/MmsApp:  start initViewCache mms
,08-23 15:43:22.345  7029  7029 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1936.763176
,08-23 15:43:22.345  7029  7029 D Mms/ComposeMessageFragment: fillCache, easy = false
,08-23 15:43:22.465  7029  7029 D AbsListView: Get MotionRecognitionManager
,08-23 15:43:22.465  1019  1761 D MotionRecognitionService:  ssp status : false
,08-23 15:43:22.475  7029  7029 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 123.991198
,08-23 15:43:22.565  7029  7029 D Mms/BubbleViewCache: fillCache bubble = 1
,08-23 15:43:23.585  1019  3348 D SSRM:n  : SIOP:: AP = 410
,08-23 15:43:23.895  1019  3377 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-23 15:43:23.965  1670  1670 I ConfigService: onDestroy
,08-23 15:43:25.195   289   289 E SMD     : DCD OFF,
,08-23 15:43:25.625  6795  6827 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter,
,08-23 15:43:25.645  6795  6827 I AcmsKeyStoreHelper: Key Store exist,
,08-23 15:43:25.645  6795  6827 I AcmsKeyStoreHelper: Hence loading the keystore file
,08-23 15:43:25.695  6795  6827 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit,
08-23 15:43:25.695  6795  6827 I AcmsCertificateMngr: getKeyStoreForApplication success 
08-23 15:43:25.695  6795  6827 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
08-23 15:43:25.695  6795  6827 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-23 15:43:25.695  6795  6827 D AcmsServiceMonitor: Decrementing - Counter value: 1
08-23 15:43:25.695  6795  6827 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
08-23 15:43:25.695  6795  6827 D AcmsCore: This is NOT a valid MirrorLink app
,08-23 15:43:25.695  6795  6827 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
08-23 15:43:25.695  6795  6827 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-23 15:43:25.695  6795  6827 D AcmsServiceMonitor: Decrementing - Counter value: 0
08-23 15:43:25.695  6795  6827 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service,
08-23 15:43:25.705  6795  6795 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
08-23 15:43:25.705  6795  6795 D AcmsService: Enter onDestroy
08-23 15:43:25.705  6795  6795 I AcmsService: cleanUp(): inside service clean up
08-23 15:43:25.705  6795  6795 D AcmsCore: AcmsCore: inside DeInit
08-23 15:43:25.705  6795  6795 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
,08-23 15:43:25.705  6795  6795 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
08-23 15:43:25.705  6795  6795 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
08-23 15:43:25.705  6795  6795 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
08-23 15:43:25.705  6795  6795 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
,08-23 15:43:25.705  6795  6795 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
08-23 15:43:25.705  6795  6795 D AcmsService: killing acms process
,08-23 15:43:25.705  6795  6795 I Process : Sending signal. PID: 6795 SIG: 9
,08-23 15:43:25.865  1019  1762 I ActivityManager: Process ACMS.Process (pid 6795)(adj 0) has died(25,746)
,08-23 15:43:27.085  1019  1546 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 15:43:27.085  1019  1546 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4273, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-23 15:43:27.085  1019  1546 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-23 15:43:27.095  1019  1546 D BatteryService: stay LED for charging
08-23 15:43:27.095  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 15:43:27.095  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 15:43:27.095  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 15:43:27.095  1019  1019 I MotionRecognitionService: Plugged
,08-23 15:43:27.095  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 15:43:27.095  1440  1440 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-23 15:43:27.095  1440  1440 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-23 15:43:27.115  3184  3184 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 15:43:27.115  3184  3338 D HeadsetStateMachine: Disconnected process message: 10
,08-23 15:43:27.125  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-23 15:43:27.125  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-23 15:43:27.125  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-23 15:43:27.125  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-23 15:43:27.125  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-23 15:43:28.195   289   289 E SMD     : DCD OFF
,08-23 15:43:28.445  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-23 15:43:28.445  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:28.445  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:28.445  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:28.465  7325  7325 E Zygote  : MountEmulatedStorage()
,08-23 15:43:28.465  1019  1045 I ActivityManager: Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=7325 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
08-23 15:43:28.465  7325  7325 E Zygote  : v2
08-23 15:43:28.465  7325  7325 I libpersona: KNOX_SDCARD checking this for 10011
08-23 15:43:28.465  7325  7325 I libpersona: KNOX_SDCARD not a persona
,08-23 15:43:28.465  7325  7325 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 15:43:28.465  7325  7325 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-23 15:43:28.465  7325  7325 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,08-23 15:43:28.485  7325  7325 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 15:43:28.485  7325  7325 D ActivityThread: Added TimaKeyStore provider
,08-23 15:43:28.505  7325  7325 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-23 15:43:28.505  7325  7325 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-23 15:43:28.535  7325  7325 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,08-23 15:43:28.535  7325  7325 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,08-23 15:43:28.545  7325  7325 I MultiDex: VM with version 2.1.0 has multidex support
08-23 15:43:28.545  7325  7325 I MultiDex: install
08-23 15:43:28.545  7325  7325 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-23 15:43:28.565  7325  7325 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-23 15:43:28.625  7325  7325 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
08-23 15:43:28.625  7325  7325 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@dcccf7d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-23 15:43:28.625  7325  7325 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-23 15:43:28.635  1019  1045 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:28.635  1019  1045 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:28.635  1019  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:28.635  1019  1505 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
08-23 15:43:28.635  1019  1505 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-23 15:43:28.635  1019  1505 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:28.635  1019  1505 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:28.635  1019  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-23 15:43:28.635  1019  1762 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,08-23 15:43:28.635  1019  1762 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
08-23 15:43:28.635  1019  1762 I splitIntent: other index=5, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
08-23 15:43:28.635  1670  5122 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-23 15:43:28.635  1019  1762 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,08-23 15:43:28.635  1019  1762 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:28.635  1019  1762 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:28.635  1019  1762 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:28.645  1019  1266 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:28.645  1019  1266 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-23 15:43:28.645  1019  1266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:28.655  1670  1670 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-23 15:43:28.655  1019  1137 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:28.655  1019  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-23 15:43:28.655  1019  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:28.655  1019  4305 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,08-23 15:43:28.655  1019  4305 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,08-23 15:43:28.665  1019  4305 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:28.665  1019  4305 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-23 15:43:28.665  1019  4305 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-23 15:43:28.665  1019  1545 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:28.665  1019  1545 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-23 15:43:28.665  1019  1545 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:28.675  1670  1670 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
08-23 15:43:28.675  1670  1670 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 15:43:28.675  1019  1514 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:28.675  1019  1514 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-23 15:43:28.675  1019  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:28.685  3774  3774 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,08-23 15:43:28.685  1019  1543 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-23 15:43:28.695  1019  1543 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,08-23 15:43:28.695  1019  1543 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:28.695  1019  1543 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:28.695  1019  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-23 15:43:28.695  7325  7343 D NativeLibraryUtils: Install completed successfully. count=0 extracted=0
,08-23 15:43:28.695  1019  1266 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:28.695  1019  1266 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:28.695  1019  1266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:28.705  1019  4305 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:28.705  1019  4305 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:28.705  1019  4305 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:28.705  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:28.715  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-23 15:43:28.715  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:28.715  1019  1031 I ActivityManager: Killing 6362:com.samsung.android.sm/1000 (adj 15): empty #21
,08-23 15:43:28.715  1019  1032 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 15:43:28.725  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:28.725  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:28.725  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:28.725  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:28.725  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:28.725  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:28.725  7325  7325 D WearableService: callingUid 10011, callindPid: 7325
,08-23 15:43:28.735  1019  1546 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:28.735  1019  1546 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:28.735  1019  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:28.755  1019  1544 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:28.755  1019  1544 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:28.755  1019  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:28.755  1019  1543 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:28.755  1019  1543 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-23 15:43:28.755  1019  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:28.765  1019  1031 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 15:43:28.765  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:28.765  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:28.765  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:28.775  1019  1546 W ActivityManager: userId = 0, bbcId = -10000,
08-23 15:43:28.775  1019  1546 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:28.775  1019  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:28.775  1019  1545 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-23 15:43:28.775  1019  1545 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,08-23 15:43:28.775  1019  1545 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:28.775  1019  1545 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:28.775  1019  1545 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:28.785  3774  7346 D LocationInitializer: Restart initialization of location
,08-23 15:43:28.785  1019  1762 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-23 15:43:28.785  1019  1762 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,08-23 15:43:28.785  1019  1762 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:28.785  1019  1762 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:28.785  1019  1762 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:28.795  1019  1505 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 15:43:28.795  1019  1505 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:28.795  1019  1505 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:28.795  1019  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-23 15:43:28.905  1019  1137 I art     : Explicit concurrent mark sweep GC freed 23036(1286KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 22MB/34MB, paused 2.424ms total 146.331ms
,08-23 15:43:28.915  1797  5121 E MDM     : [186] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-23 15:43:29.445  1019  1333 E Watchdog: !@Sync 3
,08-23 15:43:29.535  1019  1059 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-23 15:43:30.195   326   326 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6,
08-23 15:43:30.195   326   326 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-23 15:43:30.945  1019  1059 D PackageManager: [MSG] MCS_UNBIND
,08-23 15:43:31.195   289   289 E SMD     : DCD OFF
,08-23 15:43:33.325  1019  1052 I PowerManagerService: [PWL] Off : 50s ago,
,08-23 15:43:33.615  1019  3348 D SSRM:n  : SIOP:: AP = 380,
,08-23 15:43:33.925  1019  1514 I ActivityManager: Killing 6884:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
,08-23 15:43:34.195   289   289 E SMD     : DCD OFF
,08-23 15:43:34.305  1019  1098 V AlarmManager: waitForAlarm result :4
,08-23 15:43:34.305  1019  1098 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,08-23 15:43:34.525  6967  7062 D Finsky  : [1304] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,08-23 15:43:34.525  6967  6967 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-23 15:43:35.205   326   326 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 15:43:36.205   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 15:43:36.425  7092  7284 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-23 15:43:36.425  7092  7284 I jxcore-log: 
,08-23 15:43:37.135  1019  1544 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 15:43:37.135  1019  1544 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4276, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-23 15:43:37.135  1019  1544 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-23 15:43:37.135  1019  1544 D BatteryService: stay LED for charging
08-23 15:43:37.135  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 15:43:37.135  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 15:43:37.145  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
08-23 15:43:37.145  1019  1019 I MotionRecognitionService: Plugged
08-23 15:43:37.145  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 15:43:37.145  1440  1440 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-23 15:43:37.145  1440  1440 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-23 15:43:37.155  3184  3184 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-23 15:43:37.155  3184  3338 D HeadsetStateMachine: Disconnected process message: 10
,08-23 15:43:37.165  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-23 15:43:37.165  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-23 15:43:37.165  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
08-23 15:43:37.165  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-23 15:43:37.165  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-23 15:43:37.195   289   289 E SMD     : DCD OFF
,08-23 15:43:37.205   326   326 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 15:43:38.205   326   326 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 15:43:38.685  7092  7284 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js,
08-23 15:43:38.685  7092  7284 I jxcore-log: 
,08-23 15:43:38.725  7092  7284 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js,
08-23 15:43:38.725  7092  7284 I jxcore-log: 
,08-23 15:43:38.745  7092  7284 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js,
08-23 15:43:38.745  7092  7284 I jxcore-log: 
,08-23 15:43:38.775  7092  7284 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js,
08-23 15:43:38.775  7092  7284 I jxcore-log: 
,08-23 15:43:38.775  7092  7284 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js,
08-23 15:43:38.775  7092  7284 I jxcore-log: 
,08-23 15:43:39.205   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 15:43:39.665  5944  5944 D FactoryTest: Not factory mode
,08-23 15:43:39.665  5944  5944 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-23 15:43:39.665  5944  5944 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-23 15:43:39.665  5944  5944 D MTPRx   : still no open session command from host, so toast
,08-23 15:43:39.665  5944  5944 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,08-23 15:43:39.665  5944  5944 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-23 15:43:39.675  5944  5944 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:118550
,08-23 15:43:39.675  1019  1761 E PersonaManagerService: inState():  stateMachine is null !!
,08-23 15:43:39.675  1019  1761 I PersonaManagerService: PersonaId don't exist
08-23 15:43:39.675  1019  1761 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-23 15:43:39.675  1019  1761 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-23 15:43:39.675  1019  1761 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:39.675  1019  1761 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:39.675  1019  1761 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-23 15:43:39.685  1019  1761 W ActivityManager: mDVFSHelper.acquire()
,08-23 15:43:39.695  1019  1761 D PersonaManager: isKioskContainerExistOnDevice
,08-23 15:43:39.705  1019  1761 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-23 15:43:39.705  1019  1761 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-23 15:43:39.705  1019  1761 D InputDispatcher: Focused application set to: xxxx
08-23 15:43:39.705  1019  1761 D InputDispatcher: Focus left window: 7092
,08-23 15:43:39.705  5944  5944 E MTPRx   : started activity for popup
,08-23 15:43:39.715  1019  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-23 15:43:39.715  1019  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-23 15:43:39.735  5944  5944 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
08-23 15:43:39.735  5944  5944 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-23 15:43:39.735  5944  5944 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-23 15:43:39.735  5944  5944 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-23 15:43:39.735  5944  5944 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-23 15:43:39.735  5944  5944 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-23 15:43:39.765  5944  5944 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-23 15:43:39.765  1019  1543 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-23 15:43:39.765  1019  1543 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-23 15:43:39.765  1019  1543 D InputDispatcher: Focused application set to: xxxx
,08-23 15:43:39.765  1019  1543 D InputDispatcher: Focus entered window: 7092
,08-23 15:43:39.765  1019  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-23 15:43:39.775  1019  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-23 15:43:39.775  1019  1762 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-23 15:43:39.775  1019  1762 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@48ed9f9 attribute=null, token = android.os.BinderProxy@2948bceb
,08-23 15:43:39.805  5944  5944 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-23 15:43:39.815  5944  5944 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-23 15:43:39.815  5944  5944 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-23 15:43:39.835  7092  7092 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-23 15:43:39.835  7092  7092 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,08-23 15:43:39.835  7092  7092 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-23 15:43:39.845  7092  7092 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-23 15:43:39.845  1019  4305 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-23 15:43:39.845  1019  4305 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-23 15:43:39.845  1019  4305 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-23 15:43:39.845  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-23 15:43:39.845  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
,08-23 15:43:39.855  7092  7092 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-23 15:43:39.855  7092  7092 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-23 15:43:39.855  7092  7092 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@235c8e6a time:118738
08-23 15:43:39.855  7092  7092 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1f199086 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@3903274f, 16908290=android.view.AbsSavedState$1@3903274f}, android:focusedViewId=100}]}]
08-23 15:43:39.855  7092  7092 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-23 15:43:39.865  7092  7092 V ActivityThread: updateVisibility : ActivityRecord{359243f8 token=android.os.BinderProxy@235c8e6a {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-23 15:43:39.865  7092  7092 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-23 15:43:39.865  7092  7092 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-23 15:43:39.875  1019  1761 D PersonaManager: isKioskContainerExistOnDevice
,08-23 15:43:40.195   289   289 E SMD     : DCD OFF
,08-23 15:43:40.205   326   326 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-23 15:43:42.615  7092  7284 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
08-23 15:43:42.615  7092  7284 I jxcore-log: 
,08-23 15:43:42.625  7092  7284 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
08-23 15:43:42.625  7092  7284 I jxcore-log: 
,08-23 15:43:42.625  7092  7284 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 15:43:42.625  7092  7284 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 15:43:42.625  7092  7284 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 15:43:42.625  7092  7284 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 15:43:42.625  7092  7284 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 15:43:42.625  7092  7284 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 15:43:42.625  7092  7284 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 15:43:42.625  7092  7284 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 15:43:42.625  7092  7284 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,08-23 15:43:42.635  7092  7284 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native,
08-23 15:43:42.635  7092  7284 I jxcore-log: 
,08-23 15:43:42.635  7092  7284 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native,
08-23 15:43:42.635  7092  7284 I jxcore-log: 
,08-23 15:43:42.685  1019  1045 W ActivityManager: mDVFSHelper.release()
,08-23 15:43:43.195   289   289 E SMD     : DCD OFF
,08-23 15:43:43.635  1019  3348 D SSRM:n  : SIOP:: AP = 360,
,08-23 15:43:43.895  1019  3377 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 15:43:45.205   326   326 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 15:43:46.195   289   289 E SMD     : DCD OFF
,08-23 15:43:46.205   326   326 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 15:43:47.185  1019  1544 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-23 15:43:47.185  1019  1544 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4276, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-23 15:43:47.185  1019  1544 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-23 15:43:47.185  1019  1544 D BatteryService: stay LED for charging
08-23 15:43:47.185  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 15:43:47.185  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 15:43:47.195  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 15:43:47.195  1019  1019 I MotionRecognitionService: Plugged
,08-23 15:43:47.195  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 15:43:47.195  1440  1440 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 15:43:47.195  1440  1440 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-23 15:43:47.205  3184  3184 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 15:43:47.205  3184  3338 D HeadsetStateMachine: Disconnected process message: 10
,08-23 15:43:47.205   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 15:43:47.215  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-23 15:43:47.215  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-23 15:43:47.215  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-23 15:43:47.215  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-23 15:43:47.215  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-23 15:43:47.455  7092  7284 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-23 15:43:47.455  7092  7284 I jxcore-log: 
,08-23 15:43:47.615  7092  7284 I jxcore-log: ERROR runTests: 
08-23 15:43:47.615  7092  7284 I jxcore-log: 
,08-23 15:43:47.625  7092  7284 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js: Error: Cannot find module 'thali/NextGeneration/thaliMoblie'
08-23 15:43:47.625  7092  7284 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"39","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:39:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
,08-23 15:43:47.625  7092  7284 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 15:43:47.625  7092  7284 I jxcore-log: 
,08-23 15:43:47.625  7092  7092 I chromium: [INFO:CONSOLE(56)] "app.js file failed to load : "Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js: Error: Cannot find module 'thali/NextGeneration/thaliMoblie'\nError: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js: Error: Cannot find module 'thali/NextGeneration/thaliMoblie'\n    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11\n    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:39:7\n    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3\n    at $w.prototype._compile@module.js:621:8\n    at $w._extensions[\".js\"]@module.js:651:1\n    at $w.prototype.load@module.js:442:1"", source: file:///android_asset/www/js/thali_main.js (56)
,08-23 15:43:47.635  7092  7092 I chromium: [INFO:CONSOLE(72)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (72)
,08-23 15:43:47.635  1019  4305 D FocusedStackFrame: Set to : 0
08-23 15:43:47.635  1019  4305 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-23 15:43:47.635  1019  4305 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-23 15:43:47.635  1019  4305 D InputDispatcher: Focused application set to: xxxx
08-23 15:43:47.635  1019  4305 D InputDispatcher: Focus left window: 7092
08-23 15:43:47.635  1019  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-23 15:43:47.635  1019  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-23 15:43:47.645  1019  4305 I ActivityManager: Killing 6867:com.google.android.partnersetup/u0a14 (adj 15): empty #21
,08-23 15:43:47.645  7092  7092 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-23 15:43:47.645  7092  7092 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
08-23 15:43:47.645  7092  7092 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 15:43:47.645  7092  7092 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 15:43:47.645  7092  7092 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 15:43:47.645  7092  7092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 15:43:47.645  7092  7092 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e2dd52f removed from the list
08-23 15:43:47.645  7092  7092 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 15:43:47.645  7092  7092 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ded661a removed from the list
08-23 15:43:47.645  7092  7092 D io.jxcore.node.ConnectivityMonitor: stop
08-23 15:43:47.645  7092  7092 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
08-23 15:43:47.655  7092  7092 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-23 15:43:47.665   258   448 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
,08-23 15:43:47.665   258   451 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,08-23 15:43:47.675  1019  1762 W ActivityManager: mDVFSHelper.acquire()
,08-23 15:43:47.685  1019  1762 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,08-23 15:43:47.715  1507  1507 D Launcher: onRestart, Launcher: 877868868
,08-23 15:43:47.715  1507  1507 D Launcher: onStart, Launcher: 877868868
,08-23 15:43:47.715  1507  1507 D Launcher.HomeView: onStart
,08-23 15:43:47.715  1507  1507 D Launcher: onResume, Launcher: 877868868
,08-23 15:43:47.715  1019  1031 D SettingsProvider: name = kids_home_mode
,08-23 15:43:47.715  1019  1031 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 15:43:47.715  1019  1031 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 15:43:47.715  1019  1031 D SettingsProvider: selectionArgs: false
08-23 15:43:47.715  1019  1031 D SettingsProvider: selectionArgs: 10006
08-23 15:43:47.715  1019  1031 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-23 15:43:47.715  1019  1031 D SettingsProvider: ret = -1
08-23 15:43:47.715  1507  1507 D Launcher.HomeView: onResume
,08-23 15:43:47.725  1507  1507 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-23 15:43:47.735  1507  1507 D MenuAppsGridFragment: onResume
,08-23 15:43:47.735  1019  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:47.735  1507  1507 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
08-23 15:43:47.735  1019  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 15:43:47.735  1019  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,08-23 15:43:47.735  1507  1507 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-23 15:43:47.735  1019  1543 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=7, mSplitNum[2]=9, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=11
,08-23 15:43:47.745  1019  1543 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,08-23 15:43:47.745  1019  1543 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:47.745  1019  1543 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:47.745  1019  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,08-23 15:43:47.745  1019  1543 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,08-23 15:43:47.745  1019  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:47.745  1019  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:47.745  1019  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:47.745  1019  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:47.775  7361  7361 E Zygote  : MountEmulatedStorage(),
08-23 15:43:47.775  7361  7361 I libpersona: KNOX_SDCARD checking this for 10039
08-23 15:43:47.775  7361  7361 E Zygote  : v2
08-23 15:43:47.775  7361  7361 I libpersona: KNOX_SDCARD not a persona
08-23 15:43:47.775  1019  1543 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=7361 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,08-23 15:43:47.785  1019  1546 D ActivityManager: handle home activity for 0,
08-23 15:43:47.785  1019  1546 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
08-23 15:43:47.785  1019  1546 D KnoxTimeoutHandler: post home show event for user 0
08-23 15:43:47.785  1019  1546 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-23 15:43:47.785  1019  1546 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-23 15:43:47.785  1019  1019 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
08-23 15:43:47.785  1019  1019 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
08-23 15:43:47.785  1019  1546 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-23 15:43:47.785  1507  1507 D Launcher.HomeView: onPause
08-23 15:43:47.785  1507  1507 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-23 15:43:47.785  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-23 15:43:47.785  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
,08-23 15:43:47.785  7361  7361 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 15:43:47.785  1019  1045 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:47.785  1019  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:47.785  1019  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
08-23 15:43:47.795  1019  1045 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:47.795  1019  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:47.795  1019  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.dualclockdigital
08-23 15:43:47.795  1019  1045 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.dualclockdigital, hostingType: broadcast
,08-23 15:43:47.795  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:47.795  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:47.795  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:47.795  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:47.795  7361  7361 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 15:43:47.795  7361  7361 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 15:43:47.805  7369  7369 E Zygote  : MountEmulatedStorage(),
08-23 15:43:47.805  7369  7369 E Zygote  : v2,
,08-23 15:43:47.805  7369  7369 I libpersona: KNOX_SDCARD checking this for 10089
08-23 15:43:47.805  7369  7369 I libpersona: KNOX_SDCARD not a persona
,08-23 15:43:47.815  7369  7369 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 15:43:47.815  7369  7369 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 15:43:47.815  1019  1045 I ActivityManager: Start proc com.sec.android.widgetapp.dualclockdigital for broadcast com.sec.android.widgetapp.dualclockdigital/.DigitalDualClockWidgetProvider: pid=7369 uid=10089 gids={50089, 9997, 3003} abi=armeabi-v7a
,08-23 15:43:47.815  1019  1045 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:47.815  1019  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:47.815  1019  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
08-23 15:43:47.815  1019  1045 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
08-23 15:43:47.815  7369  7369 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,08-23 15:43:47.815  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:47.815  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:47.815  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:47.815  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:47.835  7361  7361 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 15:43:47.845  7361  7361 D ActivityThread: Added TimaKeyStore provider
,08-23 15:43:47.845  7369  7369 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-23 15:43:47.845  7369  7369 D ActivityThread: Added TimaKeyStore provider
,08-23 15:43:47.845  7391  7391 E Zygote  : MountEmulatedStorage(),
08-23 15:43:47.845  7391  7391 E Zygote  : v2
08-23 15:43:47.845  7391  7391 I libpersona: KNOX_SDCARD checking this for 10139
08-23 15:43:47.845  7391  7391 I libpersona: KNOX_SDCARD not a persona
,08-23 15:43:47.845  7391  7391 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 15:43:47.845  1019  1045 I ActivityManager: Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=7391 uid=10139 gids={50139, 9997, 1028, 1015} abi=armeabi-v7a
,08-23 15:43:47.865  7391  7391 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 15:43:47.865  7391  7391 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 15:43:47.875   258   258 I SurfaceFlinger: id=14 createSurf (540x960),1 flag=4, Mauncher
,08-23 15:43:47.885  1019  1514 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:47.885  1019  1514 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1507, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
08-23 15:43:47.885  1019  1514 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:47.885  1019  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,08-23 15:43:47.885  1019  1048 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-23 15:43:47.895  1019  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:47.895  1019  1048 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-23 15:43:47.895  1019  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:47.895  1019  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,08-23 15:43:47.895  2576  2576 D Recents_RecreateReceiver: onReceive by home
,08-23 15:43:47.905  1019  1543 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:47.905  1019  1543 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:47.905  1019  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
,08-23 15:43:47.905  1019  1544 D InputDispatcher: Focus entered window: 1507
08-23 15:43:47.905  1019  1543 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
,08-23 15:43:47.905  1019  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-23 15:43:47.905  1019  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:47.905  1019  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
08-23 15:43:47.905  1019  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:47.905  1507  1507 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-23 15:43:47.905  1019  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:47.905  1019  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:47.905  7391  7391 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 15:43:47.905  7391  7391 D ActivityThread: Added TimaKeyStore provider
,08-23 15:43:47.915  7361  7361 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-23 15:43:47.915  7361  7361 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 15:43:47.915  7361  7361 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-23 15:43:47.915  7361  7361 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
08-23 15:43:47.915  7361  7361 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-23 15:43:47.915  7361  7361 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-23 15:43:47.915  7361  7361 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-23 15:43:47.915  7369  7369 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-23 15:43:47.915  7369  7369 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,08-23 15:43:47.935  7357  7357 D AndroidRuntime: 
08-23 15:43:47.935  7357  7357 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-23 15:43:47.935  7407  7407 E Zygote  : MountEmulatedStorage()
08-23 15:43:47.935  7407  7407 E Zygote  : v2
08-23 15:43:47.935  7407  7407 I libpersona: KNOX_SDCARD checking this for 10084
08-23 15:43:47.935  7407  7407 I libpersona: KNOX_SDCARD not a persona
,08-23 15:43:47.935  7407  7407 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 15:43:47.935  7357  7357 D AndroidRuntime: CheckJNI is OFF
08-23 15:43:47.935  7357  7357 D AndroidRuntime: readGMSProperty: start
08-23 15:43:47.935  7357  7357 D AndroidRuntime: readGMSProperty: already setted!!
08-23 15:43:47.935  7357  7357 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-23 15:43:47.935  1507  1507 V ActivityThread: updateVisibility : ActivityRecord{36279d79 token=android.os.BinderProxy@177826fa {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
08-23 15:43:47.935  7357  7357 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-23 15:43:47.935  7357  7357 D AndroidRuntime: readGMSProperty: end
08-23 15:43:47.935  7357  7357 D AndroidRuntime: addProductProperty: start
08-23 15:43:47.935  1507  1507 D Launcher.HomeView: onStop
08-23 15:43:47.935  1019  1761 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-23 15:43:47.935  7407  7407 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 15:43:47.935  1019  1543 I ActivityManager: Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=7407 uid=10084 gids={50084, 9997} abi=armeabi-v7a
08-23 15:43:47.945  7407  7407 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
08-23 15:43:47.945  1019  7413 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 15:43:47.945  1178  1178 D PanelView: There is/are notification(s) 
,08-23 15:43:47.955  7092  7092 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-23 15:43:47.955  1019  1019 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,08-23 15:43:47.965  1838  1838 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,08-23 15:43:47.975  7391  7391 V TaskCloserActivity: TaskCloserActivity enter()
,08-23 15:43:47.985   314   314 I art     : Explicit concurrent mark sweep GC freed 8673(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 602us total 46.208ms
08-23 15:43:47.985  7391  7391 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
08-23 15:43:47.985  1019  1762 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:47.985  1019  1762 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:47.985  1019  1762 I ActivityManager: Killing 6910:com.google.android.apps.docs/u0a87 (adj 15): empty #21
08-23 15:43:47.985  1019  1762 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,08-23 15:43:48.015   314   314 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 574us total 17.961ms
,08-23 15:43:48.015  7407  7407 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 15:43:48.015  7407  7407 D ActivityThread: Added TimaKeyStore provider
08-23 15:43:48.025  1507  1507 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@177826fa time:126903
,08-23 15:43:48.035  1019  1504 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:48.035  1019  1504 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
08-23 15:43:48.035  1019  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:48.035  1019  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,08-23 15:43:48.045  1019  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:48.045  1019  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:48.045  1019  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:48.045  1019  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:48.045   314   314 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 990us total 18.865ms
,08-23 15:43:48.055  7407  7407 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-23 15:43:48.065  7433  7433 E Zygote  : MountEmulatedStorage(),
,08-23 15:43:48.065  7433  7433 E Zygote  : v2
08-23 15:43:48.065  7433  7433 I libpersona: KNOX_SDCARD checking this for 10135
,08-23 15:43:48.065  7433  7433 I libpersona: KNOX_SDCARD not a persona
,08-23 15:43:48.065  7433  7433 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-23 15:43:48.065  1019  1504 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=7433 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
08-23 15:43:48.065  1019  1050 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{16af9f8a u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t162} time:126948
08-23 15:43:48.065  1019  1504 I ActivityManager: Killing 6931:com.sec.pcw.device/1000 (adj 15): empty #21
08-23 15:43:48.065  1019  1050 W ActivityManager: mDVFSHelper.release()
,08-23 15:43:48.065  7433  7433 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 15:43:48.075  7433  7433 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-23 15:43:48.085  1019  1545 I ActivityManager: Killing 6819:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,08-23 15:43:48.085  7357  7357 E AffinityControl: AffinityControl: registerfunction enter
,08-23 15:43:48.095  1019  1137 D PersonaManager: isKioskContainerExistOnDevice
,08-23 15:43:48.095  7433  7433 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 15:43:48.095  7433  7433 D ActivityThread: Added TimaKeyStore provider
,08-23 15:43:48.115  7357  7357 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-23 15:43:48.115  7433  7433 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.,
08-23 15:43:48.115  7433  7433 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-23 15:43:48.115  7433  7433 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
08-23 15:43:48.115  7433  7433 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
08-23 15:43:48.115  7433  7433 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-23 15:43:48.135  1019  1514 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-23 15:43:48.135  1019  1514 D PackageManager: START PACKAGE DELETE: observer{375181105}
08-23 15:43:48.135  1019  1514 D PackageManager: pkg{<packageName>}
08-23 15:43:48.135  1019  1514 D PackageManager: user{0}
08-23 15:43:48.135  1019  1514 D PackageManager: caller{2000}
08-23 15:43:48.135  1019  1514 D PackageManager: flags{2}
08-23 15:43:48.135  1019  1514 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-23 15:43:48.135  1019  1514 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-23 15:43:48.135  1019  1514 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-23 15:43:48.135  1019  1514 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-23 15:43:48.135  1019  1059 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-23 15:43:48.135  1019  1059 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-23 15:43:48.135  1019  1059 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-23 15:43:48.135  1019  1059 D ApplicationPolicy: getApplicationUninstallationEnabled
08-23 15:43:48.135  1019  1059 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-23 15:43:48.135  7361  7361 D NearbySource: Nearby Source Create!
08-23 15:43:48.135  7361  7361 D NearbyContext: Nearby Context Create!
,08-23 15:43:48.135  1019  1059 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
,08-23 15:43:48.145  1019  1045 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
08-23 15:43:48.145  1019  1045 I ActivityManager: Killing 7092:com.test.thalitest/u0a170 (adj 15): stop com.test.thalitest cause uninstall pkg
,08-23 15:43:48.185   257   521 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
08-23 15:43:48.185   257   521 W Vold    : Returning OperationFailed - no handler for errno 0
,08-23 15:43:48.185  7361  7361 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
08-23 15:43:48.185  7361  7361 D SLinkSource: Samsung link source created
,08-23 15:43:48.205   326   326 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 15:43:48.265  1019  1059 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,08-23 15:43:48.295  1019  1059 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-23 15:43:48.315  1019  1544 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-23 15:43:48.325  2822  2822 I art     : Explicit concurrent mark sweep GC freed 24441(1324KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 2.082ms total 46.867ms
,08-23 15:43:48.335  1838  1838 E SamsungIME: mOCRHelper is null
,08-23 15:43:48.345  1019  1101 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-23 15:43:48.345  1797  2097 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-23 15:43:48.365  1019  1266 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-23 15:43:48.375  1019  1126 V NetworkStats: removeUidsLocked() for UIDs [10170]
08-23 15:43:48.375  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 15:43:48.375  1019  1126 V NetworkStats: performPollLocked(flags=0x3)
,08-23 15:43:48.375  1019  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-23 15:43:48.375  7361  7361 D GalleryCacheReady: Receive : home resume
,08-23 15:43:48.375  1019  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-23 15:43:48.375  1019  1126 V NetworkStats: performPollLocked() took 6ms
08-23 15:43:48.375  1019  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 15:43:48.395  1019  1044 D EnterpriseDeviceManagerService: Package has changed for user 0
08-23 15:43:48.395  1019  1044 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
08-23 15:43:48.395  1019  1044 W TextServicesManagerService: no available spell checker services found
,08-23 15:43:48.395  1019  1762 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:48.395  1019  1762 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:48.395  1019  1762 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,08-23 15:43:48.405  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 15:43:48.415  1465  1465 D PersonaManager: isKioskContainerExistOnDevice
,08-23 15:43:48.415  1465  1465 D RegisteredServicesCache: empty dynamic service
,08-23 15:43:48.415  7029  7029 D Mms/UIEventReceiver: ui event
,08-23 15:43:48.415  1019  4305 I splitIntent: Queue : background intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart  false.
,08-23 15:43:48.415  1019  4305 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:48.415  1019  4305 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:48.415  1019  4305 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,08-23 15:43:48.425  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 15:43:48.425  7361  7451 D ContactProvider: getAllContactInfoList Start
,08-23 15:43:48.435  7391  7391 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,08-23 15:43:48.435  1019  1505 I ActivityManager: Killing 6997:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
,08-23 15:43:48.445  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 15:43:48.445  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 15:43:48.445  2806  2806 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Aug 23 15:43:48 GMT+02:00 2016
,08-23 15:43:48.445  1019  1543 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-23 15:43:48.445  1019  1543 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-23 15:43:48.455  1019  1543 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:48.455  1019  1543 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:48.455  1019  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-23 15:43:48.455  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 15:43:48.465  1465  1465 D RegisteredComponentCache: Collect Tech packages for Knox
,08-23 15:43:48.465  2806  2806 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-23 15:43:48.465  1465  1465 D PersonaManager: isKioskContainerExistOnDevice
,08-23 15:43:48.465  1019  1266 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=22, mSplitNum[2]=32, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=42
,08-23 15:43:48.475  1019  1266 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-23 15:43:48.475  1019  1266 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-23 15:43:48.475  2806  2806 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-23 15:43:48.475  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 15:43:48.475  1019  1543 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-23 15:43:48.475  1019  1543 D SecContentProvider2: mCursor = null
,08-23 15:43:48.475  1019  1266 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:48.475  1019  1266 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:48.475  1019  1266 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:48.475  1019  1266 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:48.485  2806  2806 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-23 15:43:48.505  7454  7454 E Zygote  : MountEmulatedStorage()
08-23 15:43:48.505  7454  7454 E Zygote  : v2
08-23 15:43:48.505  7454  7454 I libpersona: KNOX_SDCARD checking this for 10090
08-23 15:43:48.505  7454  7454 I libpersona: KNOX_SDCARD not a persona
,08-23 15:43:48.505  7454  7454 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 15:43:48.505  7454  7454 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-23 15:43:48.505  1019  1266 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7454 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
08-23 15:43:48.505  7454  7454 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 15:43:48.505  1019  1045 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
08-23 15:43:48.505  2806  2806 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-23 15:43:48.505  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:48.505  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:48.505  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:48.505  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:48.515  1019  1019 I art     : Explicit concurrent mark sweep GC freed 35157(2MB) AllocSpace objects, 16(256KB) LOS objects, 33% free, 23MB/34MB, paused 7.537ms total 234.396ms
,08-23 15:43:48.525  1019  1059 I art     : WaitForGcToComplete blocked for 154.174ms for cause Explicit
,08-23 15:43:48.525  2806  7453 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-23 15:43:48.535  7470  7470 E Zygote  : MountEmulatedStorage()
08-23 15:43:48.535  7470  7470 E Zygote  : v2
08-23 15:43:48.535  7470  7470 I libpersona: KNOX_SDCARD checking this for 10032
08-23 15:43:48.535  7470  7470 I libpersona: KNOX_SDCARD not a persona
,08-23 15:43:48.535  7470  7470 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 15:43:48.545  7470  7470 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 15:43:48.545  1019  1045 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=7470 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-23 15:43:48.545  7470  7470 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
08-23 15:43:48.545  7454  7454 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 15:43:48.545  7454  7454 D ActivityThread: Added TimaKeyStore provider
,08-23 15:43:48.545  2806  7453 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,08-23 15:43:48.555  2806  7453 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,08-23 15:43:48.555  1019  1045 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,08-23 15:43:48.565  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:48.565  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:48.565  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:48.565  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:48.575  2806  7453 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,08-23 15:43:48.585  7485  7485 E Zygote  : MountEmulatedStorage()
08-23 15:43:48.585  7485  7485 E Zygote  : v2
08-23 15:43:48.585  7485  7485 I libpersona: KNOX_SDCARD checking this for 10052
08-23 15:43:48.585  7485  7485 I libpersona: KNOX_SDCARD not a persona
,08-23 15:43:48.585  7485  7485 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 15:43:48.585  7485  7485 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-23 15:43:48.585  7485  7485 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-23 15:43:48.595  1019  1045 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7485 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
08-23 15:43:48.595  1019  1045 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast,
,08-23 15:43:48.595  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-23 15:43:48.595  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:48.595  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:48.595  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:48.595  7470  7470 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 15:43:48.595  7470  7470 D ActivityThread: Added TimaKeyStore provider
,08-23 15:43:48.615  1019  1045 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=7493 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-23 15:43:48.615  7493  7493 E Zygote  : MountEmulatedStorage()
08-23 15:43:48.615  7493  7493 E Zygote  : v2
08-23 15:43:48.615  7493  7493 I libpersona: KNOX_SDCARD checking this for 10098
08-23 15:43:48.615  7493  7493 I libpersona: KNOX_SDCARD not a persona
08-23 15:43:48.615  7493  7493 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 15:43:48.625  7493  7493 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 15:43:48.635  7493  7493 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 15:43:48.635  7454  7454 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,08-23 15:43:48.645  7361  7451 D ContactProvider: getAllContactInfoList End
,08-23 15:43:48.645  7361  7451 I syncContacts: thread: 1368, sync time = 352
,08-23 15:43:48.655  7454  7454 D elm:15121: ELMEngine.ELMEngine( context ).
,08-23 15:43:48.665  7454  7454 D elm:15121: MDMBridge.setEnterpriseBridge()
,08-23 15:43:48.665  1019  1266 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
08-23 15:43:48.665  1019  1266 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-23 15:43:48.665  1019  1266 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:48.665  1019  1266 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:48.665  1019  1266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,08-23 15:43:48.665  7454  7454 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,08-23 15:43:48.675  7485  7485 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 15:43:48.675  7485  7485 D ActivityThread: Added TimaKeyStore provider
,08-23 15:43:48.675  2806  7453 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,08-23 15:43:48.675  7454  7454 D elm:15121: ElmAgentService : onCreate()
,08-23 15:43:48.675  7454  7514 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
08-23 15:43:48.675  7454  7514 D elm:15121: MainReceiver.listeningToPackageRemoved()
,08-23 15:43:48.675  7454  7514 D elm:15121: MDMBridge.getInstance()
08-23 15:43:48.675  7454  7514 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-23 15:43:48.685  7454  7514 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-23 15:43:48.685  7493  7493 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 15:43:48.685  7493  7493 D ActivityThread: Added TimaKeyStore provider
,08-23 15:43:48.685  2806  7453 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,08-23 15:43:48.695  2806  7453 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,08-23 15:43:48.695  2806  2806 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-23 15:43:48.705  7454  7454 D elm:15121: ElmAgentService : onDestroy().
,08-23 15:43:48.715  1019  1762 I ActivityManager: Killing 7021:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
,08-23 15:43:48.725  1019  1059 I art     : Explicit concurrent mark sweep GC freed 6732(344KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 3.217ms total 199.119ms
,08-23 15:43:48.735  1019  1514 D ActivityManager: startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,08-23 15:43:48.735  1019  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:48.735  1019  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:48.735  1019  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:48.735  1019  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:48.755  7518  7518 E Zygote  : MountEmulatedStorage()
08-23 15:43:48.755  7518  7518 E Zygote  : v2
08-23 15:43:48.755  7518  7518 I libpersona: KNOX_SDCARD checking this for 1000
08-23 15:43:48.755  7518  7518 I libpersona: KNOX_SDCARD not a persona
,08-23 15:43:48.755  7518  7518 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 15:43:48.755  1019  1514 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=7518 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-23 15:43:48.755  1019  1514 I ActivityManager: Killing 7071:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
,08-23 15:43:48.755  1019  4305 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-23 15:43:48.765  7518  7518 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-23 15:43:48.765  7470  7517 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
08-23 15:43:48.765  7470  7517 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
08-23 15:43:48.765  7518  7518 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-23 15:43:48.765  7470  7517 D SPPClientService: PushLog.txt file is not deleted.
08-23 15:43:48.765  7470  7517 D SPPClientService: PushLog.txt file is not deleted.
08-23 15:43:48.765  7470  7517 D SPPClientService: ============PushLog. stop!
,08-23 15:43:48.775  1019  4305 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:48.775  1019  4305 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:48.775  1019  4305 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:48.775  1019  4305 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:48.795  7528  7528 E Zygote  : MountEmulatedStorage(),
,08-23 15:43:48.795  7528  7528 I libpersona: KNOX_SDCARD checking this for 10032
,08-23 15:43:48.795  7528  7528 E Zygote  : v2
08-23 15:43:48.795  7528  7528 I libpersona: KNOX_SDCARD not a persona
08-23 15:43:48.795  7528  7528 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 15:43:48.795  1019  1044 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
08-23 15:43:48.795  1019  4305 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7528 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-23 15:43:48.805  1019  1514 I ActivityManager: Killing 7109:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,08-23 15:43:48.805  7528  7528 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 15:43:48.805  7528  7528 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-23 15:43:48.815  1019  1504 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-23 15:43:48.815  1019  1504 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,08-23 15:43:48.815  1019  1504 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:48.815  1019  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:48.815  1019  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-23 15:43:48.815  7518  7518 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 15:43:48.815  7518  7518 D ActivityThread: Added TimaKeyStore provider
08-23 15:43:48.815  1019  1544 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-23 15:43:48.815  1019  1544 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,08-23 15:43:48.815  1019  1544 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:48.815  1019  1544 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:48.815  1019  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-23 15:43:48.835  1019  1514 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-23 15:43:48.845  1019  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:48.845  1019  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:48.845  7528  7528 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 15:43:48.845  1019  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:48.845  1019  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:48.845  7528  7528 D ActivityThread: Added TimaKeyStore provider
,08-23 15:43:48.855  7550  7550 E Zygote  : MountEmulatedStorage()
,08-23 15:43:48.855  7550  7550 E Zygote  : v2
08-23 15:43:48.855  7550  7550 I libpersona: KNOX_SDCARD checking this for 10055
08-23 15:43:48.855  7550  7550 I libpersona: KNOX_SDCARD not a persona
08-23 15:43:48.855  7550  7550 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 15:43:48.855  7550  7550 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-23 15:43:48.855  1019  1514 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=7550 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-23 15:43:48.865  7550  7550 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 15:43:48.875  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 15:43:48.885  1019  1019 D RCPManagerService: PackageReceiver onReceive()
,08-23 15:43:48.885  1019  1019 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-23 15:43:48.885  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 15:43:48.885  1019  1019 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-23 15:43:48.885  1019  1019 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-23 15:43:48.885  1019  1019 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,08-23 15:43:48.895  1019  1545 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
,08-23 15:43:48.895  1019  1019 I OTPFW   : ProvisionData::getAllEntries Enter
,08-23 15:43:48.895  1019  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:48.895  1019  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:48.895  1019  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:48.895  1019  1019 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-23 15:43:48.895  1019  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:48.915  7560  7560 E Zygote  : MountEmulatedStorage()
08-23 15:43:48.915  7560  7560 E Zygote  : v2
08-23 15:43:48.915  7560  7560 I libpersona: KNOX_SDCARD checking this for 1000,
08-23 15:43:48.915  7560  7560 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 15:43:48.915  7560  7560 I libpersona: KNOX_SDCARD not a persona
,08-23 15:43:48.915  1019  1059 D PackageManager: delete codoeFile: 
08-23 15:43:48.915  7560  7560 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 15:43:48.925  7560  7560 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 15:43:48.925  1019  1545 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7560 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-23 15:43:48.935  1019  1059 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
,08-23 15:43:48.935  1019  1059 I AASA_removePackage: UID=10170 Target=com.test.thalitest
,08-23 15:43:48.935  7550  7550 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 15:43:48.935  7550  7550 D ActivityThread: Added TimaKeyStore provider
08-23 15:43:48.935  1019  1545 I ActivityManager: Killing 7182:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,08-23 15:43:48.945  1019  1059 D PackageManager: result of delete: 1{375181105}
,08-23 15:43:48.945  7357  7357 D AndroidRuntime: Shutting down VM
,08-23 15:43:48.965  7560  7560 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 15:43:48.965  7560  7560 D ActivityThread: Added TimaKeyStore provider
,08-23 15:43:48.985  1019  1059 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-23 15:43:48.985  1019  1059 D PackageManager: userId{-1}
08-23 15:43:48.985  1019  1059 D PackageManager: andCode{true}
,08-23 15:43:48.995  1019  1059 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-23 15:43:49.005  7550  7550 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-23 15:43:49.015  1019  1019 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-23 15:43:49.015  1019  1019 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-23 15:43:49.015  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-23 15:43:49.015  1019  1019 V EnterpriseBillingPolicy: uID is 10170
08-23 15:43:49.015  1019  1019 V EnterpriseBillingPolicy: Removed Packageuid is0
08-23 15:43:49.015  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-23 15:43:49.015  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-23 15:43:49.015  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-23 15:43:49.015  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-23 15:43:49.015  7560  7560 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
08-23 15:43:49.015  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-23 15:43:49.015  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-23 15:43:49.025  1019  1761 D ActivityManager: startService callerProcessName:com.android.keychain, calleePkgName: com.android.keychain
08-23 15:43:49.025  1019  1761 D ActivityManager: retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
08-23 15:43:49.025  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 15:43:49.025  1019  1761 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:49.025  1019  1761 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:49.025  1019  1761 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,08-23 15:43:49.025  1019  1504 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,08-23 15:43:49.025  1019  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:49.025  1019  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:49.025  1019  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:49.025  1019  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:49.035  1019  1044 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.,
08-23 15:43:49.035  1019  1044 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 15:43:49.035  1019  1044 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.,
,08-23 15:43:49.035  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,08-23 15:43:49.045  7587  7587 E Zygote  : MountEmulatedStorage(),
08-23 15:43:49.045  7587  7587 E Zygote  : v2,
08-23 15:43:49.045  7587  7587 I libpersona: KNOX_SDCARD checking this for 1000,
08-23 15:43:49.045  7528  7585 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-23 15:43:49.045  7587  7587 I libpersona: KNOX_SDCARD not a persona
08-23 15:43:49.045  7528  7585 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-23 15:43:49.055  7587  7587 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-23 15:43:49.055  7587  7587 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-23 15:43:49.055  7587  7587 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-23 15:43:49.055  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 15:43:49.055  7550  7550 D UserAnalysis.SecureDbManager: Key for secure DB is newly created,
,08-23 15:43:49.055  7550  7550 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() ,
08-23 15:43:49.055  7550  7550 D UserAnalysis: Create SecureDbHelper,
,08-23 15:43:49.065  1019  1504 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=7587 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-23 15:43:49.065  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-23 15:43:49.065  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-23 15:43:49.065  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-23 15:43:49.065  1019  1019 V EnterpriseBillingPolicy: uID is 10170
08-23 15:43:49.065  1019  1019 V EnterpriseBillingPolicy: Removed Packageuid is0
08-23 15:43:49.065  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-23 15:43:49.065  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-23 15:43:49.065  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-23 15:43:49.065  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-23 15:43:49.065  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-23 15:43:49.065  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-23 15:43:49.065  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-23 15:43:49.065  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-23 15:43:49.065  1019  3348 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,08-23 15:43:49.075  7528  7585 D SPPClientService: PushLog.txt file is not deleted.
08-23 15:43:49.075  7528  7585 D SPPClientService: PushLog.txt file is not deleted.
08-23 15:43:49.075  7528  7585 D SPPClientService: ============PushLog. stop!
,08-23 15:43:49.075  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 15:43:49.075  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-23 15:43:49.075  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-23 15:43:49.085  1019  1019 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
,08-23 15:43:49.085  1019  1164 D TaskPersister: removeObsoleteFile: deleting file=163_task.xml
,08-23 15:43:49.085  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-23 15:43:49.085  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-23 15:43:49.095  7587  7587 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 15:43:49.095  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-23 15:43:49.095  7587  7587 D ActivityThread: Added TimaKeyStore provider
,08-23 15:43:49.095  1019  4305 D ActivityManager: startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
08-23 15:43:49.095  1019  4305 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
,08-23 15:43:49.095  1019  4305 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:49.095  1019  4305 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:49.095  1019  4305 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,08-23 15:43:49.095  1019  1504 D LocationManagerService: getProviders()=[passive, gps]
,08-23 15:43:49.095  1019  1761 D ActivityManager: getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
,08-23 15:43:49.095  7550  7550 D IntelligenceServiceApplication: onCreate()
,08-23 15:43:49.095  7550  7550 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,08-23 15:43:49.095  1019  1761 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:49.095  1019  1761 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:49.095  1019  1761 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:49.095  1019  1761 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:49.105  7550  7550 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-23 15:43:49.115  7607  7607 E Zygote  : MountEmulatedStorage()
,08-23 15:43:49.115  7607  7607 E Zygote  : v2
08-23 15:43:49.115  7607  7607 I libpersona: KNOX_SDCARD checking this for 10014
08-23 15:43:49.115  7607  7607 I libpersona: KNOX_SDCARD not a persona
,08-23 15:43:49.115  7607  7607 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 15:43:49.125  1019  1761 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7607 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
,08-23 15:43:49.125  7607  7607 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 15:43:49.125  7607  7607 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-23 15:43:49.125  1019  1031 I ActivityManager: Killing 7165:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
08-23 15:43:49.125  1019  1504 I ActivityManager: Killing 7198:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
,08-23 15:43:49.125  1019  1505 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-23 15:43:49.145  1019  1762 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,08-23 15:43:49.145  7607  7607 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 15:43:49.145  1019  1762 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:49.145  7607  7607 D ActivityThread: Added TimaKeyStore provider
08-23 15:43:49.145  1019  1762 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:49.145  1019  1762 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:49.145  1019  1762 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:49.155   314   314 I art     : Explicit concurrent mark sweep GC freed 8703(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 630us total 34.134ms
08-23 15:43:49.155  7550  7550 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-23 15:43:49.155  7357  7357 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-23 15:43:49.165  7550  7550 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-23 15:43:49.175   314   314 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 577us total 17.578ms
,08-23 15:43:49.175  7587  7624 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_REMOVED
,08-23 15:43:49.185  7587  7624 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,08-23 15:43:49.195  7550  7550 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
08-23 15:43:49.195  7550  7550 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
08-23 15:43:49.195  7550  7550 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
08-23 15:43:49.195  7550  7550 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
08-23 15:43:49.195  7550  7550 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
08-23 15:43:49.195  7550  7550 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
08-23 15:43:49.195  7550  7550 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
08-23 15:43:49.195  7550  7550 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
08-23 15:43:49.195  7550  7550 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
08-23 15:43:49.195  7550  7550 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
08-23 15:43:49.195   314   314 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 562us total 17.507ms
,08-23 15:43:49.195  7550  7550 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
08-23 15:43:49.195  7550  7550 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
08-23 15:43:49.195  7550  7550 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,08-23 15:43:49.195  7550  7550 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
08-23 15:43:49.195  7550  7550 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
08-23 15:43:49.195  7550  7550 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
08-23 15:43:49.195  7550  7550 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
08-23 15:43:49.205  7550  7550 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
,08-23 15:43:49.205  7550  7550 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
08-23 15:43:49.205   289   289 E SMD     : DCD OFF
08-23 15:43:49.205  7550  7550 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
08-23 15:43:49.205  7550  7550 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
08-23 15:43:49.205  7550  7550 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
08-23 15:43:49.205  7550  7550 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
08-23 15:43:49.205  7550  7550 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
,08-23 15:43:49.215   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 15:43:49.215  7550  7550 D BluetoothAdapter: cancelDiscovery
,08-23 15:43:49.215  7626  7626 E Zygote  : MountEmulatedStorage()
08-23 15:43:49.215  7626  7626 I libpersona: KNOX_SDCARD checking this for 1000
08-23 15:43:49.215  7626  7626 E Zygote  : v2
08-23 15:43:49.215  7626  7626 I libpersona: KNOX_SDCARD not a persona
,08-23 15:43:49.215  1019  1762 I ActivityManager: Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=7626 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
08-23 15:43:49.225  1019  1762 I ActivityManager: Killing 7219:com.wsomacp/u0a23 (adj 15): empty #21
,08-23 15:43:49.225  7626  7626 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 15:43:49.235  7626  7626 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 15:43:49.235  7626  7626 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-23 15:43:49.235  1019  4305 D ActivityManager: startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
08-23 15:43:49.235  1019  4305 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
,08-23 15:43:49.235  7485  7546 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-23 15:43:49.235  1019  4305 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:49.235  1019  4305 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:49.235  1019  4305 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,08-23 15:43:49.245  7587  7587 D AcmsService: Enter Oncreate
08-23 15:43:49.245  7587  7587 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-23 15:43:49.245  7587  7587 D AcmsService: creating AcmsCore
,08-23 15:43:49.245  7587  7587 D AcmsCore: AcmsCore.getAcmsCore() - Enter
08-23 15:43:49.245  7587  7587 D AcmsCore: AcmsCore
,08-23 15:43:49.245  7587  7587 D AcmsCore: init
08-23 15:43:49.245  7587  7587 D AcmsCore: Looper handler is not null
08-23 15:43:49.245  7587  7587 D AcmsCore: Post to AcmsCoreHandler
08-23 15:43:49.245  7587  7587 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-23 15:43:49.245  7587  7587 D AcmsServiceMonitor: Incrementing - Counter value: 1
08-23 15:43:49.245  7587  7587 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>1
08-23 15:43:49.245  7587  7587 D AcmsService: onStartCommand
08-23 15:43:49.245  7587  7587 D AcmsService: Action: android.intent.action.PACKAGE_REMOVED
08-23 15:43:49.245  7587  7587 D AcmsServiceMonitor: Enter incrementSvcCounter with startId 1
08-23 15:43:49.245  7587  7587 D AcmsServiceMonitor: Incrementing - Counter value: 2
08-23 15:43:49.245  7587  7587 D AcmsService: Incremented Counter Value : onStartCommand
,08-23 15:43:49.245  7587  7635 D AcmsCertificateMngr: AcmsCertificateMngr
,08-23 15:43:49.255  7587  7635 D AcmsRevocationMngr: AcmsRevocationMngr
,08-23 15:43:49.255  1019  1544 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
08-23 15:43:49.255  7587  7587 D ActivityThread: Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,08-23 15:43:49.255  3184  3195 D BluetoothAdapterProperties: mDiscovering is false
08-23 15:43:49.255  3184  3195 E BluetoothAdapterService: This is not a scanning status. cancelDiscovery() will be not called.
,08-23 15:43:49.255  1019  1044 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
08-23 15:43:49.255  1019  1044 D UsbSettingsManager: clearDefaults: com.test.thalitest
08-23 15:43:49.255  7550  7550 D BluetoothAdapter: cancelDiscovery = true
08-23 15:43:49.255  7550  7550 V PlaceDetection v1.0.19 : [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
,08-23 15:43:49.265  1670  1670 E NetworkScheduler.SchedulerReceiver: Invalid parameter app,
08-23 15:43:49.265  1019  1266 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
08-23 15:43:49.265  1670  1670 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
08-23 15:43:49.265  7361  7361 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
08-23 15:43:49.265  1019  1032 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
08-23 15:43:49.265  7626  7626 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 15:43:49.265  7550  7550 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.,
08-23 15:43:49.265  7550  7550 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
08-23 15:43:49.265  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:49.265  7626  7626 D ActivityThread: Added TimaKeyStore provider
08-23 15:43:49.265  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:49.265  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:49.265  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:49.285  7361  7361 E SharedPreferencesImpl: Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
08-23 15:43:49.285  7643  7643 E Zygote  : MountEmulatedStorage()
08-23 15:43:49.285  7643  7643 I libpersona: KNOX_SDCARD checking this for 10117
08-23 15:43:49.285  7643  7643 E Zygote  : v2
08-23 15:43:49.285  7643  7643 I libpersona: KNOX_SDCARD not a persona
,08-23 15:43:49.285  7643  7643 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 15:43:49.285  7550  7550 W FileUtils: Failed to chmod(/data/data/com.samsung.android.intelligenceservice/databases/dump.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
08-23 15:43:49.285  7550  7550 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-23 15:43:49.285  7550  7550 E SQLiteLog: (3850) statement aborts at 17: [INSERT INTO dump_log(timestamp,message) VALUES (?,?)] disk I/O error
08-23 15:43:49.285  1019  1032 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7643 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-23 15:43:49.295  7550  7550 E SQLiteDatabase: Error inserting timestamp=1471959829120 message=Predictor: service is stopped by Application.onCreate
08-23 15:43:49.295  7550  7550 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 15:43:49.295  7550  7550 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-23 15:43:49.295  7550  7550 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
08-23 15:43:49.295  7550  7550 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
08-23 15:43:49.295  7550  7550 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-23 15:43:49.295  7550  7550 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
08-23 15:43:49.295  7550  7550 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
08-23 15:43:49.295  7550  7550 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:110)
08-23 15:43:49.295  7550  7550 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
08-23 15:43:49.295  7550  7550 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
08-23 15:43:49.295  7550  7550 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-23 15:43:49.295  7550  7550 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-23 15:43:49.295  7550  7550 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 15:43:49.295  7550  7550 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 15:43:49.295  7550  7550 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 15:43:49.295  7550  7550 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 15:43:49.295  7550  7550 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-23 15:43:49.295  7550  7550 E UserAnalysis: It failed to insert to dump_log table
08-23 15:43:49.295  7550  7550 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-23 15:43:49.295  7550  7550 E SQLiteLog: (3850) statement aborts at 17: [INSERT INTO dump_log(timestamp,message) VALUES (?,?)] disk I/O error
,08-23 15:43:49.295  7550  7550 E SQLiteDatabase: Error inserting timestamp=1471959829269 message=Predictor: service stopped by removePlaceCategories()
08-23 15:43:49.295  7550  7550 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 15:43:49.295  7550  7550 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-23 15:43:49.295  7550  7550 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
08-23 15:43:49.295  7550  7550 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
08-23 15:43:49.295  7550  7550 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-23 15:43:49.295  7550  7550 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
08-23 15:43:49.295  7550  7550 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
08-23 15:43:49.295  7550  7550 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:110)
08-23 15:43:49.295  7550  7550 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
08-23 15:43:49.295  7550  7550 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
08-23 15:43:49.295  7550  7550 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-23 15:43:49.295  7550  7550 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-23 15:43:49.295  7550  7550 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 15:43:49.295  7550  7550 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 15:43:49.295  7550  7550 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 15:43:49.295  7550  7550 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 15:43:49.295  7550  7550 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-23 15:43:49.295  7550  7550 E UserAnalysis: It failed to insert to dump_log table
08-23 15:43:49.295  7643  7643 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 15:43:49.305  7029  7029 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
08-23 15:43:49.305  7643  7643 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-23 15:43:49.305  7587  7587 D AcmsService: Inside handle Intent
08-23 15:43:49.305  7587  7587 D AcmsService: App removed - package name: com.test.thalitest
08-23 15:43:49.305  7587  7587 D AcmsCore: Post to AcmsCoreHandler
08-23 15:43:49.305  7587  7587 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-23 15:43:49.305  7587  7587 D AcmsServiceMonitor: Incrementing - Counter value: 3
08-23 15:43:49.305  7587  7587 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>5
08-23 15:43:49.305  7587  7587 D AcmsService: Decremented Counter Value : handleStartIntent
08-23 15:43:49.305  7587  7587 D AcmsServiceMonitor: Decrementing - Counter value: 2
08-23 15:43:49.305  7485  7546 E SQLiteLog: (28) failed to open "/data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db" with flag (131138) and mode_t (0) due to error (30)
08-23 15:43:49.315  1019  1031 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
08-23 15:43:49.315  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
08-23 15:43:49.315  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:49.315  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:49.315  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
08-23 15:43:49.325  1019  1762 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
08-23 15:43:49.325  1019  1762 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
08-23 15:43:49.325  7029  7656 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
08-23 15:43:49.325  7029  7656 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
08-23 15:43:49.325  1019  1762 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:49.325  1019  1762 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:49.325  1019  1762 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-23 15:43:49.325  7485  7546 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db'.
08-23 15:43:49.325  7485  7546 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 15:43:49.325  7485  7546 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 15:43:49.325  7485  7546 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-23 15:43:49.325  7485  7546 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-23 15:43:49.325  7485  7546 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-23 15:43:49.325  7485  7546 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-23 15:43:49.325  7485  7546 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-23 15:43:49.325  7485  7546 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-23 15:43:49.325  7485  7546 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-23 15:43:49.325  7485  7546 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-23 15:43:49.325  7485  7546 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-23 15:43:49.325  7485  7546 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-23 15:43:49.325  7485  7546 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 15:43:49.325  7485  7546 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 15:43:49.325  7485  7546 E SQLiteDatabase: 	at com.google.android.search.core.icingsync.d.getWritableDatabase(InternalIcingCorporaProvider.java:592)
08-23 15:43:49.325  7485  7546 E SQLiteDatabase: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:284)
08-23 15:43:49.325  7485  7546 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:340)
08-23 15:43:49.325  7485  7546 E SQLiteDatabase: 	at android.content.ContentResolver.update(ContentResolver.java:1386)
08-23 15:43:49.325  7485  7546 E SQLiteDatabase: 	at com.google.android.search.core.icingsync.e.Jx(UpdateIcingCorporaService.java:408)
08-23 15:43:49.325  7485  7546 E SQLiteDatabase: 	at com.google.android.search.core.icingsync.g.bdp(UpdateIcingCorporaService.java:347)
08-23 15:43:49.325  7485  7546 E SQLiteDatabase: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
08-23 15:43:49.325  7485  7546 E SQLiteDatabase: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:1215)
08-23 15:43:49.325  7485  7546 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-23 15:43:49.325  7485  7546 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 15:43:49.325  7485  7546 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-23 15:43:49.325  7485  7546 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 15:43:49.335  7626  7626 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-23 15:43:49.335  7643  7643 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 15:43:49.335  7643  7643 D ActivityThread: Added TimaKeyStore provider
08-23 15:43:49.335  1019  1546 I TactileAssist: enable value -1
08-23 15:43:49.335  1019  1546 I TactileAssist: internal enable value -1
08-23 15:43:49.335  1019  1546 I TactileAssist: intensity value -1
08-23 15:43:49.335  1019  1546 I TactileAssist: saveAppList value true
08-23 15:43:49.345  3774  7662 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-23 15:43:49.345  3774  7662 D AccountUtils: Clearing selected account for com.test.thalitest
08-23 15:43:49.345  1019  1546 I TactileAssist: List of disabled apps :
08-23 15:43:49.355  1019  1761 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-23 15:43:49.355  1019  1761 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService; callingUser = 0; userId(target) = 0
08-23 15:43:49.355  1019  1761 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:49.355  1019  1761 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:49.355  1019  1761 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
08-23 15:43:49.355  1019  1761 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:49.355  1019  1761 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:49.355  1019  1761 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:49.355  1019  1761 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:49.365  7643  7643 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 15:43:49.365  7626  7626 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.sm/databases/lowpowercontext-system-db" with flag (131138) and mode_t (0) due to error (30)
08-23 15:43:49.365  7664  7664 E Zygote  : MountEmulatedStorage()
08-23 15:43:49.365  7664  7664 E Zygote  : v2
08-23 15:43:49.365  7664  7664 I libpersona: KNOX_SDCARD checking this for 10052
08-23 15:43:49.365  7664  7664 I libpersona: KNOX_SDCARD not a persona
08-23 15:43:49.375  7626  7626 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.sm/databases/lowpowercontext-system-db'.
08-23 15:43:49.375  7626  7626 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 15:43:49.375  7626  7626 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 15:43:49.375  7626  7626 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-23 15:43:49.375  7626  7626 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-23 15:43:49.375  7626  7626 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-23 15:43:49.375  7626  7626 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-23 15:43:49.375  7626  7626 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-23 15:43:49.375  7626  7626 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-23 15:43:49.375  7626  7626 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-23 15:43:49.375  7626  7626 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-23 15:43:49.375  7626  7626 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-23 15:43:49.375  7626  7626 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-23 15:43:49.375  7626  7626 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 15:43:49.375  7626  7626 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 15:43:49.375  7626  7626 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f$b.a(DataStore.java:2443)
08-23 15:43:49.375  7626  7626 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(DataStore.java:85)
08-23 15:43:49.375  7626  7626 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextProvider.onCreate(LowpowerContextProvider.java:303)
08-23 15:43:49.375  7626  7626 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
08-23 15:43:49.375  7626  7626 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
08-23 15:43:49.375  7626  7626 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
08-23 15:43:49.375  7626  7626 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
08-23 15:43:49.375  7626  7626 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
08-23 15:43:49.375  7626  7626 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-23 15:43:49.375  7626  7626 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-23 15:43:49.375  7626  7626 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 15:43:49.375  7626  7626 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-23 15:43:49.375  7626  7626 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 15:43:49.375  7626  7626 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 15:43:49.375  7626  7626 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 15:43:49.375  7626  7626 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 15:43:49.375  7626  7626 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-23 15:43
```
