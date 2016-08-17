#### Test 808075738e7a0be_thali03_samsung-SM-A500FU Logs


```
--------- beginning of system
08-17 19:16:20.595  1012  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:20.595  1012  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:20.595  1012  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:20.595  1012  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
--------- beginning of main
08-17 19:16:20.605  6261  6261 E Zygote  : MountEmulatedStorage()
08-17 19:16:20.605  6261  6261 E Zygote  : v2
08-17 19:16:20.605  6261  6261 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-17 19:16:20.605  6261  6261 I libpersona: KNOX_SDCARD checking this for 10012
08-17 19:16:20.605  6261  6261 I libpersona: KNOX_SDCARD not a persona
08-17 19:16:20.615  6261  6261 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-17 19:16:20.615  6261  6261 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-17 19:16:20.615  1012  1221 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6261 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
08-17 19:16:20.645  6261  6261 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 19:16:20.645  6261  6261 D ActivityThread: Added TimaKeyStore provider
08-17 19:16:20.645   303   303 I art     : Explicit concurrent mark sweep GC freed 8717(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 792us total 37.484ms
08-17 19:16:20.675   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 731us total 21.073ms
08-17 19:16:20.675  6261  6261 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-17 19:16:20.675  6261  6261 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-17 19:16:20.695   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.129ms total 20.941ms
08-17 19:16:20.725  6261  6261 I MultiDex: VM with version 2.1.0 has multidex support
08-17 19:16:20.725  6261  6261 I MultiDex: install
08-17 19:16:20.725  6261  6261 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-17 19:16:20.765  6261  6261 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
08-17 19:16:20.825  1012  1092 V AlarmManager: waitForAlarm result :4
08-17 19:16:20.825  6261  6261 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-17 19:16:20.825  6261  6261 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@e4fc136: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-17 19:16:20.835  6261  6261 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
08-17 19:16:20.855  1012  1540 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
08-17 19:16:20.855  6261  6261 D ChimeraCfgMgr: Reading stored module config
08-17 19:16:20.865  1012  1024 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-17 19:16:20.865  1012  1024 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:20.865  1012  1024 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:20.865  1012  1024 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-17 19:16:20.875  1012  1478 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-17 19:16:20.875  1012  1478 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:20.875  1012  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:20.875  1012  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-17 19:16:20.945  6261  6283 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
08-17 19:16:20.955  6278  6278 D AndroidRuntime: 
08-17 19:16:20.955  6278  6278 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-17 19:16:20.955  6278  6278 D AndroidRuntime: CheckJNI is OFF
08-17 19:16:20.955  6278  6278 D AndroidRuntime: readGMSProperty: start
08-17 19:16:20.955  6278  6278 D AndroidRuntime: readGMSProperty: already setted!!
08-17 19:16:20.955  6278  6278 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-17 19:16:20.955  6278  6278 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-17 19:16:20.955  6278  6278 D AndroidRuntime: readGMSProperty: end
08-17 19:16:20.955  6278  6278 D AndroidRuntime: addProductProperty: start
08-17 19:16:20.965  1906  2113 I art     : Explicit concurrent mark sweep GC freed 65838(3MB) AllocSpace objects, 13(448KB) LOS objects, 40% free, 14MB/23MB, paused 1.533ms total 78.850ms
08-17 19:16:20.975  6261  6261 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
08-17 19:16:20.975  6261  6261 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
08-17 19:16:20.995  1906  1906 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=8e99e691-678d-4118-8e03-f7d5285b5278
08-17 19:16:21.005  1012  2929 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-17 19:16:21.005  1012  2929 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
08-17 19:16:21.005  1012  2929 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:21.005  1012  2929 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:21.005  1012  2929 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-17 19:16:21.045  1906  1906 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
08-17 19:16:21.045  1906  1906 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
08-17 19:16:21.065  1012  1478 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-17 19:16:21.065  1012  1478 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:21.065  1012  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:21.065  1012  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-17 19:16:21.065   282   691 D WVCdm   : Instantiating CDM.
08-17 19:16:21.075   282   684 I WVCdm   : CdmEngine::OpenSession
08-17 19:16:21.075   282   684 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
08-17 19:16:21.095   282   684 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
08-17 19:16:21.105  6278  6278 E AffinityControl: AffinityControl: registerfunction enter
08-17 19:16:21.115   282   684 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
08-17 19:16:21.115   282   684 D DrmWidevineDash: Service_Initialize: starts!
08-17 19:16:21.115   282   684 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-17 19:16:21.115   282   684 D QSEECOMAPI: : App is not loaded in QSEE
08-17 19:16:21.115   282   684 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
08-17 19:16:21.115   282   684 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-17 19:16:21.115   282   684 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-17 19:16:21.115   282   684 D QSEECOMAPI: : App is not loaded in QSEE
08-17 19:16:21.115   282   684 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
08-17 19:16:21.125   282   684 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-17 19:16:21.125   282   684 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-17 19:16:21.125   282   684 D QSEECOMAPI: : App is not loaded in QSEE
08-17 19:16:21.125  6278  6278 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-17 19:16:21.145   282   684 D QSEECOMAPI: : Loaded image: APP id = 11
08-17 19:16:21.145  1012  1541 E PersonaManagerService: inState():  stateMachine is null !!
08-17 19:16:21.145  1012  1541 I PersonaManagerService: PersonaId don't exist
08-17 19:16:21.145  1012  1541 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-17 19:16:21.145   282   684 D DrmWidevineDash: Service_Initialize: ends! returns 0
08-17 19:16:21.145  1012  1541 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-17 19:16:21.145   282   684 D QSAPPSVER: qsapps_get_capabilities: Capability from secure side: 0x0
08-17 19:16:21.145   282   684 D QSAPPSVER: qsapps_get_capabilities: returns 0
08-17 19:16:21.145   282   684 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1444000
08-17 19:16:21.145   282   684 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1444000
08-17 19:16:21.145   282   684 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-17 19:16:21.155   419   428 D DrmLibTime: got the req here! ret=0
08-17 19:16:21.155   419   428 D DrmLibTime: command id, time_cmd_id = 770
08-17 19:16:21.155   419   428 D DrmLibTime: time_getutcsec starts!
08-17 19:16:21.155   419   428 D DrmLibTime: QSEE Time Listener: time_getutcsec
08-17 19:16:21.155   419   428 D DrmLibTime: QSEE Time Listener: get_utc_seconds
08-17 19:16:21.155   419   428 D DrmLibTime: QSEE Time Listener: time_get_modem_time
08-17 19:16:21.155   419   428 D DrmLibTime: QSEE Time Listener: Checking if ATS_MODEM is set or not.
08-17 19:16:21.165   419   428 D QC-time-services: Lib:time_genoff_operation: pargs->base = 13
08-17 19:16:21.165   419   428 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 2
08-17 19:16:21.165   419   428 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 0
08-17 19:16:21.165   419   428 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
08-17 19:16:21.165   317   555 D QC-time-services: Daemon: Connection accepted:time_genoff
08-17 19:16:21.165   317  6296 D QC-time-services: Daemon:Received base = 13, unit = 1, operation = 2,value = 0
08-17 19:16:21.165   317  6296 D QC-time-services: Daemon:genoff_opr: Base = 13, val = 0, operation = 2
08-17 19:16:21.165   317  6296 D QC-time-services: offset is: 0 for base: 0
08-17 19:16:21.165   419   428 E QC-time-services: Receive Passed == base = 13, unit = 1, operation = 2, result = 0
08-17 19:16:21.165   419   428 D DrmLibTime: QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
08-17 19:16:21.165   419   428 D DrmLibTime: QSEE Time Listener: Retrieved Android system time: 1471454181
08-17 19:16:21.165   419   428 D DrmLibTime: time_getutcsec returns 0, sec = 1471454181; nsec = 0
08-17 19:16:21.165   419   428 D DrmLibTime: time_getutcsec finished! 
08-17 19:16:21.165   419   428 D DrmLibTime: iotcl_continue_command finished! and return 0 
08-17 19:16:21.165   419   428 D DrmLibTime: before calling ioctl to read the next time_cmd
08-17 19:16:21.165   317   555 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
08-17 19:16:21.165   282   684 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-17 19:16:21.165  1012  1541 W ActivityManager: mDVFSHelper.acquire()
08-17 19:16:21.165   282   684 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
08-17 19:16:21.165   282   684 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
08-17 19:16:21.165   282   684 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-17 19:16:21.165  1012  1541 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:21.165   282   684 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-17 19:16:21.165  1012  1541 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:21.165   282   684 D DrmWidevineDash: hlos api version =  9
08-17 19:16:21.165  1012  1541 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:21.165   282   684 D DrmWidevineDash: tz api version =  9
08-17 19:16:21.165  1012  1541 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:21.165   282   684 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
08-17 19:16:21.165   282   684 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
08-17 19:16:21.165   282   684 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-17 19:16:21.175  1012  1042 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-17 19:16:21.175  1012  1042 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-17 19:16:21.185  6298  6298 E Zygote  : MountEmulatedStorage()
08-17 19:16:21.185  6298  6298 E Zygote  : v2
08-17 19:16:21.185  6298  6298 I libpersona: KNOX_SDCARD checking this for 10155
08-17 19:16:21.185  6298  6298 I libpersona: KNOX_SDCARD not a persona
08-17 19:16:21.185  6298  6298 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-17 19:16:21.185  1012  1541 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
08-17 19:16:21.185  1012  1541 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6298 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-17 19:16:21.185  1012  1541 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-17 19:16:21.185  1012  1541 D InputDispatcher: Focused application set to: xxxx
08-17 19:16:21.185  1012  1541 D InputDispatcher: Focus left window: 3144
08-17 19:16:21.195  6278  6278 D AndroidRuntime: Shutting down VM
08-17 19:16:21.195  6298  6298 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-17 19:16:21.195  1012  1042 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-17 19:16:21.195  1012  1042 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-17 19:16:21.195  6298  6298 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-17 19:16:21.195   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, uhalitest
08-17 19:16:21.205   282   684 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-17 19:16:21.205   282   684 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
08-17 19:16:21.205   282   684 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
08-17 19:16:21.205   282   684 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb1946960
08-17 19:16:21.205   282   684 D DrmWidevineDash: OEMCrypto_OpenSession Session ID = 0
08-17 19:16:21.205   282   684 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-17 19:16:21.205   282   684 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-17 19:16:21.205   282   684 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
08-17 19:16:21.205   282   684 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
08-17 19:16:21.205   282   684 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb7c71e80, dataLength=8
08-17 19:16:21.205   282   684 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-17 19:16:21.205   282   684 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-17 19:16:21.205   282   684 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
08-17 19:16:21.205   282   684 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xb7c05f58, wrapped_rsa_key_length=1280
08-17 19:16:21.205   282   684 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-17 19:16:21.215   282   684 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-17 19:16:21.215   282   684 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
08-17 19:16:21.215   282   684 I WVCdm   : CdmEngine::QueryKeyControlInfo
08-17 19:16:21.215  1012  1042 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-17 19:16:21.215  1012  1042 D PointerIcon: setMouseCustomIcon IconType is same.101
08-17 19:16:21.215   282  1072 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
08-17 19:16:21.215   282  1072 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-17 19:16:21.215   282  1072 I WVCdm   : CdmEngine::GenerateKeyRequest
08-17 19:16:21.215   282  1072 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb7c031c8, idLength=0xb174a730
08-17 19:16:21.215   282  1072 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-17 19:16:21.235  6298  6298 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 19:16:21.235  6298  6298 D ActivityThread: Added TimaKeyStore provider
08-17 19:16:21.245   282  1072 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-17 19:16:21.245   282  1072 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
08-17 19:16:21.245   282  1072 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
08-17 19:16:21.245   282  1072 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-17 19:16:21.245   282  1072 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-17 19:16:21.245   282  1072 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
08-17 19:16:21.245   282  1072 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 24
08-17 19:16:21.245   282  1072 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0
08-17 19:16:21.245   282  1072 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!, current = 0xb174a746, maximum = 0xb174a747
08-17 19:16:21.245   282  1072 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-17 19:16:21.245   282  1072 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-17 19:16:21.245   282  1072 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0
08-17 19:16:21.245   282  1072 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
08-17 19:16:21.245   282  1072 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-17 19:16:21.245   282  1072 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-17 19:16:21.245   282  1072 D DrmWidevineDash: hlos api version =  9
08-17 19:16:21.245   282  1072 D DrmWidevineDash: tz api version =  9
08-17 19:16:21.245   282  1072 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
08-17 19:16:21.245   282  1072 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xb174a7b4
08-17 19:16:21.245   282  1072 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-17 19:16:21.245   282  1072 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-17 19:16:21.245   282  1072 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
08-17 19:16:21.245   282  1072 D WVCdm   : PrepareKeyRequest: nonce=2046683273
08-17 19:16:21.245  1012  1040 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-17 19:16:21.245   282  1072 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7c2b600
08-17 19:16:21.245   282  1072 D DrmWidevineDash: message_length=1599, signature=0xb7c2b2b8, signature_length=0xb174a714
08-17 19:16:21.245   282  1072 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-17 19:16:21.255  1012  1074 D PersonaManager: isKioskContainerExistOnDevice
08-17 19:16:21.265  1650  2131 I art     : Explicit concurrent mark sweep GC freed 1378(47KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 773us total 34.594ms
08-17 19:16:21.285  6261  6270 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
08-17 19:16:21.285  6261  6270 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-17 19:16:21.295  6261  6270 I System.out: (HTTPLog)-Static: isShipBuild true
08-17 19:16:21.295  6261  6270 I System.out: (HTTPLog)-Thread-1048-658474827: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-17 19:16:21.295  6261  6270 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-17 19:16:21.295   277   958 D EnterpriseController: uids 10012
08-17 19:16:21.295   277   958 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-17 19:16:21.295   277   958 D Netd    : getNetworkForDns: using netid 502 for uid 10012
08-17 19:16:21.295  6261  6270 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-17 19:16:21.295  6261  6270 I qtaguid : Tagging socket 33 with tag 1000180300000000{268441603,0} for uid -1, pid: 6261, getuid(): 10012
08-17 19:16:21.385  1906  2106 W GCoreFlp: No location to return for getLastLocation()
08-17 19:16:21.385  6298  6298 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
08-17 19:16:21.405  6278  6278 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
08-17 19:16:21.415  6298  6298 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 1667-1670)
08-17 19:16:21.415  6298  6298 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-17 19:16:21.415   282  1072 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-17 19:16:21.415   282  1072 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
08-17 19:16:21.415   282   691 I WVCdm   : CdmEngine::CloseSession
08-17 19:16:21.415   282   691 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
08-17 19:16:21.415   282   691 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-17 19:16:21.415   282   691 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-17 19:16:21.415   282   691 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
08-17 19:16:21.415   282   691 I WVCdm   : L3 Terminate.
08-17 19:16:21.415   282   691 D DrmWidevineDash: OEMCrypto_Terminate: starts!
08-17 19:16:21.415   282   691 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-17 19:16:21.415   282   691 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-17 19:16:21.415   282   691 D DrmWidevineDash: Service_Uninitialize: starts!
08-17 19:16:21.415   282   691 D QSEECOMAPI: : QSEECom_dealloc_memory 
08-17 19:16:21.415   282   691 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 11
08-17 19:16:21.415   282   691 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
08-17 19:16:21.415   282   691 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
08-17 19:16:21.445   257   435 I SurfaceFlinger: id=11 Removed YUIInstallC (5/9)
08-17 19:16:21.445   257   435 I SurfaceFlinger: id=11 Removed YUIInstallC (-2/9)
08-17 19:16:21.445  3144  3144 V ActivityThread: updateVisibility : ActivityRecord{7bdc3f9 token=android.os.BinderProxy@2565f204 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
08-17 19:16:21.455  1012  1474 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-17 19:16:21.455  1012  1474 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:21.455  1012  1474 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:21.455  1012  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-17 19:16:21.455  6298  6298 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {34793505}
08-17 19:16:21.455  6298  6298 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-17 19:16:21.455  6298  6298 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
08-17 19:16:21.455  1012  1497 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-17 19:16:21.455  1012  1497 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:21.455  1012  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:21.455  1012  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-17 19:16:21.455  1906  2110 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-17 19:16:21.465  3821  6255 D UdcContextInitService: registered all accounts: true
08-17 19:16:21.465  1012  1474 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-17 19:16:21.465  1012  1474 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:21.465  1012  1474 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:21.465  1012  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-17 19:16:21.475   287   287 E SMD     : DCD OFF
08-17 19:16:21.485  1906  2130 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
08-17 19:16:21.495  6298  6298 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-17 19:16:21.495  6298  6298 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-17 19:16:21.495  6298  6298 E SysUtils: ApplicationContext is null in ApplicationStatus
08-17 19:16:21.525  6298  6298 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
08-17 19:16:21.525  6298  6298 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
08-17 19:16:21.525  6298  6298 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
08-17 19:16:21.525  6298  6298 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-17 19:16:21.525  6298  6298 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-17 19:16:21.525  6298  6298 I Adreno-EGL: Build Date: 04/06/15 Mon
08-17 19:16:21.525  6298  6298 I Adreno-EGL: Local Branch: 
08-17 19:16:21.525  6298  6298 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-17 19:16:21.525  6298  6298 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-17 19:16:21.525  6298  6298 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
08-17 19:16:21.585  6261  6270 I qtaguid : Untagging socket 33
08-17 19:16:21.675  1012  2930 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-17 19:16:21.685  1012  2930 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
08-17 19:16:21.685  1012  2930 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:21.685  1012  2930 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:21.685  1012  2930 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-17 19:16:21.705  6298  6331 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
08-17 19:16:21.755  6298  6298 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-17 19:16:21.755  1012  1478 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-17 19:16:21.755  1012  1478 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
08-17 19:16:21.755  1012  1478 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:21.755  1012  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:21.755  1012  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-17 19:16:21.765  1906  2130 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-17 19:16:21.765  1012  1037 W ActivityManager: Activity pause timeout for ActivityRecord{39f08555 u0 com.test.thalitest/.MainActivity t129}
08-17 19:16:21.765   277   958 D EnterpriseController: uids 10012
08-17 19:16:21.765   277   958 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-17 19:16:21.765   277   958 D Netd    : getNetworkForDns: using netid 502 for uid 10012
08-17 19:16:21.775  1906  2130 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-17 19:16:21.775  1906  2130 I qtaguid : Tagging socket 65 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1906, getuid(): 10012
08-17 19:16:21.775  6298  6298 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-17 19:16:21.785  6298  6298 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-17 19:16:21.785  6298  6298 D PhoneWindow: *FMB* installDecor flags : -2139027200
08-17 19:16:21.795  6298  6298 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
08-17 19:16:21.805  6298  6298 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-17 19:16:21.805  6298  6298 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-17 19:16:21.815  1906  2130 I qtaguid : Tagging socket 68 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1906, getuid(): 10012
08-17 19:16:21.855  6298  6346 D OpenGLRenderer: Render dirty regions requested: true
08-17 19:16:21.855  1012  1025 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-17 19:16:21.855  1012  1025 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-17 19:16:21.855  1012  1025 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-17 19:16:21.855  1012  1012 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-17 19:16:21.865  1012  1012 D PersonaManagerService: getPersonasForUser(): returning null!
08-17 19:16:21.865  6298  6298 V ActivityThread: updateVisibility : ActivityRecord{94b6144 token=android.os.BinderProxy@5639fd6 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-17 19:16:21.875  6298  6298 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-17 19:16:21.875  6298  6298 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-17 19:16:21.875   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, NainActivit
08-17 19:16:21.885  1012  1474 D InputDispatcher: Focus entered window: 6298
08-17 19:16:21.895  1012  1042 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-17 19:16:21.895  1012  1042 D PointerIcon: setMouseCustomIcon IconType is same.101
08-17 19:16:21.895  6298  6298 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-17 19:16:21.895  6298  6346 I OpenGLRenderer: Initialized EGL, version 1.4
08-17 19:16:21.905  6298  6346 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-17 19:16:21.905  6298  6346 D OpenGLRenderer: Enabling debug mode 0
08-17 19:16:21.945  1012  1360 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-17 19:16:21.955  1173  1173 D PanelView: There is/are notification(s) 
08-17 19:16:21.955  6298  6298 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@5639fd6 time:122211
08-17 19:16:21.955  1012  6349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-17 19:16:21.955  6298  6298 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-17 19:16:21.965  1888  1888 I SamsungIME: getCurrentCandidateView
08-17 19:16:21.965  1012  1042 I ActivityManager: Displayed Component not be shown by security: +700ms (total +7s279ms)
08-17 19:16:21.965  1012  1042 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{39f08555 u0 com.test.thalitest/.MainActivity t129} time:122226
08-17 19:16:21.965  1012  1042 W ActivityManager: mDVFSHelper.release()
08-17 19:16:21.975   257  1094 I SurfaceFlinger: id=13 Removed uhalitest (7/9)
08-17 19:16:21.975   257  1095 I SurfaceFlinger: id=13 Removed uhalitest (-2/9)
08-17 19:16:22.035  6298  6298 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6298
08-17 19:16:22.095  1888  1888 D SamsungIME: Dismiss ExpandCandiate
08-17 19:16:22.115  6355  6355 I dex2oat : ----------------------------------------------------
08-17 19:16:22.115  6355  6355 I dex2oat : <SS>: S T A R T I N G . . .
08-17 19:16:22.115  6355  6355 I dex2oat : <SS>: Zip is absent. Canceled.
08-17 19:16:22.115  6355  6355 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=44 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
08-17 19:16:22.155  6355  6355 I dex2oat : dex2oat took 32.177ms (threads: 4)
08-17 19:16:22.165  6261  6270 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-17 19:16:22.165  6261  6270 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-17 19:16:22.165  6261  6270 I Adreno-EGL: Build Date: 04/06/15 Mon
08-17 19:16:22.165  6261  6270 I Adreno-EGL: Local Branch: 
08-17 19:16:22.165  6261  6270 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-17 19:16:22.165  6261  6270 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-17 19:16:22.165  6261  6270 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
08-17 19:16:22.185  6298  6298 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-17 19:16:22.255  1888  1888 I SamsungIME: getDebugLevel  : 0x4f4c
,08-17 19:16:22.285  6298  6352 D jxcore_app_log: JniHelper::setJavaVM(0xb74bf328), pthread_self() = -1214133368
,08-17 19:16:22.295  1888  1888 I SamsungIME: getDebugLevel  : 0x4f4c
,08-17 19:16:22.295  6298  6352 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-17 19:16:22.295  6298  6352 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-17 19:16:22.295  6298  6352 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-17 19:16:22.295  6298  6352 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-17 19:16:22.295  6298  6352 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-17 19:16:22.295  6298  6352 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@176ba374 added. We now have 1 listener(s)
,08-17 19:16:22.305  6298  6352 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,08-17 19:16:22.305  6298  6352 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-17 19:16:22.305  6298  6352 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 19:16:22.305  6298  6352 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 19:16:22.305  1888  1888 I SamsungIME: KeybaordView init() : load resources
,08-17 19:16:22.315  6298  6352 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-17 19:16:22.315  6298  6352 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-17 19:16:22.315  6298  6352 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-17 19:16:22.315  6298  6352 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
08-17 19:16:22.315  6298  6352 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-17 19:16:22.315  6298  6352 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-17 19:16:22.315  6298  6352 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-17 19:16:22.315  6298  6352 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-17 19:16:22.315  6298  6352 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-17 19:16:22.315  6298  6352 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-17 19:16:22.315  6298  6352 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-17 19:16:22.315  6298  6352 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-17 19:16:22.315  6298  6352 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-17 19:16:22.315  6298  6352 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-17 19:16:22.315  6298  6352 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11cbe8e3 added. We now have 1 listener(s)
,08-17 19:16:22.315  6298  6352 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 19:16:22.315  6298  6352 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 19:16:22.315  6298  6352 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-17 19:16:22.315  6298  6352 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-17 19:16:22.315  6298  6352 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-17 19:16:22.315  6298  6352 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-17 19:16:22.325  6298  6352 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:16:22.325  6298  6352 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:37:96:AB
,08-17 19:16:22.335  6298  6352 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-17 19:16:22.335  6298  6352 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:16:22.335  6298  6352 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:22.335  6298  6352 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:22.335  6298  6352 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:22.335  6298  6352 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:22.335  6298  6352 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:16:22.335  6298  6352 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:16:22.335  6298  6352 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 19:16:22.335  6298  6352 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-17 19:16:22.335  6298  6352 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 19:16:22.335  1888  1888 I SamsungIME: getCurrentKeyboard
08-17 19:16:22.335  1888  1888 I SamsungIME: getTextKeyboard
,08-17 19:16:22.335  6298  6352 I io.jxcore.node.LifeCycleMonitor: start: OK,
,08-17 19:16:22.335  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:22.345  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:22.355  1888  1888 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-17 19:16:22.365  6298  6298 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-17 19:16:22.505  6261  6270 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-17 19:16:22.505  6261  6270 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-17 19:16:22.505  6261  6270 I Adreno-EGL: Build Date: 04/06/15 Mon
08-17 19:16:22.505  6261  6270 I Adreno-EGL: Local Branch: 
08-17 19:16:22.505  6261  6270 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-17 19:16:22.505  6261  6270 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-17 19:16:22.505  6261  6270 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-17 19:16:22.585  6261  6270 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-17 19:16:22.585  6261  6270 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-17 19:16:22.585  6261  6270 I Adreno-EGL: Build Date: 04/06/15 Mon
08-17 19:16:22.585  6261  6270 I Adreno-EGL: Local Branch: 
08-17 19:16:22.585  6261  6270 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-17 19:16:22.585  6261  6270 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-17 19:16:22.585  6261  6270 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-17 19:16:22.695  1906  6257 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 19:16:22.695  1906  6257 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-17 19:16:22.705  1906  6257 I qtaguid : Tagging socket 69 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1906, getuid(): 10012
,08-17 19:16:22.745  1906  6257 I qtaguid : Tagging socket 72 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1906, getuid(): 10012
,08-17 19:16:22.925  1888  6364 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-17 19:16:22.935  1906  2130 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-17 19:16:22.935  1906  2130 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,08-17 19:16:22.945  1906  2130 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-08-17 19:16:21.578+0200, stopTime=2016-08-17 19:16:22.948+0200, duration=1370ms
,08-17 19:16:22.955  1906  6371 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 19:16:22.955   277   958 D EnterpriseController: uids 10012
08-17 19:16:22.955   277   958 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-17 19:16:22.955   277   958 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-17 19:16:22.955  1906  6371 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-17 19:16:22.955  1906  6371 I qtaguid : Tagging socket 74 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1906, getuid(): 10012
,08-17 19:16:22.985  1012  2930 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-17 19:16:22.995  1906  6371 I qtaguid : Tagging socket 76 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1906, getuid(): 10012
,08-17 19:16:23.175  6298  6363 W jxcore-log: Initializing JXcore engine
08-17 19:16:23.175  6298  6363 W jxcore-log: JXcore engine is ready
,08-17 19:16:23.225  1887  1887 E audit   : type=1400 msg=audit(1471454183.225:205): avc:  denied  { ioctl } for  pid=6363 comm="Thread-1079" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-17 19:16:23.225  1887  1887 E audit   :  SEPF_SM-A500FU_5.0.2-1_0051
08-17 19:16:23.225  1887  1887 E audit   : type=1300 msg=audit(1471454183.225:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9ec008f8 items=0 ppid=303 ppcomm=main pid=6363 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-1079" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-17 19:16:23.225  1887  1887 E audit   : type=1320 msg=audit(1471454183.225:205): 
,08-17 19:16:23.235  6298  6363 W jxcore-log: Starting JXcore engine
08-17 19:16:23.255  1906  6371 I qtaguid : Untagging socket 74
,08-17 19:16:23.285  1012  1478 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-17 19:16:23.285  1012  1478 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
,08-17 19:16:23.285  1012  1478 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:23.285  1012  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:23.285  1012  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:23.315  1906  2130 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-17 19:16:23.355  6298  6363 W jxcore-log: Platform android
08-17 19:16:23.355  6298  6363 W jxcore-log: 
08-17 19:16:23.355  6298  6363 W jxcore-log: Process ARCH arm
08-17 19:16:23.355  6298  6363 W jxcore-log: 
,08-17 19:16:23.405  1012  1541 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:16:23.405  1012  1541 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:23.405  1012  1541 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:23.405  1012  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:23.435  1012  1497 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:16:23.435  1012  1497 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:23.435  1012  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-17 19:16:23.435  1012  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:23.495  1012  1540 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:16:23.495  1012  1540 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:23.495  1012  1540 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:23.495  1012  1540 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:23.495  1906  6376 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-17 19:16:23.495  1906  6374 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-17 19:16:23.495  1012  1074 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:16:23.495  1012  1074 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:23.495  1012  1074 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-17 19:16:23.495  1012  1074 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:23.515   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-17 19:16:23.525  1012  1360 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:16:23.525  1012  1360 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:23.525  1012  1360 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:23.525  1012  1360 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:23.525  1906  6376 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-17 19:16:23.525  1906  6374 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-17 19:16:23.525  1012  1221 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:16:23.525  1012  1221 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:23.525  1012  1221 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-17 19:16:23.525  1012  1221 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:23.555  1012  2930 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:16:23.555  1012  2930 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:23.555  1012  2930 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:23.555  1012  2930 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:23.555  1906  6376 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-17 19:16:23.555  1906  6374 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-17 19:16:23.555  1906  6374 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,08-17 19:16:23.575  1906  6374 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-17 19:16:23.655  6298  6363 I jxcore-log: JXcore Cordova bridge is ready!
08-17 19:16:23.655  6298  6363 I jxcore-log: 
,08-17 19:16:23.655  6298  6363 W jxcore-log: JXcore engine is started
,08-17 19:16:23.655  6298  6352 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-17 19:16:23.665  6298  6298 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-17 19:16:23.765  1012  1478 I art     : Explicit concurrent mark sweep GC freed 22547(1195KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 2.473ms total 153.176ms,
,08-17 19:16:23.785  1012  1025 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-17 19:16:23.815  1906  6374 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 19:16:23.825   277   958 D EnterpriseController: uids 10012
08-17 19:16:23.825   277   958 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-17 19:16:23.825   277   958 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-17 19:16:23.825  1906  6374 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-17 19:16:23.825  1906  6374 I qtaguid : Tagging socket 85 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1906, getuid(): 10012
,08-17 19:16:23.865  1906  6374 I qtaguid : Tagging socket 88 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1906, getuid(): 10012
,08-17 19:16:24.085  1012  2929 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-17 19:16:24.085  1906  6374 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 19:16:24.095  1906  6374 I qtaguid : Tagging socket 85 with tag 11065fff00000000{285630463,0} for uid -1, pid: 1906, getuid(): 10012
,08-17 19:16:24.215  1012  1360 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-17 19:16:24.245  1906  6374 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 19:16:24.245  1906  6374 I qtaguid : Tagging socket 65 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1906, getuid(): 10012
,08-17 19:16:24.405  1906  6374 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 19:16:24.405  1906  6374 I qtaguid : Tagging socket 85 with tag fffffca200000000{4294966434,0} for uid -1, pid: 1906, getuid(): 10012
,08-17 19:16:24.475   287   287 E SMD     : DCD OFF
,08-17 19:16:24.515   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-17 19:16:24.545  1012  1474 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-17 19:16:24.555  1906  6374 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 19:16:24.555  1906  6374 I qtaguid : Tagging socket 85 with tag fffffb1f00000000{4294966047,0} for uid -1, pid: 1906, getuid(): 10012
,08-17 19:16:24.675  1012  1540 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-17 19:16:24.685  1906  6374 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 19:16:24.685  1906  6374 I qtaguid : Tagging socket 85 with tag 1106583100000000{285628465,0} for uid -1, pid: 1906, getuid(): 10012
,08-17 19:16:25.065  1906  6369 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 19:16:25.065  1906  6369 I qtaguid : Tagging socket 74 with tag 1000310200000000{268448002,0} for uid 10012, pid: 1906, getuid(): 10012
,08-17 19:16:25.275  1906  6369 I qtaguid : Untagging socket 74
,08-17 19:16:25.285  1906  2130 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0,
,08-17 19:16:25.305  1012  1221 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-17 19:16:25.515   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-17 19:16:25.855  1012  1024 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-17 19:16:25.855  1012  1024 D BatteryService: level:93, scale:100, status:2, health:2, present:true, voltage: 4182, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-17 19:16:25.855  1012  1024 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,08-17 19:16:25.855  1012  1024 D BatteryService: stay LED for charging
08-17 19:16:25.855  1012  1012 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-17 19:16:25.855  1012  1012 I MotionRecognitionService: Plugged
08-17 19:16:25.855  1012  1012 I MotionRecognitionService: mGripSensorEnabled= false
,08-17 19:16:25.855  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-17 19:16:25.855  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-17 19:16:25.855  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
08-17 19:16:25.855  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,08-17 19:16:25.875  2650  2650 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-17 19:16:25.875  2650  2756 D HeadsetStateMachine: Disconnected process message: 10
,08-17 19:16:25.885  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,08-17 19:16:25.885  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,08-17 19:16:25.885  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,08-17 19:16:26.515   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-17 19:16:27.475   287   287 E SMD     : DCD OFF,
,08-17 19:16:27.515   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-17 19:16:27.685  1012  1024 I ActivityManager: Killing 5382:com.google.android.talk/u0a104 (adj 15): empty #31
,08-17 19:16:27.915  1012  1044 I PowerManagerService: [PWL] Off : 50s ago
,08-17 19:16:28.205  1012  2745 D SSRM:n  : SIOP:: AP = 330
,08-17 19:16:28.515   314   314 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-17 19:16:30.475   287   287 E SMD     : DCD OFF
,08-17 19:16:31.225  1012  1052 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-17 19:16:33.485   287   287 E SMD     : DCD OFF
,08-17 19:16:35.905  1012  1540 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-17 19:16:35.905  1012  1540 D BatteryService: level:93, scale:100, status:2, health:2, present:true, voltage: 4197, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,08-17 19:16:35.905  1012  1540 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-17 19:16:35.905  1012  1540 D BatteryService: stay LED for charging
,08-17 19:16:35.915  1012  1012 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-17 19:16:35.915  1012  1012 I MotionRecognitionService: Plugged
,08-17 19:16:35.915  1012  1012 I MotionRecognitionService: mGripSensorEnabled= false
,08-17 19:16:35.915  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-17 19:16:35.915  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-17 19:16:35.915  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-17 19:16:35.915  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,08-17 19:16:35.935  2650  2650 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-17 19:16:35.935  2650  2756 D HeadsetStateMachine: Disconnected process message: 10
,08-17 19:16:35.945  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,08-17 19:16:35.945  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,08-17 19:16:35.945  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,08-17 19:16:36.435  6298  6363 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
08-17 19:16:36.435  6298  6363 I jxcore-log: 
,08-17 19:16:36.445  6298  6363 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
08-17 19:16:36.445  6298  6363 I jxcore-log: 
,08-17 19:16:36.445  6298  6363 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-17 19:16:36.445  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:36.445  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:36.445  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:36.445  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:36.445  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:16:36.445  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:16:36.445  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 19:16:36.445  6298  6363 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 19:16:36.445  6298  6363 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-17 19:16:36.445  6298  6363 I jxcore-log: 
08-17 19:16:36.455  6298  6363 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-17 19:16:36.455  6298  6363 I jxcore-log: 
,08-17 19:16:36.485   287   287 E SMD     : DCD OFF
,08-17 19:16:36.585  1012  2772 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-17 19:16:36.905  6298  6363 D ExecuteNativeTests: Running unit tests
,08-17 19:16:36.985  6298  6363 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 19:16:36.985  6298  6363 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1251fed2 added. We now have 2 listener(s)
,08-17 19:16:36.985  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-17 19:16:36.985  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:16:36.985  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
08-17 19:16:36.985  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:16:36.985  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30f9aba3 added. We now have 2 listener(s)
08-17 19:16:36.985  6298  6363 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:16:36.985  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 19:16:36.985  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:16:36.995  6298  6363 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:16:36.995  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:36.995  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:36.995  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:36.995  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:36.995  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:16:36.995  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:16:36.995  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 19:16:36.995  6298  6363 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 19:16:36.995  6298  6363 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 19:16:36.995  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:36.995  6298  6363 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-17 19:16:36.995  6298  6363 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 19:16:36.995  6298  6363 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-17 19:16:36.995  6298  6363 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-17 19:16:36.995  6298  6363 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-17 19:16:36.995  6298  6363 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 19:16:36.995  6298  6363 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 19:16:36.995  6298  6363 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-17 19:16:36.995  6298  6363 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:37.005  6298  6363 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:37.005  6298  6363 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 19:16:37.005  6298  6363 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:37.005  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.005  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:16:37.005  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 19:16:37.005  6298  6363 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1251fed2 removed from the list
08-17 19:16:37.005  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:37.005  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30f9aba3 removed from the list
,08-17 19:16:37.005  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:37.005  6298  6363 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:37.005  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:37.005  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.005  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:37.005  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 19:16:37.005  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:37.005  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:37.005  6298  6363 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30f9aba3 not in the list
,08-17 19:16:37.005  6298  6363 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-17 19:16:37.015  6298  6363 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:37.015  6298  6363 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:37.015  6298  6363 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:37.015  6298  6363 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:37.015  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.015  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:37.015  6298  6363 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1251fed2 not in the list
08-17 19:16:37.015  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:37.015  6298  6363 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30f9aba3 not in the list
08-17 19:16:37.015  6298  6363 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:37.015  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.015  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:37.015  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.015  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:37.015  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:37.015  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:37.015  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:37.015  6298  6363 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30f9aba3 not in the list
08-17 19:16:37.015  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-17 19:16:37.015  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-17 19:16:37.015  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-17 19:16:37.025  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-17 19:16:37.025  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-17 19:16:37.025  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-17 19:16:37.025  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-17 19:16:37.025  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-17 19:16:37.025  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-17 19:16:37.025  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-17 19:16:37.025  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-17 19:16:37.025  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-17 19:16:37.025  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-17 19:16:37.025  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-17 19:16:37.025  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-17 19:16:37.025  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-17 19:16:37.025  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-17 19:16:37.025  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-17 19:16:37.025  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-17 19:16:37.025  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-17 19:16:37.025  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-17 19:16:37.025  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-17 19:16:37.025  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-17 19:16:37.025  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-17 19:16:37.025  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-17 19:16:37.025  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-17 19:16:37.025  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-17 19:16:37.025  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-17 19:16:37.025  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-17 19:16:37.025  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-17 19:16:37.025  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-17 19:16:37.025  6298  6363 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:37.025  6298  6363 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:37.025  6298  6363 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:37.025  6298  6363 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:37.025  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.025  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:37.025  6298  6363 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1251fed2 not in the list
08-17 19:16:37.025  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:37.025  6298  6363 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30f9aba3 not in the list
08-17 19:16:37.025  6298  6363 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:37.025  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.025  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:37.025  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.025  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:37.025  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:37.025  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:37.025  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:37.025  6298  6363 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30f9aba3 not in the list
08-17 19:16:37.025  6298  6363 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-17 19:16:37.025  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:16:37.035  6298  6363 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:16:37.035  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:37.035  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:37.035  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:37.035  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:37.035  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:16:37.035  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:16:37.035  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 19:16:37.035  6298  6363 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 19:16:37.035  6298  6363 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 19:16:37.035  6298  6363 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 19:16:37.035  6298  6363 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 19:16:37.035  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 19:16:37.035  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:16:37.035  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 19:16:37.045  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:37.045  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:16:37.045  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-17 19:16:37.055  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-17 19:16:37.055  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-17 19:16:37.055  6298  6363 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-17 19:16:37.065  6298  6363 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-17 19:16:37.065  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-17 19:16:37.065  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 19:16:37.075  6298  6363 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-17 19:16:37.085  2650  5377 D BtGatt.GattService: registerClient() - UUID=942477cb-6f43-4607-b75a-d3cd935b86df
,08-17 19:16:37.125  2650  2734 D BtGatt.GattService: onClientRegistered() - UUID=942477cb-6f43-4607-b75a-d3cd935b86df, clientIf=6
,08-17 19:16:37.125  6298  6308 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-17 19:16:37.135  2650  2951 D BtGatt.GattService: start scan with filters
,08-17 19:16:37.135  2650  2754 D BtGatt.ScanManager: handling starting scan
,08-17 19:16:37.135  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-17 19:16:37.135  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-17 19:16:37.135  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-17 19:16:37.135  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 19:16:37.145  2650  2754 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34793505
,08-17 19:16:37.145  6298  6363 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 19:16:37.145  6298  6298 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 19:16:37.145  6298  6363 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 19:16:37.155  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 19:16:37.155  2650  2734 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-17 19:16:37.155  2650  2734 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:37.155  2650  2754 D BtGatt.ScanManager: allow scan with filters
08-17 19:16:37.155  2650  2754 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-17 19:16:37.155  2650  2754 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-17 19:16:37.165  6298  6363 I io.jxcore.node.ConnectionHelper: start: OK
,08-17 19:16:37.165  2650  2734 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-17 19:16:37.165  2650  2734 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:37.165  2650  2754 D BtGatt.ScanManager: Starting BLE batch scan,
08-17 19:16:37.165  2650  2754 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-17 19:16:37.165  6298  6363 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:37.165  6298  6363 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-17 19:16:37.165  6298  6363 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:37.165  6298  6363 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-17 19:16:37.165  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.165  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 19:16:37.165  6298  6363 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts,
08-17 19:16:37.165  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 19:16:37.165  6298  6363 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 19:16:37.165  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 19:16:37.165  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 19:16:37.165  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 19:16:37.175  2650  2664 D BtGatt.GattService: stopScan() - queue size =1
,08-17 19:16:37.175  2650  5377 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-17 19:16:37.175  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 19:16:37.175  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 19:16:37.175  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 19:16:37.175  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 19:16:37.175  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 19:16:37.175  6298  6363 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
08-17 19:16:37.175  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-17 19:16:37.175  6298  6363 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-17 19:16:37.175  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 19:16:37.175  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 19:16:37.175  6298  6298 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
08-17 19:16:37.175  6298  6298 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:16:37.175  6298  6298 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 19:16:37.175  6298  6363 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:37.175  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
,08-17 19:16:37.175  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:16:37.175  6298  6363 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1251fed2 not in the list
08-17 19:16:37.175  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:37.175  6298  6363 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30f9aba3 not in the list
08-17 19:16:37.175  6298  6363 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:37.175  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:37.175  6298  6363 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-17 19:16:37.185  2650  2734 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-17 19:16:37.185  2650  2734 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:37.185  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:16:37.185  2650  2734 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
08-17 19:16:37.185  2650  2734 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:37.195  6298  6363 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:16:37.195  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:37.195  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:37.195  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:37.195  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:37.195  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:16:37.195  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:16:37.195  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 19:16:37.195  6298  6363 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 19:16:37.195  6298  6363 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 19:16:37.195  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:16:37.205  6298  6363 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 19:16:37.205  6298  6363 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 19:16:37.205  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 19:16:37.205  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:16:37.205  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 19:16:37.205  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:37.205  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 19:16:37.215  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 19:16:37.215  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 19:16:37.215  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-17 19:16:37.215  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-17 19:16:37.215  6298  6363 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-17 19:16:37.225  2650  2754 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 57
,08-17 19:16:37.225  2650  2951 D BtGatt.GattService: registerClient() - UUID=f884e441-d0df-4da2-947a-5bcaf82838e1
,08-17 19:16:37.225  2650  2754 D BtGatt.ScanManager: filter size is 1
,08-17 19:16:37.225  2650  2754 D BtGatt.ScanManager: delete FilterIndex - 3
,08-17 19:16:37.235  2650  2734 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-17 19:16:37.235  2650  2734 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:37.235  2650  2754 D BtGatt.ScanManager: stopping BLe Batch
,08-17 19:16:37.245  2650  2734 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-17 19:16:37.245  2650  2734 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:16:37.245  2650  2754 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-17 19:16:37.255  2650  2734 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-17 19:16:37.255  2650  2734 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:37.265  2650  2734 D BtGatt.GattService: onClientRegistered() - UUID=f884e441-d0df-4da2-947a-5bcaf82838e1, clientIf=6
,08-17 19:16:37.265  6298  6350 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6,
08-17 19:16:37.265  2650  5377 D BtGatt.GattService: start scan with filters
08-17 19:16:37.265  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-17 19:16:37.265  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-17 19:16:37.265  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 19:16:37.265  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 19:16:37.275  6298  6363 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 19:16:37.275  6298  6363 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 19:16:37.275  6298  6298 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 19:16:37.275  2650  2754 D BtGatt.ScanManager: handling starting scan
,08-17 19:16:37.275  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 19:16:37.275  2650  2734 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-17 19:16:37.285  2650  2734 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:37.285  6298  6363 I io.jxcore.node.ConnectionHelper: start: OK
,08-17 19:16:37.285  2650  2754 D BtGatt.ScanManager: allow scan with filters
08-17 19:16:37.285  2650  2754 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-17 19:16:37.285  2650  2754 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-17 19:16:37.285  6298  6363 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 19:16:37.285  6298  6363 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-17 19:16:37.285  6298  6363 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:37.285  6298  6363 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-17 19:16:37.285  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.285  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 19:16:37.285  6298  6363 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-17 19:16:37.285  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 19:16:37.285  6298  6363 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 19:16:37.285  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 19:16:37.285  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 19:16:37.285  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 19:16:37.285  2650  2734 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-17 19:16:37.285  2650  2734 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:16:37.285  2650  2754 D BtGatt.ScanManager: Starting BLE batch scan
08-17 19:16:37.295  2650  2754 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-17 19:16:37.295  2650  2660 D BtGatt.GattService: stopScan() - queue size =1
08-17 19:16:37.295  2650  2951 D BtGatt.GattService: unregisterClient() - clientIf=6
08-17 19:16:37.295  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 19:16:37.295  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 19:16:37.295  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 19:16:37.295  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 19:16:37.295  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-17 19:16:37.295  6298  6363 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 19:16:37.295  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-17 19:16:37.295  6298  6363 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 19:16:37.295  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 19:16:37.295  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 19:16:37.305  2650  2734 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-17 19:16:37.305  2650  2734 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:37.305  6298  6298 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 19:16:37.305  6298  6298 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 19:16:37.305  6298  6298 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 19:16:37.305  6298  6363 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:37.305  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:16:37.305  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:16:37.305  6298  6363 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1251fed2 not in the list
,08-17 19:16:37.305  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:37.305  6298  6363 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30f9aba3 not in the list
,08-17 19:16:37.305  6298  6363 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:37.305  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:37.315  2650  2734 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-17 19:16:37.315  2650  2734 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:37.325  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:16:37.325  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:37.325  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:37.325  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:37.325  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:37.325  6298  6363 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30f9aba3 not in the list
,08-17 19:16:37.325  6298  6363 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-17 19:16:37.325  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:16:37.325  2650  2754 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 58
,08-17 19:16:37.335  6298  6363 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:16:37.335  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:37.335  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:37.335  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:37.335  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:37.335  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:16:37.335  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:16:37.335  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 19:16:37.335  2650  2754 D BtGatt.ScanManager: filter size is 1
,08-17 19:16:37.335  2650  2754 D BtGatt.ScanManager: delete FilterIndex - 4
,08-17 19:16:37.335  6298  6363 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 19:16:37.335  6298  6363 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 19:16:37.335  6298  6363 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 19:16:37.335  6298  6363 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 19:16:37.335  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 19:16:37.335  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:16:37.335  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 19:16:37.335  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:37.335  2650  2734 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-17 19:16:37.335  2650  2734 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:37.335  2650  2754 D BtGatt.ScanManager: stopping BLe Batch
,08-17 19:16:37.345  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:37.345  2650  2734 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
08-17 19:16:37.345  2650  2734 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:16:37.345  2650  2754 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-17 19:16:37.345  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 19:16:37.345  2650  2734 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-17 19:16:37.345  2650  2734 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:37.355  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,08-17 19:16:37.355  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 19:16:37.355  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-17 19:16:37.355  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-17 19:16:37.355  6298  6363 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-17 19:16:37.355  2650  5377 D BtGatt.GattService: registerClient() - UUID=db76c90f-1bda-494d-9ca6-39d5fa71bad3
,08-17 19:16:37.405  2650  2734 D BtGatt.GattService: onClientRegistered() - UUID=db76c90f-1bda-494d-9ca6-39d5fa71bad3, clientIf=6
,08-17 19:16:37.405  6298  6350 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-17 19:16:37.405  2650  2664 D BtGatt.GattService: start scan with filters
,08-17 19:16:37.405  2650  2754 D BtGatt.ScanManager: handling starting scan
,08-17 19:16:37.405  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-17 19:16:37.405  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 19:16:37.405  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 19:16:37.405  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 19:16:37.405  6298  6363 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 19:16:37.405  6298  6363 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-17 19:16:37.415  6298  6298 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 19:16:37.415  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 19:16:37.415  2650  2734 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-17 19:16:37.415  2650  2734 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:37.415  2650  2754 D BtGatt.ScanManager: allow scan with filters
08-17 19:16:37.415  2650  2754 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-17 19:16:37.415  2650  2754 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-17 19:16:37.425  6298  6363 I io.jxcore.node.ConnectionHelper: start: OK
,08-17 19:16:37.425  6298  6363 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:37.425  6298  6363 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-17 19:16:37.425  6298  6363 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-17 19:16:37.425  2650  2734 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-17 19:16:37.425  2650  2734 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:37.425  2650  2754 D BtGatt.ScanManager: Starting BLE batch scan
08-17 19:16:37.425  2650  2754 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-17 19:16:37.425  6298  6363 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-17 19:16:37.425  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.425  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-17 19:16:37.425  6298  6363 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 19:16:37.425  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 19:16:37.425  6298  6363 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-17 19:16:37.425  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-17 19:16:37.425  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 19:16:37.425  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 19:16:37.435  2650  5377 D BtGatt.GattService: stopScan() - queue size =1
,08-17 19:16:37.435  2650  2664 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-17 19:16:37.435  2650  2734 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-17 19:16:37.435  2650  2734 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:37.435  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-17 19:16:37.435  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 19:16:37.435  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-17 19:16:37.435  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 19:16:37.435  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 19:16:37.435  6298  6363 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 19:16:37.435  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-17 19:16:37.445  6298  6363 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 19:16:37.445  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 19:16:37.445  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 19:16:37.445  2650  2734 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-17 19:16:37.445  2650  2734 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:37.445  6298  6298 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 19:16:37.445  6298  6363 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:37.445  6298  6363 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-17 19:16:37.445  6298  6363 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:37.445  6298  6363 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:37.445  6298  6363 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:37.445  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.445  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:16:37.445  6298  6363 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1251fed2 not in the list
08-17 19:16:37.445  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:37.445  6298  6363 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30f9aba3 not in the list
08-17 19:16:37.445  6298  6363 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:37.445  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:37.445  6298  6298 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:16:37.445  6298  6298 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 19:16:37.445  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.445  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:37.455  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:37.455  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:37.455  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:37.455  6298  6363 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30f9aba3 not in the list
,08-17 19:16:37.455  6298  6363 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-17 19:16:37.455  6298  6363 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:37.455  6298  6363 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:37.455  6298  6363 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:37.455  6298  6363 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:37.455  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.455  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:37.455  6298  6363 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1251fed2 not in the list
08-17 19:16:37.455  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:37.455  6298  6363 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30f9aba3 not in the list
08-17 19:16:37.455  6298  6363 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:37.455  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.455  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:37.455  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.455  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:37.455  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 19:16:37.455  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:37.455  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:37.455  6298  6363 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30f9aba3 not in the list
,08-17 19:16:37.455  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-17 19:16:37.455  6298  6363 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 19:16:37.455  6298  6363 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:37.455  6298  6363 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 19:16:37.455  6298  6363 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 19:16:37.455  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.455  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:37.455  6298  6363 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1251fed2 not in the list
,08-17 19:16:37.455  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:37.455  6298  6363 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30f9aba3 not in the list
08-17 19:16:37.455  6298  6363 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:37.455  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.455  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:37.455  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:16:37.455  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:37.465  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:37.465  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:37.465  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:37.465  6298  6363 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30f9aba3 not in the list
,08-17 19:16:37.465  6298  6363 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-17 19:16:37.465  6298  6363 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:37.465  6298  6363 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:37.465  6298  6363 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:37.465  6298  6363 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:37.465  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.465  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:37.465  6298  6363 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1251fed2 not in the list
08-17 19:16:37.465  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:37.465  6298  6363 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30f9aba3 not in the list
08-17 19:16:37.465  6298  6363 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:37.465  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.465  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:37.465  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.465  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:37.465  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:37.465  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:37.465  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:37.465  6298  6363 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30f9aba3 not in the list
,08-17 19:16:37.465  2650  2754 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 59
08-17 19:16:37.465  6298  6363 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-17 19:16:37.465  6298  6363 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:37.465  6298  6363 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 19:16:37.465  6298  6363 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:37.465  6298  6363 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:37.465  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.465  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:37.465  6298  6363 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1251fed2 not in the list
,08-17 19:16:37.465  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:37.465  6298  6363 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30f9aba3 not in the list
08-17 19:16:37.465  6298  6363 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:37.465  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.465  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:37.465  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.465  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:37.465  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:37.465  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 19:16:37.465  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:37.465  6298  6363 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30f9aba3 not in the list
08-17 19:16:37.465  6298  6363 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-17 19:16:37.465  6298  6363 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1,
08-17 19:16:37.465  6298  6363 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 19:16:37.465  6298  6363 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 19:16:37.465  6298  6363 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-17 19:16:37.465  6298  6363 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 19:16:37.465  6298  6363 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:37.465  6298  6363 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:37.465  6298  6363 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:37.465  6298  6363 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:37.465  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.465  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:37.465  6298  6363 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1251fed2 not in the list
08-17 19:16:37.465  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:37.465  6298  6363 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30f9aba3 not in the list
08-17 19:16:37.465  6298  6363 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:37.465  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.465  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:37.465  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.465  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:37.475  2650  2754 D BtGatt.ScanManager: filter size is 1
08-17 19:16:37.475  2650  2754 D BtGatt.ScanManager: delete FilterIndex - 5
,08-17 19:16:37.475  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:37.475  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 19:16:37.475  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:37.475  6298  6363 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30f9aba3 not in the list
08-17 19:16:37.475  6298  6363 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-17 19:16:37.475  6298  6363 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-17 19:16:37.475  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-17 19:16:37.475  6298  6363 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-17 19:16:37.475  6298  6363 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-17 19:16:37.475  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-17 19:16:37.475  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-17 19:16:37.475  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-17 19:16:37.475  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-17 19:16:37.475  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-17 19:16:37.475  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-17 19:16:37.475  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-17 19:16:37.475  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-17 19:16:37.475  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-17 19:16:37.475  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-17 19:16:37.475  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-17 19:16:37.475  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-17 19:16:37.475  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-17 19:16:37.475  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-17 19:16:37.475  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-17 19:16:37.475  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-17 19:16:37.475  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-17 19:16:37.475  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-17 19:16:37.475  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-17 19:16:37.475  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-17 19:16:37.475  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-17 19:16:37.475  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-17 19:16:37.475  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-17 19:16:37.475  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-17 19:16:37.475  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-17 19:16:37.475  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-17 19:16:37.475  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-17 19:16:37.475  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-17 19:16:37.475  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-17 19:16:37.475  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-17 19:16:37.475  6298  6363 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-17 19:16:37.475  6298  6363 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 19:16:37.475  6298  6363 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-17 19:16:37.475  6298  6363 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 19:16:37.475  6298  6363 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 19:16:37.475  6298  6363 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-17 19:16:37.475  6298  6363 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 19:16:37.475  6298  6363 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 19:16:37.475  6298  6363 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-17 19:16:37.475  2650  2734 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-17 19:16:37.475  2650  2734 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:16:37.475  2650  2754 D BtGatt.ScanManager: stopping BLe Batch
08-17 19:16:37.485  2650  2734 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-17 19:16:37.485  2650  2734 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:16:37.485  2650  2754 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-17 19:16:37.485  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-17 19:16:37.485  2650  2734 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-17 19:16:37.485  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-17 19:16:37.485  2650  2734 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:16:37.485  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-17 19:16:37.485  6298  6363 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-17 19:16:37.485  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-17 19:16:37.485  6298  6363 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-17 19:16:37.485  6298  6363 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 19:16:37.485  6298  6363 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-17 19:16:37.485  6298  6363 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:37.485  6298  6363 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:37.485  6298  6363 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:37.485  6298  6363 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:37.485  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.485  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:37.485  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-17 19:16:37.485  6298  6391 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1143)
08-17 19:16:37.485  6298  6363 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1251fed2 not in the list
08-17 19:16:37.485  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:37.485  6298  6363 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30f9aba3 not in the list
08-17 19:16:37.485  6298  6363 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:37.485  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.485  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:37.485  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.485  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:37.495  6298  6392 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1143
08-17 19:16:37.495  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:37.495  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:37.495  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:37.495  6298  6363 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30f9aba3 not in the list
08-17 19:16:37.495  6298  6363 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-17 19:16:37.495  6298  6363 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:37.495  6298  6363 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:37.495  6298  6363 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:37.495  6298  6363 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:37.495  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.495  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:37.495  6298  6363 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1251fed2 not in the list
08-17 19:16:37.495  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:37.495  6298  6363 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30f9aba3 not in the list
08-17 19:16:37.495  6298  6363 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:37.495  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.495  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:37.495  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.495  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:37.495  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:37.495  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:37.495  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:37.495  6298  6363 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30f9aba3 not in the list
08-17 19:16:37.495  6298  6363 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-17 19:16:37.495  6298  6363 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:37.495  6298  6363 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:37.495  6298  6363 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:37.495  6298  6363 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:37.495  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.495  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:37.495  6298  6363 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1251fed2 not in the list
08-17 19:16:37.495  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:37.495  6298  6363 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30f9aba3 not in the list
08-17 19:16:37.495  6298  6363 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:37.495  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.495  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:37.495  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.495  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:37.495  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:37.495  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:37.495  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:37.495  6298  6363 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30f9aba3 not in the list
08-17 19:16:37.495  6298  6363 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-17 19:16:37.495  6298  6363 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-17 19:16:37.495  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 19:16:37.495  6298  6363 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-17 19:16:37.495  6298  6363 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-17 19:16:37.495  6298  6363 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-17 19:16:37.495  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 19:16:37.495  6298  6363 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-17 19:16:37.495  6298  6363 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-17 19:16:37.495  6298  6363 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-17 19:16:37.495  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 19:16:37.495  6298  6363 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-17 19:16:37.495  6298  6363 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:37.495  6298  6363 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:37.495  6298  6363 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:37.495  6298  6363 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:37.495  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.495  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:37.495  6298  6363 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1251fed2 not in the list
08-17 19:16:37.495  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:37.495  6298  6363 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30f9aba3 not in the list
08-17 19:16:37.495  6298  6363 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:37.495  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.495  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:37.495  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.495  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:37.505  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:37.505  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:37.505  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:37.505  6298  6363 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30f9aba3 not in the list
08-17 19:16:37.505  6298  6363 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:37.505  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.505  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:37.505  6298  6363 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1251fed2 not in the list
08-17 19:16:37.505  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:37.505  6298  6363 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30f9aba3 not in the list
08-17 19:16:37.505  6298  6363 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:37.505  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.505  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:37.505  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:37.505  6298  6363 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30f9aba3 not in the list
08-17 19:16:37.505  6298  6363 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:37.505  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.505  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:37.505  6298  6363 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1251fed2 not in the list
08-17 19:16:37.505  6298  6363 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:37.505  6298  6363 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:37.505  6298  6363 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:37.505  6298  6363 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:37.505  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.505  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:37.505  6298  6363 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1251fed2 not in the list
08-17 19:16:37.505  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:37.505  6298  6363 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30f9aba3 not in the list
08-17 19:16:37.505  6298  6363 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:37.505  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.505  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:37.505  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.505  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:37.505  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:37.505  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:37.505  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:37.505  6298  6363 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30f9aba3 not in the list
08-17 19:16:37.505  6298  6391 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
08-17 19:16:37.505  6298  6363 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-17 19:16:37.505  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:16:37.505  6298  6391 D BluetoothSocket: connect(): myUserId = 0
08-17 19:16:37.505  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-17 19:16:37.505  6298  6391 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 19:16:37.505  6298  6363 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-17 19:16:37.505  6298  6363 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-17 19:16:37.505  6298  6363 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-17 19:16:37.505  6298  6363 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 19:16:37.505  6298  6363 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:37.505  6298  6363 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-17 19:16:37.505  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-17 19:16:37.505  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-17 19:16:37.505  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:37.505  6298  6363 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-17 19:16:37.505  6298  6363 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1251fed2 not in the list
08-17 19:16:37.505  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:37.505  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 19:16:37.505  6298  6363 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 19:16:37.505  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 19:16:37.505  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.505  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:37.505  2650  5377 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:16:37.505  6298  6298 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-17 19:16:37.505  6298  6298 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-17 19:16:37.515  6298  6393 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-17 19:16:37.515  6298  6393 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-17 19:16:37.515  6298  6391 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[103]}
08-17 19:16:37.515  6298  6363 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 19:16:37.515  6298  6363 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30f9aba3 not in the list
08-17 19:16:37.515  6298  6298 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:16:37.515  6298  6363 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:37.515  6298  6298 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:16:37.515  6298  6363 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:37.515  6298  6363 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:37.515  6298  6363 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:37.515  6298  6298 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-17 19:16:37.515  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.515  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:37.515  6298  6363 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1251fed2 not in the list
08-17 19:16:37.515  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:37.515  6298  6363 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30f9aba3 not in the list
08-17 19:16:37.515  6298  6363 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:37.515  6298  6298 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 19:16:37.515  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.515  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:37.515  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.515  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:37.515  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:37.515  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:37.515  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:37.515  6298  6363 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30f9aba3 not in the list
08-17 19:16:37.515  6298  6363 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-17 19:16:37.515  6298  6363 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-17 19:16:37.515  6298  6363 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 19:16:37.515  6298  6363 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 19:16:37.515  6298  6363 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:37.515  6298  6363 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:37.515  6298  6363 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:37.515  6298  6363 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:37.515  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.515  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:37.515  6298  6363 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1251fed2 not in the list
08-17 19:16:37.515  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:37.515  6298  6363 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30f9aba3 not in the list
08-17 19:16:37.515  6298  6363 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:37.515  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.515  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:37.515  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.515  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:37.515  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:37.515  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:37.515  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:37.515  6298  6363 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30f9aba3 not in the list
08-17 19:16:37.525  6298  6363 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:37.525  6298  6363 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:37.525  6298  6363 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:37.525  6298  6363 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:37.525  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.525  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:37.525  6298  6363 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1251fed2 not in the list
08-17 19:16:37.525  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:37.525  6298  6363 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30f9aba3 not in the list
08-17 19:16:37.525  6298  6363 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:37.525  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.525  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:37.525  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.525  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:37.525  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:37.525  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:37.525  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:37.525  6298  6363 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30f9aba3 not in the list
08-17 19:16:37.525  6298  6363 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:37.525  6298  6363 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:37.525  6298  6363 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:37.525  6298  6363 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:37.525  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.525  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:37.525  6298  6363 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1251fed2 not in the list
08-17 19:16:37.525  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:37.525  6298  6363 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30f9aba3 not in the list
08-17 19:16:37.525  6298  6363 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:37.525  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.525  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:37.525  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:37.525  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:37.525  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:37.525  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:37.525  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:37.525  6298  6363 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30f9aba3 not in the list
08-17 19:16:37.525  6298  6363 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-17 19:16:37.525  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 19:16:37.525  6298  6363 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-17 19:16:37.525  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 19:16:37.525  6298  6363 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-17 19:16:37.525  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 19:16:37.525  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-17 19:16:37.525  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-17 19:16:37.525  6298  6363 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-17 19:16:37.525  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-17 19:16:37.525  6298  6363 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-17 19:16:37.525  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-17 19:16:37.525  6298  6363 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-17 19:16:37.525  6298  6363 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-17 19:16:37.525  6298  6363 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-17 19:16:37.525  6298  6363 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-17 19:16:37.525  6298  6363 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-17 19:16:37.525  6298  6363 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-17 19:16:37.525  6298  6363 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-17 19:16:37.525  6298  6363 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-17 19:16:37.525  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:16:37.525  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9cbefcd added. We now have 2 listener(s)
08-17 19:16:37.535  6298  6363 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:16:37.535  6298  6363 D BluetoothAdapter: enable()
08-17 19:16:37.535  6298  6363 D BluetoothAdapter: enable(): BT is already enabled..!
08-17 19:16:37.535  1012  1074 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-17 19:16:37.535  1012  1074 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-17 19:16:37.535  1012  1074 D SecContentProvider2: mCursor = null
08-17 19:16:37.535  1012  1074 D WifiService: setWifiEnabled: true pid=6298, uid=10155
08-17 19:16:37.535  1012  1074 W ActivityManager: Permission Denial: getCurrentUser() from pid=6298, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-17 19:16:37.535  1012  1074 W WifiService: Failed getting userId using ActivityManagerNative
08-17 19:16:37.535  1012  1074 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6298, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-17 19:16:37.535  1012  1074 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-17 19:16:37.535  1012  1074 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-17 19:16:37.535  1012  1074 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-17 19:16:37.535  1012  1074 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-17 19:16:37.535  1012  1074 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-17 19:16:37.535  1012  1074 D SettingsProvider: name = wifi_on
08-17 19:16:37.535  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:16:37.535  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1473c082 added. We now have 3 listener(s)
08-17 19:16:37.535  6298  6363 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:16:37.545  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:16:37.545  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@207cc393 added. We now have 4 listener(s)
08-17 19:16:37.545  6298  6363 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:16:37.545  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:16:37.545  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2f683fd0 added. We now have 5 listener(s)
08-17 19:16:37.545  6298  6363 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:16:37.545  1012  2930 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-17 19:16:37.545  1012  2930 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-17 19:16:37.545  1012  2930 D SecContentProvider2: mCursor = null
08-17 19:16:37.545  1012  2930 D WifiService: setWifiEnabled: false pid=6298, uid=10155
08-17 19:16:37.545  1012  2930 D SettingsProvider: name = wifi_on
,08-17 19:16:37.555  1012  1126 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-17 19:16:37.555  6298  6363 D BluetoothAdapter: disable()
,08-17 19:16:37.555  2101  2101 I wpa_supplicant: reset timer : RESET_TIMER 0
08-17 19:16:37.555  2101  2101 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-17 19:16:37.555  2101  2101 I wpa_supplicant: P2P: Current p2p state = IDLE
08-17 19:16:37.555  2101  2101 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-17 19:16:37.565  1012  1474 D SettingsProvider: name = bluetooth_on
,08-17 19:16:37.565  1012  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 19:16:37.565  2650  2731 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
08-17 19:16:37.565  2650  2731 D BluetoothAdapterProperties: Setting state to 13
08-17 19:16:37.565  2650  2731 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-17 19:16:37.575  2650  2731 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-17 19:16:37.575  2650  2731 D BluetoothAdapterService: updateAdapterState state is 13
,08-17 19:16:37.575  1012  1024 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:37.575  1012  1024 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:37.575  1012  1024 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-17 19:16:37.575  1012  1024 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 19:16:37.575  1012  1024 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 19:16:37.575  2650  2650 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
08-17 19:16:37.575  2650  2731 D BluetoothAdapterService: Autoconnection is available 
08-17 19:16:37.575  2650  2731 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-17 19:16:37.575  2650  2731 D BluetoothAdapterService: terminating service from this receiver
08-17 19:16:37.575  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:16:37.575  2650  2650 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2e75a72f, channel: 19, state: LISTENING,
08-17 19:16:37.575  2650  2650 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2e75a72f, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@a97e837, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1e62b13cmSocket: android.net.LocalSocket@126deec5 impl:android.net.LocalSocketImpl@8ece01a fd:FileDescriptor[74]
08-17 19:16:37.575  2650  2650 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@126deec5 impl:android.net.LocalSocketImpl@8ece01a fd:FileDescriptor[74]
,08-17 19:16:37.575  1012  1012 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-17 19:16:37.575  1012  1012 I InputMethodManagerService: [BT Setting State] State =13
,08-17 19:16:37.585  1012  1126 E WifiNative-wlan0: do suspend true
,08-17 19:16:37.585  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:37.585  6298  6363 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:16:37.585  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:37.585  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:37.585  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:37.585  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:16:37.585  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:16:37.585  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:16:37.585  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 19:16:37.585  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:37.585  6298  6363 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 19:16:37.585  6298  6363 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 19:16:37.585  1173  1173 D BluetoothTile:  onBluetoothStateChange:
,08-17 19:16:37.595  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-17 19:16:37.595  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-17 19:16:37.595  1173  1173 D BluetoothTile:  getBluetoothState : 13
,08-17 19:16:37.595  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:37.595  1173  1707 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 19:16:37.595  1888  1888 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-17 19:16:37.595  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:37.595  1012  1074 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-17 19:16:37.595  1012  2929 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-17 19:16:37.595  1312  1312 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:37.605  1173  1707 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 19:16:37.605  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-17 19:16:37.605  6298  6298 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:37.605  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:37.605  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:37.605  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:37.605  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:37.605  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:16:37.605  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:16:37.605  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:16:37.605  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 19:16:37.605  6298  6298 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:37.605  6298  6298 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 19:16:37.605  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:16:37.605  1012  1360 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-17 19:16:37.605  1173  1707 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-17 19:16:37.615  1012  1360 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:37.615  1012  1360 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:37.615  1012  1360 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 19:16:37.615  2650  2731 D BluetoothAdapterProperties: onBluetoothDisable(),
08-17 19:16:37.615  2650  2731 D BluetoothAdapterProperties: mDiscovering is false
08-17 19:16:37.615  1012  1540 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 19:16:37.615  1012  1540 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-17 19:16:37.615  1012  2929 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-17 19:16:37.615  2650  2731 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-17 19:16:37.615  1012  1540 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:37.615  1312  1312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 19:16:37.615  1012  1540 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:37.615  1012  1540 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:37.625  1012  1541 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-17 19:16:37.625  1012  1541 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-17 19:16:37.635  1012  1541 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:37.635  1012  1541 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:37.635  1012  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-17 19:16:37.635  1312  1312 D BluetoothPbap: Proxy object disconnected
08-17 19:16:37.635  1312  1312 D PbapServerProfile: Bluetooth service disconnected
,08-17 19:16:37.635  2650  2734 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-17 19:16:37.635  2650  2734 D BluetoothAdapterProperties: Scan Mode:20
,08-17 19:16:37.635  1312  1312 D DockEventReceiver: finishStartingService: stopping service
08-17 19:16:37.645  2650  2731 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-17 19:16:37.645  2650  2731 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-17 19:16:37.645  2650  2731 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-17 19:16:37.645  2650  2731 E bt-btif : cmd socket is not created
08-17 19:16:37.645  6298  6391 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3da162ce, channel: -1, state: INIT
08-17 19:16:37.645  2650  2731 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-17 19:16:37.645  6298  6391 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3da162ce, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@232605ef, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@12d988fcmSocket: android.net.LocalSocket@3d444b85 impl:android.net.LocalSocketImpl@12f4ddda fd:FileDescriptor[103]
08-17 19:16:37.645  6298  6391 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3d444b85 impl:android.net.LocalSocketImpl@12f4ddda fd:FileDescriptor[103]
08-17 19:16:37.645  6298  6391 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1143)
08-17 19:16:37.645  2650  5033 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-17 19:16:37.645  2650  2828 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-17 19:16:37.645  2650  2828 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-17 19:16:37.645  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:37.645  2650  2828 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-17 19:16:37.645  2650  2828 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 19:16:37.645  2650  2828 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-17 19:16:37.655  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:37.655  2650  2650 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@273f874b, channel: 5, state: LISTENING
08-17 19:16:37.655  2650  2650 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@273f874b, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1cf8d1a4, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@47a528mSocket: android.net.LocalSocket@17c3b241 impl:android.net.LocalSocketImpl@1de8e3e6 fd:FileDescriptor[76]
08-17 19:16:37.655  2650  2650 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@17c3b241 impl:android.net.LocalSocketImpl@1de8e3e6 fd:FileDescriptor[76]
08-17 19:16:37.655  2650  2650 I BtOppRfcommListener: stopping Accept Thread
08-17 19:16:37.655  2650  2650 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1b7d4d27, channel: 12, state: LISTENING
08-17 19:16:37.655  2650  2650 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1b7d4d27, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1451c10e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3505ebd4mSocket: android.net.LocalSocket@1b58317d impl:android.net.LocalSocketImpl@74f5872 fd:FileDescriptor[79]
08-17 19:16:37.655  2650  2650 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1b58317d impl:android.net.LocalSocketImpl@74f5872 fd:FileDescriptor[79]
,08-17 19:16:37.655  2650  5033 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-17 19:16:37.655  1312  1312 D BluetoothNotiBroadcastReceiver: onReceive
,08-17 19:16:37.665  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:37.665  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-17 19:16:37.665  2650  2650 V BluetoothOppManager: cleanUp...
,08-17 19:16:37.665  1012  1478 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-17 19:16:37.665  1012  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:37.675  1012  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:37.675  1012  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:37.675  1012  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:37.685  6400  6400 E Zygote  : MountEmulatedStorage(),
08-17 19:16:37.685  6400  6400 I libpersona: KNOX_SDCARD checking this for 10003
08-17 19:16:37.685  6400  6400 E Zygote  : v2
08-17 19:16:37.685  6400  6400 I libpersona: KNOX_SDCARD not a persona
08-17 19:16:37.685  1012  1478 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6400 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,08-17 19:16:37.695  6400  6400 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-17 19:16:37.695  6400  6400 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-17 19:16:37.695  6400  6400 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-17 19:16:37.735  6400  6400 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:37.735  6400  6400 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:37.735  2101  2101 I wpa_supplicant: nl80211: Received scan results (17 BSSes)
,08-17 19:16:37.735  1012  1125 D WifiP2pService: InactiveState{ what=147461 }
,08-17 19:16:37.735  1012  1125 D WifiP2pService: P2pEnabledState{ what=147461 }
08-17 19:16:37.735  1012  1125 D WifiP2pService: DefaultState{ what=147461 }
,08-17 19:16:37.735  1012  1125 D WifiP2pService: InactiveState{ what=143375 }
,08-17 19:16:37.735  1012  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-17 19:16:37.745   277   962 D CommandListener: Clearing all IP addresses on wlan0
,08-17 19:16:37.745  1906  4459 V NativeCrypto: Read error: ssl=0xb784e418: I/O error during system call, Connection timed out
,08-17 19:16:37.755  1906  4459 V NativeCrypto: SSL shutdown failed: ssl=0xb784e418: I/O error during system call, Broken pipe
,08-17 19:16:37.755  1906  4459 E GCM     : Wifi connection closed with errorCode 20
,08-17 19:16:37.755  1012  1474 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,08-17 19:16:37.755  1012  2216 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
08-17 19:16:37.755  1012  2216 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
08-17 19:16:37.755  1012  2216 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-17 19:16:37.755  1012  2216 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-17 19:16:37.755  1012  2216 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
08-17 19:16:37.755  1012  2216 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-17 19:16:37.755  1012  2216 I qtaguid : Tagging socket 361 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1012, getuid(): 1000
08-17 19:16:37.755  1012  1128 E ConnectivityService: updateNetworkInfo()
08-17 19:16:37.755  1012  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 19:16:37.755  1012  1128 E ConnectivityService: updateNetworkInfo()
08-17 19:16:37.755  1012  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,08-17 19:16:37.755  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:16:37.755  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-17 19:16:37.755  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:37.755  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:37.755  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,08-17 19:16:37.755  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-17 19:16:37.765  1012  1012 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-17 19:16:37.765  1012  2216 I qtaguid : Untagging socket 361
08-17 19:16:37.765  1012  2216 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 19:16:37.775  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:16:37.775  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 19:16:37.775  1012  1125 D WifiP2pService: InactiveState{ what=131204 }
08-17 19:16:37.775  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:37.775  1012  1125 D WifiP2pService: P2pEnabledState{ what=131204 }
08-17 19:16:37.775  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:37.775  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:37.775  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:37.775  1012  1012 D WifiScanningService: SCAN_AVAILABLE : 1
08-17 19:16:37.775  1012  1148 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-17 19:16:37.775  1012  1012 D RttService: SCAN_AVAILABLE : 1
08-17 19:16:37.775  1012  1149 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-17 19:16:37.775  1012  1126 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-17 19:16:37.785  1012  1125 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-17 19:16:37.785  1012  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-17 19:16:37.795  1012  1125 D WifiP2pService: P2pDisablingState,
08-17 19:16:37.795  1012  1042 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 19:16:37.795  1012  1042 D WifiDisplayAdapter: onP2pDisconnected
08-17 19:16:37.795  1012  1125 D WifiP2pService: P2pDisablingState{ what=147458 }
08-17 19:16:37.795  1012  1125 D WifiP2pService: p2p socket connection lost
08-17 19:16:37.795  1012  1125 D WifiP2pService: P2pDisabledState
,08-17 19:16:37.795  1012  1126 E WifiNative-wlan0: do suspend true
08-17 19:16:37.795  1012  1012 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-17 19:16:37.795  1012  1042 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-17 19:16:37.795  1012  1042 D IpRemoteDisplayController: WfdBridgeServer is already null
08-17 19:16:37.795  1012  1042 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-17 19:16:37.795  1012  1042 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-17 19:16:37.795  1012  1042 D WifiDisplayController: disconnect
08-17 19:16:37.795  1012  1042 D WifiDisplayController: updateConnection
08-17 19:16:37.795  1012  1042 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-17 19:16:37.795  1012  1042 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-17 19:16:37.795  1012  1042 D WifiDisplayAdapter: onP2pDisconnected
08-17 19:16:37.795  1012  1042 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-17 19:16:37.795  1012  1042 D IpRemoteDisplayController: WfdBridgeServer is already null
08-17 19:16:37.795  1012  1042 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-17 19:16:37.805  1173  1173 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-17 19:16:37.805  1012  1074 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-17 19:16:37.805  1173  1173 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-17 19:16:37.815  6400  6400 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-17 19:16:37.835  1906  6399 I art     : Explicit concurrent mark sweep GC freed 67043(3MB) AllocSpace objects, 57(2MB) LOS objects, 40% free, 14MB/24MB, paused 1.475ms total 112.865ms
,08-17 19:16:37.845  2650  2828 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-17 19:16:37.845  2650  2828 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 19:16:37.845  6400  6400 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
08-17 19:16:37.845  2650  2828 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-17 19:16:37.845  2650  2828 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 19:16:37.845  2650  2828 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 19:16:37.845  2650  2828 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 19:16:37.845  2650  2828 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 19:16:37.845  2650  2828 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 19:16:37.845  2650  2828 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 19:16:37.845  2650  2828 W bt-btif : ag scb idx 1 not allocated
08-17 19:16:37.845  2650  2828 W bt-btif : ag scb idx 2 not allocated
08-17 19:16:37.845  2650  2828 E bt-btif : BTA AG is already disabled, ignoring ...
08-17 19:16:37.845  2650  2918 I bt_userial_mct: exiting userial_read_thread
08-17 19:16:37.845  2650  2918 D bt_userial_mct: Leaving userial_evt_read_thread()
08-17 19:16:37.845  2650  2734 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-17 19:16:37.845  6400  6400 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-17 19:16:37.845  6400  6400 D UserAnalysis: Create SecureDbHelper
,08-17 19:16:37.845  2650  2833 I bt_vendor: hw_epilog_process
,08-17 19:16:37.845  2650  2734 D bt_userial_mct: userial_close
08-17 19:16:37.845  2650  2734 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-17 19:16:37.855  6400  6400 D IntelligenceServiceApplication: onCreate()
,08-17 19:16:37.865  1012  1478 I ActivityManager: Killing 5070:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,08-17 19:16:37.865  6400  6400 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-17 19:16:37.865  1012  1478 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-17 19:16:37.865  1012  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:37.875  1012  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:37.875  1012  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:37.875  1012  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:37.885  6422  6422 E Zygote  : MountEmulatedStorage(),
08-17 19:16:37.885  6422  6422 E Zygote  : v2
08-17 19:16:37.885  6422  6422 I libpersona: KNOX_SDCARD checking this for 10107
08-17 19:16:37.885  6422  6422 I libpersona: KNOX_SDCARD not a persona
08-17 19:16:37.885  6422  6422 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-17 19:16:37.885  1012  1478 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6422 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-17 19:16:37.885  6422  6422 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-17 19:16:37.885  1012  1497 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
08-17 19:16:37.885  6422  6422 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-17 19:16:37.895  6400  6400 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-17 19:16:37.905  6400  6400 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-17 19:16:37.905  6422  6422 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:37.905  6422  6422 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:37.935  1012  1125 D WifiP2pService: P2pDisabledState{ what=143375 }
08-17 19:16:37.935  1012  1125 D WifiP2pService: DefaultState{ what=143375 }
,08-17 19:16:37.935  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 19:16:37.935  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 19:16:37.935  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:37.945  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:37.945  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:37.945  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:37.945   277   958 D EnterpriseController: uids 1000
08-17 19:16:37.945   277   958 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-17 19:16:37.945   277   958 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-17 19:16:37.945   277   962 D CommandListener: Clearing all IP addresses on wlan0
,08-17 19:16:37.945  1012  1128 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-17 19:16:37.945  1012  1128 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,08-17 19:16:37.945  1012  2216 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
08-17 19:16:37.945  1012  2216 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,08-17 19:16:37.945  1012  1041 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-17 19:16:37.945  1173  1681 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,08-17 19:16:37.955  2101  2101 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-17 19:16:37.955  1012  2216 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-17 19:16:37.955  1012  1012 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-17 19:16:37.955  1012  1128 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 19:16:37.955  1012  1125 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-17 19:16:37.955  3821  6245 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,08-17 19:16:37.955  1453  1453 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-17 19:16:37.955  1453  1453 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-17 19:16:37.955  1012  1128 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-17 19:16:37.955  1012  1128 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-17 19:16:37.955  1012  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-17 19:16:37.965  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-17 19:16:37.965  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 19:16:37.965  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:37.965  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:37.965  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:37.965  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:37.965  1012  1128 D ConnectivityService: nai.networkMonitor.doQuit()
08-17 19:16:37.965  1012  1128 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-17 19:16:37.965  1012  1128 E ConnectivityService: updateNetworkInfo()
,08-17 19:16:37.965  1012  1128 E ConnectivityService: updateNetworkInfo()
08-17 19:16:37.965  1012  1128 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 19:16:37.965  1012  1041 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-17 19:16:37.965  1012  1126 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-17 19:16:37.975  1012  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 19:16:37.975  1012  1126 D SecContentProvider2: mCursor = null
,08-17 19:16:37.975  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 19:16:37.975  1012  1331 E Watchdog: !@Sync 4
08-17 19:16:37.975  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-17 19:16:37.975  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:37.975  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:37.975  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:37.975  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:37.975  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 19:16:37.975  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-17 19:16:37.975  1173  1707 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-17 19:16:37.975  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-17 19:16:37.975  1312  1312 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-17 19:16:37.975  1173  1173 D HotspotTile: onReceive : 0, 0
,08-17 19:16:37.985  1012  1012 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,08-17 19:16:37.985  1012  1129 D Tethering: MasterInitialState.processMessage what=3
,08-17 19:16:37.985  1012  1123 V NetworkStats: updateIfacesLocked()
08-17 19:16:37.985  1012  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:37.985  1012  1123 V NetworkStats: performPollLocked(flags=0x1)
,08-17 19:16:37.985  6298  6298 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 19:16:37.985  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:37.985  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:37.985  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:37.985  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:16:37.985  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:16:37.985  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:37.985  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:37.985  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:16:37.985  1012  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-17 19:16:37.985  1012  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-17 19:16:37.985  6298  6298 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:37.985  6298  6298 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:16:37.985  1012  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:37.985  1012  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:37.985  1012  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:37.985  1012  1124 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-17 19:16:37.985  1012  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:37.995  6298  6298 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:37.995  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:37.995  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:37.995  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:37.995  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:16:37.995  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:16:37.995  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:37.995  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:37.995  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:16:37.995  6298  6298 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:37.995  6298  6298 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:16:37.995  1173  1173 D StatusBar.NetworkController: EthernetConnected: false
,08-17 19:16:37.995  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-17 19:16:37.995  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-17 19:16:37.995  1173  1173 D StatusBar.NetworkController: updateDataNetType()
08-17 19:16:37.995  1173  1173 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-17 19:16:37.995  1173  1173 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-17 19:16:37.995  1012  1123 V NetworkStats: performPollLocked() took 11ms
08-17 19:16:37.995  1012  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:37.995  1173  1173 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,08-17 19:16:37.995  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-17 19:16:37.995  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,08-17 19:16:37.995  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 19:16:37.995  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-17 19:16:38.005  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:38.005  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:38.005  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:38.005  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:38.005  1012  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:38.005  1012  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:38.015  6298  6298 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 19:16:38.045  2101  2101 I wpa_supplicant: Blacklist: Clear (all) 
,08-17 19:16:38.045  2650  2734 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-17 19:16:38.045  2650  2734 I bt_vendor: bluetooth satus is on
08-17 19:16:38.045  2650  2734 I bt_vendor: bt-vendor : resetting BT status
08-17 19:16:38.045  2650  2734 I bt_vendor: Starting hciattach daemon
08-17 19:16:38.045  2650  2734 I bt_vendor: try to set false
,08-17 19:16:38.045  2650  2734 I bt_vendor: Starting hciattach daemon
,08-17 19:16:38.045  2650  2734 I bt_vendor: try to set false
,08-17 19:16:38.045  2650  2734 I bt_vendor: cleanup
,08-17 19:16:38.045  2650  2828 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-17 19:16:38.045  2650  2734 I GKI_LINUX: GKI_exit_task 0 done
08-17 19:16:38.045  2650  2734 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-17 19:16:38.055  2650  2731 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-17 19:16:38.055  2650  2731 D BtConfig.SecureMode: isSecureModeOn:false
,08-17 19:16:38.055  2650  2731 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-17 19:16:38.055  2650  2731 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,08-17 19:16:38.055  2650  2731 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-17 19:16:38.055  2650  2731 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-17 19:16:38.055  1012  1074 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:16:38.055  1012  1074 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-17 19:16:38.055  1012  1074 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:38.055  1012  1074 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:38.055  1012  1074 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:38.065  2650  2731 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
,08-17 19:16:38.065  2650  2731 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-17 19:16:38.065  2650  2731 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-17 19:16:38.065  2650  2650 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 19:16:38.065  2650  2650 D BtGatt.GattService: Received stop request...Stopping profile...
08-17 19:16:38.065  2650  2650 D BtGatt.GattService: stop()
08-17 19:16:38.065  2650  2650 D BtGatt.AdvertiseManager: advertise clients cleared
,08-17 19:16:38.065  1012  1478 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:16:38.065  1012  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-17 19:16:38.065  1012  1478 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:38.065  1012  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:38.065  1012  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:38.065  2650  2731 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-17 19:16:38.065  2650  2731 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-17 19:16:38.075  2650  2731 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-17 19:16:38.075  2650  2650 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34793505
,08-17 19:16:38.075  1012  1541 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:38.075  1012  1541 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 19:16:38.075  1012  1541 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:38.075  1012  1541 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:38.075  1012  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:38.075  2650  2731 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-17 19:16:38.075  2650  2731 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-17 19:16:38.075  2101  2101 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-17 19:16:38.075  1012  1039 D Tethering: interfaceLinkStateChanged p2p0, false
,08-17 19:16:38.075  1012  1039 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-17 19:16:38.075  1012  1039 D Tethering: interfaceStatusChanged p2p0, false
08-17 19:16:38.075  2650  2731 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-17 19:16:38.075  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 19:16:38.085  1012  1025 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:38.085  1012  1025 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-17 19:16:38.085  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 19:16:38.085  1012  1025 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:38.085  1012  1025 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:38.085  1012  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:38.085  2650  2731 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-17 19:16:38.085  2650  2731 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-17 19:16:38.085  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-17 19:16:38.085  1012  1024 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:38.085  2650  2731 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-17 19:16:38.085  1012  1024 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-17 19:16:38.085  1012  1024 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:38.085  1012  1024 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:38.085  1012  1024 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 19:16:38.085  2650  2731 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,08-17 19:16:38.085  2650  2731 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-17 19:16:38.085  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 19:16:38.085  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-17 19:16:38.085  2650  2731 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-17 19:16:38.085  1012  1074 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:38.085  1012  1074 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-17 19:16:38.095  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 19:16:38.095  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-17 19:16:38.095  1012  1074 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:38.095  1012  1074 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:38.095  1012  1074 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:38.095  2650  2731 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-17 19:16:38.095  2650  2731 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-17 19:16:38.095  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-17 19:16:38.095  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-17 19:16:38.095  2650  2731 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-17 19:16:38.095  1012  1474 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:38.095  1012  1474 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-17 19:16:38.095  1012  1474 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:38.095  1012  1474 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:38.095  1012  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:38.095  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-17 19:16:38.095  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-17 19:16:38.095  2650  2731 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-17 19:16:38.095  2650  2731 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-17 19:16:38.095  2650  2731 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-17 19:16:38.095  1012  1541 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:16:38.095  1012  1541 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-17 19:16:38.105  2101  2101 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,08-17 19:16:38.105  2101  2101 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-17 19:16:38.105  2101  2101 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
,08-17 19:16:38.105  2101  2101 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-17 19:16:38.105  2101  2101 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-17 19:16:38.105  1012  1541 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:38.105  1012  1541 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:38.105  1012  1126 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14956 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
08-17 19:16:38.105  1012  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 19:16:38.105  1012  1039 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:16:38.105  1012  1039 D Tethering: interfaceLinkStateChanged wlan0, false
,08-17 19:16:38.105  1012  1039 D Tethering: interfaceStatusChanged wlan0, false
08-17 19:16:38.105  2650  2731 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-17 19:16:38.105  2650  2731 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:16:38.105  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-17 19:16:38.105  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 19:16:38.105  1012  1129 D Tethering: InitialState.processMessage what=4
,08-17 19:16:38.105  2650  2731 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:16:38.105  2650  2731 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:16:38.105  2650  2731 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:16:38.105  1012  1039 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:16:38.105  1012  1039 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:16:38.105  1012  1039 D Tethering: interfaceStatusChanged wlan0, false
,08-17 19:16:38.105  2650  2731 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:16:38.105  2650  2731 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-17 19:16:38.105  2650  2731 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-17 19:16:38.105  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-17 19:16:38.105  2650  2731 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-17 19:16:38.105  2650  2731 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-17 19:16:38.105  2650  2731 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-17 19:16:38.105  2650  2731 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-17 19:16:38.105  2650  2731 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-17 19:16:38.105  2650  2650 E BluetoothAdapterService(880358661): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
08-17 19:16:38.105  1012  1129 E Tethering: No numeric data
08-17 19:16:38.105  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 19:16:38.115  2650  2650 D HeadsetService: Received stop request...Stopping profile...
,08-17 19:16:38.115  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 19:16:38.115  2650  2650 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34793505
,08-17 19:16:38.115  1012  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-17 19:16:38.115  1012  1129 D Tethering: clearTetheredNotification()
,08-17 19:16:38.115  1012  1012 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-17 19:16:38.115  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 19:16:38.115  1012  1039 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:16:38.115  1012  1039 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:16:38.115  1012  1039 D Tethering: interfaceStatusChanged wlan0, false
,08-17 19:16:38.125  1012  1039 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:16:38.125  1012  1039 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:16:38.125  1012  1039 D Tethering: interfaceStatusChanged wlan0, false
08-17 19:16:38.125  1012  1123 V NetworkStats: performPollLocked(flags=0x1)
08-17 19:16:38.125  1012  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:38.125  1312  1312 D HeadsetProfile: Bluetooth service disconnected
,08-17 19:16:38.125  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 19:16:38.125  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 19:16:38.125  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-17 19:16:38.125  1173  1173 D HotspotTile: updateTetherState():false, false
,08-17 19:16:38.125  1012  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 19:16:38.125  1012  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-17 19:16:38.125  2650  2650 D A2dpService: Received stop request...Stopping profile...
,08-17 19:16:38.125  2650  2773 D A2dpStateMachine: Exit Disconnected: -1
,08-17 19:16:38.125  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-17 19:16:38.125  1012  1123 V NetworkStats: performPollLocked() took 7ms
08-17 19:16:38.125  1012  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:38.125  1012  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:38.125  1012  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:38.125  2650  2650 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34793505
,08-17 19:16:38.135  1012  1012 D BluetoothA2dp: Proxy object disconnected
08-17 19:16:38.135  1012  1012 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-17 19:16:38.135  2650  2650 D HidService: Received stop request...Stopping profile...
08-17 19:16:38.135  1312  1312 D BluetoothA2dp: Proxy object disconnected
08-17 19:16:38.135  2650  2650 D HidService: Stopping Bluetooth HidService
08-17 19:16:38.135  2650  2650 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-17 19:16:38.135  2650  2650 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-17 19:16:38.135  2650  2650 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-17 19:16:38.135  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 19:16:38.135  2650  2650 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34793505
,08-17 19:16:38.135  1312  1312 D A2dpProfile: Bluetooth service disconnected
,08-17 19:16:38.135  2889  2889 D BluetoothA2dp: Proxy object disconnected
08-17 19:16:38.135  1312  1312 D BluetoothInputDevice: Proxy object disconnected
08-17 19:16:38.135  1312  1312 D HidProfile: Bluetooth service disconnected
,08-17 19:16:38.135  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 19:16:38.135  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 19:16:38.135  2650  2650 D HealthService: Received stop request...Stopping profile...
,08-17 19:16:38.145  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-17 19:16:38.145  2650  2650 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34793505
,08-17 19:16:38.145  2650  2650 D PanService: Received stop request...Stopping profile...
08-17 19:16:38.145  2650  2650 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34793505
08-17 19:16:38.145  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 19:16:38.145  1012  1012 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-17 19:16:38.145  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 19:16:38.145  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-17 19:16:38.145  2650  2650 D BluetoothMapService: Received stop request...Stopping profile...
,08-17 19:16:38.145  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-17 19:16:38.145  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 19:16:38.155  2650  2650 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34793505
,08-17 19:16:38.155  1312  1312 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-17 19:16:38.155  1312  1312 D PanProfile: Bluetooth service disconnected
,08-17 19:16:38.155  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 19:16:38.155  1312  1312 D BluetoothMap: Proxy object disconnected
,08-17 19:16:38.155  1312  1312 D MapProfile: Bluetooth service disconnected
08-17 19:16:38.155  2650  2650 D SapService: Received stop request...Stopping profile...
,08-17 19:16:38.155  2650  2650 D SapService: Stopping Bluetooth SapService
08-17 19:16:38.155  2650  2650 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34793505
,08-17 19:16:38.155  1312  1312 D Bluetoothsap: BluetoothSAP Proxy object disconnected
,08-17 19:16:38.155  1312  1312 D SapProfile: Bluetooth service disconnected
,08-17 19:16:38.155  2650  2650 E BluetoothAdapterService(880358661): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-17 19:16:38.155  2650  2650 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-17 19:16:38.155  2650  2650 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-17 19:16:38.165   271   271 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb77437c8
08-17 19:16:38.165   271   271 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
,08-17 19:16:38.165   271   271 I rmt_storage: wakelock acquired: 1, error no: 42
08-17 19:16:38.165   271   358 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1217120968)
,08-17 19:16:38.165  2650  2650 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-17 19:16:38.165  2650  2650 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-17 19:16:38.165  2650  2650 E BluetoothAdapterService(880358661): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-17 19:16:38.165  2650  2650 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-17 19:16:38.165  2650  2650 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-17 19:16:38.165  2650  2650 D BluetoothA2dp: Proxy object disconnected
08-17 19:16:38.165  2650  2650 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-17 19:16:38.165  2650  2774 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-17 19:16:38.165  2650  2650 I GKI_LINUX: GKI_exit_task 2 done
08-17 19:16:38.165  2650  2650 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-17 19:16:38.175  2650  2650 E BluetoothAdapterService(880358661): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-17 19:16:38.175  2650  2650 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 19:16:38.175  2650  2650 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-17 19:16:38.175  2650  2650 E BluetoothAdapterService(880358661): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-17 19:16:38.175  2650  2650 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 19:16:38.175  2650  2650 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-17 19:16:38.175  2650  2650 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-17 19:16:38.175  2650  2650 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-17 19:16:38.175  2650  2650 E BluetoothAdapterService(880358661): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-17 19:16:38.175  2650  2650 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 19:16:38.175  2650  2650 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-17 19:16:38.175  2650  2650 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-17 19:16:38.175  2650  2650 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-17 19:16:38.175  2650  2650 E BluetoothAdapterService(880358661): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-17 19:16:38.175  2650  2650 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-17 19:16:38.175  2650  2650 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-17 19:16:38.175  2650  2650 E BluetoothAdapterService(880358661): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-17 19:16:38.175  2650  2650 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-17 19:16:38.175  2650  2650 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-17 19:16:38.185  2650  2731 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-17 19:16:38.185  2650  2731 D BluetoothAdapterProperties: Setting state to 10
08-17 19:16:38.185  2650  2731 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-17 19:16:38.185  2650  2731 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-17 19:16:38.185  2650  2731 D BluetoothAdapterService: updateAdapterState state is 10
08-17 19:16:38.185  2650  2731 D BluetoothAdapterService: Autoconnection is available 
08-17 19:16:38.185  2650  2731 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-17 19:16:38.185  2650  2731 I BluetoothAdapterState: Entering OffState
08-17 19:16:38.185  1312  6396 D Bluetoothsap: onBluetoothStateChange: up=false
08-17 19:16:38.185  1312  6396 D Bluetoothsap: Unbinding service...
08-17 19:16:38.185  2650  2664 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 19:16:38.185  2650  2664 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-17 19:16:38.195  2889  2897 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 19:16:38.195  2889  2897 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-17 19:16:38.195  1173  1882 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 19:16:38.195  1173  1882 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:16:38.205  1429  1452 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 19:16:38.205  1429  1452 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:16:38.205  2889  2904 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-17 19:16:38.205  1906  2112 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 19:16:38.205  1906  2112 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:16:38.205  1012  1041 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 19:16:38.205  1012  1074 D ActivityManager: bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
08-17 19:16:38.205  1012  1074 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-17 19:16:38.205  1012  1074 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:38.205  1012  1074 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:38.205  1012  1074 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-17 19:16:38.215  2650  2660 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-17 19:16:38.215  1312  1326 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 19:16:38.215  1312  1326 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-17 19:16:38.215  1312  6396 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-17 19:16:38.215  1312  1327 D BluetoothPbap: onBluetoothStateChange: up=false
,08-17 19:16:38.215  1906  1906 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-17 19:16:38.215  1453  1468 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 19:16:38.225  1453  1468 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-17 19:16:38.225  1906  1906 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-17 19:16:38.225  1312  1326 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 19:16:38.225   271   358 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
08-17 19:16:38.225   271   358 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
08-17 19:16:38.225   271   358 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1217120968) wakelock released: 1, error no: 0
08-17 19:16:38.225   271   358 I rmt_storage: 
08-17 19:16:38.225  1442  1466 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 19:16:38.225  1442  1466 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-17 19:16:38.225  1012  1041 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 19:16:38.225  1012  1041 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:16:38.225  6422  6422 D StrictMode: StrictMode policy violation; ~duration=260 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:16:38.225  6422  6422 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-17 19:16:38.225  6422  6422 D StrictMode: StrictMode policy violation; ~duration=251 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:16:38.225  6422  6422 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:16:38.235  1012  2745 D SSRM:n  : SIOP:: AP = 330
08-17 19:16:38.225   271   271 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb77437c8
08-17 19:16:38.225  6422  6422 D StrictMode: StrictMode policy violation; ~duration=192 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:16:38.225  6422  6422 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at java.io.File.exists(File.java:363)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at com.google.android.apps.gm,m.shared.f.h.a(PG:150)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:16:38.225  6422  6422 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:16:38.235  6422  6422 D StrictMode: StrictMode policy violation; ~duration=191 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:16:38.235  6422  6422 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:15,43)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:16:38.235  6422  6422 D StrictMode: StrictMode policy violation; ~duration=190 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:16:38.235  6422  6422 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:16:38.235  6422  6422 D StrictMode: StrictMode policy violation; ~duration=188 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:16:38.235  6422  6422 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.r.k.c(PG:1187)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:23)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.r.v.a(PG:1206)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.r.y.a(PG:2233)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.r.e.b(PG:170)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.r.e.b(PG:13188)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:16:38.235  6422  6422 D StrictMode: StrictMode policy violation; ~duration=183 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:16:38.235  6422  6422 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.r.k.c(PG:1187)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.r.k.b(PG:14147)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.r.k.c(PG:583)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:40)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.r.v.a(PG:1206)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.r.y.a(PG:2233)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.r.e.b(PG:170)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.r.e.b(PG:13188)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:16:38.235  6422  6422 D StrictMode: StrictMode policy violation; ~duration=149 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 19:16:38.235  6422  6422 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at java.io.File.exists(File.java:363)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:16:38.235  6422  6422 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 19:16:38.235  6298  6312 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 19:16:38.245  1012  2929 I ActivityManager: Killing 5522:com.google.android.partnersetup/u0a15 (adj 15): empty #31
08-17 19:16:38.235  6298  6312 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-17 19:16:38.235  6298  6312 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-17 19:16:38.235  6298  6312 D BluetoothLeAdvertiser: Exit stop advertising
08-17 19:16:38.235  6298  6312 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-17 19:16:38.235  6298  6312 D BluetoothLeScanner: Exiting stopAllScan
08-17 19:16:38.235  1312  1327 D BluetoothMap: onBluetoothStateChange: up=false
08-17 19:16:38.245  2101  2101 I wpa_supplicant: Blacklist: Clear (all) 
08-17 19:16:38.245  1906  1906 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-17 19:16:38.255  1012  1041 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
08-17 19:16:38.255  1906  1906 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-17 19:16:38.255  1012  1041 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-17 19:16:38.265  1012  2930 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 19:16:38.265  1012  2930 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-17 19:16:38.265  1012  2930 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:38.265  1012  2930 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:38.265  1012  2930 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-17 19:16:38.265  3642  3642 I Hs20UtilService: Starting #8
08-17 19:16:38.265  3642  3679 I Hs20UtilService: Message received 5007
08-17 19:16:38.265  1012  1012 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-17 19:16:38.265  1012  1012 I InputMethodManagerService: [BT Setting State] State =10
08-17 19:16:38.265  1012  1012 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
08-17 19:16:38.275  1173  1173 D BluetoothAdapter: 545127418: getState() :  mService = null. Returning STATE_OFF
08-17 19:16:38.275  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-17 19:16:38.275  1173  1707 D BluetoothAdapter: 545127418: getState() :  mService = null. Returning STATE_OFF
08-17 19:16:38.275  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-17 19:16:38.275  1173  1707 D BluetoothAdapter: 545127418: getState() :  mService = null. Returning STATE_OFF
08-17 19:16:38.275  1173  1173 D BluetoothTile:  getBluetoothState : 10
,08-17 19:16:38.275  1173  1173 D BluetoothAdapter: 545127418: getState() :  mService = null. Returning STATE_OFF
08-17 19:16:38.275  1173  1173 D BluetoothAdapter: 545127418: getState() :  mService = null. Returning STATE_OFF
08-17 19:16:38.275  1012  1025 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-17 19:16:38.275  1012  1074 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-17 19:16:38.275  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-17 19:16:38.275  1888  1888 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
08-17 19:16:38.275  1906  2123 D BluetoothAdapter: 792504002: getState() :  mService = null. Returning STATE_OFF
08-17 19:16:38.275  1906  2123 D BluetoothAdapter: 792504002: getState() :  mService = null. Returning STATE_OFF
08-17 19:16:38.275  1312  1312 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-17 19:16:38.275  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:16:38.275  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:16:38.275  1312  1312 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-17 19:16:38.275  1012  2929 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-17 19:16:38.285  1312  1312 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-17 19:16:38.285  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-17 19:16:38.285  1012  2929 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:38.285  1012  2929 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:38.285  2650  2734 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-17 19:16:38.285  2650  2650 I GKI_LINUX: GKI_exit_task 1 done
08-17 19:16:38.285  2650  2650 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-17 19:16:38.285  2650  2650 I BluetoothServiceJni: cleanupNative: return from cleanup
08-17 19:16:38.285  1012  2929 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-17 19:16:38.285  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-17 19:16:38.285  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 19:16:38.285  1312  1312 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-17 19:16:38.285  1312  3094 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-17 19:16:38.285  1012  1497 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 19:16:38.285  1012  1497 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-17 19:16:38.285  1012  1497 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:38.285  1012  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:38.285  1012  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-17 19:16:38.295  2650  2650 I art     : System.exit called, status: 0
08-17 19:16:38.295  2650  2650 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-17 19:16:38.295  1012  1074 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:38.295  1012  1074 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
08-17 19:16:38.295  1012  1074 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:38.295  1012  1074 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
08-17 19:16:38.295  6422  6442 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
08-17 19:16:38.295  1012  1074 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:38.295  1012  1074 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:38.295  1012  1074 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:38.295  1012  1074 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:38.305  2101  2101 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-17 19:16:38.305  1012  1039 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:16:38.305  1012  1039 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:16:38.305  1012  1039 D Tethering: interfaceStatusChanged wlan0, false
,08-17 19:16:38.315  6466  6466 E Zygote  : MountEmulatedStorage(),
08-17 19:16:38.315  6466  6466 I libpersona: KNOX_SDCARD checking this for 10104
08-17 19:16:38.315  6466  6466 E Zygote  : v2
08-17 19:16:38.315  6466  6466 I libpersona: KNOX_SDCARD not a persona
08-17 19:16:38.315  6466  6466 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-17 19:16:38.315  1012  1074 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6466 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-17 19:16:38.325  1012  1024 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:16:38.325  1012  1024 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:38.325  1012  1024 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:38.325  1012  1024 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms,
08-17 19:16:38.325  6466  6466 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-17 19:16:38.325  6466  6466 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-17 19:16:38.345  1012  1497 I ActivityManager: Process com.android.bluetooth (pid 2650)(adj 0) has died(41,1100)
,08-17 19:16:38.355  6466  6466 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:38.355  6466  6466 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:38.365  6466  6466 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-17 19:16:38.405  1012  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-17 19:16:38.405  1012  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-17 19:16:38.405  1012  1126 E WifiConfigStore: setLastSelectedConfiguration -1
,08-17 19:16:38.405  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:16:38.405  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-17 19:16:38.405  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:38.405  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:38.405  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:38.405  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:38.415  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 19:16:38.415  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-17 19:16:38.415  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 19:16:38.415  1173  1707 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-17 19:16:38.415  1173  1173 D HotspotTile: onReceive : 1, 0
,08-17 19:16:38.415  1906  2123 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 19:16:38.415  1312  1312 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-17 19:16:38.415  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:38.415  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:38.465  1012  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 19:16:38.475  1012  1012 I ApplicationPolicy: updateDataUsageMap
,08-17 19:16:38.485  3144  3144 I DBG_DM  : [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,08-17 19:16:38.485  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:38.485  1012  1036 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-17 19:16:38.485  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:38.485  3144  3144 I DBG_DM  : [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,08-17 19:16:38.515   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-17 19:16:38.555  6466  6493 I Babel   : MmsConfig: mnc/mcc: 0/0
,08-17 19:16:38.555  6466  6493 I Babel   : MmsConfig.loadMmsSettings
08-17 19:16:38.555  6466  6493 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
08-17 19:16:38.555  6466  6493 I Babel   : MmsConfig.loadFromDatabase
,08-17 19:16:38.565  1012  1540 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-17 19:16:38.565  1012  1540 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-17 19:16:38.565  1012  1540 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:38.565  1012  1540 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:38.565  1012  1540 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-17 19:16:38.575  6466  6466 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 19:16:38.575  6466  6493 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-17 19:16:38.575  6466  6493 I Babel   : MmsConfig.loadFromResources
,08-17 19:16:38.585  6466  6493 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,08-17 19:16:38.585  6466  6493 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,08-17 19:16:38.635  6466  6466 I Babel_StickerModule: App launched.
,08-17 19:16:38.645  1312  1312 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-17 19:16:38.645  1312  1312 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-17 19:16:38.645  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-17 19:16:38.645  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-17 19:16:38.645  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 19:16:38.645  1312  1312 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-17 19:16:38.645  1312  3094 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 19:16:38.645   282   282 W QCamera2Factory: getCameraInfo: E, camera_id = 0
,08-17 19:16:38.645   282   282 W QCamera2Factory: getCameraInfo: X
08-17 19:16:38.645  1012  1074 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-17 19:16:38.645  1012  1074 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:38.645  1012  1074 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:38.645  1012  1074 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:38.645  1012  1074 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:38.655   282   684 W QCamera2Factory: getCameraInfo: E, camera_id = 1
08-17 19:16:38.655   282   684 W QCamera2Factory: getCameraInfo: X
,08-17 19:16:38.665  6495  6495 E Zygote  : MountEmulatedStorage()
08-17 19:16:38.665  6495  6495 E Zygote  : v2
08-17 19:16:38.665  6495  6495 I libpersona: KNOX_SDCARD checking this for 10068
08-17 19:16:38.665  6495  6495 I libpersona: KNOX_SDCARD not a persona
08-17 19:16:38.665  6495  6495 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-17 19:16:38.665  1012  1074 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6495 uid=10068 gids={50068, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-17 19:16:38.665  6495  6495 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-17 19:16:38.665  6495  6495 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:16:38.685  6466  6466 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-17 19:16:38.685  6466  6466 W AudioCapabilities: Unsupported mime audio/evrc
,08-17 19:16:38.685  6466  6466 W AudioCapabilities: Unsupported mime audio/qcelp
,08-17 19:16:38.685  6495  6495 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:38.695  6495  6495 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:38.695  6466  6466 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-17 19:16:38.695  6466  6466 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-17 19:16:38.715  6495  6495 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-17 19:16:38.715  6466  6466 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-17 19:16:38.715  6466  6466 W AudioCapabilities: Unsupported mime audio/x-ima
,08-17 19:16:38.715  6466  6466 W AudioCapabilities: Unsupported mime audio/qcelp
,08-17 19:16:38.715  6466  6466 W AudioCapabilities: Unsupported mime audio/evrc
,08-17 19:16:38.725  6466  6466 W VideoCapabilities: Unsupported mime video/wvc1
,08-17 19:16:38.725  6466  6466 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-17 19:16:38.735  6495  6495 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-17 19:16:38.735  6495  6495 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-17 19:16:38.735  6466  6466 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-17 19:16:38.735  6466  6466 W VideoCapabilities: Unsupported mime video/wvc1
,08-17 19:16:38.745  6466  6466 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-17 19:16:38.745  6466  6466 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-17 19:16:38.745  6466  6466 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-17 19:16:38.745  6466  6466 W VideoCapabilities: Unsupported mime video/mp43
,08-17 19:16:38.755  6466  6466 W VideoCapabilities: Unsupported mime video/sorenson
,08-17 19:16:38.755  6466  6466 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-17 19:16:38.775  6495  6495 D FileShare-Client: Outbound.stopDelayTimer - 
,08-17 19:16:38.775  1012  1025 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-17 19:16:38.775  6466  6466 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-17 19:16:38.775  1012  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:38.775  1012  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:38.775  1012  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:38.775  1012  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:38.785  6510  6510 E Zygote  : MountEmulatedStorage(),
08-17 19:16:38.785  1012  1025 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6510 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-17 19:16:38.785  1012  1025 I ActivityManager: Killing 5819:com.samsung.android.sm/1000 (adj 15): empty #31
08-17 19:16:38.795  6510  6510 E Zygote  : v2
,08-17 19:16:38.795  6510  6510 I libpersona: KNOX_SDCARD checking this for 10069
08-17 19:16:38.795  6510  6510 I libpersona: KNOX_SDCARD not a persona,
,08-17 19:16:38.795  6510  6510 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,08-17 19:16:38.795  6510  6510 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-17 19:16:38.805  6510  6510 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:16:38.815  6510  6510 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:38.815  6510  6510 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:38.825  1012  1478 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,08-17 19:16:38.825  1012  1478 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,08-17 19:16:38.825  1012  1478 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:38.825  1012  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:38.825  1012  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-17 19:16:38.845  1012  1074 I ActivityManager: Killing 5154:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,08-17 19:16:38.855  6510  6510 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-17 19:16:38.855  1012  1221 I ActivityManager: Killing 5611:com.google.android.apps.plus/u0a120 (adj 15): empty #31
,08-17 19:16:38.865  1012  2929 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 19:16:38.865  1012  2929 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 19:16:38.865  1012  2929 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:38.865  1012  2929 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:38.865  1012  2929 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 19:16:38.865  1312  1312 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-17 19:16:38.865  3642  3642 I Hs20UtilService: Starting #9
08-17 19:16:38.865  1312  1312 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-17 19:16:38.865  3642  3679 I Hs20UtilService: Message received 5007
08-17 19:16:38.865  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-17 19:16:38.875  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-17 19:16:38.875  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 19:16:38.875  1312  1312 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-17 19:16:38.875  1312  3094 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 19:16:38.875  1012  1074 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-17 19:16:38.875  1012  1074 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 19:16:38.875  1012  1074 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:38.875  1012  1074 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:38.875  1012  1074 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 19:16:38.885  3642  3642 I Hs20UtilService: Starting #10
08-17 19:16:38.885  3642  3679 I Hs20UtilService: Message received 5011
,08-17 19:16:38.885  1012  1478 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,08-17 19:16:38.885  1012  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:38.885  1012  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:38.885  1012  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:38.885  1012  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:38.895  6526  6526 E Zygote  : MountEmulatedStorage()
,08-17 19:16:38.895  6526  6526 E Zygote  : v2
08-17 19:16:38.895  6526  6526 I libpersona: KNOX_SDCARD checking this for 1000
08-17 19:16:38.895  6526  6526 I libpersona: KNOX_SDCARD not a persona
,08-17 19:16:38.895  6526  6526 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-17 19:16:38.895  1012  1478 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6526 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,08-17 19:16:38.895  6526  6526 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-17 19:16:38.895  6526  6526 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:16:38.915  6526  6526 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:38.915  6526  6526 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:38.945  1012  1039 D Tethering: interfaceRemoved wlan0
08-17 19:16:38.945  1012  1039 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-17 19:16:38.945  6526  6526 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-17 19:16:38.955  6526  6526 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-17 19:16:38.955  6526  6526 D SecurityLogAgent: StateMachine : Current State = 1
,08-17 19:16:38.955  6526  6526 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 19:16:38.955  1012  1478 I ActivityManager: Killing 5865:com.sec.pcw.device/1000 (adj 15): empty #31
,08-17 19:16:38.965  1012  1478 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:38.965  1012  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:38.965  1012  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:16:39.035  1012  1012 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:39.035  1012  1012 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:39.035  1012  1012 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:16:39.035  1012  1012 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:39.035  1012  1012 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:39.035  1012  1012 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:16:39.035  1012  1012 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:39.035  1012  1012 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:39.035  1012  1012 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:16:39.045  1012  1012 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:39.045  1012  1012 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:39.045  1012  1012 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:16:39.045  1012  1012 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:39.045  1012  1012 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:39.045  1012  1012 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:16:39.045  1012  1012 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:39.045  1012  1012 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:39.045  1012  1012 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:16:39.045  1012  1012 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:39.045  1012  1012 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:39.045  1012  1012 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:16:39.055  1012  1012 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:39.055  1012  1012 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:39.055  1012  1012 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:16:39.055  1012  1012 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:39.055  1012  1012 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:39.055  1012  1012 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:16:39.055  1012  1012 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:39.055  1012  1012 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:39.055  1012  1012 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:16:39.055  1012  1012 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:39.055  1012  1012 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:39.055  1012  1012 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:16:39.065  1012  1012 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:39.065  1012  1012 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:39.065  1012  1012 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:16:39.065  1012  1012 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:39.065  1012  1012 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:39.065  1012  1012 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:16:39.065  1012  1012 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:39.065  1012  1012 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:39.065  1012  1012 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 19:16:39.075  1312  1312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 19:16:39.075  1012  1025 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-17 19:16:39.075  1012  1025 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-17 19:16:39.075  1012  1025 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:39.075  1012  1025 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:39.075  1012  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-17 19:16:39.085  1312  1312 D DockEventReceiver: finishStartingService: stopping service
,08-17 19:16:39.085  1312  1312 D BluetoothNotiBroadcastReceiver: onReceive
,08-17 19:16:39.095  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:39.095  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-17 19:16:39.095  1012  1074 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-17 19:16:39.095  1012  1074 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:39.095  1012  1074 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:39.095  1012  1074 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:39.095  1012  1074 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:39.105  1012  1039 D Tethering: interfaceRemoved p2p0
08-17 19:16:39.105  1012  1039 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-17 19:16:39.115  1012  1074 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6543 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-17 19:16:39.115  6543  6543 E Zygote  : MountEmulatedStorage()
08-17 19:16:39.115  6543  6543 E Zygote  : v2
08-17 19:16:39.115  6543  6543 I libpersona: KNOX_SDCARD checking this for 1002
08-17 19:16:39.115  6543  6543 I libpersona: KNOX_SDCARD not a persona
,08-17 19:16:39.115  6543  6543 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-17 19:16:39.125  6543  6543 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-17 19:16:39.125  6543  6543 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-17 19:16:39.145  6543  6543 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 19:16:39.145  6543  6543 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:39.155  6543  6543 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-17 19:16:39.165  6543  6543 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-17 19:16:39.195  6543  6543 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-17 19:16:39.235  6543  6543 D BtSettings.ProfileConfig: Adding GattService
,08-17 19:16:39.235  6543  6543 D BtSettings.ProfileConfig: Adding HeadsetService
,08-17 19:16:39.235  6543  6543 D BtSettings.ProfileConfig: Adding A2dpService
,08-17 19:16:39.235  6543  6543 D BtSettings.ProfileConfig: Adding HidService
,08-17 19:16:39.245  6543  6543 D BtSettings.ProfileConfig: Adding HealthService
,08-17 19:16:39.245  6543  6543 D BtSettings.ProfileConfig: Adding PanService
,08-17 19:16:39.245  6543  6543 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-17 19:16:39.245  6543  6543 D BtSettings.ProfileConfig: Adding SapService
,08-17 19:16:39.245  6543  6543 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-17 19:16:39.245  6543  6543 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-17 19:16:39.245  6543  6543 D BtSettings.ProfileConfig: Adding SapClientService
,08-17 19:16:39.245  6543  6543 D BtSettings.ProfileConfig: Adding HidDevService
,08-17 19:16:39.245  6543  6543 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-17 19:16:39.245  1012  1478 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-17 19:16:39.245  1012  1478 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:39.245  1012  1478 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-17 19:16:39.245  1012  1478 D SettingsProvider: selectionArgs: false
08-17 19:16:39.245  1012  1478 D SettingsProvider: selectionArgs: 1002
,08-17 19:16:39.255  1012  1478 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:39.255  1012  1478 D SettingsProvider: ret = -1
,08-17 19:16:39.255  1012  1360 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,08-17 19:16:39.255  1012  1360 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:39.255  1012  1360 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:39.255  1012  1360 D SettingsProvider: selectionArgs: false
,08-17 19:16:39.255  1012  1360 D SettingsProvider: selectionArgs: 1002
08-17 19:16:39.255  1012  1360 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-17 19:16:39.255  1012  1360 D SettingsProvider: ret = -1
,08-17 19:16:39.255  1012  1497 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,08-17 19:16:39.255  1012  1497 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:39.255  1012  1497 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:39.255  1012  1497 D SettingsProvider: selectionArgs: false
08-17 19:16:39.255  1012  1497 D SettingsProvider: selectionArgs: 1002
,08-17 19:16:39.255  1012  1497 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-17 19:16:39.255  1012  1497 D SettingsProvider: ret = -1
,08-17 19:16:39.255  1012  1540 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
,08-17 19:16:39.255  1012  1540 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-17 19:16:39.255  1012  1540 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-17 19:16:39.255  1012  1540 D SettingsProvider: selectionArgs: false
08-17 19:16:39.255  1012  1540 D SettingsProvider: selectionArgs: 1002
08-17 19:16:39.255  1012  1540 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:39.255  1012  1540 D SettingsProvider: ret = -1
08-17 19:16:39.255  1012  1024 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-17 19:16:39.255  1012  1024 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:39.255  1012  1024 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:39.255  1012  1024 D SettingsProvider: selectionArgs: false
08-17 19:16:39.255  1012  1024 D SettingsProvider: selectionArgs: 1002
08-17 19:16:39.255  1012  1024 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:39.255  1012  1024 D SettingsProvider: ret = -1
08-17 19:16:39.255  1012  2930 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-17 19:16:39.255  1012  2930 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:39.255  1012  2930 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:39.255  1012  2930 D SettingsProvider: selectionArgs: false
08-17 19:16:39.255  1012  2930 D SettingsProvider: selectionArgs: 1002
08-17 19:16:39.255  1012  2930 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:39.255  1012  2930 D SettingsProvider: ret = -1
08-17 19:16:39.255  1012  1541 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-17 19:16:39.255  1012  1541 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:39.255  1012  1541 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:39.255  1012  1541 D SettingsProvider: selectionArgs: false
08-17 19:16:39.255  1012  1541 D SettingsProvider: selectionArgs: 1002
08-17 19:16:39.255  1012  1541 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:39.255  1012  1541 D SettingsProvider: ret = -1
08-17 19:16:39.255  1012  1074 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-17 19:16:39.255  1012  1074 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:39.255  1012  1074 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:39.255  1012  1074 D SettingsProvider: selectionArgs: false
08-17 19:16:39.255  1012  1074 D SettingsProvider: selectionArgs: 1002
08-17 19:16:39.255  1012  1074 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:39.255  1012  1074 D SettingsProvider: ret = -1
08-17 19:16:39.255  1012  1025 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:16:39.255  1012  1025 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:39.255  1012  1025 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:39.255  1012  1025 D SettingsProvider: selectionArgs: false
08-17 19:16:39.255  1012  1025 D SettingsProvider: selectionArgs: 1002
08-17 19:16:39.255  1012  1025 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:39.255  1012  1025 D SettingsProvider: ret = -1
08-17 19:16:39.265  1012  1221 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:16:39.265  1012  1221 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:39.265  1012  1221 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:39.265  1012  1221 D SettingsProvider: selectionArgs: false
08-17 19:16:39.265  1012  1221 D SettingsProvider: selectionArgs: 1002
08-17 19:16:39.265  1012  1221 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:39.265  1012  1221 D SettingsProvider: ret = -1
08-17 19:16:39.265  1012  1474 D SettingsProvider: name = bt_svc,st_com.android.bluetooth.sapclient.SapClientService
08-17 19:16:39.265  1012  1474 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:39.265  1012  1474 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:39.265  1012  1474 D SettingsProvider: selectionArgs: false
08-17 19:16:39.265  1012  1474 D SettingsProvider: selectionArgs: 1002
08-17 19:16:39.265  1012  1474 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:39.265  1012  1474 D SettingsProvider: ret = -1
08-17 19:16:39.265  1012  2929 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-17 19:16:39.265  1012  2929 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:39.265  1012  2929 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:39.265  1012  2929 D SettingsProvider: selectionArgs: false
08-17 19:16:39.265  1012  2929 D SettingsProvider: selectionArgs: 1002
08-17 19:16:39.265  1012  2929 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:39.265  1012  2929 D SettingsProvider: ret = -1
,08-17 19:16:39.275  1012  1497 I ActivityManager: Killing 5879:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,08-17 19:16:39.275  1906  1906 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-17 19:16:39.275  1012  1074 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-17 19:16:39.275  1012  1074 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-17 19:16:39.285  1012  1074 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:39.285  1012  1074 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:39.285  1012  1074 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:39.295  1906  6559 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-17 19:16:39.295  1012  1025 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:16:39.295  1906  1906 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-17 19:16:39.295  1012  1025 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:39.295  1012  1025 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-17 19:16:39.295  1012  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:39.315  1012  1025 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-17 19:16:39.315  1012  1025 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 19:16:39.315  1012  1025 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:39.315  1012  1025 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:39.315  1012  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 19:16:39.315  1012  1074 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-17 19:16:39.315  3642  3642 I Hs20UtilService: Starting #11
,08-17 19:16:39.315  3642  3679 I Hs20UtilService: Message received 5011
,08-17 19:16:39.325  1012  1074 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:39.325  1012  1074 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:39.325  1012  1074 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:39.335  6526  6526 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-17 19:16:39.335  6526  6526 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-17 19:16:39.335  6526  6526 D SecurityLogAgent: StateMachine : Current State = 1
08-17 19:16:39.335  6526  6526 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 19:16:39.335  1906  6559 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-17 19:16:39.345  1012  1025 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-17 19:16:39.345  1012  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:39.345  1012  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:39.345  1012  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:39.345  1012  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:39.355  6560  6560 E Zygote  : MountEmulatedStorage(),
08-17 19:16:39.355  1012  1025 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6560 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
08-17 19:16:39.355  6560  6560 E Zygote  : v2
08-17 19:16:39.355  6560  6560 I libpersona: KNOX_SDCARD checking this for 1000
08-17 19:16:39.355  6560  6560 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-17 19:16:39.355  6560  6560 I libpersona: KNOX_SDCARD not a persona
,08-17 19:16:39.365  6560  6560 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-17 19:16:39.365  6560  6560 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-17 19:16:39.385  6560  6560 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:39.385  6560  6560 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:39.405  6560  6560 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-17 19:16:39.405  6560  6560 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-17 19:16:39.405  6560  6560 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-17 19:16:39.425  6560  6560 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-17 19:16:39.425  6560  6560 I PCWCLIENTTRACE_PushUtil: sales region : global
,08-17 19:16:39.425  6560  6560 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,08-17 19:16:39.425  6560  6560 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-17 19:16:39.425  1012  1540 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
,08-17 19:16:39.425  1012  1540 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-17 19:16:39.435  6560  6575 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true,
08-17 19:16:39.435  1012  1540 D ActivityManager: startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,08-17 19:16:39.435  1012  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:39.435  1012  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:39.435  1012  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:39.435  1012  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:39.445  6577  6577 E Zygote  : MountEmulatedStorage()
,08-17 19:16:39.455  6577  6577 E Zygote  : v2
,08-17 19:16:39.455  6577  6577 I libpersona: KNOX_SDCARD checking this for 10111
08-17 19:16:39.455  6577  6577 I libpersona: KNOX_SDCARD not a persona
,08-17 19:16:39.455  6577  6577 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-17 19:16:39.455  1012  1540 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6577 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-17 19:16:39.455  6577  6577 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
08-17 19:16:39.465  1012  1037 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-17 19:16:39.465  6577  6577 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-17 19:16:39.465  1012  1037 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-17 19:16:39.465  1012  1037 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:39.465  1012  1037 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:39.465  1012  1037 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-17 19:16:39.485   287   287 E SMD     : DCD OFF
,08-17 19:16:39.485  6591  6591 E Zygote  : MountEmulatedStorage(),
08-17 19:16:39.485  6591  6591 E Zygote  : v2
08-17 19:16:39.485  6591  6591 I libpersona: KNOX_SDCARD checking this for 10009
08-17 19:16:39.485  6591  6591 I libpersona: KNOX_SDCARD not a persona
08-17 19:16:39.485  6591  6591 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,08-17 19:16:39.495  1012  1037 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6591 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-17 19:16:39.495  1729  1729 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-17 19:16:39.495  6591  6591 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-17 19:16:39.495  1012  1037 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,08-17 19:16:39.505  6591  6591 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-17 19:16:39.505  6577  6577 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:39.505  6577  6577 D ActivityThread: Added TimaKeyStore provider
08-17 19:16:39.505  1012  1037 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:39.505  1012  1037 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:39.505  1012  1037 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:39.505  1012  1037 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:39.515   303   303 I art     : Explicit concurrent mark sweep GC freed 8708(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 774us total 24.767ms
,08-17 19:16:39.515   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-17 19:16:39.525  6591  6591 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-17 19:16:39.525  6591  6591 D ActivityThread: Added TimaKeyStore provider,
,08-17 19:16:39.535   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 712us total 20.209ms,
,08-17 19:16:39.555   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 720us total 20.275ms,
,08-17 19:16:39.575  6607  6607 E Zygote  : MountEmulatedStorage(),
08-17 19:16:39.575  6607  6607 E Zygote  : v2,
,08-17 19:16:39.575  1012  1037 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6607 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,08-17 19:16:39.575  6607  6607 I libpersona: KNOX_SDCARD checking this for 10145
08-17 19:16:39.575  6607  6607 I libpersona: KNOX_SDCARD not a persona
,08-17 19:16:39.585  6607  6607 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-17 19:16:39.585  6607  6607 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
08-17 19:16:39.585  6607  6607 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:16:39.585  1729  1729 D accuweather: [KK AccuPhone]>>> U:4106 [0:0] getPWC : surface = 0, remote = 1
08-17 19:16:39.585  1729  1729 D accuweather: [KK AccuPhone]>>> U:4284 [0:0] Store PWC = 1
08-17 19:16:39.585  1729  1729 D accuweather: [KK AccuPhone]>>> U:4158 [0:0] addPWC = 1
08-17 19:16:39.585  1729  1729 D accuweather: [KK AccuPhone]>>> UIM:306 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-17 19:16:39.605  1729  1729 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-17 19:16:39.605  1729  1729 D accuweather: [KK AccuPhone]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,08-17 19:16:39.605  1012  1497 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
08-17 19:16:39.605  1012  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:39.605  1012  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:39.605  1012  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:39.605  1012  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:39.615  6607  6607 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 19:16:39.615  1295  1310 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 22
,08-17 19:16:39.615  6607  6607 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:39.625  1012  1497 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6622 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-17 19:16:39.625  6622  6622 E Zygote  : MountEmulatedStorage()
08-17 19:16:39.625  6622  6622 E Zygote  : v2
,08-17 19:16:39.625  6622  6622 I libpersona: KNOX_SDCARD checking this for 10081
08-17 19:16:39.625  6622  6622 I libpersona: KNOX_SDCARD not a persona
08-17 19:16:39.635  6622  6622 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-17 19:16:39.635  6622  6622 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-17 19:16:39.635  6622  6622 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,08-17 19:16:39.635  1729  1729 D accuweather: [KK AccuPhone]>>> U:4250 [0:0] Store PWC succeed
,08-17 19:16:39.655  6622  6622 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:39.655  6622  6622 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:39.655  6607  6607 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-17 19:16:39.655  6607  6607 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 19:16:39.655  6607  6607 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-17 19:16:39.655  6607  6607 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-17 19:16:39.655  6607  6607 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-17 19:16:39.675  1012  1497 I ActivityManager: Killing 5545:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31,
,08-17 19:16:39.695  3680  3680 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Aug 17 19:16:39 GMT+02:00 2016
,08-17 19:16:39.695  1012  2930 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-17 19:16:39.695  1012  2930 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-17 19:16:39.695  1012  2930 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:39.695  6577  6577 I MusicStore: Database version: 108
08-17 19:16:39.695  1012  2930 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 19:16:39.695  1012  2930 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-17 19:16:39.705  3680  3680 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,08-17 19:16:39.705  1012  1360 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-17 19:16:39.705  1012  1360 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:39.705  1012  1360 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:39.705  1012  1360 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:39.705  1012  1360 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:39.715  3680  3680 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,08-17 19:16:39.715  3680  3680 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-17 19:16:39.725  6643  6643 E Zygote  : MountEmulatedStorage()
08-17 19:16:39.725  6643  6643 I libpersona: KNOX_SDCARD checking this for 10034
08-17 19:16:39.725  6643  6643 E Zygote  : v2
08-17 19:16:39.725  6643  6643 I libpersona: KNOX_SDCARD not a persona
,08-17 19:16:39.725  1012  1474 D RCPManagerService: exchangeData() failure , invalid userId
,08-17 19:16:39.725  6643  6643 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-17 19:16:39.725  1012  1360 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6643 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
08-17 19:16:39.725  6643  6643 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-17 19:16:39.725  6643  6643 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-17 19:16:39.725  1012  1025 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
08-17 19:16:39.725  1012  1025 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-17 19:16:39.725  1012  1025 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:39.725  1012  1025 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
08-17 19:16:39.725  1012  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
08-17 19:16:39.735  3680  3680 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-17 19:16:39.735  3680  6642 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-17 19:16:39.735  3680  6642 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-17 19:16:39.735  1012  1074 D RCPManagerService: exchangeData() failure , invalid userId
,08-17 19:16:39.745  3680  6642 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-17 19:16:39.745  3680  6642 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END
,08-17 19:16:39.755  6643  6643 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:39.755  6643  6643 D ActivityThread: Added TimaKeyStore provider
08-17 19:16:39.755  3680  3680 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,08-17 19:16:39.785  6643  6643 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-17 19:16:39.795  1012  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-17 19:16:39.805  1012  2929 D RCPManagerService: exchangeData() failure , invalid userId,
,08-17 19:16:39.815  6577  6577 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-17 19:16:39.815  6577  6577 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-17 19:16:39.815  3215  6666 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,08-17 19:16:39.825  3215  6666 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-17 19:16:39.825  3215  6666 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,08-17 19:16:39.825  3215  6666 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,08-17 19:16:39.825  3215  6666 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-17 19:16:39.825  1012  1074 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-17 19:16:39.835  1012  1074 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:39.835  1012  1074 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:39.835  1012  1074 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:39.835  1012  1360 D RCPManagerService: exchangeData() failure , invalid userId
08-17 19:16:39.835  4188  4188 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-17 19:16:39.835  1012  1074 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:39.845  6667  6667 E Zygote  : MountEmulatedStorage()
08-17 19:16:39.845  6667  6667 E Zygote  : v2
08-17 19:16:39.845  6667  6667 I libpersona: KNOX_SDCARD checking this for 10113
08-17 19:16:39.845  6667  6667 I libpersona: KNOX_SDCARD not a persona
,08-17 19:16:39.845  6667  6667 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-17 19:16:39.855  1012  1074 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6667 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-17 19:16:39.855  1012  1497 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push,
08-17 19:16:39.855  1012  1497 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,08-17 19:16:39.865  1012  1497 W ActivityManager: userId = 0, bbcId = -10000,
08-17 19:16:39.865  1012  1497 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-17 19:16:39.865  1012  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,08-17 19:16:39.865  6577  6577 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
08-17 19:16:39.865  6667  6667 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-17 19:16:39.865  6667  6667 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-17 19:16:39.875  6081  6081 I SA      : [DM] init START
,08-17 19:16:39.875  4188  6674 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-17 19:16:39.885  6081  6081 I SA      : [DM] This device is not a Vodafone
,08-17 19:16:39.895  6667  6667 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:39.895  6667  6667 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:39.915  6051  6061 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge',
,08-17 19:16:39.915  1012  1540 D RCPManagerService: exchangeData() failure , invalid userId
,08-17 19:16:39.915  6081  6081 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
08-17 19:16:39.915  6081  6081 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
08-17 19:16:39.915  6081  6081 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,08-17 19:16:39.915  6081  6081 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,08-17 19:16:39.925  6081  6081 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
08-17 19:16:39.925  6081  6081 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,08-17 19:16:39.925  6081  6081 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,08-17 19:16:39.925  6051  6061 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-17 19:16:39.925  6051  6061 D BadgeProvider: sendNotify, [notify] : null
08-17 19:16:39.925  6051  6061 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-17 19:16:39.925  6051  6061 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-17 19:16:39.925  6051  6061 D BadgeProvider: update, [UpdateCount] : 1
08-17 19:16:39.925  1475  1475 D Launcher.Model: reloadBadges entered.
,08-17 19:16:39.935  1012  1221 D RCPManagerService: exchangeData() failure , invalid userId
,08-17 19:16:39.935  6081  6081 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-17 19:16:39.935  6081  6081 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,08-17 19:16:39.935  6081  6081 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,08-17 19:16:39.945  6081  6081 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,08-17 19:16:39.945  6081  6081 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,08-17 19:16:39.945  6081  6081 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
08-17 19:16:39.945  6081  6081 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,08-17 19:16:39.945  6081  6081 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,08-17 19:16:39.955  6081  6081 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
08-17 19:16:39.955  6081  6081 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,08-17 19:16:39.955  6081  6081 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,08-17 19:16:39.955  6081  6081 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,08-17 19:16:39.955  6081  6081 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,08-17 19:16:39.955  6081  6081 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,08-17 19:16:39.955  6081  6081 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,08-17 19:16:39.955  6081  6081 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
08-17 19:16:39.955  6081  6081 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,08-17 19:16:39.955  6081  6081 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,08-17 19:16:39.955  6081  6081 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,08-17 19:16:39.955  6577  6577 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-17 19:16:39.955  6577  6577 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@140eab09: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-17 19:16:39.955  6577  6577 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
08-17 19:16:39.955  6577  6577 D AndroidMusic: GMSCore installation verified
,08-17 19:16:39.965  6081  6081 I SA      : [SCU] isHaveSA() - false
08-17 19:16:39.965  6081  6081 I SA      : support phone number id : false
08-17 19:16:39.965  6081  6081 I SA      : [DM] Supports Ref Jpn : true
08-17 19:16:39.965  6081  6081 I SA      : [DM] init END
,08-17 19:16:39.965  6081  6081 I SA      : [OR] onReceive log=[SA = 2.1.0240 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOJ6 PSS = 4.978878039476607  ]
,08-17 19:16:39.965  1012  1478 D RCPManagerService: exchangeData() failure , invalid userId
,08-17 19:16:39.965  6081  6081 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
08-17 19:16:39.965  6081  6081 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-17 19:16:39.965  6081  6081 I SA      : [SLFUCHKMGR] constructor called
,08-17 19:16:39.975  1012  1025 D RCPManagerService: exchangeData() failure , invalid userId
,08-17 19:16:39.985  1012  1024 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
08-17 19:16:39.985  1012  1024 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,08-17 19:16:39.985  1012  1024 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:39.985  1012  1024 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:39.985  1012  1024 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-17 19:16:39.985  6526  6526 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-17 19:16:39.985  6526  6526 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-17 19:16:39.985  6526  6526 D SecurityLogAgent: StateMachine : Current State = 1
08-17 19:16:39.985  6526  6526 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-17 19:16:39.985  6081  6081 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-17 19:16:39.985  6081  6081 I SA      : [OR] == isSIMCardReady false ==
,08-17 19:16:39.995  6081  6081 I SA      : [SCU] == networkStateCheck == false
08-17 19:16:39.995  6081  6081 I SA      : [OR] onReceive END
,08-17 19:16:39.995  1012  1474 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,08-17 19:16:39.995  1012  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:39.995  1012  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:39.995  1012  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:39.995  1012  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:40.005  6689  6689 E Zygote  : MountEmulatedStorage()
,08-17 19:16:40.005  6689  6689 E Zygote  : v2
08-17 19:16:40.005  6689  6689 I libpersona: KNOX_SDCARD checking this for 10159
08-17 19:16:40.005  6689  6689 I libpersona: KNOX_SDCARD not a persona
,08-17 19:16:40.005  1012  1474 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=6689 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-17 19:16:40.005  6689  6689 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-17 19:16:40.015  1012  1474 I ActivityManager: Killing 5897:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
08-17 19:16:40.015  1012  1474 I ActivityManager: Killing 5578:com.sec.knox.bridge/1000 (adj 15): empty #31
,08-17 19:16:40.015  6689  6689 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
08-17 19:16:40.025  6577  6577 I ConfigStore: Config Database version: 1
08-17 19:16:40.025  1230  1230 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
08-17 19:16:40.025  6689  6689 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,08-17 19:16:40.045  6689  6689 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:40.045  6689  6689 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:40.095  1012  1497 I ActivityManager: Killing 5946:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
,08-17 19:16:40.095  1012  2930 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-17 19:16:40.105  1012  2930 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-17 19:16:40.105  1012  2930 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:40.105  1012  2930 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:40.105  1012  2930 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:40.115  3821  3821 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-17 19:16:40.115  3821  4624 I iu.UploadsManager: num queued entries: 0
,08-17 19:16:40.115  3821  4624 I iu.UploadsManager: num updated entries: 0
,08-17 19:16:40.115  3821  4624 I iu.SyncManager: NEXT; no task
,08-17 19:16:40.135   256   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
08-17 19:16:40.135   256   530 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 19:16:40.135  6577  6577 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,08-17 19:16:40.145   256   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
08-17 19:16:40.145   256   530 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 19:16:40.145  6577  6577 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,08-17 19:16:40.145   256   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
08-17 19:16:40.145   256   530 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 19:16:40.145  6577  6577 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,08-17 19:16:40.305  1012  1497 I art     : Explicit concurrent mark sweep GC freed 52101(2MB) AllocSpace objects, 11(224KB) LOS objects, 33% free, 27MB/41MB, paused 2.419ms total 146.097ms
,08-17 19:16:40.305  1012  1541 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
08-17 19:16:40.305  1012  1541 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,08-17 19:16:40.305  1012  1541 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:40.305  1012  1541 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:40.305  1012  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-17 19:16:40.315  1012  1474 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-17 19:16:40.315  1012  1474 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,08-17 19:16:40.315  1012  1474 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:40.315  1012  1474 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:40.315  1012  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-17 19:16:40.325   256   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-17 19:16:40.325   256   530 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 19:16:40.335  6667  6709 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-17 19:16:40.335   256   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-17 19:16:40.335   256   530 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 19:16:40.335  6667  6709 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-17 19:16:40.345   256   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/,
08-17 19:16:40.345   256   530 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 19:16:40.345  6667  6713 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-17 19:16:40.345  1012  1221 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
08-17 19:16:40.345  1012  1221 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-17 19:16:40.355  1012  1025 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-17 19:16:40.355  1012  1474 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-17 19:16:40.355  1012  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-17 19:16:40.355   256   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-17 19:16:40.355   256   530 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 19:16:40.355  6667  6713 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-17 19:16:40.355  1012  2930 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-17 19:16:40.365  1012  1074 I AudioService: getStreamVolume 3 index 0
,08-17 19:16:40.365  6577  6577 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,08-17 19:16:40.375  6577  6577 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,08-17 19:16:40.395  1012  1360 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-17 19:16:40.395  1012  1360 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-17 19:16:40.395  1012  1360 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:40.395  1012  1360 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:40.395  1012  1360 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-17 19:16:40.395  1012  1540 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-17 19:16:40.395  1012  1540 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,08-17 19:16:40.395  1012  1540 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:40.395  1012  1540 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:40.395  1012  1540 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-17 19:16:40.405  1012  1025 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-17 19:16:40.405  1012  1025 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,08-17 19:16:40.405  1012  1025 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:40.405  1012  1025 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-17 19:16:40.405  1012  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-17 19:16:40.415  1012  1474 I ActivityManager: Killing 5848:com.android.mms/u0a46 (adj 15): empty #31
,08-17 19:16:40.415  1012  1478 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-17 19:16:40.425  1012  1012 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-17 19:16:40.425  1012  1012 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:40.425  1012  1012 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:40.425  1012  1012 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:40.425  1012  1012 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:40.445  6717  6717 E Zygote  : MountEmulatedStorage()
08-17 19:16:40.445  6717  6717 E Zygote  : v2
08-17 19:16:40.445  6717  6717 I libpersona: KNOX_SDCARD checking this for 10002
08-17 19:16:40.445  6717  6717 I libpersona: KNOX_SDCARD not a persona
,08-17 19:16:40.445  6717  6717 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-17 19:16:40.445  1012  1012 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6717 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-17 19:16:40.445  6717  6717 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
08-17 19:16:40.445  6717  6717 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:16:40.465  1012  2929 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
08-17 19:16:40.465  1012  2929 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-17 19:16:40.465  6717  6717 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:40.465  1012  2929 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:40.465  1012  2929 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:40.465  1012  2929 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,08-17 19:16:40.465  6717  6717 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:40.475  6577  6577 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
,08-17 19:16:40.475  1012  2930 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
08-17 19:16:40.475  1012  2930 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-17 19:16:40.475  1012  2930 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:40.475  1012  2930 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:40.475  1012  2930 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-17 19:16:40.495  1012  1478 I ActivityManager: Killing 6038:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,08-17 19:16:40.505  1012  1360 D CountryDetector: No listener is left
,08-17 19:16:40.515   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-17 19:16:40.525  1012  1024 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:16:40.525  1012  1024 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:40.525  1012  1024 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:40.525  1012  1024 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-17 19:16:40.535  1012  1474 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-17 19:16:40.535  1012  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:40.535  1012  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:40.535  1012  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:40.535  1012  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:40.545  6667  6667 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,08-17 19:16:40.555  6749  6749 E Zygote  : MountEmulatedStorage()
08-17 19:16:40.555  6749  6749 E Zygote  : v2
08-17 19:16:40.555  6749  6749 I libpersona: KNOX_SDCARD checking this for 1000
08-17 19:16:40.555  6749  6749 I libpersona: KNOX_SDCARD not a persona
08-17 19:16:40.555  6749  6749 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-17 19:16:40.555  6749  6749 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-17 19:16:40.555  6749  6749 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
08-17 19:16:40.555  1012  1474 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6749 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,08-17 19:16:40.565  6667  6667 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 827-829)
,08-17 19:16:40.575  6667  6667 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-17 19:16:40.575  6749  6749 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 19:16:40.575  6667  6667 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1de8e3e6}
,08-17 19:16:40.575  6749  6749 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:40.575  6667  6667 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-17 19:16:40.585  6667  6667 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,08-17 19:16:40.585  1012  1540 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-17 19:16:40.585  1012  1540 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-17 19:16:40.585  1012  1540 D SecContentProvider2: mCursor = null
,08-17 19:16:40.585  1012  1540 D WifiService: setWifiEnabled: true pid=6298, uid=10155
08-17 19:16:40.585  1012  1540 W ActivityManager: Permission Denial: getCurrentUser() from pid=6298, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-17 19:16:40.585  1012  1540 W WifiService: Failed getting userId using ActivityManagerNative
08-17 19:16:40.585  1012  1540 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6298, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-17 19:16:40.585  1012  1540 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-17 19:16:40.585  1012  1540 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-17 19:16:40.585  1012  1540 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-17 19:16:40.585  1012  1540 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-17 19:16:40.585  1012  1540 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-17 19:16:40.585  1012  1540 D SettingsProvider: name = wifi_on
,08-17 19:16:40.595  1012  1126 E WifiHW  : ##################### set firmware type 0 #####################
,08-17 19:16:40.605  6667  6667 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-17 19:16:40.605  6667  6667 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-17 19:16:40.605  6667  6667 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-17 19:16:40.625  6749  6749 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-17 19:16:40.635  6667  6667 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,08-17 19:16:40.635  6667  6667 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
,08-17 19:16:40.635  6667  6667 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,08-17 19:16:40.635  6667  6667 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-17 19:16:40.635  6667  6667 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-17 19:16:40.635  6667  6667 I Adreno-EGL: Build Date: 04/06/15 Mon
08-17 19:16:40.635  6667  6667 I Adreno-EGL: Local Branch: 
08-17 19:16:40.635  6667  6667 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-17 19:16:40.635  6667  6667 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-17 19:16:40.635  6667  6667 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-17 19:16:40.735  6749  6749 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-17 19:16:40.745  6749  6749 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-17 19:16:40.755  6749  6749 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-17 19:16:40.755  6749  6749 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-17 19:16:40.755  6749  6749 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-17 19:16:40.755  6749  6749 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-17 19:16:40.755  1012  2929 I ActivityManager: Killing 5925:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty #31
,08-17 19:16:40.815  6667  6780 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-17 19:16:40.815  6667  6667 I NSApplication: Starting up...
,08-17 19:16:40.825  1012  1360 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-17 19:16:40.825  1012  1360 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:40.825  1012  1360 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:40.825  1012  1360 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:40.825  1012  1360 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:40.845  6788  6788 E Zygote  : MountEmulatedStorage(),
08-17 19:16:40.845  6788  6788 E Zygote  : v2
08-17 19:16:40.845  6788  6788 I libpersona: KNOX_SDCARD checking this for 10120
08-17 19:16:40.845  6788  6788 I libpersona: KNOX_SDCARD not a persona
08-17 19:16:40.845  6788  6788 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,08-17 19:16:40.845  1012  1360 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6788 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a,
08-17 19:16:40.845  6788  6788 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-17 19:16:40.845  1012  1360 I ActivityManager: Killing 6118:com.sec.android.app.soundalive/u0a53 (adj 15): empty #31
08-17 19:16:40.845  1012  1360 I ActivityManager: Killing 6101:com.wsomacp/u0a25 (adj 15): empty #32
,08-17 19:16:40.845  6788  6788 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-17 19:16:40.865  6788  6788 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:16:40.875  6788  6788 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:40.885  6788  6788 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-17 19:16:40.945  1012  1039 D Tethering: interfaceAdded wlan0
,08-17 19:16:40.955  1012  1039 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:16:40.955  1012  1039 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:16:40.955  1012  1039 D Tethering: interfaceStatusChanged wlan0, false
,08-17 19:16:40.955  1012  1129 E Tethering: No numeric data
,08-17 19:16:40.955  1012  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-17 19:16:40.955  1012  1129 D Tethering: clearTetheredNotification()
08-17 19:16:40.955  1012  1129 D Tethering: InitialState.processMessage what=4
,08-17 19:16:40.965  1012  1129 E Tethering: No numeric data
08-17 19:16:40.965  1012  1039 D Tethering: interfaceAdded p2p0
,08-17 19:16:40.965  1012  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-17 19:16:40.965  1012  1129 D Tethering: clearTetheredNotification()
,08-17 19:16:40.965  1012  1039 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-17 19:16:40.965  1012  1039 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-17 19:16:40.965  1012  1039 D Tethering: interfaceLinkStateChanged p2p0, false
08-17 19:16:40.965  1012  1039 D Tethering: interfaceStatusChanged p2p0, false
,08-17 19:16:40.975   277   962 I WifiHW  : wifi_change_fw_path(): fwpath = sta,
08-17 19:16:40.975   277   962 D SoftapController: Softap fwReload - Ok
,08-17 19:16:40.985   277   962 D CommandListener: Setting iface cfg
08-17 19:16:40.985   277   962 D CommandListener: Trying to bring down wlan0
,08-17 19:16:40.985   277   962 D CommandListener: Clearing all IP addresses on wlan0
,08-17 19:16:40.995  1012  1126 E WifiHW  : supplicant_name : p2p_supplicant
,08-17 19:16:40.995  1012  1126 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-17 19:16:40.995  1012  1126 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,08-17 19:16:41.025  1012  1123 D NtpTrustedTime: currentTimeMillis() cache hit,
08-17 19:16:41.025  1012  1123 V NetworkStats: performPollLocked(flags=0x1)
08-17 19:16:41.025  1012  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 19:16:41.025  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED,
08-17 19:16:41.025  1012  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-17 19:16:41.025  1173  1173 D HotspotTile: updateTetherState():false, false
,08-17 19:16:41.025  1012  1123 V NetworkStats: performPollLocked() took 4ms
08-17 19:16:41.025  1012  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:41.035  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:16:41.035  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 19:16:41.035  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-17 19:16:41.035  1173  1707 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-17 19:16:41.035  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:41.035  1173  1173 D HotspotTile: onReceive : 2, 0
08-17 19:16:41.035  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:41.035  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:41.035  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:41.035  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 19:16:41.035  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2),
08-17 19:16:41.035  1312  1312 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-17 19:16:41.045  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-17 19:16:41.045  1012  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:41.045  1012  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:41.045  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:41.045  6808  6808 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL,
08-17 19:16:41.045  6808  6808 I wpa_supplicant: Successfully initialized wpa_supplicant
08-17 19:16:41.045  6808  6808 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-17 19:16:41.065  6808  6808 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
,08-17 19:16:41.065   367   367 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6808,
08-17 19:16:41.065   367   367 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-17 19:16:41.065  6808  6808 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-17 19:16:41.065  6808  6808 I wpa_supplicant: ssSupport state is = 1
08-17 19:16:41.065  6808  6808 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
,08-17 19:16:41.065  6808  6808 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-17 19:16:41.065   367   367 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6808
08-17 19:16:41.065   367   367 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-17 19:16:41.225   367   367 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,08-17 19:16:41.235  6808  6808 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed,
,08-17 19:16:41.245  1012  2930 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-17 19:16:41.255  1012  2930 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:41.255  1012  2930 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:41.255  1012  2930 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:41.255  1012  2930 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:41.265  6814  6814 E Zygote  : MountEmulatedStorage()
08-17 19:16:41.265  6814  6814 E Zygote  : v2
08-17 19:16:41.265  6814  6814 I libpersona: KNOX_SDCARD checking this for 10125
08-17 19:16:41.265  6814  6814 I libpersona: KNOX_SDCARD not a persona
,08-17 19:16:41.265  6814  6814 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-17 19:16:41.265  6814  6814 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-17 19:16:41.275  6814  6814 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-17 19:16:41.275  1012  2930 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6814 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
08-17 19:16:41.275  1012  2930 I ActivityManager: Killing 5914:com.google.android.apps.docs/u0a91 (adj 15): empty #31
,08-17 19:16:41.305  6808  6808 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-17 19:16:41.305  6808  6808 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
08-17 19:16:41.305  6814  6814 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 19:16:41.305  6814  6814 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:41.315  6808  6808 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,08-17 19:16:41.315   367   367 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6808
08-17 19:16:41.315   367   367 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-17 19:16:41.315  6808  6808 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-17 19:16:41.315  6808  6808 I wpa_supplicant: ssSupport state is = 1
08-17 19:16:41.315  6808  6808 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-17 19:16:41.315  6808  6808 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 19:16:41.315  6808  6808 E wpa_supplicant: SIM READ ERROR
08-17 19:16:41.315  6808  6808 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 19:16:41.315  6808  6808 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 19:16:41.315  6808  6808 E wpa_supplicant: SIM READ ERROR
08-17 19:16:41.315  6808  6808 I wpa_supplicant: Blacklist: Clear (all) 
08-17 19:16:41.315  6808  6808 I wpa_supplicant: wpa_default_ap_write_once
08-17 19:16:41.315  6808  6808 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-17 19:16:41.315  6808  6808 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 19:16:41.315  6814  6814 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 19:16:41.315  6808  6808 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-17 19:16:41.315  6808  6808 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 19:16:41.315  6814  6814 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-17 19:16:41.315  6808  6808 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 19:16:41.315  6814  6814 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-17 19:16:41.315  6808  6808 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-17 19:16:41.325  1012  1039 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:16:41.325  1012  1039 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:16:41.325  1012  1039 D Tethering: interfaceStatusChanged wlan0, false
,08-17 19:16:41.335  6814  6814 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-17 19:16:41.335  6814  6814 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-17 19:16:41.335  6814  6814 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-17 19:16:41.335  1012  1478 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-17 19:16:41.335  1012  1478 I ActivityManager: Killing 6156:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,08-17 19:16:41.345  1012  1025 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-17 19:16:41.345  1012  1025 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 19:16:41.345  1012  1025 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:41.345  1012  1025 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:41.345  1012  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 19:16:41.355  3642  3642 I Hs20UtilService: Starting #12,
08-17 19:16:41.355  3642  3679 I Hs20UtilService: Message received 5011
08-17 19:16:41.355  6526  6526 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-17 19:16:41.355  6526  6526 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-17 19:16:41.355  6526  6526 D SecurityLogAgent: StateMachine : Current State = 1
08-17 19:16:41.355  6526  6526 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 19:16:41.445  6808  6808 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-17 19:16:41.515   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-17 19:16:41.555  6808  6808 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-17 19:16:41.555  6808  6808 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,08-17 19:16:41.565  6808  6808 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-17 19:16:41.565   367   367 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6808
08-17 19:16:41.565   367   367 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,08-17 19:16:41.575  6808  6808 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-17 19:16:41.575  6808  6808 I wpa_supplicant: ssSupport state is = 1,
08-17 19:16:41.575  6808  6808 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-17 19:16:41.575  6808  6808 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-17 19:16:41.585  6808  6808 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-17 19:16:41.585   367   367 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6808
08-17 19:16:41.585   367   367 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,08-17 19:16:41.585  6808  6808 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-17 19:16:41.585  6808  6808 I wpa_supplicant: ssSupport state is = 1
08-17 19:16:41.585  1012  1039 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-17 19:16:41.585  6808  6808 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 19:16:41.585  6808  6808 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 19:16:41.585  6808  6808 E wpa_supplicant: SIM READ ERROR
08-17 19:16:41.585  6808  6808 I wpa_supplicant: wpa_default_ap_write_once
08-17 19:16:41.585  6808  6808 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-17 19:16:41.585  6808  6808 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-17 19:16:41.585  1012  1039 D Tethering: interfaceLinkStateChanged p2p0, false
08-17 19:16:41.585  1012  1039 D Tethering: interfaceStatusChanged p2p0, false
,08-17 19:16:41.595  1012  1039 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-17 19:16:41.595  1012  1039 D Tethering: interfaceLinkStateChanged p2p0, false
,08-17 19:16:41.595  1012  1039 D Tethering: interfaceStatusChanged p2p0, false
,08-17 19:16:41.725  6808  6808 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-17 19:16:41.725  6808  6808 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-17 19:16:41.775  6808  6808 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-17 19:16:41.775  6808  6808 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-17 19:16:41.775  6808  6808 I wpa_supplicant: Skip scan - bUseNetwork false,
,08-17 19:16:41.955  1012  1039 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-17 19:16:41.955  1012  1039 D Tethering: interfaceLinkStateChanged p2p0, false
08-17 19:16:41.955  1012  1039 D Tethering: interfaceStatusChanged p2p0, false,
08-17 19:16:41.955  1012  1953 V SAMP_SPCM_test: CSC File load.. 
,08-17 19:16:41.965  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,08-17 19:16:41.965  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
08-17 19:16:41.965  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
,08-17 19:16:41.965  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
08-17 19:16:41.965  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
,08-17 19:16:41.965  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
08-17 19:16:41.965  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
,08-17 19:16:41.965  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
08-17 19:16:41.965  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
,08-17 19:16:41.965  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
08-17 19:16:41.965  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
,08-17 19:16:41.965  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
08-17 19:16:41.965  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
,08-17 19:16:41.965  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
08-17 19:16:41.965  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn,
08-17 19:16:41.965  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
,08-17 19:16:41.965  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
08-17 19:16:41.975  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
,08-17 19:16:41.975  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
08-17 19:16:41.975  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
08-17 19:16:41.975  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,08-17 19:16:41.995  1012  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-17 19:16:42.005  1012  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21],
08-17 19:16:42.005  6808  6808 I wpa_supplicant: HOTSPOT20_ENABLE called
08-17 19:16:42.005  6808  6808 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 19:16:42.005  6808  6808 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 19:16:42.005  6808  6808 E wpa_supplicant: SIM READ ERROR
,08-17 19:16:42.005  6808  6808 I wpa_supplicant: Blacklist: Clear (all) 
,08-17 19:16:42.005  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
08-17 19:16:42.005  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
,08-17 19:16:42.005  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
08-17 19:16:42.005  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
08-17 19:16:42.005  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
,08-17 19:16:42.005  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
08-17 19:16:42.005  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
08-17 19:16:42.005  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
08-17 19:16:42.005  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
08-17 19:16:42.005  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
,08-17 19:16:42.005  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
08-17 19:16:42.005  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
08-17 19:16:42.005  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
08-17 19:16:42.005  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
08-17 19:16:42.005  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
,08-17 19:16:42.005  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
08-17 19:16:42.005  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
08-17 19:16:42.005  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
08-17 19:16:42.005  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
08-17 19:16:42.005  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
08-17 19:16:42.005  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time,
,08-17 19:16:42.025  6808  6808 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-17 19:16:42.025  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
08-17 19:16:42.025  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
08-17 19:16:42.025  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
08-17 19:16:42.025  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
,08-17 19:16:42.025  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
08-17 19:16:42.025  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
08-17 19:16:42.025  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
,08-17 19:16:42.025  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
08-17 19:16:42.025  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
08-17 19:16:42.025  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
08-17 19:16:42.025  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
08-17 19:16:42.025  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
,08-17 19:16:42.025  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
08-17 19:16:42.025  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
08-17 19:16:42.025  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
08-17 19:16:42.025  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
08-17 19:16:42.025  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
08-17 19:16:42.025  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
08-17 19:16:42.025  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
,08-17 19:16:42.025  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
08-17 19:16:42.025  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
08-17 19:16:42.025  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
08-17 19:16:42.025  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
08-17 19:16:42.025  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
08-17 19:16:42.025  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
08-17 19:16:42.025  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
08-17 19:16:42.025  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
,08-17 19:16:42.025  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
08-17 19:16:42.025  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
08-17 19:16:42.025  1012  1953 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
08-17 19:16:42.025  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
,08-17 19:16:42.025  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
08-17 19:16:42.025  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
08-17 19:16:42.025  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
,08-17 19:16:42.025  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
08-17 19:16:42.025  1012  1953 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:42.025  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
,08-17 19:16:42.025  1012  1953 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-17 19:16:42.025  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
08-17 19:16:42.025  1012  1953 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:42.025  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
08-17 19:16:42.025  1012  1953 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-17 19:16:42.025  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
08-17 19:16:42.025  1012  1953 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
08-17 19:16:42.035  6808  6808 I wpa_supplicant: Skip scan - bUseNetwork false
,08-17 19:16:42.045  1012  1953 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=6833 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
08-17 19:16:42.045  6833  6833 E Zygote  : MountEmulatedStorage()
08-17 19:16:42.045  6833  6833 E Zygote  : v2
08-17 19:16:42.045  6833  6833 I libpersona: KNOX_SDCARD checking this for 1000
08-17 19:16:42.045  6833  6833 I libpersona: KNOX_SDCARD not a persona
,08-17 19:16:42.045  1012  1126 D WifiNative-wlan0: callSECApiInt - ID [210]
08-17 19:16:42.045  6833  6833 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-17 19:16:42.045  6833  6833 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-17 19:16:42.045  1012  1126 D WifiConfigStore: Loading config and enabling all networks 
,08-17 19:16:42.055  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:16:42.055  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 19:16:42.055  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:42.055  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:42.055  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:42.055  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:42.055  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 19:16:42.055  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-17 19:16:42.055  1173  1707 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-17 19:16:42.055  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-17 19:16:42.055  1173  1173 D HotspotTile: onReceive : 3, 0
,08-17 19:16:42.055  1312  1312 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-17 19:16:42.055  6833  6833 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-17 19:16:42.055  6298  6298 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:42.055  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:42.055  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:42.055  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:42.055  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:42.055  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:16:42.055  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:42.055  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:42.055  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 19:16:42.055  6298  6298 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 19:16:42.055  6298  6298 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:16:42.065  1012  1074 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 19:16:42.065  1012  1074 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 19:16:42.065  1012  1074 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:42.065  1012  1074 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:42.065  1012  1074 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 19:16:42.065  6298  6298 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:42.065  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:42.065  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:42.065  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:42.065  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:42.065  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:16:42.065  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:42.065  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:42.065  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 19:16:42.065  6298  6298 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:42.065  6298  6298 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:16:42.065  3642  3642 I Hs20UtilService: Starting #13
,08-17 19:16:42.065  3642  3679 I Hs20UtilService: Message received 5011
,08-17 19:16:42.075  6526  6526 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-17 19:16:42.075  6526  6526 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-17 19:16:42.075  6526  6526 D SecurityLogAgent: StateMachine : Current State = 1
08-17 19:16:42.075  6526  6526 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 19:16:42.075  1012  1126 E WifiConfigStore: Not a HS20
,08-17 19:16:42.075  1012  1126 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-17 19:16:42.085  1012  1126 D WifiNative-wlan0: callSECApiInt - ID [65]
08-17 19:16:42.085  1012  1126 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-17 19:16:42.085  6808  6808 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-17 19:16:42.085  6808  6808 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-17 19:16:42.085  6808  6808 I wpa_supplicant: reset timer : RESET_TIMER 0
08-17 19:16:42.085  6808  6808 I wpa_supplicant: P2P: Current p2p state = IDLE
08-17 19:16:42.085  6808  6808 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-17 19:16:42.085  6808  6808 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-17 19:16:42.085  6808  6808 I wpa_supplicant: First Scan Start
08-17 19:16:42.085  6833  6833 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 19:16:42.085  6808  6808 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-17 19:16:42.085  6833  6833 D ActivityThread: Added TimaKeyStore provider
08-17 19:16:42.085  1012  1126 D WifiNative-wlan0: Setting external_sim to 1
08-17 19:16:42.085  1012  1126 D WifiStateMachine: Setting OUI to DA-A1-19
08-17 19:16:42.085  1012  1126 I WifiNative-HAL: startHal
08-17 19:16:42.085  1012  1126 E wifi    : getStaticLongField sWifiHalHandle 0x9ca2a88c
08-17 19:16:42.085  1012  1126 I WifiNative-HAL: Could not start hal
08-17 19:16:42.085  6466  6466 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 19:16:42.085  1012  1126 E WifiNative-wlan0: do suspend true
,08-17 19:16:42.095  1012  1125 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-17 19:16:42.095  1012  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-17 19:16:42.095  1012  1012 D WifiScanningService: SCAN_AVAILABLE : 3
08-17 19:16:42.095  1012  1125 D WifiP2pService: P2pEnablingState
08-17 19:16:42.095  1012  1148 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-17 19:16:42.095  1012  1125 D WifiP2pService: P2pEnablingState{ what=147457 }
08-17 19:16:42.095  1012  1148 I WifiNative-HAL: startHal
08-17 19:16:42.095  1012  1125 D WifiP2pService: P2p socket connection successful
08-17 19:16:42.095  1012  1148 E wifi    : getStaticLongField sWifiHalHandle 0x9dcda9bc
08-17 19:16:42.095  1012  1125 D WifiP2pService: P2pEnabledState
08-17 19:16:42.095  1012  1148 I WifiNative-HAL: Could not start hal
08-17 19:16:42.095  1012  1148 E WifiScanningService: could not start HAL
08-17 19:16:42.095  1012  1012 D RttService: SCAN_AVAILABLE : 3
08-17 19:16:42.095  1012  1149 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-17 19:16:42.095  1012  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-17 19:16:42.095  1012  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-17 19:16:42.095  1012  1126 E WifiNative-wlan0: invaild command id : 215
,08-17 19:16:42.095   277   962 D CommandListener: Setting iface cfg
08-17 19:16:42.095   277   962 D CommandListener: Trying to bring up p2p0
08-17 19:16:42.095  1012  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-17 19:16:42.095  1012  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-17 19:16:42.095  1012  1126 E WifiNative-wlan0: invaild command id : 215
08-17 19:16:42.095  1012  1125 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-17 19:16:42.105  6808  6808 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-17 19:16:42.105  6808  6808 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-17 19:16:42.105  6833  6833 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-17 19:16:42.105  6808  6808 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
08-17 19:16:42.105  1012  1128 E ConnectivityService: updateNetworkInfo()
08-17 19:16:42.105  1012  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-17 19:16:42.105  1012  1012 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-17 19:16:42.105  1012  1042 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-17 19:16:42.105  1012  1042 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-17 19:16:42.105  1012  1042 D WifiDisplayController: disconnect
08-17 19:16:42.105  1012  1042 D WifiDisplayController: updateConnection
08-17 19:16:42.105  1012  1042 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-17 19:16:42.105  1012  1042 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-17 19:16:42.105  1012  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 19:16:42.105  1012  1126 D SecContentProvider2: mCursor = null
,08-17 19:16:42.115  1012  1125 D WifiNative-p2p0: p2pGetDeviceAddress
08-17 19:16:42.115  1012  1125 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
,08-17 19:16:42.115  1312  1312 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-17 19:16:42.115  1312  1312 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-17 19:16:42.115  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-17 19:16:42.115  1012  1125 D WifiP2pService: DeviceAddress: 7e:96:ac
,08-17 19:16:42.115  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-17 19:16:42.115  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 19:16:42.115  1312  1312 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-17 19:16:42.115  1012  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 19:16:42.115  1012  1126 D SecContentProvider2: mCursor = null
08-17 19:16:42.115  1012  1042 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 19:16:42.115  1012  1042 D WifiDisplayAdapter: onP2pDisconnected
08-17 19:16:42.115  1012  1042 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-17 19:16:42.115  1012  1042 D IpRemoteDisplayController: WfdBridgeServer is already null
08-17 19:16:42.115  1012  1042 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
08-17 19:16:42.115  1012  1042 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
08-17 19:16:42.115  1012  1042 D WifiDisplayController:  primary type: 10-0050F204-5
08-17 19:16:42.115  1012  1042 D WifiDisplayController:  secondary type: null
08-17 19:16:42.115  1012  1042 D WifiDisplayController:  wps: 0
08-17 19:16:42.115  1012  1042 D WifiDisplayController:  grpcapab: 0
08-17 19:16:42.115  1012  1042 D WifiDisplayController:  devcapab: 0
08-17 19:16:42.115  1012  1042 D WifiDisplayController:  status: 3
08-17 19:16:42.115  1012  1042 D WifiDisplayController:  wfdInfo: null
08-17 19:16:42.115  1012  1042 D WifiDisplayController:  groupownerAddress: null
08-17 19:16:42.115  1012  1042 D WifiDisplayController:  GOdeviceName: null
08-17 19:16:42.115  1012  1042 D WifiDisplayController:  interfaceAddress: 
08-17 19:16:42.115  1012  1042 D WifiDisplayController:  SConnectInfo : null
,08-17 19:16:42.115  1312  3094 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 19:16:42.115  1173  1173 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-17 19:16:42.115  1012  1074 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-17 19:16:42.125  1173  1173 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-17 19:16:42.125  6495  6495 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-17 19:16:42.125  6495  6495 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-17 19:16:42.125  6495  6495 D FileShare-Client: Outbound.stopDelayTimer - 
,08-17 19:16:42.135  6510  6510 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-17 19:16:42.135  1012  1125 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-17 19:16:42.135  1012  1125 D WifiP2pService: InactiveState
,08-17 19:16:42.135  1012  1125 D WifiP2pService: InactiveState{ what=143376 }
08-17 19:16:42.135  1012  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-17 19:16:42.135  6808  6808 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
,08-17 19:16:42.135  1012  1125 D WifiP2pService: InactiveState{ what=143376 }
08-17 19:16:42.135  1012  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-17 19:16:42.145  1012  1012 I ActivityManager: Killing 6176:com.samsung.helphub/1000 (adj 15): empty #31
,08-17 19:16:42.145  1012  1953 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,08-17 19:16:42.485   287   287 E SMD     : DCD OFF,
,08-17 19:16:42.525   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-17 19:16:43.285  6808  6808 I wpa_supplicant: nl80211: Received scan results (29 BSSes),
08-17 19:16:43.285  6808  6808 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-17 19:16:43.285  6808  6808 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-17 19:16:43.285  6808  6808 I wpa_supplicant: Trying to associate with  'G700'
08-17 19:16:43.285  6808  6808 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-17 19:16:43.285  6808  6808 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-17 19:16:43.285  1012  6832 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-17 19:16:43.305  1012  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-17 19:16:43.305  1012  1126 D SecContentProvider2: mCursor = null
,08-17 19:16:43.405  6808  6808 E wpa_supplicant: Cmd 35605 not handled
,08-17 19:16:43.405  6808  6808 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-17 19:16:43.405  6808  6808 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,08-17 19:16:43.405  6808  6808 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-17 19:16:43.405  6808  6808 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-17 19:16:43.405  6808  6808 I wpa_supplicant: Associated with F4.99.3E
08-17 19:16:43.405  6808  6808 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-17 19:16:43.405  6808  6808 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE,
,08-17 19:16:43.405  1012  1039 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:16:43.405  1012  1039 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:16:43.405  1012  1039 D Tethering: interfaceStatusChanged wlan0, false
,08-17 19:16:43.405  6808  6808 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
08-17 19:16:43.415  1012  1039 D Tethering: interfaceLinkStateChanged wlan0, false
,08-17 19:16:43.415  1012  1039 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:16:43.415  1012  1039 D Tethering: interfaceStatusChanged wlan0, false
,08-17 19:16:43.415  1012  1039 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:16:43.415  1012  1039 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:16:43.415  1012  1039 D Tethering: interfaceStatusChanged wlan0, false
,08-17 19:16:43.415  6808  6808 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-17 19:16:43.415  6808  6808 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-17 19:16:43.415  1012  1039 D Tethering: interfaceLinkStateChanged wlan0, true
08-17 19:16:43.415  1012  1039 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-17 19:16:43.415  1012  1039 D Tethering: interfaceStatusChanged wlan0, true
,08-17 19:16:43.425  6808  6808 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-17 19:16:43.425  6808  6808 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,08-17 19:16:43.425  6808  6808 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-17 19:16:43.425  6808  6808 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,08-17 19:16:43.425  6808  6808 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-17 19:16:43.425  6808  6808 I wpa_supplicant: Blacklist: Clear (temp) 
08-17 19:16:43.425  6808  6808 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-17 19:16:43.425  1012  1039 D Tethering: interfaceLinkStateChanged wlan0, true
08-17 19:16:43.425  1012  1039 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-17 19:16:43.425  1012  1039 D Tethering: interfaceStatusChanged wlan0, true
08-17 19:16:43.425  1012  1129 E Tethering: No numeric data
08-17 19:16:43.425  1012  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-17 19:16:43.425  1012  1129 D Tethering: clearTetheredNotification()
,08-17 19:16:43.435  1012  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 19:16:43.435  1012  1126 D SecContentProvider2: mCursor = null
08-17 19:16:43.435  1012  1123 V NetworkStats: performPollLocked(flags=0x1)
08-17 19:16:43.435  1012  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:43.435  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-17 19:16:43.435  1173  1173 D HotspotTile: updateTetherState():false, false
08-17 19:16:43.435  1012  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 19:16:43.435  1012  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 19:16:43.435  1012  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 19:16:43.435  1012  1126 D SecContentProvider2: mCursor = null
,08-17 19:16:43.445  1012  1123 V NetworkStats: performPollLocked() took 8ms
,08-17 19:16:43.445  1012  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:43.445  1012  1126 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-17 19:16:43.445  1012  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:43.445  1012  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:43.445  1012  1126 E WifiConfigStore: setLastSelectedConfiguration -1
,08-17 19:16:43.445  1012  1126 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-17 19:16:43.445  1012  1128 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-17 19:16:43.445  1012  1128 E ConnectivityService: updateNetworkInfo()
08-17 19:16:43.445  1012  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-17 19:16:43.455  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 19:16:43.455  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 19:16:43.455  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:43.455  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:43.455  1012  1037 I ActivityManager: Killing 5983:com.google.android.gms:car/u0a12 (adj 15): empty #31
08-17 19:16:43.455  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:43.455  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:43.455  1012  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 19:16:43.465  1012  1540 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 19:16:43.465  1012  1540 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 19:16:43.465  1012  1540 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:43.465  1012  1540 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:43.465  1012  1540 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings,
08-17 19:16:43.465  3642  3642 I Hs20UtilService: Starting #14
,08-17 19:16:43.475  3642  3679 I Hs20UtilService: Message received 5007
,08-17 19:16:43.475  1312  1312 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-17 19:16:43.475  1312  1312 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-17 19:16:43.475  1012  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 19:16:43.475  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-17 19:16:43.475  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-17 19:16:43.475  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 19:16:43.475  1312  1312 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-17 19:16:43.475  1312  3094 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 19:16:43.485   277   962 D CommandListener: Setting iface cfg
,08-17 19:16:43.485  1012  1126 E WifiStateMachine: Start Dhcp Watchdog 2
,08-17 19:16:43.495  1012  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 19:16:43.495  1012  1126 D SecContentProvider2: mCursor = null
,08-17 19:16:43.495  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 19:16:43.495  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-17 19:16:43.495  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:43.505  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:43.505  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:43.505  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:43.505  1012  1126 E WifiNative-wlan0: do suspend false
,08-17 19:16:43.505  1012  1125 D WifiP2pService: InactiveState{ what=143375 }
,08-17 19:16:43.505  1012  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-17 19:16:43.505  1012  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 19:16:43.505  1012  1126 D SecContentProvider2: mCursor = null
,08-17 19:16:43.525   314   314 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-17 19:16:43.595  1012  1540 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-17 19:16:43.595  1012  1540 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-17 19:16:43.595  1012  1540 D SecContentProvider2: mCursor = null
,08-17 19:16:43.595  1012  1540 D WifiService: setWifiEnabled: false pid=6298, uid=10155
,08-17 19:16:43.595  1012  1540 D SettingsProvider: name = wifi_on
,08-17 19:16:43.605  1012  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 19:16:43.615  1012  1126 E WifiNative-wlan0: do suspend true,
,08-17 19:16:43.635  1012  1125 D WifiP2pService: InactiveState{ what=143375 },
,08-17 19:16:43.635  1012  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-17 19:16:43.645  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 19:16:43.645  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 19:16:43.645   277   962 D CommandListener: Clearing all IP addresses on wlan0
08-17 19:16:43.645  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:43.645  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:43.645  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:43.645  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:43.645  1012  1128 E ConnectivityService: updateNetworkInfo(),
08-17 19:16:43.645  1012  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-17 19:16:43.645   277   962 E Netd    : no such netId 503
08-17 19:16:43.645  1012  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
08-17 19:16:43.655  1012  1128 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '74 network destroy 503' failed with '400 74 destroyNetwork() failed (Machine is not on the network)'
,08-17 19:16:43.655  1012  1128 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null,
08-17 19:16:43.655  1012  1128 D ConnectivityService: nai.networkMonitor.doQuit()
08-17 19:16:43.655  1012  1128 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
,08-17 19:16:43.655  1012  1128 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-17 19:16:43.655  1012  1128 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-17 19:16:43.655  1012  1126 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-17 19:16:43.655  1012  1128 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent,
08-17 19:16:43.655  1012  1012 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-17 19:16:43.655  1012  1125 D WifiP2pService: InactiveState{ what=131204 }
08-17 19:16:43.655  1012  1128 E ConnectivityService: updateNetworkInfo()
08-17 19:16:43.655  1012  1125 D WifiP2pService: P2pEnabledState{ what=131204 }
,08-17 19:16:43.655  1012  1125 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-17 19:16:43.665  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-17 19:16:43.665  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 19:16:43.665  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:43.665  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:43.665  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:43.665  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:43.665  1012  1012 D WifiScanningService: SCAN_AVAILABLE : 1
08-17 19:16:43.665  1012  1148 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-17 19:16:43.665  1012  1012 D RttService: SCAN_AVAILABLE : 1
08-17 19:16:43.665  1012  1149 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-17 19:16:43.675  1012  1042 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 19:16:43.675  1012  1042 D WifiDisplayAdapter: onP2pDisconnected
08-17 19:16:43.675  1012  1042 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-17 19:16:43.675  1012  1478 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 19:16:43.675  1012  1478 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-17 19:16:43.675  1012  1042 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-17 19:16:43.675  1012  1128 E ConnectivityService: updateNetworkInfo(),
08-17 19:16:43.675  1012  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-17 19:16:43.675  1012  1478 W ActivityManager: userId = 0, bbcId = -10000,
08-17 19:16:43.675  1012  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:43.675  1012  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-17 19:16:43.675  1012  1012 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-17 19:16:43.675  3642  3642 I Hs20UtilService: Starting #15
08-17 19:16:43.675  3642  3679 I Hs20UtilService: Message received 5007
,08-17 19:16:43.675  1012  1042 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-17 19:16:43.675  1012  1042 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-17 19:16:43.675  1012  1042 D WifiDisplayController: disconnect
08-17 19:16:43.675  1012  1042 D WifiDisplayController: updateConnection
08-17 19:16:43.675  1012  1042 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-17 19:16:43.675  1012  1042 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-17 19:16:43.685  1012  1125 D WifiP2pService: P2pDisablingState
,08-17 19:16:43.685  1012  1125 D WifiP2pService: P2pDisablingState{ what=147458 }
,08-17 19:16:43.685  1012  1125 D WifiP2pService: p2p socket connection lost
,08-17 19:16:43.685  1012  1125 D WifiP2pService: P2pDisabledState
,08-17 19:16:43.685  1012  1042 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-17 19:16:43.685  1012  1042 D WifiDisplayAdapter: onP2pDisconnected
08-17 19:16:43.685  1012  1042 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-17 19:16:43.685  1012  1042 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-17 19:16:43.685  1012  1126 E WifiNative-wlan0: do suspend true
,08-17 19:16:43.685  1173  1173 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-17 19:16:43.685  1012  1541 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-17 19:16:43.695  1173  1173 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-17 19:16:43.695  1312  1312 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-17 19:16:43.695  1312  1312 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-17 19:16:43.695  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-17 19:16:43.695  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-17 19:16:43.695  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 19:16:43.695  1312  1312 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-17 19:16:43.695  1312  3094 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 19:16:43.705  1312  1312 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-17 19:16:43.705  1312  1312 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-17 19:16:43.705  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-17 19:16:43.715  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-17 19:16:43.715  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 19:16:43.715  1312  1312 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-17 19:16:43.715  1312  3094 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 19:16:43.725  1012  1125 D WifiP2pService: P2pDisabledState{ what=143375 }
08-17 19:16:43.725  1012  1125 D WifiP2pService: DefaultState{ what=143375 }
,08-17 19:16:43.725  6495  6495 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-17 19:16:43.725   277   962 D CommandListener: Clearing all IP addresses on wlan0
,08-17 19:16:43.725  6495  6495 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected,
08-17 19:16:43.725  6495  6495 D FileShare-Client: Outbound.stopDelayTimer - 
08-17 19:16:43.735  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:16:43.735  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 19:16:43.735  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:43.735  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:43.735  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:43.735  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:43.735  6855  6855 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-17 19:16:43.735  6855  6855 I dhcpcd  : version 5.5.6 starting
,08-17 19:16:43.735  6855  6855 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-17 19:16:43.735  6808  6808 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-17 19:16:43.745  1012  1012 I WifiTrafficPoller: evaluateTrafficStatsPolling,
,08-17 19:16:43.745  6510  6510 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-17 19:16:43.755  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-17 19:16:43.755  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 19:16:43.755  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:43.755  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-17 19:16:43.755  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:43.755  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:43.755  1012  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 19:16:43.755  1012  1126 D SecContentProvider2: mCursor = null
,08-17 19:16:43.755  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-17 19:16:43.755  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-17 19:16:43.755  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:43.755  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:43.755  1173  1707 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-17 19:16:43.755  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:43.755  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 19:16:43.755  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:43.755  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 19:16:43.755  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-17 19:16:43.765  1173  1173 D HotspotTile: onReceive : 0, 0
,08-17 19:16:43.765  1312  1312 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
,08-17 19:16:43.765  6298  6298 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:43.765  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:43.765  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:43.765  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:43.765  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:16:43.765  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:16:43.765  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:43.765  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:43.765  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:16:43.765  6298  6298 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:43.765  6298  6298 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:16:43.775  6298  6298 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:43.775  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:43.775  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:43.775  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:43.775  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:16:43.775  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:16:43.775  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:43.775  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:43.775  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 19:16:43.775  6298  6298 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:43.775  6298  6298 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:16:43.775  1012  1025 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-17 19:16:43.775  1012  1025 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 19:16:43.775  1012  1025 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:43.775  1012  1025 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:43.775  1012  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 19:16:43.775  3642  3642 I Hs20UtilService: Starting #16
08-17 19:16:43.775  3642  3679 I Hs20UtilService: Message received 5007
,08-17 19:16:43.785  1312  1312 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-17 19:16:43.785  1312  1312 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null,
,08-17 19:16:43.795  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED,
,08-17 19:16:43.795  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED,
,08-17 19:16:43.805  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false,
08-17 19:16:43.805  1312  1312 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-17 19:16:43.805  1312  3094 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 19:16:43.805  1012  1478 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 19:16:43.805  1012  1478 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-17 19:16:43.805  1012  1478 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:43.805  1012  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:43.805  1012  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-17 19:16:43.805  3642  3642 I Hs20UtilService: Starting #17,
,08-17 19:16:43.815  3642  3679 I Hs20UtilService: Message received 5011
,08-17 19:16:43.815  6526  6526 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-17 19:16:43.815  6526  6526 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-17 19:16:43.815  6526  6526 D SecurityLogAgent: StateMachine : Current State = 1
08-17 19:16:43.815  6526  6526 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 19:16:43.825  6855  6855 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-17 19:16:43.825  6855  6855 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-17 19:16:43.825  6855  6855 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-17 19:16:43.825  6855  6855 I dhcpcd  : bssid match
,08-17 19:16:43.825  6855  6855 I dhcpcd  : wlan0: rebinding lease of 192.168.1.111
,08-17 19:16:43.895  6808  6808 I wpa_supplicant: Blacklist: Clear (all) ,
,08-17 19:16:43.975  6855  6855 I dhcpcd  : wlan0: acknowledged 192.168.1.111 from 192.168.1.1
,08-17 19:16:44.015  6808  6808 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-17 19:16:44.015  1012  1039 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
08-17 19:16:44.015  1012  1039 D Tethering: interfaceLinkStateChanged p2p0, false
08-17 19:16:44.015  1012  1039 D Tethering: interfaceStatusChanged p2p0, false,
,08-17 19:16:44.035  6808  6808 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1,
08-17 19:16:44.045  1012  1039 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:16:44.045  1012  1039 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:16:44.045  6808  6808 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-17 19:16:44.045  6808  6808 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-17 19:16:44.045  6808  6808 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
,08-17 19:16:44.045  6808  6808 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
08-17 19:16:44.045  1012  1039 D Tethering: interfaceStatusChanged wlan0, false
08-17 19:16:44.045  1012  1129 D Tethering: InitialState.processMessage what=4
,08-17 19:16:44.045  1012  1039 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:16:44.045  1012  1126 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14956 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
08-17 19:16:44.045  1012  1039 D Tethering: interfaceStatusChanged wlan0, false
,08-17 19:16:44.045  1012  1039 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-17 19:16:44.055  1012  1129 E Tethering: No numeric data
,08-17 19:16:44.055  1012  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-17 19:16:44.055  1012  1129 D Tethering: clearTetheredNotification()
,08-17 19:16:44.055  1012  1039 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:16:44.055  1012  1039 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-17 19:16:44.055  1012  1039 D Tethering: interfaceStatusChanged wlan0, false
,08-17 19:16:44.055  6855  6855 I dhcpcd  : wlan0: leased 192.168.1.111 for 172800 seconds,
08-17 19:16:44.065  1012  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:44.065  1012  1123 V NetworkStats: performPollLocked(flags=0x1)
,08-17 19:16:44.065  1012  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 19:16:44.065  1012  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-17 19:16:44.065  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-17 19:16:44.065  1173  1173 D HotspotTile: updateTetherState():false, false
,08-17 19:16:44.065  1012  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:44.065  1012  1123 V NetworkStats: performPollLocked() took 8ms
,08-17 19:16:44.075  1012  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:44.075  1012  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:44.275  6808  6808 I wpa_supplicant: Blacklist: Clear (all) 
,08-17 19:16:44.405  6808  6808 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-17 19:16:44.405  1012  1039 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:16:44.405  1012  1039 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:16:44.405  1012  1039 D Tethering: interfaceStatusChanged wlan0, false
,08-17 19:16:44.415  1012  1039 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:16:44.415  1012  1039 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:16:44.415  1012  1039 D Tethering: interfaceStatusChanged wlan0, false
,08-17 19:16:44.515  1012  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-17 19:16:44.515  1012  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-17 19:16:44.515  1012  1126 E WifiConfigStore: setLastSelectedConfiguration -1
,08-17 19:16:44.525  6466  6466 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 19:16:44.525  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 19:16:44.525  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-17 19:16:44.525  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:44.525  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:44.525  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:44.525  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:44.525  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 19:16:44.525  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-17 19:16:44.525  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 19:16:44.525  1173  1707 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-17 19:16:44.525  1906  2123 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 19:16:44.535  1312  1312 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-17 19:16:44.535  1173  1173 D HotspotTile: onReceive : 1, 0
,08-17 19:16:44.535  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:16:44.535  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-17 19:16:44.535  1012  1478 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
08-17 19:16:44.535  1012  1478 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 19:16:44.535  1012  1478 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:44.535  1012  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:44.535  1012  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 19:16:44.545  3642  3642 I Hs20UtilService: Starting #18
,08-17 19:16:44.545  3642  3679 I Hs20UtilService: Message received 5011
,08-17 19:16:44.545  6526  6526 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-17 19:16:44.545  6526  6526 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-17 19:16:44.545  6526  6526 D SecurityLogAgent: StateMachine : Current State = 1
08-17 19:16:44.545  6526  6526 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 19:16:45.035   277   956 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,08-17 19:16:45.035  1012  1039 D Tethering: interfaceRemoved wlan0
,08-17 19:16:45.035  1012  1039 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-17 19:16:45.175  1012  1039 D Tethering: interfaceRemoved p2p0
,08-17 19:16:45.175  1012  1039 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-17 19:16:45.325  1012  2929 D ActivityManager: bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,08-17 19:16:45.325  1012  2929 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,08-17 19:16:45.325  1012  2929 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:45.325  1012  2929 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:45.325  1012  2929 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-17 19:16:45.335  6667  6711 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-17 19:16:45.345  1012  1037 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:45.345  1012  1037 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:45.345  1012  1037 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-17 19:16:45.355  1012  1541 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,08-17 19:16:45.355  1012  1541 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,08-17 19:16:45.355  1012  1541 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:45.365  1012  1541 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:45.365  1012  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-17 19:16:45.365  1012  1024 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:45.365  1012  1024 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-17 19:16:45.375  1012  1024 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-17 19:16:45.375  1012  1540 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-17 19:16:45.385  1012  1540 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,08-17 19:16:45.385  1012  1540 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:45.385  1012  1540 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-17 19:16:45.385  1012  1540 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-17 19:16:45.385  1012  2930 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-17 19:16:45.385  1012  2930 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,08-17 19:16:45.395  1012  2930 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:45.395  1012  2930 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:45.395  1012  2930 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-17 19:16:45.395  1012  1221 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-17 19:16:45.395  1012  1221 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-17 19:16:45.395  1012  1221 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:45.395  1012  1221 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-17 19:16:45.395  1012  1221 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-17 19:16:45.415  1012  1074 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,08-17 19:16:45.415  1012  1074 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,08-17 19:16:45.415  1012  1074 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:45.415  1012  1074 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-17 19:16:45.415  1012  1074 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-17 19:16:45.455  1012  1474 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:16:45.455  1012  1474 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:45.455  1012  1474 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-17 19:16:45.455  1012  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,08-17 19:16:45.465  1906  1906 D WearableService: callingUid 10012, callindPid: 1906
,08-17 19:16:45.485   287   287 E SMD     : DCD OFF
,08-17 19:16:45.495  1012  1474 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
08-17 19:16:45.495  1012  1474 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-17 19:16:45.495  1012  1474 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:45.495  1012  1474 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:45.495  1012  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-17 19:16:45.525  6577  6885 I MusicLeanback: Conditions not met for autocaching.
08-17 19:16:45.525  6577  6885 I MusicLeanback: Stop autocaching.
,08-17 19:16:45.525  6577  6577 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,08-17 19:16:45.535  6577  6890 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,08-17 19:16:45.935  1012  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-17 19:16:45.975  1012  1074 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-17 19:16:45.975  1012  1074 D BatteryService: level:93, scale:100, status:2, health:2, present:true, voltage: 4221, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,08-17 19:16:45.975  1012  1074 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,08-17 19:16:45.975  1012  1074 D BatteryService: stay LED for charging
08-17 19:16:45.975  1012  1012 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-17 19:16:45.985  1012  1012 I MotionRecognitionService: Plugged
,08-17 19:16:45.985  1012  1012 I MotionRecognitionService: mGripSensorEnabled= false
,08-17 19:16:45.985  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-17 19:16:45.985  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-17 19:16:45.985  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-17 19:16:45.985  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,08-17 19:16:46.005  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,08-17 19:16:46.005  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,08-17 19:16:46.015  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,08-17 19:16:46.605  6298  6363 D BluetoothAdapter: enable(),
,08-17 19:16:46.615  1012  1474 W ActivityManager: Permission Denial: getCurrentUser() from pid=6298, uid=10155 requires android.permission.INTERACT_ACROSS_USERS,
,08-17 19:16:46.625  1012  1474 W BluetoothManagerService: Failed getting userId using ActivityManagerNative,
08-17 19:16:46.625  1012  1474 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6298, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-17 19:16:46.625  1012  1474 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-17 19:16:46.625  1012  1474 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270),
08-17 19:16:46.625  1012  1474 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
08-17 19:16:46.625  1012  1474 W BluetoothManagerService: 	,at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
08-17 19:16:46.625  1012  1474 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
08-17 19:16:46.625  1012  1474 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 19:16:46.625  1012  1474 D SettingsProvider: name = bluetooth_on
08-17 19:16:46.625  1012  1474 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 19:16:46.625  1012  1041 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 19:16:46.635  1012  1041 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 19:16:46.635  1012  1041 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth,
08-17 19:16:46.635  1012  1041 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-17 19:16:46.665  6543  6543 D BluetoothAdapterState: make
,08-17 19:16:46.675  6543  6543 I bluedroid: init
,08-17 19:16:46.675  6543  6894 I BluetoothAdapterState: Entering OffState
,08-17 19:16:46.685  6543  6543 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-17 19:16:46.685  6543  6543 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-17 19:16:46.685  6543  6543 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-17 19:16:46.685  6543  6543 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-17 19:16:46.685  6543  6543 E bt-btif : btif_fetch_local_ble_random_bdaddr
,08-17 19:16:46.685  6543  6543 I bluedroid: get_profile_interface socket
,08-17 19:16:46.685  6543  6543 I bluedroid: get_profile_interface map_client
,08-17 19:16:46.685  6543  6543 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-17 19:16:46.685  6543  6897 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-17 19:16:46.695  6543  6543 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:16:46.695  1012  2929 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp,
08-17 19:16:46.695  1012  2929 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 19:16:46.695  1012  2929 W ActivityManager: userId = 0, bbcId = -10000,
08-17 19:16:46.695  1012  2929 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:46.695  1012  2929 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:46.705  6543  6897 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
08-17 19:16:46.705  6543  6897 E BluetoothServiceJni: populateRssiValuesNative
08-17 19:16:46.705  6543  6897 I bluedroid: getModelRssiValues
08-17 19:16:46.705  6543  6897 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-17 19:16:46.705  6543  6897 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-17 19:16:46.705  6543  6897 D BluetoothAdapterProperties: Name is: A5-1
,08-17 19:16:46.705  1012  1012 D SettingsProvider: name = bluetooth_name
,08-17 19:16:46.705  6543  6552 I bluedroid: config_hci_snoop_log
,08-17 19:16:46.705  1012  1041 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,08-17 19:16:46.715  1012  1041 D BluetoothManagerService: Ble is always on enable gatt
,08-17 19:16:46.715  1012  1041 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-17 19:16:46.715  1012  1041 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-17 19:16:46.715  1012  1041 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-17 19:16:46.715  6543  6543 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-17 19:16:46.725  1012  1041 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-17 19:16:46.725  1012  1041 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 19:16:46.725  1012  1041 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-17 19:16:46.735  6543  6894 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-17 19:16:46.735  6543  6894 D BluetoothAdapterProperties: Setting state to 11
,08-17 19:16:46.735  6543  6894 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-17 19:16:46.735  6543  6894 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-17 19:16:46.735  6543  6894 D BluetoothAdapterService: updateAdapterState state is 11
,08-17 19:16:46.735  6543  6894 D BluetoothAdapterService: Autoconnection is available 
,08-17 19:16:46.735  6543  6894 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-17 19:16:46.735  6543  6894 D BluetoothSecureManager: getInstant: null
,08-17 19:16:46.745  1012  1041 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-17 19:16:46.745  6543  6894 D BluetoothSecureManager: calling getMethod for getService
08-17 19:16:46.745  6543  6894 D BluetoothSecureManager: calling getService
,08-17 19:16:46.745  6543  6894 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@27f1c480
08-17 19:16:46.745  1012  1012 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:46.745  1012  1012 I InputMethodManagerService: [BT Setting State] State =11
08-17 19:16:46.745  1012  1497 D BluetoothSecureManagerService: isSecureModeEnabled
08-17 19:16:46.745  1012  1497 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-17 19:16:46.745  6543  6894 D BtConfig.SecureMode: isSecureModeOn:false
08-17 19:16:46.745  6543  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-17 19:16:46.755  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:46.755  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-17 19:16:46.755  6543  6894 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-17 19:16:46.755  1173  1173 D BluetoothTile:  getBluetoothState : 11
08-17 19:16:46.755  6543  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-17 19:16:46.755  6543  6894 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-17 19:16:46.755  6543  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-17 19:16:46.755  6543  6894 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
,08-17 19:16:46.755  6543  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-17 19:16:46.755  6543  6894 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-17 19:16:46.755  6543  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-17 19:16:46.755  6543  6894 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-17 19:16:46.755  6543  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-17 19:16:46.755  1012  1360 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 19:16:46.755  6543  6894 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-17 19:16:46.755  6543  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-17 19:16:46.755  1012  1497 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-17 19:16:46.765  1888  1888 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
08-17 19:16:46.765  1312  1312 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:46.765  1012  1478 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 19:16:46.765  1012  1478 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-17 19:16:46.765  6543  6894 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-17 19:16:46.765  6543  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-17 19:16:46.765  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-17 19:16:46.765  6543  6894 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-17 19:16:46.765  6543  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-17 19:16:46.765  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:16:46.765  1012  1478 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:46.765  1012  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:46.765  1012  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:46.765  6543  6894 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:16:46.765  6543  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:16:46.765  1173  1707 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 19:16:46.765  1173  1707 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-17 19:16:46.765  6543  6894 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:16:46.765  6543  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-17 19:16:46.765  6543  6894 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-17 19:16:46.765  6543  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-17 19:16:46.765  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:16:46.765  6543  6894 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-17 19:16:46.765  6543  6894 D BluetoothBondStateMachine: make
,08-17 19:16:46.775  6543  6894 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-17 19:16:46.775  1012  1474 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:46.775  6543  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-17 19:16:46.775  1012  1474 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
08-17 19:16:46.775  6543  6894 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-17 19:16:46.775  6543  6900 I BluetoothBondStateMachine: StableState(): Entering Off State
08-17 19:16:46.775  1012  1474 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:46.775  1012  1474 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:46.775  1012  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 19:16:46.775  6543  6894 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-17 19:16:46.775  6543  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-17 19:16:46.775  6543  6894 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-17 19:16:46.775  6543  6543 D BtGatt.DebugUtils: handleDebugAction() action=null
08-17 19:16:46.775  6543  6543 D BtGatt.GattService: Received start request. Starting profile...
08-17 19:16:46.775  6543  6543 D BtGatt.GattService: start()
08-17 19:16:46.775  6543  6543 D BtGatt.GattService: start()
08-17 19:16:46.775  6543  6543 I bluedroid: get_profile_interface gatt
,08-17 19:16:46.775  6543  6543 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1aa1d78b
08-17 19:16:46.775  6543  6543 D BtGatt.AdvertiseManager: advertise manager created
,08-17 19:16:46.775  1312  1312 D BluetoothNotiBroadcastReceiver: onReceive
,08-17 19:16:46.785  1012  1221 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:46.785  1012  1221 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-17 19:16:46.785  1012  1221 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:46.785  1012  1221 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:46.785  1012  1221 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:46.795  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-17 19:16:46.795  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-17 19:16:46.795  6543  6894 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-17 19:16:46.795  6543  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-17 19:16:46.795  6543  6894 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-17 19:16:46.795  1012  1541 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:16:46.795  6543  6543 D BtGatt.GattService: mStartError = false
,08-17 19:16:46.795  6543  6543 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1aa1d78b
08-17 19:16:46.795  1012  1541 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 19:16:46.795  1012  1541 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:46.795  1012  1541 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:46.795  1012  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:46.805  6543  6543 D HeadsetService: Received start request. Starting profile...
08-17 19:16:46.805  6543  6543 D HeadsetService: start()
,08-17 19:16:46.805  6543  6543 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-17 19:16:46.805  6543  6543 D HeadsetStateMachine: make
,08-17 19:16:46.805  6543  6543 E HeadsetStateMachine: # of Max HF connection is 2
,08-17 19:16:46.815  6543  6894 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-17 19:16:46.815  6543  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-17 19:16:46.815  6543  6894 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-17 19:16:46.815  1012  1360 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:46.815  1012  1360 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-17 19:16:46.815  1012  1360 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:46.815  1012  1360 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 19:16:46.815  1012  1360 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:46.815  1012  2929 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-17 19:16:46.815  1012  2929 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-17 19:16:46.815  1012  2929 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:46.815  1012  2929 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:46.815  1012  2929 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-17 19:16:46.825  6543  6894 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,08-17 19:16:46.825  1012  2930 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-17 19:16:46.825  6543  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-17 19:16:46.825  1012  2930 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
08-17 19:16:46.825  6543  6894 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-17 19:16:46.825  1012  2930 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:46.825  1012  2930 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:46.825  1012  2930 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-17 19:16:46.825  6543  6543 I bluedroid: get_profile_interface handsfree
08-17 19:16:46.825  1012  1497 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:16:46.825  1012  1497 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-17 19:16:46.825  1012  1497 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:46.825  1012  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-17 19:16:46.825  1012  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:46.825  6543  6894 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,08-17 19:16:46.825  6543  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-17 19:16:46.825  6543  6894 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-17 19:16:46.835  1012  1025 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:46.835  1012  1025 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-17 19:16:46.835  1012  1025 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:46.835  1012  1025 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:46.835  1012  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:46.845  6543  6894 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-17 19:16:46.845  6543  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 19:16:46.845  6543  6894 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-17 19:16:46.845  1012  1478 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:46.845  1012  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-17 19:16:46.845  1012  1478 W ActivityManager: userId = 0, bbcId = -10000,
08-17 19:16:46.845  1012  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:46.845  1012  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:46.845  6543  6543 I DualScoManager: Instantiating Dual Sco Manager
08-17 19:16:46.845  6543  6543 I DualScoManager: Set HeadsetServiceHelper
,08-17 19:16:46.845  6543  6543 D BluetoothAtMessage: createCMTIContentObservers
,08-17 19:16:46.845  1012  1541 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-17 19:16:46.845  1012  1541 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:46.845  1012  1541 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:46.845  1012  1541 D SettingsProvider: selectionArgs: false
08-17 19:16:46.845  1012  1541 D SettingsProvider: selectionArgs: 1002
08-17 19:16:46.845  1012  1541 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:46.845  1012  1541 D SettingsProvider: ret = -1
,08-17 19:16:46.845  6543  6904 D HeadsetStateMachine: Enter Disconnected: -2
,08-17 19:16:46.845  6543  6894 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-17 19:16:46.845  6543  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-17 19:16:46.845  6543  6543 D HeadsetService: mStartError = false
08-17 19:16:46.845  6543  6543 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1aa1d78b
,08-17 19:16:46.845  6543  6894 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-17 19:16:46.845  1012  1497 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:46.845  1012  1497 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-17 19:16:46.855  6543  6904 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-17 19:16:46.855  6543  6904 D HeadsetStateMachine: map size, before remove : 0
,08-17 19:16:46.855  6543  6904 D HeadsetStateMachine: map size, after remove: 0
08-17 19:16:46.855  1012  1497 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:46.855  1012  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:46.855  1012  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:46.855  6543  6894 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:16:46.855  6543  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:16:46.855  6543  6894 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:16:46.855  6543  6894 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:16:46.855  6543  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:16:46.855  6543  6894 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:16:46.855  6543  6894 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-17 19:16:46.855  6543  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-17 19:16:46.855  6543  6894 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-17 19:16:46.855  6543  6894 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-17 19:16:46.855  6543  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-17 19:16:46.855  6543  6894 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-17 19:16:46.855  6543  6543 E BluetoothAdapterService(446814091): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-17 19:16:46.855  6543  6894 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-17 19:16:46.855  6543  6543 D A2dpService: Received start request. Starting profile...
,08-17 19:16:46.855  6543  6543 D A2dpService: start()
,08-17 19:16:46.865  6543  6543 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-17 19:16:46.865  6543  6543 I bluedroid: get_profile_interface avrcp
,08-17 19:16:46.865  6543  6543 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-17 19:16:46.885  6543  6543 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-17 19:16:46.885  6543  6908 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-17 19:16:46.885  6543  6543 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-17 19:16:46.885  6543  6543 D A2dpStateMachine: make
,08-17 19:16:46.885  6543  6543 I bluedroid: get_profile_interface a2dp
,08-17 19:16:46.885  6543  6910 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-17 19:16:46.885  6543  6543 E bt-btif : warning : media task started media_task_refcnt 1 
,08-17 19:16:46.895  6543  6543 D A2dpService: mStartError = false
08-17 19:16:46.895  6543  6543 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1aa1d78b
,08-17 19:16:46.895  6543  6543 I BluetoothHidServiceJni: classInitNative: succeeds
,08-17 19:16:46.895  6543  6909 D A2dpStateMachine: Enter Disconnected: -2
08-17 19:16:46.895  6543  6543 D HidService: Received start request. Starting profile...
08-17 19:16:46.895  6543  6543 D HidService: start()
08-17 19:16:46.895  6543  6543 I bluedroid: get_profile_interface hidhost
08-17 19:16:46.895  6543  6543 D HidService: setHidService(): set to: null
08-17 19:16:46.895  6543  6543 D HidService: mStartError = false
08-17 19:16:46.895  6543  6543 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1aa1d78b
,08-17 19:16:46.905  6543  6543 D HeadsetStateMachine: Try to query the phonestate on bind
,08-17 19:16:46.905  1429  1452 I Telecom : BluetoothPhoneService: queryPhoneState
,08-17 19:16:46.905  1429  1429 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-17 19:16:46.905  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-17 19:16:46.905  1429  1452 I Telecom : BluetoothPhoneService: Result of Message : true
08-17 19:16:46.905  1906  1906 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-17 19:16:46.905  6543  6543 D HeadsetStateMachine: Proxy object connected
,08-17 19:16:46.905  6543  6543 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-17 19:16:46.905  6543  6543 D HealthService: Received start request. Starting profile...
08-17 19:16:46.905  6543  6543 D HealthService: start()
,08-17 19:16:46.905  1906  1906 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-17 19:16:46.905  6543  6543 I bluedroid: get_profile_interface health
,08-17 19:16:46.905  6543  6543 D HealthService: mStartError = false
08-17 19:16:46.905  6543  6543 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1aa1d78b
,08-17 19:16:46.905  6543  6543 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
08-17 19:16:46.905  6543  6904 D HeadsetStateMachine: Disconnected process message: 11
,08-17 19:16:46.915  6543  6543 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-17 19:16:46.915  6543  6543 D PanService: Received start request. Starting profile...
08-17 19:16:46.915  6543  6543 D PanService: start()
08-17 19:16:46.915  6543  6543 D BluetoothPanServiceJni: initializeNative(L110): pan
08-17 19:16:46.915  6543  6543 I bluedroid: get_profile_interface pan
,08-17 19:16:46.915  6543  6543 D PanService: mStartError = false
08-17 19:16:46.915  6543  6543 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1aa1d78b
,08-17 19:16:46.915  6543  6543 D HeadsetPhoneState: sendDeviceDataStateChanged
08-17 19:16:46.915  6543  6543 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-17 19:16:46.915  6543  6904 D HeadsetStateMachine: Disconnected process message: 18
,08-17 19:16:46.915  6543  6908 D BluetoothMediaBrowser: no now playing list
,08-17 19:16:46.915  6543  6908 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-17 19:16:46.915  6543  6543 D BluetoothMapService: Received start request. Starting profile...
,08-17 19:16:46.915  6543  6543 D BluetoothMapService: start()
,08-17 19:16:46.915  6543  6543 D BluetoothMapService: mStartError = false
,08-17 19:16:46.925  6543  6543 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1aa1d78b
,08-17 19:16:46.925  6543  6543 E BluetoothAdapterService(446814091): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,08-17 19:16:46.925  6543  6543 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-17 19:16:46.925  6543  6904 D HeadsetStateMachine: Disconnected process message: 10,
08-17 19:16:46.925  6543  6904 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-17 19:16:46.925  6543  6543 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
08-17 19:16:46.925  6543  6904 D HeadsetStateMachine: Disconnected process message: 11
,08-17 19:16:46.925  6543  6543 D SapService: Received start request. Starting profile...
,08-17 19:16:46.925  6543  6543 D SapService: start()
08-17 19:16:46.925  6543  6543 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-17 19:16:46.925  6543  6543 I bluedroid: get_profile_interface sap
08-17 19:16:46.925  6543  6543 D SapService: mStartError = false
08-17 19:16:46.925  6543  6543 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1aa1d78b
08-17 19:16:46.925  6543  6543 D BluetoothA2dp: Proxy object connected
08-17 19:16:46.925  6543  6543 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-17 19:16:46.925  6543  6543 E BluetoothAdapterService(446814091): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-17 19:16:46.925  6543  6543 E BluetoothAdapterService(446814091): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-17 19:16:46.925  6543  6543 E BluetoothAdapterService(446814091): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-17 19:16:46.925  6543  6543 E BluetoothAdapterService(446814091): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-17 19:16:46.955  6543  6543 E BluetoothAdapterService(446814091): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-17 19:16:46.955  6543  6543 E BluetoothAdapterService(446814091): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-17 19:16:46.955  6543  6894 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-17 19:16:46.955  6543  6894 I bluedroid: enable
,08-17 19:16:46.955  6543  6894 I bt_hci_bdroid: init
,08-17 19:16:46.955  6543  6914 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-17 19:16:46.955  6543  6894 I bt_vendor: bt-vendor : init
,08-17 19:16:46.955  6543  6894 I bt_vendor: bt-vendor : get_bt_soc_type
08-17 19:16:46.955  6543  6894 E bt_vendor: get_bt_soc_type: Failed to get soc type
,08-17 19:16:46.955  6543  6894 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
08-17 19:16:46.955  6543  6894 D bt_userial_mct: userial_init
,08-17 19:16:46.955  6543  6894 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-17 19:16:46.955  6543  6894 I bt_vendor: Starting hciattach daemon
08-17 19:16:46.955  6543  6894 I bt_vendor: try to set false
,08-17 19:16:46.965  6543  6894 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,08-17 19:16:46.965  6543  6894 I bt_vendor: Starting hciattach daemon
08-17 19:16:46.965  6543  6894 I bt_vendor: try to set true
,08-17 19:16:46.975  6918  6918 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-17 19:16:47.025  6924  6924 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-17 19:16:47.035  6925  6925 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-17 19:16:47.055  6927  6927 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-17 19:16:47.065  6928  6928 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-17 19:16:47.075  6929  6929 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-17 19:16:47.085  6930  6930 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-17 19:16:47.345  6933  6933 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab ,
,08-17 19:16:47.355  6934  6934 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-17 19:16:47.365  6543  6894 I bt_vendor: bluetooth satus is on
,08-17 19:16:47.375  6543  6916 D bt_userial_mct: userial_open(port:0)
,08-17 19:16:47.375  6543  6916 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-17 19:16:47.375  6543  6916 I bt_vendor: Done intiailizing UART,
,08-17 19:16:47.375  6543  6916 I bt_vendor: Done intiailizing UART
,08-17 19:16:47.375  6543  6916 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-17 19:16:47.375  6543  6916 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-17 19:16:47.375  6543  6936 D bt_userial_mct: Entering userial_read_thread()
,08-17 19:16:47.385  6543  6914 I         : BTE_InitTraceLevels -- TRC_HCI,
08-17 19:16:47.385  6543  6914 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-17 19:16:47.385  6543  6914 I         : BTE_InitTraceLevels -- TRC_RFCOMM,
08-17 19:16:47.385  6543  6914 I         : BTE_InitTraceLevels -- TRC_AVDT
08-17 19:16:47.385  6543  6914 I         : BTE_InitTraceLevels -- TRC_AVRC
08-17 19:16:47.385  6543  6914 I         : BTE_InitTraceLevels -- TRC_A2D,
08-17 19:16:47.385  6543  6914 I         : BTE_InitTraceLevels -- TRC_BNEP
08-17 19:16:47.385  6543  6914 I         : BTE_InitTraceLevels -- TRC_BTM,
08-17 19:16:47.385  6543  6914 I         : BTE_InitTraceLevels -- TRC_GAP
08-17 19:16:47.385  6543  6914 I         : BTE_InitTraceLevels -- TRC_PAN
08-17 19:16:47.385  6543  6914 I         : BTE_InitTraceLevels -- TRC_SAP
,08-17 19:16:47.385  6543  6914 I         : BTE_InitTraceLevels -- TRC_SDP
08-17 19:16:47.385  6543  6914 I         : BTE_InitTraceLevels -- TRC_GATT
,08-17 19:16:47.385  6543  6914 I         : BTE_InitTraceLevels -- TRC_SMP
08-17 19:16:47.385  6543  6914 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-17 19:16:47.385  6543  6914 I         : BTE_InitTraceLevels -- TRC_BTIF
08-17 19:16:47.385  6543  6914 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-17 19:16:47.495  6543  6914 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-17 19:16:47.495  6543  6914 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa3f386e9 
,08-17 19:16:47.495  6543  6914 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3f386e9 
,08-17 19:16:47.515  6543  6897 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-17 19:16:47.515  6543  6897 E bt-btif : Calling BTA_HhEnable
,08-17 19:16:47.515  6543  6897 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-17 19:16:47.515  6543  6897 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,08-17 19:16:47.525  6543  6897 E BluetoothServiceJni: populateRssiValuesNative
08-17 19:16:47.525  6543  6897 I bluedroid: getModelRssiValues
08-17 19:16:47.525  6543  6897 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127,
08-17 19:16:47.525  6543  6897 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-17 19:16:47.525  1012  1012 D SettingsProvider: name = bluetooth_name
,08-17 19:16:47.525  6543  6897 D BluetoothAdapterProperties: Name is: A5-1
,08-17 19:16:47.525  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:47.535  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:47.535  6543  6897 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-17 19:16:47.535  6543  6897 D BluetoothAdapterProperties: Scan Mode:20
,08-17 19:16:47.535  6543  6897 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-17 19:16:47.535  6543  6897 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
,08-17 19:16:47.535  6543  6897 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,08-17 19:16:47.535  6543  6897 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,08-17 19:16:47.535  6543  6897 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-17 19:16:47.535  6543  6897 E bt-btif : btif_sock_init: !vhci_init
,08-17 19:16:47.535  6543  6897 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-17 19:16:47.545  6543  6897 D IOP_DB_BT: db_open: db_open : handle 3027972112l, read 13894 bytes onto local cache
08-17 19:16:47.545  6543  6897 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
08-17 19:16:47.545  6543  6897 D IOP_DB_BT: db_query: result 1
,08-17 19:16:47.545  6543  6897 I         : iop_db_open: iop_db_open status 0
,08-17 19:16:47.545  6543  6897 D bte_conf: Device ID record 1 : primary
08-17 19:16:47.545  6543  6897 D bte_conf:   vendorId            = 0075
08-17 19:16:47.545  6543  6897 D bte_conf:   vendorIdSource      = 0001
,08-17 19:16:47.545  6543  6936 E bt_mct  : hci lib postload completed
08-17 19:16:47.545  6543  6897 D bte_conf:   product             = 0100
08-17 19:16:47.545  6543  6897 D bte_conf:   version             = 0200
08-17 19:16:47.545  6543  6897 D bte_conf:   clientExecutableURL = 
,08-17 19:16:47.545  6543  6897 D bte_conf:   serviceDescription  = 
08-17 19:16:47.545  6543  6897 D bte_conf:   documentationURL    = 
08-17 19:16:47.545  6543  6897 D bte_conf: bte_load_did_conf no section named DID2.
08-17 19:16:47.545  6543  6897 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-17 19:16:47.545  6543  6894 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-17 19:16:47.545  6543  6894 D BluetoothAdapterProperties: ScanMode =  20
,08-17 19:16:47.545  6543  6894 D BluetoothAdapterProperties: State =  11
,08-17 19:16:47.545  1012  1497 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-17 19:16:47.545  6543  6894 D BluetoothAdapterProperties: Setting state to 12,
08-17 19:16:47.545  6543  6894 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-17 19:16:47.555  6543  6897 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-17 19:16:47.555  6543  6897 D BluetoothAdapterProperties: Scan Mode:21
,08-17 19:16:47.555  6543  6897 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-17 19:16:47.555  1012  2929 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-17 19:16:47.555  1012  2929 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-17 19:16:47.555  1012  2929 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-17 19:16:47.555  1012  2929 D SettingsProvider: selectionArgs: false
08-17 19:16:47.555  1012  1221 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:47.555  1012  2929 D SettingsProvider: selectionArgs: 1002
08-17 19:16:47.555  1012  1221 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-17 19:16:47.555  1012  2929 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
,08-17 19:16:47.555  1012  2929 D SettingsProvider: ret = -1
08-17 19:16:47.555  6543  6894 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-17 19:16:47.555  6543  6894 D BluetoothAdapterService: updateAdapterState state is 12
08-17 19:16:47.555  1012  1221 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:47.555  1012  1221 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:47.555  1012  1221 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
08-17 19:16:47.565  6543  6894 D BluetoothAdapterService: Autoconnection is available 
08-17 19:16:47.565  6543  6894 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-17 19:16:47.565  6543  6894 D BluetoothAdapterService: starting service from this receiver
08-17 19:16:47.565  1312  6396 D Bluetoothsap: onBluetoothStateChange: up=true
08-17 19:16:47.565  1312  6396 D Bluetoothsap: Binding service...
,08-17 19:16:47.565  1012  2929 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:47.565  1012  2929 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-17 19:16:47.565  1312  6396 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-17 19:16:47.565  1012  2929 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:47.565  1012  2929 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 19:16:47.565  1012  2929 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 19:16:47.575  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:47.575  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:47.575  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:47.575  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:16:47.575  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:47.575  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:47.575  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:47.575  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:16:47.575  1012  1041 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-17 19:16:47.575  6543  6894 I BluetoothAdapterState: Entering On State from state = 11
08-17 19:16:47.575  1012  1041 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-17 19:16:47.575  1012  1041 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:47.575  1012  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 19:16:47.575  1012  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:47.575  1312  6396 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-17 19:16:47.585  2889  2897 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:16:47.585  2889  2897 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:16:47.585  6298  6298 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:16:47.585  1173  2082 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:16:47.585  1173  2082 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:16:47.585  6543  6543 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-17 19:16:47.585  1429  1443 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:16:47.585  1429  1443 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:16:47.585  2889  2904 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 19:16:47.585  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:47.585  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:47.585  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:47.585  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:16:47.585  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:47.585  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:47.585  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:47.585  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:16:47.595  2889  2904 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:16:47.595  1012  1041 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-17 19:16:47.595  1012  1041 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 19:16:47.595  1012  1041 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:47.595  1012  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:47.595  1012  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:47.595  6298  6298 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:16:47.595  2889  2889 D BluetoothA2dp: Proxy object connected
,08-17 19:16:47.595  1906  2112 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:16:47.595  1906  2112 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:16:47.605  1312  1327 D BluetoothPan: Binding service...
,08-17 19:16:47.605  6543  6543 I BluetoothPbapService: Handler(): got msg=1
,08-17 19:16:47.605  1012  1041 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-17 19:16:47.605  1012  1041 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-17 19:16:47.605  1012  1478 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-17 19:16:47.605  1012  1041 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:47.605  1012  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:47.605  1012  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-17 19:16:47.605  1012  1041 D BluetoothA2dp: onBluetoothStateChange: up=true
08-17 19:16:47.605  1012  1041 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-17 19:16:47.605  1012  1041 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-17 19:16:47.605  1012  1041 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 19:16:47.605  1312  1312 D Bluetoothsap: BluetoothSAP Proxy object connected
,08-17 19:16:47.605  1312  1312 D SapProfile: Bluetooth service connected
08-17 19:16:47.605  1312  1312 D Bluetoothsap: getConnectedDevices()
,08-17 19:16:47.615  1012  1012 D BluetoothA2dp: Proxy object connected
,08-17 19:16:47.615  2889  2897 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:16:47.615  1012  1041 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 19:16:47.615  1012  1041 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 19:16:47.615  1012  1041 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:47.615  1012  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:47.615  1012  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:47.615  2889  2897 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 19:16:47.615  1312  1326 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-17 19:16:47.615  6543  6941 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-17 19:16:47.615  1312  1312 D BluetoothPan: BluetoothPAN Proxy object connected
,08-17 19:16:47.615  1312  1326 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-17 19:16:47.615  1312  1312 D PanProfile: Bluetooth service connected
,08-17 19:16:47.625  1312  1327 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-17 19:16:47.625  1012  1041 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-17 19:16:47.625  1012  1041 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-17 19:16:47.625  1012  1041 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:47.625  1012  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:47.625  1012  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:47.625  1012  1041 D BluetoothPan: Binding service...
,08-17 19:16:47.625  1012  1041 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-17 19:16:47.625  1012  1041 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-17 19:16:47.625  1312  1326 D BluetoothPbap: onBluetoothStateChange: up=true
08-17 19:16:47.625  1012  1012 D BluetoothPan: BluetoothPAN Proxy object connected
,08-17 19:16:47.625  6543  6941 D BluetoothSocket: bindListen(): myUserId = 0
08-17 19:16:47.625  6543  6941 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 19:16:47.625  1012  1041 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,08-17 19:16:47.625  1012  1041 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-17 19:16:47.625  1012  1041 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:47.625  1012  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:47.635  1012  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:47.635  1312  1312 D BluetoothInputDevice: Proxy object connected
08-17 19:16:47.635  1312  1312 D HidProfile: Bluetooth service connected
08-17 19:16:47.635  6543  6941 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
08-17 19:16:47.635  6543  6941 D BluetoothSocket: bindListen(), new LocalSocket 
08-17 19:16:47.635  6543  6941 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-17 19:16:47.635  6543  6941 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1cf8d1a4
,08-17 19:16:47.635  6543  6941 D BluetoothSocket: channel: 19
08-17 19:16:47.635  6543  6941 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-17 19:16:47.635  1429  1452 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:16:47.635  1012  1041 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 19:16:47.635  1012  1041 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 19:16:47.635  1012  1041 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:47.635  1312  1312 D BluetoothPbap: Proxy object connected
,08-17 19:16:47.635  1312  1312 D PbapServerProfile: Bluetooth service connected
08-17 19:16:47.635  1012  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:47.635  1012  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:47.635  1429  1452 E BluetoothHeadset: BluetoothHeadset service is binded
08-17 19:16:47.635  1453  1760 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:16:47.635  1453  1760 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-17 19:16:47.635  1012  1041 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:16:47.635  1012  1041 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 19:16:47.635  1012  1041 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 19:16:47.635  1012  1041 E BluetoothHeadset: BluetoothHeadset service is binded
08-17 19:16:47.635  1312  1327 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 19:16:47.645  1312  1327 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:16:47.645  1012  1041 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-17 19:16:47.645  1012  1041 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 19:16:47.645  1012  1041 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:47.645  1012  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:47.645  1012  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:47.645  1312  1312 D BluetoothA2dp: Proxy object connected
,08-17 19:16:47.645  1429  1452 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:16:47.645  1312  1312 D A2dpProfile: Bluetooth service connected
,08-17 19:16:47.645  1012  1041 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-17 19:16:47.645  1012  1041 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 19:16:47.645  1012  1041 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:47.645  1012  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:47.645  1012  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:47.645  1429  1452 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 19:16:47.645  1442  2952 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-17 19:16:47.645  1442  2952 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-17 19:16:47.645  1012  1041 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-17 19:16:47.645  1012  1041 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:16:47.655  1312  1327 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:16:47.655  1012  1041 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-17 19:16:47.655  1012  1041 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 19:16:47.655  1012  1041 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:47.655  1012  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:47.655  1012  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:47.655  1312  1312 D HeadsetProfile: Bluetooth service connected
,08-17 19:16:47.655  1312  1327 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 19:16:47.655  6298  6350 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:16:47.655  6298  6350 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:16:47.655  1312  6396 D BluetoothMap: onBluetoothStateChange: up=true
,08-17 19:16:47.655  1012  1041 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,08-17 19:16:47.655  1012  1041 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-17 19:16:47.655  1012  1041 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:47.655  1012  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:47.655  1012  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:47.665  6422  6438 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:16:47.665  6422  6438 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:16:47.665  6543  6552 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:16:47.665  6543  6552 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-17 19:16:47.665  6543  6899 D BluetoothA2dp: onBluetoothStateChange: up=true
08-17 19:16:47.665  1312  1312 D BluetoothMap: Proxy object connected
08-17 19:16:47.665  1312  1312 D MapProfile: Bluetooth service connected
08-17 19:16:47.665  1312  1312 D BluetoothMap: getConnectedDevices()
,08-17 19:16:47.665  1429  6942 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:16:47.665  1012  1041 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-17 19:16:47.665  1012  1041 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 19:16:47.665  1012  1041 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:47.665  1012  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:47.665  1012  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:47.665  1429  6942 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 19:16:47.665  1453  1637 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:16:47.665  1012  1041 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-17 19:16:47.665  1012  1041 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 19:16:47.665  1012  1041 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:47.675  1012  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:47.675  1012  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:47.675  1453  1637 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 19:16:47.675  1012  1041 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-17 19:16:47.675  1012  1041 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-17 19:16:47.675  1012  1012 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-17 19:16:47.675  1012  1012 I InputMethodManagerService: [BT Setting State] State =12
08-17 19:16:47.675  1012  1012 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-17 19:16:47.675  1173  1173 D BluetoothTile:  onBluetoothStateChange:
,08-17 19:16:47.685  1429  1429 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@11cbe8e3, true
,08-17 19:16:47.685  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-17 19:16:47.685  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-17 19:16:47.685  1173  1173 D BluetoothTile:  getBluetoothState : 12
,08-17 19:16:47.685  1429  1429 D BluetoothHeadset: registerMessageListener
,08-17 19:16:47.685  1888  1888 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-17 19:16:47.685  1173  1707 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 19:16:47.685  1312  1312 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:47.685  1012  1541 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 19:16:47.695  1012  1474 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-17 19:16:47.695  6543  6898 D HeadsetService: registerMessageListener,
08-17 19:16:47.695  6543  6898 D HeadsetService: registerMessageListener
08-17 19:16:47.695  1012  1474 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-17 19:16:47.695  6543  6904 D HeadsetStateMachine: Disconnected process message: 70
,08-17 19:16:47.695  6543  6904 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@2ea96b0d
08-17 19:16:47.695  1012  1474 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:47.695  1012  1474 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:47.695  1012  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:47.695  1429  1429 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-17 19:16:47.695  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-17 19:16:47.695  1012  1541 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-17 19:16:47.705  1429  1429 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-17 19:16:47.705  1429  1429 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-17 19:16:47.705  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
08-17 19:16:47.705  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:47.705  1173  1707 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 19:16:47.705  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 19:16:47.705  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:47.705  1173  1707 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 19:16:47.705  6543  6904 D HeadsetStateMachine: Disconnected process message: 9
08-17 19:16:47.705  6543  6904 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
08-17 19:16:47.705  1312  1312 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-17 19:16:47.705  1312  1312 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-17 19:16:47.705  1312  1312 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-17 19:16:47.705  1312  1312 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-17 19:16:47.715   282   684 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false,
08-17 19:16:47.715   282   684 V voice   : voice_set_parameters: enter: A2dpSuspended=false
,08-17 19:16:47.715   282   684 V voice   : voice_set_parameters: exit with code(-2)
08-17 19:16:47.715   282   684 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-17 19:16:47.715   282   684 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-17 19:16:47.715   282   684 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-17 19:16:47.715   282   684 V audio_hw_primary: adev_set_parameters: exit
08-17 19:16:47.715  6543  6904 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-17 19:16:47.715  1312  1312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 19:16:47.715  1012  1497 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-17 19:16:47.715  1012  1497 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-17 19:16:47.715  1012  1497 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:47.715  6543  6943 D BluetoothMapMasInstance: set MAP SDP message type : 1
08-17 19:16:47.715  1012  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 19:16:47.715  1012  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-17 19:16:47.725  6543  6943 D BluetoothSocket: bindListen(): myUserId = 0
08-17 19:16:47.725  6543  6943 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 19:16:47.725  6543  6943 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
08-17 19:16:47.725  6543  6943 D BluetoothSocket: bindListen(), new LocalSocket 
08-17 19:16:47.725  6543  6943 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-17 19:16:47.725  6543  6943 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@15cebac2
08-17 19:16:47.725  6543  6943 D BluetoothSocket: channel: 5
,08-17 19:16:47.725  1312  1312 D DockEventReceiver: finishStartingService: stopping service
,08-17 19:16:47.725  1312  1312 D BluetoothNotiBroadcastReceiver: onReceive
,08-17 19:16:47.735  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:47.735  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-17 19:16:47.745  6543  6543 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1aa1d78b
08-17 19:16:47.745  6543  6543 D BtConfig.SecureMode: isSecureModeOn:false
,08-17 19:16:47.745  1012  1025 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:16:47.745  1012  1025 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-17 19:16:47.745  1012  1025 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:47.745  1012  1025 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:47.755  1012  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:47.775  1906  1906 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-17 19:16:47.775  1012  1025 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 19:16:47.775  1012  1025 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
08-17 19:16:47.775  1012  1025 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:47.775  1012  1025 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:47.775  1012  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:47.785  1012  1074 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-17 19:16:47.785  1906  1906 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-17 19:16:47.785  1906  6952 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-17 19:16:47.795  6543  6954 D BluetoothSocket: bindListen(): myUserId = 0
,08-17 19:16:47.805  6543  6954 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 19:16:47.805  6543  6954 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[81]}
,08-17 19:16:47.805  6543  6954 D BluetoothSocket: bindListen(), new LocalSocket 
08-17 19:16:47.805  6543  6954 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-17 19:16:47.805  6543  6954 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1451c10e
08-17 19:16:47.805  6543  6954 D BluetoothSocket: channel: 12
,08-17 19:16:47.805  6543  6954 I BtOppRfcommListener: Accept thread started.
,08-17 19:16:47.935  1012  1360 I art     : Explicit concurrent mark sweep GC freed 72403(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 2.448ms total 147.350ms
,08-17 19:16:47.935  1012  1360 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:16:47.935  1012  1360 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:47.935  1012  1360 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:47.935  1012  1360 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:47.955  1012  1025 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:16:47.955  1012  1025 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:47.955  1012  1025 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:47.955  1012  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:47.965  1906  6952 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-17 19:16:48.245  1012  2745 D SSRM:n  : SIOP:: AP = 330
,08-17 19:16:48.495   287   287 E SMD     : DCD OFF,
,08-17 19:16:49.635  6298  6363 D BluetoothAdapter: disable()
,08-17 19:16:49.635  1012  1474 D SettingsProvider: name = bluetooth_on
,08-17 19:16:49.645  6543  6894 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-17 19:16:49.645  6543  6894 D BluetoothAdapterProperties: Setting state to 13
08-17 19:16:49.645  6543  6894 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-17 19:16:49.645  6543  6894 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-17 19:16:49.645  6543  6894 D BluetoothAdapterService: updateAdapterState state is 13
,08-17 19:16:49.645  1012  2930 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:49.645  1012  2930 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:49.645  1012  2930 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-17 19:16:49.645  1012  2930 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:49.645  1012  2930 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:49.645  6543  6543 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-17 19:16:49.645  6543  6894 D BluetoothAdapterService: Autoconnection is available 
,08-17 19:16:49.645  6543  6894 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
,08-17 19:16:49.645  6543  6894 D BluetoothAdapterService: terminating service from this receiver
,08-17 19:16:49.655  6543  6543 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2e75a72f, channel: 19, state: LISTENING
,08-17 19:16:49.655  6543  6543 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2e75a72f, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1cf8d1a4, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1e62b13cmSocket: android.net.LocalSocket@126deec5 impl:android.net.LocalSocketImpl@8ece01a fd:FileDescriptor[75]
,08-17 19:16:49.655  6543  6543 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@126deec5 impl:android.net.LocalSocketImpl@8ece01a fd:FileDescriptor[75]
08-17 19:16:49.655  1012  1221 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-17 19:16:49.655  1012  1221 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:49.655  1012  1221 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:49.655  1012  1221 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:49.655  6543  6894 D BluetoothAdapterProperties: onBluetoothDisable(),
08-17 19:16:49.655  6543  6894 D BluetoothAdapterProperties: mDiscovering is false
,08-17 19:16:49.655  1012  1540 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-17 19:16:49.655  6543  6894 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-17 19:16:49.665  1012  1012 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-17 19:16:49.665  1012  1012 I InputMethodManagerService: [BT Setting State] State =13
,08-17 19:16:49.665  1173  1173 D BluetoothTile:  onBluetoothStateChange:
,08-17 19:16:49.665  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-17 19:16:49.675  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:49.675  1173  1173 D BluetoothTile:  getBluetoothState : 13
,08-17 19:16:49.675  1173  1707 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 19:16:49.675  1173  1707 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 19:16:49.675  1173  1707 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-17 19:16:49.675  1888  1888 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-17 19:16:49.685  1012  1540 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 19:16:49.685  1012  1074 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-17 19:16:49.685  1312  1312 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:49.685  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-17 19:16:49.685  6298  6298 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 19:16:49.685  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:49.685  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:49.685  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:49.685  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:16:49.685  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:16:49.685  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:49.685  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:49.685  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:16:49.695  6298  6298 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 19:16:49.695  6298  6298 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:16:49.695  1012  1478 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 19:16:49.695  1012  1478 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-17 19:16:49.695  1012  1478 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:49.695  1012  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:49.695  1012  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:49.705  6543  6897 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-17 19:16:49.705  6543  6897 D BluetoothAdapterProperties: Scan Mode:20
,08-17 19:16:49.705  6298  6298 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 19:16:49.705  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:49.705  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:49.705  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:49.705  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:16:49.705  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:16:49.705  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:49.705  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:49.705  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:16:49.705  1312  1312 D BluetoothPbap: Proxy object disconnected
08-17 19:16:49.705  1312  1312 D PbapServerProfile: Bluetooth service disconnected
,08-17 19:16:49.715  6543  6894 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-17 19:16:49.715  6543  6894 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
08-17 19:16:49.715  1312  1312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 19:16:49.715  1012  1497 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-17 19:16:49.715  6543  6894 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-17 19:16:49.715  1012  1497 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-17 19:16:49.715  6298  6298 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:16:49.715  6543  6894 E bt-btif : BTA got event 0x1a1c
08-17 19:16:49.715  6543  6914 E bt-btm  : btm_ble_start_auto_conn start : 0, 0,
08-17 19:16:49.715  6543  6914 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-17 19:16:49.715  1012  1497 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:49.715  6543  6894 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-17 19:16:49.715  6298  6298 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null,
08-17 19:16:49.715  1012  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-17 19:16:49.715  1012  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-17 19:16:49.725  6543  6914 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 19:16:49.725  6543  6914 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 19:16:49.725  6543  6914 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-17 19:16:49.725  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:49.725  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:49.725  6543  6954 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-17 19:16:49.735  6543  6543 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@273f874b, channel: 5, state: LISTENING
08-17 19:16:49.735  6543  6543 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@273f874b, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@15cebac2, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@47a528mSocket: android.net.LocalSocket@17c3b241 impl:android.net.LocalSocketImpl@1de8e3e6 fd:FileDescriptor[77]
08-17 19:16:49.735  6543  6543 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@17c3b241 impl:android.net.LocalSocketImpl@1de8e3e6 fd:FileDescriptor[77]
,08-17 19:16:49.735  6543  6543 I BtOppRfcommListener: stopping Accept Thread
08-17 19:16:49.735  6543  6543 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1b7d4d27, channel: 12, state: LISTENING
08-17 19:16:49.735  6543  6543 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1b7d4d27, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1451c10e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3505ebd4mSocket: android.net.LocalSocket@1b58317d impl:android.net.LocalSocketImpl@74f5872 fd:FileDescriptor[81]
08-17 19:16:49.735  1312  1312 D DockEventReceiver: finishStartingService: stopping service
08-17 19:16:49.735  6543  6543 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1b58317d impl:android.net.LocalSocketImpl@74f5872 fd:FileDescriptor[81]
,08-17 19:16:49.735  6543  6954 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-17 19:16:49.735  1312  1312 D BluetoothNotiBroadcastReceiver: onReceive
,08-17 19:16:49.735  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:49.735  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-17 19:16:49.745  6543  6543 V BluetoothOppManager: cleanUp...
,08-17 19:16:49.765  1906  1906 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-17 19:16:49.775  1906  1906 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-17 19:16:49.915  6543  6914 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-17 19:16:49.915  6543  6914 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 19:16:49.915  6543  6914 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 19:16:49.915  6543  6914 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 19:16:49.915  6543  6914 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 19:16:49.915  6543  6914 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 19:16:49.915  6543  6914 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 19:16:49.915  6543  6914 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 19:16:49.915  6543  6914 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 19:16:49.915  6543  6914 W bt-btif : ag scb idx 1 not allocated
08-17 19:16:49.915  6543  6914 W bt-btif : ag scb idx 2 not allocated
08-17 19:16:49.915  6543  6914 E bt-btif : BTA AG is already disabled, ignoring ...
08-17 19:16:49.915  6543  6936 I bt_userial_mct: exiting userial_read_thread
08-17 19:16:49.915  6543  6936 D bt_userial_mct: Leaving userial_evt_read_thread()
08-17 19:16:49.915  6543  6897 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-17 19:16:49.915  6543  6916 I bt_vendor: hw_epilog_process
08-17 19:16:49.915  6543  6897 D bt_userial_mct: userial_close
08-17 19:16:49.915  6543  6897 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-17 19:16:50.295  6543  6897 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-17 19:16:50.295  6543  6897 I bt_vendor: bluetooth satus is on
08-17 19:16:50.295  6543  6897 I bt_vendor: bt-vendor : resetting BT status
08-17 19:16:50.295  6543  6897 I bt_vendor: Starting hciattach daemon
08-17 19:16:50.295  6543  6897 I bt_vendor: try to set false
,08-17 19:16:50.295  6543  6897 I bt_vendor: Starting hciattach daemon
08-17 19:16:50.295  6543  6897 I bt_vendor: try to set false
,08-17 19:16:50.295  6543  6897 I bt_vendor: cleanup
,08-17 19:16:50.295  6543  6914 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-17 19:16:50.295  6543  6897 I GKI_LINUX: GKI_exit_task 0 done
,08-17 19:16:50.295  6543  6897 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-17 19:16:50.295  6543  6894 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-17 19:16:50.295  6543  6894 D BtConfig.SecureMode: isSecureModeOn:false
08-17 19:16:50.295  6543  6894 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
,08-17 19:16:50.295  6543  6894 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-17 19:16:50.295  6543  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-17 19:16:50.295  6543  6894 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-17 19:16:50.295  1012  1541 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:50.295  1012  1541 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:50.295  1012  1541 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0,
08-17 19:16:50.295  1012  1541 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:50.295  1012  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:50.295  6543  6894 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-17 19:16:50.295  6543  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-17 19:16:50.295  6543  6894 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-17 19:16:50.305  6543  6543 D BtGatt.DebugUtils: handleDebugAction() action=null
08-17 19:16:50.305  1012  1478 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:16:50.305  1012  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-17 19:16:50.305  6543  6543 D BtGatt.GattService: Received stop request...Stopping profile...
08-17 19:16:50.305  6543  6543 D BtGatt.GattService: stop()
08-17 19:16:50.305  6543  6543 D BtGatt.AdvertiseManager: advertise clients cleared
,08-17 19:16:50.305  1012  1478 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:50.305  1012  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:50.305  1012  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:50.305  6543  6894 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,08-17 19:16:50.305  6543  6543 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1aa1d78b
,08-17 19:16:50.305  6543  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-17 19:16:50.305  6543  6894 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-17 19:16:50.305  1012  1221 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:16:50.305  1012  1221 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 19:16:50.315  6543  6543 D HeadsetService: Received stop request...Stopping profile...
,08-17 19:16:50.315  1012  1221 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:50.315  1012  1221 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:50.315  1012  1221 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:50.315  6543  6543 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1aa1d78b
,08-17 19:16:50.315  6543  6894 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-17 19:16:50.315  6543  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-17 19:16:50.315  6543  6894 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-17 19:16:50.315  1012  1541 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:50.315  1012  1541 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-17 19:16:50.315  1012  1541 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:50.315  1012  1541 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:50.315  1012  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:50.315  6543  6894 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-17 19:16:50.315  6543  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-17 19:16:50.315  6543  6894 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-17 19:16:50.315  1012  1478 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:16:50.315  1012  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-17 19:16:50.325  1012  1478 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:50.325  1012  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:50.325  1012  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:50.325  6543  6894 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,08-17 19:16:50.325  6543  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-17 19:16:50.325  6543  6894 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-17 19:16:50.325  1012  1025 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:50.325  1012  1025 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-17 19:16:50.325  1012  1025 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:50.325  1312  1312 D HeadsetProfile: Bluetooth service disconnected
08-17 19:16:50.325  1012  1025 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:50.325  1012  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:50.325  1012  1012 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-17 19:16:50.335  6543  6894 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-17 19:16:50.335  6543  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 19:16:50.335  6543  6894 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-17 19:16:50.335  1012  1540 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:50.335  1012  1540 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-17 19:16:50.335  1012  1540 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:50.335  1012  1540 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:50.335  1012  1540 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:50.335  6543  6894 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-17 19:16:50.335  6543  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-17 19:16:50.335  6543  6894 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-17 19:16:50.335  1012  1360 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:50.335  1012  1360 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-17 19:16:50.335  1012  1360 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:50.335  1012  1360 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 19:16:50.335  1012  1360 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:50.335  6543  6894 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:16:50.335  6543  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:16:50.335  6543  6894 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:16:50.335  6543  6894 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:16:50.335  6543  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:16:50.335  6543  6894 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:16:50.335  6543  6894 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-17 19:16:50.335  6543  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-17 19:16:50.335  6543  6894 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-17 19:16:50.335  6543  6894 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-17 19:16:50.335  6543  6894 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-17 19:16:50.335  6543  6894 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-17 19:16:50.335  6543  6894 D BluetoothAdapterState: Stopping profile services that were post enabled
08-17 19:16:50.335  6543  6543 E BluetoothAdapterService(446814091): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
08-17 19:16:50.335  6543  6543 E BluetoothAdapterService(446814091): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-17 19:16:50.335  6543  6543 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-17 19:16:50.335  6543  6543 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-17 19:16:50.335  6543  6543 D A2dpService: Received stop request...Stopping profile...
,08-17 19:16:50.335  6543  6909 D A2dpStateMachine: Exit Disconnected: -1
,08-17 19:16:50.345  6543  6543 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1aa1d78b
,08-17 19:16:50.345  1012  1012 D BluetoothA2dp: Proxy object disconnected
08-17 19:16:50.345  1012  1012 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-17 19:16:50.345  2889  2889 D BluetoothA2dp: Proxy object disconnected
,08-17 19:16:50.345  1312  1312 D BluetoothA2dp: Proxy object disconnected
08-17 19:16:50.345  1312  1312 D A2dpProfile: Bluetooth service disconnected
,08-17 19:16:50.345  6543  6543 D HidService: Received stop request...Stopping profile...
,08-17 19:16:50.345  6543  6543 D HidService: Stopping Bluetooth HidService
,08-17 19:16:50.345  6543  6543 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-17 19:16:50.345  6543  6543 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-17 19:16:50.345  6543  6543 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-17 19:16:50.345  6543  6543 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1aa1d78b
,08-17 19:16:50.345  6543  6543 D HealthService: Received stop request...Stopping profile...
,08-17 19:16:50.345  6543  6543 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1aa1d78b
,08-17 19:16:50.345  1312  1312 D BluetoothInputDevice: Proxy object disconnected
,08-17 19:16:50.355  1312  1312 D HidProfile: Bluetooth service disconnected
,08-17 19:16:50.355  6543  6543 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-17 19:16:50.355  6543  6543 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-17 19:16:50.355  6543  6543 D PanService: Received stop request...Stopping profile...
,08-17 19:16:50.355  6543  6543 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1aa1d78b
,08-17 19:16:50.355  6543  6543 D BluetoothMapService: Received stop request...Stopping profile...
,08-17 19:16:50.355  1012  1012 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-17 19:16:50.355  1312  1312 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-17 19:16:50.355  1312  1312 D PanProfile: Bluetooth service disconnected
,08-17 19:16:50.355  6543  6543 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1aa1d78b
,08-17 19:16:50.365  6543  6543 D SapService: Received stop request...Stopping profile...
,08-17 19:16:50.365  6543  6543 D SapService: Stopping Bluetooth SapService
,08-17 19:16:50.365  6543  6543 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1aa1d78b
,08-17 19:16:50.365  6543  6543 E BluetoothAdapterService(446814091): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-17 19:16:50.365  6543  6543 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-17 19:16:50.365  6543  6543 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-17 19:16:50.365  6543  6543 D BluetoothA2dp: Proxy object disconnected
08-17 19:16:50.365  6543  6543 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-17 19:16:50.365  6543  6910 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-17 19:16:50.365  6543  6543 I GKI_LINUX: GKI_exit_task 2 done
08-17 19:16:50.365  6543  6543 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-17 19:16:50.365  6543  6543 E BluetoothAdapterService(446814091): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-17 19:16:50.365  6543  6543 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 19:16:50.365  6543  6543 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-17 19:16:50.365  6543  6543 E BluetoothAdapterService(446814091): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-17 19:16:50.365  6543  6543 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 19:16:50.365  6543  6543 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-17 19:16:50.365  6543  6543 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-17 19:16:50.365  1312  1312 D BluetoothMap: Proxy object disconnected
08-17 19:16:50.365  1312  1312 D MapProfile: Bluetooth service disconnected
08-17 19:16:50.365  6543  6543 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-17 19:16:50.365  1312  1312 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-17 19:16:50.365  1312  1312 D SapProfile: Bluetooth service disconnected
08-17 19:16:50.365  6543  6543 E BluetoothAdapterService(446814091): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-17 19:16:50.365  6543  6543 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 19:16:50.365  6543  6543 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-17 19:16:50.365  6543  6543 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-17 19:16:50.365  6543  6543 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-17 19:16:50.365  6543  6543 E BluetoothAdapterService(446814091): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,08-17 19:16:50.365  6543  6543 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-17 19:16:50.375  6543  6543 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-17 19:16:50.375  6543  6543 E BluetoothAdapterService(446814091): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,08-17 19:16:50.375  6543  6894 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,08-17 19:16:50.375  6543  6894 D BluetoothAdapterProperties: Setting state to 10
08-17 19:16:50.375  6543  6894 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
,08-17 19:16:50.375  6543  6894 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-17 19:16:50.375  6543  6894 D BluetoothAdapterService: updateAdapterState state is 10
,08-17 19:16:50.375  1312  1327 D Bluetoothsap: onBluetoothStateChange: up=false
08-17 19:16:50.375  6543  6543 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-17 19:16:50.375  6543  6543 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-17 19:16:50.375  6543  6894 D BluetoothAdapterService: Autoconnection is available 
08-17 19:16:50.375  6543  6894 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-17 19:16:50.375  6543  6894 I BluetoothAdapterState: Entering OffState
08-17 19:16:50.375  1312  1327 D Bluetoothsap: Unbinding service...
,08-17 19:16:50.375  2889  2897 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 19:16:50.375  2889  2897 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:16:50.375  1173  2082 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 19:16:50.375  1173  2082 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:16:50.375  1429  1452 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 19:16:50.375  1429  1452 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:16:50.375  2889  2904 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-17 19:16:50.385  1906  2113 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 19:16:50.385  1906  2113 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:16:50.385  1012  1041 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-17 19:16:50.385  1312  1326 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 19:16:50.385  1312  1326 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:16:50.385  1312  1327 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-17 19:16:50.385  1312  6396 D BluetoothPbap: onBluetoothStateChange: up=false
,08-17 19:16:50.385  1453  1468 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 19:16:50.385  1453  1468 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:16:50.385  1312  1326 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-17 19:16:50.385  1442  2952 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 19:16:50.385  1442  2952 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-17 19:16:50.385  1012  1041 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 19:16:50.385  1012  1041 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:16:50.395  6298  6312 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 19:16:50.395  6298  6312 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-17 19:16:50.395  6298  6312 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
,08-17 19:16:50.395  6298  6312 D BluetoothLeAdvertiser: Exit stop advertising
08-17 19:16:50.395  6298  6312 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-17 19:16:50.395  6298  6312 D BluetoothLeScanner: Exiting stopAllScan
,08-17 19:16:50.395  1312  6396 D BluetoothMap: onBluetoothStateChange: up=false
,08-17 19:16:50.395  6422  6438 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 19:16:50.395  6422  6438 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:16:50.395  6543  6899 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 19:16:50.395  6543  6899 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 19:16:50.395  6543  6552 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-17 19:16:50.395  1012  1041 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 11 receivers.
,08-17 19:16:50.395  1012  1041 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-17 19:16:50.405  1012  1012 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:50.405  1012  1012 I InputMethodManagerService: [BT Setting State] State =10
08-17 19:16:50.405  1012  1012 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-17 19:16:50.405  1173  1173 D BluetoothAdapter: 545127418: getState() :  mService = null. Returning STATE_OFF
,08-17 19:16:50.415  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-17 19:16:50.415  1173  1707 D BluetoothAdapter: 545127418: getState() :  mService = null. Returning STATE_OFF
08-17 19:16:50.415  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-17 19:16:50.415  1173  1173 D BluetoothTile:  getBluetoothState : 10
,08-17 19:16:50.415  1173  1707 D BluetoothAdapter: 545127418: getState() :  mService = null. Returning STATE_OFF
08-17 19:16:50.415  6543  6897 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-17 19:16:50.415  1173  1173 D BluetoothAdapter: 545127418: getState() :  mService = null. Returning STATE_OFF
08-17 19:16:50.415  1173  1173 D BluetoothAdapter: 545127418: getState() :  mService = null. Returning STATE_OFF
,08-17 19:16:50.415  6543  6543 I GKI_LINUX: GKI_exit_task 1 done
08-17 19:16:50.415  6543  6543 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-17 19:16:50.415  1012  1478 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-17 19:16:50.415  6543  6543 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-17 19:16:50.415  1012  1497 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-17 19:16:50.415  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-17 19:16:50.415  1888  1888 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-17 19:16:50.415  1312  1312 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:50.415  1906  2123 D BluetoothAdapter: 792504002: getState() :  mService = null. Returning STATE_OFF
08-17 19:16:50.415  1906  2123 D BluetoothAdapter: 792504002: getState() :  mService = null. Returning STATE_OFF
,08-17 19:16:50.415  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:50.415  1012  2930 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-17 19:16:50.415  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:16:50.415  1012  2930 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-17 19:16:50.425  6543  6543 I art     : System.exit called, status: 0
,08-17 19:16:50.425  6543  6543 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-17 19:16:50.425  1012  2930 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:50.425  1012  2930 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:50.425  1012  2930 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:50.425  1312  1312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 19:16:50.425  1012  1024 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-17 19:16:50.425  1012  1024 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-17 19:16:50.425  1012  1024 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:50.425  1012  1024 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:50.425  1012  1024 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-17 19:16:50.435  1312  1312 D DockEventReceiver: finishStartingService: stopping service
,08-17 19:16:50.435  1312  1312 D BluetoothNotiBroadcastReceiver: onReceive
,08-17 19:16:50.445  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-17 19:16:50.445  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-17 19:16:50.455  1012  1024 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-17 19:16:50.455  1012  1024 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-17 19:16:50.455  1012  1024 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppReceiver}
08-17 19:16:50.455  1012  1024 W BroadcastQueue: android.os.TransactionTooLargeException
08-17 19:16:50.455  1012  1024 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-17 19:16:50.455  1012  1024 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-17 19:16:50.455  1012  1024 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-17 19:16:50.455  1012  1024 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-17 19:16:50.455  1012  1024 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-17 19:16:50.455  1012  1024 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20437)
08-17 19:16:50.455  1012  1024 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-17 19:16:50.455  1012  1024 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3278)
08-17 19:16:50.455  1012  1024 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,08-17 19:16:50.455  1012  1024 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-17 19:16:50.465  1012  1024 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:50.465  1012  1024 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:50.465  1012  1024 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:16:50.465  1012  1024 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:16:50.475  1012  1024 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6969 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-17 19:16:50.475  6969  6969 E Zygote  : MountEmulatedStorage()
08-17 19:16:50.475  6969  6969 I libpersona: KNOX_SDCARD checking this for 1002
08-17 19:16:50.475  6969  6969 E Zygote  : v2
08-17 19:16:50.475  6969  6969 I libpersona: KNOX_SDCARD not a persona
,08-17 19:16:50.485  6969  6969 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-17 19:16:50.485  6969  6969 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-17 19:16:50.485  6969  6969 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:16:50.495   303   303 I art     : Explicit concurrent mark sweep GC freed 8723(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 616us total 23.375ms
08-17 19:16:50.505  6969  6969 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 19:16:50.505  6969  6969 D ActivityThread: Added TimaKeyStore provider
,08-17 19:16:50.515   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 609us total 16.921ms
,08-17 19:16:50.525  6969  6969 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-17 19:16:50.525  6969  6969 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-17 19:16:50.545   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 644us total 24.766ms
,08-17 19:16:50.545  6969  6969 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-17 19:16:50.585  6969  6969 D BtSettings.ProfileConfig: Adding GattService
08-17 19:16:50.585  6969  6969 D BtSettings.ProfileConfig: Adding HeadsetService
08-17 19:16:50.585  6969  6969 D BtSettings.ProfileConfig: Adding A2dpService
08-17 19:16:50.585  6969  6969 D BtSettings.ProfileConfig: Adding HidService
08-17 19:16:50.585  6969  6969 D BtSettings.ProfileConfig: Adding HealthService
08-17 19:16:50.585  6969  6969 D BtSettings.ProfileConfig: Adding PanService
08-17 19:16:50.585  6969  6969 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-17 19:16:50.585  6969  6969 D BtSettings.ProfileConfig: Adding SapService
08-17 19:16:50.585  6969  6969 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-17 19:16:50.585  6969  6969 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-17 19:16:50.585  6969  6969 D BtSettings.ProfileConfig: Adding SapClientService
08-17 19:16:50.585  6969  6969 D BtSettings.ProfileConfig: Adding HidDevService
08-17 19:16:50.585  6969  6969 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-17 19:16:50.585  1012  1025 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService,
08-17 19:16:50.585  1012  1025 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:50.585  1012  1025 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:50.585  1012  1025 D SettingsProvider: selectionArgs: false
08-17 19:16:50.585  1012  1025 D SettingsProvider: selectionArgs: 1002
,08-17 19:16:50.585  1012  1025 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:50.585  1012  1025 D SettingsProvider: ret = -1
08-17 19:16:50.585  1012  1478 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-17 19:16:50.585  1012  1478 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:50.585  1012  1478 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:50.585  1012  1478 D SettingsProvider: selectionArgs: false
08-17 19:16:50.585  1012  1478 D SettingsProvider: selectionArgs: 1002
08-17 19:16:50.585  1012  1478 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:50.585  1012  1478 D SettingsProvider: ret = -1
08-17 19:16:50.585  1012  1497 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-17 19:16:50.585  1012  1497 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:50.585  1012  1497 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:50.585  1012  1497 D SettingsProvider: selectionArgs: false
,08-17 19:16:50.585  1012  1497 D SettingsProvider: selectionArgs: 1002
08-17 19:16:50.585  1012  1497 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:50.585  1012  1497 D SettingsProvider: ret = -1
08-17 19:16:50.585  1012  1541 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-17 19:16:50.585  1012  1541 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:50.585  1012  1541 D SettingsProvider: projectionArgs: isSettingsChangesAllowed,
08-17 19:16:50.585  1012  1541 D SettingsProvider: selectionArgs: false
08-17 19:16:50.585  1012  1541 D SettingsProvider: selectionArgs: 1002
08-17 19:16:50.585  1012  1541 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:50.585  1012  1541 D SettingsProvider: ret = -1
,08-17 19:16:50.585  1012  1540 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-17 19:16:50.585  1012  1540 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:50.585  1012  1540 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:50.585  1012  1540 D SettingsProvider: selectionArgs: false
08-17 19:16:50.585  1012  1540 D SettingsProvider: selectionArgs: 1002
08-17 19:16:50.585  1012  1540 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:50.585  1012  1540 D SettingsProvider: ret = -1
,08-17 19:16:50.595  1012  1221 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-17 19:16:50.595  1012  1221 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:50.595  1012  1221 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:50.595  1012  1221 D SettingsProvider: selectionArgs: false
08-17 19:16:50.595  1012  1221 D SettingsProvider: selectionArgs: 1002
,08-17 19:16:50.595  1012  1221 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:50.595  1012  1221 D SettingsProvider: ret = -1
08-17 19:16:50.595  1012  1024 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-17 19:16:50.595  1012  1024 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:50.595  1012  1024 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:50.595  1012  1024 D SettingsProvider: selectionArgs: false
08-17 19:16:50.595  1012  1024 D SettingsProvider: selectionArgs: 1002,
08-17 19:16:50.595  1012  1024 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:50.595  1012  1024 D SettingsProvider: ret = -1
08-17 19:16:50.595  1012  2929 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-17 19:16:50.595  1012  2929 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:50.595  1012  2929 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:50.595  1012  2929 D SettingsProvider: selectionArgs: false
08-17 19:16:50.595  1012  2929 D SettingsProvider: selectionArgs: 1002
08-17 19:16:50.595  1012  2929 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-17 19:16:50.595  1012  2929 D SettingsProvider: ret = -1
08-17 19:16:50.595  1012  1074 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:16:50.595  1012  1074 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:50.595  1012  1074 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:50.595  1012  1074 D SettingsProvider: selectionArgs: false
08-17 19:16:50.595  1012  1074 D SettingsProvider: selectionArgs: 1002
,08-17 19:16:50.595  1012  1074 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:50.595  1012  1074 D SettingsProvider: ret = -1
08-17 19:16:50.595  1012  2930 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:16:50.595  1012  2930 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:50.595  1012  2930 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:50.595  1012  2930 D SettingsProvider: selectionArgs: false
08-17 19:16:50.595  1012  2930 D SettingsProvider: selectionArgs: 1002
08-17 19:16:50.595  1012  2930 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:50.595  1012  2930 D SettingsProvider: ret = -1
08-17 19:16:50.595  1012  1474 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-17 19:16:50.595  1012  1474 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-17 19:16:50.595  1012  1474 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:50.595  1012  1474 D SettingsProvider: selectionArgs: false
08-17 19:16:50.595  1012  1474 D SettingsProvider: selectionArgs: 1002
08-17 19:16:50.595  1012  1474 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:50.595  1012  1474 D SettingsProvider: ret = -1,
08-17 19:16:50.595  1012  1360 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-17 19:16:50.595  1012  1360 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:50.595  1012  1360 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-17 19:16:50.595  1012  1360 D SettingsProvider: selectionArgs: false
08-17 19:16:50.595  1012  1360 D SettingsProvider: selectionArgs: 1002
08-17 19:16:50.595  1012  1360 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:50.595  1012  1360 D SettingsProvider: ret = -1
,08-17 19:16:50.605  1906  1906 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-17 19:16:50.605  1012  1024 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 19:16:50.605  1012  1024 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
08-17 19:16:50.605  1012  1024 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:50.605  1012  1024 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:50.605  1012  1024 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:50.615  1906  6985 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-17 19:16:50.615  1906  1906 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-17 19:16:50.625  1012  1025 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:16:50.625  1012  1025 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:50.625  1012  1025 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:50.625  1012  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:50.635  1906  6985 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-17 19:16:51.495   287   287 E SMD     : DCD OFF
,08-17 19:16:52.645  6298  6363 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 19:16:52.645  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:52.915  1012  1044 I PowerManagerService: [PWL] Off : 75s ago
,08-17 19:16:52.915  1012  1044 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
08-17 19:16:52.915  1012  1044 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
,08-17 19:16:52.915  1012  1044 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1012, ws=null) (elapsedTime=14951)
,08-17 19:16:54.495   287   287 E SMD     : DCD OFF,
,08-17 19:16:55.645  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 19:16:55.645  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1e77120b added. We now have 6 listener(s)
,08-17 19:16:55.645  6298  6363 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 19:16:55.645  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 19:16:55.645  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3fb438e8 added. We now have 7 listener(s)
,08-17 19:16:55.645  6298  6363 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 19:16:55.655  6298  6363 I System.out: IsBluetoothEnabled
,08-17 19:16:55.655  6298  6363 D BluetoothAdapter: disable()
,08-17 19:16:55.655  1012  1221 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-17 19:16:55.655  6298  6363 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:55.655  6298  6363 D BluetoothAdapter: enable()
,08-17 19:16:55.665  1012  1540 W ActivityManager: Permission Denial: getCurrentUser() from pid=6298, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,08-17 19:16:55.665  1012  1540 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-17 19:16:55.665  1012  1540 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6298, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-17 19:16:55.665  1012  1540 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-17 19:16:55.665  1012  1540 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
08-17 19:16:55.665  1012  1540 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
08-17 19:16:55.665  1012  1540 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
08-17 19:16:55.665  1012  1540 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-17 19:16:55.665  1012  1540 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-17 19:16:55.665  1012  1540 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 19:16:55.665  1012  1540 D SettingsProvider: name = bluetooth_on
,08-17 19:16:55.675  1012  1041 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-17 19:16:55.675  1012  1041 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 19:16:55.675  1012  1041 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
08-17 19:16:55.675  1012  1041 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-17 19:16:55.695  6969  6969 D BluetoothAdapterState: make
,08-17 19:16:55.695  6969  6969 I bluedroid: init
,08-17 19:16:55.695  6969  6993 I BluetoothAdapterState: Entering OffState
,08-17 19:16:55.705  6969  6969 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-17 19:16:55.705  6969  6969 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-17 19:16:55.705  6969  6969 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-17 19:16:55.705  6969  6969 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-17 19:16:55.705  6969  6969 E bt-btif : btif_fetch_local_ble_random_bdaddr
,08-17 19:16:55.705  6969  6969 I bluedroid: get_profile_interface socket
,08-17 19:16:55.705  6969  6969 I bluedroid: get_profile_interface map_client
,08-17 19:16:55.705  6969  6969 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-17 19:16:55.715  6969  6996 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-17 19:16:55.715  6969  6996 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,08-17 19:16:55.715  6969  6996 E BluetoothServiceJni: populateRssiValuesNative
08-17 19:16:55.715  6969  6996 I bluedroid: getModelRssiValues
08-17 19:16:55.715  6969  6996 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-17 19:16:55.715  6969  6996 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-17 19:16:55.715  6969  6996 D BluetoothAdapterProperties: Name is: A5-1
,08-17 19:16:55.715  1012  1012 D SettingsProvider: name = bluetooth_name
,08-17 19:16:55.725  6969  6969 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:16:55.725  1012  1497 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp,
,08-17 19:16:55.725  1012  1497 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:55.725  1012  1497 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 19:16:55.725  1012  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:55.725  1012  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:55.725  6969  6977 I bluedroid: config_hci_snoop_log
,08-17 19:16:55.735  1012  1041 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,08-17 19:16:55.735  1012  1041 D BluetoothManagerService: Ble is always on enable gatt
,08-17 19:16:55.735  1012  1041 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-17 19:16:55.735  1012  1041 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-17 19:16:55.735  1012  1041 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-17 19:16:55.745  6969  6969 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-17 19:16:55.755  1012  1041 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 19:16:55.765  1012  1041 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 19:16:55.775  1012  1041 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-17 19:16:55.785  6969  6993 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-17 19:16:55.785  6969  6993 D BluetoothAdapterProperties: Setting state to 11
,08-17 19:16:55.785  6969  6993 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-17 19:16:55.785  6969  6993 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-17 19:16:55.785  6969  6993 D BluetoothAdapterService: updateAdapterState state is 11
,08-17 19:16:55.785  6969  6993 D BluetoothAdapterService: Autoconnection is available 
,08-17 19:16:55.785  6969  6993 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-17 19:16:55.785  1012  1041 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-17 19:16:55.785  1012  1012 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:55.785  1012  1012 I InputMethodManagerService: [BT Setting State] State =11
,08-17 19:16:55.795  6969  6993 D BluetoothSecureManager: getInstant: null
08-17 19:16:55.795  6969  6993 D BluetoothSecureManager: calling getMethod for getService
08-17 19:16:55.795  6969  6993 D BluetoothSecureManager: calling getService
,08-17 19:16:55.795  6969  6993 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@27f1c480
08-17 19:16:55.795  1012  1474 D BluetoothSecureManagerService: isSecureModeEnabled
,08-17 19:16:55.795  1012  1474 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-17 19:16:55.795  6969  6993 D BtConfig.SecureMode: isSecureModeOn:false
08-17 19:16:55.795  6969  6993 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-17 19:16:55.805  6969  6993 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-17 19:16:55.805  6969  6993 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-17 19:16:55.805  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-17 19:16:55.805  6969  6993 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-17 19:16:55.805  6969  6993 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-17 19:16:55.805  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-17 19:16:55.805  1173  1173 D BluetoothTile:  getBluetoothState : 11
,08-17 19:16:55.805  6969  6993 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-17 19:16:55.805  6969  6993 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-17 19:16:55.805  1888  1888 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-17 19:16:55.805  6969  6993 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
,08-17 19:16:55.805  6969  6993 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-17 19:16:55.805  1312  1312 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:55.815  6969  6993 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-17 19:16:55.815  6969  6993 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-17 19:16:55.815  6969  6993 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-17 19:16:55.815  6969  6993 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-17 19:16:55.815  6969  6993 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-17 19:16:55.815  6969  6993 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-17 19:16:55.815  6969  6993 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-17 19:16:55.815  6969  6993 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-17 19:16:55.815  6969  6993 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:16:55.815  6969  6993 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:16:55.815  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:55.815  1012  1221 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 19:16:55.815  6969  6993 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:16:55.815  1012  1221 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-17 19:16:55.815  6969  6993 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-17 19:16:55.815  6969  6993 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-17 19:16:55.815  6969  6993 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-17 19:16:55.815  1012  1221 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:55.815  1012  1221 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:55.815  1012  1221 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:55.815  6969  6993 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-17 19:16:55.815  1012  2929 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 19:16:55.825  6969  6993 D BluetoothBondStateMachine: make
08-17 19:16:55.825  1012  1025 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-17 19:16:55.825  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 19:16:55.825  6969  6993 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService,
08-17 19:16:55.825  1173  1707 D BluetoothTile:  handleUpdatestate:false name:null
08-17 19:16:55.825  6969  6993 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService,
08-17 19:16:55.825  1173  1707 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-17 19:16:55.825  6969  6993 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-17 19:16:55.825  1312  1312 D BluetoothNotiBroadcastReceiver: onReceive
,08-17 19:16:55.825  1012  1074 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:16:55.825  1012  1074 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
08-17 19:16:55.825  6969  7000 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-17 19:16:55.825  1012  1074 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:55.825  1012  1074 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:55.825  1012  1074 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:55.825  6969  6993 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-17 19:16:55.825  6969  6993 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-17 19:16:55.825  6969  6993 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-17 19:16:55.825  6969  6969 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 19:16:55.835  6969  6969 D BtGatt.GattService: Received start request. Starting profile...
08-17 19:16:55.835  6969  6969 D BtGatt.GattService: start()
08-17 19:16:55.835  6969  6969 D BtGatt.GattService: start()
08-17 19:16:55.835  6969  6969 I bluedroid: get_profile_interface gatt
,08-17 19:16:55.835  6969  6969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1aa1d78b
08-17 19:16:55.835  6969  6969 D BtGatt.AdvertiseManager: advertise manager created
,08-17 19:16:55.835  1012  1541 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:16:55.835  1012  1541 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-17 19:16:55.835  1012  1541 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:55.835  1012  1541 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:55.835  1012  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:55.845  6969  6993 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-17 19:16:55.845  6969  6993 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-17 19:16:55.845  6969  6993 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-17 19:16:55.845  1012  2929 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:55.845  1012  2929 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 19:16:55.845  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-17 19:16:55.845  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-17 19:16:55.845  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-17 19:16:55.845  1012  2929 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:55.845  1012  2929 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:55.845  1012  2929 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:55.855  6969  6993 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-17 19:16:55.855  6969  6993 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-17 19:16:55.855  6969  6993 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-17 19:16:55.855  6969  6969 D BtGatt.GattService: mStartError = false
,08-17 19:16:55.855  6969  6969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1aa1d78b
,08-17 19:16:55.855  1012  1540 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:16:55.855  1012  1540 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-17 19:16:55.855  1012  1540 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:55.855  1012  1540 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:55.855  1012  1540 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:55.855  6969  6969 D HeadsetService: Received start request. Starting profile...
08-17 19:16:55.855  6969  6969 D HeadsetService: start()
,08-17 19:16:55.855  6969  6969 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-17 19:16:55.855  6969  6969 D HeadsetStateMachine: make
,08-17 19:16:55.865  6969  6993 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-17 19:16:55.865  6969  6993 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-17 19:16:55.865  6969  6993 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-17 19:16:55.865  6969  6969 E HeadsetStateMachine: # of Max HF connection is 2
,08-17 19:16:55.875  1012  1497 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-17 19:16:55.875  1012  1497 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-17 19:16:55.875  1012  1497 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:55.875  1012  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:55.875  1012  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-17 19:16:55.875  1012  1025 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:16:55.875  1012  1025 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-17 19:16:55.875  1012  1025 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:55.875  1012  1025 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:55.875  1012  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:55.885  1012  1541 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-17 19:16:55.885  1012  1541 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-17 19:16:55.885  1012  1541 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:55.885  1012  1541 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:55.885  1012  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-17 19:16:55.885  6969  6969 I bluedroid: get_profile_interface handsfree
08-17 19:16:55.885  6969  6993 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-17 19:16:55.885  6969  6993 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-17 19:16:55.885  6969  6993 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-17 19:16:55.885  1012  1478 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 19:16:55.885  1012  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-17 19:16:55.885  1012  1478 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:55.885  1012  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:55.885  1012  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:55.885  6969  6993 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-17 19:16:55.885  6969  6993 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 19:16:55.885  6969  6993 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-17 19:16:55.895  1012  1540 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:55.895  1012  1540 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-17 19:16:55.895  1012  1540 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:55.895  1012  1540 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:55.895  1012  1540 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:55.895  6969  6993 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-17 19:16:55.895  6969  6993 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-17 19:16:55.895  6969  6993 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-17 19:16:55.895  1012  1024 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:55.895  1012  1024 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-17 19:16:55.895  1012  1024 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:55.895  1012  1024 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 19:16:55.895  1012  1024 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:55.905  6969  6993 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-17 19:16:55.905  6969  6993 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-17 19:16:55.905  6969  6993 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,08-17 19:16:55.905  6969  6993 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:16:55.905  6969  6993 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-17 19:16:55.905  6969  6993 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,08-17 19:16:55.905  6969  6993 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-17 19:16:55.905  6969  6993 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-17 19:16:55.905  6969  6993 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-17 19:16:55.905  6969  6993 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-17 19:16:55.905  6969  6969 I DualScoManager: Instantiating Dual Sco Manager
08-17 19:16:55.905  6969  6969 I DualScoManager: Set HeadsetServiceHelper
,08-17 19:16:55.905  6969  6993 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-17 19:16:55.905  6969  6993 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,08-17 19:16:55.905  6969  6993 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-17 19:16:55.905  6969  6969 D BluetoothAtMessage: createCMTIContentObservers
,08-17 19:16:55.905  1012  1360 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-17 19:16:55.905  1012  1360 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:55.905  1012  1360 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:55.905  1012  1360 D SettingsProvider: selectionArgs: false
08-17 19:16:55.905  1012  1360 D SettingsProvider: selectionArgs: 1002
08-17 19:16:55.905  1012  1360 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 19:16:55.905  1012  1360 D SettingsProvider: ret = -1
,08-17 19:16:55.905  6969  7004 D HeadsetStateMachine: Enter Disconnected: -2
,08-17 19:16:55.905  6969  6969 D HeadsetService: mStartError = false
08-17 19:16:55.905  6969  6969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1aa1d78b
,08-17 19:16:55.905  6969  6969 D A2dpService: Received start request. Starting profile...
08-17 19:16:55.905  6969  6969 D A2dpService: start()
,08-17 19:16:55.915  6969  7004 D HeadsetStateMachine: Clear mHeadsetBrsf
08-17 19:16:55.915  6969  6969 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-17 19:16:55.915  6969  7004 D HeadsetStateMachine: map size, before remove : 0
08-17 19:16:55.915  6969  7004 D HeadsetStateMachine: map size, after remove: 0
,08-17 19:16:55.915  6969  6969 I bluedroid: get_profile_interface avrcp
,08-17 19:16:55.915  6969  6969 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-17 19:16:55.935  6969  6969 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-17 19:16:55.935  6969  7008 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-17 19:16:55.935  6969  6969 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-17 19:16:55.935  6969  6969 D A2dpStateMachine: make
,08-17 19:16:55.935  6969  6969 I bluedroid: get_profile_interface a2dp
,08-17 19:16:55.935  6969  7010 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-17 19:16:55.935  6969  6969 E bt-btif : warning : media task started media_task_refcnt 1 
,08-17 19:16:55.945  6969  6969 D A2dpService: mStartError = false
08-17 19:16:55.945  6969  6969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1aa1d78b
,08-17 19:16:55.945  6969  7009 D A2dpStateMachine: Enter Disconnected: -2
,08-17 19:16:55.945  6969  6969 E BluetoothAdapterService(446814091): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-17 19:16:55.945  6969  6969 I BluetoothHidServiceJni: classInitNative: succeeds
,08-17 19:16:55.945  6969  6969 D HidService: Received start request. Starting profile...
08-17 19:16:55.945  6969  6969 D HidService: start()
08-17 19:16:55.945  6969  6969 I bluedroid: get_profile_interface hidhost
08-17 19:16:55.945  6969  6969 D HidService: setHidService(): set to: null
08-17 19:16:55.945  6969  6969 D HidService: mStartError = false
08-17 19:16:55.945  6969  6969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1aa1d78b
,08-17 19:16:55.945  6969  6969 D HeadsetStateMachine: Try to query the phonestate on bind
,08-17 19:16:55.945  1429  1443 I Telecom : BluetoothPhoneService: queryPhoneState
,08-17 19:16:55.945  1429  1429 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-17 19:16:55.945  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-17 19:16:55.955  1429  1443 I Telecom : BluetoothPhoneService: Result of Message : true
,08-17 19:16:55.955  6969  6969 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-17 19:16:55.955  6969  6969 D HealthService: Received start request. Starting profile...
08-17 19:16:55.955  6969  6969 D HealthService: start()
,08-17 19:16:55.955  6969  6969 I bluedroid: get_profile_interface health
08-17 19:16:55.955  6969  6969 D HealthService: mStartError = false
08-17 19:16:55.955  6969  6969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1aa1d78b
08-17 19:16:55.955  6969  6969 D HeadsetStateMachine: Proxy object connected
08-17 19:16:55.955  6969  6969 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-17 19:16:55.955  6969  7004 D HeadsetStateMachine: Disconnected process message: 11
08-17 19:16:55.955  6969  6969 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-17 19:16:55.955  6969  6969 D PanService: Received start request. Starting profile...
08-17 19:16:55.955  6969  6969 D PanService: start()
08-17 19:16:55.955  6969  6969 D BluetoothPanServiceJni: initializeNative(L110): pan
08-17 19:16:55.955  6969  6969 I bluedroid: get_profile_interface pan
,08-17 19:16:55.955  6969  6969 D PanService: mStartError = false
08-17 19:16:55.955  6969  6969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1aa1d78b
,08-17 19:16:55.955  6969  7008 D BluetoothMediaBrowser: no now playing list
08-17 19:16:55.955  6969  7008 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-17 19:16:55.965  1906  1906 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-17 19:16:55.965  6969  6969 D BluetoothMapService: Received start request. Starting profile...
,08-17 19:16:55.965  6969  6969 D BluetoothMapService: start()
,08-17 19:16:55.965  1906  1906 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-17 19:16:55.965  6969  6969 D BluetoothMapService: mStartError = false
08-17 19:16:55.965  6969  6969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1aa1d78b
,08-17 19:16:55.965  6969  6969 D HeadsetPhoneState: sendDeviceDataStateChanged
08-17 19:16:55.965  6969  6969 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-17 19:16:55.965  6969  7004 D HeadsetStateMachine: Disconnected process message: 18
08-17 19:16:55.965  6969  6969 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-17 19:16:55.965  6969  6969 D SapService: Received start request. Starting profile...
,08-17 19:16:55.965  6969  6969 D SapService: start()
,08-17 19:16:55.965  6969  6969 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-17 19:16:55.965  6969  6969 I bluedroid: get_profile_interface sap
08-17 19:16:55.965  6969  6969 D SapService: mStartError = false
08-17 19:16:55.965  6969  6969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1aa1d78b
,08-17 19:16:55.965  6969  6969 E BluetoothAdapterService(446814091): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-17 19:16:55.965  6969  6969 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-17 19:16:55.965  6969  6969 D BluetoothA2dp: Proxy object connected,
08-17 19:16:55.965  6969  6969 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-17 19:16:55.975  6969  6969 E BluetoothAdapterService(446814091): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-17 19:16:55.975  6969  7004 D HeadsetStateMachine: Disconnected process message: 10
08-17 19:16:55.975  6969  6969 E BluetoothAdapterService(446814091): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-17 19:16:55.975  6969  7004 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-17 19:16:55.975  6969  6969 E BluetoothAdapterService(446814091): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-17 19:16:55.975  6969  7004 D HeadsetStateMachine: Disconnected process message: 11
08-17 19:16:55.975  6969  6969 E BluetoothAdapterService(446814091): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-17 19:16:55.995  6969  6969 E BluetoothAdapterService(446814091): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true,
08-17 19:16:55.995  6969  6969 E BluetoothAdapterService(446814091): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-17 19:16:55.995  6969  6993 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-17 19:16:55.995  6969  6993 I bluedroid: enable
,08-17 19:16:55.995  6969  6993 I bt_hci_bdroid: init
08-17 19:16:55.995  6969  7014 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-17 19:16:56.005  6969  6993 I bt_vendor: bt-vendor : init
08-17 19:16:56.005  6969  6993 I bt_vendor: bt-vendor : get_bt_soc_type
08-17 19:16:56.005  6969  6993 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-17 19:16:56.005  6969  6993 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
08-17 19:16:56.005  6969  6993 D bt_userial_mct: userial_init
,08-17 19:16:56.005  6969  6993 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-17 19:16:56.005  6969  6993 I bt_vendor: Starting hciattach daemon
08-17 19:16:56.005  6969  6993 I bt_vendor: try to set false
,08-17 19:16:56.005  6969  6993 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-17 19:16:56.005  6969  6993 I bt_vendor: Starting hciattach daemon
,08-17 19:16:56.005  6969  6993 I bt_vendor: try to set true
,08-17 19:16:56.015  7018  7018 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-17 19:16:56.055  1012  1360 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-17 19:16:56.055  1012  1360 D BatteryService: level:93, scale:100, status:2, health:2, present:true, voltage: 4190, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-17 19:16:56.055  1012  1360 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-17 19:16:56.055  1012  1360 D BatteryService: stay LED for charging,
,08-17 19:16:56.055  1012  1012 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-17 19:16:56.065  1012  1012 I MotionRecognitionService: Plugged
08-17 19:16:56.065  1012  1012 I MotionRecognitionService: mGripSensorEnabled= false,
,08-17 19:16:56.065  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-17 19:16:56.065  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-17 19:16:56.065  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-17 19:16:56.065  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,08-17 19:16:56.075  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,08-17 19:16:56.075  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,08-17 19:16:56.075  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,08-17 19:16:56.085  6969  6969 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-17 19:16:56.085  6969  7004 D HeadsetStateMachine: Disconnected process message: 10
,08-17 19:16:56.095  7024  7024 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-17 19:16:56.105  7025  7025 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-17 19:16:56.125  7027  7027 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-17 19:16:56.125  7028  7028 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-17 19:16:56.135  7029  7029 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-17 19:16:56.145  7030  7030 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-17 19:16:56.425  7033  7033 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab ,
,08-17 19:16:56.435  7034  7034 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-17 19:16:56.455  6969  6993 I bt_vendor: bluetooth satus is on
,08-17 19:16:56.455  6969  7016 D bt_userial_mct: userial_open(port:0)
08-17 19:16:56.455  6969  7016 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-17 19:16:56.465  6969  7016 I bt_vendor: Done intiailizing UART
,08-17 19:16:56.465  6969  7016 I bt_vendor: Done intiailizing UART,
08-17 19:16:56.465  6969  7016 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-17 19:16:56.465  6969  7016 I bt_vendor: Bluetooth Firmware and transport layer are initialized,
08-17 19:16:56.465  6969  7036 D bt_userial_mct: Entering userial_read_thread(),
,08-17 19:16:56.475  6969  7014 I         : BTE_InitTraceLevels -- TRC_HCI
08-17 19:16:56.475  6969  7014 I         : BTE_InitTraceLevels -- TRC_L2CAP,
08-17 19:16:56.475  6969  7014 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-17 19:16:56.475  6969  7014 I         : BTE_InitTraceLevels -- TRC_AVDT
08-17 19:16:56.475  6969  7014 I         : BTE_InitTraceLevels -- TRC_AVRC,
08-17 19:16:56.475  6969  7014 I         : BTE_InitTraceLevels -- TRC_A2D
08-17 19:16:56.475  6969  7014 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-17 19:16:56.475  6969  7014 I         : BTE_InitTraceLevels -- TRC_BTM
08-17 19:16:56.475  6969  7014 I         : BTE_InitTraceLevels -- TRC_GAP
08-17 19:16:56.475  6969  7014 I         : BTE_InitTraceLevels -- TRC_PAN
,08-17 19:16:56.475  6969  7014 I         : BTE_InitTraceLevels -- TRC_SAP
08-17 19:16:56.475  6969  7014 I         : BTE_InitTraceLevels -- TRC_SDP
08-17 19:16:56.475  6969  7014 I         : BTE_InitTraceLevels -- TRC_GATT,
08-17 19:16:56.475  6969  7014 I         : BTE_InitTraceLevels -- TRC_SMP
08-17 19:16:56.475  6969  7014 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-17 19:16:56.475  6969  7014 I         : BTE_InitTraceLevels -- TRC_BTIF
08-17 19:16:56.475  6969  7014 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-17 19:16:56.575  6969  7014 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-17 19:16:56.575  6969  7014 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa3f386e9 
,08-17 19:16:56.585  6969  7014 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3f386e9 
,08-17 19:16:56.585  1012  2772 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-17 19:16:56.595  6969  6996 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-17 19:16:56.605  6969  6996 E bt-btif : Calling BTA_HhEnable
,08-17 19:16:56.605  6969  6996 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-17 19:16:56.605  6969  6996 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,08-17 19:16:56.605  6969  6996 E BluetoothServiceJni: populateRssiValuesNative
08-17 19:16:56.605  6969  6996 I bluedroid: getModelRssiValues
,08-17 19:16:56.605  6969  6996 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-17 19:16:56.605  6969  6996 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-17 19:16:56.615  1012  1012 D SettingsProvider: name = bluetooth_name
,08-17 19:16:56.615  6969  6996 D BluetoothAdapterProperties: Name is: A5-1
,08-17 19:16:56.615  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:56.615  6969  6996 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-17 19:16:56.615  6969  6996 D BluetoothAdapterProperties: Scan Mode:20
,08-17 19:16:56.615  6969  6996 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-17 19:16:56.625  6969  6996 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
,08-17 19:16:56.625  6969  6996 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,08-17 19:16:56.625  6969  6996 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,08-17 19:16:56.625  6969  6996 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,08-17 19:16:56.625  6969  6996 E bt-btif : btif_sock_init: !vhci_init
,08-17 19:16:56.625  6969  7036 E bt_mct  : hci lib postload completed
,08-17 19:16:56.625  6969  6996 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-17 19:16:56.625  6969  6996 D IOP_DB_BT: db_open: db_open : handle 3027972112l, read 13894 bytes onto local cache
,08-17 19:16:56.625  6969  6996 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-17 19:16:56.625  6969  6996 D IOP_DB_BT: db_query: result 1
,08-17 19:16:56.625  6969  6996 I         : iop_db_open: iop_db_open status 0
,08-17 19:16:56.625  6969  6996 D bte_conf: Device ID record 1 : primary
08-17 19:16:56.625  6969  6996 D bte_conf:   vendorId            = 0075
08-17 19:16:56.625  6969  6996 D bte_conf:   vendorIdSource      = 0001
08-17 19:16:56.625  6969  6996 D bte_conf:   product             = 0100
08-17 19:16:56.625  6969  6996 D bte_conf:   version             = 0200
08-17 19:16:56.625  6969  6996 D bte_conf:   clientExecutableURL = 
08-17 19:16:56.625  6969  6996 D bte_conf:   serviceDescription  = 
08-17 19:16:56.625  6969  6996 D bte_conf:   documentationURL    = 
08-17 19:16:56.625  6969  6996 D bte_conf: bte_load_did_conf no section named DID2.
,08-17 19:16:56.635  6969  6993 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-17 19:16:56.635  6969  6993 D BluetoothAdapterProperties: ScanMode =  20
,08-17 19:16:56.635  6969  6993 D BluetoothAdapterProperties: State =  11
08-17 19:16:56.635  6969  6996 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-17 19:16:56.635  1012  1478 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-17 19:16:56.635  6969  6993 D BluetoothAdapterProperties: Setting state to 12
,08-17 19:16:56.635  6969  6993 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-17 19:16:56.645  6969  6996 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-17 19:16:56.645  6969  6996 D BluetoothAdapterProperties: Scan Mode:21
08-17 19:16:56.645  6969  6996 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-17 19:16:56.645  1012  1360 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-17 19:16:56.645  1012  1360 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 19:16:56.645  1012  1360 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 19:16:56.645  1012  1360 D SettingsProvider: selectionArgs: false
08-17 19:16:56.645  1012  1360 D SettingsProvider: selectionArgs: 1002,
08-17 19:16:56.645  1012  1360 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-17 19:16:56.645  1012  1360 D SettingsProvider: ret = -1
08-17 19:16:56.645  6969  6993 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-17 19:16:56.645  6969  6993 D BluetoothAdapterService: updateAdapterState state is 12
,08-17 19:16:56.645  1012  1497 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:56.645  1012  1497 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-17 19:16:56.645  1012  1497 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:56.645  1012  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:56.645  1012  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:56.655  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:56.655  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:56.655  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:56.655  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:16:56.655  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:56.655  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:56.655  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:56.655  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:16:56.655  6298  6298 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:16:56.655  6969  6993 D BluetoothAdapterService: Autoconnection is available 
,08-17 19:16:56.655  6969  6993 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-17 19:16:56.655  6969  6993 D BluetoothAdapterService: starting service from this receiver
,08-17 19:16:56.665  1312  1327 D Bluetoothsap: onBluetoothStateChange: up=true
08-17 19:16:56.665  1312  1327 D Bluetoothsap: Binding service...
08-17 19:16:56.665  1012  1474 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:56.665  1012  1474 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-17 19:16:56.665  1012  1474 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:56.665  1312  1327 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
08-17 19:16:56.665  1012  1474 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:56.665  1012  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:56.665  6969  6993 I BluetoothAdapterState: Entering On State from state = 11
08-17 19:16:56.665  1012  1041 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-17 19:16:56.665  1012  1041 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-17 19:16:56.665  1012  1041 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:56.665  1012  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:56.665  1012  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-17 19:16:56.665  1312  1327 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-17 19:16:56.675  2889  6940 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:16:56.675  2889  6940 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:16:56.675  1173  1186 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:16:56.675  1173  1186 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:16:56.675  1429  6942 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:16:56.675  1429  6942 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:16:56.675  2889  2897 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 19:16:56.675  2889  2897 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:16:56.675  1012  1041 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-17 19:16:56.675  1012  1041 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 19:16:56.675  6969  6969 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-17 19:16:56.685  6298  6363 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:56.685  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:56.685  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:56.685  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:16:56.685  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:56.685  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:56.685  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:56.685  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:16:56.685  6298  6363 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:16:56.685  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 19:16:56.685  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@34831b01 added. We now have 8 listener(s)
,08-17 19:16:56.685  6298  6363 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 19:16:56.695  1012  1041 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:56.695  1012  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:56.695  1012  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:56.695  2889  2889 D BluetoothA2dp: Proxy object connected
,08-17 19:16:56.695  1906  1917 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-17 19:16:56.695  1906  1917 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:16:56.695  6969  6999 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 19:16:56.695  1312  6396 D BluetoothPan: Binding service...
,08-17 19:16:56.695  1012  1041 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-17 19:16:56.695  1012  1041 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-17 19:16:56.695  1012  1041 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:56.695  1012  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:56.695  1012  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:56.695  1012  1041 D BluetoothA2dp: onBluetoothStateChange: up=true
08-17 19:16:56.695  1012  1041 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:16:56.695  1012  1041 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-17 19:16:56.695  1012  1041 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 19:16:56.705  1012  1360 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-17 19:16:56.705  1012  1360 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-17 19:16:56.705  1012  1360 D SecContentProvider2: mCursor = null
08-17 19:16:56.705  1012  1012 D BluetoothA2dp: Proxy object connected
,08-17 19:16:56.705  1312  1312 D Bluetoothsap: BluetoothSAP Proxy object connected
08-17 19:16:56.705  1312  1312 D SapProfile: Bluetooth service connected
08-17 19:16:56.705  1312  1312 D Bluetoothsap: getConnectedDevices()
08-17 19:16:56.705  6969  6969 I BluetoothPbapService: Handler(): got msg=1
,08-17 19:16:56.705  2889  6940 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:16:56.705  1012  1025 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-17 19:16:56.705  1012  1041 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 19:16:56.705  1012  1041 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-17 19:16:56.705  1012  1041 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:56.705  1012  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:56.705  1012  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:56.705  2889  6940 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 19:16:56.705  1312  1327 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:16:56.705  1312  1327 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:16:56.705  1012  1360 D SettingsProvider: name = wifi_on
08-17 19:16:56.705  1012  1360 D WifiService: setWifiEnabled: false pid=6298, uid=10155
,08-17 19:16:56.715  6969  6999 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:16:56.715  6969  6999 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:16:56.715  1312  6396 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-17 19:16:56.715  1312  1312 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 19:16:56.715  1312  1312 D PanProfile: Bluetooth service connected
,08-17 19:16:56.715  6969  7041 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-17 19:16:56.715  1012  1041 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-17 19:16:56.715  1012  1041 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-17 19:16:56.715  1012  1041 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:56.715  1012  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:56.715  1012  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:56.715  1012  1041 D BluetoothPan: Binding service...
,08-17 19:16:56.715  1012  1041 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-17 19:16:56.725  1012  1041 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-17 19:16:56.725  1312  1326 D BluetoothPbap: onBluetoothStateChange: up=true
08-17 19:16:56.725  1312  1312 D BluetoothInputDevice: Proxy object connected
08-17 19:16:56.725  1312  1312 D HidProfile: Bluetooth service connected
08-17 19:16:56.725  1012  1012 D BluetoothPan: BluetoothPAN Proxy object connected
,08-17 19:16:56.725  6298  6363 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:56.725  1012  1041 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,08-17 19:16:56.725  1012  1041 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-17 19:16:56.725  1012  1041 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:56.725  1012  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:56.725  1012  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:56.725  1012  1360 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-17 19:16:56.725  1012  1360 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-17 19:16:56.725  1012  1360 D SecContentProvider2: mCursor = null
,08-17 19:16:56.725  1012  1360 D WifiService: setWifiEnabled: true pid=6298, uid=10155
08-17 19:16:56.725  1012  1360 W ActivityManager: Permission Denial: getCurrentUser() from pid=6298, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,08-17 19:16:56.725  6969  7041 D BluetoothSocket: bindListen(): myUserId = 0
08-17 19:16:56.725  1012  1360 W WifiService: Failed getting userId using ActivityManagerNative
08-17 19:16:56.725  1012  1360 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6298, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-17 19:16:56.725  1012  1360 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-17 19:16:56.725  1012  1360 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-17 19:16:56.725  1012  1360 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-17 19:16:56.725  1012  1360 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-17 19:16:56.725  1012  1360 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-17 19:16:56.725  6969  7041 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 19:16:56.725  1012  1360 D SettingsProvider: name = wifi_on
08-17 19:16:56.725  1429  1443 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:16:56.725  1312  1312 D BluetoothPbap: Proxy object connected
08-17 19:16:56.725  1312  1312 D PbapServerProfile: Bluetooth service connected
08-17 19:16:56.725  1012  1041 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 19:16:56.725  1012  1041 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-17 19:16:56.725  6969  7041 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
08-17 19:16:56.725  6969  7041 D BluetoothSocket: bindListen(), new LocalSocket 
08-17 19:16:56.725  6969  7041 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-17 19:16:56.725  6969  7041 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1cf8d1a4
,08-17 19:16:56.735  6969  7041 D BluetoothSocket: channel: 19
08-17 19:16:56.735  6969  7041 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-17 19:16:56.735  1012  1041 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:56.735  1012  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:56.735  1012  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:56.735  1429  1443 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 19:16:56.735  1012  1126 E WifiHW  : ##################### set firmware type 0 #####################
,08-17 19:16:56.735  1453  1760 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:16:56.735  1453  1760 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:16:56.735  1012  1041 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:16:56.735  1012  1041 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 19:16:56.735  1012  1041 E BluetoothHeadset: BluetoothHeadset service is binded
08-17 19:16:56.735  1012  1041 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 19:16:56.745  1312  1326 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 19:16:56.745  1312  1326 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:16:56.745  1012  1041 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-17 19:16:56.745  1012  1041 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 19:16:56.745  1012  1041 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:56.745  1012  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:56.745  1012  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:56.745  1312  1312 D BluetoothA2dp: Proxy object connected
,08-17 19:16:56.745  1429  6942 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:16:56.745  1312  1312 D A2dpProfile: Bluetooth service connected
08-17 19:16:56.745  1012  1041 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 19:16:56.745  1012  1041 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 19:16:56.745  1012  1041 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:56.745  1012  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:56.745  1012  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:56.745  1429  6942 E BluetoothHeadset: BluetoothHeadset service is binded
08-17 19:16:56.745  1442  1451 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:16:56.745  1442  1451 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-17 19:16:56.745  1012  1041 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:16:56.745  1012  1041 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 19:16:56.755  1312  1327 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:16:56.755  1012  1041 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 19:16:56.755  1012  1041 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 19:16:56.755  1012  1041 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:56.755  1012  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:56.755  1012  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:56.755  1312  1327 E BluetoothHeadset: BluetoothHeadset service is binded
08-17 19:16:56.755  1312  1312 D HeadsetProfile: Bluetooth service connected
08-17 19:16:56.755  6298  6308 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 19:16:56.755  6298  6308 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-17 19:16:56.755  1312  1326 D BluetoothMap: onBluetoothStateChange: up=true
,08-17 19:16:56.755  1012  1041 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-17 19:16:56.755  1012  1041 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-17 19:16:56.755  1012  1041 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:56.755  1012  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:56.755  1012  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:56.755  6422  6436 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-17 19:16:56.755  6422  6436 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-17 19:16:56.755  1312  1312 D BluetoothMap: Proxy object connected
08-17 19:16:56.755  1312  1312 D MapProfile: Bluetooth service connected
08-17 19:16:56.755  1312  1312 D BluetoothMap: getConnectedDevices()
,08-17 19:16:56.765  1429  1443 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:16:56.765  1012  1041 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 19:16:56.765  1012  1041 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 19:16:56.765  1012  1041 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:56.765  1012  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:56.765  1012  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:56.765  1429  1443 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 19:16:56.765  1453  1467 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 19:16:56.765  1012  1041 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-17 19:16:56.765  1012  1041 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 19:16:56.765  1012  1041 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:56.765  1012  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:56.765  1012  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
08-17 19:16:56.765  1453  1467 E BluetoothHeadset: BluetoothHeadset service is binded
08-17 19:16:56.765  1012  1041 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-17 19:16:56.765  1012  1041 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
08-17 19:16:56.765  1012  1012 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-17 19:16:56.765  1012  1012 I InputMethodManagerService: [BT Setting State] State =12
08-17 19:16:56.765  1012  1012 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-17 19:16:56.775  1173  1173 D BluetoothTile:  onBluetoothStateChange:
,08-17 19:16:56.775  1173  1707 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 19:16:56.775  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-17 19:16:56.785  1429  1429 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@375982e0, true
,08-17 19:16:56.785  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-17 19:16:56.785  1173  1707 D BluetoothTile:  handleUpdatestate:false name:null
08-17 19:16:56.785  1173  1173 D BluetoothTile:  getBluetoothState : 12
,08-17 19:16:56.785  1429  1429 D BluetoothHeadset: registerMessageListener
,08-17 19:16:56.785  1173  1707 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 19:16:56.785  1888  1888 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-17 19:16:56.785  1012  1497 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 19:16:56.785  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 19:16:56.785  1012  2930 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
08-17 19:16:56.785  1312  1312 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:16:56.795  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:56.795  1012  1540 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 19:16:56.795  1012  1540 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-17 19:16:56.795  6969  6979 D HeadsetService: registerMessageListener
,08-17 19:16:56.795  1012  1540 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:56.795  6969  6979 D HeadsetService: registerMessageListener
,08-17 19:16:56.795  1012  1540 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:56.795  1012  1540 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-17 19:16:56.795  6969  7004 D HeadsetStateMachine: Disconnected process message: 70
08-17 19:16:56.795  1429  1429 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
,08-17 19:16:56.795  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-17 19:16:56.795  6969  7004 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@2ea96b0d
,08-17 19:16:56.805  1429  1429 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,08-17 19:16:56.805  1429  1429 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-17 19:16:56.805  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-17 19:16:56.805  1312  1312 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,08-17 19:16:56.805  1312  1312 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
,08-17 19:16:56.815  1312  1312 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-17 19:16:56.815  1312  1312 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
08-17 19:16:56.815  6969  7004 D HeadsetStateMachine: Disconnected process message: 9
,08-17 19:16:56.815  6969  7004 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
08-17 19:16:56.815  6969  7045 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-17 19:16:56.815   282  1072 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-17 19:16:56.815   282  1072 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-17 19:16:56.815   282  1072 V voice   : voice_set_parameters: exit with code(-2)
08-17 19:16:56.815   282  1072 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-17 19:16:56.815   282  1072 V msm8974_platform: platform_set_parameters: exit with code(-2)
,08-17 19:16:56.815   282  1072 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-17 19:16:56.815   282  1072 V audio_hw_primary: adev_set_parameters: exit
08-17 19:16:56.815  6969  7004 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-17 19:16:56.825  6969  7045 D BluetoothSocket: bindListen(): myUserId = 0
,08-17 19:16:56.825  6969  7045 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 19:16:56.825  1312  1312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-17 19:16:56.825  1012  1540 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-17 19:16:56.825  1012  1540 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
08-17 19:16:56.825  6969  7045 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
08-17 19:16:56.825  6969  7045 D BluetoothSocket: bindListen(), new LocalSocket 
08-17 19:16:56.825  6969  7045 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-17 19:16:56.825  6969  7045 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@15cebac2
,08-17 19:16:56.825  6969  7045 D BluetoothSocket: channel: 5
08-17 19:16:56.825  1012  1540 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:56.825  1012  1540 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:56.825  1012  1540 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-17 19:16:56.835  1312  1312 D DockEventReceiver: finishStartingService: stopping service
,08-17 19:16:56.835  1312  1312 D BluetoothNotiBroadcastReceiver: onReceive
,08-17 19:16:56.845  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-17 19:16:56.845  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-17 19:16:56.845  6969  6969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1aa1d78b
,08-17 19:16:56.845  1012  1360 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 19:16:56.845  6969  6969 D BtConfig.SecureMode: isSecureModeOn:false
08-17 19:16:56.845  1012  1360 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-17 19:16:56.855  1012  1360 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:56.855  1012  1360 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:56.855  1012  1360 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 19:16:56.865  1906  1906 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-17 19:16:56.865  1012  1478 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 19:16:56.865  1012  1478 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-17 19:16:56.865  1012  1478 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:56.865  1012  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:56.865  1012  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:56.875  1906  7051 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-17 19:16:56.875  1012  2930 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-17 19:16:56.875  1906  1906 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-17 19:16:56.885  1012  1541 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:16:56.885  1012  1541 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:56.885  1012  1541 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:56.885  1012  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:56.895  1012  1541 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 19:16:56.895  6969  7055 D BluetoothSocket: bindListen(): myUserId = 0
08-17 19:16:56.905  6969  7055 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 19:16:56.905  1012  1541 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:56.905  1012  1541 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 19:16:56.905  1012  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 19:16:56.905  6969  7055 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
08-17 19:16:56.905  6969  7055 D BluetoothSocket: bindListen(), new LocalSocket 
08-17 19:16:56.905  6969  7055 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-17 19:16:56.905  6969  7055 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1451c10e
,08-17 19:16:56.905  6969  7055 D BluetoothSocket: channel: 12
08-17 19:16:56.905  6969  7055 I BtOppRfcommListener: Accept thread started.
,08-17 19:16:56.915  1906  7051 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-17 19:16:57.125  1012  1039 D Tethering: interfaceLinkStateChanged wlan0, false,
08-17 19:16:57.125  1012  1039 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:16:57.125  1012  1039 D Tethering: interfaceStatusChanged wlan0, false,
,08-17 19:16:57.125  1012  1039 D Tethering: interfaceAdded wlan0
,08-17 19:16:57.135  1012  1129 E Tethering: No numeric data
08-17 19:16:57.135  1012  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-17 19:16:57.135  1012  1039 D Tethering: interfaceAdded p2p0
08-17 19:16:57.135  1012  1039 D Tethering: p2p0 is not a tetherable iface, ignoring
08-17 19:16:57.145  1012  1129 D Tethering: clearTetheredNotification()
,08-17 19:16:57.145  1012  1039 D Tethering: interfaceLinkStateChanged p2p0, false
08-17 19:16:57.145  1012  1039 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-17 19:16:57.145  1012  1039 D Tethering: interfaceStatusChanged p2p0, false
08-17 19:16:57.145  1012  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:57.145  1012  1123 V NetworkStats: performPollLocked(flags=0x1)
,08-17 19:16:57.145  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-17 19:16:57.145  1173  1173 D HotspotTile: updateTetherState():false, false
,08-17 19:16:57.155   277   962 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-17 19:16:57.155  1012  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 19:16:57.155  1012  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-17 19:16:57.155   277   962 D SoftapController: Softap fwReload - Ok
,08-17 19:16:57.155   277   962 D CommandListener: Setting iface cfg,
08-17 19:16:57.155  1012  1123 V NetworkStats: performPollLocked() took 12ms
08-17 19:16:57.155   277   962 D CommandListener: Trying to bring down wlan0
08-17 19:16:57.155  1012  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:57.155   277   962 D CommandListener: Clearing all IP addresses on wlan0
,08-17 19:16:57.155  1012  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:57.155  1012  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:57.165  1012  1126 E WifiHW  : supplicant_name : p2p_supplicant
,08-17 19:16:57.165  1012  1126 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-17 19:16:57.175  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:16:57.175  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-17 19:16:57.175  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:57.175  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:57.175  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:57.175  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:57.175  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-17 19:16:57.175  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-17 19:16:57.175  1173  1707 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-17 19:16:57.175  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-17 19:16:57.185  1173  1173 D HotspotTile: onReceive : 2, 0
,08-17 19:16:57.185  1312  1312 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-17 19:16:57.185  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:57.185  1012  2930 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-17 19:16:57.195  1012  2930 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 19:16:57.195  1012  2930 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:16:57.195  1012  2930 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:57.195  1012  2930 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 19:16:57.195  3642  3642 I Hs20UtilService: Starting #19
,08-17 19:16:57.195  3642  3679 I Hs20UtilService: Message received 5011
,08-17 19:16:57.195  6526  6526 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-17 19:16:57.195  6526  6526 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-17 19:16:57.195  6526  6526 D SecurityLogAgent: StateMachine : Current State = 1
08-17 19:16:57.205  6526  6526 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 19:16:57.215  7063  7063 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,08-17 19:16:57.215  7063  7063 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-17 19:16:57.215  7063  7063 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-17 19:16:57.235  7063  7063 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
08-17 19:16:57.235   367   367 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7063
08-17 19:16:57.235   367   367 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-17 19:16:57.235  7063  7063 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-17 19:16:57.235  7063  7063 I wpa_supplicant: ssSupport state is = 1
08-17 19:16:57.235  7063  7063 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-17 19:16:57.235  7063  7063 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-17 19:16:57.235   367   367 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7063
08-17 19:16:57.235   367   367 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
,08-17 19:16:57.375   367   367 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0,
,08-17 19:16:57.385  7063  7063 I SecureStorage: [INFO]: SPID(0x00000004)Processing data has been completed,
,08-17 19:16:57.455  7063  7063 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-17 19:16:57.455  7063  7063 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,08-17 19:16:57.465  7063  7063 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
08-17 19:16:57.465   367   367 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7063,
08-17 19:16:57.465   367   367 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
,08-17 19:16:57.465  7063  7063 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
08-17 19:16:57.465  7063  7063 I wpa_supplicant: ssSupport state is = 1
08-17 19:16:57.465  7063  7063 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 19:16:57.465  7063  7063 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 19:16:57.465  7063  7063 E wpa_supplicant: SIM READ ERROR
08-17 19:16:57.465  7063  7063 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 19:16:57.465  7063  7063 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 19:16:57.465  7063  7063 E wpa_supplicant: SIM READ ERROR
08-17 19:16:57.465  7063  7063 I wpa_supplicant: Blacklist: Clear (all) 
08-17 19:16:57.465  7063  7063 I wpa_supplicant: wpa_default_ap_write_once
08-17 19:16:57.465  7063  7063 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-17 19:16:57.465  7063  7063 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 19:16:57.465  7063  7063 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-17 19:16:57.465  7063  7063 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 19:16:57.465  7063  7063 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 19:16:57.465  7063  7063 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-17 19:16:57.465  1012  1039 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-17 19:16:57.465  1012  1039 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:16:57.465  1012  1039 D Tethering: interfaceStatusChanged wlan0, false
08-17 19:16:57.475  1012  1129 D Tethering: InitialState.processMessage what=4
,08-17 19:16:57.475  1012  1129 E Tethering: No numeric data,
08-17 19:16:57.475  1012  1123 V NetworkStats: performPollLocked(flags=0x1)
08-17 19:16:57.475  1012  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0,
08-17 19:16:57.475  1012  1129 D Tethering: clearTetheredNotification()
08-17 19:16:57.475  1012  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:57.475  1012  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 19:16:57.475  1012  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 19:16:57.485  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-17 19:16:57.485  1173  1173 D HotspotTile: updateTetherState():false, false,
08-17 19:16:57.485  1012  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:57.485  1012  1123 V NetworkStats: performPollLocked() took 8ms
08-17 19:16:57.485  1012  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:57.485  1012  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:57.495   287   287 E SMD     : DCD OFF,
,08-17 19:16:57.535  7063  7063 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-17 19:16:57.865  7063  7063 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-17 19:16:57.865  7063  7063 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage,
,08-17 19:16:57.885  7063  7063 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
,08-17 19:16:57.885   367   367 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7063
08-17 19:16:57.885   367   367 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
08-17 19:16:57.885  7063  7063 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
08-17 19:16:57.885  7063  7063 I wpa_supplicant: ssSupport state is = 1
,08-17 19:16:57.885  7063  7063 I wpa_supplicant: Ctrl_iface: loading cred from phone
,08-17 19:16:57.885  7063  7063 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,08-17 19:16:57.905  7063  7063 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
,08-17 19:16:57.915   367   367 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7063
08-17 19:16:57.915   367   367 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
08-17 19:16:57.915  7063  7063 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
08-17 19:16:57.915  7063  7063 I wpa_supplicant: ssSupport state is = 1
08-17 19:16:57.915  7063  7063 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 19:16:57.915  7063  7063 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 19:16:57.915  7063  7063 E wpa_supplicant: SIM READ ERROR
08-17 19:16:57.915  7063  7063 I wpa_supplicant: wpa_default_ap_write_once
08-17 19:16:57.915  7063  7063 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-17 19:16:57.915  7063  7063 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-17 19:16:57.915  1012  1039 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-17 19:16:57.915  1012  1039 D Tethering: interfaceLinkStateChanged p2p0, false
08-17 19:16:57.915  1012  1039 D Tethering: interfaceStatusChanged p2p0, false
,08-17 19:16:57.915  1012  1039 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-17 19:16:57.915  1012  1039 D Tethering: interfaceLinkStateChanged p2p0, false
08-17 19:16:57.915  1012  1039 D Tethering: interfaceStatusChanged p2p0, false,
,08-17 19:16:57.985  7063  7063 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-17 19:16:57.985  7063  7063 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-17 19:16:58.025  7063  7063 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-17 19:16:58.025  7063  7063 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,08-17 19:16:58.025  7063  7063 I wpa_supplicant: Skip scan - bUseNetwork false
,08-17 19:16:58.035  1012  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
08-17 19:16:58.035  1012  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-17 19:16:58.035  7063  7063 I wpa_supplicant: HOTSPOT20_ENABLE called,
08-17 19:16:58.045  7063  7063 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 19:16:58.045  7063  7063 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-17 19:16:58.045  7063  7063 E wpa_supplicant: SIM READ ERROR
08-17 19:16:58.045  7063  7063 I wpa_supplicant: Blacklist: Clear (all) ,
,08-17 19:16:58.055  7063  7063 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-17 19:16:58.065  1012  1126 D WifiNative-wlan0: callSECApiInt - ID [210]
,08-17 19:16:58.065  7063  7063 I wpa_supplicant: Skip scan - bUseNetwork false
,08-17 19:16:58.065  1012  1126 D WifiConfigStore: Loading config and enabling all networks 
,08-17 19:16:58.065  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 19:16:58.065  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 19:16:58.065  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:58.065  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:58.065  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:58.065  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:58.065  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 19:16:58.065  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-17 19:16:58.065  1173  1707 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-17 19:16:58.075  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-17 19:16:58.075  1173  1173 D HotspotTile: onReceive : 3, 0
,08-17 19:16:58.075  1312  1312 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-17 19:16:58.085  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:58.085  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:58.085  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:58.085  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:58.085  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:58.085  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:58.085  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:58.085  6298  6298 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:16:58.085  1012  1474 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 19:16:58.085  1012  1474 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 19:16:58.085  1012  1474 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:58.085  1012  1474 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:16:58.085  1012  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 19:16:58.085  1012  1126 E WifiConfigStore: Not a HS20
,08-17 19:16:58.085  1012  1126 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-17 19:16:58.085  3642  3642 I Hs20UtilService: Starting #20
,08-17 19:16:58.085  6298  6298 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:16:58.085  3642  3679 I Hs20UtilService: Message received 5011
,08-17 19:16:58.095  6526  6526 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-17 19:16:58.095  1012  1126 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-17 19:16:58.095  6526  6526 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-17 19:16:58.095  6526  6526 D SecurityLogAgent: StateMachine : Current State = 1
08-17 19:16:58.095  6526  6526 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 19:16:58.095  1012  1126 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-17 19:16:58.095  7063  7063 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-17 19:16:58.095  7063  7063 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-17 19:16:58.095  7063  7063 I wpa_supplicant: reset timer : RESET_TIMER 0
08-17 19:16:58.095  7063  7063 I wpa_supplicant: P2P: Current p2p state = IDLE
08-17 19:16:58.095  7063  7063 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-17 19:16:58.095  7063  7063 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-17 19:16:58.095  7063  7063 I wpa_supplicant: First Scan Start
,08-17 19:16:58.095  7063  7063 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-17 19:16:58.105  1012  1126 D WifiNative-wlan0: Setting external_sim to 1
,08-17 19:16:58.105  1012  1126 D WifiStateMachine: Setting OUI to DA-A1-19
08-17 19:16:58.105  1012  1126 I WifiNative-HAL: startHal
08-17 19:16:58.105  1012  1126 E wifi    : getStaticLongField sWifiHalHandle 0x9ca2a88c
08-17 19:16:58.105  1012  1126 I WifiNative-HAL: Could not start hal
,08-17 19:16:58.105  6466  6466 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 19:16:58.105  1012  1126 E WifiNative-wlan0: do suspend true
,08-17 19:16:58.105  1012  1125 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-17 19:16:58.105   277   962 D CommandListener: Setting iface cfg
08-17 19:16:58.105   277   962 D CommandListener: Trying to bring up p2p0
,08-17 19:16:58.105  1012  1125 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-17 19:16:58.115  1012  1125 D WifiP2pService: P2pEnablingState
,08-17 19:16:58.115  1012  1125 D WifiP2pService: P2pEnablingState{ what=147457 }
,08-17 19:16:58.115  1012  1125 D WifiP2pService: P2p socket connection successful
,08-17 19:16:58.115  1012  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-17 19:16:58.115  1012  1012 D WifiScanningService: SCAN_AVAILABLE : 3
,08-17 19:16:58.115  1012  1148 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,08-17 19:16:58.115  1012  1148 I WifiNative-HAL: startHal
08-17 19:16:58.115  1012  1148 E wifi    : getStaticLongField sWifiHalHandle 0x9dcda9bc
,08-17 19:16:58.115  1012  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-17 19:16:58.115  1012  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-17 19:16:58.115  1012  1126 E WifiNative-wlan0: invaild command id : 215
,08-17 19:16:58.115  1012  1148 I WifiNative-HAL: Could not start hal
08-17 19:16:58.115  1012  1125 D WifiP2pService: P2pEnabledState,
08-17 19:16:58.115  1012  1148 E WifiScanningService: could not start HAL
08-17 19:16:58.115  1012  1012 D RttService: SCAN_AVAILABLE : 3
08-17 19:16:58.115  1012  1149 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-17 19:16:58.115  1012  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
,08-17 19:16:58.115  1012  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-17 19:16:58.115  1012  1126 E WifiNative-wlan0: invaild command id : 215
,08-17 19:16:58.115  1012  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-17 19:16:58.125  7063  7063 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-17 19:16:58.125  1012  1128 E ConnectivityService: updateNetworkInfo()
,08-17 19:16:58.125  1012  1039 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-17 19:16:58.125  1012  1039 D Tethering: interfaceLinkStateChanged p2p0, false
08-17 19:16:58.125  1012  1039 D Tethering: interfaceStatusChanged p2p0, false
,08-17 19:16:58.125  7063  7063 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-17 19:16:58.125  1012  1012 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-17 19:16:58.125  1012  1042 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-17 19:16:58.125  1012  1042 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-17 19:16:58.125  1012  1042 D WifiDisplayController: disconnect
08-17 19:16:58.125  1012  1042 D WifiDisplayController: updateConnection
08-17 19:16:58.125  1012  1042 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-17 19:16:58.125  1012  1042 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-17 19:16:58.125  7063  7063 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN,
,08-17 19:16:58.125  1012  1125 D WifiNative-p2p0: p2pGetDeviceAddress
,08-17 19:16:58.125  1012  1042 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-17 19:16:58.135  1012  1042 D WifiDisplayAdapter: onP2pDisconnected
08-17 19:16:58.135  1012  1125 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
08-17 19:16:58.135  1012  1042 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-17 19:16:58.135  1012  1042 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-17 19:16:58.135  1012  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-17 19:16:58.135  1012  1126 D SecContentProvider2: mCursor = null
08-17 19:16:58.135  1173  1173 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-17 19:16:58.135  1012  1540 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-17 19:16:58.135  1173  1173 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-17 19:16:58.135  1312  1312 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-17 19:16:58.135  1312  1312 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-17 19:16:58.135  1012  1125 D WifiP2pService: DeviceAddress: 7e:96:ac
,08-17 19:16:58.135  1012  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 19:16:58.135  1012  1126 D SecContentProvider2: mCursor = null
08-17 19:16:58.135  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-17 19:16:58.135  1012  1042 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
08-17 19:16:58.135  1012  1042 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
08-17 19:16:58.135  1012  1042 D WifiDisplayController:  primary type: 10-0050F204-5
08-17 19:16:58.135  1012  1042 D WifiDisplayController:  secondary type: null
08-17 19:16:58.135  1012  1042 D WifiDisplayController:  wps: 0
08-17 19:16:58.135  1012  1042 D WifiDisplayController:  grpcapab: 0
08-17 19:16:58.135  1012  1042 D WifiDisplayController:  devcapab: 0
08-17 19:16:58.135  1012  1042 D WifiDisplayController:  status: 3
08-17 19:16:58.135  1012  1042 D WifiDisplayController:  wfdInfo: null
08-17 19:16:58.135  1012  1042 D WifiDisplayController:  groupownerAddress: null
08-17 19:16:58.135  1012  1042 D WifiDisplayController:  GOdeviceName: null
08-17 19:16:58.135  1012  1042 D WifiDisplayController:  interfaceAddress: 
08-17 19:16:58.135  1012  1042 D WifiDisplayController:  SConnectInfo : null
,08-17 19:16:58.135  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-17 19:16:58.135  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 19:16:58.135  1312  1312 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-17 19:16:58.135  1312  3094 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 19:16:58.145  6495  6495 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-17 19:16:58.145  6495  6495 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-17 19:16:58.145  6495  6495 D FileShare-Client: Outbound.stopDelayTimer - 
,08-17 19:16:58.155  1012  1125 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-17 19:16:58.155  1012  1125 D WifiP2pService: InactiveState
08-17 19:16:58.155  6510  6510 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
08-17 19:16:58.155  1012  1125 D WifiP2pService: InactiveState{ what=143376 }
,08-17 19:16:58.155  1012  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-17 19:16:58.155  7063  7063 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-17 19:16:58.155  1012  1125 D WifiP2pService: InactiveState{ what=143376 }
,08-17 19:16:58.155  1012  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-17 19:16:58.265  1012  2745 D SSRM:n  : SIOP:: AP = 320
,08-17 19:16:58.525   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-17 19:16:58.745  6298  6363 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:16:58.745  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:58.745  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:58.745  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:58.745  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:58.745  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:58.745  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:58.745  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:16:58.745  6298  6363 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:16:58.755  6298  6363 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-17 19:16:58.755  6298  6363 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-17 19:16:58.755  6298  6363 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@260a6975 Bundle[{}]
,08-17 19:16:58.755  6298  6363 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-17 19:16:58.755  6298  6363 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-17 19:16:58.765  6298  6363 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-17 19:16:58.765  6298  6363 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-17 19:16:58.765  6298  6363 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-17 19:16:58.765  6298  6363 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-17 19:16:58.765  6298  6363 I System.out: Running OutgoingSocketThread
,08-17 19:16:58.775  6298  7071 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1173)
,08-17 19:16:58.775  6298  7071 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 54804
,08-17 19:16:58.775  6298  7071 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-17 19:16:59.275  7063  7063 I wpa_supplicant: nl80211: Received scan results (19 BSSes),
08-17 19:16:59.275  7063  7063 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-17 19:16:59.275  7063  7063 I wpa_supplicant: Trying to associate with SSID '4E47373030'
,08-17 19:16:59.275  7063  7063 I wpa_supplicant: Trying to associate with  'G700'
08-17 19:16:59.275  7063  7063 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-17 19:16:59.275  7063  7063 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,08-17 19:16:59.275  1012  7069 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-17 19:16:59.285  1012  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 19:16:59.285  1012  1126 D SecContentProvider2: mCursor = null
,08-17 19:16:59.405  7063  7063 E wpa_supplicant: Cmd 35605 not handled
,08-17 19:16:59.405  7063  7063 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-17 19:16:59.405  7063  7063 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,08-17 19:16:59.405  7063  7063 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-17 19:16:59.405  7063  7063 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-17 19:16:59.405  7063  7063 I wpa_supplicant: Associated with F4.99.3E
08-17 19:16:59.405  7063  7063 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-17 19:16:59.405  7063  7063 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-17 19:16:59.405  7063  7063 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-17 19:16:59.405  1012  1039 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 19:16:59.405  1012  1039 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:16:59.405  1012  1039 D Tethering: interfaceStatusChanged wlan0, false
,08-17 19:16:59.415  1012  1039 D Tethering: interfaceLinkStateChanged wlan0, false,
,08-17 19:16:59.415  1012  1039 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:16:59.415  1012  1039 D Tethering: interfaceStatusChanged wlan0, false
08-17 19:16:59.415  1012  1039 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 19:16:59.415  1012  1039 D Tethering: interfaceLinkStateChanged wlan0, false
,08-17 19:16:59.415  1012  1039 D Tethering: interfaceStatusChanged wlan0, false
08-17 19:16:59.415  1012  1039 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-17 19:16:59.415  1012  1039 D Tethering: interfaceLinkStateChanged wlan0, true
08-17 19:16:59.415  1012  1039 D Tethering: interfaceStatusChanged wlan0, true
,08-17 19:16:59.415  7063  7063 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-17 19:16:59.415  7063  7063 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-17 19:16:59.425  7063  7063 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE,
08-17 19:16:59.425  7063  7063 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,08-17 19:16:59.425  7063  7063 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-17 19:16:59.425  7063  7063 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,08-17 19:16:59.425  7063  7063 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-17 19:16:59.425  1012  1129 E Tethering: No numeric data
08-17 19:16:59.425  7063  7063 I wpa_supplicant: Blacklist: Clear (temp) 
08-17 19:16:59.425  1012  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-17 19:16:59.425  7063  7063 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-17 19:16:59.425  1012  1129 D Tethering: clearTetheredNotification()
08-17 19:16:59.425  1012  1039 D Tethering: interfaceLinkStateChanged wlan0, true
08-17 19:16:59.425  1012  1039 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-17 19:16:59.425  1012  1039 D Tethering: interfaceStatusChanged wlan0, true
,08-17 19:16:59.425  1012  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 19:16:59.425  1012  1126 D SecContentProvider2: mCursor = null
,08-17 19:16:59.425  1012  1123 V NetworkStats: performPollLocked(flags=0x1)
,08-17 19:16:59.425  1012  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:59.425  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-17 19:16:59.425  1173  1173 D HotspotTile: updateTetherState():false, false
,08-17 19:16:59.425  1012  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-17 19:16:59.435  1012  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 19:16:59.435  1012  1126 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-17 19:16:59.435  1012  1126 E WifiConfigStore: setLastSelectedConfiguration -1
,08-17 19:16:59.435  1012  1123 V NetworkStats: performPollLocked() took 8ms
08-17 19:16:59.435  1012  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:59.435  1012  1126 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-17 19:16:59.435  1012  1128 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-17 19:16:59.435  1012  1128 E ConnectivityService: updateNetworkInfo()
,08-17 19:16:59.435  1012  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-17 19:16:59.445  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 19:16:59.445  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-17 19:16:59.445  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:59.445  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:59.445  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:59.445  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:59.455  1012  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-17 19:16:59.455  1012  1025 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 19:16:59.455  1012  1025 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 19:16:59.455  1012  1025 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:16:59.455  1012  1025 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 19:16:59.455  1012  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 19:16:59.455  1012  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:16:59.455  1012  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:16:59.455  3642  3642 I Hs20UtilService: Starting #21
,08-17 19:16:59.455  3642  3679 I Hs20UtilService: Message received 5007
,08-17 19:16:59.455  1312  1312 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-17 19:16:59.455  1312  1312 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-17 19:16:59.465  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-17 19:16:59.465  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-17 19:16:59.465  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 19:16:59.465  1312  1312 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-17 19:16:59.465  1312  3094 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 19:16:59.465  1012  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 19:16:59.475   277   962 D CommandListener: Setting iface cfg
,08-17 19:16:59.475  1012  1126 E WifiStateMachine: Start Dhcp Watchdog 3
,08-17 19:16:59.475  1012  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-17 19:16:59.475  1012  1126 D SecContentProvider2: mCursor = null
,08-17 19:16:59.485  1012  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-17 19:16:59.485  1012  1126 D SecContentProvider2: mCursor = null
,08-17 19:16:59.495  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 19:16:59.495  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-17 19:16:59.495  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:59.495  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:16:59.495  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:59.495  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:16:59.495  1012  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-17 19:16:59.495  1012  1126 D SecContentProvider2: mCursor = null
,08-17 19:16:59.505  1012  1126 E WifiNative-wlan0: do suspend false
,08-17 19:16:59.505  1012  1125 D WifiP2pService: InactiveState{ what=143375 }
,08-17 19:16:59.505  1012  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-17 19:16:59.525   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-17 19:16:59.715  7074  7074 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-17 19:16:59.725  7074  7074 I dhcpcd  : version 5.5.6 starting,
,08-17 19:16:59.725  7074  7074 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-17 19:16:59.775  6298  6363 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1174),
08-17 19:16:59.775  6298  6363 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1174)
,08-17 19:16:59.775  6298  6363 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1179),
08-17 19:16:59.775  6298  6363 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-17 19:16:59.775  6298  6363 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1180),
,08-17 19:16:59.775  6298  6363 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
08-17 19:16:59.775  6298  6363 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31d2fda6 added. We now have 2 listener(s)
08-17 19:16:59.785  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB",
08-17 19:16:59.785  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:16:59.785  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 19:16:59.785  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:16:59.785  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1482c3e7 added. We now have 9 listener(s)
08-17 19:16:59.785  6298  6363 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:16:59.785  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 19:16:59.785  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-17 19:16:59.795  6298  6363 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:16:59.795  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:59.795  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:59.795  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:59.795  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:59.795  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:59.795  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:59.795  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:16:59.795  7074  7074 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-17 19:16:59.795  6298  6363 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 19:16:59.795  7074  7074 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-17 19:16:59.795  7074  7074 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-17 19:16:59.795  6298  6363 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 19:16:59.795  6298  6363 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 19:16:59.795  6298  6363 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d85663d added. We now have 3 listener(s)
,08-17 19:16:59.795  7074  7074 I dhcpcd  : bssid match
,08-17 19:16:59.795  7074  7074 I dhcpcd  : wlan0: rebinding lease of 192.168.1.111
08-17 19:16:59.795  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:16:59.795  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:59.805  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-17 19:16:59.805  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 19:16:59.805  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 19:16:59.805  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:16:59.805  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17214e32 added. We now have 10 listener(s)
08-17 19:16:59.805  6298  6363 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-17 19:16:59.805  6298  6363 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:59.805  6298  6363 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:59.805  6298  6363 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 19:16:59.805  6298  6363 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:59.805  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:59.805  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-17 19:16:59.805  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 19:16:59.805  6298  6363 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31d2fda6 removed from the list
08-17 19:16:59.805  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:59.805  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1482c3e7 removed from the list
08-17 19:16:59.805  6298  6363 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:59.805  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:59.805  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:59.805  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:59.805  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:59.805  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:59.805  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:59.805  6298  6363 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1482c3e7 not in the list
08-17 19:16:59.805  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:59.805  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-17 19:16:59.805  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:59.805  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:59.805  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:59.805  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17214e32 removed from the list
08-17 19:16:59.805  6298  6363 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:59.805  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:59.805  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:59.805  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 19:16:59.805  6298  6363 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d85663d removed from the list
08-17 19:16:59.805  6298  6363 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 19:16:59.805  6298  6363 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2badb783 added. We now have 2 listener(s)
,08-17 19:16:59.815  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-17 19:16:59.815  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:16:59.815  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 19:16:59.815  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:16:59.815  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39333d00 added. We now have 9 listener(s)
,08-17 19:16:59.815  6298  6363 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 19:16:59.815  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 19:16:59.815  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:16:59.825  6298  6363 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:16:59.825  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:16:59.825  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:16:59.825  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:16:59.825  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:16:59.825  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:16:59.825  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:16:59.825  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:16:59.825  6298  6363 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:16:59.825  6298  6363 D io.jxcore.node.ConnectivityMonitor: start: OK,
08-17 19:16:59.825  6298  6363 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 19:16:59.825  6298  6363 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36921b7e added. We now have 3 listener(s)
08-17 19:16:59.825  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:16:59.825  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:16:59.825  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-17 19:16:59.825  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:16:59.825  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 19:16:59.825  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:16:59.825  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20a48df added. We now have 10 listener(s)
08-17 19:16:59.825  6298  6363 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 19:16:59.825  6298  6363 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 19:16:59.825  6298  6363 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 19:16:59.825  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 19:16:59.825  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:16:59.825  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 19:16:59.835  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 19:16:59.835  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 19:16:59.835  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 19:16:59.845  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-17 19:16:59.845  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 19:16:59.845  6298  6363 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-17 19:16:59.845  6969  6999 D BtGatt.GattService: registerClient() - UUID=c1aef036-e9a4-4473-b1dc-bbc8967d03a5
,08-17 19:16:59.865  7074  7074 I dhcpcd  : wlan0: acknowledged 192.168.1.111 from 192.168.1.1
,08-17 19:16:59.885  6969  6996 D BtGatt.GattService: onClientRegistered() - UUID=c1aef036-e9a4-4473-b1dc-bbc8967d03a5, clientIf=6
,08-17 19:16:59.885  6298  6308 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-17 19:16:59.885  6969  6977 D BtGatt.GattService: start scan with filters
,08-17 19:16:59.895  6969  7003 D BtGatt.ScanManager: handling starting scan
,08-17 19:16:59.895  6969  7003 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1aa1d78b
,08-17 19:16:59.895  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-17 19:16:59.895  6969  6996 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-17 19:16:59.895  6969  6996 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:59.895  6969  7003 D BtGatt.ScanManager: allow scan with filters
,08-17 19:16:59.895  6969  7003 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-17 19:16:59.905  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 19:16:59.905  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 19:16:59.905  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 19:16:59.905  6969  7003 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-17 19:16:59.905  6969  6996 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-17 19:16:59.905  6969  6996 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:59.905  6969  7003 D BtGatt.ScanManager: Starting BLE batch scan
,08-17 19:16:59.905  6969  7003 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-17 19:16:59.905  6969  6996 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-17 19:16:59.915  6969  6996 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:16:59.915  6298  6363 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 19:16:59.915  6298  6363 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 19:16:59.915  7074  7074 I dhcpcd  : wlan0: leased 192.168.1.111 for 172800 seconds
08-17 19:16:59.915  6298  6298 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 19:16:59.915  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 19:16:59.925  6969  6996 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-17 19:16:59.925  6969  6996 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:59.935  6298  6363 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation,
,08-17 19:16:59.935  6298  6363 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:59.935  6298  6363 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-17 19:16:59.935  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:59.935  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 19:16:59.935  6298  6363 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 19:16:59.935  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-17 19:16:59.935  6298  6363 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 19:16:59.935  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 19:16:59.935  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 19:16:59.935  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-17 19:16:59.935  6969  6999 D BtGatt.GattService: stopScan() - queue size =1
,08-17 19:16:59.935  6969  6977 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-17 19:16:59.935  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 19:16:59.935  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 19:16:59.945  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 19:16:59.945  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 19:16:59.945  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 19:16:59.945  6298  6363 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 19:16:59.955  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 19:16:59.955  6298  6363 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 19:16:59.955  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 19:16:59.955  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 19:16:59.965  6298  6298 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:16:59.965  6298  6298 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
08-17 19:16:59.965  6298  6298 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 19:16:59.965  6969  7003 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 60
,08-17 19:16:59.965  6298  6363 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:16:59.965  6298  6363 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:16:59.965  6298  6363 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:16:59.965  6298  6363 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:59.965  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:16:59.965  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:16:59.965  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 19:16:59.965  6298  6363 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2badb783 removed from the list
08-17 19:16:59.965  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:59.965  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39333d00 removed from the list
08-17 19:16:59.965  6298  6363 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:16:59.965  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:59.965  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:59.965  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:59.965  6969  7003 D BtGatt.ScanManager: filter size is 1
08-17 19:16:59.965  6969  7003 D BtGatt.ScanManager: delete FilterIndex - 3
,08-17 19:16:59.965  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-17 19:16:59.965  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:59.965  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:59.965  6969  6996 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-17 19:16:59.965  6969  6996 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:16:59.965  6298  6363 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39333d00 not in the list
,08-17 19:16:59.965  6969  7003 D BtGatt.ScanManager: stopping BLe Batch
08-17 19:16:59.965  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:59.965  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:16:59.975  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:16:59.975  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:16:59.975  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:16:59.975  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20a48df removed from the list
08-17 19:16:59.975  6298  6363 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:16:59.975  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:16:59.975  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:16:59.975  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 19:16:59.975  6298  6363 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36921b7e removed from the list
,08-17 19:16:59.975  6298  6363 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 19:16:59.975  6298  6363 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a7493fb added. We now have 2 listener(s)
,08-17 19:16:59.975  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-17 19:16:59.975  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:16:59.975  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 19:16:59.975  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:16:59.975  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37dbac18 added. We now have 9 listener(s)
08-17 19:16:59.975  6298  6363 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:16:59.975  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 19:16:59.975  6969  6996 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-17 19:16:59.975  6969  6996 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:16:59.975  6969  7003 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-17 19:16:59.975  6969  6996 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
08-17 19:16:59.975  6969  6996 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:16:59.995  1012  1092 V AlarmManager: waitForAlarm result :8,
,08-17 19:16:59.995  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:17:00.005  6298  6363 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:17:00.005  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:17:00.005  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:17:00.005  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:17:00.005  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:17:00.005  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:17:00.005  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:17:00.005  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:17:00.005  6298  6363 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
08-17 19:17:00.005  6298  6363 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 19:17:00.005  6298  6363 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 19:17:00.005  6298  6363 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39ac1c56 added. We now have 3 listener(s)
,08-17 19:17:00.005  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:17:00.015  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:17:00.015  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-17 19:17:00.015  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:17:00.015  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 19:17:00.015  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:17:00.015  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f6e74d7 added. We now have 10 listener(s)
,08-17 19:17:00.015  6298  6363 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:17:00.015  6298  6363 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 19:17:00.015  6298  6363 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 19:17:00.015  6298  6363 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 19:17:00.015  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 19:17:00.015  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:17:00.015  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 19:17:00.025  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 19:17:00.035  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 19:17:00.035  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 19:17:00.045  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-17 19:17:00.045  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 19:17:00.045  6298  6363 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-17 19:17:00.045  6969  7044 D BtGatt.GattService: registerClient() - UUID=d4406a62-0470-46ff-9a57-36057c71e423
,08-17 19:17:00.095  6969  6996 D BtGatt.GattService: onClientRegistered() - UUID=d4406a62-0470-46ff-9a57-36057c71e423, clientIf=6,
08-17 19:17:00.095  6298  6312 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-17 19:17:00.095  6969  6977 D BtGatt.GattService: start scan with filters
08-17 19:17:00.095  6969  7003 D BtGatt.ScanManager: handling starting scan
,08-17 19:17:00.095  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-17 19:17:00.095  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 19:17:00.095  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 19:17:00.095  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-17 19:17:00.095  6969  6996 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
08-17 19:17:00.095  6969  6996 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:17:00.095  6969  7003 D BtGatt.ScanManager: allow scan with filters
08-17 19:17:00.095  6969  7003 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-17 19:17:00.095  6969  7003 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
08-17 19:17:00.095  6969  6996 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-17 19:17:00.095  6969  6996 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:17:00.095  6969  7003 D BtGatt.ScanManager: Starting BLE batch scan,
08-17 19:17:00.095  6969  7003 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-17 19:17:00.095  6969  6996 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-17 19:17:00.095  6969  6996 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:17:00.105  6298  6363 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 19:17:00.105  6298  6298 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 19:17:00.105  6298  6363 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 19:17:00.105  6969  6996 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-17 19:17:00.105  6969  6996 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:17:00.105  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 19:17:00.115  6298  6363 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 19:17:00.115  6298  6363 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-17 19:17:00.115  6298  6363 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:17:00.115  6298  6363 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-17 19:17:00.115  6298  6363 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:17:00.115  6298  6363 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:17:00.115  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:17:00.115  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 19:17:00.115  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 19:17:00.115  6298  6363 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a7493fb removed from the list
,08-17 19:17:00.115  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:17:00.115  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37dbac18 removed from the list
08-17 19:17:00.115  6298  6363 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:17:00.115  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 19:17:00.115  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-17 19:17:00.115  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-17 19:17:00.115  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:17:00.115  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 19:17:00.115  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:17:00.115  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-17 19:17:00.115  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:17:00.115  6298  6363 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37dbac18 not in the list
08-17 19:17:00.115  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 19:17:00.115  6298  6363 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 19:17:00.115  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 19:17:00.115  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-17 19:17:00.115  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 19:17:00.115  6969  6999 D BtGatt.GattService: stopScan() - queue size =1
,08-17 19:17:00.115  6969  6999 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-17 19:17:00.125  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 19:17:00.125  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 19:17:00.125  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 19:17:00.125  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-17 19:17:00.125  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-17 19:17:00.125  6969  7003 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 61
08-17 19:17:00.125  6298  6363 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 19:17:00.125  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-17 19:17:00.125  6298  6363 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 19:17:00.125  6969  7003 D BtGatt.ScanManager: filter size is 1
08-17 19:17:00.125  6969  7003 D BtGatt.ScanManager: delete FilterIndex - 4
08-17 19:17:00.125  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 19:17:00.125  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:17:00.125  6969  6996 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-17 19:17:00.125  6969  6996 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:17:00.125  6969  7003 D BtGatt.ScanManager: stopping BLe Batch
,08-17 19:17:00.125  6298  6298 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:17:00.125  6298  6298 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:17:00.125  6298  6298 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 19:17:00.125  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-17 19:17:00.125  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:17:00.125  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:17:00.125  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f6e74d7 removed from the list
,08-17 19:17:00.125  6298  6363 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:17:00.135  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:17:00.135  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:17:00.135  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 19:17:00.135  6298  6363 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39ac1c56 removed from the list
08-17 19:17:00.135  6298  6363 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 19:17:00.135  6298  6363 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37bb8773 added. We now have 2 listener(s),
08-17 19:17:00.135  6969  6996 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-17 19:17:00.135  6969  6996 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:17:00.135  6969  7003 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-17 19:17:00.135  6969  6996 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-17 19:17:00.135  6969  6996 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,08-17 19:17:00.135  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB",
08-17 19:17:00.135  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:17:00.135  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 19:17:00.135  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:17:00.135  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@140fe630 added. We now have 9 listener(s),
08-17 19:17:00.135  6298  6363 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 19:17:00.135  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 19:17:00.135  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:17:00.145  6298  6363 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:17:00.145  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:17:00.145  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:17:00.145  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:17:00.145  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:17:00.145  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:17:00.145  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:17:00.145  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:17:00.145  6298  6363 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:17:00.145  6298  6363 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 19:17:00.145  6298  6363 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 19:17:00.145  6298  6363 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@293a602e added. We now have 3 listener(s)
,08-17 19:17:00.145  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:17:00.145  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-17 19:17:00.145  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:17:00.145  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 19:17:00.145  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:17:00.145  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28bd27cf added. We now have 10 listener(s)
08-17 19:17:00.145  6298  6363 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:17:00.145  6298  6363 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 19:17:00.145  6298  6363 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 19:17:00.145  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 19:17:00.145  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:17:00.145  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 19:17:00.145  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:17:00.145  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 19:17:00.155  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 19:17:00.155  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 19:17:00.155  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-17 19:17:00.155  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 19:17:00.155  6298  6363 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-17 19:17:00.155  6969  6999 D BtGatt.GattService: registerClient() - UUID=ea7c53a4-8b76-4f2b-a27d-c87225e38fee
,08-17 19:17:00.205  6969  6996 D BtGatt.GattService: onClientRegistered() - UUID=ea7c53a4-8b76-4f2b-a27d-c87225e38fee, clientIf=6
,08-17 19:17:00.205  6298  6312 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-17 19:17:00.205  6969  7044 D BtGatt.GattService: start scan with filters
,08-17 19:17:00.205  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-17 19:17:00.205  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 19:17:00.205  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 19:17:00.205  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 19:17:00.205  6969  7003 D BtGatt.ScanManager: handling starting scan
,08-17 19:17:00.205  6969  6996 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-17 19:17:00.205  6969  6996 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:17:00.205  6969  7003 D BtGatt.ScanManager: allow scan with filters
,08-17 19:17:00.205  6969  7003 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-17 19:17:00.205  6969  7003 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-17 19:17:00.205  6298  6363 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 19:17:00.205  6298  6363 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 19:17:00.205  6298  6298 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 19:17:00.205  6969  6996 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-17 19:17:00.205  6969  6996 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:17:00.205  6969  7003 D BtGatt.ScanManager: Starting BLE batch scan
08-17 19:17:00.215  6969  7003 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-17 19:17:00.215  6969  6996 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-17 19:17:00.215  6969  6996 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:17:00.215  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 19:17:00.215  6969  6996 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-17 19:17:00.215  6969  6996 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 19:17:00.235  6298  6363 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-17 19:17:00.235  6298  6363 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 19:17:00.235  6298  6363 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-17 19:17:00.235  6298  6363 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:17:00.235  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:17:00.235  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 19:17:00.235  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 19:17:00.235  6298  6363 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37bb8773 removed from the list
,08-17 19:17:00.235  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:17:00.235  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@140fe630 removed from the list
08-17 19:17:00.235  6298  6363 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 19:17:00.235  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:17:00.235  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-17 19:17:00.235  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-17 19:17:00.235  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:17:00.235  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:17:00.235  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:17:00.235  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:17:00.235  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-17 19:17:00.235  6298  6363 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@140fe630 not in the list
08-17 19:17:00.235  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 19:17:00.235  6298  6363 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 19:17:00.235  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 19:17:00.235  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 19:17:00.235  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-17 19:17:00.235  6969  6999 D BtGatt.GattService: stopScan() - queue size =1
08-17 19:17:00.235  6969  7044 D BtGatt.GattService: unregisterClient() - clientIf=6
08-17 19:17:00.235  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 19:17:00.235  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 19:17:00.235  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 19:17:00.235  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 19:17:00.235  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-17 19:17:00.235  6298  6363 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 19:17:00.245  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 19:17:00.245  6298  6363 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 19:17:00.245  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 19:17:00.245  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:17:00.245  6969  7003 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 62
08-17 19:17:00.245  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:17:00.245  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:17:00.245  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:17:00.245  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28bd27cf removed from the list
08-17 19:17:00.245  6298  6363 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:17:00.245  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:17:00.245  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:17:00.245  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 19:17:00.245  6298  6363 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@293a602e removed from the list
08-17 19:17:00.245  6298  6363 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 19:17:00.245  6298  6363 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28e71eb added. We now have 2 listener(s)
08-17 19:17:00.245  6969  7003 D BtGatt.ScanManager: filter size is 1
08-17 19:17:00.245  6969  7003 D BtGatt.ScanManager: delete FilterIndex - 5
08-17 19:17:00.245  6298  6298 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:17:00.245  6298  6298 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:17:00.245  6298  6298 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 19:17:00.245  6969  6996 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-17 19:17:00.245  6969  6996 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:17:00.245  6969  7003 D BtGatt.ScanManager: stopping BLe Batch
08-17 19:17:00.245  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-17 19:17:00.245  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:17:00.245  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 19:17:00.245  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:17:00.245  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@41e4b48 added. We now have 9 listener(s)
08-17 19:17:00.245  6298  6363 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:17:00.245  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 19:17:00.255  6969  6996 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-17 19:17:00.255  6969  6996 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:17:00.255  6969  7003 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-17 19:17:00.255  6969  6996 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-17 19:17:00.255  6969  6996 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 19:17:00.255  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:17:00.255  6298  6363 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:17:00.255  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:17:00.255  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:17:00.255  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:17:00.255  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:17:00.255  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:17:00.255  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:17:00.255  6298  6363 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 19:17:00.265  6298  6363 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 19:17:00.265  6298  6363 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 19:17:00.265  6298  6363 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 19:17:00.265  6298  6363 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31224706 added. We now have 3 listener(s)
08-17 19:17:00.265  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:17:00.265  6298  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:17:00.265  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-17 19:17:00.265  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:17:00.265  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 19:17:00.265  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:17:00.265  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11e041c7 added. We now have 10 listener(s)
08-17 19:17:00.265  6298  6363 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:17:00.265  6298  6363 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:17:00.275  6298  6363 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:17:00.275  6298  6363 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:17:00.275  6298  6363 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:17:00.275  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:17:00.275  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:17:00.275  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 19:17:00.275  6298  6363 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28e71eb removed from the list
08-17 19:17:00.275  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:17:00.275  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@41e4b48 removed from the list
08-17 19:17:00.275  6298  6363 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:17:00.275  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:17:00.275  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:17:00.275  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:17:00.275  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:17:00.275  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:17:00.275  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:17:00.275  6298  6363 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@41e4b48 not in the list
08-17 19:17:00.275  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:17:00.275  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:17:00.275  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:17:00.275  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:17:00.275  6298  6363 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:17:00.275  6298  6363 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11e041c7 removed from the list
08-17 19:17:00.275  6298  6363 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:17:00.275  6298  6363 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:17:00.275  6298  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:17:00.275  6298  6363 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 19:17:00.275  6298  6363 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31224706 removed from the list
08-17 19:17:00.275  6298  6363 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-17 19:17:00.275  6298  6363 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-17 19:17:00.275  6298  6363 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-17 19:17:00.275  6298  6363 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 19:17:00.275  6298  6363 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-17 19:17:00.275  6298  6363 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-17 19:17:00.285  6298  7107 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1187, name: My test thread name)
08-17 19:17:00.285  6298  7107 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1187, thread name: My test thread name)
08-17 19:17:00.285  6298  7107 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1187, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-17 19:17:00.295  6298  7108 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1189, name: My test thread name)
08-17 19:17:00.295  6298  7108 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1189, thread name: My test thread name)
08-17 19:17:00.295  6298  7108 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1189, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-17 19:17:00.295  6298  6363 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-17 19:17:00.295  6298  6363 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-17 19:17:00.295  6298  6363 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-17 19:17:00.295  6298  6363 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-17 19:17:00.295  6298  6363 D com.test.thalitest.ThaliTestRunner: Total duration: 23314 ms
08-17 19:17:00.295  6298  6363 I jxcore-log: Total number of executed tests:  80
08-17 19:17:00.295  6298  6363 I jxcore-log: 
08-17 19:17:00.295  6298  6363 I jxcore-log: Number of passed tests:  80
08-17 19:17:00.295  6298  6363 I jxcore-log: 
08-17 19:17:00.295  6298  6363 I jxcore-log: Number of failed tests:  0
08-17 19:17:00.295  6298  6363 I jxcore-log: 
08-17 19:17:00.295  6298  6363 I jxcore-log: Number of ignored tests:  0
08-17 19:17:00.295  6298  6363 I jxcore-log: 
08-17 19:17:00.295  6298  6363 I jxcore-log: Total duration:  23314
08-17 19:17:00.295  6298  6363 I jxcore-log: 
08-17 19:17:00.295  6298  6363 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-17 19:17:00.295  6298  6363 I jxcore-log: 
08-17 19:17:00.295  6298  6363 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:17:00.295  6298  6363 I jxcore-log: 
08-17 19:17:00.305  6298  6363 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:17:00.305  6298  6363 I jxcore-log: 
08-17 19:17:00.305  6298  6363 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:17:00.305  6298  6363 I jxcore-log: 
08-17 19:17:00.315  6298  6363 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:17:00.315  6298  6363 I jxcore-log: 
08-17 19:17:00.315  6298  6363 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:17:00.315  6298  6363 I jxcore-log: 
08-17 19:17:00.315  6298  6363 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:17:00.315  6298  6363 I jxcore-log: 
08-17 19:17:00.315  1012  1126 E WifiNative-wlan0: do suspend true
,08-17 19:17:00.315  6298  6298 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-17 19:17:00.315  6298  6363 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:17:00.315  6298  6363 I jxcore-log: 
08-17 19:17:00.325  6298  6363 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 19:17:00.325  6298  6363 I jxcore-log: 
08-17 19:17:00.325  6298  6363 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 19:17:00.325  6298  6363 I jxcore-log: 
08-17 19:17:00.325  6298  6363 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 19:17:00.325  6298  6363 I jxcore-log: 
08-17 19:17:00.325  6298  6363 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 19:17:00.325  6298  6363 I jxcore-log: 
08-17 19:17:00.325  6298  6363 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 19:17:00.325  6298  6363 I jxcore-log: 
08-17 19:17:00.325  6298  6363 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 19:17:00.325  6298  6363 I jxcore-log: 
08-17 19:17:00.325  6298  6363 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 19:17:00.325  6298  6363 I jxcore-log: 
08-17 19:17:00.335  6298  6363 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 19:17:00.335  6298  6363 I jxcore-log: 
08-17 19:17:00.335  6298  6363 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 19:17:00.335  6298  6363 I jxcore-log: 
08-17 19:17:00.335  6298  6363 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 19:17:00.335  6298  6363 I jxcore-log: 
08-17 19:17:00.335  6298  6363 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 19:17:00.335  6298  6363 I jxcore-log: 
08-17 19:17:00.335  6298  6363 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 19:17:00.335  6298  6363 I jxcore-log: 
08-17 19:17:00.335  6298  6363 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 19:17:00.335  6298  6363 I jxcore-log: 
,08-17 19:17:00.335  6298  6363 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 19:17:00.335  6298  6363 I jxcore-log: 
,08-17 19:17:00.335  6298  6363 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 19:17:00.335  6298  6363 I jxcore-log: 
08-17 19:17:00.335  6298  6363 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 19:17:00.335  6298  6363 I jxcore-log: 
08-17 19:17:00.335  6298  6363 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 19:17:00.335  6298  6363 I jxcore-log: 
08-17 19:17:00.335  6298  6363 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 19:17:00.335  6298  6363 I jxcore-log: 
08-17 19:17:00.345  1012  1125 D WifiP2pService: InactiveState{ what=143375 }
08-17 19:17:00.345  6298  6363 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 19:17:00.345  6298  6363 I jxcore-log: 
08-17 19:17:00.345  1012  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
08-17 19:17:00.345  6298  6363 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 19:17:00.345  6298  6363 I jxcore-log: 
08-17 19:17:00.345  1012  1126 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-17 19:17:00.345  1012  1126 E WifiStateMachine: VerifyingLinkState enter
,08-17 19:17:00.345  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 19:17:00.345  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 19:17:00.345  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:17:00.345  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:17:00.345  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:17:00.345  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:17:00.345  1012  1126 D WifiNative-wlan0: callSECApiInt - ID [210]
08-17 19:17:00.345  1012  1128 E ConnectivityService: updateNetworkInfo()
,08-17 19:17:00.345  1012  1128 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,08-17 19:17:00.345  1012  1128 D ConnectivityService: Adding iface wlan0 to network 504
,08-17 19:17:00.365  1012  1142 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
08-17 19:17:00.365  1012  1142 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-17 19:17:00.365  1012  1142 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-17 19:17:00.365  1012  1142 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-17 19:17:00.365  1012  1142 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-17 19:17:00.365  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:17:00.365  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 19:17:00.365  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:17:00.365  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:17:00.365  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:17:00.365  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:17:00.365  1012  1128 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
08-17 19:17:00.365  1012  1128 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,08-17 19:17:00.375  1012  1128 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
08-17 19:17:00.375  1012  1478 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 19:17:00.375  1012  1128 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-17 19:17:00.375  1012  1128 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
08-17 19:17:00.375  1012  1128 D ConnectivityService: LTETest block dns file not exists
08-17 19:17:00.375  1012  1478 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 19:17:00.375  1012  1126 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
08-17 19:17:00.375  1012  1478 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:17:00.375  1012  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:17:00.375  1012  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings,
,08-17 19:17:00.375  3642  3642 I Hs20UtilService: Starting #22
,08-17 19:17:00.375  1012  1128 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,08-17 19:17:00.385  1012  1128 E ConnectivityService: updateNetworkInfo()
,08-17 19:17:00.385  1312  1312 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-17 19:17:00.385  1312  1312 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-17 19:17:00.385  1012  1126 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp,
08-17 19:17:00.385  1012  1126 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-17 19:17:00.385  1012  1128 E ConnectivityService: updateNetworkInfo()
08-17 19:17:00.385  1012  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 19:17:00.385  1012  1128 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
,08-17 19:17:00.385  1012  1128 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
,08-17 19:17:00.395  1012  7072 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-17 19:17:00.395  1012  7072 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-17 19:17:00.395  1012  7072 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-17 19:17:00.395  1012  7072 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
08-17 19:17:00.395  1012  7072 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 19:17:00.395  3642  3679 I Hs20UtilService: Message received 5007
08-17 19:17:00.395   277   958 D EnterpriseController: uids 1000
08-17 19:17:00.395   277   958 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-17 19:17:00.395   277   958 D Netd    : getNetworkForDns: using netid 504 for uid 1000
08-17 19:17:00.395  1012  1012 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-17 19:17:00.395  1012  1125 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false,
08-17 19:17:00.395  1012  1128 D ConnectivityService:    accepting network in place of null
08-17 19:17:00.395  1012  1126 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-17 19:17:00.395  1012  1128 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
08-17 19:17:00.395  1453  1453 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-17 19:17:00.395  1012  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-17 19:17:00.395  1453  1453 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 19:17:00.395  1012  1128 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,08-17 19:17:00.405  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 19:17:00.405  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 19:17:00.405  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:17:00.405  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:17:00.405  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:17:00.405  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:17:00.405  1012  1012 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-17 19:17:00.405  1012  1012 I WifiTrafficPoller: mBoosterFLAG : 0
08-17 19:17:00.405  1012  1012 I WifiTrafficPoller: current booster mode : FullMode
08-17 19:17:00.405  1012  1012 D WifiNative-wlan0: callSECApiVoid - ID [212]
,08-17 19:17:00.415  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:17:00.415  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-17 19:17:00.415  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:17:00.415  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:17:00.415  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:17:00.415  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:17:00.415  1012  1128 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
08-17 19:17:00.415  1012  1012 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-17 19:17:00.415  1012  1129 D Tethering: MasterInitialState.processMessage what=3
,08-17 19:17:00.415  1012  1128 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,08-17 19:17:00.415  1012  1041 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-17 19:17:00.425  1012  1123 V NetworkStats: updateIfacesLocked()
08-17 19:17:00.425  1012  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:17:00.425  1012  1123 V NetworkStats: performPollLocked(flags=0x1)
08-17 19:17:00.425  1173  1681 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-17 19:17:00.425  3821  6245 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-17 19:17:00.425  1012  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 19:17:00.425  1012  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-17 19:17:00.425  1012  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:17:00.425  1012  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:17:00.425  1012  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:17:00.425  1012  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:17:00.425  1012  1124 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,08-17 19:17:00.425  1012  1123 V NetworkStats: performPollLocked() took 5ms
,08-17 19:17:00.425  1012  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:17:00.425  1012  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:17:00.425  1012  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:17:00.435  1173  1173 D StatusBar.NetworkController: EthernetConnected: false
08-17 19:17:00.435  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-17 19:17:00.435  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-17 19:17:00.435  1173  1173 D StatusBar.NetworkController: updateDataNetType()
08-17 19:17:00.435  1173  1173 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-17 19:17:00.435  1173  1173 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-17 19:17:00.435  1012  1074 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 19:17:00.435  1012  1074 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 19:17:00.445  1012  1074 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:17:00.445  1012  1074 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:17:00.445  1012  1074 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 19:17:00.445  1173  1173 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-17 19:17:00.445  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-17 19:17:00.445  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-17 19:17:00.445  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 19:17:00.445  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-17 19:17:00.445  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:17:00.445  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:17:00.445  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:17:00.445  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:17:00.445  3642  3642 I Hs20UtilService: Starting #23
08-17 19:17:00.445  3642  3679 I Hs20UtilService: Message received 5007
08-17 19:17:00.445  1312  1312 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-17 19:17:00.445  1312  1312 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-17 19:17:00.445  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,08-17 19:17:00.455  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-17 19:17:00.455  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,08-17 19:17:00.455  1312  1312 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-17 19:17:00.465  6298  6298 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-17 19:17:00.465  1012  1221 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 19:17:00.465  1012  1221 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 19:17:00.465  1012  1221 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:17:00.465  1012  1221 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:17:00.465  1012  1221 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-17 19:17:00.465  6298  6363 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 19:17:00.465  6298  6363 I jxcore-log: 
,08-17 19:17:00.465  3642  3642 I Hs20UtilService: Starting #24
,08-17 19:17:00.465  3642  3679 I Hs20UtilService: Message received 5007
,08-17 19:17:00.465  1312  1312 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-17 19:17:00.465  1312  1312 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-17 19:17:00.475  1012  2930 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-17 19:17:00.475  1012  1360 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState,
,08-17 19:17:00.475  1012  1360 D SecContentProvider2: mCursor = null
,08-17 19:17:00.485  1012  2929 D SecContentProvider2: uri = 15 selection = getToastGravity,
08-17 19:17:00.485  1012  2929 D SecContentProvider2: mCursor = null
08-17 19:17:00.485  1012  1221 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
08-17 19:17:00.485  1012  1221 D SecContentProvider2: mCursor = null
,08-17 19:17:00.485  1012  1025 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
08-17 19:17:00.485  1012  1025 D SecContentProvider2: mCursor = null
08-17 19:17:00.485  1012  7072 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-17 19:17:00.485  1012  1497 D SecContentProvider2: uri = 15 selection = getToastEnabledState
,08-17 19:17:00.485  1012  1497 D SecContentProvider2: mCursor = null
08-17 19:17:00.485  1012  1474 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
08-17 19:17:00.485  1012  1474 D SecContentProvider2: mCursor = null
,08-17 19:17:00.495   287   287 E SMD     : DCD OFF
,08-17 19:17:00.515   257   257 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=4, Uoast,
,08-17 19:17:00.525  1012  2929 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1012
,08-17 19:17:00.525   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-17 19:17:00.535  1173  1173 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-17 19:17:00.535  1012  7072 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 17 Aug 2016 17:17:00 GMT], X-Android-Received-Millis=[1471454220546], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471454220519]}
,08-17 19:17:00.535  1012  7072 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-17 19:17:00.535  1012  7072 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-17 19:17:00.545  1012  1128 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
08-17 19:17:00.545  1012  1128 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-17 19:17:00.545  1012  1128 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
08-17 19:17:00.545  1012  1128 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,08-17 19:17:00.545  1012  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-17 19:17:00.545  3821  6245 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-17 19:17:00.545  1173  1681 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-17 19:17:00.565  1173  1173 D StatusBar.NetworkController: EthernetConnected: false
,08-17 19:17:00.565  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-17 19:17:00.565  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-17 19:17:00.565  1173  1173 D StatusBar.NetworkController: updateDataNetType()
08-17 19:17:00.565  1173  1173 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-17 19:17:00.565  1173  1173 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-17 19:17:00.565  1173  1173 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,08-17 19:17:00.565  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,08-17 19:17:00.575  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,08-17 19:17:00.575  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 19:17:00.575  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-17 19:17:00.575  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:17:00.575  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 19:17:00.575  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:17:00.575  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 19:17:00.585  7111  7111 D AndroidRuntime: 
08-17 19:17:00.585  7111  7111 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-17 19:17:00.595  7111  7111 D AndroidRuntime: CheckJNI is OFF
,08-17 19:17:00.595  7111  7111 D AndroidRuntime: readGMSProperty: start
,08-17 19:17:00.595  7111  7111 D AndroidRuntime: readGMSProperty: already setted!!
08-17 19:17:00.595  7111  7111 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-17 19:17:00.595  7111  7111 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
,08-17 19:17:00.595  7111  7111 D AndroidRuntime: readGMSProperty: end
08-17 19:17:00.595  7111  7111 D AndroidRuntime: addProductProperty: start
,08-17 19:17:00.625  6298  6298 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 19:17:00.635  6298  6363 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
08-17 19:17:00.635  6298  6363 I jxcore-log: 
,08-17 19:17:00.725  7111  7111 E AffinityControl: AffinityControl: registerfunction enter,
,08-17 19:17:00.745  6298  6298 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-17 19:17:00.745  6298  6363 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 19:17:00.745  6298  6363 I jxcore-log: 
,08-17 19:17:00.755  7111  7111 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm,
,08-17 19:17:00.765  1012  1221 D PackageManager: START PACKAGE DELETE: observer{137142109},
08-17 19:17:00.765  1012  1221 D PackageManager: pkg{<packageName>}
08-17 19:17:00.765  1012  1221 D PackageManager: user{0}
08-17 19:17:00.765  1012  1221 D PackageManager: caller{2000}
08-17 19:17:00.765  1012  1221 D PackageManager: flags{2}
,08-17 19:17:00.765  1012  1221 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
08-17 19:17:00.765  1012  1221 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-17 19:17:00.765  1012  1221 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true,
08-17 19:17:00.765  1012  1221 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-17 19:17:00.765  1012  1221 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-17 19:17:00.765  1012  1052 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER,
08-17 19:17:00.775  1012  1052 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-17 19:17:00.775  1012  1052 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-17 19:17:00.775  1012  1052 D ApplicationPolicy: getApplicationUninstallationEnabled
08-17 19:17:00.775  1012  1052 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-17 19:17:00.775  1012  1052 D PackageManager: !@killApplicatoin: 10155, uninstall pkg
,08-17 19:17:00.775  1012  1037 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
08-17 19:17:00.775  1012  1037 I ActivityManager: Killing 6298:com.test.thalitest/u0a155 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-17 19:17:00.775  1012  1037 I ActivityManager:   Force finishing activity ActivityRecord{39f08555 u0 com.test.thalitest/.MainActivity t129}
,08-17 19:17:00.785  1012  1037 W ActivityManager: mDVFSHelper.acquire()
,08-17 19:17:00.895  1012  1052 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=0: pkg removed
,08-17 19:17:00.895  1012  1052 I ActivityManager:   Force finishing activity ActivityRecord{39f08555 u0 com.test.thalitest/.MainActivity t129 f}
,08-17 19:17:00.895  1012  1052 W ActivityManager: Duplicate finish request for ActivityRecord{39f08555 u0 com.test.thalitest/.MainActivity t129 f}
,08-17 19:17:00.915  1012  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 19:17:00.925  1012  1540 I WindowState: WIN DEATH: Window{1354067a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-17 19:17:00.935  1012  1052 W ActivityManager: CustomStartingWindow se packge removed so remove capture also,
08-17 19:17:00.945   257  1094 I SurfaceFlinger: id=14 Removed NainActivit (6/9)
08-17 19:17:00.945   257  1095 I SurfaceFlinger: id=14 Removed NainActivit (-2/9),
,08-17 19:17:00.945  1012  1540 D InputDispatcher: Focus left window: 6298
,08-17 19:17:00.955  5714  5714 I art     : Explicit concurrent mark sweep GC freed 2068(118KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 705us total 25.615ms
,08-17 19:17:00.965  1012  1042 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-17 19:17:00.965  1012  1042 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-17 19:17:00.965  3144  3144 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,08-17 19:17:00.975  3144  3144 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 3
,08-17 19:17:00.985  1012  1037 D InputDispatcher: Focused application released
,08-17 19:17:01.005  5501  5501 I art     : Explicit concurrent mark sweep GC freed 404(27KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 8MB/11MB, paused 1.980ms total 60.475ms
,08-17 19:17:01.005  1012  1097 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-17 19:17:01.005  3144  3144 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,08-17 19:17:01.015  3821  3821 I art     : Explicit concurrent mark sweep GC freed 22861(1396KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 15MB/26MB, paused 1.399ms total 116.282ms
,08-17 19:17:01.025  3144  3144 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,08-17 19:17:01.025  3144  3144 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 3
,08-17 19:17:01.035  3144  3144 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,08-17 19:17:01.035  1888  1888 E SamsungIME: mOCRHelper is null
,08-17 19:17:01.075  6577  6577 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-17 19:17:01.115  1012  1123 V NetworkStats: removeUidsLocked() for UIDs [10155]
08-17 19:17:01.115  1012  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 19:17:01.115  1012  1123 V NetworkStats: performPollLocked(flags=0x3)
,08-17 19:17:01.115  1012  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 19:17:01.115  1012  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 19:17:01.115  1012  1123 V NetworkStats: performPollLocked() took 6ms
08-17 19:17:01.115  1012  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:17:01.125  3144  3144 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,08-17 19:17:01.135  1012  1012 I art     : Explicit concurrent mark sweep GC freed 74671(4MB) AllocSpace objects, 13(208KB) LOS objects, 33% free, 28MB/42MB, paused 5.939ms total 211.840ms
,08-17 19:17:01.135  1012  1541 I art     : WaitForGcToComplete blocked for 99.427ms for cause Explicit
,08-17 19:17:01.135  1442  1442 D PersonaManager: isKioskContainerExistOnDevice
,08-17 19:17:01.135  3144  3144 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,08-17 19:17:01.135  3680  3680 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Aug 17 19:17:01 GMT+02:00 2016
,08-17 19:17:01.155  1442  1442 D RegisteredServicesCache: empty dynamic service
,08-17 19:17:01.155  3144  3144 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,08-17 19:17:01.165  1442  1442 D RegisteredComponentCache: Collect Tech packages for Knox
,08-17 19:17:01.165  1442  1442 D PersonaManager: isKioskContainerExistOnDevice
,08-17 19:17:01.175  1012  1221 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
08-17 19:17:01.175  1012  1221 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,08-17 19:17:01.185  3144  3144 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 3
,08-17 19:17:01.195  3144  3144 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,08-17 19:17:01.205  3144  3144 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,08-17 19:17:01.205  3144  3144 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,08-17 19:17:01.205  3144  3144 I DBG_DM  : [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,08-17 19:17:01.215  3144  3144 I DBG_DM  : [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,08-17 19:17:01.215  1012  2929 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-17 19:17:01.215  1012  2929 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-17 19:17:01.215  1012  2929 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-17 19:17:01.215  3144  3144 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,08-17 19:17:01.275  1012  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:17:01.275  1012  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 19:17:01.305  1012  1012 D RCPManagerService: PackageReceiver onReceive()
,08-17 19:17:01.305  1012  1012 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-17 19:17:01.305  1012  1012 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-17 19:17:01.305  1012  1012 I OTPFW   : PackageRemovalReceiver::onReceive Enter
,08-17 19:17:01.315  1012  1012 D OTPFW   : OtpDbHelper::getInstance New instance created
,08-17 19:17:01.315  1012  1012 D OTPFW   : DBIntegrity::getInstance - New instance created
,08-17 19:17:01.325  1012  1012 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
,08-17 19:17:01.325  1012  1012 I OTPFW   : ProvisionData::getAllEntries Enter
,08-17 19:17:01.325  1012  1012 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-17 19:17:01.325  1012  1541 I art     : Explicit concurrent mark sweep GC freed 17999(2040KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 4.830ms total 192.205ms
,08-17 19:17:01.325  1012  1052 I art     : WaitForGcToComplete blocked for 362.541ms for cause Explicit
,08-17 19:17:01.325  1906  2110 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-17 19:17:01.325   257   257 I SurfaceFlinger: id=16 createSurf (720x1280),1 flag=404, YUIInstallC
,08-17 19:17:01.325  1012  1012 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-17 19:17:01.325  1012  1012 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-17 19:17:01.325  1012  1012 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-17 19:17:01.325  1012  1540 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-17 19:17:01.325  1012  1012 V EnterpriseBillingPolicy: uID is 10155
08-17 19:17:01.325  1012  1012 V EnterpriseBillingPolicy: Removed Packageuid is0
08-17 19:17:01.325  1012  1012 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
08-17 19:17:01.325  1012  1040 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-17 19:17:01.325  1012  1012 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-17 19:17:01.325  1012  1012 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-17 19:17:01.325  1012  1012 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-17 19:17:01.325  1012  1012 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-17 19:17:01.335  1012  1540 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
08-17 19:17:01.335  1012  2930 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-17 19:17:01.335  1012  1012 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
08-17 19:17:01.335  1012  2930 D SecContentProvider2: mCursor = null
,08-17 19:17:01.335  1012  1540 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:17:01.335  1012  1540 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:17:01.335  1012  1540 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-17 19:17:01.335  1012  1497 D InputDispatcher: Focus entered window: 3144
,08-17 19:17:01.335  1012  1042 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-17 19:17:01.335  3144  3144 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-17 19:17:01.335  1012  1042 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-17 19:17:01.335  1012  1012 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-17 19:17:01.335  1012  1036 D EnterpriseDeviceManagerService: Package has changed for user 0
08-17 19:17:01.335  1012  1036 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-17 19:17:01.335  1012  1012 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-17 19:17:01.335  1012  1012 V EnterpriseBillingPolicy: uID is 10155
08-17 19:17:01.345  1012  1012 V EnterpriseBillingPolicy: Removed Packageuid is0
08-17 19:17:01.345  1012  1012 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-17 19:17:01.345  1012  1036 W TextServicesManagerService: no available spell checker services found
08-17 19:17:01.345  1012  1012 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-17 19:17:01.345  1012  1012 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-17 19:17:01.345  1012  1012 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-17 19:17:01.345  1012  1012 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-17 19:17:01.345  1012  1012 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-17 19:17:01.345  1012  1012 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
08-17 19:17:01.345  1012  1012 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-17 19:17:01.345  1012  1012 D PersonaManagerService: getPersonasForUser(): returning null!
08-17 19:17:01.345  1012  1012 V AlarmManagerEXT: com.test.thalitest(10155) is removed.
,08-17 19:17:01.355  1012  1036 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 19:17:01.355  3680  3680 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,08-17 19:17:01.355  1012  1478 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
,08-17 19:17:01.355  1012  1478 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-17 19:17:01.355  3144  3144 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,08-17 19:17:01.355  3144  3144 V ActivityThread: updateVisibility : ActivityRecord{7bdc3f9 token=android.os.BinderProxy@2565f204 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,08-17 19:17:01.365  1012  1478 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-17 19:17:01.365  1012  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:17:01.365  1012  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:17:01.365  1012  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:17:01.365  1012  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:17:01.365  1012  2745 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,08-17 19:17:01.365  3680  3680 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,08-17 19:17:01.375  3680  3680 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-17 19:17:01.385  7128  7128 E Zygote  : MountEmulatedStorage()
08-17 19:17:01.385  7128  7128 I libpersona: KNOX_SDCARD checking this for 10094
08-17 19:17:01.385  7128  7128 E Zygote  : v2
08-17 19:17:01.385  7128  7128 I libpersona: KNOX_SDCARD not a persona
,08-17 19:17:01.385  7128  7128 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-17 19:17:01.385  7128  7128 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-17 19:17:01.385  3680  3680 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-17 19:17:01.385  7128  7128 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-17 19:17:01.385  1012  1360 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-17 19:17:01.395  1012  1478 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7128 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,08-17 19:17:01.395  3680  7127 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-17 19:17:01.395  1012  1037 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
08-17 19:17:01.395  1012  7134 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-17 19:17:01.395  3680  7127 I KLMS-2.5.183: : KLMSIntentService(): PACKAGE_REMOVED
08-17 19:17:01.395  1012  1360 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6298 uid 10155
,08-17 19:17:01.405  3680  7127 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().START
,08-17 19:17:01.405  1012  1037 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:17:01.405  1012  1037 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:17:01.405  1012  1037 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:17:01.405  1012  1037 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:17:01.405  3680  7127 I KLMS-2.5.183: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
08-17 19:17:01.415  1012  1036 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-17 19:17:01.415  3144  3144 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2565f204 time:161675
08-17 19:17:01.425  1012  1128 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
08-17 19:17:01.425  1888  1888 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,08-17 19:17:01.425  1173  1173 D PanelView: There is/are notification(s) 
,08-17 19:17:01.435  7145  7145 E Zygote  : MountEmulatedStorage(),
08-17 19:17:01.435  7145  7145 E Zygote  : v2
08-17 19:17:01.435  7145  7145 I libpersona: KNOX_SDCARD checking this for 10044
08-17 19:17:01.435  7145  7145 I libpersona: KNOX_SDCARD not a persona
,08-17 19:17:01.435  1012  1037 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7145 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,08-17 19:17:01.435  7145  7145 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-17 19:17:01.435  7145  7145 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-17 19:17:01.435  1012  1036 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 19:17:01.445  7145  7145 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-17 19:17:01.445  1012  1159 D TaskPersister: removeObsoleteFile: deleting file=129_task.xml
08-17 19:17:01.445  1012  1042 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1b497a14 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t127} time:161703
08-17 19:17:01.445  1012  1159 D TaskPersister: removeObsoleteFile: deleting file=127_task.xml
08-17 19:17:01.445  1173  1173 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
08-17 19:17:01.445  1012  1042 W ActivityManager: mDVFSHelper.release()
08-17 19:17:01.445  1173  1173 D PersonaManager: isKioskContainerExistOnDevice
08-17 19:17:01.445  1173  1173 D PersonaManager: isKioskContainerExistOnDevice
08-17 19:17:01.445  1173  1173 D PanelView: There is/are notification(s) 
08-17 19:17:01.445  1173  1173 D PanelView: kidsfalse mQsExpansionEnabled:true
,08-17 19:17:01.455  1012  1037 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,08-17 19:17:01.455  1173  1173 D PersonaManager: isKioskContainerExistOnDevice
08-17 19:17:01.455  1173  1173 D PanelView: There is/are notification(s) 
08-17 19:17:01.455  1173  1173 D PanelView: kidsfalse mQsExpansionEnabled:true
,08-17 19:17:01.455  1012  1037 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:17:01.455  1012  1037 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:17:01.455  1012  1037 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:17:01.455  1012  1037 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:17:01.455  7128  7128 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:17:01.455  7128  7128 D ActivityThread: Added TimaKeyStore provider
,08-17 19:17:01.475  7156  7156 E Zygote  : MountEmulatedStorage()
08-17 19:17:01.475  7156  7156 E Zygote  : v2
,08-17 19:17:01.475  7156  7156 I libpersona: KNOX_SDCARD checking this for 10149
08-17 19:17:01.475  7156  7156 I libpersona: KNOX_SDCARD not a persona
08-17 19:17:01.475  7156  7156 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-17 19:17:01.475  7156  7156 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-17 19:17:01.475  7156  7156 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-17 19:17:01.475  1012  1037 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7156 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-17 19:17:01.505  3680  7127 I KLMS-2.5.183: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,08-17 19:17:01.505  7145  7145 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:17:01.505  7145  7145 D ActivityThread: Added TimaKeyStore provider
,08-17 19:17:01.515  7156  7156 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:17:01.515  7156  7156 D ActivityThread: Added TimaKeyStore provider
,08-17 19:17:01.525  3680  7127 I KLMS-2.5.183: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,08-17 19:17:01.525  1173  1173 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,08-17 19:17:01.525  3680  7127 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().END
,08-17 19:17:01.525   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-17 19:17:01.535  6833  7158 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,08-17 19:17:01.555  3680  3680 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,08-17 19:17:01.565  7145  7145 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-17 19:17:01.565  7145  7145 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 19:17:01.565  7145  7145 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-17 19:17:01.565  7145  7145 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-17 19:17:01.565  7145  7145 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,08-17 19:17:01.565  7145  7145 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-17 19:17:01.565  7145  7145 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-17 19:17:01.565  7145  7145 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-17 19:17:01.565  6051  6061 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
08-17 19:17:01.565  6051  6061 D BadgeProvider: sendNotify, [notify] : null
08-17 19:17:01.565  6051  6061 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
08-17 19:17:01.565  6051  6061 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-17 19:17:01.565  6051  6061 D BadgeProvider: update, [UpdateCount] : 1
,08-17 19:17:01.575  6833  6833 I art     : Explicit concurrent mark sweep GC freed 767(55KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 6MB/9MB, paused 4.783ms total 56.450ms
,08-17 19:17:01.585  1012  1036 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-17 19:17:01.595  1012  1036 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 19:17:01.595  7128  7128 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,08-17 19:17:01.605  1012  1036 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 19:17:01.605  7128  7128 D elm:15183: ELMEngine.ELMEngine( context ).
,08-17 19:17:01.605  7128  7128 D elm:15183: MDMBridge.setEnterpriseBridge()
,08-17 19:17:01.605  1012  1497 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
08-17 19:17:01.605  1012  1497 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-17 19:17:01.605  1012  1497 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:17:01.605  1012  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:17:01.605  1012  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,08-17 19:17:01.605  1012  1024 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-17 19:17:01.605  1012  1024 D SecContentProvider2: mCursor = null
,08-17 19:17:01.615  7128  7128 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,08-17 19:17:01.625  1012  1360 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,08-17 19:17:01.625  1012  1360 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:17:01.625  1012  1360 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:17:01.625  1012  1360 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:17:01.625  1012  1360 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:17:01.625  7128  7128 D elm:15183: ElmAgentService : onCreate()
,08-17 19:17:01.625  7128  7180 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,08-17 19:17:01.635  7128  7180 D elm:15183: MainReceiver.listeningToPackageRemoved()
08-17 19:17:01.635  7128  7180 D elm:15183: MDMBridge.getInstance()
08-17 19:17:01.635  7128  7180 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,08-17 19:17:01.645  7181  7181 E Zygote  : MountEmulatedStorage()
,08-17 19:17:01.645  7181  7181 E Zygote  : v2
08-17 19:17:01.645  7181  7181 I libpersona: KNOX_SDCARD checking this for 1000
,08-17 19:17:01.645  7181  7181 I libpersona: KNOX_SDCARD not a persona
08-17 19:17:01.645  1012  1360 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7181 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
08-17 19:17:01.645  7181  7181 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-17 19:17:01.645  7181  7181 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-17 19:17:01.655  7128  7180 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,08-17 19:17:01.655  7181  7181 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-17 19:17:01.655  3359  3359 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,08-17 19:17:01.655  3359  3359 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-17 19:17:01.655  3359  3359 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
08-17 19:17:01.655  3359  3359 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
08-17 19:17:01.655  3359  3359 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
08-17 19:17:01.655  3359  3359 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
08-17 19:17:01.655  3359  3359 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
08-17 19:17:01.655  3359  3359 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:17:01.655  3359  3359 W System.err: 	at android.os.Looper.loop(Looper.java:145)
08-17 19:17:01.655  3359  3359 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 19:17:01.655  3359  3359 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:17:01.655  3359  3359 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 19:17:01.655  3359  3359 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 19:17:01.655  3359  3359 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-17 19:17:01.675  7128  7128 D elm:15183: ElmAgentService : onDestroy().
,08-17 19:17:01.685  7156  7156 D ThemeInfoUtil: getCurrentFestivalName is [null]
,08-17 19:17:01.685  1012  1036 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 19:17:01.685  7156  7156 D ThemeInfoUtil: isCurrentFestival = false
08-17 19:17:01.685  6560  6560 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-17 19:17:01.685  6560  6560 I PCWCLIENTTRACE_PushUtil: sales region : global
08-17 19:17:01.685  6560  6560 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-17 19:17:01.685  6560  6560 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,08-17 19:17:01.685  7181  7181 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:17:01.685  7181  7181 D ActivityThread: Added TimaKeyStore provider
,08-17 19:17:01.685  1012  1074 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,08-17 19:17:01.695  1012  1074 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:17:01.695  1012  1074 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:17:01.695  1012  1074 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:17:01.695  1012  1074 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:17:01.695  1012  1052 I art     : Explicit concurrent mark sweep GC freed 12134(734KB) AllocSpace objects, 6(102KB) LOS objects, 33% free, 27MB/41MB, paused 5.243ms total 369.105ms
,08-17 19:17:01.705  7198  7198 E Zygote  : MountEmulatedStorage(),
08-17 19:17:01.705  7198  7198 E Zygote  : v2,
08-17 19:17:01.705  1012  1074 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7198 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
08-17 19:17:01.715  7198  7198 I libpersona: KNOX_SDCARD checking this for 10032
,08-17 19:17:01.715  7198  7198 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-17 19:17:01.715  7198  7198 I libpersona: KNOX_SDCARD not a persona
08-17 19:17:01.715  7198  7198 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-17 19:17:01.715  7198  7198 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-17 19:17:01.715  1012  1074 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,08-17 19:17:01.715  1012  1074 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:17:01.715  1012  1074 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:17:01.715  1012  1074 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:17:01.715  1012  1074 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:17:01.735  7214  7214 E Zygote  : MountEmulatedStorage()
08-17 19:17:01.735  7214  7214 E Zygote  : v2
08-17 19:17:01.735  7214  7214 I libpersona: KNOX_SDCARD checking this for 10152
08-17 19:17:01.735  7214  7214 I libpersona: KNOX_SDCARD not a persona
08-17 19:17:01.735  1012  1036 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-17 19:17:01.735  1012  1036 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 19:17:01.735  1012  1036 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-17 19:17:01.735  7214  7214 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-17 19:17:01.735  1012  1036 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 19:17:01.745  7198  7198 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:17:01.745  7198  7198 D ActivityThread: Added TimaKeyStore provider
08-17 19:17:01.745  1012  1074 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7214 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
08-17 19:17:01.745  7214  7214 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-17 19:17:01.745  7214  7214 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:17:01.765  7214  7214 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:17:01.765  7214  7214 D ActivityThread: Added TimaKeyStore provider
,08-17 19:17:01.775  1012  1052 D PackageManager: delete codoeFile: 
,08-17 19:17:01.795  1012  1052 D AASAuninstall: userId = 0, info.removedAppID = 10155, info.uid = 10155, packageName = com.test.thalitest
,08-17 19:17:01.795  1012  1052 I AASA_removePackage: UID=10155 Target=com.test.thalitest
,08-17 19:17:01.795  1012  1052 D PackageManager: result of delete: 1{137142109}
,08-17 19:17:01.815  7111  7111 D AndroidRuntime: Shutting down VM
,08-17 19:17:01.825  7145  7145 D NearbySource: Nearby Source Create!
,08-17 19:17:01.825  7145  7145 D NearbyContext: Nearby Context Create!
,08-17 19:17:01.825  1012  1036 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 19:17:01.825  1012  1128 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-17 19:17:01.825  7214  7214 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
08-17 19:17:01.825  1012  1128 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,08-17 19:17:01.835  1012  1036 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 19:17:01.835  1173  1681 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-17 19:17:01.835  1012  1036 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-17 19:17:01.835  1012  1036 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-17 19:17:01.835  1012  1128 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,08-17 19:17:01.835  7198  7229 I FeatureConfig: init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,08-17 19:17:01.835  3821  6245 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-17 19:17:01.845  7181  7181 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,08-17 19:17:01.845  1012  1541 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
,08-17 19:17:01.845  1012  1541 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,08-17 19:17:01.845  1173  1681 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-17 19:17:01.855  1012  1541 W ActivityManager: userId = 0, bbcId = -10000
,08-17 19:17:01.855  1012  1541 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:17:01.855  1012  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
08-17 19:17:01.855  1012  1036 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 19:17:01.855  3821  6245 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-17 19:17:01.855  1012  1036 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-17 19:17:01.855  1012  1036 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-17 19:17:01.865  1012  1036 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-17 19:17:01.865  1012  1036 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-17 19:17:01.865  1012  1052 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-17 19:17:01.865  1012  1052 D PackageManager: userId{-1}
08-17 19:17:01.865  1012  1052 D PackageManager: andCode{true}
,08-17 19:17:01.865  1012  1036 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 19:17:01.875  1012  1540 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
,08-17 19:17:01.875  1012  1540 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,08-17 19:17:01.875  1012  1540 W ActivityManager: userId = 0, bbcId = -10000
08-17 19:17:01.875  1012  1540 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 19:17:01.875  1012  1540 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,08-17 19:17:01.885  7198  7229 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,08-17 19:17:01.885  7198  7229 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 19:17:01.885  7198  7229 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-17 19:17:01.885  7198  7229 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-17 19:17:01.885  7198  7229 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-17 19:17:01.885  1012  1025 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,08-17 19:17:01.885  7198  7229 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,08-17 19:17:01.885  1012  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:17:01.885  1012  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:17:01.885  1012  1036 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-17 19:17:01.885  1012  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:17:01.885  1012  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:17:01.895  1475  1475 D Launcher.Model: reloadBadges entered.,
,08-17 19:17:01.895  7198  7229 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.,
08-17 19:17:01.895  7198  7229 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-17 19:17:01.895  7198  7229 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-17 19:17:01.895  7198  7229 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 19:17:01.895  7198  7229 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-17 19:17:01.895  7198  7229 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.,
08-17 19:17:01.895  1012  1036 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-17 19:17:01.905  1012  1036 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-17 19:17:01.905  7233  7233 E Zygote  : MountEmulatedStorage()
08-17 19:17:01.905  7233  7233 E Zygote  : v2
08-17 19:17:01.905  7233  7233 I libpersona: KNOX_SDCARD checking this for 1000
08-17 19:17:01.905  7233  7233 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-17 19:17:01.905  7233  7233 I libpersona: KNOX_SDCARD not a persona
08-17 19:17:01.905   256   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
08-17 19:17:01.905   256   530 W Vold    : Returning OperationFailed - no handler for errno 0
08-17 19:17:01.905  1012  1025 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7233 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,08-17 19:17:01.905  7145  7145 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
08-17 19:17:01.905  7233  7233 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-17 19:17:01.905  7145  7145 D SLinkSource: Samsung link source created
08-17 19:17:01.905  7233  7233 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:17:01.915  1012  1025 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-17 19:17:01.915  1012  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:17:01.915  1012  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:17:01.915  1012  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:17:01.915  1012  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:17:01.935  7198  7229 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-17 19:17:01.935  7198  7229 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 19:17:01.935  7198  7229 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-17 19:17:01.935  7245  7245 E Zygote  : MountEmulatedStorage()
08-17 19:17:01.935  7245  7245 I libpersona: KNOX_SDCARD checking this for 10035
08-17 19:17:01.935  7245  7245 E Zygote  : v2
08-17 19:17:01.935  7245  7245 I libpersona: KNOX_SDCARD not a persona
08-17 19:17:01.935  7245  7245 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-17 19:17:01.935  1012  1025 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7245 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-17 19:17:01.935  7245  7245 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-17 19:17:01.935  7245  7245 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-17 19:17:01.945  1012  1052 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-17 19:17:01.945  7233  7233 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 19:17:01.945  7233  7233 D ActivityThread: Added TimaKeyStore provider
,08-17 19:17:01.945  7198  7229 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-17 19:17:01.945  7198  7229 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-17 19:17:01.945  7198  7229 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,08-17 19:17:01.955  1012  1025 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,08-17 19:17:01.965  1012  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:17:01.965  1012  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:17:01.965  1012  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:17:01.965  1012  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:17:01.965  7198  7229 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-17 19:17:01.965  7198  7229 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 19:17:01.965  7198  7229 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-17 19:17:01.965  7198  7229 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-17 19:17:01.965  7198  7229 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
08-17 19:17:01.965  7198  7229 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-17 19:17:01.965  7198  7229 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-17 19:17:01.965  7198  7229 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-17 19:17:01.965  7245  7245 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:17:01.965  7245  7245 D ActivityThread: Added TimaKeyStore provider
,08-17 19:17:01.975  7198  7229 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-17 19:17:01.975  7198  7229 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-17 19:17:01.975  7198  7229 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-17 19:17:01.985  7198  7229 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.,
08-17 19:17:01.985  7198  7229 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-17 19:17:01.985  7198  7229 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-17 19:17:01.985  7198  7229 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-17 19:17:01.985  7198  7229 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-17 19:17:01.985  7266  7266 E Zygote  : MountEmulatedStorage()
,08-17 19:17:01.985  7266  7266 E Zygote  : v2
08-17 19:17:01.985  7266  7266 I libpersona: KNOX_SDCARD checking this for 10156
08-17 19:17:01.985  7266  7266 I libpersona: KNOX_SDCARD not a persona,
08-17 19:17:01.985  7266  7266 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,08-17 19:17:01.985  7266  7266 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
08-17 19:17:01.985  1012  1025 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7266 uid=10156 gids={50156, 9997} abi=armeabi-v7a
08-17 19:17:01.985  7266  7266 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:17:01.995  7198  7229 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
08-17 19:17:01.995  7198  7229 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-17 19:17:01.995  7198  7229 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-17 19:17:01.995  7198  7229 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-17 19:17:02.005  1012  1024 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-17 19:17:02.015  7198  7229 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
08-17 19:17:02.015  7198  7229 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 19:17:02.015  7198  7229 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-17 19:17:02.015  7198  7229 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-17 19:17:02.015  7198  7229 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-17 19:17:02.015  1012  1024 I ActivityManager: Killing 5501:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,08-17 19:17:02.015  1012  1024 I ActivityManager: Killing 5633:com.android.vending/u0a28 (adj 15): empty #31
,08-17 19:17:02.025  1012  1541 I ActivityManager: Killing 6261:com.google.android.gms.unstable/u0a12 (adj 15): empty #31
,08-17 19:17:02.025  7111  7111 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.,
,08-17 19:17:02.025  7266  7266 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:17:02.025  7266  7266 D ActivityThread: Added TimaKeyStore provider
,08-17 19:17:02.035  7233  7233 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-17 19:17:02.035  1012  1478 I ActivityManager: Killing 6622:com.android.chrome/u0a81 (adj 15): empty #31
,08-17 19:17:02.035  1012  1025 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-17 19:17:02.045  7198  7229 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
08-17 19:17:02.045  7198  7229 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,08-17 19:17:02.055  7145  7145 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
,08-17 19:17:02.055  1012  1540 D PersonaManager: isKioskContainerExistOnDevice
,08-17 19:17:02.065  7145  7265 D ContactProvider: getAllContactInfoList Start
,08-17 19:17:02.065  7266  7266 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
,08-17 19:17:02.065  7266  7266 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,08-17 19:17:02.065  7233  7233 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
08-17 19:17:02.075  1012  1221 D ActivityManager: startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
,08-17 19:17:02.075  1012  1025 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
08-17 19:17:02.075  1012  1025 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,08-17 19:17:02.075  1012  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:17:02.075  1012  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:17:02.075  1012  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:17:02.075  1012  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:17:02.075  7266  7266 I TapandpayWidget:Utils: Clear T&P info.
,08-17 19:17:02.085  7198  7229 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-17 19:17:02.085  7198  7229 W ResourcesManager: Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
08-17 19:17:02.085  7198  7229 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-17 19:17:02.085  7198  7229 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-17 19:17:02.085  7198  7229 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-17 19:17:02.085  7198  7229 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-17 19:17:02.085  7266  7266 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
,08-17 19:17:02.095  7198  7229 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
08-17 19:17:02.095  7198  7229 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-17 19:17:02.095  7284  7284 E Zygote  : MountEmulatedStorage()
08-17 19:17:02.095  7284  7284 E Zygote  : v2
08-17 19:17:02.095  7284  7284 I libpersona: KNOX_SDCARD checking this for 10046
08-17 19:17:02.095  7284  7284 I libpersona: KNOX_SDCARD not a persona
,08-17 19:17:02.095  7284  7284 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-17 19:17:02.095  1012  1221 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=7284 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,08-17 19:17:02.095  7284  7284 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-17 19:17:02.105  7284  7284 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-17 19:17:02.105  1012  1221 I ActivityManager: Killing 6591:com.sec.android.fotaclient/u0a9 (adj 15): empty #31,
,08-17 19:17:02.105  6833  6833 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
08-17 19:17:02.105  1012  1221 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
,08-17 19:17:02.105  7198  7229 W GalaxyFinderApplication: system/finder_cp/cpdata.xml file not found
08-17 19:17:02.105  1012  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:17:02.105  1012  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:17:02.105  1012  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:17:02.105  1012  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:17:02.125  7299  7299 E Zygote  : MountEmulatedStorage()
08-17 19:17:02.125  7299  7299 E Zygote  : v2
08-17 19:17:02.125  7299  7299 I libpersona: KNOX_SDCARD checking this for 10091
08-17 19:17:02.125  7299  7299 I libpersona: KNOX_SDCARD not a persona
,08-17 19:17:02.125  7299  7299 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-17 19:17:02.135  7299  7299 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
08-17 19:17:02.135  7284  7284 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:17:02.135  7284  7284 D ActivityThread: Added TimaKeyStore provider
08-17 19:17:02.135  7299  7299 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-17 19:17:02.135  1012  1221 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7299 uid=10091 gids={50091, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-17 19:17:02.135  1012  1221 I ActivityManager: Killing 6643:com.sec.android.soagent/u0a34 (adj 15): empty #31
,08-17 19:17:02.145  7245  7306 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-17 19:17:02.155  7245  7306 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-17 19:17:02.155   303   303 I art     : Explicit concurrent mark sweep GC freed 8709(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 724us total 22.807ms
08-17 19:17:02.155  7299  7299 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 19:17:02.155  7299  7299 D ActivityThread: Added TimaKeyStore provider
,08-17 19:17:02.165  7245  7306 D SPPClientService: PushLog.txt file is not deleted.
08-17 19:17:02.165  7245  7306 D SPPClientService: PushLog.txt file is not deleted.
08-17 19:17:02.165  7245  7306 D SPPClientService: ============PushLog. stop!
,08-17 19:17:02.165  1012  2930 I ActivityManager: Killing 6466:com.google.android.talk/u0a104 (adj 15): empty #31
,08-17 19:17:02.175  1012  1221 D ActivityManager: startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
,08-17 19:17:02.175  6051  6061 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
08-17 19:17:02.175  1475  1475 D Launcher.Model: reloadBadges entered.
,08-17 19:17:02.175  6051  6061 D BadgeProvider: sendNotify, [notify] : null
08-17 19:17:02.175  6051  6061 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
08-17 19:17:02.175  6051  6061 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-17 19:17:02.175  6051  6061 D BadgeProvider: update, [UpdateCount] : 1
08-17 19:17:02.175  1012  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:17:02.175  1012  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:17:02.175  1012  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:17:02.175  1012  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:17:02.175  7284  7284 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
08-17 19:17:02.175  7284  7284 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 19:17:02.175  7284  7284 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-17 19:17:02.175  7284  7284 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-17 19:17:02.175  7284  7284 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-17 19:17:02.175  7284  7284 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,08-17 19:17:02.175   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 912us total 20.561ms
,08-17 19:17:02.195   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 630us total 17.817ms
,08-17 19:17:02.225  7318  7318 E Zygote  : MountEmulatedStorage(),
08-17 19:17:02.225  7318  7318 E Zygote  : v2
08-17 19:17:02.225  7318  7318 I libpersona: KNOX_SDCARD checking this for 10160
08-17 19:17:02.225  7318  7318 I libpersona: KNOX_SDCARD not a persona
08-17 19:17:02.225  1012  1221 I ActivityManager: Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=7318 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
,08-17 19:17:02.235  7318  7318 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-17 19:17:02.235  7284  7284 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
08-17 19:17:02.235  7318  7318 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-17 19:17:02.235  7318  7318 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 19:17:02.245  1012  1221 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sdk.samsunglink, hostingType: broadcast
,08-17 19:17:02.245  1012  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-17 19:17:02.245  1012  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:17:02.245  1012  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 19:17:02.245  1012  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 19:17:02.265  7333  7333 E Zygote  : MountEmulatedStorage()
08-17 19:17:02.265  7333  7333 E Zygote  : v2,
08-17 19:17:02.265  7333  7333 I libpersona: KNOX_SDCARD checking this for 10038
08-17 19:17:02.265  7333  7333 I libpersona: KNOX_SDCARD not a persona
,08-17 19:17:02.265  7333  7333 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-17 19:17:02.265  7318  7318 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-17 19:17:02.275  1012  1221 I ActivityManager: Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=7333 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
08-17 19:17:02.275  7318  7318 D ActivityThread: Added TimaKeyStore provider
,08-17 19:17:02.275  7333  7333 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051

```
