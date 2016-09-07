#### Test 82914073126c10a_thali03_samsung-SM-A300FU Logs


```
--------- beginning of main
09-07 15:29:13.823  6876  6876 E Zygote  : MountEmulatedStorage()
09-07 15:29:13.823  6876  6876 E Zygote  : v2
09-07 15:29:13.823  6876  6876 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
--------- beginning of system
09-07 15:29:13.823  6876  6876 I libpersona: KNOX_SDCARD checking this for 1000
09-07 15:29:13.823  6876  6876 I libpersona: KNOX_SDCARD not a persona
09-07 15:29:13.833  6876  6876 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 15:29:13.833  6876  6876 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-07 15:29:13.833  1017  1042 I ActivityManager: Start proc com.samsung.aasaservice for service com.samsung.aasaservice/.AASAService: pid=6876 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-07 15:29:13.843  1679  1777 I art     : Explicit concurrent mark sweep GC freed 13315(613KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 8MB/13MB, paused 1.108ms total 141.244ms
09-07 15:29:13.843  6692  6768 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
09-07 15:29:13.853  1908  6766 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
09-07 15:29:13.853  1908  6766 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-07 15:29:13.853  1908  6766 I System.out: (HTTPLog)-Static: isShipBuild true
09-07 15:29:13.853  1908  6766 I System.out: (HTTPLog)-Thread-247-1011507177: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
09-07 15:29:13.853  1908  6766 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-07 15:29:13.863  6876  6876 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 15:29:13.863   278   986 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-07 15:29:13.863   278   986 D Netd    : getNetworkForDns: using netid 502 for uid 10011
09-07 15:29:13.863  6876  6876 D ActivityThread: Added TimaKeyStore provider
09-07 15:29:13.873  1017  1503 I ActivityManager: Killing 6468:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
09-07 15:29:13.893  1017  1504 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
09-07 15:29:13.893  1017  1504 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
09-07 15:29:13.893  1017  1504 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:13.893  1017  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 15:29:13.893  1017  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
09-07 15:29:13.893  6876  6876 D AASAservice: onCreate()
09-07 15:29:13.893  6876  6876 E AASAservice: getConfirmRuleVersion() : Version File is not exist.
,09-07 15:29:13.903  2751  2751 I DBG_POLICYDM: [com.sec.android.policydm.aasa.AASAUpdater$1(72/onServiceConnected)] AASA: onServiceConnected
09-07 15:29:13.913  1017  1255 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
09-07 15:29:13.913  1017  1255 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
09-07 15:29:13.913  1017  1255 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:13.913  1017  1255 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 15:29:13.913  1017  1255 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
09-07 15:29:13.963  1017  3786 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-07 15:29:13.983  1908  6766 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
09-07 15:29:13.983  1908  6766 I qtaguid : Tagging socket 101 with tag 1000040b00000000{268436491,0} for uid -1, pid: 1908, getuid(): 10011
09-07 15:29:13.993  1017  1029 E EdmStorageProvider: Admin not in database, something went wrong
09-07 15:29:14.003  6744  6897 D ContactProvider: getAllContactInfoList Start
09-07 15:29:14.073  1908  6766 I qtaguid : Tagging socket 105 with tag 1000040b00000000{268436491,0} for uid -1, pid: 1908, getuid(): 10011
09-07 15:29:14.103  1017  1545 I art     : Explicit concurrent mark sweep GC freed 143426(8MB) AllocSpace objects, 3(1847KB) LOS objects, 33% free, 23MB/34MB, paused 2.565ms total 175.616ms
09-07 15:29:14.113  1017  1546 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
09-07 15:29:14.113  1017  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:14.113  1017  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:14.113  1017  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:14.113  1017  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:14.133  6904  6904 E Zygote  : MountEmulatedStorage()
09-07 15:29:14.133  6904  6904 E Zygote  : v2
09-07 15:29:14.133  6904  6904 I libpersona: KNOX_SDCARD checking this for 10148
09-07 15:29:14.133  6904  6904 I libpersona: KNOX_SDCARD not a persona
09-07 15:29:14.133  6904  6904 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 15:29:14.133  6904  6904 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 15:29:14.133  6904  6904 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-07 15:29:14.143  1017  3785 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:14.143  1017  1546 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=6904 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
09-07 15:29:14.143  1017  3785 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 15:29:14.143  1017  3785 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-07 15:29:14.143  1017  3785 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
09-07 15:29:14.153   273   273 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7de67c8
09-07 15:29:14.153   273   273 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
09-07 15:29:14.153   273   273 I rmt_storage: wakelock acquired: 1, error no: 42
09-07 15:29:14.153   273   324 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1210161016)
09-07 15:29:14.173  1017  1545 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-07 15:29:14.173  6901  6901 D AndroidRuntime: 
09-07 15:29:14.173  6901  6901 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-07 15:29:14.173  1017  1545 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
09-07 15:29:14.173  6901  6901 D AndroidRuntime: CheckJNI is OFF
09-07 15:29:14.173  6901  6901 D AndroidRuntime: readGMSProperty: start
09-07 15:29:14.173  6901  6901 D AndroidRuntime: readGMSProperty: already setted!!
09-07 15:29:14.173  6901  6901 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-07 15:29:14.173  6901  6901 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-07 15:29:14.173  6901  6901 D AndroidRuntime: readGMSProperty: end
09-07 15:29:14.173  6901  6901 D AndroidRuntime: addProductProperty: start
09-07 15:29:14.183  1017  1545 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:14.183  1017  1545 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 15:29:14.183  1017  1545 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-07 15:29:14.193  6904  6904 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 15:29:14.193  6904  6904 D ActivityThread: Added TimaKeyStore provider
09-07 15:29:14.193  1017  1520 I ActivityManager: Killing 6484:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
09-07 15:29:14.213   273   324 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
09-07 15:29:14.213   273   324 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
09-07 15:29:14.213   273   324 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1210161016) wakelock released: 1, error no: 0
09-07 15:29:14.213   273   324 I rmt_storage: 
09-07 15:29:14.213   273   273 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb7de67c8
09-07 15:29:14.223  1017  1503 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
09-07 15:29:14.233  1017  1501 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-07 15:29:14.233  6744  6744 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
09-07 15:29:14.233  1017  1503 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:14.233  1017  1503 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 15:29:14.233  1017  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-07 15:29:14.243  1017  1520 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-07 15:29:14.243  1017  1520 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
09-07 15:29:14.243  1017  1520 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:14.243  1017  1520 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 15:29:14.243  1017  1520 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-07 15:29:14.243  1908  6770 W BaseAppContext: Using Auth Proxy for data requests.
09-07 15:29:14.243  1908  6770 W BaseAppContext: Using Auth Proxy for data requests.
09-07 15:29:14.253  1017  1546 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-07 15:29:14.253  1017  1546 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:14.253  1017  1546 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 15:29:14.253  1017  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-07 15:29:14.263  1017  1029 D PowerManagerService: [api] handleWakeLockDeath : release WakeLock : PARTIAL_WAKE_LOCK              'AlarmReceiver' (uid=10081, pid=6484, ws=null) (elapsedTime=2754)
09-07 15:29:14.273  6744  6897 D ContactProvider: getAllContactInfoList End
09-07 15:29:14.273  6744  6897 I syncContacts: thread: 1248, sync time = 358
09-07 15:29:14.273  1017  1029 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-07 15:29:14.273  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:14.273  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 15:29:14.273  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
09-07 15:29:14.283  6857  6857 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-07 15:29:14.283  6904  6904 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
09-07 15:29:14.283  1017  1544 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
09-07 15:29:14.283  1017  1544 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:14.283  1017  1544 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 15:29:14.283  1017  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-07 15:29:14.303  1908  6770 W BaseAppContext: Using Auth Proxy for data requests.
09-07 15:29:14.303  6857  6857 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-07 15:29:14.303  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
09-07 15:29:14.313  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:14.313  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:14.313  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:14.313  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:14.323  6932  6932 E Zygote  : MountEmulatedStorage()
09-07 15:29:14.323  6932  6932 I libpersona: KNOX_SDCARD checking this for 1000
09-07 15:29:14.323  6932  6932 E Zygote  : v2
09-07 15:29:14.323  6932  6932 I libpersona: KNOX_SDCARD not a persona
09-07 15:29:14.333  1017  1029 I ActivityManager: Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=6932 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-07 15:29:14.333  1017  1029 I ActivityManager: Killing 6499:com.wsomacp/u0a23 (adj 15): empty #21
09-07 15:29:14.333  6932  6932 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 15:29:14.333  6932  6932 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 15:29:14.333  6932  6932 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-07 15:29:14.333  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
09-07 15:29:14.353  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:14.353  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:14.353  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:14.353  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:14.353  6932  6932 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 15:29:14.363  6946  6946 E Zygote  : MountEmulatedStorage()
09-07 15:29:14.363  6946  6946 E Zygote  : v2
09-07 15:29:14.363  6946  6946 I libpersona: KNOX_SDCARD checking this for 10041
09-07 15:29:14.363  6946  6946 I libpersona: KNOX_SDCARD not a persona
09-07 15:29:14.373  6946  6946 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 15:29:14.373  6946  6946 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 15:29:14.373  6946  6946 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
09-07 15:29:14.373  1017  1030 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.smishing.PackageInstallReceiver: pid=6946 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
09-07 15:29:14.373  1017  1030 I ActivityManager: Killing 6352:com.android.defcontainer/u0a3 (adj 15): empty #21
09-07 15:29:14.383  1017  3785 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-07 15:29:14.383  1017  3785 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
09-07 15:29:14.383  1017  3785 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:14.383  1017  3785 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 15:29:14.383  1017  3785 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-07 15:29:14.393  6932  6932 D ActivityThread: Added TimaKeyStore provider
09-07 15:29:14.403  1908  6770 W BaseAppContext: Using Auth Proxy for data requests.
09-07 15:29:14.403  6901  6901 E AffinityControl: AffinityControl: registerfunction enter
09-07 15:29:14.413  6932  6932 W ResourcesManager: Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
09-07 15:29:14.423  6946  6946 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 15:29:14.423  6946  6946 D ActivityThread: Added TimaKeyStore provider
09-07 15:29:14.433  6901  6901 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-07 15:29:14.433  6692  6768 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 579 ms] updated apps [took 578 ms] 
09-07 15:29:14.443  1017  1503 I ActivityManager: Killing 6516:com.sec.esdk.elm/u0a90 (adj 15): empty #21
09-07 15:29:14.443  1017  1501 E PersonaManagerService: inState():  stateMachine is null !!
09-07 15:29:14.453  1017  1501 I PersonaManagerService: PersonaId don't exist
09-07 15:29:14.453  1908  6770 W BaseAppContext: Using Auth Proxy for data requests.
09-07 15:29:14.453  1017  1501 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
09-07 15:29:14.453  1017  1501 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-07 15:29:14.453  6946  6946 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
09-07 15:29:14.453  6946  6946 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 15:29:14.453  6946  6946 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-07 15:29:14.453  6946  6946 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-07 15:29:14.453  6946  6946 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
09-07 15:29:14.463  6857  6857 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
09-07 15:29:14.473  1017  1501 W ActivityManager: mDVFSHelper.acquire()
09-07 15:29:14.473  1017  1501 D FocusedStackFrame: Set to : 0
09-07 15:29:14.483  6857  6857 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-07 15:29:14.503  1017  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:14.503  1017  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:14.503  1017  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:14.503  1017  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:14.503  1017  1047 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-07 15:29:14.503  1017  1047 D PhoneWindow: *FMB* installDecor flags : -2122120936
09-07 15:29:14.513  6970  6970 E Zygote  : MountEmulatedStorage()
09-07 15:29:14.513  6970  6970 I libpersona: KNOX_SDCARD checking this for 10170
09-07 15:29:14.513  6970  6970 E Zygote  : v2
09-07 15:29:14.513  6970  6970 I libpersona: KNOX_SDCARD not a persona
09-07 15:29:14.523  6970  6970 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 15:29:14.523  6970  6970 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 15:29:14.523  1017  1501 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6970 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-07 15:29:14.523  6970  6970 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
09-07 15:29:14.523  1017  1501 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
09-07 15:29:14.523  1017  1501 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-07 15:29:14.523  1017  1501 D InputDispatcher: Focused application set to: xxxx
09-07 15:29:14.523  1017  1501 D InputDispatcher: Focus left window: 1505
09-07 15:29:14.533  1017  3795 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
09-07 15:29:14.533  1017  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-07 15:29:14.533  1017  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-07 15:29:14.533   258   258 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
09-07 15:29:14.533  1017  3795 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:14.533  1017  3795 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:14.533  1017  3795 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:14.533  1017  3795 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:14.533  6901  6901 D AndroidRuntime: Shutting down VM
09-07 15:29:14.553  6970  6970 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 15:29:14.553  6970  6970 D ActivityThread: Added TimaKeyStore provider
09-07 15:29:14.563  6986  6986 E Zygote  : MountEmulatedStorage()
09-07 15:29:14.563  6986  6986 I libpersona: KNOX_SDCARD checking this for 10152
09-07 15:29:14.563  6986  6986 E Zygote  : v2
09-07 15:29:14.563  6986  6986 I libpersona: KNOX_SDCARD not a persona
09-07 15:29:14.563  6986  6986 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 15:29:14.573  1017  3795 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=6986 uid=10152 gids={50152, 9997} abi=armeabi-v7a
09-07 15:29:14.573  1017  3795 I ActivityManager: Killing 6251:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
09-07 15:29:14.573  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-07 15:29:14.573  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
09-07 15:29:14.573  6986  6986 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 15:29:14.583  6986  6986 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-07 15:29:14.593  1017  3796 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
09-07 15:29:14.603  1017  1017 V ActivityManager: Display changed displayId=0
09-07 15:29:14.603  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-07 15:29:14.623  6986  6986 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 15:29:14.623  6986  6986 D ActivityThread: Added TimaKeyStore provider
09-07 15:29:14.623  1908  6766 I qtaguid : Untagging socket 101
09-07 15:29:14.633  1908  1908 I ConfigFetchService: fetch service done; releasing wakelock
09-07 15:29:14.633  6857  6857 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-07 15:29:14.633  1908  1908 I ConfigFetchService: stopping self
09-07 15:29:14.633   258  1097 I SurfaceFlinger: id=9 Removed Mauncher (5/9)
09-07 15:29:14.633  6857  6857 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-07 15:29:14.633   258  1833 I SurfaceFlinger: id=9 Removed Mauncher (-2/9)
09-07 15:29:14.643  1505  1505 V ActivityThread: updateVisibility : ActivityRecord{39e47896 token=android.os.BinderProxy@12dd8187 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
09-07 15:29:14.643  1505  1505 D Launcher: onTrimMemory. Level: 20
09-07 15:29:14.643  6857  6857 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-07 15:29:14.643  1017  3796 D PersonaManager: isKioskContainerExistOnDevice
09-07 15:29:14.643  6857  6857 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-07 15:29:14.653  6946  6946 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
09-07 15:29:14.673  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
09-07 15:29:14.683  1908  6770 W BaseAppContext: Using Auth Proxy for data requests.
09-07 15:29:14.713  6986  6986 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
09-07 15:29:14.713  6986  6986 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
09-07 15:29:14.733  6986  6986 I TapandpayWidget:Utils: Clear T&P info.
09-07 15:29:14.733  6857  6857 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-07 15:29:14.733  6857  6857 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-07 15:29:14.733  6857  6857 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-07 15:29:14.733  6857  6857 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-07 15:29:14.733  6857  6857 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-07 15:29:14.743  6857  6857 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-07 15:29:14.743  6857  6857 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-07 15:29:14.753  6901  6901 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-07 15:29:14.753  6986  6986 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
,09-07 15:29:14.763  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,09-07 15:29:14.763  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:14.763  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:14.763  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:14.763  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:14.763  6857  6857 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-07 15:29:14.773  6857  6857 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.,
,09-07 15:29:14.773  6857  6857 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.,
,09-07 15:29:14.773  6857  6857 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-07 15:29:14.783  6857  6857 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.,
,09-07 15:29:14.783  6857  6857 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.,
,09-07 15:29:14.793  7011  7011 E Zygote  : MountEmulatedStorage()
,09-07 15:29:14.793  7011  7011 E Zygote  : v2
09-07 15:29:14.793  7011  7011 I libpersona: KNOX_SDCARD checking this for 10009
09-07 15:29:14.793  7011  7011 I libpersona: KNOX_SDCARD not a persona
09-07 15:29:14.793  7011  7011 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 15:29:14.793  7011  7011 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 15:29:14.793  7011  7011 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-07 15:29:14.813  6970  6970 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,09-07 15:29:14.823  1017  1030 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=7011 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,09-07 15:29:14.823   288   288 E SMD     : DCD OFF
09-07 15:29:14.823  6857  6857 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-07 15:29:14.833  6857  6857 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-07 15:29:14.833  1017  1030 I ActivityManager: Killing 6267:com.android.calendar/u0a131 (adj 15): empty #21
,09-07 15:29:14.853  7011  7011 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 15:29:14.853  7011  7011 D ActivityThread: Added TimaKeyStore provider
,09-07 15:29:14.873  6946  6946 W art     : Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 134.476ms
,09-07 15:29:14.883  1017  3796 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,09-07 15:29:14.883  6857  6857 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-07 15:29:14.883  6857  6857 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-07 15:29:14.883  6857  6857 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,09-07 15:29:14.913  1017  3785 I ActivityManager: Killing 6547:com.samsung.android.securitylogagent/1000 (adj 15): empty #21
,09-07 15:29:14.923  6970  6970 I cr.library_loader: Time to load native libraries: 12 ms (timestamps 7967-7979)
,09-07 15:29:14.923  6970  6970 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-07 15:29:14.963  6970  6970 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3d8a90b0}
,09-07 15:29:14.963  6970  6970 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-07 15:29:14.963  6970  6970 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,09-07 15:29:15.003  6857  6857 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,09-07 15:29:15.003  1017  1095 V AlarmManager: waitForAlarm result :4
,09-07 15:29:15.003  1017  1477 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,09-07 15:29:15.003  1017  1477 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,09-07 15:29:15.003  1017  1477 W ActivityManager: userId = 0, bbcId = -10000
,09-07 15:29:15.003  1017  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-07 15:29:15.013  1017  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,09-07 15:29:15.023  6946  6946 W art     : Verification of com.sec.android.touchwiz.animator.TwDndHorizontalListAnimator com.android.mms.ArtClassLoader.createTwDndHorizontalListAnimator(android.content.Context) took 154.600ms
,09-07 15:29:15.033  6857  6857 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,09-07 15:29:15.033  1017  3795 I ActivityManager: Killing 6570:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,09-07 15:29:15.043  6970  6970 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,09-07 15:29:15.043  6970  6970 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-07 15:29:15.053  6946  7037 D Mms/ArtClassLoader: init before art
,09-07 15:29:15.053  6946  6946 D Mms/TelephonyPermission: start operation mode monitor
,09-07 15:29:15.053  6970  6970 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-07 15:29:15.073  6946  6946 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-07 15:29:15.103  6970  6970 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-07 15:29:15.103  6970  6970 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-07 15:29:15.103  6970  6970 I Adreno-EGL: Build Date: 04/06/15 Mon
09-07 15:29:15.103  6970  6970 I Adreno-EGL: Local Branch: 
09-07 15:29:15.103  6970  6970 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-07 15:29:15.103  6970  6970 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-07 15:29:15.103  6970  6970 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-07 15:29:15.103  6857  7038 D Ads     : Skipping gmscore version check
,09-07 15:29:15.103  6946  6946 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
09-07 15:29:15.103  6946  6946 D Mms/TelephonyPermission: isDefault true
,09-07 15:29:15.103  6946  6946 D Mms/MmsApp: onCreate() com.android.mms
,09-07 15:29:15.113  1017  3375 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-07 15:29:15.153  1017  1042 W ActivityManager: Activity pause timeout for ActivityRecord{2aebb6d4 u0 com.test.thalitest/.MainActivity t163}
,09-07 15:29:15.153  1017  3796 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-07 15:29:15.153  1017  3796 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:15.153  1017  3796 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 15:29:15.153  1017  3796 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,09-07 15:29:15.173  6807  6898 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
09-07 15:29:15.173  6807  6898 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-07 15:29:15.173  6807  6898 I GAv4    :   adb logcat -s GAv4
,09-07 15:29:15.183  6946  6946 D Mms/MmsApp: [start]    initCountryIso consume time = 527.313333
,09-07 15:29:15.183  1017  1503 D CountryDetector: The first listener is added
,09-07 15:29:15.223  6946  6946 D Mms/MmsApp: [end]    initCountryIso consume time = 38.104531
09-07 15:29:15.223  6946  6946 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.110104
,09-07 15:29:15.243  6946  6946 D Mms/MmsConfig: before partial update
,09-07 15:29:15.253  6970  6970 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-07 15:29:15.263  6946  6946 D Mms/MmsConfig: Load Resize quality : 80
,09-07 15:29:15.273  6857  6857 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-07 15:29:15.273  6946  6946 D EasySignUpManager_1.0.1: serviceId : 1, features : -1
09-07 15:29:15.273  6946  6946 D EasySignUpManager_1.0.1: isAuth is false
09-07 15:29:15.273  6946  6946 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
09-07 15:29:15.273  6970  6970 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
09-07 15:29:15.273  6970  6970 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,09-07 15:29:15.283  1480  1491 D TP/MmsSmsProvider: query,matched:2117, calling pid = 6946
,09-07 15:29:15.283  1480  1491 D TP/MmsSmsProvider: match 2117:Elapsed time : 2.255 ms
,09-07 15:29:15.283  6970  6970 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,09-07 15:29:15.283  6970  6970 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,09-07 15:29:15.293  6946  6946 D EasySignUpManager_1.0.1: isAuth is false
,09-07 15:29:15.303  6946  6946 D EasySignUpManager_1.0.1: getServiceStatus : serviceId (1) is OFF
,09-07 15:29:15.303  6946  6946 E CscParser: mps_code.dat does not exist
,09-07 15:29:15.303  6946  6946 E CscParser: customer_path =/system/csc/customer.xml
,09-07 15:29:15.303  6946  6946 E CscParser: fileName + /system/csc/customer.xml
,09-07 15:29:15.313  6946  6946 E CscParser: mps_code.dat does not exist
09-07 15:29:15.313  6946  6946 E CscParser: customer_path =/system/csc/customer.xml
09-07 15:29:15.313  6946  6946 E CscParser: fileName + /system/csc/customer.xml
,09-07 15:29:15.333  6946  6946 D CscParser: getInstance fileName =/system/csc/customer.xml
,09-07 15:29:15.333  6946  6946 D Mms/MmsConfig:  enable multiwindow = false
,09-07 15:29:15.353  6946  6946 E Mms/MessageUtils: setCountryDetector : update country detector info 
09-07 15:29:15.353  6946  6946 E Mms/MessageUtils: updateCountryIso : update country iso info 
,09-07 15:29:15.353  6807  6898 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-07 15:29:15.353  1017  1545 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,09-07 15:29:15.363  6946  6946 D Mms/MmsConfig: [end]    init() consume time = 142.740104
,09-07 15:29:15.363  6946  6946 D Mms/Contact: [start]    init() consume time = 0.771563
,09-07 15:29:15.383  6946  6946 D Mms/Contact: [end]    init consume time = 13.618073
,09-07 15:29:15.393  1480  3320 D TP/MmsSmsProvider: query,matched:13, calling pid = 6946
,09-07 15:29:15.393  1480  3320 D TP/MmsSmsProvider: match 13:Elapsed time : 1.791 ms
,09-07 15:29:15.393  6807  6898 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-07 15:29:15.413  6946  6946 D Mms/MethodReflector: getSubId is called
09-07 15:29:15.413  6946  6946 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,09-07 15:29:15.413  6946  6946 D Mms/MethodReflector: getTelephonyProperty is called
09-07 15:29:15.413  6946  6946 D Mms/DownloadManager: roaming -> false (slotId = 0)
09-07 15:29:15.413  6946  6946 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
09-07 15:29:15.413  6946  6946 D Mms/DownloadManager: auto download without roaming -> true
09-07 15:29:15.413  6946  6946 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
,09-07 15:29:15.413  6946  6946 D Mms/MethodReflector: getSubId is called
,09-07 15:29:15.433  6946  6946 D Mms/MethodReflector: getDefaultSmsSubId is called
09-07 15:29:15.433  6946  6946 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
09-07 15:29:15.433  6946  6946 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
09-07 15:29:15.433  6946  6946 D Mms/MethodReflector: getTelephonyProperty is called
09-07 15:29:15.433  6946  6946 D Mms/DownloadManager: roaming -> false (slotId = 1)
09-07 15:29:15.433  6946  6946 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
09-07 15:29:15.433  6946  6946 D Mms/DownloadManager: auto download without roaming -> true
09-07 15:29:15.433  6946  6946 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
09-07 15:29:15.433  6946  6946 D Mms/DownloadManager: auto download during roaming secondary -> false
09-07 15:29:15.433  6946  6946 D Mms/DownloadManager: mAutoDownload ------> true
,09-07 15:29:15.433  6946  7063 D Mms/DraftCache: [start]    rebuildCache consume time = 51.698229
,09-07 15:29:15.433  1480  1496 D TP/MmsSmsProvider: query,matched:12, calling pid = 6946
,09-07 15:29:15.443  1480  1496 D TP/MmsSmsProvider: match 12:Elapsed time : 4.849 ms
,09-07 15:29:15.443  6807  6898 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.357.23.33
,09-07 15:29:15.453  6946  7063 D Mms/DraftCache: [end]    rebuildCache consume time = 23.335312
,09-07 15:29:15.473  6807  7066 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-07 15:29:15.483  6946  6946 D ComposerPerformance: 1473254955499 ms / [DONE] Composer constructor
,09-07 15:29:15.493  6946  7068 D Mms/Conversation: [start]    init() consume time = 37.080053
,09-07 15:29:15.493  6946  6946 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
,09-07 15:29:15.493  6946  6946 I Mms/ReservationManager: ReservationManager()
,09-07 15:29:15.493  6946  6946 I Mms/ReservationManager: resetAfterConnected()
,09-07 15:29:15.493  1480  3320 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
,09-07 15:29:15.493  1480  1660 D TP/MmsSmsProvider: query,matched:7, calling pid = 6946
,09-07 15:29:15.493  1480  3320 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
,09-07 15:29:15.503  1480  3320 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
09-07 15:29:15.503  1480  1660 D TP/MmsSmsProvider: match 7:Elapsed time : 3.332 ms
,09-07 15:29:15.503  1480  3320 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
,09-07 15:29:15.503  6946  6946 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,09-07 15:29:15.503  6946  6946 D Mms/MmsApp: [end]    onCreate() consume time = 14.32302
,09-07 15:29:15.513  1480  3320 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
,09-07 15:29:15.513  1480  3320 D TP/MmsSmsProvider: need read changed broadcast:false
,09-07 15:29:15.513  1908  1929 W art     : Suspending all threads took: 59.199ms
,09-07 15:29:15.513  6946  7068 D Mms/Conversation: [end]    init consume time = 5.786146
,09-07 15:29:15.513  6946  7068 D Mms/MessagingNotification: [start]    init() consume time = 3.234531
,09-07 15:29:15.523  6970  6970 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-07 15:29:15.523  6946  7068 D Mms/MessagingNotification: [end]    init consume time = 9.087344
,09-07 15:29:15.523  1908  3810 I Icing   : Indexing D0AE1F45F393341DA3213A207506F1C2E721F1A9 from com.google.android.googlequicksearchbox
,09-07 15:29:15.523  1480  1491 D TP/MmsSmsProvider: query,matched:0, calling pid = 6946
09-07 15:29:15.523  6946  7070 D Mms/Synchronizer: [start]    doSync consume time = 4.554792
,09-07 15:29:15.533  1480  1491 V TP/MmsSmsProvider: getSimpleConversations entered.
,09-07 15:29:15.533  6946  7069 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 1.466719
09-07 15:29:15.533  1480  1491 D TP/MmsSmsProvider: match 0:Elapsed time : 2.604 ms
09-07 15:29:15.533  1480  1660 D TP/MmsSmsProvider: update, matched:300, calling pid = 6946
09-07 15:29:15.533  1480  1660 V TP/MmsSmsProvider: syncDBData start
09-07 15:29:15.533  1480  1660 V TP/MmsSmsProvider: syncDBData sms end
09-07 15:29:15.533  1480  1660 V TP/MmsSmsProvider: syncDBData mms end
09-07 15:29:15.533  1480  1660 V TP/MmsSmsProvider: syncDBData end
09-07 15:29:15.533  6946  7070 D Mms/Synchronizer: [end]    doSync consume time = 7.030781
,09-07 15:29:15.543  1017  1546 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
,09-07 15:29:15.543  1480  3320 D TP/MmsSmsProvider: query,matched:400, calling pid = 6946
,09-07 15:29:15.543  1017  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:15.543  1017  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:15.543  1017  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:15.543  1017  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:15.553  7071  7071 E Zygote  : MountEmulatedStorage(),
09-07 15:29:15.553  7071  7071 I libpersona: KNOX_SDCARD checking this for 10068
09-07 15:29:15.553  7071  7071 E Zygote  : v2
09-07 15:29:15.553  7071  7071 I libpersona: KNOX_SDCARD not a persona
09-07 15:29:15.553  6946  7069 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 21.385625,
,09-07 15:29:15.553  1017  1546 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7071 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,09-07 15:29:15.563  6946  6946 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=760]
09-07 15:29:15.563  7071  7071 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 15:29:15.563  6946  6946 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
09-07 15:29:15.563  7071  7071 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 15:29:15.563  7071  7071 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-07 15:29:15.573  6946  6946 D Mms/MethodReflector: getSubId is called
09-07 15:29:15.573  6946  6946 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,09-07 15:29:15.573  6946  6946 D Mms/MethodReflector: getTelephonyProperty is called
09-07 15:29:15.573  6946  6946 D Mms/DownloadManager: roaming -> false (slotId = 0)
09-07 15:29:15.573  6946  6946 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
09-07 15:29:15.573  6946  6946 D Mms/DownloadManager: auto download without roaming -> true
09-07 15:29:15.573  6946  6946 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
09-07 15:29:15.573  6946  6946 D Mms/DownloadManager: mAutoDownload ------> true
,09-07 15:29:15.583  6946  7037 D Mms/ArtClassLoader: init [DONE] art
,09-07 15:29:15.583  6946  6946 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_ADDED
09-07 15:29:15.583  1017  1503 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
09-07 15:29:15.583  7071  7071 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 15:29:15.583  1017  1503 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
09-07 15:29:15.593  7071  7071 D ActivityThread: Added TimaKeyStore provider
09-07 15:29:15.593  1017  1503 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:15.593  1017  1503 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:15.593  1017  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,09-07 15:29:15.593  6970  6970 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-07 15:29:15.603  1017  1544 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
,09-07 15:29:15.613  6970  6970 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-07 15:29:15.613  6970  6970 D PhoneWindow: *FMB* installDecor flags : -2139027200
,09-07 15:29:15.623  6970  6970 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-07 15:29:15.633  1017  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:15.633  1017  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:15.633  6946  7086 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_ADDED
09-07 15:29:15.633  6946  7086 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_ADDED
,09-07 15:29:15.633  1017  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:15.633  1017  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:15.643  7088  7088 E Zygote  : MountEmulatedStorage()
09-07 15:29:15.643  7088  7088 E Zygote  : v2
09-07 15:29:15.643  7088  7088 I libpersona: KNOX_SDCARD checking this for 10042
09-07 15:29:15.643  7088  7088 I libpersona: KNOX_SDCARD not a persona
09-07 15:29:15.643  7088  7088 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 15:29:15.643  7088  7088 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 15:29:15.643  7088  7088 E SELinux : [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
,09-07 15:29:15.653  7071  7071 D BadgeProvider: onCreate
09-07 15:29:15.653  7071  7071 D BadgeProvider: DatabaseHelper
,09-07 15:29:15.653  1017  1544 I ActivityManager: Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=7088 uid=10042 gids={50042, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
,09-07 15:29:15.663  6970  6970 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-07 15:29:15.663  6970  6970 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-07 15:29:15.683  1017  3795 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.filterinstaller, hostingType: broadcast
,09-07 15:29:15.683  1017  3795 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:15.683  1017  3795 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:15.683  1017  3795 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:15.683  1017  3795 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:15.683  1908  3810 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,09-07 15:29:15.703  7088  7088 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 15:29:15.703  7088  7088 D ActivityThread: Added TimaKeyStore provider
,09-07 15:29:15.703  1017  3795 I ActivityManager: Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=7107 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,09-07 15:29:15.703  7107  7107 E Zygote  : MountEmulatedStorage(),
09-07 15:29:15.703  7107  7107 E Zygote  : v2
,09-07 15:29:15.703  7107  7107 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 15:29:15.703  7107  7107 I libpersona: KNOX_SDCARD checking this for 1000
09-07 15:29:15.703  7107  7107 I libpersona: KNOX_SDCARD not a persona
,09-07 15:29:15.713  1017  3795 I ActivityManager: Killing 6587:com.qualcomm.timeservice/1000 (adj 15): empty #21,
09-07 15:29:15.713  1017  3795 I ActivityManager: Killing 6538:com.android.providers.calendar/u0a37 (adj 15): empty #22
,09-07 15:29:15.713  7107  7107 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-07 15:29:15.713  7107  7107 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 15:29:15.743  6946  7068 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,09-07 15:29:15.743  1480  3320 D TP/SmsProvider: query,matched:26, calling pid = 6946
,09-07 15:29:15.753  1480  3320 D TP/SmsProvider: match 26:Elapsed time : 3.245 ms
,09-07 15:29:15.753  7088  7088 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-07 15:29:15.753  7088  7088 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-07 15:29:15.753  7088  7088 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-07 15:29:15.763  7107  7107 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 15:29:15.763  7107  7107 D ActivityThread: Added TimaKeyStore provider
,09-07 15:29:15.763  1017  1520 I ActivityManager: Killing 6609:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
,09-07 15:29:15.783  1480  1496 D TP/MmsSmsProvider: query,matched:6, calling pid = 6946
,09-07 15:29:15.783  1480  1496 D TP/MmsSmsProvider: match 6:Elapsed time : 1.640 ms
,09-07 15:29:15.803  6970  7126 D OpenGLRenderer: Render dirty regions requested: true
,09-07 15:29:15.813  7107  7107 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
,09-07 15:29:15.813  1017  1504 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-07 15:29:15.813  1017  1504 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-07 15:29:15.813  1017  1504 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
09-07 15:29:15.813  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-07 15:29:15.813  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,09-07 15:29:15.813  7107  7107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
,09-07 15:29:15.813  1017  3796 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
09-07 15:29:15.813  1017  3796 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
,09-07 15:29:15.813  1017  3796 W ActivityManager: userId = 0, bbcId = -10000
,09-07 15:29:15.813  1017  3796 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:15.813  1017  3796 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,09-07 15:29:15.823  1017  1544 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,09-07 15:29:15.823  1017  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:15.823  1017  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:15.823  1017  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:15.823  1017  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:15.823  7107  7107 I FilterInstaller: FilterPackageService : ACTION_CHANGED
,09-07 15:29:15.833  7128  7128 E Zygote  : MountEmulatedStorage()
09-07 15:29:15.833  7128  7128 E Zygote  : v2
09-07 15:29:15.833  7128  7128 I libpersona: KNOX_SDCARD checking this for 10023
,09-07 15:29:15.833  7128  7128 I libpersona: KNOX_SDCARD not a persona
,09-07 15:29:15.843  7128  7128 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 15:29:15.843  7128  7128 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 15:29:15.843  7128  7128 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 15:29:15.843  1017  1544 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=7128 uid=10023 gids={50023, 9997} abi=armeabi-v7a
,09-07 15:29:15.853  7107  7127 E FilterInstaller: installFilters
09-07 15:29:15.853  6970  6970 V ActivityThread: updateVisibility : ActivityRecord{90ebfd3 token=android.os.BinderProxy@105c020d {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-07 15:29:15.853  7107  7127 E FilterInstaller: There is no requred permission
09-07 15:29:15.853  6970  7051 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
09-07 15:29:15.863  6970  6970 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-07 15:29:15.863  6970  6970 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-07 15:29:15.863   309   309 I art     : Explicit concurrent mark sweep GC freed 8705(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 600us total 22.958ms
09-07 15:29:15.883  7128  7128 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 15:29:15.883   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
09-07 15:29:15.883   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 586us total 17.783ms
09-07 15:29:15.883  7128  7128 D ActivityThread: Added TimaKeyStore provider
09-07 15:29:15.893  1017  1501 I ActivityManager: Killing 6624:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
09-07 15:29:15.903  6807  7098 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-07 15:29:15.903  6807  7098 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
09-07 15:29:15.903  1017  1136 D InputDispatcher: Focus entered window: 6970
09-07 15:29:15.903   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 613us total 18.142ms
09-07 15:29:15.903  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-07 15:29:15.903  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
09-07 15:29:15.913  6970  6970 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
09-07 15:29:15.913  1908  3810 I Icing   : Indexing done D0AE1F45F393341DA3213A207506F1C2E721F1A9
09-07 15:29:15.913  1017  1504 I ActivityManager: Killing 5026:com.google.android.gms.wearable/u0a11 (adj 15): empty #21
09-07 15:29:15.913  6970  7126 I OpenGLRenderer: Initialized EGL, version 1.4
09-07 15:29:15.923  6970  7126 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
09-07 15:29:15.923  6970  7126 D OpenGLRenderer: Enabling debug mode 0
09-07 15:29:15.943  1017  1503 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
09-07 15:29:15.953  6807  7098 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
09-07 15:29:15.953  1175  1175 D PanelView: There is/are notification(s) 
09-07 15:29:15.953  1017  7147 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
09-07 15:29:15.963  1017  1047 I ActivityManager: Displayed Component not be shown by security: +1s316ms (total +1s467ms)
09-07 15:29:15.963  1017  1047 W ActivityManager: mDVFSHelper.release()
09-07 15:29:15.963  1017  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2aebb6d4 u0 com.test.thalitest/.MainActivity t163} time:99028
09-07 15:29:15.973  6970  6970 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
09-07 15:29:15.973  7128  7128 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
09-07 15:29:15.973   258   445 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
09-07 15:29:15.973   258  1097 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
09-07 15:29:15.983  6970  6970 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@105c020d time:99041
09-07 15:29:15.993  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
09-07 15:29:15.993  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:15.993  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 15:29:15.993  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-07 15:29:16.003  6946  7068 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
09-07 15:29:16.013  7128  7128 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
09-07 15:29:16.023  7128  7128 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
09-07 15:29:16.023  7128  7128 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
09-07 15:29:16.023  6807  7098 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
09-07 15:29:16.023  7128  7128 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
09-07 15:29:16.023  6807  7098 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@10b1b7e7: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
09-07 15:29:16.023  6807  7098 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
09-07 15:29:16.023  7128  7128 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
09-07 15:29:16.023  7128  7128 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
09-07 15:29:16.023  7128  7128 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
09-07 15:29:16.023  7128  7128 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
09-07 15:29:16.023  7128  7128 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
09-07 15:29:16.033  7128  7128 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
09-07 15:29:16.033  7128  7128 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
09-07 15:29:16.033  7128  7128 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
09-07 15:29:16.033  7128  7128 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
09-07 15:29:16.063  7088  7088 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
09-07 15:29:16.063  1017  1057 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
09-07 15:29:16.063  1017  1057 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
09-07 15:29:16.063  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:16.063  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:16.063  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:16.063  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:16.083  7150  7150 E Zygote  : MountEmulatedStorage()
09-07 15:29:16.083  7150  7150 I libpersona: KNOX_SDCARD checking this for 10003
09-07 15:29:16.083  7150  7150 E Zygote  : v2
09-07 15:29:16.083  7150  7150 I libpersona: KNOX_SDCARD not a persona
09-07 15:29:16.083  7150  7150 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 15:29:16.083  1017  1057 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7150 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
09-07 15:29:16.083  1017  1545 I splitIntent: Queue : backgroundsplit_0 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
09-07 15:29:16.083  1017  1545 I ActivityManager: Killing 6635:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
09-07 15:29:16.083  7150  7150 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 15:29:16.083  7150  7150 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-07 15:29:16.083  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
09-07 15:29:16.093  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:16.093  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:16.093  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:16.093  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:16.103  7160  7160 E Zygote  : MountEmulatedStorage()
09-07 15:29:16.103  7160  7160 E Zygote  : v2
09-07 15:29:16.103  7160  7160 I libpersona: KNOX_SDCARD checking this for 10130
09-07 15:29:16.103  7160  7160 I libpersona: KNOX_SDCARD not a persona
09-07 15:29:16.103  7160  7160 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 15:29:16.103  7160  7160 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 15:29:16.103  1017  1042 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=7160 uid=10130 gids={50130, 9997} abi=armeabi-v7a
09-07 15:29:16.103  7160  7160 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
09-07 15:29:16.103  1882  1882 I SamsungIME: getCurrentCandidateView
09-07 15:29:16.113  7150  7150 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 15:29:16.113  7150  7150 D ActivityThread: Added TimaKeyStore provider
09-07 15:29:16.123  7160  7160 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 15:29:16.133  7160  7160 D ActivityThread: Added TimaKeyStore provider
09-07 15:29:16.143  6970  6970 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6970
09-07 15:29:16.163  7160  7160 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-07 15:29:16.163  7160  7160 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
09-07 15:29:16.163   284   284 E installd: system dir 0 : /system/app/
09-07 15:29:16.163   284   284 E installd: system dir 1 : /system/priv-app/
09-07 15:29:16.163   284   284 E installd: system dir 2 : /vendor/app/
09-07 15:29:16.163   284   284 E installd: system dir 3 : /oem/app/
09-07 15:29:16.193  1017  1057 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
09-07 15:29:16.213  1017  1504 D ActivityManager: startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
09-07 15:29:16.213  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:16.213  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:16.213  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:16.213  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:16.223  7185  7185 E Zygote  : MountEmulatedStorage()
09-07 15:29:16.223  7185  7185 E Zygote  : v2
09-07 15:29:16.223  7185  7185 I libpersona: KNOX_SDCARD checking this for 10131
09-07 15:29:16.223  7185  7185 I libpersona: KNOX_SDCARD not a persona
09-07 15:29:16.223  7185  7185 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 15:29:16.233  1017  1504 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=7185 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
09-07 15:29:16.233  7185  7185 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 15:29:16.233  7185  7185 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-07 15:29:16.233  1017  1504 I ActivityManager: Killing 6660:com.samsung.helphub/1000 (adj 15): empty #21
09-07 15:29:16.243  1882  1882 D SamsungIME: Dismiss ExpandCandiate
09-07 15:29:16.253  7185  7185 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 15:29:16.253  7185  7185 D ActivityThread: Added TimaKeyStore provider
09-07 15:29:16.273  1017  1520 I ActivityManager: Killing 6669:com.sec.spp.push/u0a32 (adj 15): empty #21
09-07 15:29:16.283  7185  7185 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-07 15:29:16.283  7185  7185 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 15:29:16.283  7185  7185 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-07 15:29:16.323  1017  3785 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
09-07 15:29:16.323  1017  3785 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
09-07 15:29:16.323  1017  3785 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:16.323  1017  3785 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:16.323  1017  3785 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
09-07 15:29:16.333  2678  5025 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
09-07 15:29:16.353  1017  1544 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
09-07 15:29:16.353  1017  1544 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
09-07 15:29:16.353  1017  1544 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:16.353  1017  1544 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:16.353  1017  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
09-07 15:29:16.353  6970  6970 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
09-07 15:29:16.363  1017  1477 D ActivityManager: startProcessLocked calleePkgName: com.android.providers.calendar, hostingType: broadcast
09-07 15:29:16.363  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:16.363  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:16.363  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:16.363  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:16.373  7207  7207 E Zygote  : MountEmulatedStorage()
09-07 15:29:16.373  7207  7207 E Zygote  : v2
09-07 15:29:16.373  7207  7207 I libpersona: KNOX_SDCARD checking this for 10037
09-07 15:29:16.373  7207  7207 I libpersona: KNOX_SDCARD not a persona
09-07 15:29:16.373  7207  7207 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 15:29:16.383  7207  7207 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 15:29:16.383  7207  7207 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
09-07 15:29:16.393  1017  1477 I ActivityManager: Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=7207 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-07 15:29:16.413  7207  7207 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 15:29:16.413  7207  7207 D ActivityThread: Added TimaKeyStore provider
09-07 15:29:16.433  1017  1545 I ActivityManager: Killing 6744:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
09-07 15:29:16.443  7207  7207 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
09-07 15:29:16.473  6970  7149 D jxcore_app_log: JniHelper::setJavaVM(0xb75da2b0), pthread_self() = -1212783488
09-07 15:29:16.473  1882  1882 I SamsungIME: getDebugLevel  : 0x4f4c
09-07 15:29:16.483  6970  7149 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-07 15:29:16.483  6970  7149 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-07 15:29:16.483  6970  7149 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-07 15:29:16.483  6970  7149 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-07 15:29:16.483  6970  7149 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-07 15:29:16.483  6970  7149 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c533ee6 added. We now have 1 listener(s)
09-07 15:29:16.483  7207  7207 I CalendarProvider2: CalendarProvider2.onCreate() called
09-07 15:29:16.493  6970  7149 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
09-07 15:29:16.493  6970  7149 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-07 15:29:16.493  6970  7149 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 15:29:16.493  6970  7149 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 15:29:16.503  6970  7149 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-07 15:29:16.503  6970  7149 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-07 15:29:16.503  6970  7149 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-07 15:29:16.503  6970  7149 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
09-07 15:29:16.503  6970  7149 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-07 15:29:16.503  6970  7149 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-07 15:29:16.503  6970  7149 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-07 15:29:16.503  6970  7149 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-07 15:29:16.503  6970  7149 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-07 15:29:16.503  6970  7149 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-07 15:29:16.503  6970  7149 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-07 15:29:16.503  6970  7149 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-07 15:29:16.503  6970  7149 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-07 15:29:16.503  6970  7149 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-07 15:29:16.503  6970  7149 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@65e887d added. We now have 1 listener(s)
09-07 15:29:16.503  6970  7149 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 15:29:16.503  6970  7149 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 15:29:16.503  6970  7149 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-07 15:29:16.503  6970  7149 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-07 15:29:16.503  6970  7149 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-07 15:29:16.503  6970  7149 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-07 15:29:16.513  6970  7149 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 15:29:16.513  6970  7149 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
09-07 15:29:16.523  6970  7149 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-07 15:29:16.523  6970  7149 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 15:29:16.523  6970  7149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:16.523  6970  7149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:16.523  6970  7149 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:29:16.523  6970  7149 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:29:16.523  6970  7149 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 15:29:16.523  6970  7149 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 15:29:16.523  6970  7149 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 15:29:16.523  6970  7149 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-07 15:29:16.523  6970  7149 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 15:29:16.523  1882  1882 I SamsungIME: getDebugLevel  : 0x4f4c
09-07 15:29:16.523  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:29:16.533  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:29:16.533  6970  7149 I io.jxcore.node.LifeCycleMonitor: start: OK
09-07 15:29:16.533  1882  1882 I SamsungIME: KeybaordView init() : load resources
09-07 15:29:16.563  6713  6764 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
,09-07 15:29:16.563  6970  6970 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-07 15:29:16.563  1882  1882 I SamsungIME: getCurrentKeyboard
09-07 15:29:16.563  1882  1882 I SamsungIME: getTextKeyboard
,09-07 15:29:16.573  1017  1030 D ActivityManager: startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
09-07 15:29:16.573  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.CalendarProviderIntentService; callingUser = 0; userId(target) = 0
,09-07 15:29:16.573  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:16.573  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:16.573  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,09-07 15:29:16.583  6713  6764 I AcmsKeyStoreHelper: Key Store exist
09-07 15:29:16.583  6713  6764 I AcmsKeyStoreHelper: Hence loading the keystore file
,09-07 15:29:16.593  1017  1503 D ActivityManager: startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
,09-07 15:29:16.593  1017  1503 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,09-07 15:29:16.593  1017  1503 W ActivityManager: userId = 0, bbcId = -10000
,09-07 15:29:16.593  7207  7228 E SQLiteLog: (284) automatic index on view_events(_id)
09-07 15:29:16.593  1017  1503 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:16.593  1017  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,09-07 15:29:16.603  1882  1882 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-07 15:29:16.683  6713  6764 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
09-07 15:29:16.693  6713  6764 I AcmsCertificateMngr: getKeyStoreForApplication success 
09-07 15:29:16.693  6713  6764 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
09-07 15:29:16.693  6713  6764 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-07 15:29:16.693  6713  6764 D AcmsServiceMonitor: Decrementing - Counter value: 1
09-07 15:29:16.693  6713  6764 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
,09-07 15:29:16.693  6713  6764 D AcmsCore: This is NOT a valid MirrorLink app
09-07 15:29:16.693  6713  6764 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
09-07 15:29:16.693  6713  6764 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-07 15:29:16.693  6713  6764 D AcmsServiceMonitor: Decrementing - Counter value: 0
09-07 15:29:16.693  6713  6764 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
,09-07 15:29:16.693  6713  6713 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
09-07 15:29:16.693  6713  6713 D AcmsService: Enter onDestroy
09-07 15:29:16.693  6713  6713 I AcmsService: cleanUp(): inside service clean up
09-07 15:29:16.693  6713  6713 D AcmsCore: AcmsCore: inside DeInit
09-07 15:29:16.693  6713  6713 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
09-07 15:29:16.693  6713  6713 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
09-07 15:29:16.693  6713  6713 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
09-07 15:29:16.693  6713  6713 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
09-07 15:29:16.693  6713  6713 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
09-07 15:29:16.693  6713  6713 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
09-07 15:29:16.693  6713  6713 D AcmsService: killing acms process
09-07 15:29:16.693  6713  6713 I Process : Sending signal. PID: 6713 SIG: 9
,09-07 15:29:16.733  1017  3795 I ActivityManager: Process ACMS.Process (pid 6713)(adj 0) has died(28,784)
,09-07 15:29:16.753  1017  1136 I art     : Explicit concurrent mark sweep GC freed 19919(1078KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 3.624ms total 148.900ms
,09-07 15:29:16.763  7207  7228 D CalendarAlarmManager: sys current time:1473254956600
,09-07 15:29:16.763  7207  7228 D CalendarAlarmManager: reminder amount:0
,09-07 15:29:17.133  6970  7226 W jxcore-log: Initializing JXcore engine
09-07 15:29:17.133  6970  7226 W jxcore-log: JXcore engine is ready
,09-07 15:29:17.193  2014  2014 E audit   : type=1400 msg=audit(1473254957.193:205): avc:  denied  { ioctl } for  pid=7226 comm="Thread-1320" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-07 15:29:17.193  2014  2014 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
,09-07 15:29:17.193  2014  2014 E audit   : type=1300 msg=audit(1473254957.193:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9d1008f8 items=0 ppid=309 ppcomm=main pid=7226 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1320" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
09-07 15:29:17.193  2014  2014 E audit   : type=1320 msg=audit(1473254957.193:205): 
,09-07 15:29:17.213  6970  7226 W jxcore-log: Starting JXcore engine
,09-07 15:29:17.323  6970  7226 W jxcore-log: Platform android
09-07 15:29:17.323  6970  7226 W jxcore-log: 
09-07 15:29:17.323  6970  7226 W jxcore-log: Process ARCH arm
09-07 15:29:17.323  6970  7226 W jxcore-log: 
,09-07 15:29:17.503  6946  6946 I Mms/MmsApp:  start initViewCache mms
,09-07 15:29:17.503  6946  6946 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1949.597655
,09-07 15:29:17.513  6946  6946 D Mms/ComposeMessageFragment: fillCache, easy = false
,09-07 15:29:17.533  6970  7226 I jxcore-log: JXcore Cordova bridge is ready!
09-07 15:29:17.533  6970  7226 I jxcore-log: 
09-07 15:29:17.533  6970  7226 W jxcore-log: JXcore engine is started,
,09-07 15:29:17.543  6970  7149 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-07 15:29:17.543  6970  6970 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-07 15:29:17.593  7207  7207 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,09-07 15:29:17.603  1017  1136 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,09-07 15:29:17.603  1017  1136 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:17.603  1017  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:17.603  1017  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
09-07 15:29:17.603  1017  1255 I ActivityManager: Killing 6692:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
09-07 15:29:17.613  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:17.613  1017  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:17.613  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
09-07 15:29:17.613  1017  1520 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:17.613  1017  1520 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:17.613  1017  1520 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
09-07 15:29:17.623  1017  1545 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
09-07 15:29:17.623  1017  1545 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
09-07 15:29:17.623  1017  1545 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:17.623  1017  1545 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:17.623  1017  1545 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
09-07 15:29:17.623  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:17.623  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:17.623  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
09-07 15:29:17.633  6946  6946 D AbsListView: Get MotionRecognitionManager
09-07 15:29:17.633  1017  1546 D MotionRecognitionService:  ssp status : false
09-07 15:29:17.633  1017  1136 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
09-07 15:29:17.633  1017  1136 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
09-07 15:29:17.633  1017  1136 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:17.633  1017  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:17.633  1017  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,09-07 15:29:17.643  6946  6946 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 133.994115
,09-07 15:29:17.733  6946  6946 D Mms/BubbleViewCache: fillCache bubble = 1
,09-07 15:29:17.823   288   288 E SMD     : DCD OFF
,09-07 15:29:19.683  1679  1679 I ConfigService: onDestroy
,09-07 15:29:20.043  1017  3359 D SSRM:n  : SIOP:: AP = 410
,09-07 15:29:20.113  1017  3375 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-07 15:29:20.833   288   288 E SMD     : DCD OFF,
,09-07 15:29:22.893  1017  3785 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-07 15:29:22.893  1017  3785 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4261, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-07 15:29:22.893  1017  3785 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-07 15:29:22.893  1017  3785 D BatteryService: stay LED for charging
09-07 15:29:22.893  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-07 15:29:22.893  1017  1017 I MotionRecognitionService: Plugged
,09-07 15:29:22.893  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,09-07 15:29:22.893  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-07 15:29:22.903  1175  1175 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-07 15:29:22.903  1432  1432 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-07 15:29:22.903  1432  1432 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-07 15:29:22.913  3212  3212 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-07 15:29:22.913  3212  3352 D HeadsetStateMachine: Disconnected process message: 10
,09-07 15:29:22.923  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-07 15:29:22.923  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-07 15:29:22.933  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-07 15:29:22.933  1175  1175 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
09-07 15:29:22.933  1175  1175 D SViewCoverView: level :100 plugged : 2
,09-07 15:29:23.833   288   288 E SMD     : DCD OFF,
,09-07 15:29:24.543  1017  1057 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-07 15:29:25.153  1017  1328 E Watchdog: !@Sync 3
,09-07 15:29:25.813   329   329 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-07 15:29:25.813   329   329 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-07 15:29:26.203  1017  1057 D PackageManager: [MSG] MCS_UNBIND
,09-07 15:29:26.213  1017  1544 I ActivityManager: Killing 6146:com.samsung.android.sm/1000 (adj 15): empty #21
,09-07 15:29:26.833   288   288 E SMD     : DCD OFF
,09-07 15:29:29.833   288   288 E SMD     : DCD OFF,
,09-07 15:29:29.893  1017  1095 V AlarmManager: waitForAlarm result :4,
09-07 15:29:29.893  6970  7226 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-07 15:29:29.893  6970  7226 I jxcore-log: 
09-07 15:29:29.893  1017  1095 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,09-07 15:29:29.903  6970  7226 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-07 15:29:29.903  6970  7226 I jxcore-log: 
,09-07 15:29:29.903  6970  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 15:29:29.903  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:29.903  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:29.903  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:29:29.903  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:29:29.903  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 15:29:29.903  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 15:29:29.903  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 15:29:29.913  6970  7226 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 15:29:29.913  6970  7226 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-07 15:29:29.913  6970  7226 I jxcore-log: 
,09-07 15:29:29.923  6970  7226 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-07 15:29:29.923  6970  7226 I jxcore-log: 
,09-07 15:29:30.053  1017  1049 I PowerManagerService: [PWL] Off : 50s ago
,09-07 15:29:30.063  1017  3359 D SSRM:n  : SIOP:: AP = 380
,09-07 15:29:30.143  6857  7016 D Finsky  : [1289] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,09-07 15:29:30.143  6857  6857 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,09-07 15:29:30.613  6970  7226 D executeNativeTests: Running unit tests
,09-07 15:29:30.703  6970  7226 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 15:29:30.703  6970  7226 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dbf9036 added. We now have 2 listener(s)
,09-07 15:29:30.703  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-07 15:29:30.703  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 15:29:30.703  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 15:29:30.703  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 15:29:30.703  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38450b37 added. We now have 2 listener(s)
09-07 15:29:30.703  6970  7226 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 15:29:30.703  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 15:29:30.703  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 15:29:30.713  6970  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 15:29:30.713  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:30.713  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:30.713  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:29:30.713  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:29:30.713  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 15:29:30.713  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 15:29:30.713  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 15:29:30.713  6970  7226 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 15:29:30.713  6970  7226 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 15:29:30.713  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:29:30.713  6970  7226 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-07 15:29:30.713  6970  7226 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-07 15:29:30.723  6970  7226 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-07 15:29:30.723  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:29:30.723  6970  7226 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-07 15:29:30.723  6970  7226 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-07 15:29:30.723  6970  7226 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 15:29:30.723  6970  7226 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 15:29:30.723  6970  7226 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-07 15:29:30.723  6970  7226 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 15:29:30.723  6970  7226 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:29:30.723  6970  7226 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 15:29:30.723  6970  7226 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:29:30.723  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:30.723  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 15:29:30.723  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 15:29:30.723  6970  7226 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dbf9036 removed from the list
09-07 15:29:30.723  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:30.723  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38450b37 removed from the list
09-07 15:29:30.723  6970  7226 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:29:30.723  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 15:29:30.723  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:30.723  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 15:29:30.723  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:29:30.723  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:29:30.723  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:30.723  6970  7226 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38450b37 not in the list
,09-07 15:29:30.723  6970  7226 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-07 15:29:30.723  6970  7226 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 15:29:30.723  6970  7226 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:29:30.723  6970  7226 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:29:30.723  6970  7226 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:29:30.723  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:30.723  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:30.723  6970  7226 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dbf9036 not in the list
09-07 15:29:30.723  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:30.733  6970  7226 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38450b37 not in the list
09-07 15:29:30.733  6970  7226 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:29:30.733  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:30.733  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:30.733  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:30.733  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 15:29:30.733  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:29:30.733  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:29:30.733  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:30.733  6970  7226 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38450b37 not in the list
,09-07 15:29:30.733  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-07 15:29:30.733  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-07 15:29:30.733  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-07 15:29:30.733  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210],
09-07 15:29:30.733  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-07 15:29:30.733  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-07 15:29:30.733  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-07 15:29:30.733  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-07 15:29:30.733  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-07 15:29:30.733  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-07 15:29:30.733  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-07 15:29:30.733  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-07 15:29:30.733  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-07 15:29:30.733  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-07 15:29:30.733  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-07 15:29:30.733  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-07 15:29:30.733  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-07 15:29:30.733  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-07 15:29:30.733  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-07 15:29:30.733  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-07 15:29:30.733  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-07 15:29:30.733  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-07 15:29:30.733  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-07 15:29:30.733  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-07 15:29:30.733  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-07 15:29:30.733  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-07 15:29:30.733  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-07 15:29:30.733  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-07 15:29:30.733  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-07 15:29:30.733  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-07 15:29:30.733  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-07 15:29:30.733  6970  7226 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:29:30.733  6970  7226 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:29:30.733  6970  7226 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:29:30.733  6970  7226 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:29:30.733  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:30.733  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:30.733  6970  7226 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dbf9036 not in the list
09-07 15:29:30.733  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:30.733  6970  7226 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38450b37 not in the list
09-07 15:29:30.733  6970  7226 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:29:30.733  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:30.733  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:30.733  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:30.733  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:30.733  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:29:30.733  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:29:30.733  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:30.733  6970  7226 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38450b37 not in the list
09-07 15:29:30.733  6970  7226 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 15:29:30.743  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 15:29:30.743  6970  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 15:29:30.743  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:30.743  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:30.743  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:29:30.743  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:29:30.743  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 15:29:30.743  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 15:29:30.743  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 15:29:30.743  6970  7226 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 15:29:30.743  6970  7226 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 15:29:30.743  6970  7226 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 15:29:30.743  6970  7226 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 15:29:30.743  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 15:29:30.743  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 15:29:30.743  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 15:29:30.753  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-07 15:29:30.753  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:29:30.753  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:29:30.753  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-07 15:29:30.763  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-07 15:29:30.763  6970  7226 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-07 15:29:30.763  6970  7226 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-07 15:29:30.763  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-07 15:29:30.763  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-07 15:29:30.763  6970  7226 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-07 15:29:30.773  3212  3221 D BtGatt.GattService: registerClient() - UUID=33b4cb04-3bab-4c8d-b32a-58d3d9fa9010
,09-07 15:29:30.813  3212  3294 D BtGatt.GattService: onClientRegistered() - UUID=33b4cb04-3bab-4c8d-b32a-58d3d9fa9010, clientIf=6
09-07 15:29:30.813  6970  6979 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-07 15:29:30.813  3212  3349 D BtGatt.GattService: start scan with filters
09-07 15:29:30.813   329   329 I ServiceManager: Waiting for service AtCmdFwd...
,09-07 15:29:30.823  3212  3348 D BtGatt.ScanManager: handling starting scan
,09-07 15:29:30.823  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-07 15:29:30.823  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-07 15:29:30.823  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-07 15:29:30.823  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-07 15:29:30.823  3212  3348 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26244bf3
,09-07 15:29:30.833  6970  7226 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 15:29:30.833  6970  7226 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-07 15:29:30.833  6970  6970 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 15:29:30.833  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-07 15:29:30.833  3212  3294 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-07 15:29:30.833  3212  3294 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 15:29:30.833  3212  3348 D BtGatt.ScanManager: allow scan with filters
09-07 15:29:30.833  3212  3348 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-07 15:29:30.833  3212  3348 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,09-07 15:29:30.843  3212  3294 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-07 15:29:30.843  3212  3294 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 15:29:30.843  3212  3348 D BtGatt.ScanManager: Starting BLE batch scan
,09-07 15:29:30.843  3212  3348 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-07 15:29:30.843  3212  3294 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-07 15:29:30.843  3212  3294 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 15:29:30.853  6970  7226 I io.jxcore.node.ConnectionHelper: start: OK
,09-07 15:29:30.853  6970  7226 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 15:29:30.853  6970  7226 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-07 15:29:30.853  3212  3294 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-07 15:29:30.853  3212  3294 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 15:29:30.863  6970  7226 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-07 15:29:30.863  6970  7226 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-07 15:29:30.863  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:30.863  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 15:29:30.863  6970  7226 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 15:29:30.863  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 15:29:30.863  6970  7226 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 15:29:30.863  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-07 15:29:30.863  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 15:29:30.863  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-07 15:29:30.863  3212  3350 D BtGatt.GattService: stopScan() - queue size =1
,09-07 15:29:30.863  3212  3348 D BtGatt.ScanManager: filter size is 1
,09-07 15:29:30.863  3212  3348 D BtGatt.ScanManager: delete FilterIndex - 3
,09-07 15:29:30.863  3212  3294 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-07 15:29:30.863  3212  3294 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 15:29:30.863  3212  3348 D BtGatt.ScanManager: stopping BLe Batch
,09-07 15:29:30.873  3212  3221 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-07 15:29:30.873  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 15:29:30.873  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-07 15:29:30.873  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-07 15:29:30.873  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-07 15:29:30.873  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-07 15:29:30.873  6970  7226 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 15:29:30.873  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-07 15:29:30.873  3212  3294 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-07 15:29:30.873  3212  3294 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 15:29:30.873  3212  3348 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-07 15:29:30.873  6970  7226 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-07 15:29:30.873  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-07 15:29:30.883  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 15:29:30.883  3212  3294 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-07 15:29:30.883  3212  3294 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 15:29:30.883  6970  7226 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:29:30.883  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:30.883  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 15:29:30.883  6970  7226 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dbf9036 not in the list
09-07 15:29:30.883  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:30.883  6970  7226 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38450b37 not in the list
09-07 15:29:30.883  6970  7226 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:29:30.883  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:30.883  6970  7226 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-07 15:29:30.883  6970  6970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 15:29:30.883  6970  6970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 15:29:30.883  6970  6970 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 15:29:30.883  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 15:29:30.893  6970  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 15:29:30.893  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:30.893  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:30.893  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:29:30.893  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:29:30.893  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 15:29:30.893  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 15:29:30.893  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 15:29:30.893  6970  7226 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 15:29:30.893  6970  7226 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 15:29:30.893  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:29:30.893  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:29:30.893  6970  7226 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 15:29:30.903  6970  7226 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-07 15:29:30.903  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 15:29:30.903  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 15:29:30.903  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 15:29:30.903  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-07 15:29:30.903  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 15:29:30.913  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 15:29:30.913  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-07 15:29:30.913  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-07 15:29:30.913  6970  7226 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-07 15:29:30.913  3212  3221 D BtGatt.GattService: registerClient() - UUID=be8cc90b-3c6d-4215-8e5a-11670e9adbd8
,09-07 15:29:30.953  3212  3294 D BtGatt.GattService: onClientRegistered() - UUID=be8cc90b-3c6d-4215-8e5a-11670e9adbd8, clientIf=6
,09-07 15:29:30.953  6970  6981 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-07 15:29:30.963  3212  3349 D BtGatt.GattService: start scan with filters
,09-07 15:29:30.963  3212  3348 D BtGatt.ScanManager: handling starting scan
,09-07 15:29:30.963  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-07 15:29:30.963  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-07 15:29:30.963  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-07 15:29:30.963  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-07 15:29:30.963  6970  7226 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 15:29:30.963  3212  3294 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-07 15:29:30.963  3212  3294 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 15:29:30.963  3212  3348 D BtGatt.ScanManager: allow scan with filters
,09-07 15:29:30.963  3212  3348 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-07 15:29:30.963  3212  3348 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,09-07 15:29:30.963  6970  6970 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 15:29:30.973  6970  7226 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-07 15:29:30.973  3212  3294 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-07 15:29:30.973  3212  3294 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 15:29:30.973  3212  3348 D BtGatt.ScanManager: Starting BLE batch scan
,09-07 15:29:30.973  3212  3348 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-07 15:29:30.973  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 15:29:30.983  3212  3294 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-07 15:29:30.983  3212  3294 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 15:29:30.983  6970  7226 I io.jxcore.node.ConnectionHelper: start: OK
,09-07 15:29:30.983  6970  7226 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 15:29:30.983  6970  7226 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-07 15:29:30.993  3212  3294 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-07 15:29:30.993  3212  3294 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 15:29:30.993  6970  7226 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-07 15:29:30.993  6970  7226 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-07 15:29:30.993  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 15:29:30.993  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 15:29:30.993  6970  7226 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-07 15:29:30.993  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 15:29:30.993  6970  7226 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-07 15:29:30.993  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-07 15:29:31.003  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-07 15:29:31.003  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-07 15:29:31.003  3212  3350 D BtGatt.GattService: stopScan() - queue size =1
,09-07 15:29:31.003  3212  3348 D BtGatt.ScanManager: filter size is 1
,09-07 15:29:31.003  3212  3348 D BtGatt.ScanManager: delete FilterIndex - 4
,09-07 15:29:31.003  3212  3221 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-07 15:29:31.003  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-07 15:29:31.003  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-07 15:29:31.003  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-07 15:29:31.003  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-07 15:29:31.003  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-07 15:29:31.013  3212  3294 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-07 15:29:31.013  3212  3294 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 15:29:31.013  3212  3348 D BtGatt.ScanManager: stopping BLe Batch
,09-07 15:29:31.013  6970  7226 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 15:29:31.013  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 15:29:31.013  6970  7226 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 15:29:31.013  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 15:29:31.013  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 15:29:31.013  6970  6970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 15:29:31.013  6970  6970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 15:29:31.013  6970  6970 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 15:29:31.013  6970  7226 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:29:31.013  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:31.013  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 15:29:31.013  6970  7226 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dbf9036 not in the list
09-07 15:29:31.013  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:31.013  6970  7226 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38450b37 not in the list
09-07 15:29:31.013  6970  7226 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:29:31.013  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 15:29:31.013  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:31.013  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 15:29:31.013  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:29:31.013  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:29:31.013  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:31.013  6970  7226 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38450b37 not in the list
,09-07 15:29:31.013  3212  3294 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-07 15:29:31.013  3212  3294 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 15:29:31.023  6970  7226 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 15:29:31.023  3212  3348 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-07 15:29:31.023  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 15:29:31.023  3212  3294 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-07 15:29:31.023  3212  3294 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 15:29:31.033  6970  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 15:29:31.033  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:31.033  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:31.033  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:29:31.033  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:29:31.033  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 15:29:31.033  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 15:29:31.033  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 15:29:31.033  6970  7226 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 15:29:31.033  6970  7226 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 15:29:31.033  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:29:31.043  6970  7226 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 15:29:31.043  6970  7226 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 15:29:31.043  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 15:29:31.043  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 15:29:31.043  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 15:29:31.043  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:29:31.043  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-07 15:29:31.043  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 15:29:31.043  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 15:29:31.053  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-07 15:29:31.053  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-07 15:29:31.053  6970  7226 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-07 15:29:31.053  3212  3349 D BtGatt.GattService: registerClient() - UUID=6a3c1420-1164-4bd3-b438-9294b456c684
,09-07 15:29:31.093  3212  3294 D BtGatt.GattService: onClientRegistered() - UUID=6a3c1420-1164-4bd3-b438-9294b456c684, clientIf=6
,09-07 15:29:31.093  6970  6981 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-07 15:29:31.093  3212  3226 D BtGatt.GattService: start scan with filters
09-07 15:29:31.093  3212  3348 D BtGatt.ScanManager: handling starting scan
09-07 15:29:31.093  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-07 15:29:31.093  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-07 15:29:31.093  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-07 15:29:31.093  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-07 15:29:31.103  6970  7226 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
,09-07 15:29:31.103  3212  3294 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-07 15:29:31.103  6970  7226 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-07 15:29:31.103  6970  6970 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-07 15:29:31.103  3212  3294 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 15:29:31.103  3212  3348 D BtGatt.ScanManager: allow scan with filters
09-07 15:29:31.103  3212  3348 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-07 15:29:31.103  3212  3348 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,09-07 15:29:31.103  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 15:29:31.113  3212  3294 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-07 15:29:31.113  3212  3294 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 15:29:31.113  3212  3348 D BtGatt.ScanManager: Starting BLE batch scan
,09-07 15:29:31.113  3212  3348 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-07 15:29:31.113  6970  7226 I io.jxcore.node.ConnectionHelper: start: OK
,09-07 15:29:31.113  6970  7226 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 15:29:31.113  6970  7226 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-07 15:29:31.113  6970  7226 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-07 15:29:31.113  6970  7226 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-07 15:29:31.113  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:31.113  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 15:29:31.113  6970  7226 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-07 15:29:31.123  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 15:29:31.123  6970  7226 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 15:29:31.123  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 15:29:31.123  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 15:29:31.123  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-07 15:29:31.123  3212  3349 D BtGatt.GattService: stopScan() - queue size =1,
09-07 15:29:31.123  3212  3226 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-07 15:29:31.123  3212  3294 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-07 15:29:31.123  3212  3294 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
09-07 15:29:31.123  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 15:29:31.123  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-07 15:29:31.123  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-07 15:29:31.123  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-07 15:29:31.123  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-07 15:29:31.123  6970  7226 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 15:29:31.133  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 15:29:31.133  6970  7226 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 15:29:31.133  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-07 15:29:31.133  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 15:29:31.133  3212  3294 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
09-07 15:29:31.133  3212  3294 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 15:29:31.133  3212  3348 D BtGatt.ScanManager: filter size is 1
,09-07 15:29:31.133  3212  3348 D BtGatt.ScanManager: delete FilterIndex - 5
,09-07 15:29:31.133  6970  6970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 15:29:31.133  6970  6970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 15:29:31.143  6970  6970 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 15:29:31.143  6970  7226 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:29:31.143  6970  7226 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-07 15:29:31.143  6970  7226 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:29:31.143  6970  7226 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:29:31.143  6970  7226 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:29:31.143  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:31.143  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 15:29:31.143  6970  7226 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dbf9036 not in the list
09-07 15:29:31.143  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:31.143  6970  7226 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38450b37 not in the list
09-07 15:29:31.143  6970  7226 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:29:31.143  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 15:29:31.143  3212  3294 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-07 15:29:31.143  3212  3294 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 15:29:31.143  3212  3348 D BtGatt.ScanManager: stopping BLe Batch
,09-07 15:29:31.143  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 15:29:31.143  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 15:29:31.143  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 15:29:31.143  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-07 15:29:31.143  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 15:29:31.153  6970  7226 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38450b37 not in the list
,09-07 15:29:31.153  3212  3294 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-07 15:29:31.153  6970  7226 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-07 15:29:31.153  6970  7226 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:29:31.153  6970  7226 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:29:31.153  6970  7226 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:29:31.153  6970  7226 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 15:29:31.153  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:31.153  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:31.153  6970  7226 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dbf9036 not in the list
09-07 15:29:31.153  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:31.153  6970  7226 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38450b37 not in the list
09-07 15:29:31.153  6970  7226 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:29:31.153  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:31.153  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:31.153  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:31.153  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 15:29:31.153  3212  3294 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 15:29:31.153  3212  3348 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-07 15:29:31.153  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 15:29:31.153  3212  3294 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-07 15:29:31.153  3212  3294 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 15:29:31.153  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:29:31.153  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:31.153  6970  7226 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38450b37 not in the list
09-07 15:29:31.153  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-07 15:29:31.153  6970  7226 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 15:29:31.163  6970  7226 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:29:31.163  6970  7226 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:29:31.163  6970  7226 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:29:31.163  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:31.163  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:31.163  6970  7226 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dbf9036 not in the list
09-07 15:29:31.163  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:31.163  6970  7226 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38450b37 not in the list
09-07 15:29:31.163  6970  7226 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:29:31.163  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:31.163  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:31.163  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:31.163  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 15:29:31.163  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:29:31.163  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-07 15:29:31.163  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:31.163  6970  7226 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38450b37 not in the list
,09-07 15:29:31.163  6970  7226 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-07 15:29:31.163  6970  7226 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 15:29:31.163  6970  7226 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:29:31.163  6970  7226 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:29:31.163  6970  7226 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
09-07 15:29:31.163  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:31.163  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 15:29:31.163  6970  7226 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dbf9036 not in the list
09-07 15:29:31.163  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 15:29:31.163  6970  7226 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38450b37 not in the list
09-07 15:29:31.163  6970  7226 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 15:29:31.163  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:31.163  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:31.163  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:31.163  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 15:29:31.163  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:29:31.163  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:29:31.163  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 15:29:31.163  6970  7226 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38450b37 not in the list
09-07 15:29:31.163  6970  7226 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,09-07 15:29:31.163  6970  7226 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:29:31.163  6970  7226 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:29:31.163  6970  7226 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:29:31.163  6970  7226 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:29:31.163  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:31.163  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:31.163  6970  7226 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dbf9036 not in the list
09-07 15:29:31.163  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:31.163  6970  7226 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38450b37 not in the list
09-07 15:29:31.163  6970  7226 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:29:31.163  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:31.163  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:31.163  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:31.163  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:31.163  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:29:31.163  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:29:31.163  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:31.163  6970  7226 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38450b37 not in the list
09-07 15:29:31.163  6970  7226 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 15:29:31.163  6970  7226 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 15:29:31.163  6970  7226 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 15:29:31.163  6970  7226 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 15:29:31.163  6970  7226 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 15:29:31.163  6970  7226 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 15:29:31.163  6970  7226 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:29:31.163  6970  7226 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:29:31.163  6970  7226 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state alre,ady matches the desired outcome of this operation, skipping...
09-07 15:29:31.173  6970  7226 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:29:31.173  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:31.173  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:31.173  6970  7226 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dbf9036 not in the list
09-07 15:29:31.173  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:31.173  6970  7226 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38450b37 not in the list
09-07 15:29:31.173  6970  7226 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:29:31.173  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:31.173  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:31.173  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:31.173  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:31.173  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:29:31.173  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:29:31.173  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:31.173  6970  7226 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38450b37 not in the list
09-07 15:29:31.173  6970  7226 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 15:29:31.173  6970  7226 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,09-07 15:29:31.173  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-07 15:29:31.173  6970  7226 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55,
09-07 15:29:31.173  6970  7226 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-07 15:29:31.173  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-07 15:29:31.173  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-07 15:29:31.173  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210],
,09-07 15:29:31.173  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-07 15:29:31.173  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-07 15:29:31.173  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-07 15:29:31.173  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-07 15:29:31.173  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-07 15:29:31.173  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810],
,09-07 15:29:31.173  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-07 15:29:31.173  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-07 15:29:31.173  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-07 15:29:31.173  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-07 15:29:31.173  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310],
09-07 15:29:31.173  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-07 15:29:31.173  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-07 15:29:31.173  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610],
09-07 15:29:31.173  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-07 15:29:31.173  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-07 15:29:31.173  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-07 15:29:31.173  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-07 15:29:31.173  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-07 15:29:31.173  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,09-07 15:29:31.173  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-07 15:29:31.173  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-07 15:29:31.173  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,09-07 15:29:31.173  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-07 15:29:31.173  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-07 15:29:31.173  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-07 15:29:31.173  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910],
09-07 15:29:31.173  6970  7226 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-07 15:29:31.173  6970  7226 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 15:29:31.173  6970  7226 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,09-07 15:29:31.173  6970  7226 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-07 15:29:31.173  6970  7226 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 15:29:31.173  6970  7226 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,09-07 15:29:31.173  6970  7226 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 15:29:31.173  6970  7226 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 15:29:31.173  6970  7226 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-07 15:29:31.173  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-07 15:29:31.173  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,09-07 15:29:31.183  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-07 15:29:31.183  6970  7226 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-07 15:29:31.183  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-07 15:29:31.183  6970  7226 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-07 15:29:31.183  6970  7226 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-07 15:29:31.183  6970  7226 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-07 15:29:31.183  6970  7226 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:29:31.183  6970  7226 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:29:31.183  6970  7226 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:29:31.183  6970  7226 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:29:31.183  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:31.183  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:31.183  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-07 15:29:31.183  6970  7226 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dbf9036 not in the list
09-07 15:29:31.183  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:31.183  6970  7226 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38450b37 not in the list
09-07 15:29:31.183  6970  7226 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:29:31.183  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-07 15:29:31.183  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:31.183  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:31.183  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:31.183  6970  7243 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1384
09-07 15:29:31.183  6970  7242 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1384)
09-07 15:29:31.183  6970  7242 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1384)
09-07 15:29:31.183  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:29:31.183  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:29:31.183  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:31.183  6970  7226 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38450b37 not in the list
09-07 15:29:31.183  6970  7226 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-07 15:29:31.183  6970  7226 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:29:31.183  6970  7226 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:29:31.183  6970  7226 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:29:31.183  6970  7226 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:29:31.183  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:31.183  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:31.183  6970  7226 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dbf9036 not in the list
09-07 15:29:31.183  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:31.183  6970  7226 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38450b37 not in the list
,09-07 15:29:31.183  6970  7226 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:29:31.183  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:31.183  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:31.183  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:31.183  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:31.183  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 15:29:31.183  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:29:31.183  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:31.183  6970  7226 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38450b37 not in the list
09-07 15:29:31.183  6970  7226 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-07 15:29:31.183  6970  7226 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:29:31.183  6970  7226 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 15:29:31.183  6970  7226 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:29:31.183  6970  7226 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:29:31.183  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:31.183  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:31.183  6970  7226 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dbf9036 not in the list
09-07 15:29:31.193  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:31.193  6970  7226 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38450b37 not in the list
09-07 15:29:31.193  6970  7226 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:29:31.193  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:31.193  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:31.193  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:31.193  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:31.193  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:29:31.193  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:29:31.193  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:31.193  6970  7226 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38450b37 not in the list
,09-07 15:29:31.193  6970  7226 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-07 15:29:31.193  6970  7226 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-07 15:29:31.193  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 15:29:31.193  6970  7226 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-07 15:29:31.193  6970  7226 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-07 15:29:31.193  6970  7226 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-07 15:29:31.193  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-07 15:29:31.193  6970  7226 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-07 15:29:31.193  6970  7226 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-07 15:29:31.193  6970  7226 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-07 15:29:31.193  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 15:29:31.193  6970  7226 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-07 15:29:31.193  6970  7226 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:29:31.193  6970  7226 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:29:31.193  6970  7226 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:29:31.193  6970  7226 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 15:29:31.193  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:31.193  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:31.193  6970  7226 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dbf9036 not in the list
09-07 15:29:31.193  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:31.193  6970  7226 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38450b37 not in the list
09-07 15:29:31.193  6970  7226 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:29:31.193  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 15:29:31.193  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:31.193  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:31.193  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:31.193  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:29:31.193  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:29:31.193  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:31.193  6970  7226 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38450b37 not in the list
,09-07 15:29:31.193  6970  7226 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:29:31.193  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:31.193  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:31.193  6970  7226 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dbf9036 not in the list,
09-07 15:29:31.193  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:31.193  6970  7226 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38450b37 not in the list
09-07 15:29:31.193  6970  7226 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:29:31.193  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:31.193  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:31.193  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:31.193  6970  7226 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38450b37 not in the list
09-07 15:29:31.193  6970  7226 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:29:31.193  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:31.193  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:31.193  6970  7226 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dbf9036 not in the list
,09-07 15:29:31.193  6970  7226 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:29:31.193  6970  7226 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:29:31.193  6970  7226 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:29:31.193  6970  7226 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:29:31.193  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:31.193  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:31.193  6970  7226 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dbf9036 not in the list
09-07 15:29:31.193  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:31.193  6970  7226 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38450b37 not in the list,
09-07 15:29:31.193  6970  7226 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:29:31.193  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:31.193  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:31.193  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:31.193  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:31.193  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:29:31.193  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:29:31.193  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:31.193  6970  7226 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38450b37 not in the list
09-07 15:29:31.203  6970  7226 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-07 15:29:31.203  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 15:29:31.203  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-07 15:29:31.203  6970  7226 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-07 15:29:31.203  6970  7226 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-07 15:29:31.203  6970  7226 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-07 15:29:31.203  6970  7226 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 15:29:31.203  6970  7226 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:29:31.203  6970  7226 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-07 15:29:31.203  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-07 15:29:31.203  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-07 15:29:31.203  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:31.203  6970  7226 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-07 15:29:31.203  6970  6970 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-07 15:29:31.203  6970  7226 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dbf9036 not in the list
09-07 15:29:31.203  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:31.203  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 15:29:31.203  6970  7226 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 15:29:31.203  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 15:29:31.203  6970  6970 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-07 15:29:31.203  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:31.203  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 liste,ner(s) left
09-07 15:29:31.203  6970  7244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-07 15:29:31.203  6970  7244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-07 15:29:31.203  6970  7226 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 15:29:31.203  6970  7226 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38450b37 not in the list
09-07 15:29:31.203  6970  6970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 15:29:31.203  6970  7226 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:29:31.203  6970  6970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 15:29:31.203  6970  7226 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:29:31.203  6970  7226 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:29:31.203  6970  7226 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:29:31.203  6970  6970 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-07 15:29:31.203  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:31.203  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:31.203  6970  7226 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dbf9036 not in the list
09-07 15:29:31.203  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:31.203  6970  6970 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 15:29:31.203  6970  7226 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38450b37 not in the list
09-07 15:29:31.203  6970  7226 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:29:31.203  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:31.203  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:31.203  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:31.203  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:31.213  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:29:31.213  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:29:31.213  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:31.213  6970  7226 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38450b37 not in the list
09-07 15:29:31.223  6970  7226 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error mess,age: ErrorMessage
09-07 15:29:31.223  6970  7226 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-07 15:29:31.223  6970  7226 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 15:29:31.223  6970  7226 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 15:29:31.223  6970  7226 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:29:31.223  6970  7226 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:29:31.223  6970  7226 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:29:31.223  6970  7226 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:29:31.223  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:31.223  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:31.223  6970  7226 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dbf9036 not in the list
09-07 15:29:31.223  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:31.223  6970  7226 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38450b37 not in the list
09-07 15:29:31.223  6970  7226 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:29:31.223  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:31.223  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:31.223  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:31.223  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:31.223  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:29:31.223  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:29:31.223  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:31.223  6970  7226 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38450b37 not in the list
09-07 15:29:31.223  6970  7226 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:29:31.223  6970  7226 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:29:31.223  6970  7226 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:29:31.223  6970  7226 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:29:31.223  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:31.223  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:31.223  6970  7226 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dbf9036 not in the list
09-07 15:29:31.223  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:31.223  6970  7226 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38450b37 not in the list
09-07 15:29:31.223  6970  7226 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:29:31.223  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:31.223  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:31.223  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:31.223  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:31.223  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:29:31.223  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:29:31.223  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:31.223  6970  7226 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38450b37 not in the list
09-07 15:29:31.223  6970  7226 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:29:31.223  6970  7226 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:29:31.223  6970  7226 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:29:31.223  6970  7226 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:29:31.223  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:31.223  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:31.223  6970  7226 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dbf9036 not in the list
09-07 15:29:31.223  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:31.223  6970  7226 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38450b37 not in the list
09-07 15:29:31.223  6970  7226 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:29:31.223  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:31.223  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:31.223  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:31.223  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:31.223  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:29:31.223  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:29:31.223  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:31.223  6970  7226 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38450b37 not in the list
09-07 15:29:31.233  6970  7226 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-07 15:29:31.233  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 15:29:31.233  6970  7226 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-07 15:29:31.233  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 15:29:31.233  6970  7226 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-07 15:29:31.233  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 15:29:31.233  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-07 15:29:31.233  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-07 15:29:31.233  6970  7226 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-07 15:29:31.233  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-07 15:29:31.233  6970  7226 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-07 15:29:31.233  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-07 15:29:31.233  6970  7226 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-07 15:29:31.233  6970  7226 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-07 15:29:31.233  6970  7226 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-07 15:29:31.233  6970  7226 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-07 15:29:31.233  6970  7226 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-07 15:29:31.233  6970  7226 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-07 15:29:31.233  6970  7226 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-07 15:29:31.233  6970  7226 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-07 15:29:31.233  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 15:29:31.233  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@36261d41 added. We now have 2 listener(s)
09-07 15:29:31.233  6970  7226 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 15:29:31.233  6970  7226 D BluetoothAdapter: enable()
09-07 15:29:31.233  6970  7226 D BluetoothAdapter: enable(): BT is already enabled..!
09-07 15:29:31.233  1017  1255 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-07 15:29:31.243  1017  1255 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-07 15:29:31.243  1017  1255 D SecContentProvider2: mCursor = null
09-07 15:29:31.243  1017  1255 D WifiService: setWifiEnabled: true pid=6970, uid=10170
09-07 15:29:31.243  1017  1255 W ActivityManager: Permission Denial: getCurrentUser() from pid=6970, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-07 15:29:31.243  1017  1255 W WifiService: Failed getting userId using ActivityManagerNative
09-07 15:29:31.243  1017  1255 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6970, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-07 15:29:31.243  1017  1255 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-07 15:29:31.243  1017  1255 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-07 15:29:31.243  1017  1255 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-07 15:29:31.243  1017  1255 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-07 15:29:31.243  1017  1255 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-07 15:29:31.243  1017  1255 D SettingsProvider: name = wifi_on
09-07 15:29:31.243  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 15:29:31.243  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c6a72e6 added. We now have 3 listener(s)
09-07 15:29:31.243  6970  7226 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 15:29:31.243  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 15:29:31.253  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3c393027 added. We now have 4 listener(s)
09-07 15:29:31.253  6970  7226 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 15:29:31.253  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 15:29:31.253  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@362f92d4 added. We now have 5 listener(s)
09-07 15:29:31.253  6970  7226 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 15:29:31.253  1017  3795 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-07 15:29:31.253  1017  3795 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-07 15:29:31.253  1017  3795 D SecContentProvider2: mCursor = null
09-07 15:29:31.253  1017  3795 D WifiService: setWifiEnabled: false pid=6970, uid=10170
09-07 15:29:31.253  1017  3795 D SettingsProvider: name = wifi_on
,09-07 15:29:31.263  1017  1128 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-07 15:29:31.263  6970  7226 D BluetoothAdapter: disable()
09-07 15:29:31.263  1369  1369 I wpa_supplicant: reset timer : RESET_TIMER 0
09-07 15:29:31.263  1369  1369 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
09-07 15:29:31.263  1369  1369 I wpa_supplicant: P2P: Current p2p state = IDLE
09-07 15:29:31.263  1017  1520 D SettingsProvider: name = bluetooth_on
09-07 15:29:31.263  1369  1369 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
09-07 15:29:31.263  3212  3291 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
09-07 15:29:31.263  3212  3291 D BluetoothAdapterProperties: Setting state to 13
09-07 15:29:31.263  3212  3291 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-07 15:29:31.263  3212  3291 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-07 15:29:31.263  3212  3291 D BluetoothAdapterService: updateAdapterState state is 13
09-07 15:29:31.273  1017  3786 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 15:29:31.273  1017  3786 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
09-07 15:29:31.273  1017  3786 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:31.273  1017  3786 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:31.273  1017  3786 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-07 15:29:31.273  3212  3291 D BluetoothAdapterService: Autoconnection is available 
09-07 15:29:31.273  3212  3291 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-07 15:29:31.273  3212  3291 D BluetoothAdapterService: terminating service from this receiver
09-07 15:29:31.273  1017  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-07 15:29:31.273  1017  3785 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
09-07 15:29:31.273  3212  3212 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
09-07 15:29:31.273  1017  3785 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:31.273  1017  3785 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:31.273  1017  3785 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-07 15:29:31.273  3212  3212 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2fd88d22, channel: 19, state: LISTENING
09-07 15:29:31.273  3212  3212 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2fd88d22, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2938eeca, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2480a3b3mSocket: android.net.LocalSocket@c186d70 impl:android.net.LocalSocketImpl@2c5ee8e9 fd:FileDescriptor[74]
09-07 15:29:31.273  3212  3212 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@c186d70 impl:android.net.LocalSocketImpl@2c5ee8e9 fd:FileDescriptor[74]
09-07 15:29:31.273  3212  3291 D BluetoothAdapterProperties: onBluetoothDisable()
09-07 15:29:31.273  3212  3291 D BluetoothAdapterProperties: mDiscovering is false
09-07 15:29:31.273  1017  1255 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
09-07 15:29:31.273  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 15:29:31.273  3212  3291 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-07 15:29:31.283  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-07 15:29:31.283  1017  1017 I InputMethodManagerService: [BT Setting State] State =13
09-07 15:29:31.283  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:29:31.283  6970  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 15:29:31.283  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:31.283  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:31.283  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:29:31.283  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 15:29:31.283  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 15:29:31.283  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 15:29:31.283  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 15:29:31.283  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:29:31.283  6970  7226 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 15:29:31.283  6970  7226 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 15:29:31.293  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:29:31.293  1175  1175 D BluetoothTile:  onBluetoothStateChange:
09-07 15:29:31.293  1017  1128 E WifiNative-wlan0: do suspend true
09-07 15:29:31.293  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-07 15:29:31.293  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-07 15:29:31.293  1882  1882 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
09-07 15:29:31.293  1175  1175 D BluetoothTile:  getBluetoothState : 13
09-07 15:29:31.293  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:29:31.293  1017  1546 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-07 15:29:31.293  1175  1718 D BluetoothTile:  handleUpdatestate:false name:null
,09-07 15:29:31.293  4781  4781 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-07 15:29:31.293  1017  3785 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-07 15:29:31.303  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-07 15:29:31.303  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-07 15:29:31.303  1175  1718 D BluetoothTile:  handleUpdatestate:false name:null
,09-07 15:29:31.303  1175  1718 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-07 15:29:31.303  3212  3294 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-07 15:29:31.303  3212  3294 D BluetoothAdapterProperties: Scan Mode:20
,09-07 15:29:31.303  3212  3291 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-07 15:29:31.303  3212  3291 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,09-07 15:29:31.313  3212  3291 E bt-btif : cmd socket is not created
09-07 15:29:31.313  3212  5235 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-07 15:29:31.313  6970  6970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:29:31.313  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:29:31.313  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:31.313  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:31.313  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:29:31.313  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 15:29:31.313  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 15:29:31.313  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 15:29:31.313  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 15:29:31.313  3212  3291 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-07 15:29:31.313  6970  6970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:29:31.313  6970  6970 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 15:29:31.313  3212  3295 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,09-07 15:29:31.323  3212  3212 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1c96596e, channel: 5, state: LISTENING
09-07 15:29:31.323  3212  3212 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1c96596e, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@203b683b, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1457c80fmSocket: android.net.LocalSocket@32eef09c impl:android.net.LocalSocketImpl@31b42aa5 fd:FileDescriptor[76]
09-07 15:29:31.323  3212  3212 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@32eef09c impl:android.net.LocalSocketImpl@31b42aa5 fd:FileDescriptor[76]
,09-07 15:29:31.323  3212  3212 I BtOppRfcommListener: stopping Accept Thread
09-07 15:29:31.323  3212  3212 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2f529e7a, channel: 12, state: LISTENING
09-07 15:29:31.323  3212  3212 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2f529e7a, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@78aed, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1ed2d62bmSocket: android.net.LocalSocket@2d487a88 impl:android.net.LocalSocketImpl@2a61cc21 fd:FileDescriptor[80]
09-07 15:29:31.323  3212  3212 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2d487a88 impl:android.net.LocalSocketImpl@2a61cc21 fd:FileDescriptor[80]
09-07 15:29:31.323  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:29:31.323  3212  5235 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-07 15:29:31.323  4781  4781 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 15:29:31.323  1017  1029 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-07 15:29:31.323  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-07 15:29:31.323  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:29:31.323  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,09-07 15:29:31.323  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:29:31.323  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 15:29:31.323  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-07 15:29:31.333  3212  3295 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-07 15:29:31.333  3212  3295 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 15:29:31.333  3212  3295 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-07 15:29:31.333  3212  3295 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-07 15:29:31.333  3212  3295 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 15:29:31.333  3212  3295 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-07 15:29:31.333  4781  4781 D BluetoothPbap: Proxy object disconnected
09-07 15:29:31.333  3212  3212 V BluetoothOppManager: cleanUp...
09-07 15:29:31.333  4781  4781 D PbapServerProfile: Bluetooth service disconnected
,09-07 15:29:31.343  1679  1679 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 15:29:31.343  4781  4781 D DockEventReceiver: finishStartingService: stopping service
,09-07 15:29:31.343  4781  4781 D BluetoothNotiBroadcastReceiver: onReceive
,09-07 15:29:31.343  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-07 15:29:31.343  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-07 15:29:31.353  1017  1504 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-07 15:29:31.353  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:31.353  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:31.353  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:31.353  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:31.363  1017  1504 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7249 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,09-07 15:29:31.363  7249  7249 E Zygote  : MountEmulatedStorage(),
09-07 15:29:31.363  7249  7249 I libpersona: KNOX_SDCARD checking this for 10055
09-07 15:29:31.363  7249  7249 E Zygote  : v2
09-07 15:29:31.363  7249  7249 I libpersona: KNOX_SDCARD not a persona
,09-07 15:29:31.363  7249  7249 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-07 15:29:31.373  7249  7249 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-07 15:29:31.373  7249  7249 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-07 15:29:31.393  7249  7249 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 15:29:31.393  7249  7249 D ActivityThread: Added TimaKeyStore provider
,09-07 15:29:31.423  7249  7249 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-07 15:29:31.463  7249  7249 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,09-07 15:29:31.463  7249  7249 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
,09-07 15:29:31.463  7249  7249 D UserAnalysis: Create SecureDbHelper
,09-07 15:29:31.473  7249  7249 D IntelligenceServiceApplication: onCreate()
,09-07 15:29:31.473  1017  1136 I ActivityManager: Killing 6772:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
,09-07 15:29:31.483  1017  1136 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,09-07 15:29:31.483  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:31.483  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:31.483  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:31.483  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:31.483  7249  7249 D IntelligenceServiceApplication: no applications having user consent for prediction
,09-07 15:29:31.493  7264  7264 E Zygote  : MountEmulatedStorage()
,09-07 15:29:31.493  7264  7264 E Zygote  : v2
09-07 15:29:31.493  7264  7264 I libpersona: KNOX_SDCARD checking this for 10105
09-07 15:29:31.493  7264  7264 I libpersona: KNOX_SDCARD not a persona
,09-07 15:29:31.493  7264  7264 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-07 15:29:31.503  7264  7264 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-07 15:29:31.503  1017  1136 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7264 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,09-07 15:29:31.503  7264  7264 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-07 15:29:31.503  1017  1503 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-07 15:29:31.503  7249  7249 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.,
,09-07 15:29:31.513  7249  7249 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.,
,09-07 15:29:31.513  3212  3291 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-07 15:29:31.513  3212  3291 D BtConfig.SecureMode: isSecureModeOn:false
09-07 15:29:31.513  3212  3291 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-07 15:29:31.513  3212  3291 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
09-07 15:29:31.513  3212  3291 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
09-07 15:29:31.513  3212  3291 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
09-07 15:29:31.513  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-07 15:29:31.513  3212  3291 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-07 15:29:31.513  1017  3785 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 15:29:31.513  1017  3785 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-07 15:29:31.513  1017  3785 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:31.513  1017  3785 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 15:29:31.513  1017  3785 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 15:29:31.523  3212  3291 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
09-07 15:29:31.523  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-07 15:29:31.523  3212  3291 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-07 15:29:31.523  3212  3212 D HeadsetService: Received stop request...Stopping profile...
09-07 15:29:31.523  3212  3212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26244bf3
,09-07 15:29:31.523  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,09-07 15:29:31.523  4781  4781 D HeadsetProfile: Bluetooth service disconnected
,09-07 15:29:31.523  1017  1520 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 15:29:31.523  1017  1520 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-07 15:29:31.523  1017  1520 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:31.523  1017  1520 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:31.523  1017  1520 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 15:29:31.523  3212  3291 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
09-07 15:29:31.523  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-07 15:29:31.523  3212  3291 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-07 15:29:31.523  1017  1503 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 15:29:31.523  1017  1503 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-07 15:29:31.533  1017  1503 W ActivityManager: userId = 0, bbcId = -10000
,09-07 15:29:31.533  1017  1503 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 15:29:31.533  7264  7264 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 15:29:31.533  1017  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 15:29:31.533  7264  7264 D ActivityThread: Added TimaKeyStore provider
09-07 15:29:31.533  3212  3291 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
09-07 15:29:31.533  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-07 15:29:31.533  3212  3291 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-07 15:29:31.533  1017  1544 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-07 15:29:31.533  1017  1544 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-07 15:29:31.533  1017  1544 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:31.533  1017  1544 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:31.533  1017  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 15:29:31.543  3212  3291 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
09-07 15:29:31.543  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-07 15:29:31.543  3212  3291 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
09-07 15:29:31.543  1017  1501 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-07 15:29:31.543  1017  1501 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-07 15:29:31.543  1017  1501 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:31.543  1017  1501 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:31.543  1017  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 15:29:31.543  3212  3291 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
09-07 15:29:31.543  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-07 15:29:31.543  3212  3291 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-07 15:29:31.543  1017  1136 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 15:29:31.543  1017  1136 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-07 15:29:31.543  1017  1136 W ActivityManager: userId = 0, bbcId = -10000
,09-07 15:29:31.543  1017  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:31.543  1017  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 15:29:31.543  3212  3291 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
,09-07 15:29:31.543  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-07 15:29:31.553  3212  3291 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-07 15:29:31.553  1017  3785 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-07 15:29:31.553  1017  3785 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-07 15:29:31.553  1017  3785 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:31.553  1017  3785 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:31.553  1017  3785 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-07 15:29:31.553  3212  3291 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-07 15:29:31.553  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-07 15:29:31.553  3212  3291 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,09-07 15:29:31.553  3212  3291 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
,09-07 15:29:31.553  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-07 15:29:31.553  3212  3291 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-07 15:29:31.553  3212  3291 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
,09-07 15:29:31.553  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-07 15:29:31.553  3212  3291 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-07 15:29:31.553  3212  3291 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
09-07 15:29:31.553  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-07 15:29:31.553  3212  3291 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-07 15:29:31.553  3212  3291 D BluetoothAdapterState: Stopping profile services that were post enabled
09-07 15:29:31.553  3212  3212 E BluetoothAdapterService(639912947): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-07 15:29:31.553  3212  3212 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-07 15:29:31.553  3212  3212 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-07 15:29:31.573  3212  3212 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-07 15:29:31.573  3212  3212 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object,
,09-07 15:29:31.573  3212  3212 D A2dpService: Received stop request...Stopping profile...
09-07 15:29:31.573  3212  3354 D A2dpStateMachine: Exit Disconnected: -1
09-07 15:29:31.573  3212  3212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26244bf3
09-07 15:29:31.573  1017  1017 D BluetoothA2dp: Proxy object disconnected
09-07 15:29:31.573  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-07 15:29:31.573  4781  4781 D BluetoothA2dp: Proxy object disconnected
09-07 15:29:31.573  4781  4781 D A2dpProfile: Bluetooth service disconnected
,09-07 15:29:31.573  3212  3212 D HidService: Received stop request...Stopping profile...
09-07 15:29:31.573  3212  3212 D HidService: Stopping Bluetooth HidService
09-07 15:29:31.573  3212  3212 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-07 15:29:31.573  3212  3212 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-07 15:29:31.573  3212  3212 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-07 15:29:31.573  3212  3212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26244bf3
,09-07 15:29:31.573  4781  4781 D BluetoothInputDevice: Proxy object disconnected
09-07 15:29:31.573  4781  4781 D HidProfile: Bluetooth service disconnected
,09-07 15:29:31.573  3212  3212 D HealthService: Received stop request...Stopping profile...
,09-07 15:29:31.583  3212  3212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26244bf3
,09-07 15:29:31.583  3212  3212 D PanService: Received stop request...Stopping profile...
,09-07 15:29:31.583  3212  3212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26244bf3
,09-07 15:29:31.583  3212  3212 D BluetoothMapService: Received stop request...Stopping profile...
,09-07 15:29:31.583  1017  1017 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-07 15:29:31.583  3212  3212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26244bf3
,09-07 15:29:31.583  4781  4781 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-07 15:29:31.583  4781  4781 D PanProfile: Bluetooth service disconnected
,09-07 15:29:31.593  4781  4781 D BluetoothMap: Proxy object disconnected
,09-07 15:29:31.593  4781  4781 D MapProfile: Bluetooth service disconnected
09-07 15:29:31.593  3212  3212 D SapService: Received stop request...Stopping profile...
09-07 15:29:31.593  3212  3212 D SapService: Stopping Bluetooth SapService
,09-07 15:29:31.593  3212  3212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26244bf3
,09-07 15:29:31.593  3212  3212 E BluetoothAdapterService(639912947): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,09-07 15:29:31.593  3212  3212 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-07 15:29:31.593  3212  3212 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-07 15:29:31.593  3212  3212 D BluetoothA2dp: Proxy object disconnected
09-07 15:29:31.593  3212  3212 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
09-07 15:29:31.593  3212  3355 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating,
09-07 15:29:31.593  3212  3212 I GKI_LINUX: GKI_exit_task 2 done
09-07 15:29:31.593  3212  3212 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-07 15:29:31.593  3212  3212 E BluetoothAdapterService(639912947): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-07 15:29:31.593  3212  3212 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,09-07 15:29:31.593  3212  3212 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-07 15:29:31.593  3212  3212 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-07 15:29:31.593  3212  3212 E BluetoothAdapterService(639912947): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-07 15:29:31.593  3212  3212 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-07 15:29:31.593  3212  3212 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-07 15:29:31.593  3212  3212 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-07 15:29:31.593  3212  3212 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-07 15:29:31.593  3212  3212 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-07 15:29:31.593  3212  3212 E BluetoothAdapterService(639912947): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-07 15:29:31.593  3212  3212 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-07 15:29:31.593  3212  3212 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-07 15:29:31.593  3212  3212 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-07 15:29:31.593  3212  3212 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-07 15:29:31.593  3212  3212 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-07 15:29:31.593  4781  4781 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-07 15:29:31.593  4781  4781 D SapProfile: Bluetooth service disconnected
,09-07 15:29:31.593  3212  3212 E BluetoothAdapterService(639912947): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true,
09-07 15:29:31.593  3212  3212 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-07 15:29:31.593  3212  3212 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-07 15:29:31.593  3212  3212 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
09-07 15:29:31.593  3212  3212 E BluetoothAdapterService(639912947): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-07 15:29:31.593  3212  3212 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-07 15:29:31.593  3212  3212 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-07 15:29:31.593  3212  3212 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,09-07 15:29:31.603  3212  3291 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,09-07 15:29:31.603  3212  3291 D BluetoothAdapterProperties: Setting state to 10
09-07 15:29:31.603  3212  3291 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-07 15:29:31.603  3212  3291 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-07 15:29:31.603  3212  3291 D BluetoothAdapterService: updateAdapterState state is 10
09-07 15:29:31.603  3212  3291 D BluetoothAdapterService: Autoconnection is available 
09-07 15:29:31.603  3212  3291 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-07 15:29:31.603  3212  3291 I BluetoothAdapterState: Entering OffState
,09-07 15:29:31.603  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 15:29:31.603  4781  7278 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-07 15:29:31.603  6970  6979 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-07 15:29:31.603  6970  6979 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 15:29:31.603  6970  6979 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
,09-07 15:29:31.603  6970  6979 D BluetoothLeAdvertiser: Exit stop advertising
09-07 15:29:31.603  6970  6979 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-07 15:29:31.603  6970  6979 D BluetoothLeScanner: Exiting stopAllScan
,09-07 15:29:31.603  3212  3349 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-07 15:29:31.603  3212  3349 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 15:29:31.603  1175  1842 D BluetoothAdapter: onBluetoothStateChange: up=false
09-07 15:29:31.603  1175  1842 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-07 15:29:31.603  1755  2514 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-07 15:29:31.603  1755  2514 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-07 15:29:31.613  3212  3221 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-07 15:29:31.613  4781  4791 D BluetoothPbap: onBluetoothStateChange: up=false
,09-07 15:29:31.613  4781  4789 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-07 15:29:31.613  1453  1465 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-07 15:29:31.613  1453  1465 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 15:29:31.613  4781  7278 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-07 15:29:31.613  4781  7278 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 15:29:31.613  1480  3320 D BluetoothAdapter: onBluetoothStateChange: up=false
09-07 15:29:31.613  1480  3320 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-07 15:29:31.613  4781  4791 D BluetoothMap: onBluetoothStateChange: up=false
,09-07 15:29:31.613  1463  1488 D BluetoothAdapter: onBluetoothStateChange: up=false
09-07 15:29:31.613  1463  1488 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 15:29:31.623  1679  1696 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-07 15:29:31.623  1679  1696 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 15:29:31.623  4781  7278 D Bluetoothsap: onBluetoothStateChange: up=false
,09-07 15:29:31.623  4781  7278 D Bluetoothsap: Unbinding service...
,09-07 15:29:31.623  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-07 15:29:31.623  1017  1046 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 15:29:31.623  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-07 15:29:31.623  1017  1017 I InputMethodManagerService: [BT Setting State] State =10
,09-07 15:29:31.623  1017  1017 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-07 15:29:31.633  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-07 15:29:31.633  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-07 15:29:31.633  1175  1175 D BluetoothTile:  getBluetoothState : 10
,09-07 15:29:31.633  1882  1882 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-07 15:29:31.633  4781  4781 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-07 15:29:31.643  1017  1477 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-07 15:29:31.643  1017  1520 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-07 15:29:31.643  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:29:31.643  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-07 15:29:31.643  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:29:31.663  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-07 15:29:31.663   257   533 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-07 15:29:31.663   257   533 W Vold    : Returning OperationFailed - no handler for errno 0
,09-07 15:29:31.663  7264  7284 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-07 15:29:31.673   257   533 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-07 15:29:31.673   257   533 W Vold    : Returning OperationFailed - no handler for errno 0
,09-07 15:29:31.673  7264  7284 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-07 15:29:31.703  6970  6970 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 15:29:31.813   329   329 I ServiceManager: Waiting for service AtCmdFwd...
,09-07 15:29:31.823  1369  1369 I wpa_supplicant: nl80211: Received scan results (17 BSSes),
,09-07 15:29:31.823  1017  1127 D WifiP2pService: InactiveState{ what=147461 },
,09-07 15:29:31.823  1017  1127 D WifiP2pService: P2pEnabledState{ what=147461 }
,09-07 15:29:31.823  1017  1127 D WifiP2pService: DefaultState{ what=147461 }
,09-07 15:29:31.833  1017  1127 D WifiP2pService: InactiveState{ what=143375 }
09-07 15:29:31.833  1017  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-07 15:29:31.833   278   990 D CommandListener: Clearing all IP addresses on wlan0
,09-07 15:29:31.833  1175  1175 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 15:29:31.833  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-07 15:29:31.833  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:31.833  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:31.833  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:31.833  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:31.833  1679  2540 V NativeCrypto: Read error: ssl=0xb7b0a6e0: I/O error during system call, Connection timed out
09-07 15:29:31.843  1679  2540 V NativeCrypto: SSL shutdown failed: ssl=0xb7b0a6e0: I/O error during system call, Broken pipe
,09-07 15:29:31.843  1017  1130 E ConnectivityService: updateNetworkInfo()
,09-07 15:29:31.843  1017  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 15:29:31.843  1017  1130 E ConnectivityService: updateNetworkInfo()
,09-07 15:29:31.843  1017  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
09-07 15:29:31.843  1017  1127 D WifiP2pService: InactiveState{ what=131204 }
09-07 15:29:31.843  1017  1127 D WifiP2pService: P2pEnabledState{ what=131204 }
,09-07 15:29:31.843  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-07 15:29:31.843  1017  1127 D WifiP2pService: sending p2p connection changed broadcast: FAILED,
,09-07 15:29:31.843  1017  1751 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:29:31.843  1017  1545 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
09-07 15:29:31.843  1017  1751 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,09-07 15:29:31.843  1017  1751 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
,09-07 15:29:31.843  1017  1751 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:29:31.843  1017  1751 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
09-07 15:29:31.853  1017  1751 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-07 15:29:31.853  1017  1751 I qtaguid : Tagging socket 352 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1017, getuid(): 1000
,09-07 15:29:31.853  7264  7264 D StrictMode: StrictMode policy violation; ~duration=175 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at java.io.File.exists(File.java:363)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 15:29:31.853  7264  7264 D StrictMode: StrictMode policy violation; ~duration=174 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 15:29:31.853  7264  7264 D StrictMode: StrictMode policy violation; ~duration=173 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 15:29:31.853  7264  7264 D StrictMode: StrictMode policy violation; ~duration=171 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.q.k.a(PG:2107)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.q.e.b(PG:170)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 15:29:31.853  7264  7264 D StrictMode: StrictMode policy violation; ~duration=169 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.q.k.c(PG:18147)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.q.k.d(PG:583)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.q.e.b(PG:170)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 15:29:31.853  7264  7264 D StrictMode: StrictMode policy violation; ~duration=140 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at java.io.File.exists(File.java:363)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 15:29:31.853  7264  7264 D StrictMode: StrictMode policy violation; ~duration=139 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at java.io.File.exists(File.java:363)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 15:29:31.853  7264  7264 D StrictMode: StrictMode policy violation; ~duration=138 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at java.io.File.lastModified(File.java:571)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 15:29:31.853  7264  7264 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 15:29:31.863  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 15:29:31.863  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 1
09-07 15:29:31.863  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
09-07 15:29:31.863  1017  1017 D RttService: SCAN_AVAILABLE : 1
09-07 15:29:31.863  1017  1151 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:29:31.863  1017  1152 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:29:31.863  1017  1128 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-07 15:29:31.863  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-07 15:29:31.863  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 15:29:31.863  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-07 15:29:31.863  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:31.863  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:31.873  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:31.873  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:31.873  1017  1042 I ActivityManager: Killing 6807:com.google.android.apps.docs/u0a87 (adj 15): empty #21
09-07 15:29:31.873  1017  1751 I qtaguid : Untagging socket 352
09-07 15:29:31.873  1017  1751 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-07 15:29:31.873  1017  1127 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-07 15:29:31.883  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-07 15:29:31.883  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
09-07 15:29:31.883  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-07 15:29:31.883  4781  4781 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-07 15:29:31.883  1017  1127 D WifiP2pService: P2pDisablingState
09-07 15:29:31.883  1017  3786 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-07 15:29:31.883  1017  1127 D WifiP2pService: P2pDisablingState{ what=147458 }
09-07 15:29:31.883  1017  3786 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
09-07 15:29:31.883  1017  1127 D WifiP2pService: p2p socket connection lost
09-07 15:29:31.883  1017  1127 D WifiP2pService: P2pDisabledState
09-07 15:29:31.883  1017  1128 E WifiNative-wlan0: do suspend true
09-07 15:29:31.883  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-07 15:29:31.883  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-07 15:29:31.883  1017  1047 D WifiDisplayController: disconnect
09-07 15:29:31.883  1017  1047 D WifiDisplayController: updateConnection
09-07 15:29:31.883  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-07 15:29:31.883  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-07 15:29:31.883  1017  1127 D WifiP2pService: P2pDisabledState{ what=143375 }
09-07 15:29:31.883  1017  3786 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:31.883  1017  1127 D WifiP2pService: DefaultState{ what=143375 }
09-07 15:29:31.883  1017  3786 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:31.883  1017  3786 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
09-07 15:29:31.893  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-07 15:29:31.893  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
09-07 15:29:31.893  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-07 15:29:31.893  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
09-07 15:29:31.893  1175  1175 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-07 15:29:31.893  1017  1545 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-07 15:29:31.903  1175  1175 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
09-07 15:29:31.903  1679  1679 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 15:29:31.913   278   986 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-07 15:29:31.913   278   986 D Netd    : getNetworkForDns: using netid 0 for uid 1000
09-07 15:29:31.913   278   990 D CommandListener: Clearing all IP addresses on wlan0
09-07 15:29:31.913  1017  1130 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
09-07 15:29:31.913  1017  1130 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 15:29:31.913  1017  1130 V NetworkStats: updateIfacesLocked()
09-07 15:29:31.913  1017  1130 V NetworkStats: performPollLocked(flags=0x1)
09-07 15:29:31.913  1017  1130 D NetworkStatsFactory: UpdateStatsForKnox updated
09-07 15:29:31.913  1017  1130 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-07 15:29:31.913  1017  1751 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
09-07 15:29:31.913  1017  1751 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
09-07 15:29:31.913  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-07 15:29:31.913  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 15:29:31.913  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-07 15:29:31.913  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:31.913  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:31.913  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:31.913  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-07 15:29:31.923  4781  4781 D DockEventReceiver: finishStartingService: stopping service
09-07 15:29:31.923  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:31.923  1017  1130 V NetworkStats: performPollLocked() took 9ms
09-07 15:29:31.923  1017  1130 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 15:29:31.923  1369  1369 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
09-07 15:29:31.923  4781  4781 D BluetoothNotiBroadcastReceiver: onReceive
09-07 15:29:31.923  1017  1130 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
09-07 15:29:31.923  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 15:29:31.923  1017  1751 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:29:31.923  1017  1130 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 15:29:31.923  1175  1688 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-07 15:29:31.933  1017  1130 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
09-07 15:29:31.923  1017  1127 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-07 15:29:31.933  1017  1130 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
09-07 15:29:31.923  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 15:29:31.933  1017  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-07 15:29:31.933  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-07 15:29:31.933  1017  1128 D SecContentProvider2: mCursor = null
09-07 15:29:31.933  1480  1480 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-07 15:29:31.933  1480  1480 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 15:29:31.933  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-07 15:29:31.933  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 15:29:31.933  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-07 15:29:31.933  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:31.933  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:31.933  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:31.933  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:31.933  1017  1046 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-07 15:29:31.943  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-07 15:29:31.943  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 15:29:31.943  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-07 15:29:31.943  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 15:29:31.943  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,09-07 15:29:31.943  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:31.943  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-07 15:29:31.943  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:31.943  1175  1718 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-07 15:29:31.943  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-07 15:29:31.943  1175  1175 D HotspotTile: onReceive : 0, 0
09-07 15:29:31.943  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
09-07 15:29:31.943  4781  4781 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-07 15:29:31.943  7264  7294 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-07 15:29:31.953  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-07 15:29:31.953  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-07 15:29:31.953  1017  1130 D ConnectivityService: nai.networkMonitor.doQuit()
09-07 15:29:31.953  1017  1130 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 15:29:31.953  1017  1130 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-07 15:29:31.953  1017  1130 E ConnectivityService: updateNetworkInfo()
09-07 15:29:31.953  1017  1130 E ConnectivityService: updateNetworkInfo()
09-07 15:29:31.953  1017  1128 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-07 15:29:31.953  1017  1046 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-07 15:29:31.963  6970  6970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 15:29:31.963  1017  1017 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-07 15:29:31.963  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:29:31.963  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:31.963  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:31.963  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 15:29:31.963  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 15:29:31.963  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:29:31.963  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:29:31.963  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 15:29:31.963  1017  1131 D Tethering: MasterInitialState.processMessage what=3
,09-07 15:29:31.963  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 15:29:31.963  1017  1125 V NetworkStats: updateIfacesLocked()
09-07 15:29:31.963  1017  1125 V NetworkStats: performPollLocked(flags=0x1)
,09-07 15:29:31.963  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
09-07 15:29:31.963  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-07 15:29:31.963  6970  6970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 15:29:31.963  6970  6970 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 15:29:31.963  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 15:29:31.963  1017  1125 V NetworkStats: performPollLocked() took 6ms
09-07 15:29:31.963  1175  1175 D StatusBar.NetworkController: EthernetConnected: false
09-07 15:29:31.963  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-07 15:29:31.963  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-07 15:29:31.963  1175  1175 D StatusBar.NetworkController: updateDataNetType()
,09-07 15:29:31.973  6970  6970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 15:29:31.973  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:29:31.973  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:31.973  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:31.973  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 15:29:31.973  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 15:29:31.973  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:29:31.973  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:29:31.973  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 15:29:31.973  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 15:29:31.973  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 15:29:31.973  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 15:29:31.973  1017  1126 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-07 15:29:31.973  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 15:29:31.973  6970  6970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:29:31.973  6970  6970 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 15:29:31.973  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-07 15:29:31.973  1175  1175 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-07 15:29:31.973  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 15:29:31.973  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 15:29:31.983  1175  1175 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-07 15:29:31.983  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 24 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
09-07 15:29:31.983  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
09-07 15:29:31.983  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,09-07 15:29:31.983  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-07 15:29:31.983  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 15:29:31.983  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-07 15:29:31.983  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:31.983  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:31.983  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:31.983  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 15:29:31.983  1017  1136 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-07 15:29:31.983  1017  1136 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:31.983  1017  1136 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 15:29:31.983  1017  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-07 15:29:32.003  1017  1030 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-07 15:29:32.003  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-07 15:29:32.003  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:32.003  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:32.003  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-07 15:29:32.013  1369  1369 I wpa_supplicant: Blacklist: Clear (all) 
,09-07 15:29:32.013  1633  1633 I Hs20UtilService: Starting #8
,09-07 15:29:32.013  1633  1663 I Hs20UtilService: Message received 5007
,09-07 15:29:32.013  4781  4781 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-07 15:29:32.013  4781  4781 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-07 15:29:32.013  4781  4781 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-07 15:29:32.013  4781  4781 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-07 15:29:32.023  4781  4781 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-07 15:29:32.023  4781  4781 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-07 15:29:32.023  4781  4834 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-07 15:29:32.033  4781  4781 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-07 15:29:32.033  4781  4781 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-07 15:29:32.033  4781  4781 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-07 15:29:32.043  4781  4781 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-07 15:29:32.043  4781  4781 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-07 15:29:32.043  4781  4781 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-07 15:29:32.043  4781  4834 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-07 15:29:32.043  1017  1544 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,09-07 15:29:32.043  1017  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:32.043  1017  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:32.043  1017  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:32.043  1017  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:32.053  1369  1369 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-07 15:29:32.053  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
09-07 15:29:32.053  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,09-07 15:29:32.053  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
,09-07 15:29:32.053  7305  7305 E Zygote  : MountEmulatedStorage(),
,09-07 15:29:32.053  7305  7305 E Zygote  : v2
,09-07 15:29:32.063  7305  7305 I libpersona: KNOX_SDCARD checking this for 10064
09-07 15:29:32.063  7305  7305 I libpersona: KNOX_SDCARD not a persona
,09-07 15:29:32.063  1017  1544 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7305 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,09-07 15:29:32.063  7305  7305 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 15:29:32.063  7305  7305 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 15:29:32.073  7305  7305 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 15:29:32.073  1369  1369 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,09-07 15:29:32.073  1369  1369 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-07 15:29:32.073  1369  1369 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-07 15:29:32.073  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-07 15:29:32.073  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
09-07 15:29:32.073  1369  1369 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
,09-07 15:29:32.073  1369  1369 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
09-07 15:29:32.073  1017  1131 D Tethering: InitialState.processMessage what=4
09-07 15:29:32.073  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-07 15:29:32.073  1017  1131 E Tethering: No numeric data
09-07 15:29:32.073  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-07 15:29:32.073  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
09-07 15:29:32.073  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-07 15:29:32.083  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-07 15:29:32.083  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-07 15:29:32.083  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
09-07 15:29:32.083  1017  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-07 15:29:32.083  1017  1131 D Tethering: clearTetheredNotification()
,09-07 15:29:32.083  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 15:29:32.083  1017  1125 V NetworkStats: performPollLocked(flags=0x1)
,09-07 15:29:32.083  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
09-07 15:29:32.083  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-07 15:29:32.083  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED,
09-07 15:29:32.083  1175  1175 D HotspotTile: updateTetherState():false, false
,09-07 15:29:32.083  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 15:29:32.083  1017  1125 V NetworkStats: performPollLocked() took 4ms
09-07 15:29:32.083  1480  1480 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-07 15:29:32.083  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 15:29:32.083  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 15:29:32.093  1480  1480 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-07 15:29:32.093  1480  1480 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-07 15:29:32.093  1480  1480 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-07 15:29:32.093  1480  1480 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
09-07 15:29:32.093  7305  7305 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 15:29:32.093  7305  7305 D ActivityThread: Added TimaKeyStore provider
09-07 15:29:32.093  1480  1480 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-07 15:29:32.093  1480  1480 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-07 15:29:32.093  1480  1480 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-07 15:29:32.093  1480  1480 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-07 15:29:32.103  1480  1480 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-07 15:29:32.103  1480  1480 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-07 15:29:32.103  1480  1480 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-07 15:29:32.103  1480  1480 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-07 15:29:32.103  1480  1480 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-07 15:29:32.103  1480  1480 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-07 15:29:32.103  1480  1480 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-07 15:29:32.103  1480  1480 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-07 15:29:32.113  1480  1480 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-07 15:29:32.113  7305  7305 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-07 15:29:32.113  1480  1480 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-07 15:29:32.113  1480  1480 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-07 15:29:32.113  1480  1480 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-07 15:29:32.113  1480  1480 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-07 15:29:32.113  1480  1480 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-07 15:29:32.113  1480  1480 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-07 15:29:32.113  1480  1480 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-07 15:29:32.113  1480  1480 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-07 15:29:32.113  1480  1480 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-07 15:29:32.113  1480  1480 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-07 15:29:32.113  1480  1480 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-07 15:29:32.123  1480  1480 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-07 15:29:32.123  7305  7305 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-07 15:29:32.133  7305  7305 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-07 15:29:32.153  7305  7305 D FileShare-Client: Outbound.stopDelayTimer - 
,09-07 15:29:32.153  1017  1545 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,09-07 15:29:32.153  1017  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:32.163  1017  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:32.163  1017  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:32.163  1017  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:32.163  1017  1095 V AlarmManager: waitForAlarm result :4
,09-07 15:29:32.173  7336  7336 E Zygote  : MountEmulatedStorage()
,09-07 15:29:32.173  7336  7336 E Zygote  : v2
,09-07 15:29:32.173  7336  7336 I libpersona: KNOX_SDCARD checking this for 10065
09-07 15:29:32.173  7336  7336 I libpersona: KNOX_SDCARD not a persona
,09-07 15:29:32.173  7336  7336 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 15:29:32.173  1017  1545 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7336 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,09-07 15:29:32.173  7336  7336 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 15:29:32.173  1017  1545 I ActivityManager: Killing 6780:com.google.android.partnersetup/u0a14 (adj 15): empty #21
,09-07 15:29:32.173  7336  7336 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 15:29:32.193  7336  7336 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 15:29:32.193  7336  7336 D ActivityThread: Added TimaKeyStore provider
,09-07 15:29:32.213  7336  7336 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-07 15:29:32.223  1017  1545 I ActivityManager: Killing 6828:com.sec.pcw.device/1000 (adj 15): empty #21
,09-07 15:29:32.223  1017  1545 W ActivityManager: userId = 0, bbcId = -10000
,09-07 15:29:32.223  1017  1545 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 15:29:32.223  1017  1545 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
09-07 15:29:32.223  1017  1545 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,09-07 15:29:32.223  1017  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:32.223  1017  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:32.223  1017  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:32.223  1017  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:32.233  7351  7351 E Zygote  : MountEmulatedStorage(),
,09-07 15:29:32.243  7351  7351 E Zygote  : v2
09-07 15:29:32.243  7351  7351 I libpersona: KNOX_SDCARD checking this for 10102
09-07 15:29:32.243  7351  7351 I libpersona: KNOX_SDCARD not a persona
,09-07 15:29:32.243  7351  7351 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 15:29:32.243  7351  7351 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 15:29:32.243  1017  1545 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7351 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
09-07 15:29:32.243  7351  7351 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-07 15:29:32.263  7351  7351 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 15:29:32.263  7351  7351 D ActivityThread: Added TimaKeyStore provider
,09-07 15:29:32.273  7351  7351 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-07 15:29:32.373  1369  1369 I wpa_supplicant: Blacklist: Clear (all) 
,09-07 15:29:32.443  1369  1369 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-07 15:29:32.443  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-07 15:29:32.443  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-07 15:29:32.443  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-07 15:29:32.453  1017  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 15:29:32.463  1017  1017 I ApplicationPolicy: updateDataUsageMap
,09-07 15:29:32.473  6970  6970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:29:32.473  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:29:32.473  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:32.473  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:32.473  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 15:29:32.473  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 15:29:32.473  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:29:32.473  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:29:32.473  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 15:29:32.473  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:29:32.493  1017  1041 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-07 15:29:32.503  7351  7371 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
09-07 15:29:32.503  7351  7371 I Babel_SMS: MmsConfig.loadMmsSettings
09-07 15:29:32.503  7351  7371 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
09-07 15:29:32.503  7351  7371 I Babel_SMS: MmsConfig.loadFromDatabase
,09-07 15:29:32.543  7351  7371 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,09-07 15:29:32.543  7351  7371 I Babel_SMS: MmsConfig.loadFromResources
,09-07 15:29:32.543  1017  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,09-07 15:29:32.543  1017  1128 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-07 15:29:32.543  7351  7371 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,09-07 15:29:32.543  7351  7371 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,09-07 15:29:32.553  1755  2203 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 15:29:32.563  4781  4781 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-07 15:29:32.563  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-07 15:29:32.563  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 15:29:32.563  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-07 15:29:32.563  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:32.563  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:32.563  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:32.563  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:32.563  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-07 15:29:32.563  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-07 15:29:32.563  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,09-07 15:29:32.563  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-07 15:29:32.563  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:29:32.563  1017  1546 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
09-07 15:29:32.563  1017  1546 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,09-07 15:29:32.563  1175  1718 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-07 15:29:32.573  1017  1546 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:32.573  1017  1546 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 15:29:32.573  1017  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-07 15:29:32.573  1175  1175 D HotspotTile: onReceive : 1, 0
,09-07 15:29:32.583  7351  7351 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 15:29:32.593  7351  7351 I Babel_Crash: startup - clean
,09-07 15:29:32.623  1017  3795 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-07 15:29:32.623  1017  3795 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-07 15:29:32.623  1017  3795 W ActivityManager: userId = 0, bbcId = -10000
,09-07 15:29:32.623  1017  3795 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:32.623  1017  3795 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-07 15:29:32.623  1633  1633 I Hs20UtilService: Starting #9
,09-07 15:29:32.623  4781  4781 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-07 15:29:32.623  1633  1663 I Hs20UtilService: Message received 5007
,09-07 15:29:32.623  4781  4781 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-07 15:29:32.623  4781  4781 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-07 15:29:32.633  4781  4781 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-07 15:29:32.633  4781  4781 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-07 15:29:32.633  4781  4781 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-07 15:29:32.633  4781  4834 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-07 15:29:32.633  1017  1504 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-07 15:29:32.633  1017  1504 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-07 15:29:32.633  1017  1504 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:32.633  1017  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:32.633  1017  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-07 15:29:32.643  1633  1633 I Hs20UtilService: Starting #10
09-07 15:29:32.643  1633  1663 I Hs20UtilService: Message received 5011
09-07 15:29:32.643  1017  3786 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,09-07 15:29:32.643  1017  3786 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:32.643  1017  3786 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:32.643  1017  3786 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:32.643  1017  3786 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:32.643  7351  7351 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-07 15:29:32.653  7374  7374 E Zygote  : MountEmulatedStorage()
09-07 15:29:32.653  7374  7374 E Zygote  : v2
09-07 15:29:32.653  7374  7374 I libpersona: KNOX_SDCARD checking this for 1000
09-07 15:29:32.653  7374  7374 I libpersona: KNOX_SDCARD not a persona
,09-07 15:29:32.653  1017  3786 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=7374 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-07 15:29:32.653  7374  7374 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 15:29:32.653  7374  7374 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 15:29:32.653  7374  7374 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 15:29:32.653  7351  7351 W AudioCapabilities: Unsupported mime audio/evrc
,09-07 15:29:32.663  7351  7351 W AudioCapabilities: Unsupported mime audio/qcelp
,09-07 15:29:32.663  7351  7351 W AudioCapabilities: Unsupported mime audio/mpeg-L1
09-07 15:29:32.663  7351  7351 W AudioCapabilities: Unsupported mime audio/mpeg-L2
09-07 15:29:32.663  7351  7351 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-07 15:29:32.663  7351  7351 W AudioCapabilities: Unsupported mime audio/x-ima
,09-07 15:29:32.683  7351  7351 W AudioCapabilities: Unsupported mime audio/qcelp
09-07 15:29:32.683  7351  7351 W AudioCapabilities: Unsupported mime audio/evrc
,09-07 15:29:32.693  7374  7374 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 15:29:32.693  7374  7374 D ActivityThread: Added TimaKeyStore provider
,09-07 15:29:32.693  7351  7351 W VideoCapabilities: Unsupported mime video/wvc1
,09-07 15:29:32.703  7351  7351 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-07 15:29:32.703  7351  7351 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,09-07 15:29:32.713  7351  7351 W VideoCapabilities: Unsupported mime video/wvc1
,09-07 15:29:32.713  7351  7351 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-07 15:29:32.713  7351  7351 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,09-07 15:29:32.713  7351  7351 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,09-07 15:29:32.713  7351  7351 W VideoCapabilities: Unsupported mime video/mp43
,09-07 15:29:32.723  7351  7351 W VideoCapabilities: Unsupported mime video/sorenson
,09-07 15:29:32.723  7351  7351 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-07 15:29:32.733  7374  7374 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-07 15:29:32.733  7374  7374 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-07 15:29:32.733  7374  7374 D SecurityLogAgent: StateMachine : Current State = 1
,09-07 15:29:32.733  7374  7374 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-07 15:29:32.733  1017  3796 I ActivityManager: Killing 6733:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,09-07 15:29:32.743  1017  3796 W ActivityManager: userId = 0, bbcId = -10000
,09-07 15:29:32.743  1017  3796 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:32.743  1017  3796 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 15:29:32.753  7351  7351 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-07 15:29:32.763  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,09-07 15:29:32.763  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:32.763  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 15:29:32.763  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,09-07 15:29:32.763  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:32.763  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 15:29:32.773  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,09-07 15:29:32.773  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:32.773  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 15:29:32.773  7351  7351 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-07 15:29:32.773  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:32.773  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:32.773  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 15:29:32.773  7351  7351 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-07 15:29:32.773  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:32.773  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:32.773  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 15:29:32.783  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:32.783  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:32.783  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 15:29:32.783  7351  7351 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-07 15:29:32.783  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:32.783  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:32.783  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 15:29:32.783  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:32.783  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:32.783  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 15:29:32.783  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:32.783  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:32.783  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 15:29:32.783  7351  7351 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-07 15:29:32.793  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:32.793  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:32.793  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 15:29:32.793  1017  1501 I ActivityManager: Killing 6904:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
,09-07 15:29:32.793  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:32.793  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:32.793  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 15:29:32.793  7351  7351 I vclib   : onServiceConnected
,09-07 15:29:32.793  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:32.793  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:32.793  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 15:29:32.803  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:32.803  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:32.803  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 15:29:32.803  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,09-07 15:29:32.803  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:32.803  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 15:29:32.813  1017  1136 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-07 15:29:32.813  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:32.813  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:32.813  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:32.813  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:32.813   278   986 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-07 15:29:32.813   278   986 D Netd    : getNetworkForDns: using netid 0 for uid 10011
09-07 15:29:32.813   329   329 I ServiceManager: Waiting for service AtCmdFwd...
,09-07 15:29:32.823  7394  7394 E Zygote  : MountEmulatedStorage()
09-07 15:29:32.823  7394  7394 I libpersona: KNOX_SDCARD checking this for 1000
09-07 15:29:32.823  7394  7394 E Zygote  : v2
09-07 15:29:32.823  7394  7394 I libpersona: KNOX_SDCARD not a persona
,09-07 15:29:32.823  7394  7394 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 15:29:32.823  7394  7394 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 15:29:32.833  7394  7394 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 15:29:32.833   288   288 E SMD     : DCD OFF
09-07 15:29:32.833  1017  1136 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7394 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-07 15:29:32.843  7394  7394 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 15:29:32.843  7394  7394 D ActivityThread: Added TimaKeyStore provider
,09-07 15:29:32.853   309   309 I art     : Explicit concurrent mark sweep GC freed 8692(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 596us total 21.787ms
,09-07 15:29:32.873  7394  7394 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,09-07 15:29:32.873  7394  7394 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
09-07 15:29:32.873  7394  7394 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-07 15:29:32.873   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 593us total 16.384ms,
,09-07 15:29:32.893  7394  7394 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-07 15:29:32.893  7394  7394 I PCWCLIENTTRACE_PushUtil: sales region : global
09-07 15:29:32.893  7394  7394 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-07 15:29:32.893  7394  7394 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-07 15:29:32.893   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 578us total 17.112ms
,09-07 15:29:32.893  1017  1544 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
,09-07 15:29:32.893  1017  1544 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
09-07 15:29:32.893  1017  1544 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
09-07 15:29:32.893  1017  1544 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,09-07 15:29:32.893  1017  1544 I ActivityManager: Killing 6932:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
,09-07 15:29:32.903  7394  7409 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,09-07 15:29:32.903  1017  1017 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,09-07 15:29:32.903  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:32.903  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:32.903  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:32.903  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:32.913  7411  7411 E Zygote  : MountEmulatedStorage()
09-07 15:29:32.913  7411  7411 I libpersona: KNOX_SDCARD checking this for 10001
09-07 15:29:32.913  7411  7411 E Zygote  : v2
09-07 15:29:32.913  7411  7411 I libpersona: KNOX_SDCARD not a persona
,09-07 15:29:32.913  7411  7411 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 15:29:32.923  7411  7411 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-07 15:29:32.923  7411  7411 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 15:29:32.923  1017  1017 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7411 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,09-07 15:29:32.943  1017  1503 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-07 15:29:32.943  1017  1503 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4212, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-07 15:29:32.943  1017  1503 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-07 15:29:32.943  1017  1503 D BatteryService: stay LED for charging
09-07 15:29:32.943  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-07 15:29:32.943  1017  1017 I MotionRecognitionService: Plugged
,09-07 15:29:32.943  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,09-07 15:29:32.953  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-07 15:29:32.953  1175  1175 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-07 15:29:32.953  7411  7411 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 15:29:32.953  7411  7411 D ActivityThread: Added TimaKeyStore provider
,09-07 15:29:32.953  1432  1432 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-07 15:29:32.953  1432  1432 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-07 15:29:32.973  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-07 15:29:32.973  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-07 15:29:32.973  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-07 15:29:32.973  1175  1175 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
09-07 15:29:32.973  1175  1175 D SViewCoverView: level :100 plugged : 2
,09-07 15:29:33.033  1017  1545 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,09-07 15:29:33.033  1017  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:33.033  1017  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:33.033  1017  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:33.033  1017  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:33.053  7429  7429 E Zygote  : MountEmulatedStorage(),
09-07 15:29:33.053  1017  1545 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7429 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-07 15:29:33.053  7429  7429 E Zygote  : v2
,09-07 15:29:33.053  7429  7429 I libpersona: KNOX_SDCARD checking this for 1000
09-07 15:29:33.053  7429  7429 I libpersona: KNOX_SDCARD not a persona
09-07 15:29:33.053  7429  7429 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 15:29:33.053  1017  1545 I ActivityManager: Killing 6986:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21,
,09-07 15:29:33.053  7429  7429 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 15:29:33.063  7429  7429 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 15:29:33.083  7429  7429 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 15:29:33.083  7429  7429 D ActivityThread: Added TimaKeyStore provider
,09-07 15:29:33.113  7429  7429 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,09-07 15:29:33.183  1017  1044 D Tethering: interfaceRemoved wlan0
,09-07 15:29:33.183  1017  1044 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-07 15:29:33.233  7429  7429 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,09-07 15:29:33.243  7429  7429 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,09-07 15:29:33.243  7429  7429 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,09-07 15:29:33.243  7429  7429 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-07 15:29:33.243  7429  7429 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,09-07 15:29:33.243  7429  7429 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-07 15:29:33.253  1017  1255 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,09-07 15:29:33.253  1017  1255 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-07 15:29:33.253  1017  1255 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:33.253  1017  1255 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:33.253  1017  1255 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:33.263  7444  7444 E Zygote  : MountEmulatedStorage()
,09-07 15:29:33.263  7444  7444 E Zygote  : v2
09-07 15:29:33.263  7444  7444 I libpersona: KNOX_SDCARD checking this for 10008
09-07 15:29:33.263  7444  7444 I libpersona: KNOX_SDCARD not a persona
,09-07 15:29:33.263  1017  1255 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7444 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-07 15:29:33.263  1017  1255 I ActivityManager: Killing 7011:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21,
09-07 15:29:33.263  7444  7444 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 15:29:33.273  7444  7444 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 15:29:33.273  7444  7444 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-07 15:29:33.293  7444  7444 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 15:29:33.293  7444  7444 D ActivityThread: Added TimaKeyStore provider
,09-07 15:29:33.363  1017  3786 I ActivityManager: Killing 6946:com.android.mms/u0a41 (adj 15): empty #21
,09-07 15:29:33.363  1017  3795 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
09-07 15:29:33.363  1017  3795 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-07 15:29:33.373  1017  3795 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:33.373  1017  3795 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 15:29:33.373  1017  3795 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,09-07 15:29:33.383  1908  1908 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-07 15:29:33.383  1017  1136 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-07 15:29:33.383  1017  1136 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,09-07 15:29:33.383  1017  1136 W ActivityManager: userId = 0, bbcId = -10000
,09-07 15:29:33.383  1017  1136 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 15:29:33.383  1017  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 15:29:33.393  1908  2809 I iu.UploadsManager: num queued entries: 0
,09-07 15:29:33.393  1908  2809 I iu.UploadsManager: num updated entries: 0
,09-07 15:29:33.393  1908  2809 I iu.SyncManager: NEXT; no task
,09-07 15:29:33.393  1908  1908 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-07 15:29:33.393  1017  1044 D Tethering: interfaceRemoved p2p0
09-07 15:29:33.393  1017  1044 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-07 15:29:33.393  1908  1908 I Kids    : [GCoreUtils] Current gmscore version, 8115234 is smaller than the required version 8400000
,09-07 15:29:33.403  2813  2813 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Sep 07 15:29:33 GMT+02:00 2016
,09-07 15:29:33.403  1017  3796 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
09-07 15:29:33.403  1017  3796 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-07 15:29:33.403  1017  3796 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:33.403  1017  3796 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:33.403  1017  3796 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-07 15:29:33.413  2813  2813 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-07 15:29:33.423  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,09-07 15:29:33.423  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:33.423  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:33.423  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:33.423  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:33.423  2813  2813 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,09-07 15:29:33.433  2813  2813 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-07 15:29:33.443  7461  7461 E Zygote  : MountEmulatedStorage()
09-07 15:29:33.443  7461  7461 I libpersona: KNOX_SDCARD checking this for 10031
09-07 15:29:33.443  7461  7461 E Zygote  : v2
09-07 15:29:33.443  7461  7461 I libpersona: KNOX_SDCARD not a persona
09-07 15:29:33.443  7461  7461 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-07 15:29:33.443  7461  7461 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-07 15:29:33.443  7461  7461 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-07 15:29:33.443  1017  1030 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7461 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
09-07 15:29:33.443  2813  2813 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-07 15:29:33.453  1017  1095 V AlarmManager: waitForAlarm result :4
,09-07 15:29:33.453  2813  7460 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-07 15:29:33.453  2813  7460 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,09-07 15:29:33.453  2813  7460 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,09-07 15:29:33.463  2813  7460 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,09-07 15:29:33.463  2813  2813 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-07 15:29:33.473  7461  7461 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 15:29:33.473  7461  7461 D ActivityThread: Added TimaKeyStore provider
,09-07 15:29:33.483  1017  3786 D CountryDetector: No listener is left
,09-07 15:29:33.503  7461  7461 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,09-07 15:29:33.513  1017  1520 I ActivityManager: Killing 7071:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,09-07 15:29:33.523  1017  1545 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,09-07 15:29:33.533  1017  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:33.533  1017  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:33.533  1017  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:33.533  1017  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:33.543  2751  7477 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false,
,09-07 15:29:33.553  2751  7477 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false,
,09-07 15:29:33.553  2751  7477 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,09-07 15:29:33.553  7478  7478 E Zygote  : MountEmulatedStorage()
09-07 15:29:33.553  7478  7478 E Zygote  : v2
09-07 15:29:33.553  7478  7478 I libpersona: KNOX_SDCARD checking this for 10032
09-07 15:29:33.553  7478  7478 I libpersona: KNOX_SDCARD not a persona
,09-07 15:29:33.553  7478  7478 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 15:29:33.553  2751  7477 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,09-07 15:29:33.563  2751  7477 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,09-07 15:29:33.563  1017  1545 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7478 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,09-07 15:29:33.563  7478  7478 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-07 15:29:33.563  7478  7478 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-07 15:29:33.603  7478  7478 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 15:29:33.603  7478  7478 D ActivityThread: Added TimaKeyStore provider,
,09-07 15:29:33.673  7478  7493 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,09-07 15:29:33.673  7478  7493 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,09-07 15:29:33.683  7478  7478 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,09-07 15:29:33.683  1017  3786 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,09-07 15:29:33.683  7478  7493 D SPPClientService: PushLog.txt file is not deleted.
09-07 15:29:33.683  1017  3786 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:33.683  1017  3786 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:33.683  1017  3786 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:33.683  1017  3786 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:33.683  7478  7493 D SPPClientService: PushLog.txt file is not deleted.
,09-07 15:29:33.693  7478  7493 D SPPClientService: ============PushLog. stop!
,09-07 15:29:33.703  7495  7495 E Zygote  : MountEmulatedStorage(),
09-07 15:29:33.703  1017  3786 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7495 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-07 15:29:33.703  7495  7495 E Zygote  : v2
09-07 15:29:33.703  7495  7495 I libpersona: KNOX_SDCARD checking this for 10036
09-07 15:29:33.703  7495  7495 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 15:29:33.703  7495  7495 I libpersona: KNOX_SDCARD not a persona
09-07 15:29:33.713  1017  3786 I ActivityManager: Killing 7088:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
,09-07 15:29:33.713  1017  1546 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
09-07 15:29:33.713  1017  1546 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,09-07 15:29:33.713  1017  1546 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:33.713  1017  1546 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-07 15:29:33.713  1017  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,09-07 15:29:33.713  7495  7495 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-07 15:29:33.723  7495  7495 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,09-07 15:29:33.743  7495  7495 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 15:29:33.743  7495  7495 D ActivityThread: Added TimaKeyStore provider
,09-07 15:29:33.753  7478  7501 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,09-07 15:29:33.793  7495  7495 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@3e458698
,09-07 15:29:33.803  7495  7495 I SA      : [SSP] onCreated
,09-07 15:29:33.823   329   329 I ServiceManager: Waiting for service AtCmdFwd...
,09-07 15:29:33.823  7495  7495 I SA      : [TPM] There is no property file
,09-07 15:29:33.823  7495  7495 I SA      : [SCU] isHaveSA() - false
,09-07 15:29:33.823  7495  7495 I SA      : [TPM] getModelProperty : null
,09-07 15:29:33.823  7495  7495 I SA      : [TPM] getCSCProperty : null
,09-07 15:29:33.833  7495  7495 I SA      : [DM] FLOATING AMOLED FEATURE: true
,09-07 15:29:33.833  7495  7495 I SA      : [DM] PRODUCT AMOLED FEATURE: false
09-07 15:29:33.833  7495  7495 I SA      : [DM] TFT FEATURE: false
,09-07 15:29:33.833  7495  7495 I SA      : [DM] init START
,09-07 15:29:33.833  7495  7495 I SA      : [DM] This device is not a Vodafone
,09-07 15:29:33.843  7495  7495 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,09-07 15:29:33.843  7495  7495 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
09-07 15:29:33.843  7495  7495 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,09-07 15:29:33.843  7495  7495 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
09-07 15:29:33.843  7495  7495 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,09-07 15:29:33.843  7495  7495 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
09-07 15:29:33.843  7495  7495 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,09-07 15:29:33.843  7495  7495 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-07 15:29:33.843  7495  7495 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,09-07 15:29:33.843  7495  7495 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,09-07 15:29:33.843  7495  7495 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
09-07 15:29:33.843  7495  7495 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,09-07 15:29:33.843  7495  7495 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,09-07 15:29:33.843  7495  7495 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
09-07 15:29:33.843  7495  7495 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
09-07 15:29:33.843  7495  7495 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,09-07 15:29:33.843  7495  7495 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
09-07 15:29:33.843  7495  7495 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,09-07 15:29:33.843  7495  7495 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,09-07 15:29:33.853  7495  7495 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
09-07 15:29:33.853  7495  7495 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,09-07 15:29:33.853  7495  7495 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
09-07 15:29:33.853  7495  7495 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,09-07 15:29:33.853  7495  7495 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
09-07 15:29:33.853  7495  7495 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,09-07 15:29:33.853  7495  7495 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
09-07 15:29:33.853  7495  7495 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
,09-07 15:29:33.853  7495  7495 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,09-07 15:29:33.853  7495  7495 I SA      : [SCU] isHaveSA() - false,
09-07 15:29:33.853  7495  7495 I SA      : support phone number id : false
09-07 15:29:33.853  7495  7495 I SA      : [DM] Supports Ref Jpn : true
09-07 15:29:33.853  7495  7495 I SA      : [DM] init END
,09-07 15:29:33.853  7495  7495 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,09-07 15:29:33.853  7495  7495 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ],
09-07 15:29:33.853  7495  7495 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-07 15:29:33.863  7495  7495 I SA      : [SLFUCHKMGR] constructor called,
,09-07 15:29:33.863  7495  7495 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
09-07 15:29:33.863  7495  7495 I SA      : [OR] == isSIMCardReady false ==
,09-07 15:29:33.873  7495  7495 I SA      : [SCU] == networkStateCheck == false,
09-07 15:29:33.873  7495  7495 I SA      : [OR] onReceive END
,09-07 15:29:33.873  1017  1477 I ActivityManager: Killing 7107:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
,09-07 15:29:33.873  1227  1227 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-07 15:29:33.883  1806  1806 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-07 15:29:33.893  2678  2690 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,09-07 15:29:33.893  1806  1806 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,09-07 15:29:33.893  1806  1806 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,09-07 15:29:33.893  1806  1806 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,09-07 15:29:33.893  1806  1806 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-07 15:29:33.893  1806  1806 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-07 15:29:33.903  1806  1806 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,09-07 15:29:33.903  1017  3786 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,09-07 15:29:33.903  1017  3786 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:33.903  1017  3786 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:33.903  1017  3786 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:33.903  1017  3786 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:33.923  1017  3786 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7517 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-07 15:29:33.923  7517  7517 E Zygote  : MountEmulatedStorage()
09-07 15:29:33.923  7517  7517 E Zygote  : v2
09-07 15:29:33.923  7517  7517 I libpersona: KNOX_SDCARD checking this for 10077
09-07 15:29:33.923  7517  7517 I libpersona: KNOX_SDCARD not a persona
09-07 15:29:33.923  7517  7517 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 15:29:33.923  7517  7517 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 15:29:33.923  7517  7517 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,09-07 15:29:33.943  7517  7517 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 15:29:33.943  7517  7517 D ActivityThread: Added TimaKeyStore provider
,09-07 15:29:34.113  1017  1520 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,09-07 15:29:34.113  1017  1520 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,09-07 15:29:34.113  1017  1520 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:34.113  1017  1520 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-07 15:29:34.113  1017  1520 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-07 15:29:34.123  1017  3785 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,09-07 15:29:34.123  1017  3785 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:34.123  1017  3785 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:34.123  1017  3785 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:34.123  1017  3785 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:34.133  7535  7535 E Zygote  : MountEmulatedStorage(),
09-07 15:29:34.133  1017  3785 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7535 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-07 15:29:34.133  7535  7535 E Zygote  : v2
09-07 15:29:34.133  7535  7535 I libpersona: KNOX_SDCARD checking this for 10110
,09-07 15:29:34.133  7535  7535 I libpersona: KNOX_SDCARD not a persona
,09-07 15:29:34.143  7535  7535 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 15:29:34.143  1017  1503 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,09-07 15:29:34.143  1017  1503 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
09-07 15:29:34.143  1017  1503 W ActivityManager: userId = 0, bbcId = -10000
,09-07 15:29:34.143  1017  1503 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
,09-07 15:29:34.143  1017  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
09-07 15:29:34.143  7535  7535 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 15:29:34.143  1017  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
09-07 15:29:34.143  7351  7534 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-07 15:29:34.143  7535  7535 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-07 15:29:34.153  1017  1029 I ActivityManager: Killing 7128:com.wsomacp/u0a23 (adj 15): empty #21
,09-07 15:29:34.163  7535  7535 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 15:29:34.163  7535  7535 D ActivityThread: Added TimaKeyStore provider
,09-07 15:29:34.293  1017  1136 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-07 15:29:34.293  1017  1136 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-07 15:29:34.293  1017  1136 D SecContentProvider2: mCursor = null
,09-07 15:29:34.293  1017  1136 D WifiService: setWifiEnabled: true pid=6970, uid=10170
,09-07 15:29:34.293  1017  1136 W ActivityManager: Permission Denial: getCurrentUser() from pid=6970, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-07 15:29:34.293  1017  1136 W WifiService: Failed getting userId using ActivityManagerNative
09-07 15:29:34.293  1017  1136 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6970, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-07 15:29:34.293  1017  1136 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-07 15:29:34.293  1017  1136 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-07 15:29:34.293  1017  1136 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-07 15:29:34.293  1017  1136 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-07 15:29:34.293  1017  1136 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-07 15:29:34.293  1017  1136 D SettingsProvider: name = wifi_on
,09-07 15:29:34.313  1017  1128 E WifiHW  : ##################### set firmware type 0 #####################,
,09-07 15:29:34.363  1017  1477 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-07 15:29:34.493   257   533 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-07 15:29:34.493   257   533 W Vold    : Returning OperationFailed - no handler for errno 0
,09-07 15:29:34.493  7535  7555 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-07 15:29:34.503   257   533 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-07 15:29:34.503   257   533 W Vold    : Returning OperationFailed - no handler for errno 0
,09-07 15:29:34.503  7535  7555 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-07 15:29:34.503  7535  7535 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-07 15:29:34.503  7535  7535 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-07 15:29:34.503  7535  7535 I GAv4    :   adb logcat -s GAv4
,09-07 15:29:34.523   257   533 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-07 15:29:34.523   257   533 W Vold    : Returning OperationFailed - no handler for errno 0
,09-07 15:29:34.523  7535  7557 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-07 15:29:34.523   257   533 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-07 15:29:34.523   257   533 W Vold    : Returning OperationFailed - no handler for errno 0
,09-07 15:29:34.533  7535  7557 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-07 15:29:34.533  7535  7535 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-07 15:29:34.533  1017  1503 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-07 15:29:34.553  7535  7535 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-07 15:29:34.563  7535  7564 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-07 15:29:34.653  5881  5881 D FactoryTest: Not factory mode
09-07 15:29:34.653  5881  5881 D FactoryTest: Not factory mode. isFactoryMode() returend false
,09-07 15:29:34.663  5881  5881 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
09-07 15:29:34.663  5881  5881 D MTPRx   : still no open session command from host, so toast
,09-07 15:29:34.663  5881  5881 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,09-07 15:29:34.663  5881  5881 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,09-07 15:29:34.663  5881  5881 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:117725
,09-07 15:29:34.663  1017  1546 E PersonaManagerService: inState():  stateMachine is null !!
,09-07 15:29:34.663  1017  1546 I PersonaManagerService: PersonaId don't exist
09-07 15:29:34.663  1017  1546 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,09-07 15:29:34.663  1017  1546 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-07 15:29:34.673  1017  1546 W ActivityManager: userId = 0, bbcId = -10000
,09-07 15:29:34.673  1017  1546 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
09-07 15:29:34.673  1017  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,09-07 15:29:34.683  1017  1546 W ActivityManager: mDVFSHelper.acquire()
,09-07 15:29:34.683  1017  1044 D Tethering: interfaceAdded wlan0,
,09-07 15:29:34.693  1017  1131 E Tethering: No numeric data
,09-07 15:29:34.693  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-07 15:29:34.693  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-07 15:29:34.693  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-07 15:29:34.703  1017  1044 D Tethering: interfaceAdded p2p0,
09-07 15:29:34.703  1017  1044 D Tethering: p2p0 is not a tetherable iface, ignoring
,09-07 15:29:34.703  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
09-07 15:29:34.703  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,09-07 15:29:34.703  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-07 15:29:34.703   278   990 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,09-07 15:29:34.703   278   990 D SoftapController: Softap fwReload - Ok
,09-07 15:29:34.713   278   990 D CommandListener: Setting iface cfg,
09-07 15:29:34.713   278   990 D CommandListener: Trying to bring down wlan0
09-07 15:29:34.713   278   990 D CommandListener: Clearing all IP addresses on wlan0
,09-07 15:29:34.713  1017  1546 D PersonaManager: isKioskContainerExistOnDevice
,09-07 15:29:34.723  1017  1128 E WifiHW  : supplicant_name : p2p_supplicant,
,09-07 15:29:34.723  1017  1546 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-07 15:29:34.723  1017  1546 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
09-07 15:29:34.723  1017  1546 D InputDispatcher: Focused application set to: xxxx
09-07 15:29:34.723  1017  1546 D InputDispatcher: Focus left window: 6970
,09-07 15:29:34.723  5881  5881 E MTPRx   : started activity for popup
,09-07 15:29:34.733  1017  1128 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-07 15:29:34.733  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-07 15:29:34.733  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
09-07 15:29:34.733  1017  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-07 15:29:34.733  1017  1131 D Tethering: clearTetheredNotification()
09-07 15:29:34.733  1017  1131 D Tethering: InitialState.processMessage what=4
,09-07 15:29:34.733  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit,
09-07 15:29:34.733  1017  1125 V NetworkStats: performPollLocked(flags=0x1)
09-07 15:29:34.733  1017  1131 E Tethering: No numeric data
09-07 15:29:34.743  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox updated,
,09-07 15:29:34.743  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-07 15:29:34.743  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-07 15:29:34.743  1175  1175 D HotspotTile: updateTetherState():false, false
,09-07 15:29:34.743  1017  1125 V NetworkStats: performPollLocked() took 9ms,
09-07 15:29:34.743  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 15:29:34.753  5881  5881 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
09-07 15:29:34.753  5881  5881 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-07 15:29:34.753  5881  5881 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-07 15:29:34.753  5881  5881 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 15:29:34.753  5881  5881 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-07 15:29:34.753  5881  5881 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-07 15:29:34.753  1017  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-07 15:29:34.753  1017  1131 D Tethering: clearTetheredNotification()
09-07 15:29:34.753  4781  4781 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-07 15:29:34.763  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 15:29:34.763  1017  1125 V NetworkStats: performPollLocked(flags=0x1)
,09-07 15:29:34.763  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 15:29:34.763  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit,
09-07 15:29:34.763  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:29:34.763  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
09-07 15:29:34.763  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-07 15:29:34.763  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 15:29:34.763  1017  1125 V NetworkStats: performPollLocked() took 4ms
,09-07 15:29:34.763  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-07 15:29:34.763  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 15:29:34.763  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 15:29:34.763  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 15:29:34.763  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-07 15:29:34.763  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 15:29:34.763  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:34.763  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-07 15:29:34.763  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:34.763  1175  1175 D HotspotTile: onReceive : 2, 0
09-07 15:29:34.763  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 15:29:34.763  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-07 15:29:34.763  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-07 15:29:34.763  1175  1175 D HotspotTile: updateTetherState():false, false
09-07 15:29:34.763  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:29:34.763  1175  1718 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-07 15:29:34.763  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,09-07 15:29:34.803  7568  7568 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-07 15:29:34.803  7568  7568 I wpa_supplicant: Successfully initialized wpa_supplicant
09-07 15:29:34.803  7568  7568 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-07 15:29:34.803  5881  5881 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,09-07 15:29:34.823   329   329 I ServiceManager: Waiting for service AtCmdFwd...,
,09-07 15:29:34.853  1017  3786 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
,09-07 15:29:34.853  1017  3786 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-07 15:29:34.853  1017  1477 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@32275f4d attribute=null, token = android.os.BinderProxy@2adcd4e8,
09-07 15:29:34.853  1017  3786 D InputDispatcher: Focused application set to: xxxx,
09-07 15:29:34.853  1017  3786 D InputDispatcher: Focus entered window: 6970
09-07 15:29:34.853  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
09-07 15:29:34.853  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
09-07 15:29:34.853  1017  1477 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false,
09-07 15:29:34.853  7568  7568 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
09-07 15:29:34.863   398   398 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7568
09-07 15:29:34.863   398   398 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C,
09-07 15:29:34.863  7568  7568 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
,09-07 15:29:34.863  7568  7568 I wpa_supplicant: ssSupport state is = 1
09-07 15:29:34.863  7568  7568 I wpa_supplicant: >>>>> GET KEY, IV <<<<<,
09-07 15:29:34.863  7568  7568 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
09-07 15:29:34.863   398   398 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7568,
09-07 15:29:34.863   398   398 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,09-07 15:29:34.903  5881  5881 D SettingsReceiverActivity: dev.kiessupport is : TRUE,
,09-07 15:29:34.903  5881  5881 D PhoneWindow: *FMB* installDecor mIsFloating : true
09-07 15:29:34.903  5881  5881 D PhoneWindow: *FMB* installDecor flags : 8388610
,09-07 15:29:34.913  1017  1504 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
09-07 15:29:34.923  1017  1504 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:34.923  1017  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 15:29:34.923  1017  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-07 15:29:34.953  6970  6970 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-07 15:29:34.953  6970  6970 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,09-07 15:29:34.953  6970  6970 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-07 15:29:34.953  6970  6970 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,09-07 15:29:34.963  1017  1501 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-07 15:29:34.963  1017  1501 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-07 15:29:34.963  1017  1501 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-07 15:29:34.963  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,09-07 15:29:34.963  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,09-07 15:29:34.993  6970  6970 D io.jxcore.node.LifeCycleMonitor: onActivityPaused,
09-07 15:29:34.993  6970  6970 V ActivityThread: updateVisibility : ActivityRecord{90ebfd3 token=android.os.BinderProxy@105c020d {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-07 15:29:34.993  6970  6970 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
09-07 15:29:34.993  7535  7535 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
09-07 15:29:34.993  6970  6970 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@105c020d time:118053
09-07 15:29:34.993  6970  6970 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1ca27099 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@3ddad772, 16908290=android.view.AbsSavedState$1@3ddad772}, android:focusedViewId=100}]}]
09-07 15:29:34.993  6970  6970 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-07 15:29:34.993  6970  6970 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-07 15:29:34.993  6970  6970 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-07 15:29:35.023  7535  7535 I cr.library_loader: Time to load native libraries: 3 ms (timestamps 8079-8082)
09-07 15:29:35.023  7535  7535 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-07 15:29:35.033  1017  1501 D PersonaManager: isKioskContainerExistOnDevice
,09-07 15:29:35.053  7535  7535 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2480a3b3}
09-07 15:29:35.053  7535  7535 I cr.library_loader: Expected native library version number "", actual native library version number ""
09-07 15:29:35.053  7535  7535 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,09-07 15:29:35.063   398   398 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0,
,09-07 15:29:35.063  7568  7568 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed,
,09-07 15:29:35.073  7535  7535 I cr.BrowserStartup: Initializing chromium process, singleProcess=true,
,09-07 15:29:35.073  7535  7535 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-07 15:29:35.073  7535  7535 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-07 15:29:35.093  7535  7535 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-07 15:29:35.093  7535  7535 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-07 15:29:35.093  7535  7535 I Adreno-EGL: Build Date: 04/06/15 Mon
09-07 15:29:35.093  7535  7535 I Adreno-EGL: Local Branch: 
09-07 15:29:35.093  7535  7535 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-07 15:29:35.093  7535  7535 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-07 15:29:35.093  7535  7535 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-07 15:29:35.133  7568  7568 I wpa_supplicant: Ctrl_iface: loading cred from phone,
09-07 15:29:35.133  7568  7568 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-07 15:29:35.143  7568  7568 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,09-07 15:29:35.143   398   398 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7568
09-07 15:29:35.143   398   398 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-07 15:29:35.143  7568  7568 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-07 15:29:35.143  7568  7568 I wpa_supplicant: ssSupport state is = 1
,09-07 15:29:35.143  7568  7568 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-07 15:29:35.143  7568  7568 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-07 15:29:35.143  7568  7568 E wpa_supplicant: SIM READ ERROR
09-07 15:29:35.143  7568  7568 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-07 15:29:35.143  7568  7568 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-07 15:29:35.143  7568  7568 E wpa_supplicant: SIM READ ERROR
09-07 15:29:35.143  7568  7568 I wpa_supplicant: Blacklist: Clear (all) 
09-07 15:29:35.153  7568  7568 I wpa_supplicant: wpa_default_ap_write_once
,09-07 15:29:35.153  7568  7568 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-07 15:29:35.153  7568  7568 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-07 15:29:35.153  7568  7568 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-07 15:29:35.153  7568  7568 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-07 15:29:35.153  7568  7568 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-07 15:29:35.153  7568  7568 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-07 15:29:35.153  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false,
09-07 15:29:35.153  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-07 15:29:35.153  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-07 15:29:35.163  7535  7535 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-07 15:29:35.173  7535  7598 W cr.media: Requires BLUETOOTH permission
,09-07 15:29:35.183  7535  7535 I NSApplication: Starting up...
,09-07 15:29:35.183  1017  1520 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-07 15:29:35.183  1017  3795 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-07 15:29:35.193  1017  1503 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,09-07 15:29:35.193  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:35.193  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:35.193  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:35.193  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:35.203  7568  7568 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,09-07 15:29:35.203  7603  7603 E Zygote  : MountEmulatedStorage()
,09-07 15:29:35.203  7603  7603 E Zygote  : v2
09-07 15:29:35.203  7603  7603 I libpersona: KNOX_SDCARD checking this for 10117
09-07 15:29:35.203  7603  7603 I libpersona: KNOX_SDCARD not a persona
,09-07 15:29:35.203  7603  7603 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 15:29:35.203  1017  1503 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7603 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-07 15:29:35.213  1017  1503 I ActivityManager: Killing 7207:com.android.providers.calendar/u0a37 (adj 15): empty #21,
,09-07 15:29:35.213  7603  7603 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 15:29:35.213  7603  7603 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-07 15:29:35.223  7603  7603 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 15:29:35.233  7603  7603 D ActivityThread: Added TimaKeyStore provider
,09-07 15:29:35.243  7603  7603 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-07 15:29:35.493  7568  7568 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-07 15:29:35.493  7568  7568 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-07 15:29:35.513  7568  7568 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
09-07 15:29:35.513   398   398 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7568
09-07 15:29:35.513   398   398 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-07 15:29:35.513  7568  7568 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
,09-07 15:29:35.513  7568  7568 I wpa_supplicant: ssSupport state is = 1
,09-07 15:29:35.533  7568  7568 I wpa_supplicant: Ctrl_iface: loading cred from phone,
09-07 15:29:35.533  7568  7568 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-07 15:29:35.543  7568  7568 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
09-07 15:29:35.543   398   398 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7568
09-07 15:29:35.543   398   398 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-07 15:29:35.543  7568  7568 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running,
09-07 15:29:35.543  7568  7568 I wpa_supplicant: ssSupport state is = 1
09-07 15:29:35.543  7568  7568 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-07 15:29:35.543  7568  7568 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-07 15:29:35.543  7568  7568 E wpa_supplicant: SIM READ ERROR
09-07 15:29:35.543  7568  7568 I wpa_supplicant: wpa_default_ap_write_once
09-07 15:29:35.543  7568  7568 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-07 15:29:35.543  7568  7568 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-07 15:29:35.543  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
09-07 15:29:35.543  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
09-07 15:29:35.543  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-07 15:29:35.543  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false,
09-07 15:29:35.543  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-07 15:29:35.543  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,09-07 15:29:35.573  1017  3785 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,09-07 15:29:35.583  1017  3785 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:35.583  1017  3785 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:35.583  1017  3785 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:35.583  1017  3785 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:35.593  7626  7626 E Zygote  : MountEmulatedStorage(),
09-07 15:29:35.593  7626  7626 E Zygote  : v2
09-07 15:29:35.593  7626  7626 I libpersona: KNOX_SDCARD checking this for 10121
,09-07 15:29:35.593  7626  7626 I libpersona: KNOX_SDCARD not a persona
,09-07 15:29:35.593  1017  3785 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7626 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
09-07 15:29:35.593  1017  3785 I ActivityManager: Killing 7160:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,09-07 15:29:35.593  7626  7626 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 15:29:35.603  7626  7626 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 15:29:35.603  7626  7626 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 15:29:35.613  7568  7568 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
09-07 15:29:35.613  7568  7568 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-07 15:29:35.613  7626  7626 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 15:29:35.613  7626  7626 D ActivityThread: Added TimaKeyStore provider
,09-07 15:29:35.633  7626  7626 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-07 15:29:35.633  7626  7626 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-07 15:29:35.633  7626  7626 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-07 15:29:35.643  7626  7626 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,09-07 15:29:35.653  7626  7626 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,09-07 15:29:35.653  7626  7626 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,09-07 15:29:35.653  1017  1520 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,09-07 15:29:35.653  1017  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:35.653  1017  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:35.653  1017  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:35.653  1017  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:35.673  7643  7643 E Zygote  : MountEmulatedStorage(),
09-07 15:29:35.673  7643  7643 E Zygote  : v2,
09-07 15:29:35.673  7643  7643 I libpersona: KNOX_SDCARD checking this for 10141
09-07 15:29:35.673  7643  7643 I libpersona: KNOX_SDCARD not a persona,
09-07 15:29:35.673  1017  1520 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7643 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
09-07 15:29:35.673  1017  1520 I ActivityManager: Killing 7185:com.android.calendar/u0a131 (adj 15): empty #21
,09-07 15:29:35.673  7643  7643 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 15:29:35.673  7643  7643 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 15:29:35.683  7643  7643 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 15:29:35.683  7568  7568 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,09-07 15:29:35.683  7568  7568 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-07 15:29:35.683  7568  7568 I wpa_supplicant: Skip scan - bUseNetwork false
,09-07 15:29:35.693  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
09-07 15:29:35.693  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
09-07 15:29:35.693  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-07 15:29:35.693  1017  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
09-07 15:29:35.693   309   309 I art     : Explicit concurrent mark sweep GC freed 8700(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 604us total 19.627ms
,09-07 15:29:35.693  1017  1128 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-07 15:29:35.693  7568  7568 I wpa_supplicant: HOTSPOT20_ENABLE called
09-07 15:29:35.693  7568  7568 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-07 15:29:35.693  7568  7568 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-07 15:29:35.693  7568  7568 E wpa_supplicant: SIM READ ERROR
09-07 15:29:35.693  7568  7568 I wpa_supplicant: Blacklist: Clear (all) 
,09-07 15:29:35.703  7643  7643 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 15:29:35.703  7643  7643 D ActivityThread: Added TimaKeyStore provider
,09-07 15:29:35.713   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 646us total 16.494ms
,09-07 15:29:35.713  7643  7643 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
09-07 15:29:35.713  7643  7643 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 15:29:35.713  7643  7643 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-07 15:29:35.713  7643  7643 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-07 15:29:35.723  7568  7568 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,09-07 15:29:35.723   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 573us total 16.452ms
,09-07 15:29:35.733  7568  7568 I wpa_supplicant: Skip scan - bUseNetwork false,
,09-07 15:29:35.743  1017  1128 D WifiConfigStore: Loading config and enabling all networks 
,09-07 15:29:35.743  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-07 15:29:35.743  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 15:29:35.743  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-07 15:29:35.743  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 15:29:35.743  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 15:29:35.753  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:35.753  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-07 15:29:35.753  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:35.753  1175  1718 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-07 15:29:35.753  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-07 15:29:35.753  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,09-07 15:29:35.753  1175  1175 D HotspotTile: onReceive : 3, 0
,09-07 15:29:35.753  4781  4781 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-07 15:29:35.763  6970  6970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:29:35.763  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:29:35.763  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:35.763  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:35.763  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:29:35.763  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 15:29:35.763  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:29:35.763  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:29:35.763  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 15:29:35.763  6970  6970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:29:35.763  1017  1128 E WifiConfigStore: Not a HS20
,09-07 15:29:35.763  6970  6970 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 15:29:35.763  6970  6970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 15:29:35.763  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:29:35.763  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:35.763  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:35.763  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:29:35.763  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 15:29:35.763  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:29:35.763  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:29:35.763  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 15:29:35.763  6970  6970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 15:29:35.763  6970  6970 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 15:29:35.763  1017  1128 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-07 15:29:35.763  1017  1128 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-07 15:29:35.763  7568  7568 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-07 15:29:35.763  7568  7568 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-07 15:29:35.763  7568  7568 I wpa_supplicant: reset timer : RESET_TIMER 0
09-07 15:29:35.763  7568  7568 I wpa_supplicant: P2P: Current p2p state = IDLE
09-07 15:29:35.773  7568  7568 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-07 15:29:35.773  7568  7568 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-07 15:29:35.773  7568  7568 I wpa_supplicant: First Scan Start
,09-07 15:29:35.773  7568  7568 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-07 15:29:35.773  1017  3786 D RCPManagerService: exchangeData() failure , invalid userId
09-07 15:29:35.773  1017  1128 D WifiNative-wlan0: Setting external_sim to 1
,09-07 15:29:35.773  1017  1128 D WifiStateMachine: Setting OUI to DA-A1-19
09-07 15:29:35.773  1017  1128 I WifiNative-HAL: startHal
09-07 15:29:35.773  1017  1128 E wifi    : getStaticLongField sWifiHalHandle 0x9f05088c
09-07 15:29:35.773  1017  1128 I WifiNative-HAL: Could not start hal
,09-07 15:29:35.773  7351  7351 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 15:29:35.773  1017  1128 E WifiNative-wlan0: do suspend true
,09-07 15:29:35.773  1017  1127 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-07 15:29:35.773  1017  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,09-07 15:29:35.773  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 3
,09-07 15:29:35.773  1017  1151 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:29:35.773  1017  1151 I WifiNative-HAL: startHal
09-07 15:29:35.773  1017  1151 E wifi    : getStaticLongField sWifiHalHandle 0x9df129bc
09-07 15:29:35.783  1017  1151 I WifiNative-HAL: Could not start hal
09-07 15:29:35.783  1017  1151 E WifiScanningService: could not start HAL
09-07 15:29:35.783  1017  1128 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-07 15:29:35.783  1017  1128 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-07 15:29:35.783  1017  1128 E WifiNative-wlan0: invaild command id : 215
,09-07 15:29:35.783   278   990 D CommandListener: Setting iface cfg
09-07 15:29:35.783  1017  1017 D RttService: SCAN_AVAILABLE : 3
09-07 15:29:35.783   278   990 D CommandListener: Trying to bring up p2p0
09-07 15:29:35.783  1017  1152 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-07 15:29:35.783  1017  1127 D WifiMonitor: startMonitoring(p2p0) with mConnected = true,
09-07 15:29:35.783  1017  1127 D WifiP2pService: P2pEnablingState
09-07 15:29:35.783  7568  7568 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-07 15:29:35.783  1017  1127 D WifiP2pService: P2pEnablingState{ what=147457 }
09-07 15:29:35.783  7568  7568 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-07 15:29:35.783  1017  1127 D WifiP2pService: P2p socket connection successful
09-07 15:29:35.783  1017  1130 E ConnectivityService: updateNetworkInfo()
09-07 15:29:35.783  1017  1127 D WifiP2pService: P2pEnabledState,
09-07 15:29:35.783  7568  7568 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
09-07 15:29:35.783  1017  1127 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-07 15:29:35.783  1017  1128 E WifiStateMachine: Failed to set frequency band 0
09-07 15:29:35.783  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,09-07 15:29:35.783  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-07 15:29:35.783  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-07 15:29:35.783  1017  1128 D SecContentProvider2: mCursor = null
09-07 15:29:35.783  1017  1047 D WifiDisplayController: disconnect
09-07 15:29:35.783  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-07 15:29:35.783  1017  1047 D WifiDisplayController: updateConnection
09-07 15:29:35.783  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-07 15:29:35.783  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-07 15:29:35.783  1017  1128 D SecContentProvider2: mCursor = null
09-07 15:29:35.783  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-07 15:29:35.793  1175  1175 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-07 15:29:35.793  1017  1030 D RCPManagerService: exchangeData() failure , invalid userId
09-07 15:29:35.793  1017  1029 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-07 15:29:35.793  1175  1175 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
09-07 15:29:35.793  1017  1127 D WifiNative-p2p0: p2pGetDeviceAddress
,09-07 15:29:35.793  1017  1127 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
09-07 15:29:35.793  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 15:29:35.793  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
09-07 15:29:35.793  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-07 15:29:35.793  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-07 15:29:35.793  1017  1127 D WifiP2pService: DeviceAddress: 0a:75:42
,09-07 15:29:35.793  1017  1047 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
09-07 15:29:35.793  1017  1047 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
09-07 15:29:35.793  1017  1047 D WifiDisplayController:  primary type: 10-0050F204-5
09-07 15:29:35.793  1017  1047 D WifiDisplayController:  secondary type: null
09-07 15:29:35.793  1017  1047 D WifiDisplayController:  wps: 0
09-07 15:29:35.793  1017  1047 D WifiDisplayController:  grpcapab: 0
09-07 15:29:35.793  1017  1047 D WifiDisplayController:  devcapab: 0
09-07 15:29:35.793  1017  1047 D WifiDisplayController:  status: 3
09-07 15:29:35.793  1017  1047 D WifiDisplayController:  wfdInfo: null
09-07 15:29:35.793  1017  1047 D WifiDisplayController:  groupownerAddress: null
09-07 15:29:35.793  1017  1047 D WifiDisplayController:  GOdeviceName: null
09-07 15:29:35.793  1017  1047 D WifiDisplayController:  interfaceAddress: 
09-07 15:29:35.793  1017  1047 D WifiDisplayController:  SConnectInfo : null
,09-07 15:29:35.823  1017  1504 D RCPManagerService: exchangeData() failure , invalid userId
09-07 15:29:35.823  1017  1127 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-07 15:29:35.823  1017  1127 D WifiP2pService: InactiveState
09-07 15:29:35.823  1017  1127 D WifiP2pService: InactiveState{ what=143376 }
,09-07 15:29:35.823   329   329 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
09-07 15:29:35.823  1017  1127 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-07 15:29:35.823  7568  7568 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-07 15:29:35.823  1017  1127 D WifiP2pService: InactiveState{ what=143376 }
,09-07 15:29:35.823  1017  1127 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-07 15:29:35.823  1017  1255 D RCPManagerService: exchangeData() failure , invalid userId
,09-07 15:29:35.833   288   288 E SMD     : DCD OFF
,09-07 15:29:35.863  1017  1545 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,09-07 15:29:35.873  1017  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:35.873  1017  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:35.873  1017  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:35.873  1017  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:35.883  1017  1546 D RCPManagerService: exchangeData() failure , invalid userId,
,09-07 15:29:35.883  7668  7668 E Zygote  : MountEmulatedStorage()
09-07 15:29:35.883  7668  7668 E Zygote  : v2
09-07 15:29:35.883  7668  7668 I libpersona: KNOX_SDCARD checking this for 10068
,09-07 15:29:35.883  7668  7668 I libpersona: KNOX_SDCARD not a persona
09-07 15:29:35.883  1017  1545 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7668 uid=10068 gids={50068, 9997} abi=armeabi-v7a
09-07 15:29:35.883  1017  1501 D RCPManagerService: exchangeData() failure , invalid userId
,09-07 15:29:35.883  7668  7668 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 15:29:35.893  7668  7668 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 15:29:35.893  7668  7668 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-07 15:29:35.913  7668  7668 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 15:29:35.923  1017  3795 D RCPManagerService: exchangeData() failure , invalid userId
,09-07 15:29:35.923  7668  7668 D ActivityThread: Added TimaKeyStore provider
,09-07 15:29:35.923  1017  1546 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,09-07 15:29:35.923  1017  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:35.923  1017  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:35.923  1017  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:35.923  1017  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:35.933  7684  7684 E Zygote  : MountEmulatedStorage(),
09-07 15:29:35.933  7684  7684 E Zygote  : v2
09-07 15:29:35.933  7684  7684 I libpersona: KNOX_SDCARD checking this for 10009
09-07 15:29:35.933  7684  7684 I libpersona: KNOX_SDCARD not a persona
,09-07 15:29:35.943  7684  7684 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 15:29:35.943  1017  1546 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7684 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
,09-07 15:29:35.943  1017  1546 I ActivityManager: Killing 7150:com.android.defcontainer/u0a3 (adj 15): empty #21
,09-07 15:29:35.943  7684  7684 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-07 15:29:35.943  1017  1501 I ActivityManager: Killing 6857:com.android.vending/u0a26 (adj 15): empty #21
09-07 15:29:35.943  7684  7684 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-07 15:29:35.983  7684  7684 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 15:29:35.983  7684  7684 D ActivityThread: Added TimaKeyStore provider
,09-07 15:29:36.123  1017  1503 I art     : Explicit concurrent mark sweep GC freed 71337(3MB) AllocSpace objects, 12(240KB) LOS objects, 33% free, 23MB/34MB, paused 2.463ms total 163.715ms
,09-07 15:29:36.143  7668  7668 D BadgeProvider: onCreate
,09-07 15:29:36.143  7668  7668 D BadgeProvider: DatabaseHelper
,09-07 15:29:36.163  1017  1503 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
09-07 15:29:36.163  1017  1503 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,09-07 15:29:36.163  1017  1501 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,09-07 15:29:36.173  1017  3786 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,09-07 15:29:36.173  7668  7679 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,09-07 15:29:36.183  7668  7679 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
,09-07 15:29:36.183  7668  7679 D BadgeProvider: sendNotify, [notify] : null
09-07 15:29:36.183  7668  7679 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
,09-07 15:29:36.183  7668  7679 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-07 15:29:36.183  7668  7679 D BadgeProvider: update, [UpdateCount] : 1
,09-07 15:29:36.183  1505  1505 D Launcher.Model: reloadBadges entered.
,09-07 15:29:36.203  1017  1477 I ActivityManager: Killing 7249:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,09-07 15:29:36.213  1017  1546 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-07 15:29:36.213  1017  1546 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-07 15:29:36.213  1017  1546 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:36.213  1017  1546 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:36.213  1017  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-07 15:29:36.213  1633  1633 I Hs20UtilService: Starting #11
,09-07 15:29:36.213  1633  1663 I Hs20UtilService: Message received 5011
,09-07 15:29:36.213  7374  7374 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-07 15:29:36.213  7374  7374 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-07 15:29:36.213  7374  7374 D SecurityLogAgent: StateMachine : Current State = 1
,09-07 15:29:36.213  7374  7374 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-07 15:29:36.223  1017  1545 W ActivityManager: userId = 0, bbcId = -10000
,09-07 15:29:36.223  1017  1545 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 15:29:36.223  1017  1545 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,09-07 15:29:36.223  1017  3795 W ActivityManager: userId = 0, bbcId = -10000
,09-07 15:29:36.223  1017  3795 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 15:29:36.223  1017  3795 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,09-07 15:29:36.233   278   986 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-07 15:29:36.233   278   986 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,09-07 15:29:36.233  1017  1544 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-07 15:29:36.233  1017  1544 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-07 15:29:36.233  1017  1544 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:36.233  1017  1544 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:36.233  1017  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-07 15:29:36.243  1633  1633 I Hs20UtilService: Starting #12
,09-07 15:29:36.243  1633  1663 I Hs20UtilService: Message received 5011
,09-07 15:29:36.243  7374  7374 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-07 15:29:36.243  7374  7374 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-07 15:29:36.243  7374  7374 D SecurityLogAgent: StateMachine : Current State = 1
09-07 15:29:36.243  7374  7374 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-07 15:29:36.253  1017  3796 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-07 15:29:36.253  1017  3796 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-07 15:29:36.253  1017  3796 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:36.253  1017  3796 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:36.253  1017  3796 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-07 15:29:36.253  1633  1633 I Hs20UtilService: Starting #13
,09-07 15:29:36.253  1633  1663 I Hs20UtilService: Message received 5011
,09-07 15:29:36.263  1017  1128 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-07 15:29:36.263  1017  1128 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-07 15:29:36.263  1017  1128 E WifiNative-wlan0: invaild command id : 215
,09-07 15:29:36.263  7374  7374 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-07 15:29:36.263  7374  7374 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-07 15:29:36.263  7374  7374 D SecurityLogAgent: StateMachine : Current State = 1
,09-07 15:29:36.263  7374  7374 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-07 15:29:36.273  4781  4781 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-07 15:29:36.273  4781  4781 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-07 15:29:36.273  4781  4781 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-07 15:29:36.273  4781  4781 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-07 15:29:36.273  4781  4781 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-07 15:29:36.273  4781  4781 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-07 15:29:36.273  4781  4834 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-07 15:29:36.273  7305  7305 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-07 15:29:36.283  7305  7305 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-07 15:29:36.283  7305  7305 D FileShare-Client: Outbound.stopDelayTimer - 
,09-07 15:29:36.283  7336  7336 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-07 15:29:36.283  1017  1477 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:36.283  1017  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 15:29:36.283  1017  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,09-07 15:29:36.913  7568  7568 I wpa_supplicant: nl80211: Received scan results (22 BSSes),
09-07 15:29:36.913  7568  7568 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-07 15:29:36.913  7568  7568 I wpa_supplicant: Trying to associate with SSID '4E47373030'
09-07 15:29:36.913  7568  7568 I wpa_supplicant: Trying to associate with  'G700'
09-07 15:29:36.913  7568  7568 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
09-07 15:29:36.913  7568  7568 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
09-07 15:29:36.913  1017  7653 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,09-07 15:29:36.933  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
09-07 15:29:36.933  1017  1128 D SecContentProvider2: mCursor = null
,09-07 15:29:37.033  7568  7568 E wpa_supplicant: Cmd 35605 not handled
09-07 15:29:37.033  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-07 15:29:37.033  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
09-07 15:29:37.033  7568  7568 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
,09-07 15:29:37.033  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-07 15:29:37.033  7568  7568 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,09-07 15:29:37.033  7568  7568 I wpa_supplicant: Associated with F4.99.3E
09-07 15:29:37.033  7568  7568 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-07 15:29:37.033  7568  7568 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-07 15:29:37.033  7568  7568 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
09-07 15:29:37.033  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-07 15:29:37.033  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-07 15:29:37.033  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
09-07 15:29:37.033  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-07 15:29:37.033  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-07 15:29:37.033  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-07 15:29:37.033  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true
09-07 15:29:37.033  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,09-07 15:29:37.033  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
,09-07 15:29:37.043  1017  1131 E Tethering: No numeric data
,09-07 15:29:37.043  1017  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-07 15:29:37.043  1017  1131 D Tethering: clearTetheredNotification()
,09-07 15:29:37.043  1017  1125 V NetworkStats: performPollLocked(flags=0x1)
,09-07 15:29:37.043  7568  7568 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-07 15:29:37.043  7568  7568 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,09-07 15:29:37.043  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 15:29:37.043  7568  7568 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
09-07 15:29:37.043  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-07 15:29:37.043  1175  1175 D HotspotTile: updateTetherState():false, false
,09-07 15:29:37.043  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
09-07 15:29:37.043  7568  7568 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
09-07 15:29:37.043  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-07 15:29:37.043  7568  7568 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-07 15:29:37.053  7568  7568 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,09-07 15:29:37.053  7568  7568 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-07 15:29:37.053  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-07 15:29:37.053  7568  7568 I wpa_supplicant: Blacklist: Clear (temp) 
09-07 15:29:37.053  7568  7568 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
09-07 15:29:37.053  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true
09-07 15:29:37.053  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
09-07 15:29:37.053  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-07 15:29:37.053  1017  1128 D SecContentProvider2: mCursor = null
,09-07 15:29:37.053  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-07 15:29:37.053  1017  1128 D SecContentProvider2: mCursor = null
,09-07 15:29:37.053  1017  1125 V NetworkStats: performPollLocked() took 13ms
09-07 15:29:37.063  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit,
,09-07 15:29:37.063  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 15:29:37.063  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 15:29:37.063  1017  1128 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-07 15:29:37.073  1017  1128 E WifiConfigStore: setLastSelectedConfiguration -1
,09-07 15:29:37.073  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-07 15:29:37.073  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 15:29:37.083  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-07 15:29:37.083  1017  1546 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-07 15:29:37.083  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:37.083  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:37.083  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:37.083  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 15:29:37.083  1017  1546 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-07 15:29:37.083  1017  1128 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,09-07 15:29:37.083  1017  1130 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
,09-07 15:29:37.083  1017  1546 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:37.083  1017  1546 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:37.083  1017  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-07 15:29:37.083  1017  1130 E ConnectivityService: updateNetworkInfo()
09-07 15:29:37.083  1017  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 15:29:37.083  1017  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-07 15:29:37.083  1633  1633 I Hs20UtilService: Starting #14
,09-07 15:29:37.083  1633  1663 I Hs20UtilService: Message received 5007
,09-07 15:29:37.093  4781  4781 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-07 15:29:37.093  4781  4781 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-07 15:29:37.093  4781  4781 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-07 15:29:37.093  4781  4781 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-07 15:29:37.093  4781  4781 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-07 15:29:37.093  4781  4781 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-07 15:29:37.093  4781  4834 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-07 15:29:37.103  1017  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 15:29:37.113   278   990 D CommandListener: Setting iface cfg
,09-07 15:29:37.113  1017  1128 E WifiStateMachine: Start Dhcp Watchdog 2
,09-07 15:29:37.113  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-07 15:29:37.113  1017  1128 D SecContentProvider2: mCursor = null
,09-07 15:29:37.123  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-07 15:29:37.123  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-07 15:29:37.123  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-07 15:29:37.133  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-07 15:29:37.133  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:37.133  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:37.133  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 15:29:37.133  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-07 15:29:37.133  1017  1128 D SecContentProvider2: mCursor = null
,09-07 15:29:37.133  1017  1128 E WifiNative-wlan0: do suspend false
,09-07 15:29:37.143  1017  1127 D WifiP2pService: InactiveState{ what=143375 }
,09-07 15:29:37.143  1017  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-07 15:29:37.313  1017  1255 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-07 15:29:37.313  1017  1255 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-07 15:29:37.313  1017  1255 D SecContentProvider2: mCursor = null
,09-07 15:29:37.313  1017  1255 D WifiService: setWifiEnabled: false pid=6970, uid=10170
,09-07 15:29:37.323  1017  1255 D SettingsProvider: name = wifi_on
,09-07 15:29:37.333  1017  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 15:29:37.343  1017  1128 E WifiNative-wlan0: do suspend true
,09-07 15:29:37.353  7706  7706 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-07 15:29:37.363  7706  7706 I dhcpcd  : version 5.5.6 starting,
,09-07 15:29:37.363  1017  1127 D WifiP2pService: InactiveState{ what=143375 }
,09-07 15:29:37.363   278   990 D CommandListener: Clearing all IP addresses on wlan0
,09-07 15:29:37.363  7706  7706 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-07 15:29:37.373  1017  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-07 15:29:37.373  1017  1130 E ConnectivityService: updateNetworkInfo(),
09-07 15:29:37.373  1017  1130 E ConnectivityService: updateNetworkInfo()
09-07 15:29:37.373  1017  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 15:29:37.373  1017  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
09-07 15:29:37.373   278   990 E Netd    : no such netId 503
,09-07 15:29:37.373  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-07 15:29:37.373  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 15:29:37.373  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-07 15:29:37.373  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:37.373  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:37.373  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:37.373  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 15:29:37.383  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling,
,09-07 15:29:37.383  1017  1128 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost,
09-07 15:29:37.383  1017  1127 D WifiP2pService: InactiveState{ what=131204 }
09-07 15:29:37.383  1017  1130 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 15:29:37.383  1017  1127 D WifiP2pService: P2pEnabledState{ what=131204 }
09-07 15:29:37.383  1017  1130 D NetworkStatsFactory: UpdateStatsForKnox updated
09-07 15:29:37.383  1017  1130 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '79 network destroy 503' failed with '400 79 destroyNetwork() failed (Machine is not on the network)'
09-07 15:29:37.383  1017  1130 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-07 15:29:37.383  1017  1130 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null,
09-07 15:29:37.383  1017  1130 V NetworkStats: updateIfacesLocked()
09-07 15:29:37.383  1017  1130 V NetworkStats: performPollLocked(flags=0x1)
,09-07 15:29:37.393  1017  1127 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,09-07 15:29:37.393  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-07 15:29:37.393  1017  1130 V NetworkStats: performPollLocked() took 5ms
09-07 15:29:37.393  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 15:29:37.393  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-07 15:29:37.393  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-07 15:29:37.393  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:37.393  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:37.393  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:37.393  1017  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 15:29:37.393  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 1
09-07 15:29:37.393  1017  1017 D RttService: SCAN_AVAILABLE : 1
09-07 15:29:37.393  1017  1151 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:29:37.393  1017  1152 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-07 15:29:37.393  1017  3786 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-07 15:29:37.393  1017  3786 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-07 15:29:37.393  1017  3786 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:37.393  1017  3786 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:37.393  1017  3786 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-07 15:29:37.393  1633  1633 I Hs20UtilService: Starting #15,
09-07 15:29:37.393  1017  1130 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
09-07 15:29:37.393  1017  7703 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:29:37.393  1017  1130 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-07 15:29:37.393  1017  7703 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-07 15:29:37.393  1017  1130 D ConnectivityService: nai.networkMonitor.doQuit(),
09-07 15:29:37.393  1017  1130 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-07 15:29:37.393  1017  1130 E ConnectivityService: updateNetworkInfo()
,09-07 15:29:37.393  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 15:29:37.403  1633  1663 I Hs20UtilService: Message received 5007
09-07 15:29:37.393  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
09-07 15:29:37.393  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-07 15:29:37.393  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-07 15:29:37.403  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 15:29:37.403  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 15:29:37.403  1017  1127 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-07 15:29:37.403  1017  1130 E ConnectivityService: updateNetworkInfo()
,09-07 15:29:37.403  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-07 15:29:37.403  4781  4781 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-07 15:29:37.403  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-07 15:29:37.403  4781  4781 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-07 15:29:37.403  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-07 15:29:37.403  1017  1047 D WifiDisplayController: disconnect
09-07 15:29:37.403  1017  1047 D WifiDisplayController: updateConnection
09-07 15:29:37.403  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-07 15:29:37.403  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-07 15:29:37.403  1017  1127 D WifiP2pService: P2pDisablingState
,09-07 15:29:37.403  1017  1127 D WifiP2pService: P2pDisablingState{ what=147458 }
09-07 15:29:37.403  1017  1127 D WifiP2pService: p2p socket connection lost
,09-07 15:29:37.403  1017  1127 D WifiP2pService: P2pDisabledState
09-07 15:29:37.403  1017  1128 E WifiNative-wlan0: do suspend true
09-07 15:29:37.403  4781  4781 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-07 15:29:37.413  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,09-07 15:29:37.413  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
09-07 15:29:37.413  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-07 15:29:37.413  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-07 15:29:37.413  1175  1175 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-07 15:29:37.413  1017  3796 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-07 15:29:37.413  1175  1175 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-07 15:29:37.413  4781  4781 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-07 15:29:37.413  4781  4781 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-07 15:29:37.413  4781  4781 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-07 15:29:37.413  4781  4834 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-07 15:29:37.423  4781  4781 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-07 15:29:37.423  4781  4781 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-07 15:29:37.423  4781  4781 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-07 15:29:37.423  4781  4781 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-07 15:29:37.423  4781  4781 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-07 15:29:37.423  4781  4781 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-07 15:29:37.423  4781  4834 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-07 15:29:37.423  7305  7305 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
09-07 15:29:37.423  7305  7305 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-07 15:29:37.423  7305  7305 D FileShare-Client: Outbound.stopDelayTimer - 
,09-07 15:29:37.433  7336  7336 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null,
,09-07 15:29:37.443  1017  1127 D WifiP2pService: P2pDisabledState{ what=143375 }
,09-07 15:29:37.443  1017  1127 D WifiP2pService: DefaultState{ what=143375 }
,09-07 15:29:37.443   278   990 D CommandListener: Clearing all IP addresses on wlan0
,09-07 15:29:37.443  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
09-07 15:29:37.443  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 15:29:37.443  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-07 15:29:37.443  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 15:29:37.443  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 15:29:37.443  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:37.443  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-07 15:29:37.443  7706  7706 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
09-07 15:29:37.443  7706  7706 E dhcpcd  : wlan0: sendmsg: Network is unreachable
09-07 15:29:37.443  7706  7706 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E),
,09-07 15:29:37.443  7706  7706 I dhcpcd  : bssid match
09-07 15:29:37.443  7706  7706 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
09-07 15:29:37.443  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-07 15:29:37.453  7568  7568 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-07 15:29:37.453  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-07 15:29:37.453  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-07 15:29:37.453  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-07 15:29:37.453  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:37.453  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:37.453  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 15:29:37.453  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 15:29:37.463  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-07 15:29:37.463  1017  1128 D SecContentProvider2: mCursor = null
,09-07 15:29:37.463  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-07 15:29:37.463  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-07 15:29:37.473  4781  4781 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-07 15:29:37.473  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-07 15:29:37.473  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 15:29:37.473  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:37.473  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:37.473  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:37.473  1017  1503 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-07 15:29:37.473  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-07 15:29:37.473  1017  1503 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-07 15:29:37.473  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
09-07 15:29:37.473  1017  1503 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:37.473  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-07 15:29:37.473  1017  1503 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:37.473  1017  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-07 15:29:37.473  1175  1718 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-07 15:29:37.473  1633  1633 I Hs20UtilService: Starting #16
09-07 15:29:37.473  1633  1663 I Hs20UtilService: Message received 5007
,09-07 15:29:37.473  1175  1175 D HotspotTile: onReceive : 0, 0
,09-07 15:29:37.473  6970  6970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 15:29:37.473  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:29:37.473  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:37.473  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:37.473  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 15:29:37.473  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 15:29:37.473  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:29:37.473  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:29:37.473  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 15:29:37.473  6970  6970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:29:37.473  6970  6970 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 15:29:37.473  6970  6970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:29:37.473  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:29:37.473  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:37.473  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:37.473  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 15:29:37.473  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 15:29:37.473  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:29:37.473  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:29:37.473  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 15:29:37.483  4781  4781 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-07 15:29:37.483  4781  4781 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-07 15:29:37.483  6970  6970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:29:37.483  6970  6970 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 15:29:37.483  4781  4781 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-07 15:29:37.483  4781  4781 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-07 15:29:37.483  4781  4781 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-07 15:29:37.483  4781  4781 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-07 15:29:37.483  4781  4834 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-07 15:29:37.483  1017  3795 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-07 15:29:37.483  1017  3795 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-07 15:29:37.493  1017  3795 W ActivityManager: userId = 0, bbcId = -10000
,09-07 15:29:37.493  1017  3795 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:37.493  1017  3795 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-07 15:29:37.493  1017  1095 V AlarmManager: waitForAlarm result :4
,09-07 15:29:37.493  7374  7374 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-07 15:29:37.493  7374  7374 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-07 15:29:37.493  7374  7374 D SecurityLogAgent: StateMachine : Current State = 1
09-07 15:29:37.493  7374  7374 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-07 15:29:37.503  1633  1633 I Hs20UtilService: Starting #17
,09-07 15:29:37.503  1633  1663 I Hs20UtilService: Message received 5011
,09-07 15:29:37.513  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
,09-07 15:29:37.513  1017  1042 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 15:29:37.513  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,09-07 15:29:37.563  7706  7706 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1,
,09-07 15:29:37.633  7568  7568 I wpa_supplicant: Blacklist: Clear (all) 
,09-07 15:29:37.653  7706  7706 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds
,09-07 15:29:37.683  1017  1042 W ActivityManager: mDVFSHelper.release()
,09-07 15:29:37.723  7568  7568 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-07 15:29:37.723  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-07 15:29:37.723  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
09-07 15:29:37.723  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,09-07 15:29:37.743  7568  7568 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1,
09-07 15:29:37.743  7568  7568 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-07 15:29:37.743  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-07 15:29:37.743  7568  7568 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-07 15:29:37.743  7568  7568 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-07 15:29:37.743  7568  7568 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
09-07 15:29:37.743  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-07 15:29:37.743  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-07 15:29:37.753  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-07 15:29:37.753  1017  1131 D Tethering: InitialState.processMessage what=4
09-07 15:29:37.753  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
09-07 15:29:37.753  1017  1131 E Tethering: No numeric data
09-07 15:29:37.753  1017  1125 V NetworkStats: performPollLocked(flags=0x1)
09-07 15:29:37.753  1017  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-07 15:29:37.753  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-07 15:29:37.753  1017  1131 D Tethering: clearTetheredNotification()
09-07 15:29:37.753  1175  1175 D HotspotTile: updateTetherState():false, false
09-07 15:29:37.753  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 15:29:37.753  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-07 15:29:37.753  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
09-07 15:29:37.753  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-07 15:29:37.753  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-07 15:29:37.753  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
09-07 15:29:37.753  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-07 15:29:37.763  1017  1125 V NetworkStats: performPollLocked() took 4ms
09-07 15:29:37.763  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 15:29:37.763  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 15:29:37.763  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 15:29:38.023  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
,09-07 15:29:38.023  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-07 15:29:38.023  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-07 15:29:38.043  7568  7568 I wpa_supplicant: Blacklist: Clear (all) 
,09-07 15:29:38.133  7568  7568 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
,09-07 15:29:38.133  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
,09-07 15:29:38.133  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-07 15:29:38.133  1017  1044 D Tethering: interfaceStatusChanged wlan0, false,
,09-07 15:29:38.243  1017  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0,
09-07 15:29:38.243  1017  1128 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-07 15:29:38.243  7351  7351 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
,09-07 15:29:38.253  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-07 15:29:38.263  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 15:29:38.263  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-07 15:29:38.263  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-07 15:29:38.263  1175  1718 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-07 15:29:38.263  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:38.263  1175  1175 D HotspotTile: onReceive : 1, 0
09-07 15:29:38.263  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:38.263  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:38.263  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:38.263  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-07 15:29:38.263  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
09-07 15:29:38.263  1755  2203 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 15:29:38.263  4781  4781 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-07 15:29:38.263  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:29:38.273  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:29:38.273  1017  1520 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-07 15:29:38.273  1017  1520 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-07 15:29:38.273  1017  1520 W ActivityManager: userId = 0, bbcId = -10000
,09-07 15:29:38.273  1017  1520 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:38.273  1017  1520 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-07 15:29:38.283  1633  1633 I Hs20UtilService: Starting #18
,09-07 15:29:38.283  1633  1663 I Hs20UtilService: Message received 5011
,09-07 15:29:38.283  7374  7374 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-07 15:29:38.283  7374  7374 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-07 15:29:38.283  7374  7374 D SecurityLogAgent: StateMachine : Current State = 1
09-07 15:29:38.283  7374  7374 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-07 15:29:38.833   288   288 E SMD     : DCD OFF
,09-07 15:29:39.093   278   982 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,09-07 15:29:39.093  1017  1044 D Tethering: interfaceRemoved wlan0
,09-07 15:29:39.093  1017  1044 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-07 15:29:39.223  1017  1044 D Tethering: interfaceRemoved p2p0
09-07 15:29:39.223  1017  1044 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-07 15:29:40.013  1017  1095 V AlarmManager: waitForAlarm result :4
,09-07 15:29:40.013   278   986 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-07 15:29:40.013   278   986 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,09-07 15:29:40.023  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
,09-07 15:29:40.023  1017  1042 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 15:29:40.023  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,09-07 15:29:40.033  1017  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1,
,09-07 15:29:40.083  1017  3359 D SSRM:n  : SIOP:: AP = 360
,09-07 15:29:40.123  1017  3375 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-07 15:29:40.333  6970  7226 D BluetoothAdapter: enable()
,09-07 15:29:40.333  1017  1520 W ActivityManager: Permission Denial: getCurrentUser() from pid=6970, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-07 15:29:40.333  1017  1520 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-07 15:29:40.333  1017  1520 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6970, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-07 15:29:40.333  1017  1520 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-07 15:29:40.333  1017  1520 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
09-07 15:29:40.333  1017  1520 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
09-07 15:29:40.333  1017  1520 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
09-07 15:29:40.333  1017  1520 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-07 15:29:40.333  1017  1520 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-07 15:29:40.333  1017  1520 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-07 15:29:40.343  1017  1520 D SettingsProvider: name = bluetooth_on,
,09-07 15:29:40.343  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
09-07 15:29:40.343  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
,09-07 15:29:40.353  1017  1046 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-07 15:29:40.353  3212  3291 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,09-07 15:29:40.353  3212  3291 D BluetoothAdapterProperties: Setting state to 11
,09-07 15:29:40.353  3212  3291 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,09-07 15:29:40.353  3212  3291 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-07 15:29:40.353  3212  3291 D BluetoothAdapterService: updateAdapterState state is 11
,09-07 15:29:40.363  3212  3291 D BluetoothAdapterService: Autoconnection is available 
09-07 15:29:40.363  3212  3291 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
09-07 15:29:40.363  3212  3291 D BtConfig.SecureMode: isSecureModeOn:false
09-07 15:29:40.363  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-07 15:29:40.363  3212  3291 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
09-07 15:29:40.363  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-07 15:29:40.363  3212  3291 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
,09-07 15:29:40.363  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-07 15:29:40.363  3212  3291 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
09-07 15:29:40.363  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-07 15:29:40.363  3212  3291 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
09-07 15:29:40.363  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-07 15:29:40.363  3212  3291 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
09-07 15:29:40.363  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-07 15:29:40.363  3212  3291 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
09-07 15:29:40.363  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-07 15:29:40.363  3212  3291 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
09-07 15:29:40.363  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-07 15:29:40.363  3212  3291 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
09-07 15:29:40.363  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-07 15:29:40.363  3212  3291 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-07 15:29:40.363  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService,
09-07 15:29:40.363  3212  3291 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-07 15:29:40.363  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-07 15:29:40.363  3212  3291 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-07 15:29:40.363  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService,
,09-07 15:29:40.363  3212  3291 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
09-07 15:29:40.363  3212  3291 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
09-07 15:29:40.363  3212  3291 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
09-07 15:29:40.363  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-07 15:29:40.363  3212  3291 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-07 15:29:40.363  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-07 15:29:40.363  1017  1017 I InputMethodManagerService: [BT Setting State] State =11
,09-07 15:29:40.373  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-07 15:29:40.373  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-07 15:29:40.383  1175  1175 D BluetoothTile:  getBluetoothState : 11
,09-07 15:29:40.383  1175  1718 D BluetoothTile:  handleUpdatestate:false name:null
,09-07 15:29:40.383  1175  1718 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-07 15:29:40.383  1882  1882 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-07 15:29:40.383  4781  4781 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-07 15:29:40.383  1017  1477 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-07 15:29:40.393  1017  1544 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-07 15:29:40.393  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:29:40.393  1017  1504 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-07 15:29:40.393  1017  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-07 15:29:40.393  1017  1504 W ActivityManager: userId = 0, bbcId = -10000,
09-07 15:29:40.393  1017  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:40.393  1017  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-07 15:29:40.393  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-07 15:29:40.393  3212  3291 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
09-07 15:29:40.393  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-07 15:29:40.393  3212  3291 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-07 15:29:40.393  1017  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 15:29:40.393  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-07 15:29:40.393  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:40.393  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:40.393  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-07 15:29:40.403  3212  3212 D HeadsetService: Received start request. Starting profile...
09-07 15:29:40.403  3212  3212 D HeadsetService: start()
09-07 15:29:40.403  3212  3212 D HeadsetStateMachine: make
,09-07 15:29:40.403  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:29:40.403  1679  1679 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 15:29:40.403  3212  3291 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
09-07 15:29:40.403  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-07 15:29:40.403  3212  3291 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-07 15:29:40.403  1017  1477 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 15:29:40.403  1017  1477 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-07 15:29:40.403  1017  1477 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:40.403  1017  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:40.403  1017  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 15:29:40.413  3212  3212 E HeadsetStateMachine: # of Max HF connection is 2
,09-07 15:29:40.413  3212  3291 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,09-07 15:29:40.413  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-07 15:29:40.413  3212  3291 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-07 15:29:40.423  1017  1136 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-07 15:29:40.423  1017  1136 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-07 15:29:40.423  4781  4781 D BluetoothNotiBroadcastReceiver: onReceive
,09-07 15:29:40.423  1017  1136 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:40.423  1017  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:40.423  1017  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 15:29:40.423  1017  1504 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,09-07 15:29:40.423  1017  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-07 15:29:40.423  3212  3291 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,09-07 15:29:40.423  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-07 15:29:40.423  3212  3291 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-07 15:29:40.423  1017  1504 W ActivityManager: userId = 0, bbcId = -10000
,09-07 15:29:40.423  1017  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:40.433  1017  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-07 15:29:40.433  1017  1546 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-07 15:29:40.433  1017  1546 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-07 15:29:40.433  1017  1546 W ActivityManager: userId = 0, bbcId = -10000
,09-07 15:29:40.433  1017  1546 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:40.433  1017  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 15:29:40.433  1017  1501 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
09-07 15:29:40.433  1017  1501 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-07 15:29:40.433  3212  3291 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
09-07 15:29:40.433  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-07 15:29:40.433  3212  3291 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-07 15:29:40.443  1017  1501 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:40.443  1017  1501 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 15:29:40.443  1017  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-07 15:29:40.443  3212  3212 I bluedroid: get_profile_interface handsfree
09-07 15:29:40.443  1017  3795 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 15:29:40.443  1017  3795 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:40.443  1017  3795 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
09-07 15:29:40.443  1017  3795 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 15:29:40.443  1017  1520 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 15:29:40.443  1017  3795 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-07 15:29:40.443  1017  1520 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
09-07 15:29:40.443  3212  3291 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
09-07 15:29:40.443  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-07 15:29:40.443  3212  3291 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-07 15:29:40.443  1017  1520 W ActivityManager: userId = 0, bbcId = -10000
,09-07 15:29:40.443  1017  1520 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:40.443  1017  1520 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 15:29:40.453  3212  3291 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,09-07 15:29:40.453  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-07 15:29:40.453  3212  3291 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,09-07 15:29:40.453  3212  3291 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
,09-07 15:29:40.453  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-07 15:29:40.453  3212  3291 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,09-07 15:29:40.453  3212  3291 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
,09-07 15:29:40.453  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-07 15:29:40.453  3212  3291 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,09-07 15:29:40.453  3212  3291 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
09-07 15:29:40.453  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-07 15:29:40.453  3212  3291 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-07 15:29:40.453  3212  3291 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-07 15:29:40.453  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-07 15:29:40.463  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-07 15:29:40.463  1017  1503 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-07 15:29:40.463  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:40.463  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:40.463  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:40.463  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:40.483  7741  7741 E Zygote  : MountEmulatedStorage(),
,09-07 15:29:40.483  7741  7741 E Zygote  : v2
,09-07 15:29:40.483  1017  1503 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7741 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
09-07 15:29:40.483  3212  3212 E DualScoManager: Dual Sco Manager already instantiated
09-07 15:29:40.483  7741  7741 I libpersona: KNOX_SDCARD checking this for 10055
09-07 15:29:40.483  3212  3212 I DualScoManager: Set HeadsetServiceHelper
09-07 15:29:40.483  7741  7741 I libpersona: KNOX_SDCARD not a persona
09-07 15:29:40.483  3212  3212 D BluetoothAtMessage: createCMTIContentObservers
,09-07 15:29:40.483  1017  1545 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,09-07 15:29:40.483  1017  1545 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 15:29:40.483  1017  1545 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 15:29:40.483  1017  1545 D SettingsProvider: selectionArgs: false
09-07 15:29:40.483  1017  1545 D SettingsProvider: selectionArgs: 1002
09-07 15:29:40.483  1017  1545 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 15:29:40.483  1017  1545 D SettingsProvider: ret = -1
,09-07 15:29:40.483  3212  7740 D HeadsetStateMachine: Enter Disconnected: -2
09-07 15:29:40.483  7741  7741 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 15:29:40.483  3212  3212 D HeadsetService: mStartError = false
09-07 15:29:40.483  3212  3212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26244bf3
,09-07 15:29:40.493  3212  3212 D A2dpService: Received start request. Starting profile...
09-07 15:29:40.493  3212  3212 D A2dpService: start(),
09-07 15:29:40.493  3212  3212 I bluedroid: get_profile_interface avrcp
,09-07 15:29:40.493  7741  7741 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-07 15:29:40.493  3212  7740 D HeadsetStateMachine: Clear mHeadsetBrsf,
09-07 15:29:40.493  3212  7740 D HeadsetStateMachine: map size, before remove : 0
09-07 15:29:40.493  3212  7740 D HeadsetStateMachine: map size, after remove: 0
09-07 15:29:40.493  7741  7741 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-07 15:29:40.493  3212  3212 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-07 15:29:40.493  3212  3212 D Avrcp   : Initialize Media Controller
09-07 15:29:40.493  3212  3212 D Avrcp   : Get the Context Package Name: com.android.bluetooth
09-07 15:29:40.493  3212  3212 E Avrcp   : getActiveSessions
09-07 15:29:40.493  3212  3212 D Avrcp   : pick active media Controller
09-07 15:29:40.493  3212  3212 D Avrcp   : Get the active Media Controller 
,09-07 15:29:40.503  3212  3212 I Avrcp   :  Updating now playing list upon AVRCP Start,
09-07 15:29:40.503  3212  3212 D A2dpStateMachine: make
09-07 15:29:40.503  3212  7747 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-07 15:29:40.503  3212  3212 I bluedroid: get_profile_interface a2dp
09-07 15:29:40.503  3212  7751 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-07 15:29:40.503  3212  3212 E bt-btif : warning : media task started media_task_refcnt 1 
,09-07 15:29:40.503  3212  3212 D A2dpService: mStartError = false
09-07 15:29:40.503  3212  3212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26244bf3
09-07 15:29:40.513  3212  3212 D HidService: Received start request. Starting profile...
09-07 15:29:40.513  3212  3212 D HidService: start()
09-07 15:29:40.513  3212  3212 I bluedroid: get_profile_interface hidhost
09-07 15:29:40.513  3212  3212 D HidService: setHidService(): set to: null
09-07 15:29:40.513  3212  3212 D HidService: mStartError = false
09-07 15:29:40.513  3212  3212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26244bf3
09-07 15:29:40.513  3212  7750 D A2dpStateMachine: Enter Disconnected: -2,
09-07 15:29:40.513  3212  3212 D HealthService: Received start request. Starting profile...
09-07 15:29:40.513  3212  3212 D HealthService: start()
09-07 15:29:40.513  3212  3212 I bluedroid: get_profile_interface health
09-07 15:29:40.513  3212  3212 D HealthService: mStartError = false
09-07 15:29:40.513  3212  3212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26244bf3
,09-07 15:29:40.513  3212  3212 D HeadsetStateMachine: Try to query the phonestate on bind
,09-07 15:29:40.513  1453  1465 I Telecom : BluetoothPhoneService: queryPhoneState
,09-07 15:29:40.513  1453  1453 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
09-07 15:29:40.513  1453  1453 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
09-07 15:29:40.513  1453  1465 I Telecom : BluetoothPhoneService: Result of Message : true
09-07 15:29:40.523  3212  3212 D PanService: Received start request. Starting profile...
09-07 15:29:40.523  3212  7747 D BluetoothMediaBrowser: no now playing list
09-07 15:29:40.523  3212  3212 D PanService: start()
09-07 15:29:40.523  3212  7747 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
09-07 15:29:40.523  3212  3212 D BluetoothPanServiceJni: initializeNative(L110): pan
09-07 15:29:40.523  3212  3212 I bluedroid: get_profile_interface pan
09-07 15:29:40.523  3212  3212 D PanService: mStartError = false
09-07 15:29:40.523  3212  3212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26244bf3
09-07 15:29:40.523  3212  3212 D HeadsetStateMachine: Proxy object connected
09-07 15:29:40.523  3212  3212 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
09-07 15:29:40.523  3212  7740 D HeadsetStateMachine: Disconnected process message: 11
,09-07 15:29:40.523  3212  3212 D BluetoothMapService: Received start request. Starting profile...
09-07 15:29:40.523  3212  3212 D BluetoothMapService: start()
,09-07 15:29:40.523  3212  3212 D BluetoothMapService: mStartError = false
09-07 15:29:40.523  3212  3212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26244bf3
,09-07 15:29:40.523  3212  3212 D SapService: Received start request. Starting profile...
09-07 15:29:40.523  3212  3212 D SapService: start()
09-07 15:29:40.523  3212  3212 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-07 15:29:40.523  3212  3212 I bluedroid: get_profile_interface sap
09-07 15:29:40.523  3212  3212 D SapService: mStartError = false
09-07 15:29:40.523  3212  3212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26244bf3
09-07 15:29:40.523  3212  3212 D HeadsetPhoneState: sendDeviceDataStateChanged
09-07 15:29:40.523  3212  3212 D HeadsetPhoneState: Signal level : previous=0 curr=4
09-07 15:29:40.523  3212  3212 E BluetoothAdapterService(639912947): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-07 15:29:40.523  3212  3212 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-07 15:29:40.523  3212  3212 E BluetoothAdapterService(639912947): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-07 15:29:40.523  3212  3212 E BluetoothAdapterService(639912947): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-07 15:29:40.523  3212  3212 E BluetoothAdapterService(639912947): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-07 15:29:40.523  3212  7740 D HeadsetStateMachine: Disconnected process message: 18
09-07 15:29:40.523  3212  7740 D HeadsetStateMachine: Disconnected process message: 10
09-07 15:29:40.523  3212  7740 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-07 15:29:40.523  3212  7740 D HeadsetStateMachine: Disconnected process message: 11
,09-07 15:29:40.523  3212  3212 E BluetoothAdapterService(639912947): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-07 15:29:40.543  3212  3212 E BluetoothAdapterService(639912947): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,09-07 15:29:40.543  3212  3212 E BluetoothAdapterService(639912947): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
09-07 15:29:40.543  7741  7741 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 15:29:40.543  7741  7741 D ActivityThread: Added TimaKeyStore provider
,09-07 15:29:40.543  3212  3291 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,09-07 15:29:40.543  3212  3291 I bluedroid: enable
,09-07 15:29:40.553  3212  3294 E bt-btif : Calling BTA_HhEnable
,09-07 15:29:40.553  3212  3294 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,09-07 15:29:40.553  3212  3294 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,09-07 15:29:40.563  3212  3294 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-07 15:29:40.563  3212  3294 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
,09-07 15:29:40.563  3212  3294 E BluetoothServiceJni: populateRssiValuesNative
09-07 15:29:40.563  3212  3294 I bluedroid: getModelRssiValues
09-07 15:29:40.563  3212  3294 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,09-07 15:29:40.563  3212  3294 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-07 15:29:40.563  3212  3294 D BluetoothAdapterProperties: Name is: Galaxy A3
,09-07 15:29:40.563  1017  1017 D SettingsProvider: name = bluetooth_name
,09-07 15:29:40.563  3212  3294 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-07 15:29:40.563  3212  3294 D BluetoothAdapterProperties: Scan Mode:20
09-07 15:29:40.563  3212  3294 D BluetoothAdapterProperties: Discoverable Timeout:120
09-07 15:29:40.563  3212  3294 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
09-07 15:29:40.563  3212  3294 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
09-07 15:29:40.563  3212  3294 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
09-07 15:29:40.563  3212  3294 E bt-btif : btif_sock_init: !radio_req && !rfc_init
09-07 15:29:40.573  3212  3294 E bt-btif : JVenable fails
,09-07 15:29:40.573  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:29:40.573  3212  3294 D bte_conf: Device ID record 1 : primary
09-07 15:29:40.573  3212  3294 D bte_conf:   vendorId            = 0075
09-07 15:29:40.573  3212  3294 D bte_conf:   vendorIdSource      = 0001
09-07 15:29:40.573  3212  3294 D bte_conf:   product             = 0100
09-07 15:29:40.573  3212  3294 D bte_conf:   version             = 0200
09-07 15:29:40.573  3212  3294 D bte_conf:   clientExecutableURL = 
09-07 15:29:40.573  3212  3294 D bte_conf:   serviceDescription  = 
09-07 15:29:40.573  3212  3294 D bte_conf:   documentationURL    = 
09-07 15:29:40.573  3212  3294 D bte_conf: bte_load_did_conf no section named DID2.
09-07 15:29:40.573  3212  3294 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
09-07 15:29:40.573  3212  3294 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-07 15:29:40.573  3212  3291 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,09-07 15:29:40.573  3212  3291 D BluetoothAdapterProperties: ScanMode =  20
,09-07 15:29:40.573  3212  3291 D BluetoothAdapterProperties: State =  11
09-07 15:29:40.573  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-07 15:29:40.573  1017  1546 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled,
09-07 15:29:40.573  3212  3291 D BluetoothAdapterProperties: Setting state to 12
09-07 15:29:40.573  3212  3291 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-07 15:29:40.573  3212  3294 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-07 15:29:40.573  3212  3294 D BluetoothAdapterProperties: Scan Mode:21
,09-07 15:29:40.583  3212  3294 D BluetoothAdapterProperties: Discoverable Timeout:120
09-07 15:29:40.583  1017  1136 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,09-07 15:29:40.583  1017  1136 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 15:29:40.583  1017  1136 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 15:29:40.583  1017  1136 D SettingsProvider: selectionArgs: false
09-07 15:29:40.583  1017  1136 D SettingsProvider: selectionArgs: 1002
09-07 15:29:40.583  1017  1136 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 15:29:40.583  1017  1136 D SettingsProvider: ret = -1
,09-07 15:29:40.583  3212  3291 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-07 15:29:40.583  3212  3291 D BluetoothAdapterService: updateAdapterState state is 12
,09-07 15:29:40.583  1017  1545 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 15:29:40.583  1017  1545 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-07 15:29:40.583  1017  1545 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:40.583  1017  1545 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:40.583  1017  1545 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 15:29:40.583  1017  1046 D BluetoothPan: Binding service...
,09-07 15:29:40.583  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-07 15:29:40.583  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-07 15:29:40.583  4781  4791 D BluetoothPan: Binding service...
,09-07 15:29:40.583  3212  3291 D BluetoothAdapterService: Autoconnection is available 
09-07 15:29:40.583  3212  3291 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-07 15:29:40.583  3212  3291 D BluetoothAdapterService: starting service from this receiver
09-07 15:29:40.583  1017  1255 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 15:29:40.583  1017  1255 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-07 15:29:40.583  1017  1255 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:40.583  1017  1255 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:40.583  1017  1255 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 15:29:40.593  3212  3291 I BluetoothAdapterState: Entering On State from state = 11
,09-07 15:29:40.593  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-07 15:29:40.593  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-07 15:29:40.593  3212  3212 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-07 15:29:40.593  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:40.593  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:40.593  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-07 15:29:40.593  1017  1017 D BluetoothPan: BluetoothPAN Proxy object connected
09-07 15:29:40.593  4781  4781 D BluetoothPan: BluetoothPAN Proxy object connected
09-07 15:29:40.593  4781  4781 D PanProfile: Bluetooth service connected
09-07 15:29:40.593  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-07 15:29:40.593  1453  1474 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-07 15:29:40.593  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-07 15:29:40.593  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:40.593  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:40.593  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-07 15:29:40.593  1453  1474 E BluetoothHeadset: BluetoothHeadset service is binded
,09-07 15:29:40.593  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=true
09-07 15:29:40.593  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-07 15:29:40.593  1017  1046 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-07 15:29:40.593  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-07 15:29:40.603  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:29:40.603  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:40.603  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:40.603  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 15:29:40.603  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:29:40.603  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:29:40.603  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:29:40.603  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 15:29:40.603  4781  7278 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-07 15:29:40.603  4781  7278 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-07 15:29:40.603  7741  7741 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-07 15:29:40.603  6970  6970 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 15:29:40.603  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-07 15:29:40.603  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-07 15:29:40.603  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,09-07 15:29:40.603  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:40.603  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-07 15:29:40.603  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:29:40.603  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:40.603  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:40.603  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 15:29:40.603  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:29:40.603  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:29:40.603  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:29:40.603  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 15:29:40.613  6970  6981 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 15:29:40.613  3212  3212 I BluetoothPbapService: Handler(): got msg=1
,09-07 15:29:40.613  6970  6981 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 15:29:40.613  3212  3221 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 15:29:40.613  1017  3785 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
09-07 15:29:40.613  3212  3221 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 15:29:40.613  1175  1639 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 15:29:40.613  1175  1639 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 15:29:40.613  1755  1773 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 15:29:40.613  1755  1773 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 15:29:40.613  1017  1046 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-07 15:29:40.613  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-07 15:29:40.613  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-07 15:29:40.613  1017  1046 E BluetoothHeadset: BluetoothHeadset service is binded
09-07 15:29:40.613  3212  3226 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-07 15:29:40.613  3212  3226 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-07 15:29:40.613  6970  6970 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 15:29:40.613  1017  1046 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-07 15:29:40.613  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-07 15:29:40.613  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:40.623  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:40.623  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 15:29:40.623  3212  3212 D BluetoothA2dp: Proxy object connected
09-07 15:29:40.623  3212  3212 D BluetoothAdapterService: Bluetooth A2dp source service connected
09-07 15:29:40.623  4781  4781 D BluetoothA2dp: Proxy object connected
09-07 15:29:40.623  4781  4781 D A2dpProfile: Bluetooth service connected
09-07 15:29:40.623  4781  4789 D BluetoothPbap: onBluetoothStateChange: up=true
,09-07 15:29:40.623  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-07 15:29:40.623  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-07 15:29:40.623  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:40.623  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:40.623  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-07 15:29:40.623  3212  7763 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-07 15:29:40.623  4781  4781 D BluetoothPbap: Proxy object connected
,09-07 15:29:40.623  4781  4781 D PbapServerProfile: Bluetooth service connected
09-07 15:29:40.623  4781  7278 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-07 15:29:40.623  1017  1017 D BluetoothA2dp: Proxy object connected
,09-07 15:29:40.623  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
09-07 15:29:40.623  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-07 15:29:40.623  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:40.623  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:40.623  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-07 15:29:40.623  4781  4781 D BluetoothInputDevice: Proxy object connected
,09-07 15:29:40.623  1453  1465 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 15:29:40.623  1453  1465 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-07 15:29:40.633  4781  4791 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 15:29:40.633  4781  4791 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-07 15:29:40.633  3212  7763 D BluetoothSocket: bindListen(): myUserId = 0
09-07 15:29:40.633  3212  7763 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 15:29:40.633  7264  7274 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 15:29:40.633  7264  7274 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-07 15:29:40.633  4781  4781 D HidProfile: Bluetooth service connected
,09-07 15:29:40.633  3212  7763 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
09-07 15:29:40.633  3212  7763 D BluetoothSocket: bindListen(), new LocalSocket 
09-07 15:29:40.633  3212  7763 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-07 15:29:40.633  3212  7763 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@ea3bcdf
09-07 15:29:40.633  3212  7763 D BluetoothSocket: channel: 19
09-07 15:29:40.633  3212  7763 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
09-07 15:29:40.633  1480  1496 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 15:29:40.633  1480  1496 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 15:29:40.633  4781  4789 D BluetoothMap: onBluetoothStateChange: up=true
,09-07 15:29:40.633  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
09-07 15:29:40.633  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-07 15:29:40.633  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:40.633  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:40.633  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-07 15:29:40.633  4781  4781 D BluetoothMap: Proxy object connected
,09-07 15:29:40.633  1453  1474 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-07 15:29:40.633  4781  4781 D MapProfile: Bluetooth service connected
,09-07 15:29:40.633  4781  4781 D BluetoothMap: getConnectedDevices()
09-07 15:29:40.633  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-07 15:29:40.633  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-07 15:29:40.643  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:40.643  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:40.643  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-07 15:29:40.643  1453  1474 E BluetoothHeadset: BluetoothHeadset service is binded
09-07 15:29:40.643  7741  7741 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,09-07 15:29:40.643  7741  7741 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-07 15:29:40.643  7741  7741 D UserAnalysis: Create SecureDbHelper
,09-07 15:29:40.643  1463  1488 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-07 15:29:40.643  1463  1488 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 15:29:40.643  4781  4791 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-07 15:29:40.643  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-07 15:29:40.643  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-07 15:29:40.643  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:40.643  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:40.643  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-07 15:29:40.643  4781  4781 D HeadsetProfile: Bluetooth service connected
09-07 15:29:40.643  4781  4791 E BluetoothHeadset: BluetoothHeadset service is binded
,09-07 15:29:40.643  1679  2215 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 15:29:40.643  1679  2215 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 15:29:40.643  4781  7278 D Bluetoothsap: onBluetoothStateChange: up=true
,09-07 15:29:40.653  4781  7278 D Bluetoothsap: Binding service...
,09-07 15:29:40.653  7741  7741 D IntelligenceServiceApplication: onCreate()
,09-07 15:29:40.653  4781  7278 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-07 15:29:40.653  1017  3786 I ActivityManager: Killing 7264:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,09-07 15:29:40.663  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
09-07 15:29:40.663  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-07 15:29:40.663  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,09-07 15:29:40.663  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:40.663  7741  7741 D IntelligenceServiceApplication: no applications having user consent for prediction
09-07 15:29:40.663  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
09-07 15:29:40.663  4781  7278 D Bluetoothsap: bindService called to Bluetooth SAP Service
09-07 15:29:40.663  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 15:29:40.663  1017  1046 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 15:29:40.663  1480  1491 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-07 15:29:40.663  1017  1545 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-07 15:29:40.663  7741  7741 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,09-07 15:29:40.663  1017  1046 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-07 15:29:40.663  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-07 15:29:40.663  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:40.663  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:40.663  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-07 15:29:40.663  1480  1491 E BluetoothHeadset: BluetoothHeadset service is binded
,09-07 15:29:40.673  1453  1465 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-07 15:29:40.673  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-07 15:29:40.673  7741  7741 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
09-07 15:29:40.673  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-07 15:29:40.673  4781  4781 D Bluetoothsap: BluetoothSAP Proxy object connected
,09-07 15:29:40.673  4781  4781 D SapProfile: Bluetooth service connected
09-07 15:29:40.673  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:40.673  4781  4781 D Bluetoothsap: getConnectedDevices()
,09-07 15:29:40.673  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:40.673  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-07 15:29:40.673  1453  1465 E BluetoothHeadset: BluetoothHeadset service is binded
09-07 15:29:40.673  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-07 15:29:40.673  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-07 15:29:40.673  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-07 15:29:40.673  1017  1017 I InputMethodManagerService: [BT Setting State] State =12
09-07 15:29:40.673  1017  1017 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-07 15:29:40.683  1453  1453 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@1c533ee6, true
,09-07 15:29:40.683  1453  1453 D BluetoothHeadset: registerMessageListener
,09-07 15:29:40.683  1175  1175 D BluetoothTile:  onBluetoothStateChange:
09-07 15:29:40.683  1882  1882 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-07 15:29:40.683  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-07 15:29:40.683  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-07 15:29:40.683  1175  1175 D BluetoothTile:  getBluetoothState : 12
,09-07 15:29:40.693  4781  4781 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-07 15:29:40.693  1175  1718 D BluetoothTile:  handleUpdatestate:false name:null
,09-07 15:29:40.693  3212  3221 D HeadsetService: registerMessageListener
,09-07 15:29:40.693  3212  3221 D HeadsetService: registerMessageListener
,09-07 15:29:40.693  1453  1453 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-07 15:29:40.693  1453  1453 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
09-07 15:29:40.693  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:29:40.693  3212  7740 D HeadsetStateMachine: Disconnected process message: 70
09-07 15:29:40.693  3212  7740 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@12bd8d2c
,09-07 15:29:40.693  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:29:40.693  4781  4781 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
09-07 15:29:40.693  4781  4781 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-07 15:29:40.693  4781  4781 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-07 15:29:40.693  4781  4781 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-07 15:29:40.693  1453  1453 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
09-07 15:29:40.693  1453  1453 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,09-07 15:29:40.703  3212  7766 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-07 15:29:40.703  1453  1453 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-07 15:29:40.703  1017  3785 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-07 15:29:40.703  1017  3795 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-07 15:29:40.703  3212  7740 D HeadsetStateMachine: Disconnected process message: 9
09-07 15:29:40.703  3212  7740 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-07 15:29:40.703  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-07 15:29:40.703   283   283 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
09-07 15:29:40.703  1175  1718 D BluetoothTile:  handleUpdatestate:false name:null
09-07 15:29:40.703   283   283 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-07 15:29:40.703   283   283 V voice   : voice_set_parameters: exit with code(-2)
09-07 15:29:40.703   283   283 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-07 15:29:40.703   283   283 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-07 15:29:40.703   283   283 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-07 15:29:40.703   283   283 V audio_hw_primary: adev_set_parameters: exit
09-07 15:29:40.703  3212  7766 D BluetoothSocket: bindListen(): myUserId = 0
09-07 15:29:40.703  3212  7766 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 15:29:40.713  3212  7740 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-07 15:29:40.713  3212  7766 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
09-07 15:29:40.713  3212  7766 D BluetoothSocket: bindListen(), new LocalSocket 
09-07 15:29:40.713  3212  7766 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-07 15:29:40.713  3212  7766 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@17c0b3f5
09-07 15:29:40.713  3212  7766 D BluetoothSocket: channel: 5
,09-07 15:29:40.713  1175  1718 D BluetoothTile:  handleUpdatestate:false name:null
,09-07 15:29:40.803  4781  4781 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 15:29:40.803  1017  1136 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings,
,09-07 15:29:40.803  1017  1136 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:40.803  1017  1136 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
09-07 15:29:40.803  1017  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 15:29:40.803  1017  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-07 15:29:40.813  1679  1679 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 15:29:40.823  4781  4781 D DockEventReceiver: finishStartingService: stopping service
,09-07 15:29:40.823   329   329 I ServiceManager: Waiting for service AtCmdFwd...,
,09-07 15:29:40.823  4781  4781 D BluetoothNotiBroadcastReceiver: onReceive
,09-07 15:29:40.833  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-07 15:29:40.833  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-07 15:29:40.843  3212  3212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26244bf3
,09-07 15:29:40.843  3212  3212 D BtConfig.SecureMode: isSecureModeOn:false
09-07 15:29:40.843  1017  3796 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 15:29:40.843  1017  3796 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
09-07 15:29:40.853  1017  3796 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:40.853  1017  3796 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:40.853  1017  3796 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 15:29:40.853  1017  1136 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast,
09-07 15:29:40.853  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:40.853  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-07 15:29:40.853  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:40.853  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:40.873  7769  7769 E Zygote  : MountEmulatedStorage(),
09-07 15:29:40.873  1017  1136 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7769 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,09-07 15:29:40.873  7769  7769 E Zygote  : v2
,09-07 15:29:40.873  7769  7769 I libpersona: KNOX_SDCARD checking this for 10105
09-07 15:29:40.873  7769  7769 I libpersona: KNOX_SDCARD not a persona
09-07 15:29:40.873  7769  7769 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 15:29:40.883  7769  7769 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 15:29:40.883  7769  7769 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-07 15:29:40.883  1017  1546 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-07 15:29:40.893  3212  7779 D BluetoothSocket: bindListen(): myUserId = 0
,09-07 15:29:40.893  3212  7779 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 15:29:40.893  3212  7779 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
09-07 15:29:40.893  3212  7779 D BluetoothSocket: bindListen(), new LocalSocket 
09-07 15:29:40.893  3212  7779 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-07 15:29:40.893  3212  7779 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1359a71
,09-07 15:29:40.893  3212  7779 D BluetoothSocket: channel: 12
,09-07 15:29:40.903  3212  7779 I BtOppRfcommListener: Accept thread started.
,09-07 15:29:40.913  7769  7769 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 15:29:40.913  7769  7769 D ActivityThread: Added TimaKeyStore provider
,09-07 15:29:41.063   257   533 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-07 15:29:41.063   257   533 W Vold    : Returning OperationFailed - no handler for errno 0
,09-07 15:29:41.063  7769  7790 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-07 15:29:41.063   257   533 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-07 15:29:41.063   257   533 W Vold    : Returning OperationFailed - no handler for errno 0
,09-07 15:29:41.063  7769  7790 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-07 15:29:41.233  7769  7769 D StrictMode: StrictMode policy violation; ~duration=153 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at java.io.File.exists(File.java:363)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 15:29:41.233  7769  7769 D StrictMode: StrictMode policy violation; ~duration=152 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 15:29:41.233  7769  7769 D StrictMode: StrictMode policy violation; ~duration=151 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 15:29:41.233  7769  7769 D StrictMode: StrictMode policy violation; ~duration=149 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.q.k.a(PG:2107)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.q.e.b(PG:170)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 15:29:41.233  7769  7769 D StrictMode: StrictMode policy violation; ~duration=146 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.q.k.c(PG:18147)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.q.k.d(PG:583)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.q.e.b(PG:170)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 15:29:41.233  7769  7769 D StrictMode: StrictMode policy violation; ~duration=122 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at java.io.File.exists(File.java:363)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 15:29:41.233  1017  1503 I ActivityManager: Killing 7394:com.sec.pcw.device/1000 (adj 15): empty #21
09-07 15:29:41.233  7769  7769 D StrictMode: StrictMode policy violation; ~duration=121 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at java.io.File.exists(File.java:363)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 15:29:41.233  7769  7769 D StrictMode: StrictMode policy violation; ~duration=120 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at java.io.File.lastModified(File.java:571)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 15:29:41.233  7769  7769 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-07 15:29:41.303  7769  7800 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-07 15:29:41.323  1017  1136 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-07 15:29:41.323  1017  1136 W ActivityManager: userId = 0, bbcId = -10000
,09-07 15:29:41.323  1017  1136 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 15:29:41.323  1017  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-07 15:29:41.833   329   329 I ServiceManager: Waiting for service AtCmdFwd...
,09-07 15:29:41.843   288   288 E SMD     : DCD OFF
,09-07 15:29:42.833   329   329 I ServiceManager: Waiting for service AtCmdFwd...
,09-07 15:29:43.003  1017  3786 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-07 15:29:43.003  1017  3786 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4293, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-07 15:29:43.003  1017  3786 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,09-07 15:29:43.003  1017  3786 D BatteryService: stay LED for charging
,09-07 15:29:43.003  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-07 15:29:43.003  1017  1017 I MotionRecognitionService: Plugged
,09-07 15:29:43.003  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,09-07 15:29:43.013  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-07 15:29:43.013  1175  1175 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-07 15:29:43.013  1432  1432 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-07 15:29:43.013  1432  1432 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-07 15:29:43.023  3212  3212 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
09-07 15:29:43.023  3212  7740 D HeadsetStateMachine: Disconnected process message: 10
,09-07 15:29:43.033  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-07 15:29:43.033  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
09-07 15:29:43.043  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-07 15:29:43.043  1175  1175 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,09-07 15:29:43.043  1175  1175 D SViewCoverView: level :100 plugged : 2
,09-07 15:29:43.353  6970  7226 D BluetoothAdapter: disable(),
,09-07 15:29:43.363  1017  1544 D SettingsProvider: name = bluetooth_on,
,09-07 15:29:43.373  3212  3291 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,09-07 15:29:43.373  3212  3291 D BluetoothAdapterProperties: Setting state to 13
09-07 15:29:43.373  3212  3291 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-07 15:29:43.373  3212  3291 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-07 15:29:43.373  3212  3291 D BluetoothAdapterService: updateAdapterState state is 13
,09-07 15:29:43.373  1017  1477 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
09-07 15:29:43.373  1017  1477 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-07 15:29:43.373  1017  1477 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:43.373  1017  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:43.373  1017  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
,09-07 15:29:43.373  3212  3291 D BluetoothAdapterService: Autoconnection is available 
09-07 15:29:43.373  3212  3291 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-07 15:29:43.373  1017  3795 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0,
,09-07 15:29:43.373  3212  3291 D BluetoothAdapterService: terminating service from this receiver
09-07 15:29:43.383  3212  3212 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
09-07 15:29:43.383  3212  3212 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3d476056, channel: 19, state: LISTENING
,09-07 15:29:43.383  3212  3212 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3d476056, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@ea3bcdf, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2f4268d7mSocket: android.net.LocalSocket@88255c4 impl:android.net.LocalSocketImpl@2f386cad fd:FileDescriptor[74]
09-07 15:29:43.383  3212  3212 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@88255c4 impl:android.net.LocalSocketImpl@2f386cad fd:FileDescriptor[74]
09-07 15:29:43.383  1017  3795 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:43.383  1017  3795 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:43.383  1017  3795 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 15:29:43.383  4781  4781 D BluetoothPbap: Proxy object disconnected
09-07 15:29:43.383  4781  4781 D PbapServerProfile: Bluetooth service disconnected
09-07 15:29:43.383  3212  3291 D BluetoothAdapterProperties: onBluetoothDisable()
09-07 15:29:43.383  3212  3291 D BluetoothAdapterProperties: mDiscovering is false
,09-07 15:29:43.383  1017  1136 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-07 15:29:43.383  3212  3291 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-07 15:29:43.393  3212  3294 D BluetoothUtils: getBtEnabledContainers(): btContainers = [],
09-07 15:29:43.393  3212  3294 D BluetoothAdapterProperties: Scan Mode:20
,09-07 15:29:43.393  3212  3291 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,09-07 15:29:43.393  3212  3291 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,09-07 15:29:43.393  3212  3291 E bt-btif : cmd socket is not created
09-07 15:29:43.393  3212  7779 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-07 15:29:43.403  3212  3291 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-07 15:29:43.403  3212  3295 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,09-07 15:29:43.403  6970  6970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 15:29:43.403  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:29:43.403  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:43.403  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:43.403  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 15:29:43.403  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 15:29:43.403  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:29:43.403  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:29:43.403  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 15:29:43.403  6970  6970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 15:29:43.403  6970  6970 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 15:29:43.403  6970  6970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 15:29:43.403  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:29:43.403  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:43.403  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:43.403  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 15:29:43.403  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 15:29:43.403  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:29:43.403  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:29:43.403  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 15:29:43.403  6970  6970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 15:29:43.403  6970  6970 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 15:29:43.413  3212  3295 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 15:29:43.413  3212  3295 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 15:29:43.413  3212  3295 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-07 15:29:43.413  3212  3295 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 15:29:43.413  3212  3295 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 15:29:43.413  3212  3295 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-07 15:29:43.423  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-07 15:29:43.423  1017  1017 I InputMethodManagerService: [BT Setting State] State =13
,09-07 15:29:43.433  1175  1175 D BluetoothTile:  onBluetoothStateChange:
,09-07 15:29:43.433  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-07 15:29:43.433  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-07 15:29:43.433  1175  1175 D BluetoothTile:  getBluetoothState : 13
,09-07 15:29:43.433  1017  1030 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-07 15:29:43.443  1882  1882 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
09-07 15:29:43.443  1175  1718 D BluetoothTile:  handleUpdatestate:false name:null
,09-07 15:29:43.443  1017  1501 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-07 15:29:43.443  1175  1718 D BluetoothTile:  handleUpdatestate:false name:null
,09-07 15:29:43.443  1175  1718 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-07 15:29:43.443  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-07 15:29:43.443  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:29:43.443  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:29:43.453  3212  3212 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2dabb73, channel: 5, state: LISTENING
09-07 15:29:43.453  3212  3212 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2dabb73, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@17c0b3f5, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@a310a30mSocket: android.net.LocalSocket@191c26a9 impl:android.net.LocalSocketImpl@147a242e fd:FileDescriptor[76]
09-07 15:29:43.453  3212  3212 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@191c26a9 impl:android.net.LocalSocketImpl@147a242e fd:FileDescriptor[76]
09-07 15:29:43.453  4781  4781 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-07 15:29:43.453  3212  3212 I BtOppRfcommListener: stopping Accept Thread
09-07 15:29:43.453  3212  3212 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@189b9bcf, channel: 12, state: LISTENING,
09-07 15:29:43.453  3212  3212 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@189b9bcf, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1359a71, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@34d4995cmSocket: android.net.LocalSocket@3e678465 impl:android.net.LocalSocketImpl@2788553a fd:FileDescriptor[80]
09-07 15:29:43.453  3212  3212 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3e678465 impl:android.net.LocalSocketImpl@2788553a fd:FileDescriptor[80]
,09-07 15:29:43.453  3212  7779 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-07 15:29:43.453  3212  3212 V BluetoothOppManager: cleanUp...
,09-07 15:29:43.453  4781  4781 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 15:29:43.463  1017  1544 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-07 15:29:43.463  1017  1544 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-07 15:29:43.463  1017  1544 W ActivityManager: userId = 0, bbcId = -10000
,09-07 15:29:43.463  1017  1544 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:43.463  1017  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-07 15:29:43.473  1679  1679 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 15:29:43.473  4781  4781 D DockEventReceiver: finishStartingService: stopping service
,09-07 15:29:43.473  4781  4781 D BluetoothNotiBroadcastReceiver: onReceive
,09-07 15:29:43.483  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-07 15:29:43.483  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-07 15:29:43.603  3212  3291 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,09-07 15:29:43.603  3212  3291 D BtConfig.SecureMode: isSecureModeOn:false
09-07 15:29:43.603  3212  3291 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-07 15:29:43.603  3212  3291 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
09-07 15:29:43.603  3212  3291 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
09-07 15:29:43.603  3212  3291 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
09-07 15:29:43.603  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-07 15:29:43.603  1017  3795 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 15:29:43.603  3212  3291 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
09-07 15:29:43.603  1017  3795 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-07 15:29:43.603  1017  3795 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:43.603  1017  3795 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:43.603  1017  3795 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 15:29:43.603  3212  3291 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
09-07 15:29:43.603  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-07 15:29:43.603  3212  3291 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-07 15:29:43.603  1017  1503 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 15:29:43.603  1017  1503 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-07 15:29:43.603  3212  3212 D HeadsetService: Received stop request...Stopping profile...
,09-07 15:29:43.603  1017  1503 W ActivityManager: userId = 0, bbcId = -10000,
09-07 15:29:43.603  1017  1503 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:43.603  1017  1504 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 15:29:43.603  1017  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-07 15:29:43.603  1017  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
09-07 15:29:43.603  3212  3291 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
09-07 15:29:43.603  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-07 15:29:43.603  3212  3291 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
09-07 15:29:43.603  3212  3212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26244bf3
,09-07 15:29:43.613  1017  1504 W ActivityManager: userId = 0, bbcId = -10000,
,09-07 15:29:43.613  1017  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:43.613  1017  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
09-07 15:29:43.613  3212  3291 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,09-07 15:29:43.613  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-07 15:29:43.613  3212  3291 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-07 15:29:43.613  1017  1544 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 15:29:43.613  1017  1544 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-07 15:29:43.623  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,09-07 15:29:43.623  4781  4781 D HeadsetProfile: Bluetooth service disconnected
,09-07 15:29:43.623  1017  1544 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:43.623  1017  1544 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:43.623  1017  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-07 15:29:43.623  3212  3291 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,09-07 15:29:43.623  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-07 15:29:43.623  3212  3291 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-07 15:29:43.623  1017  1546 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 15:29:43.623  1017  1546 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-07 15:29:43.623  3212  3212 D A2dpService: Received stop request...Stopping profile...
,09-07 15:29:43.623  3212  7750 D A2dpStateMachine: Exit Disconnected: -1
09-07 15:29:43.623  1017  1546 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:43.623  1017  1546 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:43.623  1017  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 15:29:43.623  3212  3291 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
09-07 15:29:43.623  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-07 15:29:43.623  3212  3291 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-07 15:29:43.623  1017  1503 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 15:29:43.623  1017  1503 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-07 15:29:43.633  3212  3212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26244bf3
,09-07 15:29:43.633  1017  1503 W ActivityManager: userId = 0, bbcId = -10000
,09-07 15:29:43.633  1017  1503 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:43.633  1017  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 15:29:43.633  1017  1017 D BluetoothA2dp: Proxy object disconnected
,09-07 15:29:43.633  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-07 15:29:43.633  3212  3291 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
,09-07 15:29:43.633  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-07 15:29:43.633  3212  3291 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-07 15:29:43.633  4781  4781 D BluetoothA2dp: Proxy object disconnected
09-07 15:29:43.633  1017  1504 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 15:29:43.633  4781  4781 D A2dpProfile: Bluetooth service disconnected
09-07 15:29:43.633  1017  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-07 15:29:43.633  1017  1504 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:43.633  1017  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:43.633  1017  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 15:29:43.633  3212  3291 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,09-07 15:29:43.633  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-07 15:29:43.633  3212  3291 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-07 15:29:43.643  3212  3291 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
,09-07 15:29:43.643  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-07 15:29:43.643  3212  3291 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-07 15:29:43.643  3212  3291 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
,09-07 15:29:43.643  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-07 15:29:43.643  3212  3291 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,09-07 15:29:43.643  3212  3291 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
09-07 15:29:43.643  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-07 15:29:43.643  3212  3291 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-07 15:29:43.643  3212  3291 D BluetoothAdapterState: Stopping profile services that were post enabled
,09-07 15:29:43.643  3212  3212 E BluetoothAdapterService(639912947): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-07 15:29:43.643  3212  3212 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-07 15:29:43.643  3212  3212 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-07 15:29:43.643  3212  3212 D HidService: Received stop request...Stopping profile...
,09-07 15:29:43.643  3212  3212 D HidService: Stopping Bluetooth HidService
,09-07 15:29:43.643  3212  3212 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-07 15:29:43.643  3212  3212 W bt-btif : cleanup: HH disabling or disabled already, status = 0
,09-07 15:29:43.643  3212  3212 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-07 15:29:43.643  3212  3212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26244bf3
,09-07 15:29:43.653  3212  3212 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-07 15:29:43.653  3212  3212 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-07 15:29:43.653  3212  3212 D HealthService: Received stop request...Stopping profile...
,09-07 15:29:43.653  3212  3212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26244bf3
,09-07 15:29:43.653  3212  3212 D PanService: Received stop request...Stopping profile...
,09-07 15:29:43.653  3212  3212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26244bf3
09-07 15:29:43.653  4781  4781 D BluetoothInputDevice: Proxy object disconnected
09-07 15:29:43.653  4781  4781 D HidProfile: Bluetooth service disconnected
,09-07 15:29:43.653  3212  3212 E BluetoothAdapterService(639912947): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,09-07 15:29:43.653  3212  3212 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-07 15:29:43.653  1017  1017 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-07 15:29:43.663  3212  3212 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-07 15:29:43.663  4781  4781 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-07 15:29:43.663  4781  4781 D PanProfile: Bluetooth service disconnected
09-07 15:29:43.663  3212  3212 D BluetoothMapService: Received stop request...Stopping profile...
,09-07 15:29:43.663  3212  3212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26244bf3
,09-07 15:29:43.663  3212  3212 D BluetoothA2dp: Proxy object disconnected
,09-07 15:29:43.663  3212  3212 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,09-07 15:29:43.663  3212  7751 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,09-07 15:29:43.663  3212  3212 I GKI_LINUX: GKI_exit_task 2 done
,09-07 15:29:43.663  3212  3212 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-07 15:29:43.663  3212  3212 D SapService: Received stop request...Stopping profile...
,09-07 15:29:43.673  4781  4781 D BluetoothMap: Proxy object disconnected
09-07 15:29:43.673  3212  3212 D SapService: Stopping Bluetooth SapService
09-07 15:29:43.673  4781  4781 D MapProfile: Bluetooth service disconnected
09-07 15:29:43.673  3212  3212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26244bf3
,09-07 15:29:43.673  3212  3212 E BluetoothAdapterService(639912947): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
,09-07 15:29:43.673  3212  3212 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,09-07 15:29:43.673  3212  3212 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-07 15:29:43.673  3212  3212 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-07 15:29:43.673  4781  4781 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-07 15:29:43.673  4781  4781 D SapProfile: Bluetooth service disconnected
,09-07 15:29:43.673  3212  3212 E BluetoothAdapterService(639912947): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-07 15:29:43.673  3212  3212 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-07 15:29:43.673  3212  3212 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-07 15:29:43.673  3212  3212 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-07 15:29:43.673  3212  3212 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-07 15:29:43.673  3212  3212 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-07 15:29:43.673  3212  3212 E BluetoothAdapterService(639912947): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-07 15:29:43.673  3212  3212 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-07 15:29:43.673  3212  3212 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-07 15:29:43.673  3212  3212 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-07 15:29:43.673  3212  3212 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-07 15:29:43.673  3212  3212 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-07 15:29:43.673  3212  3212 E BluetoothAdapterService(639912947): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,09-07 15:29:43.673  3212  3212 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,09-07 15:29:43.673  3212  3212 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-07 15:29:43.673  3212  3212 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,09-07 15:29:43.673  3212  3212 E BluetoothAdapterService(639912947): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-07 15:29:43.673  3212  3212 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-07 15:29:43.673  3212  3212 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-07 15:29:43.673  3212  3212 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,09-07 15:29:43.683  3212  3291 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
09-07 15:29:43.683  3212  3291 D BluetoothAdapterProperties: Setting state to 10
09-07 15:29:43.683  3212  3291 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-07 15:29:43.683  3212  3291 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-07 15:29:43.683  3212  3291 D BluetoothAdapterService: updateAdapterState state is 10
,09-07 15:29:43.683  3212  3291 D BluetoothAdapterService: Autoconnection is available 
09-07 15:29:43.683  3212  3291 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-07 15:29:43.683  3212  3291 I BluetoothAdapterState: Entering OffState
,09-07 15:29:43.683  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-07 15:29:43.683  4781  4791 D BluetoothA2dp: onBluetoothStateChange: up=false,
,09-07 15:29:43.683  6970  6981 D BluetoothAdapter: onBluetoothStateChange: up=false
09-07 15:29:43.683  6970  6981 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 15:29:43.683  6970  6981 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-07 15:29:43.683  6970  6981 D BluetoothLeAdvertiser: Exit stop advertising
,09-07 15:29:43.683  6970  6981 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-07 15:29:43.683  6970  6981 D BluetoothLeScanner: Exiting stopAllScan
,09-07 15:29:43.683  3212  3349 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-07 15:29:43.683  3212  3349 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 15:29:43.683  1175  2927 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-07 15:29:43.683  1175  2927 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 15:29:43.693  1755  2514 D BluetoothAdapter: onBluetoothStateChange: up=false
09-07 15:29:43.693  1755  2514 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 15:29:43.693  7769  7780 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-07 15:29:43.693  7769  7780 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 15:29:43.693  3212  3350 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-07 15:29:43.693  4781  7278 D BluetoothPbap: onBluetoothStateChange: up=false
,09-07 15:29:43.693  4781  4789 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-07 15:29:43.693  1453  1474 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-07 15:29:43.693  1453  1474 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 15:29:43.693  4781  4791 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-07 15:29:43.693  4781  4791 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 15:29:43.693  1480  1496 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-07 15:29:43.693  1480  1496 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 15:29:43.693  4781  7278 D BluetoothMap: onBluetoothStateChange: up=false
,09-07 15:29:43.703  1463  1746 D BluetoothAdapter: onBluetoothStateChange: up=false
09-07 15:29:43.703  1463  1746 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 15:29:43.703  1679  4223 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-07 15:29:43.703  1679  4223 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 15:29:43.703  4781  4791 D Bluetoothsap: onBluetoothStateChange: up=false
,09-07 15:29:43.703  4781  4791 D Bluetoothsap: Unbinding service...
,09-07 15:29:43.703  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-07 15:29:43.703  1017  1046 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 15:29:43.713  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-07 15:29:43.713  1017  1017 I InputMethodManagerService: [BT Setting State] State =10
,09-07 15:29:43.713  1017  1017 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-07 15:29:43.713  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-07 15:29:43.713  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-07 15:29:43.713  1175  1175 D BluetoothTile:  getBluetoothState : 10
,09-07 15:29:43.723  1017  1030 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-07 15:29:43.723  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ),
09-07 15:29:43.723  1017  1504 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-07 15:29:43.723  1882  1882 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-07 15:29:43.723  4781  4781 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-07 15:29:43.733  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:29:43.733  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:29:43.733  4781  4781 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 15:29:43.733  1017  1504 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-07 15:29:43.733  1017  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-07 15:29:43.733  1017  1504 W ActivityManager: userId = 0, bbcId = -10000
,09-07 15:29:43.733  1017  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:43.733  1017  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-07 15:29:43.743  1679  1679 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 15:29:43.753  4781  4781 D DockEventReceiver: finishStartingService: stopping service
,09-07 15:29:43.753  4781  4781 D BluetoothNotiBroadcastReceiver: onReceive
,09-07 15:29:43.753  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-07 15:29:43.753  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-07 15:29:43.823   329   329 I ServiceManager: Waiting for service AtCmdFwd...
,09-07 15:29:44.823   329   329 I ServiceManager: Waiting for service AtCmdFwd...
,09-07 15:29:44.843   288   288 E SMD     : DCD OFF
,09-07 15:29:45.013  1017  1095 V AlarmManager: waitForAlarm result :4
,09-07 15:29:45.023   278   986 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-07 15:29:45.023   278   986 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,09-07 15:29:45.033  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:45.033  1017  1042 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 15:29:45.033  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,09-07 15:29:45.833   329   329 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,09-07 15:29:46.373  6970  7226 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 15:29:46.373  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 15:29:47.843   288   288 E SMD     : DCD OFF
,09-07 15:29:49.373  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 15:29:49.373  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@17fea7c3 added. We now have 6 listener(s)
,09-07 15:29:49.373  6970  7226 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 15:29:49.373  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 15:29:49.373  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@125d0840 added. We now have 7 listener(s)
,09-07 15:29:49.383  6970  7226 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 15:29:49.383  6970  7226 I System.out: IsBluetoothEnabled
,09-07 15:29:49.383  6970  7226 D BluetoothAdapter: disable()
,09-07 15:29:49.383  1017  1503 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,09-07 15:29:49.393  6970  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:29:49.393  6970  7226 D BluetoothAdapter: enable()
,09-07 15:29:49.393  1017  1255 W ActivityManager: Permission Denial: getCurrentUser() from pid=6970, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-07 15:29:49.393  1017  1255 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-07 15:29:49.393  1017  1255 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6970, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-07 15:29:49.393  1017  1255 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-07 15:29:49.393  1017  1255 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
09-07 15:29:49.393  1017  1255 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
09-07 15:29:49.393  1017  1255 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
09-07 15:29:49.393  1017  1255 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-07 15:29:49.393  1017  1255 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-07 15:29:49.393  1017  1255 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-07 15:29:49.403  1017  1255 D SettingsProvider: name = bluetooth_on,
,09-07 15:29:49.403  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-07 15:29:49.403  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-07 15:29:49.413  1017  1046 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-07 15:29:49.413  3212  3291 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,09-07 15:29:49.413  3212  3291 D BluetoothAdapterProperties: Setting state to 11
09-07 15:29:49.413  3212  3291 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,09-07 15:29:49.423  3212  3291 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-07 15:29:49.423  3212  3291 D BluetoothAdapterService: updateAdapterState state is 11
,09-07 15:29:49.423  3212  3291 D BluetoothAdapterService: Autoconnection is available 
09-07 15:29:49.423  3212  3291 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
09-07 15:29:49.423  3212  3291 D BtConfig.SecureMode: isSecureModeOn:false
09-07 15:29:49.423  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-07 15:29:49.423  3212  3291 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
09-07 15:29:49.423  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-07 15:29:49.423  3212  3291 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
09-07 15:29:49.423  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-07 15:29:49.423  3212  3291 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
09-07 15:29:49.423  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-07 15:29:49.423  3212  3291 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
09-07 15:29:49.423  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-07 15:29:49.423  3212  3291 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
09-07 15:29:49.423  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-07 15:29:49.423  3212  3291 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
09-07 15:29:49.423  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-07 15:29:49.423  3212  3291 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
09-07 15:29:49.423  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-07 15:29:49.423  3212  3291 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
09-07 15:29:49.423  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-07 15:29:49.423  3212  3291 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-07 15:29:49.423  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-07 15:29:49.423  3212  3291 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-07 15:29:49.423  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-07 15:29:49.423  3212  3291 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-07 15:29:49.423  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-07 15:29:49.423  3212  3291 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
09-07 15:29:49.423  3212  3291 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
09-07 15:29:49.423  3212  3291 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
09-07 15:29:49.423  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-07 15:29:49.423  3212  3291 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-07 15:29:49.423  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-07 15:29:49.423  1017  1017 I InputMethodManagerService: [BT Setting State] State =11
,09-07 15:29:49.423  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-07 15:29:49.433  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-07 15:29:49.433  1175  1175 D BluetoothTile:  getBluetoothState : 11
,09-07 15:29:49.433  1882  1882 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-07 15:29:49.433  4781  4781 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-07 15:29:49.433  1017  1255 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-07 15:29:49.433  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:29:49.433  1017  3796 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-07 15:29:49.433  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-07 15:29:49.443  1175  1718 D BluetoothTile:  handleUpdatestate:false name:null
,09-07 15:29:49.443  1175  1718 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-07 15:29:49.443  1017  3785 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 15:29:49.443  1017  3785 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-07 15:29:49.443  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-07 15:29:49.443  1017  3785 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:49.443  1017  3785 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:49.443  1017  3785 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 15:29:49.443  3212  3291 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,09-07 15:29:49.443  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-07 15:29:49.443  3212  3291 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
09-07 15:29:49.443  1017  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-07 15:29:49.443  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0,
09-07 15:29:49.443  3212  3212 D HeadsetService: Received start request. Starting profile...
09-07 15:29:49.443  3212  3212 D HeadsetService: start()
09-07 15:29:49.443  3212  3212 D HeadsetStateMachine: make
09-07 15:29:49.443  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:49.443  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:49.443  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-07 15:29:49.453  3212  3212 E HeadsetStateMachine: # of Max HF connection is 2
,09-07 15:29:49.453  3212  3291 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,09-07 15:29:49.453  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-07 15:29:49.453  3212  3291 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
09-07 15:29:49.453  1017  1255 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-07 15:29:49.453  1017  1255 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-07 15:29:49.453  1017  1255 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:49.453  1017  1255 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:49.453  1017  1255 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-07 15:29:49.453  1017  3796 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
09-07 15:29:49.453  1017  3796 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-07 15:29:49.453  3212  3291 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
09-07 15:29:49.463  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-07 15:29:49.463  3212  3291 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
09-07 15:29:49.463  1017  3796 W ActivityManager: userId = 0, bbcId = -10000
,09-07 15:29:49.463  1017  3796 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:49.463  1017  3796 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-07 15:29:49.463  1017  1503 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,09-07 15:29:49.463  1017  1503 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-07 15:29:49.463  1017  1503 W ActivityManager: userId = 0, bbcId = -10000
,09-07 15:29:49.463  1017  1503 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:49.463  1017  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-07 15:29:49.463  1017  1546 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-07 15:29:49.463  1017  1546 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-07 15:29:49.463  1017  1546 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:49.473  3212  3212 I bluedroid: get_profile_interface handsfree
,09-07 15:29:49.473  1017  1546 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:49.473  1017  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 15:29:49.473  3212  3291 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
09-07 15:29:49.473  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-07 15:29:49.473  3212  3291 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-07 15:29:49.473  1679  1679 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 15:29:49.473  1017  3785 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 15:29:49.473  1017  3785 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-07 15:29:49.483  1017  3785 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:49.483  1017  3785 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:49.483  1017  3785 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 15:29:49.483  3212  3291 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
09-07 15:29:49.483  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-07 15:29:49.483  3212  3291 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-07 15:29:49.483  3212  3212 E DualScoManager: Dual Sco Manager already instantiated
09-07 15:29:49.483  1017  1545 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 15:29:49.483  3212  3212 I DualScoManager: Set HeadsetServiceHelper
09-07 15:29:49.483  1017  1545 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
09-07 15:29:49.483  3212  3212 D BluetoothAtMessage: createCMTIContentObservers
09-07 15:29:49.483  1017  1545 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:49.483  1017  1545 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:49.483  1017  1545 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-07 15:29:49.483  4781  4781 D BluetoothNotiBroadcastReceiver: onReceive
09-07 15:29:49.483  1017  1504 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
09-07 15:29:49.483  1017  1504 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 15:29:49.483  1017  1504 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 15:29:49.483  1017  1504 D SettingsProvider: selectionArgs: false
09-07 15:29:49.483  1017  1504 D SettingsProvider: selectionArgs: 1002
09-07 15:29:49.483  1017  1504 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 15:29:49.483  1017  1504 D SettingsProvider: ret = -1
,09-07 15:29:49.493  3212  7818 D HeadsetStateMachine: Enter Disconnected: -2,
09-07 15:29:49.493  3212  3291 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
09-07 15:29:49.493  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-07 15:29:49.493  3212  3291 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-07 15:29:49.493  3212  3212 D HeadsetService: mStartError = false
09-07 15:29:49.493  3212  3212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26244bf3,
09-07 15:29:49.493  3212  3212 D A2dpService: Received start request. Starting profile...
09-07 15:29:49.493  3212  3212 D A2dpService: start()
09-07 15:29:49.493  3212  3212 I bluedroid: get_profile_interface avrcp
,09-07 15:29:49.493  1017  3796 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 15:29:49.493  1017  3796 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-07 15:29:49.493  1017  3796 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:49.493  1017  3796 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:49.493  1017  3796 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 15:29:49.493  3212  3212 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-07 15:29:49.493  3212  3212 D Avrcp   : Initialize Media Controller
09-07 15:29:49.493  3212  3212 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,09-07 15:29:49.493  3212  3291 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-07 15:29:49.493  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-07 15:29:49.493  3212  3291 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-07 15:29:49.493  3212  3291 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-07 15:29:49.493  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-07 15:29:49.493  3212  3291 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-07 15:29:49.493  3212  3291 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
09-07 15:29:49.493  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-07 15:29:49.493  3212  3291 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-07 15:29:49.493  3212  3291 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
09-07 15:29:49.493  3212  3291 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-07 15:29:49.493  3212  3291 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-07 15:29:49.493  3212  3291 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-07 15:29:49.503  3212  3212 E Avrcp   : getActiveSessions
09-07 15:29:49.503  3212  3212 D Avrcp   : pick active media Controller
09-07 15:29:49.503  3212  3212 D Avrcp   : Get the active Media Controller 
,09-07 15:29:49.503  3212  7818 D HeadsetStateMachine: Clear mHeadsetBrsf
09-07 15:29:49.503  3212  7818 D HeadsetStateMachine: map size, before remove : 0
09-07 15:29:49.503  3212  7818 D HeadsetStateMachine: map size, after remove: 0
,09-07 15:29:49.503  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-07 15:29:49.503  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-07 15:29:49.503  3212  3212 I Avrcp   :  Updating now playing list upon AVRCP Start
09-07 15:29:49.503  3212  7819 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-07 15:29:49.513  3212  3212 D A2dpStateMachine: make
09-07 15:29:49.513  3212  3212 I bluedroid: get_profile_interface a2dp
09-07 15:29:49.513  3212  7821 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-07 15:29:49.513  3212  3212 E bt-btif : warning : media task started media_task_refcnt 1 
09-07 15:29:49.513  3212  3212 D A2dpService: mStartError = false
09-07 15:29:49.513  3212  3212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26244bf3
,09-07 15:29:49.513  3212  3212 D HidService: Received start request. Starting profile...
09-07 15:29:49.513  3212  3212 D HidService: start()
09-07 15:29:49.513  3212  3212 I bluedroid: get_profile_interface hidhost
09-07 15:29:49.513  1453  1465 I Telecom : BluetoothPhoneService: queryPhoneState
09-07 15:29:49.513  3212  3212 D HidService: setHidService(): set to: null
09-07 15:29:49.513  3212  3212 D HidService: mStartError = false
09-07 15:29:49.513  3212  3212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26244bf3
09-07 15:29:49.513  3212  3212 D HeadsetStateMachine: Try to query the phonestate on bind
,09-07 15:29:49.513  3212  7820 D A2dpStateMachine: Enter Disconnected: -2
,09-07 15:29:49.513  1453  1453 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
09-07 15:29:49.513  1453  1453 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
09-07 15:29:49.513  1453  1465 I Telecom : BluetoothPhoneService: Result of Message : true
,09-07 15:29:49.523  3212  3212 D HeadsetStateMachine: Proxy object connected
09-07 15:29:49.523  3212  3212 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,09-07 15:29:49.523  3212  7818 D HeadsetStateMachine: Disconnected process message: 11
09-07 15:29:49.523  3212  3212 D HealthService: Received start request. Starting profile...,
09-07 15:29:49.523  3212  3212 D HealthService: start()
09-07 15:29:49.523  3212  3212 I bluedroid: get_profile_interface health
09-07 15:29:49.523  3212  3212 D HealthService: mStartError = false
09-07 15:29:49.523  3212  3212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26244bf3
09-07 15:29:49.523  3212  3212 D HeadsetPhoneState: sendDeviceDataStateChanged
09-07 15:29:49.523  3212  3212 D HeadsetPhoneState: Signal level : previous=0 curr=4
,09-07 15:29:49.523  3212  7818 D HeadsetStateMachine: Disconnected process message: 18
,09-07 15:29:49.523  3212  3212 D PanService: Received start request. Starting profile...,
09-07 15:29:49.523  3212  3212 D PanService: start()
09-07 15:29:49.523  3212  3212 D BluetoothPanServiceJni: initializeNative(L110): pan
09-07 15:29:49.523  3212  3212 I bluedroid: get_profile_interface pan
,09-07 15:29:49.523  3212  3212 D PanService: mStartError = false
09-07 15:29:49.523  3212  3212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26244bf3
,09-07 15:29:49.523  3212  3212 D BluetoothMapService: Received start request. Starting profile...
09-07 15:29:49.523  3212  3212 D BluetoothMapService: start()
,09-07 15:29:49.523  3212  7819 D BluetoothMediaBrowser: no now playing list
,09-07 15:29:49.533  3212  7819 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
09-07 15:29:49.533  3212  3212 D BluetoothMapService: mStartError = false
,09-07 15:29:49.533  3212  3212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26244bf3
,09-07 15:29:49.533  3212  3212 E BluetoothAdapterService(639912947): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-07 15:29:49.533  3212  3212 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-07 15:29:49.533  3212  7818 D HeadsetStateMachine: Disconnected process message: 10
09-07 15:29:49.533  3212  7818 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-07 15:29:49.533  3212  7818 D HeadsetStateMachine: Disconnected process message: 11
,09-07 15:29:49.533  3212  3212 D SapService: Received start request. Starting profile...
09-07 15:29:49.533  3212  3212 D SapService: start()
09-07 15:29:49.533  3212  3212 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-07 15:29:49.533  3212  3212 I bluedroid: get_profile_interface sap
09-07 15:29:49.533  3212  3212 D SapService: mStartError = false
09-07 15:29:49.533  3212  3212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26244bf3
09-07 15:29:49.533  3212  3212 E BluetoothAdapterService(639912947): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-07 15:29:49.533  3212  3212 E BluetoothAdapterService(639912947): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-07 15:29:49.533  3212  3212 E BluetoothAdapterService(639912947): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-07 15:29:49.533  3212  3212 E BluetoothAdapterService(639912947): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-07 15:29:49.543  3212  3212 E BluetoothAdapterService(639912947): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
09-07 15:29:49.543  3212  3212 E BluetoothAdapterService(639912947): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-07 15:29:49.553  3212  3291 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,09-07 15:29:49.553  3212  3291 I bluedroid: enable
,09-07 15:29:49.553  3212  3294 E bt-btif : Calling BTA_HhEnable
,09-07 15:29:49.553  3212  3294 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,09-07 15:29:49.553  3212  3294 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,09-07 15:29:49.553  3212  3294 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-07 15:29:49.553  3212  3294 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
09-07 15:29:49.553  3212  3294 E BluetoothServiceJni: populateRssiValuesNative
09-07 15:29:49.553  3212  3294 I bluedroid: getModelRssiValues
,09-07 15:29:49.563  3212  3294 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-07 15:29:49.563  3212  3294 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-07 15:29:49.563  3212  3294 D BluetoothAdapterProperties: Name is: Galaxy A3
,09-07 15:29:49.563  1017  1017 D SettingsProvider: name = bluetooth_name
,09-07 15:29:49.563  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:29:49.563  3212  3294 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-07 15:29:49.563  3212  3294 D BluetoothAdapterProperties: Scan Mode:20
09-07 15:29:49.563  3212  3294 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-07 15:29:49.573  3212  3294 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
,09-07 15:29:49.573  3212  3294 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
09-07 15:29:49.573  3212  3294 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,09-07 15:29:49.573  3212  3294 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,09-07 15:29:49.573  3212  3294 E bt-btif : JVenable fails
,09-07 15:29:49.573  3212  3294 D bte_conf: Device ID record 1 : primary
,09-07 15:29:49.573  3212  3294 D bte_conf:   vendorId            = 0075
09-07 15:29:49.573  3212  3294 D bte_conf:   vendorIdSource      = 0001
09-07 15:29:49.573  3212  3294 D bte_conf:   product             = 0100
,09-07 15:29:49.573  3212  3294 D bte_conf:   version             = 0200
,09-07 15:29:49.573  3212  3294 D bte_conf:   clientExecutableURL = 
,09-07 15:29:49.573  3212  3294 D bte_conf:   serviceDescription  = 
09-07 15:29:49.573  3212  3294 D bte_conf:   documentationURL    = 
09-07 15:29:49.573  3212  3294 D bte_conf: bte_load_did_conf no section named DID2.
09-07 15:29:49.573  3212  3294 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,09-07 15:29:49.573  3212  3294 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-07 15:29:49.573  3212  3291 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false,
09-07 15:29:49.573  3212  3291 D BluetoothAdapterProperties: ScanMode =  20
09-07 15:29:49.573  3212  3291 D BluetoothAdapterProperties: State =  11
09-07 15:29:49.573  1017  1546 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled,
09-07 15:29:49.573  3212  3291 D BluetoothAdapterProperties: Setting state to 12
,09-07 15:29:49.573  3212  3291 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-07 15:29:49.573  3212  3294 D BluetoothUtils: getBtEnabledContainers(): btContainers = [],
09-07 15:29:49.573  3212  3294 D BluetoothAdapterProperties: Scan Mode:21
09-07 15:29:49.573  3212  3294 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-07 15:29:49.583  1017  1029 D SettingsProvider: name = bluetooth_a2dp_sink_mode
09-07 15:29:49.583  1017  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 15:29:49.583  1017  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 15:29:49.583  1017  1029 D SettingsProvider: selectionArgs: false
09-07 15:29:49.583  1017  1029 D SettingsProvider: selectionArgs: 1002
09-07 15:29:49.583  1017  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 15:29:49.583  1017  1029 D SettingsProvider: ret = -1
09-07 15:29:49.583  3212  3291 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-07 15:29:49.583  3212  3291 D BluetoothAdapterService: updateAdapterState state is 12
,09-07 15:29:49.583  1017  3786 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 15:29:49.583  1017  3786 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-07 15:29:49.583  1017  3786 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:49.583  1017  3786 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:49.583  1017  3786 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 15:29:49.583  1017  1046 D BluetoothPan: Binding service...
,09-07 15:29:49.583  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-07 15:29:49.583  3212  3291 D BluetoothAdapterService: Autoconnection is available 
09-07 15:29:49.583  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-07 15:29:49.583  3212  3291 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-07 15:29:49.583  1017  1520 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 15:29:49.583  3212  3291 D BluetoothAdapterService: starting service from this receiver
09-07 15:29:49.583  1017  1520 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-07 15:29:49.583  4781  4791 D BluetoothPan: Binding service...
,09-07 15:29:49.583  1017  1520 W ActivityManager: userId = 0, bbcId = -10000
,09-07 15:29:49.593  1017  1520 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:49.593  1017  1520 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 15:29:49.593  3212  3212 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
09-07 15:29:49.593  3212  3291 I BluetoothAdapterState: Entering On State from state = 11
,09-07 15:29:49.593  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:29:49.593  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:49.593  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:49.593  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 15:29:49.593  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:29:49.593  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:29:49.593  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:29:49.593  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 15:29:49.593  6970  6970 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 15:29:49.733  1017  1046 I art     : Explicit concurrent mark sweep GC freed 53180(3MB) AllocSpace objects, 7(113KB) LOS objects, 33% free, 22MB/34MB, paused 2.410ms total 145.230ms
09-07 15:29:49.733  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-07 15:29:49.733  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-07 15:29:49.733  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:49.733  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:49.733  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-07 15:29:49.733  1017  1017 D BluetoothPan: BluetoothPAN Proxy object connected
09-07 15:29:49.733  4781  4781 D BluetoothPan: BluetoothPAN Proxy object connected
09-07 15:29:49.733  4781  4781 D PanProfile: Bluetooth service connected
,09-07 15:29:49.733  3212  3212 I BluetoothPbapService: Handler(): got msg=1
,09-07 15:29:49.743  1453  1474 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-07 15:29:49.743  1017  1136 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-07 15:29:49.743  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-07 15:29:49.743  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-07 15:29:49.743  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:49.743  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:49.743  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-07 15:29:49.743  1453  1474 E BluetoothHeadset: BluetoothHeadset service is binded
,09-07 15:29:49.743  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-07 15:29:49.743  1017  1046 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-07 15:29:49.743  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-07 15:29:49.743  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-07 15:29:49.743  4781  4791 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-07 15:29:49.743  4781  4791 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-07 15:29:49.743  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-07 15:29:49.743  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-07 15:29:49.743  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:49.743  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:49.743  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-07 15:29:49.753  3212  7826 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-07 15:29:49.753  6970  6979 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-07 15:29:49.753  6970  6979 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 15:29:49.753  4781  4781 D BluetoothA2dp: Proxy object connected
09-07 15:29:49.753  4781  4781 D A2dpProfile: Bluetooth service connected
09-07 15:29:49.753  1017  1017 D BluetoothA2dp: Proxy object connected
,09-07 15:29:49.753  3212  3226 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 15:29:49.753  3212  3226 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 15:29:49.753  1175  3972 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 15:29:49.753  1175  3972 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 15:29:49.763  1755  2514 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 15:29:49.763  1755  2514 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 15:29:49.763  1017  1046 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-07 15:29:49.763  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-07 15:29:49.763  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-07 15:29:49.763  1017  1046 E BluetoothHeadset: BluetoothHeadset service is binded
,09-07 15:29:49.763  7769  7785 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 15:29:49.763  7769  7785 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 15:29:49.763  3212  3350 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-07 15:29:49.763  3212  7826 D BluetoothSocket: bindListen(): myUserId = 0
,09-07 15:29:49.763  3212  7826 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 15:29:49.763  3212  3350 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-07 15:29:49.763  3212  7826 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
,09-07 15:29:49.763  3212  7826 D BluetoothSocket: bindListen(), new LocalSocket 
09-07 15:29:49.763  3212  7826 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,09-07 15:29:49.763  3212  7826 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@39f000f2
09-07 15:29:49.763  1017  1046 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-07 15:29:49.763  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-07 15:29:49.763  3212  7826 D BluetoothSocket: channel: 19
09-07 15:29:49.763  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,09-07 15:29:49.763  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:49.763  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-07 15:29:49.763  3212  7826 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,09-07 15:29:49.763  3212  3212 D BluetoothA2dp: Proxy object connected
09-07 15:29:49.763  3212  3212 D BluetoothAdapterService: Bluetooth A2dp source service connected
,09-07 15:29:49.763  4781  4789 D BluetoothPbap: onBluetoothStateChange: up=true
,09-07 15:29:49.773  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,09-07 15:29:49.773  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-07 15:29:49.773  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:49.773  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:49.773  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-07 15:29:49.773  4781  4791 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-07 15:29:49.773  4781  4781 D BluetoothPbap: Proxy object connected
,09-07 15:29:49.773  4781  4781 D PbapServerProfile: Bluetooth service connected
,09-07 15:29:49.773  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,09-07 15:29:49.773  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-07 15:29:49.773  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:49.773  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 15:29:49.773  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-07 15:29:49.773  4781  4781 D BluetoothInputDevice: Proxy object connected
,09-07 15:29:49.783  4781  4781 D HidProfile: Bluetooth service connected
,09-07 15:29:49.783  1453  3351 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 15:29:49.783  1453  3351 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 15:29:49.783  4781  7278 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 15:29:49.783  4781  7278 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 15:29:49.783  1480  1496 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-07 15:29:49.783  1480  1496 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 15:29:49.783  4781  4789 D BluetoothMap: onBluetoothStateChange: up=true
,09-07 15:29:49.783  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,09-07 15:29:49.783  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-07 15:29:49.783  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:49.783  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:49.783  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-07 15:29:49.783  1453  1465 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-07 15:29:49.783  4781  4781 D BluetoothMap: Proxy object connected
09-07 15:29:49.783  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-07 15:29:49.783  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-07 15:29:49.783  4781  4781 D MapProfile: Bluetooth service connected
09-07 15:29:49.783  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:49.783  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:49.783  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
09-07 15:29:49.783  4781  4781 D BluetoothMap: getConnectedDevices()
,09-07 15:29:49.783  1453  1465 E BluetoothHeadset: BluetoothHeadset service is binded
,09-07 15:29:49.793  1463  1746 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 15:29:49.793  1463  1746 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 15:29:49.793  4781  4791 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-07 15:29:49.793  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-07 15:29:49.793  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-07 15:29:49.793  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,09-07 15:29:49.793  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:49.793  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-07 15:29:49.793  4781  4781 D HeadsetProfile: Bluetooth service connected
09-07 15:29:49.793  4781  4791 E BluetoothHeadset: BluetoothHeadset service is binded
,09-07 15:29:49.793  1679  2215 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 15:29:49.793  1679  2215 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-07 15:29:49.793  4781  7278 D Bluetoothsap: onBluetoothStateChange: up=true
,09-07 15:29:49.793  4781  7278 D Bluetoothsap: Binding service...
,09-07 15:29:49.793  4781  7278 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-07 15:29:49.793  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
09-07 15:29:49.793  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-07 15:29:49.793  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:49.793  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:49.793  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-07 15:29:49.803  4781  7278 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-07 15:29:49.803  4781  4781 D Bluetoothsap: BluetoothSAP Proxy object connected
09-07 15:29:49.803  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 15:29:49.803  1017  1046 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 15:29:49.803  4781  4781 D SapProfile: Bluetooth service connected
,09-07 15:29:49.803  4781  4781 D Bluetoothsap: getConnectedDevices()
09-07 15:29:49.803  1480  1660 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-07 15:29:49.803  1017  1046 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-07 15:29:49.803  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-07 15:29:49.803  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:49.803  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:49.803  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-07 15:29:49.803  1480  1660 E BluetoothHeadset: BluetoothHeadset service is binded
,09-07 15:29:49.803  1453  7807 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-07 15:29:49.803  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-07 15:29:49.803  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-07 15:29:49.813  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,09-07 15:29:49.813  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:49.813  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-07 15:29:49.813  1453  7807 E BluetoothHeadset: BluetoothHeadset service is binded
,09-07 15:29:49.813  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,09-07 15:29:49.813  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-07 15:29:49.813  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-07 15:29:49.813  1017  1017 I InputMethodManagerService: [BT Setting State] State =12
09-07 15:29:49.813  1017  1017 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-07 15:29:49.813  1453  1453 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@38800c27, true
,09-07 15:29:49.823  1453  1453 D BluetoothHeadset: registerMessageListener
,09-07 15:29:49.823  1175  1175 D BluetoothTile:  onBluetoothStateChange:
,09-07 15:29:49.823  1175  1718 D BluetoothTile:  handleUpdatestate:false name:null
,09-07 15:29:49.823  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-07 15:29:49.833  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-07 15:29:49.833  1175  1175 D BluetoothTile:  getBluetoothState : 12
,09-07 15:29:49.833  1175  1718 D BluetoothTile:  handleUpdatestate:false name:null
,09-07 15:29:49.833  1882  1882 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-07 15:29:49.833  1175  1718 D BluetoothTile:  handleUpdatestate:false name:null
,09-07 15:29:49.833  4781  4781 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-07 15:29:49.833  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:29:49.833  3212  3350 D HeadsetService: registerMessageListener
,09-07 15:29:49.843  3212  3350 D HeadsetService: registerMessageListener
09-07 15:29:49.843  3212  7818 D HeadsetStateMachine: Disconnected process message: 70
09-07 15:29:49.843  1017  1504 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-07 15:29:49.843  3212  7818 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@38a65343
09-07 15:29:49.843  1453  1453 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-07 15:29:49.843  1453  1453 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-07 15:29:49.843  1017  1546 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-07 15:29:49.843  1453  1453 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
09-07 15:29:49.843  1453  1453 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
09-07 15:29:49.843  1453  1453 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-07 15:29:49.843  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-07 15:29:49.843  4781  4781 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,09-07 15:29:49.843  4781  4781 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-07 15:29:49.843  4781  4781 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-07 15:29:49.843  4781  4781 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-07 15:29:49.843  3212  7818 D HeadsetStateMachine: Disconnected process message: 9
,09-07 15:29:49.843  3212  7818 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-07 15:29:49.843  3212  7827 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-07 15:29:49.853   283   704 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,09-07 15:29:49.853   283   704 V voice   : voice_set_parameters: enter: A2dpSuspended=false
,09-07 15:29:49.853   283   704 V voice   : voice_set_parameters: exit with code(-2)
09-07 15:29:49.853   283   704 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
,09-07 15:29:49.853   283   704 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-07 15:29:49.853   283   704 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-07 15:29:49.853   283   704 V audio_hw_primary: adev_set_parameters: exit
,09-07 15:29:49.853  3212  7818 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-07 15:29:49.853  3212  7827 D BluetoothSocket: bindListen(): myUserId = 0
09-07 15:29:49.853  3212  7827 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 15:29:49.853  4781  4781 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 15:29:49.853  3212  7827 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
09-07 15:29:49.853  3212  7827 D BluetoothSocket: bindListen(), new LocalSocket 
09-07 15:29:49.853  3212  7827 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-07 15:29:49.853  3212  7827 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@35020dc0
09-07 15:29:49.853  3212  7827 D BluetoothSocket: channel: 5
,09-07 15:29:49.853  1017  1029 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-07 15:29:49.853  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-07 15:29:49.853  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,09-07 15:29:49.853  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:49.853  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-07 15:29:49.863  1679  1679 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 15:29:49.873  4781  4781 D DockEventReceiver: finishStartingService: stopping service
,09-07 15:29:49.873  4781  4781 D BluetoothNotiBroadcastReceiver: onReceive
,09-07 15:29:49.873  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-07 15:29:49.873  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-07 15:29:49.883  3212  3212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26244bf3
,09-07 15:29:49.883  3212  3212 D BtConfig.SecureMode: isSecureModeOn:false
,09-07 15:29:49.883  1017  3795 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-07 15:29:49.883  1017  3795 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-07 15:29:49.883  1017  3795 W ActivityManager: userId = 0, bbcId = -10000
,09-07 15:29:49.883  1017  3795 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:49.883  1017  3795 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 15:29:49.893  1017  1546 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-07 15:29:49.903  3212  7832 D BluetoothSocket: bindListen(): myUserId = 0
,09-07 15:29:49.903  3212  7832 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 15:29:49.903  3212  7832 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[81]}
09-07 15:29:49.903  3212  7832 D BluetoothSocket: bindListen(), new LocalSocket 
09-07 15:29:49.903  3212  7832 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-07 15:29:49.903  3212  7832 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@32da45ec
,09-07 15:29:49.913  3212  7832 D BluetoothSocket: channel: 12
09-07 15:29:49.913  3212  7832 I BtOppRfcommListener: Accept thread started.
,09-07 15:29:50.113  1017  3359 D SSRM:n  : SIOP:: AP = 330
,09-07 15:29:50.413  6970  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:29:50.413  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:50.413  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:50.413  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 15:29:50.413  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:29:50.413  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:29:50.413  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:29:50.413  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 15:29:50.423  6970  7226 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null,
09-07 15:29:50.423  1017  1545 D WifiService: setWifiEnabled: false pid=6970, uid=10170
09-07 15:29:50.423  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 15:29:50.423  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ba03379 added. We now have 8 listener(s)
09-07 15:29:50.423  6970  7226 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 15:29:50.423  1017  1545 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-07 15:29:50.423  1017  1545 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-07 15:29:50.423  1017  1545 D SecContentProvider2: mCursor = null
09-07 15:29:50.423  1017  1545 D SettingsProvider: name = wifi_on
,09-07 15:29:50.433  6970  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:29:50.433  1017  1503 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-07 15:29:50.433  1017  1503 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-07 15:29:50.433  1017  1503 D SecContentProvider2: mCursor = null
,09-07 15:29:50.433  1017  1503 D WifiService: setWifiEnabled: true pid=6970, uid=10170
,09-07 15:29:50.433  1017  1503 W ActivityManager: Permission Denial: getCurrentUser() from pid=6970, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-07 15:29:50.433  1017  1503 W WifiService: Failed getting userId using ActivityManagerNative
09-07 15:29:50.433  1017  1503 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6970, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-07 15:29:50.433  1017  1503 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-07 15:29:50.433  1017  1503 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-07 15:29:50.433  1017  1503 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-07 15:29:50.433  1017  1503 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-07 15:29:50.433  1017  1503 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-07 15:29:50.433  1017  1503 D SettingsProvider: name = wifi_on
,09-07 15:29:50.443  1017  1128 E WifiHW  : ##################### set firmware type 0 #####################
,09-07 15:29:50.773  1017  1044 D Tethering: interfaceAdded wlan0
,09-07 15:29:50.773  1017  1131 E Tethering: No numeric data
,09-07 15:29:50.773  1017  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-07 15:29:50.773  1017  1131 D Tethering: clearTetheredNotification()
,09-07 15:29:50.773  1017  1125 V NetworkStats: performPollLocked(flags=0x1)
,09-07 15:29:50.773  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 15:29:50.773  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-07 15:29:50.783  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-07 15:29:50.783  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-07 15:29:50.783  1175  1175 D HotspotTile: updateTetherState():false, false
,09-07 15:29:50.783  1017  1125 V NetworkStats: performPollLocked() took 9ms
,09-07 15:29:50.783  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 15:29:50.783  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 15:29:50.793  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 15:29:50.793  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
,09-07 15:29:50.793  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
09-07 15:29:50.793  1017  1131 D Tethering: InitialState.processMessage what=4
09-07 15:29:50.793  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-07 15:29:50.793  1017  1131 E Tethering: No numeric data
,09-07 15:29:50.793  1017  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-07 15:29:50.793  1017  1131 D Tethering: clearTetheredNotification()
,09-07 15:29:50.793  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 15:29:50.793  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-07 15:29:50.793  1017  1044 D Tethering: interfaceAdded p2p0
09-07 15:29:50.793  1175  1175 D HotspotTile: updateTetherState():false, false
09-07 15:29:50.793  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
09-07 15:29:50.793  1017  1125 V NetworkStats: performPollLocked(flags=0x1)
09-07 15:29:50.793  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-07 15:29:50.803  1017  1044 D Tethering: p2p0 is not a tetherable iface, ignoring
,09-07 15:29:50.803  1017  1125 V NetworkStats: performPollLocked() took 6ms
,09-07 15:29:50.803  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit,
,09-07 15:29:50.803  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 15:29:50.803  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 15:29:50.813  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
,09-07 15:29:50.813  1017  1044 D Tethering: interfaceStatusChanged p2p0, false,
09-07 15:29:50.813  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-07 15:29:50.813   278   990 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,09-07 15:29:50.813   278   990 D SoftapController: Softap fwReload - Ok
,09-07 15:29:50.813   278   990 D CommandListener: Setting iface cfg,
09-07 15:29:50.813   278   990 D CommandListener: Trying to bring down wlan0
09-07 15:29:50.813   278   990 D CommandListener: Clearing all IP addresses on wlan0
,09-07 15:29:50.823  1017  1128 E WifiHW  : supplicant_name : p2p_supplicant
,09-07 15:29:50.843   288   288 E SMD     : DCD OFF
,09-07 15:29:50.863  7843  7843 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,09-07 15:29:50.863  7843  7843 I wpa_supplicant: Successfully initialized wpa_supplicant
09-07 15:29:50.863  7843  7843 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-07 15:29:50.873  7843  7843 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
,09-07 15:29:50.883   398   398 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7843,
09-07 15:29:50.883   398   398 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-07 15:29:50.883  7843  7843 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running,
09-07 15:29:50.883  7843  7843 I wpa_supplicant: ssSupport state is = 1
09-07 15:29:50.883  7843  7843 I wpa_supplicant: >>>>> GET KEY, IV <<<<<,
09-07 15:29:50.883  7843  7843 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,09-07 15:29:50.883   398   398 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7843
09-07 15:29:50.883   398   398 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,09-07 15:29:50.933  1017  1128 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-07 15:29:50.933  4781  4781 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-07 15:29:50.943  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:29:50.943  1017  1030 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-07 15:29:50.943  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-07 15:29:50.943  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:50.943  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:50.943  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-07 15:29:50.943  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-07 15:29:50.943  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 15:29:50.943  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null,
09-07 15:29:50.943  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:50.943  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-07 15:29:50.943  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:50.943  1175  1718 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-07 15:29:50.943  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:50.943  1175  1175 D HotspotTile: onReceive : 2, 0
09-07 15:29:50.943  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:50.943  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-07 15:29:50.943  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
09-07 15:29:50.943  1633  1633 I Hs20UtilService: Starting #19
09-07 15:29:50.943  1633  1663 I Hs20UtilService: Message received 5011
09-07 15:29:50.943  7374  7374 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-07 15:29:50.943  7374  7374 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-07 15:29:50.943  7374  7374 D SecurityLogAgent: StateMachine : Current State = 1
09-07 15:29:50.943  7374  7374 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-07 15:29:51.043   398   398 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,09-07 15:29:51.043  7843  7843 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,09-07 15:29:51.083  7843  7843 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-07 15:29:51.083  7843  7843 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-07 15:29:51.093  7843  7843 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
,09-07 15:29:51.093   398   398 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7843
09-07 15:29:51.093   398   398 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-07 15:29:51.093  7843  7843 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-07 15:29:51.093  7843  7843 I wpa_supplicant: ssSupport state is = 1
09-07 15:29:51.093  7843  7843 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-07 15:29:51.103  7843  7843 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-07 15:29:51.103  7843  7843 E wpa_supplicant: SIM READ ERROR
09-07 15:29:51.103  7843  7843 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-07 15:29:51.103  7843  7843 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-07 15:29:51.103  7843  7843 E wpa_supplicant: SIM READ ERROR,
09-07 15:29:51.103  7843  7843 I wpa_supplicant: Blacklist: Clear (all) 
,09-07 15:29:51.103  7843  7843 I wpa_supplicant: wpa_default_ap_write_once,
09-07 15:29:51.103  7843  7843 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-07 15:29:51.103  7843  7843 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-07 15:29:51.103  7843  7843 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory,
09-07 15:29:51.103  7843  7843 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-07 15:29:51.103  7843  7843 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-07 15:29:51.103  7843  7843 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,09-07 15:29:51.103  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false,
09-07 15:29:51.103  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-07 15:29:51.103  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-07 15:29:51.143  7843  7843 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,09-07 15:29:51.243  7843  7843 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,09-07 15:29:51.243  7843  7843 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,09-07 15:29:51.253  7843  7843 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-07 15:29:51.253   398   398 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7843
09-07 15:29:51.253   398   398 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
09-07 15:29:51.253  7843  7843 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-07 15:29:51.253  7843  7843 I wpa_supplicant: ssSupport state is = 1
09-07 15:29:51.253  7843  7843 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-07 15:29:51.263  7843  7843 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-07 15:29:51.273  7843  7843 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-07 15:29:51.273   398   398 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7843
09-07 15:29:51.273   398   398 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,09-07 15:29:51.273  7843  7843 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-07 15:29:51.273  7843  7843 I wpa_supplicant: ssSupport state is = 1
09-07 15:29:51.273  7843  7843 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-07 15:29:51.273  7843  7843 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
09-07 15:29:51.273  7843  7843 E wpa_supplicant: SIM READ ERROR
09-07 15:29:51.273  7843  7843 I wpa_supplicant: wpa_default_ap_write_once
09-07 15:29:51.273  7843  7843 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
,09-07 15:29:51.273  7843  7843 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-07 15:29:51.273  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
09-07 15:29:51.273  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
09-07 15:29:51.283  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-07 15:29:51.283  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
09-07 15:29:51.283  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,09-07 15:29:51.283  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-07 15:29:51.413  7843  7843 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
09-07 15:29:51.413  7843  7843 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-07 15:29:51.533  7843  7843 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,09-07 15:29:51.533  7843  7843 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-07 15:29:51.533  7843  7843 I wpa_supplicant: Skip scan - bUseNetwork false
,09-07 15:29:51.543  1017  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
09-07 15:29:51.543  1017  1128 D WifiNative-wlan0: callSECApiBoolean - ID [21]
09-07 15:29:51.543  7843  7843 I wpa_supplicant: HOTSPOT20_ENABLE called
,09-07 15:29:51.543  7843  7843 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-07 15:29:51.543  7843  7843 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-07 15:29:51.543  7843  7843 E wpa_supplicant: SIM READ ERROR
09-07 15:29:51.543  7843  7843 I wpa_supplicant: Blacklist: Clear (all) 
,09-07 15:29:51.573  7843  7843 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,09-07 15:29:51.583  7843  7843 I wpa_supplicant: Skip scan - bUseNetwork false,
,09-07 15:29:51.593  1017  1128 D WifiConfigStore: Loading config and enabling all networks ,
,09-07 15:29:51.593  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-07 15:29:51.593  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 15:29:51.593  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-07 15:29:51.593  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 15:29:51.593  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 15:29:51.593  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 15:29:51.593  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:51.593  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-07 15:29:51.593  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-07 15:29:51.593  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
09-07 15:29:51.603  1175  1718 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-07 15:29:51.603  1175  1175 D HotspotTile: onReceive : 3, 0
,09-07 15:29:51.603  4781  4781 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-07 15:29:51.603  1017  1546 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-07 15:29:51.613  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:29:51.613  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:51.613  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:51.613  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:29:51.613  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:29:51.613  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:29:51.613  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:29:51.613  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 15:29:51.613  1017  1546 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-07 15:29:51.613  1017  1546 W ActivityManager: userId = 0, bbcId = -10000
,09-07 15:29:51.613  1017  1546 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:51.613  1017  1128 E WifiConfigStore: Not a HS20
,09-07 15:29:51.613  1017  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-07 15:29:51.613  1633  1633 I Hs20UtilService: Starting #20
,09-07 15:29:51.613  1633  1663 I Hs20UtilService: Message received 5011
,09-07 15:29:51.623  6970  6970 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 15:29:51.623  1017  1128 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-07 15:29:51.623  7374  7374 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-07 15:29:51.623  7374  7374 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-07 15:29:51.623  7374  7374 D SecurityLogAgent: StateMachine : Current State = 1
09-07 15:29:51.623  7374  7374 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-07 15:29:51.633  1017  1128 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,09-07 15:29:51.633  7843  7843 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-07 15:29:51.633  7843  7843 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-07 15:29:51.633  7843  7843 I wpa_supplicant: reset timer : RESET_TIMER 0
09-07 15:29:51.633  7843  7843 I wpa_supplicant: P2P: Current p2p state = IDLE
09-07 15:29:51.633  7843  7843 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-07 15:29:51.633  7843  7843 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,09-07 15:29:51.633  7843  7843 I wpa_supplicant: First Scan Start
09-07 15:29:51.633  7843  7843 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-07 15:29:51.633  1017  1128 D WifiNative-wlan0: Setting external_sim to 1
,09-07 15:29:51.633  1017  1128 D WifiStateMachine: Setting OUI to DA-A1-19
09-07 15:29:51.633  1017  1128 I WifiNative-HAL: startHal
09-07 15:29:51.633  1017  1128 E wifi    : getStaticLongField sWifiHalHandle 0x9f05088c
09-07 15:29:51.633  1017  1128 I WifiNative-HAL: Could not start hal
,09-07 15:29:51.633  7351  7351 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 15:29:51.643  1017  1128 E WifiNative-wlan0: do suspend true
,09-07 15:29:51.643  1017  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
09-07 15:29:51.643  1017  1127 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-07 15:29:51.643   278   990 D CommandListener: Setting iface cfg
09-07 15:29:51.643   278   990 D CommandListener: Trying to bring up p2p0
,09-07 15:29:51.643  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 3
,09-07 15:29:51.643  1017  1151 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,09-07 15:29:51.643  1017  1151 I WifiNative-HAL: startHal
09-07 15:29:51.643  1017  1151 E wifi    : getStaticLongField sWifiHalHandle 0x9df129bc
,09-07 15:29:51.643  1017  1151 I WifiNative-HAL: Could not start hal
09-07 15:29:51.643  1017  1151 E WifiScanningService: could not start HAL
09-07 15:29:51.643  1017  1127 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-07 15:29:51.643  1017  1017 D RttService: SCAN_AVAILABLE : 3
09-07 15:29:51.643  1017  1127 D WifiP2pService: P2pEnablingState
,09-07 15:29:51.643  1017  1152 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:29:51.643  1017  1127 D WifiP2pService: P2pEnablingState{ what=147457 }
09-07 15:29:51.643  1017  1128 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-07 15:29:51.643  1017  1127 D WifiP2pService: P2p socket connection successful
09-07 15:29:51.643  1017  1128 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-07 15:29:51.643  1017  1127 D WifiP2pService: P2pEnabledState
09-07 15:29:51.643  1017  1128 E WifiNative-wlan0: invaild command id : 215
09-07 15:29:51.643  1017  1128 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-07 15:29:51.643  1017  1128 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-07 15:29:51.643  1017  1127 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-07 15:29:51.643  1017  1128 E WifiNative-wlan0: invaild command id : 215
,09-07 15:29:51.643  1017  1130 E ConnectivityService: updateNetworkInfo()
,09-07 15:29:51.653  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-07 15:29:51.653  7843  7843 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-07 15:29:51.653  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,09-07 15:29:51.653  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-07 15:29:51.653  1017  1047 D WifiDisplayController: disconnect
09-07 15:29:51.653  1017  1047 D WifiDisplayController: updateConnection
,09-07 15:29:51.653  7843  7843 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-07 15:29:51.653  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-07 15:29:51.653  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-07 15:29:51.653  7843  7843 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands,
09-07 15:29:51.653  1017  1128 E WifiStateMachine: Failed to set frequency band 0
09-07 15:29:51.653  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-07 15:29:51.653  1017  1128 D SecContentProvider2: mCursor = null,
09-07 15:29:51.653  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 15:29:51.653  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
09-07 15:29:51.653  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer,
09-07 15:29:51.653  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-07 15:29:51.663  1017  1127 D WifiNative-p2p0: p2pGetDeviceAddress
,09-07 15:29:51.663  1017  1127 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,09-07 15:29:51.663  1175  1175 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-07 15:29:51.663  1017  1504 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0},
09-07 15:29:51.663  1175  1175 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-07 15:29:51.663  4781  4781 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-07 15:29:51.673  1017  1127 D WifiP2pService: DeviceAddress: 0a:75:42
,09-07 15:29:51.673  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-07 15:29:51.673  1017  1128 D SecContentProvider2: mCursor = null
,09-07 15:29:51.673  1017  1047 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
09-07 15:29:51.673  1017  1047 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
09-07 15:29:51.673  1017  1047 D WifiDisplayController:  primary type: 10-0050F204-5
09-07 15:29:51.673  1017  1047 D WifiDisplayController:  secondary type: null
09-07 15:29:51.673  1017  1047 D WifiDisplayController:  wps: 0
09-07 15:29:51.673  1017  1047 D WifiDisplayController:  grpcapab: 0
09-07 15:29:51.673  1017  1047 D WifiDisplayController:  devcapab: 0
09-07 15:29:51.673  1017  1047 D WifiDisplayController:  status: 3
09-07 15:29:51.673  1017  1047 D WifiDisplayController:  wfdInfo: null
09-07 15:29:51.673  1017  1047 D WifiDisplayController:  groupownerAddress: null
09-07 15:29:51.673  1017  1047 D WifiDisplayController:  GOdeviceName: null
09-07 15:29:51.673  1017  1047 D WifiDisplayController:  interfaceAddress: 
09-07 15:29:51.673  1017  1047 D WifiDisplayController:  SConnectInfo : null
,09-07 15:29:51.673  4781  4781 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-07 15:29:51.673  4781  4781 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-07 15:29:51.673  4781  4781 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-07 15:29:51.673  4781  4781 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-07 15:29:51.673  4781  4781 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-07 15:29:51.673  4781  4834 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-07 15:29:51.683  7305  7305 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-07 15:29:51.683  7305  7305 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-07 15:29:51.683  7305  7305 D FileShare-Client: Outbound.stopDelayTimer - 
,09-07 15:29:51.683  7336  7336 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-07 15:29:51.693  1017  1127 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-07 15:29:51.693  1017  1127 D WifiP2pService: InactiveState
,09-07 15:29:51.693  1017  1127 D WifiP2pService: InactiveState{ what=143376 }
,09-07 15:29:51.693  1017  1127 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-07 15:29:51.693  7843  7843 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
,09-07 15:29:51.693  1017  1127 D WifiP2pService: InactiveState{ what=143376 }
,09-07 15:29:51.693  1017  1127 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-07 15:29:51.793  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
,09-07 15:29:51.793  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,09-07 15:29:51.793  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-07 15:29:52.453  6970  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
,09-07 15:29:52.453  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:52.453  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:52.453  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:29:52.453  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:29:52.453  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:29:52.453  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:29:52.453  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 15:29:52.463  6970  7226 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 15:29:52.463  6970  7226 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-07 15:29:52.463  6970  7226 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-07 15:29:52.463  6970  7226 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1ca27099 Bundle[{}]
09-07 15:29:52.463  6970  7226 I io.jxcore.node.LifeCycleMonitor: start: OK
09-07 15:29:52.463  6970  7226 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-07 15:29:52.463  6970  7226 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-07 15:29:52.463  6970  7226 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-07 15:29:52.463  6970  7226 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-07 15:29:52.473  6970  7226 D io.jxcore.node.LifeCycleMonitor: onActivityPaused,
,09-07 15:29:52.473  6970  7226 I System.out: Running OutgoingSocketThread
,09-07 15:29:52.473  6970  7852 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1414)
,09-07 15:29:52.483  6970  7852 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57500
,09-07 15:29:52.483  6970  7852 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-07 15:29:52.833  7843  7843 I wpa_supplicant: nl80211: Received scan results (23 BSSes),
09-07 15:29:52.833  7843  7843 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec,
09-07 15:29:52.833  7843  7843 I wpa_supplicant: Trying to associate with SSID '4E47373030'
09-07 15:29:52.833  7843  7843 I wpa_supplicant: Trying to associate with  'G700'
09-07 15:29:52.833  7843  7843 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,09-07 15:29:52.833  7843  7843 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
09-07 15:29:52.833  1017  7849 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,09-07 15:29:52.853  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-07 15:29:52.853  1017  1128 D SecContentProvider2: mCursor = null
,09-07 15:29:52.953  7843  7843 E wpa_supplicant: Cmd 35605 not handled
,09-07 15:29:52.953  7843  7843 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-07 15:29:52.953  7843  7843 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,09-07 15:29:52.953  7843  7843 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-07 15:29:52.953  7843  7843 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-07 15:29:52.953  7843  7843 I wpa_supplicant: Associated with F4.99.3E
09-07 15:29:52.953  7843  7843 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-07 15:29:52.953  7843  7843 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
,09-07 15:29:52.953  7843  7843 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,09-07 15:29:52.953  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-07 15:29:52.953  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-07 15:29:52.953  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-07 15:29:52.953  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false,
,09-07 15:29:52.953  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-07 15:29:52.963  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-07 15:29:52.963  7843  7843 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-07 15:29:52.963  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-07 15:29:52.963  1017  1044 D Tethering: interfaceStatusChanged wlan0, false,
,09-07 15:29:52.963  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-07 15:29:52.963  7843  7843 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE,
,09-07 15:29:52.963  7843  7843 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
09-07 15:29:52.963  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,09-07 15:29:52.963  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-07 15:29:52.963  1017  1128 D SecContentProvider2: mCursor = null
09-07 15:29:52.963  7843  7843 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
09-07 15:29:52.963  7843  7843 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-07 15:29:52.963  7843  7843 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,09-07 15:29:52.963  7843  7843 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-07 15:29:52.963  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true
,09-07 15:29:52.963  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
09-07 15:29:52.963  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-07 15:29:52.963  1017  1128 D SecContentProvider2: mCursor = null,
,09-07 15:29:52.963  7843  7843 I wpa_supplicant: Blacklist: Clear (temp) ,
09-07 15:29:52.973  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,09-07 15:29:52.963  7843  7843 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
09-07 15:29:52.973  1017  1125 V NetworkStats: performPollLocked(flags=0x1)
,09-07 15:29:52.963  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true
09-07 15:29:52.963  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
09-07 15:29:52.963  1017  1131 E Tethering: No numeric data
,09-07 15:29:52.973  1017  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-07 15:29:52.973  1017  1131 D Tethering: clearTetheredNotification()
09-07 15:29:52.973  1017  1128 D WifiNative-wlan0: callSECApiVoid - ID [50]
09-07 15:29:52.973  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 15:29:52.973  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-07 15:29:52.973  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-07 15:29:52.973  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-07 15:29:52.973  1175  1175 D HotspotTile: updateTetherState():false, false
,09-07 15:29:52.973  1017  1128 E WifiConfigStore: setLastSelectedConfiguration -1
,09-07 15:29:52.983  1017  1128 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-07 15:29:52.983  1017  1130 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-07 15:29:52.983  1017  1130 E ConnectivityService: updateNetworkInfo()
09-07 15:29:52.983  1017  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 15:29:52.983  1017  1125 V NetworkStats: performPollLocked() took 8ms
09-07 15:29:52.983  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 15:29:52.983  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-07 15:29:52.983  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 15:29:52.983  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-07 15:29:52.983  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:52.983  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:52.983  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:52.983  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 15:29:52.983  1017  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 15:29:52.993  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 15:29:52.993  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 15:29:52.993  1017  1255 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-07 15:29:52.993  1017  1255 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-07 15:29:52.993  1017  1255 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:52.993  1017  1255 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 15:29:52.993  1017  1255 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-07 15:29:52.993  1633  1633 I Hs20UtilService: Starting #21
09-07 15:29:52.993  1633  1663 I Hs20UtilService: Message received 5007
,09-07 15:29:53.003  4781  4781 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
,09-07 15:29:53.003  4781  4781 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-07 15:29:53.003  4781  4781 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-07 15:29:53.003  4781  4781 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-07 15:29:53.003  4781  4781 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-07 15:29:53.003  4781  4781 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-07 15:29:53.003  4781  4834 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-07 15:29:53.013  1017  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 15:29:53.023   278   990 D CommandListener: Setting iface cfg,
09-07 15:29:53.023  1017  1128 E WifiStateMachine: Start Dhcp Watchdog 3
,09-07 15:29:53.023  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-07 15:29:53.023  1017  1128 D SecContentProvider2: mCursor = null
,09-07 15:29:53.033  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-07 15:29:53.033  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 15:29:53.043  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-07 15:29:53.043  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 15:29:53.043  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:53.043  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:53.043  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 15:29:53.043  1017  1128 E WifiNative-wlan0: do suspend false
,09-07 15:29:53.043  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-07 15:29:53.043  1017  1128 D SecContentProvider2: mCursor = null
09-07 15:29:53.043  1017  1127 D WifiP2pService: InactiveState{ what=143375 }
,09-07 15:29:53.043  1017  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-07 15:29:53.053  1017  3785 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-07 15:29:53.053  1017  3785 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4287, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-07 15:29:53.053  1017  3785 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-07 15:29:53.053  1017  3785 D BatteryService: stay LED for charging
,09-07 15:29:53.053  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-07 15:29:53.053  1017  1017 I MotionRecognitionService: Plugged
,09-07 15:29:53.053  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,09-07 15:29:53.063  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-07 15:29:53.063  1432  1432 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-07 15:29:53.063  1432  1432 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-07 15:29:53.063  1175  1175 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-07 15:29:53.073  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-07 15:29:53.073  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-07 15:29:53.073  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-07 15:29:53.073  1175  1175 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
09-07 15:29:53.073  1175  1175 D SViewCoverView: level :100 plugged : 2
,09-07 15:29:53.073  3212  3212 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-07 15:29:53.073  3212  7818 D HeadsetStateMachine: Disconnected process message: 10
,09-07 15:29:53.273  7856  7856 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-07 15:29:53.273  7856  7856 I dhcpcd  : version 5.5.6 starting,
,09-07 15:29:53.283  7856  7856 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-07 15:29:53.333  7856  7856 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
09-07 15:29:53.333  7856  7856 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-07 15:29:53.333  7856  7856 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E),
09-07 15:29:53.333  7856  7856 I dhcpcd  : bssid match
09-07 15:29:53.333  7856  7856 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
,09-07 15:29:53.403  7856  7856 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1,
,09-07 15:29:53.473  7856  7856 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds,
,09-07 15:29:53.473  6970  7226 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1415)
09-07 15:29:53.473  6970  7226 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1415)
,09-07 15:29:53.483  6970  7226 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1420),
,09-07 15:29:53.483  6970  7226 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-07 15:29:53.483  6970  7226 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1421)
,09-07 15:29:53.483  6970  7226 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
,09-07 15:29:53.483  6970  7226 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b7af8be added. We now have 2 listener(s)
,09-07 15:29:53.493  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-07 15:29:53.493  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-07 15:29:53.493  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 15:29:53.493  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 15:29:53.493  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c19fd1f added. We now have 9 listener(s)
09-07 15:29:53.493  6970  7226 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
09-07 15:29:53.493  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
,09-07 15:29:53.493  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 15:29:53.503  6970  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 15:29:53.503  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:53.503  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:53.503  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:29:53.503  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:29:53.503  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:29:53.503  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
,09-07 15:29:53.503  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 15:29:53.503  6970  7226 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 15:29:53.503  6970  7226 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 15:29:53.503  6970  7226 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 15:29:53.503  6970  7226 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8678e35 added. We now have 3 listener(s)
,09-07 15:29:53.513  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:29:53.513  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-07 15:29:53.513  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41",
09-07 15:29:53.513  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 15:29:53.513  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 15:29:53.513  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 15:29:53.513  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1369e2ca added. We now have 10 listener(s)
,09-07 15:29:53.513  6970  7226 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 15:29:53.513  6970  7226 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 15:29:53.513  6970  7226 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:29:53.513  6970  7226 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:29:53.523  6970  7226 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:29:53.523  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 15:29:53.523  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 15:29:53.523  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 15:29:53.523  6970  7226 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b7af8be removed from the list
09-07 15:29:53.523  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:53.523  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c19fd1f removed from the list
,09-07 15:29:53.523  6970  7226 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:29:53.523  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:53.523  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:53.523  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 15:29:53.523  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:29:53.523  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:29:53.523  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:53.523  6970  7226 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c19fd1f not in the list
09-07 15:29:53.523  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:53.523  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:53.523  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:29:53.523  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:29:53.523  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:53.523  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1369e2ca removed from the list
09-07 15:29:53.523  6970  7226 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:29:53.523  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:53.523  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-07 15:29:53.523  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 15:29:53.523  6970  7226 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8678e35 removed from the list
09-07 15:29:53.523  6970  7226 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 15:29:53.523  6970  7226 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@396b4c3b added. We now have 2 listener(s)
,09-07 15:29:53.533  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-07 15:29:53.533  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 15:29:53.533  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 15:29:53.533  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
09-07 15:29:53.533  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@148b9f58 added. We now have 9 listener(s)
09-07 15:29:53.533  6970  7226 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 15:29:53.533  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 15:29:53.543  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 15:29:53.543  6970  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 15:29:53.543  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:53.543  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:53.543  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:29:53.543  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:29:53.543  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:29:53.543  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:29:53.543  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 15:29:53.553  6970  7226 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 15:29:53.553  6970  7226 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 15:29:53.553  6970  7226 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 15:29:53.553  6970  7226 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ab6196 added. We now have 3 listener(s)
09-07 15:29:53.553  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:29:53.553  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:29:53.553  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-07 15:29:53.553  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 15:29:53.553  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 15:29:53.553  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 15:29:53.553  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b87117 added. We now have 10 listener(s)
09-07 15:29:53.553  6970  7226 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 15:29:53.553  6970  7226 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 15:29:53.553  6970  7226 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 15:29:53.553  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 15:29:53.553  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 15:29:53.553  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 15:29:53.553  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-07 15:29:53.563  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-07 15:29:53.563  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-07 15:29:53.573  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-07 15:29:53.573  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-07 15:29:53.573  6970  7226 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-07 15:29:53.573  3212  3226 D BtGatt.GattService: registerClient() - UUID=aa7c4d5d-adfa-42f0-a0fc-2fe907e711d7
,09-07 15:29:53.613  3212  3294 D BtGatt.GattService: onClientRegistered() - UUID=aa7c4d5d-adfa-42f0-a0fc-2fe907e711d7, clientIf=6
,09-07 15:29:53.623  6970  6979 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-07 15:29:53.623  3212  3350 D BtGatt.GattService: start scan with filters
,09-07 15:29:53.623  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-07 15:29:53.623  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-07 15:29:53.623  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-07 15:29:53.623  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-07 15:29:53.623  3212  3348 D BtGatt.ScanManager: handling starting scan
,09-07 15:29:53.623  6970  7226 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
09-07 15:29:53.623  6970  7226 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-07 15:29:53.623  6970  6970 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false,
09-07 15:29:53.623  3212  3294 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-07 15:29:53.623  3212  3294 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 15:29:53.623  3212  3348 D BtGatt.ScanManager: allow scan with filters,
09-07 15:29:53.623  3212  3348 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-07 15:29:53.623  3212  3348 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
09-07 15:29:53.623  3212  3294 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15,
09-07 15:29:53.623  3212  3294 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 15:29:53.633  3212  3348 D BtGatt.ScanManager: Starting BLE batch scan
,09-07 15:29:53.633  3212  3348 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-07 15:29:53.633  3212  3294 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-07 15:29:53.633  3212  3294 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 15:29:53.633  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
,09-07 15:29:53.633  3212  3294 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
09-07 15:29:53.633  3212  3294 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 15:29:53.633  6970  7226 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-07 15:29:53.633  6970  7226 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-07 15:29:53.633  6970  7226 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-07 15:29:53.633  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:53.633  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 15:29:53.633  6970  7226 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 15:29:53.633  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
09-07 15:29:53.633  6970  7226 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 15:29:53.633  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 15:29:53.633  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 15:29:53.633  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-07 15:29:53.643  3212  3226 D BtGatt.GattService: stopScan() - queue size =1
09-07 15:29:53.643  3212  7765 D BtGatt.GattService: unregisterClient() - clientIf=6
09-07 15:29:53.643  3212  3348 D BtGatt.ScanManager: filter size is 1
09-07 15:29:53.643  3212  3348 D BtGatt.ScanManager: delete FilterIndex - 6
09-07 15:29:53.643  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 15:29:53.643  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-07 15:29:53.643  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-07 15:29:53.643  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-07 15:29:53.643  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-07 15:29:53.643  6970  7226 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
09-07 15:29:53.643  3212  3294 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-07 15:29:53.643  3212  3294 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 15:29:53.643  3212  3348 D BtGatt.ScanManager: stopping BLe Batch
09-07 15:29:53.643  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
09-07 15:29:53.643  6970  7226 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 15:29:53.643  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 15:29:53.643  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 15:29:53.643  6970  6970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 15:29:53.643  6970  6970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 15:29:53.643  6970  6970 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 15:29:53.653  3212  3294 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
09-07 15:29:53.653  3212  3294 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 15:29:53.653  3212  3348 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-07 15:29:53.653  3212  3294 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-07 15:29:53.653  3212  3294 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 15:29:53.653  6970  7226 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 15:29:53.653  6970  7226 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:29:53.653  6970  7226 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:29:53.653  6970  7226 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 15:29:53.653  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:53.653  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 15:29:53.653  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 15:29:53.653  6970  7226 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@396b4c3b removed from the list
09-07 15:29:53.653  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:53.653  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@148b9f58 removed from the list
,09-07 15:29:53.653  6970  7226 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:29:53.653  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:53.653  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:53.653  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 15:29:53.653  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:29:53.653  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:29:53.653  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:53.653  6970  7226 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@148b9f58 not in the list
09-07 15:29:53.653  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 15:29:53.653  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 15:29:53.663  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-07 15:29:53.663  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:29:53.663  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:53.663  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b87117 removed from the list
09-07 15:29:53.663  6970  7226 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 15:29:53.663  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:53.663  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:53.663  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 15:29:53.663  6970  7226 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ab6196 removed from the list
,09-07 15:29:53.663  6970  7226 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 15:29:53.663  6970  7226 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f4907b3 added. We now have 2 listener(s)
,09-07 15:29:53.663  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-07 15:29:53.663  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-07 15:29:53.663  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 15:29:53.663  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
09-07 15:29:53.663  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e30170 added. We now have 9 listener(s)
09-07 15:29:53.663  6970  7226 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 15:29:53.663  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 15:29:53.673  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 15:29:53.673  6970  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 15:29:53.673  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:53.673  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:53.673  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:29:53.673  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true,
09-07 15:29:53.673  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:29:53.673  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:29:53.673  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 15:29:53.683  6970  7226 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
09-07 15:29:53.683  6970  7226 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 15:29:53.683  6970  7226 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 15:29:53.683  6970  7226 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39b50d6e added. We now have 3 listener(s)
,09-07 15:29:53.683  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:29:53.683  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:29:53.683  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-07 15:29:53.683  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 15:29:53.683  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 15:29:53.683  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 15:29:53.683  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d426c0f added. We now have 10 listener(s)
09-07 15:29:53.683  6970  7226 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 15:29:53.683  6970  7226 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 15:29:53.683  6970  7226 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 15:29:53.683  6970  7226 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-07 15:29:53.683  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 15:29:53.683  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 15:29:53.683  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 15:29:53.693  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-07 15:29:53.703  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 15:29:53.703  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 15:29:53.703  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
09-07 15:29:53.703  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-07 15:29:53.703  6970  7226 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-07 15:29:53.713  3212  3221 D BtGatt.GattService: registerClient() - UUID=3f0a663f-0636-41cf-ad90-347705fc556b
,09-07 15:29:53.753  3212  3294 D BtGatt.GattService: onClientRegistered() - UUID=3f0a663f-0636-41cf-ad90-347705fc556b, clientIf=6
09-07 15:29:53.753  6970  6979 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-07 15:29:53.753  3212  3350 D BtGatt.GattService: start scan with filters
09-07 15:29:53.753  3212  3348 D BtGatt.ScanManager: handling starting scan,
09-07 15:29:53.753  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-07 15:29:53.753  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
09-07 15:29:53.753  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-07 15:29:53.753  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-07 15:29:53.753  3212  3294 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-07 15:29:53.753  3212  3294 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
09-07 15:29:53.753  3212  3348 D BtGatt.ScanManager: allow scan with filters
09-07 15:29:53.753  3212  3348 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-07 15:29:53.753  3212  3348 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
,09-07 15:29:53.763  3212  3294 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-07 15:29:53.763  3212  3294 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,09-07 15:29:53.763  3212  3348 D BtGatt.ScanManager: Starting BLE batch scan
09-07 15:29:53.763  3212  3348 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-07 15:29:53.763  3212  3294 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-07 15:29:53.763  3212  3294 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 15:29:53.763  6970  7226 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 15:29:53.763  6970  6970 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 15:29:53.763  3212  3294 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-07 15:29:53.763  3212  3294 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 15:29:53.773  6970  7226 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-07 15:29:53.773  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 15:29:53.773  6970  7226 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-07 15:29:53.773  6970  7226 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-07 15:29:53.783  6970  7226 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:29:53.783  6970  7226 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:29:53.783  6970  7226 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:29:53.783  6970  7226 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:29:53.783  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:53.783  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 15:29:53.783  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 15:29:53.783  6970  7226 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f4907b3 removed from the list
09-07 15:29:53.783  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:53.783  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e30170 removed from the list
09-07 15:29:53.783  6970  7226 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:29:53.783  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 15:29:53.783  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:53.783  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-07 15:29:53.783  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:53.783  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 15:29:53.783  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
09-07 15:29:53.783  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:29:53.783  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:53.783  6970  7226 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e30170 not in the list
09-07 15:29:53.783  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 15:29:53.783  6970  7226 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 15:29:53.783  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-07 15:29:53.783  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 15:29:53.783  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-07 15:29:53.783  3212  3349 D BtGatt.GattService: stopScan() - queue size =1
,09-07 15:29:53.783  3212  3348 D BtGatt.ScanManager: filter size is 1
09-07 15:29:53.783  3212  3348 D BtGatt.ScanManager: delete FilterIndex - 7
,09-07 15:29:53.783  3212  3350 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-07 15:29:53.783  3212  3294 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-07 15:29:53.783  3212  3294 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 15:29:53.783  3212  3348 D BtGatt.ScanManager: stopping BLe Batch
,09-07 15:29:53.783  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 15:29:53.783  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-07 15:29:53.783  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-07 15:29:53.783  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-07 15:29:53.783  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-07 15:29:53.783  6970  7226 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 15:29:53.793  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 15:29:53.793  6970  7226 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 15:29:53.793  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 15:29:53.793  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 15:29:53.793  3212  3294 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-07 15:29:53.793  3212  3294 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 15:29:53.793  3212  3348 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-07 15:29:53.793  3212  3294 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-07 15:29:53.793  3212  3294 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 15:29:53.793  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:29:53.793  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:29:53.793  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:53.793  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d426c0f removed from the list
09-07 15:29:53.793  6970  7226 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:29:53.793  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:53.793  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:53.793  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 15:29:53.793  6970  7226 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39b50d6e removed from the list
,09-07 15:29:53.793  6970  6970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 15:29:53.793  6970  7226 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 15:29:53.793  6970  7226 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25c3ba2b added. We now have 2 listener(s)
,09-07 15:29:53.793  6970  6970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 15:29:53.793  6970  6970 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 15:29:53.803  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-07 15:29:53.803  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-07 15:29:53.803  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-07 15:29:53.803  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 15:29:53.803  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f518e88 added. We now have 9 listener(s)
,09-07 15:29:53.803  6970  7226 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 15:29:53.803  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 15:29:53.813  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 15:29:53.813  6970  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 15:29:53.813  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:53.813  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:53.813  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:29:53.813  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:29:53.813  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:29:53.813  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:29:53.813  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 15:29:53.813  6970  7226 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 15:29:53.813  6970  7226 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 15:29:53.813  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:29:53.823  6970  7226 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 15:29:53.823  6970  7226 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e1d5c46 added. We now have 3 listener(s)
,09-07 15:29:53.823  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-07 15:29:53.823  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-07 15:29:53.823  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 15:29:53.823  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 15:29:53.823  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 15:29:53.823  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c1ce07 added. We now have 10 listener(s)
09-07 15:29:53.823  6970  7226 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 15:29:53.823  6970  7226 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 15:29:53.823  6970  7226 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 15:29:53.823  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 15:29:53.823  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 15:29:53.823  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 15:29:53.823  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-07 15:29:53.833  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,09-07 15:29:53.833  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 15:29:53.833  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-07 15:29:53.833  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-07 15:29:53.833  6970  7226 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-07 15:29:53.833  3212  3226 D BtGatt.GattService: registerClient() - UUID=cbadd9b4-2985-4c4b-91c6-b27a643df10e
,09-07 15:29:53.843   288   288 E SMD     : DCD OFF,
,09-07 15:29:53.863  1017  1128 E WifiNative-wlan0: do suspend true
,09-07 15:29:53.883  3212  3294 D BtGatt.GattService: onClientRegistered() - UUID=cbadd9b4-2985-4c4b-91c6-b27a643df10e, clientIf=6,
09-07 15:29:53.883  6970  6981 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-07 15:29:53.883  3212  7765 D BtGatt.GattService: start scan with filters
09-07 15:29:53.883  3212  3348 D BtGatt.ScanManager: handling starting scan,
,09-07 15:29:53.883  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-07 15:29:53.883  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-07 15:29:53.883  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
09-07 15:29:53.883  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
,09-07 15:29:53.883  3212  3294 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
,09-07 15:29:53.883  3212  3294 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 15:29:53.883  3212  3348 D BtGatt.ScanManager: allow scan with filters
09-07 15:29:53.883  3212  3348 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-07 15:29:53.883  3212  3348 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6
,09-07 15:29:53.883  3212  3294 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-07 15:29:53.883  3212  3294 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 15:29:53.883  3212  3348 D BtGatt.ScanManager: Starting BLE batch scan
09-07 15:29:53.883  3212  3348 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-07 15:29:53.883  6970  7226 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-07 15:29:53.883  6970  7226 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-07 15:29:53.883  6970  6970 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-07 15:29:53.883  3212  3294 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-07 15:29:53.883  3212  3294 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,09-07 15:29:53.893  3212  3294 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-07 15:29:53.893  1017  1127 D WifiP2pService: InactiveState{ what=143375 }
,09-07 15:29:53.893  3212  3294 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 15:29:53.893  1017  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
09-07 15:29:53.893  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 15:29:53.893  1017  1128 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-07 15:29:53.893  1017  1128 E WifiStateMachine: VerifyingLinkState enter
,09-07 15:29:53.903  1017  1130 E ConnectivityService: updateNetworkInfo()
,09-07 15:29:53.903  1017  1130 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
09-07 15:29:53.903  1017  1130 D ConnectivityService: Adding iface wlan0 to network 504
,09-07 15:29:53.913  6970  7226 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
09-07 15:29:53.913  6970  7226 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:29:53.913  6970  7226 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:29:53.913  6970  7226 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 15:29:53.913  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 15:29:53.913  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-07 15:29:53.913  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
09-07 15:29:53.913  6970  7226 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25c3ba2b removed from the list,
09-07 15:29:53.913  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:53.913  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f518e88 removed from the list
09-07 15:29:53.913  6970  7226 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:29:53.913  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
,09-07 15:29:53.913  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-07 15:29:53.913  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 15:29:53.913  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-07 15:29:53.913  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:53.913  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:53.913  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 15:29:53.913  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 15:29:53.923  1017  1145 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
09-07 15:29:53.923  1017  1145 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-07 15:29:53.923  1017  1145 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-07 15:29:53.923  1017  1145 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-07 15:29:53.923  1017  1145 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-07 15:29:53.923  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-07 15:29:53.923  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-07 15:29:53.923  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-07 15:29:53.933  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:53.933  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:53.933  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:53.933  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 15:29:53.933  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:53.933  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-07 15:29:53.933  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:53.933  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 15:29:53.943  1017  3785 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-07 15:29:53.943  1017  3785 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-07 15:29:53.943  1017  1128 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,09-07 15:29:53.943  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:29:53.943  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:29:53.943  1017  3785 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:53.943  1017  3785 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:53.943  1017  3785 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-07 15:29:53.943  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 15:29:53.943  6970  7226 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f518e88 not in the list
,09-07 15:29:53.943  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 15:29:53.943  6970  7226 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 15:29:53.943  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-07 15:29:53.943  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 15:29:53.943  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-07 15:29:53.943  1017  1130 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
09-07 15:29:53.943  1633  1633 I Hs20UtilService: Starting #22
09-07 15:29:53.943  1017  1130 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
09-07 15:29:53.943  1017  1130 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
,09-07 15:29:53.953  4781  4781 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-07 15:29:53.953  3212  3349 D BtGatt.GattService: stopScan() - queue size =1,
,09-07 15:29:53.953  1017  1130 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-07 15:29:53.953  4781  4781 I NearbySettings: MountReceiver.onReceive - Keep current state,
,09-07 15:29:53.953  1017  1130 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
09-07 15:29:53.953  3212  3348 D BtGatt.ScanManager: filter size is 1
09-07 15:29:53.953  1017  1130 D ConnectivityService: LTETest block dns file not exists
09-07 15:29:53.953  3212  3348 D BtGatt.ScanManager: delete FilterIndex - 8
09-07 15:29:53.953  3212  3350 D BtGatt.GattService: unregisterClient() - clientIf=6
09-07 15:29:53.953  1633  1663 I Hs20UtilService: Message received 5007
09-07 15:29:53.953  3212  3294 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-07 15:29:53.953  3212  3294 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 15:29:53.953  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 15:29:53.953  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-07 15:29:53.963  1017  1130 V NetworkStats: updateIfacesLocked()
09-07 15:29:53.953  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-07 15:29:53.963  1017  1130 V NetworkStats: performPollLocked(flags=0x1)
09-07 15:29:53.953  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-07 15:29:53.953  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-07 15:29:53.963  3212  3348 D BtGatt.ScanManager: stopping BLe Batch
,09-07 15:29:53.963  1017  1130 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 15:29:53.963  1017  1130 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-07 15:29:53.963  1017  1130 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-07 15:29:53.963  6970  7226 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 15:29:53.973  3212  3294 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-07 15:29:53.973  3212  3294 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 15:29:53.973  1017  1128 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-07 15:29:53.973  1017  1128 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-07 15:29:53.973  3212  3348 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-07 15:29:53.973  3212  3294 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-07 15:29:53.973  3212  3294 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 15:29:53.973  1017  1130 V NetworkStats: performPollLocked() took 13ms
09-07 15:29:53.973  1017  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 15:29:53.973  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-07 15:29:53.983  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 15:29:53.983  6970  7226 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 15:29:53.983  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-07 15:29:53.983  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-07 15:29:53.983  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-07 15:29:53.983  1017  1017 I WifiTrafficPoller: mBoosterFLAG : 0
09-07 15:29:53.983  1017  1017 I WifiTrafficPoller: current booster mode : FullMode
,09-07 15:29:53.993  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-07 15:29:53.993  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-07 15:29:53.993  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:53.993  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:53.993  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:53.993  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 15:29:53.993  1175  1175 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 15:29:53.993  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-07 15:29:53.993  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 15:29:53.993  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 15:29:53.993  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 15:29:53.993  1017  1130 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
09-07 15:29:53.993  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:53.993  1017  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-07 15:29:53.993  1017  1130 E ConnectivityService: updateNetworkInfo()
09-07 15:29:53.993  1017  1130 V NetworkStats: updateIfacesLocked()
09-07 15:29:53.993  1017  1130 E ConnectivityService: updateNetworkInfo()
,09-07 15:29:53.993  1017  1130 V NetworkStats: performPollLocked(flags=0x1)
09-07 15:29:53.993  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 15:29:53.993  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 15:29:53.993  1017  1130 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 15:29:53.993  1017  1130 D NetworkStatsFactory: UpdateStatsForKnox updated,
09-07 15:29:53.993  1017  1130 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-07 15:29:54.003  1017  1130 V NetworkStats: performPollLocked() took 3ms
09-07 15:29:54.003  1017  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 15:29:54.003  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 15:29:54.003  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 15:29:54.003  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 15:29:54.003  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:29:54.003  1017  1130 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
09-07 15:29:54.003  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:29:54.003  1017  1130 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
09-07 15:29:54.003  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:54.003  6970  6970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 15:29:54.003  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c1ce07 removed from the list
09-07 15:29:54.003  6970  6970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 15:29:54.003  6970  7226 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:29:54.003  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:54.003  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:54.003  6970  6970 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 15:29:54.003  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 15:29:54.003  6970  7226 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e1d5c46 removed from the list
09-07 15:29:54.003  1017  7853 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:29:54.003  1017  7853 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
09-07 15:29:54.003  1017  7853 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-07 15:29:54.003  1017  7853 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
09-07 15:29:54.003  6970  7226 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 15:29:54.003  6970  7226 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26a343a3 added. We now have 2 listener(s)
09-07 15:29:54.003  1017  7853 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-07 15:29:54.003   278   986 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-07 15:29:54.003   278   986 D Netd    : getNetworkForDns: using netid 504 for uid 1000
,09-07 15:29:54.003  1017  1130 D ConnectivityService:    accepting network in place of null
09-07 15:29:54.003  1017  1520 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-07 15:29:54.003  1017  1520 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-07 15:29:54.003  1017  1127 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-07 15:29:54.003  1017  1520 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:54.003  1017  1520 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:54.003  1017  1520 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-07 15:29:54.003  1480  1480 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-07 15:29:54.003  1480  1480 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 15:29:54.003  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-07 15:29:54.003  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 15:29:54.003  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 15:29:54.003  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 15:29:54.003  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2531a6a0 added. We now have 9 listener(s)
09-07 15:29:54.013  1017  1130 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
09-07 15:29:54.003  6970  7226 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 15:29:54.013  1017  1130 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-07 15:29:54.013  1017  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-07 15:29:54.013  1017  1128 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-07 15:29:54.013  1633  1633 I Hs20UtilService: Starting #23
,09-07 15:29:54.013  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 15:29:54.013  4781  4781 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-07 15:29:54.013  4781  4781 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-07 15:29:54.013  1017  1017 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-07 15:29:54.013  1017  1130 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
09-07 15:29:54.013  1017  1131 D Tethering: MasterInitialState.processMessage what=3
09-07 15:29:54.013  1633  1663 I Hs20UtilService: Message received 5007
09-07 15:29:54.013  4781  4781 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED,
09-07 15:29:54.013  1017  1130 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
09-07 15:29:54.013  4781  4781 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-07 15:29:54.013  1017  1046 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-07 15:29:54.013  4781  4781 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false,
09-07 15:29:54.013  4781  4781 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-07 15:29:54.023  1175  1688 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-07 15:29:54.023  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 15:29:54.023  1017  1125 V NetworkStats: updateIfacesLocked()
,09-07 15:29:54.023  1017  1125 V NetworkStats: performPollLocked(flags=0x1)
,09-07 15:29:54.023  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
09-07 15:29:54.023  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-07 15:29:54.023  1175  1175 D StatusBar.NetworkController: EthernetConnected: false
09-07 15:29:54.023  1017  1125 V NetworkStats: performPollLocked() took 4ms
09-07 15:29:54.023  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-07 15:29:54.023  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-07 15:29:54.023  1175  1175 D StatusBar.NetworkController: updateDataNetType()
09-07 15:29:54.023  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 15:29:54.023  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 15:29:54.023  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 15:29:54.023  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 15:29:54.023  1017  1126 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-07 15:29:54.023  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 15:29:54.023  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 15:29:54.023  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-07 15:29:54.023  1175  1175 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-07 15:29:54.033  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 15:29:54.033  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 15:29:54.033  1175  1175 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-07 15:29:54.033  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 24 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
09-07 15:29:54.033  6970  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 15:29:54.033  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:54.033  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:54.033  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:29:54.033  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:29:54.033  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 15:29:54.033  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 15:29:54.033  6970  7226 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 15:29:54.033  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
09-07 15:29:54.033  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
09-07 15:29:54.033  1175  1175 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 15:29:54.033  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-07 15:29:54.033  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:54.033  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:54.033  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 15:29:54.033  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 15:29:54.033  6970  7226 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 15:29:54.033  6970  7226 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 15:29:54.033  6970  7226 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 15:29:54.033  6970  7226 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24b5ae1e added. We now have 3 listener(s)
09-07 15:29:54.033  1017  3796 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-07 15:29:54.033  1017  3796 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-07 15:29:54.033  1017  3796 W ActivityManager: userId = 0, bbcId = -10000
09-07 15:29:54.033  1017  3796 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 15:29:54.033  1017  3796 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-07 15:29:54.033  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:29:54.033  1633  1633 I Hs20UtilService: Starting #24
,09-07 15:29:54.043  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:29:54.043  1633  1663 I Hs20UtilService: Message received 5007
09-07 15:29:54.043  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-07 15:29:54.043  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 15:29:54.043  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 15:29:54.043  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 15:29:54.043  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@59c76ff added. We now have 10 listener(s)
09-07 15:29:54.043  6970  7226 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 15:29:54.043  6970  7226 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 15:29:54.043  6970  7226 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:29:54.043  6970  7226 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:29:54.043  6970  7226 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:29:54.043  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:54.043  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 15:29:54.043  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 15:29:54.043  6970  7226 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26a343a3 removed from the list
09-07 15:29:54.043  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:54.043  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2531a6a0 removed from the list
09-07 15:29:54.043  6970  7226 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:29:54.043  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:54.043  4781  4781 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-07 15:29:54.043  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:54.043  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 15:29:54.043  4781  4781 I NearbySettings: MountReceiver.onReceive - Keep current state
09-07 15:29:54.043  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:29:54.043  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:29:54.043  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:54.043  6970  7226 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2531a6a0 not in the list
09-07 15:29:54.043  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:54.043  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:54.043  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:29:54.043  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:29:54.043  6970  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:29:54.043  6970  7226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@59c76ff removed from the list
09-07 15:29:54.043  6970  7226 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:29:54.043  6970  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:29:54.043  6970  7226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 15:29:54.043  6970  7226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 15:29:54.043  6970  7226 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24b5ae1e removed from the list
09-07 15:29:54.043  6970  7226 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-07 15:29:54.043  6970  7226 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-07 15:29:54.043  6970  7226 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-07 15:29:54.043  6970  7226 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 15:29:54.043  6970  7226 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-07 15:29:54.043  6970  7226 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-07 15:29:54.053  6970  7893 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1428, name: My test thread name)
09-07 15:29:54.053  6970  7893 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1428, thread name: My test thread name)
,09-07 15:29:54.053  6970  7893 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1428, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-07 15:29:54.053  1017  1545 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,09-07 15:29:54.053  1017  1030 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
,09-07 15:29:54.053  1017  1030 D SecContentProvider2: mCursor = null
09-07 15:29:54.053  6970  7894 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1430, name: My test thread name)
09-07 15:29:54.053  6970  7894 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1430, thread name: My test thread name)
09-07 15:29:54.053  6970  7894 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1430, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-07 15:29:54.053  6970  7226 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80,
09-07 15:29:54.053  6970  7226 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
,09-07 15:29:54.053  6970  7226 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-07 15:29:54.053  6970  7226 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,09-07 15:29:54.053  6970  7226 D com.test.thalitest.ThaliTestRunner: Total duration: 23357 ms
09-07 15:29:54.053  6970  7226 I jxcore-log: *Native tests were executed*
09-07 15:29:54.053  6970  7226 I jxcore-log: 
09-07 15:29:54.053  6970  7226 I jxcore-log: Total number of executed tests:  80,
09-07 15:29:54.053  6970  7226 I jxcore-log: 
,09-07 15:29:54.063  6970  7226 I jxcore-log: Number of passed tests:  80
09-07 15:29:54.063  6970  7226 I jxcore-log: 
09-07 15:29:54.063  6970  7226 I jxcore-log: Number of failed tests:  0
09-07 15:29:54.063  6970  7226 I jxcore-log: 
09-07 15:29:54.063  1017  3795 D SecContentProvider2: uri = 15 selection = getToastGravity
09-07 15:29:54.063  1017  3795 D SecContentProvider2: mCursor = null
09-07 15:29:54.063  6970  7226 I jxcore-log: Number of ignored tests:  0
09-07 15:29:54.063  6970  7226 I jxcore-log: 
09-07 15:29:54.063  6970  7226 I jxcore-log: Total duration:  23357
09-07 15:29:54.063  6970  7226 I jxcore-log: 
09-07 15:29:54.063  6970  7226 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-07 15:29:54.063  6970  7226 I jxcore-log: 
09-07 15:29:54.063  1017  1520 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
09-07 15:29:54.063  1017  1520 D SecContentProvider2: mCursor = null
09-07 15:29:54.063  1017  1136 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
09-07 15:29:54.063  1017  1136 D SecContentProvider2: mCursor = null
09-07 15:29:54.063  6970  7226 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:29:54.063  6970  7226 I jxcore-log: 
09-07 15:29:54.063  6970  7226 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:29:54.063  6970  7226 I jxcore-log: 
09-07 15:29:54.063  6970  7226 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:29:54.063  6970  7226 I jxcore-log: 
09-07 15:29:54.063  6970  7226 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:29:54.063  6970  7226 I jxcore-log: 
09-07 15:29:54.063  6970  7226 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:29:54.063  6970  7226 I jxcore-log: 
,09-07 15:29:54.073  6970  7226 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:29:54.073  6970  7226 I jxcore-log: 
09-07 15:29:54.073  6970  6970 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-07 15:29:54.073  1017  3785 D SecContentProvider2: uri = 15 selection = getToastEnabledState
09-07 15:29:54.073  1017  3785 D SecContentProvider2: mCursor = null
09-07 15:29:54.073  6970  7226 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:29:54.073  6970  7226 I jxcore-log: 
09-07 15:29:54.073  1017  3796 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
09-07 15:29:54.073  1017  3796 D SecContentProvider2: mCursor = null
09-07 15:29:54.073  6970  7226 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 15:29:54.073  6970  7226 I jxcore-log: 
09-07 15:29:54.073  6970  7226 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 15:29:54.073  6970  7226 I jxcore-log: 
09-07 15:29:54.073  6970  7226 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 15:29:54.073  6970  7226 I jxcore-log: 
09-07 15:29:54.073  6970  7226 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 15:29:54.073  6970  7226 I jxcore-log: 
09-07 15:29:54.083  6970  7226 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 15:29:54.083  6970  7226 I jxcore-log: 
09-07 15:29:54.083  6970  7226 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 15:29:54.083  6970  7226 I jxcore-log: 
09-07 15:29:54.083  6970  7226 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 15:29:54.083  6970  7226 I jxcore-log: 
09-07 15:29:54.083  6970  7226 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 15:29:54.083  6970  7226 I jxcore-log: 
09-07 15:29:54.083  6970  7226 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 15:29:54.083  6970  7226 I jxcore-log: 
09-07 15:29:54.083  6970  7226 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 15:29:54.083  6970  7226 I jxcore-log: 
09-07 15:29:54.083  6970  7226 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 15:29:54.083  6970  7226 I jxcore-log: 
09-07 15:29:54.083  6970  7226 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 15:29:54.083  6970  7226 I jxcore-log: 
09-07 15:29:54.083  6970  7226 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 15:29:54.083  6970  7226 I jxcore-log: 
09-07 15:29:54.083  6970  7226 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 15:29:54.083  6970  7226 I jxcore-log: 
09-07 15:29:54.083  6970  7226 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 15:29:54.083  6970  7226 I jxcore-log: 
09-07 15:29:54.083  6970  7226 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 15:29:54.083  6970  7226 I jxcore-log: 
09-07 15:29:54.083  6970  7226 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 15:29:54.083  6970  7226 I jxcore-log: 
09-07 15:29:54.083  6970  7226 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 15:29:54.083  6970  7226 I jxcore-log: 
09-07 15:29:54.093  6970  7226 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 15:29:54.093  6970  7226 I jxcore-log: 
09-07 15:29:54.093  6970  7226 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:29:54.093  6970  7226 I jxcore-log: 
,09-07 15:29:54.093   258   258 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,09-07 15:29:54.103  1017  1544 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1017,
,09-07 15:29:54.113  1175  1175 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-07 15:29:54.143  6970  6970 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 15:29:54.153  6970  7226 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 15:29:54.153  6970  7226 I jxcore-log: 
,09-07 15:29:54.293  6970  6970 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
09-07 15:29:54.293  6970  7226 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
09-07 15:29:54.293  6970  7226 I jxcore-log: 
,09-07 15:29:54.393  7896  7896 D AndroidRuntime: 
09-07 15:29:54.393  7896  7896 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-07 15:29:54.393  7896  7896 D AndroidRuntime: CheckJNI is OFF
,09-07 15:29:54.393  7896  7896 D AndroidRuntime: readGMSProperty: start
09-07 15:29:54.393  7896  7896 D AndroidRuntime: readGMSProperty: already setted!!
09-07 15:29:54.393  7896  7896 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-07 15:29:54.393  7896  7896 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-07 15:29:54.393  7896  7896 D AndroidRuntime: readGMSProperty: end
09-07 15:29:54.393  7896  7896 D AndroidRuntime: addProductProperty: start
,09-07 15:29:54.503  6970  6970 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
09-07 15:29:54.503  6970  7226 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 15:29:54.503  6970  7226 I jxcore-log: 
,09-07 15:29:54.513  1017  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,09-07 15:29:54.523  1017  1041 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-07 15:29:54.553  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-07 15:29:54.563  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:54.563  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:54.563  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:54.563  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:54.573  6970  6970 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
09-07 15:29:54.573  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:29:54.573  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:29:54.573  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:29:54.573  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:29:54.573  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 15:29:54.573  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true,
09-07 15:29:54.573  6970  6970 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 15:29:54.573  7896  7896 E AffinityControl: AffinityControl: registerfunction enter,
,09-07 15:29:54.573  6970  6970 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 15:29:54.573  6970  7226 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:29:54.573  6970  7226 I jxcore-log: 
,09-07 15:29:54.593  1017  1042 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7904 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-07 15:29:54.593  7904  7904 E Zygote  : MountEmulatedStorage()
09-07 15:29:54.593  7904  7904 I libpersona: KNOX_SDCARD checking this for 1000
09-07 15:29:54.593  7904  7904 E Zygote  : v2
09-07 15:29:54.593  7904  7904 I libpersona: KNOX_SDCARD not a persona
,09-07 15:29:54.593  7904  7904 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-07 15:29:54.603  7904  7904 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-07 15:29:54.603  7896  7896 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-07 15:29:54.603  7904  7904 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-07 15:29:54.623  1017  1520 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
,09-07 15:29:54.623  1017  1520 D PackageManager: START PACKAGE DELETE: observer{399090840}
09-07 15:29:54.623  1017  1520 D PackageManager: pkg{<packageName>}
09-07 15:29:54.623  1017  1520 D PackageManager: user{0}
09-07 15:29:54.623  1017  1520 D PackageManager: caller{2000}
09-07 15:29:54.623  1017  1520 D PackageManager: flags{2}
09-07 15:29:54.623  1017  1520 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-07 15:29:54.623  1017  1520 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,09-07 15:29:54.623  1017  1520 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-07 15:29:54.623  1017  1520 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,09-07 15:29:54.623  7904  7904 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 15:29:54.623  7904  7904 D ActivityThread: Added TimaKeyStore provider
,09-07 15:29:54.633  1017  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0,
09-07 15:29:54.633  1017  1057 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-07 15:29:54.633  1017  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1,
09-07 15:29:54.633  1017  1057 D ApplicationPolicy: getApplicationUninstallationEnabled
09-07 15:29:54.633  1017  1057 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-07 15:29:54.633  1017  1057 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
,09-07 15:29:54.663  1017  1042 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
,09-07 15:29:54.663  1017  1042 I ActivityManager: Killing 6970:com.test.thalitest/u0a170 (adj 0): stop com.test.thalitest cause uninstall pkg
,09-07 15:29:54.773   258   449 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
,09-07 15:29:54.773  1017  1255 I WindowState: WIN DEATH: Window{1c558701 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-07 15:29:54.773   258   445 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,09-07 15:29:54.773  1017  1255 D InputDispatcher: Focus left window: 6970,
,09-07 15:29:54.803  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
09-07 15:29:54.803  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-07 15:29:54.813  1017  1042 I ActivityManager:   Force finishing activity ActivityRecord{2aebb6d4 u0 com.test.thalitest/.MainActivity t163},
,09-07 15:29:54.823  7904  7904 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true,
09-07 15:29:54.823  7904  7904 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
09-07 15:29:54.823  7904  7904 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-07 15:29:54.823  1017  3786 W ActivityManager: Spurious death for ProcessRecord{369194f1 6970:com.test.thalitest/u0a170}, curProc for 6970: null
,09-07 15:29:54.843  1017  1042 D InputDispatcher: Focused application released
,09-07 15:29:54.843  1017  1057 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,09-07 15:29:54.863  1017  1057 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,09-07 15:29:54.893  7904  7904 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-07 15:29:54.893  7904  7904 I PCWCLIENTTRACE_PushUtil: sales region : global
,09-07 15:29:54.893  7904  7904 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-07 15:29:54.893  7904  7904 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-07 15:29:54.893  2829  2829 I art     : Explicit concurrent mark sweep GC freed 16591(990KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 844us total 32.646ms
,09-07 15:29:54.913  1755  1995 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-07 15:29:54.913  1882  1882 E SamsungIME: mOCRHelper is null
,09-07 15:29:54.923  1017  1099 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-07 15:29:54.953  1017  1125 V NetworkStats: removeUidsLocked() for UIDs [10170]
,09-07 15:29:54.953  1017  1125 V NetworkStats: performPollLocked(flags=0x3)
,09-07 15:29:54.953  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 15:29:54.963  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
09-07 15:29:54.963  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-07 15:29:54.963  1017  1546 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
,09-07 15:29:54.963  1017  1546 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
09-07 15:29:54.963  1017  1546 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
,09-07 15:29:54.963  1017  1546 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,09-07 15:29:54.973  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 15:29:54.973  1017  1125 V NetworkStats: performPollLocked() took 17ms
09-07 15:29:54.973  1463  1463 D PersonaManager: isKioskContainerExistOnDevice
,09-07 15:29:54.973  1017  1546 I ActivityManager: Killing 7411:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,09-07 15:29:54.973  1463  1463 D RegisteredServicesCache: empty dynamic service
,09-07 15:29:55.003  1463  1463 D RegisteredComponentCache: Collect Tech packages for Knox
,09-07 15:29:55.003  1463  1463 D PersonaManager: isKioskContainerExistOnDevice
,09-07 15:29:55.013  1017  1095 V AlarmManager: waitForAlarm result :4
,09-07 15:29:55.023  1017  1041 D EnterpriseDeviceManagerService: Package has changed for user 0
09-07 15:29:55.023  1017  1041 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,09-07 15:29:55.023  1017  1041 W TextServicesManagerService: no available spell checker services found
,09-07 15:29:55.023  1017  1130 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,09-07 15:29:55.023  1017  1501 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,09-07 15:29:55.023  1017  1501 D SecContentProvider2: mCursor = null
,09-07 15:29:55.033  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 15:29:55.033  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 15:29:55.043  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-07 15:29:55.043  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-07 15:29:55.053  1017  1049 I PowerManagerService: [PWL] Off : 75s ago
,09-07 15:29:55.053  1017  1049 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
09-07 15:29:55.053  1017  1049 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
09-07 15:29:55.053  1017  1049 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=1017, ws=WorkSource{10011 com.google.android.gms}) (elapsedTime=43)
,09-07 15:29:55.063  1017  1017 I art     : Explicit concurrent mark sweep GC freed 65882(4MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 23MB/34MB, paused 3.034ms total 199.974ms
,09-07 15:29:55.063  1017  1057 I art     : WaitForGcToComplete blocked for 131.876ms for cause Explicit
,09-07 15:29:55.073  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-07 15:29:55.083  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-07 15:29:55.153  1017  1328 E Watchdog: !@Sync 4
,09-07 15:29:55.163  1017  1041 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,09-07 15:29:55.163  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-07 15:29:55.163  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-07 15:29:55.193  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-07 15:29:55.213  1017  1017 D RCPManagerService: PackageReceiver onReceive()
,09-07 15:29:55.213  1017  1017 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,09-07 15:29:55.213  1017  1057 I art     : Explicit concurrent mark sweep GC freed 10734(499KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 4.226ms total 149.185ms
,09-07 15:29:55.213  1017  1017 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,09-07 15:29:55.223  1017  1017 I OTPFW   : PackageRemovalReceiver::onReceive Enter
,09-07 15:29:55.223  1017  1017 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,09-07 15:29:55.233  1017  1041 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-07 15:29:55.233  1017  1017 I OTPFW   : ProvisionData::getAllEntries Enter
,09-07 15:29:55.233  1017  1041 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-07 15:29:55.233  1017  1041 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-07 15:29:55.233  1017  1017 E OTPFW   : ProvisionData::getAllEntries Table is empty
,09-07 15:29:55.253  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-07 15:29:55.263  1017  1057 D PackageManager: delete codoeFile: 
,09-07 15:29:55.273  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-07 15:29:55.273  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-07 15:29:55.273  1017  1057 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
09-07 15:29:55.273  1017  1057 I AASA_removePackage: UID=10170 Target=com.test.thalitest
09-07 15:29:55.283  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-07 15:29:55.283  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
09-07 15:29:55.283  1017  1057 D PackageManager: result of delete: 1{399090840}
,09-07 15:29:55.283  7896  7896 D AndroidRuntime: Shutting down VM
,09-07 15:29:55.283  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-07 15:29:55.283  1017  1057 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-07 15:29:55.283  1017  1057 D PackageManager: userId{-1}
09-07 15:29:55.283  1017  1057 D PackageManager: andCode{true}
,09-07 15:29:55.283  1017  1057 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,09-07 15:29:55.283  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-07 15:29:55.293  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-07 15:29:55.293  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:55.293  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:55.293  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:55.293  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:55.293  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-07 15:29:55.293  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
09-07 15:29:55.293  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-07 15:29:55.303  7923  7923 E Zygote  : MountEmulatedStorage()
09-07 15:29:55.303  7923  7923 E Zygote  : v2
09-07 15:29:55.303  7923  7923 I libpersona: KNOX_SDCARD checking this for 10003
09-07 15:29:55.303  7923  7923 I libpersona: KNOX_SDCARD not a persona
,09-07 15:29:55.303  1017  1057 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7923 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a,
09-07 15:29:55.303  7923  7923 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 15:29:55.303  1017  1041 D UsbSettingsManager: clearDefaults: com.test.thalitest
,09-07 15:29:55.303  1017  1041 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,09-07 15:29:55.303  7923  7923 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 15:29:55.313  7923  7923 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 15:29:55.313  1017  1017 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,09-07 15:29:55.313  1017  1017 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-07 15:29:55.323  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
09-07 15:29:55.323  1017  1017 V EnterpriseBillingPolicy: uID is 10170
09-07 15:29:55.323  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
09-07 15:29:55.323  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-07 15:29:55.323  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-07 15:29:55.323  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-07 15:29:55.323  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-07 15:29:55.323  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
09-07 15:29:55.323  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-07 15:29:55.323  1017  1017 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-07 15:29:55.323  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
09-07 15:29:55.323  1017  1017 V EnterpriseBillingPolicy: uID is 10170
09-07 15:29:55.323  1017  3359 D SSRM:bc : MSG_TYPE_APP_REMOVED::
09-07 15:29:55.323  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
09-07 15:29:55.323  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-07 15:29:55.323  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-07 15:29:55.323  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-07 15:29:55.323  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
,09-07 15:29:55.323  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
09-07 15:29:55.323  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
09-07 15:29:55.323  1017  1162 D TaskPersister: removeObsoleteFile: deleting file=163_task.xml,
,09-07 15:29:55.333  1017  1017 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
,09-07 15:29:55.333  7923  7923 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 15:29:55.333  7923  7923 D ActivityThread: Added TimaKeyStore provider
,09-07 15:29:55.373  1017  1503 I ActivityManager: Killing 7429:com.sec.android.diagmonagent/1000 (adj 15): empty #21
,09-07 15:29:55.403  1017  1017 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,09-07 15:29:55.413  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:55.413  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:55.413  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:55.413  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:55.423  7939  7939 E Zygote  : MountEmulatedStorage(),
09-07 15:29:55.423  1017  1017 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7939 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-07 15:29:55.423  7939  7939 E Zygote  : v2,
09-07 15:29:55.423  7939  7939 I libpersona: KNOX_SDCARD checking this for 10001
09-07 15:29:55.423  7939  7939 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-07 15:29:55.423  7939  7939 I libpersona: KNOX_SDCARD not a persona
,09-07 15:29:55.423  7939  7939 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-07 15:29:55.423  7939  7939 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 15:29:55.443  7939  7939 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 15:29:55.443  7939  7939 D ActivityThread: Added TimaKeyStore provider
,09-07 15:29:55.483  1017  3796 I ActivityManager: Killing 7444:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,09-07 15:29:55.483  1017  3796 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-07 15:29:55.493  7896  7896 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-07 15:29:55.493  1017  3796 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.sec.android.diagmonagent/com.sec.android.diagmonagent.DiagMonRegistrationReceiver}
09-07 15:29:55.493  1017  3796 W BroadcastQueue: android.os.TransactionTooLargeException
09-07 15:29:55.493  1017  3796 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-07 15:29:55.493  1017  3796 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
09-07 15:29:55.493  1017  3796 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
09-07 15:29:55.493  1017  3796 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
09-07 15:29:55.493  1017  3796 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
09-07 15:29:55.493  1017  3796 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
09-07 15:29:55.493  1017  3796 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
09-07 15:29:55.493  1017  3796 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
09-07 15:29:55.493  1017  3796 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
09-07 15:29:55.493  1017  3796 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,09-07 15:29:55.493  1017  3796 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-07 15:29:55.493  1017  3796 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:55.493  1017  3796 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 15:29:55.493  1017  3796 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 15:29:55.503  1017  3796 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7956 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-07 15:29:55.513  7956  7956 E Zygote  : MountEmulatedStorage(),
09-07 15:29:55.513  7956  7956 E Zygote  : v2
09-07 15:29:55.513  7956  7956 I libpersona: KNOX_SDCARD checking this for 1000
,09-07 15:29:55.513  7956  7956 I libpersona: KNOX_SDCARD not a persona
09-07 15:29:55.513  7956  7956 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 15:29:55.513  7956  7956 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 15:29:55.513  7956  7956 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 15:29:55.533  7956  7956 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 15:29:55.533  7956  7956 D ActivityThread: Added TimaKeyStore provider
,09-07 15:29:55.583  3212  3292 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-07 15:29:55.583  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_7429/cgroup.procs: No such file or directory
,09-07 15:29:55.583  7956  7956 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,09-07 15:29:55.593  7956  7956 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
,09-07 15:29:55.593  7956  7956 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
09-07 15:29:55.593  7956  7956 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 15:29:55.593  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 15:29:55.593  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-07 15:29:55.593  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-07 15:29:55.593  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-07 15:29:55.593  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-07 15:29:55.593  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-07 15:29:55.593  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-07 15:29:55.593  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-07 15:29:55.593  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-07 15:29:55.593  7956  7956 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-07 15:29:55.593  7956  7956 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-07 15:29:55.593  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 15:29:55.593  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-07 15:29:55.593  7956  7956 E SQLiteDatabase: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
09-07 15:29:55.593  7956  7956 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
09-07 15:29:55.593  7956  7956 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
09-07 15:29:55.593  7956  7956 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
09-07 15:29:55.593  7956  7956 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-07 15:29:55.593  7956  7956 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-07 15:29:55.593  7956  7956 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 15:29:55.593  7956  7956 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 15:29:55.593  7956  7956 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 15:29:55.593  7956  7956 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 15:29:55.593  7956  7956 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:29:55.593  7956  7956 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-07 15:29:55.593  7956  7956 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 15:29:55.593  7956  7956 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:29:55.593  7956  7956 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 15:29:55.593  7956  7956 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 15:29:55.593  7956  7956 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-07 15:29:55.593  7956  7956 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
09-07 15:29:55.593  7956  7956 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 15:29:55.593  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 15:29:55.593  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-07 15:29:55.593  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-07 15:29:55.593  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-07 15:29:55.593  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-07 15:29:55.593  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-07 15:29:55.593  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-07 15:29:55.593  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-07 15:29:55.593  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-07 15:29:55.593  7956  7956 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-07 15:29:55.593  7956  7956 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-07 15:29:55.593  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 15:29:55.593  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-07 15:29:55.593  7956  7956 E SQLiteOpenHelper: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
09-07 15:29:55.593  7956  7956 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
09-07 15:29:55.593  7956  7956 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
09-07 15:29:55.593  7956  7956 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
09-07 15:29:55.593  7956  7956 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-07 15:29:55.593  7956  7956 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-07 15:29:55.593  7956  7956 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 15:29:55.593  7956  7956 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 15:29:55.593  7956  7956 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 15:29:55.593  7956  7956 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 15:29:55.593  7956  7956 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:29:55.593  7956  7956 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
09-07 15:29:55.593  7956  7956 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 15:29:55.593  7956  7956 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:29:55.593  7956  7956 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 15:29:55.593  7956  7956 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 15:29:55.593  7956  7956 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-07 15:29:55.593  7956  7956 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
,09-07 15:29:55.593  7956  7956 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
,09-07 15:29:55.603  7956  7956 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-07 15:29:55.603  7956  7956 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
,09-07 15:29:55.603  7956  7956 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
,09-07 15:29:55.603  7956  7956 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.,
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178),
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
,09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97),
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:345)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:389)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55),
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	,at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145),
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 15:29:55.603  7956  7956 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: ,	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178),
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519),
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelp,er: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:345)
,09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:389)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
,09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: ,	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
,09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 15:29:55.603  7956  7956 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 15:29:55.603  7956  7956 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode,
09-07 15:29:55.603  7956  7956 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
,09-07 15:29:55.613  7956  7956 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908),
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: ,	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
,09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:345)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: ,	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:389)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	,at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145),
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194),
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178),
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	,at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	,at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:345)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:389)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	,at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: ,	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145),
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: ,	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 15:29:55.613  7956  7956 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
,09-07 15:29:55.613  7956  7956 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
,09-07 15:29:55.613  7956  7956 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
,09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
,09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: ,	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: ,	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	,at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	,at java.lang.reflect.Method.invoke(Native Method)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194),
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):,
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
,09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
,09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-07 15:29:55.613  7956  7956 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
09-07 15:29:55.613  7956  7956 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.j,ava:1399)
09-07 15:29:55.613  7956  7956 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 15:29:55.613  7956  7956 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteIn,it.java:1194)
09-07 15:29:55.613  7956  7956 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
09-07 15:29:55.623  7956  7956 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:345)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:389)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:345)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:389)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 15:29:55.623  7956  7956 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
09-07 15:29:55.623  7956  7956 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:345)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:389)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 15:29:55.623  7956  7956 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:345)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:389)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 15:29:55.623  7956  7956 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 15:29:55.623  7956  7956 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
09-07 15:29:55.623  7956  7956 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 15:29:55.633  7956  7956 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
09-07 15:29:55.633  7956  7956 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 15:29:55.633  7956  7956 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 15:29:55.633  7956  7956 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
09-07 15:29:55.633  7956  7956 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-07 15:29:55.633  7956  7956 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
```
