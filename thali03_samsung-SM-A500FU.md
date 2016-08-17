#### Test 8135127732cb2b8_thali03_samsung-SM-A500FU Logs


```
--------- beginning of main
08-17 14:23:05.829   290   290 E SMD     : DCD OFF
08-17 14:23:05.949  6262  6262 I dex2oat : ----------------------------------------------------
08-17 14:23:05.949  6262  6262 I dex2oat : <SS>: S T A R T I N G . . .
08-17 14:23:05.949  6262  6262 I dex2oat : <SS>: Zip is absent. Canceled.
08-17 14:23:05.949  6262  6262 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
08-17 14:23:05.979  6262  6262 I dex2oat : dex2oat took 25.027ms (threads: 4)
08-17 14:23:05.989  6227  6235 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-17 14:23:05.989  6227  6235 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-17 14:23:05.989  6227  6235 I Adreno-EGL: Build Date: 04/06/15 Mon
08-17 14:23:05.989  6227  6235 I Adreno-EGL: Local Branch: 
08-17 14:23:05.989  6227  6235 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-17 14:23:05.989  6227  6235 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-17 14:23:05.989  6227  6235 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
08-17 14:23:06.069  6227  6235 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-17 14:23:06.069  6227  6235 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-17 14:23:06.069  6227  6235 I Adreno-EGL: Build Date: 04/06/15 Mon
08-17 14:23:06.069  6227  6235 I Adreno-EGL: Local Branch: 
08-17 14:23:06.069  6227  6235 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-17 14:23:06.069  6227  6235 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-17 14:23:06.069  6227  6235 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
08-17 14:23:06.149  6227  6235 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-17 14:23:06.149  6227  6235 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-17 14:23:06.149  6227  6235 I Adreno-EGL: Build Date: 04/06/15 Mon
08-17 14:23:06.149  6227  6235 I Adreno-EGL: Local Branch: 
08-17 14:23:06.149  6227  6235 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-17 14:23:06.149  6227  6235 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-17 14:23:06.149  6227  6235 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
--------- beginning of system
08-17 14:23:06.249  1017  3056 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-17 14:23:06.249  1017  3056 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
08-17 14:23:06.259  1017  3056 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:06.259  1017  3056 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 14:23:06.259  1017  3056 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-17 14:23:06.269  1934  6225 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-17 14:23:06.269   278   980 D EnterpriseController: uids 10012
08-17 14:23:06.269   278   980 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-17 14:23:06.269   278   980 D Netd    : getNetworkForDns: using netid 502 for uid 10012
08-17 14:23:06.269  1934  6225 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-17 14:23:06.269  1934  6225 I qtaguid : Tagging socket 64 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1934, getuid(): 10012
08-17 14:23:06.329  1934  6225 I qtaguid : Tagging socket 67 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1934, getuid(): 10012
08-17 14:23:06.479  1934  2135 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
08-17 14:23:06.489  1934  2135 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
08-17 14:23:06.499  1934  2135 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-08-17 14:23:04.990+0200, stopTime=2016-08-17 14:23:06.502+0200, duration=1512ms
08-17 14:23:06.509  1934  6273 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-17 14:23:06.509   278   980 D EnterpriseController: uids 10012
08-17 14:23:06.509   278   980 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-17 14:23:06.509   278   980 D Netd    : getNetworkForDns: using netid 502 for uid 10012
08-17 14:23:06.519  1934  6273 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-17 14:23:06.519  1934  6273 I qtaguid : Tagging socket 69 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1934, getuid(): 10012
08-17 14:23:06.549  1017  1505 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
08-17 14:23:06.559  1934  6273 I qtaguid : Tagging socket 72 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1934, getuid(): 10012
,08-17 14:23:06.859  1934  6273 I qtaguid : Untagging socket 69
08-17 14:23:06.889  1017  3207 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 14:23:06.889  1017  3207 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
08-17 14:23:06.889  1017  3207 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:06.889  1017  3207 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 14:23:06.889  1017  3207 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-17 14:23:06.909  1934  2135 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
08-17 14:23:06.919  6277  6277 D AndroidRuntime: 
08-17 14:23:06.919  6277  6277 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-17 14:23:06.919  6277  6277 D AndroidRuntime: CheckJNI is OFF
08-17 14:23:06.919  6277  6277 D AndroidRuntime: readGMSProperty: start
08-17 14:23:06.919  6277  6277 D AndroidRuntime: readGMSProperty: already setted!!
08-17 14:23:06.919  6277  6277 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-17 14:23:06.919  6277  6277 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-17 14:23:06.919  6277  6277 D AndroidRuntime: readGMSProperty: end
08-17 14:23:06.919  6277  6277 D AndroidRuntime: addProductProperty: start
08-17 14:23:06.959  1017  3056 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-17 14:23:06.969  1017  3056 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:06.969  1017  3056 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 14:23:06.969  1017  3056 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-17 14:23:06.999  1017  3056 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-17 14:23:06.999  1017  3056 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:06.999  1017  3056 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 14:23:06.999  1017  3056 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-17 14:23:07.049  1017  3205 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-17 14:23:07.049  1017  3205 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:07.049  1017  3205 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 14:23:07.049  1017  3205 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-17 14:23:07.049  1934  6287 E CommitToConfigurationOperation: Malformed snapshot token (size): 
08-17 14:23:07.049  1934  6279 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
08-17 14:23:07.049  1017  1079 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-17 14:23:07.049  1017  1079 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:07.049  1017  1079 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 14:23:07.049  1017  1079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-17 14:23:07.069  6277  6277 E AffinityControl: AffinityControl: registerfunction enter
08-17 14:23:07.079  1017  1029 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-17 14:23:07.079  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:07.079  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 14:23:07.079  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-17 14:23:07.079  1934  6287 E CommitToConfigurationOperation: Malformed snapshot token (size): 
08-17 14:23:07.079  1934  6279 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
08-17 14:23:07.079  1017  1505 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-17 14:23:07.079  1017  1505 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:07.079  1017  1505 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 14:23:07.079  1017  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-17 14:23:07.089  6277  6277 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-17 14:23:07.099  1017  1030 E PersonaManagerService: inState():  stateMachine is null !!
08-17 14:23:07.099  1017  1030 I PersonaManagerService: PersonaId don't exist
08-17 14:23:07.099  1017  1030 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-17 14:23:07.109  1017  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-17 14:23:07.119  1017  1030 W ActivityManager: mDVFSHelper.acquire()
08-17 14:23:07.129  1017  1048 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-17 14:23:07.129  1017  1048 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-17 14:23:07.139  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:07.139  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:07.139  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:07.139  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:07.149  6291  6291 E Zygote  : MountEmulatedStorage()
08-17 14:23:07.149  6291  6291 E Zygote  : v2
08-17 14:23:07.149  6291  6291 I libpersona: KNOX_SDCARD checking this for 10155
08-17 14:23:07.149  6291  6291 I libpersona: KNOX_SDCARD not a persona
08-17 14:23:07.149  1017  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-17 14:23:07.149  1017  1030 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6291 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-17 14:23:07.149  1017  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-17 14:23:07.149  1017  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
08-17 14:23:07.149  1017  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-17 14:23:07.149   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, uhalitest
08-17 14:23:07.149  6291  6291 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-17 14:23:07.159  6291  6291 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-17 14:23:07.159  6291  6291 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-17 14:23:07.169  1017  1030 D InputDispatcher: Focused application set to: xxxx
08-17 14:23:07.169  1017  1030 D InputDispatcher: Focus left window: 3175
08-17 14:23:07.169  6277  6277 D AndroidRuntime: Shutting down VM
08-17 14:23:07.169  1017  1344 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-17 14:23:07.169  1017  1344 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:07.169  1017  1344 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 14:23:07.169  1017  1344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-17 14:23:07.169  1934  6287 E CommitToConfigurationOperation: Malformed snapshot token (size): 
08-17 14:23:07.169  1934  6279 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
08-17 14:23:07.169  1934  6279 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
08-17 14:23:07.179  6291  6291 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 14:23:07.179  6291  6291 D ActivityThread: Added TimaKeyStore provider
08-17 14:23:07.189  1017  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-17 14:23:07.189  1934  6279 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
08-17 14:23:07.199  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-17 14:23:07.199  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
08-17 14:23:07.209  1017  2745 D PersonaManager: isKioskContainerExistOnDevice
08-17 14:23:07.239   257   444 I SurfaceFlinger: id=10 Removed YUIInstallC (5/9)
08-17 14:23:07.239   257  1039 I SurfaceFlinger: id=10 Removed YUIInstallC (-2/9)
08-17 14:23:07.249  3175  3175 V ActivityThread: updateVisibility : ActivityRecord{3ac17caf token=android.os.BinderProxy@2d009e72 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
08-17 14:23:07.289  1017  1485 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
08-17 14:23:07.319  1934  6279 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-17 14:23:07.319   278   980 D EnterpriseController: uids 10012
08-17 14:23:07.319   278   980 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-17 14:23:07.319   278   980 D Netd    : getNetworkForDns: using netid 502 for uid 10012
08-17 14:23:07.329  1934  6279 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-17 14:23:07.329  1934  6279 I qtaguid : Tagging socket 81 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1934, getuid(): 10012
08-17 14:23:07.339  6291  6291 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
08-17 14:23:07.349  6291  6291 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 3733-3734)
08-17 14:23:07.349  6291  6291 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-17 14:23:07.369  6291  6291 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {308adf9b}
08-17 14:23:07.369  6291  6291 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-17 14:23:07.369  6291  6291 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
08-17 14:23:07.379  6277  6277 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
08-17 14:23:07.379  1934  6279 I qtaguid : Tagging socket 84 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1934, getuid(): 10012
,08-17 14:23:07.409  6291  6291 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-17 14:23:07.409  6291  6291 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-17 14:23:07.409  6291  6291 E SysUtils: ApplicationContext is null in ApplicationStatus,
,08-17 14:23:07.439  6291  6291 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
08-17 14:23:07.439  6291  6291 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
08-17 14:23:07.439  6291  6291 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,08-17 14:23:07.449  6291  6291 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-17 14:23:07.449  6291  6291 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-17 14:23:07.449  6291  6291 I Adreno-EGL: Build Date: 04/06/15 Mon
08-17 14:23:07.449  6291  6291 I Adreno-EGL: Local Branch: 
08-17 14:23:07.449  6291  6291 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-17 14:23:07.449  6291  6291 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-17 14:23:07.449  6291  6291 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-17 14:23:07.569  6291  6319 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,08-17 14:23:07.619  6291  6291 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-17 14:23:07.629  1017  1505 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-17 14:23:07.629  1934  6279 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 14:23:07.629  1934  6279 I qtaguid : Tagging socket 81 with tag 11065fff00000000{285630463,0} for uid -1, pid: 1934, getuid(): 10012
,08-17 14:23:07.639  6291  6291 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-17 14:23:07.649  6291  6291 D PhoneWindow: *FMB* installDecor mIsFloating : false
,08-17 14:23:07.649  6291  6291 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-17 14:23:07.659  6291  6291 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-17 14:23:07.669  6291  6291 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-17 14:23:07.669  6291  6291 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-17 14:23:07.709  6291  6333 D OpenGLRenderer: Render dirty regions requested: true
,08-17 14:23:07.719  1017  1043 W ActivityManager: Activity pause timeout for ActivityRecord{321899ac u0 com.test.thalitest/.MainActivity t129}
,08-17 14:23:07.719  1017  1079 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-17 14:23:07.719  1017  1079 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-17 14:23:07.719  1017  1079 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-17 14:23:07.719  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!,
08-17 14:23:07.719  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-17 14:23:07.729  6291  6291 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-17 14:23:07.729  6291  6291 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-17 14:23:07.739   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, NainActivit
,08-17 14:23:07.749  1017  3205 D InputDispatcher: Focus entered window: 6291,
08-17 14:23:07.749  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-17 14:23:07.749  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
08-17 14:23:07.749  6291  6291 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! ,
08-17 14:23:07.759  6291  6333 I OpenGLRenderer: Initialized EGL, version 1.4
,08-17 14:23:07.759  6291  6333 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,08-17 14:23:07.759  6291  6333 D OpenGLRenderer: Enabling debug mode 0
,08-17 14:23:07.769  1017  1531 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-17 14:23:07.779  1934  6279 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 14:23:07.779  1934  6279 I qtaguid : Tagging socket 81 with tag fffffb1f00000000{4294966047,0} for uid -1, pid: 1934, getuid(): 10012
,08-17 14:23:07.789  6291  6291 V ActivityThread: updateVisibility : ActivityRecord{1b7aefb2 token=android.os.BinderProxy@3c016114 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-17 14:23:07.809  1017  3207 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-17 14:23:07.809  1017  6336 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-17 14:23:07.809  1181  1181 D PanelView: There is/are notification(s) 
,08-17 14:23:07.819  1797  1797 I SamsungIME: getCurrentCandidateView
,08-17 14:23:07.829  1017  1048 I ActivityManager: Displayed Component not be shown by security: +611ms (total +9s200ms)
,08-17 14:23:07.829  1017  1048 W ActivityManager: mDVFSHelper.release()
,08-17 14:23:07.829  1017  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{321899ac u0 com.test.thalitest/.MainActivity t129} time:124214
,08-17 14:23:07.839   257  1039 I SurfaceFlinger: id=13 Removed uhalitest (7/9)
,08-17 14:23:07.839  6291  6291 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-17 14:23:07.839  6291  6291 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3c016114 time:124221
,08-17 14:23:07.839   257  4387 I SurfaceFlinger: id=13 Removed uhalitest (-2/9)
,08-17 14:23:07.889  1797  1797 D SamsungIME: Dismiss ExpandCandiate
,08-17 14:23:07.899  6291  6291 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6291
,08-17 14:23:07.919  1017  1727 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-17 14:23:07.919  1934  6279 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 14:23:07.919  1934  6279 I qtaguid : Tagging socket 81 with tag 11065b5800000000{285629272,0} for uid -1, pid: 1934, getuid(): 10012
,08-17 14:23:08.019  6291  6291 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-17 14:23:08.039  1797  1797 I SamsungIME: getDebugLevel  : 0x4f4c,
,08-17 14:23:08.119  1797  1797 I SamsungIME: getDebugLevel  : 0x4f4c
,08-17 14:23:08.129  1797  1797 I SamsungIME: KeybaordView init() : load resources
,08-17 14:23:08.149  6291  6338 D jxcore_app_log: JniHelper::setJavaVM(0xb7d3b328), pthread_self() = -1205197312
,08-17 14:23:08.159  1797  1797 I SamsungIME: getCurrentKeyboard
08-17 14:23:08.159  1797  1797 I SamsungIME: getTextKeyboard
,08-17 14:23:08.169  6291  6338 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-17 14:23:08.169  6291  6338 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-17 14:23:08.169  6291  6338 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-17 14:23:08.169  6291  6338 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-17 14:23:08.169  6291  6338 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-17 14:23:08.169  6291  6338 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37aaa962 added. We now have 1 listener(s)
,08-17 14:23:08.169  6291  6338 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,08-17 14:23:08.169  6291  6338 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-17 14:23:08.169  6291  6338 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 14:23:08.169  6291  6338 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 14:23:08.179  1797  1797 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-17 14:23:08.179  6291  6338 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-17 14:23:08.179  6291  6338 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-17 14:23:08.179  6291  6338 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-17 14:23:08.179  6291  6338 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
08-17 14:23:08.179  6291  6338 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-17 14:23:08.179  6291  6338 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-17 14:23:08.179  6291  6338 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-17 14:23:08.179  6291  6338 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-17 14:23:08.179  6291  6338 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-17 14:23:08.179  6291  6338 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-17 14:23:08.179  6291  6338 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-17 14:23:08.179  6291  6338 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-17 14:23:08.179  6291  6338 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-17 14:23:08.179  6291  6338 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-17 14:23:08.179  6291  6338 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bebe229 added. We now have 1 listener(s)
,08-17 14:23:08.179  6291  6338 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 14:23:08.189  6291  6338 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 14:23:08.189  6291  6338 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-17 14:23:08.189  6291  6338 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-17 14:23:08.189  6291  6338 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-17 14:23:08.189  6291  6338 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-17 14:23:08.189  6291  6338 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 14:23:08.189  6291  6338 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:37:96:AB
,08-17 14:23:08.199  6291  6338 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-17 14:23:08.199  6291  6338 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:23:08.199  6291  6338 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:08.199  6291  6338 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:08.199  6291  6338 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:23:08.199  6291  6338 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:23:08.199  6291  6338 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:23:08.199  6291  6338 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:23:08.199  6291  6338 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 14:23:08.199  6291  6338 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-17 14:23:08.199  6291  6338 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 14:23:08.199  6291  6338 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-17 14:23:08.199  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:08.199  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:08.239  6291  6291 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-17 14:23:08.449   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-17 14:23:08.629  1934  6274 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 14:23:08.629  1934  6274 I qtaguid : Tagging socket 69 with tag 1000310200000000{268448002,0} for uid 10012, pid: 1934, getuid(): 10012
,08-17 14:23:08.739  1797  6342 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619,
,08-17 14:23:08.829   290   290 E SMD     : DCD OFF
,08-17 14:23:08.919  1934  6274 I qtaguid : Untagging socket 69
,08-17 14:23:08.919  1934  2135 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,08-17 14:23:08.949  1017  1531 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-17 14:23:08.969  6291  6344 W jxcore-log: Initializing JXcore engine
08-17 14:23:08.969  6291  6344 W jxcore-log: JXcore engine is ready
,08-17 14:23:09.019  1902  1902 E audit   : type=1400 msg=audit(1471436589.019:205): avc:  denied  { ioctl } for  pid=6344 comm="Thread-1078" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-17 14:23:09.019  1902  1902 E audit   :  SEPF_SM-A500FU_5.0.2-1_0051
08-17 14:23:09.019  1902  1902 E audit   : type=1300 msg=audit(1471436589.019:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9e7008f8 items=0 ppid=324 ppcomm=main pid=6344 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-1078" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-17 14:23:09.019  1902  1902 E audit   : type=1320 msg=audit(1471436589.019:205): 
,08-17 14:23:09.029  6291  6344 W jxcore-log: Starting JXcore engine
,08-17 14:23:09.139  6291  6344 W jxcore-log: Platform android
08-17 14:23:09.139  6291  6344 W jxcore-log: 
08-17 14:23:09.139  6291  6344 W jxcore-log: Process ARCH arm
08-17 14:23:09.139  6291  6344 W jxcore-log: 
,08-17 14:23:09.419  6291  6344 I jxcore-log: JXcore Cordova bridge is ready!
08-17 14:23:09.419  6291  6344 I jxcore-log: 
,08-17 14:23:09.419  6291  6344 W jxcore-log: JXcore engine is started
,08-17 14:23:09.429  6291  6338 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-17 14:23:09.429  6291  6291 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-17 14:23:09.449   335   335 I ServiceManager: Waiting for service AtCmdFwd...
,08-17 14:23:09.729  1017  1079 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-17 14:23:09.729  1017  1079 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4211, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-17 14:23:09.729  1017  1079 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-17 14:23:09.729  1017  1079 D BatteryService: stay LED for charging
,08-17 14:23:09.729  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-17 14:23:09.739  1017  1017 I MotionRecognitionService: Plugged
,08-17 14:23:09.739  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-17 14:23:09.739  1181  1181 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-17 14:23:09.739  1181  1181 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-17 14:23:09.739  1421  1421 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-17 14:23:09.749  1421  1421 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-17 14:23:09.759  2658  2658 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-17 14:23:09.759  2658  2757 D HeadsetStateMachine: Disconnected process message: 10
,08-17 14:23:09.769  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-17 14:23:09.769  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-17 14:23:09.769  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-17 14:23:10.449   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-17 14:23:11.249  1017  3056 I ActivityManager: Killing 5353:com.google.android.talk/u0a104 (adj 15): empty #31
,08-17 14:23:11.449   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-17 14:23:11.829   290   290 E SMD     : DCD OFF,
,08-17 14:23:12.419  1017  1050 I PowerManagerService: [PWL] Off : 50s ago
,08-17 14:23:12.449   335   335 I ServiceManager: Waiting for service AtCmdFwd...
,08-17 14:23:12.699  1017  2759 D SSRM:n  : SIOP:: AP = 330
,08-17 14:23:13.449   335   335 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-17 14:23:14.829   290   290 E SMD     : DCD OFF,
,08-17 14:23:17.189  1017  1058 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-17 14:23:17.839   290   290 E SMD     : DCD OFF
,08-17 14:23:19.789  1017  1343 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-17 14:23:19.789  1017  1343 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4238, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,08-17 14:23:19.789  1017  1343 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-17 14:23:19.789  1017  1343 D BatteryService: stay LED for charging
,08-17 14:23:19.799  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-17 14:23:19.799  1017  1017 I MotionRecognitionService: Plugged
,08-17 14:23:19.799  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-17 14:23:19.799  1181  1181 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-17 14:23:19.799  1181  1181 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-17 14:23:19.799  1421  1421 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-17 14:23:19.799  1421  1421 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-17 14:23:19.809  2658  2658 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-17 14:23:19.809  2658  2757 D HeadsetStateMachine: Disconnected process message: 10
,08-17 14:23:19.829  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-17 14:23:19.829  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-17 14:23:19.829  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-17 14:23:20.839   290   290 E SMD     : DCD OFF,
,08-17 14:23:21.209  1017  2783 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-17 14:23:22.339  1017  1345 E Watchdog: !@Sync 4,
,08-17 14:23:22.739  1017  2759 D SSRM:n  : SIOP:: AP = 350
,08-17 14:23:23.449   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-17 14:23:23.839   290   290 E SMD     : DCD OFF,
,08-17 14:23:24.449   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-17 14:23:25.459   335   335 I ServiceManager: Waiting for service AtCmdFwd...
,08-17 14:23:26.449  1017  1972 V SAMP_SPCM_test: CSC File load.. 
,08-17 14:23:26.459   335   335 I ServiceManager: Waiting for service AtCmdFwd...
,08-17 14:23:26.459  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,08-17 14:23:26.459  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
08-17 14:23:26.459  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
,08-17 14:23:26.459  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
08-17 14:23:26.459  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
08-17 14:23:26.459  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
,08-17 14:23:26.459  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
08-17 14:23:26.459  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
08-17 14:23:26.459  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
,08-17 14:23:26.459  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
08-17 14:23:26.459  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
08-17 14:23:26.459  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
,08-17 14:23:26.459  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
08-17 14:23:26.459  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
,08-17 14:23:26.469  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
08-17 14:23:26.469  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
08-17 14:23:26.469  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
,08-17 14:23:26.469  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
08-17 14:23:26.469  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
08-17 14:23:26.469  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
,08-17 14:23:26.469  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,08-17 14:23:26.499  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application,
08-17 14:23:26.499  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
08-17 14:23:26.499  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
08-17 14:23:26.499  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
08-17 14:23:26.499  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account,
08-17 14:23:26.499  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
08-17 14:23:26.499  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
08-17 14:23:26.499  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
08-17 14:23:26.499  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
,08-17 14:23:26.499  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
08-17 14:23:26.499  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
08-17 14:23:26.499  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
08-17 14:23:26.499  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
08-17 14:23:26.499  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
,08-17 14:23:26.499  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
08-17 14:23:26.499  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
08-17 14:23:26.499  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
08-17 14:23:26.499  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
08-17 14:23:26.499  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
,08-17 14:23:26.499  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
08-17 14:23:26.499  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,08-17 14:23:26.509  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password,
08-17 14:23:26.509  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
08-17 14:23:26.509  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
08-17 14:23:26.509  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
,08-17 14:23:26.509  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
08-17 14:23:26.509  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
08-17 14:23:26.509  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
08-17 14:23:26.509  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
08-17 14:23:26.509  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
,08-17 14:23:26.509  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
08-17 14:23:26.509  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
08-17 14:23:26.509  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
08-17 14:23:26.509  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
08-17 14:23:26.509  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
08-17 14:23:26.509  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
,08-17 14:23:26.509  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
08-17 14:23:26.509  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
08-17 14:23:26.509  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
08-17 14:23:26.509  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
08-17 14:23:26.509  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
,08-17 14:23:26.509  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
08-17 14:23:26.509  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
08-17 14:23:26.509  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
08-17 14:23:26.509  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
,08-17 14:23:26.509  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
08-17 14:23:26.509  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
08-17 14:23:26.509  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
,08-17 14:23:26.509  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
08-17 14:23:26.509  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
08-17 14:23:26.509  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
08-17 14:23:26.509  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
,08-17 14:23:26.509  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
08-17 14:23:26.509  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
08-17 14:23:26.509  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
,08-17 14:23:26.509  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
08-17 14:23:26.509  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
08-17 14:23:26.509  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
08-17 14:23:26.509  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
08-17 14:23:26.509  1017  1972 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,08-17 14:23:26.519  1017  1972 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,08-17 14:23:26.839   290   290 E SMD     : DCD OFF
,08-17 14:23:27.459   335   335 I ServiceManager: Waiting for service AtCmdFwd...
,08-17 14:23:28.459   335   335 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,08-17 14:23:29.799  6291  6344 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
08-17 14:23:29.799  6291  6344 I jxcore-log: 
,08-17 14:23:29.799  6291  6344 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-17 14:23:29.799  6291  6344 I jxcore-log: 
,08-17 14:23:29.799  6291  6344 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:23:29.799  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:29.799  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:29.799  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:23:29.799  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:23:29.799  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:23:29.799  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:23:29.799  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 14:23:29.809  6291  6344 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 14:23:29.809  6291  6344 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-17 14:23:29.809  6291  6344 I jxcore-log: 
,08-17 14:23:29.809  6291  6344 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-17 14:23:29.809  6291  6344 I jxcore-log: 
,08-17 14:23:29.839   290   290 E SMD     : DCD OFF
,08-17 14:23:29.859  1017  2745 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-17 14:23:29.859  1017  2745 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4237, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,08-17 14:23:29.859  1017  2745 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
,08-17 14:23:29.859  1181  1181 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-17 14:23:29.859  1017  2745 D BatteryService: stay LED for charging
08-17 14:23:29.859  1181  1181 D KeyguardUpdateMonitor: handleBatteryUpdate
08-17 14:23:29.859  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-17 14:23:29.859  1017  1017 I MotionRecognitionService: Plugged,
08-17 14:23:29.859  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
08-17 14:23:29.869  1421  1421 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-17 14:23:29.869  1421  1421 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-17 14:23:29.879  2658  2658 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-17 14:23:29.879  2658  2757 D HeadsetStateMachine: Disconnected process message: 10
,08-17 14:23:29.889  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-17 14:23:29.889  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-17 14:23:29.889  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-17 14:23:30.269  6291  6344 D ExecuteNativeTests: Running unit tests
,08-17 14:23:30.349  6291  6344 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 14:23:30.349  6291  6344 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f71de2f added. We now have 2 listener(s)
,08-17 14:23:30.359  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-17 14:23:30.359  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 14:23:30.359  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 14:23:30.359  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:23:30.359  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c881c3c added. We now have 2 listener(s)
08-17 14:23:30.359  6291  6344 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 14:23:30.359  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 14:23:30.359  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 14:23:30.369  6291  6344 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:23:30.369  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:30.369  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:30.369  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:23:30.369  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:23:30.369  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:23:30.369  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:23:30.369  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 14:23:30.369  6291  6344 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 14:23:30.369  6291  6344 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 14:23:30.369  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:30.379  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:30.379  6291  6344 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-17 14:23:30.379  6291  6344 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 14:23:30.379  6291  6344 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-17 14:23:30.379  6291  6344 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-17 14:23:30.389  6291  6344 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-17 14:23:30.389  6291  6344 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-17 14:23:30.389  6291  6344 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-17 14:23:30.389  6291  6344 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-17 14:23:30.389  6291  6344 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 14:23:30.399  6291  6344 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 14:23:30.399  6291  6344 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:23:30.399  6291  6344 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:30.399  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.399  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:23:30.399  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 14:23:30.399  6291  6344 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f71de2f removed from the list
08-17 14:23:30.399  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:30.399  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c881c3c removed from the list
08-17 14:23:30.399  6291  6344 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:23:30.399  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.399  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.399  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.399  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:23:30.399  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:23:30.399  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:30.409  6291  6344 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c881c3c not in the list
,08-17 14:23:30.409  6291  6344 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-17 14:23:30.409  6291  6344 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 14:23:30.409  6291  6344 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 14:23:30.409  6291  6344 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 14:23:30.409  6291  6344 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:30.409  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.409  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:23:30.409  6291  6344 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f71de2f not in the list
08-17 14:23:30.409  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:30.409  6291  6344 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c881c3c not in the list
08-17 14:23:30.409  6291  6344 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:23:30.409  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.409  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.409  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.409  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:23:30.409  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:23:30.409  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:23:30.409  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:30.409  6291  6344 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c881c3c not in the list
,08-17 14:23:30.419  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-17 14:23:30.419  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-17 14:23:30.419  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-17 14:23:30.419  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-17 14:23:30.419  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-17 14:23:30.419  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-17 14:23:30.419  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-17 14:23:30.419  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-17 14:23:30.419  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-17 14:23:30.419  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-17 14:23:30.419  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-17 14:23:30.419  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-17 14:23:30.419  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-17 14:23:30.419  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-17 14:23:30.419  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-17 14:23:30.419  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-17 14:23:30.419  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-17 14:23:30.419  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-17 14:23:30.429  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-17 14:23:30.429  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-17 14:23:30.429  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-17 14:23:30.429  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-17 14:23:30.429  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-17 14:23:30.429  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-17 14:23:30.429  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-17 14:23:30.429  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,08-17 14:23:30.429  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-17 14:23:30.429  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-17 14:23:30.429  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-17 14:23:30.429  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-17 14:23:30.429  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-17 14:23:30.429  6291  6344 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:23:30.429  6291  6344 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:23:30.429  6291  6344 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 14:23:30.429  6291  6344 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:30.429  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.429  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.429  6291  6344 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f71de2f not in the list
08-17 14:23:30.429  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:30.429  6291  6344 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c881c3c not in the list
08-17 14:23:30.429  6291  6344 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:23:30.429  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.429  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.429  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.429  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:23:30.429  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 14:23:30.429  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:23:30.429  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 14:23:30.429  6291  6344 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c881c3c not in the list
,08-17 14:23:30.429  6291  6344 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-17 14:23:30.429  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 14:23:30.439  6291  6344 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:23:30.439  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:30.439  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:30.439  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:23:30.439  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:23:30.439  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:23:30.439  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:23:30.439  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 14:23:30.439  6291  6344 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 14:23:30.439  6291  6344 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 14:23:30.439  6291  6344 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 14:23:30.439  6291  6344 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 14:23:30.439  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 14:23:30.439  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:23:30.439  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 14:23:30.439  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:30.439  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:30.449  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 14:23:30.449  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 14:23:30.459  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 14:23:30.459  6291  6344 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-17 14:23:30.469  6291  6344 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-17 14:23:30.469  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-17 14:23:30.469  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-17 14:23:30.469  6291  6344 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-17 14:23:30.479  2658  2667 D BtGatt.GattService: registerClient() - UUID=fa9e76de-38e1-466e-ac96-4fbf4cb25a21
,08-17 14:23:30.529  2658  2722 D BtGatt.GattService: onClientRegistered() - UUID=fa9e76de-38e1-466e-ac96-4fbf4cb25a21, clientIf=6
,08-17 14:23:30.529  6291  6299 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-17 14:23:30.529  2658  3051 D BtGatt.GattService: start scan with filters
,08-17 14:23:30.539  2658  2748 D BtGatt.ScanManager: handling starting scan
,08-17 14:23:30.539  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-17 14:23:30.539  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-17 14:23:30.539  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-17 14:23:30.539  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 14:23:30.539  6291  6344 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 14:23:30.539  2658  2748 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@308adf9b
,08-17 14:23:30.549  6291  6344 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
08-17 14:23:30.549  6291  6291 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 14:23:30.549  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 14:23:30.559  2658  2722 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-17 14:23:30.559  2658  2722 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 14:23:30.559  2658  2748 D BtGatt.ScanManager: allow scan with filters
,08-17 14:23:30.559  2658  2748 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-17 14:23:30.559  2658  2748 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-17 14:23:30.559  6291  6344 I io.jxcore.node.ConnectionHelper: start: OK
,08-17 14:23:30.569  6291  6344 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 14:23:30.569  6291  6344 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-17 14:23:30.569  2658  2722 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-17 14:23:30.569  2658  2722 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 14:23:30.569  2658  2748 D BtGatt.ScanManager: Starting BLE batch scan
,08-17 14:23:30.569  2658  2748 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-17 14:23:30.569  6291  6344 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-17 14:23:30.569  6291  6344 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-17 14:23:30.579  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.579  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 14:23:30.579  6291  6344 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts,
08-17 14:23:30.579  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-17 14:23:30.579  6291  6344 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 14:23:30.579  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-17 14:23:30.579  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 14:23:30.579  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 14:23:30.579  2658  2668 D BtGatt.GattService: stopScan() - queue size =1
,08-17 14:23:30.579  2658  2722 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-17 14:23:30.579  2658  2722 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 14:23:30.579  2658  2667 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-17 14:23:30.589  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-17 14:23:30.589  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 14:23:30.589  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 14:23:30.589  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 14:23:30.589  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 14:23:30.589  6291  6344 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 14:23:30.589  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-17 14:23:30.589  6291  6344 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-17 14:23:30.589  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 14:23:30.589  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 14:23:30.589  2658  2722 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
08-17 14:23:30.589  2658  2722 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 14:23:30.599  6291  6344 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:30.599  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.599  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:23:30.599  6291  6344 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f71de2f not in the list
08-17 14:23:30.599  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:30.599  6291  6344 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c881c3c not in the list
08-17 14:23:30.599  6291  6344 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:23:30.599  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.599  6291  6344 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-17 14:23:30.599  6291  6291 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 14:23:30.599  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 14:23:30.599  6291  6291 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 14:23:30.599  6291  6291 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 14:23:30.609  6291  6344 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:23:30.609  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:30.609  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:30.609  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:23:30.609  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:23:30.609  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:23:30.609  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:23:30.609  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 14:23:30.609  6291  6344 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 14:23:30.609  6291  6344 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 14:23:30.609  6291  6344 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 14:23:30.609  6291  6344 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 14:23:30.609  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 14:23:30.609  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:23:30.609  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 14:23:30.619  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 14:23:30.619  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:30.619  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:30.619  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 14:23:30.619  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 14:23:30.629  2658  2748 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 22
,08-17 14:23:30.629  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-17 14:23:30.629  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-17 14:23:30.629  6291  6344 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-17 14:23:30.629  2658  3051 D BtGatt.GattService: registerClient() - UUID=597317e7-b4df-4bbf-a236-00f90ff0f36b
,08-17 14:23:30.639  2658  2748 D BtGatt.ScanManager: filter size is 1
,08-17 14:23:30.639  2658  2748 D BtGatt.ScanManager: delete FilterIndex - 3
,08-17 14:23:30.649  2658  2722 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-17 14:23:30.649  2658  2722 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 14:23:30.649  2658  2748 D BtGatt.ScanManager: stopping BLe Batch
,08-17 14:23:30.649  2658  2722 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-17 14:23:30.649  2658  2722 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 14:23:30.649  2658  2748 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-17 14:23:30.659  2658  2722 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-17 14:23:30.659  2658  2722 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 14:23:30.669  2658  2722 D BtGatt.GattService: onClientRegistered() - UUID=597317e7-b4df-4bbf-a236-00f90ff0f36b, clientIf=6
,08-17 14:23:30.679  6291  6301 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-17 14:23:30.679  2658  2667 D BtGatt.GattService: start scan with filters
,08-17 14:23:30.679  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-17 14:23:30.679  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 14:23:30.679  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-17 14:23:30.679  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 14:23:30.679  6291  6344 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 14:23:30.679  2658  2748 D BtGatt.ScanManager: handling starting scan
,08-17 14:23:30.679  6291  6291 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 14:23:30.689  6291  6344 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 14:23:30.689  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 14:23:30.689  2658  2722 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-17 14:23:30.689  2658  2722 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 14:23:30.689  2658  2748 D BtGatt.ScanManager: allow scan with filters
08-17 14:23:30.689  2658  2748 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-17 14:23:30.689  2658  2748 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-17 14:23:30.689  6291  6344 I io.jxcore.node.ConnectionHelper: start: OK,
,08-17 14:23:30.699  6291  6344 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 14:23:30.699  6291  6344 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-17 14:23:30.699  6291  6344 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-17 14:23:30.699  2658  2722 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-17 14:23:30.699  2658  2722 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 14:23:30.699  2658  2748 D BtGatt.ScanManager: Starting BLE batch scan
,08-17 14:23:30.699  2658  2748 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-17 14:23:30.699  6291  6344 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-17 14:23:30.699  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:23:30.699  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 14:23:30.699  6291  6344 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 14:23:30.699  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
08-17 14:23:30.699  6291  6344 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 14:23:30.699  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-17 14:23:30.709  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 14:23:30.709  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 14:23:30.709  2658  3052 D BtGatt.GattService: stopScan() - queue size =1
,08-17 14:23:30.709  2658  3051 D BtGatt.GattService: unregisterClient() - clientIf=6,
08-17 14:23:30.709  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 14:23:30.709  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-17 14:23:30.709  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-17 14:23:30.709  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 14:23:30.709  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-17 14:23:30.709  6291  6344 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 14:23:30.709  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-17 14:23:30.709  6291  6344 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-17 14:23:30.709  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 14:23:30.709  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:23:30.709  2658  2722 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-17 14:23:30.709  2658  2722 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 14:23:30.719  6291  6291 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 14:23:30.719  6291  6291 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 14:23:30.719  6291  6344 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:30.719  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.719  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:23:30.719  6291  6344 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f71de2f not in the list
08-17 14:23:30.719  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:30.719  6291  6344 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c881c3c not in the list
08-17 14:23:30.719  6291  6344 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:23:30.719  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:23:30.719  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.719  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.719  6291  6291 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 14:23:30.719  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 14:23:30.719  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:23:30.719  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 14:23:30.719  6291  6344 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c881c3c not in the list
,08-17 14:23:30.719  2658  2722 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-17 14:23:30.719  2658  2722 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 14:23:30.719  6291  6344 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-17 14:23:30.719  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 14:23:30.739  6291  6344 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:23:30.739  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:30.739  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:30.739  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:23:30.739  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:23:30.739  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:23:30.739  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:23:30.739  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 14:23:30.739  2658  2748 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 23
,08-17 14:23:30.739  2658  2748 D BtGatt.ScanManager: filter size is 1
,08-17 14:23:30.739  2658  2748 D BtGatt.ScanManager: delete FilterIndex - 4
,08-17 14:23:30.739  6291  6344 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 14:23:30.739  6291  6344 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 14:23:30.749  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:30.749  2658  2722 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-17 14:23:30.749  2658  2722 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 14:23:30.749  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:30.749  2658  2748 D BtGatt.ScanManager: stopping BLe Batch
,08-17 14:23:30.749  6291  6344 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-17 14:23:30.749  6291  6344 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 14:23:30.749  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 14:23:30.759  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:23:30.759  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 14:23:30.759  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 14:23:30.759  2658  2722 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-17 14:23:30.759  2658  2722 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 14:23:30.759  2658  2748 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-17 14:23:30.769  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 14:23:30.769  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 14:23:30.769  2658  2722 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-17 14:23:30.769  2658  2722 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 14:23:30.789  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
08-17 14:23:30.789  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 14:23:30.789  6291  6344 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-17 14:23:30.789  2658  2667 D BtGatt.GattService: registerClient() - UUID=2d70ff0a-36ee-4b8b-85c6-56eb6420b6e5,
,08-17 14:23:30.829  2658  2722 D BtGatt.GattService: onClientRegistered() - UUID=2d70ff0a-36ee-4b8b-85c6-56eb6420b6e5, clientIf=6,
08-17 14:23:30.829  6291  6299 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-17 14:23:30.829  2658  2668 D BtGatt.GattService: start scan with filters
,08-17 14:23:30.829  2658  2748 D BtGatt.ScanManager: handling starting scan
,08-17 14:23:30.839  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-17 14:23:30.839  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 14:23:30.839  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 14:23:30.839  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 14:23:30.839  6291  6344 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 14:23:30.839  6291  6291 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 14:23:30.839  2658  2722 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-17 14:23:30.839  2658  2722 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 14:23:30.839  2658  2748 D BtGatt.ScanManager: allow scan with filters
08-17 14:23:30.839  2658  2748 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-17 14:23:30.839  2658  2748 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
08-17 14:23:30.839  6291  6344 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 14:23:30.849  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 14:23:30.849  6291  6344 I io.jxcore.node.ConnectionHelper: start: OK
,08-17 14:23:30.849  6291  6344 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 14:23:30.849  2658  2722 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-17 14:23:30.849  2658  2722 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 14:23:30.849  2658  2748 D BtGatt.ScanManager: Starting BLE batch scan
08-17 14:23:30.849  2658  2748 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-17 14:23:30.859  6291  6344 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-17 14:23:30.859  6291  6344 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-17 14:23:30.859  6291  6344 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-17 14:23:30.859  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:23:30.859  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 14:23:30.859  6291  6344 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 14:23:30.859  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-17 14:23:30.859  6291  6344 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 14:23:30.859  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-17 14:23:30.859  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 14:23:30.859  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 14:23:30.859  2658  2667 D BtGatt.GattService: stopScan() - queue size =1
,08-17 14:23:30.859  2658  2722 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-17 14:23:30.859  2658  2722 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 14:23:30.859  2658  2668 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-17 14:23:30.859  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 14:23:30.859  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 14:23:30.859  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 14:23:30.859  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 14:23:30.859  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 14:23:30.869  6291  6344 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 14:23:30.869  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-17 14:23:30.869  6291  6344 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 14:23:30.869  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 14:23:30.869  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 14:23:30.869  6291  6291 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 14:23:30.869  6291  6291 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 14:23:30.869  6291  6291 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 14:23:30.869  6291  6344 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:23:30.869  6291  6344 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-17 14:23:30.869  6291  6344 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:23:30.869  6291  6344 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:23:30.869  6291  6344 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:30.869  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.869  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:23:30.869  6291  6344 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f71de2f not in the list
08-17 14:23:30.869  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:30.869  6291  6344 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c881c3c not in the list
08-17 14:23:30.869  6291  6344 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:23:30.869  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:23:30.869  2658  2722 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-17 14:23:30.869  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.869  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.869  2658  2722 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 14:23:30.869  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:23:30.869  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:23:30.869  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:30.869  6291  6344 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c881c3c not in the list
,08-17 14:23:30.869  6291  6344 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-17 14:23:30.869  6291  6344 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:23:30.869  6291  6344 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:23:30.869  6291  6344 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:23:30.869  6291  6344 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:30.869  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.869  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.869  6291  6344 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f71de2f not in the list
08-17 14:23:30.869  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:30.869  6291  6344 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c881c3c not in the list
08-17 14:23:30.869  6291  6344 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:23:30.869  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.869  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.869  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.869  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:23:30.879  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:23:30.879  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:23:30.879  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:30.879  6291  6344 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c881c3c not in the list
08-17 14:23:30.879  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-17 14:23:30.879  6291  6344 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:23:30.879  6291  6344 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:23:30.879  6291  6344 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:23:30.879  6291  6344 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:30.879  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.879  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.879  6291  6344 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f71de2f not in the list
08-17 14:23:30.879  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:30.879  6291  6344 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c881c3c not in the list
08-17 14:23:30.879  6291  6344 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:23:30.879  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.879  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.879  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.879  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.879  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:23:30.879  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:23:30.879  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:30.879  6291  6344 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c881c3c not in the list
08-17 14:23:30.879  6291  6344 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-17 14:23:30.879  6291  6344 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:23:30.879  6291  6344 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:23:30.879  6291  6344 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:23:30.879  6291  6344 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:30.879  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.879  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.879  6291  6344 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f71de2f not in the list
08-17 14:23:30.879  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:30.879  6291  6344 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c881c3c not in the list
08-17 14:23:30.879  6291  6344 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:23:30.879  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.879  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.879  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.879  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.889  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:23:30.889  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:23:30.889  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:30.889  6291  6344 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c881c3c not in the list
08-17 14:23:30.889  6291  6344 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-17 14:23:30.889  6291  6344 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:23:30.889  6291  6344 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:23:30.889  6291  6344 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:23:30.889  6291  6344 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:30.889  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.889  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.889  6291  6344 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f71de2f not in the list
08-17 14:23:30.889  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:30.889  6291  6344 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c881c3c not in the list
08-17 14:23:30.889  6291  6344 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:23:30.889  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.889  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.889  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.889  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.889  2658  2748 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 24
08-17 14:23:30.889  2658  2748 D BtGatt.ScanManager: filter size is 1
08-17 14:23:30.889  2658  2748 D BtGatt.ScanManager: delete FilterIndex - 5
08-17 14:23:30.889  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:23:30.889  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:23:30.889  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:30.889  6291  6344 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c881c3c not in the list
08-17 14:23:30.889  6291  6344 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-17 14:23:30.889  6291  6344 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 14:23:30.889  6291  6344 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 14:23:30.889  6291  6344 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 14:23:30.889  6291  6344 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-17 14:23:30.889  6291  6344 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 14:23:30.889  6291  6344 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:23:30.889  6291  6344 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:23:30.889  6291  6344 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:23:30.889  6291  6344 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:30.889  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.889  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.889  6291  6344 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f71de2f not in the list
08-17 14:23:30.889  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:30.889  6291  6344 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c881c3c not in the list
08-17 14:23:30.889  6291  6344 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:23:30.889  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.889  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.889  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.889  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.889  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:23:30.889  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:23:30.889  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:30.889  6291  6344 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c881c3c not in the list
08-17 14:23:30.889  6291  6344 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 14:23:30.889  6291  6344 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-17 14:23:30.889  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-17 14:23:30.899  6291  6344 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 14:23:30.899  6291  6344 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-17 14:23:30.899  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-17 14:23:30.899  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-17 14:23:30.899  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-17 14:23:30.899  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-17 14:23:30.899  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-17 14:23:30.899  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-17 14:23:30.899  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-17 14:23:30.899  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-17 14:23:30.899  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-17 14:23:30.899  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-17 14:23:30.899  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-17 14:23:30.899  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-17 14:23:30.899  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-17 14:23:30.899  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-17 14:23:30.899  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-17 14:23:30.899  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-17 14:23:30.899  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-17 14:23:30.899  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-17 14:23:30.899  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810],
08-17 14:23:30.899  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-17 14:23:30.899  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-17 14:23:30.899  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-17 14:23:30.899  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-17 14:23:30.899  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-17 14:23:30.899  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-17 14:23:30.899  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-17 14:23:30.899  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-17 14:23:30.899  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-17 14:23:30.899  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-17 14:23:30.899  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-17 14:23:30.899  6291  6344 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-17 14:23:30.899  6291  6344 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 14:23:30.899  6291  6344 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-17 14:23:30.899  6291  6344 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 14:23:30.899  6291  6344 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 14:23:30.899  6291  6344 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-17 14:23:30.899  6291  6344 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 14:23:30.899  6291  6344 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 14:23:30.899  6291  6344 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-17 14:23:30.899  2658  2722 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-17 14:23:30.899  2658  2722 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 14:23:30.899  2658  2748 D BtGatt.ScanManager: stopping BLe Batch
08-17 14:23:30.909  2658  2722 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-17 14:23:30.909  2658  2722 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 14:23:30.909  2658  2748 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-17 14:23:30.909  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-17 14:23:30.909  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-17 14:23:30.909  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-17 14:23:30.909  6291  6344 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-17 14:23:30.909  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-17 14:23:30.909  6291  6344 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-17 14:23:30.909  6291  6344 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 14:23:30.909  6291  6344 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-17 14:23:30.909  6291  6344 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:23:30.909  6291  6344 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:23:30.909  6291  6344 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:23:30.909  6291  6344 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:30.909  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.909  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.909  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-17 14:23:30.919  2658  2722 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-17 14:23:30.919  2658  2722 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 14:23:30.919  6291  6362 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1142)
08-17 14:23:30.919  6291  6344 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f71de2f not in the list
08-17 14:23:30.919  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:30.919  6291  6344 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c881c3c not in the list
08-17 14:23:30.919  6291  6344 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:23:30.919  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.919  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.919  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.919  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.919  6291  6363 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1142
08-17 14:23:30.919  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:23:30.919  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:23:30.919  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:30.919  6291  6344 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c881c3c not in the list
08-17 14:23:30.919  6291  6344 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-17 14:23:30.919  6291  6344 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:23:30.919  6291  6344 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:23:30.919  6291  6344 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:23:30.919  6291  6344 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:30.919  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.919  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.919  6291  6344 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f71de2f not in the list
08-17 14:23:30.919  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:30.919  6291  6344 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c881c3c not in the list
08-17 14:23:30.919  6291  6344 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:23:30.919  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.919  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.919  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.919  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.919  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:23:30.919  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:23:30.919  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:30.919  6291  6344 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c881c3c not in the list
08-17 14:23:30.919  6291  6344 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-17 14:23:30.919  6291  6344 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:23:30.919  6291  6344 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:23:30.919  6291  6344 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:23:30.919  6291  6344 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:30.919  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.919  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.919  6291  6344 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f71de2f not in the list
08-17 14:23:30.919  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:30.919  6291  6344 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c881c3c not in the list
08-17 14:23:30.919  6291  6344 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:23:30.919  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.919  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.919  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.919  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.929  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:23:30.929  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:23:30.929  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:30.929  6291  6344 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c881c3c not in the list
08-17 14:23:30.929  6291  6344 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-17 14:23:30.929  6291  6344 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-17 14:23:30.929  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 14:23:30.929  6291  6344 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-17 14:23:30.929  6291  6344 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-17 14:23:30.929  6291  6344 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-17 14:23:30.929  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 14:23:30.929  6291  6344 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-17 14:23:30.929  6291  6344 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-17 14:23:30.929  6291  6344 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-17 14:23:30.929  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 14:23:30.929  6291  6344 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-17 14:23:30.929  6291  6344 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:23:30.929  6291  6344 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:23:30.929  6291  6344 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:23:30.929  6291  6344 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:30.929  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.929  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.929  6291  6344 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f71de2f not in the list
08-17 14:23:30.929  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:30.929  6291  6344 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c881c3c not in the list
08-17 14:23:30.929  6291  6344 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:23:30.929  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.929  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.929  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.929  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.929  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:23:30.929  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:23:30.929  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:30.929  6291  6344 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c881c3c not in the list
08-17 14:23:30.929  6291  6362 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
08-17 14:23:30.929  6291  6344 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:30.929  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.929  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.929  6291  6344 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f71de2f not in the list
08-17 14:23:30.929  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:30.929  6291  6344 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c881c3c not in the list
08-17 14:23:30.929  6291  6344 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:23:30.929  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.929  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.929  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:30.929  6291  6344 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c881c3c not in the list
08-17 14:23:30.929  6291  6344 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:30.929  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.929  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.929  6291  6344 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f71de2f not in the list
08-17 14:23:30.929  6291  6344 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:23:30.929  6291  6344 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:23:30.929  6291  6344 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:23:30.929  6291  6344 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:30.929  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.929  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.929  6291  6344 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f71de2f not in the list
08-17 14:23:30.929  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:30.929  6291  6344 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c881c3c not in the list
08-17 14:23:30.929  6291  6344 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:23:30.929  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.929  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.929  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.929  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.929  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:23:30.929  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:23:30.929  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:30.929  6291  6344 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c881c3c not in the list
08-17 14:23:30.929  6291  6362 D BluetoothSocket: connect(): myUserId = 0
08-17 14:23:30.929  6291  6362 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 14:23:30.939  2658  3051 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 14:23:30.939  6291  6362 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[108]}
08-17 14:23:30.939  6291  6344 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-17 14:23:30.939  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:23:30.939  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-17 14:23:30.939  6291  6344 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-17 14:23:30.939  6291  6344 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-17 14:23:30.939  6291  6344 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-17 14:23:30.939  6291  6344 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 14:23:30.939  6291  6291 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-17 14:23:30.939  6291  6344 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:30.939  6291  6344 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-17 14:23:30.939  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-17 14:23:30.939  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-17 14:23:30.939  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.939  6291  6344 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-17 14:23:30.939  6291  6344 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f71de2f not in the list
08-17 14:23:30.939  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:30.939  6291  6291 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-17 14:23:30.939  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 14:23:30.939  6291  6344 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 14:23:30.939  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 14:23:30.939  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.939  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.939  6291  6364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-17 14:23:30.939  6291  6364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-17 14:23:30.939  6291  6344 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 14:23:30.939  6291  6344 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c881c3c not in the list
08-17 14:23:30.939  6291  6344 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:23:30.939  6291  6344 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:23:30.939  6291  6344 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:23:30.939  6291  6344 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:30.939  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.939  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.939  6291  6344 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f71de2f not in the list
08-17 14:23:30.939  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:30.939  6291  6344 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c881c3c not in the list
08-17 14:23:30.939  6291  6344 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:23:30.939  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.939  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.939  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.939  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.949  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:23:30.949  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:23:30.949  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 14:23:30.949  6291  6344 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c881c3c not in the list
08-17 14:23:30.949  6291  6291 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 14:23:30.949  6291  6291 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 14:23:30.949  6291  6291 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-17 14:23:30.949  6291  6291 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 14:23:30.949  6291  6344 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-17 14:23:30.949  6291  6344 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-17 14:23:30.949  6291  6344 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 14:23:30.949  6291  6344 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 14:23:30.949  6291  6344 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:23:30.949  6291  6344 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:23:30.949  6291  6344 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:23:30.949  6291  6344 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:30.949  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.949  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.949  6291  6344 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f71de2f not in the list
08-17 14:23:30.949  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:30.949  6291  6344 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c881c3c not in the list
08-17 14:23:30.949  6291  6344 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:23:30.949  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.949  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.949  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.949  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.949  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:23:30.949  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:23:30.949  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:30.949  6291  6344 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c881c3c not in the list
08-17 14:23:30.949  6291  6344 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:23:30.949  6291  6344 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:23:30.949  6291  6344 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:23:30.949  6291  6344 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:30.949  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.949  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.949  6291  6344 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f71de2f not in the list
08-17 14:23:30.949  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:30.949  6291  6344 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c881c3c not in the list
08-17 14:23:30.949  6291  6344 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:23:30.949  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.949  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.949  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.949  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.949  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:23:30.949  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:23:30.949  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:30.949  6291  6344 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c881c3c not in the list
08-17 14:23:30.949  6291  6344 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:23:30.949  6291  6344 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:23:30.949  6291  6344 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:23:30.959  6291  6344 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:30.959  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.959  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.959  6291  6344 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f71de2f not in the list
08-17 14:23:30.959  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:30.959  6291  6344 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c881c3c not in the list
08-17 14:23:30.959  6291  6344 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:23:30.959  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.959  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.959  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:30.959  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:30.959  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:23:30.959  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:23:30.959  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:30.959  6291  6344 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c881c3c not in the list
08-17 14:23:30.959  6291  6344 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-17 14:23:30.959  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 14:23:30.959  6291  6344 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-17 14:23:30.959  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 14:23:30.959  6291  6344 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-17 14:23:30.959  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 14:23:30.959  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-17 14:23:30.959  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-17 14:23:30.959  6291  6344 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-17 14:23:30.959  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-17 14:23:30.959  6291  6344 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-17 14:23:30.959  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-17 14:23:30.959  6291  6344 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-17 14:23:30.959  6291  6344 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-17 14:23:30.959  6291  6344 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-17 14:23:30.959  6291  6344 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-17 14:23:30.959  6291  6344 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-17 14:23:30.959  6291  6344 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-17 14:23:30.959  6291  6344 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-17 14:23:30.959  6291  6344 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-17 14:23:30.959  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:23:30.959  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@29c7fcbe added. We now have 2 listener(s)
08-17 14:23:30.959  6291  6344 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:23:30.959  6291  6344 D BluetoothAdapter: enable()
08-17 14:23:30.959  6291  6344 D BluetoothAdapter: enable(): BT is already enabled..!
08-17 14:23:30.969  1017  1483 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-17 14:23:30.969  1017  1483 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-17 14:23:30.969  1017  1483 D SecContentProvider2: mCursor = null
08-17 14:23:30.969  1017  1483 D WifiService: setWifiEnabled: true pid=6291, uid=10155
08-17 14:23:30.969  1017  1483 W ActivityManager: Permission Denial: getCurrentUser() from pid=6291, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-17 14:23:30.969  1017  1483 W WifiService: Failed getting userId using ActivityManagerNative
08-17 14:23:30.969  1017  1483 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6291, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-17 14:23:30.969  1017  1483 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-17 14:23:30.969  1017  1483 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-17 14:23:30.969  1017  1483 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-17 14:23:30.969  1017  1483 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-17 14:23:30.969  1017  1483 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-17 14:23:30.969  1017  1483 D SettingsProvider: name = wifi_on
08-17 14:23:30.969  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:23:30.969  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@321cb11f added. We now have 3 listener(s)
08-17 14:23:30.969  6291  6344 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:23:30.969  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:23:30.969  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@31290c6c added. We now have 4 listener(s)
08-17 14:23:30.969  6291  6344 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:23:30.979  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:23:30.979  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@37cb6235 added. We now have 5 listener(s)
08-17 14:23:30.979  6291  6344 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:23:30.979  1017  1030 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-17 14:23:30.979  1017  1030 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-17 14:23:30.979  1017  1030 D SecContentProvider2: mCursor = null
08-17 14:23:30.979  1017  1030 D WifiService: setWifiEnabled: false pid=6291, uid=10155
08-17 14:23:30.979  1017  1030 D SettingsProvider: name = wifi_on
08-17 14:23:30.979  1017  1129 E WifiStateMachine: WifiStateMachine: Leaving Connected state,
08-17 14:23:30.979  2099  2099 I wpa_supplicant: reset timer : RESET_TIMER 0
08-17 14:23:30.979  2099  2099 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-17 14:23:30.989  2099  2099 I wpa_supplicant: P2P: Current p2p state = IDLE
08-17 14:23:30.989  2099  2099 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-17 14:23:30.989  6291  6344 D BluetoothAdapter: disable()
,08-17 14:23:30.989  1017  1129 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 14:23:30.989  1017  1344 D SettingsProvider: name = bluetooth_on
,08-17 14:23:30.989  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 14:23:30.999  2658  2717 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
08-17 14:23:30.999  2658  2717 D BluetoothAdapterProperties: Setting state to 13
08-17 14:23:30.999  2658  2717 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-17 14:23:30.999  1017  1505 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 14:23:30.999  2658  2717 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-17 14:23:30.999  1017  1505 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-17 14:23:30.999  2658  2717 D BluetoothAdapterService: updateAdapterState state is 13
08-17 14:23:30.999  1017  1129 E WifiNative-wlan0: do suspend true
,08-17 14:23:30.999  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:23:30.999  6291  6344 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:23:30.999  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:30.999  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:30.999  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:23:30.999  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:23:30.999  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:23:30.999  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:23:30.999  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 14:23:30.999  1017  1505 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:30.999  1017  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:30.999  1017  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:30.999  2658  2658 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13,
08-17 14:23:30.999  2658  2717 D BluetoothAdapterService: Autoconnection is available 
08-17 14:23:30.999  2658  2717 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
,08-17 14:23:30.999  2658  2717 D BluetoothAdapterService: terminating service from this receiver
08-17 14:23:30.999  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-17 14:23:30.999  2658  2658 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3dcf2455, channel: 19, state: LISTENING
08-17 14:23:30.999  1017  1017 I InputMethodManagerService: [BT Setting State] State =13
08-17 14:23:30.999  2658  2658 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3dcf2455, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@265be9d, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1d028e6amSocket: android.net.LocalSocket@31771f5b impl:android.net.LocalSocketImpl@36a843f8 fd:FileDescriptor[74]
08-17 14:23:30.999  2658  2658 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@31771f5b impl:android.net.LocalSocketImpl@36a843f8 fd:FileDescriptor[74]
08-17 14:23:31.009  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:23:31.009  6291  6344 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 14:23:31.009  6291  6344 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 14:23:31.009  6291  6291 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:23:31.009  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:23:31.009  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:31.009  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:31.009  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:23:31.009  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:23:31.009  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:23:31.009  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:23:31.009  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 14:23:31.009  6291  6291 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:23:31.009  6291  6291 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 14:23:31.009  1181  1181 D BluetoothTile:  onBluetoothStateChange:
,08-17 14:23:31.019  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:31.019  1797  1797 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
08-17 14:23:31.019  1181  1181 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-17 14:23:31.019  1181  1181 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:23:31.019  1181  1181 D BluetoothTile:  getBluetoothState : 13
,08-17 14:23:31.019  1181  1712 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 14:23:31.029  1181  1712 D BluetoothTile:  handleUpdatestate:false name:null
08-17 14:23:31.029  1323  1323 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 14:23:31.029  1017  3205 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 14:23:31.029  1017  1483 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-17 14:23:31.029  1181  1181 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-17 14:23:31.029  1181  1712 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-17 14:23:31.029  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-17 14:23:31.029  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:31.029  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:31.029  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 14:23:31.029  6291  6291 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:23:31.029  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:23:31.029  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:31.029  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:31.029  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:23:31.029  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:23:31.029  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:23:31.029  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true,
08-17 14:23:31.029  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 14:23:31.029  2658  2717 D BluetoothAdapterProperties: onBluetoothDisable()
08-17 14:23:31.029  2658  2717 D BluetoothAdapterProperties: mDiscovering is false
08-17 14:23:31.029  1017  1505 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 14:23:31.029  1017  1505 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-17 14:23:31.039  2658  2658 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@142ab0d1, channel: 5, state: LISTENING
08-17 14:23:31.039  2658  2658 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@142ab0d1, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@fd42f12, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2ab32736mSocket: android.net.LocalSocket@dfe5637 impl:android.net.LocalSocketImpl@1919a7a4 fd:FileDescriptor[76]
08-17 14:23:31.039  2658  2658 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@dfe5637 impl:android.net.LocalSocketImpl@1919a7a4 fd:FileDescriptor[76]
,08-17 14:23:31.039  2658  2658 I BtOppRfcommListener: stopping Accept Thread
08-17 14:23:31.039  2658  2658 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@dd8890d, channel: 12, state: LISTENING
08-17 14:23:31.039  2658  2658 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@dd8890d, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@cf8030c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2c0280c2mSocket: android.net.LocalSocket@18581ed3 impl:android.net.LocalSocketImpl@211b9a10 fd:FileDescriptor[79]
08-17 14:23:31.039  2658  2658 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@18581ed3 impl:android.net.LocalSocketImpl@211b9a10 fd:FileDescriptor[79]
08-17 14:23:31.039  2658  5004 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-17 14:23:31.039  2658  5004 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-17 14:23:31.039  6291  6291 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:23:31.039  1017  1079 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-17 14:23:31.039  6291  6291 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 14:23:31.039  2658  2717 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-17 14:23:31.039  1017  1505 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:31.039  1017  1505 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 14:23:31.039  1017  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 14:23:31.039  1323  1323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 14:23:31.039  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:31.049  1017  1531 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-17 14:23:31.049  1017  1531 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:31.049  1017  1531 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
08-17 14:23:31.049  1017  1531 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:31.049  1017  1531 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-17 14:23:31.049  1323  1323 D BluetoothPbap: Proxy object disconnected
08-17 14:23:31.049  1323  1323 D PbapServerProfile: Bluetooth service disconnected
,08-17 14:23:31.059  2658  2722 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-17 14:23:31.059  2658  2722 D BluetoothAdapterProperties: Scan Mode:20
,08-17 14:23:31.059  2658  2717 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-17 14:23:31.059  2658  2717 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-17 14:23:31.059  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:23:31.059  1323  1323 D DockEventReceiver: finishStartingService: stopping service
,08-17 14:23:31.059  2658  2717 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
08-17 14:23:31.059  2658  2717 E bt-btif : cmd socket is not created
08-17 14:23:31.059  2658  2838 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-17 14:23:31.059  2658  2838 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-17 14:23:31.059  2658  2717 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-17 14:23:31.069  1323  1323 D BluetoothNotiBroadcastReceiver: onReceive
08-17 14:23:31.069  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:23:31.069  6291  6362 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1ee5403b, channel: -1, state: INIT
08-17 14:23:31.069  6291  6362 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1ee5403b, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@29d08358, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3dcecb1mSocket: android.net.LocalSocket@3714e596 impl:android.net.LocalSocketImpl@39dda517 fd:FileDescriptor[108]
08-17 14:23:31.069  6291  6362 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3714e596 impl:android.net.LocalSocketImpl@39dda517 fd:FileDescriptor[108]
08-17 14:23:31.069  6291  6362 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1142)
08-17 14:23:31.069  2658  2838 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 14:23:31.069  2658  2838 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 14:23:31.069  2658  2838 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-17 14:23:31.079  1181  1181 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:23:31.079  1181  1181 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-17 14:23:31.079  1017  1485 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-17 14:23:31.079  1017  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 14:23:31.079  1017  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:31.079  1017  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:31.079  1017  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 14:23:31.099  6370  6370 E Zygote  : MountEmulatedStorage(),
08-17 14:23:31.099  6370  6370 E Zygote  : v2
08-17 14:23:31.099  6370  6370 I libpersona: KNOX_SDCARD checking this for 10003
,08-17 14:23:31.099  6370  6370 I libpersona: KNOX_SDCARD not a persona
,08-17 14:23:31.099  6370  6370 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-17 14:23:31.099  6370  6370 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-17 14:23:31.099  1017  1485 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6370 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
08-17 14:23:31.099  2658  2658 V BluetoothOppManager: cleanUp...
,08-17 14:23:31.109  6370  6370 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 14:23:31.139  6370  6370 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 14:23:31.139  6370  6370 D ActivityThread: Added TimaKeyStore provider
,08-17 14:23:31.159  2099  2099 I wpa_supplicant: nl80211: Received scan results (21 BSSes)
,08-17 14:23:31.169  1017  1128 D WifiP2pService: InactiveState{ what=147461 }
,08-17 14:23:31.169   278   986 D CommandListener: Clearing all IP addresses on wlan0
,08-17 14:23:31.169  1934  4496 V NativeCrypto: Read error: ssl=0xb8250820: I/O error during system call, Connection timed out
,08-17 14:23:31.169  1017  1128 D WifiP2pService: P2pEnabledState{ what=147461 }
08-17 14:23:31.169  1017  1128 D WifiP2pService: DefaultState{ what=147461 }
08-17 14:23:31.169  1017  1128 D WifiP2pService: InactiveState{ what=143375 }
08-17 14:23:31.169  1017  1128 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-17 14:23:31.179  1017  1131 E ConnectivityService: updateNetworkInfo(),
08-17 14:23:31.179  1017  1131 E ConnectivityService: updateNetworkInfo()
08-17 14:23:31.179  1017  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 14:23:31.179  1017  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,08-17 14:23:31.179  1181  1181 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 14:23:31.179  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-17 14:23:31.179  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:31.179  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:31.179  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:31.179  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:31.179  1934  4496 V NativeCrypto: SSL shutdown failed: ssl=0xb8250820: I/O error during system call, Broken pipe
,08-17 14:23:31.179  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-17 14:23:31.179  6370  6370 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-17 14:23:31.179  1934  4496 E GCM     : Wifi connection closed with errorCode 20
,08-17 14:23:31.179  1017  3205 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,08-17 14:23:31.189  1017  2219 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:23:31.189  1017  2219 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:23:31.189  1017  2219 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-17 14:23:31.189  1017  2219 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:23:31.189  1017  2219 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,08-17 14:23:31.189  1017  2219 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 14:23:31.189  1017  2219 I qtaguid : Tagging socket 361 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1017, getuid(): 1000
,08-17 14:23:31.199  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 14:23:31.199  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 14:23:31.199  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 14:23:31.199  1017  1128 D WifiP2pService: InactiveState{ what=131204 }
08-17 14:23:31.199  1017  1128 D WifiP2pService: P2pEnabledState{ what=131204 }
,08-17 14:23:31.199  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 1
08-17 14:23:31.199  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:31.199  1017  1152 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:23:31.199  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:31.199  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 14:23:31.199  1017  2219 I qtaguid : Untagging socket 361
,08-17 14:23:31.199  1017  2219 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-17 14:23:31.199  1017  1128 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-17 14:23:31.199  1017  1017 D RttService: SCAN_AVAILABLE : 1
,08-17 14:23:31.199  1017  1153 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-17 14:23:31.209  1017  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-17 14:23:31.209  1017  1048 D WifiDisplayAdapter: onP2pDisconnected
,08-17 14:23:31.209  1017  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-17 14:23:31.209  1017  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
08-17 14:23:31.209  1017  1129 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-17 14:23:31.209  1017  1128 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-17 14:23:31.209  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-17 14:23:31.209  1017  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-17 14:23:31.209  1017  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-17 14:23:31.209  1017  1048 D WifiDisplayController: disconnect
08-17 14:23:31.209  1017  1048 D WifiDisplayController: updateConnection
08-17 14:23:31.209  1017  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-17 14:23:31.209  1017  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-17 14:23:31.219  1017  1128 D WifiP2pService: P2pDisablingState
,08-17 14:23:31.219  1017  1128 D WifiP2pService: P2pDisablingState{ what=147458 }
08-17 14:23:31.219  1017  1128 D WifiP2pService: p2p socket connection lost
08-17 14:23:31.219  1017  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-17 14:23:31.219  1017  1048 D WifiDisplayAdapter: onP2pDisconnected
08-17 14:23:31.219  1017  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-17 14:23:31.219  1017  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
08-17 14:23:31.219  1017  1128 D WifiP2pService: P2pDisabledState
,08-17 14:23:31.219  1017  1129 E WifiNative-wlan0: do suspend true
,08-17 14:23:31.219  6370  6370 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-17 14:23:31.219  6370  6370 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-17 14:23:31.219  6370  6370 D UserAnalysis: Create SecureDbHelper
08-17 14:23:31.219  1181  1181 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-17 14:23:31.219  1017  1344 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-17 14:23:31.219  1181  1181 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-17 14:23:31.229  6370  6370 D IntelligenceServiceApplication: onCreate()
,08-17 14:23:31.229  1017  1030 I ActivityManager: Killing 5040:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,08-17 14:23:31.239  6370  6370 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-17 14:23:31.239  1017  2745 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0,
08-17 14:23:31.239  6370  6370 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-17 14:23:31.239  1017  1485 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-17 14:23:31.239  1017  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 14:23:31.239  1017  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:31.239  1017  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:31.239  1017  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 14:23:31.249  6370  6370 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-17 14:23:31.259  6393  6393 E Zygote  : MountEmulatedStorage(),
08-17 14:23:31.259  6393  6393 E Zygote  : v2
08-17 14:23:31.259  6393  6393 I libpersona: KNOX_SDCARD checking this for 10107
08-17 14:23:31.259  6393  6393 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-17 14:23:31.259  6393  6393 I libpersona: KNOX_SDCARD not a persona
,08-17 14:23:31.259  1017  1485 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6393 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-17 14:23:31.259  2658  2838 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 14:23:31.259  2658  2934 I bt_userial_mct: exiting userial_read_thread
08-17 14:23:31.259  2658  2934 D bt_userial_mct: Leaving userial_evt_read_thread(),
08-17 14:23:31.259  2658  2838 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 14:23:31.259  2658  2838 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 14:23:31.259  2658  2838 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 14:23:31.259  2658  2838 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 14:23:31.259  2658  2838 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-17 14:23:31.259  2658  2838 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 14:23:31.259  2658  2838 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 14:23:31.259  6393  6393 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-17 14:23:31.259  2658  2838 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 14:23:31.259  2658  2838 W bt-btif : ag scb idx 1 not allocated
,08-17 14:23:31.259  2658  2838 W bt-btif : ag scb idx 2 not allocated
08-17 14:23:31.259  2658  2838 E bt-btif : BTA AG is already disabled, ignoring ...
08-17 14:23:31.259  2658  2722 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-17 14:23:31.259  2658  2840 I bt_vendor: hw_epilog_process
08-17 14:23:31.259  2658  2722 D bt_userial_mct: userial_close
08-17 14:23:31.259  2658  2722 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-17 14:23:31.269  6393  6393 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-17 14:23:31.279  6393  6393 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 14:23:31.289  6393  6393 D ActivityThread: Added TimaKeyStore provider
,08-17 14:23:31.349  1017  1128 D WifiP2pService: P2pDisabledState{ what=143375 },
08-17 14:23:31.349  1017  1128 D WifiP2pService: DefaultState{ what=143375 }
,08-17 14:23:31.359  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 14:23:31.359  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
08-17 14:23:31.359  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:31.359  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:31.359  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:31.359  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,08-17 14:23:31.359   278   980 D EnterpriseController: uids 1000,
08-17 14:23:31.359   278   980 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-17 14:23:31.369  1017  1131 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-17 14:23:31.359   278   980 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-17 14:23:31.369  1017  1131 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
08-17 14:23:31.369   278   986 D CommandListener: Clearing all IP addresses on wlan0
,08-17 14:23:31.369  1181  1697 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-17 14:23:31.369  1017  1047 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false,
08-17 14:23:31.369  1017  1131 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 14:23:31.369  1459  1459 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-17 14:23:31.369  1017  1131 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-17 14:23:31.369  1017  1128 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-17 14:23:31.369  1017  1131 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-17 14:23:31.369  1459  1459 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 14:23:31.369  1017  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-17 14:23:31.369  1017  2219 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
08-17 14:23:31.369  1017  2219 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-17 14:23:31.369  1017  2219 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,08-17 14:23:31.369  2099  2099 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-17 14:23:31.369  3852  6213 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,08-17 14:23:31.379  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-17 14:23:31.379  1017  1017 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,08-17 14:23:31.389  1017  1131 D ConnectivityService: nai.networkMonitor.doQuit()
08-17 14:23:31.389  1017  1131 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-17 14:23:31.389  1017  1133 D Tethering: MasterInitialState.processMessage what=3
08-17 14:23:31.389  1017  1131 E ConnectivityService: updateNetworkInfo()
08-17 14:23:31.389  1017  1131 E ConnectivityService: updateNetworkInfo()
08-17 14:23:31.389  1017  1131 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-17 14:23:31.389  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 14:23:31.389  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 14:23:31.389  1017  1126 V NetworkStats: updateIfacesLocked()
08-17 14:23:31.389  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:31.389  1017  1126 V NetworkStats: performPollLocked(flags=0x1)
08-17 14:23:31.389  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:31.389  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:31.389  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:31.389  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 14:23:31.389  1017  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 14:23:31.389  1017  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 14:23:31.389  1017  1047 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-17 14:23:31.389  1181  1181 D StatusBar.NetworkController: EthernetConnected: false
08-17 14:23:31.389  1181  1181 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-17 14:23:31.389  1181  1181 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-17 14:23:31.389  1181  1181 D StatusBar.NetworkController: updateDataNetType()
08-17 14:23:31.389  1181  1181 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-17 14:23:31.389  1181  1181 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-17 14:23:31.389  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 14:23:31.389  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 14:23:31.389  1017  1129 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-17 14:23:31.389  1017  1126 V NetworkStats: performPollLocked() took 8ms
08-17 14:23:31.389  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 14:23:31.389  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 14:23:31.389  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 14:23:31.389  1017  1127 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,08-17 14:23:31.399  1017  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 14:23:31.399  1017  1129 D SecContentProvider2: mCursor = null
,08-17 14:23:31.399  1181  1181 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,08-17 14:23:31.399  1181  1181 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-17 14:23:31.399  1181  1181 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,08-17 14:23:31.399  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 14:23:31.399  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 14:23:31.399  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:31.399  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:31.399  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:31.399  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 14:23:31.399  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 14:23:31.399  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-17 14:23:31.399  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:31.399  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:31.399  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:31.399  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:31.399  1181  1181 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 14:23:31.399  1181  1181 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-17 14:23:31.399  1181  1712 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-17 14:23:31.409  1181  1181 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-17 14:23:31.409  1181  1181 D HotspotTile: onReceive : 0, 0
,08-17 14:23:31.409  1323  1323 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-17 14:23:31.409  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 14:23:31.419  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 14:23:31.419  6291  6291 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 14:23:31.419  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:23:31.419  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:31.419  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:31.419  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:23:31.419  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:23:31.419  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:23:31.419  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:23:31.419  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 14:23:31.429  6291  6291 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 14:23:31.429  6291  6291 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 14:23:31.429  6291  6291 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:23:31.429  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:23:31.429  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:31.429  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:31.429  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:23:31.429  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:23:31.429  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:23:31.429  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:23:31.429  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 14:23:31.429  6291  6291 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 14:23:31.429  6291  6291 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 14:23:31.449  6291  6291 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 14:23:31.459  2658  2722 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-17 14:23:31.459  2658  2722 I bt_vendor: bluetooth satus is on
08-17 14:23:31.459  2658  2722 I bt_vendor: bt-vendor : resetting BT status
08-17 14:23:31.459  2658  2722 I bt_vendor: Starting hciattach daemon
08-17 14:23:31.459  2658  2722 I bt_vendor: try to set false
,08-17 14:23:31.459  2658  2722 I bt_vendor: Starting hciattach daemon
,08-17 14:23:31.459  2658  2722 I bt_vendor: try to set false
,08-17 14:23:31.459  2658  2722 I bt_vendor: cleanup
,08-17 14:23:31.459  2658  2838 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,08-17 14:23:31.459  2658  2722 I GKI_LINUX: GKI_exit_task 0 done
,08-17 14:23:31.459  2658  2722 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-17 14:23:31.459  2658  2717 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-17 14:23:31.459  2658  2717 D BtConfig.SecureMode: isSecureModeOn:false
,08-17 14:23:31.459  2658  2717 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-17 14:23:31.459  2658  2717 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-17 14:23:31.459  2658  2717 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-17 14:23:31.459  2658  2717 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-17 14:23:31.469  1017  1079 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 14:23:31.469  1017  1079 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-17 14:23:31.469  1017  1079 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:31.469  1017  1079 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 14:23:31.469  1017  1079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:31.469  2658  2717 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
,08-17 14:23:31.469  2658  2717 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-17 14:23:31.469  2658  2658 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 14:23:31.469  2658  2717 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-17 14:23:31.469  2658  2658 D BtGatt.GattService: Received stop request...Stopping profile...
08-17 14:23:31.469  2658  2658 D BtGatt.GattService: stop()
08-17 14:23:31.469  2658  2658 D BtGatt.AdvertiseManager: advertise clients cleared
,08-17 14:23:31.469  2658  2658 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@308adf9b
,08-17 14:23:31.469  1017  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 14:23:31.479  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-17 14:23:31.479  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:31.479  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:31.479  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:31.479  2658  2717 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,08-17 14:23:31.479  2658  2717 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-17 14:23:31.479  2658  2717 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-17 14:23:31.479  1017  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 14:23:31.479  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 14:23:31.479  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:31.479  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 14:23:31.479  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:31.479  2658  2717 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-17 14:23:31.479  2658  2717 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-17 14:23:31.489  2099  2099 I wpa_supplicant: Blacklist: Clear (all) 
,08-17 14:23:31.489  2658  2717 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-17 14:23:31.489  1017  3056 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 14:23:31.489  1017  3056 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-17 14:23:31.489  1017  3056 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:31.489  1017  3056 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:31.489  1017  3056 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:31.489  2658  2717 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-17 14:23:31.489  2658  2717 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-17 14:23:31.489  2658  2717 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-17 14:23:31.489  1017  1727 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 14:23:31.489  1017  1727 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-17 14:23:31.499  1017  1727 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:31.499  1017  1727 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:31.499  1017  1727 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:31.499  2658  2717 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-17 14:23:31.499  2658  2717 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-17 14:23:31.499  2658  2717 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-17 14:23:31.499  1017  1222 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 14:23:31.499  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-17 14:23:31.499  1017  1222 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-17 14:23:31.499  1017  1222 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:31.499  1017  1222 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:31.499  1017  1222 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:31.509  2658  2717 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-17 14:23:31.509  2658  2717 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-17 14:23:31.509  2658  2717 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-17 14:23:31.509  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-17 14:23:31.509  1017  1531 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 14:23:31.509  1017  1531 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-17 14:23:31.509  1017  1531 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:31.509  1017  1531 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:31.509  1017  1531 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 14:23:31.509  2658  2717 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-17 14:23:31.509  2658  2717 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-17 14:23:31.509  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 14:23:31.509  2658  2717 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-17 14:23:31.509  1017  1222 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 14:23:31.509  1017  1222 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-17 14:23:31.509  1017  1222 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:31.509  1017  1222 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:31.519  1017  1222 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:31.519  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 14:23:31.519  2658  2717 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-17 14:23:31.519  2658  2717 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-17 14:23:31.519  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-17 14:23:31.519  2658  2717 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-17 14:23:31.519  2658  2717 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-17 14:23:31.519  2658  2717 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-17 14:23:31.519  2658  2717 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,08-17 14:23:31.519  2658  2717 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-17 14:23:31.519  2658  2717 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-17 14:23:31.519  2658  2717 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-17 14:23:31.519  2658  2717 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-17 14:23:31.519  2658  2717 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-17 14:23:31.519  2658  2717 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-17 14:23:31.519  2658  2717 D BluetoothAdapterState: Stopping profile services that were post enabled
08-17 14:23:31.519  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-17 14:23:31.519  2658  2658 E BluetoothAdapterService(814407579): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
08-17 14:23:31.519  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-17 14:23:31.519  2658  2658 D HeadsetService: Received stop request...Stopping profile...
,08-17 14:23:31.519  2658  2658 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@308adf9b
,08-17 14:23:31.519  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 14:23:31.519  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-17 14:23:31.529  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-17 14:23:31.529  1323  1323 D HeadsetProfile: Bluetooth service disconnected
,08-17 14:23:31.529  2658  2658 D A2dpService: Received stop request...Stopping profile...
,08-17 14:23:31.529  2099  2099 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-17 14:23:31.529  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-17 14:23:31.529  2658  2765 D A2dpStateMachine: Exit Disconnected: -1
,08-17 14:23:31.529  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-17 14:23:31.529  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-17 14:23:31.529  2658  2658 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@308adf9b
,08-17 14:23:31.539  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 14:23:31.539  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 14:23:31.539  1017  1017 D BluetoothA2dp: Proxy object disconnected
08-17 14:23:31.539  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-17 14:23:31.539  2892  2892 D BluetoothA2dp: Proxy object disconnected
,08-17 14:23:31.539  2658  2658 D HidService: Received stop request...Stopping profile...
,08-17 14:23:31.539  2658  2658 D HidService: Stopping Bluetooth HidService
08-17 14:23:31.539  2658  2658 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-17 14:23:31.539  2658  2658 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-17 14:23:31.539  2658  2658 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-17 14:23:31.539  2658  2658 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@308adf9b
,08-17 14:23:31.549  1323  1323 D BluetoothA2dp: Proxy object disconnected
08-17 14:23:31.549  1323  1323 D A2dpProfile: Bluetooth service disconnected
08-17 14:23:31.549  1323  1323 D BluetoothInputDevice: Proxy object disconnected
08-17 14:23:31.549  1323  1323 D HidProfile: Bluetooth service disconnected
08-17 14:23:31.549  2658  2658 D HealthService: Received stop request...Stopping profile...
08-17 14:23:31.549  2658  2658 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@308adf9b
08-17 14:23:31.549  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-17 14:23:31.549  2658  2658 D PanService: Received stop request...Stopping profile...
08-17 14:23:31.549  2658  2658 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@308adf9b
08-17 14:23:31.549  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-17 14:23:31.549  1017  1017 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-17 14:23:31.559  2099  2099 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,08-17 14:23:31.559  2099  2099 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-17 14:23:31.559  2099  2099 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
,08-17 14:23:31.559  2099  2099 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-17 14:23:31.559  2099  2099 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-17 14:23:31.559  2658  2658 D BluetoothMapService: Received stop request...Stopping profile...
08-17 14:23:31.559  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 14:23:31.559  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
08-17 14:23:31.559  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 14:23:31.559  1017  1133 D Tethering: InitialState.processMessage what=4
08-17 14:23:31.559  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-17 14:23:31.559  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 14:23:31.559  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 14:23:31.559  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 14:23:31.559  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 14:23:31.559  1017  1129 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14956 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
08-17 14:23:31.559  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
08-17 14:23:31.559  1017  1133 E Tethering: No numeric data
,08-17 14:23:31.559  2658  2658 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@308adf9b
08-17 14:23:31.569  2658  2658 D SapService: Received stop request...Stopping profile...
08-17 14:23:31.569  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-17 14:23:31.569  1017  1133 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-17 14:23:31.569  1017  1133 D Tethering: clearTetheredNotification()
08-17 14:23:31.569  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-17 14:23:31.569  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-17 14:23:31.569  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 14:23:31.569  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
08-17 14:23:31.569  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-17 14:23:31.569  2658  2658 D SapService: Stopping Bluetooth SapService
08-17 14:23:31.569  2658  2658 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@308adf9b
,08-17 14:23:31.569  1017  1126 V NetworkStats: performPollLocked(flags=0x1)
08-17 14:23:31.569  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 14:23:31.569  1323  1323 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-17 14:23:31.569  1323  1323 D PanProfile: Bluetooth service disconnected
08-17 14:23:31.569  1323  1323 D BluetoothMap: Proxy object disconnected
,08-17 14:23:31.569  1323  1323 D MapProfile: Bluetooth service disconnected
,08-17 14:23:31.569  1017  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 14:23:31.569  1017  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 14:23:31.569  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-17 14:23:31.569  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 14:23:31.569  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
08-17 14:23:31.569  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 14:23:31.569  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-17 14:23:31.569  1181  1181 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-17 14:23:31.569  1181  1181 D HotspotTile: updateTetherState():false, false
,08-17 14:23:31.579  1323  1323 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-17 14:23:31.579  1017  1126 V NetworkStats: performPollLocked() took 7ms
08-17 14:23:31.579  2658  2658 E BluetoothAdapterService(814407579): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-17 14:23:31.579  2658  2658 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-17 14:23:31.579  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 14:23:31.579  2658  2658 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-17 14:23:31.579  1323  1323 D SapProfile: Bluetooth service disconnected
,08-17 14:23:31.579  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-17 14:23:31.579  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 14:23:31.579  2658  2658 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-17 14:23:31.579  2658  2658 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-17 14:23:31.579  2658  2658 E BluetoothAdapterService(814407579): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-17 14:23:31.579  2658  2658 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-17 14:23:31.579  2658  2658 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-17 14:23:31.579  2658  2658 D BluetoothA2dp: Proxy object disconnected
08-17 14:23:31.579  2658  2658 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-17 14:23:31.579  2658  2766 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-17 14:23:31.579  2658  2658 I GKI_LINUX: GKI_exit_task 2 done
08-17 14:23:31.579  2658  2658 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-17 14:23:31.579  2658  2658 E BluetoothAdapterService(814407579): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-17 14:23:31.579  2658  2658 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 14:23:31.579  2658  2658 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-17 14:23:31.579  2658  2658 E BluetoothAdapterService(814407579): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-17 14:23:31.579  2658  2658 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 14:23:31.579  2658  2658 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-17 14:23:31.579  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-17 14:23:31.579  2658  2658 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-17 14:23:31.579  2658  2658 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-17 14:23:31.579  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 14:23:31.579  2658  2658 E BluetoothAdapterService(814407579): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-17 14:23:31.579  2658  2658 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 14:23:31.579  2658  2658 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-17 14:23:31.579  2658  2658 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-17 14:23:31.579  2658  2658 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-17 14:23:31.579  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 14:23:31.579  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 14:23:31.589  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-17 14:23:31.589  2658  2658 E BluetoothAdapterService(814407579): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,08-17 14:23:31.589  2658  2658 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-17 14:23:31.589  2658  2658 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-17 14:23:31.589  2658  2658 E BluetoothAdapterService(814407579): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,08-17 14:23:31.589  2658  2658 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
,08-17 14:23:31.589  2658  2658 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-17 14:23:31.589  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 14:23:31.589  2658  2717 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-17 14:23:31.589  2658  2717 D BluetoothAdapterProperties: Setting state to 10
08-17 14:23:31.589  2658  2717 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-17 14:23:31.589  2658  2717 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-17 14:23:31.589  2658  2717 D BluetoothAdapterService: updateAdapterState state is 10
08-17 14:23:31.589  1017  1047 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 14:23:31.589  1017  1047 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 14:23:31.589  2658  2717 D BluetoothAdapterService: Autoconnection is available 
,08-17 14:23:31.589  2658  2717 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-17 14:23:31.589  2658  2717 I BluetoothAdapterState: Entering OffState
08-17 14:23:31.589  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 14:23:31.589  1446  1466 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 14:23:31.589  1446  1466 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 14:23:31.589  2658  3052 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 14:23:31.589  1017  1343 D ActivityManager: bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
08-17 14:23:31.589  2658  3052 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-17 14:23:31.589  1017  1343 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
08-17 14:23:31.589  1436  2754 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 14:23:31.589  1436  2754 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-17 14:23:31.599  1017  1343 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:31.599  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-17 14:23:31.599  1017  1343 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 14:23:31.599  1017  1343 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-17 14:23:31.599  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 14:23:31.599  6291  6299 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 14:23:31.599  6291  6299 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 14:23:31.599  6291  6299 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-17 14:23:31.599  6291  6299 D BluetoothLeAdvertiser: Exit stop advertising
08-17 14:23:31.599  6291  6299 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-17 14:23:31.599  6291  6299 D BluetoothLeScanner: Exiting stopAllScan
08-17 14:23:31.599  1934  1934 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-17 14:23:31.599  1323  1336 D Bluetoothsap: onBluetoothStateChange: up=false
08-17 14:23:31.599  1323  1336 D Bluetoothsap: Unbinding service...
,08-17 14:23:31.599  1459  1469 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 14:23:31.609  1459  1469 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 14:23:31.609  1934  1934 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-17 14:23:31.609  2658  2668 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-17 14:23:31.609  1323  1335 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 14:23:31.609  1323  1335 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 14:23:31.609  1323  1336 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-17 14:23:31.609  1934  1949 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 14:23:31.609  1934  1949 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 14:23:31.609   272   272 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb74aa7c8
08-17 14:23:31.609   272   272 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
08-17 14:23:31.609   272   272 I rmt_storage: wakelock acquired: 1, error no: 42
08-17 14:23:31.619   272   306 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1219844808)
08-17 14:23:31.619  1323  1335 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-17 14:23:31.629  1017  1047 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 14:23:31.629  1323  1336 D BluetoothPbap: onBluetoothStateChange: up=false
08-17 14:23:31.629  2892  2900 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 14:23:31.629  2892  2900 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-17 14:23:31.629  2892  2914 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 14:23:31.629  1181  1213 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 14:23:31.629  1181  1213 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 14:23:31.629  1323  1335 D BluetoothMap: onBluetoothStateChange: up=false
,08-17 14:23:31.639  1017  1047 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-17 14:23:31.639  1017  1047 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-17 14:23:31.649  6393  6393 D StrictMode: StrictMode policy violation; ~duration=318 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 14:23:31.649  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-17 14:23:31.649  6393  6393 D StrictMode: StrictMode policy violation; ~duration=311 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
08-17 14:23:31.649  63,93  6393 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 14:23:31.649  1017  1017 I InputMethodManagerService: [BT Setting State] State =10
08-17 14:23:31.649  6393  6393 D StrictMode: StrictMode policy violation; ~duration=223 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at java.io.File.exists(File.java:363)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-17 14:23:31.649  6393  6393 D StrictMode: ,	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
,08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 14:23:31.649  1017  1017 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-17 14:23:31.649  6393  6393 D StrictMode: StrictMode policy violation; ~duration=222 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150),
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 14:23:31.649  6393  6393 D StrictMode: StrictMode policy violation; ~duration=219 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 14:23:31.6,49  6393  6393 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 14:23:31.649  6393  6393 D StrictMode: StrictMode policy violation; ~duration=217 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.r.k.c(PG:1187)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:23)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.r.v.a(PG:1206)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.r.y.a(PG:2233)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.r.e.b(PG:170)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.r.e.b(PG:13188)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-17 14:23:31.649  6393  6393 D StrictMode: 	,at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 14:23:31.659  1181  1181 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-17 14:23:31.649  6393  6393 D StrictMode: StrictMode policy violation; ~duration=215 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.r.k.c(PG:1187)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.r.k.b(PG:14147)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.r.k.c(PG:583)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:40)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.r.v.a(PG:1206)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.r.y.a(PG:2233)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.r.e.b(PG:170)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.r.e.b(PG:13188)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
,08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 14:23:31.659  1181  1181 D BluetoothTile:  getBluetoothState : 10
08-17 14:23:31.649  6393  6393 D StrictMode: StrictMode policy violation; ~duration=183 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at java.io.File.doAccess(File.java:283)
,08-17 14:23:31.649  6393  6393 D StrictMode: 	at java.io.File.exists(File.java:363)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 14:23:31.649  6393  6393 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 14:23:31.669  1017  1483 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 14:23:31.659  1181  1181 D BluetoothAdapter: 490535640: getState() :  mService = null. Returning STATE_OFF
08-17 14:23:31.669  1017  1505 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-17 14:23:31.659  1181  1712 D BluetoothAdapter: 490535640: getState() :  mService = null. Returning STATE_OFF
08-17 14:23:31.659  1181  1181 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:23:31.659  1181  1712 D BluetoothAdapter: 490535640: getState() :  mService = null. Returning STATE_OFF
08-17 14:23:31.659  1181  1181 D BluetoothAdapter: 490535640: getState() :  mService = null. Returning STATE_OFF
08-17 14:23:31.659  1181  1181 D BluetoothAdapter: 490535640: getState() :  mService = null. Returning STATE_OFF
08-17 14:23:31.669  1181  1181 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-17 14:23:31.669  1797  1797 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
08-17 14:23:31.669  1323  1323 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:23:31.669  1934  2129 D BluetoothAdapter: 662714400: getState() :  mService = null. Returning STATE_OFF
08-17 14:23:31.669  1934  2129 D BluetoothAdapter: 662714400: getState() :  mService = null. Returning STATE_OFF
,08-17 14:23:31.669  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:31.669  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:23:31.669  2658  2722 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-17 14:23:31.669  1017  3056 I ActivityManager: Killing 5504:com.google.android.partnersetup/u0a15 (adj 15): empty #31
08-17 14:23:31.669  2658  2658 I GKI_LINUX: GKI_exit_task 1 done
08-17 14:23:31.669  2658  2658 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-17 14:23:31.679  2658  2658 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-17 14:23:31.679   272   306 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
08-17 14:23:31.679  1017  1344 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-17 14:23:31.679   272   306 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
08-17 14:23:31.679   272   306 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1219844808) wakelock released: 1, error no: 0
08-17 14:23:31.679   272   306 I rmt_storage: 
08-17 14:23:31.679  2658  2658 I art     : System.exit called, status: 0
08-17 14:23:31.679  2658  2658 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-17 14:23:31.679   272   272 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb74aa7c8
08-17 14:23:31.689  1017  1344 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:31.689  1017  1344 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 14:23:31.689  1017  1344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 14:23:31.689  1017  3207 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 14:23:31.689  1017  3207 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-17 14:23:31.689  1017  3207 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:31.689  1017  3207 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 14:23:31.689  1017  3207 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 14:23:31.689  1934  1934 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-17 14:23:31.709  1934  1934 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-17 14:23:31.719  2099  2099 I wpa_supplicant: Blacklist: Clear (all) 
08-17 14:23:31.719  1017  1029 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 14:23:31.719  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-17 14:23:31.719  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:31.719  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:31.719  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 14:23:31.719  3670  3670 I Hs20UtilService: Starting #8
,08-17 14:23:31.719  6393  6412 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-17 14:23:31.719  1323  1323 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-17 14:23:31.719  1323  1323 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-17 14:23:31.719  3670  3711 I Hs20UtilService: Message received 5007
,08-17 14:23:31.719  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-17 14:23:31.729  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-17 14:23:31.729  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 14:23:31.729  1323  1323 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-17 14:23:31.729  1323  3116 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 14:23:31.729  1323  1323 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-17 14:23:31.729  1323  1323 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-17 14:23:31.729  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-17 14:23:31.739  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-17 14:23:31.739  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 14:23:31.739  1323  1323 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-17 14:23:31.739  1323  3116 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-17 14:23:31.739  1017  1079 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-17 14:23:31.739  1017  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:31.739  1017  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:31.739  1017  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:31.739  1017  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 14:23:31.769  6441  6441 E Zygote  : MountEmulatedStorage()
08-17 14:23:31.769  1017  1079 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6441 uid=10068 gids={50068, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-17 14:23:31.769  6441  6441 E Zygote  : v2
08-17 14:23:31.769  6441  6441 I libpersona: KNOX_SDCARD checking this for 10068
08-17 14:23:31.769  6441  6441 I libpersona: KNOX_SDCARD not a persona
,08-17 14:23:31.769  6441  6441 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-17 14:23:31.769  6441  6441 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-17 14:23:31.769  6441  6441 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 14:23:31.789  6441  6441 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 14:23:31.789  6441  6441 D ActivityThread: Added TimaKeyStore provider
,08-17 14:23:31.789  1017  1030 I ActivityManager: Process com.android.bluetooth (pid 2658)(adj 0) has died(41,1091)
,08-17 14:23:31.829  2099  2099 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-17 14:23:31.829  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 14:23:31.829  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
08-17 14:23:31.829  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-17 14:23:31.889  1017  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,08-17 14:23:31.889  1017  1017 I ApplicationPolicy: updateDataUsageMap
08-17 14:23:31.889  1017  1485 I art     : Explicit concurrent mark sweep GC freed 57519(3MB) AllocSpace objects, 13(256KB) LOS objects, 33% free, 27MB/41MB, paused 2.504ms total 153.336ms
,08-17 14:23:31.899  1017  1042 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-17 14:23:31.899  3175  3175 I DBG_DM  : [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,08-17 14:23:31.899  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:31.909  1017  1485 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 14:23:31.909  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:31.909  1017  1485 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:31.909  1017  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 14:23:31.909  1017  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-17 14:23:31.909  3175  3175 I DBG_DM  : [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,08-17 14:23:31.929  1017  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-17 14:23:31.929  1017  1129 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-17 14:23:31.929  1017  1129 E WifiConfigStore: setLastSelectedConfiguration -1
,08-17 14:23:31.939  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 14:23:31.939  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-17 14:23:31.939  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:31.939  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:31.939  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:31.939  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:31.939  1181  1181 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 14:23:31.939  1181  1181 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-17 14:23:31.939  1181  1712 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-17 14:23:31.939  6441  6441 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-17 14:23:31.939  1181  1181 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-17 14:23:31.939  1181  1181 D HotspotTile: onReceive : 1, 0
,08-17 14:23:31.949  1934  2129 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 14:23:31.949  1323  1323 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-17 14:23:31.949  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:31.949  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:31.959  6441  6441 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-17 14:23:31.959  6441  6441 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-17 14:23:31.989  6441  6441 D FileShare-Client: Outbound.stopDelayTimer - 
,08-17 14:23:31.989  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-17 14:23:31.989  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 14:23:31.989  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 14:23:31.989  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 14:23:31.989  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 14:23:31.999  1934  2116 I art     : Explicit concurrent mark sweep GC freed 60797(3MB) AllocSpace objects, 55(2MB) LOS objects, 40% free, 14MB/24MB, paused 1.405ms total 78.239ms,
,08-17 14:23:32.009  6456  6456 E Zygote  : MountEmulatedStorage(),
08-17 14:23:32.009  6456  6456 E Zygote  : v2
08-17 14:23:32.009  6456  6456 I libpersona: KNOX_SDCARD checking this for 10069,
08-17 14:23:32.009  6456  6456 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-17 14:23:32.009  6456  6456 I libpersona: KNOX_SDCARD not a persona,
,08-17 14:23:32.009  6456  6456 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-17 14:23:32.009  6456  6456 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-17 14:23:32.009  1017  1030 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6456 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-17 14:23:32.019  1017  1030 I ActivityManager: Killing 5106:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,08-17 14:23:32.039  6456  6456 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 14:23:32.039  6456  6456 D ActivityThread: Added TimaKeyStore provider
,08-17 14:23:32.059  6456  6456 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-17 14:23:32.059  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:32.059  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-17 14:23:32.059  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,08-17 14:23:32.059  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,08-17 14:23:32.069  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 14:23:32.069  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:32.069  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 14:23:32.069  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 14:23:32.079  6471  6471 E Zygote  : MountEmulatedStorage(),
,08-17 14:23:32.079  6471  6471 E Zygote  : v2
,08-17 14:23:32.079  6471  6471 I libpersona: KNOX_SDCARD checking this for 10104
08-17 14:23:32.079  6471  6471 I libpersona: KNOX_SDCARD not a persona,
,08-17 14:23:32.079  6471  6471 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,08-17 14:23:32.089  1017  1029 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6471 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-17 14:23:32.089  1017  1029 I ActivityManager: Killing 5838:com.sec.pcw.device/1000 (adj 15): empty #31
,08-17 14:23:32.089  6471  6471 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-17 14:23:32.089  6471  6471 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-17 14:23:32.109  6471  6471 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 14:23:32.109  6471  6471 D ActivityThread: Added TimaKeyStore provider
,08-17 14:23:32.119  6471  6471 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-17 14:23:32.299  6471  6494 I Babel   : MmsConfig: mnc/mcc: 0/0
,08-17 14:23:32.299  6471  6494 I Babel   : MmsConfig.loadMmsSettings
08-17 14:23:32.299  6471  6494 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,08-17 14:23:32.299  6471  6494 I Babel   : MmsConfig.loadFromDatabase
,08-17 14:23:32.309  1017  3205 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-17 14:23:32.309  1017  3205 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-17 14:23:32.309  1017  3205 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:32.309  6471  6494 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-17 14:23:32.309  6471  6494 I Babel   : MmsConfig.loadFromResources
,08-17 14:23:32.309  1017  3205 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 14:23:32.309  1017  3205 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-17 14:23:32.319  6471  6494 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,08-17 14:23:32.319  6471  6494 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,08-17 14:23:32.319  6471  6471 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 14:23:32.359  6471  6471 I Babel_StickerModule: App launched.
,08-17 14:23:32.369  1017  2745 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-17 14:23:32.369  1017  2745 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 14:23:32.369  1017  2745 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:32.369  1017  2745 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:32.369  1017  2745 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 14:23:32.369  3670  3670 I Hs20UtilService: Starting #9
,08-17 14:23:32.369  1323  1323 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-17 14:23:32.369  1323  1323 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-17 14:23:32.379  3670  3711 I Hs20UtilService: Message received 5007
,08-17 14:23:32.379  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-17 14:23:32.379  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-17 14:23:32.379  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 14:23:32.379  1323  1323 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-17 14:23:32.379  1323  3116 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 14:23:32.379  1017  1505 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:32.379  1017  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:32.379  1017  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 14:23:32.389  1017  1483 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-17 14:23:32.389  1017  1483 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 14:23:32.389  1017  1483 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:32.389  1017  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:32.389  1017  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 14:23:32.389   283   697 W QCamera2Factory: getCameraInfo: E, camera_id = 0
,08-17 14:23:32.389   283   697 W QCamera2Factory: getCameraInfo: X
,08-17 14:23:32.389  1017  1727 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
08-17 14:23:32.389   283   283 W QCamera2Factory: getCameraInfo: E, camera_id = 1
08-17 14:23:32.389   283   283 W QCamera2Factory: getCameraInfo: X
,08-17 14:23:32.389  3670  3670 I Hs20UtilService: Starting #10
08-17 14:23:32.389  3670  3711 I Hs20UtilService: Message received 5011
,08-17 14:23:32.389  1017  1727 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 14:23:32.389  1017  1727 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:32.389  1017  1727 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:32.389  1017  1727 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 14:23:32.399  6496  6496 E Zygote  : MountEmulatedStorage()
,08-17 14:23:32.409  6496  6496 E Zygote  : v2
08-17 14:23:32.409  6496  6496 I libpersona: KNOX_SDCARD checking this for 1000
08-17 14:23:32.409  6496  6496 I libpersona: KNOX_SDCARD not a persona
,08-17 14:23:32.409  6496  6496 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-17 14:23:32.409  1017  1727 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6496 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
08-17 14:23:32.409  6496  6496 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-17 14:23:32.409  6496  6496 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-17 14:23:32.409  6471  6471 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-17 14:23:32.419  6471  6471 W AudioCapabilities: Unsupported mime audio/evrc
08-17 14:23:32.419  6471  6471 W AudioCapabilities: Unsupported mime audio/qcelp
,08-17 14:23:32.419  6471  6471 W AudioCapabilities: Unsupported mime audio/mpeg-L1
08-17 14:23:32.419  6471  6471 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-17 14:23:32.429  6471  6471 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-17 14:23:32.429  6471  6471 W AudioCapabilities: Unsupported mime audio/x-ima
,08-17 14:23:32.439  6471  6471 W AudioCapabilities: Unsupported mime audio/qcelp
,08-17 14:23:32.439  6471  6471 W AudioCapabilities: Unsupported mime audio/evrc
,08-17 14:23:32.439  6496  6496 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 14:23:32.439  6496  6496 D ActivityThread: Added TimaKeyStore provider
,08-17 14:23:32.449  6471  6471 W VideoCapabilities: Unsupported mime video/wvc1
,08-17 14:23:32.459  6471  6471 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-17 14:23:32.459  6471  6471 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-17 14:23:32.459  6471  6471 W VideoCapabilities: Unsupported mime video/wvc1
,08-17 14:23:32.469  6471  6471 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-17 14:23:32.469  6471  6471 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-17 14:23:32.469  6471  6471 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-17 14:23:32.469  6471  6471 W VideoCapabilities: Unsupported mime video/mp43
,08-17 14:23:32.469  6496  6496 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-17 14:23:32.479  6496  6496 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-17 14:23:32.479  6496  6496 D SecurityLogAgent: StateMachine : Current State = 1
,08-17 14:23:32.479  6471  6471 W VideoCapabilities: Unsupported mime video/sorenson
,08-17 14:23:32.479  6496  6496 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 14:23:32.479  1017  1222 I ActivityManager: Killing 5593:com.google.android.apps.plus/u0a120 (adj 15): empty #31
,08-17 14:23:32.489  1017  3207 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:32.489  1017  3207 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:32.489  1017  3207 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 14:23:32.489  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:32.489  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:32.489  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 14:23:32.489  6471  6471 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-17 14:23:32.499  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:32.499  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:32.499  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 14:23:32.499  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:32.499  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:32.499  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 14:23:32.509  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:32.509  6471  6471 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
08-17 14:23:32.509  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:32.509  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 14:23:32.509  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:32.509  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:32.509  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 14:23:32.519  1017  1045 D Tethering: interfaceRemoved wlan0
,08-17 14:23:32.519  1017  1045 E Tethering: attempting to remove unknown iface (wlan0), ignoring,
08-17 14:23:32.519  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:32.519  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:32.519  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 14:23:32.519  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:32.519  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:32.519  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 14:23:32.529  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:32.529  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:32.529  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 14:23:32.529  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:32.529  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:32.529  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 14:23:32.529  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:32.529  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:32.529  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 14:23:32.529  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:32.529  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:32.529  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 14:23:32.539  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:32.539  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:32.539  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 14:23:32.539  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:32.539  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:32.539  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 14:23:32.549  1017  1030 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,08-17 14:23:32.549  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,08-17 14:23:32.549  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:32.549  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 14:23:32.549  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-17 14:23:32.549  1323  1323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 14:23:32.549  1017  3205 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-17 14:23:32.549  1017  3205 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-17 14:23:32.559  1017  3205 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:32.559  1017  3205 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:32.559  1017  3205 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-17 14:23:32.559  1017  1531 I ActivityManager: Killing 5853:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,08-17 14:23:32.569  1323  1323 D DockEventReceiver: finishStartingService: stopping service
,08-17 14:23:32.569  1323  1323 D BluetoothNotiBroadcastReceiver: onReceive
,08-17 14:23:32.569  1181  1181 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 14:23:32.569  1181  1181 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-17 14:23:32.579  1017  1505 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-17 14:23:32.579  1017  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:32.579  1017  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:32.579  1017  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:32.579  1017  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 14:23:32.599  6515  6515 E Zygote  : MountEmulatedStorage(),
08-17 14:23:32.599  6515  6515 E Zygote  : v2
08-17 14:23:32.599  6515  6515 I libpersona: KNOX_SDCARD checking this for 1002
08-17 14:23:32.599  6515  6515 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-17 14:23:32.599  6515  6515 I libpersona: KNOX_SDCARD not a persona
08-17 14:23:32.599  1017  1505 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6515 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a,
08-17 14:23:32.599  6515  6515 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-17 14:23:32.609  6515  6515 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 14:23:32.619  6515  6515 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 14:23:32.629  6515  6515 D ActivityThread: Added TimaKeyStore provider
,08-17 14:23:32.639  6515  6515 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-17 14:23:32.639  6515  6515 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-17 14:23:32.669  6515  6515 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-17 14:23:32.699  6515  6515 D BtSettings.ProfileConfig: Adding GattService
,08-17 14:23:32.699  6515  6515 D BtSettings.ProfileConfig: Adding HeadsetService
08-17 14:23:32.699  6515  6515 D BtSettings.ProfileConfig: Adding A2dpService
,08-17 14:23:32.699  6515  6515 D BtSettings.ProfileConfig: Adding HidService
08-17 14:23:32.699  6515  6515 D BtSettings.ProfileConfig: Adding HealthService
08-17 14:23:32.699  6515  6515 D BtSettings.ProfileConfig: Adding PanService
08-17 14:23:32.699  6515  6515 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-17 14:23:32.699  6515  6515 D BtSettings.ProfileConfig: Adding SapService
,08-17 14:23:32.699  6515  6515 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-17 14:23:32.699  6515  6515 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-17 14:23:32.699  6515  6515 D BtSettings.ProfileConfig: Adding SapClientService
08-17 14:23:32.699  6515  6515 D BtSettings.ProfileConfig: Adding HidDevService
08-17 14:23:32.699  6515  6515 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-17 14:23:32.699  1017  3057 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-17 14:23:32.699  1017  3057 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 14:23:32.699  1017  3057 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 14:23:32.699  1017  3057 D SettingsProvider: selectionArgs: false
,08-17 14:23:32.699  1017  3057 D SettingsProvider: selectionArgs: 1002
08-17 14:23:32.699  1017  3057 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-17 14:23:32.699  1017  3057 D SettingsProvider: ret = -1
,08-17 14:23:32.709  1017  1727 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-17 14:23:32.709  1017  1727 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 14:23:32.709  1017  1727 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-17 14:23:32.709  1017  1727 D SettingsProvider: selectionArgs: false
08-17 14:23:32.709  1017  1727 D SettingsProvider: selectionArgs: 1002
08-17 14:23:32.709  1017  1727 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 14:23:32.709  1017  1727 D SettingsProvider: ret = -1
,08-17 14:23:32.709  1017  3207 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-17 14:23:32.709  1017  3207 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 14:23:32.709  1017  3207 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 14:23:32.709  1017  3207 D SettingsProvider: selectionArgs: false
,08-17 14:23:32.709  1017  3207 D SettingsProvider: selectionArgs: 1002
08-17 14:23:32.709  1017  3207 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-17 14:23:32.709  1017  3207 D SettingsProvider: ret = -1
,08-17 14:23:32.709  1017  3205 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-17 14:23:32.709  1017  3205 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-17 14:23:32.709  1017  3205 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 14:23:32.709  1017  3205 D SettingsProvider: selectionArgs: false
08-17 14:23:32.709  1017  3205 D SettingsProvider: selectionArgs: 1002
,08-17 14:23:32.709  1017  3205 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 14:23:32.709  1017  3205 D SettingsProvider: ret = -1
,08-17 14:23:32.709  1017  1343 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
,08-17 14:23:32.709  1017  1343 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 14:23:32.709  1017  1343 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 14:23:32.709  1017  1343 D SettingsProvider: selectionArgs: false
,08-17 14:23:32.709  1017  1343 D SettingsProvider: selectionArgs: 1002
08-17 14:23:32.709  1017  1343 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 14:23:32.709  1017  1343 D SettingsProvider: ret = -1
,08-17 14:23:32.709  1017  1485 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
,08-17 14:23:32.709  1017  1485 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 14:23:32.709  1017  1485 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 14:23:32.709  1017  1485 D SettingsProvider: selectionArgs: false
,08-17 14:23:32.709  1017  1485 D SettingsProvider: selectionArgs: 1002
08-17 14:23:32.719  1017  1485 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 14:23:32.719  1017  1485 D SettingsProvider: ret = -1
,08-17 14:23:32.719  1017  2745 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,08-17 14:23:32.719  1017  2745 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 14:23:32.719  1017  2745 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 14:23:32.719  1017  2745 D SettingsProvider: selectionArgs: false
08-17 14:23:32.719  1017  2745 D SettingsProvider: selectionArgs: 1002
,08-17 14:23:32.719  1017  2745 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-17 14:23:32.719  1017  2745 D SettingsProvider: ret = -1
08-17 14:23:32.719  1017  1222 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService,
08-17 14:23:32.719  1017  1222 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-17 14:23:32.719  1017  1222 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-17 14:23:32.719  1017  1222 D SettingsProvider: selectionArgs: false
08-17 14:23:32.719  1017  1222 D SettingsProvider: selectionArgs: 1002
08-17 14:23:32.719  1017  1222 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 14:23:32.719  1017  1222 D SettingsProvider: ret = -1
08-17 14:23:32.719  1017  1029 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-17 14:23:32.719  1017  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-17 14:23:32.719  1017  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 14:23:32.719  1017  1029 D SettingsProvider: selectionArgs: false
08-17 14:23:32.719  1017  1029 D SettingsProvider: selectionArgs: 1002
08-17 14:23:32.719  1017  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 14:23:32.719  1017  1029 D SettingsProvider: ret = -1
08-17 14:23:32.719  1017  1505 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,08-17 14:23:32.719  1017  1505 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 14:23:32.719  1017  1505 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 14:23:32.719  1017  1505 D SettingsProvider: selectionArgs: false
08-17 14:23:32.719  1017  1505 D SettingsProvider: selectionArgs: 1002
08-17 14:23:32.719  1017  1505 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 14:23:32.719  1017  1505 D SettingsProvider: ret = -1
,08-17 14:23:32.719  1017  1030 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-17 14:23:32.719  1017  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 14:23:32.719  1017  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 14:23:32.719  1017  1030 D SettingsProvider: selectionArgs: false
08-17 14:23:32.719  1017  1030 D SettingsProvider: selectionArgs: 1002
08-17 14:23:32.719  1017  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-17 14:23:32.719  1017  1030 D SettingsProvider: ret = -1
08-17 14:23:32.719  1017  3056 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-17 14:23:32.719  1017  3056 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 14:23:32.719  1017  3056 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 14:23:32.719  1017  3056 D SettingsProvider: selectionArgs: false
08-17 14:23:32.719  1017  3056 D SettingsProvider: selectionArgs: 1002
08-17 14:23:32.719  1017  3056 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
08-17 14:23:32.719  1017  3056 D SettingsProvider: ret = -1
,08-17 14:23:32.729  1017  1045 D Tethering: interfaceRemoved p2p0
,08-17 14:23:32.729  1017  1045 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-17 14:23:32.729  1017  1483 I ActivityManager: Killing 5528:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
,08-17 14:23:32.739  1934  1934 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-17 14:23:32.739  1017  3207 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 14:23:32.739  1017  3207 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-17 14:23:32.739  1017  3207 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:32.739  1017  3207 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 14:23:32.739  1017  3207 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 14:23:32.739  1934  6531 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-17 14:23:32.739  1934  1934 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-17 14:23:32.749  1017  1344 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-17 14:23:32.749  1017  1344 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:32.749  1017  1344 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:32.749  1017  1344 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:32.749  1017  1344 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 14:23:32.759  6532  6532 E Zygote  : MountEmulatedStorage()
,08-17 14:23:32.759  6532  6532 E Zygote  : v2
08-17 14:23:32.759  6532  6532 I libpersona: KNOX_SDCARD checking this for 1000
08-17 14:23:32.759  6532  6532 I libpersona: KNOX_SDCARD not a persona
,08-17 14:23:32.759  6532  6532 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-17 14:23:32.759  1017  2759 D SSRM:n  : SIOP:: AP = 340
,08-17 14:23:32.769  1017  1344 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6532 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,08-17 14:23:32.769  6532  6532 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-17 14:23:32.769  6532  6532 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-17 14:23:32.769  1017  3207 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 14:23:32.769  1017  3207 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:32.769  1017  3207 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 14:23:32.769  1017  3207 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 14:23:32.779  6532  6532 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 14:23:32.789  6532  6532 D ActivityThread: Added TimaKeyStore provider
,08-17 14:23:32.789  1017  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 14:23:32.789  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:32.789  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 14:23:32.789  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 14:23:32.799  1934  6531 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-17 14:23:32.809  6532  6532 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-17 14:23:32.819  6532  6532 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-17 14:23:32.819  6532  6532 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-17 14:23:32.829  6532  6532 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-17 14:23:32.829  6532  6532 I PCWCLIENTTRACE_PushUtil: sales region : global
,08-17 14:23:32.829  6532  6532 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-17 14:23:32.829  6532  6532 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-17 14:23:32.829  1017  1531 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
,08-17 14:23:32.829  1017  1531 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
08-17 14:23:32.829  6532  6547 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,08-17 14:23:32.829  1017  1531 D ActivityManager: startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,08-17 14:23:32.829  1017  1531 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 14:23:32.829  1017  1531 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:32.829  1017  1531 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:32.829  1017  1531 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 14:23:32.839   290   290 E SMD     : DCD OFF,
,08-17 14:23:32.849  6549  6549 E Zygote  : MountEmulatedStorage(),
,08-17 14:23:32.849  6549  6549 E Zygote  : v2,
08-17 14:23:32.849  6549  6549 I libpersona: KNOX_SDCARD checking this for 10111
,08-17 14:23:32.849  1017  1531 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6549 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-17 14:23:32.849  6549  6549 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-17 14:23:32.849  6549  6549 I libpersona: KNOX_SDCARD not a persona
,08-17 14:23:32.859  1017  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-17 14:23:32.859  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:32.859  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:32.859  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:32.859  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-17 14:23:32.859  6549  6549 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-17 14:23:32.859  6549  6549 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,08-17 14:23:32.869  6558  6558 E Zygote  : MountEmulatedStorage()
08-17 14:23:32.879  6558  6558 E Zygote  : v2
,08-17 14:23:32.879  6558  6558 I libpersona: KNOX_SDCARD checking this for 10009
08-17 14:23:32.879  6558  6558 I libpersona: KNOX_SDCARD not a persona
,08-17 14:23:32.879  6558  6558 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-17 14:23:32.879  6558  6558 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-17 14:23:32.879  6558  6558 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-17 14:23:32.879  1017  1043 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6558 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-17 14:23:32.879  1017  1043 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,08-17 14:23:32.889  1730  1730 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE,
08-17 14:23:32.889  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:32.889  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:32.889  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:32.889  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 14:23:32.889  6549  6549 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 14:23:32.889  6549  6549 D ActivityThread: Added TimaKeyStore provider
,08-17 14:23:32.899   324   324 I art     : Explicit concurrent mark sweep GC freed 8733(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 950us total 20.192ms
,08-17 14:23:32.909  6558  6558 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 14:23:32.909  6558  6558 D ActivityThread: Added TimaKeyStore provider
,08-17 14:23:32.919   324   324 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 607us total 16.899ms
,08-17 14:23:32.929   324   324 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 597us total 16.603ms,
,08-17 14:23:32.949  6579  6579 E Zygote  : MountEmulatedStorage()
,08-17 14:23:32.949  6579  6579 E Zygote  : v2
08-17 14:23:32.949  6579  6579 I libpersona: KNOX_SDCARD checking this for 10145
08-17 14:23:32.949  1017  1043 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6579 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,08-17 14:23:32.949  6579  6579 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-17 14:23:32.949  6579  6579 I libpersona: KNOX_SDCARD not a persona
,08-17 14:23:32.949  6579  6579 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-17 14:23:32.949  6579  6579 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 14:23:32.979  1730  1730 D accuweather: [KK AccuPhone]>>> U:4106 [0:0] getPWC : surface = 0, remote = 1
08-17 14:23:32.979  1730  1730 D accuweather: [KK AccuPhone]>>> U:4284 [0:0] Store PWC = 1
,08-17 14:23:32.979  1730  1730 D accuweather: [KK AccuPhone]>>> U:4158 [0:0] addPWC = 1
08-17 14:23:32.979  1730  1730 D accuweather: [KK AccuPhone]>>> UIM:306 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-17 14:23:32.989  1730  1730 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-17 14:23:32.989  1298  1311 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 8
,08-17 14:23:32.999  1730  1730 D accuweather: [KK AccuPhone]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,08-17 14:23:32.999  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-17 14:23:32.999  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 14:23:32.999  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 14:23:32.999  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:32.999  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 14:23:33.009  6579  6579 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 14:23:33.009  6579  6579 D ActivityThread: Added TimaKeyStore provider
,08-17 14:23:33.029  6594  6594 E Zygote  : MountEmulatedStorage()
08-17 14:23:33.029  6594  6594 E Zygote  : v2
08-17 14:23:33.029  6594  6594 I libpersona: KNOX_SDCARD checking this for 10081
08-17 14:23:33.029  6594  6594 I libpersona: KNOX_SDCARD not a persona
,08-17 14:23:33.029  6594  6594 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-17 14:23:33.039  1017  1030 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6594 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-17 14:23:33.039  6594  6594 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-17 14:23:33.039  6594  6594 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,08-17 14:23:33.049  1730  1730 D accuweather: [KK AccuPhone]>>> U:4250 [0:0] Store PWC succeed
,08-17 14:23:33.059  6579  6579 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-17 14:23:33.069  6579  6579 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 14:23:33.069  6579  6579 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-17 14:23:33.069  6579  6579 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-17 14:23:33.069  6579  6579 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-17 14:23:33.069  6594  6594 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 14:23:33.069  6594  6594 D ActivityThread: Added TimaKeyStore provider
,08-17 14:23:33.079  1017  2745 I ActivityManager: Killing 5561:com.sec.knox.bridge/1000 (adj 15): empty #31
,08-17 14:23:33.079  3717  3717 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Aug 17 14:23:33 GMT+02:00 2016
,08-17 14:23:33.079  1017  1029 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-17 14:23:33.079  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-17 14:23:33.089  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:33.089  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:33.089  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-17 14:23:33.089  6549  6549 I MusicStore: Database version: 108
08-17 14:23:33.089  3717  3717 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,08-17 14:23:33.099  3717  3717 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,08-17 14:23:33.099  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-17 14:23:33.099  3717  3717 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
08-17 14:23:33.099  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:33.099  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:33.099  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:33.099  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 14:23:33.109  3717  3717 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-17 14:23:33.109  3717  6613 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-17 14:23:33.109  3717  6613 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-17 14:23:33.109  3717  6613 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-17 14:23:33.119  6615  6615 E Zygote  : MountEmulatedStorage()
08-17 14:23:33.119  6615  6615 I libpersona: KNOX_SDCARD checking this for 10034
08-17 14:23:33.119  6615  6615 E Zygote  : v2
08-17 14:23:33.119  6615  6615 I libpersona: KNOX_SDCARD not a persona
08-17 14:23:33.119  6615  6615 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-17 14:23:33.119  1017  1030 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6615 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
,08-17 14:23:33.119  6615  6615 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-17 14:23:33.119  6615  6615 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 14:23:33.119  3717  6613 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END
,08-17 14:23:33.129  1017  1727 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-17 14:23:33.129  3717  3717 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
08-17 14:23:33.129  1017  1727 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-17 14:23:33.129  1017  1727 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:33.129  1017  1727 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 14:23:33.129  1017  1727 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-17 14:23:33.139  6615  6615 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 14:23:33.139  6615  6615 D ActivityThread: Added TimaKeyStore provider
,08-17 14:23:33.159  1017  3207 D RCPManagerService: exchangeData() failure , invalid userId
,08-17 14:23:33.169  1017  1029 D RCPManagerService: exchangeData() failure , invalid userId
,08-17 14:23:33.179  6615  6615 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-17 14:23:33.199  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-17 14:23:33.199  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 14:23:33.199  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:33.199  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:33.199  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 14:23:33.199  3211  6635 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,08-17 14:23:33.209  3211  6635 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-17 14:23:33.219  1017  1029 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6637 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-17 14:23:33.219  1017  3205 D RCPManagerService: exchangeData() failure , invalid userId,
08-17 14:23:33.219  1017  1029 I ActivityManager: Killing 4109:com.sec.spp.push/u0a35 (adj 15): empty #31
,08-17 14:23:33.219  3211  6635 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
08-17 14:23:33.219  6637  6637 I libpersona: KNOX_SDCARD checking this for 10113
08-17 14:23:33.219  6637  6637 E Zygote  : MountEmulatedStorage()
08-17 14:23:33.219  6637  6637 I libpersona: KNOX_SDCARD not a persona
08-17 14:23:33.219  6637  6637 E Zygote  : v2
08-17 14:23:33.219  3211  6635 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
08-17 14:23:33.219  6637  6637 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-17 14:23:33.219  3211  6635 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-17 14:23:33.229  6637  6637 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-17 14:23:33.229  6637  6637 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-17 14:23:33.239  6637  6637 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 14:23:33.239  6637  6637 D ActivityThread: Added TimaKeyStore provider
,08-17 14:23:33.249  6549  6549 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-17 14:23:33.249  6549  6549 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-17 14:23:33.249  1017  1029 D RCPManagerService: exchangeData() failure , invalid userId
,08-17 14:23:33.259  6088  6088 I SA      : [DM] init START
,08-17 14:23:33.259  6088  6088 I SA      : [DM] This device is not a Vodafone
,08-17 14:23:33.269  6088  6088 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,08-17 14:23:33.269  6088  6088 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
08-17 14:23:33.269  6088  6088 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,08-17 14:23:33.269  6088  6088 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,08-17 14:23:33.269  6088  6088 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
08-17 14:23:33.269  6088  6088 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,08-17 14:23:33.269  6088  6088 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,08-17 14:23:33.269  6088  6088 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-17 14:23:33.269  6088  6088 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,08-17 14:23:33.279  6088  6088 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,08-17 14:23:33.279  6088  6088 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,08-17 14:23:33.279  6088  6088 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,08-17 14:23:33.279  6088  6088 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,08-17 14:23:33.279  6088  6088 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,08-17 14:23:33.279  6088  6088 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,08-17 14:23:33.279  6088  6088 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,08-17 14:23:33.289  6088  6088 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,08-17 14:23:33.289  6088  6088 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,08-17 14:23:33.289  6088  6088 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,08-17 14:23:33.289  6088  6088 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,08-17 14:23:33.289  6088  6088 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,08-17 14:23:33.289  6088  6088 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
08-17 14:23:33.289  6088  6088 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75),
08-17 14:23:33.289  6088  6088 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,08-17 14:23:33.289  6088  6088 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
08-17 14:23:33.289  6088  6088 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,08-17 14:23:33.299  6549  6549 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-17 14:23:33.299  6088  6088 I SA      : [SCU] isHaveSA() - false
08-17 14:23:33.299  6088  6088 I SA      : support phone number id : false
08-17 14:23:33.299  6088  6088 I SA      : [DM] Supports Ref Jpn : true
,08-17 14:23:33.299  6088  6088 I SA      : [DM] init END
08-17 14:23:33.299  6088  6088 I SA      : [OR] onReceive log=[SA = 2.1.0240 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOJ6 PSS = 4.978878039476607  ]
,08-17 14:23:33.309  6088  6088 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,08-17 14:23:33.309  6088  6088 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-17 14:23:33.309  6088  6088 I SA      : [SLFUCHKMGR] constructor called
,08-17 14:23:33.329  5983  5996 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-17 14:23:33.329  6088  6088 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
08-17 14:23:33.329  6088  6088 I SA      : [OR] == isSIMCardReady false ==
,08-17 14:23:33.329  1017  1030 D RCPManagerService: exchangeData() failure , invalid userId
08-17 14:23:33.329  6088  6088 I SA      : [SCU] == networkStateCheck == false
08-17 14:23:33.329  6088  6088 I SA      : [OR] onReceive END
,08-17 14:23:33.349  1017  3057 D RCPManagerService: exchangeData() failure , invalid userId
,08-17 14:23:33.349  1486  1486 D Launcher.Model: reloadBadges entered.
,08-17 14:23:33.349  5983  5996 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
,08-17 14:23:33.349  5983  5996 D BadgeProvider: sendNotify, [notify] : null
,08-17 14:23:33.349  5983  5996 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-17 14:23:33.359  5983  5996 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-17 14:23:33.359  5983  5996 D BadgeProvider: update, [UpdateCount] : 1
,08-17 14:23:33.359  1233  1233 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-17 14:23:33.369  1017  1727 D RCPManagerService: exchangeData() failure , invalid userId
,08-17 14:23:33.369  6549  6549 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-17 14:23:33.369  6549  6549 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@20c8de3f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
08-17 14:23:33.369  6549  6549 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
08-17 14:23:33.369  6549  6549 D AndroidMusic: GMSCore installation verified
,08-17 14:23:33.379  1017  1030 D RCPManagerService: exchangeData() failure , invalid userId
,08-17 14:23:33.389  6496  6496 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-17 14:23:33.389  6496  6496 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-17 14:23:33.389  6496  6496 D SecurityLogAgent: StateMachine : Current State = 1
08-17 14:23:33.389  6496  6496 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 14:23:33.389  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,08-17 14:23:33.399  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:33.399  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:33.399  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:33.399  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 14:23:33.409  6662  6662 E Zygote  : MountEmulatedStorage()
08-17 14:23:33.409  6662  6662 I libpersona: KNOX_SDCARD checking this for 10159
08-17 14:23:33.409  6662  6662 E Zygote  : v2
08-17 14:23:33.409  6662  6662 I libpersona: KNOX_SDCARD not a persona
08-17 14:23:33.409  6662  6662 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-17 14:23:33.409  6662  6662 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-17 14:23:33.419  6662  6662 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL,
08-17 14:23:33.419  1017  1030 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=6662 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-17 14:23:33.419  1017  1030 I ActivityManager: Killing 5868:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,08-17 14:23:33.419  1017  1079 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-17 14:23:33.419  1017  1079 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,08-17 14:23:33.419  1017  1079 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:33.419  1017  1079 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 14:23:33.419  1017  1079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-17 14:23:33.439  1017  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-17 14:23:33.439  6549  6549 I ConfigStore: Config Database version: 1
,08-17 14:23:33.449  6662  6662 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 14:23:33.459  6662  6662 D ActivityThread: Added TimaKeyStore provider
,08-17 14:23:33.499  1017  1030 I ActivityManager: Killing 5932:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
,08-17 14:23:33.499  1017  2745 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-17 14:23:33.499  1017  2745 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-17 14:23:33.499  1017  2745 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:33.499  1017  2745 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 14:23:33.499  1017  2745 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 14:23:33.519  3852  3852 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-17 14:23:33.529  3852  4602 I iu.UploadsManager: num queued entries: 0
,08-17 14:23:33.529  3852  4602 I iu.UploadsManager: num updated entries: 0
,08-17 14:23:33.529  3852  4602 I iu.SyncManager: NEXT; no task
,08-17 14:23:33.539   256   537 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
08-17 14:23:33.539   256   537 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 14:23:33.539  6549  6549 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,08-17 14:23:33.539   256   537 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
08-17 14:23:33.539   256   537 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 14:23:33.539  6549  6549 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,08-17 14:23:33.549   256   537 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
08-17 14:23:33.549   256   537 W Vold    : Returning OperationFailed - no handler for errno 0
08-17 14:23:33.549  6549  6549 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,08-17 14:23:33.559  1017  2745 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,08-17 14:23:33.559  1017  2745 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,08-17 14:23:33.559  1017  2745 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:33.559  1017  2745 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 14:23:33.559  1017  2745 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-17 14:23:33.569   256   537 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-17 14:23:33.569   256   537 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 14:23:33.569  6637  6679 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-17 14:23:33.569   256   537 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-17 14:23:33.569   256   537 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 14:23:33.569  6637  6679 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-17 14:23:33.579  1017  3056 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-17 14:23:33.579  1017  3056 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,08-17 14:23:33.579  1017  3056 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:33.579  1017  3056 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 14:23:33.579  1017  3056 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-17 14:23:33.589   256   537 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-17 14:23:33.589   256   537 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 14:23:33.589  6637  6683 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-17 14:23:33.589   256   537 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-17 14:23:33.589   256   537 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 14:23:33.589  6637  6683 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-17 14:23:33.619  1017  1079 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-17 14:23:33.619  1017  1079 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-17 14:23:33.629  1017  3207 I AudioService: getStreamVolume 3 index 0
,08-17 14:23:33.629  6549  6549 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,08-17 14:23:33.639  6549  6549 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,08-17 14:23:33.639  1017  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,08-17 14:23:33.639  1017  1485 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-17 14:23:33.649  1017  1222 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-17 14:23:33.649  1017  3207 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-17 14:23:33.659  1017  1030 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
08-17 14:23:33.659  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-17 14:23:33.659  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:33.659  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 14:23:33.659  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-17 14:23:33.659  1017  1343 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
08-17 14:23:33.659  1017  1343 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,08-17 14:23:33.659  1017  1343 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:33.659  1017  1343 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 14:23:33.659  1017  1343 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-17 14:23:33.669  1017  1727 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
08-17 14:23:33.669  1017  1727 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,08-17 14:23:33.669  1017  1727 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:33.669  1017  1727 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 14:23:33.669  1017  1727 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-17 14:23:33.669  1017  1079 I ActivityManager: Killing 5819:com.android.mms/u0a46 (adj 15): empty #31
,08-17 14:23:33.669  1017  1485 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-17 14:23:33.679  1017  2745 D CountryDetector: No listener is left
,08-17 14:23:33.689  1017  1017 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-17 14:23:33.689  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 14:23:33.689  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:33.689  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:33.689  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 14:23:33.709  6688  6688 E Zygote  : MountEmulatedStorage()
08-17 14:23:33.709  6688  6688 E Zygote  : v2
08-17 14:23:33.709  6688  6688 I libpersona: KNOX_SDCARD checking this for 10002
08-17 14:23:33.709  6688  6688 I libpersona: KNOX_SDCARD not a persona
,08-17 14:23:33.709  6688  6688 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-17 14:23:33.709  1017  1017 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6688 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-17 14:23:33.709  6688  6688 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-17 14:23:33.719  6688  6688 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 14:23:33.729  1017  1079 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
08-17 14:23:33.729  1017  1079 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-17 14:23:33.729  1017  1079 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:33.729  1017  1079 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 14:23:33.739  1017  1079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,08-17 14:23:33.739  6549  6549 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
,08-17 14:23:33.749  1017  1343 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
08-17 14:23:33.749  1017  1343 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-17 14:23:33.749  1017  1343 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:33.749  1017  1343 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 14:23:33.749  1017  1343 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-17 14:23:33.749  6688  6688 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 14:23:33.749  6688  6688 D ActivityThread: Added TimaKeyStore provider
,08-17 14:23:33.789  1017  1029 I ActivityManager: Killing 6006:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,08-17 14:23:33.809  1017  1343 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 14:23:33.809  1017  1343 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:33.809  1017  1343 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-17 14:23:33.809  1017  1343 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-17 14:23:33.839  6637  6637 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,08-17 14:23:33.849  1017  1344 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-17 14:23:33.849  6637  6637 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 235-237)
08-17 14:23:33.849  6637  6637 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-17 14:23:33.849  1017  1344 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 14:23:33.859  1017  1344 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 14:23:33.859  1017  1344 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:33.859  1017  1344 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 14:23:33.859  6637  6637 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1919a7a4},
08-17 14:23:33.859  6637  6637 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-17 14:23:33.859  6637  6637 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,08-17 14:23:33.879  6637  6637 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-17 14:23:33.879  6637  6637 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-17 14:23:33.879  6637  6637 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-17 14:23:33.889  6722  6722 E Zygote  : MountEmulatedStorage()
,08-17 14:23:33.889  6722  6722 E Zygote  : v2
08-17 14:23:33.889  6722  6722 I libpersona: KNOX_SDCARD checking this for 1000
08-17 14:23:33.889  6722  6722 I libpersona: KNOX_SDCARD not a persona
,08-17 14:23:33.889  6722  6722 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-17 14:23:33.889  1017  1344 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6722 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,08-17 14:23:33.899  6722  6722 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-17 14:23:33.899  6722  6722 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-17 14:23:33.909  6637  6637 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,08-17 14:23:33.909  6637  6637 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
,08-17 14:23:33.909  6637  6637 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,08-17 14:23:33.919  6637  6637 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-17 14:23:33.919  6637  6637 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-17 14:23:33.919  6637  6637 I Adreno-EGL: Build Date: 04/06/15 Mon
08-17 14:23:33.919  6637  6637 I Adreno-EGL: Local Branch: 
08-17 14:23:33.919  6637  6637 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-17 14:23:33.919  6637  6637 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-17 14:23:33.919  6637  6637 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
08-17 14:23:33.919  6722  6722 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 14:23:33.919  6722  6722 D ActivityThread: Added TimaKeyStore provider
,08-17 14:23:33.959  6722  6722 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-17 14:23:33.979  6637  6747 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-17 14:23:33.989  6637  6637 I NSApplication: Starting up...
,08-17 14:23:33.999  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-17 14:23:33.999  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 14:23:33.999  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:33.999  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:33.999  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 14:23:34.009  1017  1483 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-17 14:23:34.009  1017  1483 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-17 14:23:34.009  1017  1483 D SecContentProvider2: mCursor = null
,08-17 14:23:34.009  1017  1483 D WifiService: setWifiEnabled: true pid=6291, uid=10155
,08-17 14:23:34.009  1017  1483 W ActivityManager: Permission Denial: getCurrentUser() from pid=6291, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,08-17 14:23:34.009  1017  1483 W WifiService: Failed getting userId using ActivityManagerNative
08-17 14:23:34.009  1017  1483 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6291, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-17 14:23:34.009  1017  1483 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-17 14:23:34.009  1017  1483 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-17 14:23:34.009  1017  1483 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-17 14:23:34.009  1017  1483 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-17 14:23:34.009  1017  1483 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-17 14:23:34.009  6752  6752 E Zygote  : MountEmulatedStorage()
,08-17 14:23:34.009  6752  6752 E Zygote  : v2
08-17 14:23:34.009  6752  6752 I libpersona: KNOX_SDCARD checking this for 10120
08-17 14:23:34.009  6752  6752 I libpersona: KNOX_SDCARD not a persona
,08-17 14:23:34.009  1017  1483 D SettingsProvider: name = wifi_on
08-17 14:23:34.009  6752  6752 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-17 14:23:34.019  1017  1129 E WifiHW  : ##################### set firmware type 0 #####################
,08-17 14:23:34.019  6752  6752 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-17 14:23:34.019  1017  1029 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6752 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-17 14:23:34.019  1017  1029 I ActivityManager: Killing 5898:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty #31
,08-17 14:23:34.019  1017  1029 I ActivityManager: Killing 6041:com.wsomacp/u0a25 (adj 15): empty #32
,08-17 14:23:34.029  6752  6752 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-17 14:23:34.059  6752  6752 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 14:23:34.059  6752  6752 D ActivityThread: Added TimaKeyStore provider
,08-17 14:23:34.079  6752  6752 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-17 14:23:34.099  6722  6722 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-17 14:23:34.109  6722  6722 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-17 14:23:34.109  6722  6722 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-17 14:23:34.109  6722  6722 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-17 14:23:34.109  6722  6722 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-17 14:23:34.109  6722  6722 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-17 14:23:34.109  1017  3056 I ActivityManager: Killing 6069:com.sec.android.app.soundalive/u0a53 (adj 15): empty #31
,08-17 14:23:34.379  1017  1727 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-17 14:23:34.379  1017  1727 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 14:23:34.379  1017  1727 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 14:23:34.379  1017  1727 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:34.379  1017  1727 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 14:23:34.389  1017  1045 D Tethering: interfaceAdded wlan0
,08-17 14:23:34.389  1017  1133 E Tethering: No numeric data
,08-17 14:23:34.399  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 14:23:34.399  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-17 14:23:34.399  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-17 14:23:34.399  1017  1045 D Tethering: interfaceAdded p2p0,
08-17 14:23:34.399  1017  1045 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-17 14:23:34.409  6781  6781 E Zygote  : MountEmulatedStorage()
,08-17 14:23:34.409  6781  6781 E Zygote  : v2
08-17 14:23:34.409  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-17 14:23:34.409  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
08-17 14:23:34.409  6781  6781 I libpersona: KNOX_SDCARD checking this for 10125
08-17 14:23:34.409  6781  6781 I libpersona: KNOX_SDCARD not a persona
08-17 14:23:34.409  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-17 14:23:34.409   278   986 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-17 14:23:34.409   278   986 D SoftapController: Softap fwReload - Ok
,08-17 14:23:34.409  6781  6781 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,08-17 14:23:34.409   278   986 D CommandListener: Setting iface cfg
08-17 14:23:34.409   278   986 D CommandListener: Trying to bring down wlan0,
,08-17 14:23:34.409   278   986 D CommandListener: Clearing all IP addresses on wlan0
,08-17 14:23:34.409  6781  6781 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-17 14:23:34.409  6781  6781 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-17 14:23:34.419  1017  1129 E WifiHW  : supplicant_name : p2p_supplicant
,08-17 14:23:34.419  1017  1727 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6781 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,08-17 14:23:34.419  1017  1133 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-17 14:23:34.419  1017  1727 I ActivityManager: Killing 5883:com.google.android.apps.docs/u0a91 (adj 15): empty #31
08-17 14:23:34.419  1017  1133 D Tethering: clearTetheredNotification()
08-17 14:23:34.419  1017  1133 D Tethering: InitialState.processMessage what=4
,08-17 14:23:34.419  1017  1133 E Tethering: No numeric data
08-17 14:23:34.419  1017  1126 V NetworkStats: performPollLocked(flags=0x1)
08-17 14:23:34.419  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 14:23:34.419  1017  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-17 14:23:34.429  1017  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-17 14:23:34.429  1181  1181 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-17 14:23:34.429  1181  1181 D HotspotTile: updateTetherState():false, false
,08-17 14:23:34.429  1017  1133 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-17 14:23:34.429  1017  1133 D Tethering: clearTetheredNotification()
,08-17 14:23:34.429  1181  1181 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-17 14:23:34.429  1181  1181 D HotspotTile: updateTetherState():false, false
,08-17 14:23:34.439  1017  1126 V NetworkStats: performPollLocked() took 13ms
08-17 14:23:34.439  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 14:23:34.439  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 14:23:34.439  1017  1126 V NetworkStats: performPollLocked(flags=0x1)
08-17 14:23:34.439  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 14:23:34.439  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 14:23:34.439  1017  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 14:23:34.439  1017  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-17 14:23:34.439  6781  6781 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 14:23:34.439  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 14:23:34.439  1017  1126 V NetworkStats: performPollLocked() took 5ms
,08-17 14:23:34.439  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 14:23:34.439  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 14:23:34.439  6781  6781 D ActivityThread: Added TimaKeyStore provider
,08-17 14:23:34.459  6781  6781 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-17 14:23:34.459  6781  6781 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-17 14:23:34.459  6781  6781 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-17 14:23:34.459  6788  6788 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-17 14:23:34.459  6788  6788 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-17 14:23:34.459  6788  6788 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-17 14:23:34.479  6788  6788 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
08-17 14:23:34.479   398   398 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 6788
08-17 14:23:34.479   398   398 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
08-17 14:23:34.479  6788  6788 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-17 14:23:34.479  6788  6788 I wpa_supplicant: ssSupport state is = 1
08-17 14:23:34.479  6788  6788 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-17 14:23:34.479  6788  6788 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-17 14:23:34.479  6781  6781 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
08-17 14:23:34.479   398   398 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 6788
08-17 14:23:34.479   398   398 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x00000106
,08-17 14:23:34.479  6781  6781 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-17 14:23:34.479  6781  6781 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
08-17 14:23:34.479  1017  1222 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-17 14:23:34.489  1017  1222 I ActivityManager: Killing 6122:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,08-17 14:23:34.489  1017  1485 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 14:23:34.489  1017  1485 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 14:23:34.489  1017  1485 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:34.489  1017  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:34.489  1017  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 14:23:34.499  3670  3670 I Hs20UtilService: Starting #11
,08-17 14:23:34.499  3670  3711 I Hs20UtilService: Message received 5011
,08-17 14:23:34.499  6496  6496 D SecurityLogAgent: KnoxConfiguration : Current State = 1,
08-17 14:23:34.499  6496  6496 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-17 14:23:34.499  6496  6496 D SecurityLogAgent: StateMachine : Current State = 1
08-17 14:23:34.499  6496  6496 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 14:23:34.519  1017  1129 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-17 14:23:34.519  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 14:23:34.519  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-17 14:23:34.519  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:34.519  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:34.519  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-17 14:23:34.519  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:34.519  1181  1181 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 14:23:34.519  1181  1181 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
08-17 14:23:34.519  1181  1712 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-17 14:23:34.519  1181  1181 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-17 14:23:34.519  1181  1181 D HotspotTile: onReceive : 2, 0
08-17 14:23:34.519  1323  1323 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-17 14:23:34.529  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:34.529  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:34.529  1017  1505 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-17 14:23:34.529  1017  1505 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 14:23:34.529  1017  1505 W ActivityManager: userId = 0, bbcId = -10000,
08-17 14:23:34.529  1017  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:34.529  1017  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 14:23:34.539  3670  3670 I Hs20UtilService: Starting #12
08-17 14:23:34.539  3670  3711 I Hs20UtilService: Message received 5011
,08-17 14:23:34.539  6496  6496 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-17 14:23:34.539  6496  6496 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-17 14:23:34.539  6496  6496 D SecurityLogAgent: StateMachine : Current State = 1
08-17 14:23:34.539  6496  6496 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 14:23:34.639   398   398 I SecureStorage: [INFO]: SPID(0x00000005)Secure Storage Daemon finished processing with result: 0
,08-17 14:23:34.639  6788  6788 I SecureStorage: [INFO]: SPID(0x00000005)Processing data has been completed
,08-17 14:23:34.709  6788  6788 I wpa_supplicant: Ctrl_iface: loading cred from phone
,08-17 14:23:34.709  6788  6788 I SecureStorage: [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,08-17 14:23:34.719  6788  6788 I SecureStorage: [INFO]: SPID(0x00000005)This device supports Secure Storage
,08-17 14:23:34.719   398   398 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 6788
08-17 14:23:34.719   398   398 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
08-17 14:23:34.719  6788  6788 I SecureStorage: [INFO]: SPID(0x00000005)SS Daemon is running
08-17 14:23:34.719  6788  6788 I wpa_supplicant: ssSupport state is = 1
08-17 14:23:34.719  6788  6788 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-17 14:23:34.719  6788  6788 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 14:23:34.719  6788  6788 E wpa_supplicant: SIM READ ERROR
08-17 14:23:34.719  6788  6788 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 14:23:34.719  6788  6788 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 14:23:34.719  6788  6788 E wpa_supplicant: SIM READ ERROR
08-17 14:23:34.719  6788  6788 I wpa_supplicant: Blacklist: Clear (all) ,
08-17 14:23:34.719  6788  6788 I wpa_supplicant: wpa_default_ap_write_once
08-17 14:23:34.719  6788  6788 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-17 14:23:34.719  6788  6788 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 14:23:34.719  6788  6788 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-17 14:23:34.719  6788  6788 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 14:23:34.719  6788  6788 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
,08-17 14:23:34.729  6788  6788 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-17 14:23:34.729  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false,
08-17 14:23:34.729  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 14:23:34.729  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-17 14:23:34.849  6788  6788 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-17 14:23:35.079  6788  6788 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-17 14:23:35.079  6788  6788 I SecureStorage: [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,08-17 14:23:35.089  6788  6788 I SecureStorage: [INFO]: SPID(0x00000005)This device supports Secure Storage,
,08-17 14:23:35.099   398   398 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 6788
08-17 14:23:35.099   398   398 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
08-17 14:23:35.099  6788  6788 I SecureStorage: [INFO]: SPID(0x00000005)SS Daemon is running
08-17 14:23:35.099  6788  6788 I wpa_supplicant: ssSupport state is = 1
,08-17 14:23:35.099  6788  6788 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-17 14:23:35.099  6788  6788 I SecureStorage: [INFO]: SPID(0x00000005)Checking if this device supports Secure Storage
,08-17 14:23:35.109  6788  6788 I SecureStorage: [INFO]: SPID(0x00000005)This device supports Secure Storage,
08-17 14:23:35.109   398   398 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 6788
08-17 14:23:35.109   398   398 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
08-17 14:23:35.109  6788  6788 I SecureStorage: [INFO]: SPID(0x00000005)SS Daemon is running
,08-17 14:23:35.109  6788  6788 I wpa_supplicant: ssSupport state is = 1
08-17 14:23:35.109  6788  6788 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 14:23:35.109  6788  6788 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 14:23:35.109  6788  6788 E wpa_supplicant: SIM READ ERROR
08-17 14:23:35.109  6788  6788 I wpa_supplicant: wpa_default_ap_write_once
08-17 14:23:35.109  6788  6788 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap,
08-17 14:23:35.109  6788  6788 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-17 14:23:35.109  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-17 14:23:35.109  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-17 14:23:35.109  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-17 14:23:35.109  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false,
08-17 14:23:35.109  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-17 14:23:35.109  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-17 14:23:35.209  6788  6788 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-17 14:23:35.209  6788  6788 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-17 14:23:35.329  6788  6788 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-17 14:23:35.329  6788  6788 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-17 14:23:35.329  6788  6788 I wpa_supplicant: Skip scan - bUseNetwork false
,08-17 14:23:35.339  1017  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
08-17 14:23:35.339  1017  1129 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-17 14:23:35.339  6788  6788 I wpa_supplicant: HOTSPOT20_ENABLE called,
08-17 14:23:35.339  6788  6788 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 14:23:35.339  6788  6788 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 14:23:35.339  6788  6788 E wpa_supplicant: SIM READ ERROR
08-17 14:23:35.339  6788  6788 I wpa_supplicant: Blacklist: Clear (all) ,
,08-17 14:23:35.369  6788  6788 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-17 14:23:35.379  1017  1129 D WifiNative-wlan0: callSECApiInt - ID [210],
08-17 14:23:35.379  6788  6788 I wpa_supplicant: Skip scan - bUseNetwork false
,08-17 14:23:35.379  1017  1129 D WifiConfigStore: Loading config and enabling all networks ,
08-17 14:23:35.379  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 14:23:35.379  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-17 14:23:35.389  1181  1712 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-17 14:23:35.379  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:35.389  1181  1181 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 14:23:35.379  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:35.379  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-17 14:23:35.379  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:35.379  1181  1181 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-17 14:23:35.389  1181  1181 D HotspotTile: onReceive : 3, 0
08-17 14:23:35.379  1181  1181 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3),
08-17 14:23:35.389  1323  1323 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-17 14:23:35.389  6291  6291 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:23:35.389  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:23:35.389  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:35.389  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED,
08-17 14:23:35.389  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:23:35.389  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:23:35.389  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:23:35.389  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:23:35.389  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 14:23:35.389  6291  6291 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 14:23:35.389  6291  6291 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 14:23:35.399  6291  6291 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:23:35.399  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:23:35.399  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:35.399  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:35.399  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:23:35.399  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:23:35.399  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:23:35.399  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:23:35.399  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 14:23:35.399  6291  6291 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:23:35.399  6291  6291 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 14:23:35.399  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-17 14:23:35.399  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
08-17 14:23:35.399  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-17 14:23:35.399  1017  1483 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-17 14:23:35.399  1017  1483 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 14:23:35.399  1017  1483 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:35.399  1017  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:35.399  1017  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 14:23:35.409  1017  1129 E WifiConfigStore: Not a HS20
08-17 14:23:35.409  6496  6496 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-17 14:23:35.409  3670  3670 I Hs20UtilService: Starting #13
08-17 14:23:35.409  6496  6496 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-17 14:23:35.409  6496  6496 D SecurityLogAgent: StateMachine : Current State = 1
08-17 14:23:35.409  6496  6496 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-17 14:23:35.409  3670  3711 I Hs20UtilService: Message received 5011
,08-17 14:23:35.409  1017  1129 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory),
,08-17 14:23:35.419  1017  1129 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-17 14:23:35.419  1017  1129 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-17 14:23:35.419  6788  6788 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-17 14:23:35.419  6788  6788 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-17 14:23:35.419  6788  6788 I wpa_supplicant: reset timer : RESET_TIMER 0
,08-17 14:23:35.419  6788  6788 I wpa_supplicant: P2P: Current p2p state = IDLE
08-17 14:23:35.419  6788  6788 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-17 14:23:35.419  6788  6788 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-17 14:23:35.419  6788  6788 I wpa_supplicant: First Scan Start
08-17 14:23:35.419  6788  6788 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-17 14:23:35.419  1017  1129 D WifiNative-wlan0: Setting external_sim to 1
,08-17 14:23:35.419  1017  1129 D WifiStateMachine: Setting OUI to DA-A1-19
08-17 14:23:35.419  1017  1129 I WifiNative-HAL: startHal
08-17 14:23:35.419  1017  1129 E wifi    : getStaticLongField sWifiHalHandle 0x9e11c88c
,08-17 14:23:35.419  1017  1129 I WifiNative-HAL: Could not start hal
08-17 14:23:35.419  6471  6471 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 14:23:35.419  1017  1129 E WifiNative-wlan0: do suspend true
,08-17 14:23:35.429  1017  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3,
08-17 14:23:35.429  1017  1128 D WifiP2pService: P2pDisabledState{ what=131203 }
08-17 14:23:35.429  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 3
08-17 14:23:35.429  1017  1152 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:23:35.429  1017  1152 I WifiNative-HAL: startHal
08-17 14:23:35.429  1017  1128 D WifiP2pService: P2pEnablingState
08-17 14:23:35.429  1017  1152 E wifi    : getStaticLongField sWifiHalHandle 0x9cdfe9bc
08-17 14:23:35.429  1017  1152 I WifiNative-HAL: Could not start hal
,08-17 14:23:35.429  1017  1128 D WifiP2pService: P2pEnablingState{ what=147457 }
08-17 14:23:35.429  1017  1152 E WifiScanningService: could not start HAL
08-17 14:23:35.429  1017  1128 D WifiP2pService: P2p socket connection successful
08-17 14:23:35.429  1017  1017 D RttService: SCAN_AVAILABLE : 3
08-17 14:23:35.429  1017  1128 D WifiP2pService: P2pEnabledState
08-17 14:23:35.429   278   986 D CommandListener: Setting iface cfg
08-17 14:23:35.429  1017  1153 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:23:35.429   278   986 D CommandListener: Trying to bring up p2p0
,08-17 14:23:35.429  1017  1128 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-17 14:23:35.429  1017  1131 E ConnectivityService: updateNetworkInfo(),
08-17 14:23:35.429  1017  1128 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-17 14:23:35.429  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-17 14:23:35.429  1017  1129 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-17 14:23:35.429  1017  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-17 14:23:35.429  1017  1129 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-17 14:23:35.429  1017  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-17 14:23:35.429  1017  1129 E WifiNative-wlan0: invaild command id : 215
08-17 14:23:35.429  1017  1048 D WifiDisplayController: disconnect
08-17 14:23:35.429  1017  1129 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-17 14:23:35.429  1017  1048 D WifiDisplayController: updateConnection
08-17 14:23:35.429  1017  1129 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
,08-17 14:23:35.429  1017  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-17 14:23:35.429  1017  1129 E WifiNative-wlan0: invaild command id : 215
08-17 14:23:35.429  1017  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-17 14:23:35.439  6788  6788 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-17 14:23:35.439  1017  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 14:23:35.439  1017  1048 D WifiDisplayAdapter: onP2pDisconnected
08-17 14:23:35.439  1017  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-17 14:23:35.439  1017  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
08-17 14:23:35.439  6788  6788 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-17 14:23:35.439  1181  1181 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-17 14:23:35.439  6788  6788 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,08-17 14:23:35.439  1017  1030 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-17 14:23:35.439  1181  1181 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-17 14:23:35.449  1017  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 14:23:35.449  1017  1129 D SecContentProvider2: mCursor = null
,08-17 14:23:35.449  1017  1128 D WifiNative-p2p0: p2pGetDeviceAddress
,08-17 14:23:35.449  1017  1128 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
,08-17 14:23:35.449  1323  1323 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-17 14:23:35.449  1323  1323 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-17 14:23:35.449  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-17 14:23:35.449  1017  1128 D WifiP2pService: DeviceAddress: 7e:96:ac
,08-17 14:23:35.449  1017  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 14:23:35.449  1017  1129 D SecContentProvider2: mCursor = null
08-17 14:23:35.449  1017  1048 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
08-17 14:23:35.449  1017  1048 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
08-17 14:23:35.449  1017  1048 D WifiDisplayController:  primary type: 10-0050F204-5
08-17 14:23:35.449  1017  1048 D WifiDisplayController:  secondary type: null
08-17 14:23:35.449  1017  1048 D WifiDisplayController:  wps: 0
08-17 14:23:35.449  1017  1048 D WifiDisplayController:  grpcapab: 0
08-17 14:23:35.449  1017  1048 D WifiDisplayController:  devcapab: 0
08-17 14:23:35.449  1017  1048 D WifiDisplayController:  status: 3
08-17 14:23:35.449  1017  1048 D WifiDisplayController:  wfdInfo: null
08-17 14:23:35.449  1017  1048 D WifiDisplayController:  groupownerAddress: null
08-17 14:23:35.449  1017  1048 D WifiDisplayController:  GOdeviceName: null
08-17 14:23:35.449  1017  1048 D WifiDisplayController:  interfaceAddress: 
08-17 14:23:35.449  1017  1048 D WifiDisplayController:  SConnectInfo : null
08-17 14:23:35.449  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-17 14:23:35.449  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 14:23:35.449  1323  1323 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-17 14:23:35.459  1323  3116 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 14:23:35.459  6441  6441 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-17 14:23:35.459  6441  6441 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-17 14:23:35.459  6441  6441 D FileShare-Client: Outbound.stopDelayTimer - 
,08-17 14:23:35.469  6456  6456 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-17 14:23:35.479  1017  1128 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-17 14:23:35.479  1017  1128 D WifiP2pService: InactiveState
,08-17 14:23:35.479  1017  1128 D WifiP2pService: InactiveState{ what=143376 }
,08-17 14:23:35.479  1017  1128 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-17 14:23:35.479  6788  6788 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
,08-17 14:23:35.479  1017  1128 D WifiP2pService: InactiveState{ what=143376 }
,08-17 14:23:35.479  1017  1128 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-17 14:23:35.839   290   290 E SMD     : DCD OFF,
,08-17 14:23:36.599  6788  6788 I wpa_supplicant: nl80211: Received scan results (28 BSSes),
,08-17 14:23:36.599  6788  6788 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-17 14:23:36.609  1017  6801 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
08-17 14:23:36.609  6788  6788 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-17 14:23:36.609  6788  6788 I wpa_supplicant: Trying to associate with  'G700'
,08-17 14:23:36.609  6788  6788 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,08-17 14:23:36.609  6788  6788 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,08-17 14:23:36.629  1017  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 14:23:36.629  1017  1129 D SecContentProvider2: mCursor = null
,08-17 14:23:36.719  6788  6788 E wpa_supplicant: Cmd 35605 not handled
,08-17 14:23:36.719  6788  6788 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-17 14:23:36.719  6788  6788 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,08-17 14:23:36.719  6788  6788 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-17 14:23:36.719  6788  6788 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-17 14:23:36.719  6788  6788 I wpa_supplicant: Associated with F4.99.3E
08-17 14:23:36.719  6788  6788 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-17 14:23:36.719  6788  6788 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-17 14:23:36.719  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
,08-17 14:23:36.719  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-17 14:23:36.719  6788  6788 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
08-17 14:23:36.719  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 14:23:36.719  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
,08-17 14:23:36.719  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 14:23:36.719  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
08-17 14:23:36.729  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 14:23:36.719  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 14:23:36.729  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-17 14:23:36.719  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
08-17 14:23:36.729  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, true
08-17 14:23:36.729  1017  1045 D Tethering: interfaceStatusChanged wlan0, true
08-17 14:23:36.729  6788  6788 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-17 14:23:36.729  6788  6788 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-17 14:23:36.729  6788  6788 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-17 14:23:36.729  6788  6788 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,08-17 14:23:36.739  6788  6788 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP],
08-17 14:23:36.739  6788  6788 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,08-17 14:23:36.739  6788  6788 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-17 14:23:36.739  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-17 14:23:36.739  1017  1133 E Tethering: No numeric data
08-17 14:23:36.739  6788  6788 I wpa_supplicant: Blacklist: Clear (temp) 
08-17 14:23:36.739  6788  6788 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-17 14:23:36.739  1017  1133 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-17 14:23:36.739  1017  1133 D Tethering: clearTetheredNotification()
08-17 14:23:36.739  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, true
,08-17 14:23:36.739  1017  1045 D Tethering: interfaceStatusChanged wlan0, true
08-17 14:23:36.739  1017  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 14:23:36.739  1017  1129 D SecContentProvider2: mCursor = null
,08-17 14:23:36.739  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 14:23:36.739  1017  1126 V NetworkStats: performPollLocked(flags=0x1)
,08-17 14:23:36.749  1181  1181 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-17 14:23:36.749  1017  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 14:23:36.749  1017  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-17 14:23:36.749  1181  1181 D HotspotTile: updateTetherState():false, false
,08-17 14:23:36.749  1017  1126 V NetworkStats: performPollLocked() took 5ms
08-17 14:23:36.749  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 14:23:36.749  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 14:23:36.749  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 14:23:36.759  1017  1129 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-17 14:23:36.759  1017  1129 E WifiConfigStore: setLastSelectedConfiguration -1
,08-17 14:23:36.769  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 14:23:36.769  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 14:23:36.769  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:36.769  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:36.769  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:36.769  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 14:23:36.769  1017  1129 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-17 14:23:36.769  1017  1131 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-17 14:23:36.769  1017  1131 E ConnectivityService: updateNetworkInfo()
08-17 14:23:36.769  1017  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-17 14:23:36.769  1017  1129 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 14:23:36.779  1017  2745 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-17 14:23:36.779  1017  2745 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 14:23:36.779  1017  2745 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:36.779  1017  2745 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:36.779  1017  2745 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 14:23:36.779  3670  3670 I Hs20UtilService: Starting #14
08-17 14:23:36.779  3670  3711 I Hs20UtilService: Message received 5007
,08-17 14:23:36.779  1323  1323 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-17 14:23:36.779  1323  1323 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-17 14:23:36.789  1017  1129 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 14:23:36.789  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-17 14:23:36.789  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-17 14:23:36.789  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 14:23:36.789  1323  1323 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-17 14:23:36.789  1323  3116 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 14:23:36.799   278   986 D CommandListener: Setting iface cfg
,08-17 14:23:36.809  1017  1129 E WifiStateMachine: Start Dhcp Watchdog 2
,08-17 14:23:36.809  1017  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-17 14:23:36.809  1017  1129 D SecContentProvider2: mCursor = null
,08-17 14:23:36.809  1017  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-17 14:23:36.809  1017  1129 D SecContentProvider2: mCursor = null
,08-17 14:23:36.819  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 14:23:36.819  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 14:23:36.819  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 14:23:36.819  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 14:23:36.829  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 14:23:36.829  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 14:23:36.829  1017  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-17 14:23:36.829  1017  1129 D SecContentProvider2: mCursor = null
,08-17 14:23:36.839  1017  1129 E WifiNative-wlan0: do suspend false
,08-17 14:23:36.839  1017  1128 D WifiP2pService: InactiveState{ what=143375 },
08-17 14:23:36.839  1017  1128 D WifiP2pService: P2pEnabledState{ what=143375 },
,08-17 14:23:37.019  1017  1030 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-17 14:23:37.019  1017  1030 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-17 14:23:37.019  1017  1030 D SecContentProvider2: mCursor = null
,08-17 14:23:37.019  1017  1030 D WifiService: setWifiEnabled: false pid=6291, uid=10155
08-17 14:23:37.019  1017  1030 D SettingsProvider: name = wifi_on
,08-17 14:23:37.029  1017  1129 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 14:23:37.039  1017  1129 E WifiNative-wlan0: do suspend true,
,08-17 14:23:37.049  6810  6810 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-17 14:23:37.049  6810  6810 I dhcpcd  : version 5.5.6 starting
,08-17 14:23:37.059  1017  1128 D WifiP2pService: InactiveState{ what=143375 }
,08-17 14:23:37.059  1017  1128 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-17 14:23:37.059   278   986 D CommandListener: Clearing all IP addresses on wlan0
08-17 14:23:37.059  6810  6810 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-17 14:23:37.059  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 14:23:37.059  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 14:23:37.059  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:37.059  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:37.059  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:37.059  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 14:23:37.069  1017  1131 E ConnectivityService: updateNetworkInfo()
08-17 14:23:37.069  1017  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 14:23:37.069  1017  1131 E ConnectivityService: updateNetworkInfo()
08-17 14:23:37.069  1017  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
08-17 14:23:37.069   278   986 E Netd    : no such netId 503
08-17 14:23:37.069  1017  1131 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '74 network destroy 503' failed with '400 74 destroyNetwork() failed (Machine is not on the network)'
08-17 14:23:37.069  1017  1131 D ConnectivityService: nai.networkMonitor.doQuit()
08-17 14:23:37.069  1017  1131 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-17 14:23:37.069  1017  1131 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-17 14:23:37.069  1017  1131 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
08-17 14:23:37.069  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-17 14:23:37.069  1017  1131 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-17 14:23:37.079  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 14:23:37.079  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-17 14:23:37.079  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:37.079  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:37.079  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:37.079  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 14:23:37.089  1017  1043 I ActivityManager: Killing 6147:com.samsung.helphub/1000 (adj 15): empty #31
,08-17 14:23:37.089  1017  1129 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-17 14:23:37.089  1017  1128 D WifiP2pService: InactiveState{ what=131204 }
08-17 14:23:37.089  1017  1131 E ConnectivityService: updateNetworkInfo()
08-17 14:23:37.089  1017  1128 D WifiP2pService: P2pEnabledState{ what=131204 }
08-17 14:23:37.089  1017  1131 E ConnectivityService: updateNetworkInfo()
08-17 14:23:37.089  1017  1128 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-17 14:23:37.089  1017  1129 E WifiNative-wlan0: do suspend true
08-17 14:23:37.089  1017  1128 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-17 14:23:37.089  1017  1128 D WifiP2pService: P2pDisablingState
08-17 14:23:37.099  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 1
08-17 14:23:37.089  1017  1128 D WifiP2pService: P2pDisablingState{ what=147458 }
08-17 14:23:37.099  1017  1152 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:23:37.089  1017  1128 D WifiP2pService: p2p socket connection lost
08-17 14:23:37.099  1017  1017 D RttService: SCAN_AVAILABLE : 1
08-17 14:23:37.089  1017  1128 D WifiP2pService: P2pDisabledState
,08-17 14:23:37.099  1017  1153 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-17 14:23:37.109  1017  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false],
08-17 14:23:37.109  1017  1048 D WifiDisplayAdapter: onP2pDisconnected
08-17 14:23:37.109  1017  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer,
08-17 14:23:37.109  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-17 14:23:37.109  1017  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
08-17 14:23:37.109  1017  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-17 14:23:37.109  1017  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-17 14:23:37.109  1017  1048 D WifiDisplayController: disconnect
08-17 14:23:37.109  1017  1048 D WifiDisplayController: updateConnection
,08-17 14:23:37.109  1017  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-17 14:23:37.109  1017  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-17 14:23:37.109  1181  1181 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-17 14:23:37.109  1017  3056 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 14:23:37.109  1017  3056 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-17 14:23:37.109  1017  2745 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-17 14:23:37.109  1181  1181 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-17 14:23:37.109  1017  3056 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:37.109  1017  3056 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:37.109  1017  3056 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 14:23:37.109  3670  3670 I Hs20UtilService: Starting #15
,08-17 14:23:37.119  3670  3711 I Hs20UtilService: Message received 5007
,08-17 14:23:37.119  1323  1323 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-17 14:23:37.119  1323  1323 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-17 14:23:37.119  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-17 14:23:37.119  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-17 14:23:37.119  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 14:23:37.119  1323  1323 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-17 14:23:37.119  1323  3116 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 14:23:37.129  1017  1128 D WifiP2pService: P2pDisabledState{ what=143375 }
08-17 14:23:37.129  1017  1128 D WifiP2pService: DefaultState{ what=143375 }
08-17 14:23:37.129   278   986 D CommandListener: Clearing all IP addresses on wlan0
,08-17 14:23:37.129  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 14:23:37.129  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 14:23:37.129  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:37.129  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:37.129  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:37.129  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 14:23:37.139  1323  1323 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-17 14:23:37.139  1323  1323 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-17 14:23:37.139  6810  6810 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-17 14:23:37.139  6810  6810 E dhcpcd  : wlan0: sendmsg: Network is unreachable
08-17 14:23:37.139  6810  6810 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-17 14:23:37.139  6810  6810 I dhcpcd  : bssid match
08-17 14:23:37.139  6810  6810 I dhcpcd  : wlan0: rebinding lease of 192.168.1.111,
08-17 14:23:37.139  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-17 14:23:37.139  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-17 14:23:37.149  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-17 14:23:37.149  6788  6788 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-17 14:23:37.149  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-17 14:23:37.149  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 14:23:37.149  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 14:23:37.149  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:37.149  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:37.149  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:37.149  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 14:23:37.159  1323  1323 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-17 14:23:37.159  1323  3116 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 14:23:37.159  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 14:23:37.159  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-17 14:23:37.159  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:37.159  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:37.159  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:37.159  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:37.159  1181  1181 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 14:23:37.159  1181  1181 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-17 14:23:37.159  1181  1181 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-17 14:23:37.159  1181  1712 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-17 14:23:37.159  1181  1181 D HotspotTile: onReceive : 0, 0
,08-17 14:23:37.159  1323  1323 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-17 14:23:37.169  6291  6291 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 14:23:37.169  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:23:37.169  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:37.169  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:37.169  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:23:37.169  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:23:37.169  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:23:37.169  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:23:37.169  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 14:23:37.169  6291  6291 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:23:37.169  6291  6291 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 14:23:37.169  1017  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 14:23:37.169  1017  1129 D SecContentProvider2: mCursor = null
,08-17 14:23:37.169  6291  6291 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 14:23:37.169  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:23:37.169  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:37.169  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:37.169  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:23:37.169  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:23:37.169  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:23:37.169  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:23:37.169  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 14:23:37.169  6291  6291 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 14:23:37.169  6291  6291 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 14:23:37.169  6441  6441 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-17 14:23:37.179  6441  6441 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-17 14:23:37.179  6441  6441 D FileShare-Client: Outbound.stopDelayTimer - 
,08-17 14:23:37.179  6456  6456 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-17 14:23:37.189  1017  1344 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-17 14:23:37.189  1017  1344 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 14:23:37.189  1017  1344 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:37.189  1017  1344 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:37.189  1017  1344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 14:23:37.199  3670  3670 I Hs20UtilService: Starting #16
08-17 14:23:37.199  1323  1323 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-17 14:23:37.199  1323  1323 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-17 14:23:37.199  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-17 14:23:37.199  3670  3711 I Hs20UtilService: Message received 5007
08-17 14:23:37.199  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-17 14:23:37.199  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-17 14:23:37.199  1323  1323 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-17 14:23:37.199  1323  3116 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 14:23:37.209  1017  1531 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-17 14:23:37.209  1017  1531 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 14:23:37.209  1017  1531 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:37.209  1017  1531 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:37.209  1017  1531 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 14:23:37.209  6810  6810 I dhcpcd  : wlan0: acknowledged 192.168.1.111 from 192.168.1.1
08-17 14:23:37.209  3670  3670 I Hs20UtilService: Starting #17
,08-17 14:23:37.209  3670  3711 I Hs20UtilService: Message received 5011
,08-17 14:23:37.209  6496  6496 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-17 14:23:37.209  6496  6496 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-17 14:23:37.209  6496  6496 D SecurityLogAgent: StateMachine : Current State = 1
08-17 14:23:37.209  6496  6496 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 14:23:37.229  6788  6788 I wpa_supplicant: Blacklist: Clear (all) 
,08-17 14:23:37.289  6788  6788 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-17 14:23:37.289  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-17 14:23:37.289  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-17 14:23:37.289  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-17 14:23:37.309  6788  6788 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-17 14:23:37.309  6788  6788 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-17 14:23:37.309  6788  6788 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-17 14:23:37.309  6788  6788 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-17 14:23:37.309  6788  6788 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-17 14:23:37.309  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
,08-17 14:23:37.309  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-17 14:23:37.309  1017  1129 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14956 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
,08-17 14:23:37.319  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-17 14:23:37.319  1017  1133 D Tethering: InitialState.processMessage what=4
,08-17 14:23:37.319  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false,
08-17 14:23:37.319  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-17 14:23:37.369  6810  6810 I dhcpcd  : wlan0: leased 192.168.1.111 for 172800 seconds,
,08-17 14:23:37.419  1017  1050 I PowerManagerService: [PWL] Off : 75s ago
,08-17 14:23:37.419  1017  1050 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
08-17 14:23:37.419  1017  1050 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
08-17 14:23:37.419  1017  1050 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1017, ws=null) (elapsedTime=6033)
,08-17 14:23:37.439  1017  3056 I art     : Explicit concurrent mark sweep GC freed 69652(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/41MB, paused 2.651ms total 161.055ms
,08-17 14:23:37.439  1017  1133 E Tethering: No numeric data
,08-17 14:23:37.439  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 14:23:37.439  1017  1133 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-17 14:23:37.439  1017  1133 D Tethering: clearTetheredNotification()
,08-17 14:23:37.439  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 14:23:37.439  1017  1126 V NetworkStats: performPollLocked(flags=0x1)
08-17 14:23:37.439  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 14:23:37.439  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 14:23:37.439  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
08-17 14:23:37.439  1181  1181 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-17 14:23:37.439  1181  1181 D HotspotTile: updateTetherState():false, false
,08-17 14:23:37.439  1017  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 14:23:37.439  1017  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 14:23:37.449  1017  1126 V NetworkStats: performPollLocked() took 8ms
,08-17 14:23:37.449  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 14:23:37.449  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 14:23:37.449  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 14:23:37.579  6788  6788 I wpa_supplicant: Blacklist: Clear (all) 
,08-17 14:23:37.719  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false,
08-17 14:23:37.719  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
08-17 14:23:37.719  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-17 14:23:37.719  6788  6788 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-17 14:23:37.719  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 14:23:37.719  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 14:23:37.719  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-17 14:23:37.819  1017  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-17 14:23:37.829  1017  1129 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-17 14:23:37.829  1017  1129 E WifiConfigStore: setLastSelectedConfiguration -1
,08-17 14:23:37.829  6471  6471 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 14:23:37.839  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 14:23:37.839  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-17 14:23:37.839  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:37.839  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:37.839  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:37.839  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:37.839  1181  1181 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 14:23:37.839  1181  1181 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-17 14:23:37.839  1181  1712 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-17 14:23:37.839  1181  1181 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-17 14:23:37.839  1181  1181 D HotspotTile: onReceive : 1, 0
08-17 14:23:37.839  1934  2129 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 14:23:37.839  1323  1323 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-17 14:23:37.839  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:37.839  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:37.849  1017  1343 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 14:23:37.849  1017  1343 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 14:23:37.849  1017  1343 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:37.849  1017  1343 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:37.849  1017  1343 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 14:23:37.859  6496  6496 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-17 14:23:37.859  6496  6496 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-17 14:23:37.859  6496  6496 D SecurityLogAgent: StateMachine : Current State = 1
08-17 14:23:37.859  6496  6496 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 14:23:37.859  3670  3670 I Hs20UtilService: Starting #18
,08-17 14:23:37.859  3670  3711 I Hs20UtilService: Message received 5011
,08-17 14:23:38.439   278   978 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,08-17 14:23:38.439  1017  1045 D Tethering: interfaceRemoved wlan0
,08-17 14:23:38.439  1017  1045 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-17 14:23:38.579  1017  2745 D ActivityManager: bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,08-17 14:23:38.579  1017  2745 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,08-17 14:23:38.579  1017  2745 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:38.579  1017  2745 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 14:23:38.579  1017  2745 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-17 14:23:38.589  6637  6681 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-17 14:23:38.609  1017  1043 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:38.609  1017  1043 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 14:23:38.609  1017  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-17 14:23:38.619  1017  1030 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,08-17 14:23:38.619  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,08-17 14:23:38.619  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:38.619  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 14:23:38.619  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-17 14:23:38.629  1017  1727 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:38.629  1017  1727 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 14:23:38.629  1017  1727 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-17 14:23:38.639  1017  3207 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-17 14:23:38.639  1017  3207 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,08-17 14:23:38.649  1017  3207 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:38.649  1017  3207 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 14:23:38.649  1017  3207 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-17 14:23:38.649  1017  1505 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-17 14:23:38.649  1017  1505 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,08-17 14:23:38.649  1017  1505 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:38.649  1017  1505 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-17 14:23:38.649  1017  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-17 14:23:38.659  1017  1485 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-17 14:23:38.659  1017  1485 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-17 14:23:38.659  1017  1485 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:38.659  1017  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 14:23:38.659  1017  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-17 14:23:38.679  1017  1079 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,08-17 14:23:38.679  1017  1079 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,08-17 14:23:38.679  1017  1079 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:38.679  1017  1079 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 14:23:38.679  1017  1079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-17 14:23:38.689  1017  1045 D Tethering: interfaceRemoved p2p0
08-17 14:23:38.689  1017  1045 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-17 14:23:38.709  1017  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 14:23:38.719  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:38.719  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 14:23:38.719  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,08-17 14:23:38.719  1934  1934 D WearableService: callingUid 10012, callindPid: 1934
,08-17 14:23:38.739  1017  3207 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-17 14:23:38.739  1017  3207 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
08-17 14:23:38.739  1017  3207 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:38.739  1017  3207 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 14:23:38.739  1017  3207 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-17 14:23:38.759  6549  6842 I MusicLeanback: Conditions not met for autocaching.
08-17 14:23:38.759  6549  6842 I MusicLeanback: Stop autocaching.
,08-17 14:23:38.779  6549  6549 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,08-17 14:23:38.779  6549  6847 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,08-17 14:23:38.839   290   290 E SMD     : DCD OFF
,08-17 14:23:39.509  1017  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-17 14:23:39.929  1017  3057 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-17 14:23:39.929  1017  3057 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4256, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,08-17 14:23:39.929  1017  3057 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-17 14:23:39.929  1017  3057 D BatteryService: stay LED for charging
,08-17 14:23:39.929  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-17 14:23:39.929  1017  1017 I MotionRecognitionService: Plugged
,08-17 14:23:39.929  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-17 14:23:39.939  1181  1181 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-17 14:23:39.939  1181  1181 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-17 14:23:39.939  1421  1421 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-17 14:23:39.939  1421  1421 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-17 14:23:39.969  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-17 14:23:39.969  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-17 14:23:39.969  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-17 14:23:40.029  6291  6344 D BluetoothAdapter: enable()
,08-17 14:23:40.029  1017  3205 W ActivityManager: Permission Denial: getCurrentUser() from pid=6291, uid=10155 requires android.permission.INTERACT_ACROSS_USERS,
,08-17 14:23:40.029  1017  3205 W BluetoothManagerService: Failed getting userId using ActivityManagerNative,
08-17 14:23:40.029  1017  3205 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6291, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-17 14:23:40.029  1017  3205 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-17 14:23:40.029  1017  3205 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
08-17 14:23:40.029  1017  3205 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
08-17 14:23:40.029  1017  3205 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
08-17 14:23:40.029  1017  3205 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
08-17 14:23:40.029  1017  3205 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-17 14:23:40.029  1017  3205 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 14:23:40.039  1017  3205 D SettingsProvider: name = bluetooth_on
,08-17 14:23:40.039  1017  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 14:23:40.039  1017  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 14:23:40.039  1017  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,08-17 14:23:40.039  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-17 14:23:40.069  6515  6515 D BluetoothAdapterState: make
,08-17 14:23:40.079  6515  6515 I bluedroid: init
,08-17 14:23:40.079  6515  6850 I BluetoothAdapterState: Entering OffState,
,08-17 14:23:40.079  6515  6515 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf,
,08-17 14:23:40.089  6515  6515 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-17 14:23:40.089  6515  6515 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-17 14:23:40.089  6515  6515 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-17 14:23:40.089  6515  6515 E bt-btif : btif_fetch_local_ble_random_bdaddr
,08-17 14:23:40.089  6515  6515 I bluedroid: get_profile_interface socket
08-17 14:23:40.089  6515  6515 I bluedroid: get_profile_interface map_client
,08-17 14:23:40.089  6515  6853 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-17 14:23:40.089  6515  6515 D BluetoothAdapterService: checkAddrForIOP: Loading from conf,
,08-17 14:23:40.099  6515  6853 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,08-17 14:23:40.099  6515  6853 E BluetoothServiceJni: populateRssiValuesNative
,08-17 14:23:40.099  6515  6853 I bluedroid: getModelRssiValues
08-17 14:23:40.099  6515  6853 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-17 14:23:40.099  6515  6853 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-17 14:23:40.099  6515  6515 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-17 14:23:40.099  1017  2745 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-17 14:23:40.099  1017  2745 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 14:23:40.099  1017  2745 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:40.099  1017  2745 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:40.099  1017  2745 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:40.099  6515  6853 D BluetoothAdapterProperties: Name is: A5-1
,08-17 14:23:40.099  1017  1017 D SettingsProvider: name = bluetooth_name
,08-17 14:23:40.109  6515  6526 I bluedroid: config_hci_snoop_log
,08-17 14:23:40.109  1017  1047 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,08-17 14:23:40.109  1017  1047 D BluetoothManagerService: Ble is always on enable gatt
,08-17 14:23:40.109  1017  1047 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-17 14:23:40.109  1017  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-17 14:23:40.109  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-17 14:23:40.119  6515  6515 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-17 14:23:40.129  1017  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-17 14:23:40.129  1017  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 14:23:40.139  1017  1047 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-17 14:23:40.139  6515  6850 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-17 14:23:40.139  6515  6850 D BluetoothAdapterProperties: Setting state to 11
,08-17 14:23:40.139  6515  6850 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-17 14:23:40.139  6515  6850 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-17 14:23:40.139  6515  6850 D BluetoothAdapterService: updateAdapterState state is 11
,08-17 14:23:40.139  6515  6850 D BluetoothAdapterService: Autoconnection is available 
08-17 14:23:40.139  6515  6850 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-17 14:23:40.149  1017  1047 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-17 14:23:40.149  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-17 14:23:40.149  1017  1017 I InputMethodManagerService: [BT Setting State] State =11
,08-17 14:23:40.149  1797  1797 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-17 14:23:40.159  1181  1181 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-17 14:23:40.159  6515  6850 D BluetoothSecureManager: getInstant: null
08-17 14:23:40.159  6515  6850 D BluetoothSecureManager: calling getMethod for getService
08-17 14:23:40.159  6515  6850 D BluetoothSecureManager: calling getService
,08-17 14:23:40.159  6515  6850 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@220fa16f
08-17 14:23:40.159  1017  3207 D BluetoothSecureManagerService: isSecureModeEnabled
08-17 14:23:40.159  1017  3207 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
08-17 14:23:40.159  1181  1181 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:23:40.159  6515  6850 D BtConfig.SecureMode: isSecureModeOn:false
08-17 14:23:40.159  6515  6850 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-17 14:23:40.159  1181  1181 D BluetoothTile:  getBluetoothState : 11
,08-17 14:23:40.159  1323  1323 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:23:40.159  6515  6850 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-17 14:23:40.159  6515  6850 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-17 14:23:40.159  6515  6850 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
,08-17 14:23:40.159  6515  6850 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-17 14:23:40.169  1017  1531 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-17 14:23:40.169  1017  1531 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-17 14:23:40.169  1181  1712 D BluetoothTile:  handleUpdatestate:false name:null
08-17 14:23:40.169  1181  1712 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-17 14:23:40.169  1017  1531 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:40.169  6515  6850 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-17 14:23:40.169  6515  6850 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-17 14:23:40.169  1017  1531 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 14:23:40.169  1017  1531 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 14:23:40.169  6515  6850 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-17 14:23:40.169  6515  6850 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-17 14:23:40.169  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:40.169  6515  6850 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-17 14:23:40.169  6515  6850 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-17 14:23:40.169  6515  6850 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-17 14:23:40.169  6515  6850 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-17 14:23:40.169  6515  6850 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-17 14:23:40.169  6515  6850 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-17 14:23:40.179  1017  3205 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 14:23:40.179  1017  1030 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-17 14:23:40.179  1181  1181 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-17 14:23:40.179  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:40.179  6515  6850 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-17 14:23:40.179  6515  6850 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-17 14:23:40.179  1323  1323 D BluetoothNotiBroadcastReceiver: onReceive
08-17 14:23:40.179  6515  6850 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-17 14:23:40.179  6515  6850 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-17 14:23:40.179  6515  6850 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-17 14:23:40.179  6515  6850 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-17 14:23:40.179  6515  6850 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-17 14:23:40.179  6515  6850 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-17 14:23:40.179  6515  6850 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-17 14:23:40.179  6515  6850 D BluetoothBondStateMachine: make
,08-17 14:23:40.179  6515  6850 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-17 14:23:40.179  6515  6850 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-17 14:23:40.179  6515  6850 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-17 14:23:40.189  6515  6856 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-17 14:23:40.189  1017  1222 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 14:23:40.189  1181  1181 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:23:40.189  1181  1181 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-17 14:23:40.189  1017  1222 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-17 14:23:40.189  1017  1222 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:40.189  1017  1222 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:40.189  1017  1222 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:40.189  6515  6850 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService,
08-17 14:23:40.189  6515  6850 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-17 14:23:40.189  6515  6850 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-17 14:23:40.189  6515  6515 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 14:23:40.189  6515  6515 D BtGatt.GattService: Received start request. Starting profile...
,08-17 14:23:40.189  6515  6515 D BtGatt.GattService: start()
08-17 14:23:40.189  6515  6515 D BtGatt.GattService: start()
08-17 14:23:40.189  6515  6515 I bluedroid: get_profile_interface gatt
,08-17 14:23:40.189  6515  6515 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d6b0b11
08-17 14:23:40.189  6515  6515 D BtGatt.AdvertiseManager: advertise manager created
,08-17 14:23:40.199  1017  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-17 14:23:40.199  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-17 14:23:40.199  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:40.199  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:40.199  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:40.199  6515  6850 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,08-17 14:23:40.199  6515  6850 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-17 14:23:40.199  6515  6850 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-17 14:23:40.209  1017  3057 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 14:23:40.209  1017  3057 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 14:23:40.209  6515  6515 D BtGatt.GattService: mStartError = false
08-17 14:23:40.209  6515  6515 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d6b0b11
,08-17 14:23:40.209  1017  3057 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:40.209  1017  3057 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:40.209  1017  3057 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:40.209  6515  6515 D HeadsetService: Received start request. Starting profile...
,08-17 14:23:40.209  6515  6515 D HeadsetService: start()
,08-17 14:23:40.209  6515  6850 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-17 14:23:40.209  6515  6850 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-17 14:23:40.209  6515  6850 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-17 14:23:40.209  1017  1531 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 14:23:40.209  1017  1531 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-17 14:23:40.209  6515  6515 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-17 14:23:40.209  6515  6515 D HeadsetStateMachine: make
08-17 14:23:40.219  1017  1531 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:40.219  1017  1531 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:40.219  1017  1531 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:40.219  6515  6850 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-17 14:23:40.219  6515  6515 E HeadsetStateMachine: # of Max HF connection is 2
,08-17 14:23:40.219  6515  6850 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-17 14:23:40.219  6515  6850 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-17 14:23:40.219  1017  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 14:23:40.219  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-17 14:23:40.219  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:40.219  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:40.219  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:40.229  6515  6850 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-17 14:23:40.229  6515  6850 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-17 14:23:40.229  6515  6850 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-17 14:23:40.229  1017  1222 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-17 14:23:40.229  1017  1222 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-17 14:23:40.229  1017  1222 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:40.229  1017  1222 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 14:23:40.229  1017  1222 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-17 14:23:40.229  1017  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 14:23:40.229  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-17 14:23:40.229  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:40.229  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 14:23:40.229  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:40.229  1017  1222 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-17 14:23:40.239  6515  6850 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-17 14:23:40.239  1017  1222 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
08-17 14:23:40.239  6515  6850 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 14:23:40.239  6515  6850 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-17 14:23:40.239  1017  1222 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:40.239  1017  1222 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:40.239  1017  1222 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-17 14:23:40.239  1017  1344 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 14:23:40.239  6515  6515 I bluedroid: get_profile_interface handsfree
,08-17 14:23:40.239  1017  1344 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-17 14:23:40.239  1017  1344 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:40.239  1017  1344 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:40.239  1017  1344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:40.239  6515  6850 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-17 14:23:40.239  6515  6850 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-17 14:23:40.239  6515  6850 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-17 14:23:40.239  1017  3207 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 14:23:40.239  1017  3207 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-17 14:23:40.239  1017  3207 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:40.239  1017  3207 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:40.239  1017  3207 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:40.239  6515  6850 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-17 14:23:40.249  6515  6850 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-17 14:23:40.249  6515  6850 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-17 14:23:40.249  6515  6850 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-17 14:23:40.249  6515  6850 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-17 14:23:40.249  6515  6850 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-17 14:23:40.249  6515  6850 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-17 14:23:40.249  6515  6850 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-17 14:23:40.249  6515  6850 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-17 14:23:40.249  6515  6850 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-17 14:23:40.249  6515  6850 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-17 14:23:40.249  6515  6850 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-17 14:23:40.249  6515  6850 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-17 14:23:40.249  6515  6515 I DualScoManager: Instantiating Dual Sco Manager
08-17 14:23:40.249  6515  6515 I DualScoManager: Set HeadsetServiceHelper
,08-17 14:23:40.259  6515  6515 D BluetoothAtMessage: createCMTIContentObservers
,08-17 14:23:40.259  1017  1343 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-17 14:23:40.259  1017  1343 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 14:23:40.259  1017  1343 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 14:23:40.259  1017  1343 D SettingsProvider: selectionArgs: false
08-17 14:23:40.259  1017  1343 D SettingsProvider: selectionArgs: 1002
08-17 14:23:40.259  1017  1343 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 14:23:40.259  1017  1343 D SettingsProvider: ret = -1
,08-17 14:23:40.259  6515  6859 D HeadsetStateMachine: Enter Disconnected: -2
,08-17 14:23:40.259  6515  6515 D HeadsetService: mStartError = false
08-17 14:23:40.259  6515  6515 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d6b0b11
,08-17 14:23:40.259  6515  6515 E BluetoothAdapterService(1030425361): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-17 14:23:40.269  6515  6515 D A2dpService: Received start request. Starting profile...
08-17 14:23:40.269  6515  6515 D A2dpService: start()
,08-17 14:23:40.269  6515  6859 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-17 14:23:40.269  6515  6515 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-17 14:23:40.269  6515  6859 D HeadsetStateMachine: map size, before remove : 0
08-17 14:23:40.269  6515  6859 D HeadsetStateMachine: map size, after remove: 0
,08-17 14:23:40.269  6515  6515 I bluedroid: get_profile_interface avrcp
,08-17 14:23:40.269  1934  1934 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-17 14:23:40.279  6515  6515 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-17 14:23:40.279  1934  1934 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-17 14:23:40.299  6515  6515 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-17 14:23:40.299  6515  6863 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
08-17 14:23:40.299  6515  6515 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-17 14:23:40.299  6515  6515 D A2dpStateMachine: make
,08-17 14:23:40.299  6515  6515 I bluedroid: get_profile_interface a2dp
08-17 14:23:40.299  6515  6865 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-17 14:23:40.299  6515  6515 E bt-btif : warning : media task started media_task_refcnt 1 
,08-17 14:23:40.299  6515  6515 D A2dpService: mStartError = false
08-17 14:23:40.299  6515  6515 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d6b0b11
,08-17 14:23:40.299  6515  6864 D A2dpStateMachine: Enter Disconnected: -2
,08-17 14:23:40.299  6515  6515 I BluetoothHidServiceJni: classInitNative: succeeds
,08-17 14:23:40.299  6515  6515 D HidService: Received start request. Starting profile...
08-17 14:23:40.299  6515  6515 D HidService: start()
,08-17 14:23:40.309  6515  6515 I bluedroid: get_profile_interface hidhost
08-17 14:23:40.309  6515  6515 D HidService: setHidService(): set to: null
,08-17 14:23:40.309  6515  6515 D HidService: mStartError = false
08-17 14:23:40.309  6515  6515 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d6b0b11
,08-17 14:23:40.309  6515  6515 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-17 14:23:40.309  6515  6515 D HealthService: Received start request. Starting profile...
08-17 14:23:40.309  6515  6515 D HealthService: start()
,08-17 14:23:40.309  6515  6515 I bluedroid: get_profile_interface health
,08-17 14:23:40.309  6515  6515 D HealthService: mStartError = false
08-17 14:23:40.309  6515  6515 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d6b0b11
,08-17 14:23:40.309  6515  6515 D HeadsetStateMachine: Try to query the phonestate on bind
,08-17 14:23:40.309  1436  2754 I Telecom : BluetoothPhoneService: queryPhoneState
,08-17 14:23:40.309  1436  1436 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-17 14:23:40.309  1436  1436 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-17 14:23:40.309  1436  2754 I Telecom : BluetoothPhoneService: Result of Message : true
,08-17 14:23:40.319  6515  6515 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-17 14:23:40.319  6515  6515 D PanService: Received start request. Starting profile...
08-17 14:23:40.319  6515  6515 D PanService: start()
08-17 14:23:40.319  6515  6515 D BluetoothPanServiceJni: initializeNative(L110): pan
08-17 14:23:40.319  6515  6515 I bluedroid: get_profile_interface pan
,08-17 14:23:40.319  6515  6515 D PanService: mStartError = false
08-17 14:23:40.319  6515  6515 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d6b0b11
,08-17 14:23:40.319  6515  6515 D HeadsetStateMachine: Proxy object connected
,08-17 14:23:40.319  6515  6863 D BluetoothMediaBrowser: no now playing list
,08-17 14:23:40.319  6515  6863 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
08-17 14:23:40.319  6515  6515 D BluetoothMapService: Received start request. Starting profile...
,08-17 14:23:40.319  6515  6515 D BluetoothMapService: start()
,08-17 14:23:40.319  6515  6515 D BluetoothMapService: mStartError = false
08-17 14:23:40.319  6515  6515 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d6b0b11
,08-17 14:23:40.329  6515  6515 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-17 14:23:40.329  6515  6515 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-17 14:23:40.329  6515  6859 D HeadsetStateMachine: Disconnected process message: 11
08-17 14:23:40.329  6515  6515 D SapService: Received start request. Starting profile...
,08-17 14:23:40.329  6515  6515 D SapService: start()
08-17 14:23:40.329  6515  6515 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-17 14:23:40.329  6515  6515 I bluedroid: get_profile_interface sap
08-17 14:23:40.329  6515  6515 D SapService: mStartError = false
08-17 14:23:40.329  6515  6515 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d6b0b11
08-17 14:23:40.329  6515  6515 D HeadsetPhoneState: sendDeviceDataStateChanged
08-17 14:23:40.329  6515  6515 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-17 14:23:40.329  6515  6515 E BluetoothAdapterService(1030425361): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-17 14:23:40.329  6515  6515 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-17 14:23:40.329  6515  6515 D BluetoothA2dp: Proxy object connected
08-17 14:23:40.329  6515  6515 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-17 14:23:40.329  6515  6515 E BluetoothAdapterService(1030425361): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-17 14:23:40.329  6515  6515 E BluetoothAdapterService(1030425361): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-17 14:23:40.329  6515  6515 E BluetoothAdapterService(1030425361): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-17 14:23:40.329  6515  6515 E BluetoothAdapterService(1030425361): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-17 14:23:40.329  6515  6859 D HeadsetStateMachine: Disconnected process message: 18
,08-17 14:23:40.329  6515  6859 D HeadsetStateMachine: Disconnected process message: 10
,08-17 14:23:40.329  6515  6859 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-17 14:23:40.329  6515  6859 D HeadsetStateMachine: Disconnected process message: 11
,08-17 14:23:40.359  6515  6515 E BluetoothAdapterService(1030425361): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-17 14:23:40.359  6515  6515 E BluetoothAdapterService(1030425361): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-17 14:23:40.359  6515  6850 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-17 14:23:40.359  6515  6850 I bluedroid: enable
,08-17 14:23:40.369  6515  6870 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-17 14:23:40.369  6515  6850 I bt_hci_bdroid: init
,08-17 14:23:40.379  6515  6850 I bt_vendor: bt-vendor : init
,08-17 14:23:40.379  6515  6850 I bt_vendor: bt-vendor : get_bt_soc_type
08-17 14:23:40.379  6515  6850 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-17 14:23:40.379  6515  6850 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
08-17 14:23:40.379  6515  6850 D bt_userial_mct: userial_init
,08-17 14:23:40.379  6515  6850 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-17 14:23:40.379  6515  6850 I bt_vendor: Starting hciattach daemon
08-17 14:23:40.379  6515  6850 I bt_vendor: try to set false
,08-17 14:23:40.379  6515  6850 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On,
08-17 14:23:40.379  6515  6850 I bt_vendor: Starting hciattach daemon
08-17 14:23:40.379  6515  6850 I bt_vendor: try to set true
,08-17 14:23:40.399  6874  6874 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-17 14:23:40.449  6880  6880 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-17 14:23:40.459  6881  6881 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-17 14:23:40.469  6883  6883 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-17 14:23:40.479  6884  6884 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-17 14:23:40.489  6885  6885 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-17 14:23:40.499  6886  6886 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-17 14:23:40.739  6889  6889 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab ,
,08-17 14:23:40.749  6890  6890 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-17 14:23:40.789  6515  6850 I bt_vendor: bluetooth satus is on,
08-17 14:23:40.789  6515  6872 D bt_userial_mct: userial_open(port:0)
08-17 14:23:40.789  6515  6872 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-17 14:23:40.789  6515  6872 I bt_vendor: Done intiailizing UART,
,08-17 14:23:40.789  6515  6872 I bt_vendor: Done intiailizing UART
08-17 14:23:40.799  6515  6872 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67,
08-17 14:23:40.799  6515  6872 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-17 14:23:40.799  6515  6893 D bt_userial_mct: Entering userial_read_thread()
,08-17 14:23:40.809  6515  6870 I         : BTE_InitTraceLevels -- TRC_HCI
,08-17 14:23:40.809  6515  6870 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-17 14:23:40.809  6515  6870 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-17 14:23:40.809  6515  6870 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-17 14:23:40.809  6515  6870 I         : BTE_InitTraceLevels -- TRC_AVRC
08-17 14:23:40.809  6515  6870 I         : BTE_InitTraceLevels -- TRC_A2D
08-17 14:23:40.809  6515  6870 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-17 14:23:40.809  6515  6870 I         : BTE_InitTraceLevels -- TRC_BTM
08-17 14:23:40.809  6515  6870 I         : BTE_InitTraceLevels -- TRC_GAP
,08-17 14:23:40.809  6515  6870 I         : BTE_InitTraceLevels -- TRC_PAN
08-17 14:23:40.809  6515  6870 I         : BTE_InitTraceLevels -- TRC_SAP
08-17 14:23:40.809  6515  6870 I         : BTE_InitTraceLevels -- TRC_SDP
,08-17 14:23:40.809  6515  6870 I         : BTE_InitTraceLevels -- TRC_GATT
08-17 14:23:40.809  6515  6870 I         : BTE_InitTraceLevels -- TRC_SMP
,08-17 14:23:40.809  6515  6870 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-17 14:23:40.809  6515  6870 I         : BTE_InitTraceLevels -- TRC_BTIF
08-17 14:23:40.809  6515  6870 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-17 14:23:40.909  6515  6870 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-17 14:23:40.919  6515  6870 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa3faa6e9 
,08-17 14:23:40.919  6515  6870 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3faa6e9 
,08-17 14:23:40.939  6515  6853 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-17 14:23:40.939  6515  6853 E bt-btif : Calling BTA_HhEnable
,08-17 14:23:40.939  6515  6853 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-17 14:23:40.939  6515  6853 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,08-17 14:23:40.939  6515  6853 E BluetoothServiceJni: populateRssiValuesNative
08-17 14:23:40.939  6515  6853 I bluedroid: getModelRssiValues
,08-17 14:23:40.939  6515  6853 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-17 14:23:40.939  6515  6853 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-17 14:23:40.949  6515  6853 D BluetoothAdapterProperties: Name is: A5-1
,08-17 14:23:40.949  1017  1017 D SettingsProvider: name = bluetooth_name
,08-17 14:23:40.949  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:40.959  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-17 14:23:40.959  6515  6853 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-17 14:23:40.959  6515  6853 D BluetoothAdapterProperties: Scan Mode:20
08-17 14:23:40.959  6515  6853 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-17 14:23:40.959  6515  6853 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
08-17 14:23:40.959  6515  6853 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-17 14:23:40.959  6515  6853 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
08-17 14:23:40.959  6515  6853 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-17 14:23:40.959  6515  6853 E bt-btif : btif_sock_init: !vhci_init
,08-17 14:23:40.959  6515  6853 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
08-17 14:23:40.959  6515  6853 D IOP_DB_BT: db_open: db_open : handle 3028439056l, read 13894 bytes onto local cache
,08-17 14:23:40.959  6515  6853 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
08-17 14:23:40.959  6515  6853 D IOP_DB_BT: db_query: result 1
08-17 14:23:40.959  6515  6853 I         : iop_db_open: iop_db_open status 0
,08-17 14:23:40.959  6515  6853 D bte_conf: Device ID record 1 : primary
,08-17 14:23:40.959  6515  6853 D bte_conf:   vendorId            = 0075
08-17 14:23:40.959  6515  6853 D bte_conf:   vendorIdSource      = 0001
08-17 14:23:40.959  6515  6853 D bte_conf:   product             = 0100
08-17 14:23:40.959  6515  6853 D bte_conf:   version             = 0200
08-17 14:23:40.959  6515  6853 D bte_conf:   clientExecutableURL = 
08-17 14:23:40.959  6515  6853 D bte_conf:   serviceDescription  = 
08-17 14:23:40.959  6515  6853 D bte_conf:   documentationURL    = 
08-17 14:23:40.959  6515  6853 D bte_conf: bte_load_did_conf no section named DID2.
,08-17 14:23:40.959  6515  6853 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-17 14:23:40.959  6515  6850 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-17 14:23:40.959  6515  6850 D BluetoothAdapterProperties: ScanMode =  20
,08-17 14:23:40.959  6515  6850 D BluetoothAdapterProperties: State =  11
,08-17 14:23:40.969  1017  1727 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-17 14:23:40.969  6515  6893 E bt_mct  : hci lib postload completed
08-17 14:23:40.969  6515  6850 D BluetoothAdapterProperties: Setting state to 12
08-17 14:23:40.969  6515  6850 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-17 14:23:40.969  6515  6853 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-17 14:23:40.969  6515  6853 D BluetoothAdapterProperties: Scan Mode:21
08-17 14:23:40.969  6515  6853 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-17 14:23:40.969  1017  1344 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-17 14:23:40.969  1017  1344 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 14:23:40.969  1017  1344 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 14:23:40.969  1017  1344 D SettingsProvider: selectionArgs: false
08-17 14:23:40.969  1017  1344 D SettingsProvider: selectionArgs: 1002
08-17 14:23:40.969  1017  1344 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 14:23:40.969  1017  1344 D SettingsProvider: ret = -1
,08-17 14:23:40.969  6515  6850 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-17 14:23:40.969  6515  6850 D BluetoothAdapterService: updateAdapterState state is 12
,08-17 14:23:40.979  1017  1485 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 14:23:40.979  1017  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-17 14:23:40.979  1017  1485 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:40.979  1017  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:40.979  1017  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:40.979  1017  1047 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-17 14:23:40.979  1017  1047 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-17 14:23:40.979  6515  6850 D BluetoothAdapterService: Autoconnection is available 
08-17 14:23:40.979  6515  6850 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-17 14:23:40.979  6515  6850 D BluetoothAdapterService: starting service from this receiver
,08-17 14:23:40.979  1017  1727 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 14:23:40.979  1017  1727 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-17 14:23:40.989  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:23:40.989  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:40.989  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:40.989  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:23:40.989  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:23:40.989  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:23:40.989  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:23:40.989  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 14:23:40.989  1017  1727 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:40.989  1017  1727 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:40.989  1017  1727 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:40.989  1446  3054 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 14:23:40.989  6515  6850 I BluetoothAdapterState: Entering On State from state = 11
,08-17 14:23:40.989  1446  3054 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 14:23:40.989  1436  1457 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-17 14:23:40.989  1436  1457 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 14:23:40.999  6291  6291 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 14:23:40.999  1436  1445 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 14:23:40.999  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:23:40.999  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:40.999  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:40.999  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:23:40.999  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:23:40.999  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:23:40.999  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:23:40.999  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 14:23:41.009  1017  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 14:23:41.009  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 14:23:41.009  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:41.009  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:41.009  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-17 14:23:41.009  6515  6515 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-17 14:23:41.009  6291  6291 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 14:23:41.009  1436  1445 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 14:23:41.009  6291  6299 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-17 14:23:41.019  6291  6299 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-17 14:23:41.019  1323  1335 D Bluetoothsap: onBluetoothStateChange: up=true
,08-17 14:23:41.019  1323  1335 D Bluetoothsap: Binding service...
,08-17 14:23:41.019  6515  6515 I BluetoothPbapService: Handler(): got msg=1
,08-17 14:23:41.019  1323  1335 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
08-17 14:23:41.019  1017  1029 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
08-17 14:23:41.019  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-17 14:23:41.019  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-17 14:23:41.029  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:41.029  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:41.029  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-17 14:23:41.029  1323  1335 D Bluetoothsap: bindService called to Bluetooth SAP Service
08-17 14:23:41.029  1017  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-17 14:23:41.029  1017  1047 D BluetoothPan: Binding service...
08-17 14:23:41.029  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-17 14:23:41.029  1459  1683 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-17 14:23:41.029  1459  1683 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 14:23:41.029  6393  6403 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-17 14:23:41.029  1017  1017 D BluetoothPan: BluetoothPAN Proxy object connected
,08-17 14:23:41.029  6393  6403 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 14:23:41.029  2892  2900 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 14:23:41.029  1017  1047 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-17 14:23:41.039  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 14:23:41.039  1323  1323 D Bluetoothsap: BluetoothSAP Proxy object connected
08-17 14:23:41.039  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:41.039  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:41.039  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:41.039  2892  2900 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 14:23:41.039  1323  1323 D SapProfile: Bluetooth service connected
08-17 14:23:41.039  6515  6898 V BluetoothPbapService: PBAP Service initSocket try: 0
08-17 14:23:41.039  1323  1323 D Bluetoothsap: getConnectedDevices()
,08-17 14:23:41.039  6515  6523 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-17 14:23:41.039  6515  6523 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-17 14:23:41.039  1323  1335 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 14:23:41.039  1323  1335 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 14:23:41.039  1323  1336 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-17 14:23:41.039  6515  6898 D BluetoothSocket: bindListen(): myUserId = 0
,08-17 14:23:41.039  6515  6898 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 14:23:41.039  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-17 14:23:41.039  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-17 14:23:41.049  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:41.049  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:41.049  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:41.049  1323  1323 D BluetoothInputDevice: Proxy object connected
08-17 14:23:41.049  1323  1323 D HidProfile: Bluetooth service connected
,08-17 14:23:41.049  1934  2121 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-17 14:23:41.049  1934  2121 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 14:23:41.049  6515  6898 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
08-17 14:23:41.049  6515  6898 D BluetoothSocket: bindListen(), new LocalSocket 
08-17 14:23:41.049  6515  6898 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-17 14:23:41.049  6515  6898 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@fd42f12
08-17 14:23:41.049  6515  6898 D BluetoothSocket: channel: 19
,08-17 14:23:41.049  6515  6898 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-17 14:23:41.049  1436  1457 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 14:23:41.049  1017  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-17 14:23:41.049  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 14:23:41.059  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:41.059  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:41.059  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:41.059  1436  1457 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 14:23:41.059  1323  1336 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 14:23:41.059  1323  1336 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-17 14:23:41.059  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-17 14:23:41.059  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 14:23:41.059  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:41.059  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:41.059  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:41.059  1323  1323 D BluetoothA2dp: Proxy object connected
,08-17 14:23:41.069  1323  1323 D A2dpProfile: Bluetooth service connected
08-17 14:23:41.069  1017  1047 D BluetoothA2dp: onBluetoothStateChange: up=true
08-17 14:23:41.069  1017  1047 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-17 14:23:41.069  1017  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-17 14:23:41.069  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 14:23:41.069  1017  1017 D BluetoothA2dp: Proxy object connected
,08-17 14:23:41.069  1436  2754 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 14:23:41.069  1017  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-17 14:23:41.069  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 14:23:41.069  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:41.069  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:41.069  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:41.069  1436  2754 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 14:23:41.069  6515  6854 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 14:23:41.069  1323  1335 D BluetoothPbap: onBluetoothStateChange: up=true
,08-17 14:23:41.069  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,08-17 14:23:41.069  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-17 14:23:41.079  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:41.079  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 14:23:41.079  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:41.079  2892  2900 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-17 14:23:41.079  2892  2900 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-17 14:23:41.079  1323  1323 D BluetoothPbap: Proxy object connected
,08-17 14:23:41.079  2892  2914 D BluetoothA2dp: onBluetoothStateChange: up=true
08-17 14:23:41.079  1323  1323 D PbapServerProfile: Bluetooth service connected
,08-17 14:23:41.079  2892  2914 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-17 14:23:41.079  1017  1047 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-17 14:23:41.079  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 14:23:41.079  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:41.079  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 14:23:41.089  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:41.089  2892  2892 D BluetoothA2dp: Proxy object connected
,08-17 14:23:41.089  1323  6900 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 14:23:41.089  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 14:23:41.089  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 14:23:41.089  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:41.089  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:41.089  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:41.089  1323  6900 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 14:23:41.089  1323  1323 D HeadsetProfile: Bluetooth service connected
,08-17 14:23:41.089  1323  1335 D BluetoothPan: Binding service...
,08-17 14:23:41.099  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-17 14:23:41.099  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-17 14:23:41.099  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:41.099  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:41.099  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:41.099  1181  2716 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 14:23:41.099  1181  2716 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-17 14:23:41.099  1323  1335 D BluetoothMap: onBluetoothStateChange: up=true
,08-17 14:23:41.099  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-17 14:23:41.099  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-17 14:23:41.099  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:41.099  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:41.099  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:41.099  1323  1323 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 14:23:41.099  1323  1323 D PanProfile: Bluetooth service connected
,08-17 14:23:41.099  1459  1471 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 14:23:41.099  1017  1047 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 14:23:41.099  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 14:23:41.109  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:41.109  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:41.109  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:41.109  1323  1323 D BluetoothMap: Proxy object connected
08-17 14:23:41.109  1323  1323 D MapProfile: Bluetooth service connected
08-17 14:23:41.109  1323  1323 D BluetoothMap: getConnectedDevices()
08-17 14:23:41.109  1459  1471 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 14:23:41.109  1017  1047 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 14:23:41.109  1017  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 14:23:41.109  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 14:23:41.109  1017  1047 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 14:23:41.109  1017  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-17 14:23:41.109  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-17 14:23:41.119  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED,
08-17 14:23:41.119  1436  1436 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@bebe229, true
08-17 14:23:41.119  1017  1017 I InputMethodManagerService: [BT Setting State] State =12
08-17 14:23:41.119  1017  1017 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-17 14:23:41.119  1436  1436 D BluetoothHeadset: registerMessageListener
,08-17 14:23:41.119  1181  1181 D BluetoothTile:  onBluetoothStateChange:
,08-17 14:23:41.119  1181  1181 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-17 14:23:41.119  1181  1181 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-17 14:23:41.119  1181  1712 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 14:23:41.119  1181  1181 D BluetoothTile:  getBluetoothState : 12
,08-17 14:23:41.129  1017  1079 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-17 14:23:41.129  1181  1712 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 14:23:41.129  1017  1029 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
08-17 14:23:41.129  1181  1181 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 14:23:41.129  1797  1797 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
08-17 14:23:41.129  1181  1712 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 14:23:41.129  1323  1323 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 14:23:41.129  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:41.129  6515  6523 D HeadsetService: registerMessageListener
,08-17 14:23:41.129  1017  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 14:23:41.129  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:41.129  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-17 14:23:41.129  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 14:23:41.129  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-17 14:23:41.129  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:23:41.139  6515  6523 D HeadsetService: registerMessageListener
,08-17 14:23:41.139  6515  6859 D HeadsetStateMachine: Disconnected process message: 70
08-17 14:23:41.139  6515  6859 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@1d9bb6e3
08-17 14:23:41.139  1436  1436 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
,08-17 14:23:41.139  1436  1436 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-17 14:23:41.139  1436  1436 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,08-17 14:23:41.139  1323  1323 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-17 14:23:41.139  1323  1323 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
,08-17 14:23:41.139  1323  1323 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-17 14:23:41.139  1323  1323 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
08-17 14:23:41.139  1436  1436 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-17 14:23:41.139  1436  1436 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-17 14:23:41.149  6515  6901 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-17 14:23:41.149  6515  6859 D HeadsetStateMachine: Disconnected process message: 9
08-17 14:23:41.149  6515  6859 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-17 14:23:41.159   283   283 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-17 14:23:41.159   283   283 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-17 14:23:41.159   283   283 V voice   : voice_set_parameters: exit with code(-2)
08-17 14:23:41.159   283   283 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-17 14:23:41.159   283   283 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-17 14:23:41.159   283   283 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-17 14:23:41.159   283   283 V audio_hw_primary: adev_set_parameters: exit
,08-17 14:23:41.159  6515  6859 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
08-17 14:23:41.159  6515  6901 D BluetoothSocket: bindListen(): myUserId = 0
08-17 14:23:41.159  6515  6901 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 14:23:41.159  1323  1323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 14:23:41.159  1017  1485 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-17 14:23:41.159  1017  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-17 14:23:41.159  6515  6901 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
08-17 14:23:41.159  6515  6901 D BluetoothSocket: bindListen(), new LocalSocket 
08-17 14:23:41.159  6515  6901 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,08-17 14:23:41.159  6515  6901 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@239838e0
,08-17 14:23:41.159  6515  6901 D BluetoothSocket: channel: 5
08-17 14:23:41.159  1017  1485 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:41.159  1017  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:41.159  1017  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-17 14:23:41.169  1323  1323 D DockEventReceiver: finishStartingService: stopping service
,08-17 14:23:41.169  1323  1323 D BluetoothNotiBroadcastReceiver: onReceive
,08-17 14:23:41.179  1181  1181 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:23:41.179  1181  1181 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-17 14:23:41.189  6515  6515 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d6b0b11
,08-17 14:23:41.189  6515  6515 D BtConfig.SecureMode: isSecureModeOn:false
,08-17 14:23:41.189  1017  1344 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 14:23:41.189  1017  1344 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-17 14:23:41.189  1017  1344 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:41.189  1017  1344 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:41.189  1017  1344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:41.199  1934  1934 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-17 14:23:41.209  1017  1531 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 14:23:41.209  1017  1531 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-17 14:23:41.209  1017  1531 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:41.209  1017  1531 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 14:23:41.209  1017  1531 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 14:23:41.209  1017  2783 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-17 14:23:41.219  1017  3056 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-17 14:23:41.219  1934  6908 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-17 14:23:41.219  1934  1934 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-17 14:23:41.219  1017  1727 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 14:23:41.229  1017  1727 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:41.229  1017  1727 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 14:23:41.229  1017  1727 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 14:23:41.229  6515  6911 D BluetoothSocket: bindListen(): myUserId = 0
,08-17 14:23:41.229  6515  6911 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 14:23:41.239  6515  6911 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[81]}
08-17 14:23:41.239  6515  6911 D BluetoothSocket: bindListen(), new LocalSocket 
08-17 14:23:41.239  6515  6911 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-17 14:23:41.239  6515  6911 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@cf8030c
08-17 14:23:41.239  6515  6911 D BluetoothSocket: channel: 12
08-17 14:23:41.239  6515  6911 I BtOppRfcommListener: Accept thread started.
,08-17 14:23:41.239  1017  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 14:23:41.239  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:41.239  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 14:23:41.239  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 14:23:41.249  1934  6908 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-17 14:23:41.849   290   290 E SMD     : DCD OFF
,08-17 14:23:42.809  1017  2759 D SSRM:n  : SIOP:: AP = 340
,08-17 14:23:43.039  6291  6344 D BluetoothAdapter: disable()
,08-17 14:23:43.039  1017  1505 D SettingsProvider: name = bluetooth_on
,08-17 14:23:43.049  6515  6850 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-17 14:23:43.049  6515  6850 D BluetoothAdapterProperties: Setting state to 13
,08-17 14:23:43.049  6515  6850 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-17 14:23:43.049  6515  6850 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-17 14:23:43.049  6515  6850 D BluetoothAdapterService: updateAdapterState state is 13
,08-17 14:23:43.049  1017  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 14:23:43.049  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-17 14:23:43.059  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:43.059  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:43.059  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:43.059  6515  6850 D BluetoothAdapterService: Autoconnection is available 
,08-17 14:23:43.059  6515  6850 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
,08-17 14:23:43.059  6515  6850 D BluetoothAdapterService: terminating service from this receiver
,08-17 14:23:43.059  1017  2745 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-17 14:23:43.059  6515  6515 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
08-17 14:23:43.059  1017  2745 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:43.059  1017  2745 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:43.059  1017  2745 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:43.059  6515  6515 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3dcf2455, channel: 19, state: LISTENING
,08-17 14:23:43.059  6515  6850 D BluetoothAdapterProperties: onBluetoothDisable()
,08-17 14:23:43.059  6515  6850 D BluetoothAdapterProperties: mDiscovering is false
,08-17 14:23:43.069  6515  6515 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3dcf2455, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@fd42f12, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1d028e6amSocket: android.net.LocalSocket@31771f5b impl:android.net.LocalSocketImpl@36a843f8 fd:FileDescriptor[75]
08-17 14:23:43.069  6515  6515 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@31771f5b impl:android.net.LocalSocketImpl@36a843f8 fd:FileDescriptor[75]
,08-17 14:23:43.069  1017  3056 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-17 14:23:43.069  6515  6850 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-17 14:23:43.069  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-17 14:23:43.069  1017  1017 I InputMethodManagerService: [BT Setting State] State =13
,08-17 14:23:43.079  1181  1181 D BluetoothTile:  onBluetoothStateChange:
,08-17 14:23:43.079  1181  1181 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-17 14:23:43.079  1181  1181 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:23:43.079  1181  1181 D BluetoothTile:  getBluetoothState : 13
,08-17 14:23:43.079  1181  1712 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 14:23:43.089  1017  1079 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 14:23:43.089  1017  1343 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-17 14:23:43.089  1181  1712 D BluetoothTile:  handleUpdatestate:false name:null
08-17 14:23:43.089  1323  1323 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 14:23:43.089  1181  1181 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-17 14:23:43.089  1797  1797 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-17 14:23:43.089  1181  1712 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-17 14:23:43.089  6291  6291 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 14:23:43.089  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:23:43.089  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:43.089  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:43.089  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:23:43.089  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:23:43.089  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:23:43.089  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:23:43.089  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 14:23:43.089  6291  6291 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 14:23:43.099  6291  6291 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 14:23:43.099  1017  1505 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 14:23:43.099  1017  1505 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-17 14:23:43.099  1017  1505 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:43.099  1017  1505 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-17 14:23:43.099  1017  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 14:23:43.099  6515  6853 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-17 14:23:43.099  6515  6853 D BluetoothAdapterProperties: Scan Mode:20
,08-17 14:23:43.099  6291  6291 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 14:23:43.099  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:23:43.099  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:43.099  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:43.099  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:23:43.099  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:23:43.099  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:23:43.099  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:23:43.099  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 14:23:43.109  6291  6291 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:23:43.109  6291  6291 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 14:23:43.109  6515  6850 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-17 14:23:43.109  6515  6850 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-17 14:23:43.109  6515  6850 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-17 14:23:43.109  6515  6850 E bt-btif : BTM_SEC_CLR[17]: id 57
08-17 14:23:43.109  6515  6850 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-17 14:23:43.109  6515  6911 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-17 14:23:43.119  6515  6870 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
,08-17 14:23:43.119  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:43.119  6515  6870 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-17 14:23:43.119  6515  6870 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-17 14:23:43.119  6515  6870 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 14:23:43.119  6515  6870 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-17 14:23:43.119  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-17 14:23:43.129  1323  1323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 14:23:43.129  1017  3205 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-17 14:23:43.129  1017  3205 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-17 14:23:43.129  1017  3205 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:43.129  1017  3205 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:43.129  1017  3205 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-17 14:23:43.129  1323  1323 D BluetoothPbap: Proxy object disconnected
08-17 14:23:43.129  1323  1323 D PbapServerProfile: Bluetooth service disconnected
,08-17 14:23:43.139  6515  6515 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@142ab0d1, channel: 5, state: LISTENING
,08-17 14:23:43.139  6515  6515 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@142ab0d1, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@239838e0, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2ab32736mSocket: android.net.LocalSocket@dfe5637 impl:android.net.LocalSocketImpl@1919a7a4 fd:FileDescriptor[77]
08-17 14:23:43.139  6515  6515 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@dfe5637 impl:android.net.LocalSocketImpl@1919a7a4 fd:FileDescriptor[77]
,08-17 14:23:43.139  6515  6515 I BtOppRfcommListener: stopping Accept Thread
08-17 14:23:43.139  6515  6515 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@dd8890d, channel: 12, state: LISTENING
08-17 14:23:43.139  6515  6515 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@dd8890d, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@cf8030c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2c0280c2mSocket: android.net.LocalSocket@18581ed3 impl:android.net.LocalSocketImpl@211b9a10 fd:FileDescriptor[81]
08-17 14:23:43.139  6515  6515 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@18581ed3 impl:android.net.LocalSocketImpl@211b9a10 fd:FileDescriptor[81]
08-17 14:23:43.139  6515  6911 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-17 14:23:43.139  1323  1323 D DockEventReceiver: finishStartingService: stopping service
,08-17 14:23:43.139  6515  6515 V BluetoothOppManager: cleanUp...
,08-17 14:23:43.149  1323  1323 D BluetoothNotiBroadcastReceiver: onReceive
,08-17 14:23:43.149  1181  1181 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 14:23:43.149  1181  1181 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-17 14:23:43.169  1934  1934 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-17 14:23:43.169  1934  1934 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-17 14:23:43.319  6515  6870 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-17 14:23:43.319  6515  6870 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-17 14:23:43.319  6515  6870 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 14:23:43.319  6515  6870 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-17 14:23:43.319  6515  6870 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 14:23:43.319  6515  6870 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-17 14:23:43.319  6515  6870 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-17 14:23:43.319  6515  6870 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 14:23:43.319  6515  6870 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-17 14:23:43.319  6515  6870 W bt-btif : ag scb idx 1 not allocated
08-17 14:23:43.319  6515  6870 W bt-btif : ag scb idx 2 not allocated
,08-17 14:23:43.319  6515  6893 I bt_userial_mct: exiting userial_read_thread
08-17 14:23:43.319  6515  6893 D bt_userial_mct: Leaving userial_evt_read_thread()
08-17 14:23:43.319  6515  6853 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-17 14:23:43.319  6515  6872 I bt_vendor: hw_epilog_process
,08-17 14:23:43.319  6515  6853 D bt_userial_mct: userial_close
08-17 14:23:43.319  6515  6853 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-17 14:23:43.319  6515  6870 E bt-btif : BTA AG is already disabled, ignoring ...
,08-17 14:23:43.459   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-17 14:23:44.329  6515  6853 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-17 14:23:44.329  6515  6853 I bt_vendor: bluetooth satus is on
08-17 14:23:44.329  6515  6853 I bt_vendor: bt-vendor : resetting BT status
08-17 14:23:44.329  6515  6853 I bt_vendor: Starting hciattach daemon
08-17 14:23:44.329  6515  6853 I bt_vendor: try to set false
,08-17 14:23:44.329  6515  6853 I bt_vendor: Starting hciattach daemon
,08-17 14:23:44.329  6515  6853 I bt_vendor: try to set false
08-17 14:23:44.329  6515  6853 I bt_vendor: cleanup
,08-17 14:23:44.329  6515  6870 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-17 14:23:44.329  6515  6853 I GKI_LINUX: GKI_exit_task 0 done
,08-17 14:23:44.329  6515  6853 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-17 14:23:44.329  6515  6850 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true,
,08-17 14:23:44.329  6515  6850 D BtConfig.SecureMode: isSecureModeOn:false
,08-17 14:23:44.329  1017  1344 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 14:23:44.329  6515  6850 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-17 14:23:44.329  1017  1344 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-17 14:23:44.329  6515  6850 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-17 14:23:44.329  6515  6850 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-17 14:23:44.329  6515  6850 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-17 14:23:44.329  1017  1344 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:44.329  1017  1344 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:44.329  1017  1344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 14:23:44.339  6515  6850 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-17 14:23:44.339  6515  6850 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-17 14:23:44.339  1017  1344 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 14:23:44.339  6515  6850 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-17 14:23:44.339  1017  1344 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-17 14:23:44.339  6515  6515 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 14:23:44.339  6515  6515 D BtGatt.GattService: Received stop request...Stopping profile...
,08-17 14:23:44.339  6515  6515 D BtGatt.GattService: stop()
08-17 14:23:44.339  6515  6515 D BtGatt.AdvertiseManager: advertise clients cleared
08-17 14:23:44.339  1017  1344 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:44.339  1017  1344 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:44.339  1017  1344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
08-17 14:23:44.339  6515  6850 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-17 14:23:44.339  6515  6850 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-17 14:23:44.339  6515  6850 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-17 14:23:44.339  1017  2745 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 14:23:44.339  1017  2745 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 14:23:44.339  1017  2745 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:44.339  1017  2745 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:44.339  1017  2745 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:44.339  6515  6515 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d6b0b11
,08-17 14:23:44.349  6515  6850 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-17 14:23:44.349  6515  6850 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-17 14:23:44.349  6515  6850 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService,
08-17 14:23:44.349  1017  1483 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 14:23:44.349  1017  1483 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-17 14:23:44.349  6515  6515 D HeadsetService: Received stop request...Stopping profile...
08-17 14:23:44.349  1017  1483 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:44.349  1017  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:44.349  1017  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:44.349  6515  6850 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,08-17 14:23:44.349  6515  6850 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-17 14:23:44.349  6515  6850 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-17 14:23:44.349  6515  6515 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d6b0b11
,08-17 14:23:44.349  1017  1222 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 14:23:44.349  1017  1222 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-17 14:23:44.349  1017  1222 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:44.349  1017  1222 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:44.349  1017  1222 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:44.359  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-17 14:23:44.359  6515  6515 D A2dpService: Received stop request...Stopping profile...
08-17 14:23:44.359  6515  6850 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-17 14:23:44.359  6515  6864 D A2dpStateMachine: Exit Disconnected: -1
08-17 14:23:44.359  6515  6850 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-17 14:23:44.359  6515  6850 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-17 14:23:44.359  1323  1323 D HeadsetProfile: Bluetooth service disconnected
08-17 14:23:44.359  1017  1485 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 14:23:44.359  1017  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-17 14:23:44.359  1017  1485 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:44.359  1017  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 14:23:44.359  1017  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:44.359  6515  6850 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-17 14:23:44.359  1017  1483 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 14:23:44.359  6515  6850 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 14:23:44.359  1017  1483 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-17 14:23:44.359  6515  6850 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-17 14:23:44.359  6515  6515 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d6b0b11
08-17 14:23:44.369  1017  1483 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:44.369  1017  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 14:23:44.369  1017  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:44.369  1017  1017 D BluetoothA2dp: Proxy object disconnected
,08-17 14:23:44.369  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-17 14:23:44.369  6515  6850 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-17 14:23:44.369  2892  2892 D BluetoothA2dp: Proxy object disconnected
08-17 14:23:44.369  6515  6850 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-17 14:23:44.369  6515  6850 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-17 14:23:44.369  1017  3056 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 14:23:44.369  1323  1323 D BluetoothA2dp: Proxy object disconnected
08-17 14:23:44.369  1323  1323 D A2dpProfile: Bluetooth service disconnected
,08-17 14:23:44.369  1017  3056 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-17 14:23:44.369  1017  3056 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:44.369  1017  3056 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:44.369  1017  3056 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:44.369  6515  6850 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-17 14:23:44.369  6515  6850 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-17 14:23:44.369  6515  6850 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-17 14:23:44.369  6515  6850 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
,08-17 14:23:44.369  6515  6850 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-17 14:23:44.369  6515  6850 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,08-17 14:23:44.379  6515  6850 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-17 14:23:44.379  6515  6850 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-17 14:23:44.379  6515  6850 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-17 14:23:44.379  6515  6850 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-17 14:23:44.379  6515  6850 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-17 14:23:44.379  6515  6850 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-17 14:23:44.379  6515  6850 D BluetoothAdapterState: Stopping profile services that were post enabled
08-17 14:23:44.379  6515  6515 E BluetoothAdapterService(1030425361): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,08-17 14:23:44.379  6515  6515 D HidService: Received stop request...Stopping profile...
08-17 14:23:44.379  6515  6515 D HidService: Stopping Bluetooth HidService
08-17 14:23:44.379  6515  6515 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-17 14:23:44.379  6515  6515 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-17 14:23:44.379  6515  6515 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-17 14:23:44.379  6515  6515 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d6b0b11
,08-17 14:23:44.379  6515  6515 E BluetoothAdapterService(1030425361): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,08-17 14:23:44.379  6515  6515 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-17 14:23:44.379  6515  6515 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-17 14:23:44.379  6515  6515 D HealthService: Received stop request...Stopping profile...
,08-17 14:23:44.379  6515  6515 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d6b0b11
,08-17 14:23:44.389  1323  1323 D BluetoothInputDevice: Proxy object disconnected
08-17 14:23:44.389  1323  1323 D HidProfile: Bluetooth service disconnected
,08-17 14:23:44.389  6515  6515 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-17 14:23:44.389  6515  6515 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-17 14:23:44.389  6515  6515 D PanService: Received stop request...Stopping profile...
,08-17 14:23:44.389  6515  6515 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d6b0b11
,08-17 14:23:44.389  1017  1017 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-17 14:23:44.389  1323  1323 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-17 14:23:44.389  6515  6515 E BluetoothAdapterService(1030425361): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-17 14:23:44.389  6515  6515 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-17 14:23:44.389  6515  6515 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-17 14:23:44.389  6515  6515 D BluetoothMapService: Received stop request...Stopping profile...
,08-17 14:23:44.389  6515  6515 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d6b0b11
,08-17 14:23:44.389  1323  1323 D PanProfile: Bluetooth service disconnected
,08-17 14:23:44.399  6515  6515 D BluetoothA2dp: Proxy object disconnected
08-17 14:23:44.399  6515  6515 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-17 14:23:44.399  6515  6865 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-17 14:23:44.399  6515  6515 I GKI_LINUX: GKI_exit_task 2 done
,08-17 14:23:44.399  6515  6515 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-17 14:23:44.399  6515  6515 D SapService: Received stop request...Stopping profile...
08-17 14:23:44.399  1323  1323 D BluetoothMap: Proxy object disconnected
08-17 14:23:44.399  6515  6515 D SapService: Stopping Bluetooth SapService
08-17 14:23:44.399  1323  1323 D MapProfile: Bluetooth service disconnected
08-17 14:23:44.399  6515  6515 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d6b0b11
,08-17 14:23:44.399  6515  6515 E BluetoothAdapterService(1030425361): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-17 14:23:44.399  6515  6515 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 14:23:44.399  6515  6515 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-17 14:23:44.399  1323  1323 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-17 14:23:44.399  6515  6515 E BluetoothAdapterService(1030425361): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-17 14:23:44.399  6515  6515 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 14:23:44.399  6515  6515 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-17 14:23:44.399  6515  6515 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-17 14:23:44.399  1323  1323 D SapProfile: Bluetooth service disconnected
,08-17 14:23:44.399  6515  6515 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-17 14:23:44.399  6515  6515 E BluetoothAdapterService(1030425361): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
,08-17 14:23:44.399  6515  6515 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-17 14:23:44.399  6515  6515 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-17 14:23:44.399  6515  6515 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-17 14:23:44.399  6515  6515 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-17 14:23:44.399  6515  6515 E BluetoothAdapterService(1030425361): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true,
08-17 14:23:44.399  6515  6515 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-17 14:23:44.399  6515  6515 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-17 14:23:44.409  6515  6515 E BluetoothAdapterService(1030425361): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,08-17 14:23:44.409  6515  6515 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
,08-17 14:23:44.409  6515  6515 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
08-17 14:23:44.409  6515  6850 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-17 14:23:44.409  6515  6850 D BluetoothAdapterProperties: Setting state to 10
08-17 14:23:44.409  6515  6850 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-17 14:23:44.409  6515  6850 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-17 14:23:44.409  6515  6850 D BluetoothAdapterService: updateAdapterState state is 10
,08-17 14:23:44.409  1017  1047 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 14:23:44.409  6515  6850 D BluetoothAdapterService: Autoconnection is available 
08-17 14:23:44.409  1017  1047 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 14:23:44.409  6515  6850 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-17 14:23:44.409  6515  6850 I BluetoothAdapterState: Entering OffState
08-17 14:23:44.409  1446  3054 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 14:23:44.409  1446  3054 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-17 14:23:44.409  1436  1445 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 14:23:44.409  1436  1445 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 14:23:44.409  6291  6299 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 14:23:44.409  6291  6299 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-17 14:23:44.409  6291  6299 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-17 14:23:44.409  6291  6299 D BluetoothLeAdvertiser: Exit stop advertising
08-17 14:23:44.409  6291  6299 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-17 14:23:44.409  6291  6299 D BluetoothLeScanner: Exiting stopAllScan
,08-17 14:23:44.409  1323  6900 D Bluetoothsap: onBluetoothStateChange: up=false
08-17 14:23:44.409  1323  6900 D Bluetoothsap: Unbinding service...,
08-17 14:23:44.409  1459  1792 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 14:23:44.409  1459  1792 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 14:23:44.409  6393  6402 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 14:23:44.409  6393  6402 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-17 14:23:44.409  6515  6854 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 14:23:44.409  6515  6854 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-17 14:23:44.409  1323  1336 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 14:23:44.409  1323  1336 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan,
,08-17 14:23:44.409  1323  1335 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-17 14:23:44.419  1934  2123 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 14:23:44.419  1934  2123 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 14:23:44.419  1323  6900 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 14:23:44.419  1017  1047 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 14:23:44.419  6515  6523 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 14:23:44.419  1323  1336 D BluetoothPbap: onBluetoothStateChange: up=false
08-17 14:23:44.419  2892  6899 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 14:23:44.419  2892  6899 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-17 14:23:44.419  2892  2900 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-17 14:23:44.419  1181  1760 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 14:23:44.419  1181  1760 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-17 14:23:44.419  1323  1336 D BluetoothMap: onBluetoothStateChange: up=false
,08-17 14:23:44.429  1017  1047 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 11 receivers.
,08-17 14:23:44.429  1017  1047 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-17 14:23:44.429  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-17 14:23:44.439  1017  1017 I InputMethodManagerService: [BT Setting State] State =10
08-17 14:23:44.439  1017  1017 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-17 14:23:44.439  1181  1181 D BluetoothAdapter: 490535640: getState() :  mService = null. Returning STATE_OFF
,08-17 14:23:44.439  1181  1181 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-17 14:23:44.439  1181  1712 D BluetoothAdapter: 490535640: getState() :  mService = null. Returning STATE_OFF
,08-17 14:23:44.439  1181  1181 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:23:44.439  1181  1712 D BluetoothAdapter: 490535640: getState() :  mService = null. Returning STATE_OFF
08-17 14:23:44.439  1181  1181 D BluetoothTile:  getBluetoothState : 10
,08-17 14:23:44.439  1181  1181 D BluetoothAdapter: 490535640: getState() :  mService = null. Returning STATE_OFF
,08-17 14:23:44.439  1181  1181 D BluetoothAdapter: 490535640: getState() :  mService = null. Returning STATE_OFF
08-17 14:23:44.439  1017  1343 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 14:23:44.439  1797  1797 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
08-17 14:23:44.439  6515  6853 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-17 14:23:44.439  6515  6515 I GKI_LINUX: GKI_exit_task 1 done
,08-17 14:23:44.449  6515  6515 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-17 14:23:44.449  6515  6515 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-17 14:23:44.449  1017  1505 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-17 14:23:44.449  1181  1181 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-17 14:23:44.449  1181  1181 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-17 14:23:44.449  1934  2129 D BluetoothAdapter: 662714400: getState() :  mService = null. Returning STATE_OFF
,08-17 14:23:44.449  1934  2129 D BluetoothAdapter: 662714400: getState() :  mService = null. Returning STATE_OFF
,08-17 14:23:44.449  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:23:44.449  1323  1323 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 14:23:44.449  1017  1344 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 14:23:44.449  1017  1344 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-17 14:23:44.449  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:23:44.449  1017  1344 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:44.449  1017  1344 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 14:23:44.449  1017  1344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 14:23:44.459  1323  1323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 14:23:44.459  1017  1505 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-17 14:23:44.459  1017  1505 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
08-17 14:23:44.459  6515  6515 I art     : System.exit called, status: 0
,08-17 14:23:44.459  6515  6515 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-17 14:23:44.459  1017  1505 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:44.459  1017  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:44.459  1017  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-17 14:23:44.459   335   335 I ServiceManager: Waiting for service AtCmdFwd...
,08-17 14:23:44.469  1323  1323 D DockEventReceiver: finishStartingService: stopping service
,08-17 14:23:44.469  1323  1323 D BluetoothNotiBroadcastReceiver: onReceive
,08-17 14:23:44.479  1181  1181 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:23:44.479  1181  1181 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-17 14:23:44.479  1017  1727 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-17 14:23:44.489  1017  1727 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppReceiver}
08-17 14:23:44.489  1017  1727 W BroadcastQueue: android.os.TransactionTooLargeException
08-17 14:23:44.489  1017  1727 W BroadcastQueue: 	,at android.os.BinderProxy.transactNative(Native Method)
08-17 14:23:44.489  1017  1727 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-17 14:23:44.489  1017  1727 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-17 14:23:44.489  1017  1727 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-17 14:23:44.489  1017  1727 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-17 14:23:44.489  1017  1727 W BroadcastQueue: ,	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20437)
08-17 14:23:44.489  1017  1727 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-17 14:23:44.489  1017  1727 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3278)
08-17 14:23:44.489  1017  1727 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,08-17 14:23:44.489  1017  1727 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-17 14:23:44.489  1017  1727 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:44.489  1017  1727 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:44.489  1017  1727 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:44.489  1017  1727 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 14:23:44.499  6926  6926 E Zygote  : MountEmulatedStorage(),
08-17 14:23:44.499  6926  6926 E Zygote  : v2
08-17 14:23:44.499  6926  6926 I libpersona: KNOX_SDCARD checking this for 1002
08-17 14:23:44.499  6926  6926 I libpersona: KNOX_SDCARD not a persona,
,08-17 14:23:44.509  6926  6926 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-17 14:23:44.509  1017  1727 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6926 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a,
,08-17 14:23:44.509  6926  6926 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-17 14:23:44.509  6926  6926 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 14:23:44.529  6926  6926 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 14:23:44.529  6926  6926 D ActivityThread: Added TimaKeyStore provider
,08-17 14:23:44.539  6926  6926 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-17 14:23:44.549  6926  6926 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.,
,08-17 14:23:44.569  6926  6926 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-17 14:23:44.599  6926  6926 D BtSettings.ProfileConfig: Adding GattService
,08-17 14:23:44.599  6926  6926 D BtSettings.ProfileConfig: Adding HeadsetService
,08-17 14:23:44.599  6926  6926 D BtSettings.ProfileConfig: Adding A2dpService
,08-17 14:23:44.599  6926  6926 D BtSettings.ProfileConfig: Adding HidService
,08-17 14:23:44.599  6926  6926 D BtSettings.ProfileConfig: Adding HealthService
,08-17 14:23:44.599  6926  6926 D BtSettings.ProfileConfig: Adding PanService
,08-17 14:23:44.599  6926  6926 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-17 14:23:44.599  6926  6926 D BtSettings.ProfileConfig: Adding SapService
08-17 14:23:44.599  6926  6926 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-17 14:23:44.599  6926  6926 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-17 14:23:44.599  6926  6926 D BtSettings.ProfileConfig: Adding SapClientService
,08-17 14:23:44.599  6926  6926 D BtSettings.ProfileConfig: Adding HidDevService
08-17 14:23:44.609  6926  6926 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-17 14:23:44.609  1017  1079 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-17 14:23:44.609  1017  1079 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-17 14:23:44.609  1017  1079 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 14:23:44.609  1017  1079 D SettingsProvider: selectionArgs: false
,08-17 14:23:44.609  1017  1079 D SettingsProvider: selectionArgs: 1002
,08-17 14:23:44.609  1017  1079 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-17 14:23:44.609  1017  1079 D SettingsProvider: ret = -1
,08-17 14:23:44.609  1017  1727 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService,
08-17 14:23:44.609  1017  1727 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 14:23:44.609  1017  1727 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 14:23:44.609  1017  1727 D SettingsProvider: selectionArgs: false
,08-17 14:23:44.609  1017  1727 D SettingsProvider: selectionArgs: 1002
08-17 14:23:44.609  1017  1727 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 14:23:44.609  1017  1727 D SettingsProvider: ret = -1
08-17 14:23:44.609  1017  1029 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-17 14:23:44.609  1017  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 14:23:44.609  1017  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 14:23:44.609  1017  1029 D SettingsProvider: selectionArgs: false
08-17 14:23:44.609  1017  1029 D SettingsProvider: selectionArgs: 1002
08-17 14:23:44.609  1017  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 14:23:44.609  1017  1029 D SettingsProvider: ret = -1
08-17 14:23:44.619  1017  3205 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-17 14:23:44.619  1017  3205 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 14:23:44.619  1017  3205 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 14:23:44.619  1017  3205 D SettingsProvider: selectionArgs: false
08-17 14:23:44.619  1017  3205 D SettingsProvider: selectionArgs: 1002
08-17 14:23:44.619  1017  3205 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 14:23:44.619  1017  3205 D SettingsProvider: ret = -1
,08-17 14:23:44.619  1017  3056 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-17 14:23:44.619  1017  3056 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
08-17 14:23:44.619  1017  3056 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 14:23:44.619  1017  3056 D SettingsProvider: selectionArgs: false
08-17 14:23:44.619  1017  3056 D SettingsProvider: selectionArgs: 1002
,08-17 14:23:44.619  1017  3056 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 14:23:44.619  1017  3056 D SettingsProvider: ret = -1
08-17 14:23:44.619  1017  1344 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService,
08-17 14:23:44.619  1017  1344 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 14:23:44.619  1017  1344 D SettingsProvider: projectionArgs: isSettingsChangesAllowed,
08-17 14:23:44.619  1017  1344 D SettingsProvider: selectionArgs: false
08-17 14:23:44.619  1017  1344 D SettingsProvider: selectionArgs: 1002
08-17 14:23:44.619  1017  1344 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-17 14:23:44.619  1017  1344 D SettingsProvider: ret = -1
08-17 14:23:44.619  1017  1485 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-17 14:23:44.619  1017  1485 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 14:23:44.619  1017  1485 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-17 14:23:44.619  1017  1485 D SettingsProvider: selectionArgs: false
08-17 14:23:44.619  1017  1485 D SettingsProvider: selectionArgs: 1002
08-17 14:23:44.619  1017  1485 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 14:23:44.619  1017  1485 D SettingsProvider: ret = -1
,08-17 14:23:44.619  1017  1483 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-17 14:23:44.619  1017  1483 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 14:23:44.619  1017  1483 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-17 14:23:44.619  1017  1483 D SettingsProvider: selectionArgs: false
08-17 14:23:44.619  1017  1483 D SettingsProvider: selectionArgs: 1002
08-17 14:23:44.619  1017  1483 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 14:23:44.619  1017  1483 D SettingsProvider: ret = -1
08-17 14:23:44.619  1017  3057 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-17 14:23:44.619  1017  3057 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 14:23:44.619  1017  3057 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 14:23:44.619  1017  3057 D SettingsProvider: selectionArgs: false
08-17 14:23:44.619  1017  3057 D SettingsProvider: selectionArgs: 1002
08-17 14:23:44.619  1017  3057 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 14:23:44.619  1017  3057 D SettingsProvider: ret = -1
08-17 14:23:44.619  1017  1505 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-17 14:23:44.619  1017  1505 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 14:23:44.619  1017  1505 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 14:23:44.619  1017  1505 D SettingsProvider: selectionArgs: false
08-17 14:23:44.619  1017  1505 D SettingsProvider: selectionArgs: 1002
08-17 14:23:44.619  1017  1505 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 14:23:44.619  1017  1505 D SettingsProvider: ret = -1
08-17 14:23:44.619  1017  1222 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-17 14:23:44.619  1017  1222 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 14:23:44.619  1017  1222 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 14:23:44.619  1017  1222 D SettingsProvider: selectionArgs: false
08-17 14:23:44.619  1017  1222 D SettingsProvider: selectionArgs: 1002
08-17 14:23:44.619  1017  1222 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 14:23:44.619  1017  1222 D SettingsProvider: ret = -1
08-17 14:23:44.619  1017  1030 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-17 14:23:44.619  1017  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 14:23:44.619  1017  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 14:23:44.619  1017  1030 D SettingsProvider: selectionArgs: false
08-17 14:23:44.619  1017  1030 D SettingsProvider: selectionArgs: 1002
08-17 14:23:44.619  1017  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 14:23:44.619  1017  1030 D SettingsProvider: ret = -1
,08-17 14:23:44.639  1934  1934 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-17 14:23:44.639  1017  1727 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-17 14:23:44.649  1017  1727 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-17 14:23:44.649  1017  1727 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:44.649  1017  1727 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-17 14:23:44.649  1017  1727 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 14:23:44.659  1934  1934 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-17 14:23:44.659  1934  6942 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-17 14:23:44.669  1017  1344 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 14:23:44.669  1017  1344 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:44.669  1017  1344 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 14:23:44.669  1017  1344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 14:23:44.679  1934  6942 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-17 14:23:44.849   290   290 E SMD     : DCD OFF,
,08-17 14:23:45.459   335   335 I ServiceManager: Waiting for service AtCmdFwd...
,08-17 14:23:46.049  6291  6344 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 14:23:46.049  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:23:46.459   335   335 I ServiceManager: Waiting for service AtCmdFwd...
,08-17 14:23:47.459   335   335 I ServiceManager: Waiting for service AtCmdFwd...
,08-17 14:23:47.829  3852  4409 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient,
,08-17 14:23:47.849   290   290 E SMD     : DCD OFF,
,08-17 14:23:48.459   335   335 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,08-17 14:23:49.049  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 14:23:49.049  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@32767d04 added. We now have 6 listener(s)
,08-17 14:23:49.049  6291  6344 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 14:23:49.059  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 14:23:49.059  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ba2a2ed added. We now have 7 listener(s)
,08-17 14:23:49.059  6291  6344 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 14:23:49.059  6291  6344 I System.out: IsBluetoothEnabled
,08-17 14:23:49.059  6291  6344 D BluetoothAdapter: disable()
,08-17 14:23:49.059  1017  1531 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-17 14:23:49.069  6291  6344 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:49.069  6291  6344 D BluetoothAdapter: enable()
,08-17 14:23:49.069  1017  1029 W ActivityManager: Permission Denial: getCurrentUser() from pid=6291, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,08-17 14:23:49.069  1017  1029 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-17 14:23:49.069  1017  1029 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6291, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-17 14:23:49.069  1017  1029 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-17 14:23:49.069  1017  1029 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
08-17 14:23:49.069  1017  1029 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
08-17 14:23:49.069  1017  1029 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
08-17 14:23:49.069  1017  1029 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-17 14:23:49.069  1017  1029 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 14:23:49.069  1017  1029 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 14:23:49.069  1017  1029 D SettingsProvider: name = bluetooth_on
,08-17 14:23:49.079  1017  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-17 14:23:49.079  1017  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 14:23:49.079  1017  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,08-17 14:23:49.079  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-17 14:23:49.109  6926  6926 D BluetoothAdapterState: make
,08-17 14:23:49.109  6926  6926 I bluedroid: init
,08-17 14:23:49.109  6926  6948 I BluetoothAdapterState: Entering OffState
,08-17 14:23:49.119  6926  6926 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-17 14:23:49.119  6926  6926 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-17 14:23:49.119  6926  6926 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-17 14:23:49.119  6926  6926 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-17 14:23:49.119  6926  6926 E bt-btif : btif_fetch_local_ble_random_bdaddr
,08-17 14:23:49.119  6926  6926 I bluedroid: get_profile_interface socket
,08-17 14:23:49.119  6926  6926 I bluedroid: get_profile_interface map_client
,08-17 14:23:49.129  6926  6951 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-17 14:23:49.129  6926  6926 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-17 14:23:49.129  6926  6951 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,08-17 14:23:49.129  6926  6951 E BluetoothServiceJni: populateRssiValuesNative
08-17 14:23:49.129  6926  6951 I bluedroid: getModelRssiValues
08-17 14:23:49.129  6926  6951 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-17 14:23:49.129  6926  6951 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-17 14:23:49.139  6926  6951 D BluetoothAdapterProperties: Name is: A5-1
,08-17 14:23:49.139  1017  1017 D SettingsProvider: name = bluetooth_name
,08-17 14:23:49.139  6926  6926 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-17 14:23:49.139  1017  3205 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-17 14:23:49.149  1017  3205 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 14:23:49.149  1017  3205 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:49.149  1017  3205 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 14:23:49.149  1017  3205 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:49.149  6926  6935 I bluedroid: config_hci_snoop_log
,08-17 14:23:49.149  1017  1047 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,08-17 14:23:49.159  1017  1047 D BluetoothManagerService: Ble is always on enable gatt
,08-17 14:23:49.159  1017  1047 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-17 14:23:49.159  1017  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-17 14:23:49.159  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-17 14:23:49.159  6926  6926 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-17 14:23:49.159  1017  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 14:23:49.159  1017  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 14:23:49.169  1017  1047 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-17 14:23:49.169  6926  6948 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-17 14:23:49.169  6926  6948 D BluetoothAdapterProperties: Setting state to 11
,08-17 14:23:49.169  6926  6948 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-17 14:23:49.169  6926  6948 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-17 14:23:49.179  6926  6948 D BluetoothAdapterService: updateAdapterState state is 11
,08-17 14:23:49.179  6926  6948 D BluetoothAdapterService: Autoconnection is available 
,08-17 14:23:49.179  6926  6948 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-17 14:23:49.179  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-17 14:23:49.179  1017  1017 I InputMethodManagerService: [BT Setting State] State =11
,08-17 14:23:49.189  6926  6948 D BluetoothSecureManager: getInstant: null
08-17 14:23:49.189  6926  6948 D BluetoothSecureManager: calling getMethod for getService
08-17 14:23:49.189  6926  6948 D BluetoothSecureManager: calling getService
,08-17 14:23:49.189  6926  6948 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@210a3c4e
,08-17 14:23:49.189  1017  3207 D BluetoothSecureManagerService: isSecureModeEnabled
,08-17 14:23:49.189  1017  3207 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-17 14:23:49.189  6926  6948 D BtConfig.SecureMode: isSecureModeOn:false
08-17 14:23:49.189  6926  6948 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-17 14:23:49.189  6926  6948 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-17 14:23:49.189  6926  6948 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-17 14:23:49.189  6926  6948 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-17 14:23:49.189  6926  6948 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-17 14:23:49.199  1181  1181 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-17 14:23:49.199  6926  6948 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-17 14:23:49.199  6926  6948 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-17 14:23:49.199  6926  6948 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-17 14:23:49.199  6926  6948 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-17 14:23:49.199  6926  6948 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-17 14:23:49.199  6926  6948 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-17 14:23:49.199  6926  6948 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-17 14:23:49.199  6926  6948 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-17 14:23:49.199  1181  1181 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:23:49.199  1181  1181 D BluetoothTile:  getBluetoothState : 11
,08-17 14:23:49.199  6926  6948 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-17 14:23:49.199  6926  6948 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-17 14:23:49.199  1797  1797 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-17 14:23:49.199  6926  6948 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
,08-17 14:23:49.199  6926  6948 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-17 14:23:49.209  6926  6948 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-17 14:23:49.209  6926  6948 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-17 14:23:49.209  6926  6948 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
,08-17 14:23:49.209  1181  1712 D BluetoothTile:  handleUpdatestate:false name:null
08-17 14:23:49.209  6926  6948 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService,
08-17 14:23:49.209  1181  1712 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-17 14:23:49.209  1323  1323 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:23:49.209  6926  6948 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
,08-17 14:23:49.209  6926  6948 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-17 14:23:49.209  6926  6948 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-17 14:23:49.209  1017  1483 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 14:23:49.219  1017  1030 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-17 14:23:49.219  6926  6948 D BluetoothBondStateMachine: make
,08-17 14:23:49.219  1017  1029 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-17 14:23:49.219  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:49.219  1017  1047 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-17 14:23:49.219  1181  1181 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-17 14:23:49.219  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-17 14:23:49.219  6926  6948 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-17 14:23:49.229  6926  6948 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-17 14:23:49.229  6926  6948 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-17 14:23:49.229  6926  6953 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-17 14:23:49.229  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:49.229  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 14:23:49.229  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 14:23:49.229  1017  3056 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 14:23:49.229  1017  3056 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-17 14:23:49.229  1017  3056 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:49.229  1017  3056 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:49.229  1017  3056 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:49.239  6926  6948 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-17 14:23:49.239  6926  6948 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-17 14:23:49.239  6926  6948 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-17 14:23:49.239  6926  6926 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 14:23:49.239  1323  1323 D BluetoothNotiBroadcastReceiver: onReceive
,08-17 14:23:49.239  6926  6926 D BtGatt.GattService: Received start request. Starting profile...
,08-17 14:23:49.239  6926  6926 D BtGatt.GattService: start()
08-17 14:23:49.239  6926  6926 D BtGatt.GattService: start()
08-17 14:23:49.239  6926  6926 I bluedroid: get_profile_interface gatt
08-17 14:23:49.239  1017  2745 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 14:23:49.239  1017  2745 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-17 14:23:49.249  6926  6926 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d6b0b11
,08-17 14:23:49.249  6926  6926 D BtGatt.AdvertiseManager: advertise manager created
,08-17 14:23:49.249  1017  2745 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:49.249  1017  2745 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:49.249  1017  2745 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:49.249  6926  6948 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-17 14:23:49.249  6926  6948 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-17 14:23:49.249  6926  6948 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-17 14:23:49.259  1181  1181 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 14:23:49.259  1181  1181 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-17 14:23:49.259  1017  1222 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 14:23:49.259  1017  1222 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 14:23:49.259  1017  1222 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:49.259  1017  1222 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:49.259  1017  1222 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:49.269  6926  6926 D BtGatt.GattService: mStartError = false
,08-17 14:23:49.269  6926  6926 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d6b0b11
,08-17 14:23:49.269  6926  6926 D HeadsetService: Received start request. Starting profile...
,08-17 14:23:49.269  6926  6926 D HeadsetService: start()
,08-17 14:23:49.269  6926  6926 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-17 14:23:49.269  6926  6926 D HeadsetStateMachine: make
08-17 14:23:49.269  6926  6948 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-17 14:23:49.269  6926  6948 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-17 14:23:49.269  6926  6948 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-17 14:23:49.269  1017  1344 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 14:23:49.269  1017  1344 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-17 14:23:49.269  1017  1344 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:49.269  1017  1344 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:49.279  1017  1344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:49.279  6926  6926 E HeadsetStateMachine: # of Max HF connection is 2
,08-17 14:23:49.279  6926  6948 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,08-17 14:23:49.279  6926  6948 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-17 14:23:49.279  6926  6948 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-17 14:23:49.279  1017  1505 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 14:23:49.279  1017  1505 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-17 14:23:49.289  1017  1505 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:49.289  1017  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 14:23:49.289  1017  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:49.289  6926  6948 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-17 14:23:49.289  6926  6948 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-17 14:23:49.289  6926  6948 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-17 14:23:49.299  1017  1531 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-17 14:23:49.299  1017  1531 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-17 14:23:49.299  1017  1531 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:49.299  1017  1531 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:49.299  1017  1531 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-17 14:23:49.299  1017  1483 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 14:23:49.299  1017  1483 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-17 14:23:49.299  1017  1483 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:49.299  1017  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:49.299  1017  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:49.309  6926  6948 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-17 14:23:49.309  6926  6948 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-17 14:23:49.309  6926  6948 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-17 14:23:49.309  1017  1222 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:49.309  1017  1222 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-17 14:23:49.309  1017  1222 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:49.309  1017  1222 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
08-17 14:23:49.309  1017  1222 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-17 14:23:49.309  6926  6926 I bluedroid: get_profile_interface handsfree,
,08-17 14:23:49.309  1017  3207 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 14:23:49.309  1017  3207 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-17 14:23:49.309  1017  3207 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:49.309  1017  3207 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:49.309  1017  3207 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 14:23:49.309  6926  6948 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-17 14:23:49.309  6926  6948 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-17 14:23:49.319  6926  6948 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-17 14:23:49.329  1017  1531 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 14:23:49.329  1017  1531 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-17 14:23:49.329  1017  1531 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:49.329  1017  1531 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:49.329  1017  1531 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:49.329  6926  6948 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-17 14:23:49.329  6926  6948 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-17 14:23:49.329  6926  6948 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,08-17 14:23:49.329  6926  6948 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-17 14:23:49.329  6926  6948 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-17 14:23:49.339  6926  6926 I DualScoManager: Instantiating Dual Sco Manager
08-17 14:23:49.339  6926  6926 I DualScoManager: Set HeadsetServiceHelper
08-17 14:23:49.339  6926  6948 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,08-17 14:23:49.339  6926  6948 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
,08-17 14:23:49.339  6926  6948 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-17 14:23:49.339  6926  6948 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-17 14:23:49.339  6926  6948 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
,08-17 14:23:49.339  6926  6948 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-17 14:23:49.339  6926  6926 D BluetoothAtMessage: createCMTIContentObservers
08-17 14:23:49.339  6926  6948 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,08-17 14:23:49.339  1017  1727 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-17 14:23:49.339  6926  6948 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-17 14:23:49.339  1017  1727 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 14:23:49.339  1017  1727 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 14:23:49.339  1017  1727 D SettingsProvider: selectionArgs: false
08-17 14:23:49.339  1017  1727 D SettingsProvider: selectionArgs: 1002
08-17 14:23:49.339  1017  1727 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 14:23:49.339  1017  1727 D SettingsProvider: ret = -1
,08-17 14:23:49.339  6926  6957 D HeadsetStateMachine: Enter Disconnected: -2
,08-17 14:23:49.339  6926  6926 D HeadsetService: mStartError = false
,08-17 14:23:49.339  6926  6926 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d6b0b11
,08-17 14:23:49.339  6926  6926 E BluetoothAdapterService(1030425361): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-17 14:23:49.349  6926  6926 D A2dpService: Received start request. Starting profile...
,08-17 14:23:49.349  6926  6926 D A2dpService: start()
,08-17 14:23:49.349  6926  6926 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-17 14:23:49.349  6926  6926 I bluedroid: get_profile_interface avrcp
,08-17 14:23:49.349  6926  6957 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-17 14:23:49.349  6926  6957 D HeadsetStateMachine: map size, before remove : 0
08-17 14:23:49.349  6926  6957 D HeadsetStateMachine: map size, after remove: 0
,08-17 14:23:49.359  6926  6926 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-17 14:23:49.379  6926  6926 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-17 14:23:49.379  6926  6961 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-17 14:23:49.379  6926  6926 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-17 14:23:49.379  6926  6926 D A2dpStateMachine: make
,08-17 14:23:49.379  6926  6926 I bluedroid: get_profile_interface a2dp
,08-17 14:23:49.379  6926  6963 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-17 14:23:49.379  6926  6926 E bt-btif : warning : media task started media_task_refcnt 1 
,08-17 14:23:49.389  6926  6926 D A2dpService: mStartError = false
08-17 14:23:49.389  6926  6926 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d6b0b11
,08-17 14:23:49.389  6926  6926 I BluetoothHidServiceJni: classInitNative: succeeds
,08-17 14:23:49.389  6926  6962 D A2dpStateMachine: Enter Disconnected: -2
08-17 14:23:49.389  6926  6926 D HidService: Received start request. Starting profile...
08-17 14:23:49.389  6926  6926 D HidService: start()
08-17 14:23:49.389  6926  6926 I bluedroid: get_profile_interface hidhost
08-17 14:23:49.389  6926  6926 D HidService: setHidService(): set to: null
08-17 14:23:49.389  6926  6926 D HidService: mStartError = false
08-17 14:23:49.389  6926  6926 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d6b0b11
,08-17 14:23:49.389  6926  6926 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-17 14:23:49.389  6926  6926 D HealthService: Received start request. Starting profile...
08-17 14:23:49.389  6926  6926 D HealthService: start()
,08-17 14:23:49.389  6926  6926 I bluedroid: get_profile_interface health
,08-17 14:23:49.389  6926  6926 D HealthService: mStartError = false
08-17 14:23:49.389  6926  6926 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d6b0b11
,08-17 14:23:49.389  6926  6926 D HeadsetStateMachine: Try to query the phonestate on bind
08-17 14:23:49.389  1436  2754 I Telecom : BluetoothPhoneService: queryPhoneState
,08-17 14:23:49.399  1436  1436 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0,
08-17 14:23:49.399  1436  1436 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-17 14:23:49.399  1436  2754 I Telecom : BluetoothPhoneService: Result of Message : true
08-17 14:23:49.399  6926  6926 I BluetoothPanServiceJni: classInitNative(L105): succeeds,
,08-17 14:23:49.399  6926  6961 D BluetoothMediaBrowser: no now playing list
,08-17 14:23:49.399  6926  6961 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-17 14:23:49.399  6926  6926 D PanService: Received start request. Starting profile...
08-17 14:23:49.399  6926  6926 D PanService: start()
08-17 14:23:49.399  6926  6926 D BluetoothPanServiceJni: initializeNative(L110): pan
08-17 14:23:49.399  6926  6926 I bluedroid: get_profile_interface pan
,08-17 14:23:49.399  6926  6926 D PanService: mStartError = false
08-17 14:23:49.399  6926  6926 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d6b0b11
,08-17 14:23:49.399  6926  6926 D HeadsetStateMachine: Proxy object connected
,08-17 14:23:49.399  6926  6926 D BluetoothMapService: Received start request. Starting profile...
,08-17 14:23:49.399  6926  6926 D BluetoothMapService: start()
,08-17 14:23:49.409  6926  6926 D BluetoothMapService: mStartError = false
,08-17 14:23:49.409  6926  6926 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d6b0b11
,08-17 14:23:49.409  6926  6926 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
08-17 14:23:49.409  6926  6957 D HeadsetStateMachine: Disconnected process message: 11
08-17 14:23:49.409  6926  6926 D HeadsetPhoneState: sendDeviceDataStateChanged
,08-17 14:23:49.409  6926  6926 D HeadsetPhoneState: Signal level : previous=0 curr=0
,08-17 14:23:49.409  6926  6926 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
08-17 14:23:49.409  6926  6957 D HeadsetStateMachine: Disconnected process message: 18
,08-17 14:23:49.409  6926  6926 D SapService: Received start request. Starting profile...
08-17 14:23:49.409  6926  6926 D SapService: start()
08-17 14:23:49.409  6926  6926 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-17 14:23:49.409  6926  6926 I bluedroid: get_profile_interface sap
08-17 14:23:49.409  6926  6926 D SapService: mStartError = false
08-17 14:23:49.409  6926  6926 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d6b0b11
08-17 14:23:49.409  6926  6926 E BluetoothAdapterService(1030425361): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,08-17 14:23:49.409  6926  6926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-17 14:23:49.409  6926  6926 D BluetoothA2dp: Proxy object connected
08-17 14:23:49.409  6926  6926 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-17 14:23:49.409  6926  6926 E BluetoothAdapterService(1030425361): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-17 14:23:49.409  6926  6926 E BluetoothAdapterService(1030425361): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-17 14:23:49.409  6926  6926 E BluetoothAdapterService(1030425361): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,08-17 14:23:49.409  6926  6957 D HeadsetStateMachine: Disconnected process message: 10
08-17 14:23:49.409  6926  6957 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-17 14:23:49.409  6926  6957 D HeadsetStateMachine: Disconnected process message: 11
,08-17 14:23:49.419  6926  6926 E BluetoothAdapterService(1030425361): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-17 14:23:49.429  1934  1934 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-17 14:23:49.429  1934  1934 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-17 14:23:49.449  6926  6926 E BluetoothAdapterService(1030425361): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-17 14:23:49.449  6926  6926 E BluetoothAdapterService(1030425361): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-17 14:23:49.459  6926  6948 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-17 14:23:49.459  6926  6948 I bluedroid: enable
,08-17 14:23:49.459  6926  6967 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-17 14:23:49.459  6926  6948 I bt_hci_bdroid: init
,08-17 14:23:49.459  6926  6948 I bt_vendor: bt-vendor : init
08-17 14:23:49.459  6926  6948 I bt_vendor: bt-vendor : get_bt_soc_type
08-17 14:23:49.459  6926  6948 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-17 14:23:49.459  6926  6948 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
08-17 14:23:49.459  6926  6948 D bt_userial_mct: userial_init
08-17 14:23:49.459  6926  6948 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-17 14:23:49.459  6926  6948 I bt_vendor: Starting hciattach daemon
08-17 14:23:49.459  6926  6948 I bt_vendor: try to set false
,08-17 14:23:49.459  6926  6948 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,08-17 14:23:49.459  6926  6948 I bt_vendor: Starting hciattach daemon
08-17 14:23:49.459  6926  6948 I bt_vendor: try to set true
,08-17 14:23:49.489  6971  6971 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-17 14:23:49.539  6977  6977 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-17 14:23:49.549  6978  6978 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-17 14:23:49.569  6980  6980 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-17 14:23:49.579  6981  6981 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-17 14:23:49.589  6982  6982 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-17 14:23:49.589  6983  6983 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-17 14:23:49.819  6986  6986 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab ,
,08-17 14:23:49.829  6987  6987 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-17 14:23:49.869  6926  6948 I bt_vendor: bluetooth satus is on,
08-17 14:23:49.869  6926  6969 D bt_userial_mct: userial_open(port:0)
08-17 14:23:49.869  6926  6969 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-17 14:23:49.879  6926  6969 I bt_vendor: Done intiailizing UART,
,08-17 14:23:49.879  6926  6969 I bt_vendor: Done intiailizing UART,
08-17 14:23:49.879  6926  6969 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-17 14:23:49.879  6926  6969 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-17 14:23:49.879  6926  6967 I         : BTE_InitTraceLevels -- TRC_HCI
08-17 14:23:49.879  6926  6967 I         : BTE_InitTraceLevels -- TRC_L2CAP,
08-17 14:23:49.879  6926  6967 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-17 14:23:49.879  6926  6967 I         : BTE_InitTraceLevels -- TRC_AVDT
08-17 14:23:49.879  6926  6967 I         : BTE_InitTraceLevels -- TRC_AVRC
08-17 14:23:49.879  6926  6967 I         : BTE_InitTraceLevels -- TRC_A2D
08-17 14:23:49.879  6926  6967 I         : BTE_InitTraceLevels -- TRC_BNEP,
08-17 14:23:49.879  6926  6967 I         : BTE_InitTraceLevels -- TRC_BTM
08-17 14:23:49.879  6926  6967 I         : BTE_InitTraceLevels -- TRC_GAP
08-17 14:23:49.879  6926  6967 I         : BTE_InitTraceLevels -- TRC_PAN
08-17 14:23:49.879  6926  6967 I         : BTE_InitTraceLevels -- TRC_SAP
08-17 14:23:49.879  6926  6967 I         : BTE_InitTraceLevels -- TRC_SDP
08-17 14:23:49.879  6926  6967 I         : BTE_InitTraceLevels -- TRC_GATT
08-17 14:23:49.879  6926  6967 I         : BTE_InitTraceLevels -- TRC_SMP
08-17 14:23:49.879  6926  6967 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-17 14:23:49.879  6926  6967 I         : BTE_InitTraceLevels -- TRC_BTIF
08-17 14:23:49.879  6926  6967 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
08-17 14:23:49.879  6926  6990 D bt_userial_mct: Entering userial_read_thread()
,08-17 14:23:49.979  6926  6967 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-17 14:23:49.979  6926  6967 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa3faa6e9 
,08-17 14:23:49.979  6926  6967 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3faa6e9 
,08-17 14:23:49.989  1017  3056 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-17 14:23:49.989  1017  3056 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4253, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,08-17 14:23:49.989  1017  3056 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,08-17 14:23:49.989  1017  3056 D BatteryService: stay LED for charging
08-17 14:23:49.989  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-17 14:23:49.999  1017  1017 I MotionRecognitionService: Plugged
08-17 14:23:49.999  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-17 14:23:49.999  1181  1181 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-17 14:23:49.999  1181  1181 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-17 14:23:49.999  1421  1421 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-17 14:23:49.999  1421  1421 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-17 14:23:50.019  6926  6926 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-17 14:23:50.019  6926  6957 D HeadsetStateMachine: Disconnected process message: 10
,08-17 14:23:50.019  6926  6951 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-17 14:23:50.029  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-17 14:23:50.029  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-17 14:23:50.029  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-17 14:23:50.029  6926  6951 E bt-btif : Calling BTA_HhEnable
,08-17 14:23:50.029  6926  6951 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-17 14:23:50.029  6926  6951 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
08-17 14:23:50.029  6926  6951 E BluetoothServiceJni: populateRssiValuesNative
08-17 14:23:50.029  6926  6951 I bluedroid: getModelRssiValues
08-17 14:23:50.029  6926  6951 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-17 14:23:50.029  6926  6951 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-17 14:23:50.029  1017  1017 D SettingsProvider: name = bluetooth_name
,08-17 14:23:50.029  6926  6951 D BluetoothAdapterProperties: Name is: A5-1
,08-17 14:23:50.039  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:50.039  6926  6951 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-17 14:23:50.039  6926  6951 D BluetoothAdapterProperties: Scan Mode:20
08-17 14:23:50.039  6926  6951 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-17 14:23:50.039  6926  6951 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
08-17 14:23:50.039  6926  6951 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-17 14:23:50.039  6926  6951 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
08-17 14:23:50.039  6926  6951 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-17 14:23:50.039  6926  6951 E bt-btif : btif_sock_init: !vhci_init
08-17 14:23:50.039  6926  6951 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-17 14:23:50.039  6926  6951 D IOP_DB_BT: db_open: db_open : handle 3028398096l, read 13894 bytes onto local cache
,08-17 14:23:50.039  6926  6951 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-17 14:23:50.039  6926  6951 D IOP_DB_BT: db_query: result 1
,08-17 14:23:50.039  6926  6951 I         : iop_db_open: iop_db_open status 0
,08-17 14:23:50.039  6926  6951 D bte_conf: Device ID record 1 : primary
,08-17 14:23:50.039  6926  6951 D bte_conf:   vendorId            = 0075
08-17 14:23:50.039  6926  6951 D bte_conf:   vendorIdSource      = 0001
,08-17 14:23:50.049  6926  6951 D bte_conf:   product             = 0100
08-17 14:23:50.049  6926  6951 D bte_conf:   version             = 0200
08-17 14:23:50.049  6926  6990 E bt_mct  : hci lib postload completed
08-17 14:23:50.049  6926  6951 D bte_conf:   clientExecutableURL = 
,08-17 14:23:50.049  6926  6951 D bte_conf:   serviceDescription  = 
,08-17 14:23:50.049  6926  6951 D bte_conf:   documentationURL    = 
,08-17 14:23:50.049  6926  6951 D bte_conf: bte_load_did_conf no section named DID2.
,08-17 14:23:50.049  6926  6948 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-17 14:23:50.049  6926  6948 D BluetoothAdapterProperties: ScanMode =  20
,08-17 14:23:50.049  6926  6948 D BluetoothAdapterProperties: State =  11
,08-17 14:23:50.049  1017  3207 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-17 14:23:50.049  6926  6948 D BluetoothAdapterProperties: Setting state to 12
,08-17 14:23:50.049  6926  6948 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-17 14:23:50.059  6926  6951 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-17 14:23:50.059  6926  6951 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-17 14:23:50.059  6926  6951 D BluetoothAdapterProperties: Scan Mode:21
08-17 14:23:50.059  6926  6951 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-17 14:23:50.059  1017  1531 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-17 14:23:50.059  1017  1531 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 14:23:50.059  1017  1531 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 14:23:50.059  1017  1531 D SettingsProvider: selectionArgs: false
08-17 14:23:50.059  1017  1531 D SettingsProvider: selectionArgs: 1002
,08-17 14:23:50.059  1017  1531 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 14:23:50.059  1017  1531 D SettingsProvider: ret = -1
,08-17 14:23:50.059  6926  6948 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-17 14:23:50.059  6926  6948 D BluetoothAdapterService: updateAdapterState state is 12
,08-17 14:23:50.059  1017  1079 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 14:23:50.059  1017  1079 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-17 14:23:50.069  1017  1079 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:50.069  1017  1079 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:50.069  1017  1079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:50.069  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:23:50.069  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:50.069  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:50.069  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:23:50.069  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:23:50.069  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:23:50.069  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:23:50.069  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 14:23:50.069  1017  1047 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-17 14:23:50.069  1017  1047 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 14:23:50.069  6926  6948 D BluetoothAdapterService: Autoconnection is available 
08-17 14:23:50.069  1446  1470 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 14:23:50.069  1446  1470 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-17 14:23:50.069  6926  6948 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-17 14:23:50.069  6926  6948 D BluetoothAdapterService: starting service from this receiver
08-17 14:23:50.069  1436  1457 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 14:23:50.079  1017  1222 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 14:23:50.069  1436  1457 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-17 14:23:50.079  1017  1222 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-17 14:23:50.079  6926  6935 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-17 14:23:50.079  6926  6935 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 14:23:50.079  6291  6291 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 14:23:50.079  1017  1222 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:50.079  1436  2754 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 14:23:50.079  1017  1222 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:50.079  1017  1222 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:50.079  6926  6948 I BluetoothAdapterState: Entering On State from state = 11
08-17 14:23:50.079  1017  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 14:23:50.079  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 14:23:50.079  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:50.079  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:50.079  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:50.089  1436  2754 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 14:23:50.089  6291  6301 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 14:23:50.089  6291  6301 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-17 14:23:50.089  1323  1335 D Bluetoothsap: onBluetoothStateChange: up=true
08-17 14:23:50.089  1323  1335 D Bluetoothsap: Binding service...
,08-17 14:23:50.089  6291  6344 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:23:50.089  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:50.089  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:50.089  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:23:50.089  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:23:50.089  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:23:50.089  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:23:50.089  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 14:23:50.089  6291  6344 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 14:23:50.089  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 14:23:50.089  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3231c522 added. We now have 8 listener(s)
08-17 14:23:50.089  6291  6344 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 14:23:50.099  1323  1335 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-17 14:23:50.099  1017  3205 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-17 14:23:50.099  1017  3205 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-17 14:23:50.099  1017  3205 D SecContentProvider2: mCursor = null
,08-17 14:23:50.099  1017  3205 D WifiService: setWifiEnabled: false pid=6291, uid=10155
,08-17 14:23:50.099  1017  3205 D SettingsProvider: name = wifi_on
,08-17 14:23:50.099  6926  6926 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-17 14:23:50.109  6291  6344 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:50.109  1017  1485 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-17 14:23:50.109  1017  1485 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-17 14:23:50.109  1017  1485 D SecContentProvider2: mCursor = null
,08-17 14:23:50.109  1017  1485 D WifiService: setWifiEnabled: true pid=6291, uid=10155
,08-17 14:23:50.109  1017  1485 W ActivityManager: Permission Denial: getCurrentUser() from pid=6291, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,08-17 14:23:50.109  1017  1485 W WifiService: Failed getting userId using ActivityManagerNative
08-17 14:23:50.109  1017  1485 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6291, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-17 14:23:50.109  1017  1485 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-17 14:23:50.109  1017  1485 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-17 14:23:50.109  1017  1485 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-17 14:23:50.109  1017  1485 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-17 14:23:50.109  1017  1485 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-17 14:23:50.109  1017  1485 D SettingsProvider: name = wifi_on
,08-17 14:23:50.119  1017  1129 E WifiHW  : ##################### set firmware type 0 #####################
,08-17 14:23:50.249  1017  1047 I art     : Explicit concurrent mark sweep GC freed 29731(1758KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 27MB/41MB, paused 2.624ms total 150.254ms
,08-17 14:23:50.249  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-17 14:23:50.249  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-17 14:23:50.249  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:50.249  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:50.249  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:50.249  1323  1335 D Bluetoothsap: bindService called to Bluetooth SAP Service
08-17 14:23:50.249  1017  1047 D BluetoothPan: Binding service...
08-17 14:23:50.249  1017  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-17 14:23:50.249  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-17 14:23:50.249  1459  1469 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 14:23:50.249  1459  1469 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 14:23:50.249  6393  6403 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 14:23:50.249  6393  6403 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 14:23:50.259  2892  2900 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 14:23:50.259  1017  1047 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 14:23:50.259  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 14:23:50.259  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:50.259  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:50.259  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:50.259  2892  2900 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 14:23:50.259  6926  6926 I BluetoothPbapService: Handler(): got msg=1
,08-17 14:23:50.259  1323  6900 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-17 14:23:50.259  1323  6900 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-17 14:23:50.259  1017  1030 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-17 14:23:50.259  1323  1336 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-17 14:23:50.269  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-17 14:23:50.269  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-17 14:23:50.269  1323  1323 D Bluetoothsap: BluetoothSAP Proxy object connected
08-17 14:23:50.269  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:50.269  1017  1017 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 14:23:50.269  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:50.269  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:50.269  1323  1323 D SapProfile: Bluetooth service connected
08-17 14:23:50.269  1323  1323 D Bluetoothsap: getConnectedDevices()
08-17 14:23:50.269  1934  2123 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 14:23:50.269  1934  2123 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 14:23:50.269  6926  6999 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-17 14:23:50.269  1436  1445 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 14:23:50.269  1017  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 14:23:50.269  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 14:23:50.279  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:50.279  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:50.279  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:50.279  1436  1445 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 14:23:50.279  1323  1335 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 14:23:50.279  1323  1323 D BluetoothInputDevice: Proxy object connected
,08-17 14:23:50.279  1323  1335 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-17 14:23:50.279  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-17 14:23:50.279  1323  1323 D HidProfile: Bluetooth service connected
08-17 14:23:50.279  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 14:23:50.279  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:50.279  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:50.279  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:50.279  1017  1047 D BluetoothA2dp: onBluetoothStateChange: up=true
08-17 14:23:50.279  6926  6999 D BluetoothSocket: bindListen(): myUserId = 0
08-17 14:23:50.279  6926  6999 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 14:23:50.279  1017  1047 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-17 14:23:50.279  1017  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-17 14:23:50.279  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 14:23:50.279  1017  1017 D BluetoothA2dp: Proxy object connected
,08-17 14:23:50.279  1436  2754 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 14:23:50.279  1323  1323 D BluetoothA2dp: Proxy object connected
,08-17 14:23:50.289  1017  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 14:23:50.289  1323  1323 D A2dpProfile: Bluetooth service connected
08-17 14:23:50.289  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 14:23:50.289  6926  6999 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
,08-17 14:23:50.289  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:50.289  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:50.289  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-17 14:23:50.289  6926  6999 D BluetoothSocket: bindListen(), new LocalSocket 
08-17 14:23:50.289  6926  6999 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-17 14:23:50.289  6926  6999 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@fd42f12
,08-17 14:23:50.289  1436  2754 E BluetoothHeadset: BluetoothHeadset service is binded
08-17 14:23:50.289  6926  6999 D BluetoothSocket: channel: 19
08-17 14:23:50.289  6926  6999 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-17 14:23:50.289  1323  6900 D BluetoothPbap: onBluetoothStateChange: up=true
,08-17 14:23:50.289  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-17 14:23:50.289  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-17 14:23:50.289  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:50.289  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:50.289  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:50.289  2892  6899 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-17 14:23:50.289  2892  6899 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-17 14:23:50.289  2892  2914 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 14:23:50.299  1323  1323 D BluetoothPbap: Proxy object connected
08-17 14:23:50.299  1323  1323 D PbapServerProfile: Bluetooth service connected
,08-17 14:23:50.299  2892  2914 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-17 14:23:50.299  1017  1047 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-17 14:23:50.299  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 14:23:50.299  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:50.299  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:50.299  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:50.299  2892  2892 D BluetoothA2dp: Proxy object connected
,08-17 14:23:50.299  1323  1335 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 14:23:50.299  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 14:23:50.299  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 14:23:50.309  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:50.309  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:50.309  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:50.309  1323  1335 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 14:23:50.309  1323  1323 D HeadsetProfile: Bluetooth service connected
,08-17 14:23:50.309  1323  1336 D BluetoothPan: Binding service...
,08-17 14:23:50.309  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-17 14:23:50.309  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-17 14:23:50.309  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:50.309  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:50.309  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:50.309  1181  1895 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-17 14:23:50.319  1181  1895 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-17 14:23:50.319  1323  1323 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 14:23:50.319  1323  1323 D PanProfile: Bluetooth service connected
,08-17 14:23:50.319  1323  6900 D BluetoothMap: onBluetoothStateChange: up=true
,08-17 14:23:50.319  1017  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,08-17 14:23:50.319  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-17 14:23:50.319  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:50.319  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:50.319  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:50.329  6926  6935 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 14:23:50.329  1323  1323 D BluetoothMap: Proxy object connected
,08-17 14:23:50.329  1459  1471 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 14:23:50.329  1323  1323 D MapProfile: Bluetooth service connected
08-17 14:23:50.329  1017  1047 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 14:23:50.329  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-17 14:23:50.329  1323  1323 D BluetoothMap: getConnectedDevices()
,08-17 14:23:50.329  1017  1047 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:50.329  1017  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:50.329  1017  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:50.329  1459  1471 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 14:23:50.329  1017  1047 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 14:23:50.329  1017  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 14:23:50.329  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-17 14:23:50.329  1017  1047 E BluetoothHeadset: BluetoothHeadset service is binded
08-17 14:23:50.329  1017  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-17 14:23:50.329  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-17 14:23:50.339  1181  1181 D BluetoothTile:  onBluetoothStateChange:
,08-17 14:23:50.339  1181  1712 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 14:23:50.339  1181  1181 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-17 14:23:50.339  1181  1181 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:23:50.339  1181  1181 D BluetoothTile:  getBluetoothState : 12
,08-17 14:23:50.339  1436  1436 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@70df9ae, true
,08-17 14:23:50.339  1436  1436 D BluetoothHeadset: registerMessageListener
,08-17 14:23:50.349  1797  1797 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-17 14:23:50.349  1181  1712 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 14:23:50.349  1017  3207 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 14:23:50.349  1017  1483 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-17 14:23:50.349  1181  1181 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 14:23:50.349  1181  1712 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 14:23:50.349  1323  1323 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 14:23:50.359  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:23:50.359  1017  3057 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 14:23:50.359  6926  6934 D HeadsetService: registerMessageListener
08-17 14:23:50.359  1017  3057 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-17 14:23:50.359  6926  6934 D HeadsetService: registerMessageListener
08-17 14:23:50.359  1436  1436 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-17 14:23:50.359  1017  3057 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:50.359  1436  1436 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-17 14:23:50.359  1017  3057 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-17 14:23:50.359  1436  1436 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-17 14:23:50.359  1017  3057 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-17 14:23:50.359  1436  1436 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-17 14:23:50.359  1436  1436 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-17 14:23:50.359  6926  6957 D HeadsetStateMachine: Disconnected process message: 70
08-17 14:23:50.359  6926  6957 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@1d9bb6e3
,08-17 14:23:50.359  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-17 14:23:50.359  1017  1017 I InputMethodManagerService: [BT Setting State] State =12
08-17 14:23:50.359  1017  1017 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-17 14:23:50.369  1323  1323 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,08-17 14:23:50.369  1323  1323 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-17 14:23:50.369  1323  1323 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-17 14:23:50.369  1323  1323 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-17 14:23:50.369  6926  6957 D HeadsetStateMachine: Disconnected process message: 9
08-17 14:23:50.369  6926  6957 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-17 14:23:50.369  6926  7007 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-17 14:23:50.369   283  1015 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-17 14:23:50.369   283  1015 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-17 14:23:50.369   283  1015 V voice   : voice_set_parameters: exit with code(-2)
08-17 14:23:50.369   283  1015 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-17 14:23:50.369   283  1015 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-17 14:23:50.369   283  1015 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-17 14:23:50.369   283  1015 V audio_hw_primary: adev_set_parameters: exit
,08-17 14:23:50.369  6926  6957 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-17 14:23:50.379  1323  1323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 14:23:50.379  1017  3205 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-17 14:23:50.379  1017  3205 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-17 14:23:50.379  1017  3205 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:50.379  1017  3205 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:50.379  1017  3205 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
08-17 14:23:50.379  6926  7007 D BluetoothSocket: bindListen(): myUserId = 0
08-17 14:23:50.379  6926  7007 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 14:23:50.389  6926  7007 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
08-17 14:23:50.389  6926  7007 D BluetoothSocket: bindListen(), new LocalSocket 
08-17 14:23:50.389  6926  7007 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-17 14:23:50.389  6926  7007 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@239838e0
,08-17 14:23:50.389  6926  7007 D BluetoothSocket: channel: 5
,08-17 14:23:50.389  1323  1323 D DockEventReceiver: finishStartingService: stopping service
,08-17 14:23:50.389  1323  1323 D BluetoothNotiBroadcastReceiver: onReceive
,08-17 14:23:50.399  1181  1181 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 14:23:50.399  1181  1181 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-17 14:23:50.409  6926  6926 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d6b0b11
,08-17 14:23:50.409  6926  6926 D BtConfig.SecureMode: isSecureModeOn:false
,08-17 14:23:50.409  1017  3205 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 14:23:50.409  1017  3205 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-17 14:23:50.409  1017  3205 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:50.409  1017  3205 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:50.409  1017  3205 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 14:23:50.429  1934  1934 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-17 14:23:50.429  1017  2745 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-17 14:23:50.429  1017  2745 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-17 14:23:50.429  1017  2745 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:50.429  1017  2745 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 14:23:50.429  1017  2745 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 14:23:50.439  1017  3057 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-17 14:23:50.439  1934  7015 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-17 14:23:50.439  1934  1934 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-17 14:23:50.439  1017  1505 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 14:23:50.439  1017  1505 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:50.439  1017  1505 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-17 14:23:50.439  1017  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 14:23:50.459  6926  7017 D BluetoothSocket: bindListen(): myUserId = 0
,08-17 14:23:50.459  6926  7017 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 14:23:50.459  1017  1505 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 14:23:50.459  1017  1505 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:50.459  1017  1505 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 14:23:50.459  6926  7017 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
08-17 14:23:50.459  6926  7017 D BluetoothSocket: bindListen(), new LocalSocket 
08-17 14:23:50.459  1017  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-17 14:23:50.459  6926  7017 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-17 14:23:50.459  6926  7017 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@cf8030c
,08-17 14:23:50.459  6926  7017 D BluetoothSocket: channel: 12
08-17 14:23:50.459  6926  7017 I BtOppRfcommListener: Accept thread started.
,08-17 14:23:50.469  1017  1045 D Tethering: interfaceAdded wlan0
,08-17 14:23:50.469  1017  1133 E Tethering: No numeric data
08-17 14:23:50.469  1017  1133 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-17 14:23:50.469  1017  1133 D Tethering: clearTetheredNotification()
,08-17 14:23:50.469  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 14:23:50.469  1017  1126 V NetworkStats: performPollLocked(flags=0x1)
08-17 14:23:50.469  1934  7015 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
08-17 14:23:50.469  1017  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 14:23:50.469  1017  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 14:23:50.469  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 14:23:50.469  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
08-17 14:23:50.469  1181  1181 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-17 14:23:50.469  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 14:23:50.479  1017  1133 D Tethering: InitialState.processMessage what=4
08-17 14:23:50.469  1181  1181 D HotspotTile: updateTetherState():false, false
,08-17 14:23:50.479  1017  1133 E Tethering: No numeric data
08-17 14:23:50.479  1017  1126 V NetworkStats: performPollLocked() took 6ms
08-17 14:23:50.479  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 14:23:50.479  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 14:23:50.479  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 14:23:50.479  1017  1133 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-17 14:23:50.479  1017  1133 D Tethering: clearTetheredNotification()
,08-17 14:23:50.479  1017  1126 V NetworkStats: performPollLocked(flags=0x1)
08-17 14:23:50.479  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 14:23:50.479  1017  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 14:23:50.479  1017  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 14:23:50.479  1181  1181 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-17 14:23:50.479  1181  1181 D HotspotTile: updateTetherState():false, false
,08-17 14:23:50.489  1017  1126 V NetworkStats: performPollLocked() took 3ms
08-17 14:23:50.489  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 14:23:50.489  1017  1045 D Tethering: interfaceAdded p2p0
,08-17 14:23:50.489  1017  1045 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-17 14:23:50.489  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 14:23:50.489  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 14:23:50.489  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false
,08-17 14:23:50.489  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-17 14:23:50.489  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-17 14:23:50.489   278   986 I WifiHW  : wifi_change_fw_path(): fwpath = sta,
08-17 14:23:50.489   278   986 D SoftapController: Softap fwReload - Ok,
,08-17 14:23:50.499   278   986 D CommandListener: Setting iface cfg,
08-17 14:23:50.499   278   986 D CommandListener: Trying to bring down wlan0
08-17 14:23:50.499   278   986 D CommandListener: Clearing all IP addresses on wlan0
,08-17 14:23:50.499  1017  1129 E WifiHW  : supplicant_name : p2p_supplicant
,08-17 14:23:50.499  1017  1129 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-17 14:23:50.509  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 14:23:50.509  1181  1712 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-17 14:23:50.509  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-17 14:23:50.509  1181  1181 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 14:23:50.509  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:50.509  1181  1181 D HotspotTile: onReceive : 2, 0
08-17 14:23:50.509  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:50.509  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-17 14:23:50.509  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:50.509  1181  1181 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 14:23:50.509  1181  1181 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-17 14:23:50.519  1323  1323 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-17 14:23:50.519  1017  1531 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-17 14:23:50.519  1017  1531 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 14:23:50.519  1017  1531 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:50.519  1017  1531 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:50.519  1017  1531 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 14:23:50.519  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:50.529  6496  6496 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-17 14:23:50.529  6496  6496 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-17 14:23:50.529  6496  6496 D SecurityLogAgent: StateMachine : Current State = 1
,08-17 14:23:50.529  3670  3670 I Hs20UtilService: Starting #19
08-17 14:23:50.529  6496  6496 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 14:23:50.529  3670  3711 I Hs20UtilService: Message received 5011,
,08-17 14:23:50.539  7019  7019 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-17 14:23:50.539  7019  7019 I wpa_supplicant: Successfully initialized wpa_supplicant
08-17 14:23:50.539  7019  7019 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-17 14:23:50.549  7019  7019 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-17 14:23:50.549   398   398 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 7019,
08-17 14:23:50.549   398   398 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
08-17 14:23:50.549  7019  7019 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
,08-17 14:23:50.549  7019  7019 I wpa_supplicant: ssSupport state is = 1
08-17 14:23:50.549  7019  7019 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-17 14:23:50.549  7019  7019 I SecureStorage: [INFO]: SPID(0x00000000)Processing data,
08-17 14:23:50.549   398   398 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 7019,
08-17 14:23:50.549   398   398 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x00000106
,08-17 14:23:50.709   398   398 I SecureStorage: [INFO]: SPID(0x00000006)Secure Storage Daemon finished processing with result: 0,
,08-17 14:23:50.719  7019  7019 I SecureStorage: [INFO]: SPID(0x00000006)Processing data has been completed
,08-17 14:23:50.779  7019  7019 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-17 14:23:50.779  7019  7019 I SecureStorage: [INFO]: SPID(0x00000006)Checking if this device supports Secure Storage
,08-17 14:23:50.789  7019  7019 I SecureStorage: [INFO]: SPID(0x00000006)This device supports Secure Storage,
08-17 14:23:50.789   398   398 I SecureStorage: [INFO]: SPID(0x00000006)Credentials: uid 1010, gid 1010, pid 7019
08-17 14:23:50.789   398   398 I SecureStorage: [INFO]: SPID(0x00000006)Received function mask & code: 0x0000010C
08-17 14:23:50.789  7019  7019 I SecureStorage: [INFO]: SPID(0x00000006)SS Daemon is running,
08-17 14:23:50.789  7019  7019 I wpa_supplicant: ssSupport state is = 1
08-17 14:23:50.789  7019  7019 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 14:23:50.789  7019  7019 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 14:23:50.789  7019  7019 E wpa_supplicant: SIM READ ERROR,
08-17 14:23:50.789  7019  7019 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 14:23:50.789  7019  7019 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 14:23:50.789  7019  7019 E wpa_supplicant: SIM READ ERROR
08-17 14:23:50.789  7019  7019 I wpa_supplicant: Blacklist: Clear (all) ,
,08-17 14:23:50.799  7019  7019 I wpa_supplicant: wpa_default_ap_write_once
08-17 14:23:50.799  7019  7019 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-17 14:23:50.799  7019  7019 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-17 14:23:50.799  7019  7019 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-17 14:23:50.799  7019  7019 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 14:23:50.799  7019  7019 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-17 14:23:50.799  7019  7019 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-17 14:23:50.799  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false,
08-17 14:23:50.799  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 14:23:50.799  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-17 14:23:50.849  7019  7019 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-17 14:23:50.849   290   290 E SMD     : DCD OFF,
,08-17 14:23:50.999  7019  7019 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-17 14:23:50.999  7019  7019 I SecureStorage: [INFO]: SPID(0x00000006)Checking if this device supports Secure Storage,
,08-17 14:23:51.009  7019  7019 I SecureStorage: [INFO]: SPID(0x00000006)This device supports Secure Storage
08-17 14:23:51.009   398   398 I SecureStorage: [INFO]: SPID(0x00000006)Credentials: uid 1010, gid 1010, pid 7019,
08-17 14:23:51.009   398   398 I SecureStorage: [INFO]: SPID(0x00000006)Received function mask & code: 0x0000010C
08-17 14:23:51.009  7019  7019 I SecureStorage: [INFO]: SPID(0x00000006)SS Daemon is running
08-17 14:23:51.009  7019  7019 I wpa_supplicant: ssSupport state is = 1,
08-17 14:23:51.019  7019  7019 I wpa_supplicant: Ctrl_iface: loading cred from phone
,08-17 14:23:51.019  7019  7019 I SecureStorage: [INFO]: SPID(0x00000006)Checking if this device supports Secure Storage
,08-17 14:23:51.029  7019  7019 I SecureStorage: [INFO]: SPID(0x00000006)This device supports Secure Storage,
08-17 14:23:51.029   398   398 I SecureStorage: [INFO]: SPID(0x00000006)Credentials: uid 1010, gid 1010, pid 7019
08-17 14:23:51.029   398   398 I SecureStorage: [INFO]: SPID(0x00000006)Received function mask & code: 0x0000010C,
08-17 14:23:51.029  7019  7019 I SecureStorage: [INFO]: SPID(0x00000006)SS Daemon is running
08-17 14:23:51.029  7019  7019 I wpa_supplicant: ssSupport state is = 1
08-17 14:23:51.029  7019  7019 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-17 14:23:51.029  7019  7019 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-17 14:23:51.039  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-17 14:23:51.029  7019  7019 E wpa_supplicant: SIM READ ERROR
08-17 14:23:51.039  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-17 14:23:51.029  7019  7019 I wpa_supplicant: wpa_default_ap_write_once
08-17 14:23:51.029  7019  7019 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
,08-17 14:23:51.029  7019  7019 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-17 14:23:51.039  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false
,08-17 14:23:51.039  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
08-17 14:23:51.039  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-17 14:23:51.039  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-17 14:23:51.079  7019  7019 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-17 14:23:51.079  7019  7019 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-17 14:23:51.139  7019  7019 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-17 14:23:51.139  7019  7019 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-17 14:23:51.139  7019  7019 I wpa_supplicant: Skip scan - bUseNetwork false,
,08-17 14:23:51.149  1017  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
,08-17 14:23:51.149  1017  1129 D WifiNative-wlan0: callSECApiBoolean - ID [21],
08-17 14:23:51.149  7019  7019 I wpa_supplicant: HOTSPOT20_ENABLE called
08-17 14:23:51.149  7019  7019 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-17 14:23:51.149  7019  7019 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 14:23:51.149  7019  7019 E wpa_supplicant: SIM READ ERROR,
,08-17 14:23:51.149  7019  7019 I wpa_supplicant: Blacklist: Clear (all) ,
,08-17 14:23:51.159  7019  7019 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-17 14:23:51.169  1017  1129 D WifiNative-wlan0: callSECApiInt - ID [210],
08-17 14:23:51.169  7019  7019 I wpa_supplicant: Skip scan - bUseNetwork false,
08-17 14:23:51.169  1017  1129 D WifiConfigStore: Loading config and enabling all networks ,
,08-17 14:23:51.179  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 14:23:51.179  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 14:23:51.179  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:51.179  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:51.179  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:51.179  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:51.179  1181  1181 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 14:23:51.179  1181  1181 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-17 14:23:51.179  1181  1712 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-17 14:23:51.179  1181  1181 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-17 14:23:51.179  1181  1181 D HotspotTile: onReceive : 3, 0,
,08-17 14:23:51.189  1323  1323 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
,08-17 14:23:51.189  1017  1030 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 14:23:51.189  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 14:23:51.189  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:51.189  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:51.189  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 14:23:51.189  1017  1129 E WifiConfigStore: Not a HS20
,08-17 14:23:51.189  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:23:51.189  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:51.189  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:51.189  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:23:51.189  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:23:51.189  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:23:51.189  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:23:51.189  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 14:23:51.199  1017  1129 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-17 14:23:51.199  1017  1129 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-17 14:23:51.199  6291  6291 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 14:23:51.199  3670  3670 I Hs20UtilService: Starting #20
08-17 14:23:51.199  3670  3711 I Hs20UtilService: Message received 5011
,08-17 14:23:51.199  1017  1129 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,08-17 14:23:51.199  7019  7019 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-17 14:23:51.199  7019  7019 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-17 14:23:51.199  7019  7019 I wpa_supplicant: reset timer : RESET_TIMER 0
08-17 14:23:51.199  7019  7019 I wpa_supplicant: P2P: Current p2p state = IDLE
08-17 14:23:51.199  7019  7019 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-17 14:23:51.199  7019  7019 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-17 14:23:51.199  7019  7019 I wpa_supplicant: First Scan Start
,08-17 14:23:51.199  7019  7019 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-17 14:23:51.209  6496  6496 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-17 14:23:51.209  6496  6496 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-17 14:23:51.209  6496  6496 D SecurityLogAgent: StateMachine : Current State = 1
08-17 14:23:51.209  6496  6496 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-17 14:23:51.209  1017  1129 D WifiNative-wlan0: Setting external_sim to 1
,08-17 14:23:51.209  1017  1129 D WifiStateMachine: Setting OUI to DA-A1-19
08-17 14:23:51.209  1017  1129 I WifiNative-HAL: startHal
08-17 14:23:51.209  1017  1129 E wifi    : getStaticLongField sWifiHalHandle 0x9e11c88c
08-17 14:23:51.209  1017  1129 I WifiNative-HAL: Could not start hal
,08-17 14:23:51.209  6471  6471 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 14:23:51.209  1017  1129 E WifiNative-wlan0: do suspend true
,08-17 14:23:51.219  1017  1128 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-17 14:23:51.219   278   986 D CommandListener: Setting iface cfg
08-17 14:23:51.219   278   986 D CommandListener: Trying to bring up p2p0
,08-17 14:23:51.219  1017  1128 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-17 14:23:51.219  1017  1129 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-17 14:23:51.219  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 3
,08-17 14:23:51.219  1017  1152 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,08-17 14:23:51.219  1017  1152 I WifiNative-HAL: startHal
08-17 14:23:51.219  1017  1152 E wifi    : getStaticLongField sWifiHalHandle 0x9cdfe9bc
,08-17 14:23:51.219  1017  1152 I WifiNative-HAL: Could not start hal
08-17 14:23:51.219  1017  1152 E WifiScanningService: could not start HAL
08-17 14:23:51.219  1017  1128 D WifiP2pService: P2pEnablingState
08-17 14:23:51.219  1017  1017 D RttService: SCAN_AVAILABLE : 3
08-17 14:23:51.219  1017  1128 D WifiP2pService: P2pEnablingState{ what=147457 }
08-17 14:23:51.219  1017  1153 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:23:51.219  1017  1128 D WifiP2pService: P2p socket connection successful
08-17 14:23:51.219  1017  1129 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-17 14:23:51.219  1017  1128 D WifiP2pService: P2pEnabledState
08-17 14:23:51.219  1017  1129 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-17 14:23:51.219  1017  1128 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-17 14:23:51.219  1017  1129 E WifiNative-wlan0: invaild command id : 215
08-17 14:23:51.219  1017  1131 E ConnectivityService: updateNetworkInfo()
08-17 14:23:51.229  1017  1129 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-17 14:23:51.229  1017  1129 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-17 14:23:51.229  1017  1129 E WifiNative-wlan0: invaild command id : 215
,08-17 14:23:51.229  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED,
,08-17 14:23:51.229  1017  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-17 14:23:51.229  1017  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false,
08-17 14:23:51.229  1017  1048 D WifiDisplayController: disconnect
08-17 14:23:51.229  1017  1048 D WifiDisplayController: updateConnection,
,08-17 14:23:51.229  7019  7019 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-17 14:23:51.229  1017  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-17 14:23:51.229  7019  7019 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-17 14:23:51.229  1017  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-17 14:23:51.229  1181  1181 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-17 14:23:51.229  1017  1344 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-17 14:23:51.229  1181  1181 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-17 14:23:51.229  1017  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 14:23:51.229  1017  1048 D WifiDisplayAdapter: onP2pDisconnected
08-17 14:23:51.229  1017  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-17 14:23:51.229  1017  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-17 14:23:51.239  7019  7019 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,08-17 14:23:51.239  1323  1323 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-17 14:23:51.239  1323  1323 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-17 14:23:51.239  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-17 14:23:51.239  1017  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 14:23:51.239  1017  1129 D SecContentProvider2: mCursor = null
08-17 14:23:51.239  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-17 14:23:51.239  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 14:23:51.239  1323  1323 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-17 14:23:51.239  1017  1128 D WifiNative-p2p0: p2pGetDeviceAddress
08-17 14:23:51.239  1323  3116 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-17 14:23:51.239  1017  1128 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
,08-17 14:23:51.239  1017  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 14:23:51.239  1017  1129 D SecContentProvider2: mCursor = null
08-17 14:23:51.239  1017  1128 D WifiP2pService: DeviceAddress: 7e:96:ac
,08-17 14:23:51.239  1017  1048 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
08-17 14:23:51.239  1017  1048 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
08-17 14:23:51.239  1017  1048 D WifiDisplayController:  primary type: 10-0050F204-5
08-17 14:23:51.239  1017  1048 D WifiDisplayController:  secondary type: null
08-17 14:23:51.239  1017  1048 D WifiDisplayController:  wps: 0
,08-17 14:23:51.239  1017  1048 D WifiDisplayController:  grpcapab: 0
08-17 14:23:51.239  1017  1048 D WifiDisplayController:  devcapab: 0
08-17 14:23:51.239  1017  1048 D WifiDisplayController:  status: 3
08-17 14:23:51.239  1017  1048 D WifiDisplayController:  wfdInfo: null
08-17 14:23:51.239  1017  1048 D WifiDisplayController:  groupownerAddress: null
08-17 14:23:51.239  1017  1048 D WifiDisplayController:  GOdeviceName: null
08-17 14:23:51.239  1017  1048 D WifiDisplayController:  interfaceAddress: 
08-17 14:23:51.239  1017  1048 D WifiDisplayController:  SConnectInfo : null
,08-17 14:23:51.249  6441  6441 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-17 14:23:51.249  6441  6441 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected,
08-17 14:23:51.249  6441  6441 D FileShare-Client: Outbound.stopDelayTimer - 
,08-17 14:23:51.259  6456  6456 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-17 14:23:51.269  1017  1128 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-17 14:23:51.269  1017  1128 D WifiP2pService: InactiveState
,08-17 14:23:51.269  1017  1128 D WifiP2pService: InactiveState{ what=143376 }
08-17 14:23:51.269  1017  1128 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-17 14:23:51.269  7019  7019 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-17 14:23:51.269  1017  1128 D WifiP2pService: InactiveState{ what=143376 }
,08-17 14:23:51.269  1017  1128 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-17 14:23:51.469  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false,
08-17 14:23:51.469  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-17 14:23:51.469  1017  1045 D Tethering: interfaceStatusChanged p2p0, false,
,08-17 14:23:52.129  6291  6344 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:23:52.129  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:52.129  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:52.129  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:23:52.129  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:23:52.129  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:23:52.129  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:23:52.129  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 14:23:52.129  6291  6344 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 14:23:52.139  6291  6344 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-17 14:23:52.139  6291  6344 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-17 14:23:52.139  6291  6344 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@151ee58b Bundle[{}]
,08-17 14:23:52.139  6291  6344 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-17 14:23:52.139  6291  6344 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-17 14:23:52.149  6291  6344 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-17 14:23:52.149  6291  6344 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-17 14:23:52.149  6291  6344 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-17 14:23:52.149  6291  6344 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-17 14:23:52.159  6291  6344 I System.out: Running OutgoingSocketThread
,08-17 14:23:52.159  6291  7028 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1172)
,08-17 14:23:52.159  6291  7028 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 60120
,08-17 14:23:52.159  6291  7028 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-17 14:23:52.299  7019  7019 I wpa_supplicant: nl80211: Received scan results (16 BSSes)
08-17 14:23:52.299  7019  7019 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-17 14:23:52.299  7019  7019 I wpa_supplicant: Trying to associate with SSID '4E47373030',
08-17 14:23:52.299  7019  7019 I wpa_supplicant: Trying to associate with  'G700'
,08-17 14:23:52.299  7019  7019 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,08-17 14:23:52.299  7019  7019 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,08-17 14:23:52.299  1017  7024 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-17 14:23:52.319  1017  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 14:23:52.319  1017  1129 D SecContentProvider2: mCursor = null
,08-17 14:23:52.339  1017  1345 E Watchdog: !@Sync 5
,08-17 14:23:52.419  7019  7019 E wpa_supplicant: Cmd 35605 not handled
,08-17 14:23:52.419  7019  7019 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-17 14:23:52.419  7019  7019 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-17 14:23:52.419  7019  7019 I wpa_supplicant: Associated with F4.99.3E
08-17 14:23:52.419  7019  7019 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-17 14:23:52.419  7019  7019 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
,08-17 14:23:52.419  7019  7019 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-17 14:23:52.419  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 14:23:52.419  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-17 14:23:52.419  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
,08-17 14:23:52.419  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false,
08-17 14:23:52.419  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-17 14:23:52.419  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
08-17 14:23:52.429  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 14:23:52.429  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
,08-17 14:23:52.429  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-17 14:23:52.429  1017  1045 D Tethering: interfaceStatusChanged wlan0, false,
,08-17 14:23:52.429  7019  7019 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e,
08-17 14:23:52.429  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, true
08-17 14:23:52.429  1017  1045 D Tethering: interfaceStatusChanged wlan0, true
,08-17 14:23:52.429  7019  7019 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-17 14:23:52.429  7019  7019 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-17 14:23:52.429  7019  7019 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-17 14:23:52.429  7019  7019 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-17 14:23:52.429  7019  7019 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED,
,08-17 14:23:52.429  7019  7019 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-17 14:23:52.439  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-17 14:23:52.429  1017  1133 E Tethering: No numeric data
08-17 14:23:52.439  1017  1126 V NetworkStats: performPollLocked(flags=0x1)
08-17 14:23:52.429  1017  1133 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-17 14:23:52.439  1181  1181 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-17 14:23:52.429  1017  1133 D Tethering: clearTetheredNotification()
08-17 14:23:52.439  1181  1181 D HotspotTile: updateTetherState():false, false
08-17 14:23:52.429  7019  7019 I wpa_supplicant: Blacklist: Clear (temp) 
,08-17 14:23:52.429  7019  7019 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-17 14:23:52.439  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, true
08-17 14:23:52.439  1017  1045 D Tethering: interfaceStatusChanged wlan0, true
08-17 14:23:52.439  1017  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 14:23:52.439  1017  1129 D SecContentProvider2: mCursor = null
,08-17 14:23:52.439  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 14:23:52.439  1017  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 14:23:52.439  1017  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 14:23:52.449  1017  1129 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-17 14:23:52.449  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 14:23:52.449  1017  1126 V NetworkStats: performPollLocked() took 9ms
,08-17 14:23:52.449  1017  1129 E WifiConfigStore: setLastSelectedConfiguration -1
,08-17 14:23:52.459  1017  1129 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-17 14:23:52.459  1017  1131 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-17 14:23:52.459  1017  1131 E ConnectivityService: updateNetworkInfo()
08-17 14:23:52.459  1017  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-17 14:23:52.459  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 14:23:52.459  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 14:23:52.459  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 14:23:52.459  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-17 14:23:52.459  1017  1129 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 14:23:52.469  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 14:23:52.469  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:52.469  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:52.469  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 14:23:52.469  1017  1727 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 14:23:52.469  1017  1727 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 14:23:52.469  1017  1727 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:52.469  1017  1727 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:52.469  1017  1727 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 14:23:52.479  3670  3670 I Hs20UtilService: Starting #21
,08-17 14:23:52.479  3670  3711 I Hs20UtilService: Message received 5007
08-17 14:23:52.479  1017  1129 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-17 14:23:52.479  1323  1323 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-17 14:23:52.479  1323  1323 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-17 14:23:52.479  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-17 14:23:52.479  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED,
08-17 14:23:52.479  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 14:23:52.479  1323  1323 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-17 14:23:52.479  1323  3116 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 14:23:52.489   278   986 D CommandListener: Setting iface cfg
,08-17 14:23:52.489  1017  1129 E WifiStateMachine: Start Dhcp Watchdog 3
,08-17 14:23:52.499  1017  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-17 14:23:52.499  1017  1129 D SecContentProvider2: mCursor = null
,08-17 14:23:52.499  1017  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-17 14:23:52.499  1017  1129 D SecContentProvider2: mCursor = null
,08-17 14:23:52.509  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 14:23:52.509  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-17 14:23:52.509  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 14:23:52.509  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 14:23:52.509  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:52.509  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 14:23:52.519  1017  1129 E WifiNative-wlan0: do suspend false
,08-17 14:23:52.519  1017  1128 D WifiP2pService: InactiveState{ what=143375 },
08-17 14:23:52.519  1017  1129 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 14:23:52.519  1017  1128 D WifiP2pService: P2pEnabledState{ what=143375 }
08-17 14:23:52.519  1017  1129 D SecContentProvider2: mCursor = null
,08-17 14:23:52.609  1934  2582 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-17 14:23:52.739  7031  7031 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-17 14:23:52.739  7031  7031 I dhcpcd  : version 5.5.6 starting
,08-17 14:23:52.739  7031  7031 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-17 14:23:52.799  7031  7031 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-17 14:23:52.799  7031  7031 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-17 14:23:52.799  7031  7031 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-17 14:23:52.799  7031  7031 I dhcpcd  : bssid match
08-17 14:23:52.799  7031  7031 I dhcpcd  : wlan0: rebinding lease of 192.168.1.111
,08-17 14:23:52.819  1017  2759 D SSRM:n  : SIOP:: AP = 330
,08-17 14:23:52.849  7031  7031 I dhcpcd  : wlan0: acknowledged 192.168.1.111 from 192.168.1.1
,08-17 14:23:52.909  7031  7031 I dhcpcd  : wlan0: leased 192.168.1.111 for 172800 seconds,
,08-17 14:23:53.129  1017  1129 E WifiNative-wlan0: do suspend true
,08-17 14:23:53.159  1017  1128 D WifiP2pService: InactiveState{ what=143375 },
08-17 14:23:53.159  1017  1128 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-17 14:23:53.159  6291  6344 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1173)
08-17 14:23:53.159  6291  6344 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1173),
08-17 14:23:53.159  6291  6344 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1178)
,08-17 14:23:53.159  6291  6344 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-17 14:23:53.159  6291  6344 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1179)
,08-17 14:23:53.159  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 14:23:53.159  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 14:23:53.159  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 14:23:53.159  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:53.159  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:53.159  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:53.169  6291  6344 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 14:23:53.169  6291  6344 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@238d7bb3 added. We now have 2 listener(s)
08-17 14:23:53.169  1017  1129 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-17 14:23:53.169  1017  1129 E WifiStateMachine: VerifyingLinkState enter
,08-17 14:23:53.169  1017  1129 D WifiNative-wlan0: callSECApiInt - ID [210]
08-17 14:23:53.169  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-17 14:23:53.169  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 14:23:53.169  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 14:23:53.169  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:23:53.169  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e606570 added. We now have 9 listener(s)
08-17 14:23:53.169  6291  6344 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 14:23:53.169  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 14:23:53.169  1017  1131 E ConnectivityService: updateNetworkInfo()
,08-17 14:23:53.179  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 14:23:53.179  1017  1131 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
08-17 14:23:53.179  1017  1131 D ConnectivityService: Adding iface wlan0 to network 504
,08-17 14:23:53.189  1017  1146 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,08-17 14:23:53.189  1017  1146 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-17 14:23:53.189  1017  1146 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-17 14:23:53.189  1017  1146 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-17 14:23:53.189  1017  1146 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-17 14:23:53.189  6291  6344 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:23:53.189  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:53.189  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:53.189  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:23:53.189  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:23:53.189  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:23:53.189  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:23:53.189  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 14:23:53.199  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 14:23:53.199  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 14:23:53.199  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:53.199  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:53.199  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:53.199  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 14:23:53.209  1017  3056 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-17 14:23:53.209  1017  3056 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 14:23:53.209  1017  3056 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:53.209  1017  3056 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:53.209  1017  3056 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 14:23:53.209  6291  6344 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 14:23:53.209  1017  1131 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
08-17 14:23:53.209  6291  6344 D io.jxcore.node.ConnectivityMonitor: start: OK,
08-17 14:23:53.209  6291  6344 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 14:23:53.209  6291  6344 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@174b116e added. We now have 3 listener(s)
08-17 14:23:53.209  3670  3670 I Hs20UtilService: Starting #22
08-17 14:23:53.209  1017  1131 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,08-17 14:23:53.219  3670  3711 I Hs20UtilService: Message received 5007
08-17 14:23:53.219  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:53.219  1017  1131 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
,08-17 14:23:53.219  1017  1129 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,08-17 14:23:53.219  1017  1131 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-17 14:23:53.219  1323  1323 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-17 14:23:53.219  1017  1131 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
08-17 14:23:53.219  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-17 14:23:53.219  1017  1131 D ConnectivityService: LTETest block dns file not exists
08-17 14:23:53.219  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 14:23:53.219  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
08-17 14:23:53.219  1323  1323 I NearbySettings: MountReceiver.onReceive - Keep current state
08-17 14:23:53.219  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:23:53.219  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@335a200f added. We now have 10 listener(s)
08-17 14:23:53.219  6291  6344 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:23:53.219  6291  6344 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:23:53.219  6291  6344 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:23:53.219  6291  6344 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:23:53.219  6291  6344 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:53.219  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:53.219  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:23:53.219  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 14:23:53.219  6291  6344 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@238d7bb3 removed from the list
08-17 14:23:53.219  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:23:53.219  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:53.219  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e606570 removed from the list
08-17 14:23:53.219  6291  6344 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:23:53.219  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:23:53.229  1017  1131 E ConnectivityService: updateNetworkInfo()
08-17 14:23:53.229  1017  1131 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-17 14:23:53.229  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:53.229  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:23:53.239  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:23:53.239  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:23:53.239  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:53.239  6291  6344 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e606570 not in the list
08-17 14:23:53.239  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:53.239  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:23:53.239  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 14:23:53.239  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:23:53.239  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:53.239  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@335a200f removed from the list
08-17 14:23:53.239  6291  6344 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:53.239  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:53.239  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:53.239  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 14:23:53.239  6291  6344 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@174b116e removed from the list
08-17 14:23:53.239  6291  6344 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 14:23:53.239  6291  6344 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2dbe689c added. We now have 2 listener(s)
08-17 14:23:53.239  1017  1129 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-17 14:23:53.239  1017  1129 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-17 14:23:53.239  1017  1131 E ConnectivityService: updateNetworkInfo()
08-17 14:23:53.239  1017  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 14:23:53.239  1017  1131 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
,08-17 14:23:53.239  1017  7029 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,08-17 14:23:53.239  1017  1131 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-17 14:23:53.239  1017  7029 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-17 14:23:53.239  1017  7029 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-17 14:23:53.239  1017  7029 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
08-17 14:23:53.239  1017  7029 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 14:23:53.249   278   980 D EnterpriseController: uids 1000
08-17 14:23:53.249   278   980 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-17 14:23:53.249   278   980 D Netd    : getNetworkForDns: using netid 504 for uid 1000
,08-17 14:23:53.259  1017  1131 D ConnectivityService:    accepting network in place of null
,08-17 14:23:53.259  1017  1129 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-17 14:23:53.259  1017  1128 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-17 14:23:53.259  1459  1459 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-17 14:23:53.259  1459  1459 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-17 14:23:53.259  1017  1131 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-17 14:23:53.259  1017  1131 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
08-17 14:23:53.259  1017  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-17 14:23:53.259  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-17 14:23:53.269  1181  1181 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 14:23:53.269  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 14:23:53.269  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-17 14:23:53.269  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-17 14:23:53.269  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 14:23:53.269  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-17 14:23:53.269  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-17 14:23:53.269  1017  1017 I WifiTrafficPoller: mBoosterFLAG : 0
08-17 14:23:53.269  1017  1017 I WifiTrafficPoller: current booster mode : FullMode
08-17 14:23:53.269  1017  1017 D WifiNative-wlan0: callSECApiVoid - ID [212]
,08-17 14:23:53.279  1181  1181 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 14:23:53.279  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-17 14:23:53.279  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 14:23:53.279  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 14:23:53.279  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 14:23:53.279  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 14:23:53.279  1017  1131 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,08-17 14:23:53.289  1017  1017 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-17 14:23:53.289  1017  1131 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,08-17 14:23:53.289  1017  1133 D Tethering: MasterInitialState.processMessage what=3
,08-17 14:23:53.289  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-17 14:23:53.289  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 14:23:53.289  1017  1126 V NetworkStats: updateIfacesLocked()
08-17 14:23:53.289  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 14:23:53.289  1017  1126 V NetworkStats: performPollLocked(flags=0x1)
08-17 14:23:53.289  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 14:23:53.289  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:23:53.289  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29a42a5 added. We now have 9 listener(s)
08-17 14:23:53.289  6291  6344 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:23:53.289  1017  1047 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-17 14:23:53.289  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 14:23:53.289  1017  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 14:23:53.289  1017  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 14:23:53.289  1017  3205 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-17 14:23:53.289  1017  3205 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-17 14:23:53.289  1017  3205 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:53.289  1017  3205 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:53.289  1017  3205 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 14:23:53.289  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 14:23:53.289  1017  1126 V NetworkStats: performPollLocked() took 5ms
,08-17 14:23:53.289  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 14:23:53.289  3670  3670 I Hs20UtilService: Starting #23
,08-17 14:23:53.299  1181  1697 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290,
08-17 14:23:53.299  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:23:53.299  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 14:23:53.299  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 14:23:53.299  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 14:23:53.299  1017  1127 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-17 14:23:53.299  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 14:23:53.299  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 14:23:53.299  3852  6213 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-17 14:23:53.299  1181  1181 D StatusBar.NetworkController: EthernetConnected: false
08-17 14:23:53.299  1181  1181 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-17 14:23:53.299  1181  1181 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-17 14:23:53.299  1181  1181 D StatusBar.NetworkController: updateDataNetType()
08-17 14:23:53.299  1181  1181 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-17 14:23:53.299  1181  1181 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-17 14:23:53.299  3670  3711 I Hs20UtilService: Message received 5007
,08-17 14:23:53.309  6291  6344 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:23:53.309  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:53.309  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:53.309  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:23:53.309  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:23:53.309  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:23:53.309  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:23:53.309  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 14:23:53.309  1323  1323 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-17 14:23:53.309  1181  1181 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-17 14:23:53.309  1181  1181 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-17 14:23:53.309  1181  1181 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-17 14:23:53.309  1323  1323 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null,
,08-17 14:23:53.309  1181  1181 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 14:23:53.309  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-17 14:23:53.309  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:53.309  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:53.309  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:53.309  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:53.309  6291  6344 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 14:23:53.309  6291  6344 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 14:23:53.309  6291  6344 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 14:23:53.309  6291  6344 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27a2ae2b added. We now have 3 listener(s)
08-17 14:23:53.309  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
08-17 14:23:53.309  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-17 14:23:53.309  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
08-17 14:23:53.309  1323  1323 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-17 14:23:53.319  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-17 14:23:53.319  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-17 14:23:53.319  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 14:23:53.319  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 14:23:53.319  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:23:53.319  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11977288 added. We now have 10 listener(s),
08-17 14:23:53.319  6291  6344 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 14:23:53.319  6291  6344 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 14:23:53.319  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:23:53.319  6291  6344 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 14:23:53.319  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 14:23:53.319  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:23:53.319  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 14:23:53.319  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 14:23:53.329  1017  1343 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 14:23:53.329  1017  1343 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 14:23:53.329  1017  1343 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:53.329  1017  1343 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:53.329  1017  1343 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 14:23:53.329  3670  3670 I Hs20UtilService: Starting #24
,08-17 14:23:53.329  3670  3711 I Hs20UtilService: Message received 5007
,08-17 14:23:53.329  1323  1323 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-17 14:23:53.329  1323  1323 I NearbySettings: MountReceiver.onReceive - Keep current state
08-17 14:23:53.329  1017  7029 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-17 14:23:53.329  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 14:23:53.339  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 14:23:53.339  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-17 14:23:53.339  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 14:23:53.339  6291  6344 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-17 14:23:53.339  1017  1483 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-17 14:23:53.339  1017  1505 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
08-17 14:23:53.339  1017  1505 D SecContentProvider2: mCursor = null
,08-17 14:23:53.349  1017  2745 D SecContentProvider2: uri = 15 selection = getToastGravity
08-17 14:23:53.349  1017  2745 D SecContentProvider2: mCursor = null
,08-17 14:23:53.349  6926  6993 D BtGatt.GattService: registerClient() - UUID=8c83bb3a-3fe4-4889-9fdb-1b69c995e861
,08-17 14:23:53.349  1017  3207 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
,08-17 14:23:53.349  1017  3207 D SecContentProvider2: mCursor = null
,08-17 14:23:53.349  1017  1343 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
,08-17 14:23:53.349  1017  1343 D SecContentProvider2: mCursor = null
,08-17 14:23:53.359  1017  3205 D SecContentProvider2: uri = 15 selection = getToastEnabledState
08-17 14:23:53.359  1017  3205 D SecContentProvider2: mCursor = null
,08-17 14:23:53.359  1017  3056 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
08-17 14:23:53.359  1017  3056 D SecContentProvider2: mCursor = null
,08-17 14:23:53.379   257   257 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=4, Uoast
,08-17 14:23:53.389  6926  6951 D BtGatt.GattService: onClientRegistered() - UUID=8c83bb3a-3fe4-4889-9fdb-1b69c995e861, clientIf=6
,08-17 14:23:53.389  6291  6299 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-17 14:23:53.389  6926  7006 D BtGatt.GattService: start scan with filters
,08-17 14:23:53.399  6926  6956 D BtGatt.ScanManager: handling starting scan
,08-17 14:23:53.399  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-17 14:23:53.399  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 14:23:53.399  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 14:23:53.399  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 14:23:53.399  6926  6956 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3d6b0b11
,08-17 14:23:53.399  6291  6344 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 14:23:53.399  6291  6344 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-17 14:23:53.399  6291  6291 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 14:23:53.399  6926  6951 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-17 14:23:53.399  1017  2745 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1017
08-17 14:23:53.399  6926  6951 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 14:23:53.399  6926  6956 D BtGatt.ScanManager: allow scan with filters,
08-17 14:23:53.399  6926  6956 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-17 14:23:53.399  6926  6956 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
08-17 14:23:53.399  6926  6951 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-17 14:23:53.399  6926  6951 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
08-17 14:23:53.399  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-17 14:23:53.399  6926  6956 D BtGatt.ScanManager: Starting BLE batch scan
,08-17 14:23:53.399  6926  6956 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-17 14:23:53.409  6926  6951 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-17 14:23:53.409  6926  6951 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 14:23:53.409  1181  1181 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-17 14:23:53.409  6926  6951 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-17 14:23:53.409  6926  6951 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 14:23:53.409  6291  6344 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-17 14:23:53.419  6291  6344 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-17 14:23:53.419  6291  6344 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-17 14:23:53.419  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:53.419  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 14:23:53.419  6291  6344 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 14:23:53.419  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 14:23:53.419  6291  6344 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 14:23:53.419  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 14:23:53.419  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 14:23:53.419  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 14:23:53.419  1017  7029 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 17 Aug 2016 12:23:53 GMT], X-Android-Received-Millis=[1471436633425], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471436633373]}
,08-17 14:23:53.419  1017  7029 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-17 14:23:53.419  1017  1131 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
08-17 14:23:53.419  1017  7029 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,08-17 14:23:53.419  1017  1131 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-17 14:23:53.419  3852  6213 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-17 14:23:53.419  1017  1131 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
08-17 14:23:53.419  1181  1697 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-17 14:23:53.419  1017  1131 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-17 14:23:53.419  6926  6993 D BtGatt.GattService: stopScan() - queue size =1
08-17 14:23:53.419  1017  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-17 14:23:53.419  6926  6934 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-17 14:23:53.419  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 14:23:53.419  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 14:23:53.419  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 14:23:53.419  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 14:23:53.419  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 14:23:53.429  6291  6344 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 14:23:53.429  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-17 14:23:53.429  6291  6344 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 14:23:53.429  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 14:23:53.429  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:23:53.429  6926  6956 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 25
,08-17 14:23:53.429  6291  6291 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 14:23:53.429  6291  6291 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 14:23:53.429  6291  6291 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 14:23:53.429  6291  6344 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-17 14:23:53.429  6291  6344 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:23:53.429  6291  6344 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:23:53.429  6291  6344 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:53.429  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:53.429  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:23:53.429  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 14:23:53.429  6291  6344 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2dbe689c removed from the list
08-17 14:23:53.429  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 14:23:53.429  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29a42a5 removed from the list
08-17 14:23:53.429  6291  6344 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:23:53.429  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:53.429  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:53.429  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:23:53.429  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:23:53.429  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:23:53.429  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:53.429  6291  6344 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29a42a5 not in the list
08-17 14:23:53.429  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:53.429  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:23:53.439  6926  6956 D BtGatt.ScanManager: filter size is 1
08-17 14:23:53.439  6926  6956 D BtGatt.ScanManager: delete FilterIndex - 3
,08-17 14:23:53.439  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:23:53.439  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:23:53.439  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:53.439  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11977288 removed from the list
08-17 14:23:53.439  6291  6344 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:53.439  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:53.439  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:53.439  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 14:23:53.439  6926  6951 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-17 14:23:53.439  6291  6344 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27a2ae2b removed from the list
08-17 14:23:53.439  6926  6951 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 14:23:53.439  6926  6956 D BtGatt.ScanManager: stopping BLe Batch
,08-17 14:23:53.439  6291  6344 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 14:23:53.439  6291  6344 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2752f34 added. We now have 2 listener(s)
,08-17 14:23:53.439  6926  6951 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-17 14:23:53.439  6926  6951 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 14:23:53.439  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-17 14:23:53.439  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 14:23:53.439  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 14:23:53.439  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:23:53.439  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@367f215d added. We now have 9 listener(s)
08-17 14:23:53.439  6291  6344 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 14:23:53.439  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 14:23:53.439  6926  6956 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-17 14:23:53.439  1181  1181 D StatusBar.NetworkController: EthernetConnected: false
,08-17 14:23:53.449  1181  1181 D StatusBar.NetworkController: getUpdateDataNetType(): 0
,08-17 14:23:53.449  1181  1181 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-17 14:23:53.449  1181  1181 D StatusBar.NetworkController: updateDataNetType()
,08-17 14:23:53.449  1181  1181 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-17 14:23:53.449  1181  1181 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-17 14:23:53.449  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 14:23:53.449  1181  1181 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-17 14:23:53.449  1181  1181 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,08-17 14:23:53.449  1181  1181 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,08-17 14:23:53.449  1181  1181 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 14:23:53.449  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-17 14:23:53.449  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:53.449  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:53.449  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:53.449  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 14:23:53.449  6926  6951 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-17 14:23:53.449  6926  6951 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 14:23:53.449  6291  6344 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:23:53.449  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:53.449  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:53.449  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:23:53.449  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:23:53.449  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:23:53.449  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:23:53.449  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 14:23:53.449  6291  6344 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 14:23:53.459  6291  6344 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 14:23:53.459  6291  6344 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 14:23:53.459  6291  6344 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3eecb7a3 added. We now have 3 listener(s)
,08-17 14:23:53.459  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:53.459  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-17 14:23:53.459  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-17 14:23:53.459  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 14:23:53.459  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 14:23:53.459  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:23:53.459  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15d00aa0 added. We now have 10 listener(s)
08-17 14:23:53.459  6291  6344 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:23:53.459  6291  6344 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 14:23:53.459  6291  6344 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 14:23:53.459  6291  6344 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only,
08-17 14:23:53.459  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 14:23:53.459  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:23:53.459  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 14:23:53.459  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 14:23:53.469  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 14:23:53.469  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 14:23:53.469  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-17 14:23:53.469  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-17 14:23:53.469  6291  6344 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-17 14:23:53.469  6926  6935 D BtGatt.GattService: registerClient() - UUID=4a26be49-e2f4-439f-8843-a9ec0ff56179
,08-17 14:23:53.519  6926  6951 D BtGatt.GattService: onClientRegistered() - UUID=4a26be49-e2f4-439f-8843-a9ec0ff56179, clientIf=6
,08-17 14:23:53.519  6291  6299 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-17 14:23:53.519  6926  6993 D BtGatt.GattService: start scan with filters
,08-17 14:23:53.519  6926  6956 D BtGatt.ScanManager: handling starting scan
,08-17 14:23:53.519  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-17 14:23:53.519  6926  6951 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-17 14:23:53.519  6926  6951 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 14:23:53.519  6926  6956 D BtGatt.ScanManager: allow scan with filters
08-17 14:23:53.519  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 14:23:53.519  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 14:23:53.519  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-17 14:23:53.519  6926  6956 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-17 14:23:53.519  6926  6956 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-17 14:23:53.529  6926  6951 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-17 14:23:53.529  6926  6951 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 14:23:53.529  6926  6956 D BtGatt.ScanManager: Starting BLE batch scan
,08-17 14:23:53.529  6926  6956 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-17 14:23:53.529  6926  6951 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-17 14:23:53.529  6926  6951 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 14:23:53.529  6291  6344 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 14:23:53.529  6291  6291 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 14:23:53.539  6926  6951 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-17 14:23:53.539  6291  6344 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-17 14:23:53.539  6926  6951 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 14:23:53.549  6926  6956 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 26
,08-17 14:23:53.549  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 14:23:53.549  6291  6344 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-17 14:23:53.549  6291  6344 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-17 14:23:53.549  6291  6344 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 14:23:53.559  6291  6344 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 14:23:53.559  6291  6344 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 14:23:53.559  6291  6344 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 14:23:53.559  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:23:53.559  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 14:23:53.559  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-17 14:23:53.559  6291  6344 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2752f34 removed from the list
,08-17 14:23:53.559  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 14:23:53.559  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@367f215d removed from the list
,08-17 14:23:53.559  6291  6344 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 14:23:53.559  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 14:23:53.559  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:23:53.559  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-17 14:23:53.559  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:23:53.559  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 14:23:53.569  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 14:23:53.569  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:23:53.569  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:53.569  6291  6344 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@367f215d not in the list
08-17 14:23:53.569  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 14:23:53.569  6291  6344 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 14:23:53.569  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 14:23:53.569  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 14:23:53.569  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 14:23:53.569  6926  7006 D BtGatt.GattService: stopScan() - queue size =1
,08-17 14:23:53.569  6926  6956 D BtGatt.ScanManager: filter size is 1
08-17 14:23:53.569  6926  6956 D BtGatt.ScanManager: delete FilterIndex - 4
,08-17 14:23:53.569  6926  6935 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-17 14:23:53.569  6926  6951 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-17 14:23:53.569  6926  6951 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 14:23:53.569  6926  6956 D BtGatt.ScanManager: stopping BLe Batch
,08-17 14:23:53.569  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 14:23:53.569  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 14:23:53.569  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 14:23:53.569  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 14:23:53.569  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 14:23:53.579  6291  6344 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 14:23:53.579  6926  6951 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-17 14:23:53.579  6926  6951 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 14:23:53.579  6926  6956 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-17 14:23:53.579  6926  6951 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-17 14:23:53.579  6926  6951 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 14:23:53.579  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-17 14:23:53.579  6291  6344 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 14:23:53.579  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 14:23:53.579  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:23:53.579  6291  6291 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 14:23:53.589  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:23:53.589  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:23:53.589  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:53.589  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15d00aa0 removed from the list
08-17 14:23:53.589  6291  6344 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:53.589  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:53.589  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:53.589  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 14:23:53.589  6291  6344 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3eecb7a3 removed from the list
,08-17 14:23:53.589  6291  6344 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 14:23:53.589  6291  6344 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e3b30cc added. We now have 2 listener(s)
,08-17 14:23:53.589  6291  6291 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 14:23:53.589  6291  6291 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 14:23:53.589  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-17 14:23:53.589  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 14:23:53.589  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 14:23:53.589  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 14:23:53.589  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11da1f15 added. We now have 9 listener(s)
,08-17 14:23:53.589  6291  6344 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 14:23:53.599  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 14:23:53.599  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 14:23:53.599  6291  6344 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:23:53.599  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:53.599  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:53.599  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:23:53.599  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:23:53.599  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:23:53.599  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:23:53.599  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 14:23:53.609  6291  6344 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 14:23:53.609  6291  6344 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 14:23:53.609  6291  6344 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 14:23:53.609  6291  6344 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@324f781b added. We now have 3 listener(s)
,08-17 14:23:53.609  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:53.609  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:53.609  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-17 14:23:53.609  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 14:23:53.609  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 14:23:53.609  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:23:53.609  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22508db8 added. We now have 10 listener(s)
08-17 14:23:53.609  6291  6344 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:23:53.609  6291  6344 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 14:23:53.609  6291  6344 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 14:23:53.609  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 14:23:53.609  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:23:53.609  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 14:23:53.619  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 14:23:53.619  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 14:23:53.619  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 14:23:53.629  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-17 14:23:53.629  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-17 14:23:53.629  6291  6344 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-17 14:23:53.629  6926  6993 D BtGatt.GattService: registerClient() - UUID=fbc1bfa1-a3cc-47fc-8776-a5855978b53a
,08-17 14:23:53.679  6926  6951 D BtGatt.GattService: onClientRegistered() - UUID=fbc1bfa1-a3cc-47fc-8776-a5855978b53a, clientIf=6
,08-17 14:23:53.679  6291  6301 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-17 14:23:53.679  6926  6934 D BtGatt.GattService: start scan with filters
,08-17 14:23:53.679  6926  6956 D BtGatt.ScanManager: handling starting scan
,08-17 14:23:53.679  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-17 14:23:53.679  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 14:23:53.679  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 14:23:53.679  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 14:23:53.679  6291  6344 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 14:23:53.679  6291  6291 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 14:23:53.679  6291  6344 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 14:23:53.689  6926  6951 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-17 14:23:53.689  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 14:23:53.689  6926  6951 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 14:23:53.689  6926  6956 D BtGatt.ScanManager: allow scan with filters
08-17 14:23:53.689  6926  6956 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-17 14:23:53.689  6926  6956 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-17 14:23:53.689  6291  6344 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 14:23:53.689  6291  6344 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 14:23:53.689  6291  6344 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 14:23:53.689  6926  6951 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-17 14:23:53.699  6291  6344 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:53.699  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:53.699  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 14:23:53.699  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 14:23:53.699  6291  6344 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e3b30cc removed from the list
08-17 14:23:53.699  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:53.699  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11da1f15 removed from the list
08-17 14:23:53.699  6291  6344 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:23:53.699  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:23:53.699  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:53.699  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-17 14:23:53.699  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:53.699  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 14:23:53.699  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 14:23:53.699  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:23:53.699  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-17 14:23:53.699  6291  6344 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11da1f15 not in the list
08-17 14:23:53.699  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-17 14:23:53.699  6291  6344 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 14:23:53.699  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-17 14:23:53.699  6926  6951 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 14:23:53.699  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 14:23:53.699  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-17 14:23:53.699  6926  6956 D BtGatt.ScanManager: Starting BLE batch scan
08-17 14:23:53.699  6926  6956 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-17 14:23:53.709  6926  6952 D BtGatt.GattService: stopScan() - queue size =1
,08-17 14:23:53.709  6926  6935 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-17 14:23:53.709  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-17 14:23:53.709  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-17 14:23:53.709  6926  6951 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-17 14:23:53.709  6926  6951 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 14:23:53.709  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-17 14:23:53.709  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-17 14:23:53.709  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 14:23:53.719  6291  6344 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
,08-17 14:23:53.719  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 14:23:53.719  6291  6344 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 14:23:53.719  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 14:23:53.719  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:53.719  6291  6291 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 14:23:53.719  6291  6291 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 14:23:53.719  6291  6291 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 14:23:53.719  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:23:53.719  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:23:53.719  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:53.719  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22508db8 removed from the list
08-17 14:23:53.719  6291  6344 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:53.719  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:53.719  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:53.719  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 14:23:53.719  6291  6344 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@324f781b removed from the list
,08-17 14:23:53.719  6291  6344 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 14:23:53.719  6291  6344 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@365ccd64 added. We now have 2 listener(s)
,08-17 14:23:53.719  6926  6951 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-17 14:23:53.719  6926  6951 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 14:23:53.729  1017  1131 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-17 14:23:53.729  1017  1131 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,08-17 14:23:53.729  1181  1697 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-17 14:23:53.729  1017  1131 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,08-17 14:23:53.729  3852  6213 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-17 14:23:53.739  1181  1697 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-17 14:23:53.739  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-17 14:23:53.739  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 14:23:53.739  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 14:23:53.739  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 14:23:53.739  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b701bcd added. We now have 9 listener(s)
08-17 14:23:53.739  6291  6344 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 14:23:53.739  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 14:23:53.739  6926  6956 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 27
,08-17 14:23:53.739  3852  6213 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-17 14:23:53.739  6926  6956 D BtGatt.ScanManager: filter size is 1
08-17 14:23:53.739  6926  6956 D BtGatt.ScanManager: delete FilterIndex - 5
,08-17 14:23:53.749  6926  6951 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-17 14:23:53.749  6926  6951 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 14:23:53.749  6926  6956 D BtGatt.ScanManager: stopping BLe Batch
,08-17 14:23:53.749  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 14:23:53.749  6926  6951 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-17 14:23:53.749  6926  6951 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 14:23:53.749  6926  6956 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-17 14:23:53.749  6926  6951 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-17 14:23:53.749  6926  6951 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 14:23:53.759  6291  6344 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:23:53.759  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:53.759  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:53.759  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:23:53.759  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:23:53.759  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:23:53.759  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:23:53.759  6291  6344 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 14:23:53.759  6291  6344 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 14:23:53.759  6291  6344 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 14:23:53.759  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:53.769  6291  6344 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 14:23:53.769  6291  6344 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74acf93 added. We now have 3 listener(s)
,08-17 14:23:53.769  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:53.769  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-17 14:23:53.769  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 14:23:53.769  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 14:23:53.769  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 14:23:53.769  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4cb5bd0 added. We now have 10 listener(s)
,08-17 14:23:53.769  6291  6344 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 14:23:53.769  6291  6344 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 14:23:53.769  6291  6344 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 14:23:53.769  6291  6344 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 14:23:53.769  6291  6344 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 14:23:53.769  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:23:53.769  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 14:23:53.769  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-17 14:23:53.769  6291  6344 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@365ccd64 removed from the list
08-17 14:23:53.779  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:53.779  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b701bcd removed from the list
08-17 14:23:53.779  6291  6344 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:23:53.779  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:23:53.779  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:23:53.779  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:23:53.779  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 14:23:53.779  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 14:23:53.779  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 14:23:53.779  6291  6344 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b701bcd not in the list
,08-17 14:23:53.779  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:23:53.779  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:23:53.779  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:23:53.779  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:23:53.779  6291  6344 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:53.779  6291  6344 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4cb5bd0 removed from the list
08-17 14:23:53.779  6291  6344 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:53.779  6291  6344 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:53.779  6291  6344 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:53.779  6291  6344 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 14:23:53.779  6291  6344 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74acf93 removed from the list
,08-17 14:23:53.779  6291  6344 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-17 14:23:53.779  6291  6344 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-17 14:23:53.779  6291  6344 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-17 14:23:53.779  6291  6344 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-17 14:23:53.779  6291  6344 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-17 14:23:53.779  6291  6344 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-17 14:23:53.779  1017  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 14:23:53.789  6291  7070 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1186, name: My test thread name)
,08-17 14:23:53.789  6291  7070 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1186, thread name: My test thread name)
08-17 14:23:53.789  6291  7070 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1186, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-17 14:23:53.799  6291  7071 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1188, name: My test thread name)
,08-17 14:23:53.799  6291  7071 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1188, thread name: My test thread name)
08-17 14:23:53.799  6291  7071 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1188, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-17 14:23:53.799  6291  6344 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-17 14:23:53.799  6291  6344 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-17 14:23:53.799  6291  6344 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-17 14:23:53.799  6291  6344 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-17 14:23:53.799  6291  6344 D com.test.thalitest.ThaliTestRunner: Total duration: 23456 ms
,08-17 14:23:53.799  6291  6344 I jxcore-log: Total number of executed tests:  80
08-17 14:23:53.799  6291  6344 I jxcore-log: 
08-17 14:23:53.799  6291  6344 I jxcore-log: Number of passed tests:  80
08-17 14:23:53.799  6291  6344 I jxcore-log: 
08-17 14:23:53.799  6291  6344 I jxcore-log: Number of failed tests:  0
08-17 14:23:53.799  6291  6344 I jxcore-log: 
08-17 14:23:53.799  6291  6344 I jxcore-log: Number of ignored tests:  0
08-17 14:23:53.799  6291  6344 I jxcore-log: 
08-17 14:23:53.799  6291  6344 I jxcore-log: Total duration:  23456
08-17 14:23:53.799  6291  6344 I jxcore-log: 
,08-17 14:23:53.799  6291  6344 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-17 14:23:53.799  6291  6344 I jxcore-log: 
,08-17 14:23:53.799  1017  1042 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-17 14:23:53.809  6291  6344 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:23:53.809  6291  6344 I jxcore-log: 
08-17 14:23:53.809  6291  6344 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:23:53.809  6291  6344 I jxcore-log: 
08-17 14:23:53.809  6291  6344 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:23:53.809  6291  6344 I jxcore-log: 
08-17 14:23:53.809  6291  6344 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:23:53.809  6291  6344 I jxcore-log: 
08-17 14:23:53.809  6291  6344 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:23:53.809  6291  6344 I jxcore-log: 
08-17 14:23:53.809  3175  3175 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
08-17 14:23:53.819  6291  6344 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:23:53.819  6291  6344 I jxcore-log: 
08-17 14:23:53.819  6291  6344 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:23:53.819  6291  6344 I jxcore-log: 
08-17 14:23:53.819  6291  6344 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:23:53.819  6291  6344 I jxcore-log: 
,08-17 14:23:53.819  6291  6344 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 14:23:53.819  6291  6344 I jxcore-log: 
,08-17 14:23:53.819  6291  6344 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 14:23:53.819  6291  6344 I jxcore-log: 
,08-17 14:23:53.819  6291  6344 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 14:23:53.819  6291  6344 I jxcore-log: 
08-17 14:23:53.829  6291  6344 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 14:23:53.829  6291  6344 I jxcore-log: 
08-17 14:23:53.829  6291  6344 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 14:23:53.829  6291  6344 I jxcore-log: 
,08-17 14:23:53.829  6291  6344 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 14:23:53.829  6291  6344 I jxcore-log: 
08-17 14:23:53.829  6291  6291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:23:53.829  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:53.829  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:53.829  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:23:53.829  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:23:53.829  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:23:53.829  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:23:53.829  6291  6291 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 14:23:53.829  6291  6344 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 14:23:53.829  6291  6344 I jxcore-log: 
,08-17 14:23:53.829  6291  6344 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 14:23:53.829  6291  6344 I jxcore-log: 
,08-17 14:23:53.829  6549  6549 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
08-17 14:23:53.829  6291  6344 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 14:23:53.829  6291  6344 I jxcore-log: 
,08-17 14:23:53.829  6291  6344 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 14:23:53.829  6291  6344 I jxcore-log: 
,08-17 14:23:53.829  6291  6344 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 14:23:53.829  6291  6344 I jxcore-log: 
,08-17 14:23:53.829  6291  6344 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 14:23:53.829  6291  6344 I jxcore-log: 
,08-17 14:23:53.829  6291  6344 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 14:23:53.829  6291  6344 I jxcore-log: 
,08-17 14:23:53.829  6291  6344 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 14:23:53.829  6291  6344 I jxcore-log: 
,08-17 14:23:53.829  6291  6344 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 14:23:53.829  6291  6344 I jxcore-log: 
,08-17 14:23:53.839  6291  6344 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 14:23:53.839  6291  6344 I jxcore-log: 
,08-17 14:23:53.839  6291  6344 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:23:53.839  6291  6344 I jxcore-log: 
,08-17 14:23:53.839  6291  6291 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 14:23:53.839  6291  6344 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:23:53.839  6291  6344 I jxcore-log: 
08-17 14:23:53.839  6291  6291 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-17 14:23:53.839  6291  6344 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:23:53.839  6291  6344 I jxcore-log: 
,08-17 14:23:53.839  6291  6344 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:23:53.839  6291  6344 I jxcore-log: 
,08-17 14:23:53.839  6291  6344 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:23:53.839  6291  6344 I jxcore-log: 
,08-17 14:23:53.849  6532  6532 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-17 14:23:53.849  6532  6532 I PCWCLIENTTRACE_PushUtil: sales region : global
08-17 14:23:53.849  6532  6532 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-17 14:23:53.849  6532  6532 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-17 14:23:53.849  1017  1029 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
08-17 14:23:53.849  1017  1029 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-17 14:23:53.849   290   290 E SMD     : DCD OFF
,08-17 14:23:53.859  6549  6549 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,08-17 14:23:53.859  1730  1730 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-17 14:23:53.869  6558  6558 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,08-17 14:23:53.869  1017  1030 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-17 14:23:53.869  1017  1030 D SecContentProvider2: mCursor = null
,08-17 14:23:53.879  1730  1730 D accuweather: [KK AccuPhone]>>> U:4106 [0:0] getPWC : surface = 0, remote = 1
,08-17 14:23:53.879  1730  1730 D accuweather: [KK AccuPhone]>>> U:4284 [0:0] Store PWC = 1
08-17 14:23:53.879  1730  1730 D accuweather: [KK AccuPhone]>>> U:4158 [0:0] addPWC = 1
08-17 14:23:53.879  1730  1730 D accuweather: [KK AccuPhone]>>> UIM:306 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-17 14:23:53.879  1017  1343 D RCPManagerService: exchangeData() failure , invalid userId
,08-17 14:23:53.889  1017  1344 D RCPManagerService: exchangeData() failure , invalid userId
,08-17 14:23:53.889  6558  6558 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,08-17 14:23:53.889  1730  1730 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-17 14:23:53.889  6558  6558 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,08-17 14:23:53.889  1298  1534 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 6
08-17 14:23:53.889  1730  1730 D accuweather: [KK AccuPhone]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,08-17 14:23:53.889  6558  6558 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,08-17 14:23:53.899  6496  6496 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-17 14:23:53.899  6496  6496 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-17 14:23:53.899  6496  6496 D SecurityLogAgent: StateMachine : Current State = 1
,08-17 14:23:53.899  1730  1730 D accuweather: [KK AccuPhone]>>> U:4250 [0:0] Store PWC succeed
,08-17 14:23:53.909  6496  6496 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 14:23:53.909  3717  3717 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Aug 17 14:23:53 GMT+02:00 2016
,08-17 14:23:53.919  6722  6722 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-17 14:23:53.919  6722  6722 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-17 14:23:53.919  6722  6722 I DIAGMON_AGENT: ./extraInfo: "NG700"
,08-17 14:23:53.919  6722  6722 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,08-17 14:23:53.919  1017  3056 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-17 14:23:53.919  1017  3056 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-17 14:23:53.919  1017  3056 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:53.919  1017  3056 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:53.919  1017  3056 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-17 14:23:53.919  3717  3717 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,08-17 14:23:53.929  6291  6291 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 14:23:53.929  6291  6344 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 14:23:53.929  6291  6344 I jxcore-log: 
,08-17 14:23:53.939  3717  3717 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,08-17 14:23:53.939  3717  3717 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-17 14:23:53.939  3717  3717 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-17 14:23:53.949  3717  7075 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-17 14:23:53.949  3717  7075 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-17 14:23:53.949  1017  1531 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
08-17 14:23:53.949  1017  1531 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,08-17 14:23:53.949  1017  1531 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:53.949  1017  1531 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:53.949  1017  1531 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,08-17 14:23:53.959  1017  3057 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 14:23:53.959  1017  3057 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
08-17 14:23:53.959  3717  7075 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
08-17 14:23:53.959  1017  3057 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:53.959  1017  3057 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 14:23:53.959  1017  3057 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-17 14:23:53.959  3717  7075 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().START
,08-17 14:23:53.969   278   980 D EnterpriseController: uids 10012
,08-17 14:23:53.969   278   980 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-17 14:23:53.969   278   980 D Netd    : getNetworkForDns: using netid 504 for uid 10012
,08-17 14:23:53.969  3717  7075 I KLMS-2.5.183: : NetworkChangeOperations(): uploadRequestLog().START 
,08-17 14:23:53.979  3852  3852 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-17 14:23:53.989  3717  7075 I KLMS-2.5.183: : NetworkChangeOperations(): uploadRequestLog().END 
,08-17 14:23:53.989  3717  7075 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END
,08-17 14:23:53.989  3852  4602 I iu.UploadsManager: num queued entries: 0
,08-17 14:23:53.999  3717  3717 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,08-17 14:23:53.999  3852  4602 I iu.UploadsManager: num updated entries: 0
,08-17 14:23:54.009  3852  4602 I iu.SyncManager: NEXT; no task
,08-17 14:23:54.009  6016  6016 D WaitQueueForNetworkActivate: notifyNetworkActivated
,08-17 14:23:54.019  6781  6781 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-17 14:23:54.019  6781  6781 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
08-17 14:23:54.019  6781  6781 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-17 14:23:54.029  1017  3056 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-17 14:23:54.029  1017  3056 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 14:23:54.029  1017  3056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:54.029  1017  3056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:54.029  1017  3056 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 14:23:54.039  3211  7085 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
08-17 14:23:54.039  3211  7085 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
,08-17 14:23:54.039  3211  7085 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-17 14:23:54.049  7088  7088 E Zygote  : MountEmulatedStorage()
08-17 14:23:54.049  7088  7088 I libpersona: KNOX_SDCARD checking this for 10035
08-17 14:23:54.049  7088  7088 E Zygote  : v2
08-17 14:23:54.049  7088  7088 I libpersona: KNOX_SDCARD not a persona
08-17 14:23:54.059  7088  7088 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-17 14:23:54.059  7088  7088 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-17 14:23:54.059  7088  7088 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-17 14:23:54.079  1017  3056 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7088 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-17 14:23:54.079  7073  7073 D AndroidRuntime: 
08-17 14:23:54.079  7073  7073 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-17 14:23:54.089  7073  7073 D AndroidRuntime: CheckJNI is OFF
,08-17 14:23:54.089  7073  7073 D AndroidRuntime: readGMSProperty: start
08-17 14:23:54.089  7073  7073 D AndroidRuntime: readGMSProperty: already setted!!
08-17 14:23:54.089  7073  7073 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-17 14:23:54.089  7073  7073 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-17 14:23:54.089  7073  7073 D AndroidRuntime: readGMSProperty: end
08-17 14:23:54.089  7073  7073 D AndroidRuntime: addProductProperty: start
,08-17 14:23:54.089  6291  6291 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 14:23:54.089  7088  7088 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 14:23:54.089  6291  6344 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 14:23:54.089  6291  6344 I jxcore-log: 
08-17 14:23:54.089  7088  7088 D ActivityThread: Added TimaKeyStore provider
,08-17 14:23:54.089   324   324 I art     : Explicit concurrent mark sweep GC freed 8730(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 719us total 24.534ms
,08-17 14:23:54.119   324   324 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 611us total 19.121ms
,08-17 14:23:54.129   324   324 I art     : Explicit concurrent mark sweep GC freed 3(96B) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 1.021ms total 17.850ms
,08-17 14:23:54.139  1934  7078 I qtaguid : Tagging socket 52 with tag 1000040700000000{268436487,0} for uid -1, pid: 1934, getuid(): 10012
,08-17 14:23:54.169  3211  7085 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,08-17 14:23:54.179  7088  7113 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
08-17 14:23:54.179  7088  7113 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-17 14:23:54.179  7088  7088 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,08-17 14:23:54.179  6088  6088 I SA      : [OR] onReceive log=[SA = 2.1.0240 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOJ6 PSS = 4.978878039476607  ]
08-17 14:23:54.179  6088  6088 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
08-17 14:23:54.179  6088  6088 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
08-17 14:23:54.179  3211  7085 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,08-17 14:23:54.189  3211  7085 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,08-17 14:23:54.189  3211  7085 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,08-17 14:23:54.189  3211  7085 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
08-17 14:23:54.189  7088  7113 D SPPClientService: PushLog.txt file is not deleted.
08-17 14:23:54.189  7088  7113 D SPPClientService: PushLog.txt file is not deleted.
08-17 14:23:54.189  7088  7113 D SPPClientService: ============PushLog. stop!
08-17 14:23:54.189  3211  7085 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
08-17 14:23:54.189  3211  7085 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
08-17 14:23:54.189  6088  6088 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
08-17 14:23:54.189  6088  6088 I SA      : [OR] == isSIMCardReady false ==
,08-17 14:23:54.189  6088  6088 I SA      : [SCU] == networkStateCheck == true
08-17 14:23:54.189  3211  7085 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
08-17 14:23:54.189  6088  6088 I SA      : [DM] getCountryCodeFromCSC : PL
,08-17 14:23:54.189  6088  6088 I SA      : isChinaCountryCode : false
08-17 14:23:54.189  6088  6088 I SA      : [SCU] is ChinestModel Data Restricted   : false
08-17 14:23:54.189  6088  6088 I SA      : [OR] == networkStateCheck true ==
08-17 14:23:54.189  6088  6088 I SA      : [OR] GetMyCountryZoneTask
08-17 14:23:54.199  6088  6088 I SA      : [OR] onReceive END
,08-17 14:23:54.199  3211  7085 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
08-17 14:23:54.199  1233  1233 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-17 14:23:54.209  1017  2745 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads,
08-17 14:23:54.209  1017  2745 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0,
,08-17 14:23:54.219  1017  2745 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:54.219  1017  2745 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:54.219  1017  2745 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,08-17 14:23:54.219  6291  6291 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-17 14:23:54.219  6291  6344 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 14:23:54.219  6291  6344 I jxcore-log: 
,08-17 14:23:54.229  6088  7115 I SA      : [SRS] prepareGetMyCountryZone
,08-17 14:23:54.239  3211  7085 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,08-17 14:23:54.249  1017  1079 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
08-17 14:23:54.249  1017  1079 D SecContentProvider2: mCursor = null
,08-17 14:23:54.259  6088  7115 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-17 14:23:54.259  6088  7115 I SA      : [SSP] query invoked
08-17 14:23:54.259  7073  7073 E AffinityControl: AffinityControl: registerfunction enter
,08-17 14:23:54.269  6088  7115 I SA      : [TPMU] GetMccFromDB : null
,08-17 14:23:54.269  6088  7115 I SA      : [SCU] getMccFromPreferece mcc = 260
08-17 14:23:54.269  6088  7115 I SA      : [LBE] isSupportCheckDomainRegion : false
08-17 14:23:54.269  6088  7115 I SA      : [TPM] isNoProxy(default) : true
,08-17 14:23:54.279  6088  7115 E File    : fail readDirectory() errno=2
,08-17 14:23:54.279  7073  7073 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-17 14:23:54.289  1017  1131 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-17 14:23:54.299  1017  1079 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
08-17 14:23:54.299  1017  1079 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,08-17 14:23:54.299  1017  1079 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:54.299  1017  1079 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-17 14:23:54.299  1017  1079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,08-17 14:23:54.309  6016  6016 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,08-17 14:23:54.309  1017  1727 D PackageManager: START PACKAGE DELETE: observer{610330788}
08-17 14:23:54.309  1017  1727 D PackageManager: pkg{<packageName>}
08-17 14:23:54.309  1017  1727 D PackageManager: user{0}
08-17 14:23:54.309  1017  1727 D PackageManager: caller{2000}
08-17 14:23:54.309  1017  1727 D PackageManager: flags{2}
08-17 14:23:54.309  6016  6016 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
08-17 14:23:54.319  1017  1727 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-17 14:23:54.319  1017  1727 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-17 14:23:54.319  1017  1727 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-17 14:23:54.319  1017  1727 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-17 14:23:54.319  1017  1727 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-17 14:23:54.319  6016  6016 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
08-17 14:23:54.319  6016  6016 D InitializeManagerStateMachine: exit::IDLE
08-17 14:23:54.319  1017  1343 I splitIntent: Queue : backgroundsplit_2 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
08-17 14:23:54.319  6016  6016 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,08-17 14:23:54.319  6016  6016 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
08-17 14:23:54.319  6016  6016 D InitializeManagerStateMachine: exit::NETWORK_CHECK
08-17 14:23:54.319  6016  6016 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
08-17 14:23:54.319  6016  6016 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
08-17 14:23:54.319  6016  6016 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
08-17 14:23:54.319  6016  6016 D InitializeManagerStateMachine: entry::SUCCESS
08-17 14:23:54.319  6016  6016 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,08-17 14:23:54.319  1017  1043 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:54.319  1017  1043 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-17 14:23:54.319  1017  1058 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-17 14:23:54.319  1017  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,08-17 14:23:54.319  1017  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,08-17 14:23:54.319  1017  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
,08-17 14:23:54.319  1017  1058 D ApplicationPolicy: getApplicationUninstallationEnabled
08-17 14:23:54.319  1017  1058 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-17 14:23:54.329  1017  1058 D PackageManager: !@killApplicatoin: 10155, uninstall pkg
,08-17 14:23:54.329  1017  1043 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
,08-17 14:23:54.329  1017  1043 I ActivityManager: Killing 6291:com.test.thalitest/u0a155 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-17 14:23:54.329  6016  6016 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
08-17 14:23:54.329  6016  6016 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,08-17 14:23:54.339  1017  1043 I ActivityManager:   Force finishing activity ActivityRecord{321899ac u0 com.test.thalitest/.MainActivity t129}
,08-17 14:23:54.349  1017  1043 W ActivityManager: mDVFSHelper.acquire(),
,08-17 14:23:54.369  6016  6016 D InitializeManagerStateMachine: exit::SUCCESS
08-17 14:23:54.369  6016  6016 D InitializeManagerStateMachine: entry::IDLE
,08-17 14:23:54.469  1017  1343 I WindowState: WIN DEATH: Window{f7a5e0c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-17 14:23:54.469   257   447 I SurfaceFlinger: id=14 Removed NainActivit (6/9)
,08-17 14:23:54.469   257  4387 I SurfaceFlinger: id=14 Removed NainActivit (-2/9)
,08-17 14:23:54.469  1017  1343 D InputDispatcher: Focus left window: 6291
,08-17 14:23:54.479  1017  1058 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=0: pkg removed
,08-17 14:23:54.479   257  4387 I SurfaceFlinger: id=14 Removed NainActivit (-2/9)
,08-17 14:23:54.489  1017  1058 I ActivityManager:   Force finishing activity ActivityRecord{321899ac u0 com.test.thalitest/.MainActivity t129 f}
08-17 14:23:54.489  1017  1058 W ActivityManager: Duplicate finish request for ActivityRecord{321899ac u0 com.test.thalitest/.MainActivity t129 f}
,08-17 14:23:54.499  1017  1058 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-17 14:23:54.529  5694  5694 I art     : Explicit concurrent mark sweep GC freed 2328(137KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 747us total 25.663ms
,08-17 14:23:54.539  4781  4781 I art     : Explicit concurrent mark sweep GC freed 98(15KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 648us total 27.990ms
,08-17 14:23:54.549  1017  1043 D InputDispatcher: Focused application released
,08-17 14:23:54.549  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-17 14:23:54.549  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-17 14:23:54.559  5484  5484 I art     : Explicit concurrent mark sweep GC freed 404(27KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 8MB/11MB, paused 1.024ms total 44.631ms
,08-17 14:23:54.589  3852  3852 I art     : Explicit concurrent mark sweep GC freed 23862(1427KB) AllocSpace objects, 3(48KB) LOS objects, 39% free, 15MB/26MB, paused 1.300ms total 84.982ms
,08-17 14:23:54.589  1017  1100 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-17 14:23:54.599  3852  3862 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,08-17 14:23:54.599  1797  1797 E SamsungIME: mOCRHelper is null
,08-17 14:23:54.599  1934  2118 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-17 14:23:54.639  1017  1126 V NetworkStats: removeUidsLocked() for UIDs [10155]
,08-17 14:23:54.639  1017  1126 V NetworkStats: performPollLocked(flags=0x3)
08-17 14:23:54.639  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 14:23:54.639  1017  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 14:23:54.639  1017  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 14:23:54.659  1017  1126 V NetworkStats: performPollLocked() took 18ms
08-17 14:23:54.659  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 14:23:54.669  3175  3175 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,08-17 14:23:54.679  3175  3175 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 3
,08-17 14:23:54.679  1446  1446 D PersonaManager: isKioskContainerExistOnDevice
,08-17 14:23:54.679  1446  1446 D RegisteredServicesCache: empty dynamic service
,08-17 14:23:54.689  3175  3175 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,08-17 14:23:54.689  3717  3717 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Aug 17 14:23:54 GMT+02:00 2016
,08-17 14:23:54.689  1017  3205 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-17 14:23:54.689  1017  3205 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-17 14:23:54.689  3175  3175 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,08-17 14:23:54.699  1017  3205 W ActivityManager: userId = 0, bbcId = -10000
,08-17 14:23:54.699  1017  3205 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 14:23:54.699  1017  3205 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-17 14:23:54.709  3175  3175 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 3
,08-17 14:23:54.709  1446  1446 D RegisteredComponentCache: Collect Tech packages for Knox
,08-17 14:23:54.709  3175  3175 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,08-17 14:23:54.719  3175  3175 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,08-17 14:23:54.729  3175  3175 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,08-17 14:23:54.729  1446  1446 D PersonaManager: isKioskContainerExistOnDevice
,08-17 14:23:54.739  3717  3717 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,08-17 14:23:54.739  1017  1344 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
,08-17 14:23:54.739  1017  1344 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-17 14:23:54.739  1017  1344 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-17 14:23:54.749  3175  3175 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,08-17 14:23:54.749  1017  1344 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 14:23:54.749  1017  1344 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:54.749  1017  1344 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 14:23:54.759  3717  3717 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,08-17 14:23:54.759  1017  1344 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 14:23:54.769  3717  3717 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-17 14:23:54.769  7124  7124 E Zygote  : MountEmulatedStorage()
08-17 14:23:54.769  7124  7124 E Zygote  : v2
08-17 14:23:54.769  7124  7124 I libpersona: KNOX_SDCARD checking this for 10094
08-17 14:23:54.769  7124  7124 I libpersona: KNOX_SDCARD not a persona
,08-17 14:23:54.769  7124  7124 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-17 14:23:54.769  7124  7124 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-17 14:23:54.779  7124  7124 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 14:23:54.779  1017  1344 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7124 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,08-17 14:23:54.789  1017  1042 D EnterpriseDeviceManagerService: Package has changed for user 0
,08-17 14:23:54.789  1017  1042 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-17 14:23:54.799  3717  3717 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-17 14:23:54.799  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 14:23:54.799  1017  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 14:23:54.799  3717  7123 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-17 14:23:54.809  1017  1483 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-17 14:23:54.809  1017  1483 D SecContentProvider2: mCursor = null
,08-17 14:23:54.809  1017  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,08-17 14:23:54.809  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:54.809  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:54.809  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:54.809  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 14:23:54.819  1017  1042 W TextServicesManagerService: no available spell checker services found
,08-17 14:23:54.819  1017  1531 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,08-17 14:23:54.819  1017  1531 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,08-17 14:23:54.819  7124  7124 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 14:23:54.819  7124  7124 D ActivityThread: Added TimaKeyStore provider
,08-17 14:23:54.829  7139  7139 E Zygote  : MountEmulatedStorage()
,08-17 14:23:54.829  7139  7139 E Zygote  : v2
08-17 14:23:54.829  7139  7139 I libpersona: KNOX_SDCARD checking this for 10044
08-17 14:23:54.829  7139  7139 I libpersona: KNOX_SDCARD not a persona
08-17 14:23:54.829  7139  7139 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,08-17 14:23:54.829  3175  3175 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 3
,08-17 14:23:54.829  1017  1043 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7139 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,08-17 14:23:54.839  7139  7139 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-17 14:23:54.839  7139  7139 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 14:23:54.839  6088  7115 I SA      : [RC New] Execute method=[GET] start
,08-17 14:23:54.849  3175  3175 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,08-17 14:23:54.849  3175  3175 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,08-17 14:23:54.859  3175  3175 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,08-17 14:23:54.859  3175  3175 I DBG_DM  : [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,08-17 14:23:54.859  3175  3175 I DBG_DM  : [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,08-17 14:23:54.869  1017  1058 I art     : Explicit concurrent mark sweep GC freed 80668(5MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 28MB/42MB, paused 12.546ms total 361.839ms
,08-17 14:23:54.879  7139  7139 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 14:23:54.879  7139  7139 D ActivityThread: Added TimaKeyStore provider
,08-17 14:23:54.879  6088  7115 I SA      : [RC New] Security=[true]
,08-17 14:23:54.879  6088  7115 I System.out: Thread-1035(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,08-17 14:23:54.879  6088  7115 I System.out: Thread-1035(ApacheHTTPLog):isSBSettingEnabled false
08-17 14:23:54.879  6088  7115 I System.out: Thread-1035(ApacheHTTPLog):isShipBuild true
08-17 14:23:54.879  6088  7115 I System.out: Thread-1035(ApacheHTTPLog):SMARTBONDING_ENABLED is false
08-17 14:23:54.879  6088  7115 I System.out: Thread-1035(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,08-17 14:23:54.879  1017  1017 D RCPManagerService: PackageReceiver onReceive()
,08-17 14:23:54.889  1017  1017 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-17 14:23:54.889  3717  7123 I KLMS-2.5.183: : KLMSIntentService(): PACKAGE_REMOVED
,08-17 14:23:54.889   278   980 D EnterpriseController: uids 10041
08-17 14:23:54.889   278   980 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-17 14:23:54.889   278   980 D Netd    : getNetworkForDns: using netid 504 for uid 10041
,08-17 14:23:54.899  1017  1017 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,08-17 14:23:54.899  1017  1017 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-17 14:23:54.899  3717  7123 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().START
,08-17 14:23:54.899  1017  1058 D PackageManager: delete codoeFile: 
,08-17 14:23:54.899  1017  1017 D OTPFW   : OtpDbHelper::getInstance New instance created
,08-17 14:23:54.899  1017  1017 D OTPFW   : DBIntegrity::getInstance - New instance created
,08-17 14:23:54.899  1017  1505 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-17 14:23:54.899  1017  1505 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-17 14:23:54.899  1017  1505 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-17 14:23:54.899  3717  7123 I KLMS-2.5.183: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,08-17 14:23:54.909  1017  1017 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
,08-17 14:23:54.909  3175  3175 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,08-17 14:23:54.909  1017  1017 I OTPFW   : ProvisionData::getAllEntries Enter
,08-17 14:23:54.909  1017  1017 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-17 14:23:54.909  1017  1017 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-17 14:23:54.909  1017  1017 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-17 14:23:54.909  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-17 14:23:54.909  1017  1017 V EnterpriseBillingPolicy: uID is 10155
08-17 14:23:54.909  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
08-17 14:23:54.909  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-17 14:23:54.919  1017  1058 D AASAuninstall: userId = 0, info.removedAppID = 10155, info.uid = 10155, packageName = com.test.thalitest
08-17 14:23:54.919  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-17 14:23:54.919  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-17 14:23:54.919  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-17 14:23:54.919  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-17 14:23:54.919  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 14:23:54.919  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-17 14:23:54.919  1017  1058 I AASA_removePackage: UID=10155 Target=com.test.thalitest
,08-17 14:23:54.919  1017  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,08-17 14:23:54.929  1017  1058 D PackageManager: result of delete: 1{610330788}
08-17 14:23:54.929  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:54.929  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:54.929  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:54.929  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 14:23:54.929  7124  7124 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,08-17 14:23:54.929  7124  7124 D elm:15183: ELMEngine.ELMEngine( context ).
,08-17 14:23:54.939  7156  7156 E Zygote  : MountEmulatedStorage()
08-17 14:23:54.939  7156  7156 E Zygote  : v2
08-17 14:23:54.939  7156  7156 I libpersona: KNOX_SDCARD checking this for 10149
08-17 14:23:54.939  7156  7156 I libpersona: KNOX_SDCARD not a persona
,08-17 14:23:54.939  7156  7156 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
08-17 14:23:54.939  7124  7124 D elm:15183: MDMBridge.setEnterpriseBridge()
,08-17 14:23:54.939  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 14:23:54.939  7156  7156 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-17 14:23:54.949  7073  7073 D AndroidRuntime: Shutting down VM
,08-17 14:23:54.949  7139  7139 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-17 14:23:54.949  7156  7156 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-17 14:23:54.949  7139  7139 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 14:23:54.949  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-17 14:23:54.949  7139  7139 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-17 14:23:54.949  7139  7139 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-17 14:23:54.949  7139  7139 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
08-17 14:23:54.949  7139  7139 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-17 14:23:54.949  7139  7139 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-17 14:23:54.949  7139  7139 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-17 14:23:54.949  1017  1043 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7156 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-17 14:23:54.959  1017  1343 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
08-17 14:23:54.959  1017  1343 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-17 14:23:54.969  1017  1343 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:54.969  1017  1343 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:54.969  1017  1343 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,08-17 14:23:54.969  1017  1017 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-17 14:23:54.969  1017  1043 W ActivityManager: Activity pause timeout for ActivityRecord{25f27978 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t127}
,08-17 14:23:54.979  7124  7124 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,08-17 14:23:54.979  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-17 14:23:54.979  1017  1017 V EnterpriseBillingPolicy: uID is 10155
08-17 14:23:54.979  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
08-17 14:23:54.979  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-17 14:23:54.979  1017  2759 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,08-17 14:23:54.979  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-17 14:23:54.979  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-17 14:23:54.979  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-17 14:23:54.979  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-17 14:23:54.979  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-17 14:23:54.979  1017  1017 V AlarmManagerEXT: com.test.thalitest(10155) is removed.
,08-17 14:23:54.979   257   257 I SurfaceFlinger: id=16 createSurf (720x1280),1 flag=404, YUIInstallC
,08-17 14:23:54.979  1017  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-17 14:23:54.979  4781  7155 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,08-17 14:23:54.989  3406  3406 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,08-17 14:23:54.989  3406  3406 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-17 14:23:54.989  3406  3406 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
08-17 14:23:54.989  3406  3406 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
08-17 14:23:54.989  3406  3406 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
08-17 14:23:54.989  3406  3406 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
08-17 14:23:54.989  3406  3406 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
08-17 14:23:54.989  3406  3406 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:23:54.989  3406  3406 W System.err: 	at android.os.Looper.loop(Looper.java:145)
08-17 14:23:54.989  3406  3406 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 14:23:54.989  3406  3406 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 14:23:54.989  3406  3406 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 14:23:54.989  3406  3406 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 14:23:54.989  3406  3406 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-17 14:23:54.989  1017  1505 D InputDispatcher: Focus entered window: 3175
08-17 14:23:54.989  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-17 14:23:54.989  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-17 14:23:54.989  3175  3175 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-17 14:23:54.999  7124  7124 D elm:15183: ElmAgentService : onCreate()
,08-17 14:23:54.999  7124  7171 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,08-17 14:23:54.999  3175  3175 V ActivityThread: updateVisibility : ActivityRecord{3ac17caf token=android.os.BinderProxy@2d009e72 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,08-17 14:23:54.999  7124  7171 D elm:15183: MainReceiver.listeningToPackageRemoved()
08-17 14:23:54.999  7124  7171 D elm:15183: MDMBridge.getInstance()
08-17 14:23:54.999  7124  7171 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,08-17 14:23:54.999  7156  7156 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 14:23:55.009  1017  1531 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-17 14:23:55.009  7156  7156 D ActivityThread: Added TimaKeyStore provider
,08-17 14:23:55.019  7124  7171 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,08-17 14:23:55.019  3717  7123 I KLMS-2.5.183: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,08-17 14:23:55.019  1017  1531 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6291 uid 10155
,08-17 14:23:55.019  1017  1017 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
08-17 14:23:55.019  1017  1164 D TaskPersister: removeObsoleteFile: deleting file=129_task.xml
,08-17 14:23:55.019  1017  1164 D TaskPersister: removeObsoleteFile: deleting file=127_task.xml
,08-17 14:23:55.029  1017  7173 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-17 14:23:55.039  3717  7123 I KLMS-2.5.183: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,08-17 14:23:55.049  1797  1797 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,08-17 14:23:55.049  4781  4781 I art     : Explicit concurrent mark sweep GC freed 622(36KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 797us total 60.253ms
,08-17 14:23:55.059  3717  7123 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().END
,08-17 14:23:55.059  3175  3175 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2d009e72 time:171446
,08-17 14:23:55.059  3717  3717 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,08-17 14:23:55.069  7124  7124 D elm:15183: ElmAgentService : onDestroy().
,08-17 14:23:55.079  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-17 14:23:55.079  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,08-17 14:23:55.079  1017  1048 W ActivityManager: mDVFSHelper.release()
08-17 14:23:55.079  1017  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{25f27978 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t127} time:171464
,08-17 14:23:55.099  1017  1079 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,08-17 14:23:55.099  1017  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 14:23:55.099  1017  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 14:23:55.099  1017  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:55.099  5983  5995 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
08-17 14:23:55.099  1017  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:55.099  5983  5995 D BadgeProvider: sendNotify, [notify] : null
08-17 14:23:55.099  5983  5995 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
08-17 14:23:55.099  5983  5995 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-17 14:23:55.099  5983  5995 D BadgeProvider: update, [UpdateCount] : 1
,08-17 14:23:55.109  7178  7178 E Zygote  : MountEmulatedStorage(),
08-17 14:23:55.109  7178  7178 I libpersona: KNOX_SDCARD checking this for 1000
08-17 14:23:55.109  7178  7178 E Zygote  : v2
08-17 14:23:55.109  7178  7178 I libpersona: KNOX_SDCARD not a persona
,08-17 14:23:55.109  7178  7178 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-17 14:23:55.119  7178  7178 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-17 14:23:55.119  7178  7178 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 14:23:55.119  1017  1079 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7178 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
08-17 14:23:55.119  1181  1181 D PanelView: There is/are notification(s) 
,08-17 14:23:55.129  1017  1042 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-17 14:23:55.129  1181  1181 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,08-17 14:23:55.129  1181  1181 D PersonaManager: isKioskContainerExistOnDevice
08-17 14:23:55.129  1181  1181 D PersonaManager: isKioskContainerExistOnDevice
,08-17 14:23:55.129  1181  1181 D PanelView: There is/are notification(s) 
08-17 14:23:55.129  1181  1181 D PanelView: kidsfalse mQsExpansionEnabled:true
,08-17 14:23:55.129  1181  1181 D PersonaManager: isKioskContainerExistOnDevice
08-17 14:23:55.129  1181  1181 D PanelView: There is/are notification(s) 
08-17 14:23:55.129  1181  1181 D PanelView: kidsfalse mQsExpansionEnabled:true
,08-17 14:23:55.129  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 14:23:55.129  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 14:23:55.139  6532  6532 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-17 14:23:55.139  6532  6532 I PCWCLIENTTRACE_PushUtil: sales region : global
08-17 14:23:55.139  6532  6532 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-17 14:23:55.139  6532  6532 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,08-17 14:23:55.139  1017  1343 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,08-17 14:23:55.139  7156  7156 D ThemeInfoUtil: getCurrentFestivalName is [null]
08-17 14:23:55.139  7156  7156 D ThemeInfoUtil: isCurrentFestival = false
,08-17 14:23:55.139  1017  1343 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:55.139  1017  1343 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:55.139  1017  1343 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:55.139  1017  1343 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 14:23:55.149  7073  7073 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.,
,08-17 14:23:55.159  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 14:23:55.159  7193  7193 E Zygote  : MountEmulatedStorage()
,08-17 14:23:55.159  1017  1042 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-17 14:23:55.159  1017  1042 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-17 14:23:55.159  1017  1042 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-17 14:23:55.159  7193  7193 E Zygote  : v2
08-17 14:23:55.159  1017  1343 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7193 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,08-17 14:23:55.159  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-17 14:23:55.159  7193  7193 I libpersona: KNOX_SDCARD checking this for 10032
08-17 14:23:55.159  7193  7193 I libpersona: KNOX_SDCARD not a persona
08-17 14:23:55.159  7193  7193 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-17 14:23:55.169  7193  7193 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-17 14:23:55.169  7193  7193 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 14:23:55.169  7178  7178 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 14:23:55.169  7178  7178 D ActivityThread: Added TimaKeyStore provider
,08-17 14:23:55.169  1017  1343 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
08-17 14:23:55.179  1017  1058 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-17 14:23:55.179  1017  1058 D PackageManager: userId{-1}
08-17 14:23:55.179  1017  1058 D PackageManager: andCode{true}
08-17 14:23:55.179  1017  1343 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:55.179  1017  1343 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:55.179  1017  1343 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:55.179  1017  1343 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 14:23:55.179  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 14:23:55.189  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 14:23:55.189  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-17 14:23:55.189  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-17 14:23:55.199  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 14:23:55.199  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-17 14:23:55.199  7208  7208 E Zygote  : MountEmulatedStorage()
08-17 14:23:55.199  7208  7208 I libpersona: KNOX_SDCARD checking this for 10152
08-17 14:23:55.199  7208  7208 E Zygote  : v2
08-17 14:23:55.199  7208  7208 I libpersona: KNOX_SDCARD not a persona
08-17 14:23:55.199  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-17 14:23:55.199  7208  7208 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-17 14:23:55.199  1181  1181 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,08-17 14:23:55.199  1017  1343 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7208 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
08-17 14:23:55.199  7208  7208 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-17 14:23:55.199  1017  1343 I ActivityManager: Killing 5913:com.google.android.gms:car/u0a12 (adj 15): empty #31
,08-17 14:23:55.199  7208  7208 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 14:23:55.209  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-17 14:23:55.209  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-17 14:23:55.209  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 14:23:55.209  7193  7193 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 14:23:55.209  1017  1058 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
08-17 14:23:55.209  7193  7193 D ActivityThread: Added TimaKeyStore provider
,08-17 14:23:55.239  1017  1042 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-17 14:23:55.239  1017  1042 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-17 14:23:55.249  7208  7208 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 14:23:55.249  7208  7208 D ActivityThread: Added TimaKeyStore provider
,08-17 14:23:55.259  7139  7139 D NearbySource: Nearby Source Create!
,08-17 14:23:55.259  7139  7139 D NearbyContext: Nearby Context Create!
,08-17 14:23:55.269  1017  3057 D PersonaManager: isKioskContainerExistOnDevice
08-17 14:23:55.269  7178  7178 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,08-17 14:23:55.279  1017  2745 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
,08-17 14:23:55.279  1017  2745 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,08-17 14:23:55.279  1017  2745 W ActivityManager: userId = 0, bbcId = -10000
08-17 14:23:55.279  1017  2745 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 14:23:55.279  1017  2745 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,08-17 14:23:55.289  1017  1505 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,08-17 14:23:55.289  1017  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:55.289  1017  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:55.289  1017  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:55.289  1017  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 14:23:55.289  7208  7208 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.provider.shootingmodeprovider/databases/shootingmodemanager.db" with flag (131138) and mode_t (0) due to error (30)
,08-17 14:23:55.299  7208  7208 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.provider.shootingmodeprovider/databases/shootingmodemanager.db'.
08-17 14:23:55.299  7208  7208 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 14:23:55.299  7208  7208 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 14:23:55.299  7208  7208 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-17 14:23:55.299  7208  7208 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-17 14:23:55.299  7208  7208 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-17 14:23:55.299  7208  7208 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-17 14:23:55.299  7208  7208 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-17 14:23:55.299  7208  7208 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-17 14:23:55.299  7208  7208 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-17 14:23:55.299  7208  7208 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-17 14:23:55.299  7208  7208 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-17 14:23:55.299  7208  7208 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-17 14:23:55.299  7208  7208 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 14:23:55.299  7208  7208 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 14:23:55.299  7208  7208 E SQLiteDatabase: 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.initializeSQLiteStatements(ShootingModeProvider.java:277)
08-17 14:23:55.299  7208  7208 E SQLiteDatabase: 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.onCreate(ShootingModeProvider.java:240)
08-17 14:23:55.299  7208  7208 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
08-17 14:23:55.299  7208  7208 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
08-17 14:23:55.299  7208  7208 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
08-17 14:23:55.299  7208  7208 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
08-17 14:23:55.299  7208  7208 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
08-17 14:23:55.299  7208  7208 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 14:23:55.299  7208  7208 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 14:23:55.299  7208  7208 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:23:55.299  7208  7208 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-17 14:23:55.299  7208  7208 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 14:23:55.299  7208  7208 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 14:23:55.299  7208  7208 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 14:23:55.299  7208  7208 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 14:23:55.299  7208  7208 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 14:23:55.299  7208  7208 D AndroidRuntime: Shutting down, VM
08-17 14:23:55.299  7208  7208 E AndroidRuntime: FATAL EXCEPTION: main
08-17 14:23:55.299  7208  7208 E AndroidRuntime: Process: com.samsung.android.provider.shootingmodeprovider, PID: 7208
08-17 14:23:55.299  7208  7208 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 14:23:55.299  7208  7208 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5705)
08-17 14:23:55.299  7208  7208 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
08-17 14:23:55.299  7208  7208 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
08-17 14:23:55.299  7208  7208 E AndroidRuntime: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 14:23:55.299  7208  7208 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 14:23:55.299  7208  7208 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:23:55.299  7208  7208 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-17 14:23:55.299  7208  7208 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 14:23:55.299  7208  7208 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 14:23:55.299  7208  7208 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 14:23:55.299  7208  7208 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 14:23:55.299  7208  7208 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 14:23:55.299  7208  7208 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 14:23:55.299  7208  7208 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 14:23:55.299  7208  7208 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-17 14:23:55.299  7208  7208 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-17 14:23:55.299  7208  7208 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-17 14:23:55.299  7208  7208 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-17 14:23:55.299  7208  7208 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-17 14:23:55.299  7208  7208 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-17 14:23:55.299  7208  7208 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-17 14:23:55.299  7208  7208 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-17 14:23:55.299  7208  7208 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-17 14:23:55.299  7208  7208 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-17 14:23:55.299  7208  7208 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 14:23:55.299  7208  7208 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 14:23:55.299  7208  7208 E AndroidRuntime: 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.initializeSQLiteStatements(ShootingModeProvider.java:277)
08-17 14:23:55.299  7208  7208 E AndroidRuntime: 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.onCreate(ShootingModeProvider,.java:240)
08-17 14:23:55.299  7208  7208 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
08-17 14:23:55.299  7208  7208 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
08-17 14:23:55.299  7208  7208 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
08-17 14:23:55.299  7208  7208 E AndroidRuntime: 	... 11 more
08-17 14:23:55.309  7178  7226 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (30)
08-17 14:23:55.309  7227  7227 E Zygote  : MountEmulatedStorage()
08-17 14:23:55.309  7227  7227 E Zygote  : v2
08-17 14:23:55.309  7227  7227 I libpersona: KNOX_SDCARD checking this for 1000
08-17 14:23:55.309  7227  7227 I libpersona: KNOX_SDCARD not a persona
08-17 14:23:55.309  7178  7226 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
08-17 14:23:55.309  7178  7226 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 14:23:55.309  7178  7226 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 14:23:55.309  7178  7226 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-17 14:23:55.309  7178  7226 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-17 14:23:55.309  7178  7226 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-17 14:23:55.309  7178  7226 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-17 14:23:55.309  7178  7226 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-17 14:23:55.309  7178  7226 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-17 14:23:55.309  7178  7226 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-17 14:23:55.309  7178  7226 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-17 14:23:55.309  7178  7226 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-17 14:23:55.309  7178  7226 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-17 14:23:55.309  7178  7226 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 14:23:55.309  7178  7226 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 14:23:55.309  7178  7226 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
08-17 14:23:55.309  7178  7226 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:112)
08-17 14:23:55.309  7178  7226 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-17 14:23:55.309  7178  7226 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:23:55.309  7178  7226 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-17 14:23:55.309  7178  7226 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-17 14:23:55.309  7178  7226 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 14:23:55.309  1017  1505 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7227 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
08-17 14:23:55.309  7178  7226 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 14:23:55.309  7178  7226 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-17 14:23:55.309  7178  7226 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-17 14:23:55.309  7178  7226 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-17 14:23:55.309  7178  7226 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-17 14:23:55.309  7178  7226 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-17 14:23:55.309  7178  7226 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-17 14:23:55.309  7178  7226 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-17 14:23:55.309  7178  7226 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-17 14:23:55.309  7178  7226 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-17 14:23:55.309  7178  7226 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-17 14:23:55.309  7178  7226 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 14:23:55.309  7178  7226 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 14:23:55.309  7178  7226 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
08-17 14:23:55.309  7178  7226 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:112)
08-17 14:23:55.309  7178  7226 W System.err: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-17 14:23:55.309  7178  7226 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:23:55.309  7178  7226 W System.err: 	at android.os.Looper.loop(Looper.java:145)
08-17 14:23:55.309  7178  7226 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-17 14:23:55.319  7227  7227 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-17 14:23:55.319   256   537 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
08-17 14:23:55.319   256   537 W Vold    : Returning OperationFailed - no handler for errno 0
08-17 14:23:55.319  1017  1079 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.provider.shootingmodeprovider
08-17 14:23:55.319  7227  7227 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-17 14:23:55.319  7139  7139 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
08-17 14:23:55.319  7227  7227 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-17 14:23:55.319  7139  7139 D SLinkSource: Samsung link source created
08-17 14:23:55.319  1017  1029 I ActivityManager: Killing 5484:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,08-17 14:23:55.339  7193  7233 I FeatureConfig: init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
08-17 14:23:55.349  1017  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
08-17 14:23:55.349  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:55.349  7227  7227 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 14:23:55.349  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:55.349  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:55.349  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:55.349  7227  7227 D ActivityThread: Added TimaKeyStore provider
08-17 14:23:55.359  1017  7240 E DropBoxManagerService: Can't write: system_app_crash
08-17 14:23:55.359  1017  7240 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop200.tmp: open failed: EROFS (Read-only file system)
08-17 14:23:55.359  1017  7240 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-17 14:23:55.359  1017  7240 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-17 14:23:55.359  1017  7240 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-17 14:23:55.359  1017  7240 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-17 14:23:55.359  1017  7240 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-17 14:23:55.359  1017  7240 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15777)
08-17 14:23:55.359  1017  7240 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-17 14:23:55.359  1017  7240 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-17 14:23:55.359  1017  7240 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-17 14:23:55.359  1017  7240 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-17 14:23:55.359  1017  7240 E DropBoxManagerService: 	... 5 more
08-17 14:23:55.359  7088  7088 E SQLiteLog: (28) failed to open "/data/data/com.sec.spp.push/databases/registration_db" with flag (131138) and mode_t (0) due to error (30)
08-17 14:23:55.359  7088  7088 E SQLiteDatabase: Failed to open database '/data/data/com.sec.spp.push/databases/registration_db'.
08-17 14:23:55.359  7088  7088 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 14:23:55.359  7088  7088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 14:23:55.359  7088  7088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-17 14:23:55.359  7088  7088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-17 14:23:55.359  7088  7088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-17 14:23:55.359  7088  7088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-17 14:23:55.359  7088  7088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-17 14:23:55.359  7088  7088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-17 14:23:55.359  7088  7088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-17 14:23:55.359  7088  7088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-17 14:23:55.359  7088  7088 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-17 14:23:55.359  7088  7088 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-17 14:23:55.359  7088  7088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 14:23:55.359  7088  7088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 14:23:55.359  7088  7088 E SQLiteDatabase: 	at com.sec.spp.push.i.a.a(Unknown Source)
08-17 14:23:55.359  7088  7088 E SQLiteDatabase: 	at com.sec.spp.push.i.c.d(Unknown Source)
08-17 14:23:55.359  7088  7088 E SQLiteDatabase: 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
08-17 14:23:55.359  7088  7088 E SQLiteDatabase: 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
08-17 14:23:55.359  7088  7088 E SQLiteDatabase: 	at com.sec.spp.push.receiver.a.handleMessage(Unknown Source)
08-17 14:23:55.359  7088  7088 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:23:55.359  7088  7088 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-17 14:23:55.359  7088  7088 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 14:23:55.359  7088  7088 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 14:23:55.359  7088  7088 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 14:23:55.359  7088  7088 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 14:23:55.359  7088  7088 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 14:23:55.359  7088  7088 E SPPClientService: [c] [getAppId()] SQLiteException with message =not an error (code 0): Could not open the database in read/write mode.
08-17 14:23:55.369  7245  7245 E Zygote  : MountEmulatedStorage()
08-17 14:23:55.369  7245  7245 I libpersona: KNOX_SDCARD checking this for 10156
08-17 14:23:55.369  7245  7245 E Zygote  : v2
08-17 14:23:55.369  7245  7245 I libpersona: KNOX_SDCARD not a persona
08-17 14:23:55.369  7245  7245 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-17 14:23:55.369  7245  7245 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-17 14:23:55.369  7245  7245 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 14:23:55.379  7193  7233 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,08-17 14:23:55.379  7193  7233 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 14:23:55.379  7193  7233 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-17 14:23:55.379  7193  7233 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-17 14:23:55.379  7193  7233 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-17 14:23:55.379  7193  7233 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,08-17 14:23:55.379  1017  1043 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7245 uid=10156 gids={50156, 9997} abi=armeabi-v7a
,08-17 14:23:55.379  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-17 14:23:55.389  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:55.389  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:55.389  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:23:55.389  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0

```
