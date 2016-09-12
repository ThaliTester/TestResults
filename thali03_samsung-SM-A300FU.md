#### Test 82894682da71698_thali03_samsung-SM-A300FU Logs


```
--------- beginning of system
09-13 00:05:26.382  1018  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:26.382  1018  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:26.382  1018  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:26.382  1018  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
--------- beginning of main
09-13 00:05:26.402  6928  6928 E Zygote  : MountEmulatedStorage()
09-13 00:05:26.402  6928  6928 E Zygote  : v2
09-13 00:05:26.402  6928  6928 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 00:05:26.402  6928  6928 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 00:05:26.402  6928  6928 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
09-13 00:05:26.402  6928  6928 I libpersona: KNOX_SDCARD checking this for 10041
09-13 00:05:26.402  6928  6928 I libpersona: KNOX_SDCARD not a persona
09-13 00:05:26.402  1018  1486 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.smishing.PackageInstallReceiver: pid=6928 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
09-13 00:05:26.412  1018  1486 I ActivityManager: Killing 6517:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
09-13 00:05:26.422  6928  6928 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 00:05:26.422  6928  6928 D ActivityThread: Added TimaKeyStore provider
09-13 00:05:26.452  1925  6799 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
09-13 00:05:26.452  1925  6799 I qtaguid : Tagging socket 101 with tag 1000040b00000000{268436491,0} for uid -1, pid: 1925, getuid(): 10011
09-13 00:05:26.462  6928  6928 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
09-13 00:05:26.462  6928  6928 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 00:05:26.462  6928  6928 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-13 00:05:26.462  6928  6928 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-13 00:05:26.462  6928  6928 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
09-13 00:05:26.482  6889  6889 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-13 00:05:26.492  6889  6889 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-13 00:05:26.502  1018  1031 D PowerManagerService: [api] handleWakeLockDeath : release WakeLock : PARTIAL_WAKE_LOCK              'AlarmReceiver' (uid=10081, pid=6517, ws=null) (elapsedTime=2593)
09-13 00:05:26.522  6928  6928 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
09-13 00:05:26.562  1018  1079 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
09-13 00:05:26.562  1018  1079 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
09-13 00:05:26.562  1018  1079 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:26.562  1018  1079 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 00:05:26.562  1018  1079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
09-13 00:05:26.612  1018  4259 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
09-13 00:05:26.612  1018  4259 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
09-13 00:05:26.622  6889  6889 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
09-13 00:05:26.632  6928  6928 W art     : Verification of com.android.mms.ui.ConversationComposer com.android.mms.ArtClassLoader.createConversationComposer() took 105.220ms
09-13 00:05:26.642  1018  4259 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:26.642  1018  4259 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 00:05:26.642  1018  4259 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
09-13 00:05:26.662  6889  6889 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-13 00:05:26.662  1018  1223 I art     : Explicit concurrent mark sweep GC freed 140358(7MB) AllocSpace objects, 3(1847KB) LOS objects, 33% free, 23MB/34MB, paused 2.577ms total 201.741ms
09-13 00:05:26.662  1925  6799 I qtaguid : Tagging socket 105 with tag 1000040b00000000{268436491,0} for uid -1, pid: 1925, getuid(): 10011
09-13 00:05:26.692  1925  6804 W BaseAppContext: Using Auth Proxy for data requests.
09-13 00:05:26.722  6721  6739 W art     : Suspending all threads took: 28.646ms
09-13 00:05:26.742  1018  4258 E EdmStorageProvider: Admin not in database, something went wrong
09-13 00:05:26.752  6953  6953 D AndroidRuntime: 
09-13 00:05:26.752  6953  6953 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-13 00:05:26.752  6953  6953 D AndroidRuntime: CheckJNI is OFF
09-13 00:05:26.752  6953  6953 D AndroidRuntime: readGMSProperty: start
09-13 00:05:26.752  6953  6953 D AndroidRuntime: readGMSProperty: already setted!!
09-13 00:05:26.752  6953  6953 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-13 00:05:26.752  6953  6953 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-13 00:05:26.752  6953  6953 D AndroidRuntime: readGMSProperty: end
09-13 00:05:26.752  6953  6953 D AndroidRuntime: addProductProperty: start
09-13 00:05:26.762  1695  4295 I art     : Explicit concurrent mark sweep GC freed 12256(588KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 8MB/13MB, paused 1.616ms total 61.778ms
09-13 00:05:26.782  1018  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-13 00:05:26.792  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:26.792  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 00:05:26.792  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
09-13 00:05:26.792  1018  1031 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 00:05:26.802  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
09-13 00:05:26.802  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:26.802  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 00:05:26.802  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-13 00:05:26.802  1018  1486 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
09-13 00:05:26.812  1018  1486 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:26.812  1018  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 00:05:26.812  1018  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-13 00:05:26.812  1018  1030 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
09-13 00:05:26.812  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:26.812  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:26.812  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:26.812  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:26.832  6965  6965 E Zygote  : MountEmulatedStorage()
09-13 00:05:26.832  6965  6965 E Zygote  : v2
09-13 00:05:26.832  6965  6965 I libpersona: KNOX_SDCARD checking this for 10148
09-13 00:05:26.832  6965  6965 I libpersona: KNOX_SDCARD not a persona
09-13 00:05:26.832  6965  6965 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 00:05:26.832  1018  1030 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=6965 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
09-13 00:05:26.832  6965  6965 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 00:05:26.832  6965  6965 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-13 00:05:26.842  1018  1505 I ActivityManager: Killing 6532:com.wsomacp/u0a23 (adj 15): empty #21
09-13 00:05:26.842  1018  4258 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:26.842  1018  4258 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 00:05:26.842  1018  4258 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 00:05:26.842  1018  4258 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
09-13 00:05:26.842  1018  4258 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-13 00:05:26.852  6965  6965 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 00:05:26.852  6965  6965 D ActivityThread: Added TimaKeyStore provider
09-13 00:05:26.892  1018  1486 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-13 00:05:26.892  1018  1486 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:26.892  1018  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 00:05:26.892  1018  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-13 00:05:26.902  1018  4259 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-13 00:05:26.902  1018  4259 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:26.902  1018  4259 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 00:05:26.902  1018  4259 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
09-13 00:05:26.912  1925  6804 W BaseAppContext: Using Auth Proxy for data requests.
09-13 00:05:26.922  1925  6804 W BaseAppContext: Using Auth Proxy for data requests.
09-13 00:05:26.962  6965  6965 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
09-13 00:05:26.962   274   274 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb75267c8
09-13 00:05:26.962   274   274 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
09-13 00:05:26.962   274   274 I rmt_storage: wakelock acquired: 1, error no: 42
09-13 00:05:26.962   274   316 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1219336056)
09-13 00:05:26.972  6928  6928 W art     : Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 237.579ms
09-13 00:05:26.972  6953  6953 E AffinityControl: AffinityControl: registerfunction enter
09-13 00:05:26.972  6889  6889 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-13 00:05:26.992  6889  6889 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-13 00:05:26.992  6721  6801 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 648 ms] updated apps [took 647 ms] 
09-13 00:05:27.002  6889  6889 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-13 00:05:27.002  1018  1487 I ActivityManager: Killing 6383:com.android.defcontainer/u0a3 (adj 15): empty #21
09-13 00:05:27.002  6889  6889 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-13 00:05:27.012  1018  1505 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
09-13 00:05:27.022  6953  6953 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-13 00:05:27.022  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:27.022  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:27.022  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:27.022  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:27.032  6889  6889 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-13 00:05:27.032  6889  6889 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-13 00:05:27.032  6889  6889 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-13 00:05:27.032  6889  6889 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-13 00:05:27.032  6889  6889 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-13 00:05:27.032  6889  6889 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-13 00:05:27.032  6889  6889 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-13 00:05:27.032   274   316 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
09-13 00:05:27.032   274   316 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
09-13 00:05:27.032   274   316 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1219336056) wakelock released: 1, error no: 0
09-13 00:05:27.032   274   316 I rmt_storage: 
09-13 00:05:27.032  6889  6889 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-13 00:05:27.042   274   274 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb75267c8
09-13 00:05:27.042  6889  6889 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-13 00:05:27.042  1018  1505 I ActivityManager: Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=6999 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-13 00:05:27.042  6889  6889 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-13 00:05:27.042  1018  1505 I ActivityManager: Killing 6549:com.sec.esdk.elm/u0a90 (adj 15): empty #21
09-13 00:05:27.052  6999  6999 E Zygote  : MountEmulatedStorage()
09-13 00:05:27.052  6999  6999 E Zygote  : v2
09-13 00:05:27.052  6889  6889 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-13 00:05:27.052  6999  6999 I libpersona: KNOX_SDCARD checking this for 1000
09-13 00:05:27.052  6999  6999 I libpersona: KNOX_SDCARD not a persona
09-13 00:05:27.052  6889  6889 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-13 00:05:27.052  6999  6999 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 00:05:27.052  6889  6889 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
09-13 00:05:27.062  6999  6999 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 00:05:27.062  1925  6804 W BaseAppContext: Using Auth Proxy for data requests.
09-13 00:05:27.062  6999  6999 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-13 00:05:27.082  1018  1487 E PersonaManagerService: inState():  stateMachine is null !!
09-13 00:05:27.092  6889  6889 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-13 00:05:27.092  1018  1487 I PersonaManagerService: PersonaId don't exist
09-13 00:05:27.092  1018  1487 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
09-13 00:05:27.092  6999  6999 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 00:05:27.102  6999  6999 D ActivityThread: Added TimaKeyStore provider
09-13 00:05:27.102  6889  6889 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-13 00:05:27.132  1018  1487 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-13 00:05:27.132  6928  6928 W art     : Verification of com.sec.android.touchwiz.animator.TwDndHorizontalListAnimator com.android.mms.ArtClassLoader.createTwDndHorizontalListAnimator(android.content.Context) took 158.757ms
09-13 00:05:27.132  6928  7016 D Mms/ArtClassLoader: init before art
09-13 00:05:27.132  6928  6928 D Mms/TelephonyPermission: start operation mode monitor
09-13 00:05:27.132  6999  6999 W ResourcesManager: Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
09-13 00:05:27.152  1018  1487 W ActivityManager: mDVFSHelper.acquire()
09-13 00:05:27.152  6928  6928 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-13 00:05:27.152  1018  1487 D FocusedStackFrame: Set to : 0
09-13 00:05:27.172   292   292 E SMD     : DCD OFF
09-13 00:05:27.172  6889  6889 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-13 00:05:27.172  6889  6889 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-13 00:05:27.172  6889  6889 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
09-13 00:05:27.222  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:27.222  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:27.222  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:27.222  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:27.222  1018  1048 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-13 00:05:27.222  1018  1048 D PhoneWindow: *FMB* installDecor flags : -2122120936
09-13 00:05:27.242  7018  7018 E Zygote  : MountEmulatedStorage()
09-13 00:05:27.242  7018  7018 E Zygote  : v2
09-13 00:05:27.242  7018  7018 I libpersona: KNOX_SDCARD checking this for 10170
09-13 00:05:27.242  7018  7018 I libpersona: KNOX_SDCARD not a persona
09-13 00:05:27.242  1018  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-13 00:05:27.242  1018  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-13 00:05:27.242   259   259 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
09-13 00:05:27.252  7018  7018 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 00:05:27.252  7018  7018 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 00:05:27.252  7018  7018 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
09-13 00:05:27.262  1018  1487 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7018 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-13 00:05:27.262  1018  1487 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
09-13 00:05:27.262  1018  1487 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-13 00:05:27.262  1018  1487 D InputDispatcher: Focused application set to: xxxx
09-13 00:05:27.272  1018  1487 D InputDispatcher: Focus left window: 1488
09-13 00:05:27.272  6953  6953 D AndroidRuntime: Shutting down VM
09-13 00:05:27.272  1018  1472 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
09-13 00:05:27.272  1018  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:27.272  1018  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:27.272  1018  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:27.272  1018  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:27.282  6928  6928 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
09-13 00:05:27.282  6928  6928 D Mms/TelephonyPermission: isDefault true
09-13 00:05:27.282  6928  6928 D Mms/MmsApp: onCreate() com.android.mms
09-13 00:05:27.292  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-13 00:05:27.292  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
09-13 00:05:27.312  7018  7018 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 00:05:27.312  7018  7018 D ActivityThread: Added TimaKeyStore provider
09-13 00:05:27.322  7034  7034 E Zygote  : MountEmulatedStorage()
09-13 00:05:27.322  7034  7034 E Zygote  : v2
09-13 00:05:27.322  7034  7034 I libpersona: KNOX_SDCARD checking this for 10152
09-13 00:05:27.322  1925  6799 I qtaguid : Untagging socket 101
09-13 00:05:27.322  7034  7034 I libpersona: KNOX_SDCARD not a persona
09-13 00:05:27.322  7034  7034 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 00:05:27.332  7034  7034 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 00:05:27.332  6928  6928 D Mms/MmsApp: [start]    initCountryIso consume time = 810.773646
09-13 00:05:27.332  1018  1472 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7034 uid=10152 gids={50152, 9997} abi=armeabi-v7a
09-13 00:05:27.332  1018  1472 I ActivityManager: Killing 6263:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
09-13 00:05:27.332  7034  7034 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-13 00:05:27.342  1018  1331 D CountryDetector: The first listener is added
09-13 00:05:27.342  1018  1079 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
09-13 00:05:27.342  1018  1018 V ActivityManager: Display changed displayId=0
09-13 00:05:27.342  1925  1925 I ConfigFetchService: fetch service done; releasing wakelock
09-13 00:05:27.352  1018  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-13 00:05:27.362  1018  1030 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
09-13 00:05:27.382  1925  1925 I ConfigFetchService: stopping self
09-13 00:05:27.402  6928  6928 D Mms/MmsApp: [end]    initCountryIso consume time = 66.856875
09-13 00:05:27.402  6928  6928 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.11427
09-13 00:05:27.402  7034  7034 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 00:05:27.402  7034  7034 D ActivityThread: Added TimaKeyStore provider
09-13 00:05:27.402  1018  1079 D PersonaManager: isKioskContainerExistOnDevice
09-13 00:05:27.422  6928  6928 D Mms/MmsConfig: before partial update
09-13 00:05:27.432   259   437 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
09-13 00:05:27.432   259   440 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
09-13 00:05:27.432  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
09-13 00:05:27.452  1018  1486 I ActivityManager: Killing 6283:com.android.calendar/u0a131 (adj 15): empty #21
09-13 00:05:27.452  6928  6928 D Mms/MmsConfig: Load Resize quality : 80
09-13 00:05:27.462  6928  6928 D EasySignUpManager_1.0.1: serviceId : 1, features : -1
09-13 00:05:27.462  1488  1488 D Launcher: onTrimMemory. Level: 20
09-13 00:05:27.462  1488  1488 V ActivityThread: updateVisibility : ActivityRecord{1c616a26 token=android.os.BinderProxy@350e492 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
09-13 00:05:27.472  6928  6928 D EasySignUpManager_1.0.1: isAuth is false
09-13 00:05:27.472  6928  6928 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
09-13 00:05:27.482  6953  6953 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
09-13 00:05:27.482  6889  6889 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,09-13 00:05:27.492  1018  1810 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
09-13 00:05:27.492  1018  1810 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
09-13 00:05:27.502  1018  1810 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:27.502  1460  2580 D TP/MmsSmsProvider: query,matched:2117, calling pid = 6928
09-13 00:05:27.502  1018  1810 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 00:05:27.502  1018  1810 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
09-13 00:05:27.502  1460  2580 D TP/MmsSmsProvider: match 2117:Elapsed time : 3.364 ms
09-13 00:05:27.512  6889  7052 D Ads     : Skipping gmscore version check
09-13 00:05:27.512  7034  7034 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
09-13 00:05:27.512  7034  7034 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
09-13 00:05:27.522  7034  7034 I TapandpayWidget:Utils: Clear T&P info.
09-13 00:05:27.522  6928  6928 D EasySignUpManager_1.0.1: isAuth is false
09-13 00:05:27.522  6928  6928 D EasySignUpManager_1.0.1: getServiceStatus : serviceId (1) is OFF
09-13 00:05:27.532  6889  6889 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
09-13 00:05:27.542  6928  6928 E CscParser: mps_code.dat does not exist
09-13 00:05:27.542  6928  6928 E CscParser: customer_path =/system/csc/customer.xml
09-13 00:05:27.542  6928  6928 E CscParser: fileName + /system/csc/customer.xml
09-13 00:05:27.542  6928  6928 E CscParser: mps_code.dat does not exist
09-13 00:05:27.542  6928  6928 E CscParser: customer_path =/system/csc/customer.xml
09-13 00:05:27.542  6928  6928 E CscParser: fileName + /system/csc/customer.xml
09-13 00:05:27.552  7034  7034 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
09-13 00:05:27.552  1018  1489 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
09-13 00:05:27.552  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:27.552  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:27.562  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:27.562  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:27.572  7057  7057 E Zygote  : MountEmulatedStorage()
09-13 00:05:27.572  7057  7057 I libpersona: KNOX_SDCARD checking this for 10009
09-13 00:05:27.572  7057  7057 E Zygote  : v2
09-13 00:05:27.572  7057  7057 I libpersona: KNOX_SDCARD not a persona
09-13 00:05:27.572  7057  7057 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 00:05:27.572  6928  6928 D CscParser: getInstance fileName =/system/csc/customer.xml
09-13 00:05:27.572  7057  7057 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 00:05:27.572  6928  6928 D Mms/MmsConfig:  enable multiwindow = false
09-13 00:05:27.582  7057  7057 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
09-13 00:05:27.582  1018  1489 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=7057 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
09-13 00:05:27.582  1018  1489 I ActivityManager: Killing 6586:com.samsung.android.securitylogagent/1000 (adj 15): empty #21
09-13 00:05:27.582  1018  1031 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-13 00:05:27.592  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:27.592  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 00:05:27.592  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
09-13 00:05:27.592  6928  6928 E Mms/MessageUtils: setCountryDetector : update country detector info 
09-13 00:05:27.592  6928  6928 E Mms/MessageUtils: updateCountryIso : update country iso info 
09-13 00:05:27.602  7018  7018 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
09-13 00:05:27.612  6928  6928 D Mms/MmsConfig: [end]    init() consume time = 210.311927
09-13 00:05:27.612  6928  6928 D Mms/Contact: [start]    init() consume time = 0.85625
09-13 00:05:27.622  7018  7018 I cr.library_loader: Time to load native libraries: 3 ms (timestamps 8494-8497)
09-13 00:05:27.622  7018  7018 I cr.library_loader: Expected native library version number "", actual native library version number ""
09-13 00:05:27.632  7057  7057 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 00:05:27.632  7057  7057 D ActivityThread: Added TimaKeyStore provider
09-13 00:05:27.642  6889  6889 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-13 00:05:27.642  1460  2580 D TP/MmsSmsProvider: query,matched:13, calling pid = 6928
09-13 00:05:27.642  1460  2580 D TP/MmsSmsProvider: match 13:Elapsed time : 1.530 ms
09-13 00:05:27.642  6928  6928 D Mms/Contact: [end]    init consume time = 37.987188
09-13 00:05:27.652  6740  6795 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
09-13 00:05:27.662  6928  7077 D Mms/DraftCache: [start]    rebuildCache consume time = 11.21526
09-13 00:05:27.662  6928  6928 D Mms/MethodReflector: getSubId is called
09-13 00:05:27.662  6928  6928 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
09-13 00:05:27.662  6928  6928 D Mms/MethodReflector: getTelephonyProperty is called
09-13 00:05:27.662  6928  6928 D Mms/DownloadManager: roaming -> false (slotId = 0)
09-13 00:05:27.662  6928  6928 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
09-13 00:05:27.662  6928  6928 D Mms/DownloadManager: auto download without roaming -> true
09-13 00:05:27.662  6928  6928 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
09-13 00:05:27.662  6928  6928 D Mms/MethodReflector: getSubId is called
09-13 00:05:27.672  6928  6928 D Mms/MethodReflector: getDefaultSmsSubId is called
09-13 00:05:27.672  6928  6928 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
09-13 00:05:27.672  6928  6928 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
09-13 00:05:27.672  6928  6928 D Mms/MethodReflector: getTelephonyProperty is called
09-13 00:05:27.672  6928  6928 D Mms/DownloadManager: roaming -> false (slotId = 1)
09-13 00:05:27.672  6928  6928 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
09-13 00:05:27.672  6928  6928 D Mms/DownloadManager: auto download without roaming -> true
09-13 00:05:27.672  6928  6928 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
09-13 00:05:27.672  6928  6928 D Mms/DownloadManager: auto download during roaming secondary -> false
09-13 00:05:27.672  6928  6928 D Mms/DownloadManager: mAutoDownload ------> true
09-13 00:05:27.672  1460  1479 D TP/MmsSmsProvider: query,matched:12, calling pid = 6928
09-13 00:05:27.672  1460  1479 D TP/MmsSmsProvider: match 12:Elapsed time : 1.717 ms
09-13 00:05:27.682  6843  6923 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
09-13 00:05:27.682  6843  6923 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-13 00:05:27.682  6843  6923 I GAv4    :   adb logcat -s GAv4
09-13 00:05:27.692  6928  7077 D Mms/DraftCache: [end]    rebuildCache consume time = 34.102552
09-13 00:05:27.712  6843  6923 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
09-13 00:05:27.712  1018  1486 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
09-13 00:05:27.712  6928  7016 D Mms/ArtClassLoader: init [DONE] art
09-13 00:05:27.722  6843  6923 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
09-13 00:05:27.732  6843  7081 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
09-13 00:05:27.742  6843  6923 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.357.23.33
09-13 00:05:27.742  6928  6928 D ComposerPerformance: 1473717927755 ms / [DONE] Composer constructor
09-13 00:05:27.742  6928  6928 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
09-13 00:05:27.742  6928  6928 I Mms/ReservationManager: ReservationManager()
09-13 00:05:27.742  6928  6928 I Mms/ReservationManager: resetAfterConnected()
09-13 00:05:27.752  1460  1644 D TP/MmsSmsProvider: query,matched:7, calling pid = 6928
09-13 00:05:27.752  1460  1644 D TP/MmsSmsProvider: match 7:Elapsed time : 2.896 ms
09-13 00:05:27.752  6928  6928 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
09-13 00:05:27.762  6928  7082 D Mms/Conversation: [start]    init() consume time = 65.024844
09-13 00:05:27.762  6928  6928 D Mms/MmsApp: [end]    onCreate() consume time = 0.947188
09-13 00:05:27.762  1460  1479 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
09-13 00:05:27.762  1460  1479 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
09-13 00:05:27.762  1460  1479 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
09-13 00:05:27.762  1460  1479 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
09-13 00:05:27.762  1460  1479 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
09-13 00:05:27.772  1460  1479 D TP/MmsSmsProvider: need read changed broadcast:false
09-13 00:05:27.772  6928  7082 D Mms/Conversation: [end]    init consume time = 10.173333
09-13 00:05:27.772  6928  7082 D Mms/MessagingNotification: [start]    init() consume time = 3.370365
09-13 00:05:27.772  6928  7082 D Mms/MessagingNotification: [end]    init consume time = 2.812864
09-13 00:05:27.782  1460  2580 D TP/MmsSmsProvider: query,matched:0, calling pid = 6928
09-13 00:05:27.782  1460  2580 V TP/MmsSmsProvider: getSimpleConversations entered.
09-13 00:05:27.782  1460  2580 D TP/MmsSmsProvider: match 0:Elapsed time : 1.568 ms
09-13 00:05:27.782  6928  7084 D Mms/Synchronizer: [start]    doSync consume time = 5.307969
09-13 00:05:27.782  1018  3428 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
09-13 00:05:27.782  6928  7083 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 1.860469
09-13 00:05:27.782  6928  6928 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=760]
09-13 00:05:27.782  6928  6928 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
09-13 00:05:27.782  1460  1644 D TP/MmsSmsProvider: update, matched:300, calling pid = 6928
09-13 00:05:27.782  1460  1644 V TP/MmsSmsProvider: syncDBData start
09-13 00:05:27.782  1460  1644 V TP/MmsSmsProvider: syncDBData sms end
09-13 00:05:27.782  1460  1644 V TP/MmsSmsProvider: syncDBData mms end
09-13 00:05:27.782  1460  1644 V TP/MmsSmsProvider: syncDBData end
09-13 00:05:27.792  6928  7084 D Mms/Synchronizer: [end]    doSync consume time = 5.938437
09-13 00:05:27.792  6928  6928 D Mms/MethodReflector: getSubId is called
09-13 00:05:27.792  6928  6928 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
09-13 00:05:27.792  1460  1644 D TP/MmsSmsProvider: query,matched:400, calling pid = 6928
09-13 00:05:27.792  6740  6795 I AcmsKeyStoreHelper: Key Store exist
09-13 00:05:27.792  6740  6795 I AcmsKeyStoreHelper: Hence loading the keystore file
09-13 00:05:27.792  6928  6928 D Mms/MethodReflector: getTelephonyProperty is called
09-13 00:05:27.792  6928  6928 D Mms/DownloadManager: roaming -> false (slotId = 0)
09-13 00:05:27.792  6928  6928 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
09-13 00:05:27.792  6928  6928 D Mms/DownloadManager: auto download without roaming -> true
09-13 00:05:27.792  6928  6928 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
09-13 00:05:27.792  6928  6928 D Mms/DownloadManager: mAutoDownload ------> true
09-13 00:05:27.792  1018  1223 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
09-13 00:05:27.792  1018  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:27.792  1018  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:27.792  1018  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:27.792  1018  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:27.802  7018  7018 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {31be1a1c}
09-13 00:05:27.802  7018  7018 I cr.library_loader: Expected native library version number "", actual native library version number ""
09-13 00:05:27.812  7086  7086 E Zygote  : MountEmulatedStorage()
09-13 00:05:27.812  7086  7086 I libpersona: KNOX_SDCARD checking this for 10068
09-13 00:05:27.812  7086  7086 E Zygote  : v2
09-13 00:05:27.812  7086  7086 I libpersona: KNOX_SDCARD not a persona
09-13 00:05:27.812  7086  7086 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 00:05:27.812  1018  1223 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7086 uid=10068 gids={50068, 9997} abi=armeabi-v7a
09-13 00:05:27.812  7086  7086 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 00:05:27.822  7086  7086 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
09-13 00:05:27.822  6928  7083 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 30.634323
09-13 00:05:27.832  6928  6928 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_ADDED
09-13 00:05:27.832  1018  1810 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
09-13 00:05:27.832  1018  1810 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
09-13 00:05:27.832  1018  1810 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:27.832  1018  1810 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:27.832  1018  1810 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
09-13 00:05:27.842  1018  1331 I ActivityManager: Killing 6603:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
09-13 00:05:27.842  7018  7018 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
09-13 00:05:27.842  1018  1331 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
09-13 00:05:27.842  1018  1331 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:27.842  1018  1331 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:27.842  1018  1331 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:27.842  1018  1331 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:27.852  7086  7086 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 00:05:27.852  7086  7086 D ActivityThread: Added TimaKeyStore provider
09-13 00:05:27.862  7102  7102 E Zygote  : MountEmulatedStorage()
09-13 00:05:27.862  7102  7102 E Zygote  : v2
09-13 00:05:27.862  7102  7102 I libpersona: KNOX_SDCARD checking this for 10042
09-13 00:05:27.862  7102  7102 I libpersona: KNOX_SDCARD not a persona
09-13 00:05:27.862  6928  7101 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_ADDED
09-13 00:05:27.862  6928  7101 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_ADDED
09-13 00:05:27.862  7102  7102 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 00:05:27.862  7102  7102 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 00:05:27.862  7102  7102 E SELinux : [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
09-13 00:05:27.862  1018  1331 I ActivityManager: Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=7102 uid=10042 gids={50042, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
09-13 00:05:27.872  1018  1489 I ActivityManager: Killing 6621:com.qualcomm.timeservice/1000 (adj 15): empty #21
09-13 00:05:27.872  1018  1489 I ActivityManager: Killing 6570:com.android.providers.calendar/u0a37 (adj 15): empty #22
09-13 00:05:27.882  7102  7102 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 00:05:27.882  7102  7102 D ActivityThread: Added TimaKeyStore provider
09-13 00:05:27.902  7086  7086 D BadgeProvider: onCreate
09-13 00:05:27.902  7086  7086 D BadgeProvider: DatabaseHelper
09-13 00:05:27.902  6843  6857 W art     : Suspending all threads took: 36.760ms
09-13 00:05:27.912  1018  1043 W ActivityManager: Activity pause timeout for ActivityRecord{29a44c4e u0 com.test.thalitest/.MainActivity t163}
09-13 00:05:27.922  6928  7082 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
09-13 00:05:27.932  1460  1479 D TP/SmsProvider: query,matched:26, calling pid = 6928
09-13 00:05:27.932  7018  7018 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
09-13 00:05:27.932  1460  1479 D TP/SmsProvider: match 26:Elapsed time : 2.337 ms
09-13 00:05:27.932  7018  7018 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-13 00:05:27.932  7102  7102 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-13 00:05:27.932  7102  7102 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-13 00:05:27.932  7102  7102 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-13 00:05:27.942  6740  6795 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
09-13 00:05:27.942  6740  6795 I AcmsCertificateMngr: getKeyStoreForApplication success 
09-13 00:05:27.942  6740  6795 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
09-13 00:05:27.942  6740  6795 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-13 00:05:27.942  6740  6795 D AcmsServiceMonitor: Decrementing - Counter value: 1
09-13 00:05:27.942  6740  6795 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
09-13 00:05:27.942  6740  6795 D AcmsCore: This is NOT a valid MirrorLink app
09-13 00:05:27.942  6740  6795 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
09-13 00:05:27.942  6740  6795 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-13 00:05:27.942  6740  6795 D AcmsServiceMonitor: Decrementing - Counter value: 0
09-13 00:05:27.942  6740  6795 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
09-13 00:05:27.952  6740  6740 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
09-13 00:05:27.952  6740  6740 D AcmsService: Enter onDestroy
09-13 00:05:27.952  6740  6740 I AcmsService: cleanUp(): inside service clean up
09-13 00:05:27.952  6740  6740 D AcmsCore: AcmsCore: inside DeInit
09-13 00:05:27.952  6740  6740 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
09-13 00:05:27.952  6740  6740 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
09-13 00:05:27.952  6740  6740 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
09-13 00:05:27.952  6740  6740 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
09-13 00:05:27.952  1460  1644 D TP/MmsSmsProvider: query,matched:6, calling pid = 6928
09-13 00:05:27.952  1460  1644 D TP/MmsSmsProvider: match 6:Elapsed time : 1.143 ms
09-13 00:05:27.952  6740  6740 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
09-13 00:05:27.952  6740  6740 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
09-13 00:05:27.952  6740  6740 D AcmsService: killing acms process
09-13 00:05:27.952  6740  6740 I Process : Sending signal. PID: 6740 SIG: 9
09-13 00:05:27.972  1018  1487 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
09-13 00:05:27.972  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:27.972  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:27.972  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:27.972  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:27.982  7118  7118 E Zygote  : MountEmulatedStorage()
09-13 00:05:27.982  7118  7118 E Zygote  : v2
09-13 00:05:27.982  7118  7118 I libpersona: KNOX_SDCARD checking this for 10023
09-13 00:05:27.982  7118  7118 I libpersona: KNOX_SDCARD not a persona
09-13 00:05:27.982  7118  7118 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 00:05:27.992  7118  7118 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 00:05:27.992  1018  1487 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=7118 uid=10023 gids={50023, 9997} abi=armeabi-v7a
09-13 00:05:27.992  7118  7118 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-13 00:05:28.002  7018  7018 E SysUtils: ApplicationContext is null in ApplicationStatus
09-13 00:05:28.012   308   308 I art     : Explicit concurrent mark sweep GC freed 8692(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 612us total 21.089ms
09-13 00:05:28.022  1925  4262 I Icing   : Indexing D0AE1F45F393341DA3213A207506F1C2E721F1A9 from com.google.android.googlequicksearchbox
09-13 00:05:28.022  7118  7118 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 00:05:28.022  7118  7118 D ActivityThread: Added TimaKeyStore provider
09-13 00:05:28.032   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 613us total 18.593ms
09-13 00:05:28.032  1018  4258 I ActivityManager: Killing 6639:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
09-13 00:05:28.042  1018  1030 I ActivityManager: Process ACMS.Process (pid 6740)(adj 0) has died(67,735)
09-13 00:05:28.052   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 607us total 17.546ms
09-13 00:05:28.062  7018  7018 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-13 00:05:28.062  7018  7018 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-13 00:05:28.062  7018  7018 I Adreno-EGL: Build Date: 04/06/15 Mon
09-13 00:05:28.062  7018  7018 I Adreno-EGL: Local Branch: 
09-13 00:05:28.062  7018  7018 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-13 00:05:28.062  7018  7018 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-13 00:05:28.062  7018  7018 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
09-13 00:05:28.072  7118  7118 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
09-13 00:05:28.102  6928  7082 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
09-13 00:05:28.112  1925  4262 D Icing   : Loaded CLD2 Version V2.0 - 20141016
09-13 00:05:28.122  7118  7118 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
09-13 00:05:28.122  7118  7118 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
09-13 00:05:28.122  7118  7118 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
09-13 00:05:28.122  7118  7118 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
09-13 00:05:28.122  7118  7118 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
09-13 00:05:28.122  7102  7102 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
09-13 00:05:28.122  7118  7118 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
09-13 00:05:28.132  7118  7118 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
09-13 00:05:28.132  7118  7118 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
09-13 00:05:28.132  7118  7118 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
09-13 00:05:28.132  7118  7118 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
09-13 00:05:28.132  1018  1057 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
09-13 00:05:28.132  1018  1057 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
09-13 00:05:28.132  7118  7118 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
09-13 00:05:28.132  7118  7118 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
09-13 00:05:28.132  1018  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:28.132  1018  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:28.132  1018  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:28.132  1018  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:28.132  7118  7118 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
09-13 00:05:28.152  7139  7139 E Zygote  : MountEmulatedStorage()
09-13 00:05:28.152  7139  7139 E Zygote  : v2
09-13 00:05:28.152  7139  7139 I libpersona: KNOX_SDCARD checking this for 10003
09-13 00:05:28.152  7139  7139 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 00:05:28.152  7139  7139 I libpersona: KNOX_SDCARD not a persona
09-13 00:05:28.152  7139  7139 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 00:05:28.152  1018  1057 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7139 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
09-13 00:05:28.152  7139  7139 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-13 00:05:28.152  1018  1486 I ActivityManager: Killing 6652:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
09-13 00:05:28.182  7139  7139 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 00:05:28.182  7139  7139 D ActivityThread: Added TimaKeyStore provider
,09-13 00:05:28.222  1018  1030 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.filterinstaller, hostingType: broadcast
,09-13 00:05:28.222  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:28.222  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:28.222  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:28.222  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:05:28.232  1925  4262 I Icing   : Indexing done D0AE1F45F393341DA3213A207506F1C2E721F1A9
,09-13 00:05:28.232  7166  7166 E Zygote  : MountEmulatedStorage()
,09-13 00:05:28.232  7166  7166 E Zygote  : v2
09-13 00:05:28.232  7166  7166 I libpersona: KNOX_SDCARD checking this for 1000
09-13 00:05:28.232  7166  7166 I libpersona: KNOX_SDCARD not a persona
,09-13 00:05:28.232  7166  7166 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 00:05:28.242  1018  1030 I ActivityManager: Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=7166 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-13 00:05:28.242  7166  7166 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 00:05:28.242  7166  7166 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 00:05:28.242  1018  4258 I ActivityManager: Killing 5093:com.google.android.gms.wearable/u0a11 (adj 15): empty #21
,09-13 00:05:28.242   285   285 E installd: system dir 0 : /system/app/
09-13 00:05:28.242   285   285 E installd: system dir 1 : /system/priv-app/
09-13 00:05:28.242   285   285 E installd: system dir 2 : /vendor/app/
09-13 00:05:28.242   285   285 E installd: system dir 3 : /oem/app/
,09-13 00:05:28.262  7018  7018 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-13 00:05:28.272  1018  1057 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,09-13 00:05:28.272  7018  7018 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,09-13 00:05:28.272  7018  7018 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,09-13 00:05:28.272  7166  7166 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 00:05:28.272  7166  7166 D ActivityThread: Added TimaKeyStore provider
,09-13 00:05:28.282  1018  1331 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-13 00:05:28.282  1018  1331 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:28.282  1018  1331 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 00:05:28.282  1018  1331 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-13 00:05:28.282  7018  7018 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
09-13 00:05:28.282  7018  7018 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,09-13 00:05:28.312  7166  7166 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
,09-13 00:05:28.322  7166  7166 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
,09-13 00:05:28.322  1018  1487 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
,09-13 00:05:28.322  1018  1487 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
,09-13 00:05:28.322  1018  1487 W ActivityManager: userId = 0, bbcId = -10000
,09-13 00:05:28.322  1018  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:28.322  1018  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,09-13 00:05:28.322  1018  1031 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,09-13 00:05:28.332  7166  7166 I FilterInstaller: FilterPackageService : ACTION_CHANGED
,09-13 00:05:28.332  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
09-13 00:05:28.332  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:28.332  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:28.332  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:28.332  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:05:28.342  7188  7188 E Zygote  : MountEmulatedStorage()
,09-13 00:05:28.342  7188  7188 I libpersona: KNOX_SDCARD checking this for 10130
09-13 00:05:28.342  7188  7188 E Zygote  : v2
09-13 00:05:28.342  7188  7188 I libpersona: KNOX_SDCARD not a persona
09-13 00:05:28.342  7188  7188 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 00:05:28.342  1018  1043 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=7188 uid=10130 gids={50130, 9997} abi=armeabi-v7a,
,09-13 00:05:28.352  7188  7188 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 00:05:28.352  7188  7188 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,09-13 00:05:28.352  7166  7186 E FilterInstaller: installFilters
09-13 00:05:28.352  7166  7186 E FilterInstaller: There is no requred permission
,09-13 00:05:28.352  1018  1079 I ActivityManager: Killing 6693:com.samsung.helphub/1000 (adj 15): empty #21
,09-13 00:05:28.362  7188  7188 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 00:05:28.372  7188  7188 D ActivityThread: Added TimaKeyStore provider
,09-13 00:05:28.382  7188  7188 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-13 00:05:28.382  7188  7188 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,09-13 00:05:28.402  1018  1487 D ActivityManager: startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,09-13 00:05:28.402  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:28.402  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:28.402  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:28.402  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:05:28.412  6843  7163 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-13 00:05:28.412  6843  7163 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-13 00:05:28.422  7204  7204 E Zygote  : MountEmulatedStorage(),
09-13 00:05:28.422  7204  7204 E Zygote  : v2
09-13 00:05:28.422  7204  7204 I libpersona: KNOX_SDCARD checking this for 10131,
09-13 00:05:28.422  7204  7204 I libpersona: KNOX_SDCARD not a persona
,09-13 00:05:28.422  7204  7204 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-13 00:05:28.422  7204  7204 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-13 00:05:28.422  1018  1487 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=7204 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
09-13 00:05:28.422  7204  7204 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-13 00:05:28.422  1018  1487 I ActivityManager: Killing 6672:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
,09-13 00:05:28.462  6843  7163 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,09-13 00:05:28.462  7204  7204 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 00:05:28.462  7204  7204 D ActivityThread: Added TimaKeyStore provider
,09-13 00:05:28.482  7204  7204 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-13 00:05:28.482  7204  7204 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-13 00:05:28.482  7204  7204 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-13 00:05:28.482  7018  7018 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-13 00:05:28.492  7018  7018 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-13 00:05:28.512  7018  7018 D PhoneWindow: *FMB* installDecor mIsFloating : false
,09-13 00:05:28.512  7018  7018 D PhoneWindow: *FMB* installDecor flags : -2139027200
09-13 00:05:28.522  6843  7163 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
09-13 00:05:28.522  6843  7163 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@34153f40: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
09-13 00:05:28.522  6843  7163 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-13 00:05:28.522  7018  7018 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-13 00:05:28.522  2510  2518 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,09-13 00:05:28.532  1018  1223 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
09-13 00:05:28.532  1018  1223 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,09-13 00:05:28.532  1018  1223 W ActivityManager: userId = 0, bbcId = -10000
,09-13 00:05:28.532  1018  1223 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:28.532  7018  7018 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-13 00:05:28.532  7018  7018 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-13 00:05:28.532  1018  1223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,09-13 00:05:28.552  1018  1331 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
09-13 00:05:28.552  1018  1331 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,09-13 00:05:28.552  1018  1331 W ActivityManager: userId = 0, bbcId = -10000
,09-13 00:05:28.552  1018  1331 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:28.552  1018  1331 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,09-13 00:05:28.562  1018  1472 I ActivityManager: Killing 6707:com.sec.spp.push/u0a32 (adj 15): empty #21
,09-13 00:05:28.572  7018  7230 D OpenGLRenderer: Render dirty regions requested: true
,09-13 00:05:28.582  1018  1487 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-13 00:05:28.582  1018  1487 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-13 00:05:28.582  1018  1487 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-13 00:05:28.582  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,09-13 00:05:28.582  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
,09-13 00:05:28.592  7018  7018 V ActivityThread: updateVisibility : ActivityRecord{2874196f token=android.os.BinderProxy@83cc349 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-13 00:05:28.592  7018  7160 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,09-13 00:05:28.602  7018  7018 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,09-13 00:05:28.602  7018  7018 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,09-13 00:05:28.612   259   259 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,09-13 00:05:28.612  1018  1031 D InputDispatcher: Focus entered window: 7018
,09-13 00:05:28.622  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-13 00:05:28.622  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-13 00:05:28.622  7018  7018 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-13 00:05:28.622  7018  7230 I OpenGLRenderer: Initialized EGL, version 1.4
,09-13 00:05:28.632  7018  7230 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,09-13 00:05:28.632  7018  7230 D OpenGLRenderer: Enabling debug mode 0
,09-13 00:05:28.652  1018  1505 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-13 00:05:28.652  1175  1175 D PanelView: There is/are notification(s) 
,09-13 00:05:28.652  1018  7235 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 00:05:28.672  1018  1048 I ActivityManager: Displayed Component not be shown by security: +1s257ms (total +1s449ms)
,09-13 00:05:28.672  7018  7018 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
09-13 00:05:28.672  1018  1048 W ActivityManager: mDVFSHelper.release()
09-13 00:05:28.672  1018  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{29a44c4e u0 com.test.thalitest/.MainActivity t163} time:99543
,09-13 00:05:28.672   259  1114 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,09-13 00:05:28.672   259   440 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,09-13 00:05:28.682  7018  7018 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@83cc349 time:99550
,09-13 00:05:28.692  1886  1886 I SamsungIME: getCurrentCandidateView
,09-13 00:05:28.742  1018  1031 I ActivityManager: Killing 6766:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
,09-13 00:05:28.802  1886  1886 D SamsungIME: Dismiss ExpandCandiate
,09-13 00:05:28.832  7018  7018 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7018
,09-13 00:05:28.952  1886  1886 I SamsungIME: getDebugLevel  : 0x4f4c
,09-13 00:05:28.992  1886  1886 I SamsungIME: getDebugLevel  : 0x4f4c
,09-13 00:05:29.002  1886  1886 I SamsungIME: KeybaordView init() : load resources
,09-13 00:05:29.012  7018  7018 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-13 00:05:29.032  1886  1886 I SamsungIME: getCurrentKeyboard
,09-13 00:05:29.032  1886  1886 I SamsungIME: getTextKeyboard
,09-13 00:05:29.052  1886  1886 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-13 00:05:29.092  7018  7237 D jxcore_app_log: JniHelper::setJavaVM(0xb7d6f2b0), pthread_self() = -1204820624
,09-13 00:05:29.102  7018  7237 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-13 00:05:29.102  7018  7237 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-13 00:05:29.102  7018  7237 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-13 00:05:29.102  7018  7237 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-13 00:05:29.102  7018  7237 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-13 00:05:29.102  7018  7237 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31e6c7b2 added. We now have 1 listener(s)
,09-13 00:05:29.112  7018  7237 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
,09-13 00:05:29.112  7018  7237 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-13 00:05:29.112  7018  7237 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 00:05:29.112  7018  7237 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 00:05:29.122  7018  7237 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-13 00:05:29.122  7018  7237 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-13 00:05:29.122  7018  7237 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-13 00:05:29.122  7018  7237 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
09-13 00:05:29.122  7018  7237 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-13 00:05:29.122  7018  7237 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-13 00:05:29.122  7018  7237 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-13 00:05:29.122  7018  7237 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-13 00:05:29.122  7018  7237 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-13 00:05:29.122  7018  7237 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-13 00:05:29.122  7018  7237 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-13 00:05:29.122  7018  7237 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-13 00:05:29.122  7018  7237 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-13 00:05:29.122  7018  7237 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-13 00:05:29.122  7018  7237 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2bc010b9 added. We now have 1 listener(s)
,09-13 00:05:29.122  7018  7237 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 00:05:29.122  7018  7237 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 00:05:29.122  7018  7237 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-13 00:05:29.122  7018  7237 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-13 00:05:29.122  7018  7237 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-13 00:05:29.122  7018  7237 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-13 00:05:29.132  7018  7237 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 00:05:29.132  7018  7237 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
,09-13 00:05:29.142  7018  7237 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-13 00:05:29.142  7018  7237 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 00:05:29.142  7018  7237 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:05:29.142  7018  7237 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:05:29.142  7018  7237 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:05:29.142  7018  7237 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:05:29.142  7018  7237 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 00:05:29.142  7018  7237 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 00:05:29.142  7018  7237 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 00:05:29.142  7018  7237 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-13 00:05:29.142  7018  7237 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 00:05:29.142  7018  7237 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-13 00:05:29.142  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:05:29.152  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:05:29.172  7018  7018 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-13 00:05:29.702  7018  7244 W jxcore-log: Initializing JXcore engine
09-13 00:05:29.702  7018  7244 W jxcore-log: JXcore engine is ready
,09-13 00:05:29.762  6928  6928 I Mms/MmsApp:  start initViewCache mms
09-13 00:05:29.762  2019  2019 E audit   : type=1400 msg=audit(1473717929.752:205): avc:  denied  { ioctl } for  pid=7244 comm="Thread-1325" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2066 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-13 00:05:29.762  6928  6928 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1939.754166
09-13 00:05:29.762  2019  2019 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
09-13 00:05:29.762  2019  2019 E audit   : type=1300 msg=audit(1473717929.752:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9db048f8 items=0 ppid=308 ppcomm=main pid=7244 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1325" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
09-13 00:05:29.762  2019  2019 E audit   : type=1320 msg=audit(1473717929.752:205): 
,09-13 00:05:29.762  6928  6928 D Mms/ComposeMessageFragment: fillCache, easy = false
,09-13 00:05:29.772  7018  7244 W jxcore-log: Starting JXcore engine
,09-13 00:05:29.882  7018  7244 W jxcore-log: Platform android
09-13 00:05:29.882  7018  7244 W jxcore-log: 
09-13 00:05:29.882  7018  7244 W jxcore-log: Process ARCH arm
09-13 00:05:29.882  7018  7244 W jxcore-log: 
,09-13 00:05:29.902  1018  1031 I art     : Explicit concurrent mark sweep GC freed 19843(1073KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 22MB/34MB, paused 2.516ms total 135.211ms
,09-13 00:05:29.992  6928  6928 D AbsListView: Get MotionRecognitionManager
,09-13 00:05:29.992  1018  4259 D MotionRecognitionService:  ssp status : false
,09-13 00:05:29.992  6928  6928 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 236.878385
,09-13 00:05:30.072  6928  6928 D Mms/BubbleViewCache: fillCache bubble = 1
,09-13 00:05:30.092  7018  7244 I jxcore-log: JXcore Cordova bridge is ready!
09-13 00:05:30.092  7018  7244 I jxcore-log: 
,09-13 00:05:30.092  7018  7244 W jxcore-log: JXcore engine is started
,09-13 00:05:30.102  7018  7237 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-13 00:05:30.102  7018  7018 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-13 00:05:30.172   292   292 E SMD     : DCD OFF,
,09-13 00:05:32.442  1695  1695 I ConfigService: onDestroy
,09-13 00:05:32.532  1018  3405 D SSRM:n  : SIOP:: AP = 400
,09-13 00:05:32.782  1018  3428 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 00:05:33.172   292   292 E SMD     : DCD OFF,
,09-13 00:05:35.062  1018  1487 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 00:05:35.062  1018  1487 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4253, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-13 00:05:35.062  1018  1487 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-13 00:05:35.062  1018  1487 D BatteryService: stay LED for charging
09-13 00:05:35.062  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 00:05:35.062  1018  1018 I MotionRecognitionService: Plugged
,09-13 00:05:35.062  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,09-13 00:05:35.072  1414  1414 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-13 00:05:35.072  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-13 00:05:35.072  1175  1175 D KeyguardUpdateMonitor: handleBatteryUpdate
09-13 00:05:35.072  1414  1414 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-13 00:05:35.082  3263  3263 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 00:05:35.082  3263  3403 D HeadsetStateMachine: Disconnected process message: 10
,09-13 00:05:35.102  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 00:05:35.102  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 00:05:35.102  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 00:05:36.172   292   292 E SMD     : DCD OFF
,09-13 00:05:37.142  1018  1316 E Watchdog: !@Sync 3
,09-13 00:05:37.262  1018  1057 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS,
,09-13 00:05:38.192   323   323 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6,
09-13 00:05:38.192   323   323 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-13 00:05:38.272  1018  1057 D PackageManager: [MSG] MCS_UNBIND,
,09-13 00:05:38.282  1018  1489 I ActivityManager: Killing 6721:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,09-13 00:05:39.172   292   292 E SMD     : DCD OFF,
,09-13 00:05:42.172   292   292 E SMD     : DCD OFF,
,09-13 00:05:42.192  1018  1097 V AlarmManager: waitForAlarm result :4
,09-13 00:05:42.192  1018  1097 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,09-13 00:05:42.332  1018  1050 I PowerManagerService: [PWL] Off : 50s ago
,09-13 00:05:42.422  6889  7011 D Finsky  : [1294] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,09-13 00:05:42.422  6889  6889 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,09-13 00:05:42.522  7018  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-13 00:05:42.522  7018  7244 I jxcore-log: 
,09-13 00:05:42.522  7018  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-13 00:05:42.522  7018  7244 I jxcore-log: 
,09-13 00:05:42.522  7018  7244 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 00:05:42.522  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:05:42.522  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:05:42.522  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:05:42.522  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:05:42.522  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 00:05:42.522  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 00:05:42.522  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 00:05:42.532  7018  7244 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,09-13 00:05:42.532  7018  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native,
09-13 00:05:42.532  7018  7244 I jxcore-log: 
,09-13 00:05:42.532  7018  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native,
09-13 00:05:42.532  7018  7244 I jxcore-log: 
,09-13 00:05:42.552  1018  3405 D SSRM:n  : SIOP:: AP = 360,
,09-13 00:05:43.182  7018  7244 D executeNativeTests: Running unit tests
,09-13 00:05:43.202   323   323 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 00:05:43.272  7018  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 00:05:43.272  7018  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8d4e02 added. We now have 2 listener(s)
,09-13 00:05:43.272  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-13 00:05:43.272  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 00:05:43.272  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 00:05:43.272  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 00:05:43.272  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d7b0313 added. We now have 2 listener(s)
09-13 00:05:43.272  7018  7244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 00:05:43.272  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 00:05:43.272  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 00:05:43.282  7018  7244 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 00:05:43.282  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:05:43.282  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:05:43.282  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:05:43.282  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:05:43.282  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 00:05:43.282  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 00:05:43.282  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 00:05:43.282  7018  7244 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 00:05:43.282  7018  7244 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 00:05:43.282  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:05:43.282  7018  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-13 00:05:43.282  7018  7244 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 00:05:43.282  7018  7244 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 00:05:43.292  7018  7244 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-13 00:05:43.292  7018  7244 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 00:05:43.292  7018  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 00:05:43.292  7018  7244 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 00:05:43.292  7018  7244 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-13 00:05:43.292  7018  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:05:43.292  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:05:43.292  7018  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:05:43.292  7018  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:05:43.292  7018  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:05:43.292  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.292  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 00:05:43.292  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-13 00:05:43.292  7018  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8d4e02 removed from the list
09-13 00:05:43.292  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:43.292  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d7b0313 removed from the list
09-13 00:05:43.292  7018  7244 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:05:43.292  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 00:05:43.292  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.292  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 00:05:43.292  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:05:43.292  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:05:43.292  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:43.292  7018  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d7b0313 not in the list
,09-13 00:05:43.302  7018  7244 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-13 00:05:43.302  7018  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:05:43.302  7018  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:05:43.302  7018  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:05:43.302  7018  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:05:43.302  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.302  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:43.302  7018  7244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8d4e02 not in the list
09-13 00:05:43.302  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:43.302  7018  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d7b0313 not in the list
09-13 00:05:43.302  7018  7244 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:05:43.302  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.302  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:43.302  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.302  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 00:05:43.302  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:05:43.302  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:05:43.302  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:43.302  7018  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d7b0313 not in the list
,09-13 00:05:43.302  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55],
09-13 00:05:43.302  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 00:05:43.302  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 00:05:43.302  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 00:05:43.302  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 00:05:43.302  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 00:05:43.302  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 00:05:43.302  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 00:05:43.302  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 00:05:43.302  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-13 00:05:43.302  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 00:05:43.302  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 00:05:43.302  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 00:05:43.302  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 00:05:43.302  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 00:05:43.302  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410],
09-13 00:05:43.302  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 00:05:43.302  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 00:05:43.302  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 00:05:43.302  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 00:05:43.302  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910],
09-13 00:05:43.302  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 00:05:43.302  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 00:05:43.302  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 00:05:43.302  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-13 00:05:43.302  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 00:05:43.302  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 00:05:43.302  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 00:05:43.302  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 00:05:43.302  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 00:05:43.302  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,09-13 00:05:43.302  7018  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:05:43.302  7018  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:05:43.302  7018  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:05:43.302  7018  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:05:43.302  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.302  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:43.302  7018  7244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8d4e02 not in the list
09-13 00:05:43.302  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:43.302  7018  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d7b0313 not in the list
,09-13 00:05:43.302  7018  7244 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:05:43.302  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.302  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:43.302  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.302  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:43.302  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 00:05:43.302  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:05:43.302  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:43.302  7018  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d7b0313 not in the list
09-13 00:05:43.302  7018  7244 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 00:05:43.312  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 00:05:43.312  7018  7244 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 00:05:43.312  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:05:43.312  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:05:43.312  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:05:43.312  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:05:43.312  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 00:05:43.312  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 00:05:43.312  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 00:05:43.312  7018  7244 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
09-13 00:05:43.312  7018  7244 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 00:05:43.312  7018  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 00:05:43.312  7018  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only,
09-13 00:05:43.312  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 00:05:43.312  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
09-13 00:05:43.312  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 00:05:43.312  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:05:43.322  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:05:43.322  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 00:05:43.322  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 00:05:43.332  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 00:05:43.332  7018  7244 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-13 00:05:43.332  7018  7244 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-13 00:05:43.332  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-13 00:05:43.332  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-13 00:05:43.332  7018  7244 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-13 00:05:43.342  3263  3280 D BtGatt.GattService: registerClient() - UUID=b8615044-2920-4f54-8967-c253279e7e30
,09-13 00:05:43.392  3263  3345 D BtGatt.GattService: onClientRegistered() - UUID=b8615044-2920-4f54-8967-c253279e7e30, clientIf=6
,09-13 00:05:43.392  7018  7032 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-13 00:05:43.392  3263  3398 D BtGatt.GattService: start scan with filters
,09-13 00:05:43.392  3263  3401 D BtGatt.ScanManager: handling starting scan
,09-13 00:05:43.392  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-13 00:05:43.392  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-13 00:05:43.392  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-13 00:05:43.392  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-13 00:05:43.402  7018  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 00:05:43.402  3263  3401 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4aba78f
,09-13 00:05:43.402  7018  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 00:05:43.402  7018  7018 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 00:05:43.402  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 00:05:43.412  3263  3345 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-13 00:05:43.412  3263  3345 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 00:05:43.412  3263  3401 D BtGatt.ScanManager: allow scan with filters
,09-13 00:05:43.412  3263  3401 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-13 00:05:43.412  3263  3401 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,09-13 00:05:43.412  7018  7244 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 00:05:43.422  7018  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 00:05:43.422  7018  7244 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-13 00:05:43.422  3263  3345 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-13 00:05:43.422  3263  3345 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 00:05:43.422  7018  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-13 00:05:43.422  7018  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 00:05:43.422  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.422  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 00:05:43.422  7018  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 00:05:43.422  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 00:05:43.422  7018  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 00:05:43.422  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-13 00:05:43.422  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 00:05:43.422  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-13 00:05:43.422  3263  3401 D BtGatt.ScanManager: Starting BLE batch scan
09-13 00:05:43.422  3263  3401 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-13 00:05:43.422  3263  3398 D BtGatt.GattService: stopScan() - queue size =1
,09-13 00:05:43.422  3263  3416 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-13 00:05:43.432  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 00:05:43.432  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 00:05:43.432  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 00:05:43.432  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 00:05:43.432  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-13 00:05:43.432  7018  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 00:05:43.432  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 00:05:43.432  7018  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-13 00:05:43.432  3263  3345 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-13 00:05:43.432  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 00:05:43.432  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 00:05:43.432  3263  3345 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 00:05:43.442  7018  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:05:43.442  7018  7018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 00:05:43.442  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.442  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 00:05:43.442  7018  7018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 00:05:43.442  7018  7244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8d4e02 not in the list
,09-13 00:05:43.442  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:43.442  7018  7018 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 00:05:43.442  7018  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d7b0313 not in the list
,09-13 00:05:43.442  7018  7244 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:05:43.442  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:43.442  3263  3345 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-13 00:05:43.442  3263  3345 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 00:05:43.442  7018  7244 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-13 00:05:43.452  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 00:05:43.452  3263  3401 D BtGatt.ScanManager: filter size is 1
,09-13 00:05:43.452  3263  3401 D BtGatt.ScanManager: delete FilterIndex - 3
,09-13 00:05:43.452  7018  7244 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 00:05:43.452  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:05:43.452  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:05:43.452  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:05:43.452  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:05:43.452  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 00:05:43.452  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 00:05:43.452  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 00:05:43.452  3263  3345 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-13 00:05:43.462  3263  3345 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 00:05:43.462  3263  3401 D BtGatt.ScanManager: stopping BLe Batch
,09-13 00:05:43.462  7018  7244 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 00:05:43.462  7018  7244 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 00:05:43.462  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:05:43.462  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:05:43.462  3263  3345 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-13 00:05:43.472  3263  3345 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 00:05:43.472  3263  3401 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-13 00:05:43.472  7018  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 00:05:43.472  7018  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 00:05:43.472  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 00:05:43.472  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 00:05:43.472  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 00:05:43.472  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 00:05:43.472  3263  3345 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-13 00:05:43.472  3263  3345 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 00:05:43.482  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 00:05:43.482  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 00:05:43.482  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-13 00:05:43.482  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-13 00:05:43.482  7018  7244 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-13 00:05:43.492  3263  3280 D BtGatt.GattService: registerClient() - UUID=d86001d4-ba1d-425a-9014-e8af904d59c2
,09-13 00:05:43.532  3263  3345 D BtGatt.GattService: onClientRegistered() - UUID=d86001d4-ba1d-425a-9014-e8af904d59c2, clientIf=6
,09-13 00:05:43.532  7018  7026 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-13 00:05:43.532  3263  3398 D BtGatt.GattService: start scan with filters
,09-13 00:05:43.532  3263  3401 D BtGatt.ScanManager: handling starting scan
,09-13 00:05:43.532  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-13 00:05:43.532  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-13 00:05:43.532  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-13 00:05:43.532  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-13 00:05:43.532  7018  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 00:05:43.542  7018  7018 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 00:05:43.542  7018  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 00:05:43.542  3263  3345 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-13 00:05:43.542  3263  3345 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 00:05:43.542  3263  3401 D BtGatt.ScanManager: allow scan with filters
09-13 00:05:43.542  3263  3401 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-13 00:05:43.542  3263  3401 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,09-13 00:05:43.542  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 00:05:43.552  3263  3345 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-13 00:05:43.552  3263  3345 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 00:05:43.552  3263  3401 D BtGatt.ScanManager: Starting BLE batch scan
09-13 00:05:43.552  3263  3401 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-13 00:05:43.552  7018  7244 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 00:05:43.552  3263  3345 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-13 00:05:43.552  3263  3345 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 00:05:43.562  7018  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 00:05:43.562  7018  7244 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-13 00:05:43.562  7018  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-13 00:05:43.562  7018  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 00:05:43.562  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 00:05:43.562  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 00:05:43.562  7018  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-13 00:05:43.562  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-13 00:05:43.562  3263  3345 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-13 00:05:43.562  3263  3345 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 00:05:43.572  7018  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 00:05:43.572  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 00:05:43.572  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 00:05:43.572  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-13 00:05:43.572  3263  3398 D BtGatt.GattService: stopScan() - queue size =1
,09-13 00:05:43.572  3263  3401 D BtGatt.ScanManager: filter size is 1
09-13 00:05:43.572  3263  3401 D BtGatt.ScanManager: delete FilterIndex - 4
,09-13 00:05:43.572  3263  3416 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-13 00:05:43.572  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 00:05:43.572  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 00:05:43.572  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-13 00:05:43.572  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 00:05:43.572  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-13 00:05:43.572  7018  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 00:05:43.572  3263  3345 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-13 00:05:43.572  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 00:05:43.572  7018  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 00:05:43.572  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 00:05:43.572  3263  3345 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 00:05:43.582  3263  3401 D BtGatt.ScanManager: stopping BLe Batch
,09-13 00:05:43.582  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 00:05:43.582  7018  7018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 00:05:43.582  7018  7018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 00:05:43.582  7018  7018 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 00:05:43.582  7018  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 00:05:43.582  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.582  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 00:05:43.582  7018  7244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8d4e02 not in the list
09-13 00:05:43.582  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:43.582  7018  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d7b0313 not in the list
,09-13 00:05:43.582  7018  7244 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:05:43.582  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 00:05:43.582  3263  3345 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-13 00:05:43.582  3263  3345 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 00:05:43.582  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.582  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:43.582  3263  3401 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-13 00:05:43.582  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:05:43.582  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:05:43.582  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:43.582  7018  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d7b0313 not in the list
,09-13 00:05:43.582  7018  7244 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-13 00:05:43.592  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 00:05:43.592  3263  3345 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
09-13 00:05:43.592  3263  3345 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 00:05:43.592  7018  7244 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 00:05:43.592  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:05:43.592  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:05:43.592  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:05:43.592  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:05:43.592  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 00:05:43.592  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 00:05:43.592  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 00:05:43.592  7018  7244 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 00:05:43.602  7018  7244 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 00:05:43.602  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:05:43.602  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:05:43.602  7018  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-13 00:05:43.602  7018  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 00:05:43.602  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-13 00:05:43.602  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 00:05:43.602  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 00:05:43.612  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 00:05:43.612  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 00:05:43.612  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 00:05:43.622  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-13 00:05:43.622  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-13 00:05:43.622  7018  7244 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-13 00:05:43.622  3263  3398 D BtGatt.GattService: registerClient() - UUID=6e26ae3d-7d5d-4af6-a760-1f672a10c973
,09-13 00:05:43.662  3263  3345 D BtGatt.GattService: onClientRegistered() - UUID=6e26ae3d-7d5d-4af6-a760-1f672a10c973, clientIf=6
,09-13 00:05:43.662  7018  7032 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-13 00:05:43.662  3263  3416 D BtGatt.GattService: start scan with filters
,09-13 00:05:43.672  3263  3401 D BtGatt.ScanManager: handling starting scan
,09-13 00:05:43.672  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-13 00:05:43.672  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-13 00:05:43.672  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-13 00:05:43.672  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-13 00:05:43.672  3263  3345 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-13 00:05:43.672  3263  3345 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 00:05:43.672  3263  3401 D BtGatt.ScanManager: allow scan with filters
,09-13 00:05:43.672  3263  3401 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-13 00:05:43.672  3263  3401 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,09-13 00:05:43.682  3263  3345 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-13 00:05:43.682  3263  3345 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 00:05:43.682  3263  3401 D BtGatt.ScanManager: Starting BLE batch scan
09-13 00:05:43.682  3263  3401 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-13 00:05:43.682  7018  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 00:05:43.682  7018  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 00:05:43.682  7018  7018 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 00:05:43.682  3263  3345 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-13 00:05:43.682  3263  3345 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 00:05:43.682  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 00:05:43.692  3263  3345 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-13 00:05:43.692  3263  3345 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 00:05:43.692  7018  7244 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 00:05:43.692  7018  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:05:43.692  7018  7244 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-13 00:05:43.702  7018  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-13 00:05:43.702  7018  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 00:05:43.702  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.702  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 00:05:43.702  7018  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 00:05:43.702  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 00:05:43.702  7018  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 00:05:43.702  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 00:05:43.702  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 00:05:43.702  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-13 00:05:43.702  3263  3417 D BtGatt.GattService: stopScan() - queue size =1
,09-13 00:05:43.702  3263  3401 D BtGatt.ScanManager: filter size is 1
,09-13 00:05:43.702  3263  3401 D BtGatt.ScanManager: delete FilterIndex - 5
,09-13 00:05:43.702  3263  3280 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-13 00:05:43.702  3263  3345 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-13 00:05:43.702  3263  3345 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 00:05:43.702  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 00:05:43.702  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 00:05:43.702  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 00:05:43.702  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 00:05:43.702  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-13 00:05:43.702  3263  3401 D BtGatt.ScanManager: stopping BLe Batch
,09-13 00:05:43.712  7018  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 00:05:43.712  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 00:05:43.712  7018  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 00:05:43.712  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 00:05:43.712  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 00:05:43.712  7018  7018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 00:05:43.712  7018  7018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 00:05:43.712  7018  7018 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 00:05:43.712  7018  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 00:05:43.712  7018  7244 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-13 00:05:43.712  7018  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:05:43.712  7018  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 00:05:43.712  7018  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 00:05:43.712  3263  3345 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-13 00:05:43.712  3263  3345 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 00:05:43.712  3263  3401 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-13 00:05:43.712  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.712  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 00:05:43.712  7018  7244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8d4e02 not in the list
09-13 00:05:43.712  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:43.712  7018  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d7b0313 not in the list
09-13 00:05:43.712  7018  7244 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:05:43.712  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:43.712  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.712  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 00:05:43.722  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 00:05:43.722  3263  3345 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-13 00:05:43.722  3263  3345 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 00:05:43.722  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 00:05:43.722  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:43.722  7018  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d7b0313 not in the list
,09-13 00:05:43.722  7018  7244 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-13 00:05:43.722  7018  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 00:05:43.722  7018  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:05:43.722  7018  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 00:05:43.722  7018  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:05:43.722  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 00:05:43.722  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:43.722  7018  7244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8d4e02 not in the list
09-13 00:05:43.722  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 00:05:43.722  7018  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d7b0313 not in the list
09-13 00:05:43.722  7018  7244 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:05:43.722  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.732  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 00:05:43.732  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.732  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 00:05:43.732  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:05:43.732  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:05:43.732  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:43.732  7018  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d7b0313 not in the list
,09-13 00:05:43.732  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-13 00:05:43.732  7018  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:05:43.732  7018  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:05:43.732  7018  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 00:05:43.732  7018  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:05:43.732  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.732  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:43.732  7018  7244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8d4e02 not in the list
09-13 00:05:43.732  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:43.732  7018  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d7b0313 not in the list
09-13 00:05:43.732  7018  7244 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:05:43.732  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.732  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:43.732  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.732  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 00:05:43.732  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:05:43.732  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:05:43.732  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:43.732  7018  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d7b0313 not in the list
,09-13 00:05:43.732  7018  7244 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-13 00:05:43.732  7018  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:05:43.732  7018  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:05:43.732  7018  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:05:43.732  7018  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:05:43.732  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 00:05:43.732  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:43.732  7018  7244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8d4e02 not in the list
09-13 00:05:43.732  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:43.732  7018  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d7b0313 not in the list
09-13 00:05:43.732  7018  7244 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:05:43.732  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.732  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 00:05:43.732  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.732  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:43.732  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:05:43.732  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 00:05:43.732  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:43.732  7018  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d7b0313 not in the list
09-13 00:05:43.732  7018  7244 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-13 00:05:43.732  7018  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:05:43.732  7018  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:05:43.732  7018  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:05:43.732  7018  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:05:43.732  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.732  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:43.732  7018  7244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8d4e02 not in the list
09-13 00:05:43.732  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:43.732  7018  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d7b0313 not in the list
09-13 00:05:43.732  7018  7244 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:05:43.732  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.732  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:43.732  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.732  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:43.742  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:05:43.742  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:05:43.742  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:43.742  7018  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d7b0313 not in the list
09-13 00:05:43.742  7018  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 00:05:43.742  7018  7244 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 00:05:43.742  7018  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 00:05:43.742  7018  7244 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 00:05:43.742  7018  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 00:05:43.742  7018  7244 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfc,ommSocketPort: -1 -> 1
09-13 00:05:43.742  7018  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:05:43.742  7018  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:05:43.742  7018  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:05:43.742  7018  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:05:43.742  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.742  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:43.742  7018  7244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8d4e02 not in the list
09-13 00:05:43.742  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:43.742  7018  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d7b0313 not in the list
09-13 00:05:43.742  7018  7244 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:05:43.742  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.742  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:43.742  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.742  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:43.742  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:05:43.742  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:05:43.742  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:43.742  7018  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d7b0313 not in the list
09-13 00:05:43.742  7018  7244 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 00:05:43.742  7018  7244 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 00:05:43.742  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-13 00:05:43.752  7018  7244 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 00:05:43.752  7018  7244 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-13 00:05:43.752  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 00:05:43.752  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 00:05:43.752  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 00:05:43.752  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 00:05:43.752  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 00:05:43.752  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 00:05:43.752  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 00:05:43.752  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 00:05:43.752  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 00:05:43.752  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 00:05:43.752  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 00:05:43.752  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 00:05:43.752  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 00:05:43.752  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 00:05:43.752  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 00:05:43.752  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 00:05:43.752  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 00:05:43.752  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 00:05:43.752  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 00:05:43.752  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 00:05:43.752  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 00:05:43.752  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 00:05:43.752  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 00:05:43.752  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 00:05:43.752  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 00:05:43.752  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 00:05:43.752  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 00:05:43.752  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 00:05:43.752  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 00:05:43.752  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 00:05:43.752  7018  7244 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-13 00:05:43.752  7018  7244 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 00:05:43.752  7018  7244 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-13 00:05:43.752  7018  7244 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 00:05:43.752  7018  7244 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 00:05:43.752  7018  7244 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-13 00:05:43.752  7018  7244 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 00:05:43.752  7018  7244 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 00:05:43.752  7018  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-13 00:05:43.762  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-13 00:05:43.762  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-13 00:05:43.762  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-13 00:05:43.762  7018  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-13 00:05:43.762  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-13 00:05:43.762  7018  7244 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-13 00:05:43.762  7018  7244 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 00:05:43.762  7018  7244 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-13 00:05:43.762  7018  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:05:43.762  7018  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:05:43.762  7018  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:05:43.762  7018  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:05:43.762  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.762  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:43.762  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-13 00:05:43.762  7018  7244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8d4e02 not in the list
09-13 00:05:43.762  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:43.762  7018  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d7b0313 not in the list
09-13 00:05:43.762  7018  7244 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:05:43.762  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.762  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:43.762  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.762  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:43.762  7018  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1389)
09-13 00:05:43.762  7018  7257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1389
09-13 00:05:43.772  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:05:43.772  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:05:43.772  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:43.772  7018  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d7b0313 not in the list
09-13 00:05:43.772  7018  7244 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-13 00:05:43.772  7018  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:05:43.772  7018  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:05:43.772  7018  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:05:43.772  7018  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:05:43.772  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.772  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:43.772  7018  7244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8d4e02 not in the list
09-13 00:05:43.772  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:43.772  7018  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d7b0313 not in the list
09-13 00:05:43.772  7018  7244 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:05:43.772  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.772  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:43.772  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.772  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:43.772  7018  7256 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
09-13 00:05:43.772  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:05:43.772  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:05:43.772  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:43.772  7018  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d7b0313 not in the list
09-13 00:05:43.772  7018  7244 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-13 00:05:43.772  7018  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:05:43.772  7018  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:05:43.772  7018  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:05:43.772  7018  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:05:43.772  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.772  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:43.772  7018  7244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8d4e02 not in the list
09-13 00:05:43.772  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:43.772  7018  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d7b0313 not in the list
09-13 00:05:43.772  7018  7244 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:05:43.772  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.772  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:43.772  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.772  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:43.772  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:05:43.772  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:05:43.772  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:43.772  7018  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d7b0313 not in the list
09-13 00:05:43.772  7018  7256 D BluetoothSocket: connect(): myUserId = 0
09-13 00:05:43.772  7018  7244 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,09-13 00:05:43.772  7018  7244 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-13 00:05:43.782  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 00:05:43.782  7018  7244 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-13 00:05:43.782  7018  7244 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 00:05:43.782  7018  7244 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-13 00:05:43.782  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 00:05:43.782  7018  7244 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-13 00:05:43.782  7018  7244 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 00:05:43.782  7018  7244 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 00:05:43.782  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 00:05:43.782  7018  7244 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-13 00:05:43.782  7018  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:05:43.782  7018  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:05:43.782  7018  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:05:43.782  7018  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:05:43.782  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.782  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:43.782  7018  7244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8d4e02 not in the list
09-13 00:05:43.782  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:43.782  7018  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d7b0313 not in the list
09-13 00:05:43.782  7018  7244 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:05:43.782  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.782  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:43.782  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.782  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:43.782  7018  7256 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 00:05:43.782  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:05:43.782  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:05:43.782  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:43.782  7018  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d7b0313 not in the list
09-13 00:05:43.782  7018  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:05:43.782  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.782  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:43.782  7018  7244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8d4e02 not in the list
09-13 00:05:43.782  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:43.782  7018  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d7b0313 not in the list
09-13 00:05:43.782  7018  7244 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:05:43.782  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.782  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:43.782  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:43.782  7018  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d7b0313 not in the list
09-13 00:05:43.782  7018  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:05:43.782  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.782  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:43.782  7018  7244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8d4e02 not in the list
09-13 00:05:43.782  7018  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:05:43.782  7018  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:05:43.782  7018  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:05:43.782  7018  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:05:43.782  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.782  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:43.782  7018  7244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8d4e02 not in the list
09-13 00:05:43.782  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:43.782  7018  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d7b0313 not in the list
09-13 00:05:43.782  7018  7244 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:05:43.782  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.782  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:43.782  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.782  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:43.782  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:05:43.782  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:05:43.782  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:43.782  7018  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d7b0313 not in the list
09-13 00:05:43.782  7018  7244 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 00:05:43.782  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 00:05:43.782  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 00:05:43.782  3263  3280 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 00:05:43.782  7018  7244 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 00:05:43.782  7018  7244 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 00:05:43.782  7018  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 00:05:43.782  7018  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 00:05:43.792  7018  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:05:43.792  7018  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 00:05:43.792  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 00:05:43.792  7018  7018 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 00:05:43.792  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 00:05:43.792  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:43.792  7018  7244 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 00:05:43.792  7018  7018 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 00:05:43.792  7018  7244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8d4e02 not in the list
09-13 00:05:43.792  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:43.792  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 00:05:43.792  7018  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 00:05:43.792  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 00:05:43.792  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.792  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:43.792  7018  7256 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[105]}
09-13 00:05:43.792  7018  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 00:05:43.792  7018  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d7b0313 not in the list
09-13 00:05:43.792  7018  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:05:43.792  7018  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:05:43.792  7018  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:05:43.792  7018  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:05:43.792  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.792  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:43.792  7018  7244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8d4e02 not in the list
09-13 00:05:43.792  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:43.792  7018  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d7b0313 not in the list
09-13 00:05:43.792  7018  7244 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:05:43.792  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.792  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:43.792  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.792  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:43.792  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:05:43.792  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:05:43.792  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:43.792  7018  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d7b0313 not in the list
09-13 00:05:43.792  7018  7018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 00:05:43.792  7018  7018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 00:05:43.792  7018  7018 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 00:05:43.792  7018  7244 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-13 00:05:43.792  7018  7244 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 00:05:43.792  7018  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 00:05:43.792  7018  7244 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 00:05:43.792  7018  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:05:43.792  7018  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:05:43.792  7018  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:05:43.792  7018  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:05:43.792  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.792  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:43.792  7018  7244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8d4e02 not in the list
09-13 00:05:43.792  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:43.792  7018  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d7b0313 not in the list
09-13 00:05:43.792  7018  7244 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:05:43.792  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.792  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:43.792  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.792  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:43.792  7018  7258 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 00:05:43.792  7018  7258 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 00:05:43.792  7018  7018 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 00:05:43.792  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:05:43.792  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:05:43.792  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:43.792  7018  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d7b0313 not in the list
09-13 00:05:43.792  7018  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:05:43.802  7018  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:05:43.802  7018  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:05:43.802  7018  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:05:43.802  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.802  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:43.802  7018  7244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8d4e02 not in the list
09-13 00:05:43.802  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:43.802  7018  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d7b0313 not in the list
09-13 00:05:43.802  7018  7244 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:05:43.802  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.802  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:43.802  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.802  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:43.802  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:05:43.802  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:05:43.802  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:43.802  7018  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d7b0313 not in the list
09-13 00:05:43.802  7018  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:05:43.802  7018  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:05:43.802  7018  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:05:43.802  7018  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:05:43.802  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.802  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:43.802  7018  7244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8d4e02 not in the list
09-13 00:05:43.802  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:43.802  7018  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d7b0313 not in the list
09-13 00:05:43.802  7018  7244 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:05:43.802  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.802  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:43.802  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:05:43.802  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:05:43.802  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:05:43.802  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:05:43.802  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:05:43.802  7018  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d7b0313 not in the list
09-13 00:05:43.802  7018  7244 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-13 00:05:43.802  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 00:05:43.802  7018  7244 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-13 00:05:43.802  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 00:05:43.802  7018  7244 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-13 00:05:43.802  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 00:05:43.802  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-13 00:05:43.802  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-13 00:05:43.802  7018  7244 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-13 00:05:43.802  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 00:05:43.802  7018  7244 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-13 00:05:43.802  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 00:05:43.802  7018  7244 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-13 00:05:43.802  7018  7244 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-13 00:05:43.802  7018  7244 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-13 00:05:43.802  7018  7244 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-13 00:05:43.802  7018  7244 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-13 00:05:43.802  7018  7244 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-13 00:05:43.802  7018  7244 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-13 00:05:43.802  7018  7244 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-13 00:05:43.802  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 00:05:43.802  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@36ba99bd added. We now have 2 listener(s)
09-13 00:05:43.802  7018  7244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 00:05:43.802  7018  7244 D BluetoothAdapter: enable()
09-13 00:05:43.812  7018  7244 D BluetoothAdapter: enable(): BT is already enabled..!
09-13 00:05:43.812  1018  1472 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-13 00:05:43.812  1018  1472 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-13 00:05:43.812  1018  1472 D SecContentProvider2: mCursor = null
09-13 00:05:43.812  1018  1472 D WifiService: setWifiEnabled: true pid=7018, uid=10170
09-13 00:05:43.812  1018  1472 W ActivityManager: Permission Denial: getCurrentUser() from pid=7018, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-13 00:05:43.812  1018  1472 W WifiService: Failed getting userId using ActivityManagerNative
09-13 00:05:43.812  1018  1472 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7018, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-13 00:05:43.812  1018  1472 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-13 00:05:43.812  1018  1472 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-13 00:05:43.812  1018  1472 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-13 00:05:43.812  1018  1472 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-13 00:05:43.812  1018  1472 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-13 00:05:43.812  1018  1472 D SettingsProvider: name = wifi_on
09-13 00:05:43.822  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 00:05:43.822  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d793bb2 added. We now have 3 listener(s)
09-13 00:05:43.822  7018  7244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 00:05:43.822  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 00:05:43.822  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a7ad703 added. We now have 4 listener(s)
09-13 00:05:43.822  7018  7244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 00:05:43.822  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 00:05:43.822  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3322a680 added. We now have 5 listener(s)
09-13 00:05:43.822  7018  7244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 00:05:43.822  1018  1030 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-13 00:05:43.822  1018  1030 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-13 00:05:43.822  1018  1030 D SecContentProvider2: mCursor = null
09-13 00:05:43.822  1018  1030 D WifiService: setWifiEnabled: false pid=7018, uid=10170
09-13 00:05:43.822  1018  1030 D SettingsProvider: name = wifi_on
09-13 00:05:43.832  1018  1128 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-13 00:05:43.832  1380  1380 I wpa_supplicant: reset timer : RESET_TIMER 0
09-13 00:05:43.832  1380  1380 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
09-13 00:05:43.832  1380  1380 I wpa_supplicant: P2P: Current p2p state = IDLE
09-13 00:05:43.832  1380  1380 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
09-13 00:05:43.832  7018  7244 D BluetoothAdapter: disable()
09-13 00:05:43.842  1018  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 00:05:43.842  1018  1331 D SettingsProvider: name = bluetooth_on
09-13 00:05:43.852  3263  3342 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
09-13 00:05:43.852  3263  3342 D BluetoothAdapterProperties: Setting state to 13
09-13 00:05:43.852  3263  3342 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-13 00:05:43.852  3263  3342 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-13 00:05:43.852  3263  3342 D BluetoothAdapterService: updateAdapterState state is 13
09-13 00:05:43.852  1018  4258 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-13 00:05:43.852  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 00:05:43.852  1018  4258 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
09-13 00:05:43.852  1018  4258 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:43.852  1018  4258 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:43.852  1018  4258 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 00:05:43.862  3263  3263 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,09-13 00:05:43.862  1018  1128 E WifiNative-wlan0: do suspend true
,09-13 00:05:43.862  3263  3342 D BluetoothAdapterService: Autoconnection is available 
,09-13 00:05:43.862  3263  3342 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-13 00:05:43.862  3263  3342 D BluetoothAdapterService: terminating service from this receiver
,09-13 00:05:43.862  1018  1505 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-13 00:05:43.862  3263  3263 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2f9afb4f, channel: 19, state: LISTENING
,09-13 00:05:43.862  3263  3263 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2f9afb4f, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1c035857, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2ba942dcmSocket: android.net.LocalSocket@3b98afe5 impl:android.net.LocalSocketImpl@15b8daba fd:FileDescriptor[80]
09-13 00:05:43.862  1018  1505 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:43.862  1018  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:43.862  3263  3263 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3b98afe5 impl:android.net.LocalSocketImpl@15b8daba fd:FileDescriptor[80]
,09-13 00:05:43.862  1018  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-13 00:05:43.862  3263  3342 D BluetoothAdapterProperties: onBluetoothDisable()
,09-13 00:05:43.862  3263  3342 D BluetoothAdapterProperties: mDiscovering is false
,09-13 00:05:43.862  1018  1030 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-13 00:05:43.862  3263  3342 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-13 00:05:43.872  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-13 00:05:43.872  1018  1018 I InputMethodManagerService: [BT Setting State] State =13
,09-13 00:05:43.872  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 00:05:43.872  7018  7244 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 00:05:43.872  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:05:43.872  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:05:43.872  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:05:43.872  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 00:05:43.872  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 00:05:43.872  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 00:05:43.872  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 00:05:43.872  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 00:05:43.872  7018  7244 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 00:05:43.872  7018  7244 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 00:05:43.872  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:05:43.872  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:05:43.882  1175  1175 D BluetoothTile:  onBluetoothStateChange:
,09-13 00:05:43.882  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-13 00:05:43.882  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:05:43.882  1175  1799 D BluetoothTile:  handleUpdatestate:false name:null
,09-13 00:05:43.882  1886  1886 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
09-13 00:05:43.882  1175  1175 D BluetoothTile:  getBluetoothState : 13
,09-13 00:05:43.882  1018  4259 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-13 00:05:43.892  4836  4836 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-13 00:05:43.892  1018  4259 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-13 00:05:43.892  1175  1799 D BluetoothTile:  handleUpdatestate:false name:null
,09-13 00:05:43.892  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-13 00:05:43.892  7018  7018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 00:05:43.892  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:05:43.892  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:05:43.892  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:05:43.892  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:05:43.892  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 00:05:43.892  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 00:05:43.892  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 00:05:43.892  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 00:05:43.902  1175  1799 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-13 00:05:43.902  7018  7018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 00:05:43.902  7018  7018 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,09-13 00:05:43.902  3263  3345 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-13 00:05:43.902  3263  3345 D BluetoothAdapterProperties: Scan Mode:20
,09-13 00:05:43.902  3263  3342 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-13 00:05:43.902  3263  3342 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,09-13 00:05:43.902  3263  3342 E bt-btif : cmd socket is not created
09-13 00:05:43.902  3263  5263 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 00:05:43.902  3263  3346 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,09-13 00:05:43.902  7018  7256 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@23b60fe, channel: -1, state: INIT
09-13 00:05:43.902  7018  7256 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@23b60fe, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@d49e05f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@134baaacmSocket: android.net.LocalSocket@32404375 impl:android.net.LocalSocketImpl@1b688f0a fd:FileDescriptor[105]
09-13 00:05:43.902  7018  7256 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@32404375 impl:android.net.LocalSocketImpl@1b688f0a fd:FileDescriptor[105]
09-13 00:05:43.902  7018  7256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1389)
09-13 00:05:43.902  3263  3342 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-13 00:05:43.902  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:05:43.912  4836  4836 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 00:05:43.912  1018  4258 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-13 00:05:43.912  1018  4258 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-13 00:05:43.912  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:05:43.912  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:05:43.922  1018  4258 W ActivityManager: userId = 0, bbcId = -10000
,09-13 00:05:43.922  3263  3346 W bt-sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
09-13 00:05:43.922  3263  3346 E bt-btif : DISCOVERY_COMP_EVT slot id:4, failed to find channle,                                       status:1, scn:0
09-13 00:05:43.922  3263  3346 W bt-btif : invalid rfc slot id: 4
,09-13 00:05:43.922  1018  4258 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-13 00:05:43.922  1018  4258 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-13 00:05:43.922  3263  3346 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-13 00:05:43.922  4836  4836 D BluetoothPbap: Proxy object disconnected
09-13 00:05:43.922  4836  4836 D PbapServerProfile: Bluetooth service disconnected
,09-13 00:05:43.922  3263  3346 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-13 00:05:43.922  3263  3346 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 00:05:43.922  3263  3346 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 00:05:43.932  3263  3263 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3835fd6b, channel: 5, state: LISTENING
09-13 00:05:43.932  3263  3263 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3835fd6b, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1ca14f44, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@df5b0c8mSocket: android.net.LocalSocket@10296561 impl:android.net.LocalSocketImpl@889e886 fd:FileDescriptor[82]
09-13 00:05:43.932  3263  3263 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@10296561 impl:android.net.LocalSocketImpl@889e886 fd:FileDescriptor[82]
,09-13 00:05:43.932  3263  3346 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 00:05:43.932  3263  3346 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-13 00:05:43.932  3263  3263 I BtOppRfcommListener: stopping Accept Thread
,09-13 00:05:43.932  3263  3263 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@5350547, channel: 12, state: LISTENING
09-13 00:05:43.932  3263  3263 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@5350547, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@176551ae, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3b191174mSocket: android.net.LocalSocket@b5f69d impl:android.net.LocalSocketImpl@190c0712 fd:FileDescriptor[86]
09-13 00:05:43.932  3263  3263 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@b5f69d impl:android.net.LocalSocketImpl@190c0712 fd:FileDescriptor[86]
,09-13 00:05:43.932  3263  5263 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-13 00:05:43.932  1695  1695 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 00:05:43.932  4836  4836 D DockEventReceiver: finishStartingService: stopping service
,09-13 00:05:43.932  1380  1380 I wpa_supplicant: nl80211: Received scan results (17 BSSes)
,09-13 00:05:43.932  1018  1127 D WifiP2pService: InactiveState{ what=147461 }
09-13 00:05:43.942  1018  1127 D WifiP2pService: P2pEnabledState{ what=147461 }
09-13 00:05:43.942  1018  1127 D WifiP2pService: DefaultState{ what=147461 }
,09-13 00:05:43.942  1018  1127 D WifiP2pService: InactiveState{ what=143375 }
09-13 00:05:43.942  1018  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-13 00:05:43.942   279  1017 D CommandListener: Clearing all IP addresses on wlan0
,09-13 00:05:43.942  1695  2560 V NativeCrypto: Read error: ssl=0xb82f0568: I/O error during system call, Connection timed out
,09-13 00:05:43.952  1175  1175 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-13 00:05:43.952  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-13 00:05:43.952  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:05:43.952  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:05:43.952  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:05:43.952  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 00:05:43.952  3263  3263 V BluetoothOppManager: cleanUp...,
09-13 00:05:43.952  1018  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 00:05:43.952  4836  4836 D BluetoothNotiBroadcastReceiver: onReceive
09-13 00:05:43.952  1018  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,09-13 00:05:43.952  1018  1130 E ConnectivityService: updateNetworkInfo()
09-13 00:05:43.952  1695  2560 V NativeCrypto: SSL shutdown failed: ssl=0xb82f0568: I/O error during system call, Broken pipe
,09-13 00:05:43.952  1018  1031 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,09-13 00:05:43.952  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:05:43.952  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
09-13 00:05:43.952  1018  1761 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-3ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:05:43.952  1018  1761 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-3ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:05:43.952  1018  1761 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
,09-13 00:05:43.962  1018  1127 D WifiP2pService: InactiveState{ what=131204 }
,09-13 00:05:43.962  1018  1127 D WifiP2pService: P2pEnabledState{ what=131204 }
09-13 00:05:43.962  1018  1761 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-6ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:05:43.962  1018  1761 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
09-13 00:05:43.962  1018  1761 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 00:05:43.962  1018  1761 I qtaguid : Tagging socket 357 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1018, getuid(): 1000
09-13 00:05:43.962  1018  1128 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-13 00:05:43.972  1018  1127 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,09-13 00:05:43.972  1018  1761 I qtaguid : Untagging socket 357
,09-13 00:05:43.972  1018  1761 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-13 00:05:43.972  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-13 00:05:43.982  1018  1018 D WifiScanningService: SCAN_AVAILABLE : 1
,09-13 00:05:43.982  1018  1152 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,09-13 00:05:43.982  1018  1018 D RttService: SCAN_AVAILABLE : 1
09-13 00:05:43.982  1018  1153 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-13 00:05:43.992  1018  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 00:05:43.992  1018  1048 D WifiDisplayAdapter: onP2pDisconnected
09-13 00:05:43.992  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-13 00:05:43.992  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-13 00:05:43.992  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-13 00:05:43.992  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:05:43.992  1018  1504 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
09-13 00:05:43.992  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:05:43.992  1018  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-13 00:05:43.992  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:05:43.992  1018  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
09-13 00:05:43.992  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:05:43.992  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:43.992  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:43.992  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:43.992  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:05:44.002  7268  7268 E Zygote  : MountEmulatedStorage()
09-13 00:05:44.002  7268  7268 E Zygote  : v2
09-13 00:05:44.002  7268  7268 I libpersona: KNOX_SDCARD checking this for 10055
,09-13 00:05:44.002  7268  7268 I libpersona: KNOX_SDCARD not a persona
,09-13 00:05:44.012  1018  1504 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7268 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
09-13 00:05:44.012   279  1013 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-13 00:05:44.012   279  1013 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,09-13 00:05:44.012  1018  1130 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 00:05:44.012  1018  1130 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
09-13 00:05:44.012  7268  7268 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 00:05:44.012  1018  1130 V NetworkStats: updateIfacesLocked()
,09-13 00:05:44.012  1018  1130 D NetworkStatsFactory: UpdateStatsForKnox updated
09-13 00:05:44.012  1018  1130 V NetworkStats: performPollLocked(flags=0x1)
09-13 00:05:44.012  1018  1130 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-13 00:05:44.012  1018  1127 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-13 00:05:44.012  7268  7268 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 00:05:44.012  1018  1761 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
09-13 00:05:44.012  1018  1761 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,09-13 00:05:44.012  1018  1018 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-13 00:05:44.012  7268  7268 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-13 00:05:44.012  1018  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-13 00:05:44.012  1018  1130 V NetworkStats: performPollLocked() took 5ms
09-13 00:05:44.012  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-13 00:05:44.012  1018  1048 D WifiDisplayController: disconnect
09-13 00:05:44.012  1018  1048 D WifiDisplayController: updateConnection
09-13 00:05:44.012  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-13 00:05:44.012  1018  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-13 00:05:44.012  1018  1130 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 00:05:44.012  1018  1127 D WifiP2pService: P2pDisablingState
,09-13 00:05:44.012  1018  1127 D WifiP2pService: P2pDisablingState{ what=147458 }
09-13 00:05:44.022  1018  1127 D WifiP2pService: p2p socket connection lost
,09-13 00:05:44.022  1175  1175 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-13 00:05:44.022  1018  1128 E WifiNative-wlan0: do suspend true
09-13 00:05:44.022  1018  1127 D WifiP2pService: P2pDisabledState
,09-13 00:05:44.022  1018  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-13 00:05:44.022  1018  1048 D WifiDisplayAdapter: onP2pDisconnected
09-13 00:05:44.022  1018  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-13 00:05:44.022  1018  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-13 00:05:44.022  1018  1486 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-13 00:05:44.022  1175  1175 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
09-13 00:05:44.022  1018  1130 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,09-13 00:05:44.022  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 00:05:44.022  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 00:05:44.022  1018  1130 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 00:05:44.022  1018  1127 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-13 00:05:44.022  1175  1760 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-13 00:05:44.022  1018  1761 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:05:44.032  1018  1130 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
09-13 00:05:44.022  1460  1460 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-13 00:05:44.032  1018  1130 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
09-13 00:05:44.022  1460  1460 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 00:05:44.032  1018  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-13 00:05:44.032  1018  1047 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-13 00:05:44.032  1018  1130 D ConnectivityService: nai.networkMonitor.doQuit()
09-13 00:05:44.032  1018  1130 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-13 00:05:44.032  1018  1130 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-13 00:05:44.032  1018  1130 E ConnectivityService: updateNetworkInfo()
09-13 00:05:44.032  1018  1130 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 00:05:44.032  1018  1130 E ConnectivityService: updateNetworkInfo()
,09-13 00:05:44.032  1018  1018 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,09-13 00:05:44.032  1018  1132 D Tethering: MasterInitialState.processMessage what=3
09-13 00:05:44.032  1018  1047 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-13 00:05:44.032  1018  1125 V NetworkStats: updateIfacesLocked()
,09-13 00:05:44.032  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 00:05:44.032  1018  1125 V NetworkStats: performPollLocked(flags=0x1)
09-13 00:05:44.032  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
09-13 00:05:44.032  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-13 00:05:44.032  1175  1175 D StatusBar.NetworkController: EthernetConnected: false
09-13 00:05:44.042  1018  1126 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-13 00:05:44.032  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-13 00:05:44.032  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-13 00:05:44.032  1175  1175 D StatusBar.NetworkController: updateDataNetType()
09-13 00:05:44.042  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 00:05:44.042  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 00:05:44.042  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 00:05:44.042  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 00:05:44.042  1018  1125 V NetworkStats: performPollLocked() took 5ms
09-13 00:05:44.042  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 00:05:44.042  7268  7268 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 00:05:44.042  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-13 00:05:44.042  1175  1175 E StatusBar.NetworkController: updateLTEICONDataNetType:0
09-13 00:05:44.042  7268  7268 D ActivityThread: Added TimaKeyStore provider
,09-13 00:05:44.042  1175  1175 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-13 00:05:44.042  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 22 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
09-13 00:05:44.042  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
09-13 00:05:44.042  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,09-13 00:05:44.042  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 00:05:44.042  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 00:05:44.042  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-13 00:05:44.042  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-13 00:05:44.042  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-13 00:05:44.052  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:05:44.052  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:05:44.052  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:05:44.052  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 00:05:44.052  1018  1127 D WifiP2pService: P2pDisabledState{ what=143375 }
,09-13 00:05:44.052  1018  1127 D WifiP2pService: DefaultState{ what=143375 }
09-13 00:05:44.052   279  1017 D CommandListener: Clearing all IP addresses on wlan0
,09-13 00:05:44.062  1380  1380 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED,
,09-13 00:05:44.062  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-13 00:05:44.062  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-13 00:05:44.062  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-13 00:05:44.062  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-13 00:05:44.072  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 00:05:44.072  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 00:05:44.072  1018  1128 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-13 00:05:44.072  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:05:44.072  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 00:05:44.072  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-13 00:05:44.072  1018  1128 D SecContentProvider2: mCursor = null
,09-13 00:05:44.082  7268  7268 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
09-13 00:05:44.082  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-13 00:05:44.082  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-13 00:05:44.082  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-13 00:05:44.082  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 00:05:44.082  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:05:44.082  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:05:44.082  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 00:05:44.082  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-13 00:05:44.082  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-13 00:05:44.082  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-13 00:05:44.082  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:05:44.082  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:05:44.082  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:05:44.082  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:05:44.082  4836  4836 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
09-13 00:05:44.082  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-13 00:05:44.082  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
09-13 00:05:44.082  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-13 00:05:44.082  1175  1799 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-13 00:05:44.092  7018  7018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 00:05:44.092  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:05:44.092  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:05:44.092  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:05:44.092  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 00:05:44.092  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 00:05:44.092  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:05:44.092  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:05:44.092  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 00:05:44.092  1175  1175 D HotspotTile: onReceive : 0, 0
,09-13 00:05:44.092  7018  7018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 00:05:44.092  7018  7018 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 00:05:44.092  7018  7018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 00:05:44.092  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:05:44.092  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:05:44.092  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:05:44.092  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 00:05:44.092  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 00:05:44.092  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:05:44.092  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:05:44.092  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 00:05:44.092  7018  7018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 00:05:44.092  7018  7018 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 00:05:44.102  3263  3342 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-13 00:05:44.102  3263  3342 D BtConfig.SecureMode: isSecureModeOn:false
09-13 00:05:44.102  3263  3342 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-13 00:05:44.102  3263  3342 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
09-13 00:05:44.102  3263  3342 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
09-13 00:05:44.102  3263  3342 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
09-13 00:05:44.102  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-13 00:05:44.102  3263  3342 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-13 00:05:44.102  1018  1810 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-13 00:05:44.102  1018  1810 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
09-13 00:05:44.112  1018  1810 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:44.112  1018  1810 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:44.112  1018  1810 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 00:05:44.112  3263  3342 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
09-13 00:05:44.112  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-13 00:05:44.112  3263  3263 D HeadsetService: Received stop request...Stopping profile...
09-13 00:05:44.112  3263  3342 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
09-13 00:05:44.112  3263  3263 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4aba78f
,09-13 00:05:44.112  1018  1489 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-13 00:05:44.112  1018  1018 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-13 00:05:44.112  4836  4836 D HeadsetProfile: Bluetooth service disconnected
09-13 00:05:44.112  1018  1489 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-13 00:05:44.112  1018  1489 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:44.112  1018  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:44.112  1018  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-13 00:05:44.112  7268  7268 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
09-13 00:05:44.112  3263  3342 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
09-13 00:05:44.112  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-13 00:05:44.112  7268  7268 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-13 00:05:44.112  7268  7268 D UserAnalysis: Create SecureDbHelper
09-13 00:05:44.112  3263  3342 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
09-13 00:05:44.122  1018  1223 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-13 00:05:44.122  1018  1223 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-13 00:05:44.122  1018  1223 W ActivityManager: userId = 0, bbcId = -10000
,09-13 00:05:44.122  1018  1223 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:44.122  1018  1223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 00:05:44.122  3263  3342 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
09-13 00:05:44.122  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-13 00:05:44.122  3263  3342 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
09-13 00:05:44.122  1018  1486 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-13 00:05:44.122  1018  1486 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-13 00:05:44.122  1018  1486 W ActivityManager: userId = 0, bbcId = -10000
,09-13 00:05:44.122  1018  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:44.122  1018  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 00:05:44.122  3263  3342 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,09-13 00:05:44.122  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-13 00:05:44.122  3263  3342 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService,
,09-13 00:05:44.122  1018  1489 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-13 00:05:44.132  1018  1489 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-13 00:05:44.132  1018  1489 W ActivityManager: userId = 0, bbcId = -10000
,09-13 00:05:44.132  1018  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:44.132  1018  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 00:05:44.132  3263  3342 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
09-13 00:05:44.132  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-13 00:05:44.132  7268  7268 D IntelligenceServiceApplication: onCreate()
09-13 00:05:44.132  3263  3342 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-13 00:05:44.132  1018  1079 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-13 00:05:44.132  1018  1079 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-13 00:05:44.132  1018  1079 W ActivityManager: userId = 0, bbcId = -10000
,09-13 00:05:44.132  1018  1079 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:44.132  1018  1079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 00:05:44.142  3263  3342 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
,09-13 00:05:44.142  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-13 00:05:44.142  3263  3342 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
09-13 00:05:44.142  7268  7268 D IntelligenceServiceApplication: no applications having user consent for prediction
,09-13 00:05:44.142  1018  1030 I ActivityManager: Killing 6334:com.samsung.android.sm/1000 (adj 15): empty #21
,09-13 00:05:44.152  1018  1331 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-13 00:05:44.152  1018  1331 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-13 00:05:44.162  1380  1380 I wpa_supplicant: Blacklist: Clear (all) 
09-13 00:05:44.162  1018  1331 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:44.162  1018  1331 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:44.162  1018  1331 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 00:05:44.162  3263  3342 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-13 00:05:44.162  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-13 00:05:44.162  3263  3342 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-13 00:05:44.162  3263  3342 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-13 00:05:44.162  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-13 00:05:44.162  3263  3342 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-13 00:05:44.162  3263  3342 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
09-13 00:05:44.162  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-13 00:05:44.162  3263  3342 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-13 00:05:44.162  3263  3342 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
09-13 00:05:44.162  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-13 00:05:44.162  3263  3342 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-13 00:05:44.162  3263  3342 D BluetoothAdapterState: Stopping profile services that were post enabled
,09-13 00:05:44.162  3263  3263 E BluetoothAdapterService(78358415): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-13 00:05:44.162  3263  3263 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-13 00:05:44.162  3263  3263 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-13 00:05:44.162  1018  4258 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-13 00:05:44.172  3263  3263 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-13 00:05:44.172  3263  3263 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-13 00:05:44.172  3263  3263 D A2dpService: Received stop request...Stopping profile...
09-13 00:05:44.172  7268  7268 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,09-13 00:05:44.172  3263  3406 D A2dpStateMachine: Exit Disconnected: -1
,09-13 00:05:44.172  3263  3263 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4aba78f
,09-13 00:05:44.182  1018  1018 D BluetoothA2dp: Proxy object disconnected
,09-13 00:05:44.182  3263  3263 D HidService: Received stop request...Stopping profile...
,09-13 00:05:44.182  3263  3263 D HidService: Stopping Bluetooth HidService
,09-13 00:05:44.182  3263  3263 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-13 00:05:44.182  3263  3263 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-13 00:05:44.182  3263  3263 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-13 00:05:44.182  3263  3263 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4aba78f
,09-13 00:05:44.182  1018  1018 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,09-13 00:05:44.182  3263  3263 D HealthService: Received stop request...Stopping profile...
09-13 00:05:44.182  3263  3263 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4aba78f
,09-13 00:05:44.182  3263  3263 D PanService: Received stop request...Stopping profile...
09-13 00:05:44.182  3263  3263 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4aba78f
,09-13 00:05:44.182  1018  1018 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-13 00:05:44.182  3263  3263 D BluetoothMapService: Received stop request...Stopping profile...
,09-13 00:05:44.192  4836  4836 D BluetoothA2dp: Proxy object disconnected
,09-13 00:05:44.192  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-13 00:05:44.192  3263  3263 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4aba78f
09-13 00:05:44.192  4836  4836 D A2dpProfile: Bluetooth service disconnected
,09-13 00:05:44.192  4836  4836 D BluetoothInputDevice: Proxy object disconnected
09-13 00:05:44.192  4836  4836 D HidProfile: Bluetooth service disconnected
09-13 00:05:44.192  4836  4836 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-13 00:05:44.192  4836  4836 D PanProfile: Bluetooth service disconnected
09-13 00:05:44.192  4836  4836 D BluetoothMap: Proxy object disconnected
09-13 00:05:44.192  4836  4836 D MapProfile: Bluetooth service disconnected
09-13 00:05:44.192  1380  1380 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-13 00:05:44.192  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
09-13 00:05:44.192  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
09-13 00:05:44.192  3263  3263 D SapService: Received stop request...Stopping profile...
09-13 00:05:44.192  3263  3263 D SapService: Stopping Bluetooth SapService
09-13 00:05:44.192  3263  3263 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4aba78f
,09-13 00:05:44.192  1018  1079 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,09-13 00:05:44.192  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-13 00:05:44.192  7268  7268 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-13 00:05:44.192  1018  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:44.192  1018  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:44.192  1018  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:44.192  1018  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:05:44.192  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-13 00:05:44.192  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-13 00:05:44.202   323   323 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 00:05:44.202  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-13 00:05:44.202  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-13 00:05:44.212  7287  7287 E Zygote  : MountEmulatedStorage()
09-13 00:05:44.212  7287  7287 E Zygote  : v2
09-13 00:05:44.212  7287  7287 I libpersona: KNOX_SDCARD checking this for 10105
09-13 00:05:44.212  7287  7287 I libpersona: KNOX_SDCARD not a persona
09-13 00:05:44.212  7287  7287 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 00:05:44.212  1018  1079 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7287 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,09-13 00:05:44.212  3263  3263 E BluetoothAdapterService(78358415): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true,
09-13 00:05:44.212  3263  3263 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-13 00:05:44.212  7287  7287 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 00:05:44.212  3263  3263 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-13 00:05:44.212  7287  7287 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-13 00:05:44.212  3263  3407 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-13 00:05:44.212  3263  3263 I GKI_LINUX: GKI_exit_task 2 done
09-13 00:05:44.212  3263  3263 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,09-13 00:05:44.212  3263  3263 D BluetoothA2dp: Proxy object disconnected
09-13 00:05:44.212  3263  3263 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
09-13 00:05:44.212  3263  3263 E BluetoothAdapterService(78358415): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-13 00:05:44.212  3263  3263 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-13 00:05:44.212  3263  3263 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-13 00:05:44.212  3263  3263 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-13 00:05:44.212  3263  3263 E BluetoothAdapterService(78358415): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
,09-13 00:05:44.212  3263  3263 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-13 00:05:44.212  3263  3263 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-13 00:05:44.212  3263  3263 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService,
09-13 00:05:44.212  3263  3263 E BluetoothAdapterService(78358415): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-13 00:05:44.212  3263  3263 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. ,
09-13 00:05:44.212  3263  3263 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-13 00:05:44.222  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-13 00:05:44.212  3263  3263 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-13 00:05:44.212  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-13 00:05:44.212  3263  3263 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-13 00:05:44.212  3263  3263 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object,
09-13 00:05:44.212  3263  3263 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-13 00:05:44.212  3263  3263 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-13 00:05:44.212  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-13 00:05:44.212  4836  4836 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-13 00:05:44.212  4836  4836 D SapProfile: Bluetooth service disconnected
09-13 00:05:44.222  1380  1380 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
09-13 00:05:44.222  1380  1380 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-13 00:05:44.222  1380  1380 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-13 00:05:44.222  1380  1380 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-13 00:05:44.222  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-13 00:05:44.222  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-13 00:05:44.222  1380  1380 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
09-13 00:05:44.222  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,09-13 00:05:44.222  1018  1132 D Tethering: InitialState.processMessage what=4
09-13 00:05:44.222  3263  3263 E BluetoothAdapterService(78358415): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
09-13 00:05:44.222  3263  3263 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-13 00:05:44.222  3263  3263 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-13 00:05:44.222  3263  3263 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
09-13 00:05:44.222  3263  3263 E BluetoothAdapterService(78358415): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-13 00:05:44.222  3263  3263 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-13 00:05:44.222  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-13 00:05:44.222  3263  3263 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##,
09-13 00:05:44.222  3263  3263 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##,
09-13 00:05:44.222  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-13 00:05:44.222  1018  1132 E Tethering: No numeric data
09-13 00:05:44.222  1018  1125 V NetworkStats: performPollLocked(flags=0x1)
09-13 00:05:44.222  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-13 00:05:44.222  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,09-13 00:05:44.222  1018  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-13 00:05:44.222  1018  1132 D Tethering: clearTetheredNotification()
09-13 00:05:44.222  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-13 00:05:44.222  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-13 00:05:44.222  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,09-13 00:05:44.222  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 00:05:44.222  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-13 00:05:44.222  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
09-13 00:05:44.222  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-13 00:05:44.232  1018  1125 V NetworkStats: performPollLocked() took 4ms
09-13 00:05:44.232  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 00:05:44.232  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-13 00:05:44.232  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-13 00:05:44.232  1175  1175 D HotspotTile: updateTetherState():false, false
09-13 00:05:44.232  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 00:05:44.232  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 00:05:44.232  3263  3342 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
09-13 00:05:44.232  3263  3342 D BluetoothAdapterProperties: Setting state to 10
09-13 00:05:44.232  3263  3342 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-13 00:05:44.232  3263  3342 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-13 00:05:44.232  3263  3342 D BluetoothAdapterService: updateAdapterState state is 10
,09-13 00:05:44.232  3263  3342 D BluetoothAdapterService: Autoconnection is available 
09-13 00:05:44.232  3263  3342 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-13 00:05:44.232  3263  3279 D BluetoothAdapter: onBluetoothStateChange: up=false
09-13 00:05:44.232  3263  3279 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-13 00:05:44.232  3263  3342 I BluetoothAdapterState: Entering OffState
,09-13 00:05:44.232  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-13 00:05:44.232  1695  1713 D BluetoothAdapter: onBluetoothStateChange: up=false
09-13 00:05:44.232  1695  1713 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-13 00:05:44.232  4836  4848 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-13 00:05:44.232  1175  1192 D BluetoothAdapter: onBluetoothStateChange: up=false
09-13 00:05:44.232  1175  1192 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-13 00:05:44.232  1460  2580 D BluetoothAdapter: onBluetoothStateChange: up=false
09-13 00:05:44.232  1460  2580 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-13 00:05:44.232  4836  4846 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-13 00:05:44.232  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-13 00:05:44.242  4836  4848 D BluetoothPbap: onBluetoothStateChange: up=false
,09-13 00:05:44.242  1018  1047 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 00:05:44.242  4836  4846 D BluetoothAdapter: onBluetoothStateChange: up=false
09-13 00:05:44.242  4836  4846 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-13 00:05:44.242  1018  1047 D BluetoothAdapter: onBluetoothStateChange: up=false
09-13 00:05:44.242  1018  1047 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-13 00:05:44.242  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-13 00:05:44.242  4836  4848 D Bluetoothsap: onBluetoothStateChange: up=false
09-13 00:05:44.242  4836  4848 D Bluetoothsap: Unbinding service...
09-13 00:05:44.242  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-13 00:05:44.242  7287  7287 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 00:05:44.242  1768  1781 D BluetoothAdapter: onBluetoothStateChange: up=false
09-13 00:05:44.242  1768  1781 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-13 00:05:44.242  7018  7032 D BluetoothAdapter: onBluetoothStateChange: up=false
09-13 00:05:44.242  7018  7032 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-13 00:05:44.242  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-13 00:05:44.242  7018  7032 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-13 00:05:44.242  7018  7032 D BluetoothLeAdvertiser: Exit stop advertising
09-13 00:05:44.242  7018  7032 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-13 00:05:44.242  7018  7032 D BluetoothLeScanner: Exiting stopAllScan
09-13 00:05:44.242  7287  7287 D ActivityThread: Added TimaKeyStore provider
09-13 00:05:44.242  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-13 00:05:44.242  4836  4846 D BluetoothMap: onBluetoothStateChange: up=false
09-13 00:05:44.242  1429  1439 D BluetoothAdapter: onBluetoothStateChange: up=false
09-13 00:05:44.242  1429  1439 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-13 00:05:44.242  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-13 00:05:44.242  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-13 00:05:44.242  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-13 00:05:44.252  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-13 00:05:44.252  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-13 00:05:44.252  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-13 00:05:44.252  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-13 00:05:44.252  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-13 00:05:44.252  1447  7053 D BluetoothAdapter: onBluetoothStateChange: up=false
09-13 00:05:44.252  1447  7053 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-13 00:05:44.252  3263  3398 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 00:05:44.252  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-13 00:05:44.252  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-13 00:05:44.252  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-13 00:05:44.252  1018  1018 I InputMethodManagerService: [BT Setting State] State =10
09-13 00:05:44.252  1018  1018 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-13 00:05:44.262  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-13 00:05:44.262  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-13 00:05:44.262  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-13 00:05:44.262  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-13 00:05:44.262  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:05:44.262  1175  1175 D BluetoothTile:  getBluetoothState : 10
,09-13 00:05:44.272  1886  1886 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-13 00:05:44.272  1018  1487 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-13 00:05:44.272  4836  4836 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-13 00:05:44.272  1018  1810 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-13 00:05:44.272  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-13 00:05:44.272  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:05:44.272  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:05:44.292  7018  7018 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 00:05:44.352   258   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-13 00:05:44.352   258   518 W Vold    : Returning OperationFailed - no handler for errno 0
,09-13 00:05:44.352  7287  7318 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-13 00:05:44.352   258   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-13 00:05:44.352   258   518 W Vold    : Returning OperationFailed - no handler for errno 0
,09-13 00:05:44.352  7287  7318 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-13 00:05:44.382  1380  1380 I wpa_supplicant: Blacklist: Clear (all) 
,09-13 00:05:44.442  1380  1380 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-13 00:05:44.442  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-13 00:05:44.442  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
09-13 00:05:44.442  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-13 00:05:44.452  1018  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,09-13 00:05:44.452  1018  1128 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-13 00:05:44.462  4836  4836 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-13 00:05:44.462  1768  2204 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 00:05:44.462  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-13 00:05:44.462  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:05:44.462  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-13 00:05:44.462  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-13 00:05:44.462  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:05:44.462  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:05:44.462  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:05:44.462  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:05:44.462  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-13 00:05:44.462  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
09-13 00:05:44.462  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-13 00:05:44.462  1175  1799 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-13 00:05:44.472  1175  1175 D HotspotTile: onReceive : 1, 0
,09-13 00:05:44.472  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:05:44.532  1018  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 00:05:44.532  1018  1018 I ApplicationPolicy: updateDataUsageMap
,09-13 00:05:44.542  1018  1042 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-13 00:05:44.552  7287  7287 D StrictMode: StrictMode policy violation; ~duration=180 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at java.io.File.exists(File.java:363)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-13 00:05:44.552  7287  7287 D StrictMode: StrictMode policy violation; ~duration=179 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-13 00:05:44.552  7287  7287 D StrictMode: StrictMode policy violation; ~duration=178 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-13 00:05:44.552  7287  7287 D StrictMode: StrictMode policy violation; ~duration=177 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.q.k.a(PG:2107)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.q.e.b(PG:170)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-13 00:05:44.552  7287  7287 D StrictMode: StrictMode policy violation; ~duration=174 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.q.k.c(PG:18147)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.q.k.d(PG:583)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.q.e.b(PG:170)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-13 00:05:44.552  7287  7287 D StrictMode: StrictMode policy violation; ~duration=147 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at java.io.File.exists(File.java:363)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-13 00:05:44.552  7287  7287 D StrictMode: StrictMode policy violation; ~duration=147 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at java.io.File.exists(File.java:363)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-13 00:05:44.552  7287  7287 D StrictMode: StrictMode policy violation; ~duration=146 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at java.io.File.lastModified(File.java:571)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 00:05:44.552  7287  7287 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-13 00:05:44.552  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:05:44.552  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:05:44.552  1018  1810 I ActivityManager: Killing 6805:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
09-13 00:05:44.572  1018  1505 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-13 00:05:44.572  1018  1505 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-13 00:05:44.572  1018  1505 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:44.572  1018  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:44.572  1018  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-13 00:05:44.572  1635  1635 I Hs20UtilService: Starting #8
09-13 00:05:44.572  1635  1663 I Hs20UtilService: Message received 5007
09-13 00:05:44.572  4836  4836 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-13 00:05:44.572  4836  4836 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-13 00:05:44.582  4836  4836 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-13 00:05:44.582  4836  4836 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-13 00:05:44.582  4836  4836 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-13 00:05:44.582  4836  4836 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-13 00:05:44.582  4836  4878 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-13 00:05:44.592  4836  4836 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-13 00:05:44.592  4836  4836 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-13 00:05:44.592  4836  4836 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-13 00:05:44.602  4836  4836 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-13 00:05:44.602  4836  4836 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-13 00:05:44.602  4836  4836 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-13 00:05:44.602  4836  4878 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-13 00:05:44.602  1018  1079 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
09-13 00:05:44.602  1018  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:44.602  1018  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:44.602  1018  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:44.612  1018  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:44.622  7287  7323 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
09-13 00:05:44.622  7329  7329 E Zygote  : MountEmulatedStorage()
09-13 00:05:44.622  1018  1079 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7329 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-13 00:05:44.622  7329  7329 E Zygote  : v2
09-13 00:05:44.622  7329  7329 I libpersona: KNOX_SDCARD checking this for 10064
,09-13 00:05:44.632  7329  7329 I libpersona: KNOX_SDCARD not a persona
09-13 00:05:44.632  7329  7329 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 00:05:44.632  7329  7329 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 00:05:44.632  7329  7329 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 00:05:44.642  7329  7329 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 00:05:44.652  7329  7329 D ActivityThread: Added TimaKeyStore provider
,09-13 00:05:44.662  1018  1223 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 00:05:44.662  1018  1223 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:44.662  1018  1223 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 00:05:44.662  1018  1223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-13 00:05:44.672  7329  7329 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-13 00:05:44.692  7329  7329 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-13 00:05:44.692  7329  7329 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-13 00:05:44.722  7329  7329 D FileShare-Client: Outbound.stopDelayTimer - 
,09-13 00:05:44.722  1018  1486 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,09-13 00:05:44.722  1018  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:05:44.722  1018  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:44.722  1018  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:44.722  1018  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:05:44.742  7346  7346 E Zygote  : MountEmulatedStorage()
,09-13 00:05:44.742  7346  7346 E Zygote  : v2
09-13 00:05:44.742  7346  7346 I libpersona: KNOX_SDCARD checking this for 10065
09-13 00:05:44.742  7346  7346 I libpersona: KNOX_SDCARD not a persona
,09-13 00:05:44.742  7346  7346 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 00:05:44.742  1018  1486 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7346 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-13 00:05:44.742  1018  1486 I ActivityManager: Killing 6843:com.google.android.apps.docs/u0a87 (adj 15): empty #21
,09-13 00:05:44.742  7346  7346 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 00:05:44.742  7346  7346 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 00:05:44.762  7346  7346 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 00:05:44.762  7346  7346 D ActivityThread: Added TimaKeyStore provider
,09-13 00:05:44.782  7346  7346 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-13 00:05:44.792  1018  1505 W ActivityManager: userId = 0, bbcId = -10000
,09-13 00:05:44.792  1018  1505 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 00:05:44.792  1018  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
09-13 00:05:44.792  1018  1505 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,09-13 00:05:44.792  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:05:44.792  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:44.792  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:44.792  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:05:44.812  7362  7362 E Zygote  : MountEmulatedStorage()
09-13 00:05:44.812  7362  7362 E Zygote  : v2
09-13 00:05:44.812  7362  7362 I libpersona: KNOX_SDCARD checking this for 10102
09-13 00:05:44.812  7362  7362 I libpersona: KNOX_SDCARD not a persona
,09-13 00:05:44.812  7362  7362 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 00:05:44.812  1018  1505 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7362 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-13 00:05:44.812  1018  1505 I ActivityManager: Killing 6821:com.google.android.partnersetup/u0a14 (adj 15): empty #21
09-13 00:05:44.812  7362  7362 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 00:05:44.812  7362  7362 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-13 00:05:44.832  7362  7362 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 00:05:44.832  7362  7362 D ActivityThread: Added TimaKeyStore provider
,09-13 00:05:44.852  7362  7362 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-13 00:05:45.022  1018  1045 D Tethering: interfaceRemoved wlan0
,09-13 00:05:45.022  1018  1045 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-13 00:05:45.042  7362  7382 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
09-13 00:05:45.042  7362  7382 I Babel_SMS: MmsConfig.loadMmsSettings
09-13 00:05:45.042  7362  7382 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
09-13 00:05:45.042  7362  7382 I Babel_SMS: MmsConfig.loadFromDatabase
,09-13 00:05:45.092  7362  7382 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,09-13 00:05:45.092  7362  7382 I Babel_SMS: MmsConfig.loadFromResources
,09-13 00:05:45.092  7362  7382 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,09-13 00:05:45.092  7362  7382 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,09-13 00:05:45.102  1018  1223 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 00:05:45.112  1018  1223 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4256, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-13 00:05:45.112  1018  1223 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-13 00:05:45.112  1018  1223 D BatteryService: stay LED for charging
09-13 00:05:45.112  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 00:05:45.112  1018  1018 I MotionRecognitionService: Plugged
09-13 00:05:45.112  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,09-13 00:05:45.112  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 00:05:45.112  1175  1175 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 00:05:45.112  1414  1414 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-13 00:05:45.112  1414  1414 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-13 00:05:45.122  1018  1504 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null,
09-13 00:05:45.122  1018  1504 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,09-13 00:05:45.122  1018  1504 W ActivityManager: userId = 0, bbcId = -10000,
09-13 00:05:45.122  1018  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 00:05:45.122  1018  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-13 00:05:45.142  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 00:05:45.142  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-13 00:05:45.142  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 00:05:45.142  7362  7362 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 00:05:45.142  7362  7362 I Babel_Crash: startup - clean
,09-13 00:05:45.152  1018  1045 D Tethering: interfaceRemoved p2p0
09-13 00:05:45.152  1018  1045 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-13 00:05:45.172  1018  1810 W ActivityManager: userId = 0, bbcId = -10000
,09-13 00:05:45.172  1018  1810 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:45.172  1018  1810 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-13 00:05:45.172   292   292 E SMD     : DCD OFF
,09-13 00:05:45.182  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,09-13 00:05:45.182  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:45.182  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-13 00:05:45.182  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,09-13 00:05:45.182  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:45.182  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-13 00:05:45.192  1018  1504 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-13 00:05:45.192  1018  1504 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-13 00:05:45.192  1018  1504 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:45.192  1018  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:45.192  1018  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-13 00:05:45.192  1635  1635 I Hs20UtilService: Starting #9
,09-13 00:05:45.192  1635  1663 I Hs20UtilService: Message received 5007
09-13 00:05:45.192  7362  7362 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-13 00:05:45.192  4836  4836 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-13 00:05:45.192  4836  4836 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-13 00:05:45.192  7362  7362 W AudioCapabilities: Unsupported mime audio/evrc
09-13 00:05:45.202  4836  4836 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-13 00:05:45.202  7362  7362 W AudioCapabilities: Unsupported mime audio/qcelp
,09-13 00:05:45.202   323   323 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 00:05:45.202  4836  4836 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-13 00:05:45.202  4836  4836 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-13 00:05:45.202  4836  4836 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-13 00:05:45.202  4836  4878 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-13 00:05:45.212  7362  7362 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,09-13 00:05:45.212  7362  7362 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,09-13 00:05:45.212  1018  1223 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-13 00:05:45.212  1018  1223 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-13 00:05:45.212  1018  1223 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:45.212  1018  1223 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-13 00:05:45.212  1018  1223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-13 00:05:45.212  1635  1635 I Hs20UtilService: Starting #10
,09-13 00:05:45.212  1635  1663 I Hs20UtilService: Message received 5011
09-13 00:05:45.212  1018  1489 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,09-13 00:05:45.212  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:05:45.212  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:45.212  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:45.212  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:05:45.212  7362  7362 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,09-13 00:05:45.222  7362  7362 W AudioCapabilities: Unsupported mime audio/x-ima
,09-13 00:05:45.222  7362  7362 W AudioCapabilities: Unsupported mime audio/qcelp
09-13 00:05:45.222  7362  7362 W AudioCapabilities: Unsupported mime audio/evrc
,09-13 00:05:45.222  7385  7385 E Zygote  : MountEmulatedStorage(),
09-13 00:05:45.222  7385  7385 I libpersona: KNOX_SDCARD checking this for 1000
09-13 00:05:45.222  7385  7385 E Zygote  : v2
09-13 00:05:45.222  7385  7385 I libpersona: KNOX_SDCARD not a persona
09-13 00:05:45.222  7385  7385 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 00:05:45.232  7385  7385 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 00:05:45.232  7385  7385 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-13 00:05:45.232  1018  1489 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=7385 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-13 00:05:45.242  7362  7362 W VideoCapabilities: Unsupported mime video/wvc1
,09-13 00:05:45.242  7362  7362 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-13 00:05:45.252  7362  7362 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,09-13 00:05:45.252  7385  7385 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 00:05:45.252  7362  7362 W VideoCapabilities: Unsupported mime video/wvc1
,09-13 00:05:45.252  7385  7385 D ActivityThread: Added TimaKeyStore provider
09-13 00:05:45.252  7362  7362 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-13 00:05:45.262  7362  7362 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,09-13 00:05:45.262  7362  7362 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,09-13 00:05:45.262  7362  7362 W VideoCapabilities: Unsupported mime video/mp43
,09-13 00:05:45.262  7362  7362 W VideoCapabilities: Unsupported mime video/sorenson
,09-13 00:05:45.282  7385  7385 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-13 00:05:45.282  7385  7385 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-13 00:05:45.282  7385  7385 D SecurityLogAgent: StateMachine : Current State = 1
,09-13 00:05:45.292  7385  7385 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-13 00:05:45.292  1018  1486 I ActivityManager: Killing 6862:com.sec.pcw.device/1000 (adj 15): empty #21
,09-13 00:05:45.292  7362  7362 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-13 00:05:45.302  1018  1487 W ActivityManager: userId = 0, bbcId = -10000
,09-13 00:05:45.302  1018  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:45.302  1018  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-13 00:05:45.302  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,09-13 00:05:45.302  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:45.302  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-13 00:05:45.302  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,09-13 00:05:45.302  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:45.302  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-13 00:05:45.312  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,09-13 00:05:45.312  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:45.312  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-13 00:05:45.312  7362  7362 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-13 00:05:45.312  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:45.312  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:45.312  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-13 00:05:45.322  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,09-13 00:05:45.322  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:45.322  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-13 00:05:45.322  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:45.322  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:45.322  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-13 00:05:45.322  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:45.322  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:45.322  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-13 00:05:45.332  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:45.332  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:45.332  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-13 00:05:45.332  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:45.332  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:45.332  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-13 00:05:45.332  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:45.332  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:45.332  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-13 00:05:45.332  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:45.332  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:45.332  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-13 00:05:45.342  4836  4836 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 00:05:45.342  1018  4259 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-13 00:05:45.342  1018  4259 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-13 00:05:45.342  1018  4259 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:45.342  1018  4259 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:45.342  1018  4259 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-13 00:05:45.342  7362  7362 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-13 00:05:45.352  1695  1695 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 00:05:45.352  7362  7362 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-13 00:05:45.352  7362  7362 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-13 00:05:45.352  4836  4836 D DockEventReceiver: finishStartingService: stopping service
,09-13 00:05:45.352  4836  4836 D BluetoothNotiBroadcastReceiver: onReceive
,09-13 00:05:45.352  7362  7362 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-13 00:05:45.362  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-13 00:05:45.362  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-13 00:05:45.362  1018  4259 I ActivityManager: Killing 6780:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,09-13 00:05:45.362  7362  7362 I vclib   : onServiceConnected
,09-13 00:05:45.382  1018  1079 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-13 00:05:45.382  1018  1079 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-13 00:05:45.382  1018  1079 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:45.382  1018  1079 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:45.382  1018  1079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-13 00:05:45.392  1635  1635 I Hs20UtilService: Starting #11
,09-13 00:05:45.392  1635  1663 I Hs20UtilService: Message received 5011
,09-13 00:05:45.392  7385  7385 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-13 00:05:45.392  7385  7385 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-13 00:05:45.392  7385  7385 D SecurityLogAgent: StateMachine : Current State = 1
09-13 00:05:45.392  7385  7385 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-13 00:05:45.402  1018  1505 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-13 00:05:45.402  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:45.402  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:45.402  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:45.402  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:05:45.412  7404  7404 E Zygote  : MountEmulatedStorage()
09-13 00:05:45.412  7404  7404 E Zygote  : v2
09-13 00:05:45.412  7404  7404 I libpersona: KNOX_SDCARD checking this for 1000
09-13 00:05:45.412  7404  7404 I libpersona: KNOX_SDCARD not a persona
09-13 00:05:45.412  7404  7404 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 00:05:45.412  7404  7404 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 00:05:45.412  1018  1505 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7404 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-13 00:05:45.422  7404  7404 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-13 00:05:45.432  7404  7404 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 00:05:45.432  7404  7404 D ActivityThread: Added TimaKeyStore provider
,09-13 00:05:45.442   308   308 I art     : Explicit concurrent mark sweep GC freed 8721(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 589us total 26.058ms
,09-13 00:05:45.452  7404  7404 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
09-13 00:05:45.452  7404  7404 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
09-13 00:05:45.452  7404  7404 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-13 00:05:45.452   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 632us total 16.816ms
,09-13 00:05:45.472  7404  7404 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-13 00:05:45.472  7404  7404 I PCWCLIENTTRACE_PushUtil: sales region : global
09-13 00:05:45.472  7404  7404 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,09-13 00:05:45.472  7404  7404 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-13 00:05:45.472  1018  1504 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
09-13 00:05:45.472  1018  1504 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
09-13 00:05:45.472  1018  1504 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
09-13 00:05:45.472  1018  1504 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,09-13 00:05:45.472  1018  1504 I ActivityManager: Killing 6965:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
09-13 00:05:45.472   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 573us total 16.370ms
,09-13 00:05:45.472  7404  7419 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,09-13 00:05:45.482  1018  1018 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,09-13 00:05:45.482  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:45.482  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:45.482  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:45.482  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:05:45.492  7421  7421 E Zygote  : MountEmulatedStorage(),
09-13 00:05:45.492  7421  7421 E Zygote  : v2
09-13 00:05:45.492  7421  7421 I libpersona: KNOX_SDCARD checking this for 10001
09-13 00:05:45.492  7421  7421 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 00:05:45.492  7421  7421 I libpersona: KNOX_SDCARD not a persona
09-13 00:05:45.492  1018  1018 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7421 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-13 00:05:45.502  7421  7421 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 00:05:45.502  7421  7421 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 00:05:45.512  7421  7421 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 00:05:45.512  7421  7421 D ActivityThread: Added TimaKeyStore provider
,09-13 00:05:45.592  1018  4258 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,09-13 00:05:45.592  1018  4258 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:05:45.592  1018  4258 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:45.592  1018  4258 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:05:45.592  1018  4258 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:05:45.612  7438  7438 E Zygote  : MountEmulatedStorage(),
,09-13 00:05:45.612  7438  7438 E Zygote  : v2
,09-13 00:05:45.612  7438  7438 I libpersona: KNOX_SDCARD checking this for 1000
09-13 00:05:45.612  7438  7438 I libpersona: KNOX_SDCARD not a persona
,09-13 00:05:45.612  1018  4258 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7438 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-13 00:05:45.612  1018  4258 I ActivityManager: Killing 6999:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
,09-13 00:05:45.622  7438  7438 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 00:05:45.622  7438  7438 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 00:05:45.622  7438  7438 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 00:05:45.642  7438  7438 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 00:05:45.642  7438  7438 D ActivityThread: Added TimaKeyStore provider
,09-13 00:05:45.672  7438  7438 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,09-13 00:05:45.752  1018  1097 V AlarmManager: waitForAlarm result :4
,09-13 00:05:45.802  7438  7438 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,09-13 00:05:45.812  7438  7438 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,09-13 00:05:45.812  7438  7438 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,09-13 00:05:45.812  7438  7438 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-13 00:05:45.812  7438  7438 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,09-13 00:05:45.812  7438  7438 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-13 00:05:45.812  1018  4259 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,09-13 00:05:45.812  1018  4259 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:05:45.812  1018  4259 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:45.822  1018  4259 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:05:45.822  1018  4259 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:05:45.832  7453  7453 E Zygote  : MountEmulatedStorage()
,09-13 00:05:45.832  7453  7453 E Zygote  : v2
09-13 00:05:45.842  1018  4259 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7453 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-13 00:05:45.842  1018  4259 I ActivityManager: Killing 7034:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
09-13 00:05:45.842  7453  7453 I libpersona: KNOX_SDCARD checking this for 10008
09-13 00:05:45.842  7453  7453 I libpersona: KNOX_SDCARD not a persona
09-13 00:05:45.842  7453  7453 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 00:05:45.852  7453  7453 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 00:05:45.852  7453  7453 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-13 00:05:45.862  1018  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-13 00:05:45.872  7453  7453 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 00:05:45.872  7453  7453 D ActivityThread: Added TimaKeyStore provider
,09-13 00:05:45.942  1018  1810 I ActivityManager: Killing 7057:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,09-13 00:05:45.952  1018  1810 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
09-13 00:05:45.952  1018  1810 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-13 00:05:45.952  1018  1810 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:45.952  1018  1810 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 00:05:45.952  1018  1810 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,09-13 00:05:45.962  1925  1925 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-13 00:05:45.972  1925  2808 I iu.UploadsManager: num queued entries: 0
,09-13 00:05:45.972  1925  2808 I iu.UploadsManager: num updated entries: 0
,09-13 00:05:45.972  1925  2808 I iu.SyncManager: NEXT; no task
,09-13 00:05:45.972  1018  1031 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 00:05:45.972  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,09-13 00:05:45.972  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,09-13 00:05:45.972  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 00:05:45.972  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 00:05:45.982  1925  1925 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-13 00:05:45.982  1925  1925 I Kids    : [GCoreUtils] Current gmscore version, 8115234 is smaller than the required version 8400000
,09-13 00:05:45.992  2812  2812 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Sep 13 00:05:45 GMT+02:00 2016
,09-13 00:05:45.992  1018  1472 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-13 00:05:45.992  1018  1472 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-13 00:05:45.992  1018  1472 W ActivityManager: userId = 0, bbcId = -10000
,09-13 00:05:45.992  1018  1472 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:45.992  1018  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-13 00:05:46.002  2812  2812 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-13 00:05:46.002  1018  4258 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,09-13 00:05:46.002  1018  4258 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:05:46.002  1018  4258 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:46.002  1018  4258 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:05:46.012  1018  4258 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:05:46.012  2812  2812 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,09-13 00:05:46.012  2812  2812 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
09-13 00:05:46.022  7470  7470 I libpersona: KNOX_SDCARD checking this for 10031
09-13 00:05:46.012  2812  2812 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
09-13 00:05:46.022  7470  7470 I libpersona: KNOX_SDCARD not a persona
09-13 00:05:46.022  7470  7470 E Zygote  : MountEmulatedStorage()
09-13 00:05:46.022  7470  7470 E Zygote  : v2
09-13 00:05:46.022  7470  7470 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 00:05:46.022  7470  7470 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 00:05:46.022  1018  4258 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7470 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,09-13 00:05:46.022  2812  7469 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-13 00:05:46.022  2812  7469 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
09-13 00:05:46.022  7470  7470 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 00:05:46.032  2812  7469 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,09-13 00:05:46.042  2812  7469 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,09-13 00:05:46.042  7470  7470 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 00:05:46.042  2812  2812 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-13 00:05:46.042  7470  7470 D ActivityThread: Added TimaKeyStore provider
,09-13 00:05:46.072  7470  7470 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,09-13 00:05:46.082  1018  1486 I ActivityManager: Killing 6928:com.android.mms/u0a41 (adj 15): empty #21
,09-13 00:05:46.092  1018  4258 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,09-13 00:05:46.092  1018  4258 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:05:46.092  1018  4258 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:46.092  1018  4258 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:46.092  1018  4258 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:05:46.092  2750  7485 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,09-13 00:05:46.102  2750  7485 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,09-13 00:05:46.102  2750  7485 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
09-13 00:05:46.102  2750  7485 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0,
,09-13 00:05:46.102  2750  7485 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,09-13 00:05:46.112  1018  4258 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7486 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,09-13 00:05:46.112  7486  7486 E Zygote  : MountEmulatedStorage(),
,09-13 00:05:46.122  7486  7486 E Zygote  : v2
,09-13 00:05:46.122  7486  7486 I libpersona: KNOX_SDCARD checking this for 10032
09-13 00:05:46.122  7486  7486 I libpersona: KNOX_SDCARD not a persona
,09-13 00:05:46.122  7486  7486 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 00:05:46.122  7486  7486 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-13 00:05:46.122  7486  7486 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-13 00:05:46.152  7486  7486 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 00:05:46.152  7486  7486 D ActivityThread: Added TimaKeyStore provider
,09-13 00:05:46.202  1018  1223 D CountryDetector: No listener is left
,09-13 00:05:46.202   323   323 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 00:05:46.212  7486  7501 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,09-13 00:05:46.212  7486  7501 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,09-13 00:05:46.222  7486  7486 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,09-13 00:05:46.222  7486  7501 D SPPClientService: PushLog.txt file is not deleted.
,09-13 00:05:46.232  7486  7501 D SPPClientService: PushLog.txt file is not deleted.
09-13 00:05:46.232  7486  7501 D SPPClientService: ============PushLog. stop!
09-13 00:05:46.232  1018  1223 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,09-13 00:05:46.232  1018  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:05:46.232  1018  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:46.232  1018  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:46.232  1018  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:05:46.242  1018  1223 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7503 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
09-13 00:05:46.242  7503  7503 E Zygote  : MountEmulatedStorage()
09-13 00:05:46.242  7503  7503 E Zygote  : v2
09-13 00:05:46.242  7503  7503 I libpersona: KNOX_SDCARD checking this for 10036
09-13 00:05:46.242  7503  7503 I libpersona: KNOX_SDCARD not a persona
09-13 00:05:46.252  1018  1223 I ActivityManager: Killing 7086:com.sec.android.provider.badge/u0a68 (adj 15): empty #21,
09-13 00:05:46.252  7503  7503 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 00:05:46.252  1018  1079 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
09-13 00:05:46.252  1018  1079 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0,
09-13 00:05:46.252  1018  1079 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:46.252  1018  1079 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-13 00:05:46.252  1018  1079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
09-13 00:05:46.252  7503  7503 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 00:05:46.252  7503  7503 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,09-13 00:05:46.272  7503  7503 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 00:05:46.272  7503  7503 D ActivityThread: Added TimaKeyStore provider
,09-13 00:05:46.282  7486  7510 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,09-13 00:05:46.322  7503  7503 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@18877e84
,09-13 00:05:46.332  7503  7503 I SA      : [SSP] onCreated
,09-13 00:05:46.342  7503  7503 I SA      : [TPM] There is no property file
,09-13 00:05:46.342  7503  7503 I SA      : [SCU] isHaveSA() - false
,09-13 00:05:46.342  7503  7503 I SA      : [TPM] getModelProperty : null
,09-13 00:05:46.342  7503  7503 I SA      : [TPM] getCSCProperty : null
,09-13 00:05:46.342  7503  7503 I SA      : [DM] FLOATING AMOLED FEATURE: true
,09-13 00:05:46.342  7503  7503 I SA      : [DM] PRODUCT AMOLED FEATURE: false
09-13 00:05:46.342  7503  7503 I SA      : [DM] TFT FEATURE: false
,09-13 00:05:46.352  7503  7503 I SA      : [DM] init START
,09-13 00:05:46.352  7503  7503 I SA      : [DM] This device is not a Vodafone
,09-13 00:05:46.352  7503  7503 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,09-13 00:05:46.352  7503  7503 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,09-13 00:05:46.362  7503  7503 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,09-13 00:05:46.362  7503  7503 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,09-13 00:05:46.362  7503  7503 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
09-13 00:05:46.362  7503  7503 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,09-13 00:05:46.362  7503  7503 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,09-13 00:05:46.362  7503  7503 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-13 00:05:46.362  7503  7503 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,09-13 00:05:46.362  7503  7503 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,09-13 00:05:46.362  7503  7503 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,09-13 00:05:46.362  7503  7503 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,09-13 00:05:46.362  7503  7503 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,09-13 00:05:46.362  7503  7503 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
,09-13 00:05:46.362  7503  7503 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
09-13 00:05:46.362  7503  7503 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,09-13 00:05:46.372  7503  7503 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
,09-13 00:05:46.372  7503  7503 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
09-13 00:05:46.372  7503  7503 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,09-13 00:05:46.372  7503  7503 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,09-13 00:05:46.372  7503  7503 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,09-13 00:05:46.372  7503  7503 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,09-13 00:05:46.372  7503  7503 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
09-13 00:05:46.372  7503  7503 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,09-13 00:05:46.372  7503  7503 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
09-13 00:05:46.372  7503  7503 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,09-13 00:05:46.372  7503  7503 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
,09-13 00:05:46.372  7503  7503 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,09-13 00:05:46.382  7503  7503 I SA      : [SCU] isHaveSA() - false,
09-13 00:05:46.382  7503  7503 I SA      : support phone number id : false
09-13 00:05:46.382  7503  7503 I SA      : [DM] Supports Ref Jpn : true,
09-13 00:05:46.382  7503  7503 I SA      : [DM] init END
09-13 00:05:46.382  7503  7503 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,09-13 00:05:46.382  7503  7503 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,09-13 00:05:46.382  7503  7503 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-13 00:05:46.392  7503  7503 I SA      : [SLFUCHKMGR] constructor called,
,09-13 00:05:46.402  7503  7503 I SA      : [TPMU]  strSIMState ,	:SIM_STATE_ABSENT
09-13 00:05:46.402  7503  7503 I SA      : [OR] == isSIMCardReady false ==
,09-13 00:05:46.402  7503  7503 I SA      : [SCU] == networkStateCheck == false
,09-13 00:05:46.402  7503  7503 I SA      : [OR] onReceive END
,09-13 00:05:46.402  1018  1487 I ActivityManager: Killing 7102:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
,09-13 00:05:46.412  1233  1233 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-13 00:05:46.412  1737  1737 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-13 00:05:46.422  2510  2578 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,09-13 00:05:46.422  1737  1737 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,09-13 00:05:46.422  1737  1737 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,09-13 00:05:46.422  1737  1737 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,09-13 00:05:46.422  1737  1737 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-13 00:05:46.432  1737  1737 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-13 00:05:46.432  1737  1737 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,09-13 00:05:46.432  1018  4259 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,09-13 00:05:46.432  1018  4259 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:05:46.432  1018  4259 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:46.432  1018  4259 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:05:46.432  1018  4259 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:05:46.452  7526  7526 E Zygote  : MountEmulatedStorage(),
09-13 00:05:46.452  7526  7526 E Zygote  : v2
09-13 00:05:46.452  7526  7526 I libpersona: KNOX_SDCARD checking this for 10077
,09-13 00:05:46.452  7526  7526 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 00:05:46.452  7526  7526 I libpersona: KNOX_SDCARD not a persona
,09-13 00:05:46.452  1018  4259 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7526 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-13 00:05:46.452  7526  7526 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-13 00:05:46.452  7526  7526 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,09-13 00:05:46.472  7526  7526 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 00:05:46.472  7526  7526 D ActivityThread: Added TimaKeyStore provider
,09-13 00:05:46.642  1018  1030 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,09-13 00:05:46.642  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,09-13 00:05:46.642  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,09-13 00:05:46.652  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 00:05:46.652  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-13 00:05:46.652  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,09-13 00:05:46.652  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:46.652  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:46.652  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:46.652  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:05:46.672  7544  7544 E Zygote  : MountEmulatedStorage()
,09-13 00:05:46.672  7544  7544 E Zygote  : v2
09-13 00:05:46.672  7544  7544 I libpersona: KNOX_SDCARD checking this for 10110
09-13 00:05:46.672  7544  7544 I libpersona: KNOX_SDCARD not a persona
,09-13 00:05:46.672  7544  7544 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 00:05:46.672  7544  7544 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 00:05:46.672  1018  1031 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7544 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-13 00:05:46.672  7544  7544 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
09-13 00:05:46.672  1018  1489 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
09-13 00:05:46.672  1018  1489 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:46.672  1018  1489 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
09-13 00:05:46.672  1018  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 00:05:46.672  1018  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-13 00:05:46.682  7362  7543 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-13 00:05:46.682  1018  1223 I ActivityManager: Killing 7118:com.wsomacp/u0a23 (adj 15): empty #21
,09-13 00:05:46.702  7544  7544 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 00:05:46.702  7544  7544 D ActivityThread: Added TimaKeyStore provider
,09-13 00:05:46.832  1018  4258 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-13 00:05:46.872  1018  1031 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-13 00:05:46.872  1018  1031 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-13 00:05:46.872  1018  1031 D SecContentProvider2: mCursor = null
,09-13 00:05:46.872  1018  1031 D WifiService: setWifiEnabled: true pid=7018, uid=10170
,09-13 00:05:46.872  1018  1031 W ActivityManager: Permission Denial: getCurrentUser() from pid=7018, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-13 00:05:46.872  1018  1031 W WifiService: Failed getting userId using ActivityManagerNative
09-13 00:05:46.872  1018  1031 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7018, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-13 00:05:46.872  1018  1031 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-13 00:05:46.872  1018  1031 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-13 00:05:46.872  1018  1031 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-13 00:05:46.872  1018  1031 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-13 00:05:46.872  1018  1031 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-13 00:05:46.872  1018  1031 D SettingsProvider: name = wifi_on
,09-13 00:05:46.882  1018  1128 E WifiHW  : ##################### set firmware type 0 #####################
,09-13 00:05:46.972   258   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-13 00:05:46.972   258   518 W Vold    : Returning OperationFailed - no handler for errno 0
,09-13 00:05:46.972  7544  7563 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-13 00:05:46.972   258   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-13 00:05:46.972   258   518 W Vold    : Returning OperationFailed - no handler for errno 0
,09-13 00:05:46.972  7544  7563 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-13 00:05:46.982   258   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-13 00:05:46.982   258   518 W Vold    : Returning OperationFailed - no handler for errno 0
,09-13 00:05:46.992  7544  7564 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-13 00:05:46.992   258   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-13 00:05:46.992   258   518 W Vold    : Returning OperationFailed - no handler for errno 0
,09-13 00:05:46.992  7544  7564 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-13 00:05:47.012  7544  7544 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-13 00:05:47.012  7544  7544 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-13 00:05:47.012  7544  7544 I GAv4    :   adb logcat -s GAv4
,09-13 00:05:47.032  7544  7544 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-13 00:05:47.032  1018  1331 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-13 00:05:47.042  7544  7544 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,09-13 00:05:47.052  7544  7566 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-13 00:05:47.202   323   323 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 00:05:47.272  1018  1045 D Tethering: interfaceAdded wlan0
,09-13 00:05:47.282  1018  1132 E Tethering: No numeric data
,09-13 00:05:47.282  1018  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-13 00:05:47.282  1018  1132 D Tethering: clearTetheredNotification()
09-13 00:05:47.282  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-13 00:05:47.282  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,09-13 00:05:47.282  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 00:05:47.282  1018  1125 V NetworkStats: performPollLocked(flags=0x1)
09-13 00:05:47.282  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-13 00:05:47.282  1175  1175 D HotspotTile: updateTetherState():false, false
09-13 00:05:47.292  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-13 00:05:47.292  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-13 00:05:47.292  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-13 00:05:47.292  1018  1132 D Tethering: InitialState.processMessage what=4
,09-13 00:05:47.292  1018  1125 V NetworkStats: performPollLocked() took 5ms
,09-13 00:05:47.292  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 00:05:47.292  1018  1045 D Tethering: interfaceAdded p2p0
,09-13 00:05:47.292  1018  1132 E Tethering: No numeric data
09-13 00:05:47.292  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 00:05:47.292  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 00:05:47.292  1018  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-13 00:05:47.292  1018  1132 D Tethering: clearTetheredNotification()
,09-13 00:05:47.292  1018  1045 D Tethering: p2p0 is not a tetherable iface, ignoring
,09-13 00:05:47.292   279  1017 I WifiHW  : wifi_change_fw_path(): fwpath = sta,
09-13 00:05:47.302  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-13 00:05:47.302  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false,
,09-13 00:05:47.302  1018  1125 V NetworkStats: performPollLocked(flags=0x1)
,09-13 00:05:47.302  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
09-13 00:05:47.302  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-13 00:05:47.302   279  1017 D SoftapController: Softap fwReload - Ok
09-13 00:05:47.302  1175  1175 D HotspotTile: updateTetherState():false, false
09-13 00:05:47.302  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 00:05:47.302  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
09-13 00:05:47.302  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-13 00:05:47.302   279  1017 D CommandListener: Setting iface cfg
09-13 00:05:47.302   279  1017 D CommandListener: Trying to bring down wlan0
09-13 00:05:47.302   279  1017 D CommandListener: Clearing all IP addresses on wlan0
,09-13 00:05:47.302  1018  1125 V NetworkStats: performPollLocked() took 6ms
,09-13 00:05:47.302  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 00:05:47.302  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 00:05:47.302  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 00:05:47.312  1018  1128 E WifiHW  : supplicant_name : p2p_supplicant,
,09-13 00:05:47.312  1018  1128 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
,09-13 00:05:47.312  1018  1128 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": Permission denied
,09-13 00:05:47.332  4836  4836 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-13 00:05:47.332  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
09-13 00:05:47.332  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:05:47.332  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-13 00:05:47.332  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-13 00:05:47.332  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-13 00:05:47.332  1175  1799 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-13 00:05:47.332  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:05:47.332  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-13 00:05:47.332  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 00:05:47.332  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:05:47.332  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
09-13 00:05:47.332  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
09-13 00:05:47.342  1175  1175 D HotspotTile: onReceive : 2, 0
,09-13 00:05:47.342  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:05:47.342  1018  1331 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 00:05:47.352  1018  1331 W ActivityManager: userId = 0, bbcId = -10000
,09-13 00:05:47.352  1018  1331 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 00:05:47.352  1018  1331 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-13 00:05:47.392  7587  7587 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-13 00:05:47.392  7587  7587 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-13 00:05:47.392  7587  7587 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-13 00:05:47.392  7544  7544 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,09-13 00:05:47.412  7587  7587 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,09-13 00:05:47.412   390   390 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7587,
09-13 00:05:47.412   390   390 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
09-13 00:05:47.412  7587  7587 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-13 00:05:47.412  7587  7587 I wpa_supplicant: ssSupport state is = 1
09-13 00:05:47.412  7587  7587 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-13 00:05:47.412  7587  7587 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
09-13 00:05:47.412   390   390 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7587
09-13 00:05:47.412   390   390 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106,
,09-13 00:05:47.422  7544  7544 I cr.library_loader: Time to load native libraries: 9 ms (timestamps 8282-8291)
,09-13 00:05:47.422  7544  7544 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-13 00:05:47.432  7544  7544 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2f9afb4f}
,09-13 00:05:47.432  7544  7544 I cr.library_loader: Expected native library version number "", actual native library version number ""
09-13 00:05:47.432  7544  7544 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,09-13 00:05:47.452  7544  7544 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,09-13 00:05:47.452  7544  7544 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-13 00:05:47.452  7544  7544 E SysUtils: ApplicationContext is null in ApplicationStatus,
,09-13 00:05:47.472  7544  7544 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e),
09-13 00:05:47.472  7544  7544 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-13 00:05:47.472  7544  7544 I Adreno-EGL: Build Date: 04/06/15 Mon
09-13 00:05:47.472  7544  7544 I Adreno-EGL: Local Branch: 
09-13 00:05:47.472  7544  7544 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-13 00:05:47.472  7544  7544 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-13 00:05:47.472  7544  7544 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-13 00:05:47.502  5912  5912 D FactoryTest: Not factory mode
,09-13 00:05:47.512  5912  5912 D FactoryTest: Not factory mode. isFactoryMode() returend false
,09-13 00:05:47.512  5912  5912 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,09-13 00:05:47.512  5912  5912 D MTPRx   : still no open session command from host, so toast
,09-13 00:05:47.512  5912  5912 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,09-13 00:05:47.512  5912  5912 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,09-13 00:05:47.512  5912  5912 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:118386
,09-13 00:05:47.512  1018  1030 E PersonaManagerService: inState():  stateMachine is null !!
,09-13 00:05:47.512  1018  1030 I PersonaManagerService: PersonaId don't exist
09-13 00:05:47.512  1018  1030 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,09-13 00:05:47.522  1018  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
,09-13 00:05:47.522  1018  1030 W ActivityManager: userId = 0, bbcId = -10000,
09-13 00:05:47.522  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:47.522  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,09-13 00:05:47.522  1018  1030 W ActivityManager: mDVFSHelper.acquire(),
,09-13 00:05:47.542  1018  1030 D PersonaManager: isKioskContainerExistOnDevice
,09-13 00:05:47.562  1018  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-13 00:05:47.562  1018  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-13 00:05:47.562  1018  1030 D InputDispatcher: Focused application set to: xxxx
09-13 00:05:47.562  1018  1030 D InputDispatcher: Focus left window: 7018
,09-13 00:05:47.562  5912  5912 E MTPRx   : started activity for popup
,09-13 00:05:47.562  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-13 00:05:47.562  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-13 00:05:47.582  5912  5912 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
09-13 00:05:47.582  5912  5912 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-13 00:05:47.582  5912  5912 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-13 00:05:47.582  5912  5912 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 00:05:47.582  5912  5912 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-13 00:05:47.582  5912  5912 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-13 00:05:47.602   390   390 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0,
,09-13 00:05:47.602  7587  7587 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,09-13 00:05:47.612  5912  5912 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,09-13 00:05:47.622  1018  1504 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
09-13 00:05:47.622  1018  1504 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-13 00:05:47.622  1018  1504 D InputDispatcher: Focused application set to: xxxx
09-13 00:05:47.622  1018  1504 D InputDispatcher: Focus entered window: 7018
,09-13 00:05:47.622  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
09-13 00:05:47.622  1018  1031 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@398da606 attribute=null, token = android.os.BinderProxy@11132a10
09-13 00:05:47.622  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
09-13 00:05:47.622  1018  1031 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-13 00:05:47.632  7544  7605 W cr.media: Requires BLUETOOTH permission
,09-13 00:05:47.642  7544  7544 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-13 00:05:47.652  7544  7544 I NSApplication: Starting up...
,09-13 00:05:47.652  1018  1223 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-13 00:05:47.652  1018  1331 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-13 00:05:47.662  1018  1810 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,09-13 00:05:47.662  1018  1810 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-13 00:05:47.662  1018  1810 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:47.662  1018  1810 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:47.662  1018  1810 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:05:47.662  7587  7587 I wpa_supplicant: Ctrl_iface: loading cred from phone,
09-13 00:05:47.662  7587  7587 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-13 00:05:47.672  7587  7587 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,09-13 00:05:47.672   390   390 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7587,
,09-13 00:05:47.672   390   390 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-13 00:05:47.672  7587  7587 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-13 00:05:47.672  7587  7587 I wpa_supplicant: ssSupport state is = 1
09-13 00:05:47.682  7587  7587 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-13 00:05:47.682  7587  7587 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-13 00:05:47.682  7587  7587 E wpa_supplicant: SIM READ ERROR
09-13 00:05:47.682  7587  7587 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-13 00:05:47.682  7587  7587 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
09-13 00:05:47.682  7587  7587 E wpa_supplicant: SIM READ ERROR
09-13 00:05:47.682  7587  7587 I wpa_supplicant: Blacklist: Clear (all) 
09-13 00:05:47.682  7587  7587 I wpa_supplicant: wpa_default_ap_write_once,
09-13 00:05:47.682  7587  7587 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-13 00:05:47.682  7587  7587 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-13 00:05:47.682  7587  7587 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory,
09-13 00:05:47.682  7587  7587 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-13 00:05:47.682  7587  7587 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-13 00:05:47.682  7587  7587 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-13 00:05:47.682  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false,
09-13 00:05:47.682  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-13 00:05:47.682  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,09-13 00:05:47.692  5912  5912 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,09-13 00:05:47.692  7611  7611 E Zygote  : MountEmulatedStorage()
,09-13 00:05:47.692  7611  7611 E Zygote  : v2
09-13 00:05:47.692  7611  7611 I libpersona: KNOX_SDCARD checking this for 10117
09-13 00:05:47.692  7611  7611 I libpersona: KNOX_SDCARD not a persona
,09-13 00:05:47.692  7611  7611 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 00:05:47.692  1018  1810 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7611 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
09-13 00:05:47.692  1018  1810 I ActivityManager: Killing 7166:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
,09-13 00:05:47.692  7611  7611 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 00:05:47.692  7611  7611 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-13 00:05:47.702  5912  5912 D PhoneWindow: *FMB* installDecor mIsFloating : true
09-13 00:05:47.702  5912  5912 D PhoneWindow: *FMB* installDecor flags : 8388610
,09-13 00:05:47.722  7611  7611 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 00:05:47.722  7611  7611 D ActivityThread: Added TimaKeyStore provider
,09-13 00:05:47.722  7587  7587 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,09-13 00:05:47.742  7018  7018 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-13 00:05:47.742  7018  7018 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
09-13 00:05:47.742  7018  7018 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-13 00:05:47.742  7018  7018 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,09-13 00:05:47.752  1018  1472 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-13 00:05:47.752  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
09-13 00:05:47.752  1018  1472 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-13 00:05:47.752  1018  1472 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
09-13 00:05:47.752  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,09-13 00:05:47.752  7018  7018 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-13 00:05:47.762  7018  7018 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-13 00:05:47.762  7018  7018 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3a999295 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@32d6237b, 16908290=android.view.AbsSavedState$1@32d6237b}, android:focusedViewId=100}]}]
09-13 00:05:47.762  7018  7018 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-13 00:05:47.762  7018  7018 V ActivityThread: updateVisibility : ActivityRecord{2874196f token=android.os.BinderProxy@83cc349 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-13 00:05:47.762  7018  7018 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-13 00:05:47.762  7018  7018 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-13 00:05:47.762  7018  7018 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@83cc349 time:118634
,09-13 00:05:47.762  7611  7611 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-13 00:05:47.772  1018  1079 D PersonaManager: isKioskContainerExistOnDevice
,09-13 00:05:47.852  7587  7587 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
09-13 00:05:47.852  7587  7587 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-13 00:05:47.862  7587  7587 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
09-13 00:05:47.862   390   390 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7587
09-13 00:05:47.862   390   390 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,09-13 00:05:47.862  7587  7587 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-13 00:05:47.862  7587  7587 I wpa_supplicant: ssSupport state is = 1
,09-13 00:05:47.862  7587  7587 I wpa_supplicant: Ctrl_iface: loading cred from phone,
09-13 00:05:47.862  7587  7587 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-13 00:05:47.872  7587  7587 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
09-13 00:05:47.882   390   390 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7587
09-13 00:05:47.882   390   390 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-13 00:05:47.882  7587  7587 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-13 00:05:47.882  7587  7587 I wpa_supplicant: ssSupport state is = 1
09-13 00:05:47.882  7587  7587 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-13 00:05:47.882  7587  7587 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-13 00:05:47.882  7587  7587 E wpa_supplicant: SIM READ ERROR
09-13 00:05:47.882  7587  7587 I wpa_supplicant: wpa_default_ap_write_once
09-13 00:05:47.882  7587  7587 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-13 00:05:47.882  7587  7587 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-13 00:05:47.882  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
09-13 00:05:47.882  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-13 00:05:47.882  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,09-13 00:05:47.882  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
,09-13 00:05:47.882  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-13 00:05:47.882  1018  1045 D Tethering: interfaceStatusChanged p2p0, false,
,09-13 00:05:47.952  7587  7587 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
09-13 00:05:47.952  7587  7587 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-13 00:05:48.002  7587  7587 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
09-13 00:05:48.002  7587  7587 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-13 00:05:48.002  7587  7587 I wpa_supplicant: Skip scan - bUseNetwork false
,09-13 00:05:48.102  1018  1810 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,09-13 00:05:48.112  1018  1810 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:05:48.112  1018  1810 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:48.112  1018  1810 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:48.112  1018  1810 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:05:48.122  1018  1810 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7634 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,09-13 00:05:48.122  7634  7634 E Zygote  : MountEmulatedStorage()
09-13 00:05:48.122  7634  7634 I libpersona: KNOX_SDCARD checking this for 10121
09-13 00:05:48.122  7634  7634 E Zygote  : v2
09-13 00:05:48.122  7634  7634 I libpersona: KNOX_SDCARD not a persona
,09-13 00:05:48.122  1018  1810 I ActivityManager: Killing 7188:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21,
,09-13 00:05:48.132  7634  7634 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 00:05:48.132  7634  7634 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 00:05:48.132  7634  7634 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 00:05:48.152  7634  7634 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 00:05:48.152  7634  7634 D ActivityThread: Added TimaKeyStore provider,
,09-13 00:05:48.172  7634  7634 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
09-13 00:05:48.172  7634  7634 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-13 00:05:48.172  7634  7634 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-13 00:05:48.182   292   292 E SMD     : DCD OFF
,09-13 00:05:48.182  7634  7634 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,09-13 00:05:48.202  7634  7634 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,09-13 00:05:48.202  7634  7634 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,09-13 00:05:48.202  1018  1487 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,09-13 00:05:48.202  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:48.202  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:48.202  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:48.202  1018  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:05:48.212   323   323 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-13 00:05:48.232  7652  7652 E Zygote  : MountEmulatedStorage(),
09-13 00:05:48.232  7652  7652 E Zygote  : v2
,09-13 00:05:48.232  7652  7652 I libpersona: KNOX_SDCARD checking this for 10141
09-13 00:05:48.232  7652  7652 I libpersona: KNOX_SDCARD not a persona
,09-13 00:05:48.232  7652  7652 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 00:05:48.232  1018  1487 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7652 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
,09-13 00:05:48.232  7652  7652 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 00:05:48.232  7652  7652 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-13 00:05:48.232  1018  1487 I ActivityManager: Killing 7204:com.android.calendar/u0a131 (adj 15): empty #21,
,09-13 00:05:48.252   308   308 I art     : Explicit concurrent mark sweep GC freed 8684(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 594us total 19.424ms
,09-13 00:05:48.262  7652  7652 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 00:05:48.262  7652  7652 D ActivityThread: Added TimaKeyStore provider
,09-13 00:05:48.272   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 585us total 16.481ms
,09-13 00:05:48.272  7652  7652 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
09-13 00:05:48.282  7652  7652 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 00:05:48.282  7652  7652 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-13 00:05:48.282  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false,
09-13 00:05:48.282  7652  7652 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-13 00:05:48.282  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
09-13 00:05:48.282  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-13 00:05:48.292   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 724us total 16.569ms
,09-13 00:05:48.322  1018  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,09-13 00:05:48.322  1018  1128 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-13 00:05:48.322  7587  7587 I wpa_supplicant: HOTSPOT20_ENABLE called
09-13 00:05:48.322  7587  7587 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-13 00:05:48.322  7587  7587 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-13 00:05:48.322  7587  7587 E wpa_supplicant: SIM READ ERROR
09-13 00:05:48.322  7587  7587 I wpa_supplicant: Blacklist: Clear (all) 
,09-13 00:05:48.322  1018  1031 D RCPManagerService: exchangeData() failure , invalid userId
,09-13 00:05:48.332  7587  7587 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,09-13 00:05:48.342  7587  7587 I wpa_supplicant: Skip scan - bUseNetwork false,
09-13 00:05:48.342  1018  1128 D WifiConfigStore: Loading config and enabling all networks 
,09-13 00:05:48.342  1018  1486 D RCPManagerService: exchangeData() failure , invalid userId
,09-13 00:05:48.352  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-13 00:05:48.352  1018  1128 E WifiConfigStore: Not a HS20
09-13 00:05:48.352  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-13 00:05:48.352  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-13 00:05:48.352  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 00:05:48.352  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:05:48.352  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 00:05:48.352  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:05:48.352  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-13 00:05:48.352  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-13 00:05:48.352  4836  4836 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
09-13 00:05:48.352  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,09-13 00:05:48.352  1175  1175 D HotspotTile: onReceive : 3, 0
,09-13 00:05:48.352  1175  1799 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-13 00:05:48.352  1018  1128 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-13 00:05:48.362  1018  1128 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-13 00:05:48.362  7587  7587 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-13 00:05:48.362  7587  7587 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-13 00:05:48.362  7587  7587 I wpa_supplicant: reset timer : RESET_TIMER 0
09-13 00:05:48.362  7587  7587 I wpa_supplicant: P2P: Current p2p state = IDLE
09-13 00:05:48.362  7587  7587 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-13 00:05:48.362  7587  7587 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-13 00:05:48.362  7587  7587 I wpa_supplicant: First Scan Start
09-13 00:05:48.362  7587  7587 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-13 00:05:48.362  7018  7018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 00:05:48.362  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:05:48.362  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:05:48.362  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:05:48.362  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:05:48.362  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 00:05:48.362  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:05:48.362  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:05:48.362  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 00:05:48.362  1018  1128 D WifiNative-wlan0: Setting external_sim to 1
,09-13 00:05:48.362  1018  1128 D WifiStateMachine: Setting OUI to DA-A1-19
09-13 00:05:48.362  1018  1128 I WifiNative-HAL: startHal
09-13 00:05:48.362  1018  1128 E wifi    : getStaticLongField sWifiHalHandle 0x9f12988c
09-13 00:05:48.362  1018  1128 I WifiNative-HAL: Could not start hal
,09-13 00:05:48.362  7018  7018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 00:05:48.362  7018  7018 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 00:05:48.362  7362  7362 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 00:05:48.362  1018  1128 E WifiNative-wlan0: do suspend true
,09-13 00:05:48.362  7018  7018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 00:05:48.362  1018  1127 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-13 00:05:48.362  1018  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
09-13 00:05:48.372  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:05:48.372  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:05:48.372  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:05:48.372  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:05:48.372  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 00:05:48.372  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:05:48.372  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:05:48.372  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 00:05:48.372  1018  1018 D WifiScanningService: SCAN_AVAILABLE : 3
,09-13 00:05:48.372  1018  1018 D RttService: SCAN_AVAILABLE : 3
09-13 00:05:48.372  1018  1153 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:05:48.372  1018  1152 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,09-13 00:05:48.372  1018  1152 I WifiNative-HAL: startHal
09-13 00:05:48.372   279  1017 D CommandListener: Setting iface cfg
09-13 00:05:48.372  7018  7018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 00:05:48.372  7018  7018 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 00:05:48.372   279  1017 D CommandListener: Trying to bring up p2p0
,09-13 00:05:48.372  7587  7587 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-13 00:05:48.372  7587  7587 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-13 00:05:48.372  1018  1127 D WifiP2pService: P2pEnablingState
09-13 00:05:48.372  1018  1127 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-13 00:05:48.372  1018  1127 D WifiP2pService: P2pEnablingState{ what=147457 }
,09-13 00:05:48.372  1018  1127 D WifiP2pService: P2p socket connection successful
09-13 00:05:48.372  1018  1127 D WifiP2pService: P2pEnabledState
09-13 00:05:48.372  7587  7587 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
09-13 00:05:48.372  1018  1128 E WifiStateMachine: Failed to set frequency band 0
09-13 00:05:48.372  1018  1127 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-13 00:05:48.372  1018  1152 E wifi    : getStaticLongField sWifiHalHandle 0x9e0e99bc
09-13 00:05:48.372  1018  1130 E ConnectivityService: updateNetworkInfo()
,09-13 00:05:48.372  1018  1152 I WifiNative-HAL: Could not start hal
09-13 00:05:48.372  1018  1152 E WifiScanningService: could not start HAL
,09-13 00:05:48.372  1018  1128 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-13 00:05:48.372  1018  1128 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-13 00:05:48.372  1018  1128 E WifiNative-wlan0: invaild command id : 215
,09-13 00:05:48.372  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-13 00:05:48.372  1018  1128 D SecContentProvider2: mCursor = null
09-13 00:05:48.372  1018  1018 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-13 00:05:48.382  1018  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-13 00:05:48.382  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-13 00:05:48.382  1018  1048 D WifiDisplayController: disconnect
09-13 00:05:48.382  1018  1048 D WifiDisplayController: updateConnection
09-13 00:05:48.382  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,09-13 00:05:48.382  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-13 00:05:48.382  1018  1128 D SecContentProvider2: mCursor = null
09-13 00:05:48.382  1018  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-13 00:05:48.382  1018  1127 D WifiNative-p2p0: p2pGetDeviceAddress
,09-13 00:05:48.382  1018  1127 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,09-13 00:05:48.382  1018  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 00:05:48.382  1018  1048 D WifiDisplayAdapter: onP2pDisconnected
09-13 00:05:48.382  1018  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-13 00:05:48.382  1018  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-13 00:05:48.382  1018  1127 D WifiP2pService: DeviceAddress: 0a:75:42
,09-13 00:05:48.392  1175  1175 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-13 00:05:48.392  1018  4258 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-13 00:05:48.392  1175  1175 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
09-13 00:05:48.392  1018  1048 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3,
09-13 00:05:48.392  1018  1048 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
09-13 00:05:48.392  1018  1048 D WifiDisplayController:  primary type: 10-0050F204-5
09-13 00:05:48.392  1018  1048 D WifiDisplayController:  secondary type: null
09-13 00:05:48.392  1018  1048 D WifiDisplayController:  wps: 0
09-13 00:05:48.392  1018  1048 D WifiDisplayController:  grpcapab: 0
09-13 00:05:48.392  1018  1048 D WifiDisplayController:  devcapab: 0
09-13 00:05:48.392  1018  1048 D WifiDisplayController:  status: 3
09-13 00:05:48.392  1018  1048 D WifiDisplayController:  wfdInfo: null
09-13 00:05:48.392  1018  1048 D WifiDisplayController:  groupownerAddress: null
09-13 00:05:48.392  1018  1048 D WifiDisplayController:  GOdeviceName: null
09-13 00:05:48.392  1018  1048 D WifiDisplayController:  interfaceAddress: 
09-13 00:05:48.392  1018  1048 D WifiDisplayController:  SConnectInfo : null
,09-13 00:05:48.412  1018  1127 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-13 00:05:48.412  1018  1127 D WifiP2pService: InactiveState
09-13 00:05:48.412  1018  1127 D WifiP2pService: InactiveState{ what=143376 }
,09-13 00:05:48.412  1018  1127 D WifiP2pService: P2pEnabledState{ what=143376 },
09-13 00:05:48.412  7587  7587 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-13 00:05:48.412  1018  1127 D WifiP2pService: InactiveState{ what=143376 }
09-13 00:05:48.412  1018  1127 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-13 00:05:48.412  1018  1489 D RCPManagerService: exchangeData() failure , invalid userId
,09-13 00:05:48.422  1018  1504 D RCPManagerService: exchangeData() failure , invalid userId
,09-13 00:05:48.462  1018  1030 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,09-13 00:05:48.462  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:48.462  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:48.462  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:48.462  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:05:48.462  1018  1504 D RCPManagerService: exchangeData() failure , invalid userId
,09-13 00:05:48.472  1018  1810 D RCPManagerService: exchangeData() failure , invalid userId
,09-13 00:05:48.472  7678  7678 E Zygote  : MountEmulatedStorage(),
09-13 00:05:48.472  7678  7678 I libpersona: KNOX_SDCARD checking this for 10068
09-13 00:05:48.472  7678  7678 E Zygote  : v2
09-13 00:05:48.472  7678  7678 I libpersona: KNOX_SDCARD not a persona
09-13 00:05:48.482  7678  7678 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 00:05:48.482  1018  1030 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7678 uid=10068 gids={50068, 9997} abi=armeabi-v7a,
,09-13 00:05:48.482  7678  7678 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-13 00:05:48.482  7678  7678 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-13 00:05:48.502  7678  7678 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 00:05:48.502  7678  7678 D ActivityThread: Added TimaKeyStore provider
,09-13 00:05:48.502  1018  4258 D RCPManagerService: exchangeData() failure , invalid userId
,09-13 00:05:48.512  1018  1223 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast,
09-13 00:05:48.512  1018  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:48.512  1018  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:48.512  1018  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:48.512  1018  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:05:48.522  7693  7693 E Zygote  : MountEmulatedStorage(),
,09-13 00:05:48.522  7693  7693 E Zygote  : v2
09-13 00:05:48.522  7678  7678 D BadgeProvider: onCreate
,09-13 00:05:48.522  7693  7693 I libpersona: KNOX_SDCARD checking this for 10009
09-13 00:05:48.522  7678  7678 D BadgeProvider: DatabaseHelper
,09-13 00:05:48.522  7693  7693 I libpersona: KNOX_SDCARD not a persona
,09-13 00:05:48.522  7693  7693 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 00:05:48.532  7693  7693 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 00:05:48.532  1018  1223 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7693 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
09-13 00:05:48.532  1018  1223 I ActivityManager: Killing 6889:com.android.vending/u0a26 (adj 15): empty #21
,09-13 00:05:48.532  1018  1223 I ActivityManager: Killing 7139:com.android.defcontainer/u0a3 (adj 15): empty #22
09-13 00:05:48.532  7693  7693 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-13 00:05:48.562  7693  7693 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 00:05:48.562  7693  7693 D ActivityThread: Added TimaKeyStore provider
,09-13 00:05:48.632  1018  1505 I ActivityManager: Killing 7329:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,09-13 00:05:48.642   279  1013 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-13 00:05:48.642   279  1013 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,09-13 00:05:48.642  1018  1810 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-13 00:05:48.642  1018  1810 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-13 00:05:48.642  1018  1810 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:48.642  1018  1810 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:48.642  1018  1810 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-13 00:05:48.642  1635  1635 I Hs20UtilService: Starting #12
,09-13 00:05:48.642  1635  1663 I Hs20UtilService: Message received 5011
,09-13 00:05:48.652  7385  7385 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-13 00:05:48.652  7385  7385 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-13 00:05:48.652  7385  7385 D SecurityLogAgent: StateMachine : Current State = 1
09-13 00:05:48.652  7385  7385 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-13 00:05:48.662  1018  1079 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-13 00:05:48.662  1018  1079 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-13 00:05:48.662  1018  1079 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:48.662  1018  1079 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-13 00:05:48.662  1018  1079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-13 00:05:48.672  1635  1635 I Hs20UtilService: Starting #13
,09-13 00:05:48.672  1635  1663 I Hs20UtilService: Message received 5011
,09-13 00:05:48.682  1018  1128 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-13 00:05:48.682  1018  1128 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-13 00:05:48.682  1018  1128 E WifiNative-wlan0: invaild command id : 215
,09-13 00:05:48.682  7385  7385 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-13 00:05:48.682  7385  7385 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-13 00:05:48.692  7385  7385 D SecurityLogAgent: StateMachine : Current State = 1
09-13 00:05:48.692  7385  7385 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-13 00:05:48.702  1018  1079 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,09-13 00:05:48.702  1018  1079 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,09-13 00:05:48.702  4836  4836 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-13 00:05:48.702  4836  4836 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-13 00:05:48.702  4836  4836 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-13 00:05:48.702  1018  1505 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,09-13 00:05:48.702  1018  1030 I art     : Explicit concurrent mark sweep GC freed 71847(3MB) AllocSpace objects, 11(224KB) LOS objects, 33% free, 23MB/34MB, paused 9.603ms total 173.531ms
,09-13 00:05:48.712  1018  1223 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,09-13 00:05:48.722  4836  4836 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-13 00:05:48.722  4836  4836 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-13 00:05:48.722  4836  4836 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-13 00:05:48.722  4836  4878 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-13 00:05:48.722  1018  1810 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-13 00:05:48.722  1018  1810 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.samsung.android.app.FileShareClient/com.samsung.android.app.FileShareClient.ClientBroadcastReceiver}
09-13 00:05:48.722  1018  1810 W BroadcastQueue: android.os.TransactionTooLargeException
09-13 00:05:48.722  1018  1810 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-13 00:05:48.722  1018  1810 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
09-13 00:05:48.722  1018  1810 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
09-13 00:05:48.722  1018  1810 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
09-13 00:05:48.722  1018  1810 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
09-13 00:05:48.722  1018  1810 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
09-13 00:05:48.722  1018  1810 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
09-13 00:05:48.722  1018  1810 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
09-13 00:05:48.722  1018  1810 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,09-13 00:05:48.722  1018  1810 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,09-13 00:05:48.722  1018  1810 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:05:48.722  1018  1810 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:48.722  1018  1810 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:48.722  1018  1810 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:05:48.732  7678  7687 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge',
,09-13 00:05:48.752  1018  1042 W libprocessgroup: failed to open /acct/uid_10064/pid_7329/cgroup.procs: No such file or directory
,09-13 00:05:48.752  7713  7713 E Zygote  : MountEmulatedStorage()
,09-13 00:05:48.752  7713  7713 I libpersona: KNOX_SDCARD checking this for 10064
09-13 00:05:48.752  7713  7713 E Zygote  : v2
09-13 00:05:48.752  7713  7713 I libpersona: KNOX_SDCARD not a persona
09-13 00:05:48.752  7713  7713 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 00:05:48.752  1018  1810 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7713 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-13 00:05:48.762  7713  7713 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 00:05:48.762  7713  7713 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 00:05:48.772  7678  7687 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
,09-13 00:05:48.772  7678  7687 D BadgeProvider: sendNotify, [notify] : null
09-13 00:05:48.772  1488  1488 D Launcher.Model: reloadBadges entered.
09-13 00:05:48.772  7678  7687 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
09-13 00:05:48.772  7678  7687 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-13 00:05:48.772  7678  7687 D BadgeProvider: update, [UpdateCount] : 1
,09-13 00:05:48.772  7713  7713 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 00:05:48.772  7713  7713 D ActivityThread: Added TimaKeyStore provider
,09-13 00:05:48.792  7713  7713 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-13 00:05:48.792  7713  7713 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-13 00:05:48.802  7713  7713 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-13 00:05:48.822  7713  7713 D FileShare-Client: Outbound.stopDelayTimer - 
,09-13 00:05:48.832  7346  7346 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-13 00:05:48.832  1018  1079 W ActivityManager: userId = 0, bbcId = -10000
,09-13 00:05:48.832  1018  1079 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 00:05:48.832  1018  1079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,09-13 00:05:48.842  1018  1486 I ActivityManager: Killing 7268:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,09-13 00:05:49.592  7587  7587 I wpa_supplicant: nl80211: Received scan results (24 BSSes),
09-13 00:05:49.592  7587  7587 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-13 00:05:49.592  7587  7587 I wpa_supplicant: Trying to associate with SSID '4E47373030'
09-13 00:05:49.592  7587  7587 I wpa_supplicant: Trying to associate with  'G700'
09-13 00:05:49.592  7587  7587 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,09-13 00:05:49.592  7587  7587 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
09-13 00:05:49.592  1018  7667 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,09-13 00:05:49.612  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-13 00:05:49.612  1018  1128 D SecContentProvider2: mCursor = null
,09-13 00:05:49.732  7587  7587 E wpa_supplicant: Cmd 35605 not handled
,09-13 00:05:49.732  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-13 00:05:49.732  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
09-13 00:05:49.732  7587  7587 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-13 00:05:49.732  7587  7587 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
09-13 00:05:49.732  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-13 00:05:49.732  7587  7587 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
,09-13 00:05:49.732  7587  7587 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-13 00:05:49.732  7587  7587 I wpa_supplicant: Associated with F4.99.3E
09-13 00:05:49.732  7587  7587 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-13 00:05:49.732  7587  7587 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-13 00:05:49.732  7587  7587 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,09-13 00:05:49.732  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-13 00:05:49.732  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
09-13 00:05:49.732  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-13 00:05:49.732  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-13 00:05:49.732  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
09-13 00:05:49.732  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-13 00:05:49.732  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, true
09-13 00:05:49.732  1018  1045 D Tethering: interfaceStatusChanged wlan0, true
,09-13 00:05:49.732  1018  1132 E Tethering: No numeric data
,09-13 00:05:49.732  1018  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-13 00:05:49.732  1018  1132 D Tethering: clearTetheredNotification()
,09-13 00:05:49.732  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-13 00:05:49.732  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 00:05:49.732  1018  1125 V NetworkStats: performPollLocked(flags=0x1)
09-13 00:05:49.732  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-13 00:05:49.732  1018  1128 D SecContentProvider2: mCursor = null
,09-13 00:05:49.742  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-13 00:05:49.742  1175  1175 D HotspotTile: updateTetherState():false, false
09-13 00:05:49.742  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
09-13 00:05:49.742  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-13 00:05:49.742  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-13 00:05:49.742  1018  1128 D SecContentProvider2: mCursor = null
09-13 00:05:49.742  1018  1125 V NetworkStats: performPollLocked() took 4ms
09-13 00:05:49.742  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 00:05:49.742  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 00:05:49.742  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 00:05:49.752  7587  7587 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-13 00:05:49.752  7587  7587 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,09-13 00:05:49.752  7587  7587 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
09-13 00:05:49.752  7587  7587 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
09-13 00:05:49.752  7587  7587 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP],
09-13 00:05:49.752  7587  7587 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-13 00:05:49.752  7587  7587 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-13 00:05:49.752  7587  7587 I wpa_supplicant: Blacklist: Clear (temp) 
09-13 00:05:49.752  7587  7587 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,09-13 00:05:49.752  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, true
09-13 00:05:49.752  1018  1045 D Tethering: interfaceStatusChanged wlan0, true
09-13 00:05:49.752  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,09-13 00:05:49.752  1018  1128 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-13 00:05:49.762  1018  1128 E WifiConfigStore: setLastSelectedConfiguration -1,
,09-13 00:05:49.762  1018  1128 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,09-13 00:05:49.762  1018  1130 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-13 00:05:49.762  1018  1130 E ConnectivityService: updateNetworkInfo()
09-13 00:05:49.762  1018  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-13 00:05:49.772  1018  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
09-13 00:05:49.772  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-13 00:05:49.772  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-13 00:05:49.772  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-13 00:05:49.772  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:05:49.772  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:05:49.772  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:05:49.772  1018  4259 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-13 00:05:49.772  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:05:49.772  1018  4259 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-13 00:05:49.772  1018  4259 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:49.772  1018  4259 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-13 00:05:49.772  1018  4259 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-13 00:05:49.772  1635  1635 I Hs20UtilService: Starting #14
09-13 00:05:49.772  1635  1663 I Hs20UtilService: Message received 5007
,09-13 00:05:49.772  4836  4836 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-13 00:05:49.772  4836  4836 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-13 00:05:49.772  4836  4836 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-13 00:05:49.772  4836  4836 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-13 00:05:49.772  4836  4836 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-13 00:05:49.772  4836  4836 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-13 00:05:49.772  4836  4878 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-13 00:05:49.782  1018  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 00:05:49.792   279  1017 D CommandListener: Setting iface cfg
09-13 00:05:49.792  1018  1128 E WifiStateMachine: Start Dhcp Watchdog 2
09-13 00:05:49.792  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-13 00:05:49.792  1018  1128 D SecContentProvider2: mCursor = null
,09-13 00:05:49.802  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-13 00:05:49.802  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-13 00:05:49.802  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-13 00:05:49.802  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 00:05:49.802  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 00:05:49.802  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:05:49.802  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 00:05:49.812  1018  1128 E WifiNative-wlan0: do suspend false,
,09-13 00:05:49.812  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-13 00:05:49.812  1018  1128 D SecContentProvider2: mCursor = null
09-13 00:05:49.812  1018  1127 D WifiP2pService: InactiveState{ what=143375 }
,09-13 00:05:49.812  1018  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-13 00:05:49.882  1018  1223 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-13 00:05:49.882  1018  1223 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-13 00:05:49.882  1018  1223 D SecContentProvider2: mCursor = null
,09-13 00:05:49.892  1018  1223 D WifiService: setWifiEnabled: false pid=7018, uid=10170
,09-13 00:05:49.892  1018  1223 D SettingsProvider: name = wifi_on
,09-13 00:05:49.902  1018  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 00:05:49.922  1018  1128 E WifiNative-wlan0: do suspend true,
,09-13 00:05:49.952  1018  1127 D WifiP2pService: InactiveState{ what=143375 },
09-13 00:05:49.952  1018  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-13 00:05:49.952   279  1017 D CommandListener: Clearing all IP addresses on wlan0
,09-13 00:05:49.952  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-13 00:05:49.952  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-13 00:05:49.952  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-13 00:05:49.952  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:05:49.952  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 00:05:49.952  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:05:49.952  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 00:05:49.962  1018  1130 E ConnectivityService: updateNetworkInfo()
09-13 00:05:49.962  1018  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 00:05:49.962  1018  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
,09-13 00:05:49.962   279  1017 E Netd    : no such netId 503
,09-13 00:05:49.962  1018  1130 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '79 network destroy 503' failed with '400 79 destroyNetwork() failed (Machine is not on the network)'
,09-13 00:05:49.962  1018  1130 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,09-13 00:05:49.962  1018  1130 V NetworkStats: updateIfacesLocked()
09-13 00:05:49.962  1018  1130 V NetworkStats: performPollLocked(flags=0x1)
09-13 00:05:49.962  1018  1130 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 00:05:49.962  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-13 00:05:49.962  1018  1130 D NetworkStatsFactory: UpdateStatsForKnox updated
09-13 00:05:49.962  1018  1130 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-13 00:05:49.962  1018  1130 V NetworkStats: performPollLocked() took 4ms
09-13 00:05:49.962  1018  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 00:05:49.972  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-13 00:05:49.972  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-13 00:05:49.972  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-13 00:05:49.972  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 00:05:49.972  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:05:49.972  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:05:49.972  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 00:05:49.982  1018  1127 D WifiP2pService: InactiveState{ what=131204 }
,09-13 00:05:49.982  1018  1127 D WifiP2pService: P2pEnabledState{ what=131204 }
,09-13 00:05:49.982  1018  1127 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,09-13 00:05:49.982  1018  1018 D WifiScanningService: SCAN_AVAILABLE : 1
,09-13 00:05:49.982  1018  1018 D RttService: SCAN_AVAILABLE : 1
09-13 00:05:49.982  1018  1152 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:05:49.982  1018  1153 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-13 00:05:49.982  1018  1130 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
09-13 00:05:49.982  1018  1128 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-13 00:05:49.982  1018  7729 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:05:49.982  1018  1130 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-13 00:05:49.982  1018  1130 D ConnectivityService: nai.networkMonitor.doQuit()
09-13 00:05:49.982  1018  1130 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-13 00:05:49.982  1018  1130 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-13 00:05:49.982  1018  1130 E ConnectivityService: updateNetworkInfo()
,09-13 00:05:49.982  1018  7729 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-13 00:05:49.982  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 00:05:49.982  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 00:05:49.992  1018  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 00:05:49.992  1018  1048 D WifiDisplayAdapter: onP2pDisconnected
09-13 00:05:49.992  1018  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-13 00:05:49.992  1018  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-13 00:05:49.992  1018  1127 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-13 00:05:49.992  1018  1130 E ConnectivityService: updateNetworkInfo()
,09-13 00:05:49.992  1018  1018 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-13 00:05:49.992  1018  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-13 00:05:49.992  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-13 00:05:49.992  1018  1048 D WifiDisplayController: disconnect
09-13 00:05:49.992  1018  1048 D WifiDisplayController: updateConnection
09-13 00:05:49.992  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-13 00:05:49.992  1018  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-13 00:05:49.992  1018  1127 D WifiP2pService: P2pDisablingState
,09-13 00:05:49.992  1018  1810 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-13 00:05:49.992  1018  1810 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-13 00:05:49.992  1018  1127 D WifiP2pService: P2pDisablingState{ what=147458 }
09-13 00:05:49.992  1018  1127 D WifiP2pService: p2p socket connection lost
09-13 00:05:50.002  1018  1810 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:50.002  1018  1127 D WifiP2pService: P2pDisabledState
09-13 00:05:50.002  1018  1128 E WifiNative-wlan0: do suspend true
,09-13 00:05:50.002  1018  1810 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:50.002  1018  1810 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-13 00:05:50.002  1635  1635 I Hs20UtilService: Starting #15
,09-13 00:05:50.002  1635  1663 I Hs20UtilService: Message received 5007
,09-13 00:05:50.002  1175  1175 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-13 00:05:50.002  1018  1030 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-13 00:05:50.002  1175  1175 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-13 00:05:50.002  1018  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,09-13 00:05:50.002  1018  1048 D WifiDisplayAdapter: onP2pDisconnected
09-13 00:05:50.002  1018  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-13 00:05:50.002  1018  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-13 00:05:50.012  4836  4836 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-13 00:05:50.012  4836  4836 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-13 00:05:50.012  4836  4836 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-13 00:05:50.012  4836  4836 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-13 00:05:50.012  4836  4836 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-13 00:05:50.012  4836  4836 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-13 00:05:50.012  4836  4878 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-13 00:05:50.032  7732  7732 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
09-13 00:05:50.032  4836  4836 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-13 00:05:50.032  4836  4836 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-13 00:05:50.032  4836  4836 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-13 00:05:50.032  1018  1127 D WifiP2pService: P2pDisabledState{ what=143375 }
,09-13 00:05:50.032  1018  1127 D WifiP2pService: DefaultState{ what=143375 }
,09-13 00:05:50.032  7732  7732 I dhcpcd  : version 5.5.6 starting
,09-13 00:05:50.042   279  1017 D CommandListener: Clearing all IP addresses on wlan0
,09-13 00:05:50.042  4836  4836 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-13 00:05:50.042  4836  4836 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-13 00:05:50.042  4836  4836 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-13 00:05:50.042  4836  4878 V NearbySettings: MountReceiver.mPrefHandler - 7002,
09-13 00:05:50.042  7732  7732 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-13 00:05:50.042  7587  7587 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
09-13 00:05:50.042  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-13 00:05:50.042  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-13 00:05:50.042  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-13 00:05:50.042  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-13 00:05:50.042  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:05:50.042  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:05:50.042  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:05:50.042  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 00:05:50.052  7713  7713 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null,
,09-13 00:05:50.062  7713  7713 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-13 00:05:50.062  7713  7713 D FileShare-Client: Outbound.stopDelayTimer - 
,09-13 00:05:50.062  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
09-13 00:05:50.062  1018  1128 D SecContentProvider2: mCursor = null
,09-13 00:05:50.062  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-13 00:05:50.062  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-13 00:05:50.062  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-13 00:05:50.062  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:05:50.062  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:05:50.062  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:05:50.062  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 00:05:50.072  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-13 00:05:50.072  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-13 00:05:50.072  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-13 00:05:50.072  1175  1799 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-13 00:05:50.072  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-13 00:05:50.072  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:05:50.072  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:05:50.072  1175  1175 D HotspotTile: onReceive : 0, 0
09-13 00:05:50.072  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:05:50.072  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:05:50.072  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-13 00:05:50.072  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,09-13 00:05:50.072  4836  4836 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-13 00:05:50.082  7018  7018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 00:05:50.082  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:05:50.082  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:05:50.082  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:05:50.082  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 00:05:50.082  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 00:05:50.082  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:05:50.082  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:05:50.082  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 00:05:50.082  7018  7018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 00:05:50.082  7018  7018 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 00:05:50.092  7346  7346 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-13 00:05:50.092  7018  7018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 00:05:50.092  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:05:50.092  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:05:50.092  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:05:50.092  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 00:05:50.092  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 00:05:50.092  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:05:50.092  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:05:50.092  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 00:05:50.092  7018  7018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
09-13 00:05:50.092  7018  7018 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 00:05:50.102  1018  1487 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-13 00:05:50.102  1018  1487 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-13 00:05:50.102  1018  1487 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:50.102  1018  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:50.102  1018  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-13 00:05:50.102  1635  1635 I Hs20UtilService: Starting #16
09-13 00:05:50.102  1635  1663 I Hs20UtilService: Message received 5007
09-13 00:05:50.102  4836  4836 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-13 00:05:50.102  4836  4836 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-13 00:05:50.102  4836  4836 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-13 00:05:50.112  4836  4836 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-13 00:05:50.112  4836  4836 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-13 00:05:50.112  4836  4836 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-13 00:05:50.112  4836  4878 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-13 00:05:50.112  7732  7732 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
,09-13 00:05:50.112  7732  7732 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-13 00:05:50.112  7732  7732 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
09-13 00:05:50.112  7732  7732 I dhcpcd  : bssid match
,09-13 00:05:50.112  7732  7732 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
,09-13 00:05:50.122  1018  1472 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-13 00:05:50.122  1018  1472 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-13 00:05:50.122  1018  1472 W ActivityManager: userId = 0, bbcId = -10000
,09-13 00:05:50.122  1018  1472 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:50.122  1018  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-13 00:05:50.122  7385  7385 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-13 00:05:50.122  7385  7385 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-13 00:05:50.122  7385  7385 D SecurityLogAgent: StateMachine : Current State = 1
09-13 00:05:50.132  7385  7385 D SecurityLogAgent: StateMachine : Changed Current State = 1
09-13 00:05:50.132  1635  1635 I Hs20UtilService: Starting #17
,09-13 00:05:50.132  1635  1663 I Hs20UtilService: Message received 5011
,09-13 00:05:50.212  7732  7732 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1,
,09-13 00:05:50.272  7587  7587 I wpa_supplicant: Blacklist: Clear (all) ,
,09-13 00:05:50.342  7732  7732 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds,
09-13 00:05:50.342  7587  7587 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-13 00:05:50.342  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
09-13 00:05:50.342  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-13 00:05:50.342  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,09-13 00:05:50.372  7587  7587 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1,
09-13 00:05:50.372  7587  7587 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-13 00:05:50.372  7587  7587 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-13 00:05:50.372  7587  7587 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-13 00:05:50.372  7587  7587 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-13 00:05:50.372  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
,09-13 00:05:50.372  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,09-13 00:05:50.372  1018  1132 D Tethering: InitialState.processMessage what=4
09-13 00:05:50.372  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-13 00:05:50.372  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-13 00:05:50.372  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,09-13 00:05:50.372  1018  1132 E Tethering: No numeric data
,09-13 00:05:50.372  1018  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-13 00:05:50.372  1018  1132 D Tethering: clearTetheredNotification()
,09-13 00:05:50.382  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-13 00:05:50.382  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 00:05:50.382  1018  1125 V NetworkStats: performPollLocked(flags=0x1)
09-13 00:05:50.382  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-13 00:05:50.392  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
09-13 00:05:50.382  1175  1175 D HotspotTile: updateTetherState():false, false
09-13 00:05:50.392  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-13 00:05:50.392  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-13 00:05:50.392  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,09-13 00:05:50.392  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-13 00:05:50.392  1018  1125 V NetworkStats: performPollLocked() took 7ms
09-13 00:05:50.392  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 00:05:50.392  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 00:05:50.392  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 00:05:50.522  1018  1043 W ActivityManager: mDVFSHelper.release(),
,09-13 00:05:50.612  7587  7587 I wpa_supplicant: Blacklist: Clear (all) ,
,09-13 00:05:50.722  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false,
09-13 00:05:50.722  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
09-13 00:05:50.722  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-13 00:05:50.722  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-13 00:05:50.722  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,09-13 00:05:50.722  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-13 00:05:50.732  7587  7587 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-13 00:05:50.832  1018  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0,
09-13 00:05:50.832  1018  1128 D WifiNative-wlan0: callSECApiBoolean - ID [21]
09-13 00:05:50.842  7362  7362 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 00:05:50.842  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-13 00:05:50.852  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-13 00:05:50.852  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-13 00:05:50.852  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:05:50.852  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:05:50.852  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:05:50.852  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:05:50.852  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-13 00:05:50.852  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
09-13 00:05:50.852  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-13 00:05:50.852  1175  1799 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-13 00:05:50.852  1175  1175 D HotspotTile: onReceive : 1, 0
,09-13 00:05:50.852  4836  4836 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-13 00:05:50.852  1768  2204 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 00:05:50.852  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:05:50.862  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:05:50.862  1018  1223 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-13 00:05:50.862  1018  1223 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-13 00:05:50.862  1018  1223 W ActivityManager: userId = 0, bbcId = -10000
,09-13 00:05:50.862  1018  1223 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-13 00:05:50.862  1018  1223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-13 00:05:50.872  7385  7385 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-13 00:05:50.872  7385  7385 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-13 00:05:50.872  1635  1635 I Hs20UtilService: Starting #18
,09-13 00:05:50.872  1635  1663 I Hs20UtilService: Message received 5011
,09-13 00:05:50.872  7385  7385 D SecurityLogAgent: StateMachine : Current State = 1
,09-13 00:05:50.872  7385  7385 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-13 00:05:51.182   292   292 E SMD     : DCD OFF
,09-13 00:05:51.522   279  1011 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,09-13 00:05:51.522  1018  1045 D Tethering: interfaceRemoved wlan0
,09-13 00:05:51.522  1018  1045 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-13 00:05:51.642  1018  1045 D Tethering: interfaceRemoved p2p0
,09-13 00:05:51.642  1018  1045 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-13 00:05:52.252  1018  1097 V AlarmManager: waitForAlarm result :4
,09-13 00:05:52.252   279  1013 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
09-13 00:05:52.252   279  1013 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,09-13 00:05:52.272  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
,09-13 00:05:52.272  1018  1043 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 00:05:52.272  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,09-13 00:05:52.422  1018  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-13 00:05:52.572  1018  3405 D SSRM:n  : SIOP:: AP = 350,
,09-13 00:05:52.782  1018  3428 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,09-13 00:05:52.902  7018  7244 D BluetoothAdapter: enable()
,09-13 00:05:52.902  1018  1079 W ActivityManager: Permission Denial: getCurrentUser() from pid=7018, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-13 00:05:52.912  1018  1079 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-13 00:05:52.912  1018  1079 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7018, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-13 00:05:52.912  1018  1079 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-13 00:05:52.912  1018  1079 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
09-13 00:05:52.912  1018  1079 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
09-13 00:05:52.912  1018  1079 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
09-13 00:05:52.912  1018  1079 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-13 00:05:52.912  1018  1079 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-13 00:05:52.912  1018  1079 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-13 00:05:52.912  1018  1079 D SettingsProvider: name = bluetooth_on,
,09-13 00:05:52.922  1018  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
09-13 00:05:52.922  1018  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-13 00:05:52.922  1018  1047 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-13 00:05:52.932  3263  3342 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON,
09-13 00:05:52.932  3263  3342 D BluetoothAdapterProperties: Setting state to 11
09-13 00:05:52.932  3263  3342 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-13 00:05:52.932  3263  3342 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-13 00:05:52.932  3263  3342 D BluetoothAdapterService: updateAdapterState state is 11
09-13 00:05:52.932  3263  3342 D BluetoothAdapterService: Autoconnection is available 
09-13 00:05:52.932  3263  3342 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
09-13 00:05:52.932  3263  3342 D BtConfig.SecureMode: isSecureModeOn:false
09-13 00:05:52.932  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-13 00:05:52.932  3263  3342 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
,09-13 00:05:52.932  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-13 00:05:52.932  3263  3342 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
09-13 00:05:52.932  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-13 00:05:52.932  3263  3342 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
09-13 00:05:52.932  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-13 00:05:52.932  3263  3342 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
,09-13 00:05:52.932  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-13 00:05:52.932  3263  3342 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
09-13 00:05:52.932  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-13 00:05:52.932  3263  3342 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
09-13 00:05:52.932  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-13 00:05:52.932  3263  3342 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
09-13 00:05:52.932  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-13 00:05:52.932  3263  3342 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
09-13 00:05:52.932  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-13 00:05:52.932  3263  3342 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-13 00:05:52.932  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-13 00:05:52.932  3263  3342 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-13 00:05:52.932  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-13 00:05:52.932  3263  3342 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-13 00:05:52.932  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-13 00:05:52.932  3263  3342 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
09-13 00:05:52.932  3263  3342 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
09-13 00:05:52.932  3263  3342 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
09-13 00:05:52.932  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-13 00:05:52.932  3263  3342 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-13 00:05:52.932  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-13 00:05:52.932  1018  1018 I InputMethodManagerService: [BT Setting State] State =11
,09-13 00:05:52.942  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-13 00:05:52.952  1886  1886 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
09-13 00:05:52.952  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:05:52.952  1175  1175 D BluetoothTile:  getBluetoothState : 11
,09-13 00:05:52.952  4836  4836 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-13 00:05:52.952  1018  4258 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-13 00:05:52.962  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-13 00:05:52.962  1018  1505 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-13 00:05:52.962  1018  1487 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
09-13 00:05:52.962  1018  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0,
09-13 00:05:52.962  1018  1487 W ActivityManager: userId = 0, bbcId = -10000
,09-13 00:05:52.962  1018  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:52.962  1018  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-13 00:05:52.962  3263  3342 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
09-13 00:05:52.962  1018  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-13 00:05:52.962  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-13 00:05:52.962  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-13 00:05:52.962  3263  3342 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-13 00:05:52.962  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:05:52.962  3263  3263 D HeadsetService: Received start request. Starting profile...
,09-13 00:05:52.962  3263  3263 D HeadsetService: start()
09-13 00:05:52.962  3263  3263 D HeadsetStateMachine: make
09-13 00:05:52.972  1175  1799 D BluetoothTile:  handleUpdatestate:false name:null
09-13 00:05:52.972  1175  1799 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
09-13 00:05:52.972  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:52.972  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:52.972  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 00:05:52.972  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:05:52.972  3263  3263 E HeadsetStateMachine: # of Max HF connection is 2
09-13 00:05:52.972  3263  3342 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
09-13 00:05:52.972  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-13 00:05:52.972  3263  3342 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-13 00:05:52.972  1018  1505 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-13 00:05:52.972  1018  1505 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-13 00:05:52.972  1018  1505 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:52.972  1018  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:52.972  1018  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 00:05:52.982  1695  1695 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 00:05:52.982  3263  3342 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
09-13 00:05:52.982  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-13 00:05:52.982  3263  3342 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-13 00:05:52.982  1018  1505 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,09-13 00:05:52.982  1018  1505 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-13 00:05:52.982  1018  1505 W ActivityManager: userId = 0, bbcId = -10000
,09-13 00:05:52.982  1018  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:52.982  1018  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-13 00:05:52.982  1018  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-13 00:05:52.982  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-13 00:05:52.992  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,09-13 00:05:52.992  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:52.992  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 00:05:52.992  3263  3342 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,09-13 00:05:52.992  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-13 00:05:52.992  3263  3342 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-13 00:05:52.992  1018  4259 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
09-13 00:05:52.992  1018  4259 W ActivityManager: userId = 0, bbcId = -10000,
09-13 00:05:52.992  1018  4259 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-13 00:05:52.992  1018  4259 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:52.992  1018  1331 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
09-13 00:05:52.992  1018  4259 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-13 00:05:52.992  1018  1331 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
09-13 00:05:52.992  3263  3342 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService,
09-13 00:05:52.992  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-13 00:05:52.992  3263  3342 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-13 00:05:53.002  1018  1331 W ActivityManager: userId = 0, bbcId = -10000
,09-13 00:05:53.002  1018  1331 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-13 00:05:53.002  1018  1331 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-13 00:05:53.002  3263  3263 I bluedroid: get_profile_interface handsfree
,09-13 00:05:53.002  1018  1331 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-13 00:05:53.002  1018  1331 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-13 00:05:53.002  1018  1331 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:53.002  1018  1331 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:53.002  1018  1331 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-13 00:05:53.002  4836  4836 D BluetoothNotiBroadcastReceiver: onReceive
,09-13 00:05:53.012  3263  3342 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
09-13 00:05:53.012  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-13 00:05:53.012  3263  3342 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-13 00:05:53.012  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-13 00:05:53.012  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-13 00:05:53.012  1018  1505 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-13 00:05:53.012  1018  1505 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-13 00:05:53.022  1018  1505 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:53.022  1018  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:53.022  1018  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 00:05:53.022  3263  3342 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,09-13 00:05:53.022  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-13 00:05:53.022  3263  3342 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-13 00:05:53.022  3263  3342 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-13 00:05:53.022  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-13 00:05:53.022  3263  3342 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-13 00:05:53.022  3263  3342 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
09-13 00:05:53.022  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-13 00:05:53.022  3263  3342 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-13 00:05:53.022  3263  3342 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
09-13 00:05:53.022  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-13 00:05:53.022  3263  3342 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-13 00:05:53.022  3263  3342 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-13 00:05:53.022  3263  3263 E DualScoManager: Dual Sco Manager already instantiated
09-13 00:05:53.022  1018  4258 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
09-13 00:05:53.022  3263  3263 I DualScoManager: Set HeadsetServiceHelper
09-13 00:05:53.022  3263  3263 D BluetoothAtMessage: createCMTIContentObservers
,09-13 00:05:53.022  1018  4259 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
09-13 00:05:53.022  1018  4259 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-13 00:05:53.022  1018  4259 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-13 00:05:53.022  1018  4259 D SettingsProvider: selectionArgs: false
09-13 00:05:53.022  1018  4259 D SettingsProvider: selectionArgs: 1002
09-13 00:05:53.022  1018  4259 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-13 00:05:53.022  1018  4259 D SettingsProvider: ret = -1
,09-13 00:05:53.022  3263  7766 D HeadsetStateMachine: Enter Disconnected: -2
09-13 00:05:53.022  1018  4258 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:05:53.022  1018  4258 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:53.022  1018  4258 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:53.022  1018  4258 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:05:53.032  7767  7767 E Zygote  : MountEmulatedStorage()
09-13 00:05:53.032  7767  7767 I libpersona: KNOX_SDCARD checking this for 10055
09-13 00:05:53.032  7767  7767 E Zygote  : v2
09-13 00:05:53.032  7767  7767 I libpersona: KNOX_SDCARD not a persona
09-13 00:05:53.042  1018  4258 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7767 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,09-13 00:05:53.042  7767  7767 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 00:05:53.042  3263  3263 D HeadsetService: mStartError = false
09-13 00:05:53.042  3263  3263 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4aba78f
,09-13 00:05:53.042  3263  3263 D A2dpService: Received start request. Starting profile...
,09-13 00:05:53.042  3263  3263 D A2dpService: start()
09-13 00:05:53.042  3263  3263 I bluedroid: get_profile_interface avrcp
,09-13 00:05:53.042  3263  7766 D HeadsetStateMachine: Clear mHeadsetBrsf
,09-13 00:05:53.042  3263  7766 D HeadsetStateMachine: map size, before remove : 0
09-13 00:05:53.042  3263  7766 D HeadsetStateMachine: map size, after remove: 0
,09-13 00:05:53.042  7767  7767 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 00:05:53.042  7767  7767 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-13 00:05:53.052  3263  3263 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-13 00:05:53.052  3263  3263 D Avrcp   : Initialize Media Controller
09-13 00:05:53.052  3263  3263 D Avrcp   : Get the Context Package Name: com.android.bluetooth
09-13 00:05:53.052  3263  3263 E Avrcp   : getActiveSessions
09-13 00:05:53.052  3263  3263 D Avrcp   : pick active media Controller,
09-13 00:05:53.052  3263  3263 D Avrcp   : Get the active Media Controller 
,09-13 00:05:53.052  3263  3263 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-13 00:05:53.052  3263  7773 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-13 00:05:53.062  3263  3263 D A2dpStateMachine: make
,09-13 00:05:53.062  3263  3263 I bluedroid: get_profile_interface a2dp
09-13 00:05:53.062  3263  7779 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-13 00:05:53.062  3263  3263 E bt-btif : warning : media task started media_task_refcnt 1 
09-13 00:05:53.062  3263  3263 D A2dpService: mStartError = false
09-13 00:05:53.062  3263  3263 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4aba78f
09-13 00:05:53.062  3263  3263 D HidService: Received start request. Starting profile...
09-13 00:05:53.062  3263  3263 D HidService: start()
09-13 00:05:53.062  3263  3263 I bluedroid: get_profile_interface hidhost
09-13 00:05:53.062  3263  3263 D HidService: setHidService(): set to: null
09-13 00:05:53.062  3263  3263 D HidService: mStartError = false
09-13 00:05:53.062  3263  3263 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4aba78f
09-13 00:05:53.062  3263  3263 D HeadsetStateMachine: Try to query the phonestate on bind
09-13 00:05:53.062  1429  1439 I Telecom : BluetoothPhoneService: queryPhoneState
09-13 00:05:53.062  3263  7777 D A2dpStateMachine: Enter Disconnected: -2
09-13 00:05:53.062  1429  1429 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
09-13 00:05:53.062  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
09-13 00:05:53.062  1429  1439 I Telecom : BluetoothPhoneService: Result of Message : true
09-13 00:05:53.072  3263  3263 D HealthService: Received start request. Starting profile...
09-13 00:05:53.072  3263  3263 D HealthService: start()
,09-13 00:05:53.072  3263  7773 D BluetoothMediaBrowser: no now playing list
09-13 00:05:53.072  3263  7773 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-13 00:05:53.072  3263  3263 I bluedroid: get_profile_interface health
09-13 00:05:53.072  3263  3263 D HealthService: mStartError = false
09-13 00:05:53.072  3263  3263 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4aba78f
,09-13 00:05:53.072  3263  3263 D PanService: Received start request. Starting profile...
09-13 00:05:53.072  3263  3263 D PanService: start()
09-13 00:05:53.072  3263  3263 D BluetoothPanServiceJni: initializeNative(L110): pan
09-13 00:05:53.072  3263  3263 I bluedroid: get_profile_interface pan
09-13 00:05:53.072  3263  3263 D PanService: mStartError = false
09-13 00:05:53.072  3263  3263 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4aba78f
,09-13 00:05:53.072  3263  3263 D HeadsetStateMachine: Proxy object connected
09-13 00:05:53.072  3263  3263 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
09-13 00:05:53.072  3263  7766 D HeadsetStateMachine: Disconnected process message: 11
,09-13 00:05:53.072  3263  3263 D BluetoothMapService: Received start request. Starting profile...
09-13 00:05:53.072  3263  3263 D BluetoothMapService: start()
,09-13 00:05:53.072  3263  3263 D BluetoothMapService: mStartError = false
09-13 00:05:53.072  3263  3263 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4aba78f
09-13 00:05:53.072  3263  3263 D HeadsetPhoneState: sendDeviceDataStateChanged
,09-13 00:05:53.072  3263  3263 D HeadsetPhoneState: Signal level : previous=0 curr=4
09-13 00:05:53.072  7767  7767 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 00:05:53.072  3263  7766 D HeadsetStateMachine: Disconnected process message: 18
,09-13 00:05:53.072  7767  7767 D ActivityThread: Added TimaKeyStore provider
09-13 00:05:53.082  3263  3263 D SapService: Received start request. Starting profile...
09-13 00:05:53.082  3263  3263 D SapService: start()
09-13 00:05:53.082  3263  3263 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-13 00:05:53.082  3263  3263 I bluedroid: get_profile_interface sap
09-13 00:05:53.082  3263  3263 D SapService: mStartError = false
09-13 00:05:53.082  3263  3263 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4aba78f
09-13 00:05:53.082  3263  3263 E BluetoothAdapterService(78358415): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-13 00:05:53.082  3263  3263 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-13 00:05:53.082  3263  3263 E BluetoothAdapterService(78358415): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-13 00:05:53.082  3263  3263 E BluetoothAdapterService(78358415): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-13 00:05:53.082  3263  7766 D HeadsetStateMachine: Disconnected process message: 10
09-13 00:05:53.082  3263  7766 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-13 00:05:53.082  3263  7766 D HeadsetStateMachine: Disconnected process message: 11
,09-13 00:05:53.082  3263  3263 E BluetoothAdapterService(78358415): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-13 00:05:53.082  3263  3263 E BluetoothAdapterService(78358415): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-13 00:05:53.092  3263  3263 E BluetoothAdapterService(78358415): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
09-13 00:05:53.092  3263  3263 E BluetoothAdapterService(78358415): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-13 00:05:53.102  3263  3342 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,09-13 00:05:53.102  3263  3342 I bluedroid: enable
,09-13 00:05:53.102  3263  3345 E bt-btif : Calling BTA_HhEnable
,09-13 00:05:53.102  3263  3345 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
09-13 00:05:53.102  3263  3345 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
09-13 00:05:53.102  3263  3345 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-13 00:05:53.102  3263  3345 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
09-13 00:05:53.102  3263  3345 E BluetoothServiceJni: populateRssiValuesNative
09-13 00:05:53.102  3263  3345 I bluedroid: getModelRssiValues
,09-13 00:05:53.102  3263  3345 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,09-13 00:05:53.102  3263  3345 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-13 00:05:53.112  3263  3345 D BluetoothAdapterProperties: Name is: Galaxy A3
,09-13 00:05:53.112  1018  1018 D SettingsProvider: name = bluetooth_name
,09-13 00:05:53.112  3263  3345 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-13 00:05:53.112  3263  3345 D BluetoothAdapterProperties: Scan Mode:20
09-13 00:05:53.112  3263  3345 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 00:05:53.112  3263  3345 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
09-13 00:05:53.112  3263  3345 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
09-13 00:05:53.112  3263  3345 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
09-13 00:05:53.112  3263  3345 E bt-btif : btif_sock_init: !radio_req && !rfc_init
09-13 00:05:53.112  3263  3345 E bt-btif : JVenable fails
,09-13 00:05:53.112  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:05:53.112  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:05:53.122  3263  3345 D bte_conf: Device ID record 1 : primary
,09-13 00:05:53.122  3263  3345 D bte_conf:   vendorId            = 0075
09-13 00:05:53.122  3263  3345 D bte_conf:   vendorIdSource      = 0001
,09-13 00:05:53.122  3263  3345 D bte_conf:   product             = 0100
,09-13 00:05:53.122  3263  3345 D bte_conf:   version             = 0200
09-13 00:05:53.122  3263  3345 D bte_conf:   clientExecutableURL = 
09-13 00:05:53.122  7767  7767 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
09-13 00:05:53.122  3263  3345 D bte_conf:   serviceDescription  = 
,09-13 00:05:53.122  3263  3345 D bte_conf:   documentationURL    = 
,09-13 00:05:53.122  3263  3345 D bte_conf: bte_load_did_conf no section named DID2.
,09-13 00:05:53.122  3263  3342 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-13 00:05:53.122  3263  3342 D BluetoothAdapterProperties: ScanMode =  20
09-13 00:05:53.122  3263  3342 D BluetoothAdapterProperties: State =  11
,09-13 00:05:53.122  1018  1079 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-13 00:05:53.122  3263  3342 D BluetoothAdapterProperties: Setting state to 12
09-13 00:05:53.122  3263  3342 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-13 00:05:53.122  3263  3345 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
09-13 00:05:53.122  3263  3345 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-13 00:05:53.132  3263  3345 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-13 00:05:53.132  3263  3345 D BluetoothAdapterProperties: Scan Mode:21
09-13 00:05:53.132  3263  3345 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-13 00:05:53.132  1018  4259 D SettingsProvider: name = bluetooth_a2dp_sink_mode
09-13 00:05:53.132  1018  4259 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-13 00:05:53.132  1018  4259 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-13 00:05:53.132  1018  4259 D SettingsProvider: selectionArgs: false
09-13 00:05:53.132  1018  4259 D SettingsProvider: selectionArgs: 1002
09-13 00:05:53.132  1018  4259 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-13 00:05:53.132  1018  4259 D SettingsProvider: ret = -1
,09-13 00:05:53.132  3263  3342 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-13 00:05:53.132  3263  3342 D BluetoothAdapterService: updateAdapterState state is 12
,09-13 00:05:53.132  1018  4259 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-13 00:05:53.132  1018  4259 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-13 00:05:53.132  1018  4259 W ActivityManager: userId = 0, bbcId = -10000
,09-13 00:05:53.132  1018  4259 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:53.132  1018  4259 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 00:05:53.142  3263  3342 D BluetoothAdapterService: Autoconnection is available ,
09-13 00:05:53.142  3263  3342 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12,
09-13 00:05:53.142  1018  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-13 00:05:53.142  3263  3342 D BluetoothAdapterService: starting service from this receiver
09-13 00:05:53.142  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-13 00:05:53.142  3263  3417 D BluetoothAdapter: onBluetoothStateChange: up=true
09-13 00:05:53.142  3263  3417 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-13 00:05:53.142  3263  3263 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
09-13 00:05:53.142  3263  3263 I BluetoothPbapService: Handler(): got msg=1
09-13 00:05:53.142  1429  1446 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-13 00:05:53.142  1018  1486 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
09-13 00:05:53.142  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:53.142  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:53.142  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 00:05:53.152  3263  3342 I BluetoothAdapterState: Entering On State from state = 11,
09-13 00:05:53.152  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:05:53.152  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:05:53.152  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:05:53.152  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 00:05:53.152  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:05:53.152  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:05:53.152  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:05:53.152  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 00:05:53.152  1018  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-13 00:05:53.152  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-13 00:05:53.152  3263  7789 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-13 00:05:53.152  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:53.152  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:53.152  7767  7767 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
09-13 00:05:53.152  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-13 00:05:53.152  7767  7767 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-13 00:05:53.152  7767  7767 D UserAnalysis: Create SecureDbHelper
,09-13 00:05:53.152  1429  1446 E BluetoothHeadset: BluetoothHeadset service is binded
,09-13 00:05:53.162  7018  7018 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 00:05:53.162  1695  1812 D BluetoothAdapter: onBluetoothStateChange: up=true
09-13 00:05:53.162  1695  1812 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-13 00:05:53.162  4836  4846 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-13 00:05:53.162  3263  7789 D BluetoothSocket: bindListen(): myUserId = 0
09-13 00:05:53.162  3263  7789 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 00:05:53.162  3263  7789 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
09-13 00:05:53.162  3263  7789 D BluetoothSocket: bindListen(), new LocalSocket 
09-13 00:05:53.162  3263  7789 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-13 00:05:53.162  3263  7789 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3ed95f3b
09-13 00:05:53.162  7767  7767 D IntelligenceServiceApplication: onCreate()
09-13 00:05:53.162  3263  7789 D BluetoothSocket: channel: 19
09-13 00:05:53.162  3263  7789 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
09-13 00:05:53.162  4836  4846 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-13 00:05:53.162  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-13 00:05:53.162  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:05:53.162  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:05:53.162  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
,09-13 00:05:53.162  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 00:05:53.162  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:05:53.162  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:05:53.162  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:05:53.162  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 00:05:53.162  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-13 00:05:53.172  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:53.172  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:53.172  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
09-13 00:05:53.172  1175  1190 D BluetoothAdapter: onBluetoothStateChange: up=true
09-13 00:05:53.172  1175  1190 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-13 00:05:53.172  7018  7018 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 00:05:53.172  1460  1479 D BluetoothAdapter: onBluetoothStateChange: up=true
09-13 00:05:53.172  1460  1479 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-13 00:05:53.172  1018  1486 I ActivityManager: Killing 7287:com.google.android.apps.maps/u0a105 (adj 15): empty #21
09-13 00:05:53.172  7767  7767 D IntelligenceServiceApplication: no applications having user consent for prediction
,09-13 00:05:53.172  4836  4848 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-13 00:05:53.182  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
09-13 00:05:53.182  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-13 00:05:53.182  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:53.182  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:53.182  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-13 00:05:53.182  1018  1487 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-13 00:05:53.182  1018  1047 D BluetoothPan: Binding service...
09-13 00:05:53.182  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-13 00:05:53.182  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-13 00:05:53.182  7767  7767 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,09-13 00:05:53.182  4836  4846 D BluetoothPbap: onBluetoothStateChange: up=true
,09-13 00:05:53.192  4836  4836 D BluetoothA2dp: Proxy object connected
09-13 00:05:53.192  4836  4836 D A2dpProfile: Bluetooth service connected
,09-13 00:05:53.192  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-13 00:05:53.192  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-13 00:05:53.192  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:53.192  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:53.192  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-13 00:05:53.192  1018  1018 D BluetoothPan: BluetoothPAN Proxy object connected
,09-13 00:05:53.192  1018  1047 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 00:05:53.192  1018  1047 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-13 00:05:53.192  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-13 00:05:53.192  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-13 00:05:53.192  4836  4848 D BluetoothAdapter: onBluetoothStateChange: up=true
09-13 00:05:53.192  4836  4848 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-13 00:05:53.192  1018  1047 D BluetoothAdapter: onBluetoothStateChange: up=true
09-13 00:05:53.192  1018  1047 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-13 00:05:53.192  4836  4836 D BluetoothInputDevice: Proxy object connected
09-13 00:05:53.192  1018  1018 D BluetoothA2dp: Proxy object connected
09-13 00:05:53.192  4836  4836 D HidProfile: Bluetooth service connected
,09-13 00:05:53.192  4836  7791 D Bluetoothsap: onBluetoothStateChange: up=true
09-13 00:05:53.192  4836  7791 D Bluetoothsap: Binding service...
,09-13 00:05:53.202  4836  4836 D BluetoothPbap: Proxy object connected
09-13 00:05:53.202  4836  4836 D PbapServerProfile: Bluetooth service connected
,09-13 00:05:53.202  7767  7767 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-13 00:05:53.202  4836  7791 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-13 00:05:53.202  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,09-13 00:05:53.202  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-13 00:05:53.202  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,09-13 00:05:53.202  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:53.202  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-13 00:05:53.202  4836  7791 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-13 00:05:53.202  1768  1973 D BluetoothAdapter: onBluetoothStateChange: up=true
09-13 00:05:53.202  1768  1973 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-13 00:05:53.202  7018  7032 D BluetoothAdapter: onBluetoothStateChange: up=true
09-13 00:05:53.202  7018  7032 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-13 00:05:53.202  4836  4836 D Bluetoothsap: BluetoothSAP Proxy object connected
,09-13 00:05:53.202  4836  4836 D SapProfile: Bluetooth service connected
09-13 00:05:53.202  4836  4836 D Bluetoothsap: getConnectedDevices()
,09-13 00:05:53.202  1429  1446 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-13 00:05:53.212  1018  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-13 00:05:53.212  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-13 00:05:53.212   323   323 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 00:05:53.212  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:53.212  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:53.212  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
09-13 00:05:53.212  1429  1446 E BluetoothHeadset: BluetoothHeadset service is binded
,09-13 00:05:53.212  4836  4846 D BluetoothMap: onBluetoothStateChange: up=true
,09-13 00:05:53.212  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
09-13 00:05:53.212  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-13 00:05:53.212  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:53.212  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:53.212  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-13 00:05:53.212  1429  1446 D BluetoothAdapter: onBluetoothStateChange: up=true
09-13 00:05:53.212  1429  1446 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-13 00:05:53.212  4836  4836 D BluetoothMap: Proxy object connected
09-13 00:05:53.212  4836  4836 D MapProfile: Bluetooth service connected
09-13 00:05:53.212  4836  4836 D BluetoothMap: getConnectedDevices()
,09-13 00:05:53.212  1429  1439 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-13 00:05:53.222  1018  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-13 00:05:53.222  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-13 00:05:53.222  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:53.222  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:53.222  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-13 00:05:53.222  1429  1439 E BluetoothHeadset: BluetoothHeadset service is binded
,09-13 00:05:53.222  1460  1644 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-13 00:05:53.222  1018  1047 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-13 00:05:53.222  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-13 00:05:53.222  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:53.222  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:53.222  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-13 00:05:53.222  1460  1644 E BluetoothHeadset: BluetoothHeadset service is binded
09-13 00:05:53.222  1018  1047 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-13 00:05:53.222  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-13 00:05:53.222  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-13 00:05:53.222  1018  1047 E BluetoothHeadset: BluetoothHeadset service is binded
09-13 00:05:53.222  1018  1047 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-13 00:05:53.232  1018  1047 E BluetoothManagerService: Unable to call onBluetoothStateChange() on callback #21
09-13 00:05:53.232  1018  1047 E BluetoothManagerService: android.os.TransactionTooLargeException
09-13 00:05:53.232  1018  1047 E BluetoothManagerService: 	at android.os.BinderProxy.transactNative(Native Method)
09-13 00:05:53.232  1018  1047 E BluetoothManagerService: 	at android.os.BinderProxy.transact(Binder.java:496)
09-13 00:05:53.232  1018  1047 E BluetoothManagerService: 	at android.bluetooth.IBluetoothStateChangeCallback$Stub$Proxy.onBluetoothStateChange(IBluetoothStateChangeCallback.java:84)
09-13 00:05:53.232  1018  1047 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.sendBluetoothStateCallback(BluetoothManagerService.java:1053)
09-13 00:05:53.232  1018  1047 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.bluetoothStateChangeHandler(BluetoothManagerService.java:2007)
09-13 00:05:53.232  1018  1047 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.access$3900(BluetoothManagerService.java:105)
09-13 00:05:53.232  1018  1047 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService$BluetoothHandler.handleMessage(BluetoothManagerService.java:1576)
09-13 00:05:53.232  1018  1047 E BluetoothManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:05:53.232  1018  1047 E BluetoothManagerService: 	at android.os.Looper.loop(Looper.java:145)
09-13 00:05:53.232  1018  1047 E BluetoothManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 00:05:53.232  1018  1047 E BluetoothManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-13 00:05:53.232  4836  4848 D BluetoothPan: Binding service...
,09-13 00:05:53.232  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,09-13 00:05:53.232  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-13 00:05:53.232  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,09-13 00:05:53.232  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:53.232  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-13 00:05:53.232  4836  4836 D BluetoothPan: BluetoothPAN Proxy object connected
,09-13 00:05:53.242  4836  4836 D PanProfile: Bluetooth service connected
,09-13 00:05:53.242  1447  1464 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-13 00:05:53.242  1447  1464 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-13 00:05:53.242  4836  7791 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-13 00:05:53.242  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-13 00:05:53.242  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-13 00:05:53.242  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:53.242  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-13 00:05:53.242  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-13 00:05:53.242  4836  7791 E BluetoothHeadset: BluetoothHeadset service is binded
,09-13 00:05:53.242  3263  3398 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 00:05:53.242  4836  4836 D HeadsetProfile: Bluetooth service connected
,09-13 00:05:53.242  3263  3398 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-13 00:05:53.242  1018  1047 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-13 00:05:53.242  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-13 00:05:53.252  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:53.252  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:53.252  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 00:05:53.252  3263  3263 D BluetoothA2dp: Proxy object connected
,09-13 00:05:53.252  3263  3263 D BluetoothAdapterService: Bluetooth A2dp source service connected
09-13 00:05:53.252  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-13 00:05:53.252  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-13 00:05:53.252  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-13 00:05:53.252  1018  1018 I InputMethodManagerService: [BT Setting State] State =12
,09-13 00:05:53.252  1018  1018 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-13 00:05:53.252  1429  1429 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@31e6c7b2, true
,09-13 00:05:53.252  1429  1429 D BluetoothHeadset: registerMessageListener
09-13 00:05:53.252  1175  1175 D BluetoothTile:  onBluetoothStateChange:
,09-13 00:05:53.262  1886  1886 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-13 00:05:53.262  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:05:53.262  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:,
09-13 00:05:53.262  1175  1175 D BluetoothTile:  getBluetoothState : 12
,09-13 00:05:53.262  1175  1799 D BluetoothTile:  handleUpdatestate:false name:null
,09-13 00:05:53.262  1175  1799 D BluetoothTile:  handleUpdatestate:false name:null
,09-13 00:05:53.262  4836  4836 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-13 00:05:53.272  1018  1331 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-13 00:05:53.272  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:05:53.272  1018  1489 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-13 00:05:53.272  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-13 00:05:53.272  3263  3416 D HeadsetService: registerMessageListener
,09-13 00:05:53.272  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:05:53.272  3263  3416 D HeadsetService: registerMessageListener
09-13 00:05:53.272  3263  7766 D HeadsetStateMachine: Disconnected process message: 70
,09-13 00:05:53.272  1429  1429 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
,09-13 00:05:53.272  3263  7766 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@17a3a3b1
,09-13 00:05:53.272  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-13 00:05:53.272  3263  7793 D BluetoothMapMasInstance: set MAP SDP message type : 1
09-13 00:05:53.272  1175  1799 D BluetoothTile:  handleUpdatestate:false name:null
,09-13 00:05:53.282  1429  1429 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,09-13 00:05:53.282  1429  1429 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,09-13 00:05:53.282  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-13 00:05:53.282  3263  7793 D BluetoothSocket: bindListen(): myUserId = 0
,09-13 00:05:53.282  3263  7793 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 00:05:53.282  3263  7793 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
09-13 00:05:53.282  3263  7793 D BluetoothSocket: bindListen(), new LocalSocket 
09-13 00:05:53.282  3263  7793 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-13 00:05:53.282  3263  7793 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3872d096
09-13 00:05:53.282  3263  7793 D BluetoothSocket: channel: 5
,09-13 00:05:53.282  3263  7766 D HeadsetStateMachine: Disconnected process message: 9
,09-13 00:05:53.282  3263  7766 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-13 00:05:53.292  4836  4836 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,09-13 00:05:53.292  4836  4836 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
,09-13 00:05:53.292  4836  4836 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-13 00:05:53.292  4836  4836 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-13 00:05:53.292   284   682 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,09-13 00:05:53.292   284   682 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-13 00:05:53.292   284   682 V voice   : voice_set_parameters: exit with code(-2)
,09-13 00:05:53.292   284   682 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-13 00:05:53.292   284   682 V msm8974_platform: platform_set_parameters: exit with code(-2)
,09-13 00:05:53.292   284   682 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-13 00:05:53.292   284   682 V audio_hw_primary: adev_set_parameters: exit
,09-13 00:05:53.292  3263  7766 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-13 00:05:53.302  1018  1505 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:53.302  4836  4836 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-13 00:05:53.302  1018  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:53.302  1018  1505 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-13 00:05:53.302  1018  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
09-13 00:05:53.302  1018  1505 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-13 00:05:53.312  1695  1695 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.,
09-13 00:05:53.312  4836  4836 D DockEventReceiver: finishStartingService: stopping service
,09-13 00:05:53.322  4836  4836 D BluetoothNotiBroadcastReceiver: onReceive
,09-13 00:05:53.322  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-13 00:05:53.322  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-13 00:05:53.332  3263  3263 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4aba78f
,09-13 00:05:53.332  3263  3263 D BtConfig.SecureMode: isSecureModeOn:false
,09-13 00:05:53.332  1018  1487 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-13 00:05:53.332  1018  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-13 00:05:53.332  1018  1487 W ActivityManager: userId = 0, bbcId = -10000
,09-13 00:05:53.332  1018  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:53.332  1018  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 00:05:53.342  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,09-13 00:05:53.342  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:05:53.342  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:53.342  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:05:53.342  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:05:53.352  7796  7796 E Zygote  : MountEmulatedStorage(),
09-13 00:05:53.352  7796  7796 E Zygote  : v2
09-13 00:05:53.352  7796  7796 I libpersona: KNOX_SDCARD checking this for 10105
09-13 00:05:53.352  7796  7796 I libpersona: KNOX_SDCARD not a persona
,09-13 00:05:53.352  7796  7796 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 00:05:53.352  1018  1031 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7796 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
09-13 00:05:53.352  7796  7796 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 00:05:53.352  1018  1331 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
09-13 00:05:53.352  7796  7796 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-13 00:05:53.362  3263  7805 D BluetoothSocket: bindListen(): myUserId = 0
,09-13 00:05:53.362  3263  7805 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 00:05:53.362  3263  7805 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[87]}
09-13 00:05:53.362  3263  7805 D BluetoothSocket: bindListen(), new LocalSocket 
09-13 00:05:53.362  3263  7805 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-13 00:05:53.362  3263  7805 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@23036022
09-13 00:05:53.362  3263  7805 D BluetoothSocket: channel: 12
09-13 00:05:53.372  3263  7805 I BtOppRfcommListener: Accept thread started.
,09-13 00:05:53.382  7796  7796 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 00:05:53.382  7796  7796 D ActivityThread: Added TimaKeyStore provider
,09-13 00:05:53.502   258   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-13 00:05:53.502   258   518 W Vold    : Returning OperationFailed - no handler for errno 0
,09-13 00:05:53.502  7796  7817 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-13 00:05:53.512   258   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-13 00:05:53.512   258   518 W Vold    : Returning OperationFailed - no handler for errno 0
,09-13 00:05:53.512  7796  7817 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-13 00:05:53.722  7796  7796 D StrictMode: StrictMode policy violation; ~duration=196 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at java.io.File.exists(File.java:363)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-13 00:05:53.722  7796  7796 D StrictMode: StrictMode policy violation; ~duration=195 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-13 00:05:53.722  7796  7796 D StrictMode: StrictMode policy violation; ~duration=194 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gm,m.map.m.e.a(PG:1515)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-13 00:05:53.722  7796  7796 D StrictMode: StrictMode policy violation; ~duration=192 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.q.k.a(PG:2107)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.q.e.b(PG:170)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09,-13 00:05:53.722  7796  7796 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-13 00:05:53.722  7796  7796 D StrictMode: StrictMode policy violation; ~duration=189 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.q.k.c(PG:18147)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.q.k.d(PG:583)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.q.e.b(PG:170)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-13 00:05:53.722  7796  7796 D StrictMode: StrictMode policy violation; ~duration=165 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at java.io.File.exists(File.java:363)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-13 00:05:53.722  7796  7796 D StrictMode: StrictMode policy violation; ~duration=164 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at java.io.File.exists(File.java:363)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-13 00:05:53.722  7796  7796 D StrictMode: StrictMode policy violation; ~duration=163 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at java.io.File.lastModified(File.java:571)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 00:05:53.722  7796  7796 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-13 00:05:53.732  1018  1079 I ActivityManager: Killing 7404:com.sec.pcw.device/1000 (adj 15): empty #21
,09-13 00:05:53.782  7796  7821 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-13 00:05:53.822  1018  1079 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 00:05:53.822  1018  1079 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:53.822  1018  1079 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 00:05:53.822  1018  1079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-13 00:05:54.192   292   292 E SMD     : DCD OFF,
,09-13 00:05:54.212   323   323 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 00:05:55.162  1018  4259 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 00:05:55.162  1018  4259 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4286, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-13 00:05:55.162  1018  4259 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-13 00:05:55.162  1018  4259 D BatteryService: stay LED for charging
09-13 00:05:55.172  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-13 00:05:55.162  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
09-13 00:05:55.172  1175  1175 D KeyguardUpdateMonitor: handleBatteryUpdate
09-13 00:05:55.162  1018  1018 I MotionRecognitionService: Plugged
09-13 00:05:55.162  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,09-13 00:05:55.172  1414  1414 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-13 00:05:55.172  1414  1414 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-13 00:05:55.182  3263  3263 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 00:05:55.182  3263  7766 D HeadsetStateMachine: Disconnected process message: 10
,09-13 00:05:55.192  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 00:05:55.192  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-13 00:05:55.192  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 00:05:55.222   323   323 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 00:05:55.932  7018  7244 D BluetoothAdapter: disable()
,09-13 00:05:55.932  1018  1487 D SettingsProvider: name = bluetooth_on
,09-13 00:05:55.952  3263  3342 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,09-13 00:05:55.952  3263  3342 D BluetoothAdapterProperties: Setting state to 13
09-13 00:05:55.952  3263  3342 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-13 00:05:55.952  3263  3342 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-13 00:05:55.952  3263  3342 D BluetoothAdapterService: updateAdapterState state is 13
09-13 00:05:55.952  1018  4258 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-13 00:05:55.952  1018  4258 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-13 00:05:55.952  1018  4258 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:55.952  1018  4258 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
09-13 00:05:55.952  1018  4258 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-13 00:05:55.952  3263  3263 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
09-13 00:05:55.962  3263  3342 D BluetoothAdapterService: Autoconnection is available 
,09-13 00:05:55.962  3263  3342 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-13 00:05:55.962  1018  1486 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
09-13 00:05:55.962  3263  3342 D BluetoothAdapterService: terminating service from this receiver
09-13 00:05:55.962  3263  3263 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2c067ab3, channel: 19, state: LISTENING
09-13 00:05:55.962  3263  3263 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2c067ab3, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3ed95f3b, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1196f870mSocket: android.net.LocalSocket@139a17e9 impl:android.net.LocalSocketImpl@331b5c6e fd:FileDescriptor[80]
,09-13 00:05:55.962  3263  3263 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@139a17e9 impl:android.net.LocalSocketImpl@331b5c6e fd:FileDescriptor[80]
,09-13 00:05:55.962  1018  1486 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:55.962  1018  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:55.962  1018  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 00:05:55.962  3263  3342 D BluetoothAdapterProperties: onBluetoothDisable()
09-13 00:05:55.962  3263  3342 D BluetoothAdapterProperties: mDiscovering is false
09-13 00:05:55.962  1018  1504 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
09-13 00:05:55.962  3263  3342 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-13 00:05:55.972  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-13 00:05:55.972  4836  4836 D BluetoothPbap: Proxy object disconnected
09-13 00:05:55.972  4836  4836 D PbapServerProfile: Bluetooth service disconnected
,09-13 00:05:55.972  1018  1018 I InputMethodManagerService: [BT Setting State] State =13
,09-13 00:05:55.972  3263  3345 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-13 00:05:55.972  3263  3345 D BluetoothAdapterProperties: Scan Mode:20
,09-13 00:05:55.982  1175  1175 D BluetoothTile:  onBluetoothStateChange:
,09-13 00:05:55.982  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-13 00:05:55.982  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:05:55.982  1175  1175 D BluetoothTile:  getBluetoothState : 13
,09-13 00:05:55.982  1175  1799 D BluetoothTile:  handleUpdatestate:false name:null
,09-13 00:05:55.982  1175  1799 D BluetoothTile:  handleUpdatestate:false name:null
,09-13 00:05:55.982  1175  1799 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-13 00:05:55.982  1886  1886 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-13 00:05:55.992  4836  4836 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-13 00:05:55.992  1018  1223 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-13 00:05:55.992  1018  1472 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-13 00:05:55.992  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-13 00:05:55.992  7018  7018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 00:05:55.992  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:05:55.992  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:05:55.992  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:05:55.992  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 00:05:55.992  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 00:05:55.992  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:05:55.992  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:05:55.992  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 00:05:55.992  7018  7018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 00:05:56.002  7018  7018 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 00:05:56.002  7018  7018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 00:05:56.002  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:05:56.002  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:05:56.002  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:05:56.002  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 00:05:56.002  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 00:05:56.002  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:05:56.002  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:05:56.002  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 00:05:56.002  3263  3342 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-13 00:05:56.002  7018  7018 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 00:05:56.002  3263  3342 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,09-13 00:05:56.002  3263  3342 E bt-btif : cmd socket is not created
,09-13 00:05:56.002  3263  3342 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-13 00:05:56.002  3263  3346 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
09-13 00:05:56.002  3263  7805 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-13 00:05:56.002  7018  7018 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 00:05:56.012  4836  4836 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 00:05:56.012  1018  1079 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-13 00:05:56.012  1018  1079 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-13 00:05:56.012  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:05:56.012  3263  3346 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 00:05:56.012  3263  3346 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 00:05:56.012  3263  3346 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 00:05:56.012  3263  3346 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 00:05:56.012  3263  3346 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 00:05:56.012  3263  3346 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 00:05:56.012  1018  1079 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:56.012  1018  1079 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:56.012  1018  1079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-13 00:05:56.012  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:05:56.022  1695  1695 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 00:05:56.022  4836  4836 D DockEventReceiver: finishStartingService: stopping service
,09-13 00:05:56.022  3263  3263 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@194b2b9c, channel: 5, state: LISTENING
,09-13 00:05:56.022  3263  3263 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@194b2b9c, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3872d096, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2f349a5mSocket: android.net.LocalSocket@3ca4d17a impl:android.net.LocalSocketImpl@85c8d2b fd:FileDescriptor[82]
09-13 00:05:56.022  3263  3263 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3ca4d17a impl:android.net.LocalSocketImpl@85c8d2b fd:FileDescriptor[82]
09-13 00:05:56.022  3263  3263 I BtOppRfcommListener: stopping Accept Thread
09-13 00:05:56.022  3263  3263 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1cad6588, channel: 12, state: LISTENING
09-13 00:05:56.022  3263  3263 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1cad6588, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@23036022, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@19f3db21mSocket: android.net.LocalSocket@361e8b46 impl:android.net.LocalSocketImpl@1794d107 fd:FileDescriptor[87]
09-13 00:05:56.022  3263  3263 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@361e8b46 impl:android.net.LocalSocketImpl@1794d107 fd:FileDescriptor[87]
09-13 00:05:56.022  3263  7805 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-13 00:05:56.032  4836  4836 D BluetoothNotiBroadcastReceiver: onReceive
,09-13 00:05:56.032  3263  3263 V BluetoothOppManager: cleanUp...
,09-13 00:05:56.032  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-13 00:05:56.032  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-13 00:05:56.212  3263  3342 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,09-13 00:05:56.212  3263  3342 D BtConfig.SecureMode: isSecureModeOn:false
,09-13 00:05:56.212  3263  3342 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-13 00:05:56.212  3263  3342 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
09-13 00:05:56.212  3263  3342 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
09-13 00:05:56.212  3263  3342 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
09-13 00:05:56.212  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-13 00:05:56.212  3263  3342 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
09-13 00:05:56.212  1018  1810 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-13 00:05:56.212  1018  1810 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-13 00:05:56.212  1018  1810 W ActivityManager: userId = 0, bbcId = -10000
,09-13 00:05:56.212  1018  1810 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-13 00:05:56.212  1018  1810 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 00:05:56.212   323   323 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 00:05:56.212  3263  3342 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
09-13 00:05:56.212  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-13 00:05:56.212  3263  3342 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
09-13 00:05:56.212  1018  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-13 00:05:56.212  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-13 00:05:56.212  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:56.212  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-13 00:05:56.212  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-13 00:05:56.212  3263  3342 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
09-13 00:05:56.212  3263  3263 D HeadsetService: Received stop request...Stopping profile...
09-13 00:05:56.212  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-13 00:05:56.212  3263  3342 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-13 00:05:56.212  1018  1487 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-13 00:05:56.212  1018  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
09-13 00:05:56.222  1018  1487 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:56.222  1018  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:56.222  1018  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 00:05:56.222  3263  3342 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService,
,09-13 00:05:56.222  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-13 00:05:56.222  1018  4259 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-13 00:05:56.222  3263  3342 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService,
09-13 00:05:56.222  1018  4259 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
09-13 00:05:56.222  3263  3263 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4aba78f,
,09-13 00:05:56.222  1018  4259 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:56.222  1018  4259 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:56.222  1018  4259 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 00:05:56.232  3263  3342 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
09-13 00:05:56.232  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-13 00:05:56.232  3263  3342 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-13 00:05:56.232  1018  1018 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-13 00:05:56.232  4836  4836 D HeadsetProfile: Bluetooth service disconnected
,09-13 00:05:56.232  1018  1489 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-13 00:05:56.232  1018  1489 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-13 00:05:56.232  3263  3263 D A2dpService: Received stop request...Stopping profile...
,09-13 00:05:56.232  1018  1489 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:56.232  1018  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:56.232  1018  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 00:05:56.232  3263  3342 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
09-13 00:05:56.232  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-13 00:05:56.232  3263  3342 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
09-13 00:05:56.232  3263  7777 D A2dpStateMachine: Exit Disconnected: -1
,09-13 00:05:56.232  1018  1504 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-13 00:05:56.232  1018  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-13 00:05:56.242  1018  1504 W ActivityManager: userId = 0, bbcId = -10000
,09-13 00:05:56.242  1018  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:56.242  1018  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
09-13 00:05:56.242  3263  3342 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
09-13 00:05:56.242  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-13 00:05:56.242  3263  3342 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
09-13 00:05:56.242  1018  1079 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-13 00:05:56.242  1018  1079 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-13 00:05:56.242  1018  1079 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:05:56.242  3263  3263 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4aba78f
09-13 00:05:56.242  1018  1079 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:05:56.242  1018  1079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 00:05:56.242  3263  3342 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-13 00:05:56.242  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-13 00:05:56.242  3263  3342 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-13 00:05:56.242  3263  3342 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-13 00:05:56.242  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-13 00:05:56.242  3263  3342 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-13 00:05:56.242  3263  3342 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
09-13 00:05:56.242  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-13 00:05:56.242  3263  3342 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-13 00:05:56.242  3263  3342 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
09-13 00:05:56.242  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-13 00:05:56.242  3263  3342 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-13 00:05:56.242  3263  3342 D BluetoothAdapterState: Stopping profile services that were post enabled
,09-13 00:05:56.242  1018  1018 D BluetoothA2dp: Proxy object disconnected
09-13 00:05:56.242  1018  1018 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,09-13 00:05:56.242  3263  3263 D HidService: Received stop request...Stopping profile...
09-13 00:05:56.242  4836  4836 D BluetoothA2dp: Proxy object disconnected
09-13 00:05:56.242  3263  3263 D HidService: Stopping Bluetooth HidService
09-13 00:05:56.242  3263  3263 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-13 00:05:56.242  3263  3263 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-13 00:05:56.242  3263  3263 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-13 00:05:56.242  3263  3263 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4aba78f
,09-13 00:05:56.242  4836  4836 D A2dpProfile: Bluetooth service disconnected
,09-13 00:05:56.242  4836  4836 D BluetoothInputDevice: Proxy object disconnected
,09-13 00:05:56.252  3263  3263 E BluetoothAdapterService(78358415): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-13 00:05:56.252  3263  3263 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-13 00:05:56.252  3263  3263 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-13 00:05:56.252  4836  4836 D HidProfile: Bluetooth service disconnected
,09-13 00:05:56.252  3263  3263 D HealthService: Received stop request...Stopping profile...
09-13 00:05:56.252  3263  3263 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4aba78f
,09-13 00:05:56.252  3263  3263 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-13 00:05:56.252  3263  3263 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-13 00:05:56.252  3263  3263 D PanService: Received stop request...Stopping profile...
,09-13 00:05:56.252  3263  3263 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4aba78f
,09-13 00:05:56.252  1018  1018 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-13 00:05:56.262  3263  3263 D BluetoothMapService: Received stop request...Stopping profile...
,09-13 00:05:56.262  4836  4836 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-13 00:05:56.262  4836  4836 D PanProfile: Bluetooth service disconnected
,09-13 00:05:56.262  3263  3263 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4aba78f
,09-13 00:05:56.262  4836  4836 D BluetoothMap: Proxy object disconnected
,09-13 00:05:56.262  3263  3263 E BluetoothAdapterService(78358415): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
09-13 00:05:56.262  4836  4836 D MapProfile: Bluetooth service disconnected
,09-13 00:05:56.262  3263  3263 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-13 00:05:56.262  3263  3263 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-13 00:05:56.262  3263  3263 D BluetoothA2dp: Proxy object disconnected
09-13 00:05:56.262  3263  3263 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,09-13 00:05:56.262  3263  3263 D SapService: Received stop request...Stopping profile...
09-13 00:05:56.262  3263  3263 D SapService: Stopping Bluetooth SapService
09-13 00:05:56.262  3263  3263 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4aba78f
,09-13 00:05:56.262  3263  7779 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,09-13 00:05:56.262  4836  4836 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-13 00:05:56.262  3263  3263 I GKI_LINUX: GKI_exit_task 2 done
09-13 00:05:56.262  3263  3263 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,09-13 00:05:56.262  3263  3263 E BluetoothAdapterService(78358415): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-13 00:05:56.262  3263  3263 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-13 00:05:56.262  3263  3263 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-13 00:05:56.262  3263  3263 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-13 00:05:56.262  3263  3263 E BluetoothAdapterService(78358415): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-13 00:05:56.262  3263  3263 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-13 00:05:56.262  3263  3263 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-13 00:05:56.262  3263  3263 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-13 00:05:56.262  3263  3263 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-13 00:05:56.262  3263  3263 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 00:05:56.262  3263  3263 E BluetoothAdapterService(78358415): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-13 00:05:56.272  3263  3263 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-13 00:05:56.272  3263  3263 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-13 00:05:56.272  4836  4836 D SapProfile: Bluetooth service disconnected
09-13 00:05:56.272  3263  3263 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-13 00:05:56.272  3263  3263 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-13 00:05:56.272  3263  3263 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-13 00:05:56.272  3263  3263 E BluetoothAdapterService(78358415): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,09-13 00:05:56.272  3263  3263 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,09-13 00:05:56.272  3263  3263 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-13 00:05:56.272  3263  3263 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService,
09-13 00:05:56.272  3263  3263 E BluetoothAdapterService(78358415): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-13 00:05:56.272  3263  3263 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,09-13 00:05:56.272  3263  3263 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-13 00:05:56.272  3263  3263 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,09-13 00:05:56.272  3263  3342 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
09-13 00:05:56.272  3263  3342 D BluetoothAdapterProperties: Setting state to 10
09-13 00:05:56.272  3263  3342 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-13 00:05:56.272  3263  3342 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-13 00:05:56.272  3263  3342 D BluetoothAdapterService: updateAdapterState state is 10
,09-13 00:05:56.272  3263  3342 D BluetoothAdapterService: Autoconnection is available 
09-13 00:05:56.272  3263  3342 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-13 00:05:56.272  3263  3342 I BluetoothAdapterState: Entering OffState
09-13 00:05:56.272  3263  3417 D BluetoothAdapter: onBluetoothStateChange: up=false
09-13 00:05:56.272  3263  3417 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-13 00:05:56.272  1695  1713 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-13 00:05:56.272  1695  1713 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-13 00:05:56.272  4836  4846 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-13 00:05:56.282  1175  1991 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-13 00:05:56.282  1175  1991 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-13 00:05:56.282  1460  1485 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-13 00:05:56.282  1460  1485 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-13 00:05:56.282  4836  4848 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-13 00:05:56.282  4836  7791 D BluetoothPbap: onBluetoothStateChange: up=false
,09-13 00:05:56.282  1018  1047 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-13 00:05:56.282  4836  4846 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-13 00:05:56.282  4836  4846 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-13 00:05:56.282  1018  1047 D BluetoothAdapter: onBluetoothStateChange: up=false
09-13 00:05:56.282  1018  1047 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-13 00:05:56.282  4836  4848 D Bluetoothsap: onBluetoothStateChange: up=false
09-13 00:05:56.282  4836  4848 D Bluetoothsap: Unbinding service...
,09-13 00:05:56.282  1768  1781 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-13 00:05:56.282  1768  1781 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-13 00:05:56.292  7018  7032 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-13 00:05:56.292  7018  7032 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-13 00:05:56.292  7018  7032 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
,09-13 00:05:56.292  7018  7032 D BluetoothLeAdvertiser: Exit stop advertising
09-13 00:05:56.292  7018  7032 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-13 00:05:56.292  7018  7032 D BluetoothLeScanner: Exiting stopAllScan
,09-13 00:05:56.292  4836  7791 D BluetoothMap: onBluetoothStateChange: up=false
,09-13 00:05:56.292  1429  1439 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-13 00:05:56.292  1429  1439 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-13 00:05:56.292  7796  7809 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-13 00:05:56.292  7796  7809 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-13 00:05:56.292  1447  7053 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-13 00:05:56.292  1447  7053 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-13 00:05:56.292  3263  3280 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-13 00:05:56.302  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-13 00:05:56.302  1018  1018 I InputMethodManagerService: [BT Setting State] State =10
,09-13 00:05:56.302  1018  1018 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-13 00:05:56.312  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-13 00:05:56.312  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:05:56.312  1175  1175 D BluetoothTile:  getBluetoothState : 10
,09-13 00:05:56.312  1886  1886 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-13 00:05:56.312  1018  1031 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-13 00:05:56.312  1018  1489 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-13 00:05:56.312  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-13 00:05:56.312  4836  4836 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-13 00:05:56.322  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:05:56.322  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:05:56.322  4836  4836 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 00:05:56.322  1018  1489 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-13 00:05:56.322  1018  1489 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-13 00:05:56.322  1018  1489 W ActivityManager: userId = 0, bbcId = -10000
,09-13 00:05:56.322  1018  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-13 00:05:56.322  1018  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-13 00:05:56.332  1695  1695 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 00:05:56.332  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-13 00:05:56.332  4836  4836 D DockEventReceiver: finishStartingService: stopping service
,09-13 00:05:56.332  4836  4836 D BluetoothNotiBroadcastReceiver: onReceive
,09-13 00:05:56.352  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-13 00:05:56.352  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-13 00:05:57.182   292   292 E SMD     : DCD OFF
,09-13 00:05:57.212   323   323 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 00:05:58.212   323   323 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,09-13 00:05:58.952  7018  7244 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 00:05:58.952  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 00:05:59.462  1018  1097 V AlarmManager: waitForAlarm result :4
,09-13 00:05:59.472   279  1013 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-13 00:05:59.472   279  1013 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,09-13 00:05:59.492  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
,09-13 00:05:59.492  1018  1043 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 00:05:59.492  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,09-13 00:05:59.992  1018  1097 V AlarmManager: waitForAlarm result :8
,09-13 00:06:00.192   292   292 E SMD     : DCD OFF
,09-13 00:06:01.962  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
09-13 00:06:01.962  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@101ec598 added. We now have 6 listener(s)
09-13 00:06:01.962  7018  7244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 00:06:01.962  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 00:06:01.962  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@28dea1f1 added. We now have 7 listener(s)
09-13 00:06:01.962  7018  7244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 00:06:01.962  7018  7244 I System.out: IsBluetoothEnabled
,09-13 00:06:01.962  7018  7244 D BluetoothAdapter: disable()
,09-13 00:06:01.962  1018  4258 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.,
,09-13 00:06:01.972  7018  7244 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-13 00:06:01.972  7018  7244 D BluetoothAdapter: enable()
,09-13 00:06:01.972  1018  1505 W ActivityManager: Permission Denial: getCurrentUser() from pid=7018, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-13 00:06:01.972  1018  1505 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-13 00:06:01.972  1018  1505 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7018, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-13 00:06:01.972  1018  1505 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-13 00:06:01.972  1018  1505 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
09-13 00:06:01.972  1018  1505 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
09-13 00:06:01.972  1018  1505 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
09-13 00:06:01.972  1018  1505 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-13 00:06:01.972  1018  1505 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-13 00:06:01.972  1018  1505 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-13 00:06:01.982  1018  1505 D SettingsProvider: name = bluetooth_on,
,09-13 00:06:01.982  1018  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-13 00:06:01.982  1018  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-13 00:06:01.992  1018  1047 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-13 00:06:01.992  3263  3342 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
09-13 00:06:01.992  3263  3342 D BluetoothAdapterProperties: Setting state to 11
09-13 00:06:01.992  3263  3342 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-13 00:06:01.992  3263  3342 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-13 00:06:01.992  3263  3342 D BluetoothAdapterService: updateAdapterState state is 11
09-13 00:06:01.992  3263  3342 D BluetoothAdapterService: Autoconnection is available 
09-13 00:06:01.992  3263  3342 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
09-13 00:06:01.992  3263  3342 D BtConfig.SecureMode: isSecureModeOn:false
09-13 00:06:01.992  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-13 00:06:01.992  3263  3342 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
09-13 00:06:01.992  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-13 00:06:01.992  3263  3342 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
09-13 00:06:01.992  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-13 00:06:01.992  3263  3342 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
09-13 00:06:01.992  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-13 00:06:01.992  3263  3342 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
09-13 00:06:01.992  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-13 00:06:01.992  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-13 00:06:01.992  1018  1018 I InputMethodManagerService: [BT Setting State] State =11
09-13 00:06:01.992  3263  3342 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
09-13 00:06:01.992  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-13 00:06:01.992  3263  3342 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
09-13 00:06:01.992  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-13 00:06:01.992  3263  3342 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
09-13 00:06:01.992  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-13 00:06:01.992  3263  3342 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
09-13 00:06:01.992  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-13 00:06:01.992  3263  3342 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-13 00:06:01.992  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-13 00:06:01.992  3263  3342 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-13 00:06:01.992  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-13 00:06:01.992  3263  3342 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-13 00:06:01.992  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-13 00:06:01.992  3263  3342 W BluetoothAdapterService: processStart(): removed Cli,ent profile: com.android.bluetooth.hid.HidDevService
09-13 00:06:01.992  3263  3342 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
09-13 00:06:01.992  3263  3342 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
09-13 00:06:01.992  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-13 00:06:01.992  3263  3342 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-13 00:06:02.002  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-13 00:06:02.002  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:06:02.002  1175  1175 D BluetoothTile:  getBluetoothState : 11
,09-13 00:06:02.002  1886  1886 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
09-13 00:06:02.002  1018  1487 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-13 00:06:02.002  4836  4836 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-13 00:06:02.002  1018  1486 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-13 00:06:02.002  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-13 00:06:02.012  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:06:02.012  1018  1489 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-13 00:06:02.012  1018  1489 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
09-13 00:06:02.012  1175  1799 D BluetoothTile:  handleUpdatestate:false name:null
09-13 00:06:02.012  1175  1799 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-13 00:06:02.012  1018  1489 W ActivityManager: userId = 0, bbcId = -10000
,09-13 00:06:02.012  1018  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:06:02.012  1018  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 00:06:02.012  3263  3342 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
09-13 00:06:02.012  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-13 00:06:02.012  3263  3342 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-13 00:06:02.022  1695  1695 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 00:06:02.022  3263  3263 D HeadsetService: Received start request. Starting profile...,
09-13 00:06:02.022  1018  1489 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-13 00:06:02.022  3263  3263 D HeadsetService: start()
09-13 00:06:02.022  1018  1489 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-13 00:06:02.022  3263  3263 D HeadsetStateMachine: make
09-13 00:06:02.022  1018  1489 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:06:02.022  1018  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-13 00:06:02.022  1018  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 00:06:02.022  3263  3342 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
09-13 00:06:02.022  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-13 00:06:02.022  3263  3342 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-13 00:06:02.022  3263  3263 E HeadsetStateMachine: # of Max HF connection is 2
,09-13 00:06:02.032  1018  1489 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-13 00:06:02.032  1018  1489 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-13 00:06:02.032  1018  1489 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:06:02.032  1018  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:06:02.032  1018  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 00:06:02.032  1018  1030 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,09-13 00:06:02.032  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-13 00:06:02.032  3263  3342 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
09-13 00:06:02.032  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:06:02.032  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:06:02.032  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-13 00:06:02.032  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-13 00:06:02.032  3263  3342 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-13 00:06:02.042  1018  1079 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-13 00:06:02.042  1018  1079 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-13 00:06:02.042  1018  1079 W ActivityManager: userId = 0, bbcId = -10000
,09-13 00:06:02.042  1018  1079 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:06:02.042  1018  1079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 00:06:02.042  4836  4836 D BluetoothNotiBroadcastReceiver: onReceive
,09-13 00:06:02.042  1018  1031 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,09-13 00:06:02.042  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-13 00:06:02.052  3263  3342 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
09-13 00:06:02.052  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-13 00:06:02.052  3263  3342 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-13 00:06:02.052  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:06:02.052  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:06:02.052  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-13 00:06:02.052  3263  3263 I bluedroid: get_profile_interface handsfree
,09-13 00:06:02.052  1018  1223 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-13 00:06:02.052  1018  1223 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-13 00:06:02.052  1018  1223 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:06:02.052  1018  1223 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:06:02.052  1018  1223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 00:06:02.052  3263  3342 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,09-13 00:06:02.052  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-13 00:06:02.052  3263  3342 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
09-13 00:06:02.052  1018  1487 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-13 00:06:02.052  1018  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
09-13 00:06:02.062  1018  1487 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:06:02.062  1018  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:06:02.062  1018  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 00:06:02.062  3263  3342 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService,
09-13 00:06:02.062  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-13 00:06:02.062  3263  3342 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-13 00:06:02.062  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:06:02.062  3263  3263 E DualScoManager: Dual Sco Manager already instantiated
09-13 00:06:02.062  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
09-13 00:06:02.062  3263  3263 I DualScoManager: Set HeadsetServiceHelper
09-13 00:06:02.062  3263  3263 D BluetoothAtMessage: createCMTIContentObservers
09-13 00:06:02.062  1018  1504 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
09-13 00:06:02.062  1018  1504 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-13 00:06:02.062  1018  1504 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-13 00:06:02.062  1018  1504 D SettingsProvider: selectionArgs: false
09-13 00:06:02.062  1018  1504 D SettingsProvider: selectionArgs: 1002
09-13 00:06:02.062  1018  1504 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-13 00:06:02.062  1018  1504 D SettingsProvider: ret = -1
,09-13 00:06:02.072  3263  7845 D HeadsetStateMachine: Enter Disconnected: -2
,09-13 00:06:02.072  1018  1505 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-13 00:06:02.072  1018  1505 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-13 00:06:02.072  3263  3263 D HeadsetService: mStartError = false
09-13 00:06:02.072  3263  3263 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4aba78f
09-13 00:06:02.072  1018  1505 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:06:02.072  1018  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
09-13 00:06:02.072  1018  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 00:06:02.072  3263  3342 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-13 00:06:02.072  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-13 00:06:02.072  3263  3342 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-13 00:06:02.072  3263  3342 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
,09-13 00:06:02.072  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-13 00:06:02.072  3263  3342 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-13 00:06:02.072  3263  3342 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
09-13 00:06:02.072  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-13 00:06:02.072  3263  3342 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-13 00:06:02.072  3263  3342 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
09-13 00:06:02.072  3263  3342 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-13 00:06:02.072  3263  3342 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,09-13 00:06:02.072  3263  3342 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-13 00:06:02.082  3263  7845 D HeadsetStateMachine: Clear mHeadsetBrsf
09-13 00:06:02.082  3263  7845 D HeadsetStateMachine: map size, before remove : 0
09-13 00:06:02.082  3263  7845 D HeadsetStateMachine: map size, after remove: 0
09-13 00:06:02.082  3263  3263 D A2dpService: Received start request. Starting profile...
09-13 00:06:02.082  3263  3263 D A2dpService: start()
,09-13 00:06:02.082  3263  3263 I bluedroid: get_profile_interface avrcp
,09-13 00:06:02.082  3263  3263 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-13 00:06:02.082  3263  3263 D Avrcp   : Initialize Media Controller
09-13 00:06:02.082  3263  3263 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,09-13 00:06:02.082  3263  3263 E Avrcp   : getActiveSessions
,09-13 00:06:02.082  3263  3263 D Avrcp   : pick active media Controller
09-13 00:06:02.082  3263  3263 D Avrcp   : Get the active Media Controller 
,09-13 00:06:02.092  3263  3263 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-13 00:06:02.092  3263  3263 D A2dpStateMachine: make
09-13 00:06:02.092  3263  7846 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-13 00:06:02.092  3263  3263 I bluedroid: get_profile_interface a2dp
09-13 00:06:02.092  3263  7848 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-13 00:06:02.092  3263  3263 E bt-btif : warning : media task started media_task_refcnt 1 
09-13 00:06:02.092  3263  3263 D A2dpService: mStartError = false
,09-13 00:06:02.092  3263  3263 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4aba78f
09-13 00:06:02.092  3263  3263 D HeadsetStateMachine: Try to query the phonestate on bind
,09-13 00:06:02.102  3263  7847 D A2dpStateMachine: Enter Disconnected: -2
,09-13 00:06:02.102  1429  1446 I Telecom : BluetoothPhoneService: queryPhoneState
,09-13 00:06:02.102  1429  1429 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
09-13 00:06:02.102  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-13 00:06:02.102  1429  1446 I Telecom : BluetoothPhoneService: Result of Message : true
,09-13 00:06:02.102  3263  3263 D HidService: Received start request. Starting profile...
,09-13 00:06:02.102  3263  3263 D HidService: start()
09-13 00:06:02.102  3263  3263 I bluedroid: get_profile_interface hidhost
09-13 00:06:02.102  3263  3263 D HidService: setHidService(): set to: null
09-13 00:06:02.102  3263  3263 D HidService: mStartError = false
,09-13 00:06:02.102  3263  3263 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4aba78f
09-13 00:06:02.102  3263  3263 D HealthService: Received start request. Starting profile...
09-13 00:06:02.102  3263  3263 D HealthService: start()
,09-13 00:06:02.102  3263  3263 I bluedroid: get_profile_interface health
,09-13 00:06:02.102  3263  3263 D HealthService: mStartError = false
09-13 00:06:02.102  3263  3263 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4aba78f
09-13 00:06:02.102  3263  3263 D HeadsetStateMachine: Proxy object connected
,09-13 00:06:02.102  3263  3263 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
09-13 00:06:02.112  3263  7845 D HeadsetStateMachine: Disconnected process message: 11
,09-13 00:06:02.112  3263  3263 D PanService: Received start request. Starting profile...
09-13 00:06:02.112  3263  3263 D PanService: start()
09-13 00:06:02.112  3263  3263 D BluetoothPanServiceJni: initializeNative(L110): pan
09-13 00:06:02.112  3263  3263 I bluedroid: get_profile_interface pan
09-13 00:06:02.112  3263  3263 D PanService: mStartError = false
09-13 00:06:02.112  3263  3263 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4aba78f
,09-13 00:06:02.112  3263  3263 D BluetoothMapService: Received start request. Starting profile...
09-13 00:06:02.112  3263  3263 D BluetoothMapService: start()
,09-13 00:06:02.112  3263  3263 D BluetoothMapService: mStartError = false
09-13 00:06:02.112  3263  3263 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4aba78f
09-13 00:06:02.112  3263  3263 D HeadsetPhoneState: sendDeviceDataStateChanged
,09-13 00:06:02.112  3263  3263 D HeadsetPhoneState: Signal level : previous=0 curr=4
09-13 00:06:02.112  3263  3263 E BluetoothAdapterService(78358415): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-13 00:06:02.112  3263  7845 D HeadsetStateMachine: Disconnected process message: 18
,09-13 00:06:02.112  3263  3263 D SapService: Received start request. Starting profile...
,09-13 00:06:02.112  3263  3263 D SapService: start()
09-13 00:06:02.112  3263  3263 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-13 00:06:02.112  3263  3263 I bluedroid: get_profile_interface sap
09-13 00:06:02.112  3263  3263 D SapService: mStartError = false
09-13 00:06:02.112  3263  3263 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4aba78f
,09-13 00:06:02.112  3263  3263 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-13 00:06:02.122  3263  7845 D HeadsetStateMachine: Disconnected process message: 10
09-13 00:06:02.122  3263  7845 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-13 00:06:02.122  3263  7845 D HeadsetStateMachine: Disconnected process message: 11
09-13 00:06:02.122  3263  3263 E BluetoothAdapterService(78358415): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-13 00:06:02.122  3263  3263 E BluetoothAdapterService(78358415): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-13 00:06:02.122  3263  3263 E BluetoothAdapterService(78358415): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-13 00:06:02.122  3263  3263 E BluetoothAdapterService(78358415): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-13 00:06:02.132  3263  7846 D BluetoothMediaBrowser: no now playing list
,09-13 00:06:02.132  3263  7846 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-13 00:06:02.142  3263  3263 E BluetoothAdapterService(78358415): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,09-13 00:06:02.142  3263  3263 E BluetoothAdapterService(78358415): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-13 00:06:02.142  3263  3342 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,09-13 00:06:02.142  3263  3342 I bluedroid: enable
,09-13 00:06:02.152  3263  3345 E bt-btif : Calling BTA_HhEnable
09-13 00:06:02.152  3263  3345 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
09-13 00:06:02.152  3263  3345 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
09-13 00:06:02.152  3263  3345 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
09-13 00:06:02.152  3263  3345 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
09-13 00:06:02.152  3263  3345 E BluetoothServiceJni: populateRssiValuesNative
09-13 00:06:02.152  3263  3345 I bluedroid: getModelRssiValues
09-13 00:06:02.152  3263  3345 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-13 00:06:02.152  3263  3345 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-13 00:06:02.152  3263  3345 D BluetoothAdapterProperties: Name is: Galaxy A3
,09-13 00:06:02.152  1018  1018 D SettingsProvider: name = bluetooth_name
,09-13 00:06:02.152  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:06:02.162  3263  3345 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-13 00:06:02.162  3263  3345 D BluetoothAdapterProperties: Scan Mode:20
09-13 00:06:02.162  3263  3345 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-13 00:06:02.162  3263  3345 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
09-13 00:06:02.162  3263  3345 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
09-13 00:06:02.162  3263  3345 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
09-13 00:06:02.162  3263  3345 E bt-btif : btif_sock_init: !radio_req && !rfc_init
09-13 00:06:02.162  3263  3345 E bt-btif : JVenable fails,
09-13 00:06:02.162  3263  3345 D bte_conf: Device ID record 1 : primary
09-13 00:06:02.162  3263  3345 D bte_conf:   vendorId            = 0075
,09-13 00:06:02.162  3263  3345 D bte_conf:   vendorIdSource      = 0001
09-13 00:06:02.162  3263  3345 D bte_conf:   product             = 0100
09-13 00:06:02.162  3263  3345 D bte_conf:   version             = 0200
09-13 00:06:02.162  3263  3345 D bte_conf:   clientExecutableURL = 
09-13 00:06:02.162  3263  3345 D bte_conf:   serviceDescription  = 
09-13 00:06:02.162  3263  3345 D bte_conf:   documentationURL    = 
,09-13 00:06:02.162  3263  3345 D bte_conf: bte_load_did_conf no section named DID2.
09-13 00:06:02.162  3263  3345 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,09-13 00:06:02.162  3263  3345 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-13 00:06:02.162  3263  3342 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-13 00:06:02.162  3263  3342 D BluetoothAdapterProperties: ScanMode =  20
09-13 00:06:02.162  3263  3342 D BluetoothAdapterProperties: State =  11
,09-13 00:06:02.162  1018  1030 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-13 00:06:02.162  3263  3342 D BluetoothAdapterProperties: Setting state to 12
,09-13 00:06:02.162  3263  3342 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-13 00:06:02.162  3263  3345 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-13 00:06:02.162  3263  3345 D BluetoothAdapterProperties: Scan Mode:21
09-13 00:06:02.162  3263  3345 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-13 00:06:02.172  1018  1487 D SettingsProvider: name = bluetooth_a2dp_sink_mode
09-13 00:06:02.172  1018  1487 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-13 00:06:02.172  1018  1487 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-13 00:06:02.172  1018  1487 D SettingsProvider: selectionArgs: false
09-13 00:06:02.172  1018  1487 D SettingsProvider: selectionArgs: 1002
09-13 00:06:02.172  1018  1487 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-13 00:06:02.172  1018  1487 D SettingsProvider: ret = -1
,09-13 00:06:02.172  3263  3342 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-13 00:06:02.172  3263  3342 D BluetoothAdapterService: updateAdapterState state is 12
,09-13 00:06:02.172  1018  1487 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-13 00:06:02.172  1018  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-13 00:06:02.172  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:06:02.172  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:06:02.172  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:06:02.172  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 00:06:02.172  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:06:02.172  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:06:02.172  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:06:02.172  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 00:06:02.172  1018  1487 W ActivityManager: userId = 0, bbcId = -10000
,09-13 00:06:02.172  1018  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-13 00:06:02.172  1018  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 00:06:02.182  3263  3342 D BluetoothAdapterService: Autoconnection is available 
09-13 00:06:02.182  3263  3342 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-13 00:06:02.182  3263  3342 D BluetoothAdapterService: starting service from this receiver
09-13 00:06:02.182  3263  3280 D BluetoothAdapter: onBluetoothStateChange: up=true
09-13 00:06:02.182  3263  3280 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-13 00:06:02.182  1018  1331 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-13 00:06:02.182  1018  1331 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-13 00:06:02.182  1018  1331 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:06:02.182  1018  1331 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:06:02.182  1018  1331 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 00:06:02.182  3263  3342 I BluetoothAdapterState: Entering On State from state = 11
,09-13 00:06:02.182  3263  3263 I BluetoothPbapService: Handler(): got msg=1
,09-13 00:06:02.182  1429  7792 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-13 00:06:02.192  1018  1505 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-13 00:06:02.192  1018  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-13 00:06:02.192  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-13 00:06:02.192  7018  7018 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 00:06:02.192  3263  3263 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-13 00:06:02.192  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,09-13 00:06:02.192  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-13 00:06:02.192  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-13 00:06:02.202  1429  7792 E BluetoothHeadset: BluetoothHeadset service is binded
,09-13 00:06:02.202  1695  1713 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-13 00:06:02.202  1695  1713 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-13 00:06:02.202  4836  4848 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-13 00:06:02.202  3263  7853 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-13 00:06:02.202  4836  4848 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-13 00:06:02.212  3263  7853 D BluetoothSocket: bindListen(): myUserId = 0
,09-13 00:06:02.212  3263  7853 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 00:06:02.212  3263  7853 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
09-13 00:06:02.212  3263  7853 D BluetoothSocket: bindListen(), new LocalSocket 
09-13 00:06:02.212  3263  7853 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-13 00:06:02.212  3263  7853 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@11df43df
09-13 00:06:02.212  3263  7853 D BluetoothSocket: channel: 19
,09-13 00:06:02.212  3263  7853 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,09-13 00:06:02.352  1018  1047 I art     : Explicit concurrent mark sweep GC freed 52447(2MB) AllocSpace objects, 7(113KB) LOS objects, 33% free, 22MB/34MB, paused 2.306ms total 141.005ms,
09-13 00:06:02.352  1018  1047 W ActivityManager: userId = 0, bbcId = -10000,
09-13 00:06:02.352  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-13 00:06:02.352  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-13 00:06:02.352  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-13 00:06:02.352  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
09-13 00:06:02.352  1175  3340 D BluetoothAdapter: onBluetoothStateChange: up=true
09-13 00:06:02.352  1175  3340 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-13 00:06:02.352  1460  2580 D BluetoothAdapter: onBluetoothStateChange: up=true
09-13 00:06:02.352  1460  2580 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-13 00:06:02.352  4836  4836 D BluetoothA2dp: Proxy object connected
09-13 00:06:02.352  4836  7791 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-13 00:06:02.352  4836  4836 D A2dpProfile: Bluetooth service connected
,09-13 00:06:02.352  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
09-13 00:06:02.352  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-13 00:06:02.352  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:06:02.352  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:06:02.352  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-13 00:06:02.362  1018  1047 D BluetoothPan: Binding service...
,09-13 00:06:02.362  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-13 00:06:02.362  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-13 00:06:02.362  4836  7791 D BluetoothPbap: onBluetoothStateChange: up=true
,09-13 00:06:02.362  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-13 00:06:02.362  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-13 00:06:02.362  4836  4836 D BluetoothInputDevice: Proxy object connected,
09-13 00:06:02.362  4836  4836 D HidProfile: Bluetooth service connected
09-13 00:06:02.362  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:06:02.362  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:06:02.362  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth,
09-13 00:06:02.362  1018  1018 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 00:06:02.362  1018  1047 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 00:06:02.362  1018  1047 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-13 00:06:02.362  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-13 00:06:02.362  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-13 00:06:02.362  4836  4848 D BluetoothAdapter: onBluetoothStateChange: up=true
09-13 00:06:02.362  4836  4848 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-13 00:06:02.362  1018  1018 D BluetoothA2dp: Proxy object connected
09-13 00:06:02.362  1018  1047 D BluetoothAdapter: onBluetoothStateChange: up=true
09-13 00:06:02.362  1018  1047 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-13 00:06:02.362  4836  4836 D BluetoothPbap: Proxy object connected
09-13 00:06:02.362  4836  7791 D Bluetoothsap: onBluetoothStateChange: up=true
09-13 00:06:02.362  4836  7791 D Bluetoothsap: Binding service...
09-13 00:06:02.362  4836  4836 D PbapServerProfile: Bluetooth service connected
,09-13 00:06:02.362  4836  7791 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-13 00:06:02.362  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
09-13 00:06:02.362  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-13 00:06:02.372  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:06:02.372  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:06:02.372  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-13 00:06:02.372  4836  7791 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-13 00:06:02.372  1768  1973 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-13 00:06:02.372  4836  4836 D Bluetoothsap: BluetoothSAP Proxy object connected
09-13 00:06:02.372  1768  1973 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-13 00:06:02.372  4836  4836 D SapProfile: Bluetooth service connected
09-13 00:06:02.372  4836  4836 D Bluetoothsap: getConnectedDevices()
,09-13 00:06:02.372  7018  7026 D BluetoothAdapter: onBluetoothStateChange: up=true
09-13 00:06:02.372  7018  7026 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-13 00:06:02.372  1429  1439 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-13 00:06:02.372  1018  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-13 00:06:02.372  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-13 00:06:02.372  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:06:02.372  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:06:02.372  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-13 00:06:02.372  1429  1439 E BluetoothHeadset: BluetoothHeadset service is binded
,09-13 00:06:02.372  4836  4846 D BluetoothMap: onBluetoothStateChange: up=true
,09-13 00:06:02.372  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,09-13 00:06:02.372  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-13 00:06:02.382  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,09-13 00:06:02.382  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:06:02.382  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-13 00:06:02.382  1429  7834 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-13 00:06:02.382  1429  7834 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-13 00:06:02.382  4836  4836 D BluetoothMap: Proxy object connected
09-13 00:06:02.382  4836  4836 D MapProfile: Bluetooth service connected
09-13 00:06:02.382  4836  4836 D BluetoothMap: getConnectedDevices()
,09-13 00:06:02.382  1429  7792 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-13 00:06:02.382  1018  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-13 00:06:02.382  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-13 00:06:02.382  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:06:02.382  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:06:02.382  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
09-13 00:06:02.382  1429  7792 E BluetoothHeadset: BluetoothHeadset service is binded
,09-13 00:06:02.382  7796  7809 D BluetoothAdapter: onBluetoothStateChange: up=true
09-13 00:06:02.382  7796  7809 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-13 00:06:02.382  1460  1479 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-13 00:06:02.382  1018  1047 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-13 00:06:02.392  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-13 00:06:02.392  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,09-13 00:06:02.392  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:06:02.392  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-13 00:06:02.392  1460  1479 E BluetoothHeadset: BluetoothHeadset service is binded
,09-13 00:06:02.392  1018  1047 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-13 00:06:02.392  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-13 00:06:02.392  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-13 00:06:02.392  1018  1047 E BluetoothHeadset: BluetoothHeadset service is binded
,09-13 00:06:02.392  4836  4848 D BluetoothPan: Binding service...
,09-13 00:06:02.392  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,09-13 00:06:02.392  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-13 00:06:02.392  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,09-13 00:06:02.392  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:06:02.392  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-13 00:06:02.402  4836  4836 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 00:06:02.402  4836  4836 D PanProfile: Bluetooth service connected
,09-13 00:06:02.402  1447  7053 D BluetoothAdapter: onBluetoothStateChange: up=true
09-13 00:06:02.402  1447  7053 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-13 00:06:02.402  4836  7791 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-13 00:06:02.402  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-13 00:06:02.402  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-13 00:06:02.402  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:06:02.402  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:06:02.402  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-13 00:06:02.402  4836  7791 E BluetoothHeadset: BluetoothHeadset service is binded
,09-13 00:06:02.402  3263  3416 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-13 00:06:02.402  4836  4836 D HeadsetProfile: Bluetooth service connected
09-13 00:06:02.402  3263  3416 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-13 00:06:02.402  1018  1047 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-13 00:06:02.402  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-13 00:06:02.402  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:06:02.402  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:06:02.402  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 00:06:02.402  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-13 00:06:02.402  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-13 00:06:02.412  3263  3263 D BluetoothA2dp: Proxy object connected
,09-13 00:06:02.412  3263  3263 D BluetoothAdapterService: Bluetooth A2dp source service connected
,09-13 00:06:02.412  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-13 00:06:02.412  1018  1018 I InputMethodManagerService: [BT Setting State] State =12
09-13 00:06:02.412  1018  1018 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-13 00:06:02.412  1429  1429 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@35c77303, true
,09-13 00:06:02.412  1429  1429 D BluetoothHeadset: registerMessageListener
,09-13 00:06:02.412  1175  1175 D BluetoothTile:  onBluetoothStateChange:
,09-13 00:06:02.422  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-13 00:06:02.422  1175  1799 D BluetoothTile:  handleUpdatestate:false name:null
,09-13 00:06:02.422  1175  1799 D BluetoothTile:  handleUpdatestate:false name:null
,09-13 00:06:02.422  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-13 00:06:02.422  1175  1175 D BluetoothTile:  getBluetoothState : 12
,09-13 00:06:02.422  1175  1799 D BluetoothTile:  handleUpdatestate:false name:null
,09-13 00:06:02.432  1886  1886 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-13 00:06:02.432  1018  1505 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-13 00:06:02.432  1018  1487 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-13 00:06:02.432  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ),
09-13 00:06:02.432  4836  4836 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-13 00:06:02.432  3263  3416 D HeadsetService: registerMessageListener
,09-13 00:06:02.432  3263  3416 D HeadsetService: registerMessageListener
,09-13 00:06:02.432  3263  7845 D HeadsetStateMachine: Disconnected process message: 70
09-13 00:06:02.432  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:06:02.442  3263  7845 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@38082c
,09-13 00:06:02.442  4836  4836 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
09-13 00:06:02.442  1429  1429 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-13 00:06:02.442  4836  4836 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-13 00:06:02.442  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
09-13 00:06:02.442  4836  4836 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-13 00:06:02.442  4836  4836 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-13 00:06:02.442  1429  1429 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,09-13 00:06:02.442  1429  1429 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
09-13 00:06:02.442  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-13 00:06:02.442  3263  7854 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-13 00:06:02.442  3263  7845 D HeadsetStateMachine: Disconnected process message: 9
09-13 00:06:02.442  3263  7845 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-13 00:06:02.452   284   990 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
09-13 00:06:02.452   284   990 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-13 00:06:02.452   284   990 V voice   : voice_set_parameters: exit with code(-2)
09-13 00:06:02.452   284   990 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-13 00:06:02.452   284   990 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-13 00:06:02.452   284   990 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-13 00:06:02.452   284   990 V audio_hw_primary: adev_set_parameters: exit
09-13 00:06:02.452  3263  7845 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-13 00:06:02.452  3263  7854 D BluetoothSocket: bindListen(): myUserId = 0
09-13 00:06:02.452  3263  7854 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 00:06:02.452  3263  7854 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
,09-13 00:06:02.452  3263  7854 D BluetoothSocket: bindListen(), new LocalSocket 
,09-13 00:06:02.452  4836  4836 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 00:06:02.452  1018  1487 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-13 00:06:02.452  1018  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-13 00:06:02.452  3263  7854 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-13 00:06:02.452  3263  7854 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@286112f5
09-13 00:06:02.452  3263  7854 D BluetoothSocket: channel: 5
,09-13 00:06:02.452  1018  1487 W ActivityManager: userId = 0, bbcId = -10000
,09-13 00:06:02.452  1018  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:06:02.452  1018  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-13 00:06:02.462  1695  1695 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 00:06:02.472  4836  4836 D DockEventReceiver: finishStartingService: stopping service
,09-13 00:06:02.472  4836  4836 D BluetoothNotiBroadcastReceiver: onReceive
,09-13 00:06:02.472  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-13 00:06:02.472  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-13 00:06:02.482  3263  3263 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4aba78f
,09-13 00:06:02.482  3263  3263 D BtConfig.SecureMode: isSecureModeOn:false
,09-13 00:06:02.482  1018  1489 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-13 00:06:02.482  1018  1489 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-13 00:06:02.482  1018  1489 W ActivityManager: userId = 0, bbcId = -10000
,09-13 00:06:02.482  1018  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:06:02.482  1018  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 00:06:02.492  1018  1030 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy,
,09-13 00:06:02.502  3263  7859 D BluetoothSocket: bindListen(): myUserId = 0
09-13 00:06:02.502  3263  7859 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 00:06:02.502  3263  7859 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[85]}
09-13 00:06:02.502  3263  7859 D BluetoothSocket: bindListen(), new LocalSocket 
09-13 00:06:02.502  3263  7859 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-13 00:06:02.502  3263  7859 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@24fce971
,09-13 00:06:02.502  3263  7859 D BluetoothSocket: channel: 12
09-13 00:06:02.502  3263  7859 I BtOppRfcommListener: Accept thread started.
,09-13 00:06:02.602  1018  3405 D SSRM:n  : SIOP:: AP = 320
,09-13 00:06:02.992  7018  7244 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:06:02.992  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:06:02.992  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:06:02.992  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 00:06:02.992  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:06:02.992  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:06:02.992  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:06:02.992  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 00:06:02.992  7018  7244 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 00:06:02.992  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 00:06:02.992  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2d8891d6 added. We now have 8 listener(s)
,09-13 00:06:02.992  7018  7244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 00:06:03.002  1018  1810 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-13 00:06:03.002  1018  1810 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-13 00:06:03.002  1018  1810 D SecContentProvider2: mCursor = null
,09-13 00:06:03.002  1018  1810 D WifiService: setWifiEnabled: false pid=7018, uid=10170
,09-13 00:06:03.002  1018  1810 D SettingsProvider: name = wifi_on
,09-13 00:06:03.012  7018  7244 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:06:03.012  1018  1030 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-13 00:06:03.012  1018  1030 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-13 00:06:03.012  1018  1030 D SecContentProvider2: mCursor = null
,09-13 00:06:03.012  1018  1030 D WifiService: setWifiEnabled: true pid=7018, uid=10170
,09-13 00:06:03.012  1018  1030 W ActivityManager: Permission Denial: getCurrentUser() from pid=7018, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-13 00:06:03.012  1018  1030 W WifiService: Failed getting userId using ActivityManagerNative
09-13 00:06:03.012  1018  1030 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7018, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-13 00:06:03.012  1018  1030 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-13 00:06:03.012  1018  1030 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-13 00:06:03.012  1018  1030 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-13 00:06:03.012  1018  1030 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-13 00:06:03.012  1018  1030 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-13 00:06:03.012  1018  1030 D SettingsProvider: name = wifi_on
,09-13 00:06:03.022  1018  1128 E WifiHW  : ##################### set firmware type 0 #####################
,09-13 00:06:03.182   292   292 E SMD     : DCD OFF
,09-13 00:06:03.352  1018  1045 D Tethering: interfaceAdded wlan0
,09-13 00:06:03.352  1018  1132 E Tethering: No numeric data
,09-13 00:06:03.362  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 00:06:03.362  1018  1125 V NetworkStats: performPollLocked(flags=0x1)
09-13 00:06:03.362  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
09-13 00:06:03.362  1018  1125 V NetworkStats: performPollLocked() took 5ms
09-13 00:06:03.362  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-13 00:06:03.362  1018  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-13 00:06:03.362  1018  1132 D Tethering: clearTetheredNotification()
09-13 00:06:03.362  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 00:06:03.362  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-13 00:06:03.362  1175  1175 D HotspotTile: updateTetherState():false, false
09-13 00:06:03.372  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 00:06:03.372  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 00:06:03.372  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-13 00:06:03.372  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,09-13 00:06:03.372  1018  1132 D Tethering: InitialState.processMessage what=4
09-13 00:06:03.372  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-13 00:06:03.372  1018  1132 E Tethering: No numeric data
09-13 00:06:03.372  1018  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-13 00:06:03.372  1018  1132 D Tethering: clearTetheredNotification()
09-13 00:06:03.382  1018  1125 V NetworkStats: performPollLocked(flags=0x1)
09-13 00:06:03.382  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 00:06:03.382  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-13 00:06:03.382  1175  1175 D HotspotTile: updateTetherState():false, false
,09-13 00:06:03.382  1018  1045 D Tethering: interfaceAdded p2p0
,09-13 00:06:03.382  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
09-13 00:06:03.382  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-13 00:06:03.382  1018  1045 D Tethering: p2p0 is not a tetherable iface, ignoring
,09-13 00:06:03.392  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false,
09-13 00:06:03.392  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-13 00:06:03.392  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,09-13 00:06:03.392  1018  1125 V NetworkStats: performPollLocked() took 12ms
09-13 00:06:03.392  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 00:06:03.392  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 00:06:03.392  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 00:06:03.392   279  1017 I WifiHW  : wifi_change_fw_path(): fwpath = sta,
09-13 00:06:03.392   279  1017 D SoftapController: Softap fwReload - Ok
,09-13 00:06:03.402   279  1017 D CommandListener: Setting iface cfg,
09-13 00:06:03.402   279  1017 D CommandListener: Trying to bring down wlan0
,09-13 00:06:03.402   279  1017 D CommandListener: Clearing all IP addresses on wlan0
,09-13 00:06:03.402  1018  1128 E WifiHW  : supplicant_name : p2p_supplicant,
,09-13 00:06:03.412  1018  1128 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
09-13 00:06:03.412  1018  1128 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,09-13 00:06:03.422  4836  4836 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-13 00:06:03.422  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:06:03.422  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
09-13 00:06:03.422  1018  4258 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-13 00:06:03.422  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-13 00:06:03.422  1018  4258 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-13 00:06:03.422  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-13 00:06:03.422  1175  1799 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-13 00:06:03.422  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:06:03.422  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:06:03.422  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:06:03.422  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-13 00:06:03.422  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-13 00:06:03.422  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
09-13 00:06:03.422  1018  4258 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:06:03.422  1018  4258 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:06:03.422  1018  4258 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-13 00:06:03.422  1635  1635 I Hs20UtilService: Starting #19
09-13 00:06:03.422  1635  1663 I Hs20UtilService: Message received 5011
,09-13 00:06:03.422  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-13 00:06:03.432  1175  1175 D HotspotTile: onReceive : 2, 0
,09-13 00:06:03.432  7385  7385 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-13 00:06:03.432  7385  7385 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-13 00:06:03.432  7385  7385 D SecurityLogAgent: StateMachine : Current State = 1
09-13 00:06:03.432  7385  7385 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-13 00:06:03.462  7870  7870 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-13 00:06:03.462  7870  7870 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-13 00:06:03.462  7870  7870 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-13 00:06:03.472  7870  7870 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,09-13 00:06:03.472   390   390 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7870,
09-13 00:06:03.472   390   390 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-13 00:06:03.472  7870  7870 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-13 00:06:03.472  7870  7870 I wpa_supplicant: ssSupport state is = 1
09-13 00:06:03.472  7870  7870 I wpa_supplicant: >>>>> GET KEY, IV <<<<<,
09-13 00:06:03.472  7870  7870 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
09-13 00:06:03.472   390   390 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7870
09-13 00:06:03.472   390   390 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,09-13 00:06:03.622   390   390 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,09-13 00:06:03.622  7870  7870 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed,
,09-13 00:06:03.662  7870  7870 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-13 00:06:03.662  7870  7870 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-13 00:06:03.672  7870  7870 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-13 00:06:03.672   390   390 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7870
09-13 00:06:03.672   390   390 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-13 00:06:03.672  7870  7870 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
09-13 00:06:03.672  7870  7870 I wpa_supplicant: ssSupport state is = 1
09-13 00:06:03.672  7870  7870 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-13 00:06:03.672  7870  7870 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-13 00:06:03.672  7870  7870 E wpa_supplicant: SIM READ ERROR,
09-13 00:06:03.672  7870  7870 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-13 00:06:03.672  7870  7870 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-13 00:06:03.672  7870  7870 E wpa_supplicant: SIM READ ERROR
09-13 00:06:03.672  7870  7870 I wpa_supplicant: Blacklist: Clear (all) 
09-13 00:06:03.682  7870  7870 I wpa_supplicant: wpa_default_ap_write_once,
09-13 00:06:03.682  7870  7870 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-13 00:06:03.682  7870  7870 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-13 00:06:03.682  7870  7870 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-13 00:06:03.682  7870  7870 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-13 00:06:03.682  7870  7870 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-13 00:06:03.682  7870  7870 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,09-13 00:06:03.682  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-13 00:06:03.682  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
09-13 00:06:03.682  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-13 00:06:03.762  7870  7870 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,09-13 00:06:03.932  7870  7870 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,09-13 00:06:03.932  7870  7870 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,09-13 00:06:03.942  7870  7870 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-13 00:06:03.942   390   390 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7870
09-13 00:06:03.942   390   390 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
09-13 00:06:03.952  7870  7870 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-13 00:06:03.952  7870  7870 I wpa_supplicant: ssSupport state is = 1,
09-13 00:06:03.952  7870  7870 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-13 00:06:03.952  7870  7870 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,09-13 00:06:03.962  7870  7870 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-13 00:06:03.962   390   390 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7870
09-13 00:06:03.962   390   390 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
09-13 00:06:03.962  7870  7870 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-13 00:06:03.962  7870  7870 I wpa_supplicant: ssSupport state is = 1
09-13 00:06:03.962  7870  7870 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
,09-13 00:06:03.962  7870  7870 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-13 00:06:03.972  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
09-13 00:06:03.962  7870  7870 E wpa_supplicant: SIM READ ERROR
09-13 00:06:03.972  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-13 00:06:03.962  7870  7870 I wpa_supplicant: wpa_default_ap_write_once,
09-13 00:06:03.962  7870  7870 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-13 00:06:03.962  7870  7870 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-13 00:06:03.972  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false,
09-13 00:06:03.972  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
09-13 00:06:03.972  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
09-13 00:06:03.972  1018  1045 D Tethering: interfaceStatusChanged p2p0, false,
,09-13 00:06:04.102  7870  7870 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
09-13 00:06:04.102  7870  7870 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-13 00:06:04.202  7870  7870 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,09-13 00:06:04.202  7870  7870 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-13 00:06:04.202  7870  7870 I wpa_supplicant: Skip scan - bUseNetwork false
,09-13 00:06:04.372  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
09-13 00:06:04.372  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-13 00:06:04.372  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,09-13 00:06:04.422  1018  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
09-13 00:06:04.422  1018  1128 D WifiNative-wlan0: callSECApiBoolean - ID [21],
09-13 00:06:04.422  7870  7870 I wpa_supplicant: HOTSPOT20_ENABLE called
09-13 00:06:04.422  7870  7870 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-13 00:06:04.422  7870  7870 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-13 00:06:04.422  7870  7870 E wpa_supplicant: SIM READ ERROR
,09-13 00:06:04.422  7870  7870 I wpa_supplicant: Blacklist: Clear (all) 
,09-13 00:06:04.432  7870  7870 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,09-13 00:06:04.442  7870  7870 I wpa_supplicant: Skip scan - bUseNetwork false
,09-13 00:06:04.442  1018  1128 D WifiConfigStore: Loading config and enabling all networks 
,09-13 00:06:04.452  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
09-13 00:06:04.452  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-13 00:06:04.452  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-13 00:06:04.452  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:06:04.452  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-13 00:06:04.452  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 00:06:04.452  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:06:04.452  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-13 00:06:04.452  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-13 00:06:04.452  1175  1799 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-13 00:06:04.452  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
09-13 00:06:04.452  1175  1175 D HotspotTile: onReceive : 3, 0
09-13 00:06:04.462  4836  4836 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-13 00:06:04.462  1018  1030 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-13 00:06:04.462  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-13 00:06:04.462  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:06:04.462  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:06:04.462  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-13 00:06:04.462  1635  1635 I Hs20UtilService: Starting #20
,09-13 00:06:04.462  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:06:04.462  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:06:04.462  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:06:04.462  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:06:04.462  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:06:04.462  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:06:04.462  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:06:04.462  7018  7018 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 00:06:04.472  1018  1128 E WifiConfigStore: Not a HS20
,09-13 00:06:04.472  7018  7018 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 00:06:04.472  1018  1128 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-13 00:06:04.472  1635  1663 I Hs20UtilService: Message received 5011
,09-13 00:06:04.472  1018  1128 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,09-13 00:06:04.472  7870  7870 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-13 00:06:04.472  7870  7870 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-13 00:06:04.472  7870  7870 I wpa_supplicant: reset timer : RESET_TIMER 0
09-13 00:06:04.472  7870  7870 I wpa_supplicant: P2P: Current p2p state = IDLE
09-13 00:06:04.472  7870  7870 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-13 00:06:04.472  7870  7870 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-13 00:06:04.472  7870  7870 I wpa_supplicant: First Scan Start
,09-13 00:06:04.472  7870  7870 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-13 00:06:04.482  1018  1128 D WifiNative-wlan0: Setting external_sim to 1
,09-13 00:06:04.482  7385  7385 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-13 00:06:04.482  1018  1128 D WifiStateMachine: Setting OUI to DA-A1-19
09-13 00:06:04.482  1018  1128 I WifiNative-HAL: startHal
09-13 00:06:04.482  1018  1128 E wifi    : getStaticLongField sWifiHalHandle 0x9f12988c
09-13 00:06:04.482  1018  1128 I WifiNative-HAL: Could not start hal
,09-13 00:06:04.482  7385  7385 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-13 00:06:04.482  7385  7385 D SecurityLogAgent: StateMachine : Current State = 1
09-13 00:06:04.482  7385  7385 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-13 00:06:04.482  1018  1128 E WifiNative-wlan0: do suspend true
,09-13 00:06:04.482  7362  7362 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 00:06:04.492  1018  1127 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-13 00:06:04.492   279  1017 D CommandListener: Setting iface cfg
09-13 00:06:04.492   279  1017 D CommandListener: Trying to bring up p2p0
,09-13 00:06:04.492  1018  1127 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-13 00:06:04.492  1018  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,09-13 00:06:04.492  1018  1127 D WifiP2pService: P2pEnablingState
,09-13 00:06:04.492  1018  1127 D WifiP2pService: P2pEnablingState{ what=147457 }
,09-13 00:06:04.492  1018  1127 D WifiP2pService: P2p socket connection successful
,09-13 00:06:04.492  1018  1127 D WifiP2pService: P2pEnabledState
,09-13 00:06:04.492  1018  1127 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-13 00:06:04.502  1018  1128 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
,09-13 00:06:04.502  1018  1128 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-13 00:06:04.502  1018  1128 E WifiNative-wlan0: invaild command id : 215
,09-13 00:06:04.502  7870  7870 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-13 00:06:04.502  7870  7870 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-13 00:06:04.502  1018  1130 E ConnectivityService: updateNetworkInfo()
,09-13 00:06:04.512  7870  7870 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,09-13 00:06:04.512  1018  1128 E WifiStateMachine: Failed to set frequency band 0
,09-13 00:06:04.512  1018  1127 D WifiNative-p2p0: p2pGetDeviceAddress
09-13 00:06:04.512  1018  1128 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-13 00:06:04.512  1018  1128 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-13 00:06:04.512  1018  1128 E WifiNative-wlan0: invaild command id : 215
,09-13 00:06:04.512  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-13 00:06:04.512  1018  1128 D SecContentProvider2: mCursor = null
09-13 00:06:04.512  1018  1127 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,09-13 00:06:04.512  1018  1127 D WifiP2pService: DeviceAddress: 0a:75:42
,09-13 00:06:04.512  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-13 00:06:04.512  1018  1128 D SecContentProvider2: mCursor = null
,09-13 00:06:04.522  1018  1018 D WifiScanningService: SCAN_AVAILABLE : 3
,09-13 00:06:04.522  1018  1152 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:04.522  1018  1152 I WifiNative-HAL: startHal
09-13 00:06:04.522  1018  1018 D RttService: SCAN_AVAILABLE : 3
09-13 00:06:04.522  1018  1153 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-13 00:06:04.522  1018  1018 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-13 00:06:04.522  1018  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-13 00:06:04.522  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-13 00:06:04.522  1018  1048 D WifiDisplayController: disconnect
09-13 00:06:04.522  1018  1048 D WifiDisplayController: updateConnection
09-13 00:06:04.522  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-13 00:06:04.522  1018  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-13 00:06:04.532  1018  1152 E wifi    : getStaticLongField sWifiHalHandle 0x9e0e99bc
09-13 00:06:04.532  1018  1152 I WifiNative-HAL: Could not start hal
09-13 00:06:04.532  1018  1152 E WifiScanningService: could not start HAL
,09-13 00:06:04.532  1018  1127 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-13 00:06:04.532  4836  4836 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-13 00:06:04.532  4836  4836 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-13 00:06:04.532  1018  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 00:06:04.532  1018  1048 D WifiDisplayAdapter: onP2pDisconnected
09-13 00:06:04.532  1018  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-13 00:06:04.532  1018  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
09-13 00:06:04.532  1018  1048 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
09-13 00:06:04.532  1018  1048 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
09-13 00:06:04.532  1018  1048 D WifiDisplayController:  primary type: 10-0050F204-5
09-13 00:06:04.532  1018  1048 D WifiDisplayController:  secondary type: null
09-13 00:06:04.532  1018  1048 D WifiDisplayController:  wps: 0
09-13 00:06:04.532  1018  1048 D WifiDisplayController:  grpcapab: 0
09-13 00:06:04.532  1018  1048 D WifiDisplayController:  devcapab: 0
09-13 00:06:04.532  1018  1048 D WifiDisplayController:  status: 3
09-13 00:06:04.532  1018  1048 D WifiDisplayController:  wfdInfo: null
09-13 00:06:04.532  1018  1048 D WifiDisplayController:  groupownerAddress: null
09-13 00:06:04.532  1018  1048 D WifiDisplayController:  GOdeviceName: null
09-13 00:06:04.532  1018  1048 D WifiDisplayController:  interfaceAddress: 
09-13 00:06:04.532  1018  1048 D WifiDisplayController:  SConnectInfo : null
,09-13 00:06:04.532  4836  4836 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-13 00:06:04.532  1175  1175 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-13 00:06:04.532  1018  1127 D WifiP2pService: InactiveState
,09-13 00:06:04.532  1018  1810 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-13 00:06:04.532  1018  1127 D WifiP2pService: InactiveState{ what=143376 }
09-13 00:06:04.542  4836  4836 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-13 00:06:04.542  4836  4836 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-13 00:06:04.542  1018  1127 D WifiP2pService: P2pEnabledState{ what=143376 }
09-13 00:06:04.542  4836  4836 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-13 00:06:04.542  7870  7870 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-13 00:06:04.542  1175  1175 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
09-13 00:06:04.542  7713  7713 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-13 00:06:04.542  4836  4878 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-13 00:06:04.542  1018  1127 D WifiP2pService: InactiveState{ what=143376 }
,09-13 00:06:04.542  7713  7713 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-13 00:06:04.542  7713  7713 D FileShare-Client: Outbound.stopDelayTimer - 
09-13 00:06:04.542  1018  1127 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-13 00:06:04.542  7346  7346 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-13 00:06:05.032  7018  7244 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 00:06:05.032  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:06:05.032  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:06:05.032  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:06:05.032  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:06:05.032  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:06:05.032  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:06:05.032  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 00:06:05.042  7018  7244 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 00:06:05.042  7018  7244 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-13 00:06:05.042  7018  7244 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-13 00:06:05.042  7018  7244 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3a999295 Bundle[{}]
,09-13 00:06:05.052  7018  7244 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-13 00:06:05.052  7018  7244 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-13 00:06:05.052  7018  7244 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-13 00:06:05.052  7018  7244 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-13 00:06:05.052  7018  7244 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-13 00:06:05.052  7018  7244 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-13 00:06:05.062  7018  7244 I System.out: Running OutgoingSocketThread
,09-13 00:06:05.062  7018  7879 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1419)
,09-13 00:06:05.062  7018  7879 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 40915
,09-13 00:06:05.062  7018  7879 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-13 00:06:05.212  1018  1487 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 00:06:05.212  1018  1487 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4277, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-13 00:06:05.212  1018  1487 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-13 00:06:05.212  1018  1487 D BatteryService: stay LED for charging
,09-13 00:06:05.212  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
09-13 00:06:05.222  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-13 00:06:05.212  1018  1018 I MotionRecognitionService: Plugged,
09-13 00:06:05.222  1175  1175 D KeyguardUpdateMonitor: handleBatteryUpdate
09-13 00:06:05.212  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false,
09-13 00:06:05.222  1414  1414 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-13 00:06:05.222  1414  1414 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-13 00:06:05.232  3263  3263 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 00:06:05.232  3263  7845 D HeadsetStateMachine: Disconnected process message: 10
,09-13 00:06:05.242  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 00:06:05.242  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 00:06:05.242  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 00:06:05.722  7870  7870 I wpa_supplicant: nl80211: Received scan results (19 BSSes)
,09-13 00:06:05.722  7870  7870 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-13 00:06:05.722  7870  7870 I wpa_supplicant: Trying to associate with SSID '4E47373030'
09-13 00:06:05.722  7870  7870 I wpa_supplicant: Trying to associate with  'G700'
09-13 00:06:05.722  7870  7870 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
09-13 00:06:05.722  7870  7870 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
09-13 00:06:05.722  1018  7876 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,09-13 00:06:05.742  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-13 00:06:05.742  1018  1128 D SecContentProvider2: mCursor = null
,09-13 00:06:05.842  7870  7870 E wpa_supplicant: Cmd 35605 not handled
,09-13 00:06:05.842  7870  7870 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-13 00:06:05.842  7870  7870 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,09-13 00:06:05.842  7870  7870 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-13 00:06:05.842  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-13 00:06:05.842  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
09-13 00:06:05.842  7870  7870 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-13 00:06:05.842  7870  7870 I wpa_supplicant: Associated with F4.99.3E
09-13 00:06:05.842  7870  7870 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-13 00:06:05.842  7870  7870 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-13 00:06:05.842  7870  7870 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,09-13 00:06:05.842  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-13 00:06:05.842  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-13 00:06:05.842  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-13 00:06:05.842  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
09-13 00:06:05.842  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-13 00:06:05.842  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, true
09-13 00:06:05.842  1018  1045 D Tethering: interfaceStatusChanged wlan0, true
,09-13 00:06:05.852  7870  7870 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-13 00:06:05.852  7870  7870 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,09-13 00:06:05.852  1018  1132 E Tethering: No numeric data
,09-13 00:06:05.852  1018  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-13 00:06:05.852  1018  1132 D Tethering: clearTetheredNotification()
09-13 00:06:05.852  7870  7870 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
09-13 00:06:05.852  1018  1125 V NetworkStats: performPollLocked(flags=0x1)
,09-13 00:06:05.852  7870  7870 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
09-13 00:06:05.852  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-13 00:06:05.852  7870  7870 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-13 00:06:05.852  1175  1175 D HotspotTile: updateTetherState():false, false
09-13 00:06:05.852  7870  7870 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-13 00:06:05.852  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-13 00:06:05.852  7870  7870 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=],
09-13 00:06:05.852  7870  7870 I wpa_supplicant: Blacklist: Clear (temp) 
09-13 00:06:05.852  7870  7870 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
09-13 00:06:05.852  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, true
09-13 00:06:05.852  1018  1045 D Tethering: interfaceStatusChanged wlan0, true
09-13 00:06:05.852  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 00:06:05.852  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-13 00:06:05.852  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-13 00:06:05.862  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-13 00:06:05.862  1018  1125 V NetworkStats: performPollLocked() took 7ms
09-13 00:06:05.862  1018  1128 D SecContentProvider2: mCursor = null
09-13 00:06:05.862  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit,
,09-13 00:06:05.862  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 00:06:05.862  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 00:06:05.862  1018  1128 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-13 00:06:05.862  1018  1128 E WifiConfigStore: setLastSelectedConfiguration -1
,09-13 00:06:05.872  1018  1128 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,09-13 00:06:05.872  1018  1130 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false,
09-13 00:06:05.872  1018  1130 E ConnectivityService: updateNetworkInfo()
09-13 00:06:05.872  1018  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-13 00:06:05.872  1018  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 00:06:05.882  1018  1810 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-13 00:06:05.882  1018  1810 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-13 00:06:05.882  1018  1810 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:06:05.882  1018  1810 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-13 00:06:05.882  1018  1810 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-13 00:06:05.882  1635  1635 I Hs20UtilService: Starting #21
09-13 00:06:05.882  1635  1663 I Hs20UtilService: Message received 5007
09-13 00:06:05.882  4836  4836 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-13 00:06:05.882  4836  4836 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-13 00:06:05.882  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-13 00:06:05.882  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-13 00:06:05.882  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-13 00:06:05.882  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:06:05.882  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:06:05.882  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:06:05.882  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 00:06:05.882  4836  4836 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-13 00:06:05.892  1018  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 00:06:05.892  4836  4836 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-13 00:06:05.892  4836  4836 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,09-13 00:06:05.892  4836  4836 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-13 00:06:05.892  4836  4878 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-13 00:06:05.902   279  1017 D CommandListener: Setting iface cfg,
,09-13 00:06:05.902  1018  1128 E WifiStateMachine: Start Dhcp Watchdog 3,
,09-13 00:06:05.902  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-13 00:06:05.902  1018  1128 D SecContentProvider2: mCursor = null
,09-13 00:06:05.912  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
,09-13 00:06:05.912  1018  1128 D SecContentProvider2: mCursor = null
,09-13 00:06:05.922  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-13 00:06:05.922  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-13 00:06:05.922  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-13 00:06:05.922  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 00:06:05.922  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 00:06:05.922  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 00:06:05.922  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 00:06:05.932  1018  1128 E WifiNative-wlan0: do suspend false
,09-13 00:06:05.932  1018  1127 D WifiP2pService: InactiveState{ what=143375 }
,09-13 00:06:05.932  1018  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-13 00:06:05.932  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-13 00:06:05.932  1018  1128 D SecContentProvider2: mCursor = null
,09-13 00:06:06.072  7018  7244 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1420)
,09-13 00:06:06.072  7018  7244 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1420)
,09-13 00:06:06.072  7018  7244 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1425)
,09-13 00:06:06.072  7018  7244 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-13 00:06:06.072  7018  7244 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1426)
,09-13 00:06:06.072  7018  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 00:06:06.072  7018  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21197c57 added. We now have 2 listener(s)
,09-13 00:06:06.082  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-13 00:06:06.082  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 00:06:06.082  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 00:06:06.082  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 00:06:06.082  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e06a344 added. We now have 9 listener(s)
,09-13 00:06:06.082  7018  7244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 00:06:06.082  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 00:06:06.092  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 00:06:06.092  7018  7244 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 00:06:06.092  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:06:06.092  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:06:06.092  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:06:06.092  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:06:06.092  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:06:06.092  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:06:06.092  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 00:06:06.092  7018  7244 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 00:06:06.092  7018  7244 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 00:06:06.092  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:06:06.102  7018  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 00:06:06.102  7018  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bd3f562 added. We now have 3 listener(s)
,09-13 00:06:06.102  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:06:06.102  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-13 00:06:06.102  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 00:06:06.102  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 00:06:06.102  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 00:06:06.102  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39cf86f3 added. We now have 10 listener(s)
,09-13 00:06:06.102  7018  7244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 00:06:06.112  7018  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:06:06.112  7018  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 00:06:06.112  7018  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:06:06.112  7018  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 00:06:06.112  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:06.112  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 00:06:06.112  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-13 00:06:06.112  7018  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21197c57 removed from the list,
09-13 00:06:06.112  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:06.112  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e06a344 removed from the list
,09-13 00:06:06.112  7018  7244 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:06:06.112  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 00:06:06.112  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:06.112  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 00:06:06.112  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
09-13 00:06:06.112  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 00:06:06.112  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:06.112  7018  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e06a344 not in the list,
09-13 00:06:06.112  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 00:06:06.112  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 00:06:06.122  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-13 00:06:06.122  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 00:06:06.122  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:06.122  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39cf86f3 removed from the list
09-13 00:06:06.122  7018  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 00:06:06.122  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 00:06:06.122  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:06.122  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-13 00:06:06.122  7018  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bd3f562 removed from the list
,09-13 00:06:06.122  7018  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 00:06:06.122  7018  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b6cafb0 added. We now have 2 listener(s)
,09-13 00:06:06.122  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-13 00:06:06.122  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 00:06:06.122  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 00:06:06.122  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 00:06:06.122  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cee9e29 added. We now have 9 listener(s)
09-13 00:06:06.122  7018  7244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 00:06:06.132  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 00:06:06.132  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 00:06:06.132  7018  7244 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 00:06:06.132  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:06:06.132  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
,09-13 00:06:06.132  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:06:06.132  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:06:06.132  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:06:06.132  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:06:06.132  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 00:06:06.142  7018  7244 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
09-13 00:06:06.142  7018  7244 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 00:06:06.142  7018  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 00:06:06.142  7018  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34d19f4f added. We now have 3 listener(s)
,09-13 00:06:06.142  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41",
,09-13 00:06:06.142  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 00:06:06.142  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 00:06:06.142  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 00:06:06.142  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21e516dc added. We now have 10 listener(s)
09-13 00:06:06.142  7018  7244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
09-13 00:06:06.142  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:06:06.142  7018  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-13 00:06:06.142  7018  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 00:06:06.142  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-13 00:06:06.142  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 00:06:06.142  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 00:06:06.152  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:06:06.152  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 00:06:06.152  7884  7884 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-13 00:06:06.162  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 00:06:06.162  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
09-13 00:06:06.162  7884  7884 I dhcpcd  : version 5.5.6 starting
,09-13 00:06:06.162  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-13 00:06:06.162  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-13 00:06:06.162  7018  7244 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-13 00:06:06.162  7884  7884 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-13 00:06:06.162  3263  3398 D BtGatt.GattService: registerClient() - UUID=263e6c91-f8fb-490a-8ee1-6485c4d01484
,09-13 00:06:06.192   292   292 E SMD     : DCD OFF,
,09-13 00:06:06.202  7884  7884 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
09-13 00:06:06.202  7884  7884 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
,09-13 00:06:06.202  7884  7884 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
09-13 00:06:06.202  7884  7884 I dhcpcd  : bssid match
,09-13 00:06:06.202  7884  7884 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
,09-13 00:06:06.212  3263  3345 D BtGatt.GattService: onClientRegistered() - UUID=263e6c91-f8fb-490a-8ee1-6485c4d01484, clientIf=6,
09-13 00:06:06.212  7018  7026 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-13 00:06:06.212  3263  3417 D BtGatt.GattService: start scan with filters
09-13 00:06:06.212  3263  3401 D BtGatt.ScanManager: handling starting scan
09-13 00:06:06.212  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-13 00:06:06.212  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-13 00:06:06.212  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
09-13 00:06:06.212  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-13 00:06:06.212  3263  3345 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-13 00:06:06.212  3263  3345 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 00:06:06.212  3263  3401 D BtGatt.ScanManager: allow scan with filters,
09-13 00:06:06.212  3263  3401 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-13 00:06:06.212  3263  3401 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
09-13 00:06:06.212  3263  3345 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-13 00:06:06.212  3263  3345 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 00:06:06.212  3263  3401 D BtGatt.ScanManager: Starting BLE batch scan
09-13 00:06:06.212  3263  3401 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-13 00:06:06.222  7018  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 00:06:06.222  7018  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-13 00:06:06.222  7018  7018 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 00:06:06.222  3263  3345 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-13 00:06:06.222  3263  3345 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 00:06:06.222  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 00:06:06.222  3263  3345 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-13 00:06:06.222  3263  3345 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 00:06:06.232  7018  7244 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-13 00:06:06.232  7018  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-13 00:06:06.232  7018  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 00:06:06.232  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:06.232  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 00:06:06.232  7018  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 00:06:06.232  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 00:06:06.232  7018  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 00:06:06.232  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 00:06:06.232  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 00:06:06.232  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-13 00:06:06.232  3263  3280 D BtGatt.GattService: stopScan() - queue size =1
,09-13 00:06:06.232  3263  3401 D BtGatt.ScanManager: filter size is 1
,09-13 00:06:06.232  3263  3401 D BtGatt.ScanManager: delete FilterIndex - 6
,09-13 00:06:06.232  3263  3345 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-13 00:06:06.232  3263  3345 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 00:06:06.232  3263  3417 D BtGatt.GattService: unregisterClient() - clientIf=6
09-13 00:06:06.232  3263  3401 D BtGatt.ScanManager: stopping BLe Batch
,09-13 00:06:06.232  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 00:06:06.232  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 00:06:06.232  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 00:06:06.232  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 00:06:06.232  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-13 00:06:06.232  7018  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 00:06:06.232  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 00:06:06.232  7018  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 00:06:06.232  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 00:06:06.232  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 00:06:06.242  3263  3345 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-13 00:06:06.242  3263  3345 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 00:06:06.242  3263  3401 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-13 00:06:06.242  3263  3345 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
09-13 00:06:06.242  3263  3345 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 00:06:06.242  7018  7018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
09-13 00:06:06.242  7018  7018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 00:06:06.242  7018  7018 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 00:06:06.242  7018  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 00:06:06.242  7018  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:06:06.242  7018  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:06:06.242  7018  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:06:06.242  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:06.242  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 00:06:06.242  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 00:06:06.242  7018  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b6cafb0 removed from the list
09-13 00:06:06.242  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:06.242  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cee9e29 removed from the list
09-13 00:06:06.242  7018  7244 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:06:06.242  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:06.242  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:06.242  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 00:06:06.242  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 00:06:06.242  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:06:06.242  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:06.242  7018  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cee9e29 not in the list
09-13 00:06:06.242  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:06.242  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 00:06:06.242  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 00:06:06.242  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:06:06.242  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:06.242  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21e516dc removed from the list
,09-13 00:06:06.242  7018  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:06:06.242  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:06.242  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:06.252  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 00:06:06.252  7018  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34d19f4f removed from the list
,09-13 00:06:06.252  7018  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 00:06:06.252  7018  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1ac4c8 added. We now have 2 listener(s)
,09-13 00:06:06.252  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-13 00:06:06.252  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 00:06:06.252  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 00:06:06.252  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 00:06:06.252  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@240ae961 added. We now have 9 listener(s)
,09-13 00:06:06.252  7018  7244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 00:06:06.252  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 00:06:06.252  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 00:06:06.262  7018  7244 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 00:06:06.262  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:06:06.262  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:06:06.262  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:06:06.262  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:06:06.262  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:06:06.262  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:06:06.262  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 00:06:06.262  7018  7244 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 00:06:06.262  7018  7244 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 00:06:06.262  7018  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 00:06:06.262  7018  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e1c2947 added. We now have 3 listener(s)
,09-13 00:06:06.262  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:06:06.262  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:06:06.262  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-13 00:06:06.262  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 00:06:06.262  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 00:06:06.262  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 00:06:06.272  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a7b6574 added. We now have 10 listener(s)
09-13 00:06:06.272  7018  7244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 00:06:06.272  7018  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 00:06:06.272  7018  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 00:06:06.272  7018  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-13 00:06:06.272  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 00:06:06.272  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 00:06:06.272  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 00:06:06.272  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 00:06:06.272  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 00:06:06.272  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 00:06:06.282  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-13 00:06:06.282  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-13 00:06:06.282  7018  7244 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-13 00:06:06.282  3263  3398 D BtGatt.GattService: registerClient() - UUID=e10de3b7-9d6e-4289-9b43-51e94b1ca5fc
,09-13 00:06:06.292  7884  7884 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1,
,09-13 00:06:06.332  3263  3345 D BtGatt.GattService: onClientRegistered() - UUID=e10de3b7-9d6e-4289-9b43-51e94b1ca5fc, clientIf=6
,09-13 00:06:06.332  7018  7032 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-13 00:06:06.332  3263  3416 D BtGatt.GattService: start scan with filters
,09-13 00:06:06.332  3263  3401 D BtGatt.ScanManager: handling starting scan
,09-13 00:06:06.332  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-13 00:06:06.332  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-13 00:06:06.332  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-13 00:06:06.332  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-13 00:06:06.332  3263  3345 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-13 00:06:06.332  3263  3345 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 00:06:06.332  3263  3401 D BtGatt.ScanManager: allow scan with filters
,09-13 00:06:06.332  3263  3401 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-13 00:06:06.332  3263  3401 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
,09-13 00:06:06.332  3263  3345 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-13 00:06:06.332  3263  3345 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 00:06:06.332  3263  3401 D BtGatt.ScanManager: Starting BLE batch scan
,09-13 00:06:06.332  3263  3401 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-13 00:06:06.342  7884  7884 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds,
,09-13 00:06:06.342  3263  3345 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
09-13 00:06:06.352  3263  3345 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 00:06:06.352  7018  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
09-13 00:06:06.352  7018  7018 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 00:06:06.352  7018  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 00:06:06.352  3263  3345 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
09-13 00:06:06.352  3263  3345 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 00:06:06.352  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 00:06:06.362  7018  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only,
09-13 00:06:06.362  7018  7244 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-13 00:06:06.362  7018  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:06:06.362  7018  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 00:06:06.362  7018  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:06:06.362  7018  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:06:06.362  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:06.362  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 00:06:06.362  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 00:06:06.362  7018  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1ac4c8 removed from the list
09-13 00:06:06.362  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:06.362  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@240ae961 removed from the list
09-13 00:06:06.362  7018  7244 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 00:06:06.362  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 00:06:06.362  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:06.362  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-13 00:06:06.362  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:06.362  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 00:06:06.372  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
09-13 00:06:06.372  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:06:06.372  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:06.372  7018  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@240ae961 not in the list
09-13 00:06:06.372  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 00:06:06.372  7018  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 00:06:06.372  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 00:06:06.372  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 00:06:06.372  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-13 00:06:06.372  3263  3279 D BtGatt.GattService: stopScan() - queue size =1
,09-13 00:06:06.372  3263  3398 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-13 00:06:06.372  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 00:06:06.372  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 00:06:06.372  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 00:06:06.372  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 00:06:06.372  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-13 00:06:06.372  3263  3401 D BtGatt.ScanManager: filter size is 1
09-13 00:06:06.372  3263  3401 D BtGatt.ScanManager: delete FilterIndex - 7
09-13 00:06:06.372  7018  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 00:06:06.372  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
09-13 00:06:06.372  7018  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-13 00:06:06.372  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 00:06:06.372  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 00:06:06.372  3263  3345 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-13 00:06:06.372  3263  3345 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 00:06:06.372  3263  3401 D BtGatt.ScanManager: stopping BLe Batch
09-13 00:06:06.382  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:06:06.382  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:06:06.382  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:06.382  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a7b6574 removed from the list
09-13 00:06:06.382  7018  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:06:06.382  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:06.382  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:06.382  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 00:06:06.382  7018  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e1c2947 removed from the list
09-13 00:06:06.382  7018  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 00:06:06.382  7018  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a364e0 added. We now have 2 listener(s)
,09-13 00:06:06.382  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-13 00:06:06.382  7018  7018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 00:06:06.382  7018  7018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 00:06:06.382  7018  7018 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 00:06:06.382  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 00:06:06.382  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 00:06:06.382  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 00:06:06.382  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b8e6399 added. We now have 9 listener(s)
09-13 00:06:06.382  7018  7244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 00:06:06.382  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 00:06:06.382  3263  3345 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-13 00:06:06.382  3263  3345 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 00:06:06.382  3263  3401 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-13 00:06:06.392  3263  3345 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-13 00:06:06.392  3263  3345 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 00:06:06.392  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,09-13 00:06:06.412  7018  7244 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 00:06:06.412  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:06:06.412  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:06:06.412  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:06:06.412  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:06:06.412  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null,
09-13 00:06:06.412  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:06:06.412  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 00:06:06.412  7018  7244 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 00:06:06.412  7018  7244 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 00:06:06.412  7018  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 00:06:06.412  7018  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fefa3f added. We now have 3 listener(s)
,09-13 00:06:06.412  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:06:06.412  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 00:06:06.422  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41",
,09-13 00:06:06.432  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
09-13 00:06:06.432  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 00:06:06.432  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 00:06:06.432  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1589ef0c added. We now have 10 listener(s),
,09-13 00:06:06.432  7018  7244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 00:06:06.432  7018  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 00:06:06.432  7018  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 00:06:06.432  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-13 00:06:06.432  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 00:06:06.432  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 00:06:06.442  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 00:06:06.442  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 00:06:06.442  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 00:06:06.452  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
09-13 00:06:06.452  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-13 00:06:06.452  7018  7244 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-13 00:06:06.452  3263  3416 D BtGatt.GattService: registerClient() - UUID=f1776ab8-c79a-4dae-bac8-2a8c847f72ad,
,09-13 00:06:06.492  3263  3345 D BtGatt.GattService: onClientRegistered() - UUID=f1776ab8-c79a-4dae-bac8-2a8c847f72ad, clientIf=6,
09-13 00:06:06.492  7018  7026 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-13 00:06:06.492  3263  3280 D BtGatt.GattService: start scan with filters
09-13 00:06:06.492  3263  3401 D BtGatt.ScanManager: handling starting scan,
09-13 00:06:06.502  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-13 00:06:06.502  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-13 00:06:06.502  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-13 00:06:06.502  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-13 00:06:06.502  3263  3345 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-13 00:06:06.502  3263  3345 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 00:06:06.502  3263  3401 D BtGatt.ScanManager: allow scan with filters
09-13 00:06:06.502  3263  3401 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-13 00:06:06.502  3263  3401 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6
09-13 00:06:06.502  3263  3345 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-13 00:06:06.502  3263  3345 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 00:06:06.502  7018  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 00:06:06.502  7018  7018 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 00:06:06.502  7018  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 00:06:06.502  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
09-13 00:06:06.502  3263  3401 D BtGatt.ScanManager: Starting BLE batch scan
09-13 00:06:06.502  3263  3401 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-13 00:06:06.512  3263  3345 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-13 00:06:06.512  3263  3345 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 00:06:06.512  3263  3345 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-13 00:06:06.512  3263  3345 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 00:06:06.522  7018  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 00:06:06.522  7018  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:06:06.522  7018  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 00:06:06.522  7018  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 00:06:06.522  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:06.522  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 00:06:06.522  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 00:06:06.522  7018  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a364e0 removed from the list
09-13 00:06:06.522  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:06.522  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b8e6399 removed from the list
09-13 00:06:06.522  7018  7244 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 00:06:06.522  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 00:06:06.522  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:06.522  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-13 00:06:06.522  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:06.522  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 00:06:06.522  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:06:06.522  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-13 00:06:06.522  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:06.522  7018  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b8e6399 not in the list
09-13 00:06:06.522  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 00:06:06.522  7018  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 00:06:06.522  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 00:06:06.522  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-13 00:06:06.522  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-13 00:06:06.522  3263  3279 D BtGatt.GattService: stopScan() - queue size =1
,09-13 00:06:06.522  3263  3401 D BtGatt.ScanManager: filter size is 1
,09-13 00:06:06.522  3263  3401 D BtGatt.ScanManager: delete FilterIndex - 8
09-13 00:06:06.522  3263  3398 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-13 00:06:06.522  3263  3345 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-13 00:06:06.522  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 00:06:06.522  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 00:06:06.522  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 00:06:06.522  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 00:06:06.522  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-13 00:06:06.532  3263  3345 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 00:06:06.532  3263  3401 D BtGatt.ScanManager: stopping BLe Batch
,09-13 00:06:06.532  7018  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 00:06:06.532  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 00:06:06.532  7018  7244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 00:06:06.532  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 00:06:06.532  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:06.532  3263  3345 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-13 00:06:06.532  3263  3345 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 00:06:06.532  3263  3401 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-13 00:06:06.532  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 00:06:06.532  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:06:06.532  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:06.532  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1589ef0c removed from the list
09-13 00:06:06.532  7018  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:06:06.532  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:06.532  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:06.532  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 00:06:06.532  7018  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fefa3f removed from the list,
09-13 00:06:06.542  7018  7018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 00:06:06.542  7018  7018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 00:06:06.542  7018  7018 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 00:06:06.542  7018  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 00:06:06.542  7018  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@346ceff8 added. We now have 2 listener(s),
09-13 00:06:06.542  3263  3345 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-13 00:06:06.542  3263  3345 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 00:06:06.542  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41",
09-13 00:06:06.542  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 00:06:06.542  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 00:06:06.542  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 00:06:06.542  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@154fecd1 added. We now have 9 listener(s)
,09-13 00:06:06.542  7018  7244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 00:06:06.542  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 00:06:06.542  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 00:06:06.552  1018  1128 E WifiNative-wlan0: do suspend true,
,09-13 00:06:06.552  7018  7244 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 00:06:06.552  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 00:06:06.552  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 00:06:06.552  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 00:06:06.552  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 00:06:06.552  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 00:06:06.552  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 00:06:06.552  7018  7244 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 00:06:06.552  7018  7244 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 00:06:06.552  7018  7244 D io.jxcore.node.ConnectivityMonitor: start: OK,
09-13 00:06:06.552  7018  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 00:06:06.552  7018  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@245bf237 added. We now have 3 listener(s)
09-13 00:06:06.552  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:06:06.552  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-13 00:06:06.552  7018  7018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 00:06:06.562  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 00:06:06.562  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 00:06:06.562  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 00:06:06.562  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7d13a4 added. We now have 10 listener(s)
09-13 00:06:06.562  7018  7244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 00:06:06.562  7018  7244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 00:06:06.562  7018  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 00:06:06.562  7018  7244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 00:06:06.562  7018  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 00:06:06.562  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:06.562  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 00:06:06.562  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 00:06:06.562  7018  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@346ceff8 removed from the list
09-13 00:06:06.562  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 00:06:06.562  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@154fecd1 removed from the list
09-13 00:06:06.562  7018  7244 D io.jxcore.node.ConnectivityMonitor: stop
09-13 00:06:06.562  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 00:06:06.562  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 00:06:06.562  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 00:06:06.562  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 00:06:06.562  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 00:06:06.562  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:06.562  7018  7244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@154fecd1 not in the list
,09-13 00:06:06.562  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:06.562  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 00:06:06.562  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 00:06:06.562  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 00:06:06.562  7018  7244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 00:06:06.562  7018  7244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7d13a4 removed from the list
,09-13 00:06:06.562  7018  7244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 00:06:06.562  7018  7244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 00:06:06.562  7018  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 00:06:06.572  7018  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 00:06:06.572  7018  7244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@245bf237 removed from the list
,09-13 00:06:06.572  7018  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,09-13 00:06:06.572  7018  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-13 00:06:06.572  7018  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,09-13 00:06:06.572  7018  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 00:06:06.572  7018  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-13 00:06:06.572  7018  7244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-13 00:06:06.572  1018  1127 D WifiP2pService: InactiveState{ what=143375 },
09-13 00:06:06.572  1018  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
09-13 00:06:06.572  1018  1128 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK,
,09-13 00:06:06.572  1018  1128 E WifiStateMachine: VerifyingLinkState enter
09-13 00:06:06.572  7018  7915 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1433, name: My test thread name)
09-13 00:06:06.572  7018  7915 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1433, thread name: My test thread name)
09-13 00:06:06.572  7018  7915 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1433, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-13 00:06:06.582  1018  1130 E ConnectivityService: updateNetworkInfo()
,09-13 00:06:06.582  1018  1130 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,09-13 00:06:06.582  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-13 00:06:06.582  1018  1130 D ConnectivityService: Adding iface wlan0 to network 504
09-13 00:06:06.582  1018  1146 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,09-13 00:06:06.582  1018  1146 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-13 00:06:06.582  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-13 00:06:06.582  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-13 00:06:06.582  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:06:06.582  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:06:06.582  1018  1146 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-13 00:06:06.582  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:06:06.582  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:06:06.582  1018  1146 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-13 00:06:06.582  1018  1146 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-13 00:06:06.592  7018  7917 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1435, name: My test thread name)
,09-13 00:06:06.592  7018  7917 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1435, thread name: My test thread name)
09-13 00:06:06.592  7018  7917 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1435, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-13 00:06:06.592  7018  7244 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-13 00:06:06.592  7018  7244 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-13 00:06:06.592  7018  7244 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-13 00:06:06.592  7018  7244 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-13 00:06:06.592  7018  7244 D com.test.thalitest.ThaliTestRunner: Total duration: 23323 ms
09-13 00:06:06.592  7018  7244 I jxcore-log: *Native tests were executed*
09-13 00:06:06.592  7018  7244 I jxcore-log: 
09-13 00:06:06.592  7018  7244 I jxcore-log: Total number of executed tests:  80
09-13 00:06:06.592  7018  7244 I jxcore-log: 
09-13 00:06:06.592  7018  7244 I jxcore-log: Number of passed tests:  80
09-13 00:06:06.592  7018  7244 I jxcore-log: 
09-13 00:06:06.592  7018  7244 I jxcore-log: Number of failed tests:  0
09-13 00:06:06.592  7018  7244 I jxcore-log: 
09-13 00:06:06.592  7018  7244 I jxcore-log: Number of ignored tests:  0
09-13 00:06:06.592  7018  7244 I jxcore-log: 
09-13 00:06:06.592  7018  7244 I jxcore-log: Total duration:  23323
09-13 00:06:06.592  7018  7244 I jxcore-log: 
09-13 00:06:06.592  7018  7244 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-13 00:06:06.592  7018  7244 I jxcore-log: 
09-13 00:06:06.592  7018  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 00:06:06.592  7018  7244 I jxcore-log: 
,09-13 00:06:06.602  7018  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 00:06:06.602  7018  7244 I jxcore-log: 
09-13 00:06:06.602  7018  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 00:06:06.602  7018  7244 I jxcore-log: 
09-13 00:06:06.602  7018  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 00:06:06.602  7018  7244 I jxcore-log: 
09-13 00:06:06.602  7018  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 00:06:06.602  7018  7244 I jxcore-log: 
09-13 00:06:06.602  7018  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 00:06:06.602  7018  7244 I jxcore-log: 
09-13 00:06:06.602  7018  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 00:06:06.602  7018  7244 I jxcore-log: 
09-13 00:06:06.612  7018  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 00:06:06.612  7018  7244 I jxcore-log: 
,09-13 00:06:06.612  7018  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 00:06:06.612  7018  7244 I jxcore-log: 
09-13 00:06:06.612  7018  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 00:06:06.612  7018  7244 I jxcore-log: 
09-13 00:06:06.612  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-13 00:06:06.612  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-13 00:06:06.612  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-13 00:06:06.612  7018  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 00:06:06.612  7018  7244 I jxcore-log: 
09-13 00:06:06.612  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:06:06.612  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:06:06.612  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:06:06.612  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:06:06.612  7018  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 00:06:06.612  7018  7244 I jxcore-log: 
09-13 00:06:06.612  1018  1128 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
09-13 00:06:06.612  7018  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 00:06:06.612  7018  7244 I jxcore-log: 
09-13 00:06:06.612  7018  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 00:06:06.612  7018  7244 I jxcore-log: 
09-13 00:06:06.612  7018  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 00:06:06.612  7018  7244 I jxcore-log: 
09-13 00:06:06.612  7018  7018 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-13 00:06:06.612  7018  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 00:06:06.612  7018  7244 I jxcore-log: 
09-13 00:06:06.622  7018  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 00:06:06.622  7018  7244 I jxcore-log: 
09-13 00:06:06.622  7018  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 00:06:06.622  7018  7244 I jxcore-log: 
09-13 00:06:06.622  7018  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 00:06:06.622  7018  7244 I jxcore-log: 
,09-13 00:06:06.622  7018  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 00:06:06.622  7018  7244 I jxcore-log: 
,09-13 00:06:06.622  1018  1472 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-13 00:06:06.622  7018  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 00:06:06.622  7018  7244 I jxcore-log: 
09-13 00:06:06.622  1018  1472 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-13 00:06:06.622  1018  1472 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:06:06.622  1018  1472 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:06:06.622  1018  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-13 00:06:06.622  7018  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 00:06:06.622  7018  7244 I jxcore-log: 
09-13 00:06:06.622  7018  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 00:06:06.622  7018  7244 I jxcore-log: 
09-13 00:06:06.622  7018  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 00:06:06.622  7018  7244 I jxcore-log: 
09-13 00:06:06.622  7018  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 00:06:06.622  7018  7244 I jxcore-log: 
,09-13 00:06:06.622  1635  1635 I Hs20UtilService: Starting #22,
09-13 00:06:06.622  7018  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 00:06:06.622  7018  7244 I jxcore-log: 
09-13 00:06:06.622  4836  4836 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-13 00:06:06.622  1635  1663 I Hs20UtilService: Message received 5007
09-13 00:06:06.622  7018  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 00:06:06.622  7018  7244 I jxcore-log: 
09-13 00:06:06.632  1018  1130 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
09-13 00:06:06.632  4836  4836 I NearbySettings: MountReceiver.onReceive - Keep current state
09-13 00:06:06.632  1018  1130 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
09-13 00:06:06.632  1018  1130 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
09-13 00:06:06.632  1018  1130 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-13 00:06:06.632  1018  1130 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
09-13 00:06:06.632  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-13 00:06:06.632  1018  1130 D ConnectivityService: LTETest block dns file not exists
,09-13 00:06:06.642  1018  1128 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-13 00:06:06.642  1018  1128 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-13 00:06:06.642  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-13 00:06:06.642  1018  1018 I WifiTrafficPoller: mBoosterFLAG : 0
09-13 00:06:06.642  1018  1018 I WifiTrafficPoller: current booster mode : FullMode
09-13 00:06:06.642  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-13 00:06:06.642  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-13 00:06:06.642  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-13 00:06:06.642  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:06:06.642  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:06:06.642  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:06:06.642  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 00:06:06.652  1018  1130 V NetworkStats: updateIfacesLocked()
09-13 00:06:06.652  1018  1130 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 00:06:06.652  1018  1130 V NetworkStats: performPollLocked(flags=0x1)
09-13 00:06:06.652  1175  1175 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-13 00:06:06.652  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-13 00:06:06.652  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 00:06:06.652  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:06:06.652  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:06:06.652  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:06:06.652  1018  1130 D NetworkStatsFactory: UpdateStatsForKnox updated
09-13 00:06:06.652  1018  1130 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-13 00:06:06.662  1018  1130 V NetworkStats: performPollLocked() took 10ms
09-13 00:06:06.662  1018  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 00:06:06.662  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 00:06:06.662  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 00:06:06.662  1018  1130 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,09-13 00:06:06.662  1018  1130 E ConnectivityService: updateNetworkInfo()
09-13 00:06:06.662  1018  1130 E ConnectivityService: updateNetworkInfo()
09-13 00:06:06.662  1018  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 00:06:06.662  1018  1130 V NetworkStats: updateIfacesLocked()
09-13 00:06:06.662  1018  1130 V NetworkStats: performPollLocked(flags=0x1)
09-13 00:06:06.662  1018  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 00:06:06.672  1018  1130 D NetworkStatsFactory: UpdateStatsForKnox updated
09-13 00:06:06.672  1018  1130 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-13 00:06:06.672  1018  1489 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-13 00:06:06.672  1018  1489 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-13 00:06:06.672  1018  1489 W ActivityManager: userId = 0, bbcId = -10000
,09-13 00:06:06.672  1018  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:06:06.682  1018  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-13 00:06:06.682  1635  1635 I Hs20UtilService: Starting #23
09-13 00:06:06.682  1018  1130 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 00:06:06.682  1018  1130 V NetworkStats: performPollLocked() took 13ms
09-13 00:06:06.682  4836  4836 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-13 00:06:06.682  4836  4836 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null,
09-13 00:06:06.682  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 00:06:06.682  1018  1130 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504],
09-13 00:06:06.682  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit,
,09-13 00:06:06.682  1018  1130 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504],
09-13 00:06:06.682  1635  1663 I Hs20UtilService: Message received 5007
09-13 00:06:06.682  1018  1130 D ConnectivityService:    accepting network in place of null
09-13 00:06:06.682  4836  4836 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-13 00:06:06.682  1018  1130 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
09-13 00:06:06.682  1018  7881 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:06.682  1018  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-13 00:06:06.682  1018  7881 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
09-13 00:06:06.682  1018  7881 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-13 00:06:06.682  1018  7881 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
09-13 00:06:06.682  1018  1127 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-13 00:06:06.682  1018  7881 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-13 00:06:06.682  1460  1460 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-13 00:06:06.682  1460  1460 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 00:06:06.682  1018  1130 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-13 00:06:06.682   279  1013 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-13 00:06:06.682   279  1013 D Netd    : getNetworkForDns: using netid 504 for uid 1000
09-13 00:06:06.692  1018  1128 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,09-13 00:06:06.692  1018  1130 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
09-13 00:06:06.692  4836  4836 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED,
09-13 00:06:06.692  4836  4836 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-13 00:06:06.692  4836  4836 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-13 00:06:06.692  4836  4878 V NearbySettings: MountReceiver.mPrefHandler - 7002,
09-13 00:06:06.692  1018  1018 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-13 00:06:06.692  1018  1132 D Tethering: MasterInitialState.processMessage what=3
,09-13 00:06:06.692  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 00:06:06.692  1018  1125 V NetworkStats: updateIfacesLocked()
09-13 00:06:06.692  1018  1125 V NetworkStats: performPollLocked(flags=0x1)
,09-13 00:06:06.692  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
09-13 00:06:06.692  1018  1130 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
09-13 00:06:06.692  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-13 00:06:06.692  1018  1047 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-13 00:06:06.692  1175  1175 D StatusBar.NetworkController: EthernetConnected: false
09-13 00:06:06.692  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-13 00:06:06.692  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-13 00:06:06.692  1175  1175 D StatusBar.NetworkController: updateDataNetType()
09-13 00:06:06.692  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 00:06:06.692  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 00:06:06.692  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 00:06:06.692  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 00:06:06.692  1018  1126 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-13 00:06:06.692  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 00:06:06.692  1018  1125 V NetworkStats: performPollLocked() took 4ms
09-13 00:06:06.692  1175  1760 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-13 00:06:06.702  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-13 00:06:06.702  1175  1175 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-13 00:06:06.702  1175  1175 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-13 00:06:06.702  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 22 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
09-13 00:06:06.702  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 00:06:06.702  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 00:06:06.702  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
09-13 00:06:06.702  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
09-13 00:06:06.702  1175  1175 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-13 00:06:06.702  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,09-13 00:06:06.702  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:06:06.702  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:06:06.702  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:06:06.702  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 00:06:06.712  1018  1223 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-13 00:06:06.712  1018  1223 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-13 00:06:06.712  1018  1223 W ActivityManager: userId = 0, bbcId = -10000
09-13 00:06:06.712  1018  1223 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 00:06:06.712  1018  1223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-13 00:06:06.712  1635  1635 I Hs20UtilService: Starting #24
,09-13 00:06:06.712  1635  1663 I Hs20UtilService: Message received 5007
,09-13 00:06:06.712  4836  4836 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-13 00:06:06.712  4836  4836 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-13 00:06:06.722  1018  1504 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,09-13 00:06:06.722  1018  1505 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
09-13 00:06:06.722  1018  1505 D SecContentProvider2: mCursor = null
,09-13 00:06:06.722  1018  1031 D SecContentProvider2: uri = 15 selection = getToastGravity
09-13 00:06:06.722  1018  1031 D SecContentProvider2: mCursor = null
,09-13 00:06:06.722  1018  1030 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
09-13 00:06:06.722  1018  1030 D SecContentProvider2: mCursor = null
,09-13 00:06:06.722  1018  1489 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
09-13 00:06:06.722  1018  1489 D SecContentProvider2: mCursor = null
,09-13 00:06:06.732  1018  1223 D SecContentProvider2: uri = 15 selection = getToastEnabledState
09-13 00:06:06.732  1018  1223 D SecContentProvider2: mCursor = null
,09-13 00:06:06.732  1018  4258 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState,
09-13 00:06:06.732  1018  4258 D SecContentProvider2: mCursor = null
,09-13 00:06:06.742  7018  7018 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-13 00:06:06.742  7018  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 00:06:06.742  7018  7244 I jxcore-log: 
,09-13 00:06:06.762   259   259 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast,
,09-13 00:06:06.772  1018  1504 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1018,
,09-13 00:06:06.772  1018  7881 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false,
,09-13 00:06:06.782  1175  1175 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-13 00:06:06.822  1018  7881 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 12 Sep 2016 22:06:06 GMT], X-Android-Received-Millis=[1473717966837], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473717966810]}
,09-13 00:06:06.822  1018  7881 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
,09-13 00:06:06.822  1018  7881 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
09-13 00:06:06.822  1018  1130 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
09-13 00:06:06.822  1018  1130 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
09-13 00:06:06.822  1018  1130 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
09-13 00:06:06.822  1018  1130 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
09-13 00:06:06.822  1018  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-13 00:06:06.832  1175  1760 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-13 00:06:06.832  1175  1175 D StatusBar.NetworkController: EthernetConnected: false
09-13 00:06:06.832  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-13 00:06:06.832  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-13 00:06:06.832  1175  1175 D StatusBar.NetworkController: updateDataNetType()
,09-13 00:06:06.832  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-13 00:06:06.832  1175  1175 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-13 00:06:06.842  1175  1175 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-13 00:06:06.842  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 22 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
,09-13 00:06:06.842  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
09-13 00:06:06.842  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,09-13 00:06:06.842  1175  1175 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-13 00:06:06.842  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,09-13 00:06:06.842  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:06:06.842  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 00:06:06.842  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 00:06:06.842  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 00:06:06.872  7920  7920 D AndroidRuntime: ,
09-13 00:06:06.872  7920  7920 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-13 00:06:06.882  7920  7920 D AndroidRuntime: CheckJNI is OFF,
09-13 00:06:06.882  7920  7920 D AndroidRuntime: readGMSProperty: start,
09-13 00:06:06.882  7920  7920 D AndroidRuntime: readGMSProperty: already setted!!
09-13 00:06:06.882  7920  7920 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-13 00:06:06.882  7920  7920 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-13 00:06:06.882  7920  7920 D AndroidRuntime: readGMSProperty: end
09-13 00:06:06.882  7920  7920 D AndroidRuntime: addProductProperty: start
,09-13 00:06:06.882  7018  7018 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
,09-13 00:06:06.882  7018  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 00:06:06.882  7018  7244 I jxcore-log: 
,09-13 00:06:07.042  7018  7018 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
09-13 00:06:07.042  7018  7244 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 00:06:07.042  7018  7244 I jxcore-log: 
,09-13 00:06:07.042  7920  7920 E AffinityControl: AffinityControl: registerfunction enter
,09-13 00:06:07.072  7920  7920 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm,
,09-13 00:06:07.082  1018  1331 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
09-13 00:06:07.082  1018  1331 D PackageManager: START PACKAGE DELETE: observer{40379277}
09-13 00:06:07.082  1018  1331 D PackageManager: pkg{<packageName>}
09-13 00:06:07.082  1018  1331 D PackageManager: user{0}
09-13 00:06:07.082  1018  1331 D PackageManager: caller{2000}
09-13 00:06:07.082  1018  1331 D PackageManager: flags{2}
09-13 00:06:07.082  1018  1331 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true,
09-13 00:06:07.082  1018  1331 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,09-13 00:06:07.092  1018  1331 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2,
09-13 00:06:07.092  1018  1331 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,09-13 00:06:07.092  1018  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,09-13 00:06:07.092  1018  1057 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-13 00:06:07.092  1018  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-13 00:06:07.092  1018  1057 D ApplicationPolicy: getApplicationUninstallationEnabled
09-13 00:06:07.092  1018  1057 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-13 00:06:07.092  1018  1057 D PackageManager: !@killApplicatoin: 10170, uninstall pkg,
,09-13 00:06:07.102  1018  1043 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
,09-13 00:06:07.112  1018  1043 I ActivityManager: Killing 7018:com.test.thalitest/u0a170 (adj 0): stop com.test.thalitest cause uninstall pkg
,09-13 00:06:07.152  1018  1316 E Watchdog: !@Sync 4
,09-13 00:06:07.192  1018  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 00:06:07.212  1018  1504 I WindowState: WIN DEATH: Window{3459f909 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-13 00:06:07.212   259   437 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
,09-13 00:06:07.212   259   440 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,09-13 00:06:07.212  1018  1504 D InputDispatcher: Focus left window: 7018,
,09-13 00:06:07.222  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-13 00:06:07.222  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-13 00:06:07.262  1018  1043 I ActivityManager:   Force finishing activity ActivityRecord{29a44c4e u0 com.test.thalitest/.MainActivity t163},
,09-13 00:06:07.292  1018  1043 D InputDispatcher: Focused application released
,09-13 00:06:07.292  1018  1505 W ActivityManager: Spurious death for ProcessRecord{d3a4942 7018:com.test.thalitest/u0a170}, curProc for 7018: null
,09-13 00:06:07.302  1018  1042 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-13 00:06:07.302  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-13 00:06:07.302  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:06:07.312  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:06:07.312  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:06:07.312  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:06:07.322  7933  7933 E Zygote  : MountEmulatedStorage()
,09-13 00:06:07.322  7933  7933 E Zygote  : v2
09-13 00:06:07.322  7933  7933 I libpersona: KNOX_SDCARD checking this for 1000
09-13 00:06:07.322  7933  7933 I libpersona: KNOX_SDCARD not a persona,
09-13 00:06:07.322  1018  1043 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7933 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-13 00:06:07.322  1018  1057 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed,
,09-13 00:06:07.322  7933  7933 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 00:06:07.332  7933  7933 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 00:06:07.332  7933  7933 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 00:06:07.332  1018  1057 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
09-13 00:06:07.342  1018  1050 I PowerManagerService: [PWL] Off : 75s ago
09-13 00:06:07.342  1018  1050 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
,09-13 00:06:07.342  1018  1050 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
09-13 00:06:07.342  1018  1050 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1018, ws=null) (elapsedTime=23308)
,09-13 00:06:07.362  1018  1100 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-13 00:06:07.372  2828  2828 I art     : Explicit concurrent mark sweep GC freed 16599(991KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 797us total 35.759ms
,09-13 00:06:07.372  7933  7933 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 00:06:07.372  1886  1886 E SamsungIME: mOCRHelper is null
,09-13 00:06:07.382  7933  7933 D ActivityThread: Added TimaKeyStore provider
,09-13 00:06:07.382  1768  2009 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-13 00:06:07.392  1447  1447 D PersonaManager: isKioskContainerExistOnDevice
,09-13 00:06:07.422  1018  1125 V NetworkStats: removeUidsLocked() for UIDs [10170]
09-13 00:06:07.422  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 00:06:07.422  1018  1125 V NetworkStats: performPollLocked(flags=0x3)
,09-13 00:06:07.422  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
09-13 00:06:07.422  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-13 00:06:07.422  1018  1125 V NetworkStats: performPollLocked() took 5ms
09-13 00:06:07.422  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 00:06:07.432  1447  1447 D RegisteredServicesCache: empty dynamic service
,09-13 00:06:07.432  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 00:06:07.432  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 00:06:07.432  1018  1018 D RCPManagerService: PackageReceiver onReceive()
,09-13 00:06:07.432  1018  1018 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,09-13 00:06:07.442  1018  1018 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,09-13 00:06:07.442  1018  1018 I OTPFW   : PackageRemovalReceiver::onReceive Enter
09-13 00:06:07.442  1018  1018 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,09-13 00:06:07.452  1018  1018 I OTPFW   : ProvisionData::getAllEntries Enter
,09-13 00:06:07.462  1018  1042 D EnterpriseDeviceManagerService: Package has changed for user 0
09-13 00:06:07.462  1018  1042 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,09-13 00:06:07.462  1018  1018 E OTPFW   : ProvisionData::getAllEntries Table is empty
,09-13 00:06:07.462  1018  1042 W TextServicesManagerService: no available spell checker services found
,09-13 00:06:07.472  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-13 00:06:07.482  7933  7933 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
09-13 00:06:07.482  7933  7933 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
09-13 00:06:07.482  7933  7933 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-13 00:06:07.482  1447  1447 D RegisteredComponentCache: Collect Tech packages for Knox
09-13 00:06:07.482  1447  1447 D PersonaManager: isKioskContainerExistOnDevice
,09-13 00:06:07.482  1018  1472 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-13 00:06:07.482  1018  1472 D SecContentProvider2: mCursor = null
,09-13 00:06:07.502  7933  7933 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-13 00:06:07.502  7933  7933 I PCWCLIENTTRACE_PushUtil: sales region : global
,09-13 00:06:07.502  7933  7933 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-13 00:06:07.502  7933  7933 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-13 00:06:07.502  1018  1505 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
09-13 00:06:07.502  1018  1505 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
09-13 00:06:07.502  1018  1505 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
09-13 00:06:07.502  1018  1505 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,09-13 00:06:07.512  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-13 00:06:07.512  1018  1505 I ActivityManager: Killing 7421:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,09-13 00:06:07.532  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-13 00:06:07.532  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-13 00:06:07.592  1018  1057 I art     : Explicit concurrent mark sweep GC freed 70454(4MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/35MB, paused 2.870ms total 197.091ms
,09-13 00:06:07.622  1018  1042 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,09-13 00:06:07.622  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-13 00:06:07.632  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-13 00:06:07.642  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-13 00:06:07.652  1018  1042 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-13 00:06:07.652  1018  1042 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-13 00:06:07.652  1018  1042 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-13 00:06:07.652  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-13 00:06:07.652  1018  1018 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,09-13 00:06:07.652  1018  1018 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-13 00:06:07.662  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
09-13 00:06:07.662  1018  1018 V EnterpriseBillingPolicy: uID is 10170
09-13 00:06:07.662  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
09-13 00:06:07.662  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-13 00:06:07.662  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-13 00:06:07.662  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-13 00:06:07.662  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-13 00:06:07.662  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-13 00:06:07.662  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-13 00:06:07.662  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-13 00:06:07.662  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
09-13 00:06:07.662  1018  1018 V EnterpriseBillingPolicy: uID is 10170
09-13 00:06:07.662  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
09-13 00:06:07.662  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-13 00:06:07.662  1018  3405 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,09-13 00:06:07.662  1018  1163 D TaskPersister: removeObsoleteFile: deleting file=163_task.xml
,09-13 00:06:07.662  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-13 00:06:07.662  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-13 00:06:07.662  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-13 00:06:07.662  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-13 00:06:07.662  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-13 00:06:07.672  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-13 00:06:07.672  1018  1057 D PackageManager: delete codoeFile: 
,09-13 00:06:07.672  1018  1018 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
,09-13 00:06:07.672  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-13 00:06:07.682  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-13 00:06:07.682  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-13 00:06:07.682  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-13 00:06:07.682  1018  1057 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
,09-13 00:06:07.682  1018  1057 I AASA_removePackage: UID=10170 Target=com.test.thalitest
,09-13 00:06:07.682  1018  1057 D PackageManager: result of delete: 1{40379277},
,09-13 00:06:07.692  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-13 00:06:07.692  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-13 00:06:07.692  1018  1130 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,09-13 00:06:07.692  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-13 00:06:07.692  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-13 00:06:07.702  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-13 00:06:07.712  1018  1042 D UsbSettingsManager: clearDefaults: com.test.thalitest
,09-13 00:06:07.712  1018  1042 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,09-13 00:06:07.722  7920  7920 D AndroidRuntime: Shutting down VM
,09-13 00:06:07.732  1018  1057 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-13 00:06:07.732  1018  1057 D PackageManager: userId{-1}
09-13 00:06:07.732  1018  1057 D PackageManager: andCode{true}
,09-13 00:06:07.732  1018  1057 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,09-13 00:06:07.732  1018  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:06:07.732  1018  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:06:07.732  1018  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:06:07.732  1018  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:06:07.742  7950  7950 E Zygote  : MountEmulatedStorage(),
09-13 00:06:07.742  7950  7950 I libpersona: KNOX_SDCARD checking this for 10003
09-13 00:06:07.742  7950  7950 E Zygote  : v2
09-13 00:06:07.742  7950  7950 I libpersona: KNOX_SDCARD not a persona
,09-13 00:06:07.752  7950  7950 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 00:06:07.752  1018  1057 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7950 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,09-13 00:06:07.752  7950  7950 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-13 00:06:07.752  7950  7950 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 00:06:07.782  7950  7950 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 00:06:07.782  7950  7950 D ActivityThread: Added TimaKeyStore provider
,09-13 00:06:07.782  1018  1018 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,09-13 00:06:07.792  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:06:07.792  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:06:07.792  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:06:07.792  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:06:07.802  7965  7965 E Zygote  : MountEmulatedStorage()
,09-13 00:06:07.802  7965  7965 E Zygote  : v2
09-13 00:06:07.802  7965  7965 I libpersona: KNOX_SDCARD checking this for 10001
09-13 00:06:07.802  7965  7965 I libpersona: KNOX_SDCARD not a persona
,09-13 00:06:07.802  1018  1018 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7965 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
09-13 00:06:07.802  7965  7965 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 00:06:07.802  7965  7965 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-13 00:06:07.812  7965  7965 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-13 00:06:07.822  1018  1487 I ActivityManager: Killing 7438:com.sec.android.diagmonagent/1000 (adj 15): empty #21
,09-13 00:06:07.832  7965  7965 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 00:06:07.832  7965  7965 D ActivityThread: Added TimaKeyStore provider
,09-13 00:06:07.872  1018  1030 I ActivityManager: Killing 7453:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,09-13 00:06:07.872  1018  1030 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-13 00:06:07.872  1018  1030 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.sec.android.diagmonagent/com.sec.android.diagmonagent.DiagMonRegistrationReceiver}
09-13 00:06:07.872  1018  1030 W BroadcastQueue: android.os.TransactionTooLargeException
09-13 00:06:07.872  1018  1030 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-13 00:06:07.872  1018  1030 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
09-13 00:06:07.872  1018  1030 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
09-13 00:06:07.872  1018  1030 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
09-13 00:06:07.872  1018  1030 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
09-13 00:06:07.872  1018  1030 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
09-13 00:06:07.872  1018  1030 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
09-13 00:06:07.872  1018  1030 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
09-13 00:06:07.872  1018  1030 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
09-13 00:06:07.872  1018  1030 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,09-13 00:06:07.872  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:06:07.872  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:06:07.872  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 00:06:07.872  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 00:06:07.892  7983  7983 E Zygote  : MountEmulatedStorage(),
09-13 00:06:07.892  7983  7983 E Zygote  : v2
09-13 00:06:07.892  7983  7983 I libpersona: KNOX_SDCARD checking this for 1000
09-13 00:06:07.892  7983  7983 I libpersona: KNOX_SDCARD not a persona
,09-13 00:06:07.892  7983  7983 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 00:06:07.892  7983  7983 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-13 00:06:07.892  1018  1030 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7983 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-13 00:06:07.892  7983  7983 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 00:06:07.902  7983  7983 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 00:06:07.912  7983  7983 D ActivityThread: Added TimaKeyStore provider
,09-13 00:06:07.932  7920  7920 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-13 00:06:07.942  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_7438/cgroup.procs: No such file or directory
,09-13 00:06:07.942  7983  7983 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,09-13 00:06:08.012  7983  7983 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30),
09-13 00:06:08.012  7983  7983 W FileUtils: Failed to chmod(/data/data/com.sec.android.diagmonagent/databases/diagmondm.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.,
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
,09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: ,	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98),
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.lllIlIlIIIllIIlIllIl(llIIIIlllllIIllIIllI:773)
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:396)
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111),
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: ,	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	,at android.os.Looper.loop(Looper.java:145)
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399),
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-13 00:06:08.012  7983  7983 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):,
09-13 00:06:08.012  7983  7983 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 00:06:08.012  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 00:06:08.012  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-13 00:06:08.012  7983  7983 E SQLiteOpenHelper: 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-13 00:06:08.012  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-13 00:06:08.012  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-13 00:06:08.012  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
,09-13 00:06:08.012  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-13 00:06:08.012  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-13 00:06:08.012  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-13 00:06:08.012  7983  7983 E SQLiteOpenHelper: 	,at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-13 00:06:08.012  7983  7983 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-13 00:06:08.012  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 00:06:08.012  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
,09-13 00:06:08.012  7983  7983 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
09-13 00:06:08.012  7983  7983 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.lllIlIlIIIllIIlIllIl(llIIIIlllllIIllIIllI:773)
09-13 00:06:08.012  7983  7983 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:396)
09-13 00:06:08.012  7983  7983 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-13 00:06:08.012  7983  7983 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
,09-13 00:06:08.012  7983  7983 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 00:06:08.012  7983  7983 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 00:06:08.012  7983  7983 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 00:06:08.012  7983  7983 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 00:06:08.012  7983  7983 E SQLiteOpenHelper: ,	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:06:08.012  7983  7983 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
,09-13 00:06:08.012  7983  7983 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 00:06:08.012  7983  7983 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:06:08.012  7983  7983 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372),
09-13 00:06:08.012  7983  7983 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 00:06:08.012  7983  7983 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-13 00:06:08.012  7983  7983 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
,09-13 00:06:08.012  7983  7983 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30),
,09-13 00:06:08.012  7983  7983 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.,
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318),
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
,09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
,09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 00:06:08.012  7983  7983 E SQLiteDatabase:, 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.IllIlIIIIlIIlIIIllIl(llIIIIlllllIIllIIllI:1078)
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:402)
,09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: ,	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102),
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	,at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 00:06:08.012  7983  7983 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
,09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.IllIlIIIIlIIlIIIllIl(llIIIIlllllIIllIIllI:1078)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:402)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-13 00:06:08.022  7983  7983 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
09-13 00:06:08.022  7983  7983 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.,
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282),
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.IllIlIIIIlIIlIIIllIl(llIIIIlllllIIllIIllI:1078)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:402)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.IllIlIIIIlIIlIIIllIl(llIIIIlllllIIllIIllI:1078)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:402)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-13 00:06:08.022  7983  7983 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
09-13 00:06:08.022  7983  7983 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIIllllIIlllIIIIlll(llIIIIlllllIIllIIllI:1221)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:408)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 00:06:08.0,22  7983  7983 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 00:06:08.022  7983  7983 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: ,	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25),
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.llIIllllIIlllIIIIlll(llIIIIlllllIIllIIllI:1221)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:408)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 00:06:08.022  7983  7983 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-13 00:06:08.022  7983  7983 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
09-13 00:06:08.022  7983  7983 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIIllllIIlllIIIIlll(llIIIIlllllIIllIIllI:1221)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:408)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.,java:1399)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.llIIllllIIlllIIIIlll(llIIIIlllllIIllIIllI:1221)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:408)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-13 00:06:08.032  7983  7983 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
09-13 00:06:08.032  7983  7983 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-13 00:06:08.032  7983 , 7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at IlIlIlIIIIIllllIlIIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:154)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:416)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQL,iteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at IlIlIlIIIIIllllIlIIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:154)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:416)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-13 00:06:08.032  7983  7983 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
09-13 00:06:08.032  7983  7983 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at IlIlIlIIIIIllllIlIIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:154)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:416)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 00:06:08.032  7983  7983 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at IlIlIlIIIIIllllIlIIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:154)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:416)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 00:06:08.032  7983  7983 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-13 00:06:08.032  7983  7983 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
09-13 00:06:08.042  7983  7983 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at IlIlIlllIllIIIIlIlll.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:299)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:421)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at IlIlIlllIllIIIIlIlll.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:299)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:421)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-13 00:06:08.042  7983  7983 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
09-13 00:06:08.042  7983  7983 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at IlIlIlllIllIIIIlIlll.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:299)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:421)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 00:06:08.042  7983  7983 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at IlIlIlllIllIIIIlIlll.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:299)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:421)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 00:06:08.042  7983  7983 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-13 00:06:08.042  7983  7983 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
09-13 00:06:08.052  7983  7983 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at IlIlIlIIIIIllllIlIIl.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:116)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at com.diagmondm.db.file.XDBDiagMon.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:28)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at com.diagmondm.db.file.XDBDiagMon.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:71)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:57)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at IlIlIlIIIIIllllIlIIl.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:116)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDBDiagMon.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:28)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDBDiagMon.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:71)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:57)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-13 00:06:08.052  7983  7983 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
09-13 00:06:08.052  7983  7983 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at IlIlIlIIIIIllllIlIIl.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:116)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at com.diagmondm.db.file.XDBDiagMon.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:28)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at com.diagmondm.db.file.XDBDiagMon.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:71)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:57)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at IlIlIlIIIIIllllIlIIl.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:116)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDBDiagMon.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:28)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDBDiagMon.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:71)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:57)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-13 00:06:08.052  7983  7983 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
09-13 00:06:08.052  7983  7983 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at IlIlIlllIllIIIIlIlll.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:206)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at com.diagmondm.db.file.XDBDiagMonFunction.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:49)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at com.diagmondm.db.file.XDBDiagMonFunction.lllIlIlIIIllIIlIllIl(llIIIIlllllIIllIIllI:187)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:57)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 00:06:08.052  7983  7983 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	,at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at IlIlIlllIllIIIIlIlll.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:206)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDBDiagMonFunction.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:49)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDBDiagMonFunction.lllIlIlIIIllIIlIllIl(llIIIIlllllIIllIIllI:187)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:57)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 00:06:08.052  7983  7983 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-13 00:06:08.062  7983  7983 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
09-13 00:06:08.062  7983  7983 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)

```
