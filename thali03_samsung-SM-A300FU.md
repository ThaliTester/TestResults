#### Test 834440500e39eda_thali03_samsung-SM-A300FU Logs


```
--------- beginning of main
09-07 10:31:51.853  6941  6941 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
09-07 10:31:51.873  6941  6941 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,--------- beginning of system
09-07 10:31:51.983  1013  1496 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
09-07 10:31:51.993  1013  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:31:51.993  1013  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:31:51.993  1013  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:31:51.993  1013  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:31:52.003  1013  1496 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7002 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
09-07 10:31:52.013  1013  1496 I ActivityManager: Killing 6571:com.wsomacp/u0a23 (adj 15): empty #21
09-07 10:31:52.023  7002  7002 E Zygote  : MountEmulatedStorage()
09-07 10:31:52.023  7002  7002 E Zygote  : v2
09-07 10:31:52.023  7002  7002 I libpersona: KNOX_SDCARD checking this for 10148
09-07 10:31:52.023  7002  7002 I libpersona: KNOX_SDCARD not a persona
09-07 10:31:52.023  1013  1479 I art     : Explicit concurrent mark sweep GC freed 143543(8MB) AllocSpace objects, 3(1847KB) LOS objects, 33% free, 23MB/34MB, paused 2.626ms total 164.695ms
09-07 10:31:52.023  7002  7002 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 10:31:52.023  7002  7002 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 10:31:52.023  7002  7002 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-07 10:31:52.053  1013  3836 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-07 10:31:52.053  1013  3836 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:31:52.053  1013  3836 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 10:31:52.053  1013  3836 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
09-07 10:31:52.063  7002  7002 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 10:31:52.073  7002  7002 D ActivityThread: Added TimaKeyStore provider
09-07 10:31:52.083  1013  1479 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-07 10:31:52.083  1013  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
09-07 10:31:52.083  1013  1479 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:31:52.083  1013  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 10:31:52.083  1013  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-07 10:31:52.093  1013  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
09-07 10:31:52.093  1013  1479 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:31:52.103  1013  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 10:31:52.103  1013  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-07 10:31:52.123  1013  1026 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-07 10:31:52.123  1013  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
09-07 10:31:52.123  1013  1026 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:31:52.123  1013  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 10:31:52.123  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-07 10:31:52.153  1013  1133 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-07 10:31:52.153  1013  1133 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:31:52.153  1013  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 10:31:52.153  1013  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-07 10:31:52.153  6961  6961 W art     : Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 304.372ms
09-07 10:31:52.163  7002  7002 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
09-07 10:31:52.183  2645  4413 I art     : Explicit concurrent mark sweep GC freed 14683(687KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 8MB/13MB, paused 1.022ms total 65.075ms
09-07 10:31:52.193  6941  6941 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-07 10:31:52.203  1013  3832 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
09-07 10:31:52.203  1013  3832 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:31:52.203  1013  3832 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:31:52.203  1013  3832 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:31:52.203  1013  3832 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:31:52.203  6941  6941 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-07 10:31:52.213  7000  7000 D AndroidRuntime: 
09-07 10:31:52.213  7000  7000 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-07 10:31:52.223  7022  7022 E Zygote  : MountEmulatedStorage()
09-07 10:31:52.223  7022  7022 E Zygote  : v2
09-07 10:31:52.223  7022  7022 I libpersona: KNOX_SDCARD checking this for 1000
09-07 10:31:52.223  7022  7022 I libpersona: KNOX_SDCARD not a persona
09-07 10:31:52.223  7000  7000 D AndroidRuntime: CheckJNI is OFF
09-07 10:31:52.223  7000  7000 D AndroidRuntime: readGMSProperty: start
09-07 10:31:52.223  7000  7000 D AndroidRuntime: readGMSProperty: already setted!!
09-07 10:31:52.223  7000  7000 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-07 10:31:52.223  7000  7000 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-07 10:31:52.223  7000  7000 D AndroidRuntime: readGMSProperty: end
09-07 10:31:52.223  7000  7000 D AndroidRuntime: addProductProperty: start
09-07 10:31:52.223  7022  7022 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 10:31:52.223  7022  7022 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 10:31:52.223  1013  3832 I ActivityManager: Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=7022 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-07 10:31:52.223  1013  3832 I ActivityManager: Killing 6587:com.sec.esdk.elm/u0a90 (adj 15): empty #21
09-07 10:31:52.223  7022  7022 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-07 10:31:52.233  6941  6941 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-07 10:31:52.233  6941  6941 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-07 10:31:52.243  6941  6941 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-07 10:31:52.243  6941  6941 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-07 10:31:52.243  6941  6941 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-07 10:31:52.253  6941  6941 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-07 10:31:52.253   272   272 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb73c77c8
09-07 10:31:52.253   272   272 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
09-07 10:31:52.253   272   272 I rmt_storage: wakelock acquired: 1, error no: 42
09-07 10:31:52.253  6941  6941 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-07 10:31:52.253   272   347 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1220773752)
09-07 10:31:52.253  7022  7022 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 10:31:52.253  7022  7022 D ActivityThread: Added TimaKeyStore provider
09-07 10:31:52.273  7022  7022 W ResourcesManager: Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
09-07 10:31:52.283  6941  6941 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-07 10:31:52.283  6941  6941 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-07 10:31:52.283  6941  6941 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-07 10:31:52.303  1013  1133 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-07 10:31:52.303  1013  1133 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:31:52.303  1013  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 10:31:52.303  1013  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-07 10:31:52.313   272   347 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
09-07 10:31:52.313   272   347 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
09-07 10:31:52.313   272   347 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1220773752) wakelock released: 1, error no: 0
09-07 10:31:52.313   272   347 I rmt_storage: 
09-07 10:31:52.313   272   272 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb73c77c8
09-07 10:31:52.323  6941  6941 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-07 10:31:52.323  6941  6941 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-07 10:31:52.323  6941  6941 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-07 10:31:52.323  6941  6941 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-07 10:31:52.323  6941  6941 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
09-07 10:31:52.343  1924  6833 W BaseAppContext: Using Auth Proxy for data requests.
09-07 10:31:52.353  1924  6833 W BaseAppContext: Using Auth Proxy for data requests.
09-07 10:31:52.363  6941  6941 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-07 10:31:52.363  6941  6941 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-07 10:31:52.373  6779  6835 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 539 ms] updated apps [took 539 ms] 
09-07 10:31:52.373  7000  7000 E AffinityControl: AffinityControl: registerfunction enter
09-07 10:31:52.373  1013  3386 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
09-07 10:31:52.393  1013  1461 I ActivityManager: Killing 6322:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
09-07 10:31:52.393  1013  1461 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
09-07 10:31:52.393  1013  1461 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:31:52.393  1013  1461 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:31:52.393  1013  1461 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:31:52.393  1013  1461 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:31:52.403  7000  7000 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-07 10:31:52.413  1013  1461 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7054 uid=10152 gids={50152, 9997} abi=armeabi-v7a
09-07 10:31:52.423  7054  7054 E Zygote  : MountEmulatedStorage()
09-07 10:31:52.423  7054  7054 E Zygote  : v2
09-07 10:31:52.423  1013  1461 I ActivityManager: Killing 6341:com.android.calendar/u0a131 (adj 15): empty #21
09-07 10:31:52.423  7054  7054 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 10:31:52.423  7054  7054 I libpersona: KNOX_SDCARD checking this for 10152
09-07 10:31:52.423  7054  7054 I libpersona: KNOX_SDCARD not a persona
09-07 10:31:52.423  7054  7054 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 10:31:52.423  7054  7054 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-07 10:31:52.433  6941  6941 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-07 10:31:52.433  6941  6941 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-07 10:31:52.433  6941  6941 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
09-07 10:31:52.433  1013  1321 E PersonaManagerService: inState():  stateMachine is null !!
09-07 10:31:52.433  1013  1321 I PersonaManagerService: PersonaId don't exist
09-07 10:31:52.433  1013  1321 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
09-07 10:31:52.443  1924  6833 W BaseAppContext: Using Auth Proxy for data requests.
09-07 10:31:52.443  1013  1321 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-07 10:31:52.443  6961  6961 W art     : Verification of com.sec.android.touchwiz.animator.TwDndHorizontalListAnimator com.android.mms.ArtClassLoader.createTwDndHorizontalListAnimator(android.content.Context) took 290.696ms
09-07 10:31:52.453  6961  7064 D Mms/ArtClassLoader: init before art
09-07 10:31:52.463  6961  6961 D Mms/TelephonyPermission: start operation mode monitor
09-07 10:31:52.463  7054  7054 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 10:31:52.463  7054  7054 D ActivityThread: Added TimaKeyStore provider
09-07 10:31:52.473  6961  6961 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-07 10:31:52.483  1013  1321 W ActivityManager: mDVFSHelper.acquire()
09-07 10:31:52.483  1013  1321 D FocusedStackFrame: Set to : 0
09-07 10:31:52.493  1013  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:31:52.493  1013  1045 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-07 10:31:52.493  1013  1045 D PhoneWindow: *FMB* installDecor flags : -2122120936
09-07 10:31:52.493  1013  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:31:52.493  1013  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:31:52.493  1013  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:31:52.513  1013  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-07 10:31:52.513  1013  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-07 10:31:52.513   257   257 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
09-07 10:31:52.523  1013  1321 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7071 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-07 10:31:52.533  1013  1321 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
09-07 10:31:52.533  1013  1321 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-07 10:31:52.533  7071  7071 E Zygote  : MountEmulatedStorage()
09-07 10:31:52.533  7071  7071 E Zygote  : v2
09-07 10:31:52.533  7071  7071 I libpersona: KNOX_SDCARD checking this for 10170
09-07 10:31:52.533  7071  7071 I libpersona: KNOX_SDCARD not a persona
09-07 10:31:52.543  1013  1321 D InputDispatcher: Focused application set to: xxxx
09-07 10:31:52.543  1013  1321 D InputDispatcher: Focus left window: 1488
09-07 10:31:52.543  7071  7071 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 10:31:52.543  7000  7000 D AndroidRuntime: Shutting down VM
09-07 10:31:52.553  7071  7071 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 10:31:52.553  7071  7071 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
09-07 10:31:52.563  1013  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-07 10:31:52.563  1013  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
09-07 10:31:52.573  6961  6961 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
09-07 10:31:52.573  6961  6961 D Mms/TelephonyPermission: isDefault true
09-07 10:31:52.573  1924  6831 I qtaguid : Untagging socket 97
09-07 10:31:52.573  6961  6961 D Mms/MmsApp: onCreate() com.android.mms
09-07 10:31:52.583  1013  1321 I ActivityManager: Killing 6607:com.samsung.android.securitylogagent/1000 (adj 15): empty #21
09-07 10:31:52.583  1013  1481 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
09-07 10:31:52.593  7071  7071 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 10:31:52.593  7071  7071 D ActivityThread: Added TimaKeyStore provider
09-07 10:31:52.593  1013  3836 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
09-07 10:31:52.603  1013  1013 V ActivityManager: Display changed displayId=0
09-07 10:31:52.613  1013  1045 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
09-07 10:31:52.623  1013  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-07 10:31:52.623  7054  7054 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
09-07 10:31:52.623  7054  7054 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
09-07 10:31:52.633  1013  1045 W DisplayManagerService: Failed to notify process 6607 that displays changed, assuming it died.
09-07 10:31:52.633  1013  1045 W DisplayManagerService: android.os.TransactionTooLargeException
09-07 10:31:52.633  1013  1045 W DisplayManagerService: 	at android.os.BinderProxy.transactNative(Native Method)
09-07 10:31:52.633  1013  1045 W DisplayManagerService: 	at android.os.BinderProxy.transact(Binder.java:496)
09-07 10:31:52.633  1013  1045 W DisplayManagerService: 	at android.hardware.display.IDisplayManagerCallback$Stub$Proxy.onDisplayEvent(IDisplayManagerCallback.java:81)
09-07 10:31:52.633  1013  1045 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService$CallbackRecord.notifyDisplayEventAsync(DisplayManagerService.java:1372)
09-07 10:31:52.633  1013  1045 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService.deliverDisplayEvent(DisplayManagerService.java:1170)
09-07 10:31:52.633  1013  1045 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService.access$500(DisplayManagerService.java:146)
09-07 10:31:52.633  1013  1045 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService$DisplayManagerHandler.handleMessage(DisplayManagerService.java:1305)
09-07 10:31:52.633  1013  1045 W DisplayManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 10:31:52.633  1013  1045 W DisplayManagerService: 	at android.os.Looper.loop(Looper.java:145)
09-07 10:31:52.633  1013  1045 W DisplayManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 10:31:52.633  1013  1045 W DisplayManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-07 10:31:52.633  7054  7054 I TapandpayWidget:Utils: Clear T&P info.
09-07 10:31:52.633  1924  1924 I ConfigFetchService: fetch service done; releasing wakelock
09-07 10:31:52.643  1924  1924 I ConfigFetchService: stopping self
09-07 10:31:52.643  1013  3836 D PersonaManager: isKioskContainerExistOnDevice
09-07 10:31:52.653  7054  7054 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
09-07 10:31:52.653  1013  3836 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
09-07 10:31:52.663  1013  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:31:52.663  1013  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:31:52.663  1013  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:31:52.663  1013  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:31:52.683  6961  6961 D Mms/MmsApp: [start]    initCountryIso consume time = 900.045416
09-07 10:31:52.683  7088  7088 E Zygote  : MountEmulatedStorage()
09-07 10:31:52.683  7088  7088 E Zygote  : v2
09-07 10:31:52.683  7088  7088 I libpersona: KNOX_SDCARD checking this for 10009
09-07 10:31:52.683  7088  7088 I libpersona: KNOX_SDCARD not a persona
09-07 10:31:52.683  7088  7088 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 10:31:52.683  7088  7088 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 10:31:52.683  1013  3836 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=7088 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
09-07 10:31:52.693  1013  3836 I ActivityManager: Killing 6638:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
09-07 10:31:52.693  7088  7088 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
09-07 10:31:52.703  1013  3836 D CountryDetector: The first listener is added
09-07 10:31:52.733  1013  1013 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
09-07 10:31:52.743   292   292 E SMD     : DCD OFF
09-07 10:31:52.753  7000  7000 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
09-07 10:31:52.753  1013  3832 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
09-07 10:31:52.753  6941  6941 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
09-07 10:31:52.753  1013  3832 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
09-07 10:31:52.753  7088  7088 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 10:31:52.753  1013  3832 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:31:52.753  1013  3832 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 10:31:52.753  1013  3832 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
09-07 10:31:52.753  7088  7088 D ActivityThread: Added TimaKeyStore provider
,09-07 10:31:52.763   257   448 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
,09-07 10:31:52.763   257  1095 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
,09-07 10:31:52.763  6961  6961 D Mms/MmsApp: [end]    initCountryIso consume time = 87.636927
09-07 10:31:52.763  6961  6961 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.320313
,09-07 10:31:52.783  1488  1488 V ActivityThread: updateVisibility : ActivityRecord{15987bf0 token=android.os.BinderProxy@2c06ceda {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
09-07 10:31:52.783  1488  1488 D Launcher: onTrimMemory. Level: 20
,09-07 10:31:52.793  6961  6961 D Mms/MmsConfig: before partial update
,09-07 10:31:52.793  1013  1093 V AlarmManager: waitForAlarm result :4
,09-07 10:31:52.803  6941  7109 D Ads     : Skipping gmscore version check
,09-07 10:31:52.813  1013  3836 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-07 10:31:52.813  1013  3836 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:31:52.823  1013  3836 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 10:31:52.823  1013  3836 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,09-07 10:31:52.823  6961  6961 D Mms/MmsConfig: Load Resize quality : 80
,09-07 10:31:52.833  6941  6941 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,09-07 10:31:52.843  6961  6961 D EasySignUpManager_1.0.1: serviceId : 1, features : -1
,09-07 10:31:52.843  6961  6961 D EasySignUpManager_1.0.1: isAuth is false
09-07 10:31:52.843  6961  6961 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,09-07 10:31:52.853  6941  6941 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-07 10:31:52.873  1465  1484 D TP/MmsSmsProvider: query,matched:2117, calling pid = 6961
,09-07 10:31:52.873  7071  7071 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,09-07 10:31:52.873  1465  1484 D TP/MmsSmsProvider: match 2117:Elapsed time : 2.526 ms
,09-07 10:31:52.893  6961  6961 D EasySignUpManager_1.0.1: isAuth is false
09-07 10:31:52.893  6961  6961 D EasySignUpManager_1.0.1: getServiceStatus : serviceId (1) is OFF
,09-07 10:31:52.893  6961  6961 E CscParser: mps_code.dat does not exist
09-07 10:31:52.893  6961  6961 E CscParser: customer_path =/system/csc/customer.xml
,09-07 10:31:52.893  6961  6961 E CscParser: fileName + /system/csc/customer.xml
,09-07 10:31:52.903  7071  7071 I cr.library_loader: Time to load native libraries: 5 ms (timestamps 8159-8164)
,09-07 10:31:52.903  7071  7071 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-07 10:31:52.913  6886  6960 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
09-07 10:31:52.913  6886  6960 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-07 10:31:52.913  6886  6960 I GAv4    :   adb logcat -s GAv4
,09-07 10:31:52.913  6961  6961 E CscParser: mps_code.dat does not exist
09-07 10:31:52.913  6961  6961 E CscParser: customer_path =/system/csc/customer.xml
09-07 10:31:52.913  6961  6961 E CscParser: fileName + /system/csc/customer.xml
,09-07 10:31:52.943  6886  6960 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-07 10:31:52.943  1013  1504 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,09-07 10:31:52.953  6961  6961 D CscParser: getInstance fileName =/system/csc/customer.xml
,09-07 10:31:52.953  6961  6961 D Mms/MmsConfig:  enable multiwindow = false
,09-07 10:31:52.953  1013  1479 I ActivityManager: Killing 6617:com.android.providers.calendar/u0a37 (adj 15): empty #21
,09-07 10:31:52.963  6961  6961 E Mms/MessageUtils: setCountryDetector : update country detector info 
09-07 10:31:52.963  6961  6961 E Mms/MessageUtils: updateCountryIso : update country iso info 
,09-07 10:31:52.963  6961  6961 D Mms/MmsConfig: [end]    init() consume time = 200.210156
,09-07 10:31:52.973  6961  6961 D Mms/Contact: [start]    init() consume time = 1.675833
,09-07 10:31:52.973  6886  6960 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-07 10:31:52.983  1465  1484 D TP/MmsSmsProvider: query,matched:13, calling pid = 6961
,09-07 10:31:52.983  7071  7071 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {7b573b6}
,09-07 10:31:52.993  7071  7071 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-07 10:31:52.993  1465  1484 D TP/MmsSmsProvider: match 13:Elapsed time : 2.531 ms
,09-07 10:31:52.993  7071  7071 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,09-07 10:31:52.993  6961  6961 D Mms/Contact: [end]    init consume time = 26.549219
,09-07 10:31:53.003  6886  6960 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.357.23.33
,09-07 10:31:53.023  6961  7120 D Mms/DraftCache: [start]    rebuildCache consume time = 24.343073
,09-07 10:31:53.033  1465  1998 D TP/MmsSmsProvider: query,matched:12, calling pid = 6961
,09-07 10:31:53.033  1465  1998 D TP/MmsSmsProvider: match 12:Elapsed time : 1.008 ms
,09-07 10:31:53.033  6961  7120 D Mms/DraftCache: [end]    rebuildCache consume time = 15.476771
,09-07 10:31:53.033  6961  6961 D Mms/MethodReflector: getSubId is called
09-07 10:31:53.033  6961  6961 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,09-07 10:31:53.043  6961  6961 D Mms/MethodReflector: getTelephonyProperty is called
09-07 10:31:53.043  6961  6961 D Mms/DownloadManager: roaming -> false (slotId = 0)
09-07 10:31:53.043  6961  6961 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
09-07 10:31:53.043  6961  6961 D Mms/DownloadManager: auto download without roaming -> true
09-07 10:31:53.043  6961  6961 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
09-07 10:31:53.043  6961  6961 D Mms/MethodReflector: getSubId is called
,09-07 10:31:53.043  6961  6961 D Mms/MethodReflector: getDefaultSmsSubId is called
,09-07 10:31:53.043  6961  6961 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
,09-07 10:31:53.043  6961  6961 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
,09-07 10:31:53.043  6961  6961 D Mms/MethodReflector: getTelephonyProperty is called
,09-07 10:31:53.043  6961  6961 D Mms/DownloadManager: roaming -> false (slotId = 1)
09-07 10:31:53.043  6961  6961 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
,09-07 10:31:53.043  6961  6961 D Mms/DownloadManager: auto download without roaming -> true
,09-07 10:31:53.043  6961  6961 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
09-07 10:31:53.043  6961  6961 D Mms/DownloadManager: auto download during roaming secondary -> false
09-07 10:31:53.043  6961  6961 D Mms/DownloadManager: mAutoDownload ------> true
,09-07 10:31:53.063  7071  7071 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,09-07 10:31:53.063  7071  7071 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-07 10:31:53.073  6886  7118 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-07 10:31:53.073  7071  7071 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-07 10:31:53.093  6961  7064 D Mms/ArtClassLoader: init [DONE] art
,09-07 10:31:53.103  6961  6961 D ComposerPerformance: 1473237113112 ms / [DONE] Composer constructor
09-07 10:31:53.103  6961  6961 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
09-07 10:31:53.103  6961  6961 I Mms/ReservationManager: ReservationManager()
09-07 10:31:53.103  6961  6961 I Mms/ReservationManager: resetAfterConnected()
09-07 10:31:53.103  6961  7123 D Mms/Conversation: [start]    init() consume time = 70.79151
09-07 10:31:53.103  1465  1482 D TP/MmsSmsProvider: query,matched:7, calling pid = 6961
09-07 10:31:53.113  1465  1482 D TP/MmsSmsProvider: match 7:Elapsed time : 3.435 ms
09-07 10:31:53.123  1465  1484 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
09-07 10:31:53.123  1465  1484 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
09-07 10:31:53.123  6961  6961 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
09-07 10:31:53.123  1465  1484 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
09-07 10:31:53.133  1465  1484 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
09-07 10:31:53.133  6961  6961 D Mms/MmsApp: [end]    onCreate() consume time = 22.556094
09-07 10:31:53.133  6886  6908 W art     : Suspending all threads took: 12.843ms
09-07 10:31:53.133  1465  1484 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
09-07 10:31:53.133  1465  1484 D TP/MmsSmsProvider: need read changed broadcast:false
09-07 10:31:53.133  6961  7123 D Mms/Conversation: [end]    init consume time = 8.330417
09-07 10:31:53.143  6961  7123 D Mms/MessagingNotification: [start]    init() consume time = 4.439375
09-07 10:31:53.143  1924  6833 W art     : Verification of void com.google.android.gms.games.broker.GameAgent.addGameBadgeOps(com.google.android.gms.common.internal.ClientContext, com.google.android.gms.games.server.api.MarketInstance, java.lang.String, java.util.ArrayList, int) took 116.979ms
09-07 10:31:53.143  6961  7123 D Mms/MessagingNotification: [end]    init consume time = 3.474687
09-07 10:31:53.153  1465  1998 D TP/MmsSmsProvider: query,matched:0, calling pid = 6961
09-07 10:31:53.153  1465  1998 V TP/MmsSmsProvider: getSimpleConversations entered.
09-07 10:31:53.153  1013  1040 W ActivityManager: Activity pause timeout for ActivityRecord{35aededd u0 com.test.thalitest/.MainActivity t163}
09-07 10:31:53.153  1465  1998 D TP/MmsSmsProvider: match 0:Elapsed time : 6.824 ms
09-07 10:31:53.163  6961  7125 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 14.534532
09-07 10:31:53.163  6961  6961 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=760]
09-07 10:31:53.163  6961  6961 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
09-07 10:31:53.163  6961  6961 D Mms/MethodReflector: getSubId is called
09-07 10:31:53.163  6961  6961 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
09-07 10:31:53.163  6961  7126 D Mms/Synchronizer: [start]    doSync consume time = 7.783802
09-07 10:31:53.163  6961  6961 D Mms/MethodReflector: getTelephonyProperty is called
09-07 10:31:53.163  6961  6961 D Mms/DownloadManager: roaming -> false (slotId = 0)
09-07 10:31:53.163  6961  6961 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
09-07 10:31:53.163  6961  6961 D Mms/DownloadManager: auto download without roaming -> true
09-07 10:31:53.163  6961  6961 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
09-07 10:31:53.163  6961  6961 D Mms/DownloadManager: mAutoDownload ------> true
09-07 10:31:53.173  1465  2482 D TP/MmsSmsProvider: query,matched:400, calling pid = 6961
09-07 10:31:53.173  1013  1321 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
09-07 10:31:53.173  6961  7125 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 5.248437
09-07 10:31:53.173  1465  1860 D TP/MmsSmsProvider: update, matched:300, calling pid = 6961
09-07 10:31:53.173  6961  6961 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_ADDED
09-07 10:31:53.173  1013  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:31:53.183  1465  1860 V TP/MmsSmsProvider: syncDBData start
09-07 10:31:53.183  1013  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:31:53.183  1465  1860 V TP/MmsSmsProvider: syncDBData sms end
09-07 10:31:53.183  7071  7071 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-07 10:31:53.183  7071  7071 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-07 10:31:53.183  7071  7071 I Adreno-EGL: Build Date: 04/06/15 Mon
09-07 10:31:53.183  7071  7071 I Adreno-EGL: Local Branch: 
09-07 10:31:53.183  7071  7071 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-07 10:31:53.183  7071  7071 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-07 10:31:53.183  7071  7071 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
09-07 10:31:53.183  1013  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:31:53.183  1465  1860 V TP/MmsSmsProvider: syncDBData mms end
09-07 10:31:53.183  1013  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:31:53.183  1465  1860 V TP/MmsSmsProvider: syncDBData end
09-07 10:31:53.193  7130  7130 E Zygote  : MountEmulatedStorage()
09-07 10:31:53.193  7130  7130 I libpersona: KNOX_SDCARD checking this for 10068
09-07 10:31:53.193  7130  7130 E Zygote  : v2
09-07 10:31:53.193  7130  7130 I libpersona: KNOX_SDCARD not a persona
09-07 10:31:53.193  7130  7130 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 10:31:53.193  1013  1321 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7130 uid=10068 gids={50068, 9997} abi=armeabi-v7a
09-07 10:31:53.193  7130  7130 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 10:31:53.203  1013  1026 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
09-07 10:31:53.203  1013  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
09-07 10:31:53.203  7130  7130 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
09-07 10:31:53.203  1013  1026 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:31:53.203  1013  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:31:53.203  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
09-07 10:31:53.213  6961  7126 D Mms/Synchronizer: [end]    doSync consume time = 36.358281
09-07 10:31:53.223   314   314 I art     : Explicit concurrent mark sweep GC freed 8697(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 624us total 25.370ms
09-07 10:31:53.223  1013  1543 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
09-07 10:31:53.223  1013  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:31:53.223  1013  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:31:53.223  1013  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:31:53.223  1013  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:31:53.223  7130  7130 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 10:31:53.223  7130  7130 D ActivityThread: Added TimaKeyStore provider
09-07 10:31:53.243   314   314 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 658us total 16.552ms
09-07 10:31:53.253  6961  7145 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_ADDED
09-07 10:31:53.253  6961  7145 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_ADDED
09-07 10:31:53.253   314   314 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 572us total 17.751ms
09-07 10:31:53.273  7155  7155 E Zygote  : MountEmulatedStorage()
09-07 10:31:53.273  7155  7155 E Zygote  : v2
09-07 10:31:53.273  7155  7155 I libpersona: KNOX_SDCARD checking this for 10042
09-07 10:31:53.273  7155  7155 I libpersona: KNOX_SDCARD not a persona
09-07 10:31:53.273  7155  7155 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 10:31:53.273  7155  7155 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 10:31:53.283  7155  7155 E SELinux : [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
09-07 10:31:53.283  1013  1543 I ActivityManager: Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=7155 uid=10042 gids={50042, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
09-07 10:31:53.293  1013  1496 I ActivityManager: Killing 6424:com.android.defcontainer/u0a3 (adj 15): empty #21
09-07 10:31:53.293  1013  1496 I ActivityManager: Killing 6658:com.qualcomm.timeservice/1000 (adj 15): empty #22
09-07 10:31:53.313  7155  7155 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 10:31:53.313  7155  7155 D ActivityThread: Added TimaKeyStore provider
09-07 10:31:53.333  7155  7155 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-07 10:31:53.333  7155  7155 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-07 10:31:53.333  7155  7155 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-07 10:31:53.333  7071  7071 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-07 10:31:53.363  7071  7071 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
09-07 10:31:53.363  7071  7071 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
09-07 10:31:53.373  7071  7071 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
09-07 10:31:53.373  7071  7071 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
09-07 10:31:53.373  7130  7130 D BadgeProvider: onCreate
09-07 10:31:53.373  7130  7130 D BadgeProvider: DatabaseHelper
09-07 10:31:53.403  6961  7123 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
09-07 10:31:53.403  1465  1484 D TP/SmsProvider: query,matched:26, calling pid = 6961
09-07 10:31:53.403  1465  1484 D TP/SmsProvider: match 26:Elapsed time : 1.209 ms
09-07 10:31:53.413  1465  2482 D TP/MmsSmsProvider: query,matched:6, calling pid = 6961
09-07 10:31:53.413  1465  2482 D TP/MmsSmsProvider: match 6:Elapsed time : 1.579 ms
09-07 10:31:53.423  1013  3832 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.filterinstaller, hostingType: broadcast
09-07 10:31:53.423  1013  3832 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:31:53.423  1013  3832 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:31:53.423  1013  3832 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:31:53.423  1013  3832 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:31:53.433  7175  7175 E Zygote  : MountEmulatedStorage()
09-07 10:31:53.433  7175  7175 I libpersona: KNOX_SDCARD checking this for 1000
09-07 10:31:53.433  7175  7175 E Zygote  : v2
09-07 10:31:53.433  7175  7175 I libpersona: KNOX_SDCARD not a persona
09-07 10:31:53.433  7175  7175 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 10:31:53.443  7175  7175 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 10:31:53.443  7175  7175 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-07 10:31:53.443  1013  3832 I ActivityManager: Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=7175 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-07 10:31:53.443  1013  3832 I ActivityManager: Killing 6680:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
09-07 10:31:53.443  1013  1543 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
09-07 10:31:53.453  1013  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:31:53.453  1013  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:31:53.453  1013  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:31:53.453  1013  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:31:53.463  1924  4393 I Icing   : Indexing D0AE1F45F393341DA3213A207506F1C2E721F1A9 from com.google.android.googlequicksearchbox
09-07 10:31:53.473  7186  7186 E Zygote  : MountEmulatedStorage()
09-07 10:31:53.473  7186  7186 E Zygote  : v2
09-07 10:31:53.473  7186  7186 I libpersona: KNOX_SDCARD checking this for 10023
09-07 10:31:53.473  7186  7186 I libpersona: KNOX_SDCARD not a persona
09-07 10:31:53.473  1013  1543 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=7186 uid=10023 gids={50023, 9997} abi=armeabi-v7a
09-07 10:31:53.493  7175  7175 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 10:31:53.493  7175  7175 D ActivityThread: Added TimaKeyStore provider
09-07 10:31:53.513  7155  7155 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
09-07 10:31:53.523  7186  7186 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 10:31:53.523  1013  1054 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
09-07 10:31:53.523  1013  1054 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
09-07 10:31:53.523  7186  7186 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 10:31:53.523  1013  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:31:53.523  1013  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:31:53.523  7186  7186 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-07 10:31:53.523  1013  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:31:53.523  1013  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:31:53.533  7175  7175 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
09-07 10:31:53.533  7175  7175 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
09-07 10:31:53.543  7207  7207 E Zygote  : MountEmulatedStorage()
09-07 10:31:53.543  7207  7207 I libpersona: KNOX_SDCARD checking this for 10003
09-07 10:31:53.543  7207  7207 E Zygote  : v2
09-07 10:31:53.543  7207  7207 I libpersona: KNOX_SDCARD not a persona
09-07 10:31:53.543  7207  7207 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 10:31:53.543  7207  7207 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 10:31:53.553  1013  1054 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7207 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
09-07 10:31:53.553  1013  1479 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
09-07 10:31:53.553  1013  1479 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
09-07 10:31:53.553  7207  7207 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-07 10:31:53.553  1013  1479 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:31:53.553  7186  7186 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 10:31:53.553  7186  7186 D ActivityThread: Added TimaKeyStore provider
09-07 10:31:53.553  1013  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:31:53.553  1013  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
09-07 10:31:53.563  1013  1479 I ActivityManager: Killing 6693:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
09-07 10:31:53.563  1013  1496 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
09-07 10:31:53.563  1013  1040 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
09-07 10:31:53.563  1013  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:31:53.573  1013  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:31:53.573  1013  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:31:53.573  1013  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:31:53.573  1924  4393 D Icing   : Loaded CLD2 Version V2.0 - 20141016
09-07 10:31:53.583  7175  7175 I FilterInstaller: FilterPackageService : ACTION_CHANGED
09-07 10:31:53.583  1013  1040 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=7225 uid=10130 gids={50130, 9997} abi=armeabi-v7a
09-07 10:31:53.583  7225  7225 E Zygote  : MountEmulatedStorage()
09-07 10:31:53.583  7225  7225 I libpersona: KNOX_SDCARD checking this for 10130
09-07 10:31:53.583  7225  7225 E Zygote  : v2
09-07 10:31:53.583  7225  7225 I libpersona: KNOX_SDCARD not a persona
09-07 10:31:53.583  7225  7225 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 10:31:53.593  7207  7207 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 10:31:53.593  7207  7207 D ActivityThread: Added TimaKeyStore provider
09-07 10:31:53.593  7225  7225 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 10:31:53.593  7225  7225 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
09-07 10:31:53.623  7175  7216 E FilterInstaller: installFilters
09-07 10:31:53.623  7175  7216 E FilterInstaller: There is no requred permission
09-07 10:31:53.633   283   283 E installd: system dir 0 : /system/app/
09-07 10:31:53.633   283   283 E installd: system dir 1 : /system/priv-app/
09-07 10:31:53.633   283   283 E installd: system dir 2 : /vendor/app/
09-07 10:31:53.633   283   283 E installd: system dir 3 : /oem/app/
09-07 10:31:53.633  1013  1133 I ActivityManager: Killing 5068:com.google.android.gms.wearable/u0a11 (adj 15): empty #21
09-07 10:31:53.643  1013  1054 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
09-07 10:31:53.653  7225  7225 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 10:31:53.653  7225  7225 D ActivityThread: Added TimaKeyStore provider
09-07 10:31:53.653  7186  7186 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
09-07 10:31:53.673  6961  7123 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
09-07 10:31:53.673  7225  7225 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-07 10:31:53.673  7225  7225 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
09-07 10:31:53.683  1013  1496 I ActivityManager: Killing 6730:com.samsung.helphub/1000 (adj 15): empty #21
09-07 10:31:53.703  7186  7186 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
09-07 10:31:53.703  7186  7186 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
09-07 10:31:53.703  7186  7186 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
09-07 10:31:53.703  7186  7186 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
09-07 10:31:53.703  7186  7186 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
09-07 10:31:53.703  1013  1504 D ActivityManager: startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
09-07 10:31:53.703  7186  7186 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
09-07 10:31:53.713  7186  7186 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
09-07 10:31:53.713  7186  7186 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
09-07 10:31:53.713  6886  7174 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-07 10:31:53.713  7186  7186 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
09-07 10:31:53.713  6886  7174 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
09-07 10:31:53.713  7186  7186 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
09-07 10:31:53.713  1013  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:31:53.713  1013  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:31:53.713  1013  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:31:53.713  1013  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:31:53.713  7186  7186 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
09-07 10:31:53.713  7186  7186 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
09-07 10:31:53.723  7186  7186 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
09-07 10:31:53.723  7245  7245 E Zygote  : MountEmulatedStorage()
09-07 10:31:53.723  7245  7245 E Zygote  : v2
09-07 10:31:53.723  7245  7245 I libpersona: KNOX_SDCARD checking this for 10131
09-07 10:31:53.723  7245  7245 I libpersona: KNOX_SDCARD not a persona
09-07 10:31:53.723  7245  7245 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 10:31:53.733  1013  1504 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=7245 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
09-07 10:31:53.733  7245  7245 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 10:31:53.733  7245  7245 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-07 10:31:53.733  1013  1481 I ActivityManager: Killing 6745:com.sec.spp.push/u0a32 (adj 15): empty #21
09-07 10:31:53.733  7071  7071 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-07 10:31:53.743  1924  4393 I Icing   : Indexing done D0AE1F45F393341DA3213A207506F1C2E721F1A9
09-07 10:31:53.753  7071  7071 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-07 10:31:53.773  7071  7071 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-07 10:31:53.773  7071  7071 D PhoneWindow: *FMB* installDecor flags : -2139027200
09-07 10:31:53.773  7245  7245 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 10:31:53.773  7245  7245 D ActivityThread: Added TimaKeyStore provider
09-07 10:31:53.783  7071  7071 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
09-07 10:31:53.783  7245  7245 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-07 10:31:53.783  7245  7245 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 10:31:53.783  7245  7245 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-07 10:31:53.793  6886  7174 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
09-07 10:31:53.793  7071  7071 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-07 10:31:53.793  7071  7071 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-07 10:31:53.793  1013  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
09-07 10:31:53.803  1013  1026 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:31:53.803  1013  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 10:31:53.803  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-07 10:31:53.803  6886  6908 W art     : Suspending all threads took: 8.771ms
09-07 10:31:53.843  1013  1321 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
09-07 10:31:53.843  1013  1321 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
09-07 10:31:53.843  1013  1321 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:31:53.843  1013  1321 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:31:53.843  1013  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
09-07 10:31:53.853  2498  2510 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
09-07 10:31:53.863  6886  7174 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
09-07 10:31:53.863  6886  7174 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@29e96cdc: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
09-07 10:31:53.863  6886  7174 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-07 10:31:53.863  1013  3832 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,09-07 10:31:53.863  1013  3832 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
09-07 10:31:53.863  1013  3832 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:31:53.863  1013  3832 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:31:53.863  1013  3832 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,09-07 10:31:53.873  1013  1218 D ActivityManager: startProcessLocked calleePkgName: com.android.providers.calendar, hostingType: broadcast
,09-07 10:31:53.873  1013  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:31:53.873  1013  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:31:53.873  1013  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:31:53.873  1013  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:31:53.893  1013  1218 I ActivityManager: Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=7269 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-07 10:31:53.893  7269  7269 E Zygote  : MountEmulatedStorage(),
09-07 10:31:53.893  7269  7269 I libpersona: KNOX_SDCARD checking this for 10037
,09-07 10:31:53.893  7269  7269 E Zygote  : v2
09-07 10:31:53.893  7269  7269 I libpersona: KNOX_SDCARD not a persona
09-07 10:31:53.893  7269  7269 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-07 10:31:53.893  7269  7269 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-07 10:31:53.903  7269  7269 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-07 10:31:53.903  1013  1133 I ActivityManager: Killing 6711:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
,09-07 10:31:53.923  7269  7269 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 10:31:53.923  7269  7269 D ActivityThread: Added TimaKeyStore provider
,09-07 10:31:53.933  7071  7285 D OpenGLRenderer: Render dirty regions requested: true
,09-07 10:31:53.933  1013  3832 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,09-07 10:31:53.933  7269  7269 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,09-07 10:31:53.943  1013  3832 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-07 10:31:53.943  1013  3832 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-07 10:31:53.943  1013  1013 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-07 10:31:53.943  1013  1013 D PersonaManagerService: getPersonasForUser(): returning null!
,09-07 10:31:53.943  7071  7071 V ActivityThread: updateVisibility : ActivityRecord{827da31 token=android.os.BinderProxy@10a411bb {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-07 10:31:53.943  7071  7151 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,09-07 10:31:53.953  7071  7071 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,09-07 10:31:53.953  7071  7071 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,09-07 10:31:53.963   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,09-07 10:31:53.963  7269  7269 I CalendarProvider2: CalendarProvider2.onCreate() called
,09-07 10:31:53.973  1013  1461 D InputDispatcher: Focus entered window: 7071
,09-07 10:31:53.973  1013  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-07 10:31:53.973  7071  7071 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
09-07 10:31:53.973  7071  7285 I OpenGLRenderer: Initialized EGL, version 1.4
,09-07 10:31:53.973  1013  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-07 10:31:53.983  7071  7285 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,09-07 10:31:53.983  7071  7285 D OpenGLRenderer: Enabling debug mode 0
,09-07 10:31:54.003  1013  1496 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-07 10:31:54.013  1013  7290 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-07 10:31:54.013  1177  1177 D PanelView: There is/are notification(s) 
,09-07 10:31:54.023  1013  1045 I ActivityManager: Displayed Component not be shown by security: +1s372ms (total +1s536ms)
,09-07 10:31:54.023  1013  1045 W ActivityManager: mDVFSHelper.release()
,09-07 10:31:54.023  1013  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{35aededd u0 com.test.thalitest/.MainActivity t163} time:99288
09-07 10:31:54.033  7071  7071 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
09-07 10:31:54.033  7071  7071 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@10a411bb time:99294
09-07 10:31:54.033   257   446 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
09-07 10:31:54.033   257  1095 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,09-07 10:31:54.043  1013  1481 D ActivityManager: startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
,09-07 10:31:54.043  1013  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.CalendarProviderIntentService; callingUser = 0; userId(target) = 0
,09-07 10:31:54.043  1013  1481 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:31:54.043  1013  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 10:31:54.043  1013  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,09-07 10:31:54.053  7269  7294 E SQLiteLog: (284) automatic index on view_events(_id)
,09-07 10:31:54.063  1899  1899 I SamsungIME: getCurrentCandidateView
,09-07 10:31:54.103  7071  7071 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7071
,09-07 10:31:54.153  1013  1504 I ActivityManager: Killing 6800:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
,09-07 10:31:54.183  1899  1899 D SamsungIME: Dismiss ExpandCandiate
,09-07 10:31:54.203  1013  1479 I art     : Explicit concurrent mark sweep GC freed 18091(987KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.384ms total 149.146ms
,09-07 10:31:54.223  7269  7294 D CalendarAlarmManager: sys current time:1473237114062
,09-07 10:31:54.223  7269  7294 D CalendarAlarmManager: reminder amount:0
,09-07 10:31:54.223  1013  1504 I ActivityManager: Killing 6779:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,09-07 10:31:54.233  1013  1543 D ActivityManager: startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
09-07 10:31:54.233  1013  1543 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,09-07 10:31:54.233  1013  1543 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:31:54.233  1013  1543 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 10:31:54.233  1013  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,09-07 10:31:54.273  7071  7071 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-07 10:31:54.353  1899  1899 I SamsungIME: getDebugLevel  : 0x4f4c
,09-07 10:31:54.393  1899  1899 I SamsungIME: getDebugLevel  : 0x4f4c
,09-07 10:31:54.403  1899  1899 I SamsungIME: KeybaordView init() : load resources
,09-07 10:31:54.413  7071  7292 D jxcore_app_log: JniHelper::setJavaVM(0xb7a9c2b0), pthread_self() = -1207784176
,09-07 10:31:54.423  7071  7292 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-07 10:31:54.423  7071  7292 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-07 10:31:54.423  7071  7292 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-07 10:31:54.423  7071  7292 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-07 10:31:54.423  7071  7292 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-07 10:31:54.423  7071  7292 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28c4441c added. We now have 1 listener(s)
,09-07 10:31:54.433  7071  7292 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
,09-07 10:31:54.433  7071  7292 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-07 10:31:54.433  1899  1899 I SamsungIME: getCurrentKeyboard
09-07 10:31:54.433  1899  1899 I SamsungIME: getTextKeyboard
09-07 10:31:54.433  7071  7292 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-07 10:31:54.433  7071  7292 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-07 10:31:54.433  7071  7292 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-07 10:31:54.433  7071  7292 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-07 10:31:54.433  7071  7292 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-07 10:31:54.433  7071  7292 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
09-07 10:31:54.433  7071  7292 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-07 10:31:54.433  7071  7292 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-07 10:31:54.433  7071  7292 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-07 10:31:54.433  7071  7292 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-07 10:31:54.433  7071  7292 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-07 10:31:54.433  7071  7292 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-07 10:31:54.433  7071  7292 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-07 10:31:54.433  7071  7292 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-07 10:31:54.433  7071  7292 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-07 10:31:54.433  7071  7292 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-07 10:31:54.433  7071  7292 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d78dfab added. We now have 1 listener(s)
09-07 10:31:54.433  7071  7292 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 10:31:54.443  7071  7292 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 10:31:54.443  7071  7292 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-07 10:31:54.443  7071  7292 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-07 10:31:54.443  7071  7292 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-07 10:31:54.443  7071  7292 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-07 10:31:54.443  7071  7292 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 10:31:54.453  7071  7292 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
09-07 10:31:54.453  7071  7292 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-07 10:31:54.453  7071  7292 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 10:31:54.453  7071  7292 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:31:54.453  7071  7292 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:31:54.453  7071  7292 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:31:54.453  7071  7292 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:31:54.453  7071  7292 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 10:31:54.453  7071  7292 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 10:31:54.453  7071  7292 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 10:31:54.453  7071  7292 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-07 10:31:54.453  7071  7292 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 10:31:54.453  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:31:54.463  7071  7292 I io.jxcore.node.LifeCycleMonitor: start: OK
09-07 10:31:54.463  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:31:54.473  1899  1899 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
09-07 10:31:54.503  7071  7071 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
09-07 10:31:54.503  6761  6806 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
,09-07 10:31:54.553  6761  6806 I AcmsKeyStoreHelper: Key Store exist
09-07 10:31:54.553  6761  6806 I AcmsKeyStoreHelper: Hence loading the keystore file
,09-07 10:31:54.613  6761  6806 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
09-07 10:31:54.613  6761  6806 I AcmsCertificateMngr: getKeyStoreForApplication success 
09-07 10:31:54.613  6761  6806 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
09-07 10:31:54.613  6761  6806 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-07 10:31:54.613  6761  6806 D AcmsServiceMonitor: Decrementing - Counter value: 1
09-07 10:31:54.613  6761  6806 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
,09-07 10:31:54.613  6761  6806 D AcmsCore: This is NOT a valid MirrorLink app
09-07 10:31:54.613  6761  6806 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
09-07 10:31:54.613  6761  6806 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-07 10:31:54.613  6761  6806 D AcmsServiceMonitor: Decrementing - Counter value: 0
09-07 10:31:54.613  6761  6806 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
,09-07 10:31:54.613  6761  6761 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
,09-07 10:31:54.613  6761  6761 D AcmsService: Enter onDestroy
,09-07 10:31:54.613  6761  6761 I AcmsService: cleanUp(): inside service clean up
09-07 10:31:54.613  6761  6761 D AcmsCore: AcmsCore: inside DeInit
,09-07 10:31:54.613  6761  6761 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
,09-07 10:31:54.613  6761  6761 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
,09-07 10:31:54.613  6761  6761 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
09-07 10:31:54.613  6761  6761 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
09-07 10:31:54.613  6761  6761 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
,09-07 10:31:54.613  6761  6761 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
,09-07 10:31:54.613  6761  6761 D AcmsService: killing acms process
,09-07 10:31:54.623  6761  6761 I Process : Sending signal. PID: 6761 SIG: 9
,09-07 10:31:54.713  1013  1479 I ActivityManager: Process ACMS.Process (pid 6761)(adj 0) has died(30,768)
,09-07 10:31:55.063  7071  7301 W jxcore-log: Initializing JXcore engine
09-07 10:31:55.063  7071  7301 W jxcore-log: JXcore engine is ready
,09-07 10:31:55.123  2028  2028 E audit   : type=1400 msg=audit(1473237115.123:205): avc:  denied  { ioctl } for  pid=7301 comm="Thread-1340" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2071 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-07 10:31:55.123  2028  2028 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
09-07 10:31:55.123  2028  2028 E audit   : type=1300 msg=audit(1473237115.123:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9f2e88f8 items=0 ppid=314 ppcomm=main pid=7301 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1340" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
09-07 10:31:55.123  2028  2028 E audit   : type=1320 msg=audit(1473237115.123:205): 
,09-07 10:31:55.133  6961  6961 I Mms/MmsApp:  start initViewCache mms
,09-07 10:31:55.133  6961  6961 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1919.654635
,09-07 10:31:55.133  6961  6961 D Mms/ComposeMessageFragment: fillCache, easy = false
,09-07 10:31:55.133  7071  7301 W jxcore-log: Starting JXcore engine
,09-07 10:31:55.233  6961  6961 D AbsListView: Get MotionRecognitionManager
,09-07 10:31:55.243  1013  1218 D MotionRecognitionService:  ssp status : false
,09-07 10:31:55.243  7269  7269 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,09-07 10:31:55.243  1013  1040 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:31:55.243  1013  1040 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:31:55.243  6961  6961 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 116.468229
,09-07 10:31:55.243  1013  1040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,09-07 10:31:55.253  1013  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,09-07 10:31:55.253  1013  1026 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:31:55.253  1013  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:31:55.253  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,09-07 10:31:55.253  1013  1504 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:31:55.253  1013  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 10:31:55.253  1013  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,09-07 10:31:55.263  1013  1025 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,09-07 10:31:55.263  1013  1025 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
09-07 10:31:55.263  7071  7301 W jxcore-log: Platform android
09-07 10:31:55.263  7071  7301 W jxcore-log: 
09-07 10:31:55.263  7071  7301 W jxcore-log: Process ARCH arm
09-07 10:31:55.263  7071  7301 W jxcore-log: 
,09-07 10:31:55.263  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:31:55.263  1013  1025 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 10:31:55.263  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,09-07 10:31:55.263  1013  1496 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:31:55.263  1013  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:31:55.263  1013  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,09-07 10:31:55.273  1013  1218 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
09-07 10:31:55.273  1013  1218 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,09-07 10:31:55.273  1013  1218 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:31:55.273  1013  1218 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:31:55.273  1013  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,09-07 10:31:55.343  6961  6961 D Mms/BubbleViewCache: fillCache bubble = 1
,09-07 10:31:55.473  7071  7301 I jxcore-log: JXcore Cordova bridge is ready!
09-07 10:31:55.473  7071  7301 I jxcore-log: 
,09-07 10:31:55.473  7071  7301 W jxcore-log: JXcore engine is started
,09-07 10:31:55.473  7071  7292 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-07 10:31:55.473  7071  7071 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-07 10:31:55.743   292   292 E SMD     : DCD OFF,
,09-07 10:31:57.373  1013  3386 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-07 10:31:57.783  2645  2645 I ConfigService: onDestroy
,09-07 10:31:57.813  1013  3365 D SSRM:n  : SIOP:: AP = 380
,09-07 10:31:58.743   292   292 E SMD     : DCD OFF,
,09-07 10:31:59.983  1013  1093 V AlarmManager: waitForAlarm result :8
,09-07 10:32:00.713  1013  3836 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-07 10:32:00.713  1013  3836 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4267, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-07 10:32:00.713  1013  3836 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-07 10:32:00.713  1013  3836 D BatteryService: stay LED for charging
09-07 10:32:00.713  1013  1013 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-07 10:32:00.723  1013  1013 I MotionRecognitionService: Plugged
,09-07 10:32:00.723  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-07 10:32:00.723  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
09-07 10:32:00.723  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-07 10:32:00.723  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-07 10:32:00.723  1013  1013 I MotionRecognitionService: mGripSensorEnabled= false
,09-07 10:32:00.733  3222  3222 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-07 10:32:00.733  3222  3363 D HeadsetStateMachine: Disconnected process message: 10
,09-07 10:32:00.743  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-07 10:32:00.743  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-07 10:32:00.753  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-07 10:32:01.753   292   292 E SMD     : DCD OFF
,09-07 10:32:02.533  1013  1054 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-07 10:32:02.783  1013  1323 E Watchdog: !@Sync 3
,09-07 10:32:03.653  1013  1054 D PackageManager: [MSG] MCS_UNBIND
,09-07 10:32:03.653  1013  1496 I ActivityManager: Killing 6224:com.samsung.android.sm/1000 (adj 15): empty #21
,09-07 10:32:03.793   326   326 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-07 10:32:03.793   326   326 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-07 10:32:04.753   292   292 E SMD     : DCD OFF
,09-07 10:32:07.443  1013  1093 V AlarmManager: waitForAlarm result :4,
09-07 10:32:07.443  1013  1093 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,09-07 10:32:07.453  1013  1013 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,09-07 10:32:07.453  1013  1013 V AlarmManagerEXT: <AppSync3 Whitelist>
,09-07 10:32:07.453  1013  1013 V AlarmManagerEXT: (AppSync) ### 0 added ###
,09-07 10:32:07.453  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
09-07 10:32:07.453  1177  1177 D KeyguardUpdateMonitor: handleTimeUpdate
,09-07 10:32:07.473  1177  1177 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,09-07 10:32:07.483  1177  1177 D SecKeyguardClockView: HomeTimezone(): 1
,09-07 10:32:07.483  1177  1177 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-07 10:32:07.483  1177  1177 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
09-07 10:32:07.483  1177  1177 I KeyguardEffectViewController: *** don't update sliding image ***
,09-07 10:32:07.513  1177  1177 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-07 10:32:07.513  1177  1177 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-07 10:32:07.523  1177  1177 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-07 10:32:07.533  1177  1177 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-07 10:32:07.683  1013  1047 I PowerManagerService: [PWL] Off : 50s ago
,09-07 10:32:07.703  6941  7050 D Finsky  : [1309] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,09-07 10:32:07.703  6941  6941 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,09-07 10:32:07.753   292   292 E SMD     : DCD OFF
,09-07 10:32:07.853  1013  3365 D SSRM:n  : SIOP:: AP = 360
,09-07 10:32:07.873  7071  7301 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
09-07 10:32:07.873  7071  7301 I jxcore-log: 
,09-07 10:32:07.883  7071  7301 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
09-07 10:32:07.883  7071  7301 I jxcore-log: 
,09-07 10:32:07.883  7071  7301 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 10:32:07.883  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:07.883  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:07.883  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:32:07.883  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:32:07.883  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 10:32:07.883  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 10:32:07.883  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 10:32:07.883  7071  7301 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,09-07 10:32:07.893  7071  7301 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native,
09-07 10:32:07.893  7071  7301 I jxcore-log: 
,09-07 10:32:07.893  7071  7301 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native,
09-07 10:32:07.893  7071  7301 I jxcore-log: 
,09-07 10:32:08.543  7071  7301 D executeNativeTests: Running unit tests
,09-07 10:32:08.633  7071  7301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 10:32:08.633  7071  7301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bc3dbec added. We now have 2 listener(s)
,09-07 10:32:08.633  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-07 10:32:08.633  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 10:32:08.633  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 10:32:08.633  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 10:32:08.633  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eebbb5 added. We now have 2 listener(s)
09-07 10:32:08.633  7071  7301 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 10:32:08.633  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 10:32:08.633  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 10:32:08.643  7071  7301 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 10:32:08.643  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:08.643  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:08.643  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:32:08.643  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:32:08.643  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 10:32:08.643  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 10:32:08.643  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 10:32:08.643  7071  7301 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 10:32:08.643  7071  7301 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 10:32:08.643  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:08.643  7071  7301 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 10:32:08.643  7071  7301 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 10:32:08.643  7071  7301 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-07 10:32:08.643  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:08.643  7071  7301 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-07 10:32:08.653  7071  7301 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-07 10:32:08.653  7071  7301 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 10:32:08.653  7071  7301 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 10:32:08.653  7071  7301 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 10:32:08.653  7071  7301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:32:08.653  7071  7301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 10:32:08.653  7071  7301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 10:32:08.653  7071  7301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:32:08.653  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 10:32:08.653  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 10:32:08.653  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 10:32:08.653  7071  7301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bc3dbec removed from the list
09-07 10:32:08.653  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:08.653  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eebbb5 removed from the list
09-07 10:32:08.653  7071  7301 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:32:08.653  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 10:32:08.653  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:08.653  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 10:32:08.663  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:32:08.663  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:32:08.663  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:08.663  7071  7301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eebbb5 not in the list
,09-07 10:32:08.663  7071  7301 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-07 10:32:08.663  7071  7301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:32:08.663  7071  7301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 10:32:08.663  7071  7301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:32:08.663  7071  7301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:32:08.663  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:08.663  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:08.663  7071  7301 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bc3dbec not in the list
09-07 10:32:08.663  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:08.663  7071  7301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eebbb5 not in the list
09-07 10:32:08.663  7071  7301 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:32:08.663  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:08.663  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:08.663  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:08.663  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 10:32:08.663  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:32:08.663  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:32:08.663  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:08.663  7071  7301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eebbb5 not in the list
,09-07 10:32:08.673  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-07 10:32:08.673  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-07 10:32:08.673  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-07 10:32:08.673  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-07 10:32:08.673  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-07 10:32:08.673  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-07 10:32:08.673  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-07 10:32:08.673  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-07 10:32:08.673  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-07 10:32:08.673  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-07 10:32:08.673  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-07 10:32:08.673  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-07 10:32:08.673  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-07 10:32:08.673  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-07 10:32:08.673  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-07 10:32:08.673  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-07 10:32:08.673  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-07 10:32:08.673  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-07 10:32:08.673  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,09-07 10:32:08.673  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-07 10:32:08.673  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-07 10:32:08.673  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-07 10:32:08.673  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-07 10:32:08.673  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-07 10:32:08.673  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-07 10:32:08.673  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-07 10:32:08.673  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-07 10:32:08.673  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-07 10:32:08.673  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-07 10:32:08.673  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-07 10:32:08.673  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-07 10:32:08.673  7071  7301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:32:08.673  7071  7301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:32:08.673  7071  7301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:32:08.673  7071  7301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:32:08.673  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:08.673  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:08.673  7071  7301 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bc3dbec not in the list
09-07 10:32:08.673  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:08.673  7071  7301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eebbb5 not in the list
09-07 10:32:08.673  7071  7301 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:32:08.673  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:08.673  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:08.673  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:08.673  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:08.673  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:32:08.673  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:32:08.673  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:08.673  7071  7301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eebbb5 not in the list
09-07 10:32:08.673  7071  7301 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 10:32:08.673  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 10:32:08.683  7071  7301 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 10:32:08.683  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:08.683  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:08.683  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:32:08.683  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:32:08.683  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 10:32:08.683  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 10:32:08.683  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 10:32:08.683  7071  7301 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 10:32:08.683  7071  7301 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 10:32:08.683  7071  7301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 10:32:08.683  7071  7301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 10:32:08.683  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 10:32:08.683  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 10:32:08.683  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 10:32:08.683  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:32:08.683  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-07 10:32:08.693  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:32:08.693  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-07 10:32:08.703  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-07 10:32:08.703  7071  7301 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-07 10:32:08.703  7071  7301 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-07 10:32:08.703  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-07 10:32:08.713  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-07 10:32:08.713  7071  7301 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-07 10:32:08.713  3222  3359 D BtGatt.GattService: registerClient() - UUID=dfad7700-dc1d-4d0c-870d-cbe948382763
,09-07 10:32:08.763  3222  3298 D BtGatt.GattService: onClientRegistered() - UUID=dfad7700-dc1d-4d0c-870d-cbe948382763, clientIf=6
,09-07 10:32:08.763  7071  7084 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-07 10:32:08.763  3222  3234 D BtGatt.GattService: start scan with filters,
09-07 10:32:08.763  3222  3362 D BtGatt.ScanManager: handling starting scan
,09-07 10:32:08.763  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-07 10:32:08.763  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-07 10:32:08.763  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-07 10:32:08.763  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-07 10:32:08.773  3222  3362 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2acc5f51
,09-07 10:32:08.783  7071  7301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 10:32:08.783  7071  7301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-07 10:32:08.783  7071  7071 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false,
,09-07 10:32:08.783  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 10:32:08.783  3222  3298 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-07 10:32:08.783  3222  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 10:32:08.783  3222  3362 D BtGatt.ScanManager: allow scan with filters
09-07 10:32:08.783  3222  3362 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-07 10:32:08.783  3222  3362 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,09-07 10:32:08.793  7071  7301 I io.jxcore.node.ConnectionHelper: start: OK
,09-07 10:32:08.793   326   326 I ServiceManager: Waiting for service AtCmdFwd...,
,09-07 10:32:08.793  3222  3298 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-07 10:32:08.793  3222  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 10:32:08.793  3222  3362 D BtGatt.ScanManager: Starting BLE batch scan
09-07 10:32:08.793  3222  3362 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-07 10:32:08.803  7071  7301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 10:32:08.803  7071  7301 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-07 10:32:08.803  7071  7301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything,
09-07 10:32:08.803  7071  7301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-07 10:32:08.803  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 10:32:08.803  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 10:32:08.803  7071  7301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 10:32:08.803  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 10:32:08.803  7071  7301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 10:32:08.803  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-07 10:32:08.803  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 10:32:08.803  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-07 10:32:08.803  3222  3299 D BtGatt.GattService: stopScan() - queue size =1
,09-07 10:32:08.803  3222  3359 D BtGatt.GattService: unregisterClient() - clientIf=6,
,09-07 10:32:08.803  3222  3298 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-07 10:32:08.803  3222  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 10:32:08.813  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 10:32:08.813  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-07 10:32:08.813  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-07 10:32:08.813  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-07 10:32:08.813  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-07 10:32:08.813  7071  7301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 10:32:08.813  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-07 10:32:08.813  7071  7301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-07 10:32:08.813  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-07 10:32:08.813  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 10:32:08.813  7071  7071 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 10:32:08.823  7071  7301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:32:08.823  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:08.823  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 10:32:08.823  7071  7301 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bc3dbec not in the list
09-07 10:32:08.823  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:08.823  7071  7301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eebbb5 not in the list
09-07 10:32:08.823  7071  7301 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:32:08.823  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:08.823  7071  7301 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-07 10:32:08.823  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 10:32:08.823  3222  3298 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-07 10:32:08.823  3222  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 10:32:08.823  7071  7071 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 10:32:08.823  7071  7071 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 10:32:08.823  3222  3362 D BtGatt.ScanManager: filter size is 1
,09-07 10:32:08.833  3222  3362 D BtGatt.ScanManager: delete FilterIndex - 3
,09-07 10:32:08.833  7071  7301 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 10:32:08.833  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:08.833  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:08.833  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:32:08.833  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:32:08.833  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 10:32:08.833  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 10:32:08.833  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 10:32:08.833  7071  7301 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 10:32:08.833  7071  7301 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 10:32:08.833  3222  3298 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-07 10:32:08.833  3222  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 10:32:08.833  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:08.843  3222  3362 D BtGatt.ScanManager: stopping BLe Batch
,09-07 10:32:08.843  7071  7301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 10:32:08.843  7071  7301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 10:32:08.843  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 10:32:08.843  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 10:32:08.843  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 10:32:08.843  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:08.843  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-07 10:32:08.843  3222  3298 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-07 10:32:08.843  3222  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 10:32:08.853  3222  3362 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-07 10:32:08.853  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 10:32:08.853  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 10:32:08.853  3222  3298 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-07 10:32:08.853  3222  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 10:32:08.863  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-07 10:32:08.863  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-07 10:32:08.863  7071  7301 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-07 10:32:08.863  3222  3359 D BtGatt.GattService: registerClient() - UUID=ca59c27d-d5b4-45df-ba2d-848a01fff84e
,09-07 10:32:08.913  3222  3298 D BtGatt.GattService: onClientRegistered() - UUID=ca59c27d-d5b4-45df-ba2d-848a01fff84e, clientIf=6
,09-07 10:32:08.913  7071  7084 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-07 10:32:08.913  3222  3234 D BtGatt.GattService: start scan with filters
,09-07 10:32:08.913  3222  3362 D BtGatt.ScanManager: handling starting scan
,09-07 10:32:08.913  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-07 10:32:08.913  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-07 10:32:08.913  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-07 10:32:08.913  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-07 10:32:08.913  7071  7301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 10:32:08.913  7071  7071 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 10:32:08.913  7071  7301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-07 10:32:08.913  3222  3298 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-07 10:32:08.913  3222  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 10:32:08.913  3222  3362 D BtGatt.ScanManager: allow scan with filters
,09-07 10:32:08.913  3222  3362 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-07 10:32:08.913  3222  3362 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,09-07 10:32:08.913  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 10:32:08.923  3222  3298 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15,
09-07 10:32:08.923  3222  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 10:32:08.923  3222  3362 D BtGatt.ScanManager: Starting BLE batch scan
,09-07 10:32:08.923  3222  3362 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-07 10:32:08.923  3222  3298 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-07 10:32:08.923  3222  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 10:32:08.923  7071  7301 I io.jxcore.node.ConnectionHelper: start: OK
,09-07 10:32:08.933  3222  3298 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-07 10:32:08.933  3222  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 10:32:08.933  7071  7301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 10:32:08.933  7071  7301 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-07 10:32:08.933  7071  7301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-07 10:32:08.933  7071  7301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-07 10:32:08.933  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:08.933  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 10:32:08.933  7071  7301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-07 10:32:08.933  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
09-07 10:32:08.933  7071  7301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 10:32:08.933  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 10:32:08.933  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 10:32:08.933  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-07 10:32:08.933  3222  3299 D BtGatt.GattService: stopScan() - queue size =1
,09-07 10:32:08.933  3222  3362 D BtGatt.ScanManager: filter size is 1
09-07 10:32:08.933  3222  3362 D BtGatt.ScanManager: delete FilterIndex - 4,
,09-07 10:32:08.933  3222  3359 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-07 10:32:08.943  3222  3298 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-07 10:32:08.943  3222  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 10:32:08.943  3222  3362 D BtGatt.ScanManager: stopping BLe Batch
,09-07 10:32:08.943  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 10:32:08.943  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-07 10:32:08.943  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-07 10:32:08.943  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-07 10:32:08.943  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-07 10:32:08.943  7071  7301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 10:32:08.943  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 10:32:08.943  7071  7301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 10:32:08.943  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 10:32:08.943  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 10:32:08.943  3222  3298 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-07 10:32:08.943  3222  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 10:32:08.943  3222  3362 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-07 10:32:08.943  7071  7301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:32:08.943  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:08.943  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 10:32:08.943  7071  7301 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bc3dbec not in the list
09-07 10:32:08.943  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:08.943  7071  7301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eebbb5 not in the list
09-07 10:32:08.943  7071  7301 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:32:08.943  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 10:32:08.943  3222  3298 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-07 10:32:08.943  7071  7071 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 10:32:08.943  7071  7071 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 10:32:08.943  3222  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 10:32:08.943  7071  7071 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 10:32:08.953  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:08.953  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 10:32:08.953  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
09-07 10:32:08.953  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:32:08.953  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:08.953  7071  7301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eebbb5 not in the list
,09-07 10:32:08.953  7071  7301 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-07 10:32:08.953  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 10:32:08.953  7071  7301 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 10:32:08.953  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:08.953  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:08.953  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:32:08.953  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:32:08.953  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 10:32:08.953  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 10:32:08.953  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 10:32:08.963  7071  7301 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 10:32:08.963  7071  7301 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 10:32:08.963  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:08.963  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:08.963  7071  7301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-07 10:32:08.963  7071  7301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 10:32:08.963  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-07 10:32:08.963  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 10:32:08.963  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 10:32:08.973  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-07 10:32:08.973  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 10:32:08.973  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 10:32:08.973  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-07 10:32:08.973  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-07 10:32:08.973  7071  7301 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-07 10:32:08.983  3222  3234 D BtGatt.GattService: registerClient() - UUID=8ff86703-17d2-4f42-ba9f-0eeb6ff05721,
,09-07 10:32:09.023  3222  3298 D BtGatt.GattService: onClientRegistered() - UUID=8ff86703-17d2-4f42-ba9f-0eeb6ff05721, clientIf=6,
09-07 10:32:09.023  7071  7085 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-07 10:32:09.023  3222  3238 D BtGatt.GattService: start scan with filters,
09-07 10:32:09.023  3222  3362 D BtGatt.ScanManager: handling starting scan
,09-07 10:32:09.023  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
09-07 10:32:09.023  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-07 10:32:09.023  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-07 10:32:09.023  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-07 10:32:09.033  3222  3298 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-07 10:32:09.033  3222  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 10:32:09.033  3222  3362 D BtGatt.ScanManager: allow scan with filters
09-07 10:32:09.033  3222  3362 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-07 10:32:09.033  3222  3362 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
09-07 10:32:09.033  7071  7301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 10:32:09.033  7071  7071 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-07 10:32:09.033  7071  7301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-07 10:32:09.033  3222  3298 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-07 10:32:09.033  3222  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 10:32:09.033  3222  3362 D BtGatt.ScanManager: Starting BLE batch scan
09-07 10:32:09.033  3222  3362 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-07 10:32:09.043  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 10:32:09.043  3222  3298 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-07 10:32:09.043  3222  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 10:32:09.043  7071  7301 I io.jxcore.node.ConnectionHelper: start: OK
,09-07 10:32:09.053  7071  7301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 10:32:09.053  7071  7301 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-07 10:32:09.053  7071  7301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-07 10:32:09.053  3222  3298 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-07 10:32:09.053  3222  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 10:32:09.053  7071  7301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-07 10:32:09.053  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 10:32:09.053  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 10:32:09.053  7071  7301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-07 10:32:09.053  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 10:32:09.053  7071  7301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 10:32:09.053  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 10:32:09.053  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 10:32:09.053  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-07 10:32:09.063  3222  3234 D BtGatt.GattService: stopScan() - queue size =1
,09-07 10:32:09.063  3222  3362 D BtGatt.ScanManager: filter size is 1
,09-07 10:32:09.063  3222  3362 D BtGatt.ScanManager: delete FilterIndex - 5
,09-07 10:32:09.063  3222  3238 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-07 10:32:09.063  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-07 10:32:09.063  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-07 10:32:09.063  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-07 10:32:09.063  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-07 10:32:09.063  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-07 10:32:09.073  3222  3298 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-07 10:32:09.073  3222  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 10:32:09.073  3222  3362 D BtGatt.ScanManager: stopping BLe Batch
,09-07 10:32:09.073  7071  7301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 10:32:09.073  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 10:32:09.073  7071  7301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 10:32:09.073  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-07 10:32:09.073  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 10:32:09.073  7071  7071 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 10:32:09.073  7071  7071 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 10:32:09.073  7071  7071 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 10:32:09.073  7071  7301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:32:09.073  7071  7301 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-07 10:32:09.073  7071  7301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:32:09.073  7071  7301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:32:09.073  7071  7301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:32:09.073  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:09.073  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 10:32:09.073  7071  7301 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bc3dbec not in the list
09-07 10:32:09.073  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:09.073  7071  7301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eebbb5 not in the list
09-07 10:32:09.073  7071  7301 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:32:09.073  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:09.073  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:09.073  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 10:32:09.073  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 10:32:09.073  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:32:09.073  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 10:32:09.073  7071  7301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eebbb5 not in the list
,09-07 10:32:09.083  7071  7301 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-07 10:32:09.083  7071  7301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 10:32:09.083  7071  7301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:32:09.083  7071  7301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 10:32:09.083  3222  3298 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-07 10:32:09.083  3222  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 10:32:09.083  7071  7301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:32:09.083  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:09.083  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:09.083  7071  7301 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bc3dbec not in the list
09-07 10:32:09.083  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:09.083  7071  7301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eebbb5 not in the list
09-07 10:32:09.083  7071  7301 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:32:09.083  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:09.083  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:09.083  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:09.083  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:09.083  3222  3362 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-07 10:32:09.083  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 10:32:09.083  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:32:09.083  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 10:32:09.083  7071  7301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eebbb5 not in the list
,09-07 10:32:09.083  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-07 10:32:09.093  7071  7301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:32:09.093  7071  7301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:32:09.093  7071  7301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:32:09.093  7071  7301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
09-07 10:32:09.093  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:09.093  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:09.093  7071  7301 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bc3dbec not in the list
09-07 10:32:09.093  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:09.093  7071  7301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eebbb5 not in the list
09-07 10:32:09.093  7071  7301 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 10:32:09.093  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:09.093  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:09.093  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:09.093  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:09.093  3222  3298 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-07 10:32:09.093  3222  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,09-07 10:32:09.093  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 10:32:09.093  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:32:09.093  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 10:32:09.093  7071  7301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eebbb5 not in the list
,09-07 10:32:09.093  7071  7301 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-07 10:32:09.093  7071  7301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:32:09.093  7071  7301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:32:09.093  7071  7301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:32:09.093  7071  7301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:32:09.093  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 10:32:09.093  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:09.093  7071  7301 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bc3dbec not in the list
,09-07 10:32:09.093  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:09.093  7071  7301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eebbb5 not in the list
09-07 10:32:09.093  7071  7301 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:32:09.093  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 10:32:09.103  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:09.103  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:09.103  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 10:32:09.103  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 10:32:09.103  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:32:09.103  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:09.103  7071  7301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eebbb5 not in the list
,09-07 10:32:09.103  7071  7301 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,09-07 10:32:09.103  7071  7301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 10:32:09.103  7071  7301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:32:09.103  7071  7301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 10:32:09.103  7071  7301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:32:09.103  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 10:32:09.103  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:09.103  7071  7301 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bc3dbec not in the list
09-07 10:32:09.103  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 10:32:09.103  7071  7301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eebbb5 not in the list
,09-07 10:32:09.103  7071  7301 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:32:09.103  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:09.103  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:09.103  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:09.103  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 10:32:09.103  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:32:09.103  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:32:09.103  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:09.103  7071  7301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eebbb5 not in the list
,09-07 10:32:09.103  7071  7301 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-07 10:32:09.103  7071  7301 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 10:32:09.103  7071  7301 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 10:32:09.103  7071  7301 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 10:32:09.103  7071  7301 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 10:32:09.103  7071  7301 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 10:32:09.103  7071  7301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:32:09.103  7071  7301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:32:09.103  7071  7301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:32:09.103  7071  7301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:32:09.103  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:09.103  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:09.103  7071  7301 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bc3dbec not in the list
09-07 10:32:09.103  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:09.103  7071  7301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eebbb5 not in the list
09-07 10:32:09.103  7071  7301 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:32:09.103  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:09.103  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:09.103  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:09.103  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 10:32:09.113  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:32:09.113  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:32:09.113  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-07 10:32:09.113  7071  7301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eebbb5 not in the list
,09-07 10:32:09.113  7071  7301 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55,
09-07 10:32:09.113  7071  7301 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55,
09-07 10:32:09.113  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55],
,09-07 10:32:09.113  7071  7301 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 10:32:09.113  7071  7301 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-07 10:32:09.113  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010],
09-07 10:32:09.113  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-07 10:32:09.113  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-07 10:32:09.113  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-07 10:32:09.113  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-07 10:32:09.113  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-07 10:32:09.113  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-07 10:32:09.113  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-07 10:32:09.113  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-07 10:32:09.113  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,09-07 10:32:09.113  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-07 10:32:09.113  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-07 10:32:09.113  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-07 10:32:09.113  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-07 10:32:09.113  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-07 10:32:09.113  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-07 10:32:09.113  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-07 10:32:09.113  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-07 10:32:09.113  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-07 10:32:09.113  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-07 10:32:09.113  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-07 10:32:09.113  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-07 10:32:09.113  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,09-07 10:32:09.113  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310],
09-07 10:32:09.113  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-07 10:32:09.113  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,09-07 10:32:09.113  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-07 10:32:09.113  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-07 10:32:09.113  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-07 10:32:09.113  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-07 10:32:09.113  7071  7301 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-07 10:32:09.113  7071  7301 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 10:32:09.113  7071  7301 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-07 10:32:09.113  7071  7301 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 10:32:09.113  7071  7301 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 10:32:09.113  7071  7301 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-07 10:32:09.113  7071  7301 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 10:32:09.113  7071  7301 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 10:32:09.113  7071  7301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-07 10:32:09.113  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-07 10:32:09.123  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-07 10:32:09.123  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-07 10:32:09.123  7071  7301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-07 10:32:09.123  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-07 10:32:09.123  7071  7301 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-07 10:32:09.123  7071  7301 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 10:32:09.123  7071  7301 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-07 10:32:09.123  7071  7301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:32:09.123  7071  7301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:32:09.123  7071  7301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:32:09.123  7071  7315 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1404)
09-07 10:32:09.123  7071  7301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:32:09.123  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:09.123  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release:, 1 listener(s) left
09-07 10:32:09.123  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-07 10:32:09.123  7071  7301 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bc3dbec not in the list
09-07 10:32:09.123  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:09.123  7071  7301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eebbb5 not in the list
09-07 10:32:09.123  7071  7301 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:32:09.123  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:09.123  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:09.123  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:09.123  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:09.123  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 10:32:09.123  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:32:09.123  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:09.123  7071  7301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eebbb5 not in the list
09-07 10:32:09.123  7071  7316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1404
09-07 10:32:09.123  7071  7301 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-07 10:32:09.123  7071  7301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:32:09.123  7071  7301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:32:09.123  7071  7301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:32:09.123  7071  7301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:32:09.123  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:09.123  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:09.123  7071  7301 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bc3dbec not in the list
09-07 10:32:09.123  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:09.123  7071  7301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eebbb5 not in the list
09-07 10:32:09.123  7071  7301 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:32:09.123  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:09.123  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:09.123  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:09.123  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:09.123  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:32:09.123  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:32:09.123  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:09.123  7071  7301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eebbb5 not in the list
,09-07 10:32:09.133  7071  7301 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,09-07 10:32:09.133  7071  7301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 10:32:09.133  7071  7315 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
09-07 10:32:09.133  7071  7301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:32:09.133  7071  7301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:32:09.133  7071  7301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:32:09.133  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:09.133  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:09.133  7071  7301 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bc3dbec not in the list,
09-07 10:32:09.133  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:09.133  7071  7301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eebbb5 not in the list
09-07 10:32:09.133  7071  7301 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:32:09.133  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:09.133  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:09.133  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:09.133  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 10:32:09.133  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:32:09.133  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:32:09.133  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:09.133  7071  7301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eebbb5 not in the list
,09-07 10:32:09.133  7071  7315 D BluetoothSocket: connect(): myUserId = 0
09-07 10:32:09.133  7071  7315 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 10:32:09.133  7071  7301 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-07 10:32:09.133  7071  7301 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-07 10:32:09.133  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 10:32:09.133  7071  7301 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-07 10:32:09.133  7071  7301 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-07 10:32:09.133  7071  7301 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-07 10:32:09.133  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-07 10:32:09.133  7071  7301 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-07 10:32:09.133  7071  7301 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-07 10:32:09.133  7071  7301 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-07 10:32:09.133  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 10:32:09.133  7071  7301 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-07 10:32:09.133  7071  7301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:32:09.133  7071  7301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:32:09.133  7071  7301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:32:09.133  7071  7301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 10:32:09.133  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:09.133  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:09.133  7071  7301 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bc3dbec not in the list
09-07 10:32:09.133  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:09.133  7071  7301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eebbb5 not in the list
09-07 10:32:09.133  7071  7301 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:32:09.133  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:09.133  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:09.133  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 10:32:09.133  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:09.133  3222  3234 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 10:32:09.133  7071  7315 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
,09-07 10:32:09.133  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:32:09.133  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:32:09.133  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:09.133  7071  7301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eebbb5 not in the list
,09-07 10:32:09.143  7071  7301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 10:32:09.143  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:09.143  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:09.143  7071  7301 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bc3dbec not in the list
09-07 10:32:09.143  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:09.143  7071  7301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eebbb5 not in the list
09-07 10:32:09.143  7071  7301 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:32:09.143  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:09.143  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 10:32:09.143  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:09.143  7071  7301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eebbb5 not in the list
09-07 10:32:09.143  7071  7301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:32:09.143  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:09.143  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:09.143  7071  7301 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bc3dbec not in the list
,09-07 10:32:09.143  7071  7301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:32:09.143  7071  7301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:32:09.143  7071  7301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:32:09.143  7071  7301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:32:09.143  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 10:32:09.143  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:09.143  7071  7301 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bc3dbec not in the list
09-07 10:32:09.143  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:09.143  7071  7301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eebbb5 not in the list
09-07 10:32:09.143  7071  7301 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:32:09.143  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:09.143  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:09.143  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 10:32:09.143  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:09.143  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:32:09.143  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:32:09.143  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:09.143  7071  7301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eebbb5 not in the list
,09-07 10:32:09.143  7071  7301 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-07 10:32:09.143  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 10:32:09.143  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-07 10:32:09.143  7071  7301 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-07 10:32:09.143  7071  7301 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-07 10:32:09.143  7071  7301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-07 10:32:09.143  7071  7301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 10:32:09.143  7071  7071 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-07 10:32:09.153  7071  7301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:32:09.153  7071  7301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-07 10:32:09.153  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-07 10:32:09.153  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-07 10:32:09.153  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:09.153  7071  7301 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-07 10:32:09.153  7071  7301 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bc3dbec not in the list
09-07 10:32:09.153  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:09.153  7071  7071 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-07 10:32:09.153  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 10:32:09.153  7071  7301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 10:32:09.153  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 10:32:09.153  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:09.153  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 10:32:09.153  7071  7317 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-07 10:32:09.153  7071  7317 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-07 10:32:09.153  7071  7301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 10:32:09.153  7071  7071 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 10:32:09.153  7071  7071 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 10:32:09.153  7071  7071 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-07 10:32:09.153  7071  7071 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 10:32:09.153  7071  7301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eebbb5 not in the list
09-07 10:32:09.153  7071  7301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:32:09.153  7071  7301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:32:09.153  7071  7301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:32:09.153  7071  7301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:32:09.153  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 10:32:09.153  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:09.153  7071  7301 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bc3dbec not in the list
09-07 10:32:09.153  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:09.153  7071  7301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eebbb5 not in the list
09-07 10:32:09.153  7071  7301 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 10:32:09.153  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:09.153  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:09.153  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:09.153  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 10:32:09.153  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:32:09.153  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:32:09.153  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:09.153  7071  7301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eebbb5 not in the list
09-07 10:32:09.153  7071  7301 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-07 10:32:09.153  7071  7301 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-07 10:32:09.153  7071  7301 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 10:32:09.153  7071  7301 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 10:32:09.153  7071  7301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:32:09.153  7071  7301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
09-07 10:32:09.153  7071  7301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:32:09.153  7071  7301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:32:09.153  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:09.153  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:09.153  7071  7301 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bc3dbec not in the list
09-07 10:32:09.153  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-07 10:32:09.153  7071  7301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eebbb5 not in the list
09-07 10:32:09.153  7071  7301 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:32:09.153  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:09.153  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 10:32:09.153  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:09.153  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:09.153  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:32:09.153  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:32:09.153  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 10:32:09.153  7071  7301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eebbb5 not in the list
,09-07 10:32:09.163  7071  7301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:32:09.163  7071  7301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:32:09.163  7071  7301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:32:09.163  7071  7301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:32:09.163  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:09.163  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:09.163  7071  7301 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bc3dbec not in the list
09-07 10:32:09.163  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:09.163  7071  7301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eebbb5 not in the list
09-07 10:32:09.163  7071  7301 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:32:09.163  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:09.163  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:09.163  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:09.163  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:09.163  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:32:09.163  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:32:09.163  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:09.163  7071  7301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eebbb5 not in the list
,09-07 10:32:09.163  7071  7301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 10:32:09.163  7071  7301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:32:09.163  7071  7301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:32:09.163  7071  7301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:32:09.163  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:09.163  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:09.163  7071  7301 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bc3dbec not in the list
09-07 10:32:09.163  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:09.163  7071  7301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eebbb5 not in the list
09-07 10:32:09.163  7071  7301 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:32:09.163  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:09.163  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:09.163  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:09.163  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 10:32:09.163  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:32:09.163  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:32:09.163  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:09.163  7071  7301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eebbb5 not in the list
,09-07 10:32:09.163  7071  7301 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-07 10:32:09.163  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-07 10:32:09.163  7071  7301 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-07 10:32:09.163  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 10:32:09.163  7071  7301 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,09-07 10:32:09.163  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 10:32:09.163  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-07 10:32:09.163  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-07 10:32:09.163  7071  7301 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-07 10:32:09.163  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-07 10:32:09.163  7071  7301 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-07 10:32:09.163  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-07 10:32:09.163  7071  7301 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-07 10:32:09.163  7071  7301 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-07 10:32:09.163  7071  7301 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-07 10:32:09.163  7071  7301 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-07 10:32:09.163  7071  7301 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-07 10:32:09.163  7071  7301 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-07 10:32:09.163  7071  7301 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-07 10:32:09.163  7071  7301 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-07 10:32:09.173  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 10:32:09.173  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3f7add8f added. We now have 2 listener(s)
09-07 10:32:09.173  7071  7301 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 10:32:09.173  7071  7301 D BluetoothAdapter: enable()
,09-07 10:32:09.173  7071  7301 D BluetoothAdapter: enable(): BT is already enabled..!
,09-07 10:32:09.173  1013  1321 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-07 10:32:09.173  1013  1321 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-07 10:32:09.173  1013  1321 D SecContentProvider2: mCursor = null
,09-07 10:32:09.173  1013  1321 D WifiService: setWifiEnabled: true pid=7071, uid=10170
09-07 10:32:09.173  1013  1321 W ActivityManager: Permission Denial: getCurrentUser() from pid=7071, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-07 10:32:09.183  1013  1321 W WifiService: Failed getting userId using ActivityManagerNative
09-07 10:32:09.183  1013  1321 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7071, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-07 10:32:09.183  1013  1321 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-07 10:32:09.183  1013  1321 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-07 10:32:09.183  1013  1321 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-07 10:32:09.183  1013  1321 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-07 10:32:09.183  1013  1321 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-07 10:32:09.183  1013  1321 D SettingsProvider: name = wifi_on
,09-07 10:32:09.183  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 10:32:09.183  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@226c181c added. We now have 3 listener(s)
09-07 10:32:09.183  7071  7301 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 10:32:09.183  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 10:32:09.183  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1906fc25 added. We now have 4 listener(s)
09-07 10:32:09.183  7071  7301 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 10:32:09.183  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 10:32:09.183  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@326ad1fa added. We now have 5 listener(s)
09-07 10:32:09.183  7071  7301 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 10:32:09.193  1013  1133 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-07 10:32:09.193  1013  1133 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-07 10:32:09.193  1013  1133 D SecContentProvider2: mCursor = null
,09-07 10:32:09.193  1013  1133 D WifiService: setWifiEnabled: false pid=7071, uid=10170
,09-07 10:32:09.193  1013  1133 D SettingsProvider: name = wifi_on
,09-07 10:32:09.193  1013  1124 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-07 10:32:09.193  7071  7301 D BluetoothAdapter: disable()
,09-07 10:32:09.203  1365  1365 I wpa_supplicant: reset timer : RESET_TIMER 0
09-07 10:32:09.203  1365  1365 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,09-07 10:32:09.203  1365  1365 I wpa_supplicant: P2P: Current p2p state = IDLE
09-07 10:32:09.203  1013  1481 D SettingsProvider: name = bluetooth_on
09-07 10:32:09.203  1365  1365 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-07 10:32:09.203  1013  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 10:32:09.223  3222  3295 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,09-07 10:32:09.223  3222  3295 D BluetoothAdapterProperties: Setting state to 13
,09-07 10:32:09.223  3222  3295 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-07 10:32:09.223  3222  3295 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-07 10:32:09.223  3222  3295 D BluetoothAdapterService: updateAdapterState state is 13
,09-07 10:32:09.223  1013  1504 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 10:32:09.223  1013  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-07 10:32:09.233  1013  1504 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:09.233  1013  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:09.233  1013  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:09.233  1365  1365 I wpa_supplicant: nl80211: Received scan results (10 BSSes),
09-07 10:32:09.233  3222  3295 D BluetoothAdapterService: Autoconnection is available 
09-07 10:32:09.233  1013  1123 D WifiP2pService: InactiveState{ what=147461 }
09-07 10:32:09.233  3222  3295 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-07 10:32:09.233  1013  1123 D WifiP2pService: P2pEnabledState{ what=147461 }
09-07 10:32:09.233  3222  3295 D BluetoothAdapterService: terminating service from this receiver
09-07 10:32:09.233  1013  1123 D WifiP2pService: DefaultState{ what=147461 }
,09-07 10:32:09.233  3222  3222 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
09-07 10:32:09.233  1013  1218 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
09-07 10:32:09.233  1013  1218 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:09.233  1013  1218 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:09.233  1013  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:09.233  3222  3222 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2d1a4511, channel: 19, state: LISTENING
09-07 10:32:09.233  3222  3222 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2d1a4511, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1d90219e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3160c676mSocket: android.net.LocalSocket@37f0a477 impl:android.net.LocalSocketImpl@e9c78e4 fd:FileDescriptor[82]
09-07 10:32:09.233  3222  3222 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@37f0a477 impl:android.net.LocalSocketImpl@e9c78e4 fd:FileDescriptor[82]
,09-07 10:32:09.233  3222  3295 D BluetoothAdapterProperties: onBluetoothDisable()
09-07 10:32:09.233  3222  3295 D BluetoothAdapterProperties: mDiscovering is false
,09-07 10:32:09.233  1013  1124 E WifiNative-wlan0: do suspend true
09-07 10:32:09.233  1013  1461 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-07 10:32:09.243  3222  3295 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-07 10:32:09.243  1013  1013 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-07 10:32:09.243  1013  1013 I InputMethodManagerService: [BT Setting State] State =13
,09-07 10:32:09.243  4773  4773 D BluetoothPbap: Proxy object disconnected
,09-07 10:32:09.243  4773  4773 D PbapServerProfile: Bluetooth service disconnected
,09-07 10:32:09.243  3222  3298 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-07 10:32:09.243  3222  3298 D BluetoothAdapterProperties: Scan Mode:20,
,09-07 10:32:09.253  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,09-07 10:32:09.253  1177  1775 D BluetoothTile:  handleUpdatestate:false name:null
,09-07 10:32:09.253  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-07 10:32:09.253  1177  1775 D BluetoothTile:  handleUpdatestate:false name:null
,09-07 10:32:09.253  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-07 10:32:09.253  1177  1177 D BluetoothTile:  getBluetoothState : 13
,09-07 10:32:09.253  1177  1775 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-07 10:32:09.263  1013  1543 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-07 10:32:09.263  1013  1479 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-07 10:32:09.263  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-07 10:32:09.263  1899  1899 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-07 10:32:09.263  4773  4773 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-07 10:32:09.273  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 10:32:09.273  7071  7071 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 10:32:09.273  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 10:32:09.273  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:09.273  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:09.273  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:32:09.273  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 10:32:09.273  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 10:32:09.273  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 10:32:09.273  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 10:32:09.273  3222  3295 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-07 10:32:09.273  3222  3295 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,09-07 10:32:09.273  3222  3295 E bt-btif : cmd socket is not created
,09-07 10:32:09.273  7071  7315 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@18309a08, channel: -1, state: INIT
09-07 10:32:09.273  7071  7315 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@18309a08, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@5d035a1, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@58413c6mSocket: android.net.LocalSocket@2866ef87 impl:android.net.LocalSocketImpl@1a394eb4 fd:FileDescriptor[106]
09-07 10:32:09.273  7071  7315 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2866ef87 impl:android.net.LocalSocketImpl@1a394eb4 fd:FileDescriptor[106]
09-07 10:32:09.273  7071  7315 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1404)
,09-07 10:32:09.273  3222  5283 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-07 10:32:09.273  3222  3295 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-07 10:32:09.273  3222  3300 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,09-07 10:32:09.283  7071  7071 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 10:32:09.283  7071  7071 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 10:32:09.293  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:09.293  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 10:32:09.293  7071  7301 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 10:32:09.293  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:09.293  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:09.293  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:32:09.293  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 10:32:09.293  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 10:32:09.293  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 10:32:09.293  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 10:32:09.293  3222  3300 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 10:32:09.293  3222  3300 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 10:32:09.293  3222  3300 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-07 10:32:09.293  3222  3300 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 10:32:09.293  3222  3300 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 10:32:09.293  3222  3300 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-07 10:32:09.293  3222  3300 W bt-sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
09-07 10:32:09.293  3222  3300 E bt-btif : DISCOVERY_COMP_EVT slot id:4, failed to find channle,                                       status:1, scn:0
09-07 10:32:09.293  3222  3300 W bt-btif : invalid rfc slot id: 4
,09-07 10:32:09.293  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 10:32:09.293  7071  7301 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 10:32:09.293  3222  3222 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3b0ad402, channel: 5, state: LISTENING
,09-07 10:32:09.293  3222  3222 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3b0ad402, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@245ef3d9, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2bc11113mSocket: android.net.LocalSocket@3c1a3f50 impl:android.net.LocalSocketImpl@1e578549 fd:FileDescriptor[80]
09-07 10:32:09.293  7071  7301 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 10:32:09.293  3222  3222 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3c1a3f50 impl:android.net.LocalSocketImpl@1e578549 fd:FileDescriptor[80]
,09-07 10:32:09.293  4773  4773 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 10:32:09.293  3222  3222 I BtOppRfcommListener: stopping Accept Thread
09-07 10:32:09.293  3222  3222 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@35562e4e, channel: 12, state: LISTENING
09-07 10:32:09.293  3222  3222 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@35562e4e, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1c848138, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1621ab6fmSocket: android.net.LocalSocket@356c007c impl:android.net.LocalSocketImpl@30a2d05 fd:FileDescriptor[86]
09-07 10:32:09.293  3222  3222 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@356c007c impl:android.net.LocalSocketImpl@30a2d05 fd:FileDescriptor[86]
,09-07 10:32:09.293  3222  5283 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-07 10:32:09.293  1013  1496 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-07 10:32:09.293  1013  1496 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-07 10:32:09.303  1013  1496 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:09.303  1013  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:09.303  1013  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-07 10:32:09.303  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:09.303  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:09.303  2645  2645 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 10:32:09.313  3222  3222 V BluetoothOppManager: cleanUp...
,09-07 10:32:09.313  4773  4773 D DockEventReceiver: finishStartingService: stopping service
,09-07 10:32:09.313  1013  1123 D WifiP2pService: InactiveState{ what=143375 }
,09-07 10:32:09.313  1013  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
09-07 10:32:09.313  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:09.313  4773  4773 D BluetoothNotiBroadcastReceiver: onReceive
,09-07 10:32:09.313   277  1012 D CommandListener: Clearing all IP addresses on wlan0
,09-07 10:32:09.323  2645  2684 V NativeCrypto: Read error: ssl=0xb7fabe20: I/O error during system call, Connection timed out
,09-07 10:32:09.323  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 10:32:09.323  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-07 10:32:09.323  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:09.323  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:09.323  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:09.323  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 10:32:09.323  1013  1126 E ConnectivityService: updateNetworkInfo()
,09-07 10:32:09.323  1013  1126 E ConnectivityService: updateNetworkInfo()
09-07 10:32:09.323  1013  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 10:32:09.323  2645  2684 V NativeCrypto: SSL shutdown failed: ssl=0xb7fabe20: I/O error during system call, Broken pipe
09-07 10:32:09.323  1013  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,09-07 10:32:09.333  1013  1496 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,09-07 10:32:09.333  1013  1737 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,09-07 10:32:09.333  1013  1737 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:32:09.333  1013  1737 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-07 10:32:09.333  1013  1737 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:32:09.333  1013  1737 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
09-07 10:32:09.333  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:32:09.333  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-07 10:32:09.333  1013  1737 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-07 10:32:09.333  1013  1737 I qtaguid : Tagging socket 357 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1013, getuid(): 1000
,09-07 10:32:09.343  1013  1013 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-07 10:32:09.343  1013  1737 I qtaguid : Untagging socket 357
09-07 10:32:09.343  1013  1737 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-07 10:32:09.343  1013  1461 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-07 10:32:09.353  1013  1461 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,09-07 10:32:09.353  1013  1461 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:09.353  1013  1461 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:09.353  1013  1461 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:09.353  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-07 10:32:09.353  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 10:32:09.353  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-07 10:32:09.353  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 10:32:09.363  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:09.363  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:09.363  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 10:32:09.363  7326  7326 E Zygote  : MountEmulatedStorage(),
09-07 10:32:09.363  7326  7326 I libpersona: KNOX_SDCARD checking this for 10055
09-07 10:32:09.363  7326  7326 E Zygote  : v2,
09-07 10:32:09.363  7326  7326 I libpersona: KNOX_SDCARD not a persona
,09-07 10:32:09.373  7326  7326 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 10:32:09.373  1013  1461 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7326 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
09-07 10:32:09.373  7326  7326 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 10:32:09.373  1013  1123 D WifiP2pService: InactiveState{ what=131204 }
09-07 10:32:09.373  1013  1013 D WifiScanningService: SCAN_AVAILABLE : 1
09-07 10:32:09.373  1013  1123 D WifiP2pService: P2pEnabledState{ what=131204 }
09-07 10:32:09.373  1013  1149 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:32:09.373  7326  7326 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-07 10:32:09.373  1013  1013 D RttService: SCAN_AVAILABLE : 1
09-07 10:32:09.373  1013  1150 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-07 10:32:09.383  1013  1124 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-07 10:32:09.383  1013  1123 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,09-07 10:32:09.383  1013  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 10:32:09.383  1013  1045 D WifiDisplayAdapter: onP2pDisconnected
,09-07 10:32:09.393  1013  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-07 10:32:09.393  1013  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-07 10:32:09.393  1013  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-07 10:32:09.393   277  1008 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-07 10:32:09.393   277  1008 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,09-07 10:32:09.393  1013  1126 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
09-07 10:32:09.393  1013  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 10:32:09.393  1013  1126 V NetworkStats: updateIfacesLocked()
09-07 10:32:09.393  1013  1013 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-07 10:32:09.393  1013  1126 V NetworkStats: performPollLocked(flags=0x1)
09-07 10:32:09.393  1013  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
09-07 10:32:09.393  1013  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-07 10:32:09.393  1013  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-07 10:32:09.393  1013  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,09-07 10:32:09.393  1013  1737 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname,
09-07 10:32:09.393  1013  1045 D WifiDisplayController: disconnect
09-07 10:32:09.393  1013  1737 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
09-07 10:32:09.393  1013  1045 D WifiDisplayController: updateConnection
09-07 10:32:09.393  1013  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-07 10:32:09.393  1013  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-07 10:32:09.393  1013  1123 D WifiP2pService: P2pDisablingState
09-07 10:32:09.393  1013  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-07 10:32:09.393  1013  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 10:32:09.393  1013  1045 D WifiDisplayAdapter: onP2pDisconnected
09-07 10:32:09.393  1013  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer,
09-07 10:32:09.393  1013  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
09-07 10:32:09.393  1013  1126 V NetworkStats: performPollLocked() took 6ms
09-07 10:32:09.393  1013  1123 D WifiP2pService: P2pDisablingState{ what=147458 }
09-07 10:32:09.393  1013  1123 D WifiP2pService: p2p socket connection lost
,09-07 10:32:09.403  1013  1123 D WifiP2pService: P2pDisabledState
09-07 10:32:09.403  1013  1124 E WifiNative-wlan0: do suspend true
09-07 10:32:09.403  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-07 10:32:09.403  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit,
09-07 10:32:09.403  1013  1025 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-07 10:32:09.403  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 10:32:09.403  1013  1126 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
09-07 10:32:09.403  1013  1737 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:32:09.403  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
09-07 10:32:09.403  1177  1756 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-07 10:32:09.403  1013  1126 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 10:32:09.403  1013  1123 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-07 10:32:09.403  1013  1126 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
09-07 10:32:09.403  1465  1465 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-07 10:32:09.403  1013  1126 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
09-07 10:32:09.403  1465  1465 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 10:32:09.403  1013  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-07 10:32:09.403  1013  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-07 10:32:09.403  1013  1013 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-07 10:32:09.403  1013  1128 D Tethering: MasterInitialState.processMessage what=3
09-07 10:32:09.413  7326  7326 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 10:32:09.413  1013  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 10:32:09.413  1013  1121 V NetworkStats: updateIfacesLocked(),
09-07 10:32:09.413  1013  1126 D ConnectivityService: nai.networkMonitor.doQuit()
09-07 10:32:09.413  1013  1121 V NetworkStats: performPollLocked(flags=0x1)
09-07 10:32:09.413  1013  1126 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-07 10:32:09.413  1013  1126 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 10:32:09.413  7326  7326 D ActivityThread: Added TimaKeyStore provider
09-07 10:32:09.413  1013  1126 E ConnectivityService: updateNetworkInfo()
09-07 10:32:09.413  1013  1126 E ConnectivityService: updateNetworkInfo()
09-07 10:32:09.413  1013  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-07 10:32:09.413  1177  1177 D StatusBar.NetworkController: EthernetConnected: false
09-07 10:32:09.413  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-07 10:32:09.413  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-07 10:32:09.413  1177  1177 D StatusBar.NetworkController: updateDataNetType()
09-07 10:32:09.413  1013  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-07 10:32:09.413  1013  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-07 10:32:09.413  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 10:32:09.413  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 10:32:09.413  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-07 10:32:09.413  1177  1177 E StatusBar.NetworkController: updateLTEICONDataNetType:0
09-07 10:32:09.413  1013  1122 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-07 10:32:09.413  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 10:32:09.413  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 10:32:09.413  1013  1121 V NetworkStats: performPollLocked() took 8ms
09-07 10:32:09.413  1013  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 10:32:09.413  1177  1177 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-07 10:32:09.413  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 25 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
09-07 10:32:09.413  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
09-07 10:32:09.413  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,09-07 10:32:09.423  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-07 10:32:09.423  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 10:32:09.423  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-07 10:32:09.423  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:09.423  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:09.423  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:09.423  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 10:32:09.423  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit,
09-07 10:32:09.423  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 10:32:09.433  1013  1123 D WifiP2pService: P2pDisabledState{ what=143375 }
,09-07 10:32:09.433  1013  1123 D WifiP2pService: DefaultState{ what=143375 }
,09-07 10:32:09.433   277  1012 D CommandListener: Clearing all IP addresses on wlan0
,09-07 10:32:09.443  1365  1365 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-07 10:32:09.443  1013  1013 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-07 10:32:09.443  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-07 10:32:09.443  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 10:32:09.443  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-07 10:32:09.443  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:09.443  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:09.443  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:09.443  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 10:32:09.443  1013  1124 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false,
,09-07 10:32:09.453  1013  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-07 10:32:09.453  1013  1124 D SecContentProvider2: mCursor = null
,09-07 10:32:09.453  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-07 10:32:09.453  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 10:32:09.453  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-07 10:32:09.453  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:09.453  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:09.453  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:09.453  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:09.453  7326  7326 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-07 10:32:09.453  4773  4773 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-07 10:32:09.453  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-07 10:32:09.453  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 10:32:09.453  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-07 10:32:09.453  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 10:32:09.463  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:09.463  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 10:32:09.463  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:09.463  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-07 10:32:09.463  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
09-07 10:32:09.463  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-07 10:32:09.463  1177  1775 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-07 10:32:09.463  1177  1177 D HotspotTile: onReceive : 0, 0
09-07 10:32:09.463  7071  7071 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 10:32:09.463  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 10:32:09.463  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:09.463  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:09.463  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 10:32:09.463  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 10:32:09.463  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 10:32:09.463  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 10:32:09.463  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false,
09-07 10:32:09.463  7071  7071 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 10:32:09.463  7071  7071 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 10:32:09.463  7071  7071 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 10:32:09.463  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 10:32:09.463  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:09.463  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:09.463  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 10:32:09.463  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 10:32:09.463  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 10:32:09.463  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 10:32:09.463  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 10:32:09.463  7071  7071 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 10:32:09.463  7071  7071 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 10:32:09.483  3222  3295 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-07 10:32:09.483  3222  3295 D BtConfig.SecureMode: isSecureModeOn:false
09-07 10:32:09.483  3222  3295 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-07 10:32:09.483  3222  3295 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
09-07 10:32:09.483  3222  3295 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
09-07 10:32:09.483  3222  3295 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
09-07 10:32:09.483  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-07 10:32:09.483  3222  3295 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-07 10:32:09.483  1013  3836 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-07 10:32:09.483  1013  3836 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-07 10:32:09.483  1013  3836 W ActivityManager: userId = 0, bbcId = -10000,
09-07 10:32:09.483  1013  3836 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:09.483  1013  3836 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:09.483  7326  7326 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,09-07 10:32:09.483  7326  7326 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
,09-07 10:32:09.483  7326  7326 D UserAnalysis: Create SecureDbHelper
09-07 10:32:09.483  3222  3295 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService,
,09-07 10:32:09.483  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-07 10:32:09.493  1013  1481 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 10:32:09.483  3222  3222 D HeadsetService: Received stop request...Stopping profile...
09-07 10:32:09.493  1013  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-07 10:32:09.483  3222  3295 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-07 10:32:09.493  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2acc5f51
09-07 10:32:09.493  1013  1481 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:09.493  1013  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:09.493  1013  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-07 10:32:09.493  1013  1013 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,09-07 10:32:09.493  3222  3295 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
09-07 10:32:09.493  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-07 10:32:09.493  3222  3295 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
09-07 10:32:09.493  7326  7326 D IntelligenceServiceApplication: onCreate()
,09-07 10:32:09.493  1013  1479 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-07 10:32:09.493  1013  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-07 10:32:09.493  4773  4773 D HeadsetProfile: Bluetooth service disconnected
09-07 10:32:09.493  1013  1479 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:09.493  1013  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:09.493  1013  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:09.503  3222  3295 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
09-07 10:32:09.503  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-07 10:32:09.503  3222  3295 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-07 10:32:09.503  1013  3836 I ActivityManager: Killing 6845:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
,09-07 10:32:09.503  7326  7326 D IntelligenceServiceApplication: no applications having user consent for prediction
,09-07 10:32:09.503  1013  1461 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-07 10:32:09.503  1013  1461 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-07 10:32:09.513  1013  1461 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:09.513  1013  1461 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:09.513  1013  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:09.513  1013  1218 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-07 10:32:09.513  3222  3295 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,09-07 10:32:09.513  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-07 10:32:09.513  7326  7326 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
09-07 10:32:09.513  1013  1025 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 10:32:09.513  3222  3295 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
09-07 10:32:09.513  1013  1025 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-07 10:32:09.513  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:09.513  1013  1025 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:09.513  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-07 10:32:09.513  3222  3295 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
09-07 10:32:09.513  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-07 10:32:09.513  3222  3295 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-07 10:32:09.513  1013  1321 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 10:32:09.513  1013  1321 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-07 10:32:09.513  1013  1321 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:32:09.513  1013  1321 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:09.513  1013  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-07 10:32:09.513  3222  3295 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
09-07 10:32:09.513  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-07 10:32:09.513  3222  3295 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
09-07 10:32:09.523  1365  1365 I wpa_supplicant: Blacklist: Clear (all) 
,09-07 10:32:09.523  7326  7326 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-07 10:32:09.523  1013  3836 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 10:32:09.523  1013  3836 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-07 10:32:09.523  1013  3836 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:09.523  1013  3836 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:09.523  1013  3836 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:09.523  3222  3295 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-07 10:32:09.523  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-07 10:32:09.523  3222  3295 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-07 10:32:09.523  3222  3295 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
,09-07 10:32:09.523  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-07 10:32:09.523  3222  3295 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-07 10:32:09.523  3222  3295 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
09-07 10:32:09.523  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-07 10:32:09.523  3222  3295 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-07 10:32:09.523  3222  3295 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
09-07 10:32:09.523  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-07 10:32:09.533  3222  3295 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-07 10:32:09.533  3222  3295 D BluetoothAdapterState: Stopping profile services that were post enabled
,09-07 10:32:09.533  3222  3222 E BluetoothAdapterService(718036817): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,09-07 10:32:09.533  3222  3222 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-07 10:32:09.533  3222  3222 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-07 10:32:09.533  3222  3222 D A2dpService: Received stop request...Stopping profile...
09-07 10:32:09.533  3222  3366 D A2dpStateMachine: Exit Disconnected: -1,
,09-07 10:32:09.533  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2acc5f51,
,09-07 10:32:09.533  1013  1013 D BluetoothA2dp: Proxy object disconnected
09-07 10:32:09.533  1013  1013 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,09-07 10:32:09.533  4773  4773 D BluetoothA2dp: Proxy object disconnected
09-07 10:32:09.533  4773  4773 D A2dpProfile: Bluetooth service disconnected
,09-07 10:32:09.543  3222  3222 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-07 10:32:09.543  3222  3222 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-07 10:32:09.543  3222  3222 D HidService: Received stop request...Stopping profile...
09-07 10:32:09.543  3222  3222 D HidService: Stopping Bluetooth HidService
09-07 10:32:09.543  3222  3222 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-07 10:32:09.543  3222  3222 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-07 10:32:09.543  3222  3222 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-07 10:32:09.543  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2acc5f51
,09-07 10:32:09.543  3222  3222 D HealthService: Received stop request...Stopping profile...
09-07 10:32:09.543  1013  1543 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
09-07 10:32:09.543  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2acc5f51
09-07 10:32:09.543  4773  4773 D BluetoothInputDevice: Proxy object disconnected
09-07 10:32:09.543  4773  4773 D HidProfile: Bluetooth service disconnected
,09-07 10:32:09.553  1465  1465 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-07 10:32:09.553  1013  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:09.553  1013  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:09.553  1013  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:09.553  1013  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:09.553  1465  1465 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-07 10:32:09.553  1465  1465 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-07 10:32:09.553  1465  1465 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-07 10:32:09.563  1465  1465 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-07 10:32:09.563  1465  1465 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-07 10:32:09.563  1465  1465 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-07 10:32:09.563  1465  1465 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-07 10:32:09.563  1465  1465 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-07 10:32:09.563  1465  1465 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-07 10:32:09.563  1465  1465 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-07 10:32:09.563  1465  1465 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-07 10:32:09.563  1465  1465 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-07 10:32:09.573  7351  7351 E Zygote  : MountEmulatedStorage()
09-07 10:32:09.573  7351  7351 E Zygote  : v2
09-07 10:32:09.573  7351  7351 I libpersona: KNOX_SDCARD checking this for 10105,
09-07 10:32:09.573  7351  7351 I libpersona: KNOX_SDCARD not a persona
,09-07 10:32:09.573  7351  7351 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-07 10:32:09.573  1465  1465 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-07 10:32:09.573  1465  1465 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-07 10:32:09.573  1465  1465 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-07 10:32:09.573  1465  1465 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-07 10:32:09.573  1465  1465 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-07 10:32:09.573  1465  1465 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-07 10:32:09.573  1013  1543 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7351 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,09-07 10:32:09.573  1465  1465 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-07 10:32:09.573  7351  7351 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 10:32:09.583  1465  1465 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-07 10:32:09.583  7351  7351 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-07 10:32:09.583  1465  1465 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-07 10:32:09.583  1465  1465 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-07 10:32:09.583  1365  1365 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-07 10:32:09.583  3222  3222 D PanService: Received stop request...Stopping profile...
09-07 10:32:09.583  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2acc5f51
09-07 10:32:09.583  1013  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-07 10:32:09.583  1013  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-07 10:32:09.583  1013  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-07 10:32:09.583  1465  1465 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-07 10:32:09.583  1013  1013 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-07 10:32:09.583  1465  1465 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-07 10:32:09.583  3222  3222 D BluetoothMapService: Received stop request...Stopping profile...
09-07 10:32:09.583  4773  4773 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-07 10:32:09.583  4773  4773 D PanProfile: Bluetooth service disconnected
09-07 10:32:09.583  1465  1465 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-07 10:32:09.583  1465  1465 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-07 10:32:09.593  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2acc5f51
09-07 10:32:09.593  1465  1465 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-07 10:32:09.593  1465  1465 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-07 10:32:09.593  4773  4773 D BluetoothMap: Proxy object disconnected
09-07 10:32:09.593  4773  4773 D MapProfile: Bluetooth service disconnected
,09-07 10:32:09.593  3222  3222 D SapService: Received stop request...Stopping profile...
09-07 10:32:09.593  3222  3222 D SapService: Stopping Bluetooth SapService,
09-07 10:32:09.593  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2acc5f51
09-07 10:32:09.593  3222  3222 E BluetoothAdapterService(718036817): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,09-07 10:32:09.593  3222  3222 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-07 10:32:09.593  3222  3222 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-07 10:32:09.593  3222  3222 D BluetoothA2dp: Proxy object disconnected
09-07 10:32:09.593  3222  3222 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
09-07 10:32:09.593  1465  1465 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-07 10:32:09.593  3222  3367 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-07 10:32:09.593  4773  4773 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-07 10:32:09.593  4773  4773 D SapProfile: Bluetooth service disconnected
09-07 10:32:09.593  3222  3222 I GKI_LINUX: GKI_exit_task 2 done
09-07 10:32:09.593  3222  3222 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-07 10:32:09.593  3222  3222 E BluetoothAdapterService(718036817): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-07 10:32:09.593  3222  3222 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-07 10:32:09.593  3222  3222 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-07 10:32:09.593  3222  3222 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-07 10:32:09.593  3222  3222 E BluetoothAdapterService(718036817): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-07 10:32:09.593  3222  3222 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-07 10:32:09.593  3222  3222 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-07 10:32:09.593  3222  3222 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-07 10:32:09.593  3222  3222 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-07 10:32:09.593  3222  3222 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-07 10:32:09.593  3222  3222 E BluetoothAdapterService(718036817): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-07 10:32:09.593  3222  3222 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-07 10:32:09.593  3222  3222 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-07 10:32:09.593  3222  3222 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-07 10:32:09.593  3222  3222 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-07 10:32:09.593  3222  3222 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-07 10:32:09.593  3222  3222 E BluetoothAdapterService(718036817): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
09-07 10:32:09.593  3222  3222 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-07 10:32:09.593  3222  3222 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-07 10:32:09.593  3222  3222 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
09-07 10:32:09.593  3222  3222 E BluetoothAdapterService(718036817): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-07 10:32:09.593  3222  3222 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-07 10:32:09.593  3222  3222 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-07 10:32:09.593  3222  3222 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,09-07 10:32:09.603  3222  3295 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
09-07 10:32:09.603  3222  3295 D BluetoothAdapterProperties: Setting state to 10
09-07 10:32:09.603  3222  3295 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-07 10:32:09.603  3222  3295 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-07 10:32:09.603  3222  3295 D BluetoothAdapterService: updateAdapterState state is 10
,09-07 10:32:09.603  3222  3295 D BluetoothAdapterService: Autoconnection is available 
09-07 10:32:09.603  3222  3295 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-07 10:32:09.603  3222  3295 I BluetoothAdapterState: Entering OffState
09-07 10:32:09.603  4773  4790 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-07 10:32:09.603  1013  1044 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 10:32:09.603  4773  4782 D BluetoothMap: onBluetoothStateChange: up=false
,09-07 10:32:09.603  3222  3234 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 10:32:09.603  4773  4782 D Bluetoothsap: onBluetoothStateChange: up=false
09-07 10:32:09.603  4773  4782 D Bluetoothsap: Unbinding service...
,09-07 10:32:09.603  1747  1770 D BluetoothAdapter: onBluetoothStateChange: up=false
09-07 10:32:09.603  1747  1770 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-07 10:32:09.603  2645  2669 D BluetoothAdapter: onBluetoothStateChange: up=false
09-07 10:32:09.603  2645  2669 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 10:32:09.603  7071  7084 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-07 10:32:09.603  7071  7084 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-07 10:32:09.603  7071  7084 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-07 10:32:09.603  7071  7084 D BluetoothLeAdvertiser: Exit stop advertising
09-07 10:32:09.603  7071  7084 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-07 10:32:09.603  7071  7084 D BluetoothLeScanner: Exiting stopAllScan
09-07 10:32:09.603  1013  1044 D BluetoothAdapter: onBluetoothStateChange: up=false
09-07 10:32:09.603  1013  1044 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-07 10:32:09.613  1365  1365 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,09-07 10:32:09.613  1365  1365 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-07 10:32:09.613  1013  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-07 10:32:09.613  1365  1365 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-07 10:32:09.613  1013  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-07 10:32:09.613  1013  1042 D Tethering: interfaceStatusChanged wlan0, false
09-07 10:32:09.613  1365  1365 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-07 10:32:09.613  1365  1365 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
09-07 10:32:09.613  1013  1128 D Tethering: InitialState.processMessage what=4
09-07 10:32:09.613  1013  1128 E Tethering: No numeric data
09-07 10:32:09.613  1434  1463 D BluetoothAdapter: onBluetoothStateChange: up=false
09-07 10:32:09.613  1434  1463 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-07 10:32:09.613  1013  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-07 10:32:09.613  1013  1128 D Tethering: clearTetheredNotification()
09-07 10:32:09.613  3222  3299 D BluetoothAdapter: onBluetoothStateChange: up=false
09-07 10:32:09.613  3222  3299 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 10:32:09.613  1013  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-07 10:32:09.613  1013  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-07 10:32:09.613  1013  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-07 10:32:09.613  1013  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 10:32:09.613  1013  1121 V NetworkStats: performPollLocked(flags=0x1)
09-07 10:32:09.613  7351  7351 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 10:32:09.613  1013  1042 D Tethering: interfaceLinkStateChanged wlan0, false
,09-07 10:32:09.613  1013  1042 D Tethering: interfaceStatusChanged wlan0, false
09-07 10:32:09.613  7351  7351 D ActivityThread: Added TimaKeyStore provider
09-07 10:32:09.613  1013  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-07 10:32:09.613  1013  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-07 10:32:09.613  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-07 10:32:09.613  1177  1177 D HotspotTile: updateTetherState():false, false
,09-07 10:32:09.613  1177  2022 D BluetoothAdapter: onBluetoothStateChange: up=false
09-07 10:32:09.613  1013  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-07 10:32:09.613  1177  2022 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-07 10:32:09.613  1465  1482 D BluetoothAdapter: onBluetoothStateChange: up=false
09-07 10:32:09.613  1465  1482 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 10:32:09.623  1013  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 10:32:09.623  1013  1121 V NetworkStats: performPollLocked() took 6ms
,09-07 10:32:09.623  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 10:32:09.623  4773  4782 D BluetoothAdapter: onBluetoothStateChange: up=false
09-07 10:32:09.623  4773  4782 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-07 10:32:09.623  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 10:32:09.623  1444  1464 D BluetoothAdapter: onBluetoothStateChange: up=false
09-07 10:32:09.623  1444  1464 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 10:32:09.623  4773  4790 D BluetoothPbap: onBluetoothStateChange: up=false
,09-07 10:32:09.623  4773  4782 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-07 10:32:09.623  1013  1013 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-07 10:32:09.623  1013  1013 I InputMethodManagerService: [BT Setting State] State =10
09-07 10:32:09.623  1013  1013 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-07 10:32:09.633  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-07 10:32:09.633  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-07 10:32:09.633  1177  1177 D BluetoothTile:  getBluetoothState : 10
,09-07 10:32:09.633  1899  1899 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-07 10:32:09.633  4773  4773 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-07 10:32:09.633  1013  1025 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-07 10:32:09.633  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:09.643  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:09.643  1013  1461 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-07 10:32:09.643  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-07 10:32:09.653  7071  7071 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 10:32:09.733   256   523 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-07 10:32:09.733   256   523 W Vold    : Returning OperationFailed - no handler for errno 0
,09-07 10:32:09.733  7351  7379 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-07 10:32:09.733   256   523 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-07 10:32:09.733   256   523 W Vold    : Returning OperationFailed - no handler for errno 0
,09-07 10:32:09.733  7351  7379 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-07 10:32:09.783  1365  1365 I wpa_supplicant: Blacklist: Clear (all) 
,09-07 10:32:09.793   326   326 I ServiceManager: Waiting for service AtCmdFwd...,
,09-07 10:32:09.813  1365  1365 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
09-07 10:32:09.813  1013  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-07 10:32:09.813  1013  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-07 10:32:09.813  1013  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-07 10:32:09.883  7351  7351 D StrictMode: StrictMode policy violation; ~duration=151 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at java.io.File.exists(File.java:363)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 10:32:09.883  7351  7351 D StrictMode: StrictMode policy violation; ~duration=150 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 10:32:09.883  7351  7351 D StrictMode: StrictMode policy violation; ~duration=149 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 10:32:09.883  7351  7351 D StrictMode: StrictMode policy violation; ~duration=148 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.q.k.a(PG:2107)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.q.e.b(PG:170)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 10:32:09.883  7351  7351 D StrictMode: StrictMode policy violation; ~duration=146 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.q.k.c(PG:18147)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.q.k.d(PG:583)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.q.e.b(PG:170)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 10:32:09.883  7351  7351 D StrictMode: StrictMode policy violation; ~duration=126 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at java.io.File.exists(File.java:363)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 10:32:09.893  1013  3836 I ActivityManager: Killing 6862:com.google.android.partnersetup/u0a14 (adj 15): empty #21
09-07 10:32:09.883  7351  7351 D StrictMode: StrictMode policy violation; ~duration=125 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at java.io.File.exists(File.java:363)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 10:32:09.883  7351  7351 D StrictMode: StrictMode policy violation; ~duration=125 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at java.io.File.lastModified(File.java:571)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 10:32:09.883  7351  7351 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 10:32:09.893  1013  1218 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-07 10:32:09.893  1013  1218 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:09.893  1013  1218 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-07 10:32:09.893  1013  1218 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:09.893  1013  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-07 10:32:09.893  1602  1602 I Hs20UtilService: Starting #8
09-07 10:32:09.893  1602  1641 I Hs20UtilService: Message received 5007
09-07 10:32:09.903  4773  4773 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-07 10:32:09.903  1013  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-07 10:32:09.903  4773  4773 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-07 10:32:09.903  4773  4773 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-07 10:32:09.903  4773  4773 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-07 10:32:09.913  4773  4773 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-07 10:32:09.913  4773  4773 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-07 10:32:09.913  4773  4865 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-07 10:32:09.913  1013  1013 I ApplicationPolicy: updateDataUsageMap
,09-07 10:32:09.923  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:32:09.933  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:32:09.933  1013  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
09-07 10:32:09.933  1013  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21]
09-07 10:32:09.933  1013  3836 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:09.933  1013  3836 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 10:32:09.933  1013  3836 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
09-07 10:32:09.933  1013  3836 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
09-07 10:32:09.933  1013  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:09.933  1013  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:09.933  1013  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:09.933  1013  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:09.953  7390  7390 E Zygote  : MountEmulatedStorage()
09-07 10:32:09.953  7390  7390 E Zygote  : v2
09-07 10:32:09.953  7390  7390 I libpersona: KNOX_SDCARD checking this for 10102
09-07 10:32:09.953  7390  7390 I libpersona: KNOX_SDCARD not a persona
09-07 10:32:09.953  7390  7390 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 10:32:09.953  7390  7390 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 10:32:09.953  1013  3836 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7390 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
09-07 10:32:09.953  7390  7390 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-07 10:32:09.963  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-07 10:32:09.963  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 10:32:09.963  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,09-07 10:32:09.963  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:09.963  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:09.963  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:09.963  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:09.973  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-07 10:32:09.973  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,09-07 10:32:09.973  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-07 10:32:09.973  1177  1775 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-07 10:32:09.973  4773  4773 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
09-07 10:32:09.973  1177  1177 D HotspotTile: onReceive : 1, 0
,09-07 10:32:09.973  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:09.973  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:09.973  7351  7378 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-07 10:32:09.983  1747  2186 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 10:32:09.983  7390  7390 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 10:32:09.983  7390  7390 D ActivityThread: Added TimaKeyStore provider
,09-07 10:32:10.003  1013  3832 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-07 10:32:10.003  1013  3832 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:32:10.003  7390  7390 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-07 10:32:10.003  1013  3832 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 10:32:10.003  1013  3832 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-07 10:32:10.033  1013  1039 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-07 10:32:10.193  7390  7412 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
09-07 10:32:10.193  7390  7412 I Babel_SMS: MmsConfig.loadMmsSettings
09-07 10:32:10.193  7390  7412 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
09-07 10:32:10.193  7390  7412 I Babel_SMS: MmsConfig.loadFromDatabase
,09-07 10:32:10.213  7390  7412 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,09-07 10:32:10.213  7390  7412 I Babel_SMS: MmsConfig.loadFromResources
,09-07 10:32:10.223  7390  7412 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,09-07 10:32:10.223  7390  7412 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,09-07 10:32:10.253  1013  1218 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,09-07 10:32:10.253  1013  1218 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,09-07 10:32:10.253  1013  1218 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:32:10.253  1013  1218 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-07 10:32:10.253  1013  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-07 10:32:10.273  7390  7390 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 10:32:10.273  7390  7390 I Babel_Crash: startup - clean
,09-07 10:32:10.313  4773  4773 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-07 10:32:10.313  4773  4773 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-07 10:32:10.323  4773  4773 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-07 10:32:10.323  4773  4773 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-07 10:32:10.323  4773  4773 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,09-07 10:32:10.323  4773  4773 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-07 10:32:10.323  4773  4865 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-07 10:32:10.323  1013  3836 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,09-07 10:32:10.323  1013  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:10.323  1013  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:10.323  1013  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:10.323  1013  3836 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:10.333  7390  7390 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc,
,09-07 10:32:10.333  7390  7390 W AudioCapabilities: Unsupported mime audio/evrc,
,09-07 10:32:10.333  7390  7390 W AudioCapabilities: Unsupported mime audio/qcelp
,09-07 10:32:10.343  7415  7415 E Zygote  : MountEmulatedStorage(),
09-07 10:32:10.343  7415  7415 E Zygote  : v2
09-07 10:32:10.343  7415  7415 I libpersona: KNOX_SDCARD checking this for 10064
09-07 10:32:10.343  7415  7415 I libpersona: KNOX_SDCARD not a persona
,09-07 10:32:10.343  7415  7415 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 10:32:10.343  1013  3836 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7415 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-07 10:32:10.343  7415  7415 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 10:32:10.343  7415  7415 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-07 10:32:10.343  7390  7390 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,09-07 10:32:10.343  7390  7390 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,09-07 10:32:10.353  7390  7390 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,09-07 10:32:10.353  7390  7390 W AudioCapabilities: Unsupported mime audio/x-ima
,09-07 10:32:10.353  7390  7390 W AudioCapabilities: Unsupported mime audio/qcelp
09-07 10:32:10.353  7390  7390 W AudioCapabilities: Unsupported mime audio/evrc
,09-07 10:32:10.363  7415  7415 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 10:32:10.363  7415  7415 D ActivityThread: Added TimaKeyStore provider
,09-07 10:32:10.373   314   314 I art     : Explicit concurrent mark sweep GC freed 8698(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 592us total 28.724ms
,09-07 10:32:10.373  7390  7390 W VideoCapabilities: Unsupported mime video/wvc1
,09-07 10:32:10.373  7390  7390 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-07 10:32:10.383  7415  7415 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-07 10:32:10.383  7390  7390 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,09-07 10:32:10.383   314   314 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 574us total 16.401ms
,09-07 10:32:10.403   314   314 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 667us total 17.548ms
,09-07 10:32:10.413  7390  7390 W VideoCapabilities: Unsupported mime video/wvc1
,09-07 10:32:10.413  7390  7390 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-07 10:32:10.413  7390  7390 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,09-07 10:32:10.413  7390  7390 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,09-07 10:32:10.423  7390  7390 W VideoCapabilities: Unsupported mime video/mp43
,09-07 10:32:10.423  1013  1042 D Tethering: interfaceRemoved wlan0
09-07 10:32:10.423  1013  1042 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-07 10:32:10.423  7390  7390 W VideoCapabilities: Unsupported mime video/sorenson
,09-07 10:32:10.433  7390  7390 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-07 10:32:10.433  7415  7415 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-07 10:32:10.433  7415  7415 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-07 10:32:10.443  7390  7390 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-07 10:32:10.463  7390  7390 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-07 10:32:10.473  7390  7390 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-07 10:32:10.473  7390  7390 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-07 10:32:10.473  7415  7415 D FileShare-Client: Outbound.stopDelayTimer - 
,09-07 10:32:10.473  7390  7390 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-07 10:32:10.473  1013  1025 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,09-07 10:32:10.483  1013  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:10.483  1013  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:10.483  1013  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:10.483  1013  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:10.493  7430  7430 E Zygote  : MountEmulatedStorage()
,09-07 10:32:10.493  7430  7430 E Zygote  : v2
09-07 10:32:10.493  7430  7430 I libpersona: KNOX_SDCARD checking this for 10065
09-07 10:32:10.493  7430  7430 I libpersona: KNOX_SDCARD not a persona
,09-07 10:32:10.493  7430  7430 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 10:32:10.493  1013  1025 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7430 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-07 10:32:10.493  1013  1025 I ActivityManager: Killing 6886:com.google.android.apps.docs/u0a87 (adj 15): empty #21
,09-07 10:32:10.493  1013  1321 I ActivityManager: Killing 6922:com.sec.pcw.device/1000 (adj 15): empty #21
,09-07 10:32:10.503  7430  7430 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 10:32:10.503  7430  7430 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-07 10:32:10.503  7390  7390 I vclib   : onServiceConnected
,09-07 10:32:10.523  7430  7430 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 10:32:10.523  7430  7430 D ActivityThread: Added TimaKeyStore provider
,09-07 10:32:10.533  1013  1042 D Tethering: interfaceRemoved p2p0
09-07 10:32:10.533  1013  1042 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-07 10:32:10.543  7430  7430 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-07 10:32:10.553  1013  1461 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:32:10.553  1013  1461 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 10:32:10.553  1013  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 10:32:10.553  1013  1461 I ActivityManager: Killing 6808:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,09-07 10:32:10.553  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:32:10.553  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:10.553  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 10:32:10.553  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:32:10.553  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:10.553  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 10:32:10.563  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:32:10.563  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:10.563  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 10:32:10.563  1013  1133 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-07 10:32:10.563  1013  1133 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-07 10:32:10.563  1013  1133 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:10.563  1013  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:10.573  1013  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-07 10:32:10.573  1602  1602 I Hs20UtilService: Starting #9
,09-07 10:32:10.573  1602  1641 I Hs20UtilService: Message received 5007
,09-07 10:32:10.573  4773  4773 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-07 10:32:10.573  4773  4773 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-07 10:32:10.573  4773  4773 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-07 10:32:10.573  4773  4773 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-07 10:32:10.573  4773  4773 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-07 10:32:10.573  4773  4773 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-07 10:32:10.573  4773  4865 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-07 10:32:10.583  1013  1218 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-07 10:32:10.583  1013  1218 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-07 10:32:10.583  1013  1218 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:10.583  1013  1218 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:10.583  1013  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-07 10:32:10.583  1602  1602 I Hs20UtilService: Starting #10
,09-07 10:32:10.583  1602  1641 I Hs20UtilService: Message received 5011,
09-07 10:32:10.583  1013  1461 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast,
,09-07 10:32:10.583  1013  1461 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,09-07 10:32:10.583  1013  1461 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-07 10:32:10.583  1013  1461 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:10.583  1013  1461 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:10.603  7445  7445 E Zygote  : MountEmulatedStorage()
,09-07 10:32:10.603  7445  7445 E Zygote  : v2
09-07 10:32:10.603  7445  7445 I libpersona: KNOX_SDCARD checking this for 1000
09-07 10:32:10.603  7445  7445 I libpersona: KNOX_SDCARD not a persona
,09-07 10:32:10.603  7445  7445 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 10:32:10.603  7445  7445 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-07 10:32:10.603  1013  1461 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=7445 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-07 10:32:10.603  7445  7445 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 10:32:10.623  7445  7445 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 10:32:10.623  7445  7445 D ActivityThread: Added TimaKeyStore provider,
,09-07 10:32:10.653  7445  7445 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-07 10:32:10.653  7445  7445 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-07 10:32:10.653  7445  7445 D SecurityLogAgent: StateMachine : Current State = 1
,09-07 10:32:10.663  7445  7445 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-07 10:32:10.663  1013  1496 I ActivityManager: Killing 7002:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
,09-07 10:32:10.673  1013  1504 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:32:10.673  1013  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:10.673  1013  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 10:32:10.673  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:32:10.673  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 10:32:10.673  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 10:32:10.673  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:32:10.673  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 10:32:10.673  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 10:32:10.683  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:32:10.683  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:10.683  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 10:32:10.683  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:32:10.683  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:10.683  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 10:32:10.683  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:32:10.683  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:10.683  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 10:32:10.693  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:10.693  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:10.693  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 10:32:10.693  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:32:10.693  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:10.693  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 10:32:10.693  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:32:10.693  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:10.693  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 10:32:10.703  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:32:10.703  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:10.703  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 10:32:10.703  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:32:10.703  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:10.703  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 10:32:10.703  4773  4773 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 10:32:10.703  1013  1461 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-07 10:32:10.703  1013  1461 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
09-07 10:32:10.713  1013  1461 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:10.713  1013  1461 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:10.713  1013  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-07 10:32:10.713  4773  4773 D DockEventReceiver: finishStartingService: stopping service,
,09-07 10:32:10.713  2645  2645 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 10:32:10.723  4773  4773 D BluetoothNotiBroadcastReceiver: onReceive
,09-07 10:32:10.723  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-07 10:32:10.723  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-07 10:32:10.733  1013  3832 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-07 10:32:10.733  1013  3832 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:10.733  1013  3832 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:10.733  1013  3832 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:10.733  1013  3832 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:10.753  7463  7463 E Zygote  : MountEmulatedStorage(),
09-07 10:32:10.753  7463  7463 E Zygote  : v2
09-07 10:32:10.753  7463  7463 I libpersona: KNOX_SDCARD checking this for 1000
09-07 10:32:10.753  7463  7463 I libpersona: KNOX_SDCARD not a persona
,09-07 10:32:10.753  7463  7463 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-07 10:32:10.753   292   292 E SMD     : DCD OFF
,09-07 10:32:10.753  7463  7463 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 10:32:10.753  7463  7463 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 10:32:10.763  1013  1321 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-07 10:32:10.763  1013  1321 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4235, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-07 10:32:10.763  1013  1321 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-07 10:32:10.763  1013  1321 D BatteryService: stay LED for charging
09-07 10:32:10.763  1013  1013 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-07 10:32:10.763  1013  3832 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7463 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-07 10:32:10.773  1013  1013 I MotionRecognitionService: Plugged
,09-07 10:32:10.773  1013  1013 I MotionRecognitionService: mGripSensorEnabled= false
,09-07 10:32:10.773  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-07 10:32:10.773  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-07 10:32:10.773  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-07 10:32:10.773  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-07 10:32:10.773  7463  7463 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 10:32:10.773  7463  7463 D ActivityThread: Added TimaKeyStore provider
,09-07 10:32:10.793   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,09-07 10:32:10.793  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-07 10:32:10.793  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-07 10:32:10.803  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-07 10:32:10.803  7463  7463 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,09-07 10:32:10.803  7463  7463 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
,09-07 10:32:10.803  7463  7463 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-07 10:32:10.813  7463  7463 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-07 10:32:10.813  7463  7463 I PCWCLIENTTRACE_PushUtil: sales region : global
,09-07 10:32:10.813  7463  7463 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,09-07 10:32:10.813  7463  7463 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-07 10:32:10.823  1013  3836 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
,09-07 10:32:10.823  1013  3836 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
09-07 10:32:10.823  1013  3836 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
09-07 10:32:10.823  1013  3836 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,09-07 10:32:10.823  7463  7478 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
09-07 10:32:10.823  1013  3836 I ActivityManager: Killing 7022:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
,09-07 10:32:10.833  1013  1013 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,09-07 10:32:10.833  1013  1013 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:10.833  1013  1013 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:10.833  1013  1013 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:10.833  1013  1013 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:10.843  7480  7480 E Zygote  : MountEmulatedStorage()
,09-07 10:32:10.843  7480  7480 I libpersona: KNOX_SDCARD checking this for 10001
09-07 10:32:10.843  7480  7480 E Zygote  : v2
09-07 10:32:10.843  7480  7480 I libpersona: KNOX_SDCARD not a persona
,09-07 10:32:10.843  7480  7480 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 10:32:10.843  1013  1013 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7480 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
09-07 10:32:10.843  7480  7480 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 10:32:10.843  7480  7480 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 10:32:10.863  7480  7480 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 10:32:10.863  7480  7480 D ActivityThread: Added TimaKeyStore provider
,09-07 10:32:10.933  1013  1461 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,09-07 10:32:10.933  1013  1461 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:10.933  1013  1461 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:10.933  1013  1461 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:10.933  1013  1461 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:10.943  7497  7497 E Zygote  : MountEmulatedStorage(),
09-07 10:32:10.943  7497  7497 E Zygote  : v2
,09-07 10:32:10.943  1013  1461 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7497 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
09-07 10:32:10.943  1013  1461 I ActivityManager: Killing 7054:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
09-07 10:32:10.943  7497  7497 I libpersona: KNOX_SDCARD checking this for 1000
09-07 10:32:10.943  7497  7497 I libpersona: KNOX_SDCARD not a persona
,09-07 10:32:10.943  7497  7497 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 10:32:10.953  7497  7497 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 10:32:10.953  7497  7497 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 10:32:10.963  7497  7497 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 10:32:10.963  7497  7497 D ActivityThread: Added TimaKeyStore provider
,09-07 10:32:11.003  7497  7497 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,09-07 10:32:11.123  7497  7497 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,09-07 10:32:11.133  7497  7497 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,09-07 10:32:11.133  7497  7497 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,09-07 10:32:11.133  7497  7497 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-07 10:32:11.133  7497  7497 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,09-07 10:32:11.133  7497  7497 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-07 10:32:11.133  1013  1133 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,09-07 10:32:11.143  1013  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:11.143  1013  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:11.143  1013  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:11.143  1013  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:11.153  7512  7512 E Zygote  : MountEmulatedStorage()
09-07 10:32:11.153  7512  7512 E Zygote  : v2
09-07 10:32:11.153  7512  7512 I libpersona: KNOX_SDCARD checking this for 10008
09-07 10:32:11.153  7512  7512 I libpersona: KNOX_SDCARD not a persona
,09-07 10:32:11.153  1013  1133 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7512 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-07 10:32:11.153  7512  7512 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-07 10:32:11.153  1013  1133 I ActivityManager: Killing 7088:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
09-07 10:32:11.153  7512  7512 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 10:32:11.153  7512  7512 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-07 10:32:11.183  7512  7512 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 10:32:11.183  7512  7512 D ActivityThread: Added TimaKeyStore provider
,09-07 10:32:11.273  1013  1025 I ActivityManager: Killing 6961:com.android.mms/u0a41 (adj 15): empty #21
,09-07 10:32:11.273  1013  1461 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-07 10:32:11.273  1013  1461 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-07 10:32:11.273  1013  1461 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:32:11.273  1013  1461 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 10:32:11.273  1013  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 10:32:11.293  1924  1924 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-07 10:32:11.293  1013  1504 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-07 10:32:11.293  1013  1504 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,09-07 10:32:11.293  1013  1504 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:11.293  1013  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 10:32:11.293  1013  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 10:32:11.303  1924  2821 I iu.UploadsManager: num queued entries: 0
,09-07 10:32:11.303  1924  2821 I iu.UploadsManager: num updated entries: 0
,09-07 10:32:11.303  1924  2821 I iu.SyncManager: NEXT; no task
,09-07 10:32:11.303  1924  1924 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-07 10:32:11.303  1924  1924 I Kids    : [GCoreUtils] Current gmscore version, 8115234 is smaller than the required version 8400000
,09-07 10:32:11.313  2825  2825 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Sep 07 10:32:11 GMT+02:00 2016
,09-07 10:32:11.313  1013  1025 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-07 10:32:11.313  1013  1025 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-07 10:32:11.313  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:32:11.313  1013  1025 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 10:32:11.313  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-07 10:32:11.323  2825  2825 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-07 10:32:11.323  1013  1218 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,09-07 10:32:11.333  1013  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,09-07 10:32:11.333  1013  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:11.333  1013  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:11.333  2825  2825 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
09-07 10:32:11.333  1013  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:11.333  2825  2825 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true,
,09-07 10:32:11.333  2825  2825 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false,
,09-07 10:32:11.333  2825  7528 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-07 10:32:11.343  2825  7528 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION,
,09-07 10:32:11.353  7529  7529 E Zygote  : MountEmulatedStorage(),
09-07 10:32:11.353  7529  7529 E Zygote  : v2
,09-07 10:32:11.353  1013  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
09-07 10:32:11.353  7529  7529 I libpersona: KNOX_SDCARD checking this for 10031
09-07 10:32:11.353  7529  7529 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 10:32:11.353  7529  7529 I libpersona: KNOX_SDCARD not a persona
09-07 10:32:11.353  1013  1218 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7529 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,09-07 10:32:11.353  2825  7528 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,09-07 10:32:11.353  7529  7529 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 10:32:11.353  2825  7528 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,09-07 10:32:11.353  7529  7529 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 10:32:11.353  2825  2825 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-07 10:32:11.373  7529  7529 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 10:32:11.373  7529  7529 D ActivityThread: Added TimaKeyStore provider
09-07 10:32:11.373  1013  1218 D CountryDetector: No listener is left
,09-07 10:32:11.393  7529  7529 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,09-07 10:32:11.403  1013  1461 I ActivityManager: Killing 7130:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,09-07 10:32:11.413  1013  1025 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,09-07 10:32:11.413  1013  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:11.413  1013  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:11.413  1013  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:11.413  2763  7544 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
09-07 10:32:11.413  1013  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:11.423  2763  7544 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,09-07 10:32:11.423  2763  7544 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,09-07 10:32:11.433  2763  7544 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
09-07 10:32:11.433  7545  7545 E Zygote  : MountEmulatedStorage()
09-07 10:32:11.433  7545  7545 E Zygote  : v2
09-07 10:32:11.433  7545  7545 I libpersona: KNOX_SDCARD checking this for 10032
09-07 10:32:11.433  7545  7545 I libpersona: KNOX_SDCARD not a persona
,09-07 10:32:11.433  7545  7545 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 10:32:11.433  2763  7544 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,09-07 10:32:11.433  7545  7545 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 10:32:11.433  1013  1025 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7545 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-07 10:32:11.433  7545  7545 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
,09-07 10:32:11.463  7545  7545 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 10:32:11.463  7545  7545 D ActivityThread: Added TimaKeyStore provider
,09-07 10:32:11.503  7545  7560 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,09-07 10:32:11.503  7545  7560 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,09-07 10:32:11.513  7545  7560 D SPPClientService: PushLog.txt file is not deleted.
,09-07 10:32:11.513  7545  7560 D SPPClientService: PushLog.txt file is not deleted.
,09-07 10:32:11.513  7545  7560 D SPPClientService: ============PushLog. stop!
,09-07 10:32:11.513  7545  7545 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,09-07 10:32:11.513  1013  1481 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,09-07 10:32:11.513  1013  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:11.513  1013  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:11.513  1013  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:11.513  1013  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:11.533  7562  7562 E Zygote  : MountEmulatedStorage(),
09-07 10:32:11.533  7562  7562 E Zygote  : v2
09-07 10:32:11.533  7562  7562 I libpersona: KNOX_SDCARD checking this for 10036
09-07 10:32:11.533  7562  7562 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 10:32:11.533  7562  7562 I libpersona: KNOX_SDCARD not a persona
09-07 10:32:11.533  1013  1481 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7562 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-07 10:32:11.533  1013  1481 I ActivityManager: Killing 7155:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
,09-07 10:32:11.543  7562  7562 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 10:32:11.543  1013  1496 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
09-07 10:32:11.543  1013  1496 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
09-07 10:32:11.543  1013  1496 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:11.543  1013  1496 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-07 10:32:11.543  1013  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
09-07 10:32:11.543  7562  7562 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,09-07 10:32:11.563  7562  7562 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 10:32:11.563  7562  7562 D ActivityThread: Added TimaKeyStore provider
,09-07 10:32:11.573  7545  7569 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,09-07 10:32:11.613  7562  7562 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@352966de
,09-07 10:32:11.623  7562  7562 I SA      : [SSP] onCreated
,09-07 10:32:11.643  7562  7562 I SA      : [TPM] There is no property file
,09-07 10:32:11.643  7562  7562 I SA      : [SCU] isHaveSA() - false
,09-07 10:32:11.643  7562  7562 I SA      : [TPM] getModelProperty : null
,09-07 10:32:11.653  7562  7562 I SA      : [TPM] getCSCProperty : null
,09-07 10:32:11.653  7562  7562 I SA      : [DM] FLOATING AMOLED FEATURE: true
09-07 10:32:11.653  7562  7562 I SA      : [DM] PRODUCT AMOLED FEATURE: false
09-07 10:32:11.653  7562  7562 I SA      : [DM] TFT FEATURE: false
,09-07 10:32:11.653  7562  7562 I SA      : [DM] init START
,09-07 10:32:11.653  7562  7562 I SA      : [DM] This device is not a Vodafone
,09-07 10:32:11.663  7562  7562 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,09-07 10:32:11.663  7562  7562 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,09-07 10:32:11.663  7562  7562 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,09-07 10:32:11.663  7562  7562 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,09-07 10:32:11.663  7562  7562 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,09-07 10:32:11.663  7562  7562 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,09-07 10:32:11.663  7562  7562 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,09-07 10:32:11.673  7562  7562 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-07 10:32:11.673  7562  7562 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,09-07 10:32:11.673  7562  7562 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,09-07 10:32:11.673  7562  7562 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,09-07 10:32:11.673  7562  7562 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,09-07 10:32:11.673  7562  7562 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,09-07 10:32:11.673  7562  7562 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
,09-07 10:32:11.673  7562  7562 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
,09-07 10:32:11.683  7562  7562 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,09-07 10:32:11.683  7562  7562 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
,09-07 10:32:11.683  7562  7562 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,09-07 10:32:11.683  7562  7562 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,09-07 10:32:11.683  7562  7562 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,09-07 10:32:11.683  7562  7562 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,09-07 10:32:11.683  7562  7562 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,09-07 10:32:11.683  7562  7562 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,09-07 10:32:11.683  7562  7562 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,09-07 10:32:11.683  7562  7562 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,09-07 10:32:11.693  7562  7562 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,09-07 10:32:11.693  7562  7562 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
,09-07 10:32:11.693  7562  7562 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,09-07 10:32:11.693  7562  7562 I SA      : [SCU] isHaveSA() - false
09-07 10:32:11.693  7562  7562 I SA      : support phone number id : false
09-07 10:32:11.693  7562  7562 I SA      : [DM] Supports Ref Jpn : true
,09-07 10:32:11.693  7562  7562 I SA      : [DM] init END
,09-07 10:32:11.693  7562  7562 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,09-07 10:32:11.703  7562  7562 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,09-07 10:32:11.703  7562  7562 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-07 10:32:11.713  7562  7562 I SA      : [SLFUCHKMGR] constructor called
,09-07 10:32:11.713  7562  7562 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,09-07 10:32:11.713  7562  7562 I SA      : [OR] == isSIMCardReady false ==
,09-07 10:32:11.723  7562  7562 I SA      : [SCU] == networkStateCheck == false
,09-07 10:32:11.723  7562  7562 I SA      : [OR] onReceive END
,09-07 10:32:11.723  1013  3832 I ActivityManager: Killing 7175:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
,09-07 10:32:11.733  1225  1225 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-07 10:32:11.733  1788  1788 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-07 10:32:11.743  2498  2513 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,09-07 10:32:11.743  1788  1788 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,09-07 10:32:11.743  1788  1788 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,09-07 10:32:11.743  1788  1788 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,09-07 10:32:11.743  1788  1788 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-07 10:32:11.753  1788  1788 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-07 10:32:11.753  1788  1788 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,09-07 10:32:11.753  1013  1504 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,09-07 10:32:11.753  1013  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:11.753  1013  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:11.753  1013  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:11.763  1013  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:11.773  1013  1504 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7584 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,09-07 10:32:11.773  7584  7584 E Zygote  : MountEmulatedStorage(),
09-07 10:32:11.773  7584  7584 I libpersona: KNOX_SDCARD checking this for 10077
09-07 10:32:11.773  7584  7584 E Zygote  : v2
09-07 10:32:11.773  7584  7584 I libpersona: KNOX_SDCARD not a persona,
,09-07 10:32:11.773  7584  7584 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 10:32:11.783  7584  7584 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 10:32:11.783  7584  7584 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,09-07 10:32:11.793  7584  7584 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 10:32:11.793  7584  7584 D ActivityThread: Added TimaKeyStore provider
,09-07 10:32:11.793   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,09-07 10:32:11.983  1013  1543 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,09-07 10:32:11.983  1013  1543 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,09-07 10:32:11.983  1013  1543 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:32:11.983  1013  1543 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 10:32:11.983  1013  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-07 10:32:11.983  1013  1026 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,09-07 10:32:11.983  1013  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:11.983  1013  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:11.983  1013  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:11.983  1013  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:12.003  1013  1026 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7605 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-07 10:32:12.003  7605  7605 E Zygote  : MountEmulatedStorage()
09-07 10:32:12.003  7605  7605 I libpersona: KNOX_SDCARD checking this for 10110
09-07 10:32:12.003  7605  7605 E Zygote  : v2
09-07 10:32:12.003  7605  7605 I libpersona: KNOX_SDCARD not a persona
,09-07 10:32:12.003  7605  7605 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 10:32:12.003  1013  1025 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
09-07 10:32:12.003  1013  1025 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
09-07 10:32:12.003  7605  7605 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 10:32:12.003  7605  7605 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-07 10:32:12.003  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:12.003  1013  1025 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 10:32:12.003  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-07 10:32:12.003  7390  7604 I Babel   : connection state changed from UNKNOWN to DISCONNECTED,
,09-07 10:32:12.023  7605  7605 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 10:32:12.023   314   314 I art     : Explicit concurrent mark sweep GC freed 8714(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 589us total 22.265ms
,09-07 10:32:12.023  7605  7605 D ActivityThread: Added TimaKeyStore provider
,09-07 10:32:12.023  1013  1218 I ActivityManager: Killing 7186:com.wsomacp/u0a23 (adj 15): empty #21
,09-07 10:32:12.043   314   314 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 581us total 17.039ms
,09-07 10:32:12.053   314   314 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 565us total 16.276ms
,09-07 10:32:12.153  1013  3832 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-07 10:32:12.293  7605  7605 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-07 10:32:12.293  7605  7605 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-07 10:32:12.293  7605  7605 I GAv4    :   adb logcat -s GAv4
,09-07 10:32:12.303  1013  1321 D SecContentProvider: uri = 18 selection = isWifiEnabled,
09-07 10:32:12.303  1013  1321 D WifiService: setWifiEnabled: true pid=7071, uid=10170
09-07 10:32:12.303  1013  1321 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-07 10:32:12.303  1013  1321 W ActivityManager: Permission Denial: getCurrentUser() from pid=7071, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-07 10:32:12.303  1013  1321 D SecContentProvider2: mCursor = null,
09-07 10:32:12.303  1013  1321 W WifiService: Failed getting userId using ActivityManagerNative
09-07 10:32:12.303  1013  1321 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7071, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-07 10:32:12.303  1013  1321 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-07 10:32:12.303  1013  1321 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-07 10:32:12.303  1013  1321 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-07 10:32:12.303  1013  1321 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-07 10:32:12.303  1013  1321 W WifiService: ,	at android.os.Binder.execTransact(Binder.java:446)
09-07 10:32:12.303  1013  1321 D SettingsProvider: name = wifi_on
,09-07 10:32:12.313   256   523 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-07 10:32:12.313   256   523 W Vold    : Returning OperationFailed - no handler for errno 0
,09-07 10:32:12.313  7605  7623 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-07 10:32:12.313   256   523 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-07 10:32:12.313   256   523 W Vold    : Returning OperationFailed - no handler for errno 0
,09-07 10:32:12.313  7605  7623 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-07 10:32:12.323  1013  1124 E WifiHW  : ##################### set firmware type 0 #####################
,09-07 10:32:12.323  7605  7605 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-07 10:32:12.323  1013  1218 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-07 10:32:12.323   256   523 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-07 10:32:12.323   256   523 W Vold    : Returning OperationFailed - no handler for errno 0
,09-07 10:32:12.323  7605  7626 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-07 10:32:12.333   256   523 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-07 10:32:12.333   256   523 W Vold    : Returning OperationFailed - no handler for errno 0
,09-07 10:32:12.333  7605  7626 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-07 10:32:12.353  7605  7605 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-07 10:32:12.353  7605  7627 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-07 10:32:12.633  1013  1026 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-07 10:32:12.633  1013  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:32:12.633  1013  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 10:32:12.633  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-07 10:32:12.653  7605  7605 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,09-07 10:32:12.673  7605  7605 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 7931-7933)
,09-07 10:32:12.673  7605  7605 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-07 10:32:12.683  7605  7605 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2d1a4511}
,09-07 10:32:12.683  7605  7605 I cr.library_loader: Expected native library version number "", actual native library version number ""
09-07 10:32:12.683  7605  7605 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,09-07 10:32:12.703  7605  7605 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,09-07 10:32:12.703  7605  7605 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-07 10:32:12.703  7605  7605 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-07 10:32:12.723  7605  7605 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-07 10:32:12.723  7605  7605 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-07 10:32:12.723  7605  7605 I Adreno-EGL: Build Date: 04/06/15 Mon
09-07 10:32:12.723  7605  7605 I Adreno-EGL: Local Branch: 
09-07 10:32:12.723  7605  7605 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-07 10:32:12.723  7605  7605 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-07 10:32:12.723  7605  7605 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-07 10:32:12.783  7605  7661 W cr.media: Requires BLUETOOTH permission
,09-07 10:32:12.783  1013  1042 D Tethering: interfaceAdded wlan0
,09-07 10:32:12.793  1013  1042 D Tethering: interfaceLinkStateChanged wlan0, false
,09-07 10:32:12.793  1013  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-07 10:32:12.793   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,09-07 10:32:12.803  1013  1128 E Tethering: No numeric data
,09-07 10:32:12.803  1013  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-07 10:32:12.803  1013  1042 D Tethering: interfaceAdded p2p0
,09-07 10:32:12.803  1013  1042 D Tethering: p2p0 is not a tetherable iface, ignoring
,09-07 10:32:12.803  1013  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-07 10:32:12.803  1013  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-07 10:32:12.803  1013  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-07 10:32:12.803  1013  1128 D Tethering: clearTetheredNotification()
09-07 10:32:12.803  1013  1128 D Tethering: InitialState.processMessage what=4
09-07 10:32:12.803  1013  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-07 10:32:12.803   277  1012 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,09-07 10:32:12.803   277  1012 D SoftapController: Softap fwReload - Ok
09-07 10:32:12.803  1013  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 10:32:12.803  1013  1121 V NetworkStats: performPollLocked(flags=0x1)
,09-07 10:32:12.803  7605  7605 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-07 10:32:12.803  1013  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-07 10:32:12.803  1013  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-07 10:32:12.803   277  1012 D CommandListener: Setting iface cfg
09-07 10:32:12.803   277  1012 D CommandListener: Trying to bring down wlan0
,09-07 10:32:12.813   277  1012 D CommandListener: Clearing all IP addresses on wlan0
09-07 10:32:12.813  1013  1128 E Tethering: No numeric data
,09-07 10:32:12.813  1013  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-07 10:32:12.813  1013  1128 D Tethering: clearTetheredNotification()
,09-07 10:32:12.813  1013  1121 V NetworkStats: performPollLocked() took 6ms
09-07 10:32:12.813  1013  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 10:32:12.813  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-07 10:32:12.813  1177  1177 D HotspotTile: updateTetherState():false, false
,09-07 10:32:12.813  1013  1124 E WifiHW  : supplicant_name : p2p_supplicant
09-07 10:32:12.813  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-07 10:32:12.813  1013  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 10:32:12.813  1177  1177 D HotspotTile: updateTetherState():false, false
09-07 10:32:12.813  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 10:32:12.813  1013  1121 V NetworkStats: performPollLocked(flags=0x1)
09-07 10:32:12.813  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 10:32:12.813  1013  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-07 10:32:12.813  1013  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-07 10:32:12.813  1013  1124 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-07 10:32:12.823  7605  7605 I NSApplication: Starting up...
,09-07 10:32:12.823  1013  3832 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-07 10:32:12.823  1013  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 10:32:12.823  1013  1121 V NetworkStats: performPollLocked() took 11ms
,09-07 10:32:12.843  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 10:32:12.843  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 10:32:12.843  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:32:12.843  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-07 10:32:12.843  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-07 10:32:12.843  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-07 10:32:12.843  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:12.843  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-07 10:32:12.843  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:12.843  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:12.843  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:12.843  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-07 10:32:12.843  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,09-07 10:32:12.843  4773  4773 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
09-07 10:32:12.843  1013  1543 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-07 10:32:12.843  1177  1177 D HotspotTile: onReceive : 2, 0
,09-07 10:32:12.853  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:32:12.853  1177  1775 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-07 10:32:12.853  1013  1133 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,09-07 10:32:12.853  1013  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-07 10:32:12.853  1013  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:12.853  1013  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:12.853  1013  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:12.863  7666  7666 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL,
09-07 10:32:12.863  7666  7666 I wpa_supplicant: Successfully initialized wpa_supplicant
09-07 10:32:12.863  7666  7666 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage,
,09-07 10:32:12.873  7668  7668 E Zygote  : MountEmulatedStorage()
,09-07 10:32:12.873  7668  7668 E Zygote  : v2
09-07 10:32:12.873  7668  7668 I libpersona: KNOX_SDCARD checking this for 10117
09-07 10:32:12.873  7668  7668 I libpersona: KNOX_SDCARD not a persona
,09-07 10:32:12.873  7668  7668 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 10:32:12.873  1013  1133 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7668 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
09-07 10:32:12.873  7668  7668 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-07 10:32:12.873  1013  1133 I ActivityManager: Killing 7269:com.android.providers.calendar/u0a37 (adj 15): empty #21
,09-07 10:32:12.873  7668  7668 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-07 10:32:12.883  7666  7666 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,09-07 10:32:12.883   402   402 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7666
09-07 10:32:12.883   402   402 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
09-07 10:32:12.883  7666  7666 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-07 10:32:12.883  7666  7666 I wpa_supplicant: ssSupport state is = 1
09-07 10:32:12.883  7666  7666 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-07 10:32:12.883  7666  7666 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
09-07 10:32:12.883   402   402 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7666
09-07 10:32:12.883   402   402 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,09-07 10:32:12.903  7668  7668 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 10:32:12.903  7668  7668 D ActivityThread: Added TimaKeyStore provider
,09-07 10:32:12.923  7668  7668 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-07 10:32:12.983  5932  5932 D FactoryTest: Not factory mode
,09-07 10:32:12.983  5932  5932 D FactoryTest: Not factory mode. isFactoryMode() returend false
,09-07 10:32:12.983  5932  5932 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,09-07 10:32:12.983  5932  5932 D MTPRx   : still no open session command from host, so toast
,09-07 10:32:12.993  5932  5932 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,09-07 10:32:12.993  5932  5932 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,09-07 10:32:12.993  5932  5932 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:118253
,09-07 10:32:12.993  1013  1496 E PersonaManagerService: inState():  stateMachine is null !!
09-07 10:32:12.993  1013  1496 I PersonaManagerService: PersonaId don't exist
09-07 10:32:12.993  1013  1496 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,09-07 10:32:13.003  1013  1496 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-07 10:32:13.003  1013  1496 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:13.003  1013  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:13.003  1013  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,09-07 10:32:13.003  1013  1496 W ActivityManager: mDVFSHelper.acquire()
,09-07 10:32:13.023  1013  1496 D PersonaManager: isKioskContainerExistOnDevice
,09-07 10:32:13.033  1013  1496 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-07 10:32:13.033  1013  1496 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-07 10:32:13.033  1013  1496 D InputDispatcher: Focused application set to: xxxx
09-07 10:32:13.033  1013  1496 D InputDispatcher: Focus left window: 7071
,09-07 10:32:13.043  5932  5932 E MTPRx   : started activity for popup
,09-07 10:32:13.043  1013  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-07 10:32:13.043  1013  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-07 10:32:13.083  5932  5932 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,09-07 10:32:13.083  5932  5932 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-07 10:32:13.083  5932  5932 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-07 10:32:13.083  5932  5932 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 10:32:13.083  5932  5932 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-07 10:32:13.083  5932  5932 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-07 10:32:13.103   402   402 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,09-07 10:32:13.103  7666  7666 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed,
,09-07 10:32:13.123  5932  5932 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,09-07 10:32:13.123  1013  3832 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-07 10:32:13.123  1013  3832 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-07 10:32:13.123  1013  3832 D InputDispatcher: Focused application set to: xxxx
,09-07 10:32:13.123  1013  3832 D InputDispatcher: Focus entered window: 7071
,09-07 10:32:13.133  1013  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-07 10:32:13.133  1013  1025 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-07 10:32:13.133  1013  1025 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@17508006 attribute=null, token = android.os.BinderProxy@c00f374
,09-07 10:32:13.133  1013  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-07 10:32:13.163  1013  1093 V AlarmManager: waitForAlarm result :4,
,09-07 10:32:13.163  7666  7666 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-07 10:32:13.163  7666  7666 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
09-07 10:32:13.173  7666  7666 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
09-07 10:32:13.173   402   402 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7666
09-07 10:32:13.173   402   402 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-07 10:32:13.173  7666  7666 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-07 10:32:13.173  7666  7666 I wpa_supplicant: ssSupport state is = 1
09-07 10:32:13.173  7666  7666 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-07 10:32:13.173  7666  7666 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-07 10:32:13.173  7666  7666 E wpa_supplicant: SIM READ ERROR,
09-07 10:32:13.173  7666  7666 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-07 10:32:13.173  7666  7666 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-07 10:32:13.173  7666  7666 E wpa_supplicant: SIM READ ERROR
,09-07 10:32:13.173  7666  7666 I wpa_supplicant: Blacklist: Clear (all) 
,09-07 10:32:13.173  7666  7666 I wpa_supplicant: wpa_default_ap_write_once
09-07 10:32:13.173  7666  7666 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-07 10:32:13.173  7666  7666 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-07 10:32:13.173  7666  7666 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-07 10:32:13.173  7666  7666 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-07 10:32:13.173  7666  7666 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-07 10:32:13.183  5932  5932 D SettingsReceiverActivity: dev.kiessupport is : TRUE
09-07 10:32:13.183  7666  7666 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-07 10:32:13.183  1013  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-07 10:32:13.183  1013  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-07 10:32:13.183  1013  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-07 10:32:13.183  5932  5932 D PhoneWindow: *FMB* installDecor mIsFloating : true
09-07 10:32:13.183  5932  5932 D PhoneWindow: *FMB* installDecor flags : 8388610
,09-07 10:32:13.213  7071  7071 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-07 10:32:13.213  7071  7071 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
09-07 10:32:13.213  7071  7071 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-07 10:32:13.213  7071  7071 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,09-07 10:32:13.213  1013  1461 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-07 10:32:13.213  1013  1461 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-07 10:32:13.213  1013  1461 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
09-07 10:32:13.213  1013  1013 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-07 10:32:13.213  1013  1013 D PersonaManagerService: getPersonasForUser(): returning null!
,09-07 10:32:13.223  7071  7071 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-07 10:32:13.223  7071  7071 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-07 10:32:13.233  7071  7071 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@10a411bb time:118491
,09-07 10:32:13.233  7071  7071 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1d6e6da7 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@33998add, 16908290=android.view.AbsSavedState$1@33998add}, android:focusedViewId=100}]}]
09-07 10:32:13.233  7071  7071 V ActivityThread: updateVisibility : ActivityRecord{827da31 token=android.os.BinderProxy@10a411bb {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-07 10:32:13.233  7071  7071 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-07 10:32:13.233  7071  7071 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-07 10:32:13.233  7071  7071 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-07 10:32:13.243  1013  1218 D PersonaManager: isKioskContainerExistOnDevice,
,09-07 10:32:13.253  7666  7666 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,09-07 10:32:13.313  1013  1496 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,09-07 10:32:13.313  1013  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:13.313  1013  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:13.313  1013  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:13.313  1013  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:13.323  7693  7693 E Zygote  : MountEmulatedStorage(),
09-07 10:32:13.323  7693  7693 E Zygote  : v2
,09-07 10:32:13.333  7693  7693 I libpersona: KNOX_SDCARD checking this for 10121
09-07 10:32:13.333  7693  7693 I libpersona: KNOX_SDCARD not a persona
,09-07 10:32:13.333  7693  7693 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-07 10:32:13.333  1013  1496 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7693 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,09-07 10:32:13.333  1013  1496 I ActivityManager: Killing 7225:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,09-07 10:32:13.333  7693  7693 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 10:32:13.333  7693  7693 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 10:32:13.353  7693  7693 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 10:32:13.353  7693  7693 D ActivityThread: Added TimaKeyStore provider,
,09-07 10:32:13.373  7693  7693 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 10:32:13.373  7693  7693 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-07 10:32:13.373  7693  7693 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-07 10:32:13.383  7693  7693 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,09-07 10:32:13.393  7693  7693 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,09-07 10:32:13.393  7693  7693 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,09-07 10:32:13.393  1013  1461 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast,
,09-07 10:32:13.393  1013  1461 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:13.393  1013  1461 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:13.393  1013  1461 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:13.393  1013  1461 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,09-07 10:32:13.403  7666  7666 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-07 10:32:13.413  7666  7666 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-07 10:32:13.413  7710  7710 E Zygote  : MountEmulatedStorage()
09-07 10:32:13.413  7710  7710 I libpersona: KNOX_SDCARD checking this for 10141
,09-07 10:32:13.413  7710  7710 E Zygote  : v2
09-07 10:32:13.413  7710  7710 I libpersona: KNOX_SDCARD not a persona
09-07 10:32:13.413  7710  7710 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 10:32:13.413  7710  7710 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 10:32:13.413  7710  7710 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-07 10:32:13.413  1013  1461 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7710 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,09-07 10:32:13.413  1013  1461 I ActivityManager: Killing 7245:com.android.calendar/u0a131 (adj 15): empty #21
,09-07 10:32:13.433  7666  7666 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,09-07 10:32:13.433   402   402 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7666
09-07 10:32:13.433   402   402 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-07 10:32:13.433  7666  7666 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-07 10:32:13.433  7666  7666 I wpa_supplicant: ssSupport state is = 1
,09-07 10:32:13.433  7666  7666 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-07 10:32:13.433  7666  7666 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-07 10:32:13.443  7666  7666 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
09-07 10:32:13.443   402   402 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7666,
09-07 10:32:13.443   402   402 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,09-07 10:32:13.443  7666  7666 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-07 10:32:13.443  7666  7666 I wpa_supplicant: ssSupport state is = 1
09-07 10:32:13.443  7666  7666 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-07 10:32:13.443  7666  7666 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-07 10:32:13.443  7666  7666 E wpa_supplicant: SIM READ ERROR
09-07 10:32:13.443  7666  7666 I wpa_supplicant: wpa_default_ap_write_once
09-07 10:32:13.443  7666  7666 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-07 10:32:13.443  7666  7666 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-07 10:32:13.443  1013  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-07 10:32:13.443  1013  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-07 10:32:13.443  1013  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-07 10:32:13.443  1013  1042 D Tethering: interfaceLinkStateChanged p2p0, false
,09-07 10:32:13.443  1013  1042 D Tethering: interfaceStatusChanged p2p0, false
09-07 10:32:13.443  1013  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
,09-07 10:32:13.453  7710  7710 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 10:32:13.453  7710  7710 D ActivityThread: Added TimaKeyStore provider
,09-07 10:32:13.463  7710  7710 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,09-07 10:32:13.463  7710  7710 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-07 10:32:13.473  7710  7710 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-07 10:32:13.473  7710  7710 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-07 10:32:13.493  7666  7666 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
09-07 10:32:13.493  7666  7666 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-07 10:32:13.513  1013  1026 D RCPManagerService: exchangeData() failure , invalid userId
,09-07 10:32:13.523  1013  1133 D RCPManagerService: exchangeData() failure , invalid userId
,09-07 10:32:13.553  1013  1481 D RCPManagerService: exchangeData() failure , invalid userId
,09-07 10:32:13.563  1013  3832 D RCPManagerService: exchangeData() failure , invalid userId
09-07 10:32:13.563  7666  7666 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
09-07 10:32:13.563  7666  7666 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-07 10:32:13.563  7666  7666 I wpa_supplicant: Skip scan - bUseNetwork false
,09-07 10:32:13.573  1013  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,09-07 10:32:13.573  1013  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-07 10:32:13.573  7666  7666 I wpa_supplicant: HOTSPOT20_ENABLE called
09-07 10:32:13.573  7666  7666 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-07 10:32:13.573  7666  7666 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-07 10:32:13.573  7666  7666 E wpa_supplicant: SIM READ ERROR
09-07 10:32:13.573  7666  7666 I wpa_supplicant: Blacklist: Clear (all) 
,09-07 10:32:13.583  7666  7666 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,09-07 10:32:13.593  7666  7666 I wpa_supplicant: Skip scan - bUseNetwork false,
,09-07 10:32:13.593  1013  1124 D WifiConfigStore: Loading config and enabling all networks 
,09-07 10:32:13.603  4773  4773 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-07 10:32:13.603  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-07 10:32:13.603  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 10:32:13.603  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-07 10:32:13.603  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 10:32:13.603  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:13.603  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 10:32:13.603  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:13.603  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-07 10:32:13.603  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
09-07 10:32:13.603  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-07 10:32:13.603  1177  1775 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-07 10:32:13.603  1177  1177 D HotspotTile: onReceive : 3, 0
,09-07 10:32:13.603  7071  7071 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 10:32:13.603  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 10:32:13.603  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:13.603  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:13.603  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:32:13.603  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 10:32:13.603  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 10:32:13.603  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 10:32:13.603  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 10:32:13.603  7071  7071 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 10:32:13.603  7071  7071 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 10:32:13.613  7071  7071 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
09-07 10:32:13.613  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 10:32:13.613  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:13.613  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:13.613  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:32:13.613  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
,09-07 10:32:13.613  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 10:32:13.613  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 10:32:13.613  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 10:32:13.613  7071  7071 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 10:32:13.613  7071  7071 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 10:32:13.613  1013  1124 E WifiConfigStore: Not a HS20
,09-07 10:32:13.613  1013  1124 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-07 10:32:13.623  1013  1124 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-07 10:32:13.623  7666  7666 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-07 10:32:13.623  7666  7666 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-07 10:32:13.623  7666  7666 I wpa_supplicant: reset timer : RESET_TIMER 0
09-07 10:32:13.623  7666  7666 I wpa_supplicant: P2P: Current p2p state = IDLE
09-07 10:32:13.623  7666  7666 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-07 10:32:13.623  7666  7666 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-07 10:32:13.623  7666  7666 I wpa_supplicant: First Scan Start
,09-07 10:32:13.623  7666  7666 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-07 10:32:13.623  1013  1124 D WifiNative-wlan0: Setting external_sim to 1
,09-07 10:32:13.623  1013  1124 D WifiStateMachine: Setting OUI to DA-A1-19
09-07 10:32:13.623  1013  1124 I WifiNative-HAL: startHal
09-07 10:32:13.623  1013  1124 E wifi    : getStaticLongField sWifiHalHandle 0x9f36188c
09-07 10:32:13.623  1013  1124 I WifiNative-HAL: Could not start hal
,09-07 10:32:13.623  7390  7390 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 10:32:13.623  1013  1124 E WifiNative-wlan0: do suspend true
,09-07 10:32:13.633  1013  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
09-07 10:32:13.633  1013  1123 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-07 10:32:13.633   277  1012 D CommandListener: Setting iface cfg
09-07 10:32:13.633   277  1012 D CommandListener: Trying to bring up p2p0
,09-07 10:32:13.633  1013  1013 D WifiScanningService: SCAN_AVAILABLE : 3
09-07 10:32:13.633  1013  1123 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-07 10:32:13.633  1013  1124 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-07 10:32:13.633  1013  1124 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-07 10:32:13.633  1013  1124 E WifiNative-wlan0: invaild command id : 215
,09-07 10:32:13.633  1013  1123 D WifiP2pService: P2pEnablingState
09-07 10:32:13.633  1013  1123 D WifiP2pService: P2pEnablingState{ what=147457 }
09-07 10:32:13.633  1013  1149 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:32:13.633  1013  1123 D WifiP2pService: P2p socket connection successful
,09-07 10:32:13.633  1013  1123 D WifiP2pService: P2pEnabledState
09-07 10:32:13.633  1013  1149 I WifiNative-HAL: startHal
,09-07 10:32:13.633  1013  1149 E wifi    : getStaticLongField sWifiHalHandle 0x9e2239bc
09-07 10:32:13.633  1013  1149 I WifiNative-HAL: Could not start hal
09-07 10:32:13.633  1013  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-07 10:32:13.633  1013  1149 E WifiScanningService: could not start HAL
09-07 10:32:13.633  1013  1126 E ConnectivityService: updateNetworkInfo()
,09-07 10:32:13.633  1013  1013 D RttService: SCAN_AVAILABLE : 3
,09-07 10:32:13.633  1013  1150 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-07 10:32:13.633  1013  1481 D RCPManagerService: exchangeData() failure , invalid userId
,09-07 10:32:13.633  7666  7666 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-07 10:32:13.633  1013  1013 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-07 10:32:13.633  1013  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-07 10:32:13.633  1013  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-07 10:32:13.633  1013  1045 D WifiDisplayController: disconnect
09-07 10:32:13.633  1013  1045 D WifiDisplayController: updateConnection
09-07 10:32:13.633  1013  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-07 10:32:13.643  7666  7666 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-07 10:32:13.643  1013  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-07 10:32:13.643  1013  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-07 10:32:13.643  1013  1045 D WifiDisplayAdapter: onP2pDisconnected
09-07 10:32:13.643  1013  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-07 10:32:13.643  1013  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
09-07 10:32:13.643  7666  7666 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
09-07 10:32:13.643  1013  1124 E WifiStateMachine: Failed to set frequency band 0
,09-07 10:32:13.643  1013  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-07 10:32:13.643  1013  1124 D SecContentProvider2: mCursor = null
,09-07 10:32:13.643  1013  1123 D WifiNative-p2p0: p2pGetDeviceAddress
,09-07 10:32:13.643  1013  1133 D RCPManagerService: exchangeData() failure , invalid userId
09-07 10:32:13.643  1013  1123 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,09-07 10:32:13.643  1013  3832 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,09-07 10:32:13.643  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-07 10:32:13.643  1013  1504 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-07 10:32:13.643  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-07 10:32:13.653  1013  3832 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:13.653  1013  3832 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:13.653  1013  3832 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-07 10:32:13.653  1013  3832 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:13.663  7738  7738 E Zygote  : MountEmulatedStorage()
09-07 10:32:13.663  7738  7738 I libpersona: KNOX_SDCARD checking this for 10068
09-07 10:32:13.663  7738  7738 E Zygote  : v2
09-07 10:32:13.663  7738  7738 I libpersona: KNOX_SDCARD not a persona
09-07 10:32:13.663  7738  7738 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 10:32:13.663  1013  3832 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7738 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,09-07 10:32:13.663  7738  7738 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 10:32:13.673  1013  1123 D WifiP2pService: DeviceAddress: 0a:75:42
09-07 10:32:13.663  1013  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-07 10:32:13.673  1013  1045 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
09-07 10:32:13.673  1013  1045 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
09-07 10:32:13.673  1013  1045 D WifiDisplayController:  primary type: 10-0050F204-5
09-07 10:32:13.673  1013  1045 D WifiDisplayController:  secondary type: null
09-07 10:32:13.673  1013  1045 D WifiDisplayController:  wps: 0
09-07 10:32:13.673  1013  1045 D WifiDisplayController:  grpcapab: 0
09-07 10:32:13.673  1013  1045 D WifiDisplayController:  devcapab: 0
09-07 10:32:13.673  1013  1045 D WifiDisplayController:  status: 3
09-07 10:32:13.673  1013  1045 D WifiDisplayController:  wfdInfo: null
09-07 10:32:13.673  1013  1045 D WifiDisplayController:  groupownerAddress: null
09-07 10:32:13.673  1013  1045 D WifiDisplayController:  GOdeviceName: null
09-07 10:32:13.673  1013  1045 D WifiDisplayController:  interfaceAddress: 
09-07 10:32:13.673  1013  1045 D WifiDisplayController:  SConnectInfo : null
09-07 10:32:13.663  1013  1124 D SecContentProvider2: mCursor = null
09-07 10:32:13.673  7738  7738 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-07 10:32:13.693  1013  1123 D WifiP2pService: sending p2p persistent groups changed broadcast
09-07 10:32:13.693  1013  1123 D WifiP2pService: InactiveState
09-07 10:32:13.693  1013  1123 D WifiP2pService: InactiveState{ what=143376 }
,09-07 10:32:13.693  1013  1123 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-07 10:32:13.693  7666  7666 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-07 10:32:13.693  1013  1123 D WifiP2pService: InactiveState{ what=143376 }
09-07 10:32:13.693  1013  1123 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-07 10:32:13.703  1013  1496 D RCPManagerService: exchangeData() failure , invalid userId
,09-07 10:32:13.703  7738  7738 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 10:32:13.703  1013  1026 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,09-07 10:32:13.713  7738  7738 D ActivityThread: Added TimaKeyStore provider
,09-07 10:32:13.713  1013  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:13.713  1013  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:13.713  1013  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:13.713  1013  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:13.723  7753  7753 E Zygote  : MountEmulatedStorage()
,09-07 10:32:13.723  7753  7753 E Zygote  : v2
09-07 10:32:13.723  7753  7753 I libpersona: KNOX_SDCARD checking this for 10009
09-07 10:32:13.723  7753  7753 I libpersona: KNOX_SDCARD not a persona
,09-07 10:32:13.723  7753  7753 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 10:32:13.733  1013  1026 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7753 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,09-07 10:32:13.733  7753  7753 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 10:32:13.733  1013  1026 I ActivityManager: Killing 7207:com.android.defcontainer/u0a3 (adj 15): empty #21
,09-07 10:32:13.733  7753  7753 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
09-07 10:32:13.733  1013  1504 I ActivityManager: Killing 6941:com.android.vending/u0a26 (adj 15): empty #21
,09-07 10:32:13.753   292   292 E SMD     : DCD OFF
09-07 10:32:13.753  7753  7753 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 10:32:13.753  7753  7753 D ActivityThread: Added TimaKeyStore provider
,09-07 10:32:13.783  1013  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-07 10:32:13.783  1013  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-07 10:32:13.783  1013  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-07 10:32:13.793   326   326 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-07 10:32:13.893  1013  1481 I art     : Explicit concurrent mark sweep GC freed 70540(3MB) AllocSpace objects, 12(240KB) LOS objects, 33% free, 23MB/34MB, paused 2.398ms total 151.449ms
,09-07 10:32:13.913  7738  7738 D BadgeProvider: onCreate
,09-07 10:32:13.913  7738  7738 D BadgeProvider: DatabaseHelper
,09-07 10:32:13.933  7738  7751 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,09-07 10:32:13.933  1013  1025 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,09-07 10:32:13.933  1013  1025 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,09-07 10:32:13.943  1013  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,09-07 10:32:13.943  1013  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,09-07 10:32:13.943  7738  7751 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
09-07 10:32:13.943  7738  7751 D BadgeProvider: sendNotify, [notify] : null
09-07 10:32:13.943  7738  7751 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
09-07 10:32:13.943  7738  7751 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-07 10:32:13.943  7738  7751 D BadgeProvider: update, [UpdateCount] : 1
,09-07 10:32:13.943  1488  1488 D Launcher.Model: reloadBadges entered.
,09-07 10:32:13.973  1013  1321 I ActivityManager: Killing 7415:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,09-07 10:32:13.983  1013  1218 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-07 10:32:13.983  1013  1218 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-07 10:32:13.983  1013  1218 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:13.983  1013  1218 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 10:32:13.983  1013  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-07 10:32:13.983  1602  1602 I Hs20UtilService: Starting #11
,09-07 10:32:13.983  1602  1641 I Hs20UtilService: Message received 5011
,09-07 10:32:13.983  7445  7445 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-07 10:32:13.983  7445  7445 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-07 10:32:13.983  7445  7445 D SecurityLogAgent: StateMachine : Current State = 1
09-07 10:32:13.983  7445  7445 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-07 10:32:13.993  1013  1461 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-07 10:32:13.993  1013  1461 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-07 10:32:13.993  1013  1461 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:32:14.003  1013  1461 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:14.003  1013  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-07 10:32:14.003  1602  1602 I Hs20UtilService: Starting #12
,09-07 10:32:14.003  1602  1641 I Hs20UtilService: Message received 5011
,09-07 10:32:14.003  7445  7445 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-07 10:32:14.003  7445  7445 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-07 10:32:14.003  7445  7445 D SecurityLogAgent: StateMachine : Current State = 1
09-07 10:32:14.003  7445  7445 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-07 10:32:14.013  1013  3832 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-07 10:32:14.013  1013  3832 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-07 10:32:14.013  1013  3832 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:32:14.013  1013  3832 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:14.013  1013  3832 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-07 10:32:14.023   277  1008 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
09-07 10:32:14.023   277  1008 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,09-07 10:32:14.023  1602  1602 I Hs20UtilService: Starting #13
,09-07 10:32:14.023  7445  7445 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-07 10:32:14.023  7445  7445 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-07 10:32:14.023  7445  7445 D SecurityLogAgent: StateMachine : Current State = 1
09-07 10:32:14.023  7445  7445 D SecurityLogAgent: StateMachine : Changed Current State = 1
09-07 10:32:14.023  1602  1641 I Hs20UtilService: Message received 5011
,09-07 10:32:14.023  1013  1124 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
,09-07 10:32:14.023  1013  1124 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-07 10:32:14.023  1013  1124 E WifiNative-wlan0: invaild command id : 215
,09-07 10:32:14.033  4773  4773 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-07 10:32:14.033  4773  4773 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-07 10:32:14.033  4773  4773 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-07 10:32:14.043  4773  4773 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-07 10:32:14.043  4773  4773 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-07 10:32:14.043  4773  4773 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-07 10:32:14.043  4773  4865 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-07 10:32:14.043  1013  3832 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-07 10:32:14.043  1013  3832 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.samsung.android.app.FileShareClient/com.samsung.android.app.FileShareClient.ClientBroadcastReceiver}
09-07 10:32:14.043  1013  3832 W BroadcastQueue: android.os.TransactionTooLargeException
09-07 10:32:14.043  1013  3832 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-07 10:32:14.043  1013  3832 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
09-07 10:32:14.043  1013  3832 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
09-07 10:32:14.043  1013  3832 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
09-07 10:32:14.043  1013  3832 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
09-07 10:32:14.043  1013  3832 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
09-07 10:32:14.043  1013  3832 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
09-07 10:32:14.043  1013  3832 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
09-07 10:32:14.043  1013  3832 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,09-07 10:32:14.043  1013  3832 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,09-07 10:32:14.043  1013  3832 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:14.043  1013  3832 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:14.043  1013  3832 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:14.043  1013  3832 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:14.063  7772  7772 E Zygote  : MountEmulatedStorage()
,09-07 10:32:14.063  7772  7772 I libpersona: KNOX_SDCARD checking this for 10064
09-07 10:32:14.063  7772  7772 E Zygote  : v2
09-07 10:32:14.063  7772  7772 I libpersona: KNOX_SDCARD not a persona
09-07 10:32:14.063  7772  7772 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 10:32:14.063  1013  3832 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7772 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-07 10:32:14.063  7772  7772 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 10:32:14.063  7772  7772 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-07 10:32:14.083  7772  7772 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 10:32:14.083  7772  7772 D ActivityThread: Added TimaKeyStore provider
,09-07 10:32:14.093  1013  1039 W libprocessgroup: failed to open /acct/uid_10064/pid_7415/cgroup.procs: No such file or directory
,09-07 10:32:14.093  7772  7772 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-07 10:32:14.103  7772  7772 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-07 10:32:14.103  7772  7772 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-07 10:32:14.133  7772  7772 D FileShare-Client: Outbound.stopDelayTimer - 
,09-07 10:32:14.133  7430  7430 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-07 10:32:14.143  1013  1133 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:32:14.143  1013  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 10:32:14.143  1013  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,09-07 10:32:14.143  1013  1133 I ActivityManager: Killing 7326:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,09-07 10:32:14.823  7666  7666 I wpa_supplicant: nl80211: Received scan results (28 BSSes),
09-07 10:32:14.823  7666  7666 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-07 10:32:14.823  7666  7666 I wpa_supplicant: Trying to associate with SSID '4E47373030'
09-07 10:32:14.823  7666  7666 I wpa_supplicant: Trying to associate with  'G700'
09-07 10:32:14.823  7666  7666 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING,
09-07 10:32:14.823  7666  7666 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030,
,09-07 10:32:14.823  1013  7732 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,09-07 10:32:14.843  1013  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-07 10:32:14.843  1013  1124 D SecContentProvider2: mCursor = null
,09-07 10:32:14.953  7666  7666 E wpa_supplicant: Cmd 35605 not handled
,09-07 10:32:14.953  7666  7666 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-07 10:32:14.953  7666  7666 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,09-07 10:32:14.953  7666  7666 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-07 10:32:14.953  1013  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-07 10:32:14.953  1013  1042 D Tethering: interfaceStatusChanged wlan0, false
09-07 10:32:14.953  7666  7666 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-07 10:32:14.953  7666  7666 I wpa_supplicant: Associated with F4.99.3E
09-07 10:32:14.953  7666  7666 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-07 10:32:14.953  7666  7666 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-07 10:32:14.953  7666  7666 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
09-07 10:32:14.953  1013  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-07 10:32:14.953  1013  1042 D Tethering: interfaceLinkStateChanged wlan0, false
,09-07 10:32:14.953  1013  1042 D Tethering: interfaceStatusChanged wlan0, false
09-07 10:32:14.953  1013  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-07 10:32:14.953  1013  1042 D Tethering: interfaceLinkStateChanged wlan0, false
,09-07 10:32:14.953  1013  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-07 10:32:14.953  1013  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-07 10:32:14.953  1013  1042 D Tethering: interfaceLinkStateChanged wlan0, true
,09-07 10:32:14.953  1013  1042 D Tethering: interfaceStatusChanged wlan0, true
,09-07 10:32:14.953  1013  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-07 10:32:14.953  1013  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-07 10:32:14.953  1013  1124 D SecContentProvider2: mCursor = null
,09-07 10:32:14.953  7666  7666 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-07 10:32:14.953  7666  7666 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
09-07 10:32:14.953  1013  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-07 10:32:14.953  1013  1124 D SecContentProvider2: mCursor = null
09-07 10:32:14.953  1013  1128 E Tethering: No numeric data
09-07 10:32:14.953  7666  7666 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
09-07 10:32:14.953  7666  7666 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,09-07 10:32:14.953  7666  7666 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-07 10:32:14.953  7666  7666 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-07 10:32:14.953  7666  7666 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-07 10:32:14.953  1013  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-07 10:32:14.953  1013  1128 D Tethering: clearTetheredNotification()
09-07 10:32:14.953  7666  7666 I wpa_supplicant: Blacklist: Clear (temp) 
09-07 10:32:14.953  7666  7666 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,09-07 10:32:14.953  1013  1042 D Tethering: interfaceLinkStateChanged wlan0, true
09-07 10:32:14.953  1013  1042 D Tethering: interfaceStatusChanged wlan0, true
09-07 10:32:14.953  1013  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,09-07 10:32:14.953  1013  1121 V NetworkStats: performPollLocked(flags=0x1)
09-07 10:32:14.953  1013  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 10:32:14.953  1013  1124 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-07 10:32:14.963  1013  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-07 10:32:14.963  1013  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-07 10:32:14.963  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-07 10:32:14.963  1013  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 10:32:14.963  1013  1121 V NetworkStats: performPollLocked() took 3ms
,09-07 10:32:14.963  1177  1177 D HotspotTile: updateTetherState():false, false
,09-07 10:32:14.963  1013  1124 E WifiConfigStore: setLastSelectedConfiguration -1,
,09-07 10:32:14.973  1013  1126 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false,
09-07 10:32:14.973  1013  1124 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-07 10:32:14.973  1013  1126 E ConnectivityService: updateNetworkInfo()
09-07 10:32:14.973  1013  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 10:32:14.973  1013  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 10:32:14.973  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 10:32:14.973  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 10:32:14.973  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-07 10:32:14.973  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-07 10:32:14.973  1013  1461 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-07 10:32:14.973  1013  1461 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-07 10:32:14.973  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-07 10:32:14.973  1013  1461 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:32:14.973  1013  1461 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:14.973  1013  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-07 10:32:14.973  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:14.973  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:14.973  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:14.973  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 10:32:14.973  1602  1602 I Hs20UtilService: Starting #14
,09-07 10:32:14.983  1602  1641 I Hs20UtilService: Message received 5007
,09-07 10:32:14.983  1013  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 10:32:14.983  4773  4773 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-07 10:32:14.983  4773  4773 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-07 10:32:14.983  4773  4773 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-07 10:32:14.983  4773  4773 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-07 10:32:14.983  4773  4773 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-07 10:32:14.983  4773  4773 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-07 10:32:14.983  4773  4865 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-07 10:32:14.993   277  1012 D CommandListener: Setting iface cfg,
,09-07 10:32:14.993  1013  1124 E WifiStateMachine: Start Dhcp Watchdog 2
,09-07 10:32:14.993  1013  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-07 10:32:14.993  1013  1124 D SecContentProvider2: mCursor = null
,09-07 10:32:15.003  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-07 10:32:15.003  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 10:32:15.013  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-07 10:32:15.013  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 10:32:15.013  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:15.013  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:15.013  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 10:32:15.013  1013  1124 E WifiNative-wlan0: do suspend false
,09-07 10:32:15.013  1013  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-07 10:32:15.013  1013  1124 D SecContentProvider2: mCursor = null
09-07 10:32:15.013  1013  1123 D WifiP2pService: InactiveState{ what=143375 }
09-07 10:32:15.013  1013  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-07 10:32:15.233  7789  7789 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-07 10:32:15.233  7789  7789 I dhcpcd  : version 5.5.6 starting,
,09-07 10:32:15.243  7789  7789 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-07 10:32:15.293  7789  7789 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
09-07 10:32:15.293  7789  7789 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-07 10:32:15.293  7789  7789 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,09-07 10:32:15.303  7789  7789 I dhcpcd  : bssid match
,09-07 10:32:15.303  7789  7789 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116,
,09-07 10:32:15.323  1013  1504 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-07 10:32:15.323  1013  1504 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-07 10:32:15.323  1013  1504 D SecContentProvider2: mCursor = null
,09-07 10:32:15.323  1013  1504 D WifiService: setWifiEnabled: false pid=7071, uid=10170
,09-07 10:32:15.323  1013  1504 D SettingsProvider: name = wifi_on
,09-07 10:32:15.333  1013  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 10:32:15.343  1013  1124 E WifiNative-wlan0: do suspend true,
,09-07 10:32:15.353  7789  7789 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1,
09-07 10:32:15.353  7789  7789 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds
,09-07 10:32:15.363  1013  1123 D WifiP2pService: InactiveState{ what=143375 },
09-07 10:32:15.363  1013  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-07 10:32:15.373   277  1012 D CommandListener: Clearing all IP addresses on wlan0,
,09-07 10:32:15.373  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-07 10:32:15.373  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 10:32:15.373  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-07 10:32:15.373  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:15.373  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:15.373  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:15.373  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 10:32:15.373  1013  1126 E ConnectivityService: updateNetworkInfo(),
09-07 10:32:15.373  1013  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 10:32:15.383  1013  1126 E ConnectivityService: updateNetworkInfo()
09-07 10:32:15.383  1013  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
09-07 10:32:15.383   277  1012 E Netd    : no such netId 503,
,09-07 10:32:15.383  1013  1124 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-07 10:32:15.383  1013  1123 D WifiP2pService: InactiveState{ what=131204 }
,09-07 10:32:15.383  1013  1123 D WifiP2pService: P2pEnabledState{ what=131204 }
09-07 10:32:15.383  1013  1013 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-07 10:32:15.383  1013  1123 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,09-07 10:32:15.393  1013  1126 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '79 network destroy 503' failed with '400 79 destroyNetwork() failed (Machine is not on the network)',
09-07 10:32:15.393  1013  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 10:32:15.393  1013  1126 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
09-07 10:32:15.393  1013  1126 V NetworkStats: updateIfacesLocked()
09-07 10:32:15.393  1013  1126 V NetworkStats: performPollLocked(flags=0x1)
09-07 10:32:15.393  1013  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
09-07 10:32:15.393  1013  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-07 10:32:15.393  1013  1013 D WifiScanningService: SCAN_AVAILABLE : 1
09-07 10:32:15.393  1013  1126 V NetworkStats: performPollLocked() took 5ms
09-07 10:32:15.393  1013  1149 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:32:15.393  1013  1013 D RttService: SCAN_AVAILABLE : 1
09-07 10:32:15.393  1013  1150 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:32:15.393  1013  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 10:32:15.393  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-07 10:32:15.403  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 10:32:15.403  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-07 10:32:15.403  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:15.403  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:15.403  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:15.403  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 10:32:15.403  1013  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 10:32:15.403  1013  1045 D WifiDisplayAdapter: onP2pDisconnected
09-07 10:32:15.403  1013  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-07 10:32:15.403  1013  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-07 10:32:15.413  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 10:32:15.413  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 10:32:15.413  1013  1461 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-07 10:32:15.413  1013  1461 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-07 10:32:15.413  1013  1126 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
,09-07 10:32:15.413  1013  1461 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:15.413  1013  1126 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-07 10:32:15.413  1013  1461 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:15.413  1013  7787 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:32:15.413  1013  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-07 10:32:15.413  1013  7787 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-07 10:32:15.413  1013  1126 D ConnectivityService: nai.networkMonitor.doQuit()
09-07 10:32:15.413  1013  1126 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-07 10:32:15.413  1013  1126 E ConnectivityService: updateNetworkInfo()
09-07 10:32:15.413  1602  1602 I Hs20UtilService: Starting #15
09-07 10:32:15.413  1602  1641 I Hs20UtilService: Message received 5007
09-07 10:32:15.413  1013  1013 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-07 10:32:15.413  1013  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,09-07 10:32:15.413  1013  1126 E ConnectivityService: updateNetworkInfo()
09-07 10:32:15.413  1013  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-07 10:32:15.413  1013  1045 D WifiDisplayController: disconnect
09-07 10:32:15.413  1013  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-07 10:32:15.413  1013  1045 D WifiDisplayController: updateConnection
09-07 10:32:15.413  1013  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-07 10:32:15.413  1013  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-07 10:32:15.423  4773  4773 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-07 10:32:15.423  4773  4773 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-07 10:32:15.423  1013  1123 D WifiP2pService: P2pDisablingState
09-07 10:32:15.423  1013  1123 D WifiP2pService: P2pDisablingState{ what=147458 }
09-07 10:32:15.423  1013  1123 D WifiP2pService: p2p socket connection lost
,09-07 10:32:15.423  1013  1123 D WifiP2pService: P2pDisabledState
09-07 10:32:15.423  1013  1124 E WifiNative-wlan0: do suspend true
,09-07 10:32:15.433  1013  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-07 10:32:15.433  1013  1045 D WifiDisplayAdapter: onP2pDisconnected
09-07 10:32:15.433  1013  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-07 10:32:15.433  1013  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
09-07 10:32:15.433  4773  4773 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-07 10:32:15.433  4773  4773 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-07 10:32:15.433  4773  4773 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-07 10:32:15.433  4773  4773 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-07 10:32:15.433  4773  4865 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-07 10:32:15.433  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED,
09-07 10:32:15.433  1013  1026 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-07 10:32:15.433  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-07 10:32:15.443  4773  4773 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-07 10:32:15.443  4773  4773 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-07 10:32:15.443  4773  4773 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-07 10:32:15.453  4773  4773 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-07 10:32:15.453  4773  4773 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-07 10:32:15.453  4773  4773 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-07 10:32:15.453  4773  4865 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-07 10:32:15.463  7772  7772 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-07 10:32:15.463  7772  7772 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-07 10:32:15.463  7772  7772 D FileShare-Client: Outbound.stopDelayTimer - 
09-07 10:32:15.463  1013  1123 D WifiP2pService: P2pDisabledState{ what=143375 }
09-07 10:32:15.463  1013  1123 D WifiP2pService: DefaultState{ what=143375 }
,09-07 10:32:15.463  7430  7430 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-07 10:32:15.463   277  1012 D CommandListener: Clearing all IP addresses on wlan0
,09-07 10:32:15.473  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
09-07 10:32:15.473  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 10:32:15.473  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-07 10:32:15.473  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:15.473  1013  1013 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-07 10:32:15.473  7666  7666 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-07 10:32:15.483  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:15.483  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:15.483  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 10:32:15.493  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-07 10:32:15.493  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 10:32:15.493  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-07 10:32:15.493  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:15.493  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:15.493  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:15.493  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 10:32:15.493  1013  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-07 10:32:15.493  1013  1124 D SecContentProvider2: mCursor = null
,09-07 10:32:15.503  4773  4773 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-07 10:32:15.503  1013  1025 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-07 10:32:15.503  1013  1025 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2,
,09-07 10:32:15.503  7071  7071 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 10:32:15.503  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 10:32:15.503  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:15.503  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:15.503  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 10:32:15.503  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 10:32:15.503  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 10:32:15.503  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 10:32:15.503  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 10:32:15.503  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:15.503  1013  1025 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:15.503  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-07 10:32:15.503  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-07 10:32:15.503  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 10:32:15.503  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-07 10:32:15.503  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:15.513  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 10:32:15.513  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:15.513  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:15.513  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-07 10:32:15.513  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
09-07 10:32:15.513  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-07 10:32:15.513  1602  1602 I Hs20UtilService: Starting #16
09-07 10:32:15.513  1177  1775 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-07 10:32:15.513  1177  1177 D HotspotTile: onReceive : 0, 0
,09-07 10:32:15.513  7071  7071 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 10:32:15.513  7071  7071 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 10:32:15.513  7071  7071 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 10:32:15.513  4773  4773 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-07 10:32:15.513  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 10:32:15.513  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:15.513  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:15.513  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 10:32:15.513  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 10:32:15.513  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 10:32:15.513  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 10:32:15.513  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 10:32:15.513  4773  4773 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-07 10:32:15.513  7071  7071 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 10:32:15.523  7071  7071 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 10:32:15.523  4773  4773 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-07 10:32:15.523  4773  4773 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-07 10:32:15.523  4773  4773 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-07 10:32:15.523  4773  4773 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-07 10:32:15.523  4773  4865 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-07 10:32:15.523  1602  1641 I Hs20UtilService: Message received 5007
,09-07 10:32:15.533  1013  3832 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-07 10:32:15.533  1013  3832 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2,
09-07 10:32:15.533  1013  3832 W ActivityManager: userId = 0, bbcId = -10000,
09-07 10:32:15.533  1013  3832 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:15.533  1013  3832 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-07 10:32:15.533  1602  1602 I Hs20UtilService: Starting #17,
,09-07 10:32:15.533  1602  1641 I Hs20UtilService: Message received 5011
,09-07 10:32:15.543  7445  7445 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-07 10:32:15.543  7445  7445 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-07 10:32:15.543  7445  7445 D SecurityLogAgent: StateMachine : Current State = 1
09-07 10:32:15.543  7445  7445 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-07 10:32:15.613  7666  7666 I wpa_supplicant: Blacklist: Clear (all) 
,09-07 10:32:15.683  7666  7666 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING ,
09-07 10:32:15.683  1013  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-07 10:32:15.683  1013  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-07 10:32:15.683  1013  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-07 10:32:15.703  1013  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
,09-07 10:32:15.703  1013  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
,09-07 10:32:15.703  1013  1042 D Tethering: interfaceStatusChanged wlan0, false,
,09-07 10:32:15.713  1013  1121 V NetworkStats: performPollLocked(flags=0x1)
,09-07 10:32:15.703  1013  1128 D Tethering: InitialState.processMessage what=4,
09-07 10:32:15.713  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-07 10:32:15.713  1013  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-07 10:32:15.713  1177  1177 D HotspotTile: updateTetherState():false, false
09-07 10:32:15.713  1013  1042 D Tethering: interfaceStatusChanged wlan0, false
09-07 10:32:15.713  1013  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-07 10:32:15.713  7666  7666 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
09-07 10:32:15.723  1013  1121 V NetworkStats: performPollLocked() took 8ms
09-07 10:32:15.713  1013  1128 E Tethering: No numeric data
09-07 10:32:15.723  1013  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-07 10:32:15.713  1013  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-07 10:32:15.713  1013  1128 D Tethering: clearTetheredNotification()
09-07 10:32:15.713  1013  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 10:32:15.713  1013  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-07 10:32:15.713  1013  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-07 10:32:15.713  7666  7666 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-07 10:32:15.713  7666  7666 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-07 10:32:15.723  7666  7666 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-07 10:32:15.723  7666  7666 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
09-07 10:32:15.723  1013  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 10:32:15.723  1013  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-07 10:32:15.723  1013  1042 D Tethering: interfaceStatusChanged wlan0, false
09-07 10:32:15.723  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 10:32:15.723  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 10:32:15.943  1013  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
09-07 10:32:15.943  1013  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-07 10:32:15.943  1013  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-07 10:32:16.003  1013  1040 W ActivityManager: mDVFSHelper.release(),
,09-07 10:32:16.013  7666  7666 I wpa_supplicant: Blacklist: Clear (all) ,
,09-07 10:32:16.113  1013  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
09-07 10:32:16.113  1013  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-07 10:32:16.113  1013  1042 D Tethering: interfaceStatusChanged wlan0, false,
,09-07 10:32:16.123  7666  7666 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
,09-07 10:32:16.223  1013  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0,
,09-07 10:32:16.223  1013  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-07 10:32:16.233  7390  7390 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 10:32:16.243  1747  2186 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 10:32:16.243  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-07 10:32:16.243  4773  4773 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-07 10:32:16.243  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-07 10:32:16.243  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,09-07 10:32:16.243  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 10:32:16.243  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 10:32:16.243  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:16.243  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 10:32:16.243  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-07 10:32:16.243  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
09-07 10:32:16.243  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-07 10:32:16.243  1177  1775 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-07 10:32:16.253  1177  1177 D HotspotTile: onReceive : 1, 0
,09-07 10:32:16.253  1013  1461 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-07 10:32:16.253  1013  1461 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-07 10:32:16.253  1013  1461 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:16.253  1013  1461 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:16.253  1013  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-07 10:32:16.253  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-07 10:32:16.253  1602  1602 I Hs20UtilService: Starting #18
,09-07 10:32:16.253  1602  1641 I Hs20UtilService: Message received 5011,
09-07 10:32:16.253  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:16.263  7445  7445 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-07 10:32:16.263  7445  7445 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-07 10:32:16.263  7445  7445 D SecurityLogAgent: StateMachine : Current State = 1
09-07 10:32:16.263  7445  7445 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-07 10:32:16.753   292   292 E SMD     : DCD OFF
,09-07 10:32:17.063  1013  1042 D Tethering: interfaceRemoved wlan0
,09-07 10:32:17.063  1013  1042 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-07 10:32:17.213  1013  1042 D Tethering: interfaceRemoved p2p0,
09-07 10:32:17.213  1013  1042 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-07 10:32:17.373  1013  3386 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-07 10:32:17.873  1013  3365 D SSRM:n  : SIOP:: AP = 330
,09-07 10:32:18.033  1013  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-07 10:32:18.333  7071  7301 D BluetoothAdapter: enable(),
,09-07 10:32:18.333  1013  1504 W ActivityManager: Permission Denial: getCurrentUser() from pid=7071, uid=10170 requires android.permission.INTERACT_ACROSS_USERS,
,09-07 10:32:18.343  1013  1504 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-07 10:32:18.343  1013  1504 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7071, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-07 10:32:18.343  1013  1504 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-07 10:32:18.343  1013  1504 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
09-07 10:32:18.343  1013  1504 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
09-07 10:32:18.343  1013  1504 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
09-07 10:32:18.343  1013  1504 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
09-07 10:32:18.343  1013  1504 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-07 10:32:18.343  1013  1504 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-07 10:32:18.343  1013  1504 D SettingsProvider: name = bluetooth_on,
,09-07 10:32:18.343  1013  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
09-07 10:32:18.343  1013  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-07 10:32:18.353  1013  1044 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
09-07 10:32:18.353  3222  3295 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,09-07 10:32:18.353  3222  3295 D BluetoothAdapterProperties: Setting state to 11
09-07 10:32:18.353  3222  3295 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-07 10:32:18.353  3222  3295 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-07 10:32:18.353  3222  3295 D BluetoothAdapterService: updateAdapterState state is 11
09-07 10:32:18.353  3222  3295 D BluetoothAdapterService: Autoconnection is available 
09-07 10:32:18.353  3222  3295 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
09-07 10:32:18.353  3222  3295 D BtConfig.SecureMode: isSecureModeOn:false
09-07 10:32:18.353  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-07 10:32:18.353  3222  3295 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
09-07 10:32:18.353  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-07 10:32:18.353  3222  3295 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
09-07 10:32:18.353  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-07 10:32:18.353  3222  3295 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
,09-07 10:32:18.353  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-07 10:32:18.353  3222  3295 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
09-07 10:32:18.353  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-07 10:32:18.353  3222  3295 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
09-07 10:32:18.353  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-07 10:32:18.353  3222  3295 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
09-07 10:32:18.353  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-07 10:32:18.353  3222  3295 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10,
09-07 10:32:18.353  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-07 10:32:18.353  3222  3295 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
09-07 10:32:18.353  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-07 10:32:18.353  3222  3295 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-07 10:32:18.353  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-07 10:32:18.353  3222  3295 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-07 10:32:18.353  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-07 10:32:18.353  3222  3295 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-07 10:32:18.353  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-07 10:32:18.353  3222  3295 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
09-07 10:32:18.353  3222  3295 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
09-07 10:32:18.353  3222  3295 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
09-07 10:32:18.353  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-07 10:32:18.353  3222  3295 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
09-07 10:32:18.363  1013  1013 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-07 10:32:18.363  1013  1013 I InputMethodManagerService: [BT Setting State] State =11
,09-07 10:32:18.383  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-07 10:32:18.383  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:32:18.383  1177  1177 D BluetoothTile:  getBluetoothState : 11
,09-07 10:32:18.383  1899  1899 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-07 10:32:18.383  4773  4773 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-07 10:32:18.393  1013  1461 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-07 10:32:18.393  1013  1026 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-07 10:32:18.393  1013  1461 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
09-07 10:32:18.393  1013  1496 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-07 10:32:18.393  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-07 10:32:18.393  1013  1461 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:18.393  1013  1461 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:18.393  1013  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:18.393  1177  1775 D BluetoothTile:  handleUpdatestate:false name:null
,09-07 10:32:18.393  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:18.393  1177  1775 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-07 10:32:18.393  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:18.403  3222  3295 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
09-07 10:32:18.403  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-07 10:32:18.403  3222  3295 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-07 10:32:18.403  3222  3222 D HeadsetService: Received start request. Starting profile...
,09-07 10:32:18.403  3222  3222 D HeadsetService: start()
09-07 10:32:18.403  3222  3222 D HeadsetStateMachine: make
,09-07 10:32:18.403  1013  3832 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 10:32:18.413  1013  3832 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-07 10:32:18.413  1013  3832 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:18.413  1013  3832 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:18.413  1013  3832 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:18.413  2645  2645 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 10:32:18.413  3222  3222 E HeadsetStateMachine: # of Max HF connection is 2
,09-07 10:32:18.413  3222  3295 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
09-07 10:32:18.413  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-07 10:32:18.413  3222  3295 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-07 10:32:18.413  4773  4773 D BluetoothNotiBroadcastReceiver: onReceive
,09-07 10:32:18.423  1013  1133 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-07 10:32:18.423  1013  1133 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-07 10:32:18.423  1013  1133 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:32:18.423  1013  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:18.423  1013  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:18.423  1013  1479 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,09-07 10:32:18.423  1013  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-07 10:32:18.423  1013  1479 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:32:18.423  1013  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:18.423  1013  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-07 10:32:18.423  3222  3295 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
09-07 10:32:18.423  1013  1461 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 10:32:18.423  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-07 10:32:18.423  1013  1461 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
09-07 10:32:18.423  3222  3295 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-07 10:32:18.433  1013  1461 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:32:18.433  1013  1461 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:18.433  1013  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:18.433  3222  3295 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,09-07 10:32:18.433  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-07 10:32:18.433  3222  3295 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-07 10:32:18.433  1013  1218 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-07 10:32:18.433  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:32:18.433  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-07 10:32:18.433  1013  1218 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-07 10:32:18.433  1013  1218 W ActivityManager: userId = 0, bbcId = -10000,
09-07 10:32:18.433  1013  1218 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:18.433  1013  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:18.433  3222  3295 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService,
09-07 10:32:18.433  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-07 10:32:18.433  3222  3295 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-07 10:32:18.443  1013  1504 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,09-07 10:32:18.443  1013  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-07 10:32:18.443  1013  1504 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:18.443  1013  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:18.443  1013  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
09-07 10:32:18.443  1013  1025 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 10:32:18.443  1013  1025 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-07 10:32:18.443  3222  3222 I bluedroid: get_profile_interface handsfree
09-07 10:32:18.443  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:18.443  1013  1025 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:18.443  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:18.443  3222  3295 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
09-07 10:32:18.443  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-07 10:32:18.443  3222  3295 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-07 10:32:18.443  1013  3832 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-07 10:32:18.443  1013  3832 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:18.443  1013  3832 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:18.443  1013  3832 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:18.443  1013  3832 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:18.463  7822  7822 E Zygote  : MountEmulatedStorage()
,09-07 10:32:18.463  7822  7822 E Zygote  : v2
09-07 10:32:18.463  7822  7822 I libpersona: KNOX_SDCARD checking this for 10055
09-07 10:32:18.463  7822  7822 I libpersona: KNOX_SDCARD not a persona
,09-07 10:32:18.463  7822  7822 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-07 10:32:18.463  1013  3832 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7822 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
09-07 10:32:18.463  1013  1479 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 10:32:18.463  1013  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
09-07 10:32:18.463  1013  1479 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:18.463  1013  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:18.463  1013  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:18.473  3222  3295 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-07 10:32:18.473  7822  7822 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-07 10:32:18.473  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-07 10:32:18.473  3222  3295 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-07 10:32:18.473  3222  3295 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService,
09-07 10:32:18.473  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-07 10:32:18.473  3222  3295 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-07 10:32:18.473  3222  3295 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
09-07 10:32:18.473  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService,
09-07 10:32:18.473  3222  3295 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,09-07 10:32:18.473  3222  3295 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
09-07 10:32:18.473  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-07 10:32:18.473  3222  3295 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-07 10:32:18.473  3222  3295 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-07 10:32:18.473  7822  7822 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 10:32:18.483  3222  3222 E DualScoManager: Dual Sco Manager already instantiated
09-07 10:32:18.483  3222  3222 I DualScoManager: Set HeadsetServiceHelper
09-07 10:32:18.483  3222  3222 D BluetoothAtMessage: createCMTIContentObservers
09-07 10:32:18.483  1013  1133 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
09-07 10:32:18.483  1013  1133 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 10:32:18.483  1013  1133 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 10:32:18.483  1013  1133 D SettingsProvider: selectionArgs: false
09-07 10:32:18.483  1013  1133 D SettingsProvider: selectionArgs: 1002
09-07 10:32:18.483  1013  1133 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 10:32:18.483  1013  1133 D SettingsProvider: ret = -1
09-07 10:32:18.483  3222  7821 D HeadsetStateMachine: Enter Disconnected: -2
,09-07 10:32:18.483  3222  3222 D HeadsetService: mStartError = false
09-07 10:32:18.483  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2acc5f51
09-07 10:32:18.483  3222  3222 D A2dpService: Received start request. Starting profile...
09-07 10:32:18.483  3222  3222 D A2dpService: start()
09-07 10:32:18.483  3222  3222 I bluedroid: get_profile_interface avrcp
,09-07 10:32:18.483  3222  7821 D HeadsetStateMachine: Clear mHeadsetBrsf
09-07 10:32:18.483  3222  7821 D HeadsetStateMachine: map size, before remove : 0
09-07 10:32:18.483  3222  7821 D HeadsetStateMachine: map size, after remove: 0
,09-07 10:32:18.493  3222  3222 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-07 10:32:18.493  3222  3222 D Avrcp   : Initialize Media Controller
09-07 10:32:18.493  3222  3222 D Avrcp   : Get the Context Package Name: com.android.bluetooth
09-07 10:32:18.493  3222  3222 E Avrcp   : getActiveSessions
09-07 10:32:18.493  3222  3222 D Avrcp   : pick active media Controller
09-07 10:32:18.493  3222  3222 D Avrcp   : Get the active Media Controller 
,09-07 10:32:18.493  3222  3222 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-07 10:32:18.493  3222  7831 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-07 10:32:18.493  3222  3222 D A2dpStateMachine: make
,09-07 10:32:18.503  7822  7822 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 10:32:18.503  7822  7822 D ActivityThread: Added TimaKeyStore provider
,09-07 10:32:18.513  3222  3222 I bluedroid: get_profile_interface a2dp
,09-07 10:32:18.513  3222  7839 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-07 10:32:18.513  3222  3222 E bt-btif : warning : media task started media_task_refcnt 1 
,09-07 10:32:18.513  3222  3222 D A2dpService: mStartError = false
09-07 10:32:18.513  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2acc5f51
09-07 10:32:18.513  3222  7837 D A2dpStateMachine: Enter Disconnected: -2
,09-07 10:32:18.513  3222  3222 D HidService: Received start request. Starting profile...
09-07 10:32:18.513  3222  3222 D HidService: start()
09-07 10:32:18.513  3222  3222 I bluedroid: get_profile_interface hidhost
09-07 10:32:18.513  3222  3222 D HidService: setHidService(): set to: null
09-07 10:32:18.513  3222  3222 D HidService: mStartError = false
09-07 10:32:18.513  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2acc5f51
09-07 10:32:18.513  3222  3222 D HeadsetStateMachine: Try to query the phonestate on bind
,09-07 10:32:18.523  1434  7343 I Telecom : BluetoothPhoneService: queryPhoneState
,09-07 10:32:18.523  1434  1434 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
09-07 10:32:18.523  1434  1434 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-07 10:32:18.523  1434  7343 I Telecom : BluetoothPhoneService: Result of Message : true
,09-07 10:32:18.523  3222  7831 D BluetoothMediaBrowser: no now playing list
09-07 10:32:18.523  3222  3222 D HealthService: Received start request. Starting profile...
09-07 10:32:18.523  3222  3222 D HealthService: start()
09-07 10:32:18.523  3222  7831 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
09-07 10:32:18.523  3222  3222 I bluedroid: get_profile_interface health
09-07 10:32:18.523  3222  3222 D HealthService: mStartError = false
09-07 10:32:18.523  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2acc5f51
09-07 10:32:18.523  3222  3222 D PanService: Received start request. Starting profile...
09-07 10:32:18.523  3222  3222 D PanService: start()
09-07 10:32:18.523  3222  3222 D BluetoothPanServiceJni: initializeNative(L110): pan
09-07 10:32:18.523  3222  3222 I bluedroid: get_profile_interface pan
09-07 10:32:18.523  3222  3222 D PanService: mStartError = false
09-07 10:32:18.523  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2acc5f51
09-07 10:32:18.523  3222  3222 D HeadsetStateMachine: Proxy object connected
09-07 10:32:18.523  3222  3222 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
09-07 10:32:18.523  3222  7821 D HeadsetStateMachine: Disconnected process message: 11
09-07 10:32:18.523  3222  3222 D BluetoothMapService: Received start request. Starting profile...
09-07 10:32:18.523  3222  3222 D BluetoothMapService: start()
09-07 10:32:18.523  3222  3222 D BluetoothMapService: mStartError = false
09-07 10:32:18.523  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2acc5f51
,09-07 10:32:18.533  3222  3222 D SapService: Received start request. Starting profile...
09-07 10:32:18.533  3222  3222 D SapService: start()
09-07 10:32:18.533  3222  3222 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-07 10:32:18.533  3222  3222 I bluedroid: get_profile_interface sap
09-07 10:32:18.533  3222  3222 D SapService: mStartError = false
,09-07 10:32:18.533  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2acc5f51
,09-07 10:32:18.533  3222  3222 D HeadsetPhoneState: sendDeviceDataStateChanged
09-07 10:32:18.533  3222  3222 D HeadsetPhoneState: Signal level : previous=0 curr=4
,09-07 10:32:18.533  3222  3222 E BluetoothAdapterService(718036817): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-07 10:32:18.533  3222  7821 D HeadsetStateMachine: Disconnected process message: 18
,09-07 10:32:18.533  3222  3222 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-07 10:32:18.533  3222  3222 E BluetoothAdapterService(718036817): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-07 10:32:18.533  3222  3222 E BluetoothAdapterService(718036817): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,09-07 10:32:18.533  3222  7821 D HeadsetStateMachine: Disconnected process message: 10
09-07 10:32:18.533  3222  7821 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-07 10:32:18.533  3222  7821 D HeadsetStateMachine: Disconnected process message: 11
,09-07 10:32:18.533  3222  3222 E BluetoothAdapterService(718036817): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,09-07 10:32:18.533  3222  3222 E BluetoothAdapterService(718036817): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-07 10:32:18.543  7822  7822 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-07 10:32:18.553  3222  3222 E BluetoothAdapterService(718036817): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
09-07 10:32:18.553  3222  3222 E BluetoothAdapterService(718036817): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-07 10:32:18.553  3222  3295 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,09-07 10:32:18.553  3222  3295 I bluedroid: enable
,09-07 10:32:18.563  3222  3298 E bt-btif : Calling BTA_HhEnable
,09-07 10:32:18.563  3222  3298 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,09-07 10:32:18.563  3222  3298 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,09-07 10:32:18.563  3222  3298 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-07 10:32:18.563  3222  3298 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
09-07 10:32:18.563  3222  3298 E BluetoothServiceJni: populateRssiValuesNative
,09-07 10:32:18.563  3222  3298 I bluedroid: getModelRssiValues
,09-07 10:32:18.563  3222  3298 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-07 10:32:18.563  3222  3298 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-07 10:32:18.563  1013  1013 D SettingsProvider: name = bluetooth_name
,09-07 10:32:18.563  3222  3298 D BluetoothAdapterProperties: Name is: Galaxy A3
,09-07 10:32:18.573  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:18.573  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 10:32:18.573  7822  7822 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,09-07 10:32:18.573  7822  7822 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-07 10:32:18.573  7822  7822 D UserAnalysis: Create SecureDbHelper
,09-07 10:32:18.573  3222  3298 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-07 10:32:18.573  3222  3298 D BluetoothAdapterProperties: Scan Mode:20
09-07 10:32:18.573  3222  3298 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-07 10:32:18.573  3222  3298 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
,09-07 10:32:18.583  3222  3298 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
09-07 10:32:18.583  3222  3298 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
09-07 10:32:18.583  3222  3298 E bt-btif : btif_sock_init: !radio_req && !rfc_init
09-07 10:32:18.583  3222  3298 E bt-btif : JVenable fails
,09-07 10:32:18.583  3222  3298 D bte_conf: Device ID record 1 : primary
09-07 10:32:18.583  3222  3298 D bte_conf:   vendorId            = 0075
09-07 10:32:18.583  3222  3298 D bte_conf:   vendorIdSource      = 0001
09-07 10:32:18.583  3222  3298 D bte_conf:   product             = 0100
09-07 10:32:18.583  3222  3298 D bte_conf:   version             = 0200
09-07 10:32:18.583  3222  3298 D bte_conf:   clientExecutableURL = 
09-07 10:32:18.583  3222  3298 D bte_conf:   serviceDescription  = 
09-07 10:32:18.583  3222  3298 D bte_conf:   documentationURL    = 
,09-07 10:32:18.583  3222  3298 D bte_conf: bte_load_did_conf no section named DID2.
09-07 10:32:18.583  3222  3298 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
09-07 10:32:18.583  3222  3298 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan,
,09-07 10:32:18.583  3222  3295 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-07 10:32:18.583  3222  3295 D BluetoothAdapterProperties: ScanMode =  20
09-07 10:32:18.583  3222  3295 D BluetoothAdapterProperties: State =  11
,09-07 10:32:18.583  7822  7822 D IntelligenceServiceApplication: onCreate()
,09-07 10:32:18.583  1013  1496 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
09-07 10:32:18.583  3222  3295 D BluetoothAdapterProperties: Setting state to 12
09-07 10:32:18.583  3222  3295 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-07 10:32:18.583  1013  1543 I ActivityManager: Killing 7351:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,09-07 10:32:18.593  3222  3298 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-07 10:32:18.593  3222  3298 D BluetoothAdapterProperties: Scan Mode:21
09-07 10:32:18.593  3222  3298 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-07 10:32:18.593  7822  7822 D IntelligenceServiceApplication: no applications having user consent for prediction
09-07 10:32:18.593  1013  1479 D SettingsProvider: name = bluetooth_a2dp_sink_mode
09-07 10:32:18.593  1013  1479 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 10:32:18.593  1013  1479 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 10:32:18.593  1013  1479 D SettingsProvider: selectionArgs: false
09-07 10:32:18.593  1013  1479 D SettingsProvider: selectionArgs: 1002
09-07 10:32:18.593  1013  1479 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 10:32:18.593  1013  1479 D SettingsProvider: ret = -1
09-07 10:32:18.593  3222  3295 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-07 10:32:18.593  3222  3295 D BluetoothAdapterService: updateAdapterState state is 12
,09-07 10:32:18.593  1013  1479 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 10:32:18.593  1013  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-07 10:32:18.603  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 10:32:18.603  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:18.603  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:18.603  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 10:32:18.603  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:32:18.603  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 10:32:18.603  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 10:32:18.603  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 10:32:18.603  1013  1479 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:18.603  1013  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 10:32:18.603  1013  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:18.603  1013  1026 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-07 10:32:18.603  7071  7071 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 10:32:18.603  7822  7822 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,09-07 10:32:18.603  3222  3295 D BluetoothAdapterService: Autoconnection is available 
09-07 10:32:18.603  3222  3295 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-07 10:32:18.603  3222  3295 D BluetoothAdapterService: starting service from this receiver
,09-07 10:32:18.603  1013  1218 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-07 10:32:18.603  1013  1218 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-07 10:32:18.603  4773  4782 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-07 10:32:18.603  1013  1218 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:18.603  1013  1218 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:18.603  1013  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:18.613  3222  3222 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-07 10:32:18.613  3222  3295 I BluetoothAdapterState: Entering On State from state = 11
,09-07 10:32:18.613  1013  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
09-07 10:32:18.613  1013  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-07 10:32:18.613  1013  1044 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:18.613  1013  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:18.613  1013  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:18.613  1013  1044 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-07 10:32:18.613  1013  1044 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-07 10:32:18.613  1013  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-07 10:32:18.613  1013  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-07 10:32:18.613  4773  4790 D BluetoothMap: onBluetoothStateChange: up=true
09-07 10:32:18.613  7822  7822 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-07 10:32:18.613  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 10:32:18.613  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:18.613  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:18.613  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 10:32:18.613  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:32:18.613  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 10:32:18.613  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 10:32:18.613  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 10:32:18.613  1013  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
09-07 10:32:18.613  1013  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-07 10:32:18.623  1013  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:32:18.623  1013  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:18.623  1013  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:18.623  7071  7071 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 10:32:18.623  3222  3238 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-07 10:32:18.623  3222  3238 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-07 10:32:18.623  1013  1044 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-07 10:32:18.623  1013  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-07 10:32:18.623  1013  1044 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:18.623  1013  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:18.623  1013  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:18.623  1013  1044 D BluetoothPan: Binding service...
,09-07 10:32:18.623  3222  3222 I BluetoothPbapService: Handler(): got msg=1
,09-07 10:32:18.623  1013  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-07 10:32:18.623  1013  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-07 10:32:18.633  1013  1479 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-07 10:32:18.633  4773  4782 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-07 10:32:18.633  1013  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-07 10:32:18.633  1013  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-07 10:32:18.633  1013  1044 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:18.633  1013  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:18.633  1013  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:18.633  4773  4782 E BluetoothHeadset: BluetoothHeadset service is binded
09-07 10:32:18.633  1013  1044 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-07 10:32:18.633  3222  7847 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-07 10:32:18.633  1013  1013 D BluetoothA2dp: Proxy object connected
,09-07 10:32:18.633  4773  4773 D BluetoothInputDevice: Proxy object connected
09-07 10:32:18.633  4773  4773 D HidProfile: Bluetooth service connected
,09-07 10:32:18.643  3222  3222 D BluetoothA2dp: Proxy object connected
09-07 10:32:18.643  3222  3222 D BluetoothAdapterService: Bluetooth A2dp source service connected
09-07 10:32:18.643  3222  7847 D BluetoothSocket: bindListen(): myUserId = 0
09-07 10:32:18.643  3222  7847 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 10:32:18.643  1013  1013 D BluetoothPan: BluetoothPAN Proxy object connected
,09-07 10:32:18.643  4773  4773 D BluetoothMap: Proxy object connected
,09-07 10:32:18.643  3222  7847 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
09-07 10:32:18.643  3222  7847 D BluetoothSocket: bindListen(), new LocalSocket 
,09-07 10:32:18.643  1013  1044 E BluetoothManagerService: Unable to call onBluetoothStateChange() on callback #6
09-07 10:32:18.643  1013  1044 E BluetoothManagerService: android.os.TransactionTooLargeException
09-07 10:32:18.643  1013  1044 E BluetoothManagerService: 	at android.os.BinderProxy.transactNative(Native Method)
09-07 10:32:18.643  1013  1044 E BluetoothManagerService: 	at android.os.BinderProxy.transact(Binder.java:496)
09-07 10:32:18.643  1013  1044 E BluetoothManagerService: 	at android.bluetooth.IBluetoothStateChangeCallback$Stub$Proxy.onBluetoothStateChange(IBluetoothStateChangeCallback.java:84)
09-07 10:32:18.643  1013  1044 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.sendBluetoothStateCallback(BluetoothManagerService.java:1053)
09-07 10:32:18.643  1013  1044 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.bluetoothStateChangeHandler(BluetoothManagerService.java:2007)
09-07 10:32:18.643  1013  1044 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.access$3900(BluetoothManagerService.java:105)
09-07 10:32:18.643  1013  1044 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService$BluetoothHandler.handleMessage(BluetoothManagerService.java:1576)
09-07 10:32:18.643  1013  1044 E BluetoothManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 10:32:18.643  1013  1044 E BluetoothManagerService: 	at android.os.Looper.loop(Looper.java:145)
09-07 10:32:18.643  1013  1044 E BluetoothManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 10:32:18.643  1013  1044 E BluetoothManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-07 10:32:18.643  3222  7847 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-07 10:32:18.643  3222  7847 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@10ce8112
09-07 10:32:18.643  3222  7847 D BluetoothSocket: channel: 19
09-07 10:32:18.643  3222  7847 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,09-07 10:32:18.643  4773  4773 D MapProfile: Bluetooth service connected
09-07 10:32:18.643  4773  4773 D BluetoothMap: getConnectedDevices()
09-07 10:32:18.643  4773  4782 D Bluetoothsap: onBluetoothStateChange: up=true
09-07 10:32:18.643  4773  4782 D Bluetoothsap: Binding service...
,09-07 10:32:18.643  4773  4782 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-07 10:32:18.643  1013  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
09-07 10:32:18.643  1013  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-07 10:32:18.643  1013  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:32:18.643  1013  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 10:32:18.653  1013  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
09-07 10:32:18.653  4773  4773 D HeadsetProfile: Bluetooth service connected
,09-07 10:32:18.653  4773  4782 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-07 10:32:18.653  1434  1452 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-07 10:32:18.653  1013  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-07 10:32:18.653  1013  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-07 10:32:18.653  1013  1044 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:18.653  1013  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:18.653  1013  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:18.653  1434  1452 E BluetoothHeadset: BluetoothHeadset service is binded
,09-07 10:32:18.653  4773  4773 D Bluetoothsap: BluetoothSAP Proxy object connected
09-07 10:32:18.653  4773  4773 D SapProfile: Bluetooth service connected
09-07 10:32:18.653  4773  4773 D Bluetoothsap: getConnectedDevices()
,09-07 10:32:18.653  1465  1998 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-07 10:32:18.653  1013  1044 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-07 10:32:18.653  1013  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-07 10:32:18.653  1013  1044 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:18.653  1013  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:18.653  1013  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:18.653  1465  1998 E BluetoothHeadset: BluetoothHeadset service is binded
,09-07 10:32:18.663  1747  1770 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 10:32:18.663  1747  1770 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-07 10:32:18.663  2645  2669 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-07 10:32:18.663  2645  2669 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-07 10:32:18.663  7071  7085 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 10:32:18.663  7071  7085 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 10:32:18.663  1013  1044 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 10:32:18.663  1013  1044 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-07 10:32:18.663  1013  1044 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-07 10:32:18.663  1013  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-07 10:32:18.663  1013  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-07 10:32:18.663  1013  1044 E BluetoothHeadset: BluetoothHeadset service is binded
,09-07 10:32:18.663  1434  7343 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-07 10:32:18.663  1013  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-07 10:32:18.663  1013  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-07 10:32:18.663  1013  1044 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:18.663  1013  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 10:32:18.663  1013  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
09-07 10:32:18.663  1434  7343 E BluetoothHeadset: BluetoothHeadset service is binded
,09-07 10:32:18.663  1434  1452 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-07 10:32:18.663  1434  1452 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 10:32:18.663  3222  3299 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 10:32:18.663  3222  3299 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 10:32:18.663  1177  1872 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 10:32:18.673  1177  1872 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 10:32:18.673  1465  1860 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-07 10:32:18.673  1465  1860 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 10:32:18.673  4773  4782 D BluetoothPan: Binding service...
,09-07 10:32:18.673  1013  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,09-07 10:32:18.673  1013  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-07 10:32:18.673  1013  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:32:18.673  1013  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:18.673  1013  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:18.673  4773  7848 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 10:32:18.673  4773  7848 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-07 10:32:18.673  4773  4773 D BluetoothPan: BluetoothPAN Proxy object connected
09-07 10:32:18.673  4773  4773 D PanProfile: Bluetooth service connected
,09-07 10:32:18.673  1444  1464 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 10:32:18.673  1444  1464 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 10:32:18.673  4773  4790 D BluetoothPbap: onBluetoothStateChange: up=true
,09-07 10:32:18.683  1013  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-07 10:32:18.683  1013  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
09-07 10:32:18.683  1013  1044 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:18.683  1013  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:18.683  1013  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:18.683  4773  4773 D BluetoothPbap: Proxy object connected
09-07 10:32:18.683  4773  4773 D PbapServerProfile: Bluetooth service connected
,09-07 10:32:18.683  1434  1463 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-07 10:32:18.683  1013  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-07 10:32:18.683  1013  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-07 10:32:18.683  1013  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:32:18.683  1013  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:18.683  1013  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:18.683  1434  1463 E BluetoothHeadset: BluetoothHeadset service is binded
,09-07 10:32:18.683  4773  4782 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-07 10:32:18.683  4773  4782 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-07 10:32:18.683  1013  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-07 10:32:18.693  1013  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-07 10:32:18.693  1013  1044 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:18.693  1013  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 10:32:18.693  1013  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:18.693  4773  4773 D BluetoothA2dp: Proxy object connected
09-07 10:32:18.693  4773  4773 D A2dpProfile: Bluetooth service connected
09-07 10:32:18.693  1013  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,09-07 10:32:18.693  1013  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-07 10:32:18.693  1013  1013 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-07 10:32:18.693  1013  1013 I InputMethodManagerService: [BT Setting State] State =12
09-07 10:32:18.693  1013  1013 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-07 10:32:18.703  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,09-07 10:32:18.703  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-07 10:32:18.703  1177  1775 D BluetoothTile:  handleUpdatestate:false name:null
,09-07 10:32:18.713  1177  1775 D BluetoothTile:  handleUpdatestate:false name:null
,09-07 10:32:18.713  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:32:18.713  1177  1177 D BluetoothTile:  getBluetoothState : 12
,09-07 10:32:18.713  1434  1434 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@28c4441c, true
,09-07 10:32:18.713  1434  1434 D BluetoothHeadset: registerMessageListener
,09-07 10:32:18.713  1177  1775 D BluetoothTile:  handleUpdatestate:false name:null
,09-07 10:32:18.713  1899  1899 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-07 10:32:18.713  1013  3832 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-07 10:32:18.713  4773  4773 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-07 10:32:18.713  1013  1543 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-07 10:32:18.723  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-07 10:32:18.723  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:18.723  3222  3234 D HeadsetService: registerMessageListener
,09-07 10:32:18.723  3222  3234 D HeadsetService: registerMessageListener
,09-07 10:32:18.723  1434  1434 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-07 10:32:18.723  1434  1434 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-07 10:32:18.723  3222  7821 D HeadsetStateMachine: Disconnected process message: 70
09-07 10:32:18.723  3222  7821 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@392ca0e3
,09-07 10:32:18.723  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:18.733  3222  7850 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-07 10:32:18.733  4773  4773 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
09-07 10:32:18.733  1434  1434 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,09-07 10:32:18.733  1434  1434 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,09-07 10:32:18.733  4773  4773 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
,09-07 10:32:18.733  4773  4773 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-07 10:32:18.733  1434  1434 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-07 10:32:18.733  4773  4773 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-07 10:32:18.733  3222  7821 D HeadsetStateMachine: Disconnected process message: 9
09-07 10:32:18.733  3222  7821 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-07 10:32:18.733  3222  7850 D BluetoothSocket: bindListen(): myUserId = 0
09-07 10:32:18.733  3222  7850 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 10:32:18.733  3222  7850 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
09-07 10:32:18.733  3222  7850 D BluetoothSocket: bindListen(), new LocalSocket 
09-07 10:32:18.733  3222  7850 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-07 10:32:18.733  3222  7850 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@397dae0
09-07 10:32:18.733  3222  7850 D BluetoothSocket: channel: 5
,09-07 10:32:18.733   282   678 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
09-07 10:32:18.733   282   678 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-07 10:32:18.733   282   678 V voice   : voice_set_parameters: exit with code(-2)
09-07 10:32:18.733   282   678 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
,09-07 10:32:18.743   282   678 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-07 10:32:18.743   282   678 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
,09-07 10:32:18.743   282   678 V audio_hw_primary: adev_set_parameters: exit
,09-07 10:32:18.743  3222  7821 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-07 10:32:18.743  4773  4773 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 10:32:18.743  1013  3836 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-07 10:32:18.743  1013  3836 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-07 10:32:18.743  1013  3836 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:32:18.743  1013  3836 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:18.743  1013  3836 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-07 10:32:18.753  2645  2645 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 10:32:18.753  4773  4773 D DockEventReceiver: finishStartingService: stopping service
,09-07 10:32:18.753  4773  4773 D BluetoothNotiBroadcastReceiver: onReceive
,09-07 10:32:18.753  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-07 10:32:18.753  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-07 10:32:18.763  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2acc5f51
09-07 10:32:18.763  3222  3222 D BtConfig.SecureMode: isSecureModeOn:false
,09-07 10:32:18.763  1013  1025 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-07 10:32:18.763  1013  1025 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-07 10:32:18.773  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:32:18.773  1013  1025 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:18.773  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:18.783  1013  3832 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,09-07 10:32:18.783  1013  3832 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:18.783  1013  3832 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:18.783  1013  3832 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:18.783  1013  3832 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:18.793  7853  7853 E Zygote  : MountEmulatedStorage(),
09-07 10:32:18.793  7853  7853 I libpersona: KNOX_SDCARD checking this for 10105
09-07 10:32:18.793  7853  7853 E Zygote  : v2
,09-07 10:32:18.793  7853  7853 I libpersona: KNOX_SDCARD not a persona
09-07 10:32:18.793  7853  7853 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 10:32:18.793  1013  3832 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7853 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,09-07 10:32:18.803  7853  7853 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 10:32:18.803  1013  1026 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-07 10:32:18.803  7853  7853 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-07 10:32:18.803   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,09-07 10:32:18.813  3222  7863 D BluetoothSocket: bindListen(): myUserId = 0
,09-07 10:32:18.813  3222  7863 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 10:32:18.813  3222  7863 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[86]}
,09-07 10:32:18.813  3222  7863 D BluetoothSocket: bindListen(), new LocalSocket 
09-07 10:32:18.813  3222  7863 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-07 10:32:18.813  3222  7863 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@a4fc50c
09-07 10:32:18.813  3222  7863 D BluetoothSocket: channel: 12
09-07 10:32:18.813  3222  7863 I BtOppRfcommListener: Accept thread started.
,09-07 10:32:18.823  7853  7853 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 10:32:18.823  7853  7853 D ActivityThread: Added TimaKeyStore provider
,09-07 10:32:18.943   256   523 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-07 10:32:18.943   256   523 W Vold    : Returning OperationFailed - no handler for errno 0
,09-07 10:32:18.943  7853  7875 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-07 10:32:18.953   256   523 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-07 10:32:18.953   256   523 W Vold    : Returning OperationFailed - no handler for errno 0
,09-07 10:32:18.953  7853  7875 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-07 10:32:19.103  7853  7853 D StrictMode: StrictMode policy violation; ~duration=146 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at java.io.File.exists(File.java:363)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-07 10:32:19.103  7853  7853 D StrictMode: StrictMode policy violation; ~duration=145 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 10:32:19.103  7853  7853 D StrictMode: StrictMode policy violation; ~duration=144 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gm,m.map.m.e.a(PG:1515)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 10:32:19.103  7853  7853 D StrictMode: StrictMode policy violation; ~duration=142 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.q.k.a(PG:2107)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.q.e.b(PG:170)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09,-07 10:32:19.103  7853  7853 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 10:32:19.103  7853  7853 D StrictMode: StrictMode policy violation; ~duration=140 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.q.k.c(PG:18147)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.q.k.d(PG:583)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.q.e.b(PG:170)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 10:32:19.103  7853  7853 D StrictMode: StrictMode policy violation; ~duration=116 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at java.io.File.exists(File.java:363)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 10:32:19.103  7853  7853 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at java.io.File.exists(File.java:363)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 10:32:19.103  1013  3836 I ActivityManager: Killing 7463:com.sec.pcw.device/1000 (adj 15): empty #21
09-07 10:32:19.103  7853  7853 D StrictMode: StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at java.io.File.lastModified(File.java:571)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 10:32:19.103  7853  7853 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-07 10:32:19.163  7853  7875 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-07 10:32:19.183  1013  3832 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-07 10:32:19.183  1013  3832 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:32:19.183  1013  3832 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 10:32:19.183  1013  3832 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-07 10:32:19.763   292   292 E SMD     : DCD OFF,
,09-07 10:32:19.803   326   326 I ServiceManager: Waiting for service AtCmdFwd...,
,09-07 10:32:20.803   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,09-07 10:32:20.813  1013  1218 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-07 10:32:20.823  1013  1218 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4301, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-07 10:32:20.823  1013  1218 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-07 10:32:20.823  1013  1218 D BatteryService: stay LED for charging
,09-07 10:32:20.823  1013  1013 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-07 10:32:20.823  1013  1013 I MotionRecognitionService: Plugged
09-07 10:32:20.823  1013  1013 I MotionRecognitionService: mGripSensorEnabled= false
,09-07 10:32:20.823  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-07 10:32:20.823  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate,
,09-07 10:32:20.823  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
09-07 10:32:20.823  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-07 10:32:20.833  3222  3222 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-07 10:32:20.833  3222  7821 D HeadsetStateMachine: Disconnected process message: 10
,09-07 10:32:20.853  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-07 10:32:20.853  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-07 10:32:20.853  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-07 10:32:21.353  7071  7301 D BluetoothAdapter: disable()
,09-07 10:32:21.353  1013  1133 D SettingsProvider: name = bluetooth_on
,09-07 10:32:21.363  3222  3295 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF,
09-07 10:32:21.363  1013  1481 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 10:32:21.363  3222  3295 D BluetoothAdapterProperties: Setting state to 13
,09-07 10:32:21.363  1013  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
09-07 10:32:21.363  3222  3295 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-07 10:32:21.363  3222  3295 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-07 10:32:21.363  3222  3295 D BluetoothAdapterService: updateAdapterState state is 13
09-07 10:32:21.363  1013  1481 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:21.363  1013  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 10:32:21.363  1013  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-07 10:32:21.363  3222  3222 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,09-07 10:32:21.373  3222  3295 D BluetoothAdapterService: Autoconnection is available ,
09-07 10:32:21.373  3222  3295 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-07 10:32:21.373  1013  1013 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-07 10:32:21.373  3222  3295 D BluetoothAdapterService: terminating service from this receiver
09-07 10:32:21.373  1013  1013 I InputMethodManagerService: [BT Setting State] State =13
,09-07 10:32:21.373  3222  3222 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2548be55, channel: 19, state: LISTENING
09-07 10:32:21.373  3222  3222 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2548be55, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@10ce8112, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@14b5206amSocket: android.net.LocalSocket@3cfb495b impl:android.net.LocalSocketImpl@1eba25f8 fd:FileDescriptor[80]
09-07 10:32:21.373  3222  3222 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3cfb495b impl:android.net.LocalSocketImpl@1eba25f8 fd:FileDescriptor[80]
,09-07 10:32:21.373  1899  1899 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
09-07 10:32:21.373  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,09-07 10:32:21.383  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:32:21.383  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-07 10:32:21.383  4773  4773 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:32:21.383  1177  1177 D BluetoothTile:  getBluetoothState : 13
,09-07 10:32:21.383  7071  7071 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 10:32:21.383  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 10:32:21.383  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:21.383  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:21.383  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 10:32:21.383  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 10:32:21.383  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 10:32:21.383  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 10:32:21.383  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 10:32:21.383  1013  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-07 10:32:21.393  1013  1479 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:21.393  1013  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:21.393  1013  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:21.393  1013  1133 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-07 10:32:21.393  7071  7071 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 10:32:21.393  1013  1543 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-07 10:32:21.393  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
09-07 10:32:21.393  7071  7071 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 10:32:21.393  4773  4773 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 10:32:21.393  3222  3295 D BluetoothAdapterProperties: onBluetoothDisable()
09-07 10:32:21.393  3222  3295 D BluetoothAdapterProperties: mDiscovering is false
,09-07 10:32:21.393  1177  1775 D BluetoothTile:  handleUpdatestate:false name:null
09-07 10:32:21.393  1013  1481 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-07 10:32:21.393  1013  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
09-07 10:32:21.393  1013  1479 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-07 10:32:21.393  3222  3295 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-07 10:32:21.403  7071  7071 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 10:32:21.403  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 10:32:21.403  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:21.403  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:21.403  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 10:32:21.403  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 10:32:21.403  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 10:32:21.403  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 10:32:21.403  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 10:32:21.403  7071  7071 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 10:32:21.403  7071  7071 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 10:32:21.403  1013  1481 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:21.403  1013  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:21.403  1013  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-07 10:32:21.403  1177  1775 D BluetoothTile:  handleUpdatestate:false name:null
,09-07 10:32:21.403  1177  1775 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-07 10:32:21.413  4773  4773 D BluetoothPbap: Proxy object disconnected
,09-07 10:32:21.413  3222  3298 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-07 10:32:21.413  3222  3298 D BluetoothAdapterProperties: Scan Mode:20
,09-07 10:32:21.413  4773  4773 D PbapServerProfile: Bluetooth service disconnected
,09-07 10:32:21.413  2645  2645 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 10:32:21.413  3222  3295 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-07 10:32:21.413  3222  3295 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,09-07 10:32:21.413  3222  3295 E bt-btif : cmd socket is not created
,09-07 10:32:21.423  3222  7863 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 10:32:21.423  3222  3300 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,09-07 10:32:21.423  3222  3295 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-07 10:32:21.423  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:21.423  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:21.423  3222  3222 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@22a3ead1, channel: 5, state: LISTENING
,09-07 10:32:21.423  3222  3222 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@22a3ead1, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@397dae0, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1ffcd936mSocket: android.net.LocalSocket@1e9b2037 impl:android.net.LocalSocketImpl@2d67a9a4 fd:FileDescriptor[82]
09-07 10:32:21.423  3222  3222 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1e9b2037 impl:android.net.LocalSocketImpl@2d67a9a4 fd:FileDescriptor[82]
,09-07 10:32:21.423  3222  3222 I BtOppRfcommListener: stopping Accept Thread
09-07 10:32:21.423  3222  3222 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3ab630d, channel: 12, state: LISTENING
09-07 10:32:21.433  3222  3222 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3ab630d, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@a4fc50c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@313552c2mSocket: android.net.LocalSocket@36f788d3 impl:android.net.LocalSocketImpl@3947bc10 fd:FileDescriptor[86]
09-07 10:32:21.433  3222  3222 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@36f788d3 impl:android.net.LocalSocketImpl@3947bc10 fd:FileDescriptor[86]
09-07 10:32:21.433  3222  7863 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-07 10:32:21.433  3222  3300 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-07 10:32:21.433  4773  4773 D DockEventReceiver: finishStartingService: stopping service
09-07 10:32:21.433  3222  3300 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 10:32:21.433  3222  3300 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-07 10:32:21.433  3222  3300 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 10:32:21.433  3222  3300 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 10:32:21.433  3222  3300 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-07 10:32:21.433  4773  4773 D BluetoothNotiBroadcastReceiver: onReceive
,09-07 10:32:21.443  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED,
09-07 10:32:21.443  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13,
09-07 10:32:21.443  3222  3222 V BluetoothOppManager: cleanUp...
,09-07 10:32:21.623  3222  3295 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,09-07 10:32:21.623  3222  3295 D BtConfig.SecureMode: isSecureModeOn:false
,09-07 10:32:21.623  3222  3295 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
,09-07 10:32:21.623  3222  3295 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
,09-07 10:32:21.623  3222  3295 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
09-07 10:32:21.623  3222  3295 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
,09-07 10:32:21.623  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-07 10:32:21.623  3222  3295 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-07 10:32:21.623  1013  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
,09-07 10:32:21.623  1013  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-07 10:32:21.633  1013  1026 W ActivityManager: userId = 0, bbcId = -10000,
09-07 10:32:21.633  1013  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:21.633  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:21.633  3222  3295 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService,
09-07 10:32:21.633  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-07 10:32:21.633  1013  1496 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 10:32:21.633  3222  3295 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
09-07 10:32:21.633  1013  1496 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-07 10:32:21.633  3222  3222 D HeadsetService: Received stop request...Stopping profile...
09-07 10:32:21.633  1013  1496 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:21.633  1013  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:21.633  1013  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:21.633  3222  3295 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService,
09-07 10:32:21.633  1013  1481 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 10:32:21.633  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-07 10:32:21.633  1013  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
09-07 10:32:21.633  3222  3295 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
09-07 10:32:21.633  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2acc5f51
,09-07 10:32:21.643  1013  1481 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:21.643  1013  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:21.643  1013  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:21.643  3222  3295 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
09-07 10:32:21.643  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-07 10:32:21.643  3222  3295 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-07 10:32:21.643  1013  1218 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 10:32:21.643  1013  1218 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
09-07 10:32:21.643  1013  1218 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:21.643  1013  1218 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 10:32:21.643  1013  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:21.643  4773  4773 D HeadsetProfile: Bluetooth service disconnected
,09-07 10:32:21.643  1013  1013 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,09-07 10:32:21.643  3222  3295 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
09-07 10:32:21.653  3222  3222 D A2dpService: Received stop request...Stopping profile...
09-07 10:32:21.653  3222  7837 D A2dpStateMachine: Exit Disconnected: -1
09-07 10:32:21.653  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-07 10:32:21.653  3222  3295 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-07 10:32:21.653  1013  1496 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:21.653  1013  1496 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 10:32:21.653  1013  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:21.653  1013  1496 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-07 10:32:21.653  1013  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:21.653  3222  3295 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
09-07 10:32:21.653  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-07 10:32:21.653  3222  3295 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-07 10:32:21.653  1013  3832 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 10:32:21.653  1013  3832 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-07 10:32:21.653  1013  3832 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:32:21.653  1013  3832 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 10:32:21.653  1013  3832 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:21.653  3222  3295 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
,09-07 10:32:21.663  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-07 10:32:21.663  3222  3295 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-07 10:32:21.663  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2acc5f51
09-07 10:32:21.663  1013  1481 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-07 10:32:21.663  1013  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-07 10:32:21.663  1013  1481 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:32:21.663  1013  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 10:32:21.663  1013  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:21.663  3222  3295 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,09-07 10:32:21.663  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-07 10:32:21.663  3222  3295 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,09-07 10:32:21.663  3222  3295 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-07 10:32:21.663  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-07 10:32:21.663  3222  3295 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-07 10:32:21.663  3222  3295 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
09-07 10:32:21.663  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-07 10:32:21.663  3222  3295 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-07 10:32:21.663  3222  3295 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
09-07 10:32:21.663  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-07 10:32:21.663  3222  3295 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-07 10:32:21.663  3222  3295 D BluetoothAdapterState: Stopping profile services that were post enabled
09-07 10:32:21.663  3222  3222 E BluetoothAdapterService(718036817): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,09-07 10:32:21.663  3222  3222 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-07 10:32:21.663  3222  3222 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-07 10:32:21.663  3222  3222 D HidService: Received stop request...Stopping profile...
09-07 10:32:21.663  3222  3222 D HidService: Stopping Bluetooth HidService
09-07 10:32:21.663  3222  3222 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-07 10:32:21.663  3222  3222 W bt-btif : cleanup: HH disabling or disabled already, status = 0
,09-07 10:32:21.663  3222  3222 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-07 10:32:21.663  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2acc5f51
09-07 10:32:21.673  1013  1013 D BluetoothA2dp: Proxy object disconnected
09-07 10:32:21.673  1013  1013 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-07 10:32:21.673  4773  4773 D BluetoothA2dp: Proxy object disconnected
,09-07 10:32:21.673  4773  4773 D A2dpProfile: Bluetooth service disconnected
,09-07 10:32:21.673  4773  4773 D BluetoothInputDevice: Proxy object disconnected
,09-07 10:32:21.673  4773  4773 D HidProfile: Bluetooth service disconnected
09-07 10:32:21.673  3222  3222 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-07 10:32:21.673  3222  3222 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-07 10:32:21.673  3222  3222 D HealthService: Received stop request...Stopping profile...
09-07 10:32:21.673  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2acc5f51
,09-07 10:32:21.673  3222  3222 D PanService: Received stop request...Stopping profile...
,09-07 10:32:21.673  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2acc5f51
,09-07 10:32:21.673  1013  1013 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-07 10:32:21.683  1013  1093 V AlarmManager: waitForAlarm result :4
09-07 10:32:21.683  4773  4773 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-07 10:32:21.683  4773  4773 D PanProfile: Bluetooth service disconnected
,09-07 10:32:21.683  3222  3222 E BluetoothAdapterService(718036817): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,09-07 10:32:21.683  3222  3222 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-07 10:32:21.683  3222  3222 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-07 10:32:21.683  3222  3222 D BluetoothMapService: Received stop request...Stopping profile...
,09-07 10:32:21.683  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2acc5f51
,09-07 10:32:21.693  3222  3222 D BluetoothA2dp: Proxy object disconnected
09-07 10:32:21.693  3222  3222 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
09-07 10:32:21.693  3222  3222 E BluetoothAdapterService(718036817): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-07 10:32:21.693  3222  3222 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-07 10:32:21.693  3222  3222 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-07 10:32:21.693  3222  3222 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,09-07 10:32:21.693  3222  3222 D SapService: Received stop request...Stopping profile...
09-07 10:32:21.693  3222  3222 D SapService: Stopping Bluetooth SapService
09-07 10:32:21.693  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2acc5f51
,09-07 10:32:21.693  4773  4773 D BluetoothMap: Proxy object disconnected
09-07 10:32:21.693  4773  4773 D MapProfile: Bluetooth service disconnected
,09-07 10:32:21.693  3222  7839 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,09-07 10:32:21.693  3222  3222 I GKI_LINUX: GKI_exit_task 2 done
09-07 10:32:21.693  3222  3222 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,09-07 10:32:21.693  3222  3222 E BluetoothAdapterService(718036817): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-07 10:32:21.693  3222  3222 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-07 10:32:21.693  3222  3222 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-07 10:32:21.693  3222  3222 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-07 10:32:21.693  3222  3222 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-07 10:32:21.693  3222  3222 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-07 10:32:21.693  3222  3222 E BluetoothAdapterService(718036817): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-07 10:32:21.693  3222  3222 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-07 10:32:21.693  3222  3222 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-07 10:32:21.693  3222  3222 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-07 10:32:21.693  3222  3222 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-07 10:32:21.693   277  1008 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-07 10:32:21.693  3222  3222 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-07 10:32:21.693   277  1008 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,09-07 10:32:21.693  4773  4773 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-07 10:32:21.693  4773  4773 D SapProfile: Bluetooth service disconnected
,09-07 10:32:21.693  3222  3222 E BluetoothAdapterService(718036817): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,09-07 10:32:21.693  3222  3222 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-07 10:32:21.693  3222  3222 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-07 10:32:21.693  3222  3222 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
09-07 10:32:21.693  3222  3222 E BluetoothAdapterService(718036817): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-07 10:32:21.693  3222  3222 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-07 10:32:21.703  3222  3222 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-07 10:32:21.703  3222  3222 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,09-07 10:32:21.703  3222  3295 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,09-07 10:32:21.703  3222  3295 D BluetoothAdapterProperties: Setting state to 10
09-07 10:32:21.703  3222  3295 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-07 10:32:21.703  3222  3295 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-07 10:32:21.703  3222  3295 D BluetoothAdapterService: updateAdapterState state is 10
,09-07 10:32:21.703  3222  3295 D BluetoothAdapterService: Autoconnection is available 
09-07 10:32:21.703  3222  3295 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-07 10:32:21.703  3222  3295 I BluetoothAdapterState: Entering OffState
,09-07 10:32:21.703  4773  4782 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-07 10:32:21.703  1013  1044 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-07 10:32:21.703  4773  7848 D BluetoothMap: onBluetoothStateChange: up=false
,09-07 10:32:21.703  3222  3234 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-07 10:32:21.703  7853  7865 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-07 10:32:21.703  7853  7865 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-07 10:32:21.703  4773  4782 D Bluetoothsap: onBluetoothStateChange: up=false
,09-07 10:32:21.703  4773  4782 D Bluetoothsap: Unbinding service...
,09-07 10:32:21.713  1747  1770 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-07 10:32:21.713  1747  1770 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 10:32:21.713  2645  4413 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-07 10:32:21.713  2645  4413 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 10:32:21.713  7071  7085 D BluetoothAdapter: onBluetoothStateChange: up=false
09-07 10:32:21.713  7071  7085 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan,
09-07 10:32:21.713  7071  7085 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-07 10:32:21.713  7071  7085 D BluetoothLeAdvertiser: Exit stop advertising
09-07 10:32:21.713  7071  7085 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-07 10:32:21.713  7071  7085 D BluetoothLeScanner: Exiting stopAllScan
09-07 10:32:21.713  1013  1044 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-07 10:32:21.713  1013  1044 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 10:32:21.713  1013  1040 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:32:21.713  1013  1040 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 10:32:21.713  1013  1040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,09-07 10:32:21.723  1434  1463 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-07 10:32:21.723  1434  1463 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 10:32:21.723  3222  3359 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-07 10:32:21.723  3222  3359 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 10:32:21.723  1177  1872 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-07 10:32:21.723  1177  1872 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 10:32:21.723  1465  2482 D BluetoothAdapter: onBluetoothStateChange: up=false
09-07 10:32:21.723  1465  2482 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 10:32:21.723  4773  4790 D BluetoothAdapter: onBluetoothStateChange: up=false
09-07 10:32:21.723  4773  4790 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 10:32:21.733  1444  1476 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-07 10:32:21.733  1444  1476 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 10:32:21.733  4773  4782 D BluetoothPbap: onBluetoothStateChange: up=false
,09-07 10:32:21.733  4773  7848 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-07 10:32:21.733  1013  1013 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-07 10:32:21.733  1013  1013 I InputMethodManagerService: [BT Setting State] State =10
,09-07 10:32:21.733  1013  1013 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-07 10:32:21.743  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-07 10:32:21.743  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-07 10:32:21.743  1177  1177 D BluetoothTile:  getBluetoothState : 10
,09-07 10:32:21.753  1013  1461 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-07 10:32:21.753  1013  1026 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-07 10:32:21.753  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-07 10:32:21.753  1899  1899 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-07 10:32:21.753  4773  4773 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-07 10:32:21.763  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:21.763  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:21.763  4773  4773 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 10:32:21.763  1013  3836 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-07 10:32:21.763  1013  3836 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-07 10:32:21.763  1013  3836 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:32:21.763  1013  3836 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 10:32:21.773  1013  3836 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-07 10:32:21.773  2645  2645 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 10:32:21.773  4773  4773 D DockEventReceiver: finishStartingService: stopping service
,09-07 10:32:21.783  4773  4773 D BluetoothNotiBroadcastReceiver: onReceive
,09-07 10:32:21.783  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-07 10:32:21.783  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-07 10:32:21.803   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,09-07 10:32:22.763   292   292 E SMD     : DCD OFF,
,09-07 10:32:22.803   326   326 I ServiceManager: Waiting for service AtCmdFwd...,
,09-07 10:32:23.803   326   326 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-07 10:32:24.363  7071  7301 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 10:32:24.363  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 10:32:25.763   292   292 E SMD     : DCD OFF
,09-07 10:32:27.373  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 10:32:27.373  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@49da652 added. We now have 6 listener(s)
,09-07 10:32:27.373  7071  7301 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 10:32:27.373  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 10:32:27.373  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3538fd23 added. We now have 7 listener(s)
,09-07 10:32:27.373  7071  7301 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 10:32:27.373  7071  7301 I System.out: IsBluetoothEnabled
,09-07 10:32:27.373  7071  7301 D BluetoothAdapter: disable()
,09-07 10:32:27.373  1013  1025 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,09-07 10:32:27.383  7071  7301 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:27.383  7071  7301 D BluetoothAdapter: enable()
,09-07 10:32:27.383  1013  3832 W ActivityManager: Permission Denial: getCurrentUser() from pid=7071, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-07 10:32:27.383  1013  3832 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-07 10:32:27.383  1013  3832 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7071, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-07 10:32:27.383  1013  3832 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-07 10:32:27.383  1013  3832 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
09-07 10:32:27.383  1013  3832 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
09-07 10:32:27.383  1013  3832 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
09-07 10:32:27.383  1013  3832 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-07 10:32:27.383  1013  3832 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-07 10:32:27.383  1013  3832 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-07 10:32:27.393  1013  3832 D SettingsProvider: name = bluetooth_on,
,09-07 10:32:27.403  1013  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-07 10:32:27.403  1013  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-07 10:32:27.403  1013  1044 D SecContentProvider: uri = 3 selection = isBluetoothEnabled,
,09-07 10:32:27.413  3222  3295 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,09-07 10:32:27.413  3222  3295 D BluetoothAdapterProperties: Setting state to 11
09-07 10:32:27.413  3222  3295 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,09-07 10:32:27.413  3222  3295 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-07 10:32:27.413  3222  3295 D BluetoothAdapterService: updateAdapterState state is 11
,09-07 10:32:27.413  3222  3295 D BluetoothAdapterService: Autoconnection is available 
,09-07 10:32:27.413  3222  3295 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
09-07 10:32:27.413  3222  3295 D BtConfig.SecureMode: isSecureModeOn:false
,09-07 10:32:27.413  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-07 10:32:27.413  3222  3295 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12,
09-07 10:32:27.413  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-07 10:32:27.413  3222  3295 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
09-07 10:32:27.413  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-07 10:32:27.413  3222  3295 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
09-07 10:32:27.413  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-07 10:32:27.413  3222  3295 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
09-07 10:32:27.413  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService,
09-07 10:32:27.413  3222  3295 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
09-07 10:32:27.413  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-07 10:32:27.413  3222  3295 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
,09-07 10:32:27.413  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-07 10:32:27.413  3222  3295 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
09-07 10:32:27.413  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-07 10:32:27.413  3222  3295 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
09-07 10:32:27.413  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-07 10:32:27.413  3222  3295 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService,
09-07 10:32:27.423  1013  1461 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 10:32:27.413  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-07 10:32:27.423  1013  1461 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
09-07 10:32:27.413  3222  3295 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-07 10:32:27.413  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-07 10:32:27.413  3222  3295 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-07 10:32:27.413  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-07 10:32:27.413  3222  3295 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
09-07 10:32:27.413  3222  3295 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
09-07 10:32:27.413  3222  3295 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
09-07 10:32:27.413  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService,
09-07 10:32:27.413  3222  3295 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
09-07 10:32:27.423  1013  1461 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:27.423  1013  1461 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 10:32:27.423  1013  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-07 10:32:27.423  3222  3295 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
09-07 10:32:27.423  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-07 10:32:27.423  3222  3295 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-07 10:32:27.423  1013  1013 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED,
,09-07 10:32:27.423  3222  3222 D HeadsetService: Received start request. Starting profile...
,09-07 10:32:27.423  1013  1013 I InputMethodManagerService: [BT Setting State] State =11
09-07 10:32:27.423  3222  3222 D HeadsetService: start()
09-07 10:32:27.423  3222  3222 D HeadsetStateMachine: make
09-07 10:32:27.433  3222  3222 E HeadsetStateMachine: # of Max HF connection is 2
,09-07 10:32:27.433  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:,
09-07 10:32:27.433  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-07 10:32:27.433  1177  1177 D BluetoothTile:  getBluetoothState : 11
09-07 10:32:27.433  1899  1899 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-07 10:32:27.433  1013  1026 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-07 10:32:27.433  1013  1504 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-07 10:32:27.433  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-07 10:32:27.433  4773  4773 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-07 10:32:27.443  1177  1775 D BluetoothTile:  handleUpdatestate:false name:null
09-07 10:32:27.443  1177  1775 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-07 10:32:27.443  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:27.443  1013  1025 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 10:32:27.443  1013  1025 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-07 10:32:27.443  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:27.443  1013  1025 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:27.443  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:27.443  1013  3836 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
09-07 10:32:27.443  1013  3836 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-07 10:32:27.453  3222  3295 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
09-07 10:32:27.453  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-07 10:32:27.453  1013  3836 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:27.453  1013  3836 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:27.453  1013  3836 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
09-07 10:32:27.453  3222  3295 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
09-07 10:32:27.453  1013  1321 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 10:32:27.453  1013  1321 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-07 10:32:27.453  1013  1321 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:27.453  1013  1321 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:27.453  1013  1461 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
09-07 10:32:27.453  1013  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-07 10:32:27.453  1013  1461 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-07 10:32:27.453  1013  1461 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:27.453  1013  1461 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:27.453  1013  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-07 10:32:27.453  3222  3295 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
09-07 10:32:27.453  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-07 10:32:27.453  3222  3295 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
09-07 10:32:27.453  3222  3222 I bluedroid: get_profile_interface handsfree
,09-07 10:32:27.453  2645  2645 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 10:32:27.463  1013  1481 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 10:32:27.463  1013  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-07 10:32:27.463  1013  1481 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:32:27.463  1013  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:27.463  1013  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:27.463  3222  3295 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,09-07 10:32:27.463  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-07 10:32:27.463  3222  3295 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-07 10:32:27.463  1013  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-07 10:32:27.463  1013  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-07 10:32:27.463  1013  1026 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:27.463  1013  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:27.463  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:27.473  3222  3295 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
09-07 10:32:27.473  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-07 10:32:27.473  3222  3295 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-07 10:32:27.473  1013  3836 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 10:32:27.473  1013  3836 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-07 10:32:27.473  4773  4773 D BluetoothNotiBroadcastReceiver: onReceive
,09-07 10:32:27.473  1013  3836 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:27.473  1013  3836 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 10:32:27.473  1013  3836 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:27.483  3222  3295 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
09-07 10:32:27.483  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-07 10:32:27.483  3222  3295 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-07 10:32:27.483  3222  3222 E DualScoManager: Dual Sco Manager already instantiated
09-07 10:32:27.483  3222  3222 I DualScoManager: Set HeadsetServiceHelper
09-07 10:32:27.483  3222  3222 D BluetoothAtMessage: createCMTIContentObservers
,09-07 10:32:27.483  1013  1218 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
09-07 10:32:27.483  1013  1218 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 10:32:27.483  1013  1218 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 10:32:27.483  1013  1218 D SettingsProvider: selectionArgs: false
09-07 10:32:27.483  1013  1218 D SettingsProvider: selectionArgs: 1002
09-07 10:32:27.483  1013  1218 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 10:32:27.483  1013  1218 D SettingsProvider: ret = -1
,09-07 10:32:27.483  3222  7901 D HeadsetStateMachine: Enter Disconnected: -2
,09-07 10:32:27.483  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-07 10:32:27.483  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-07 10:32:27.483  3222  3222 D HeadsetService: mStartError = false
,09-07 10:32:27.483  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2acc5f51
,09-07 10:32:27.483  1013  3832 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-07 10:32:27.483  1013  3832 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
09-07 10:32:27.483  3222  3222 D A2dpService: Received start request. Starting profile...
09-07 10:32:27.483  3222  3222 D A2dpService: start()
09-07 10:32:27.483  3222  3222 I bluedroid: get_profile_interface avrcp
,09-07 10:32:27.493  1013  3832 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:27.493  1013  3832 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:27.493  1013  3832 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:27.493  3222  3295 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,09-07 10:32:27.493  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-07 10:32:27.493  3222  3295 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-07 10:32:27.493  3222  3295 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-07 10:32:27.493  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-07 10:32:27.493  3222  3295 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-07 10:32:27.493  3222  3295 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
09-07 10:32:27.493  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-07 10:32:27.493  3222  3295 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-07 10:32:27.493  3222  3295 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
09-07 10:32:27.493  3222  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-07 10:32:27.493  3222  3295 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-07 10:32:27.493  3222  3295 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-07 10:32:27.493  3222  7901 D HeadsetStateMachine: Clear mHeadsetBrsf
09-07 10:32:27.493  3222  7901 D HeadsetStateMachine: map size, before remove : 0
09-07 10:32:27.493  3222  7901 D HeadsetStateMachine: map size, after remove: 0
,09-07 10:32:27.493  3222  3222 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-07 10:32:27.493  3222  3222 D Avrcp   : Initialize Media Controller
09-07 10:32:27.493  3222  3222 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,09-07 10:32:27.503  3222  3222 E Avrcp   : getActiveSessions
09-07 10:32:27.503  3222  3222 D Avrcp   : pick active media Controller
09-07 10:32:27.503  3222  3222 D Avrcp   : Get the active Media Controller 
,09-07 10:32:27.503  3222  3222 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-07 10:32:27.503  3222  7902 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-07 10:32:27.503  3222  3222 D A2dpStateMachine: make
,09-07 10:32:27.513  3222  7902 D BluetoothMediaBrowser: no now playing list
,09-07 10:32:27.513  3222  7902 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-07 10:32:27.513  3222  3222 I bluedroid: get_profile_interface a2dp
,09-07 10:32:27.513  3222  7904 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-07 10:32:27.513  3222  3222 E bt-btif : warning : media task started media_task_refcnt 1 
09-07 10:32:27.513  3222  3222 D A2dpService: mStartError = false
09-07 10:32:27.513  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2acc5f51
09-07 10:32:27.513  3222  3222 D HeadsetStateMachine: Try to query the phonestate on bind
09-07 10:32:27.513  3222  7903 D A2dpStateMachine: Enter Disconnected: -2
09-07 10:32:27.513  1434  1463 I Telecom : BluetoothPhoneService: queryPhoneState
09-07 10:32:27.513  1434  1434 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
09-07 10:32:27.513  1434  1434 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
09-07 10:32:27.513  1434  1463 I Telecom : BluetoothPhoneService: Result of Message : true
09-07 10:32:27.513  3222  3222 D HeadsetStateMachine: Proxy object connected
09-07 10:32:27.513  3222  3222 D HidService: Received start request. Starting profile...
09-07 10:32:27.513  3222  3222 D HidService: start()
09-07 10:32:27.513  3222  3222 I bluedroid: get_profile_interface hidhost
09-07 10:32:27.513  3222  3222 D HidService: setHidService(): set to: null
09-07 10:32:27.513  3222  3222 D HidService: mStartError = false
09-07 10:32:27.513  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2acc5f51
09-07 10:32:27.513  3222  3222 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
09-07 10:32:27.513  3222  3222 D HealthService: Received start request. Starting profile...
09-07 10:32:27.513  3222  7901 D HeadsetStateMachine: Disconnected process message: 11
09-07 10:32:27.513  3222  3222 D HealthService: start()
,09-07 10:32:27.523  3222  3222 I bluedroid: get_profile_interface health
,09-07 10:32:27.523  3222  3222 D HealthService: mStartError = false
09-07 10:32:27.523  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2acc5f51
,09-07 10:32:27.523  3222  3222 D PanService: Received start request. Starting profile...
09-07 10:32:27.523  3222  3222 D PanService: start()
09-07 10:32:27.523  3222  3222 D BluetoothPanServiceJni: initializeNative(L110): pan
09-07 10:32:27.523  3222  3222 I bluedroid: get_profile_interface pan
09-07 10:32:27.523  3222  3222 D PanService: mStartError = false
09-07 10:32:27.523  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2acc5f51
09-07 10:32:27.523  3222  3222 D HeadsetPhoneState: sendDeviceDataStateChanged
09-07 10:32:27.523  3222  7901 D HeadsetStateMachine: Disconnected process message: 18
09-07 10:32:27.523  3222  3222 D HeadsetPhoneState: Signal level : previous=0 curr=4
,09-07 10:32:27.523  3222  3222 D BluetoothMapService: Received start request. Starting profile...
09-07 10:32:27.523  3222  3222 D BluetoothMapService: start()
,09-07 10:32:27.523  3222  3222 D BluetoothMapService: mStartError = false
,09-07 10:32:27.523  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2acc5f51
,09-07 10:32:27.523  3222  3222 E BluetoothAdapterService(718036817): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-07 10:32:27.523  3222  3222 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-07 10:32:27.523  3222  7901 D HeadsetStateMachine: Disconnected process message: 10
09-07 10:32:27.523  3222  7901 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-07 10:32:27.523  3222  7901 D HeadsetStateMachine: Disconnected process message: 11
,09-07 10:32:27.523  3222  3222 D SapService: Received start request. Starting profile...
09-07 10:32:27.523  3222  3222 D SapService: start()
09-07 10:32:27.523  3222  3222 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-07 10:32:27.523  3222  3222 I bluedroid: get_profile_interface sap
09-07 10:32:27.523  3222  3222 D SapService: mStartError = false
09-07 10:32:27.523  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2acc5f51
,09-07 10:32:27.533  3222  3222 E BluetoothAdapterService(718036817): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
,09-07 10:32:27.533  3222  3222 E BluetoothAdapterService(718036817): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,09-07 10:32:27.533  3222  3222 E BluetoothAdapterService(718036817): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,09-07 10:32:27.533  3222  3222 E BluetoothAdapterService(718036817): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-07 10:32:27.543  3222  3222 E BluetoothAdapterService(718036817): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
09-07 10:32:27.543  3222  3222 E BluetoothAdapterService(718036817): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-07 10:32:27.543  3222  3295 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,09-07 10:32:27.543  3222  3295 I bluedroid: enable
,09-07 10:32:27.553  3222  3298 E bt-btif : Calling BTA_HhEnable
,09-07 10:32:27.553  3222  3298 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,09-07 10:32:27.553  3222  3298 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,09-07 10:32:27.553  3222  3298 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-07 10:32:27.553  3222  3298 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
09-07 10:32:27.553  3222  3298 E BluetoothServiceJni: populateRssiValuesNative
09-07 10:32:27.553  3222  3298 I bluedroid: getModelRssiValues
,09-07 10:32:27.553  3222  3298 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,09-07 10:32:27.553  3222  3298 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-07 10:32:27.553  1013  1013 D SettingsProvider: name = bluetooth_name
,09-07 10:32:27.563  3222  3298 D BluetoothAdapterProperties: Name is: Galaxy A3
,09-07 10:32:27.563  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:27.563  3222  3298 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-07 10:32:27.563  3222  3298 D BluetoothAdapterProperties: Scan Mode:20
09-07 10:32:27.563  3222  3298 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-07 10:32:27.563  3222  3298 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
,09-07 10:32:27.563  3222  3298 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
09-07 10:32:27.563  3222  3298 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,09-07 10:32:27.563  3222  3298 E bt-btif : btif_sock_init: !radio_req && !rfc_init
09-07 10:32:27.563  3222  3298 E bt-btif : JVenable fails
,09-07 10:32:27.563  3222  3298 D bte_conf: Device ID record 1 : primary
,09-07 10:32:27.563  3222  3298 D bte_conf:   vendorId            = 0075
09-07 10:32:27.563  3222  3298 D bte_conf:   vendorIdSource      = 0001
09-07 10:32:27.563  3222  3298 D bte_conf:   product             = 0100
09-07 10:32:27.563  3222  3298 D bte_conf:   version             = 0200
09-07 10:32:27.563  3222  3298 D bte_conf:   clientExecutableURL = 
09-07 10:32:27.563  3222  3298 D bte_conf:   serviceDescription  = 
09-07 10:32:27.563  3222  3298 D bte_conf:   documentationURL    = 
09-07 10:32:27.563  3222  3298 D bte_conf: bte_load_did_conf no section named DID2.
09-07 10:32:27.563  3222  3298 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
09-07 10:32:27.563  3222  3298 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-07 10:32:27.573  3222  3295 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-07 10:32:27.573  3222  3295 D BluetoothAdapterProperties: ScanMode =  20
09-07 10:32:27.573  3222  3295 D BluetoothAdapterProperties: State =  11
,09-07 10:32:27.573  1013  3832 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled,
09-07 10:32:27.573  3222  3295 D BluetoothAdapterProperties: Setting state to 12
,09-07 10:32:27.573  3222  3295 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-07 10:32:27.573  3222  3298 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-07 10:32:27.573  3222  3298 D BluetoothAdapterProperties: Scan Mode:21
09-07 10:32:27.573  3222  3298 D BluetoothAdapterProperties: Discoverable Timeout:120
09-07 10:32:27.573  1013  1496 D SettingsProvider: name = bluetooth_a2dp_sink_mode,
09-07 10:32:27.573  1013  1496 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 10:32:27.573  1013  1133 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
09-07 10:32:27.573  1013  1496 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 10:32:27.573  1013  1133 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
09-07 10:32:27.573  1013  1496 D SettingsProvider: selectionArgs: false
09-07 10:32:27.573  1013  1496 D SettingsProvider: selectionArgs: 1002
,09-07 10:32:27.573  1013  1496 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 10:32:27.573  1013  1496 D SettingsProvider: ret = -1
,09-07 10:32:27.573  3222  3295 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-07 10:32:27.573  3222  3295 D BluetoothAdapterService: updateAdapterState state is 12
09-07 10:32:27.573  1013  1133 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:27.573  1013  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 10:32:27.573  1013  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:27.573  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 10:32:27.573  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:27.573  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:27.573  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 10:32:27.573  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:32:27.573  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 10:32:27.573  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 10:32:27.573  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 10:32:27.583  3222  3295 D BluetoothAdapterService: Autoconnection is available 
09-07 10:32:27.583  3222  3295 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-07 10:32:27.583  3222  3295 D BluetoothAdapterService: starting service from this receiver
,09-07 10:32:27.583  4773  7848 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-07 10:32:27.583  1013  1496 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 10:32:27.583  1013  1496 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-07 10:32:27.583  1013  1496 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:27.583  1013  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:27.583  1013  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:27.583  3222  3222 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-07 10:32:27.583  3222  3222 I BluetoothPbapService: Handler(): got msg=1
,09-07 10:32:27.583  1013  1133 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-07 10:32:27.593  3222  3295 I BluetoothAdapterState: Entering On State from state = 11
,09-07 10:32:27.593  7071  7071 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 10:32:27.593  3222  7909 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-07 10:32:27.603  3222  7909 D BluetoothSocket: bindListen(): myUserId = 0
,09-07 10:32:27.603  3222  7909 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 10:32:27.603  3222  7909 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
09-07 10:32:27.603  3222  7909 D BluetoothSocket: bindListen(), new LocalSocket 
09-07 10:32:27.603  3222  7909 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-07 10:32:27.603  3222  7909 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@ec32ba5
09-07 10:32:27.603  3222  7909 D BluetoothSocket: channel: 19
09-07 10:32:27.603  3222  7909 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,09-07 10:32:27.733  1013  1044 I art     : Explicit concurrent mark sweep GC freed 54737(3MB) AllocSpace objects, 7(113KB) LOS objects, 33% free, 23MB/34MB, paused 2.336ms total 140.245ms
,09-07 10:32:27.733  1013  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
09-07 10:32:27.733  1013  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-07 10:32:27.733  1013  1044 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:27.733  1013  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:27.733  1013  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:27.733  1013  1044 D BluetoothA2dp: onBluetoothStateChange: up=true
09-07 10:32:27.733  1013  1044 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-07 10:32:27.733  1013  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-07 10:32:27.733  1013  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-07 10:32:27.733  4773  4790 D BluetoothMap: onBluetoothStateChange: up=true
,09-07 10:32:27.733  1013  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
09-07 10:32:27.733  1013  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-07 10:32:27.733  1013  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:32:27.733  1013  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:27.733  1013  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
09-07 10:32:27.733  3222  3359 D BluetoothA2dp: onBluetoothStateChange: up=true
09-07 10:32:27.733  3222  3359 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-07 10:32:27.733  1013  1044 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-07 10:32:27.733  1013  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-07 10:32:27.733  1013  1044 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:27.733  1013  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:27.733  1013  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:27.743  1013  1044 D BluetoothPan: Binding service...
,09-07 10:32:27.743  1013  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-07 10:32:27.743  1013  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-07 10:32:27.743  3222  3222 D BluetoothA2dp: Proxy object connected
09-07 10:32:27.743  1013  1013 D BluetoothA2dp: Proxy object connected
,09-07 10:32:27.743  3222  3222 D BluetoothAdapterService: Bluetooth A2dp source service connected
,09-07 10:32:27.743  4773  4782 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-07 10:32:27.743  4773  4773 D BluetoothInputDevice: Proxy object connected
09-07 10:32:27.743  4773  4773 D HidProfile: Bluetooth service connected
,09-07 10:32:27.743  1013  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-07 10:32:27.743  1013  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-07 10:32:27.743  1013  1044 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:27.743  1013  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:27.743  1013  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:27.743  1013  1013 D BluetoothPan: BluetoothPAN Proxy object connected
,09-07 10:32:27.753  4773  4782 E BluetoothHeadset: BluetoothHeadset service is binded,
09-07 10:32:27.753  7853  7865 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 10:32:27.753  7853  7865 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-07 10:32:27.753  4773  7848 D Bluetoothsap: onBluetoothStateChange: up=true
09-07 10:32:27.753  4773  7848 D Bluetoothsap: Binding service...
09-07 10:32:27.753  4773  4773 D BluetoothMap: Proxy object connected
09-07 10:32:27.753  4773  4773 D MapProfile: Bluetooth service connected
,09-07 10:32:27.753  4773  7848 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
09-07 10:32:27.753  4773  4773 D BluetoothMap: getConnectedDevices()
,09-07 10:32:27.753  1013  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
09-07 10:32:27.753  1013  1044 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:27.753  1013  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
09-07 10:32:27.753  1013  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:27.753  1013  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:27.753  4773  7848 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-07 10:32:27.753  1434  7343 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-07 10:32:27.753  4773  4773 D HeadsetProfile: Bluetooth service connected
,09-07 10:32:27.753  1013  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-07 10:32:27.753  1013  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-07 10:32:27.753  1013  1044 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:27.753  1013  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:27.753  1013  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:27.753  1434  7343 E BluetoothHeadset: BluetoothHeadset service is binded
,09-07 10:32:27.753  4773  4773 D Bluetoothsap: BluetoothSAP Proxy object connected
,09-07 10:32:27.753  4773  4773 D SapProfile: Bluetooth service connected
09-07 10:32:27.753  4773  4773 D Bluetoothsap: getConnectedDevices()
,09-07 10:32:27.763  1465  1482 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-07 10:32:27.763  1013  1044 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-07 10:32:27.763  1013  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-07 10:32:27.763  1013  1044 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:27.763  1013  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:27.763  1013  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:27.763  1465  1482 E BluetoothHeadset: BluetoothHeadset service is binded
,09-07 10:32:27.763  1747  1765 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-07 10:32:27.763  1747  1765 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-07 10:32:27.763  2645  2669 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 10:32:27.763  2645  2669 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 10:32:27.763  7071  7084 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 10:32:27.763  7071  7084 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 10:32:27.763  1013  1044 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 10:32:27.763  1013  1044 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 10:32:27.763  1013  1044 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-07 10:32:27.763  1013  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-07 10:32:27.763  1013  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-07 10:32:27.763  1013  1044 E BluetoothHeadset: BluetoothHeadset service is binded
,09-07 10:32:27.763  1434  1463 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-07 10:32:27.773  1013  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-07 10:32:27.773  1013  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-07 10:32:27.773  1013  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:32:27.773  1013  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:27.773  1013  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:27.773  1434  1463 E BluetoothHeadset: BluetoothHeadset service is binded
,09-07 10:32:27.773  1434  7343 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 10:32:27.773  1434  7343 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-07 10:32:27.773  3222  3238 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-07 10:32:27.773  3222  3238 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-07 10:32:27.773  1177  1872 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 10:32:27.773  1177  1872 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-07 10:32:27.773  1465  1484 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-07 10:32:27.773  1465  1484 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-07 10:32:27.773  4773  4782 D BluetoothPan: Binding service...
,09-07 10:32:27.773  1013  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,09-07 10:32:27.773  1013  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-07 10:32:27.773  1013  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:32:27.773  1013  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:27.773  1013  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:27.783  4773  4773 D BluetoothPan: BluetoothPAN Proxy object connected
,09-07 10:32:27.783  4773  4790 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 10:32:27.783  4773  4790 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 10:32:27.783  4773  4773 D PanProfile: Bluetooth service connected
,09-07 10:32:27.783  1444  1476 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 10:32:27.783  1444  1476 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 10:32:27.783  4773  7848 D BluetoothPbap: onBluetoothStateChange: up=true
,09-07 10:32:27.783  1013  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,09-07 10:32:27.783  1013  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-07 10:32:27.783  1013  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:32:27.783  1013  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:27.783  1013  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:27.783  4773  4773 D BluetoothPbap: Proxy object connected
,09-07 10:32:27.783  1434  1452 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-07 10:32:27.793  4773  4773 D PbapServerProfile: Bluetooth service connected
,09-07 10:32:27.793  1013  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-07 10:32:27.793  1013  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-07 10:32:27.793  1013  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:32:27.793  1013  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:27.793  1013  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:27.793  1434  1452 E BluetoothHeadset: BluetoothHeadset service is binded
,09-07 10:32:27.793  4773  4790 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-07 10:32:27.793  4773  4790 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-07 10:32:27.793  1013  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-07 10:32:27.793  1013  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-07 10:32:27.793  1013  1044 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:27.793  1013  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:27.793  1013  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:27.793  4773  4773 D BluetoothA2dp: Proxy object connected
09-07 10:32:27.793  4773  4773 D A2dpProfile: Bluetooth service connected
09-07 10:32:27.793  1013  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-07 10:32:27.793  1013  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-07 10:32:27.793  1013  1013 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-07 10:32:27.793  1013  1013 I InputMethodManagerService: [BT Setting State] State =12
09-07 10:32:27.793  1013  1013 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-07 10:32:27.803  1434  1434 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@31f9b825, true
,09-07 10:32:27.803  1434  1434 D BluetoothHeadset: registerMessageListener
,09-07 10:32:27.803  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,09-07 10:32:27.803  1899  1899 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-07 10:32:27.803  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-07 10:32:27.803  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-07 10:32:27.803  1177  1177 D BluetoothTile:  getBluetoothState : 12
,09-07 10:32:27.813  1177  1775 D BluetoothTile:  handleUpdatestate:false name:null
,09-07 10:32:27.813  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:27.813  1177  1775 D BluetoothTile:  handleUpdatestate:false name:null
,09-07 10:32:27.813  3222  3234 D HeadsetService: registerMessageListener
,09-07 10:32:27.813  3222  3234 D HeadsetService: registerMessageListener
09-07 10:32:27.813  4773  4773 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-07 10:32:27.813  3222  7901 D HeadsetStateMachine: Disconnected process message: 70
09-07 10:32:27.813  3222  7901 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@20376546
,09-07 10:32:27.813  1434  1434 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
,09-07 10:32:27.813  1434  1434 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-07 10:32:27.823  4773  4773 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,09-07 10:32:27.823  4773  4773 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-07 10:32:27.823  4773  4773 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
,09-07 10:32:27.823  1013  1133 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-07 10:32:27.823  3222  7911 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-07 10:32:27.823  1013  1026 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
09-07 10:32:27.823  4773  4773 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-07 10:32:27.823  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-07 10:32:27.823  1434  1434 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
09-07 10:32:27.823  1434  1434 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,09-07 10:32:27.823  1434  1434 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-07 10:32:27.823  1177  1775 D BluetoothTile:  handleUpdatestate:false name:null
,09-07 10:32:27.823  3222  7901 D HeadsetStateMachine: Disconnected process message: 9
,09-07 10:32:27.823  3222  7901 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-07 10:32:27.833  3222  7911 D BluetoothSocket: bindListen(): myUserId = 0
,09-07 10:32:27.833  3222  7911 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 10:32:27.833  3222  7911 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
09-07 10:32:27.833  3222  7911 D BluetoothSocket: bindListen(), new LocalSocket 
09-07 10:32:27.833  3222  7911 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-07 10:32:27.833  3222  7911 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3295a307
09-07 10:32:27.833  3222  7911 D BluetoothSocket: channel: 5
,09-07 10:32:27.833   282   672 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,09-07 10:32:27.833   282   672 V voice   : voice_set_parameters: enter: A2dpSuspended=false
,09-07 10:32:27.833   282   672 V voice   : voice_set_parameters: exit with code(-2)
09-07 10:32:27.833   282   672 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-07 10:32:27.833   282   672 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-07 10:32:27.833   282   672 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-07 10:32:27.833   282   672 V audio_hw_primary: adev_set_parameters: exit
09-07 10:32:27.833  4773  4773 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 10:32:27.833  1013  1025 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-07 10:32:27.833  3222  7901 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-07 10:32:27.833  1013  1025 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-07 10:32:27.833  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:32:27.843  1013  1025 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:27.843  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-07 10:32:27.843  2645  2645 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 10:32:27.853  4773  4773 D DockEventReceiver: finishStartingService: stopping service
,09-07 10:32:27.853  4773  4773 D BluetoothNotiBroadcastReceiver: onReceive
,09-07 10:32:27.853  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-07 10:32:27.853  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-07 10:32:27.863  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2acc5f51
,09-07 10:32:27.863  3222  3222 D BtConfig.SecureMode: isSecureModeOn:false
,09-07 10:32:27.863  1013  1543 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-07 10:32:27.863  1013  1543 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-07 10:32:27.863  1013  1543 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:32:27.863  1013  1543 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:27.863  1013  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 10:32:27.873  1013  3832 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-07 10:32:27.883  3222  7916 D BluetoothSocket: bindListen(): myUserId = 0
09-07 10:32:27.883  3222  7916 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 10:32:27.883  3222  7916 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[85]}
09-07 10:32:27.883  3222  7916 D BluetoothSocket: bindListen(), new LocalSocket 
09-07 10:32:27.883  3222  7916 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-07 10:32:27.883  3222  7916 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@25f68a3
,09-07 10:32:27.883  3222  7916 D BluetoothSocket: channel: 12
09-07 10:32:27.883  3222  7916 I BtOppRfcommListener: Accept thread started.
,09-07 10:32:27.903  1013  3365 D SSRM:n  : SIOP:: AP = 310
,09-07 10:32:28.413  7071  7301 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 10:32:28.413  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:28.413  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:28.413  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 10:32:28.413  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:32:28.413  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 10:32:28.413  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 10:32:28.413  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 10:32:28.413  7071  7301 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 10:32:28.413  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 10:32:28.413  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3276a220 added. We now have 8 listener(s)
,09-07 10:32:28.413  7071  7301 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 10:32:28.413  1013  1218 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-07 10:32:28.423  1013  1218 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-07 10:32:28.423  1013  1218 D SecContentProvider2: mCursor = null
,09-07 10:32:28.423  1013  1218 D WifiService: setWifiEnabled: false pid=7071, uid=10170
,09-07 10:32:28.423  1013  1218 D SettingsProvider: name = wifi_on
,09-07 10:32:28.423  7071  7301 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:28.433  1013  3832 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-07 10:32:28.433  1013  3832 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-07 10:32:28.433  1013  3832 D SecContentProvider2: mCursor = null
,09-07 10:32:28.433  1013  3832 D WifiService: setWifiEnabled: true pid=7071, uid=10170
,09-07 10:32:28.433  1013  3832 W ActivityManager: Permission Denial: getCurrentUser() from pid=7071, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-07 10:32:28.433  1013  3832 W WifiService: Failed getting userId using ActivityManagerNative
09-07 10:32:28.433  1013  3832 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7071, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-07 10:32:28.433  1013  3832 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-07 10:32:28.433  1013  3832 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-07 10:32:28.433  1013  3832 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-07 10:32:28.433  1013  3832 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-07 10:32:28.433  1013  3832 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-07 10:32:28.433  1013  3832 D SettingsProvider: name = wifi_on
,09-07 10:32:28.443  1013  1124 E WifiHW  : ##################### set firmware type 0 #####################
,09-07 10:32:28.763   292   292 E SMD     : DCD OFF
,09-07 10:32:28.773  1013  1042 D Tethering: interfaceAdded wlan0
,09-07 10:32:28.773  1013  1128 E Tethering: No numeric data
,09-07 10:32:28.783  1013  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-07 10:32:28.783  1013  1128 D Tethering: clearTetheredNotification()
,09-07 10:32:28.783  1013  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 10:32:28.783  1013  1121 V NetworkStats: performPollLocked(flags=0x1)
09-07 10:32:28.783  1013  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-07 10:32:28.783  1013  1121 V NetworkStats: performPollLocked() took 4ms
09-07 10:32:28.783  1013  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-07 10:32:28.783  1013  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 10:32:28.793  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED,
09-07 10:32:28.793  1177  1177 D HotspotTile: updateTetherState():false, false
,09-07 10:32:28.793  1013  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-07 10:32:28.793  1013  1042 D Tethering: interfaceStatusChanged wlan0, false
09-07 10:32:28.793  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 10:32:28.793  1013  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-07 10:32:28.793  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 10:32:28.793  1013  1128 D Tethering: InitialState.processMessage what=4
09-07 10:32:28.793  1013  1128 E Tethering: No numeric data
,09-07 10:32:28.803  1013  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-07 10:32:28.803  1013  1128 D Tethering: clearTetheredNotification()
,09-07 10:32:28.803  1013  1042 D Tethering: interfaceAdded p2p0
,09-07 10:32:28.803  1013  1042 D Tethering: p2p0 is not a tetherable iface, ignoring
,09-07 10:32:28.803  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-07 10:32:28.803  1177  1177 D HotspotTile: updateTetherState():false, false
,09-07 10:32:28.803  1013  1042 D Tethering: interfaceLinkStateChanged p2p0, false
,09-07 10:32:28.803  1013  1042 D Tethering: interfaceStatusChanged p2p0, false
09-07 10:32:28.813  1013  1121 V NetworkStats: performPollLocked(flags=0x1)
09-07 10:32:28.813  1013  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 10:32:28.813  1013  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-07 10:32:28.813  1013  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-07 10:32:28.813  1013  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-07 10:32:28.813   277  1012 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,09-07 10:32:28.813   277  1012 D SoftapController: Softap fwReload - Ok
,09-07 10:32:28.813  1013  1121 V NetworkStats: performPollLocked() took 8ms
09-07 10:32:28.813  1013  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 10:32:28.823   277  1012 D CommandListener: Setting iface cfg
,09-07 10:32:28.823   277  1012 D CommandListener: Trying to bring down wlan0
,09-07 10:32:28.823   277  1012 D CommandListener: Clearing all IP addresses on wlan0
,09-07 10:32:28.823  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 10:32:28.823  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 10:32:28.823  1013  1124 E WifiHW  : supplicant_name : p2p_supplicant
,09-07 10:32:28.833  1013  1124 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-07 10:32:28.843  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-07 10:32:28.843  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 10:32:28.843  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-07 10:32:28.843  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:28.843  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:28.843  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:28.843  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:28.843  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-07 10:32:28.843  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,09-07 10:32:28.843  1177  1775 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-07 10:32:28.843  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-07 10:32:28.843  1177  1177 D HotspotTile: onReceive : 2, 0
,09-07 10:32:28.853  4773  4773 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-07 10:32:28.853  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:28.853  1013  1321 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-07 10:32:28.853  1013  1321 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-07 10:32:28.853  1013  1321 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:28.853  1013  1321 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:28.853  1013  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-07 10:32:28.863  1602  1602 I Hs20UtilService: Starting #19
,09-07 10:32:28.863  1602  1641 I Hs20UtilService: Message received 5011
,09-07 10:32:28.863  7445  7445 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-07 10:32:28.863  7445  7445 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-07 10:32:28.863  7445  7445 D SecurityLogAgent: StateMachine : Current State = 1
09-07 10:32:28.863  7445  7445 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-07 10:32:28.873  7927  7927 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,09-07 10:32:28.873  7927  7927 I wpa_supplicant: Successfully initialized wpa_supplicant
09-07 10:32:28.873  7927  7927 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-07 10:32:28.893  7927  7927 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
09-07 10:32:28.893   402   402 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7927
09-07 10:32:28.893   402   402 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-07 10:32:28.893  7927  7927 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-07 10:32:28.893  7927  7927 I wpa_supplicant: ssSupport state is = 1
09-07 10:32:28.893  7927  7927 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-07 10:32:28.893  7927  7927 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
09-07 10:32:28.893   402   402 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7927
09-07 10:32:28.893   402   402 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,09-07 10:32:29.053   402   402 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,09-07 10:32:29.053  7927  7927 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,09-07 10:32:29.103  7927  7927 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-07 10:32:29.103  7927  7927 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-07 10:32:29.103  7927  7927 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-07 10:32:29.113   402   402 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7927
09-07 10:32:29.113   402   402 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
09-07 10:32:29.113  7927  7927 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-07 10:32:29.113  7927  7927 I wpa_supplicant: ssSupport state is = 1
09-07 10:32:29.113  7927  7927 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-07 10:32:29.113  7927  7927 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
09-07 10:32:29.113  7927  7927 E wpa_supplicant: SIM READ ERROR
09-07 10:32:29.113  7927  7927 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-07 10:32:29.113  7927  7927 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-07 10:32:29.113  7927  7927 E wpa_supplicant: SIM READ ERROR
09-07 10:32:29.113  7927  7927 I wpa_supplicant: Blacklist: Clear (all) 
,09-07 10:32:29.113  7927  7927 I wpa_supplicant: wpa_default_ap_write_once
09-07 10:32:29.113  7927  7927 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-07 10:32:29.113  7927  7927 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-07 10:32:29.113  7927  7927 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-07 10:32:29.113  7927  7927 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
09-07 10:32:29.113  7927  7927 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-07 10:32:29.113  7927  7927 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,09-07 10:32:29.113  1013  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
09-07 10:32:29.113  1013  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-07 10:32:29.113  1013  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-07 10:32:29.253  7927  7927 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,09-07 10:32:29.423  7927  7927 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,09-07 10:32:29.423  7927  7927 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,09-07 10:32:29.433  7927  7927 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-07 10:32:29.433   402   402 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7927,
09-07 10:32:29.433   402   402 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-07 10:32:29.443  7927  7927 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
09-07 10:32:29.443  7927  7927 I wpa_supplicant: ssSupport state is = 1
09-07 10:32:29.443  7927  7927 I wpa_supplicant: Ctrl_iface: loading cred from phone
,09-07 10:32:29.443  7927  7927 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-07 10:32:29.453  7927  7927 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-07 10:32:29.453   402   402 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7927
09-07 10:32:29.453   402   402 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,09-07 10:32:29.453  7927  7927 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
,09-07 10:32:29.453  7927  7927 I wpa_supplicant: ssSupport state is = 1
09-07 10:32:29.463  1013  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-07 10:32:29.453  7927  7927 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-07 10:32:29.463  1013  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-07 10:32:29.453  7927  7927 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-07 10:32:29.453  7927  7927 E wpa_supplicant: SIM READ ERROR
09-07 10:32:29.453  7927  7927 I wpa_supplicant: wpa_default_ap_write_once
,09-07 10:32:29.453  7927  7927 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-07 10:32:29.453  7927  7927 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-07 10:32:29.453  1013  1042 D Tethering: interfaceLinkStateChanged p2p0, false
,09-07 10:32:29.453  1013  1042 D Tethering: interfaceStatusChanged p2p0, false
09-07 10:32:29.463  1013  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-07 10:32:29.463  1013  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-07 10:32:29.503  7927  7927 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
09-07 10:32:29.503  7927  7927 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-07 10:32:29.563  7927  7927 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
09-07 10:32:29.563  7927  7927 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,09-07 10:32:29.563  7927  7927 I wpa_supplicant: Skip scan - bUseNetwork false
,09-07 10:32:29.573  1013  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
,09-07 10:32:29.573  1013  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21],
09-07 10:32:29.573  7927  7927 I wpa_supplicant: HOTSPOT20_ENABLE called,
09-07 10:32:29.573  7927  7927 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-07 10:32:29.573  7927  7927 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-07 10:32:29.573  7927  7927 E wpa_supplicant: SIM READ ERROR,
09-07 10:32:29.573  7927  7927 I wpa_supplicant: Blacklist: Clear (all) ,
,09-07 10:32:29.603  7927  7927 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,09-07 10:32:29.613  7927  7927 I wpa_supplicant: Skip scan - bUseNetwork false,
,09-07 10:32:29.613  1013  1124 D WifiConfigStore: Loading config and enabling all networks 
,09-07 10:32:29.623  4773  4773 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-07 10:32:29.623  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-07 10:32:29.623  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 10:32:29.623  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
09-07 10:32:29.623  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:29.623  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:29.623  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 10:32:29.623  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:29.623  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-07 10:32:29.623  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-07 10:32:29.623  1177  1775 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-07 10:32:29.623  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
09-07 10:32:29.633  1177  1177 D HotspotTile: onReceive : 3, 0
09-07 10:32:29.633  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 10:32:29.633  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:29.633  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:29.633  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:32:29.633  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:32:29.633  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 10:32:29.633  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 10:32:29.633  7071  7071 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 10:32:29.633  1013  3836 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-07 10:32:29.633  1013  3836 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-07 10:32:29.633  1013  3836 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:29.633  1013  3836 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:29.633  1013  3836 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-07 10:32:29.633  7071  7071 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 10:32:29.633  1013  1124 E WifiConfigStore: Not a HS20
,09-07 10:32:29.643  1602  1602 I Hs20UtilService: Starting #20
,09-07 10:32:29.643  1602  1641 I Hs20UtilService: Message received 5011
,09-07 10:32:29.643  7445  7445 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-07 10:32:29.643  1013  1124 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-07 10:32:29.643  7445  7445 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-07 10:32:29.643  7445  7445 D SecurityLogAgent: StateMachine : Current State = 1
09-07 10:32:29.643  7445  7445 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-07 10:32:29.643  1013  1124 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-07 10:32:29.643  7927  7927 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-07 10:32:29.643  7927  7927 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-07 10:32:29.643  7927  7927 I wpa_supplicant: reset timer : RESET_TIMER 0
09-07 10:32:29.643  7927  7927 I wpa_supplicant: P2P: Current p2p state = IDLE
09-07 10:32:29.643  7927  7927 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-07 10:32:29.643  7927  7927 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-07 10:32:29.643  7927  7927 I wpa_supplicant: First Scan Start
09-07 10:32:29.643  7927  7927 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-07 10:32:29.643  1013  1124 D WifiNative-wlan0: Setting external_sim to 1
,09-07 10:32:29.643  1013  1124 D WifiStateMachine: Setting OUI to DA-A1-19
09-07 10:32:29.643  1013  1124 I WifiNative-HAL: startHal
09-07 10:32:29.643  1013  1124 E wifi    : getStaticLongField sWifiHalHandle 0x9f36188c
09-07 10:32:29.643  1013  1124 I WifiNative-HAL: Could not start hal
,09-07 10:32:29.653  7390  7390 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 10:32:29.653  1013  1124 E WifiNative-wlan0: do suspend true
,09-07 10:32:29.653  1013  1123 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-07 10:32:29.653   277  1012 D CommandListener: Setting iface cfg
09-07 10:32:29.653   277  1012 D CommandListener: Trying to bring up p2p0
,09-07 10:32:29.653  1013  1123 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-07 10:32:29.653  1013  1123 D WifiP2pService: P2pEnablingState
,09-07 10:32:29.653  1013  1123 D WifiP2pService: P2pEnablingState{ what=147457 }
09-07 10:32:29.653  1013  1123 D WifiP2pService: P2p socket connection successful
09-07 10:32:29.653  1013  1123 D WifiP2pService: P2pEnabledState
,09-07 10:32:29.663  1013  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,09-07 10:32:29.663  1013  1013 D WifiScanningService: SCAN_AVAILABLE : 3
,09-07 10:32:29.663  1013  1149 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,09-07 10:32:29.663  1013  1124 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-07 10:32:29.663  1013  1124 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-07 10:32:29.663  1013  1124 E WifiNative-wlan0: invaild command id : 215
,09-07 10:32:29.663  1013  1013 D RttService: SCAN_AVAILABLE : 3
09-07 10:32:29.663  1013  1149 I WifiNative-HAL: startHal
09-07 10:32:29.663  1013  1149 E wifi    : getStaticLongField sWifiHalHandle 0x9e2239bc
09-07 10:32:29.663  1013  1149 I WifiNative-HAL: Could not start hal
09-07 10:32:29.663  1013  1149 E WifiScanningService: could not start HAL
,09-07 10:32:29.663  1013  1150 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-07 10:32:29.663  7927  7927 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
09-07 10:32:29.663  1013  1126 E ConnectivityService: updateNetworkInfo()
,09-07 10:32:29.663  1013  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-07 10:32:29.663  7927  7927 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-07 10:32:29.673  7927  7927 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
09-07 10:32:29.673  1013  1124 E WifiStateMachine: Failed to set frequency band 0
,09-07 10:32:29.673  1013  1013 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-07 10:32:29.673  1013  1124 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-07 10:32:29.673  1013  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-07 10:32:29.673  1013  1124 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-07 10:32:29.673  1013  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-07 10:32:29.673  1013  1124 E WifiNative-wlan0: invaild command id : 215
09-07 10:32:29.673  1013  1045 D WifiDisplayController: disconnect
09-07 10:32:29.673  1013  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-07 10:32:29.673  1013  1045 D WifiDisplayController: updateConnection
09-07 10:32:29.673  1013  1124 D SecContentProvider2: mCursor = null
09-07 10:32:29.673  1013  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-07 10:32:29.673  1013  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-07 10:32:29.673  1013  1123 D WifiNative-p2p0: p2pGetDeviceAddress
,09-07 10:32:29.673  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-07 10:32:29.673  1013  1123 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
09-07 10:32:29.673  1013  3836 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-07 10:32:29.673  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-07 10:32:29.673  1013  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 10:32:29.673  1013  1045 D WifiDisplayAdapter: onP2pDisconnected
,09-07 10:32:29.673  1013  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-07 10:32:29.673  1013  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-07 10:32:29.683  1013  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-07 10:32:29.683  1013  1124 D SecContentProvider2: mCursor = null
09-07 10:32:29.683  1013  1123 D WifiP2pService: DeviceAddress: 0a:75:42
,09-07 10:32:29.683  4773  4773 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-07 10:32:29.683  1013  1045 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
09-07 10:32:29.683  1013  1045 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
09-07 10:32:29.683  1013  1045 D WifiDisplayController:  primary type: 10-0050F204-5
09-07 10:32:29.683  1013  1045 D WifiDisplayController:  secondary type: null
09-07 10:32:29.683  1013  1045 D WifiDisplayController:  wps: 0
09-07 10:32:29.683  1013  1045 D WifiDisplayController:  grpcapab: 0
09-07 10:32:29.683  1013  1045 D WifiDisplayController:  devcapab: 0
09-07 10:32:29.683  1013  1045 D WifiDisplayController:  status: 3
09-07 10:32:29.683  1013  1045 D WifiDisplayController:  wfdInfo: null
09-07 10:32:29.683  1013  1045 D WifiDisplayController:  groupownerAddress: null
09-07 10:32:29.683  1013  1045 D WifiDisplayController:  GOdeviceName: null
09-07 10:32:29.683  1013  1045 D WifiDisplayController:  interfaceAddress: 
09-07 10:32:29.683  1013  1045 D WifiDisplayController:  SConnectInfo : null
,09-07 10:32:29.683  4773  4773 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-07 10:32:29.683  4773  4773 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-07 10:32:29.683  4773  4773 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-07 10:32:29.683  4773  4773 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,09-07 10:32:29.683  4773  4773 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-07 10:32:29.683  4773  4865 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-07 10:32:29.693  7772  7772 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-07 10:32:29.693  7772  7772 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-07 10:32:29.693  7772  7772 D FileShare-Client: Outbound.stopDelayTimer - 
,09-07 10:32:29.693  7430  7430 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-07 10:32:29.703  1013  1123 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-07 10:32:29.703  1013  1123 D WifiP2pService: InactiveState
09-07 10:32:29.703  1013  1123 D WifiP2pService: InactiveState{ what=143376 }
,09-07 10:32:29.703  1013  1123 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-07 10:32:29.703  7927  7927 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-07 10:32:29.703  1013  1123 D WifiP2pService: InactiveState{ what=143376 }
09-07 10:32:29.703  1013  1123 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-07 10:32:29.793  1013  1042 D Tethering: interfaceLinkStateChanged p2p0, false
,09-07 10:32:29.793  1013  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-07 10:32:29.793  1013  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-07 10:32:30.463  7071  7301 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 10:32:30.463  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:30.463  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:30.463  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:32:30.463  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:32:30.463  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 10:32:30.463  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 10:32:30.463  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 10:32:30.463  7071  7301 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 10:32:30.463  7071  7301 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-07 10:32:30.463  7071  7301 D io.jxcore.node.LifeCycleMonitor: onActivityResumed,
,09-07 10:32:30.463  7071  7301 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1d6e6da7 Bundle[{}],
09-07 10:32:30.463  7071  7301 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-07 10:32:30.463  7071  7301 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-07 10:32:30.473  7071  7301 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-07 10:32:30.473  7071  7301 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-07 10:32:30.473  7071  7301 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-07 10:32:30.473  7071  7301 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-07 10:32:30.473  7071  7301 I System.out: Running OutgoingSocketThread
,09-07 10:32:30.473  7071  7936 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1434),
09-07 10:32:30.473  7071  7936 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 60880
09-07 10:32:30.473  7071  7936 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...,
,09-07 10:32:30.863  1013  1504 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-07 10:32:30.873  1013  1504 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4293, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-07 10:32:30.873  1013  1504 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-07 10:32:30.873  1013  1504 D BatteryService: stay LED for charging
09-07 10:32:30.873  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-07 10:32:30.873  1013  1013 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
,09-07 10:32:30.873  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
09-07 10:32:30.873  1013  1013 I MotionRecognitionService: Plugged,
09-07 10:32:30.873  1013  1013 I MotionRecognitionService: mGripSensorEnabled= false
09-07 10:32:30.873  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-07 10:32:30.873  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-07 10:32:30.893  3222  3222 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
09-07 10:32:30.893  3222  7901 D HeadsetStateMachine: Disconnected process message: 10
,09-07 10:32:30.903  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-07 10:32:30.903  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-07 10:32:30.903  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-07 10:32:30.943  7927  7927 I wpa_supplicant: nl80211: Received scan results (26 BSSes),
09-07 10:32:30.943  7927  7927 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-07 10:32:30.943  7927  7927 I wpa_supplicant: Trying to associate with SSID '4E47373030'
09-07 10:32:30.943  7927  7927 I wpa_supplicant: Trying to associate with  'G700',
09-07 10:32:30.943  7927  7927 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
09-07 10:32:30.943  7927  7927 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
09-07 10:32:30.943  1013  7933 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,09-07 10:32:30.963  1013  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-07 10:32:30.963  1013  1124 D SecContentProvider2: mCursor = null
,09-07 10:32:31.073  7927  7927 E wpa_supplicant: Cmd 35605 not handled
,09-07 10:32:31.073  7927  7927 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-07 10:32:31.073  7927  7927 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,09-07 10:32:31.073  7927  7927 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-07 10:32:31.073  7927  7927 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-07 10:32:31.073  1013  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-07 10:32:31.073  1013  1042 D Tethering: interfaceStatusChanged wlan0, false
09-07 10:32:31.073  7927  7927 I wpa_supplicant: Associated with F4.99.3E
09-07 10:32:31.073  7927  7927 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-07 10:32:31.073  7927  7927 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-07 10:32:31.073  7927  7927 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,09-07 10:32:31.073  1013  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
09-07 10:32:31.073  1013  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-07 10:32:31.073  1013  1042 D Tethering: interfaceStatusChanged wlan0, false
09-07 10:32:31.073  1013  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
09-07 10:32:31.073  1013  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-07 10:32:31.073  1013  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-07 10:32:31.073  1013  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-07 10:32:31.073  1013  1042 D Tethering: interfaceLinkStateChanged wlan0, true
,09-07 10:32:31.073  1013  1042 D Tethering: interfaceStatusChanged wlan0, true
,09-07 10:32:31.073  1013  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,09-07 10:32:31.073  1013  1128 E Tethering: No numeric data
,09-07 10:32:31.073  1013  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-07 10:32:31.073  1013  1128 D Tethering: clearTetheredNotification()
,09-07 10:32:31.073  1013  1121 V NetworkStats: performPollLocked(flags=0x1)
09-07 10:32:31.073  1013  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 10:32:31.083  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED,
09-07 10:32:31.083  1013  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-07 10:32:31.083  1177  1177 D HotspotTile: updateTetherState():false, false
09-07 10:32:31.083  1013  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-07 10:32:31.083  7927  7927 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-07 10:32:31.083  1013  1121 V NetworkStats: performPollLocked() took 7ms
09-07 10:32:31.083  7927  7927 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
09-07 10:32:31.083  1013  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 10:32:31.083  7927  7927 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
09-07 10:32:31.083  7927  7927 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,09-07 10:32:31.083  7927  7927 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-07 10:32:31.083  7927  7927 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-07 10:32:31.083  7927  7927 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
,09-07 10:32:31.083  7927  7927 I wpa_supplicant: Blacklist: Clear (temp) 
09-07 10:32:31.083  7927  7927 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,09-07 10:32:31.093  1013  1042 D Tethering: interfaceLinkStateChanged wlan0, true,
09-07 10:32:31.093  1013  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,09-07 10:32:31.093  1013  1042 D Tethering: interfaceStatusChanged wlan0, true
09-07 10:32:31.093  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 10:32:31.093  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 10:32:31.093  1013  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-07 10:32:31.093  1013  1124 D SecContentProvider2: mCursor = null
,09-07 10:32:31.093  1013  1124 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-07 10:32:31.103  1013  1124 E WifiConfigStore: setLastSelectedConfiguration -1,
,09-07 10:32:31.103  1013  1124 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,09-07 10:32:31.103  1013  1126 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-07 10:32:31.103  1013  1126 E ConnectivityService: updateNetworkInfo()
09-07 10:32:31.103  1013  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-07 10:32:31.113  1013  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 10:32:31.113  1013  1026 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-07 10:32:31.113  1013  1026 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-07 10:32:31.113  1013  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:32:31.113  1013  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 10:32:31.113  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-07 10:32:31.123  1602  1602 I Hs20UtilService: Starting #21
,09-07 10:32:31.123  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-07 10:32:31.123  1602  1641 I Hs20UtilService: Message received 5007
09-07 10:32:31.123  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 10:32:31.123  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-07 10:32:31.123  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 10:32:31.123  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:31.123  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:31.123  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 10:32:31.123  4773  4773 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-07 10:32:31.123  4773  4773 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-07 10:32:31.123  4773  4773 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-07 10:32:31.123  4773  4773 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-07 10:32:31.123  4773  4773 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-07 10:32:31.123  4773  4773 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-07 10:32:31.123  4773  4865 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-07 10:32:31.133  1013  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 10:32:31.143   277  1012 D CommandListener: Setting iface cfg
,09-07 10:32:31.143  1013  1124 E WifiStateMachine: Start Dhcp Watchdog 3
,09-07 10:32:31.143  1013  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-07 10:32:31.143  1013  1124 D SecContentProvider2: mCursor = null
,09-07 10:32:31.153  1013  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-07 10:32:31.153  1013  1124 D SecContentProvider2: mCursor = null
,09-07 10:32:31.163  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
09-07 10:32:31.163  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 10:32:31.163  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-07 10:32:31.163  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:31.163  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 10:32:31.163  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:31.163  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 10:32:31.163  1013  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-07 10:32:31.163  1013  1124 D SecContentProvider2: mCursor = null
,09-07 10:32:31.173  1013  1124 E WifiNative-wlan0: do suspend false
,09-07 10:32:31.173  1013  1123 D WifiP2pService: InactiveState{ what=143375 }
,09-07 10:32:31.173  1013  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-07 10:32:31.383  7939  7939 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-07 10:32:31.393  7939  7939 I dhcpcd  : version 5.5.6 starting,
,09-07 10:32:31.393  7939  7939 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-07 10:32:31.443  7939  7939 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
09-07 10:32:31.443  7939  7939 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-07 10:32:31.443  7939  7939 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E),
09-07 10:32:31.443  7939  7939 I dhcpcd  : bssid match
09-07 10:32:31.443  7939  7939 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
,09-07 10:32:31.473  7071  7301 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1435),
09-07 10:32:31.473  7071  7301 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1435)
,09-07 10:32:31.483  7071  7301 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1440)
,09-07 10:32:31.483  7071  7301 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-07 10:32:31.483  7071  7301 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1441)
,09-07 10:32:31.483  7071  7301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
09-07 10:32:31.483  7071  7301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26a8f7d9 added. We now have 2 listener(s)
,09-07 10:32:31.483  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-07 10:32:31.483  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 10:32:31.483  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 10:32:31.483  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 10:32:31.483  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c4bd59e added. We now have 9 listener(s)
09-07 10:32:31.483  7071  7301 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 10:32:31.483  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 10:32:31.483  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 10:32:31.493  7071  7301 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 10:32:31.493  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:31.493  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:31.493  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:32:31.493  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:32:31.493  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 10:32:31.493  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 10:32:31.493  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 10:32:31.493  7071  7301 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 10:32:31.493  7071  7301 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 10:32:31.493  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:31.503  7071  7301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 10:32:31.503  7071  7301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1773c04c added. We now have 3 listener(s)
,09-07 10:32:31.503  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:31.503  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-07 10:32:31.503  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-07 10:32:31.503  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 10:32:31.503  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 10:32:31.503  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a83895 added. We now have 10 listener(s)
09-07 10:32:31.503  7071  7301 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 10:32:31.503  7071  7301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 10:32:31.503  7071  7301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 10:32:31.503  7071  7301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 10:32:31.503  7071  7301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:32:31.503  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:31.503  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 10:32:31.503  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 10:32:31.503  7071  7301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26a8f7d9 removed from the list
09-07 10:32:31.503  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:31.503  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c4bd59e removed from the list
,09-07 10:32:31.503  7071  7301 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:32:31.503  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:31.503  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:31.503  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 10:32:31.503  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:32:31.503  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:32:31.503  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:31.503  7071  7301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c4bd59e not in the list
,09-07 10:32:31.503  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:31.503  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:31.503  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:32:31.503  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 10:32:31.503  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:31.503  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a83895 removed from the list
09-07 10:32:31.503  7071  7301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:32:31.503  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 10:32:31.503  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:31.503  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-07 10:32:31.503  7071  7301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1773c04c removed from the list
09-07 10:32:31.503  7071  7301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-07 10:32:31.503  7071  7301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c1badaa added. We now have 2 listener(s)
09-07 10:32:31.513  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-07 10:32:31.513  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-07 10:32:31.513  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 10:32:31.513  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 10:32:31.513  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@222eed9b added. We now have 9 listener(s)
09-07 10:32:31.513  7071  7301 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 10:32:31.513  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 10:32:31.513  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 10:32:31.513  7071  7301 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 10:32:31.513  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:31.513  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED,
09-07 10:32:31.513  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:32:31.513  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:32:31.513  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 10:32:31.513  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 10:32:31.513  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 10:32:31.523  7071  7301 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 10:32:31.523  7071  7301 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 10:32:31.523  7071  7301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 10:32:31.523  7071  7301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2620c911 added. We now have 3 listener(s)
,09-07 10:32:31.523  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-07 10:32:31.523  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:31.523  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-07 10:32:31.523  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 10:32:31.523  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 10:32:31.523  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 10:32:31.523  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d5efa76 added. We now have 10 listener(s)
09-07 10:32:31.523  7071  7301 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 10:32:31.523  7071  7301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 10:32:31.523  7071  7301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 10:32:31.523  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 10:32:31.523  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 10:32:31.523  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 10:32:31.533  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-07 10:32:31.533  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-07 10:32:31.533  7939  7939 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1
,09-07 10:32:31.533  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 10:32:31.543  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-07 10:32:31.543  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-07 10:32:31.543  7071  7301 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-07 10:32:31.543  3222  3238 D BtGatt.GattService: registerClient() - UUID=c71d8c5f-07e1-4ae2-a16c-7315a432d3e5
,09-07 10:32:31.583  3222  3298 D BtGatt.GattService: onClientRegistered() - UUID=c71d8c5f-07e1-4ae2-a16c-7315a432d3e5, clientIf=6,
,09-07 10:32:31.593  7071  7085 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-07 10:32:31.593  3222  3299 D BtGatt.GattService: start scan with filters,
09-07 10:32:31.593  3222  3362 D BtGatt.ScanManager: handling starting scan
,09-07 10:32:31.593  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-07 10:32:31.593  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-07 10:32:31.593  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-07 10:32:31.593  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-07 10:32:31.593  3222  3298 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
,09-07 10:32:31.593  3222  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 10:32:31.593  3222  3362 D BtGatt.ScanManager: allow scan with filters
09-07 10:32:31.593  3222  3362 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-07 10:32:31.593  3222  3362 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
,09-07 10:32:31.603  3222  3298 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-07 10:32:31.603  3222  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 10:32:31.603  3222  3362 D BtGatt.ScanManager: Starting BLE batch scan
09-07 10:32:31.603  3222  3362 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-07 10:32:31.603  7071  7301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-07 10:32:31.603  3222  3298 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-07 10:32:31.603  3222  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 10:32:31.603  7071  7301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-07 10:32:31.603  7071  7071 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 10:32:31.603  3222  3298 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-07 10:32:31.603  3222  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 10:32:31.613  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 10:32:31.613  7071  7301 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-07 10:32:31.613  7071  7301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-07 10:32:31.623  7071  7301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-07 10:32:31.623  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 10:32:31.623  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 10:32:31.623  7071  7301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-07 10:32:31.623  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 10:32:31.623  7071  7301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-07 10:32:31.623  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-07 10:32:31.623  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-07 10:32:31.623  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-07 10:32:31.623  3222  7849 D BtGatt.GattService: stopScan() - queue size =1
,09-07 10:32:31.623  3222  3362 D BtGatt.ScanManager: filter size is 1
,09-07 10:32:31.623  3222  3362 D BtGatt.ScanManager: delete FilterIndex - 6
,09-07 10:32:31.623  3222  7910 D BtGatt.GattService: unregisterClient() - clientIf=6
09-07 10:32:31.633  3222  3298 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-07 10:32:31.633  3222  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 10:32:31.633  3222  3362 D BtGatt.ScanManager: stopping BLe Batch
09-07 10:32:31.633  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-07 10:32:31.633  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-07 10:32:31.633  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-07 10:32:31.633  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-07 10:32:31.633  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-07 10:32:31.633  7071  7301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 10:32:31.633  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 10:32:31.633  7071  7301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 10:32:31.633  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 10:32:31.633  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 10:32:31.633  7071  7071 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 10:32:31.633  7071  7071 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 10:32:31.633  7071  7071 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 10:32:31.633  3222  3298 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-07 10:32:31.633  3222  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 10:32:31.633  3222  3362 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-07 10:32:31.633  3222  3298 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-07 10:32:31.633  3222  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 10:32:31.643  7071  7301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 10:32:31.643  7071  7301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 10:32:31.643  7071  7301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 10:32:31.643  7071  7301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 10:32:31.643  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 10:32:31.643  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 10:32:31.643  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-07 10:32:31.643  7071  7301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c1badaa removed from the list
,09-07 10:32:31.643  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:31.643  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@222eed9b removed from the list
,09-07 10:32:31.643  7071  7301 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:32:31.643  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 10:32:31.643  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 10:32:31.643  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 10:32:31.653  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
09-07 10:32:31.653  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:32:31.653  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:31.653  7071  7301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@222eed9b not in the list
09-07 10:32:31.653  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 10:32:31.653  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 10:32:31.653  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-07 10:32:31.653  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 10:32:31.653  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 10:32:31.653  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d5efa76 removed from the list
09-07 10:32:31.653  7071  7301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 10:32:31.653  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:31.653  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 10:32:31.653  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 10:32:31.653  7071  7301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2620c911 removed from the list
,09-07 10:32:31.653  7071  7301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-07 10:32:31.653  7071  7301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ab84802 added. We now have 2 listener(s)
,09-07 10:32:31.663  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-07 10:32:31.663  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-07 10:32:31.663  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-07 10:32:31.663  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 10:32:31.663  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f37513 added. We now have 9 listener(s)
,09-07 10:32:31.663  7071  7301 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 10:32:31.663  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 10:32:31.673  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 10:32:31.673  7071  7301 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 10:32:31.673  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:31.673  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:31.673  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:32:31.673  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:32:31.673  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 10:32:31.673  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 10:32:31.673  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 10:32:31.673  7071  7301 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 10:32:31.673  7071  7301 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 10:32:31.673  7071  7301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 10:32:31.673  7071  7301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@192a8949 added. We now have 3 listener(s)
,09-07 10:32:31.673  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:31.683  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:31.683  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-07 10:32:31.683  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 10:32:31.683  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 10:32:31.683  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 10:32:31.683  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2466e24e added. We now have 10 listener(s)
09-07 10:32:31.683  7071  7301 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 10:32:31.683  7071  7301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 10:32:31.683  7071  7301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 10:32:31.683  7071  7301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 10:32:31.683  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 10:32:31.683  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 10:32:31.683  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 10:32:31.683  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-07 10:32:31.693  7939  7939 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds
,09-07 10:32:31.703  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 10:32:31.703  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 10:32:31.703  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
09-07 10:32:31.703  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-07 10:32:31.703  7071  7301 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-07 10:32:31.713  3222  3359 D BtGatt.GattService: registerClient() - UUID=6ae0c10f-11b5-403d-bcf4-1d52584805b0
,09-07 10:32:31.753  3222  3298 D BtGatt.GattService: onClientRegistered() - UUID=6ae0c10f-11b5-403d-bcf4-1d52584805b0, clientIf=6,
09-07 10:32:31.753  7071  7084 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-07 10:32:31.753  3222  7849 D BtGatt.GattService: start scan with filters
,09-07 10:32:31.763  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
09-07 10:32:31.763  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-07 10:32:31.763  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-07 10:32:31.763  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-07 10:32:31.763  3222  3362 D BtGatt.ScanManager: handling starting scan
,09-07 10:32:31.763   292   292 E SMD     : DCD OFF
09-07 10:32:31.763  7071  7301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-07 10:32:31.763  7071  7071 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-07 10:32:31.763  7071  7301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-07 10:32:31.773  3222  3298 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-07 10:32:31.773  3222  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 10:32:31.773  3222  3362 D BtGatt.ScanManager: allow scan with filters,
09-07 10:32:31.773  3222  3362 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-07 10:32:31.773  3222  3362 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
09-07 10:32:31.773  3222  3298 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-07 10:32:31.773  3222  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 10:32:31.773  3222  3362 D BtGatt.ScanManager: Starting BLE batch scan
09-07 10:32:31.773  3222  3362 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-07 10:32:31.773  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 10:32:31.783  3222  3298 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-07 10:32:31.783  3222  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 10:32:31.783  3222  3298 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
09-07 10:32:31.783  3222  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 10:32:31.793  7071  7301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 10:32:31.793  7071  7301 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-07 10:32:31.793  7071  7301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:32:31.793  7071  7301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:32:31.793  7071  7301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:32:31.793  7071  7301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:32:31.793  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:31.793  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 10:32:31.793  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 10:32:31.793  7071  7301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ab84802 removed from the list
09-07 10:32:31.793  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:31.793  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f37513 removed from the list
09-07 10:32:31.793  7071  7301 D io.jxcore.node.ConnectivityMonitor: stop
09-07 10:32:31.793  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 10:32:31.793  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:31.793  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-07 10:32:31.793  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:31.793  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 10:32:31.793  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:32:31.793  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-07 10:32:31.793  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:31.793  7071  7301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f37513 not in the list
09-07 10:32:31.793  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 10:32:31.793  7071  7301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 10:32:31.793  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 10:32:31.793  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 10:32:31.793  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-07 10:32:31.793  3222  3299 D BtGatt.GattService: stopScan() - queue size =1,
,09-07 10:32:31.793  3222  3234 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-07 10:32:31.803  3222  3362 D BtGatt.ScanManager: filter size is 1
09-07 10:32:31.803  3222  3362 D BtGatt.ScanManager: delete FilterIndex - 7
09-07 10:32:31.803  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 10:32:31.803  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-07 10:32:31.803  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-07 10:32:31.803  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-07 10:32:31.803  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED],
09-07 10:32:31.803  3222  3298 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-07 10:32:31.803  3222  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 10:32:31.803  3222  3362 D BtGatt.ScanManager: stopping BLe Batch
09-07 10:32:31.803  7071  7301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 10:32:31.803  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-07 10:32:31.803  7071  7301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 10:32:31.803  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 10:32:31.803  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 10:32:31.813  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-07 10:32:31.813  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
09-07 10:32:31.813  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:31.813  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2466e24e removed from the list
09-07 10:32:31.813  7071  7301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:32:31.813  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-07 10:32:31.813  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:31.813  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 10:32:31.813  7071  7301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@192a8949 removed from the list
,09-07 10:32:31.813  7071  7071 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 10:32:31.813  7071  7071 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 10:32:31.813  7071  7071 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 10:32:31.813  7071  7301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
09-07 10:32:31.813  7071  7301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d52d55a added. We now have 2 listener(s)
09-07 10:32:31.813  3222  3298 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-07 10:32:31.813  3222  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 10:32:31.813  3222  3362 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6,
,09-07 10:32:31.823  3222  3298 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-07 10:32:31.823  3222  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 10:32:31.823  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-07 10:32:31.823  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 10:32:31.823  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 10:32:31.823  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 10:32:31.823  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16e2738b added. We now have 9 listener(s)
09-07 10:32:31.823  7071  7301 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 10:32:31.823  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 10:32:31.833  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 10:32:31.843  7071  7301 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 10:32:31.843  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:31.843  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:31.843  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:32:31.843  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:32:31.843  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 10:32:31.843  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 10:32:31.843  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 10:32:31.843  7071  7301 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 10:32:31.843  7071  7301 D io.jxcore.node.ConnectivityMonitor: start: OK,
09-07 10:32:31.843  7071  7301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 10:32:31.843  7071  7301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24351881 added. We now have 3 listener(s)
,09-07 10:32:31.843  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:31.843  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:31.843  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41",
09-07 10:32:31.843  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 10:32:31.843  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
09-07 10:32:31.843  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 10:32:31.843  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cd8ed26 added. We now have 10 listener(s),
09-07 10:32:31.843  7071  7301 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
09-07 10:32:31.843  7071  7301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 10:32:31.843  7071  7301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 10:32:31.843  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false,
09-07 10:32:31.843  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 10:32:31.843  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 10:32:31.863  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-07 10:32:31.863  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-07 10:32:31.863  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 10:32:31.873  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-07 10:32:31.873  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-07 10:32:31.873  7071  7301 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-07 10:32:31.873  3222  3359 D BtGatt.GattService: registerClient() - UUID=dd121289-4805-45e4-aaa1-c01f78110e1c
,09-07 10:32:31.923  3222  3298 D BtGatt.GattService: onClientRegistered() - UUID=dd121289-4805-45e4-aaa1-c01f78110e1c, clientIf=6,
09-07 10:32:31.923  7071  7084 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-07 10:32:31.923  3222  7849 D BtGatt.GattService: start scan with filters,
09-07 10:32:31.923  3222  3362 D BtGatt.ScanManager: handling starting scan
09-07 10:32:31.923  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-07 10:32:31.923  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-07 10:32:31.923  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-07 10:32:31.923  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-07 10:32:31.923  3222  3298 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-07 10:32:31.923  3222  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 10:32:31.923  3222  3362 D BtGatt.ScanManager: allow scan with filters
09-07 10:32:31.923  3222  3362 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-07 10:32:31.923  3222  3362 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6
09-07 10:32:31.923  3222  3298 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-07 10:32:31.923  3222  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 10:32:31.923  3222  3362 D BtGatt.ScanManager: Starting BLE batch scan
09-07 10:32:31.923  3222  3362 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
09-07 10:32:31.933  7071  7301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-07 10:32:31.933  3222  3298 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-07 10:32:31.933  3222  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 10:32:31.933  7071  7301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-07 10:32:31.933  7071  7071 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 10:32:31.933  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 10:32:31.933  3222  3298 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
09-07 10:32:31.933  3222  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 10:32:31.943  7071  7301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 10:32:31.943  7071  7301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 10:32:31.943  7071  7301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 10:32:31.943  7071  7301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 10:32:31.943  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:31.943  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-07 10:32:31.943  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 10:32:31.943  7071  7301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d52d55a removed from the list
09-07 10:32:31.943  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 10:32:31.943  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16e2738b removed from the list
09-07 10:32:31.943  7071  7301 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 10:32:31.943  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 10:32:31.943  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,09-07 10:32:31.943  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-07 10:32:31.943  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 10:32:31.943  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 10:32:31.953  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 10:32:31.953  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:32:31.953  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 10:32:31.953  7071  7301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16e2738b not in the list
09-07 10:32:31.953  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 10:32:31.953  7071  7301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-07 10:32:31.953  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-07 10:32:31.953  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
09-07 10:32:31.953  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-07 10:32:31.953  3222  3359 D BtGatt.GattService: stopScan() - queue size =1
,09-07 10:32:31.953  3222  7849 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-07 10:32:31.953  3222  3362 D BtGatt.ScanManager: filter size is 1
09-07 10:32:31.953  3222  3362 D BtGatt.ScanManager: delete FilterIndex - 8
,09-07 10:32:31.953  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 10:32:31.953  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-07 10:32:31.953  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-07 10:32:31.953  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-07 10:32:31.953  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-07 10:32:31.953  3222  3298 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-07 10:32:31.953  3222  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 10:32:31.963  3222  3362 D BtGatt.ScanManager: stopping BLe Batch
09-07 10:32:31.963  7071  7301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 10:32:31.963  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 10:32:31.963  7071  7301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 10:32:31.963  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-07 10:32:31.963  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 10:32:31.963  7071  7071 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 10:32:31.963  7071  7071 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 10:32:31.963  7071  7071 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 10:32:31.963  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:32:31.963  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:32:31.963  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:31.963  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cd8ed26 removed from the list
09-07 10:32:31.963  7071  7301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:32:31.963  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:31.963  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:31.963  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 10:32:31.963  7071  7301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24351881 removed from the list
,09-07 10:32:31.963  7071  7301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 10:32:31.963  7071  7301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3156b5b2 added. We now have 2 listener(s)
,09-07 10:32:31.963  3222  3298 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-07 10:32:31.963  3222  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 10:32:31.963  3222  3362 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-07 10:32:31.963  3222  3298 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-07 10:32:31.963  3222  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 10:32:31.973  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-07 10:32:31.973  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 10:32:31.973  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 10:32:31.973  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 10:32:31.973  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26f3c903 added. We now have 9 listener(s)
09-07 10:32:31.973  7071  7301 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 10:32:31.973  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 10:32:31.973  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 10:32:31.973  7071  7301 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 10:32:31.973  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 10:32:31.973  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 10:32:31.973  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 10:32:31.973  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 10:32:31.973  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 10:32:31.973  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 10:32:31.973  7071  7301 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 10:32:31.983  7071  7301 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 10:32:31.983  7071  7301 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 10:32:31.983  7071  7301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 10:32:31.983  7071  7301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2eab56b9 added. We now have 3 listener(s)
,09-07 10:32:31.983  1013  1124 E WifiNative-wlan0: do suspend true
,09-07 10:32:31.983  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:31.983  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-07 10:32:31.983  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 10:32:31.983  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 10:32:31.983  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 10:32:31.983  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f767afe added. We now have 10 listener(s)
09-07 10:32:31.983  7071  7301 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 10:32:31.983  7071  7301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 10:32:31.983  7071  7301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 10:32:31.983  7071  7301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 10:32:31.983  7071  7301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:32:31.983  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:31.983  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 10:32:31.983  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 10:32:31.983  7071  7301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3156b5b2 removed from the list
09-07 10:32:31.983  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 10:32:31.983  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26f3c903 removed from the list
,09-07 10:32:31.983  7071  7071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 10:32:31.983  7071  7301 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 10:32:31.983  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 10:32:31.983  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 10:32:31.983  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 10:32:31.993  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 10:32:31.993  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 10:32:31.993  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 10:32:31.993  7071  7301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26f3c903 not in the list
09-07 10:32:31.993  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 10:32:31.993  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 10:32:31.993  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-07 10:32:31.993  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 10:32:31.993  7071  7301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 10:32:31.993  7071  7301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f767afe removed from the list
09-07 10:32:31.993  7071  7301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 10:32:31.993  7071  7301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 10:32:31.993  7071  7301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 10:32:31.993  7071  7301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 10:32:31.993  7071  7301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2eab56b9 removed from the list
,09-07 10:32:31.993  7071  7301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,09-07 10:32:31.993  7071  7301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-07 10:32:31.993  7071  7301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,09-07 10:32:31.993  7071  7301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 10:32:31.993  7071  7301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-07 10:32:31.993  7071  7301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-07 10:32:32.003  7071  7972 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1448, name: My test thread name)
,09-07 10:32:32.003  7071  7972 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1448, thread name: My test thread name)
,09-07 10:32:32.003  7071  7972 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1448, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-07 10:32:32.003  7071  7973 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1450, name: My test thread name)
,09-07 10:32:32.003  7071  7973 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1450, thread name: My test thread name)
09-07 10:32:32.003  7071  7973 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1450, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-07 10:32:32.003  7071  7301 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-07 10:32:32.003  7071  7301 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-07 10:32:32.003  7071  7301 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
,09-07 10:32:32.013  7071  7301 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-07 10:32:32.013  7071  7301 D com.test.thalitest.ThaliTestRunner: Total duration: 23380 ms
,09-07 10:32:32.013  1013  1123 D WifiP2pService: InactiveState{ what=143375 }
09-07 10:32:32.013  7071  7301 I jxcore-log: *Native tests were executed*
09-07 10:32:32.013  7071  7301 I jxcore-log: 
09-07 10:32:32.013  1013  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
09-07 10:32:32.013  7071  7301 I jxcore-log: Total number of executed tests:  80
09-07 10:32:32.013  7071  7301 I jxcore-log: 
,09-07 10:32:32.013  7071  7301 I jxcore-log: Number of passed tests:  80
09-07 10:32:32.013  7071  7301 I jxcore-log: 
09-07 10:32:32.013  7071  7301 I jxcore-log: Number of failed tests:  0
09-07 10:32:32.013  7071  7301 I jxcore-log: 
09-07 10:32:32.013  7071  7301 I jxcore-log: Number of ignored tests:  0
09-07 10:32:32.013  7071  7301 I jxcore-log: 
,09-07 10:32:32.013  1013  1124 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-07 10:32:32.013  7071  7301 I jxcore-log: Total duration:  23380
09-07 10:32:32.013  7071  7301 I jxcore-log: 
09-07 10:32:32.013  1013  1124 E WifiStateMachine: VerifyingLinkState enter
09-07 10:32:32.013  7071  7301 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-07 10:32:32.013  7071  7301 I jxcore-log: 
,09-07 10:32:32.013  7071  7301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 10:32:32.013  7071  7301 I jxcore-log: 
09-07 10:32:32.013  7071  7301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 10:32:32.013  7071  7301 I jxcore-log: 
09-07 10:32:32.013  7071  7301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 10:32:32.013  7071  7301 I jxcore-log: 
09-07 10:32:32.023  7071  7301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 10:32:32.023  7071  7301 I jxcore-log: 
09-07 10:32:32.023  7071  7301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 10:32:32.023  7071  7301 I jxcore-log: 
09-07 10:32:32.023  7071  7301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 10:32:32.023  7071  7301 I jxcore-log: 
09-07 10:32:32.023  7071  7301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 10:32:32.023  7071  7301 I jxcore-log: 
09-07 10:32:32.023  7071  7301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 10:32:32.023  7071  7301 I jxcore-log: 
09-07 10:32:32.023  7071  7301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 10:32:32.023  7071  7301 I jxcore-log: 
09-07 10:32:32.023  7071  7301 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 10:32:32.023  7071  7301 I jxcore-log: 
09-07 10:32:32.033  7071  7301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 10:32:32.033  7071  7301 I jxcore-log: 
09-07 10:32:32.033  7071  7301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 10:32:32.033  7071  7301 I jxcore-log: 
09-07 10:32:32.033  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-07 10:32:32.033  7071  7301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 10:32:32.033  7071  7301 I jxcore-log: 
09-07 10:32:32.033  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 10:32:32.033  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-07 10:32:32.033  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:32.033  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:32.033  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:32.033  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:32.033  7071  7301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 10:32:32.033  7071  7301 I jxcore-log: 
09-07 10:32:32.033  7071  7301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 10:32:32.033  7071  7301 I jxcore-log: 
09-07 10:32:32.033  7071  7301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 10:32:32.033  7071  7301 I jxcore-log: 
09-07 10:32:32.033  1013  1126 E ConnectivityService: updateNetworkInfo()
09-07 10:32:32.033  7071  7301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 10:32:32.033  7071  7301 I jxcore-log: 
09-07 10:32:32.033  7071  7301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 10:32:32.033  7071  7301 I jxcore-log: 
,09-07 10:32:32.033  7071  7301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 10:32:32.033  7071  7301 I jxcore-log: 
09-07 10:32:32.033  1013  1126 D ConnectivityService: Adding iface wlan0 to network 504
09-07 10:32:32.033  7071  7301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 10:32:32.033  7071  7301 I jxcore-log: 
09-07 10:32:32.033  1013  1126 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
09-07 10:32:32.033  7071  7301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 10:32:32.033  7071  7301 I jxcore-log: 
,09-07 10:32:32.033  7071  7301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 10:32:32.033  7071  7301 I jxcore-log: 
09-07 10:32:32.033  7071  7301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 10:32:32.033  7071  7301 I jxcore-log: 
09-07 10:32:32.033  7071  7071 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-07 10:32:32.043  7071  7301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 10:32:32.043  7071  7301 I jxcore-log: 
09-07 10:32:32.043  7071  7301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 10:32:32.043  7071  7301 I jxcore-log: 
09-07 10:32:32.043  7071  7301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 10:32:32.043  7071  7301 I jxcore-log: 
09-07 10:32:32.043  7071  7301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 10:32:32.043  7071  7301 I jxcore-log: 
,09-07 10:32:32.043  1013  1143 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,09-07 10:32:32.043  1013  1143 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-07 10:32:32.043  1013  1143 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-07 10:32:32.043  1013  1143 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-07 10:32:32.043  1013  1143 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-07 10:32:32.053  1013  1124 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,09-07 10:32:32.053  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-07 10:32:32.063  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 10:32:32.063  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-07 10:32:32.063  1013  1321 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-07 10:32:32.063  1013  1321 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-07 10:32:32.063  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:32.063  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:32.063  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:32.063  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:32.063  1013  1321 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:32:32.063  1013  1321 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:32.063  1013  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-07 10:32:32.063  4773  4773 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-07 10:32:32.063  4773  4773 I NearbySettings: MountReceiver.onReceive - Keep current state
09-07 10:32:32.063  1602  1602 I Hs20UtilService: Starting #22
,09-07 10:32:32.073  1602  1641 I Hs20UtilService: Message received 5007
,09-07 10:32:32.073  1013  1126 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,09-07 10:32:32.073  1013  1126 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,09-07 10:32:32.073  1013  1126 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
,09-07 10:32:32.073  1013  1126 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-07 10:32:32.073  1013  1013 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-07 10:32:32.073  1013  1126 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
,09-07 10:32:32.073  1013  1126 D ConnectivityService: LTETest block dns file not exists
,09-07 10:32:32.083  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-07 10:32:32.083  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-07 10:32:32.083  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-07 10:32:32.083  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 10:32:32.083  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:32.083  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-07 10:32:32.083  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:32.093  1013  1126 V NetworkStats: updateIfacesLocked()
09-07 10:32:32.093  1013  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 10:32:32.093  1013  1126 V NetworkStats: performPollLocked(flags=0x1)
,09-07 10:32:32.093  1013  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
09-07 10:32:32.093  1013  1126 V NetworkStats: performPollLocked() took 4ms
09-07 10:32:32.093  1013  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-07 10:32:32.093  1013  1124 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-07 10:32:32.093  1013  1124 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-07 10:32:32.093  1013  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 10:32:32.093  1013  1013 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-07 10:32:32.093  1013  1013 I WifiTrafficPoller: mBoosterFLAG : 0
09-07 10:32:32.093  1013  1013 I WifiTrafficPoller: current booster mode : FullMode
,09-07 10:32:32.103  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-07 10:32:32.103  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-07 10:32:32.103  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:32.103  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:32.103  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:32.103  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 10:32:32.103  1013  1126 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
09-07 10:32:32.103  1013  1126 E ConnectivityService: updateNetworkInfo()
09-07 10:32:32.103  1013  1126 E ConnectivityService: updateNetworkInfo()
09-07 10:32:32.103  1013  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 10:32:32.113  1013  1126 D NtpTrustedTime: currentTimeMillis() cache hit,
09-07 10:32:32.113  1013  1126 V NetworkStats: updateIfacesLocked()
09-07 10:32:32.113  1013  1126 V NetworkStats: performPollLocked(flags=0x1)
09-07 10:32:32.113  1013  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
09-07 10:32:32.113  1013  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-07 10:32:32.113  1013  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 10:32:32.113  1013  1126 V NetworkStats: performPollLocked() took 4ms
,09-07 10:32:32.113  1013  1504 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-07 10:32:32.113  1013  1504 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-07 10:32:32.123  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 10:32:32.123  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 10:32:32.123  1013  1504 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:32.123  1013  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:32.123  1013  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-07 10:32:32.123  1602  1602 I Hs20UtilService: Starting #23
,09-07 10:32:32.123  1602  1641 I Hs20UtilService: Message received 5007
09-07 10:32:32.123  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 10:32:32.123  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 10:32:32.123  4773  4773 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-07 10:32:32.123  4773  4773 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-07 10:32:32.123  4773  4773 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-07 10:32:32.123  1013  1126 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
09-07 10:32:32.123  1013  1126 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
,09-07 10:32:32.123  1013  7937 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:32:32.123  1013  7937 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
09-07 10:32:32.123  1013  7937 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-07 10:32:32.123  4773  4773 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-07 10:32:32.123  4773  4773 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-07 10:32:32.123  1013  7937 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
09-07 10:32:32.133  1013  1126 D ConnectivityService:    accepting network in place of null
09-07 10:32:32.123  4773  4773 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-07 10:32:32.123  4773  4865 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-07 10:32:32.123  1013  7937 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-07 10:32:32.133   277  1008 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-07 10:32:32.133   277  1008 D Netd    : getNetworkForDns: using netid 504 for uid 1000
09-07 10:32:32.133  1465  1465 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-07 10:32:32.133  1013  1126 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
09-07 10:32:32.133  1013  1123 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-07 10:32:32.133  1013  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-07 10:32:32.133  1465  1465 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 10:32:32.133  1013  1126 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-07 10:32:32.133  1013  1124 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-07 10:32:32.133  7071  7071 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 10:32:32.133  1013  7937 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
09-07 10:32:32.133  1013  7937 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
09-07 10:32:32.133  7071  7301 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 10:32:32.133  7071  7301 I jxcore-log: 
,09-07 10:32:32.143  1013  1126 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} },
,09-07 10:32:32.143  1013  1013 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-07 10:32:32.143  1013  1126 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
09-07 10:32:32.143  1013  1128 D Tethering: MasterInitialState.processMessage what=3
,09-07 10:32:32.143  1177  1756 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-07 10:32:32.143  1013  1126 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
09-07 10:32:32.143  1013  1126 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
09-07 10:32:32.143  1013  1126 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
09-07 10:32:32.143  1177  1756 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-07 10:32:32.143  1013  1126 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504],
09-07 10:32:32.143  1013  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 10:32:32.143  1013  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-07 10:32:32.143  1013  1121 V NetworkStats: updateIfacesLocked()
09-07 10:32:32.143  1013  1121 V NetworkStats: performPollLocked(flags=0x1)
09-07 10:32:32.143  1013  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-07 10:32:32.143  1013  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-07 10:32:32.143  1013  1218 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-07 10:32:32.143  1013  1218 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-07 10:32:32.143  1013  1218 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:32.143  1013  1121 V NetworkStats: performPollLocked() took 3ms
09-07 10:32:32.143  1013  1218 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:32.143  1013  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-07 10:32:32.143  1177  1177 D StatusBar.NetworkController: EthernetConnected: false
09-07 10:32:32.143  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-07 10:32:32.143  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-07 10:32:32.143  1177  1177 D StatusBar.NetworkController: updateDataNetType()
09-07 10:32:32.143  1602  1602 I Hs20UtilService: Starting #24
09-07 10:32:32.143  1013  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 10:32:32.143  1602  1641 I Hs20UtilService: Message received 5007
,09-07 10:32:32.153  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 10:32:32.153  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 10:32:32.153  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 10:32:32.153  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 10:32:32.153  1013  1122 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-07 10:32:32.153  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-07 10:32:32.153  1177  1177 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-07 10:32:32.153  4773  4773 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-07 10:32:32.153  1177  1177 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-07 10:32:32.153  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 25 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
09-07 10:32:32.153  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
09-07 10:32:32.153  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,09-07 10:32:32.153  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 10:32:32.153  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-07 10:32:32.153  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:32.153  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:32.153  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:32.153  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:32.153  4773  4773 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-07 10:32:32.153  1177  1177 D StatusBar.NetworkController: EthernetConnected: false
09-07 10:32:32.153  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-07 10:32:32.153  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-07 10:32:32.153  1177  1177 D StatusBar.NetworkController: updateDataNetType()
09-07 10:32:32.163  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 10:32:32.163  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 10:32:32.163  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-07 10:32:32.163  1177  1177 E StatusBar.NetworkController: updateLTEICONDataNetType:0
09-07 10:32:32.163  1177  1177 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-07 10:32:32.163  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 25 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
09-07 10:32:32.163  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
09-07 10:32:32.163  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
09-07 10:32:32.163  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 10:32:32.163  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-07 10:32:32.163  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:32.163  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:32.163  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 10:32:32.163  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 10:32:32.163  1013  1218 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,09-07 10:32:32.163  1013  1496 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
09-07 10:32:32.163  1013  1496 D SecContentProvider2: mCursor = null
09-07 10:32:32.173  1013  3836 D SecContentProvider2: uri = 15 selection = getToastGravity
09-07 10:32:32.173  1013  3836 D SecContentProvider2: mCursor = null
,09-07 10:32:32.173  1013  1025 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
09-07 10:32:32.173  1013  1025 D SecContentProvider2: mCursor = null
09-07 10:32:32.173  1013  1481 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
09-07 10:32:32.173  1013  1481 D SecContentProvider2: mCursor = null
,09-07 10:32:32.173  1013  1543 D SecContentProvider2: uri = 15 selection = getToastEnabledState
09-07 10:32:32.173  1013  1543 D SecContentProvider2: mCursor = null
,09-07 10:32:32.173  1013  1133 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
09-07 10:32:32.173  1013  1133 D SecContentProvider2: mCursor = null
,09-07 10:32:32.203   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,09-07 10:32:32.213  1013  1496 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1013
,09-07 10:32:32.223  1177  1177 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! ,
,09-07 10:32:32.293  7976  7976 D AndroidRuntime: 
09-07 10:32:32.293  7976  7976 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-07 10:32:32.293  7976  7976 D AndroidRuntime: CheckJNI is OFF
,09-07 10:32:32.293  7976  7976 D AndroidRuntime: readGMSProperty: start
09-07 10:32:32.293  7976  7976 D AndroidRuntime: readGMSProperty: already setted!!
,09-07 10:32:32.293  7976  7976 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-07 10:32:32.293  7976  7976 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-07 10:32:32.293  7976  7976 D AndroidRuntime: readGMSProperty: end
09-07 10:32:32.293  7976  7976 D AndroidRuntime: addProductProperty: start
,09-07 10:32:32.313  7071  7071 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 10:32:32.313  7071  7301 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 10:32:32.313  7071  7301 I jxcore-log: 
,09-07 10:32:32.413  7976  7976 E AffinityControl: AffinityControl: registerfunction enter,
,09-07 10:32:32.443  7976  7976 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-07 10:32:32.463  7071  7071 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 10:32:32.463  7071  7301 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 10:32:32.463  7071  7301 I jxcore-log: 
,09-07 10:32:32.463  1013  1479 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
09-07 10:32:32.463  1013  1479 D PackageManager: START PACKAGE DELETE: observer{666243468}
09-07 10:32:32.463  1013  1479 D PackageManager: pkg{<packageName>}
09-07 10:32:32.463  1013  1479 D PackageManager: user{0}
09-07 10:32:32.463  1013  1479 D PackageManager: caller{2000}
09-07 10:32:32.463  1013  1479 D PackageManager: flags{2}
09-07 10:32:32.463  1013  1479 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-07 10:32:32.463  1013  1479 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,09-07 10:32:32.463  1013  1479 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-07 10:32:32.463  1013  1479 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,09-07 10:32:32.473  1013  1054 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0,
09-07 10:32:32.473  1013  1054 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-07 10:32:32.473  1013  1054 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-07 10:32:32.473  1013  1054 D ApplicationPolicy: getApplicationUninstallationEnabled
09-07 10:32:32.473  1013  1054 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-07 10:32:32.473  1013  1054 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
,09-07 10:32:32.493  1013  1040 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
,09-07 10:32:32.493  1013  1040 I ActivityManager: Killing 7071:com.test.thalitest/u0a170 (adj 0): stop com.test.thalitest cause uninstall pkg
,09-07 10:32:32.573  1013  1504 I WindowState: WIN DEATH: Window{264d309d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-07 10:32:32.573   257   448 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
,09-07 10:32:32.573   257  1095 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,09-07 10:32:32.583  1013  1504 D InputDispatcher: Focus left window: 7071
,09-07 10:32:32.593  1013  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-07 10:32:32.593  1013  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-07 10:32:32.603  1013  1040 I ActivityManager:   Force finishing activity ActivityRecord{35aededd u0 com.test.thalitest/.MainActivity t163}
,09-07 10:32:32.613  1013  1479 W ActivityManager: Spurious death for ProcessRecord{2650d5 7071:com.test.thalitest/u0a170}, curProc for 7071: null
,09-07 10:32:32.633  1013  1040 D InputDispatcher: Focused application released
,09-07 10:32:32.633  1013  1054 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,09-07 10:32:32.643  1013  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,09-07 10:32:32.643  1013  1054 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,09-07 10:32:32.673  1013  1097 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-07 10:32:32.683  1747  1995 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-07 10:32:32.693  1899  1899 E SamsungIME: mOCRHelper is null
,09-07 10:32:32.693  1013  1047 I PowerManagerService: [PWL] Off : 75s ago
09-07 10:32:32.693  1013  1047 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
09-07 10:32:32.693  1013  1047 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
09-07 10:32:32.693  2841  2841 I art     : Explicit concurrent mark sweep GC freed 17386(1024KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 824us total 37.907ms
09-07 10:32:32.693  1013  1047 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1013, ws=null) (elapsedTime=23281)
,09-07 10:32:32.693  2825  2825 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Sep 07 10:32:32 GMT+02:00 2016
,09-07 10:32:32.723  1013  1013 D RCPManagerService: PackageReceiver onReceive()
,09-07 10:32:32.723  1013  3836 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-07 10:32:32.733  1013  3836 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-07 10:32:32.733  1013  1013 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,09-07 10:32:32.733  1013  3836 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:32:32.733  1013  3836 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:32.733  1013  3836 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-07 10:32:32.733  1013  1013 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,09-07 10:32:32.733  1013  1013 I OTPFW   : PackageRemovalReceiver::onReceive Enter
09-07 10:32:32.733  1013  1013 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,09-07 10:32:32.743  1444  1444 D PersonaManager: isKioskContainerExistOnDevice
,09-07 10:32:32.743  2825  2825 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-07 10:32:32.753  1013  1121 V NetworkStats: removeUidsLocked() for UIDs [10170]
09-07 10:32:32.753  1013  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 10:32:32.753  1013  1121 V NetworkStats: performPollLocked(flags=0x3)
,09-07 10:32:32.753  1013  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-07 10:32:32.753  1013  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-07 10:32:32.763  1013  1013 I OTPFW   : ProvisionData::getAllEntries Enter
,09-07 10:32:32.763  1013  1013 E OTPFW   : ProvisionData::getAllEntries Table is empty
,09-07 10:32:32.763  1013  1121 V NetworkStats: performPollLocked() took 10ms
09-07 10:32:32.763  1013  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 10:32:32.763  2825  2825 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,09-07 10:32:32.783  1013  1218 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=22, mSplitNum[2]=32, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=42
09-07 10:32:32.783  1013  1218 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,09-07 10:32:32.783  1444  1444 D RegisteredServicesCache: empty dynamic service
,09-07 10:32:32.783  1013  1218 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,09-07 10:32:32.793  2825  2825 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
09-07 10:32:32.793  1013  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:32.793  1013  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:32.793  1013  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:32.793  1013  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:32.803  1013  1323 E Watchdog: !@Sync 4
,09-07 10:32:32.803  7992  7992 E Zygote  : MountEmulatedStorage()
09-07 10:32:32.803  7992  7992 I libpersona: KNOX_SDCARD checking this for 10090
09-07 10:32:32.803  7992  7992 E Zygote  : v2
09-07 10:32:32.803  7992  7992 I libpersona: KNOX_SDCARD not a persona
,09-07 10:32:32.803  7992  7992 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 10:32:32.803  1013  1218 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7992 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,09-07 10:32:32.813  7992  7992 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-07 10:32:32.813  7992  7992 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 10:32:32.823  2825  2825 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-07 10:32:32.833  2825  7991 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-07 10:32:32.843  2825  7991 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,09-07 10:32:32.853  1013  1039 D EnterpriseDeviceManagerService: Package has changed for user 0
,09-07 10:32:32.853  1013  1039 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,09-07 10:32:32.853  1013  1039 W TextServicesManagerService: no available spell checker services found
,09-07 10:32:32.853  7992  7992 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 10:32:32.853  7992  7992 D ActivityThread: Added TimaKeyStore provider
,09-07 10:32:32.853  1444  1444 D RegisteredComponentCache: Collect Tech packages for Knox
,09-07 10:32:32.863  2825  7991 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,09-07 10:32:32.863  2825  7991 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
09-07 10:32:32.863  1013  1133 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-07 10:32:32.863  1013  1133 D SecContentProvider2: mCursor = null
,09-07 10:32:32.873  1444  1444 D PersonaManager: isKioskContainerExistOnDevice
,09-07 10:32:32.893  1013  1040 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,09-07 10:32:32.893  1013  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:32.893  1013  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:32.893  1013  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:32.893  1013  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:32.903  8007  8007 E Zygote  : MountEmulatedStorage()
09-07 10:32:32.903  8007  8007 E Zygote  : v2
09-07 10:32:32.903  8007  8007 I libpersona: KNOX_SDCARD checking this for 10052
09-07 10:32:32.903  8007  8007 I libpersona: KNOX_SDCARD not a persona
09-07 10:32:32.903  8007  8007 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 10:32:32.913  8007  8007 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 10:32:32.913  1013  1040 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=8007 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
09-07 10:32:32.913  8007  8007 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-07 10:32:32.913  1013  1040 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,09-07 10:32:32.923  1013  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:32.923  1013  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:32.923  1013  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:32.923  1013  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:32.943  8022  8022 E Zygote  : MountEmulatedStorage()
,09-07 10:32:32.943  8022  8022 E Zygote  : v2,
09-07 10:32:32.943  8022  8022 I libpersona: KNOX_SDCARD checking this for 10098
09-07 10:32:32.943  8022  8022 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 10:32:32.943  8022  8022 I libpersona: KNOX_SDCARD not a persona
09-07 10:32:32.943  1013  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-07 10:32:32.943  8022  8022 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 10:32:32.953  8022  8022 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 10:32:32.953  8007  8007 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 10:32:32.953  8007  8007 D ActivityThread: Added TimaKeyStore provider
,09-07 10:32:32.953  1013  1040 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=8022 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,09-07 10:32:32.963  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 10:32:32.963  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 10:32:32.973   314   314 I art     : Explicit concurrent mark sweep GC freed 8691(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 626us total 22.597ms
,09-07 10:32:32.973  8022  8022 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 10:32:32.983  8022  8022 D ActivityThread: Added TimaKeyStore provider
,09-07 10:32:32.993  7992  7992 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,09-07 10:32:32.993   314   314 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 586us total 16.746ms
,09-07 10:32:32.993  7992  7992 D elm:15121: ELMEngine.ELMEngine( context ).
,09-07 10:32:32.993  7992  7992 D elm:15121: MDMBridge.setEnterpriseBridge()
,09-07 10:32:33.003  1013  1218 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,09-07 10:32:33.003  1013  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-07 10:32:33.003  1013  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:33.003  1013  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:33.003  1013  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:33.003  1013  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:33.013   314   314 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 655us total 16.559ms
,09-07 10:32:33.013  1013  1054 I art     : Explicit concurrent mark sweep GC freed 69354(4MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 23MB/35MB, paused 7.274ms total 301.819ms
,09-07 10:32:33.013  1013  1023 I art     : WaitForGcToComplete blocked for 284.238ms for cause HeapTrim
,09-07 10:32:33.023  8037  8037 E Zygote  : MountEmulatedStorage()
09-07 10:32:33.023  8037  8037 E Zygote  : v2
09-07 10:32:33.023  8037  8037 I libpersona: KNOX_SDCARD checking this for 10032
09-07 10:32:33.023  8037  8037 I libpersona: KNOX_SDCARD not a persona
,09-07 10:32:33.023  8037  8037 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-07 10:32:33.023  8037  8037 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 10:32:33.033  1013  1218 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=8037 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-07 10:32:33.033  8037  8037 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-07 10:32:33.053  2825  7991 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,09-07 10:32:33.053  1013  3832 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
09-07 10:32:33.053  1013  3832 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,09-07 10:32:33.063  1013  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-07 10:32:33.063  1013  3832 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:33.063  1013  3832 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 10:32:33.063  1013  3832 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,09-07 10:32:33.063  8037  8037 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 10:32:33.073  8037  8037 D ActivityThread: Added TimaKeyStore provider
,09-07 10:32:33.073  7992  7992 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,09-07 10:32:33.073  7992  7992 D elm:15121: ElmAgentService : onCreate()
,09-07 10:32:33.073  7992  8052 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,09-07 10:32:33.073  7992  8052 D elm:15121: MainReceiver.listeningToPackageRemoved()
09-07 10:32:33.073  7992  8052 D elm:15121: MDMBridge.getInstance()
,09-07 10:32:33.073  7992  8052 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,09-07 10:32:33.083  2825  7991 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,09-07 10:32:33.093  7992  8052 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,09-07 10:32:33.093  2825  7991 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,09-07 10:32:33.093  1013  1543 D ActivityManager: startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,09-07 10:32:33.093  2825  2825 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-07 10:32:33.103  1013  1013 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,09-07 10:32:33.103  1013  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:33.103  1013  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:33.103  1013  1013 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-07 10:32:33.103  1013  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:33.103  1013  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:33.103  1013  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-07 10:32:33.103  1013  1013 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
09-07 10:32:33.103  1013  1013 V EnterpriseBillingPolicy: uID is 10170
09-07 10:32:33.103  1013  1013 V EnterpriseBillingPolicy: Removed Packageuid is0
09-07 10:32:33.103  1013  1013 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-07 10:32:33.113  1013  1013 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
,09-07 10:32:33.113  1013  1013 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
,09-07 10:32:33.113  1013  1013 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-07 10:32:33.113  1013  1013 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-07 10:32:33.113  1013  1013 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-07 10:32:33.113  1013  1054 D PackageManager: delete codoeFile: 
,09-07 10:32:33.123  1013  1543 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=8054 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
09-07 10:32:33.123  8054  8054 E Zygote  : MountEmulatedStorage()
09-07 10:32:33.123  8054  8054 I libpersona: KNOX_SDCARD checking this for 1000
09-07 10:32:33.123  8054  8054 E Zygote  : v2
09-07 10:32:33.123  8054  8054 I libpersona: KNOX_SDCARD not a persona
09-07 10:32:33.123  8054  8054 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 10:32:33.123  1013  1543 I ActivityManager: Killing 7480:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
09-07 10:32:33.123  1013  1054 I AASA_removePackage: UID=10170 Target=com.test.thalitest,
09-07 10:32:33.123  1013  1054 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
09-07 10:32:33.133  8054  8054 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 10:32:33.133  1013  1054 D PackageManager: result of delete: 1{666243468},
09-07 10:32:33.133  8054  8054 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 10:32:33.133  1013  1013 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-07 10:32:33.133  1013  1013 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
,09-07 10:32:33.133  1013  3365 D SSRM:bc : MSG_TYPE_APP_REMOVED::
09-07 10:32:33.143  1013  1160 D TaskPersister: removeObsoleteFile: deleting file=163_task.xml
09-07 10:32:33.143  1013  1126 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,09-07 10:32:33.143  7976  7976 D AndroidRuntime: Shutting down VM
09-07 10:32:33.153  7992  7992 D elm:15121: ElmAgentService : onDestroy().
09-07 10:32:33.153  1013  1479 I ActivityManager: Killing 7497:com.sec.android.diagmonagent/1000 (adj 15): empty #21
,09-07 10:32:33.163  8037  8067 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,09-07 10:32:33.173  8037  8067 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,09-07 10:32:33.173  8054  8054 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 10:32:33.173  8054  8054 D ActivityThread: Added TimaKeyStore provider
,09-07 10:32:33.183  1013  1496 I ActivityManager: Killing 7512:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,09-07 10:32:33.193  1013  1026 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
09-07 10:32:33.193  1013  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-07 10:32:33.193  1013  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-07 10:32:33.193  1013  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 10:32:33.193  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,09-07 10:32:33.203  8037  8067 D SPPClientService: PushLog.txt file is not deleted.
09-07 10:32:33.203  8037  8067 D SPPClientService: PushLog.txt file is not deleted.
09-07 10:32:33.203  8037  8067 D SPPClientService: ============PushLog. stop!
,09-07 10:32:33.203  1013  1026 D ActivityManager: startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
09-07 10:32:33.203  1013  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
,09-07 10:32:33.203  1013  1026 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:33.203  1013  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:33.203  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,09-07 10:32:33.203  1013  1481 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
09-07 10:32:33.203  1013  1481 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-07 10:32:33.213  1013  1481 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:33.213  1013  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 10:32:33.213  1013  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,09-07 10:32:33.213  1013  1025 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,09-07 10:32:33.223  1013  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:33.223  1013  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:33.223  1013  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:33.223  1013  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:33.243  8074  8074 E Zygote  : MountEmulatedStorage(),
09-07 10:32:33.243  8074  8074 E Zygote  : v2
,09-07 10:32:33.243  8074  8074 I libpersona: KNOX_SDCARD checking this for 10039
09-07 10:32:33.243  8074  8074 I libpersona: KNOX_SDCARD not a persona
09-07 10:32:33.243  8074  8074 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 10:32:33.253  8074  8074 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 10:32:33.253  1013  1025 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=8074 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,09-07 10:32:33.253  8074  8074 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 10:32:33.253  1013  1039 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,09-07 10:32:33.263  1013  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-07 10:32:33.263  1013  1013 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
09-07 10:32:33.263  1013  1013 V EnterpriseBillingPolicy: uID is 10170
09-07 10:32:33.263  1013  1013 V EnterpriseBillingPolicy: Removed Packageuid is0
09-07 10:32:33.263  1013  1013 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-07 10:32:33.263  1013  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-07 10:32:33.263  1013  1013 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-07 10:32:33.263  1013  1013 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-07 10:32:33.263  1013  1013 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-07 10:32:33.263  1013  1013 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-07 10:32:33.263  1013  1013 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-07 10:32:33.273  1013  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-07 10:32:33.283  1013  1133 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
,09-07 10:32:33.283  1013  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:33.283  1013  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:33.283  1013  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:33.283  1013  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:33.283  1013  1039 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-07 10:32:33.283  1013  1039 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 10:32:33.283  1013  1039 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-07 10:32:33.283  1013  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-07 10:32:33.283  7822  7822 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,09-07 10:32:33.293  1013  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-07 10:32:33.293  8089  8089 I libpersona: KNOX_SDCARD checking this for 1000
09-07 10:32:33.293  1013  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-07 10:32:33.293  8089  8089 I libpersona: KNOX_SDCARD not a persona
09-07 10:32:33.293  8089  8089 E Zygote  : MountEmulatedStorage()
09-07 10:32:33.293  8089  8089 E Zygote  : v2
09-07 10:32:33.293  8089  8089 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 10:32:33.293  8089  8089 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 10:32:33.293  1013  1133 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=8089 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-07 10:32:33.303  8089  8089 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 10:32:33.303  8074  8074 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 10:32:33.303  8074  8074 D ActivityThread: Added TimaKeyStore provider
,09-07 10:32:33.303  1013  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-07 10:32:33.303  1013  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-07 10:32:33.303  1013  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-07 10:32:33.313  1013  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-07 10:32:33.313  1013  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-07 10:32:33.323  1013  1133 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,09-07 10:32:33.323  1013  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-07 10:32:33.323  1013  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-07 10:32:33.333  1013  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:33.333  1013  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:33.333  1013  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:33.333  1013  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:33.333  1013  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-07 10:32:33.343  7822  7822 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
,09-07 10:32:33.343  7822  7822 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
,09-07 10:32:33.343  8089  8089 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 10:32:33.343  8089  8089 D ActivityThread: Added TimaKeyStore provider
,09-07 10:32:33.353  8105  8105 E Zygote  : MountEmulatedStorage(),
09-07 10:32:33.353  8105  8105 E Zygote  : v2
09-07 10:32:33.353  8105  8105 I libpersona: KNOX_SDCARD checking this for 1000
09-07 10:32:33.353  8105  8105 I libpersona: KNOX_SDCARD not a persona
,09-07 10:32:33.353  8074  8074 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-07 10:32:33.353  8074  8074 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 10:32:33.353  8074  8074 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-07 10:32:33.353  8074  8074 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
09-07 10:32:33.353  8074  8074 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-07 10:32:33.353  8074  8074 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.,
09-07 10:32:33.353  7822  7822 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
09-07 10:32:33.353  8074  8074 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-07 10:32:33.353  7822  7822 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
09-07 10:32:33.353  1013  1133 I ActivityManager: Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=8105 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-07 10:32:33.353  7822  7822 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
09-07 10:32:33.353  1013  1133 I ActivityManager: Killing 7529:com.sec.android.soagent/u0a31 (adj 15): empty #21
,09-07 10:32:33.363  7822  7822 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,09-07 10:32:33.363  7822  7822 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
09-07 10:32:33.363  7822  7822 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
09-07 10:32:33.363  7822  7822 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
09-07 10:32:33.363  7822  7822 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
09-07 10:32:33.363  7822  7822 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
09-07 10:32:33.363  7822  7822 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
09-07 10:32:33.363  7976  7976 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
09-07 10:32:33.363  7822  7822 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
09-07 10:32:33.363  7822  7822 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
09-07 10:32:33.363  7822  7822 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
09-07 10:32:33.363  7822  7822 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
09-07 10:32:33.363  7822  7822 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
09-07 10:32:33.363  7822  7822 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
09-07 10:32:33.363  7822  7822 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
09-07 10:32:33.363  7822  7822 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
09-07 10:32:33.363  7822  7822 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
09-07 10:32:33.363  1013  1039 D UsbSettingsManager: clearDefaults: com.test.thalitest
09-07 10:32:33.363  7822  7822 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
09-07 10:32:33.363  7822  7822 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
,09-07 10:32:33.363  8105  8105 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 10:32:33.363  7822  7822 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
09-07 10:32:33.373  8105  8105 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 10:32:33.373  8105  8105 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 10:32:33.383  2645  2645 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
09-07 10:32:33.383  2645  2645 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,09-07 10:32:33.383  1013  1039 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,09-07 10:32:33.393  8105  8105 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 10:32:33.393  8105  8105 D ActivityThread: Added TimaKeyStore provider
,09-07 10:32:33.403  1013  1039 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-07 10:32:33.403  7822  7822 D BluetoothAdapter: cancelDiscovery
,09-07 10:32:33.413  1013  1054 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-07 10:32:33.413  1013  1054 D PackageManager: userId{-1}
09-07 10:32:33.413  1013  1054 D PackageManager: andCode{true}
,09-07 10:32:33.413  1013  1026 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-07 10:32:33.413  1013  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,09-07 10:32:33.413  1013  1026 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:33.413  1013  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 10:32:33.413  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-07 10:32:33.413  3222  3359 D BluetoothAdapterProperties: mDiscovering is false
09-07 10:32:33.413  3222  3359 E BluetoothAdapterService: This is not a scanning status. cancelDiscovery() will be not called.
,09-07 10:32:33.413  7822  7822 D BluetoothAdapter: cancelDiscovery = true
09-07 10:32:33.413  7822  7822 V PlaceDetection v1.0.19 : [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
,09-07 10:32:33.423  1013  3836 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-07 10:32:33.423  8089  8089 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
,09-07 10:32:33.423  1013  1025 D ActivityManager: startService callerProcessName:com.android.keychain, calleePkgName: com.android.keychain
09-07 10:32:33.423  1013  1025 D ActivityManager: retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
,09-07 10:32:33.423  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:33.423  1013  1025 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 10:32:33.423  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
09-07 10:32:33.423  7822  7822 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
09-07 10:32:33.423  7822  7822 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-07 10:32:33.433  1924  8121 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,09-07 10:32:33.433  1924  8121 D AccountUtils: Clearing selected account for com.test.thalitest
,09-07 10:32:33.433  1013  3832 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,09-07 10:32:33.443  1013  3832 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:33.443  8105  8105 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-07 10:32:33.443  1013  3832 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:33.443  1013  3832 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:33.443  1013  3832 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:33.463  8127  8127 E Zygote  : MountEmulatedStorage(),
09-07 10:32:33.463  8127  8127 E Zygote  : v2
09-07 10:32:33.463  8127  8127 I libpersona: KNOX_SDCARD checking this for 1000
09-07 10:32:33.463  8127  8127 I libpersona: KNOX_SDCARD not a persona
,09-07 10:32:33.463  8127  8127 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 10:32:33.463  1013  3832 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=8127 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-07 10:32:33.463  8127  8127 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 10:32:33.463  8127  8127 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 10:32:33.473  1013  1054 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,09-07 10:32:33.483  7822  7822 E SQLiteLog: (10) unixWrite() File Descriptor : 26 gets errno : 9
,09-07 10:32:33.483  7822  7822 E SQLiteDatabase: Error inserting timestamp=1473237153429 message=Predictor: service stopped by removePlaceCategories()
09-07 10:32:33.483  7822  7822 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
09-07 10:32:33.483  7822  7822 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
09-07 10:32:33.483  7822  7822 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
09-07 10:32:33.483  7822  7822 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
09-07 10:32:33.483  7822  7822 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
09-07 10:32:33.483  7822  7822 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
09-07 10:32:33.483  7822  7822 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
09-07 10:32:33.483  7822  7822 E SQLiteDatabase: ,	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:110)
09-07 10:32:33.483  7822  7822 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
09-07 10:32:33.483  7822  7822 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
09-07 10:32:33.483  7822  7822 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-07 10:32:33.483  7822  7822 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-07 10:32:33.483  7822  7822 E SQLiteDatabase: ,	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 10:32:33.483  7822  7822 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 10:32:33.483  7822  7822 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 10:32:33.483  7822  7822 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 10:32:33.483  7822  7822 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194),
09-07 10:32:33.483  7822  7822 E UserAnalysis: It failed to insert to dump_log table
,09-07 10:32:33.503  1013  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:33.503  1013  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:33.503  1013  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 10:32:33.503  1013  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 10:32:33.513  8105  8105 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.sm/databases/lowpowercontext-system-db" with flag (131138) and mode_t (0) due to error (30)
09-07 10:32:33.513  8105  8105 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.sm/databases/lowpowercontext-system-db'.,
09-07 10:32:33.513  8105  8105 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 10:32:33.513  8105  8105 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 10:32:33.513  8105  8105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-07 10:32:33.513  8105  8105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-07 10:32:33.513  8105  8105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-07 10:32:33.513  8105  8105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-07 10:32:33.513  8105  8105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-07 10:32:33.513  8105  8105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-07 10:32:33.513  8105  8105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-07 10:32:33.513  8105  8105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-07 10:32:33.513  8105  8105 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-07 10:32:33.513  8105  8105 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-07 10:32:33.513  8105  8105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 10:32:33.513  8105  8105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 10:32:33.513  8105  8105 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f$b.a(DataStore.java:2443)
09-07 10:32:33.513  8105  8105 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(DataStore.java:85)
09-07 10:32:33.513  8105  8105 E SQLiteDatabase: 	,at com.samsung.android.sm.database.lowpowercontext.LowpowerContextProvider.onCreate(LowpowerContextProvider.java:303)
09-07 10:32:33.513  8105  8105 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
09-07 10:32:33.513  8105  8105 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
09-07 10:32:33.513  8105  8105 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
09-07 10:32:33.513  8105  8105 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
09-07 10:32:33.513  8105  8105 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237),
09-07 10:32:33.513  8105  8105 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 10:32:33.513  8105  8105 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 10:32:33.513  8105  8105 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 10:32:33.513  8105  8105 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145),
09-07 10:32:33.513  8105  8105 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 10:32:33.513  8105  8105 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 10:32:33.513  8105  8105 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 10:32:33.513  8105  8105 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 10:32:33.513  8105  8105 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-07 10:32:33.513  8105  8105 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.sm/databases/sm.db" with flag (131138) and mode_t (0) due to error (30)
,09-07 10:32:33.523  8105  8105 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.sm/databases/sm.db'.
09-07 10:32:33.523  8105  8105 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 10:32:33.523  8105  8105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 10:32:33.523  8105  8105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-07 10:32:33.523  8105  8105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-07 10:32:33.523  8105  8105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-07 10:32:33.523  8105  8105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-07 10:32:33.523  8105  8105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-07 10:32:33.523  8105  8105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-07 10:32:33.523  8105  8105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-07 10:32:33.523  8105  8105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-07 10:32:33.523  8105  8105 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
,09-07 10:32:33.523  8105  8105 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-07 10:32:33.523  8105  8105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 10:32:33.523  8105  8105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 10:32:33.523  8105  8105 E SQLiteDatabase: 	at com.samsung.android.sm.database.b.<init>(SmDatabaseHelper.java:65)
09-07 10:32:33.523  8105  8105 E SQLiteDatabase: 	at com.samsung.android.sm.database.b.a(SmDatabaseHelper.java:54)
09-07 10:32:33.523  8105  8105 E SQLiteDatabase: 	at com.samsung.android.sm.database.SmProvider.onCreate(SmProvider.java:89)
09-07 10:32:33.523  8105  8105 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
09-07 10:32:33.523  8105  8105 E SQLiteDatabase: ,	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
09-07 10:32:33.523  8105  8105 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
09-07 10:32:33.523  8105  8105 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
09-07 10:32:33.523  8105  8105 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
09-07 10:32:33.523  8105  8105 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 10:32:33.523  8105  8105 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 10:32:33.523  8105  8105 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 10:32:33.523  8105  8105 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-07 10:32:33.523  8105  8105 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 10:32:33.523  8105  8105 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 10:32:33.523  8105  8105 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 10:32:33.523  8105  8105 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 10:32:33.523  8105  8105 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 10:32:33.523  8105  8105 D AndroidRuntime: Shutting down VM
09-07 10:32:33.523  8143  8143 I libpersona: KNOX_SDCARD checking this for 10003
,09-07 10:32:33.523  8105  8105 E AndroidRuntime: FATAL EXCEPTION: main
09-07 10:32:33.523  8105  8105 E AndroidRuntime: Process: com.samsung.android.sm, PID: 8105
09-07 10:32:33.523  8105  8105 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.samsung.android.sm.database.SmProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 10:32:33.523  8105  8105 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5705)
09-07 10:32:33.523  8105  8105 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
09-07 10:32:33.523  8105  8105 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
09-07 10:32:33.523  8105  8105 E AndroidRuntime: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 10:32:33.523  8105  8105 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
,09-07 10:32:33.523  8105  8105 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 10:32:33.523  8105  8105 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
09-07 10:32:33.523  8105  8105 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 10:32:33.523  8105  8105 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 10:32:33.523  8105  8105 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 10:32:33.523  8105  8105 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 10:32:33.523  8105  8105 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 10:32:33.523  8105  8105 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 10:32:33.523  8105  8105 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 10:32:33.523  8105  8105 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-07 10:32:33.523  8105  8105 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-07 10:32:33.523  8105  8105 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-07 10:32:33.523  8105  8105 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-07 10:32:33.523  8105  8105 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-07 10:32:33.523  8105  8105 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-07 10:32:33.523  8105  8105 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-07 10:32:33.523  8105  8105 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-07 10:32:33.523  8105  8105 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
,09-07 10:32:33.523  8105  8105 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-07 10:32:33.523  8105  8105 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 10:32:33.523  8105  8105 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 10:32:33.523  8105  8105 E AndroidRuntime: 	at com.samsung.android.sm.database.b.<init>(SmDatabaseHelper.java:65)
09-07 10:32:33.523  8105  8105 E AndroidRuntime: 	at com.samsung.android.sm.database.b.a(SmDatabaseHelper.java:54)
09-07 10:32:33.523  8105  8105 E AndroidRuntime: 	at com.samsung.android.sm.database.SmProvider.onCreate(SmProvider.java:89)
09-07 10:32:33.523  8105  8105 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
,09-07 10:32:33.523  8105  8105 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
09-07 10:32:33.523  8105  8105 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
09-07 10:32:33.523  8105  8105 E AndroidRuntime: 	... 11 more
09-07 10:32:33.523  8143  8143 I libpersona: KNOX_SDCARD not a persona
,09-07 10:32:33.523  8143  8143 E Zygote  : MountEmulatedStorage()
09-07 10:32:33.523  1013  1054 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8143 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
09-07 10:32:33.523  8143  8143 E Zygote  : v2
09-07 10:32:33.533  8127  8127 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 10:32:33.533  8127  8127 D ActivityThread: Added TimaKeyStore provider
,09-07 10:32:33.533  8143  8143 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 10:32:33.533  1013  1461 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-07 10:32:33.533  1013  1461 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:33.533  1013  1461 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 10:32:33.533  1013  1461 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-07 10:32:33.533  8143  8143 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 10:32:33.543  8143  8143 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 10:32:33.543  1013  1026 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.sm
,09-07 10:32:33.553  1013  3832 D LocationManagerService: getProviders()=[passive, gps]
,09-07 10:32:33.563  1013  1504 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-07 10:32:33.563  1013  1504 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:33.563  1013  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 10:32:33.563  1013  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 10:32:33.563  1013  8154 E DropBoxManagerService: Can't write: system_app_crash
09-07 10:32:33.563  1013  8154 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop191.tmp: open failed: EROFS (Read-only file system)
09-07 10:32:33.563  1013  8154 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-07 10:32:33.563  1013  8154 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 10:32:33.563  1013  8154 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 10:32:33.563  1013  8154 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 10:32:33.563  1013  8154 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
09-07 10:32:33.563  1013  8154 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15780)
09-07 10:32:33.563  1013  8154 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 10:32:33.563  1013  8154 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 10:32:33.563  1013  8154 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 10:32:33.563  1013  8154 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-07 10:32:33.563  1013  8154 E DropBoxManagerService: 	... 5 more
,09-07 10:32:33.563  8105  8105 I Process : Sending signal. PID: 8105 SIG: 9
,09-07 10:32:33.563  8143  8143 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 10:32:33.573  8143  8143 D ActivityThread: Added TimaKeyStore provider
,09-07 10:32:33.573  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
09-07 10:32:33.573  1013  1025 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-07 10:32:33.573  1013  1025 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 10:32:33.573  1013  1025 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService; callingUser = 0; userId(target) = 0
09-07 10:32:33.573  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms

```
