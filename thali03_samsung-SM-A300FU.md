#### Test 8180285644342f8_thali03_samsung-SM-A300FU Logs


```
--------- beginning of system
08-19 17:54:40.767  1021  1524 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.filterinstaller, hostingType: broadcast
08-19 17:54:40.767  1021  1524 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:54:40.767  1021  1524 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:54:40.767  1021  1524 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:54:40.767  1021  1524 E ActivityManager: checkUser: useridlist=null, currentuser=0
--------- beginning of main
08-19 17:54:40.787  6304  6304 E Zygote  : MountEmulatedStorage()
08-19 17:54:40.787  6304  6304 E Zygote  : v2
08-19 17:54:40.787  6304  6304 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-19 17:54:40.787  6304  6304 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-19 17:54:40.787  6304  6304 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-19 17:54:40.787  6304  6304 I libpersona: KNOX_SDCARD checking this for 1000
08-19 17:54:40.787  6304  6304 I libpersona: KNOX_SDCARD not a persona
08-19 17:54:40.787  1021  1524 I ActivityManager: Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=6304 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-19 17:54:40.787  1021  1524 I ActivityManager: Killing 5970:com.sec.spp.push/u0a32 (adj 15): empty #21
08-19 17:54:40.807  6304  6304 D TimaKeyStoreProvider: TimaSignature is unavailable
08-19 17:54:40.807  6304  6304 D ActivityThread: Added TimaKeyStore provider
08-19 17:54:40.817   287   287 E SMD     : DCD OFF
08-19 17:54:40.837  6060  6303 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-19 17:54:40.837  6060  6303 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-19 17:54:40.847  6304  6304 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
08-19 17:54:40.847  6304  6304 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
08-19 17:54:40.847  1021  1125 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
08-19 17:54:40.847  1021  1125 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
08-19 17:54:40.847  1021  1125 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:54:40.847  1021  1125 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:54:40.847  1021  1125 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
08-19 17:54:40.857  1021  4073 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-19 17:54:40.857  6304  6304 I FilterInstaller: FilterPackageService : ACTION_CHANGED
08-19 17:54:40.867  1021  1021 D ActivityManager: bindService callerProcessName:android, calleePkgName: android, action: null
08-19 17:54:40.867  1021  1021 D ActivityManager: retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
08-19 17:54:40.877   277  1004 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-19 17:54:40.877   277  1004 D Netd    : getNetworkForDns: using netid 0 for uid 10011
08-19 17:54:40.877  1021  1391 D NtpTrustedTime: forceRefresh() from cache miss
08-19 17:54:40.877  6304  6321 E FilterInstaller: installFilters
08-19 17:54:40.887  6304  6321 E FilterInstaller: There is no requred permission
08-19 17:54:40.887  1021  1508 I ActivityManager: Killing 5955:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
08-19 17:54:40.887  1021  1021 I BackgroundCompactionService: onStart. jobID=801
08-19 17:54:40.887   277  1004 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-19 17:54:40.887   277  1004 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-19 17:54:40.887  1021  1021 I BackgroundCompactionService: onStart done. jobID=801
08-19 17:54:40.887   277  1004 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-19 17:54:40.887   277  1004 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-19 17:54:40.897  1021  6325 I BackgroundCompactionService: Execute BGCompaction (type1). (0 times)
08-19 17:54:40.897  1021  1391 D NtpTrustedTime: forceRefresh Fail.
08-19 17:54:40.897  1021  6325 I BackgroundCompactionService: compact_memory command done
08-19 17:54:40.907  1021  1046 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:54:40.907  1021  1046 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-19 17:54:40.907  1021  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
08-19 17:54:40.907  1021  1046 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
08-19 17:54:40.917  1021  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:54:40.917  1021  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:54:40.917  1021  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:54:40.917  1021  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:54:40.917  6060  6303 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
08-19 17:54:40.927  6329  6329 E Zygote  : MountEmulatedStorage()
08-19 17:54:40.927  6329  6329 E Zygote  : v2
08-19 17:54:40.937  6329  6329 I libpersona: KNOX_SDCARD checking this for 10102
08-19 17:54:40.937  6329  6329 I libpersona: KNOX_SDCARD not a persona
08-19 17:54:40.937  6329  6329 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-19 17:54:40.937  6329  6329 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-19 17:54:40.947  1021  1046 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6329 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
08-19 17:54:40.947  6329  6329 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-19 17:54:40.977  6329  6329 D TimaKeyStoreProvider: TimaSignature is unavailable
08-19 17:54:40.977  6329  6329 D ActivityThread: Added TimaKeyStore provider
08-19 17:54:41.017  6329  6329 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-19 17:54:41.027  6060  6303 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-19 17:54:41.027  6060  6303 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@13f8bb0b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-19 17:54:41.027  6060  6303 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
08-19 17:54:41.137  6327  6327 D AndroidRuntime: 
08-19 17:54:41.137  6327  6327 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-19 17:54:41.137  6327  6327 D AndroidRuntime: CheckJNI is OFF
08-19 17:54:41.137  6327  6327 D AndroidRuntime: readGMSProperty: start
08-19 17:54:41.137  6327  6327 D AndroidRuntime: readGMSProperty: already setted!!
08-19 17:54:41.137  6327  6327 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-19 17:54:41.137  6327  6327 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-19 17:54:41.137  6327  6327 D AndroidRuntime: readGMSProperty: end
08-19 17:54:41.137  6327  6327 D AndroidRuntime: addProductProperty: start
08-19 17:54:41.247  6329  6355 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
08-19 17:54:41.247  6329  6355 I Babel_SMS: MmsConfig.loadMmsSettings
08-19 17:54:41.247  6329  6355 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
08-19 17:54:41.247  6329  6355 I Babel_SMS: MmsConfig.loadFromDatabase
08-19 17:54:41.257  1021  1524 I ActivityManager: Killing 5985:com.samsung.helphub/1000 (adj 15): empty #21
08-19 17:54:41.277  6329  6355 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-19 17:54:41.277  6329  6355 I Babel_SMS: MmsConfig.loadFromResources
08-19 17:54:41.277  6329  6355 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
08-19 17:54:41.277  6327  6327 E AffinityControl: AffinityControl: registerfunction enter
08-19 17:54:41.277  6329  6355 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
08-19 17:54:41.307  6327  6327 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-19 17:54:41.307  1021  1125 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
08-19 17:54:41.307  1021  1125 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
08-19 17:54:41.317  1021  1125 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:54:41.317  1021  1125 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-19 17:54:41.317  1021  1125 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
08-19 17:54:41.317  1021  4073 E PersonaManagerService: inState():  stateMachine is null !!
08-19 17:54:41.327  1021  4073 I PersonaManagerService: PersonaId don't exist
08-19 17:54:41.327  1021  4073 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-19 17:54:41.327  1021  4073 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-19 17:54:41.337  1021  4073 W ActivityManager: mDVFSHelper.acquire()
08-19 17:54:41.347  1021  4073 D FocusedStackFrame: Set to : 0
08-19 17:54:41.357  1021  4073 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:54:41.357  1021  4073 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:54:41.357  1021  4073 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:54:41.357  1021  4073 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:54:41.367  1021  1051 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-19 17:54:41.367  1021  1051 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-19 17:54:41.367  6361  6361 E Zygote  : MountEmulatedStorage()
08-19 17:54:41.367  6361  6361 E Zygote  : v2
08-19 17:54:41.367  6361  6361 I libpersona: KNOX_SDCARD checking this for 10170
08-19 17:54:41.367  1021  4073 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-19 17:54:41.367  6361  6361 I libpersona: KNOX_SDCARD not a persona
08-19 17:54:41.367  1021  4073 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-19 17:54:41.367  1021  4073 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6361 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-19 17:54:41.367  1021  4073 D InputDispatcher: Focused application set to: xxxx
08-19 17:54:41.367  1021  4073 D InputDispatcher: Focus left window: 1509
08-19 17:54:41.377  6327  6327 D AndroidRuntime: Shutting down VM
08-19 17:54:41.377  6361  6361 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-19 17:54:41.377  6329  6329 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-19 17:54:41.377  6361  6361 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-19 17:54:41.377  6361  6361 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-19 17:54:41.377  6329  6329 I Babel_Crash: startup - clean
08-19 17:54:41.387  1021  1051 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-19 17:54:41.387  1021  1051 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-19 17:54:41.387   257   257 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, uhalitest
08-19 17:54:41.407  6361  6361 D TimaKeyStoreProvider: TimaSignature is unavailable
08-19 17:54:41.407  6361  6361 D ActivityThread: Added TimaKeyStore provider
08-19 17:54:41.417  1021  1225 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-19 17:54:41.417  1021  1049 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-19 17:54:41.427  1021  1051 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-19 17:54:41.427  1021  1051 D PointerIcon: setMouseCustomIcon IconType is same.101
08-19 17:54:41.427  1021  1021 V ActivityManager: Display changed displayId=0
08-19 17:54:41.447  1021  1225 D PersonaManager: isKioskContainerExistOnDevice
08-19 17:54:41.467  1021  1021 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-19 17:54:41.477   257   581 I SurfaceFlinger: id=9 Removed Mauncher (5/9)
08-19 17:54:41.477   257   432 I SurfaceFlinger: id=9 Removed Mauncher (-2/9)
08-19 17:54:41.487  1509  1509 V ActivityThread: updateVisibility : ActivityRecord{3f8df196 token=android.os.BinderProxy@e595d20 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-19 17:54:41.487  1509  1509 D Launcher: onTrimMemory. Level: 20
08-19 17:54:41.487  6329  6329 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-19 17:54:41.497  6329  6329 W AudioCapabilities: Unsupported mime audio/evrc
08-19 17:54:41.497  6329  6329 W AudioCapabilities: Unsupported mime audio/qcelp
08-19 17:54:41.497  6329  6329 W AudioCapabilities: Unsupported mime audio/mpeg-L1
08-19 17:54:41.497  6329  6329 W AudioCapabilities: Unsupported mime audio/mpeg-L2
08-19 17:54:41.497  6329  6329 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-19 17:54:41.507  6329  6329 W AudioCapabilities: Unsupported mime audio/x-ima
08-19 17:54:41.507  6329  6329 W AudioCapabilities: Unsupported mime audio/qcelp
08-19 17:54:41.507  6329  6329 W AudioCapabilities: Unsupported mime audio/evrc
08-19 17:54:41.517  6329  6329 W VideoCapabilities: Unsupported mime video/wvc1
08-19 17:54:41.517  6329  6329 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-19 17:54:41.527  6329  6329 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
08-19 17:54:41.527  6329  6329 W VideoCapabilities: Unsupported mime video/wvc1
08-19 17:54:41.527  6329  6329 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-19 17:54:41.527  6329  6329 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
08-19 17:54:41.527  6329  6329 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
08-19 17:54:41.537  6329  6329 W VideoCapabilities: Unsupported mime video/mp43
08-19 17:54:41.537  6329  6329 W VideoCapabilities: Unsupported mime video/sorenson
08-19 17:54:41.537  6329  6329 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-19 17:54:41.547   326   326 I ServiceManager: Waiting for service AtCmdFwd...
08-19 17:54:41.557  6329  6329 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
08-19 17:54:41.577  6327  6327 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
08-19 17:54:41.577  6361  6361 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-19 17:54:41.587  6329  6329 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-19 17:54:41.587  6329  6329 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-19 17:54:41.597  6329  6329 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-19 17:54:41.597  6329  6329 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-19 17:54:41.597  6361  6361 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 3705-3707)
08-19 17:54:41.597  6361  6361 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-19 17:54:41.607  1021  4075 I ActivityManager: Killing 5541:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,08-19 17:54:41.607  6329  6329 I vclib   : onServiceConnected
,08-19 17:54:41.627  6361  6361 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {206c829}
,08-19 17:54:41.627  6361  6361 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-19 17:54:41.627  6361  6361 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-19 17:54:41.667  6361  6361 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-19 17:54:41.667  6361  6361 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-19 17:54:41.677  6361  6361 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-19 17:54:41.707  6361  6379 W chromium: [WARNING:dns_config_service_posix.cc(298)] Failed to read DnsConfig.
,08-19 17:54:41.707  6361  6361 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-19 17:54:41.707  6361  6361 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-19 17:54:41.707  6361  6361 I Adreno-EGL: Build Date: 04/06/15 Mon
08-19 17:54:41.707  6361  6361 I Adreno-EGL: Local Branch: 
08-19 17:54:41.707  6361  6361 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-19 17:54:41.707  6361  6361 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-19 17:54:41.707  6361  6361 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-19 17:54:41.797  6361  6361 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-19 17:54:41.807  6361  6361 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-19 17:54:41.817  6361  6361 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-19 17:54:41.817  6361  6361 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-19 17:54:41.827  6361  6361 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-19 17:54:41.927  6361  6361 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-19 17:54:41.937  6361  6361 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-19 17:54:41.947  6361  6361 D PhoneWindow: *FMB* installDecor mIsFloating : false
,08-19 17:54:41.947  6361  6361 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-19 17:54:41.957  6361  6361 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-19 17:54:41.957  1021  1046 W ActivityManager: Activity pause timeout for ActivityRecord{368d871f u0 com.test.thalitest/.MainActivity t163}
,08-19 17:54:41.967  6361  6361 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-19 17:54:41.967  6361  6361 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-19 17:54:42.037  6041  6041 I Mms/MmsApp:  start initViewCache mms
08-19 17:54:42.037  6041  6041 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1938.102396
08-19 17:54:42.037  6041  6041 D Mms/ComposeMessageFragment: fillCache, easy = false
08-19 17:54:42.097  6361  6401 D OpenGLRenderer: Render dirty regions requested: true
08-19 17:54:42.097  1021  4073 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-19 17:54:42.107  1021  4073 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-19 17:54:42.107  1021  4073 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-19 17:54:42.107  1021  1021 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-19 17:54:42.107  1021  1021 D PersonaManagerService: getPersonasForUser(): returning null!
08-19 17:54:42.117  6361  6388 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
08-19 17:54:42.117  6361  6361 V ActivityThread: updateVisibility : ActivityRecord{2b978f09 token=android.os.BinderProxy@2ce68ec2 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-19 17:54:42.127  6361  6361 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-19 17:54:42.127  6361  6361 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-19 17:54:42.157   257   257 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, NainActivit
08-19 17:54:42.167  6041  6041 D AbsListView: Get MotionRecognitionManager
08-19 17:54:42.167  1021  1524 D MotionRecognitionService:  ssp status : false
08-19 17:54:42.167  1021  1728 D InputDispatcher: Focus entered window: 6361
08-19 17:54:42.177  6041  6041 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 132.568802
08-19 17:54:42.177  1021  1051 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-19 17:54:42.177  1021  1051 D PointerIcon: setMouseCustomIcon IconType is same.101
08-19 17:54:42.177  6361  6361 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-19 17:54:42.177  6361  6401 I OpenGLRenderer: Initialized EGL, version 1.4
08-19 17:54:42.187  6361  6401 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-19 17:54:42.187  6361  6401 D OpenGLRenderer: Enabling debug mode 0
08-19 17:54:42.207  1021  1727 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-19 17:54:42.217  1179  1179 D PanelView: There is/are notification(s) 
08-19 17:54:42.217  1021  6406 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-19 17:54:42.237  1021  1051 I ActivityManager: Displayed Component not be shown by security: +778ms (total +879ms)
08-19 17:54:42.237  1021  1051 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{368d871f u0 com.test.thalitest/.MainActivity t163} time:84341
08-19 17:54:42.237  1021  1051 W ActivityManager: mDVFSHelper.release()
08-19 17:54:42.237  6361  6361 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-19 17:54:42.237  6361  6361 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2ce68ec2 time:84343
08-19 17:54:42.237   257   432 I SurfaceFlinger: id=11 Removed uhalitest (7/9)
08-19 17:54:42.237   257   432 I SurfaceFlinger: id=11 Removed uhalitest (-2/9)
08-19 17:54:42.267  1935  1935 I SamsungIME: getCurrentCandidateView
08-19 17:54:42.277  6041  6041 D Mms/BubbleViewCache: fillCache bubble = 1
08-19 17:54:42.277  6361  6361 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6361
08-19 17:54:42.377  1935  1935 D SamsungIME: Dismiss ExpandCandiate
08-19 17:54:42.467  6361  6361 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-19 17:54:42.527  1935  1935 I SamsungIME: getDebugLevel  : 0x4f4c
08-19 17:54:42.547  6361  6405 D jxcore_app_log: JniHelper::setJavaVM(0xb7e6b2b0), pthread_self() = -1203786816
08-19 17:54:42.557   326   326 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
08-19 17:54:42.557  6361  6405 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-19 17:54:42.557  6361  6405 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-19 17:54:42.557  6361  6405 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-19 17:54:42.557  6361  6405 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-19 17:54:42.557  6361  6405 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-19 17:54:42.557  6361  6405 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27775127 added. We now have 1 listener(s)
08-19 17:54:42.557  6361  6405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
08-19 17:54:42.567  6361  6405 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-19 17:54:42.567  1935  1935 I SamsungIME: getDebugLevel  : 0x4f4c
08-19 17:54:42.567  6361  6405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-19 17:54:42.567  6361  6405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-19 17:54:42.567  6361  6405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-19 17:54:42.567  6361  6405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-19 17:54:42.567  6361  6405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-19 17:54:42.567  6361  6405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
08-19 17:54:42.567  6361  6405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-19 17:54:42.567  6361  6405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-19 17:54:42.567  6361  6405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-19 17:54:42.567  6361  6405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-19 17:54:42.567  6361  6405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-19 17:54:42.567  6361  6405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-19 17:54:42.567  6361  6405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-19 17:54:42.567  6361  6405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-19 17:54:42.567  6361  6405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-19 17:54:42.567  6361  6405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-19 17:54:42.567  6361  6405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e042c72 added. We now have 1 listener(s)
08-19 17:54:42.567  6361  6405 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-19 17:54:42.577  1935  1935 I SamsungIME: KeybaordView init() : load resources
08-19 17:54:42.577  6361  6405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-19 17:54:42.577  6361  6405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-19 17:54:42.577  6361  6405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-19 17:54:42.577  6361  6405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-19 17:54:42.577  6361  6405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-19 17:54:42.577  6361  6405 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-19 17:54:42.577  6361  6405 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
08-19 17:54:42.587  6361  6405 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-19 17:54:42.587  6361  6405 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-19 17:54:42.587  6361  6405 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:54:42.587  6361  6405 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:54:42.587  6361  6405 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:54:42.587  6361  6405 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:54:42.587  6361  6405 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:54:42.587  6361  6405 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:54:42.587  6361  6405 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-19 17:54:42.587  6361  6405 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-19 17:54:42.587  6361  6405 D io.jxcore.node.ConnectivityMonitor: start: OK
08-19 17:54:42.597  6361  6361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:54:42.597  6361  6405 I io.jxcore.node.LifeCycleMonitor: start: OK
08-19 17:54:42.617  1935  1935 I SamsungIME: getCurrentKeyboard
08-19 17:54:42.617  1935  1935 I SamsungIME: getTextKeyboard
08-19 17:54:42.627  6361  6361 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
08-19 17:54:42.647  1935  1935 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-19 17:54:42.957  6026  6076 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
,08-19 17:54:42.977  6026  6076 I AcmsKeyStoreHelper: Key Store exist
08-19 17:54:42.977  6026  6076 I AcmsKeyStoreHelper: Hence loading the keystore file
,08-19 17:54:43.037  6026  6076 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
08-19 17:54:43.037  6026  6076 I AcmsCertificateMngr: getKeyStoreForApplication success 
08-19 17:54:43.037  6026  6076 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
08-19 17:54:43.037  6026  6076 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-19 17:54:43.037  6026  6076 D AcmsServiceMonitor: Decrementing - Counter value: 1
08-19 17:54:43.037  6026  6076 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
,08-19 17:54:43.037  6026  6076 D AcmsCore: This is NOT a valid MirrorLink app
08-19 17:54:43.037  6026  6076 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
08-19 17:54:43.037  6026  6076 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-19 17:54:43.037  6026  6076 D AcmsServiceMonitor: Decrementing - Counter value: 0
08-19 17:54:43.037  6026  6076 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
,08-19 17:54:43.037  6026  6026 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
08-19 17:54:43.037  6026  6026 D AcmsService: Enter onDestroy
08-19 17:54:43.037  6026  6026 I AcmsService: cleanUp(): inside service clean up
08-19 17:54:43.037  6026  6026 D AcmsCore: AcmsCore: inside DeInit
08-19 17:54:43.037  6026  6026 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
08-19 17:54:43.037  6026  6026 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
08-19 17:54:43.037  6026  6026 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
08-19 17:54:43.037  6026  6026 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
08-19 17:54:43.037  6026  6026 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
,08-19 17:54:43.037  6026  6026 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
08-19 17:54:43.037  6026  6026 D AcmsService: killing acms process
08-19 17:54:43.037  6026  6026 I Process : Sending signal. PID: 6026 SIG: 9
,08-19 17:54:43.137  1021  1728 I ActivityManager: Process ACMS.Process (pid 6026)(adj 0) has died(29,772)
,08-19 17:54:43.147  1021  1045 W libprocessgroup: failed to kill pid 6026: No such process
,08-19 17:54:43.187  6361  6416 W jxcore-log: Initializing JXcore engine
08-19 17:54:43.187  6361  6416 W jxcore-log: JXcore engine is ready
,08-19 17:54:43.237  1926  1926 E audit   : type=1400 msg=audit(1471622083.237:203): avc:  denied  { ioctl } for  pid=6416 comm="Thread-1171" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2074 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-19 17:54:43.237  1926  1926 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-19 17:54:43.237  1926  1926 E audit   : type=1300 msg=audit(1471622083.237:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9ca108f8 items=0 ppid=306 ppcomm=main pid=6416 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1171" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-19 17:54:43.237  1926  1926 E audit   : type=1320 msg=audit(1471622083.237:203): 
,08-19 17:54:43.247  6361  6416 W jxcore-log: Starting JXcore engine
,08-19 17:54:43.297  1021  2852 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-19 17:54:43.357  6361  6416 W jxcore-log: Platform android
08-19 17:54:43.357  6361  6416 W jxcore-log: 
08-19 17:54:43.357  6361  6416 W jxcore-log: Process ARCH arm
08-19 17:54:43.357  6361  6416 W jxcore-log: 
,08-19 17:54:43.557  6361  6416 I jxcore-log: JXcore Cordova bridge is ready!
08-19 17:54:43.557  6361  6416 I jxcore-log: 
,08-19 17:54:43.557  6361  6416 W jxcore-log: JXcore engine is started
,08-19 17:54:43.567  6361  6405 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-19 17:54:43.567  6361  6361 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41),
,08-19 17:54:43.737  1021  1033 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-19 17:54:43.747  1021  1033 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4226, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-19 17:54:43.747  1021  1033 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-19 17:54:43.747  1021  1033 D BatteryService: stay LED for charging
08-19 17:54:43.747  1021  1021 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-19 17:54:43.797  1021  1021 I MotionRecognitionService: Plugged
,08-19 17:54:43.797  1021  1021 I MotionRecognitionService: mGripSensorEnabled= false
,08-19 17:54:43.797  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-19 17:54:43.797  1441  1441 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-19 17:54:43.797  1441  1441 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-19 17:54:43.797  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-19 17:54:43.807  2760  2760 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-19 17:54:43.807  2760  3018 D HeadsetStateMachine: Disconnected process message: 10
,08-19 17:54:43.817   287   287 E SMD     : DCD OFF
08-19 17:54:43.817  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-19 17:54:43.827  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-19 17:54:43.827  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-19 17:54:43.827  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-19 17:54:43.827  1179  1179 D SViewCoverView: level :100 plugged : 2
,08-19 17:54:44.897  1681  1681 I ConfigService: onDestroy
,08-19 17:54:46.817   287   287 E SMD     : DCD OFF
,08-19 17:54:48.297  1021  2852 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-19 17:54:48.577  1345  1345 I wpa_supplicant: P2P: Current p2p state = IDLE,
08-19 17:54:48.577  1345  1345 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-19 17:54:48.577  1345  1345 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,08-19 17:54:48.577  1345  1345 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-19 17:54:48.577  1021  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-19 17:54:48.577  1021  1130 D SecContentProvider2: mCursor = null
,08-19 17:54:49.817   287   287 E SMD     : DCD OFF,
,08-19 17:54:49.847  1345  1345 I wpa_supplicant: nl80211: Received scan results (26 BSSes)
,08-19 17:54:49.847  1345  1345 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-19 17:54:49.847  1345  1345 I wpa_supplicant: wlan0: ANQP fetch completed,
,08-19 17:54:50.657  1021  1060 D PackageManager: [MSG] MCS_UNBIND
,08-19 17:54:50.667  1021  1499 I ActivityManager: Killing 4703:com.google.android.gms.wearable/u0a11 (adj 15): empty #21
,08-19 17:54:50.727  1021  2833 D SSRM:n  : SIOP:: AP = 390
,08-19 17:54:51.357  1021  1060 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-19 17:54:52.817   287   287 E SMD     : DCD OFF
,08-19 17:54:53.297  1021  2852 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-19 17:54:53.787  1021  1546 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-19 17:54:53.787  1021  1546 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4260, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-19 17:54:53.787  1021  1546 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-19 17:54:53.787  1021  1021 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-19 17:54:53.787  1021  1021 I MotionRecognitionService: Plugged
,08-19 17:54:53.787  1021  1021 I MotionRecognitionService: mGripSensorEnabled= false
08-19 17:54:53.797  1021  1546 D BatteryService: stay LED for charging
,08-19 17:54:53.797  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-19 17:54:53.797  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-19 17:54:53.797  1441  1441 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-19 17:54:53.797  1441  1441 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-19 17:54:53.807  2760  2760 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-19 17:54:53.807  2760  3018 D HeadsetStateMachine: Disconnected process message: 10
,08-19 17:54:53.817  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-19 17:54:53.817  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-19 17:54:53.817  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-19 17:54:53.817  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-19 17:54:53.817  1179  1179 D SViewCoverView: level :100 plugged : 2
,08-19 17:54:54.147  1021  1046 I ActivityManager: Waited long enough for: ServiceRecord{28bb7e75 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,08-19 17:54:54.777  1021  1099 V AlarmManager: waitForAlarm result :4,
08-19 17:54:54.777  1021  1099 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,08-19 17:54:55.007  5424  5479 D Finsky  : [959] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,08-19 17:54:55.007  5424  5424 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-19 17:54:55.377   271   271 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7e617c8,
08-19 17:54:55.377   271   271 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
08-19 17:54:55.377   271   271 I rmt_storage: wakelock acquired: 1, error no: 42
08-19 17:54:55.377   271   345 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1209658056)
,08-19 17:54:55.417   271   345 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
08-19 17:54:55.417   271   345 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
08-19 17:54:55.417   271   345 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1209658056) wakelock released: 1, error no: 0
08-19 17:54:55.417   271   345 I rmt_storage: 
,08-19 17:54:55.417   271   271 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb7e617c8
,08-19 17:54:55.817   287   287 E SMD     : DCD OFF,
,08-19 17:54:55.937  6361  6416 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
08-19 17:54:55.937  6361  6416 I jxcore-log: 
,08-19 17:54:55.937  6361  6416 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
08-19 17:54:55.937  6361  6416 I jxcore-log: 
,08-19 17:54:55.947  6361  6416 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-19 17:54:55.947  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:54:55.947  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:54:55.947  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:54:55.947  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:54:55.947  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
,08-19 17:54:55.947  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:54:55.947  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:54:55.947  6361  6416 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
,08-19 17:54:55.947  6361  6416 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native,
08-19 17:54:55.947  6361  6416 I jxcore-log: 
,08-19 17:54:55.947  6361  6416 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native,
08-19 17:54:55.947  6361  6416 I jxcore-log: 
,08-19 17:54:56.607  6361  6416 D ExecuteNativeTests: Running unit tests,
,08-19 17:54:56.687  6361  6416 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-19 17:54:56.687  6361  6416 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b1c5ad1 added. We now have 2 listener(s)
,08-19 17:54:56.697  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-19 17:54:56.697  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-19 17:54:56.697  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-19 17:54:56.697  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:54:56.697  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d648936 added. We now have 2 listener(s)
08-19 17:54:56.697  6361  6416 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-19 17:54:56.697  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-19 17:54:56.697  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-19 17:54:56.697  6361  6416 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-19 17:54:56.697  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:54:56.697  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:54:56.697  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:54:56.697  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:54:56.697  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:54:56.697  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:54:56.697  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:54:56.697  6361  6416 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:54:56.697  6361  6416 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-19 17:54:56.707  6361  6361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:54:56.707  6361  6416 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-19 17:54:56.707  6361  6416 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-19 17:54:56.707  6361  6416 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-19 17:54:56.707  6361  6416 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-19 17:54:56.707  6361  6416 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-19 17:54:56.707  6361  6416 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-19 17:54:56.707  6361  6416 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-19 17:54:56.707  6361  6416 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-19 17:54:56.707  6361  6416 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-19 17:54:56.707  6361  6416 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:54:56.707  6361  6416 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-19 17:54:56.717  6361  6416 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:54:56.717  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:56.717  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-19 17:54:56.717  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-19 17:54:56.717  6361  6416 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b1c5ad1 removed from the list
08-19 17:54:56.717  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:54:56.717  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d648936 removed from the list
08-19 17:54:56.717  6361  6416 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:54:56.717  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:54:56.717  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:56.717  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:54:56.717  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-19 17:54:56.717  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:54:56.717  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-19 17:54:56.717  6361  6416 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d648936 not in the list
,08-19 17:54:56.717  6361  6416 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-19 17:54:56.717  6361  6416 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:54:56.717  6361  6416 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:54:56.717  6361  6416 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:54:56.717  6361  6416 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:54:56.717  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:56.717  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:54:56.717  6361  6416 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b1c5ad1 not in the list
08-19 17:54:56.717  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:54:56.717  6361  6416 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d648936 not in the list
08-19 17:54:56.717  6361  6416 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:54:56.717  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:56.717  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:54:56.717  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:56.717  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:54:56.717  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:54:56.717  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:54:56.717  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:54:56.717  6361  6416 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d648936 not in the list
,08-19 17:54:56.727  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-19 17:54:56.727  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-19 17:54:56.727  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-19 17:54:56.727  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-19 17:54:56.727  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-19 17:54:56.727  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-19 17:54:56.727  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-19 17:54:56.727  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-19 17:54:56.727  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-19 17:54:56.727  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-19 17:54:56.727  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-19 17:54:56.727  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-19 17:54:56.727  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-19 17:54:56.727  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-19 17:54:56.727  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-19 17:54:56.727  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-19 17:54:56.727  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-19 17:54:56.727  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-19 17:54:56.727  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-19 17:54:56.727  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-19 17:54:56.727  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-19 17:54:56.727  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-19 17:54:56.727  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-19 17:54:56.727  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-19 17:54:56.727  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-19 17:54:56.727  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-19 17:54:56.727  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-19 17:54:56.727  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no pe,er name> 36:2610:2610:2610:2610:2610]
08-19 17:54:56.727  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-19 17:54:56.727  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-19 17:54:56.727  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-19 17:54:56.727  6361  6416 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:54:56.727  6361  6416 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:54:56.727  6361  6416 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:54:56.727  6361  6416 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:54:56.727  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:56.727  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:54:56.727  6361  6416 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b1c5ad1 not in the list
08-19 17:54:56.727  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:54:56.727  6361  6416 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d648936 not in the list
08-19 17:54:56.727  6361  6416 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:54:56.727  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:56.727  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:54:56.727  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:56.727  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:54:56.727  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:54:56.727  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:54:56.727  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:54:56.727  6361  6416 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d648936 not in the list
08-19 17:54:56.727  6361  6416 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-19 17:54:56.727  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-19 17:54:56.727  6361  6416 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-19 17:54:56.727  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:54:56.727  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:54:56.727  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:54:56.727  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:54:56.727  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:54:56.727  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:54:56.727  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-19 17:54:56.727  6361  6416 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-19 17:54:56.727  6361  6416 D io.jxcore.node.ConnectivityMonitor: start: OK
08-19 17:54:56.727  6361  6416 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-19 17:54:56.727  6361  6416 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-19 17:54:56.727  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-19 17:54:56.727  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-19 17:54:56.727  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-19 17:54:56.737  6361  6361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:54:56.737  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-19 17:54:56.737  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-19 17:54:56.747  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-19 17:54:56.747  6361  6416 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-19 17:54:56.747  6361  6416 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-19 17:54:56.747  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-19 17:54:56.747  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-19 17:54:56.747  6361  6416 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-19 17:54:56.757  2760  2777 D BtGatt.GattService: registerClient() - UUID=7880000a-744b-4da2-8adb-db7291d78f99
,08-19 17:54:56.807  2760  2819 D BtGatt.GattService: onClientRegistered() - UUID=7880000a-744b-4da2-8adb-db7291d78f99, clientIf=6
,08-19 17:54:56.807  6361  6375 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-19 17:54:56.807  2760  2998 D BtGatt.GattService: start scan with filters
,08-19 17:54:56.807  2760  2999 D BtGatt.ScanManager: handling starting scan
,08-19 17:54:56.807  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-19 17:54:56.807  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-19 17:54:56.817  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-19 17:54:56.817  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-19 17:54:56.817  2760  2999 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@68341b0
,08-19 17:54:56.817  6361  6416 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-19 17:54:56.817  6361  6361 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-19 17:54:56.817  2760  2819 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-19 17:54:56.817  2760  2819 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-19 17:54:56.817  2760  2999 D BtGatt.ScanManager: allow scan with filters
,08-19 17:54:56.817  2760  2999 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-19 17:54:56.827  6361  6416 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-19 17:54:56.827  2760  2999 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-19 17:54:56.827  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-19 17:54:56.827  2760  2819 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-19 17:54:56.827  2760  2819 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-19 17:54:56.827  2760  2999 D BtGatt.ScanManager: Starting BLE batch scan
08-19 17:54:56.827  2760  2999 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-19 17:54:56.837  6361  6416 I io.jxcore.node.ConnectionHelper: start: OK,
08-19 17:54:56.837  2760  2819 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-19 17:54:56.837  2760  2819 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-19 17:54:56.837  6361  6416 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-19 17:54:56.837  6361  6416 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-19 17:54:56.837  2760  2819 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-19 17:54:56.837  2760  2819 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-19 17:54:56.837  6361  6416 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-19 17:54:56.837  6361  6416 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-19 17:54:56.837  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:56.837  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-19 17:54:56.837  6361  6416 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-19 17:54:56.837  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-19 17:54:56.837  6361  6416 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-19 17:54:56.837  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-19 17:54:56.847  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-19 17:54:56.847  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-19 17:54:56.847  2760  2777 D BtGatt.GattService: stopScan() - queue size =1
,08-19 17:54:56.847  2760  2998 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-19 17:54:56.847  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-19 17:54:56.847  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-19 17:54:56.847  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-19 17:54:56.847  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-19 17:54:56.847  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-19 17:54:56.847  6361  6416 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-19 17:54:56.847  2760  2999 D BtGatt.ScanManager: filter size is 1
08-19 17:54:56.847  2760  2999 D BtGatt.ScanManager: delete FilterIndex - 3
,08-19 17:54:56.857  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-19 17:54:56.857  6361  6416 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-19 17:54:56.857  2760  2819 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-19 17:54:56.857  2760  2819 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-19 17:54:56.857  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-19 17:54:56.857  2760  2999 D BtGatt.ScanManager: stopping BLe Batch
08-19 17:54:56.857  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-19 17:54:56.857  6361  6361 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-19 17:54:56.857  6361  6361 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-19 17:54:56.857  6361  6361 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-19 17:54:56.857  6361  6416 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:54:56.857  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:56.857  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-19 17:54:56.857  6361  6416 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b1c5ad1 not in the list
08-19 17:54:56.857  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:54:56.857  6361  6416 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d648936 not in the list
08-19 17:54:56.857  6361  6416 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:54:56.857  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:54:56.857  6361  6416 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-19 17:54:56.867  2760  2819 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-19 17:54:56.867  2760  2819 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-19 17:54:56.867  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-19 17:54:56.867  2760  2999 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-19 17:54:56.867  2760  2819 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-19 17:54:56.867  2760  2819 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-19 17:54:56.877  6361  6416 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-19 17:54:56.877  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:54:56.877  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:54:56.877  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:54:56.877  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:54:56.877  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:54:56.877  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:54:56.877  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-19 17:54:56.877  6361  6416 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-19 17:54:56.877  6361  6416 D io.jxcore.node.ConnectivityMonitor: start: OK
08-19 17:54:56.877  6361  6361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:54:56.877  6361  6416 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-19 17:54:56.877  6361  6416 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-19 17:54:56.877  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-19 17:54:56.877  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-19 17:54:56.877  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-19 17:54:56.887  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-19 17:54:56.887  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-19 17:54:56.887  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-19 17:54:56.897  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-19 17:54:56.897  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-19 17:54:56.897  6361  6416 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-19 17:54:56.897  2760  2998 D BtGatt.GattService: registerClient() - UUID=a9a18ca2-bc8b-4e25-b9d6-0e3b66503658
,08-19 17:54:56.947  2760  2819 D BtGatt.GattService: onClientRegistered() - UUID=a9a18ca2-bc8b-4e25-b9d6-0e3b66503658, clientIf=6
,08-19 17:54:56.947  6361  6375 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-19 17:54:56.947  2760  2770 D BtGatt.GattService: start scan with filters
,08-19 17:54:56.947  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-19 17:54:56.947  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-19 17:54:56.947  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-19 17:54:56.947  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-19 17:54:56.947  2760  2999 D BtGatt.ScanManager: handling starting scan
,08-19 17:54:56.957  6361  6416 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-19 17:54:56.957  6361  6361 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-19 17:54:56.957  2760  2819 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-19 17:54:56.957  2760  2819 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-19 17:54:56.957  2760  2999 D BtGatt.ScanManager: allow scan with filters
,08-19 17:54:56.957  2760  2999 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-19 17:54:56.957  2760  2999 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-19 17:54:56.957  6361  6416 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-19 17:54:56.957  2760  2819 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-19 17:54:56.967  2760  2819 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-19 17:54:56.967  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-19 17:54:56.967  2760  2999 D BtGatt.ScanManager: Starting BLE batch scan
08-19 17:54:56.967  2760  2999 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-19 17:54:56.967  2760  2819 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-19 17:54:56.967  2760  2819 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-19 17:54:56.977  6361  6416 I io.jxcore.node.ConnectionHelper: start: OK
,08-19 17:54:56.977  2760  2819 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-19 17:54:56.977  2760  2819 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-19 17:54:56.977  6361  6416 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-19 17:54:56.977  6361  6416 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-19 17:54:56.977  6361  6416 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-19 17:54:56.977  6361  6416 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-19 17:54:56.987  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-19 17:54:56.987  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-19 17:54:56.987  6361  6416 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-19 17:54:56.987  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-19 17:54:56.987  6361  6416 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-19 17:54:56.987  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-19 17:54:56.987  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-19 17:54:56.987  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-19 17:54:56.987  2760  2777 D BtGatt.GattService: stopScan() - queue size =1
,08-19 17:54:56.987  2760  2999 D BtGatt.ScanManager: filter size is 1
,08-19 17:54:56.987  2760  2999 D BtGatt.ScanManager: delete FilterIndex - 4
,08-19 17:54:56.987  2760  2998 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-19 17:54:56.987  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-19 17:54:56.987  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-19 17:54:56.987  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-19 17:54:56.987  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-19 17:54:56.987  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-19 17:54:56.997  2760  2819 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-19 17:54:56.997  2760  2819 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-19 17:54:56.997  6361  6416 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-19 17:54:56.997  2760  2999 D BtGatt.ScanManager: stopping BLe Batch
,08-19 17:54:56.997  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-19 17:54:56.997  6361  6416 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-19 17:54:56.997  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-19 17:54:56.997  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-19 17:54:56.997  6361  6361 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-19 17:54:56.997  6361  6361 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-19 17:54:56.997  6361  6416 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:54:56.997  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:56.997  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-19 17:54:56.997  6361  6416 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b1c5ad1 not in the list
08-19 17:54:56.997  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:54:56.997  6361  6416 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d648936 not in the list
08-19 17:54:56.997  6361  6416 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:54:56.997  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:54:57.007  6361  6361 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-19 17:54:57.007  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:57.007  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:54:57.007  2760  2819 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-19 17:54:57.007  2760  2819 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-19 17:54:57.007  2760  2999 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-19 17:54:57.007  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-19 17:54:57.007  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:54:57.007  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-19 17:54:57.007  2760  2819 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-19 17:54:57.007  2760  2819 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-19 17:54:57.007  6361  6416 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d648936 not in the list
08-19 17:54:57.007  6361  6416 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-19 17:54:57.007  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-19 17:54:57.017  6361  6416 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-19 17:54:57.017  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:54:57.017  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:54:57.017  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:54:57.017  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:54:57.017  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:54:57.017  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:54:57.017  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:54:57.017  6361  6416 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:54:57.017  6361  6416 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-19 17:54:57.017  6361  6361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:54:57.017  6361  6416 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-19 17:54:57.017  6361  6416 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-19 17:54:57.017  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-19 17:54:57.017  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-19 17:54:57.017  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-19 17:54:57.027  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-19 17:54:57.027  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-19 17:54:57.027  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-19 17:54:57.037  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-19 17:54:57.037  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-19 17:54:57.037  6361  6416 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-19 17:54:57.037  2760  2770 D BtGatt.GattService: registerClient() - UUID=fd8e48a0-306f-4d84-9f76-31f93eec1437
,08-19 17:54:57.077  2760  2819 D BtGatt.GattService: onClientRegistered() - UUID=fd8e48a0-306f-4d84-9f76-31f93eec1437, clientIf=6
,08-19 17:54:57.077  6361  6375 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-19 17:54:57.077  2760  2777 D BtGatt.GattService: start scan with filters
,08-19 17:54:57.077  2760  2999 D BtGatt.ScanManager: handling starting scan
,08-19 17:54:57.087  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-19 17:54:57.087  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-19 17:54:57.087  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-19 17:54:57.087  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-19 17:54:57.087  2760  2819 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-19 17:54:57.087  2760  2819 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-19 17:54:57.087  2760  2999 D BtGatt.ScanManager: allow scan with filters
08-19 17:54:57.087  2760  2999 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-19 17:54:57.087  2760  2999 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-19 17:54:57.087  2760  2819 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-19 17:54:57.087  2760  2819 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-19 17:54:57.087  2760  2999 D BtGatt.ScanManager: Starting BLE batch scan
08-19 17:54:57.087  2760  2999 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-19 17:54:57.087  2760  2819 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
08-19 17:54:57.087  2760  2819 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,08-19 17:54:57.097  2760  2819 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-19 17:54:57.097  2760  2819 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
08-19 17:54:57.097  6361  6416 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-19 17:54:57.097  6361  6416 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-19 17:54:57.097  6361  6361 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-19 17:54:57.097  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-19 17:54:57.107  6361  6416 I io.jxcore.node.ConnectionHelper: start: OK
,08-19 17:54:57.107  6361  6416 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-19 17:54:57.107  6361  6416 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-19 17:54:57.107  6361  6416 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-19 17:54:57.107  6361  6416 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-19 17:54:57.107  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-19 17:54:57.107  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-19 17:54:57.107  6361  6416 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-19 17:54:57.107  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
,08-19 17:54:57.107  6361  6416 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-19 17:54:57.107  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-19 17:54:57.107  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-19 17:54:57.107  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-19 17:54:57.117  2760  2770 D BtGatt.GattService: stopScan() - queue size =1,
,08-19 17:54:57.117  2760  2999 D BtGatt.ScanManager: filter size is 1
,08-19 17:54:57.117  2760  2999 D BtGatt.ScanManager: delete FilterIndex - 5
,08-19 17:54:57.117  2760  2998 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-19 17:54:57.117  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-19 17:54:57.117  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-19 17:54:57.117  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-19 17:54:57.117  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-19 17:54:57.117  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-19 17:54:57.117  6361  6416 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-19 17:54:57.117  2760  2819 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-19 17:54:57.117  2760  2819 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-19 17:54:57.117  2760  2999 D BtGatt.ScanManager: stopping BLe Batch
,08-19 17:54:57.117  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-19 17:54:57.117  6361  6416 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-19 17:54:57.117  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-19 17:54:57.127  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-19 17:54:57.127  6361  6361 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-19 17:54:57.127  6361  6361 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-19 17:54:57.127  6361  6361 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-19 17:54:57.127  6361  6416 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-19 17:54:57.127  6361  6416 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-19 17:54:57.127  6361  6416 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-19 17:54:57.127  6361  6416 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:54:57.127  2760  2819 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-19 17:54:57.127  6361  6416 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:54:57.127  2760  2819 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-19 17:54:57.127  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-19 17:54:57.127  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-19 17:54:57.127  6361  6416 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b1c5ad1 not in the list
08-19 17:54:57.127  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:54:57.127  6361  6416 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d648936 not in the list
,08-19 17:54:57.127  6361  6416 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:54:57.127  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:54:57.127  2760  2999 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-19 17:54:57.127  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:57.127  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:54:57.137  2760  2819 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-19 17:54:57.137  2760  2819 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-19 17:54:57.137  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:54:57.137  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:54:57.137  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:54:57.137  6361  6416 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d648936 not in the list
,08-19 17:54:57.137  6361  6416 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-19 17:54:57.137  6361  6416 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:54:57.137  6361  6416 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:54:57.137  6361  6416 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:54:57.137  6361  6416 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:54:57.137  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:57.137  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:54:57.137  6361  6416 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b1c5ad1 not in the list
08-19 17:54:57.137  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:54:57.137  6361  6416 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d648936 not in the list
08-19 17:54:57.137  6361  6416 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:54:57.137  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:57.137  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:54:57.137  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:57.137  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:54:57.137  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:54:57.137  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:54:57.137  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:54:57.137  6361  6416 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d648936 not in the list
,08-19 17:54:57.137  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-19 17:54:57.137  6361  6416 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:54:57.137  6361  6416 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:54:57.137  6361  6416 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:54:57.137  6361  6416 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:54:57.137  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:57.137  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:54:57.137  6361  6416 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b1c5ad1 not in the list
08-19 17:54:57.137  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:54:57.137  6361  6416 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d648936 not in the list
08-19 17:54:57.137  6361  6416 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:54:57.137  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:57.137  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:54:57.137  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:57.137  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:54:57.137  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:54:57.137  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:54:57.137  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:54:57.137  6361  6416 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d648936 not in the list
,08-19 17:54:57.137  6361  6416 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-19 17:54:57.137  6361  6416 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:54:57.137  6361  6416 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:54:57.137  6361  6416 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:54:57.137  6361  6416 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:54:57.137  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:57.137  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:54:57.137  6361  6416 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b1c5ad1 not in the list
08-19 17:54:57.137  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:54:57.137  6361  6416 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d648936 not in the list
08-19 17:54:57.137  6361  6416 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:54:57.137  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:57.137  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:54:57.137  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:57.137  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:54:57.137  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:54:57.137  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-19 17:54:57.137  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-19 17:54:57.137  6361  6416 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d648936 not in the list,
08-19 17:54:57.147  6361  6416 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,08-19 17:54:57.147  6361  6416 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
,08-19 17:54:57.147  6361  6416 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-19 17:54:57.147  6361  6416 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:54:57.147  6361  6416 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-19 17:54:57.147  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-19 17:54:57.147  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,08-19 17:54:57.147  6361  6416 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b1c5ad1 not in the list,
08-19 17:54:57.147  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-19 17:54:57.147  6361  6416 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d648936 not in the list
,08-19 17:54:57.147  6361  6416 D io.jxcore.node.ConnectivityMonitor: stop
,08-19 17:54:57.147  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-19 17:54:57.147  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:54:57.147  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-19 17:54:57.147  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:54:57.147  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:54:57.147  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:54:57.147  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-19 17:54:57.147  6361  6416 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d648936 not in the list
08-19 17:54:57.147  6361  6416 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-19 17:54:57.147  6361  6416 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-19 17:54:57.147  6361  6416 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-19 17:54:57.147  6361  6416 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-19 17:54:57.147  6361  6416 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-19 17:54:57.147  6361  6416 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-19 17:54:57.147  6361  6416 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:54:57.147  6361  6416 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:54:57.147  6361  6416 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:54:57.147  6361  6416 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-19 17:54:57.147  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:57.147  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:54:57.147  6361  6416 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b1c5ad1 not in the list
08-19 17:54:57.147  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:54:57.147  6361  6416 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d648936 not in the list
08-19 17:54:57.147  6361  6416 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:54:57.147  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:57.147  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:54:57.147  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:57.147  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:54:57.147  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:54:57.147  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:54:57.147  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:54:57.147  6361  6416 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d648936 not in the list
08-19 17:54:57.147  6361  6416 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-19 17:54:57.147  6361  6416 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-19 17:54:57.147  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-19 17:54:57.147  6361  6416 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-19 17:54:57.147  6361  6416 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-19 17:54:57.147  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-19 17:54:57.147  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-19 17:54:57.147  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-19 17:54:57.157  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-19 17:54:57.157  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-19 17:54:57.157  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-19 17:54:57.157  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-19 17:54:57.157  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-19 17:54:57.157  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-19 17:54:57.157  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-19 17:54:57.157  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-19 17:54:57.157  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-19 17:54:57.157  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-19 17:54:57.157  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-19 17:54:57.157  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-19 17:54:57.157  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-19 17:54:57.157  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-19 17:54:57.157  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-19 17:54:57.157  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-19 17:54:57.157  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-19 17:54:57.157  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-19 17:54:57.157  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-19 17:54:57.157  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-19 17:54:57.157  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-19 17:54:57.157  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-19 17:54:57.157  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-19 17:54:57.157  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-19 17:54:57.157  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-19 17:54:57.157  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Pee,r: [<no peer name> 38:2810:2810:2810:2810:2810]
08-19 17:54:57.157  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-19 17:54:57.157  6361  6416 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-19 17:54:57.157  6361  6416 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-19 17:54:57.157  6361  6416 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-19 17:54:57.157  6361  6416 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-19 17:54:57.157  6361  6416 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-19 17:54:57.157  6361  6416 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-19 17:54:57.157  6361  6416 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-19 17:54:57.157  6361  6416 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-19 17:54:57.157  6361  6416 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-19 17:54:57.157  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-19 17:54:57.157  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-19 17:54:57.157  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-19 17:54:57.157  6361  6416 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-19 17:54:57.157  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-19 17:54:57.157  6361  6416 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,08-19 17:54:57.157  6361  6416 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-19 17:54:57.157  6361  6416 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-19 17:54:57.157  6361  6416 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:54:57.157  6361  6416 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:54:57.157  6361  6416 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:54:57.157  6361  6416 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:54:57.157  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:57.157  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:54:57.157  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-19 17:54:57.157  6361  6416 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b1c5ad1 not in the list
08-19 17:54:57.157  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:54:57.157  6361  6416 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d648936 not in the list
08-19 17:54:57.157  6361  6416 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:54:57.157  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:57.157  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:54:57.157  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-19 17:54:57.157  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:54:57.157  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:54:57.157  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:54:57.157  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:54:57.157  6361  6416 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d648936 not in the list
08-19 17:54:57.157  6361  6427 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1235
,08-19 17:54:57.157  6361  6416 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-19 17:54:57.157  6361  6416 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:54:57.157  6361  6416 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:54:57.157  6361  6416 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:54:57.157  6361  6416 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:54:57.157  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:57.157  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:54:57.157  6361  6416 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b1c5ad1 not in the list,
08-19 17:54:57.157  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:54:57.157  6361  6416 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d648936 not in the list
08-19 17:54:57.157  6361  6416 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:54:57.157  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:57.157  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:54:57.157  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:57.157  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:54:57.167  6361  6426 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1235)
08-19 17:54:57.167  6361  6426 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1235)
08-19 17:54:57.167  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:54:57.167  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-19 17:54:57.167  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:54:57.167  6361  6416 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d648936 not in the list
08-19 17:54:57.167  6361  6416 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-19 17:54:57.167  6361  6416 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:54:57.167  6361  6416 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:54:57.167  6361  6416 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-19 17:54:57.167  6361  6416 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:54:57.167  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:57.167  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:54:57.167  6361  6416 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b1c5ad1 not in the list
08-19 17:54:57.167  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:54:57.167  6361  6416 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d648936 not in the list
08-19 17:54:57.167  6361  6416 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:54:57.167  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:57.167  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-19 17:54:57.167  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:57.167  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:54:57.167  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:54:57.167  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-19 17:54:57.167  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:54:57.167  6361  6416 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d648936 not in the list
08-19 17:54:57.167  6361  6416 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-19 17:54:57.167  6361  6416 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString,
08-19 17:54:57.167  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-19 17:54:57.167  6361  6416 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-19 17:54:57.167  6361  6416 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-19 17:54:57.167  6361  6416 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
,08-19 17:54:57.167  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-19 17:54:57.167  6361  6416 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-19 17:54:57.167  6361  6416 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-19 17:54:57.167  6361  6416 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,08-19 17:54:57.167  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-19 17:54:57.167  6361  6416 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-19 17:54:57.167  6361  6416 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:54:57.167  6361  6416 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:54:57.167  6361  6416 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-19 17:54:57.167  6361  6416 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:54:57.167  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:57.167  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:54:57.167  6361  6416 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b1c5ad1 not in the list,
08-19 17:54:57.167  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:54:57.167  6361  6416 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d648936 not in the list
08-19 17:54:57.167  6361  6416 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:54:57.167  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-19 17:54:57.167  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:54:57.167  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:57.167  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:54:57.167  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:54:57.167  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-19 17:54:57.167  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:54:57.167  6361  6416 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d648936 not in the list
08-19 17:54:57.167  6361  6416 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:54:57.167  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:57.167  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:54:57.167  6361  6416 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b1c5ad1 not in the list
08-19 17:54:57.167  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:54:57.167  6361  6416 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d648936 not in the list
08-19 17:54:57.167  6361  6416 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:54:57.167  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:57.167  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:54:57.167  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:54:57.167  6361  6416 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d648936 not in the list
08-19 17:54:57.167  6361  6416 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:54:57.167  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:57.167  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:54:57.167  6361  6416 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b1c5ad1 not in the list
08-19 17:54:57.167  6361  6416 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:54:57.167  6361  6416 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:54:57.167  6361  6416 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:54:57.167  6361  6416 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:54:57.167  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:57.167  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:54:57.167  6361  6416 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b1c5ad1 not in the list
08-19 17:54:57.167  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-19 17:54:57.167  6361  6416 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d648936 not in the list
08-19 17:54:57.167  6361  6416 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:54:57.167  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:57.167  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:54:57.167  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:57.167  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:54:57.167  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:54:57.167  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:54:57.167  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-19 17:54:57.167  6361  6416 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d648936 not in the list
08-19 17:54:57.177  6361  6416 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-19 17:54:57.177  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-19 17:54:57.177  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-19 17:54:57.177  6361  6416 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-19 17:54:57.177  6361  6416 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-19 17:54:57.177  6361  6416 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,08-19 17:54:57.177  6361  6416 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-19 17:54:57.177  6361  6361 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-19 17:54:57.177  6361  6416 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:54:57.177  6361  6416 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-19 17:54:57.177  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-19 17:54:57.177  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-19 17:54:57.177  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:54:57.177  6361  6416 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-19 17:54:57.177  6361  6416 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b1c5ad1 not in the list
08-19 17:54:57.177  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:54:57.177  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-19 17:54:57.177  6361  6361 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-19 17:54:57.177  6361  6416 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-19 17:54:57.177  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-19 17:54:57.177  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:57.177  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:54:57.177  6361  6416 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-19 17:54:57.177  6361  6361 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-19 17:54:57.177  6361  6361 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-19 17:54:57.177  6361  6361 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-19 17:54:57.177  6361  6416 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d648936 not in the list
08-19 17:54:57.177  6361  6416 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-19 17:54:57.177  6361  6416 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:54:57.177  6361  6416 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:54:57.177  6361  6416 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:54:57.177  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:57.177  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:54:57.177  6361  6428 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,08-19 17:54:57.177  6361  6428 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-19 17:54:57.177  6361  6361 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-19 17:54:57.177  6361  6416 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b1c5ad1 not in the list
08-19 17:54:57.177  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:54:57.177  6361  6416 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d648936 not in the list
,08-19 17:54:57.177  6361  6416 D io.jxcore.node.ConnectivityMonitor: stop,
08-19 17:54:57.177  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:57.177  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:54:57.177  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:57.177  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:54:57.177  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:54:57.177  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-19 17:54:57.177  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:54:57.177  6361  6416 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d648936 not in the list
08-19 17:54:57.187  6361  6416 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-19 17:54:57.187  6361  6416 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-19 17:54:57.187  6361  6416 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-19 17:54:57.187  6361  6416 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-19 17:54:57.187  6361  6416 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:54:57.187  6361  6416 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-19 17:54:57.187  6361  6416 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:54:57.187  6361  6416 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:54:57.187  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:57.187  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:54:57.187  6361  6416 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b1c5ad1 not in the list
08-19 17:54:57.187  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:54:57.187  6361  6416 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d648936 not in the list
08-19 17:54:57.187  6361  6416 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:54:57.187  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:57.187  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:54:57.187  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:57.187  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:54:57.187  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:54:57.187  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-19 17:54:57.187  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:54:57.187  6361  6416 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d648936 not in the list
,08-19 17:54:57.187  6361  6416 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:54:57.187  6361  6416 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:54:57.187  6361  6416 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-19 17:54:57.187  6361  6416 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:54:57.187  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:57.187  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:54:57.187  6361  6416 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b1c5ad1 not in the list
08-19 17:54:57.187  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:54:57.187  6361  6416 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d648936 not in the list
08-19 17:54:57.187  6361  6416 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:54:57.187  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:57.187  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:54:57.187  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:57.187  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:54:57.187  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:54:57.187  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:54:57.187  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:54:57.187  6361  6416 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d648936 not in the list
,08-19 17:54:57.187  6361  6416 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:54:57.187  6361  6416 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:54:57.187  6361  6416 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:54:57.187  6361  6416 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:54:57.187  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:57.187  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:54:57.187  6361  6416 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b1c5ad1 not in the list
08-19 17:54:57.187  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:54:57.187  6361  6416 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d648936 not in the list
08-19 17:54:57.187  6361  6416 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:54:57.187  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:57.187  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:54:57.187  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:54:57.187  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:54:57.187  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:54:57.187  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:54:57.187  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:54:57.187  6361  6416 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d648936 not in the list
,08-19 17:54:57.187  6361  6416 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-19 17:54:57.187  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-19 17:54:57.197  6361  6416 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-19 17:54:57.197  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-19 17:54:57.197  6361  6416 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-19 17:54:57.197  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-19 17:54:57.197  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-19 17:54:57.197  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-19 17:54:57.197  6361  6416 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-19 17:54:57.197  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-19 17:54:57.197  6361  6416 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-19 17:54:57.197  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-19 17:54:57.197  6361  6416 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-19 17:54:57.197  6361  6416 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-19 17:54:57.197  6361  6416 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-19 17:54:57.197  6361  6416 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-19 17:54:57.197  6361  6416 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-19 17:54:57.197  6361  6416 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-19 17:54:57.197  6361  6416 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-19 17:54:57.197  6361  6416 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-19 17:54:57.197  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:54:57.197  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@31bf2d28 added. We now have 2 listener(s)
08-19 17:54:57.197  6361  6416 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-19 17:54:57.197  6361  6416 D BluetoothAdapter: enable()
,08-19 17:54:57.197  6361  6416 D BluetoothAdapter: enable(): BT is already enabled..!
,08-19 17:54:57.197  1021  4073 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-19 17:54:57.207  1021  4073 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-19 17:54:57.207  1021  4073 D SecContentProvider2: mCursor = null
,08-19 17:54:57.207  1021  4073 D WifiService: setWifiEnabled: true pid=6361, uid=10170
08-19 17:54:57.207  1021  4073 W ActivityManager: Permission Denial: getCurrentUser() from pid=6361, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-19 17:54:57.217  1021  4073 W WifiService: Failed getting userId using ActivityManagerNative
08-19 17:54:57.217  1021  4073 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6361, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-19 17:54:57.217  1021  4073 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-19 17:54:57.217  1021  4073 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-19 17:54:57.217  1021  4073 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-19 17:54:57.217  1021  4073 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-19 17:54:57.217  1021  4073 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-19 17:54:57.217  1021  4073 D SettingsProvider: name = wifi_on
,08-19 17:54:57.217  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:54:57.217  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3189a41 added. We now have 3 listener(s)
08-19 17:54:57.217  6361  6416 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-19 17:54:57.217  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:54:57.217  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1fbfabe6 added. We now have 4 listener(s)
08-19 17:54:57.217  6361  6416 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-19 17:54:57.227  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:54:57.227  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4e07527 added. We now have 5 listener(s)
08-19 17:54:57.227  6361  6416 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-19 17:54:57.227  1021  1499 D SecContentProvider: uri = 18 selection = isWifiEnabled,
,08-19 17:54:57.227  1021  1499 D WifiService: setWifiEnabled: false pid=6361, uid=10170,
08-19 17:54:57.227  1021  1499 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-19 17:54:57.227  1021  1499 D SecContentProvider2: mCursor = null
08-19 17:54:57.227  1021  1499 D SettingsProvider: name = wifi_on
08-19 17:54:57.227  6361  6416 D BluetoothAdapter: disable()
,08-19 17:54:57.237  1021  1129 D WifiP2pService: InactiveState{ what=131204 }
,08-19 17:54:57.237  1021  1129 D WifiP2pService: P2pEnabledState{ what=131204 }
,08-19 17:54:57.237  1021  1021 D WifiScanningService: SCAN_AVAILABLE : 1
08-19 17:54:57.237  1021  1153 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:54:57.237  1021  1021 D RttService: SCAN_AVAILABLE : 1
08-19 17:54:57.237  1021  1154 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:54:57.237  1021  1129 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-19 17:54:57.237  1021  1132 E ConnectivityService: updateNetworkInfo()
08-19 17:54:57.237  1021  1132 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-19 17:54:57.237  1021  3874 D SettingsProvider: name = bluetooth_on
,08-19 17:54:57.237  1021  1051 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-19 17:54:57.237  1021  1051 D WifiDisplayAdapter: onP2pDisconnected
,08-19 17:54:57.237  1021  1051 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-19 17:54:57.237  1021  1051 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-19 17:54:57.247  4447  4447 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-19 17:54:57.247  1021  1129 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-19 17:54:57.247  1021  1132 E ConnectivityService: updateNetworkInfo()
08-19 17:54:57.247  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-19 17:54:57.247  2760  2816 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
08-19 17:54:57.247  2760  2816 D BluetoothAdapterProperties: Setting state to 13
08-19 17:54:57.247  2760  2816 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-19 17:54:57.247  2760  2816 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-19 17:54:57.247  1021  1129 D WifiP2pService: P2pDisablingState
08-19 17:54:57.247  2760  2816 D BluetoothAdapterService: updateAdapterState state is 13
08-19 17:54:57.247  1021  1129 D WifiP2pService: P2pDisablingState{ what=147458 }
08-19 17:54:57.247  1021  1021 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-19 17:54:57.247  1021  1129 D WifiP2pService: p2p socket connection lost
08-19 17:54:57.247  1021  1129 D WifiP2pService: P2pDisabledState
08-19 17:54:57.247   277  1008 D CommandListener: Clearing all IP addresses on wlan0
,08-19 17:54:57.257  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:54:57.257  1021  1051 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,08-19 17:54:57.257  6361  6416 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-19 17:54:57.257  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:54:57.257  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:54:57.257  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:54:57.257  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-19 17:54:57.257  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:54:57.257  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:54:57.257  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-19 17:54:57.257  1021  1051 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-19 17:54:57.257  4447  4447 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-19 17:54:57.257  1021  1051 D WifiDisplayController: disconnect
08-19 17:54:57.257  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:54:57.257  1021  1051 D WifiDisplayController: updateConnection
08-19 17:54:57.257  6361  6416 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-19 17:54:57.257  1021  1051 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-19 17:54:57.257  6361  6416 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-19 17:54:57.257  1021  1051 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-19 17:54:57.257  1021  1524 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:54:57.257  1021  1524 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-19 17:54:57.257  1021  1524 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:54:57.257  1021  1524 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:54:57.257  1021  1524 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:54:57.257  2760  2760 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
08-19 17:54:57.257  1021  1051 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-19 17:54:57.257  1021  1051 D WifiDisplayAdapter: onP2pDisconnected
08-19 17:54:57.257  1021  1051 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-19 17:54:57.257  2760  2816 D BluetoothAdapterService: Autoconnection is available 
08-19 17:54:57.257  1021  1051 D IpRemoteDisplayController: WfdBridgeServer is already null
08-19 17:54:57.257  2760  2816 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-19 17:54:57.257  2760  2816 D BluetoothAdapterService: terminating service from this receiver
,08-19 17:54:57.257  2760  2760 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@15aa1e70, channel: 19, state: LISTENING
08-19 17:54:57.257  2760  2760 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@15aa1e70, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@397f9d3b, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@95545e9mSocket: android.net.LocalSocket@2fd1f26e impl:android.net.LocalSocketImpl@355ed0f fd:FileDescriptor[80]
08-19 17:54:57.257  2760  2760 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2fd1f26e impl:android.net.LocalSocketImpl@355ed0f fd:FileDescriptor[80]
08-19 17:54:57.257  6361  6361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:54:57.257  4447  4447 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-19 17:54:57.257  4447  4447 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-19 17:54:57.257  4447  4447 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-19 17:54:57.257  4447  4447 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-19 17:54:57.267  1179  1179 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-19 17:54:57.267  4447  4522 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-19 17:54:57.267  1021  1524 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-19 17:54:57.267  1021  1125 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-19 17:54:57.267  1021  1125 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:54:57.267  1021  1125 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:54:57.267  1021  1125 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-19 17:54:57.267  1179  1179 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-19 17:54:57.267  2760  2816 D BluetoothAdapterProperties: onBluetoothDisable()
08-19 17:54:57.267  2760  2816 D BluetoothAdapterProperties: mDiscovering is false
,08-19 17:54:57.267  1021  3874 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-19 17:54:57.267  2760  2816 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-19 17:54:57.267  1021  1546 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
08-19 17:54:57.267  4447  4447 D BluetoothPbap: Proxy object disconnected
08-19 17:54:57.267  4447  4447 D PbapServerProfile: Bluetooth service disconnected
,08-19 17:54:57.267  1021  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:54:57.267  1021  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:54:57.267  1021  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:54:57.267  1021  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:54:57.287  6431  6431 E Zygote  : MountEmulatedStorage(),
08-19 17:54:57.287  6431  6431 E Zygote  : v2,
08-19 17:54:57.287  6431  6431 I libpersona: KNOX_SDCARD checking this for 10064,
08-19 17:54:57.287  6431  6431 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-19 17:54:57.287  6431  6431 I libpersona: KNOX_SDCARD not a persona
08-19 17:54:57.287  6431  6431 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-19 17:54:57.287  1021  1546 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6431 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-19 17:54:57.287  2760  2819 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-19 17:54:57.287  2760  2819 D BluetoothAdapterProperties: Scan Mode:20
,08-19 17:54:57.297  6431  6431 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-19 17:54:57.297  1021  1021 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-19 17:54:57.297  1345  1345 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-19 17:54:57.297  1021  1021 D LightsService: [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1021) 
,08-19 17:54:57.297  1021  1021 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x10 | SvcLED(id=4) set Off
,08-19 17:54:57.297  6361  6361 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:54:57.297  6361  6361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:54:57.297  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:54:57.297  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:54:57.297  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:54:57.297  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-19 17:54:57.297  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:54:57.297  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:54:57.297  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:54:57.297  6361  6361 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:54:57.297  6361  6361 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:54:57.297  1021  1081 D LightsService: [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
08-19 17:54:57.297  1021  1081 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,08-19 17:54:57.307  2760  2816 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-19 17:54:57.307  2760  2816 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-19 17:54:57.307  6361  6361 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:54:57.307  6361  6361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:54:57.307  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:54:57.307  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:54:57.307  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-19 17:54:57.307  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-19 17:54:57.307  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:54:57.307  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:54:57.307  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-19 17:54:57.307  2760  2816 E bt-btif : cmd socket is not created
08-19 17:54:57.307  2760  2820 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
08-19 17:54:57.307  2760  4955 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-19 17:54:57.307  6361  6361 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:54:57.307  6361  6361 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:54:57.317  2760  2816 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-19 17:54:57.317  1179  1179 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-19 17:54:57.317  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-19 17:54:57.317  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-19 17:54:57.317  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:54:57.317  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:54:57.317  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:54:57.317  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:54:57.317  1179  1179 D PersonaManager: isKioskContainerExistOnDevice
08-19 17:54:57.317  1179  1179 D PersonaManager: isKioskContainerExistOnDevice
,08-19 17:54:57.327  1179  1179 D PanelView: There is/are notification(s) 
08-19 17:54:57.327  1179  1179 D PanelView: kidsfalse mQsExpansionEnabled:true,
,08-19 17:54:57.327  4447  4447 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-19 17:54:57.327  1179  1179 D PersonaManager: isKioskContainerExistOnDevice
,08-19 17:54:57.327  1179  1179 D PanelView: There is/are notification(s) 
08-19 17:54:57.327  1179  1179 D PanelView: kidsfalse mQsExpansionEnabled:true
08-19 17:54:57.327  1021  1021 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-19 17:54:57.327  1021  1021 I InputMethodManagerService: [BT Setting State] State =13
,08-19 17:54:57.327  6361  6361 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:54:57.327  6361  6361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:54:57.327  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:54:57.327  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:54:57.327  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-19 17:54:57.327  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-19 17:54:57.327  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:54:57.327  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:54:57.327  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:54:57.327  6361  6361 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:54:57.327  6361  6361 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:54:57.337  6361  6361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:54:57.337  1179  1179 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-19 17:54:57.337  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-19 17:54:57.337  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-19 17:54:57.337  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-19 17:54:57.337  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:54:57.337  1179  1179 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-19 17:54:57.337  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:54:57.337  1179  1700 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-19 17:54:57.337  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-19 17:54:57.337  1179  1179 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-19 17:54:57.337  1179  1179 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-19 17:54:57.337  1179  1179 D HotspotTile: onReceive : 0, 0
,08-19 17:54:57.337  1935  1935 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-19 17:54:57.347  1179  1179 D BluetoothTile:  onBluetoothStateChange:
,08-19 17:54:57.347  1179  1179 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-19 17:54:57.347  1179  1179 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:54:57.347  1179  1179 D BluetoothTile:  getBluetoothState : 13
,08-19 17:54:57.347  4447  4447 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-19 17:54:57.347  2760  2820 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-19 17:54:57.347  2760  2820 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-19 17:54:57.347  2760  2820 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-19 17:54:57.347  2760  2820 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-19 17:54:57.347  2760  2820 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-19 17:54:57.347  2760  2820 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-19 17:54:57.347  2760  2760 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@43357a5, channel: 5, state: LISTENING
08-19 17:54:57.347  2760  2760 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@43357a5, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@33e01c58, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1d2ec77amSocket: android.net.LocalSocket@300e4b2b impl:android.net.LocalSocketImpl@1f3f4b88 fd:FileDescriptor[82]
08-19 17:54:57.347  2760  2760 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@300e4b2b impl:android.net.LocalSocketImpl@1f3f4b88 fd:FileDescriptor[82]
,08-19 17:54:57.347  2760  2760 I BtOppRfcommListener: stopping Accept Thread
08-19 17:54:57.347  2760  2760 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@a26c921, channel: 12, state: LISTENING
08-19 17:54:57.347  2760  2760 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@a26c921, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@117678b3, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1451e146mSocket: android.net.LocalSocket@1ba46f07 impl:android.net.LocalSocketImpl@5419834 fd:FileDescriptor[85]
08-19 17:54:57.347  2760  2760 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1ba46f07 impl:android.net.LocalSocketImpl@5419834 fd:FileDescriptor[85]
08-19 17:54:57.347  2760  4955 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-19 17:54:57.347  1179  1700 D BluetoothTile:  handleUpdatestate:false name:null
,08-19 17:54:57.357  6361  6361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:54:57.357  6431  6431 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-19 17:54:57.357  6431  6431 D ActivityThread: Added TimaKeyStore provider
,08-19 17:54:57.357  2760  2760 V BluetoothOppManager: cleanUp...
,08-19 17:54:57.357  1021  1508 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-19 17:54:57.357  6361  6361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:54:57.357  1179  1179 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-19 17:54:57.357  1021  4075 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-19 17:54:57.357  1179  1179 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-19 17:54:57.357  1179  1700 D BluetoothTile:  handleUpdatestate:false name:null
,08-19 17:54:57.367  1179  1700 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-19 17:54:57.367  6431  6431 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-19 17:54:57.387  6431  6431 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-19 17:54:57.387  6431  6431 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-19 17:54:57.397  1179  1179 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,08-19 17:54:57.417  1345  1345 I wpa_supplicant: Blacklist: Clear (all) 
,08-19 17:54:57.417  6431  6431 D FileShare-Client: Outbound.stopDelayTimer - 
,08-19 17:54:57.417  1021  1728 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-19 17:54:57.417  1021  1728 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:54:57.417  1021  1728 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:54:57.417  1021  1728 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:54:57.417  1021  1728 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:54:57.437  6447  6447 E Zygote  : MountEmulatedStorage()
,08-19 17:54:57.437  6447  6447 E Zygote  : v2
08-19 17:54:57.437  6447  6447 I libpersona: KNOX_SDCARD checking this for 10065
08-19 17:54:57.437  6447  6447 I libpersona: KNOX_SDCARD not a persona
,08-19 17:54:57.437  6447  6447 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-19 17:54:57.447  6447  6447 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-19 17:54:57.447  1021  1728 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6447 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-19 17:54:57.447  6447  6447 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-19 17:54:57.447  1021  1728 I ActivityManager: Killing 5571:com.samsung.android.sm/1000 (adj 15): empty #21,
,08-19 17:54:57.457  1345  1345 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-19 17:54:57.457  1021  1048 D Tethering: interfaceLinkStateChanged p2p0, false
08-19 17:54:57.457  1345  1345 I wpa_supplicant: wlan0: State: SCANNING -> DISCONNECTED
,08-19 17:54:57.457  1021  1048 D Tethering: interfaceStatusChanged p2p0, false
08-19 17:54:57.457  1021  1048 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-19 17:54:57.467  1345  1345 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,08-19 17:54:57.477  6447  6447 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-19 17:54:57.477  6447  6447 D ActivityThread: Added TimaKeyStore provider
,08-19 17:54:57.507  6447  6447 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-19 17:54:57.507  2760  2816 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-19 17:54:57.507  2760  2816 D BtConfig.SecureMode: isSecureModeOn:false
08-19 17:54:57.507  2760  2816 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-19 17:54:57.507  2760  2816 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
08-19 17:54:57.507  2760  2816 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
08-19 17:54:57.507  2760  2816 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-19 17:54:57.507  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-19 17:54:57.507  2760  2816 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-19 17:54:57.507  1021  1499 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:54:57.507  1021  1499 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-19 17:54:57.517  1021  1499 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:54:57.517  1021  1499 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:54:57.517  1021  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:54:57.517  2760  2816 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-19 17:54:57.517  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-19 17:54:57.517  2760  2760 D HeadsetService: Received stop request...Stopping profile...
,08-19 17:54:57.517  2760  2816 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-19 17:54:57.517  1021  1034 I ActivityManager: Killing 5168:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
,08-19 17:54:57.517  2760  2760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@68341b0
08-19 17:54:57.517  1021  1508 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:54:57.517  4447  4447 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-19 17:54:57.517  1021  1508 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-19 17:54:57.527  4447  4447 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-19 17:54:57.527  1021  1508 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:54:57.527  1021  1508 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-19 17:54:57.527  1021  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-19 17:54:57.527  2760  2816 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-19 17:54:57.527  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-19 17:54:57.527  4447  4447 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-19 17:54:57.527  2760  2816 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-19 17:54:57.527  1021  1021 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-19 17:54:57.527  1021  1033 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:54:57.527  1021  1033 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-19 17:54:57.527  4447  4447 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-19 17:54:57.527  4447  4447 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-19 17:54:57.527  4447  4447 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-19 17:54:57.527  4447  4522 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-19 17:54:57.527  4447  4447 D HeadsetProfile: Bluetooth service disconnected
,08-19 17:54:57.527  1021  1033 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:54:57.527  1021  1033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:54:57.527  1021  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-19 17:54:57.527  2760  2816 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-19 17:54:57.527  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-19 17:54:57.537  2760  2816 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-19 17:54:57.537  1021  1498 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:54:57.537  1021  1498 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-19 17:54:57.537  6431  6431 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-19 17:54:57.537  1021  1498 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:54:57.537  6431  6431 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-19 17:54:57.537  6431  6431 D FileShare-Client: Outbound.stopDelayTimer - 
08-19 17:54:57.537  1021  1498 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:54:57.537  1021  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-19 17:54:57.537  2760  2816 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-19 17:54:57.537  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-19 17:54:57.537  2760  2816 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-19 17:54:57.547  1021  4073 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:54:57.547  1021  4073 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-19 17:54:57.547  1021  4073 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:54:57.547  1021  4073 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:54:57.547  1021  4073 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-19 17:54:57.547  2760  2816 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-19 17:54:57.547  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-19 17:54:57.547  2760  2816 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-19 17:54:57.547  1021  1033 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:54:57.547  1021  1033 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-19 17:54:57.547  1021  1033 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:54:57.547  1021  1033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:54:57.547  1021  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:54:57.557  2760  2816 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-19 17:54:57.557  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-19 17:54:57.557  6447  6447 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-19 17:54:57.557  2760  2816 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-19 17:54:57.557  1021  1225 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:54:57.557  1021  1225 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-19 17:54:57.557  1021  1225 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:54:57.557  1021  1225 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:54:57.557  1021  1225 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-19 17:54:57.557  2760  2816 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-19 17:54:57.557  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-19 17:54:57.557  2760  2816 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-19 17:54:57.557  2760  2816 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-19 17:54:57.557  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-19 17:54:57.557  2760  2816 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-19 17:54:57.557  2760  2816 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-19 17:54:57.557  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-19 17:54:57.557  2760  2816 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-19 17:54:57.557  2760  2816 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-19 17:54:57.557  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-19 17:54:57.557  2760  2816 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-19 17:54:57.557  2760  2816 D BluetoothAdapterState: Stopping profile services that were post enabled
08-19 17:54:57.557  2760  2760 E BluetoothAdapterService(109265328): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-19 17:54:57.557  2760  2760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-19 17:54:57.557  2760  2760 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-19 17:54:57.557  2760  2760 D A2dpService: Received stop request...Stopping profile...
08-19 17:54:57.557  2760  3073 D A2dpStateMachine: Exit Disconnected: -1
,08-19 17:54:57.567  1021  1524 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-19 17:54:57.567  2760  2760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@68341b0
,08-19 17:54:57.567  1021  1524 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-19 17:54:57.567  1021  1524 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:54:57.567  1021  1524 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:54:57.567  1021  1524 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-19 17:54:57.567  1631  1631 I Hs20UtilService: Starting #4
,08-19 17:54:57.567  1021  1021 D BluetoothA2dp: Proxy object disconnected
08-19 17:54:57.567  1021  1021 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-19 17:54:57.567  1631  1654 I Hs20UtilService: Message received 5007
,08-19 17:54:57.567  4447  4447 D BluetoothA2dp: Proxy object disconnected
08-19 17:54:57.567  4447  4447 D A2dpProfile: Bluetooth service disconnected
,08-19 17:54:57.577  4447  4447 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-19 17:54:57.577  2760  2760 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-19 17:54:57.577  2760  2760 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-19 17:54:57.577  4447  4447 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-19 17:54:57.577  2760  2760 D HidService: Received stop request...Stopping profile...
08-19 17:54:57.577  2760  2760 D HidService: Stopping Bluetooth HidService
08-19 17:54:57.577  2760  2760 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-19 17:54:57.577  2760  2760 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-19 17:54:57.577  2760  2760 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-19 17:54:57.577  2760  2760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@68341b0
,08-19 17:54:57.577  4447  4447 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-19 17:54:57.577  2760  2760 D HealthService: Received stop request...Stopping profile...
08-19 17:54:57.577  2760  2760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@68341b0
,08-19 17:54:57.577  2760  2760 D PanService: Received stop request...Stopping profile...
,08-19 17:54:57.577  2760  2760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@68341b0
,08-19 17:54:57.577  1021  1021 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-19 17:54:57.587  4447  4447 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-19 17:54:57.587  4447  4447 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-19 17:54:57.587  4447  4447 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-19 17:54:57.587  2760  2760 D BluetoothMapService: Received stop request...Stopping profile...
08-19 17:54:57.587  4447  4447 D BluetoothInputDevice: Proxy object disconnected
08-19 17:54:57.587  4447  4447 D HidProfile: Bluetooth service disconnected
08-19 17:54:57.587  4447  4522 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-19 17:54:57.587  4447  4447 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-19 17:54:57.587  4447  4447 D PanProfile: Bluetooth service disconnected
,08-19 17:54:57.587  2760  2760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@68341b0
,08-19 17:54:57.587  2760  2760 D SapService: Received stop request...Stopping profile...
08-19 17:54:57.587  2760  2760 D SapService: Stopping Bluetooth SapService
08-19 17:54:57.587  2760  2760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@68341b0
,08-19 17:54:57.587  4447  4447 D BluetoothMap: Proxy object disconnected
08-19 17:54:57.587  4447  4447 D MapProfile: Bluetooth service disconnected
08-19 17:54:57.587  4447  4447 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-19 17:54:57.587  4447  4447 D SapProfile: Bluetooth service disconnected
,08-19 17:54:57.597  2760  2760 E BluetoothAdapterService(109265328): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-19 17:54:57.597  2760  2760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-19 17:54:57.597  2760  2760 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-19 17:54:57.597  2760  2760 D BluetoothA2dp: Proxy object disconnected
08-19 17:54:57.597  2760  2760 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-19 17:54:57.597  2760  3074 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-19 17:54:57.597  2760  2760 I GKI_LINUX: GKI_exit_task 2 done
08-19 17:54:57.597  2760  2760 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-19 17:54:57.597  2760  2760 E BluetoothAdapterService(109265328): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-19 17:54:57.597  2760  2760 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-19 17:54:57.597  2760  2760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-19 17:54:57.597  2760  2760 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-19 17:54:57.597  2760  2760 E BluetoothAdapterService(109265328): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-19 17:54:57.597  2760  2760 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-19 17:54:57.597  2760  2760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-19 17:54:57.597  2760  2760 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-19 17:54:57.597  2760  2760 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-19 17:54:57.597  2760  2760 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-19 17:54:57.597  2760  2760 E BluetoothAdapterService(109265328): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-19 17:54:57.597  2760  2760 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-19 17:54:57.597  1021  1546 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-19 17:54:57.597  2760  2760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-19 17:54:57.597  1021  1546 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-19 17:54:57.597  2760  2760 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-19 17:54:57.597  2760  2760 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-19 17:54:57.597  2760  2760 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-19 17:54:57.597  2760  2760 E BluetoothAdapterService(109265328): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-19 17:54:57.597  2760  2760 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-19 17:54:57.597  1021  1546 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:54:57.597  2760  2760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-19 17:54:57.597  1021  1546 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:54:57.597  1021  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20set,tings, destAppInfo.processName = com.samsung.hs20settings
08-19 17:54:57.597  2760  2760 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-19 17:54:57.597  2760  2760 E BluetoothAdapterService(109265328): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-19 17:54:57.597  2760  2760 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-19 17:54:57.597  2760  2760 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-19 17:54:57.597  2760  2760 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
08-19 17:54:57.597  1631  1631 I Hs20UtilService: Starting #5
08-19 17:54:57.597  2760  2816 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-19 17:54:57.597  2760  2816 D BluetoothAdapterProperties: Setting state to 10
08-19 17:54:57.597  2760  2816 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-19 17:54:57.597  1631  1654 I Hs20UtilService: Message received 5011
08-19 17:54:57.597  2760  2816 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-19 17:54:57.597  2760  2816 D BluetoothAdapterService: updateAdapterState state is 10
,08-19 17:54:57.597  4447  4455 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-19 17:54:57.597  2760  2816 D BluetoothAdapterService: Autoconnection is available 
08-19 17:54:57.597  2760  2816 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-19 17:54:57.597  2760  2816 I BluetoothAdapterState: Entering OffState
,08-19 17:54:57.597  4447  4457 D Bluetoothsap: onBluetoothStateChange: up=false
08-19 17:54:57.597  4447  4457 D Bluetoothsap: Unbinding service...
08-19 17:54:57.597  1021  4073 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,08-19 17:54:57.607  1345  1345 I wpa_supplicant: Blacklist: Clear (all) 
,08-19 17:54:57.607  1021  4073 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:54:57.607  1021  4073 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:54:57.607  1021  4073 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:54:57.607  1021  4073 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:54:57.617  6463  6463 E Zygote  : MountEmulatedStorage()
,08-19 17:54:57.617  6463  6463 E Zygote  : v2
08-19 17:54:57.617  6463  6463 I libpersona: KNOX_SDCARD checking this for 1000
08-19 17:54:57.617  6463  6463 I libpersona: KNOX_SDCARD not a persona
,08-19 17:54:57.627  6463  6463 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-19 17:54:57.627  1021  4073 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6463 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-19 17:54:57.627  6463  6463 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-19 17:54:57.627  6463  6463 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-19 17:54:57.627  1681  1783 D BluetoothAdapter: onBluetoothStateChange: up=false
08-19 17:54:57.627  1681  1783 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-19 17:54:57.627  1179  1192 D BluetoothAdapter: onBluetoothStateChange: up=false
08-19 17:54:57.627  1179  1192 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-19 17:54:57.627  1476  1725 D BluetoothAdapter: onBluetoothStateChange: up=false
08-19 17:54:57.627  1476  1725 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-19 17:54:57.637  2760  2998 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-19 17:54:57.637  4447  6462 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-19 17:54:57.637  1729  1741 D BluetoothAdapter: onBluetoothStateChange: up=false
08-19 17:54:57.637  1729  1741 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-19 17:54:57.637  4447  4455 D BluetoothAdapter: onBluetoothStateChange: up=false
08-19 17:54:57.637  4447  4455 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-19 17:54:57.637  6361  6375 D BluetoothAdapter: onBluetoothStateChange: up=false
08-19 17:54:57.637  6361  6375 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-19 17:54:57.637  6361  6375 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-19 17:54:57.637  6361  6375 D BluetoothLeAdvertiser: Exit stop advertising
08-19 17:54:57.637  6361  6375 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-19 17:54:57.637  6361  6375 D BluetoothLeScanner: Exiting stopAllScan
,08-19 17:54:57.637  1458  1466 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-19 17:54:57.637  1458  1466 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-19 17:54:57.637   306   306 I art     : Explicit concurrent mark sweep GC freed 8712(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 593us total 21.338ms
08-19 17:54:57.637  4447  6462 D BluetoothMap: onBluetoothStateChange: up=false
,08-19 17:54:57.647  1468  1746 D BluetoothAdapter: onBluetoothStateChange: up=false
08-19 17:54:57.647  1468  1746 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-19 17:54:57.647  2760  2770 D BluetoothAdapter: onBluetoothStateChange: up=false
08-19 17:54:57.647  2760  2770 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-19 17:54:57.647  1021  1050 D BluetoothAdapter: onBluetoothStateChange: up=false
08-19 17:54:57.647  1021  1050 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-19 17:54:57.647  1021  1050 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-19 17:54:57.647  4447  4455 D BluetoothPbap: onBluetoothStateChange: up=false
,08-19 17:54:57.647  1021  1021 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-19 17:54:57.647  1021  1021 I InputMethodManagerService: [BT Setting State] State =10
08-19 17:54:57.647  1021  1021 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-19 17:54:57.657  6463  6463 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-19 17:54:57.657  1179  1179 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-19 17:54:57.657  1179  1179 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:54:57.657  1179  1179 D BluetoothTile:  getBluetoothState : 10
08-19 17:54:57.657   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 681us total 17.835ms
,08-19 17:54:57.667  1935  1935 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0,
08-19 17:54:57.667  1021  1048 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-19 17:54:57.667  1345  1345 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-19 17:54:57.667  1021  1546 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-19 17:54:57.667  1021  1048 D Tethering: interfaceLinkStateChanged wlan0, false
08-19 17:54:57.667  1021  4073 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-19 17:54:57.667  1021  1048 D Tethering: interfaceStatusChanged wlan0, false
08-19 17:54:57.667  4447  4447 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:54:57.667  1179  1179 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-19 17:54:57.667  6463  6463 D ActivityThread: Added TimaKeyStore provider
,08-19 17:54:57.667  6361  6361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:54:57.667  6361  6361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:54:57.677   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 577us total 16.797ms
,08-19 17:54:57.677  6361  6361 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
,08-19 17:54:57.697  6463  6463 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-19 17:54:57.697  6463  6463 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-19 17:54:57.697  6463  6463 D SecurityLogAgent: StateMachine : Current State = 1
,08-19 17:54:57.697  6463  6463 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-19 17:54:57.707  1021  1728 I ActivityManager: Killing 6008:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
,08-19 17:54:57.717  4447  4447 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-19 17:54:57.717  1021  4075 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-19 17:54:57.717  1021  4075 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
08-19 17:54:57.717  1021  4075 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:54:57.717  1021  4075 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:54:57.717  1021  4075 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-19 17:54:57.717  1681  1681 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-19 17:54:57.727  4447  4447 D DockEventReceiver: finishStartingService: stopping service
,08-19 17:54:57.727  4447  4447 D BluetoothNotiBroadcastReceiver: onReceive
,08-19 17:54:57.727  1179  1179 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-19 17:54:57.727  1179  1179 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-19 17:54:57.727  1021  4074 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-19 17:54:57.727  1021  4074 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:54:57.727  1021  4074 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:54:57.727  1021  4074 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:54:57.727  1021  4074 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:54:57.747  6481  6481 E Zygote  : MountEmulatedStorage(),
,08-19 17:54:57.747  6481  6481 E Zygote  : v2,
08-19 17:54:57.747  6481  6481 I libpersona: KNOX_SDCARD checking this for 10055
,08-19 17:54:57.747  6481  6481 I libpersona: KNOX_SDCARD not a persona
,08-19 17:54:57.747  6481  6481 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-19 17:54:57.747  6481  6481 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-19 17:54:57.747  1021  4074 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6481 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
08-19 17:54:57.747  6481  6481 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-19 17:54:57.767  6481  6481 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-19 17:54:57.767  6481  6481 D ActivityThread: Added TimaKeyStore provider
,08-19 17:54:57.767  1021  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-19 17:54:57.767  6329  6329 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-19 17:54:57.767  1021  1130 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-19 17:54:57.777  1179  1179 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-19 17:54:57.777  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-19 17:54:57.787  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-19 17:54:57.787  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-19 17:54:57.787  1729  2156 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-19 17:54:57.787  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-19 17:54:57.787  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:54:57.787  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:54:57.787  1179  1179 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-19 17:54:57.787  1179  1179 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-19 17:54:57.787  1179  1179 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-19 17:54:57.787  4447  4447 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-19 17:54:57.787  1179  1700 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-19 17:54:57.787  6481  6481 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-19 17:54:57.787  1179  1179 D HotspotTile: onReceive : 1, 0
,08-19 17:54:57.787  6361  6361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:54:57.797  6361  6361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:54:57.817  6481  6481 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-19 17:54:57.817  6481  6481 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-19 17:54:57.817  6481  6481 D UserAnalysis: Create SecureDbHelper
,08-19 17:54:57.827  6481  6481 D IntelligenceServiceApplication: onCreate()
,08-19 17:54:57.827  1021  1225 I ActivityManager: Killing 6060:com.google.android.apps.docs/u0a87 (adj 15): empty #21
,08-19 17:54:57.837  1021  1499 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-19 17:54:57.837  1021  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:54:57.837  1021  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:54:57.837  1021  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:54:57.837  1021  1499 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:54:57.837  6481  6481 D IntelligenceServiceApplication: no applications having user consent for prediction,
,08-19 17:54:57.847  6496  6496 E Zygote  : MountEmulatedStorage(),
08-19 17:54:57.847  6496  6496 E Zygote  : v2
08-19 17:54:57.847  6496  6496 I libpersona: KNOX_SDCARD checking this for 10105
08-19 17:54:57.847  6496  6496 I libpersona: KNOX_SDCARD not a persona
08-19 17:54:57.857  6496  6496 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-19 17:54:57.857  1021  1499 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6496 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-19 17:54:57.857  1021  1034 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
08-19 17:54:57.857  6496  6496 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-19 17:54:57.857  6481  6481 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
08-19 17:54:57.857  6496  6496 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-19 17:54:57.867  6481  6481 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-19 17:54:57.867  6496  6496 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-19 17:54:57.867  6496  6496 D ActivityThread: Added TimaKeyStore provider
,08-19 17:54:57.967   256   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-19 17:54:57.967   256   520 W Vold    : Returning OperationFailed - no handler for errno 0
,08-19 17:54:57.967  6496  6515 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-19 17:54:57.977   256   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-19 17:54:57.977   256   520 W Vold    : Returning OperationFailed - no handler for errno 0
,08-19 17:54:57.977  6496  6515 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-19 17:54:58.117  6496  6496 D StrictMode: StrictMode policy violation; ~duration=134 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at java.io.File.exists(File.java:363)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-19 17:54:58.117  6496  6496 D StrictMode: StrictMode policy violation; ~duration=133 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-19 17:54:58.117  6496  6496 D StrictMode: StrictMode policy violation; ~duration=132 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gm,m.map.m.e.a(PG:1515)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-19 17:54:58.117  6496  6496 D StrictMode: StrictMode policy violation; ~duration=131 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.q.e.b(PG:170)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08,-19 17:54:58.117  6496  6496 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-19 17:54:58.117  6496  6496 D StrictMode: StrictMode policy violation; ~duration=129 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.q.k.d(PG:583)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.q.e.b(PG:170)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-19 17:54:58.117  6496  6496 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at java.io.File.exists(File.java:363)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-19 17:54:58.117  6496  6496 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at java.io.File.exists(File.java:363)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-19 17:54:58.117  1021  1546 I ActivityManager: Killing 5660:com.google.android.apps.plus/u0a117 (adj 15): empty #21
08-19 17:54:58.117  6496  6496 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-19 17:54:58.117  6496  6496 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-19 17:54:58.127  4447  4447 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-19 17:54:58.127  1021  4074 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-19 17:54:58.127  1021  4074 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
08-19 17:54:58.127  1021  4074 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:54:58.127  1021  4074 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:54:58.127  1021  4074 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
08-19 17:54:58.137  1681  1681 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-19 17:54:58.137  4447  4447 D DockEventReceiver: finishStartingService: stopping service
08-19 17:54:58.137  4447  4447 D BluetoothNotiBroadcastReceiver: onReceive
08-19 17:54:58.147  1179  1179 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:54:58.147  1179  1179 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-19 17:54:58.157  1021  1728 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-19 17:54:58.157  1021  1728 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-19 17:54:58.157  1021  1728 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:54:58.157  1021  1728 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:54:58.157  1021  1728 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-19 17:54:58.167  1631  1631 I Hs20UtilService: Starting #6
08-19 17:54:58.167  1631  1654 I Hs20UtilService: Message received 5011
08-19 17:54:58.167  6463  6463 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-19 17:54:58.167  6463  6463 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-19 17:54:58.167  6463  6463 D SecurityLogAgent: StateMachine : Current State = 1
08-19 17:54:58.167  6463  6463 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-19 17:54:58.177  6496  6520 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-19 17:54:58.197  1021  1499 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-19 17:54:58.197  1021  1499 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:54:58.197  1021  1499 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-19 17:54:58.197  1021  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-19 17:54:58.357  1021  1048 D Tethering: interfaceRemoved wlan0
,08-19 17:54:58.357  1021  1048 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-19 17:54:58.527  1021  1048 D Tethering: interfaceRemoved p2p0
,08-19 17:54:58.527  1021  1048 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-19 17:54:58.827   287   287 E SMD     : DCD OFF,
,08-19 17:54:59.307  1021  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1,
,08-19 17:54:59.997  1021  1099 V AlarmManager: waitForAlarm result :8
,08-19 17:55:00.257  1021  1498 D SecContentProvider: uri = 18 selection = isWifiEnabled,
08-19 17:55:00.257  1021  1498 D WifiService: setWifiEnabled: true pid=6361, uid=10170
08-19 17:55:00.257  1021  1498 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-19 17:55:00.257  1021  1498 W ActivityManager: Permission Denial: getCurrentUser() from pid=6361, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-19 17:55:00.257  1021  1498 D SecContentProvider2: mCursor = null
08-19 17:55:00.257  1021  1498 W WifiService: Failed getting userId using ActivityManagerNative
08-19 17:55:00.257  1021  1498 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6361, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-19 17:55:00.257  1021  1498 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-19 17:55:00.257  1021  1498 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-19 17:55:00.257  1021  1498 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204),
08-19 17:55:00.257  1021  1498 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-19 17:55:00.257  1021  1498 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-19 17:55:00.257  1021  1498 D SettingsProvider: name = wifi_on
,08-19 17:55:00.267  1021  1130 E WifiHW  : ##################### set firmware type 0 #####################
,08-19 17:55:00.477  1021  1053 I PowerManagerService: [PWL] Off : 50s ago,
,08-19 17:55:00.627  1021  1048 D Tethering: interfaceAdded wlan0
,08-19 17:55:00.627  1179  1179 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-19 17:55:00.627  1021  1134 E Tethering: No numeric data
08-19 17:55:00.637  1179  1179 D HotspotTile: updateTetherState():false, false
08-19 17:55:00.627  1021  1134 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-19 17:55:00.627  1021  1134 D Tethering: clearTetheredNotification()
08-19 17:55:00.627  1021  1127 D NtpTrustedTime: forceRefresh() from cache miss
08-19 17:55:00.637   277  1004 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-19 17:55:00.637   277  1004 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,08-19 17:55:00.637  1021  1048 D Tethering: interfaceLinkStateChanged wlan0, false
,08-19 17:55:00.637  1021  1048 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-19 17:55:00.637  1021  1048 D Tethering: interfaceStatusChanged wlan0, false
08-19 17:55:00.637  1021  1134 D Tethering: InitialState.processMessage what=4
,08-19 17:55:00.637  1021  1134 E Tethering: No numeric data
,08-19 17:55:00.647  1021  1134 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-19 17:55:00.647  1021  1134 D Tethering: clearTetheredNotification()
,08-19 17:55:00.647  1179  1179 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-19 17:55:00.647  1179  1179 D HotspotTile: updateTetherState():false, false
,08-19 17:55:00.647  1021  1048 D Tethering: interfaceAdded p2p0
08-19 17:55:00.647  1021  1048 D Tethering: p2p0 is not a tetherable iface, ignoring
08-19 17:55:00.647   277  1004 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
,08-19 17:55:00.647   277  1004 D Netd    : getNetworkForDns: using netid 0 for uid 1000,
08-19 17:55:00.657   277  1008 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-19 17:55:00.657  1021  1127 V NetworkStats: performPollLocked(flags=0x1)
08-19 17:55:00.657  1021  1127 D NtpTrustedTime: forceRefresh Fail.
08-19 17:55:00.657  1021  1048 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-19 17:55:00.657   277  1008 D SoftapController: Softap fwReload - Ok
08-19 17:55:00.657  1021  1048 D Tethering: interfaceLinkStateChanged p2p0, false
08-19 17:55:00.657  1021  1048 D Tethering: interfaceStatusChanged p2p0, false
08-19 17:55:00.657  1021  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-19 17:55:00.657  1021  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-19 17:55:00.657   277  1008 D CommandListener: Setting iface cfg
08-19 17:55:00.657   277  1008 D CommandListener: Trying to bring down wlan0
08-19 17:55:00.657   277  1008 D CommandListener: Clearing all IP addresses on wlan0
08-19 17:55:00.667  1021  1127 D NtpTrustedTime: forceRefresh() from cache miss
08-19 17:55:00.667  1021  1127 V NetworkStats: performPollLocked() took 9ms
08-19 17:55:00.667  1021  1128 D NtpTrustedTime: forceRefresh() from cache miss
08-19 17:55:00.667  1021  1127 D NtpTrustedTime: forceRefresh Fail.
08-19 17:55:00.667  1021  1128 D NtpTrustedTime: forceRefresh Fail.
08-19 17:55:00.667  1021  1127 V NetworkStats: performPollLocked(flags=0x1)
,08-19 17:55:00.667  1021  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-19 17:55:00.667  1021  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-19 17:55:00.667  1021  1130 E WifiHW  : supplicant_name : p2p_supplicant
,08-19 17:55:00.677  1021  1127 V NetworkStats: performPollLocked() took 6ms,
,08-19 17:55:00.677  1021  1128 D NtpTrustedTime: forceRefresh() from cache miss
08-19 17:55:00.677  1021  1128 D NtpTrustedTime: forceRefresh Fail.
,08-19 17:55:00.727  6542  6542 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL,
08-19 17:55:00.727  6542  6542 I wpa_supplicant: Successfully initialized wpa_supplicant
08-19 17:55:00.727  6542  6542 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-19 17:55:00.737  1021  2833 D SSRM:n  : SIOP:: AP = 360,
,08-19 17:55:00.747  6542  6542 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
08-19 17:55:00.747   401   401 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 6542
08-19 17:55:00.747   401   401 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
,08-19 17:55:00.747  6542  6542 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-19 17:55:00.747  6542  6542 I wpa_supplicant: ssSupport state is = 1
08-19 17:55:00.747  6542  6542 I wpa_supplicant: >>>>> GET KEY, IV <<<<<,
08-19 17:55:00.747  6542  6542 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-19 17:55:00.747   401   401 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 6542,
08-19 17:55:00.747   401   401 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,08-19 17:55:00.777  1021  1130 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-19 17:55:00.787  1179  1179 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-19 17:55:00.787  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-19 17:55:00.787  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-19 17:55:00.787  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:00.787  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:00.787  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:00.787  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:00.787  1179  1179 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-19 17:55:00.787  1179  1179 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-19 17:55:00.787  1179  1179 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-19 17:55:00.787  1179  1700 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-19 17:55:00.787  4447  4447 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-19 17:55:00.787  1179  1179 D HotspotTile: onReceive : 2, 0
08-19 17:55:00.787  6361  6361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:00.787  6361  6361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:00.787  1021  1499 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-19 17:55:00.787  1021  1499 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-19 17:55:00.797  1021  1499 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:00.797  1021  1499 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:00.797  1021  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-19 17:55:00.797  1631  1631 I Hs20UtilService: Starting #7
,08-19 17:55:00.797  1631  1654 I Hs20UtilService: Message received 5011
,08-19 17:55:00.797  6463  6463 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-19 17:55:00.797  6463  6463 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-19 17:55:00.797  6463  6463 D SecurityLogAgent: StateMachine : Current State = 1
,08-19 17:55:00.797  6463  6463 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-19 17:55:00.917   401   401 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0,
,08-19 17:55:00.917  6542  6542 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,08-19 17:55:00.967  6542  6542 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-19 17:55:00.967  6542  6542 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-19 17:55:00.977  6542  6542 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-19 17:55:00.977   401   401 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6542
08-19 17:55:00.977   401   401 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-19 17:55:00.977  6542  6542 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-19 17:55:00.977  6542  6542 I wpa_supplicant: ssSupport state is = 1
,08-19 17:55:00.977  6542  6542 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-19 17:55:00.977  6542  6542 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-19 17:55:00.977  6542  6542 E wpa_supplicant: SIM READ ERROR
08-19 17:55:00.977  6542  6542 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-19 17:55:00.977  6542  6542 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-19 17:55:00.977  6542  6542 E wpa_supplicant: SIM READ ERROR
08-19 17:55:00.977  6542  6542 I wpa_supplicant: Blacklist: Clear (all) 
08-19 17:55:00.977  6542  6542 I wpa_supplicant: wpa_default_ap_write_once
08-19 17:55:00.977  6542  6542 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-19 17:55:00.977  6542  6542 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-19 17:55:00.977  6542  6542 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-19 17:55:00.977  6542  6542 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-19 17:55:00.977  6542  6542 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-19 17:55:00.977  6542  6542 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-19 17:55:00.987  1021  1048 D Tethering: interfaceLinkStateChanged wlan0, false
08-19 17:55:00.987  1021  1048 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-19 17:55:00.987  1021  1048 D Tethering: interfaceStatusChanged wlan0, false
,08-19 17:55:01.087  6542  6542 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-19 17:55:01.297  6542  6542 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-19 17:55:01.297  6542  6542 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-19 17:55:01.307  6542  6542 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-19 17:55:01.307   401   401 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6542,
08-19 17:55:01.307   401   401 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,08-19 17:55:01.317  6542  6542 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-19 17:55:01.317  6542  6542 I wpa_supplicant: ssSupport state is = 1
,08-19 17:55:01.317  6542  6542 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-19 17:55:01.317  6542  6542 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-19 17:55:01.327  6542  6542 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-19 17:55:01.327   401   401 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6542
08-19 17:55:01.327   401   401 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C,
08-19 17:55:01.327  6542  6542 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-19 17:55:01.327  6542  6542 I wpa_supplicant: ssSupport state is = 1
08-19 17:55:01.337  6542  6542 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-19 17:55:01.337  6542  6542 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-19 17:55:01.337  6542  6542 E wpa_supplicant: SIM READ ERROR
08-19 17:55:01.337  6542  6542 I wpa_supplicant: wpa_default_ap_write_once
08-19 17:55:01.337  6542  6542 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap,
08-19 17:55:01.337  6542  6542 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-19 17:55:01.337  1021  1048 D Tethering: interfaceLinkStateChanged p2p0, false
,08-19 17:55:01.337  1021  1048 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-19 17:55:01.337  1021  1048 D Tethering: interfaceStatusChanged p2p0, false
,08-19 17:55:01.337  1021  1048 D Tethering: interfaceLinkStateChanged p2p0, false
,08-19 17:55:01.337  1021  1048 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-19 17:55:01.337  1021  1048 D Tethering: interfaceStatusChanged p2p0, false
,08-19 17:55:01.447  6542  6542 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-19 17:55:01.447  6542  6542 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-19 17:55:01.487  6542  6542 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-19 17:55:01.487  6542  6542 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,08-19 17:55:01.487  6542  6542 I wpa_supplicant: Skip scan - bUseNetwork false
,08-19 17:55:01.497  1021  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
08-19 17:55:01.497  1021  1130 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-19 17:55:01.497  6542  6542 I wpa_supplicant: HOTSPOT20_ENABLE called,
08-19 17:55:01.497  6542  6542 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-19 17:55:01.507  6542  6542 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-19 17:55:01.507  6542  6542 E wpa_supplicant: SIM READ ERROR
08-19 17:55:01.507  6542  6542 I wpa_supplicant: Blacklist: Clear (all) 
,08-19 17:55:01.517  6542  6542 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-19 17:55:01.527  6542  6542 I wpa_supplicant: Skip scan - bUseNetwork false,
,08-19 17:55:01.527  1021  1130 D WifiConfigStore: Loading config and enabling all networks 
,08-19 17:55:01.537  1179  1179 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-19 17:55:01.537  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-19 17:55:01.537  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-19 17:55:01.537  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:01.537  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:01.537  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-19 17:55:01.537  4447  4447 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-19 17:55:01.537  1179  1179 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-19 17:55:01.537  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:01.537  1179  1179 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-19 17:55:01.537  1179  1179 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-19 17:55:01.537  1179  1700 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-19 17:55:01.537  1179  1179 D HotspotTile: onReceive : 3, 0
,08-19 17:55:01.537  6361  6361 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-19 17:55:01.537  6361  6361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:55:01.537  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:01.537  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:55:01.537  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:55:01.537  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-19 17:55:01.537  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:01.537  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:01.537  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:55:01.537  6361  6361 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:55:01.537  6361  6361 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:55:01.547  1021  1130 E WifiConfigStore: Not a HS20
,08-19 17:55:01.547  6361  6361 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:55:01.547  6361  6361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:55:01.547  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:01.547  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:55:01.547  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:55:01.547  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-19 17:55:01.547  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:01.547  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:01.547  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:55:01.547  6361  6361 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:55:01.547  6361  6361 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:55:01.547  1021  1727 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-19 17:55:01.547  1021  1727 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-19 17:55:01.547  1021  1727 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:01.547  1021  1727 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:01.547  1021  1727 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-19 17:55:01.547  1021  1130 D WifiNative-wlan0: callSECApiInt - ID [65],
08-19 17:55:01.547  1631  1631 I Hs20UtilService: Starting #8
,08-19 17:55:01.557  1631  1654 I Hs20UtilService: Message received 5011
,08-19 17:55:01.557  6463  6463 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-19 17:55:01.557  6463  6463 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-19 17:55:01.557  6463  6463 D SecurityLogAgent: StateMachine : Current State = 1
08-19 17:55:01.557  6463  6463 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-19 17:55:01.557  1021  1130 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,08-19 17:55:01.557  6542  6542 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-19 17:55:01.557  6542  6542 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-19 17:55:01.557  6542  6542 I wpa_supplicant: reset timer : RESET_TIMER 0
08-19 17:55:01.557  6542  6542 I wpa_supplicant: P2P: Current p2p state = IDLE
08-19 17:55:01.557  6542  6542 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-19 17:55:01.557  6542  6542 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-19 17:55:01.557  6542  6542 I wpa_supplicant: First Scan Start
,08-19 17:55:01.557  6542  6542 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-19 17:55:01.557  1021  1130 D WifiNative-wlan0: Setting external_sim to 1
,08-19 17:55:01.567  1021  1130 D WifiStateMachine: Setting OUI to DA-A1-19
08-19 17:55:01.567  1021  1130 I WifiNative-HAL: startHal
,08-19 17:55:01.567  1021  1130 E wifi    : getStaticLongField sWifiHalHandle 0x9f38988c
08-19 17:55:01.567  1021  1130 I WifiNative-HAL: Could not start hal
,08-19 17:55:01.567  6329  6329 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-19 17:55:01.567  1021  1130 E WifiNative-wlan0: do suspend true
,08-19 17:55:01.567  1021  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-19 17:55:01.567  1021  1129 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-19 17:55:01.567   277  1008 D CommandListener: Setting iface cfg
08-19 17:55:01.567   277  1008 D CommandListener: Trying to bring up p2p0
,08-19 17:55:01.567  1021  1021 D WifiScanningService: SCAN_AVAILABLE : 3
08-19 17:55:01.567  1021  1153 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:01.567  1021  1153 I WifiNative-HAL: startHal
08-19 17:55:01.567  1021  1153 E wifi    : getStaticLongField sWifiHalHandle 0x9e3499bc
08-19 17:55:01.567  1021  1153 I WifiNative-HAL: Could not start hal
08-19 17:55:01.567  1021  1153 E WifiScanningService: could not start HAL
,08-19 17:55:01.567  1021  1129 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-19 17:55:01.567  1021  1129 D WifiP2pService: P2pEnablingState
08-19 17:55:01.567  1021  1129 D WifiP2pService: P2pEnablingState{ what=147457 }
08-19 17:55:01.577  1021  1021 D RttService: SCAN_AVAILABLE : 3
08-19 17:55:01.567  1021  1129 D WifiP2pService: P2p socket connection successful
08-19 17:55:01.577  1021  1154 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:01.577  1021  1129 D WifiP2pService: P2pEnabledState
08-19 17:55:01.577  1021  1129 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-19 17:55:01.577  1021  1132 E ConnectivityService: updateNetworkInfo()
,08-19 17:55:01.577  1021  1130 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-19 17:55:01.577  1021  1130 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-19 17:55:01.577  1021  1130 E WifiNative-wlan0: invaild command id : 215
,08-19 17:55:01.577  1021  1130 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
,08-19 17:55:01.577  1021  1130 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-19 17:55:01.577  1021  1130 E WifiNative-wlan0: invaild command id : 215
08-19 17:55:01.577  1021  1021 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-19 17:55:01.577  1021  1051 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-19 17:55:01.577  1021  1051 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-19 17:55:01.577  1021  1051 D WifiDisplayController: disconnect
08-19 17:55:01.577  1021  1051 D WifiDisplayController: updateConnection
08-19 17:55:01.577  1021  1051 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-19 17:55:01.577  1021  1051 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-19 17:55:01.577  6542  6542 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-19 17:55:01.577  6542  6542 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-19 17:55:01.577  6542  6542 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,08-19 17:55:01.577  1179  1179 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-19 17:55:01.577  1021  1728 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-19 17:55:01.587  1021  1130 E WifiStateMachine: Failed to set frequency band 0,
08-19 17:55:01.577  1179  1179 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0,
08-19 17:55:01.587  1021  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-19 17:55:01.587  1021  1130 D SecContentProvider2: mCursor = null
08-19 17:55:01.587  1021  1051 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-19 17:55:01.587  1021  1051 D WifiDisplayAdapter: onP2pDisconnected
08-19 17:55:01.587  1021  1051 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-19 17:55:01.587  1021  1051 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-19 17:55:01.587  1021  1129 D WifiNative-p2p0: p2pGetDeviceAddress
08-19 17:55:01.587  1021  1129 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,08-19 17:55:01.587  1021  1051 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3,
08-19 17:55:01.587  1021  1051 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
08-19 17:55:01.587  1021  1051 D WifiDisplayController:  primary type: 10-0050F204-5
08-19 17:55:01.587  1021  1051 D WifiDisplayController:  secondary type: null
08-19 17:55:01.587  1021  1051 D WifiDisplayController:  wps: 0
08-19 17:55:01.587  1021  1051 D WifiDisplayController:  grpcapab: 0
08-19 17:55:01.587  1021  1051 D WifiDisplayController:  devcapab: 0
08-19 17:55:01.587  1021  1051 D WifiDisplayController:  status: 3
08-19 17:55:01.587  1021  1051 D WifiDisplayController:  wfdInfo: null
08-19 17:55:01.587  1021  1051 D WifiDisplayController:  groupownerAddress: null
08-19 17:55:01.587  1021  1051 D WifiDisplayController:  GOdeviceName: null
08-19 17:55:01.587  1021  1051 D WifiDisplayController:  interfaceAddress: 
08-19 17:55:01.587  1021  1051 D WifiDisplayController:  SConnectInfo : null
08-19 17:55:01.587  1021  1129 D WifiP2pService: DeviceAddress: 0a:75:42
,08-19 17:55:01.587  1021  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-19 17:55:01.587  1021  1130 D SecContentProvider2: mCursor = null
08-19 17:55:01.587  4447  4447 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-19 17:55:01.587  4447  4447 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-19 17:55:01.597  4447  4447 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-19 17:55:01.597  4447  4447 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-19 17:55:01.597  4447  4447 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-19 17:55:01.597  4447  4447 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-19 17:55:01.597  4447  4522 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-19 17:55:01.597  6431  6431 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-19 17:55:01.597  6431  6431 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-19 17:55:01.597  6431  6431 D FileShare-Client: Outbound.stopDelayTimer - 
,08-19 17:55:01.607  6447  6447 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-19 17:55:01.617  1021  1129 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-19 17:55:01.617  1021  1129 D WifiP2pService: InactiveState
,08-19 17:55:01.617  1021  1129 D WifiP2pService: InactiveState{ what=143376 }
,08-19 17:55:01.617  1021  1129 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-19 17:55:01.617  6542  6542 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-19 17:55:01.617  1021  1129 D WifiP2pService: InactiveState{ what=143376 }
,08-19 17:55:01.617  1021  1129 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-19 17:55:01.637  1021  1048 D Tethering: interfaceLinkStateChanged p2p0, false
,08-19 17:55:01.637  1021  1048 D Tethering: interfaceStatusChanged p2p0, false
08-19 17:55:01.637  1021  1048 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-19 17:55:01.827   287   287 E SMD     : DCD OFF,
,08-19 17:55:02.857  6542  6542 I wpa_supplicant: nl80211: Received scan results (32 BSSes),
08-19 17:55:02.857  6542  6542 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-19 17:55:02.857  6542  6542 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-19 17:55:02.857  6542  6542 I wpa_supplicant: Trying to associate with  'G700'
08-19 17:55:02.857  6542  6542 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-19 17:55:02.857  6542  6542 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-19 17:55:02.857  1021  6547 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-19 17:55:02.877  1021  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-19 17:55:02.877  1021  1130 D SecContentProvider2: mCursor = null
,08-19 17:55:03.277  1021  1498 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-19 17:55:03.277  1021  1498 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-19 17:55:03.277  1021  1498 D SecContentProvider2: mCursor = null
,08-19 17:55:03.277  1021  1498 D WifiService: setWifiEnabled: false pid=6361, uid=10170
,08-19 17:55:03.277  1021  1498 D SettingsProvider: name = wifi_on
,08-19 17:55:03.287  1021  1129 D WifiP2pService: InactiveState{ what=131204 }
,08-19 17:55:03.287  1021  1129 D WifiP2pService: P2pEnabledState{ what=131204 }
08-19 17:55:03.287  1021  1021 D WifiScanningService: SCAN_AVAILABLE : 1
,08-19 17:55:03.287  1021  1153 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-19 17:55:03.287  1021  1129 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-19 17:55:03.287  1021  1132 E ConnectivityService: updateNetworkInfo()
,08-19 17:55:03.287  1021  1021 D RttService: SCAN_AVAILABLE : 1
,08-19 17:55:03.287  1021  1154 D RttService: EnabledState got{ when=-2ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-19 17:55:03.287  1021  1051 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-19 17:55:03.287  1021  1051 D WifiDisplayAdapter: onP2pDisconnected
08-19 17:55:03.287  1021  1051 D IpRemoteDisplayController: disconnectWfdBridgeServer
,08-19 17:55:03.287  1021  1051 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-19 17:55:03.297  4447  4447 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-19 17:55:03.297  4447  4447 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-19 17:55:03.297  4447  4447 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-19 17:55:03.297  1021  1051 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,08-19 17:55:03.297  1021  1051 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-19 17:55:03.297  1021  1051 D WifiDisplayController: disconnect
08-19 17:55:03.297  1021  1051 D WifiDisplayController: updateConnection
,08-19 17:55:03.297  1021  1051 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-19 17:55:03.297  1021  1051 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-19 17:55:03.297  1021  1021 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-19 17:55:03.307  4447  4447 I NearbySettings: DMSUtil.isNetworkConnected - P2P: FAILED
08-19 17:55:03.307  4447  4447 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-19 17:55:03.307  4447  4447 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-19 17:55:03.307  1021  1129 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-19 17:55:03.307  1021  1132 E ConnectivityService: updateNetworkInfo()
08-19 17:55:03.307  4447  4522 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-19 17:55:03.307  1179  1179 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-19 17:55:03.307  1021  1033 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-19 17:55:03.307  1179  1179 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-19 17:55:03.307  1021  1129 D WifiP2pService: P2pDisablingState
,08-19 17:55:03.307  1021  1129 D WifiP2pService: P2pDisablingState{ what=147458 }
08-19 17:55:03.307  1021  1129 D WifiP2pService: p2p socket connection lost
,08-19 17:55:03.307   277  1008 D CommandListener: Clearing all IP addresses on wlan0
,08-19 17:55:03.317  1021  1129 D WifiP2pService: P2pDisabledState
,08-19 17:55:03.317  6431  6431 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-19 17:55:03.317  1021  1051 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,08-19 17:55:03.317  6431  6431 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-19 17:55:03.317  6431  6431 D FileShare-Client: Outbound.stopDelayTimer - 
,08-19 17:55:03.317  1021  1051 D WifiDisplayAdapter: onP2pDisconnected
08-19 17:55:03.317  1021  1051 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-19 17:55:03.317  1021  1051 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-19 17:55:03.327  1021  1021 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-19 17:55:03.327  6542  6542 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-19 17:55:03.327  1179  1179 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-19 17:55:03.337  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-19 17:55:03.337  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-19 17:55:03.337  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:03.337  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:03.337  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:03.337  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-19 17:55:03.337  6447  6447 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-19 17:55:03.347  1179  1179 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-19 17:55:03.347  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-19 17:55:03.347  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-19 17:55:03.347  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-19 17:55:03.347  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:03.347  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-19 17:55:03.347  4447  4447 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-19 17:55:03.347  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-19 17:55:03.347  1179  1179 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-19 17:55:03.347  1179  1179 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-19 17:55:03.347  1179  1179 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-19 17:55:03.347  1179  1700 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-19 17:55:03.347  6361  6361 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-19 17:55:03.347  6361  6361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:55:03.347  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:03.347  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:55:03.347  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-19 17:55:03.347  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-19 17:55:03.347  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:03.347  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:03.347  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:55:03.347  1179  1179 D HotspotTile: onReceive : 0, 0
,08-19 17:55:03.347  6361  6361 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:55:03.347  6361  6361 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:55:03.357  6361  6361 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-19 17:55:03.357  6361  6361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:55:03.357  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:03.357  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:55:03.357  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-19 17:55:03.357  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-19 17:55:03.357  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:03.357  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:03.357  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:55:03.357  6361  6361 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-19 17:55:03.357  6361  6361 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:55:03.357  4447  4447 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-19 17:55:03.357  4447  4447 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-19 17:55:03.357  4447  4447 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-19 17:55:03.357  4447  4447 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-19 17:55:03.357  4447  4447 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-19 17:55:03.357  4447  4447 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-19 17:55:03.357  4447  4522 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-19 17:55:03.367  6431  6431 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-19 17:55:03.367  6431  6431 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-19 17:55:03.367  6431  6431 D FileShare-Client: Outbound.stopDelayTimer - 
,08-19 17:55:03.367  6447  6447 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-19 17:55:03.377  1021  1033 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-19 17:55:03.377  1021  1033 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-19 17:55:03.377  1021  1033 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:03.377  1021  1033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:03.377  1021  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-19 17:55:03.387  1631  1631 I Hs20UtilService: Starting #9
,08-19 17:55:03.387  1631  1654 I Hs20UtilService: Message received 5007
,08-19 17:55:03.387  4447  4447 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-19 17:55:03.387  4447  4447 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-19 17:55:03.387  4447  4447 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-19 17:55:03.387  4447  4447 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-19 17:55:03.387  4447  4447 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-19 17:55:03.387  4447  4447 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-19 17:55:03.387  4447  4522 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-19 17:55:03.397  1021  1508 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-19 17:55:03.397  1021  1508 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-19 17:55:03.397  1021  1508 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:03.397  1021  1508 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:03.397  1021  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-19 17:55:03.407  6463  6463 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-19 17:55:03.407  6463  6463 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-19 17:55:03.407  6463  6463 D SecurityLogAgent: StateMachine : Current State = 1
,08-19 17:55:03.407  6463  6463 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-19 17:55:03.417  1631  1631 I Hs20UtilService: Starting #10
,08-19 17:55:03.417  1631  1654 I Hs20UtilService: Message received 5011
,08-19 17:55:03.517  6542  6542 I wpa_supplicant: Blacklist: Clear (all) 
,08-19 17:55:03.647  6542  6542 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-19 17:55:03.647  1021  1048 D Tethering: interfaceLinkStateChanged p2p0, false
08-19 17:55:03.647  1021  1048 D Tethering: interfaceStatusChanged p2p0, false
,08-19 17:55:03.647  1021  1048 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-19 17:55:03.837  1021  1033 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-19 17:55:03.837  1021  1033 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4272, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-19 17:55:03.837  1021  1033 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-19 17:55:03.837  1021  1033 D BatteryService: stay LED for charging
08-19 17:55:03.837  1021  1021 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-19 17:55:03.847  1021  1021 I MotionRecognitionService: Plugged
,08-19 17:55:03.847  1021  1021 I MotionRecognitionService: mGripSensorEnabled= false
,08-19 17:55:03.847  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-19 17:55:03.847  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-19 17:55:03.857  1441  1441 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-19 17:55:03.857  1441  1441 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-19 17:55:03.877  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
08-19 17:55:03.877  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-19 17:55:03.877  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-19 17:55:03.877  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-19 17:55:03.877  1179  1179 D SViewCoverView: level :100 plugged : 2
,08-19 17:55:03.967  6542  6542 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=00.00.00 reason=3 locally_generated=1
08-19 17:55:03.967  1021  1048 D Tethering: interfaceLinkStateChanged wlan0, false
08-19 17:55:03.967  1021  1048 D Tethering: interfaceStatusChanged wlan0, false
08-19 17:55:03.977  1021  1048 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-19 17:55:03.977  6542  6542 I wpa_supplicant: wlan0: State: ASSOCIATING -> DISCONNECTED
08-19 17:55:03.977  6542  6542 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=00.00.00 SSID=4E47373030
08-19 17:55:03.977  6542  6542 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-19 17:55:03.977  1021  1048 D Tethering: interfaceLinkStateChanged wlan0, false
08-19 17:55:03.977  1021  1048 D Tethering: interfaceStatusChanged wlan0, false
,08-19 17:55:03.977  1021  1048 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-19 17:55:04.317  6542  6542 I wpa_supplicant: Blacklist: Clear (all) 
,08-19 17:55:04.487  1021  1048 D Tethering: interfaceLinkStateChanged wlan0, false
08-19 17:55:04.487  1021  1048 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-19 17:55:04.487  1021  1048 D Tethering: interfaceStatusChanged wlan0, false
,08-19 17:55:04.487  6542  6542 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-19 17:55:04.597  1021  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0,
08-19 17:55:04.597  1021  1130 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-19 17:55:04.597  6329  6329 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
,08-19 17:55:04.617  1179  1179 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-19 17:55:04.617  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-19 17:55:04.617  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-19 17:55:04.617  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:04.617  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:04.617  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:04.617  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:04.617  1179  1179 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-19 17:55:04.617  1179  1179 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-19 17:55:04.617  1179  1179 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-19 17:55:04.617  1179  1700 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-19 17:55:04.617  1179  1179 D HotspotTile: onReceive : 1, 0
,08-19 17:55:04.617  1729  2156 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-19 17:55:04.617  4447  4447 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-19 17:55:04.627  1021  1033 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-19 17:55:04.627  1021  1033 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-19 17:55:04.627  1021  1033 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:04.627  1021  1033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:04.627  1021  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-19 17:55:04.627  1631  1631 I Hs20UtilService: Starting #11
,08-19 17:55:04.627  1631  1654 I Hs20UtilService: Message received 5011
,08-19 17:55:04.637  6361  6361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:04.637  6361  6361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:04.637  6463  6463 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-19 17:55:04.637  6463  6463 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-19 17:55:04.637  6463  6463 D SecurityLogAgent: StateMachine : Current State = 1
,08-19 17:55:04.637  6463  6463 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-19 17:55:04.827   287   287 E SMD     : DCD OFF
,08-19 17:55:05.367  1021  1048 D Tethering: interfaceRemoved wlan0
,08-19 17:55:05.367  1021  1048 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-19 17:55:05.487  1021  1048 D Tethering: interfaceRemoved p2p0
,08-19 17:55:05.487  1021  1048 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-19 17:55:05.887  1021  1339 E Watchdog: !@Sync 3
,08-19 17:55:06.257  1021  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-19 17:55:06.287  6361  6416 D BluetoothAdapter: enable()
,08-19 17:55:06.287  1021  1034 W ActivityManager: Permission Denial: getCurrentUser() from pid=6361, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-19 17:55:06.297  1021  1034 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-19 17:55:06.297  1021  1034 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6361, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-19 17:55:06.297  1021  1034 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-19 17:55:06.297  1021  1034 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-19 17:55:06.297  1021  1034 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-19 17:55:06.297  1021  1034 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-19 17:55:06.297  1021  1034 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-19 17:55:06.297  1021  1034 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-19 17:55:06.297  1021  1034 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-19 17:55:06.297  1021  1034 D SettingsProvider: name = bluetooth_on,
,08-19 17:55:06.297  1021  1050 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-19 17:55:06.307  1021  1050 D SecContentProvider: uri = 3 selection = isBluetoothEnabled,
08-19 17:55:06.307  1021  1050 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-19 17:55:06.307  2760  2816 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
08-19 17:55:06.307  2760  2816 D BluetoothAdapterProperties: Setting state to 11
08-19 17:55:06.307  2760  2816 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-19 17:55:06.307  2760  2816 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-19 17:55:06.307  2760  2816 D BluetoothAdapterService: updateAdapterState state is 11
08-19 17:55:06.307  2760  2816 D BluetoothAdapterService: Autoconnection is available 
08-19 17:55:06.307  2760  2816 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
08-19 17:55:06.307  2760  2816 D BtConfig.SecureMode: isSecureModeOn:false
08-19 17:55:06.307  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-19 17:55:06.307  2760  2816 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
08-19 17:55:06.307  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-19 17:55:06.307  2760  2816 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
08-19 17:55:06.307  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-19 17:55:06.307  2760  2816 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
08-19 17:55:06.307  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-19 17:55:06.307  2760  2816 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
08-19 17:55:06.307  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService,
08-19 17:55:06.307  2760  2816 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
08-19 17:55:06.307  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-19 17:55:06.307  2760  2816 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
08-19 17:55:06.307  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-19 17:55:06.307  2760  2816 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
08-19 17:55:06.307  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService,
08-19 17:55:06.307  2760  2816 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
08-19 17:55:06.307  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-19 17:55:06.307  2760  2816 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-19 17:55:06.307  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-19 17:55:06.307  2760  2816 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
,08-19 17:55:06.307  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-19 17:55:06.307  2760  2816 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-19 17:55:06.307  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-19 17:55:06.307  2760  2816 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-19 17:55:06.307  2760  2816 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
08-19 17:55:06.307  2760  2816 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
,08-19 17:55:06.307  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-19 17:55:06.307  2760  2816 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-19 17:55:06.317  1021  1021 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:06.317  1021  1021 I InputMethodManagerService: [BT Setting State] State =11
,08-19 17:55:06.327  1179  1179 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-19 17:55:06.327  1179  1179 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-19 17:55:06.327  1179  1179 D BluetoothTile:  getBluetoothState : 11
,08-19 17:55:06.327  1935  1935 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-19 17:55:06.327  1021  1524 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-19 17:55:06.327  1021  1728 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-19 17:55:06.337  1179  1700 D BluetoothTile:  handleUpdatestate:false name:null
08-19 17:55:06.337  1179  1700 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-19 17:55:06.337  1179  1179 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-19 17:55:06.337  4447  4447 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-19 17:55:06.337  6361  6361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:06.337  6361  6361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:06.337  1021  4075 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:55:06.337  1021  4075 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-19 17:55:06.337  1021  4075 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:06.337  1021  4075 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:06.337  1021  4075 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-19 17:55:06.337  2760  2816 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-19 17:55:06.337  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-19 17:55:06.337  2760  2816 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-19 17:55:06.347  1681  1681 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.,
08-19 17:55:06.347  1021  1034 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-19 17:55:06.347  2760  2760 D HeadsetService: Received start request. Starting profile...
08-19 17:55:06.347  1021  1034 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-19 17:55:06.347  2760  2760 D HeadsetService: start()
08-19 17:55:06.347  2760  2760 D HeadsetStateMachine: make
,08-19 17:55:06.347  1021  1034 W ActivityManager: userId = 0, bbcId = -10000,
08-19 17:55:06.347  1021  1034 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:06.347  1021  1034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:06.347  2760  2760 E HeadsetStateMachine: # of Max HF connection is 2
08-19 17:55:06.347  2760  2816 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,08-19 17:55:06.347  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-19 17:55:06.347  2760  2816 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-19 17:55:06.357  1021  1508 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:55:06.357  1021  1508 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-19 17:55:06.357  1021  1508 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:06.357  1021  1508 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:06.357  1021  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:06.367  4447  4447 D BluetoothNotiBroadcastReceiver: onReceive
,08-19 17:55:06.367  1021  4073 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-19 17:55:06.367  1021  4073 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-19 17:55:06.367  2760  2816 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-19 17:55:06.367  1021  4073 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:06.367  1021  1033 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:55:06.367  1021  4073 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:06.367  1021  1033 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-19 17:55:06.367  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-19 17:55:06.367  1021  4073 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-19 17:55:06.367  2760  2816 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-19 17:55:06.367  1021  1033 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:06.367  1021  1033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:06.367  1021  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:06.367  2760  2816 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-19 17:55:06.367  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-19 17:55:06.367  2760  2816 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-19 17:55:06.377  1021  4074 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-19 17:55:06.377  1021  4074 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-19 17:55:06.377  1021  4074 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:06.377  1021  4074 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:06.377  1021  4074 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-19 17:55:06.377  2760  2760 I bluedroid: get_profile_interface handsfree
08-19 17:55:06.377  1021  4075 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-19 17:55:06.377  1021  4075 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-19 17:55:06.377  1021  4075 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:06.377  1021  4075 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:06.377  1021  4075 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:06.377  2760  2816 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,08-19 17:55:06.377  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-19 17:55:06.377  2760  2816 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-19 17:55:06.387  1179  1179 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-19 17:55:06.387  1179  1179 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-19 17:55:06.397  1021  1728 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:55:06.397  1021  1728 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-19 17:55:06.397  1021  1728 W ActivityManager: userId = 0, bbcId = -10000,
08-19 17:55:06.397  1021  1728 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-19 17:55:06.397  1021  1728 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:06.397  2760  2760 E DualScoManager: Dual Sco Manager already instantiated,
08-19 17:55:06.397  2760  2760 I DualScoManager: Set HeadsetServiceHelper
08-19 17:55:06.397  2760  2760 D BluetoothAtMessage: createCMTIContentObservers,
08-19 17:55:06.397  2760  2816 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-19 17:55:06.397  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService,
08-19 17:55:06.397  2760  2816 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-19 17:55:06.397  1021  1546 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-19 17:55:06.397  1021  1546 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-19 17:55:06.397  1021  1546 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-19 17:55:06.397  1021  1546 D SettingsProvider: selectionArgs: false
08-19 17:55:06.397  1021  1546 D SettingsProvider: selectionArgs: 1002
08-19 17:55:06.397  1021  1546 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-19 17:55:06.397  1021  1546 D SettingsProvider: ret = -1
,08-19 17:55:06.397  2760  6555 D HeadsetStateMachine: Enter Disconnected: -2
,08-19 17:55:06.407  1021  4073 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:55:06.407  1021  4073 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-19 17:55:06.407  1021  4073 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:06.407  1021  4073 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-19 17:55:06.407  1021  4073 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:06.407  2760  2816 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-19 17:55:06.407  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-19 17:55:06.407  2760  2816 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-19 17:55:06.407  2760  2816 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-19 17:55:06.407  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-19 17:55:06.407  2760  2816 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-19 17:55:06.407  2760  2816 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-19 17:55:06.407  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-19 17:55:06.407  2760  2816 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-19 17:55:06.407  2760  2816 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-19 17:55:06.407  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-19 17:55:06.407  2760  2816 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-19 17:55:06.407  2760  2816 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-19 17:55:06.407  2760  2760 D HeadsetService: mStartError = false
08-19 17:55:06.407  2760  2760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@68341b0
,08-19 17:55:06.407  2760  2760 D A2dpService: Received start request. Starting profile...
,08-19 17:55:06.407  2760  2760 D A2dpService: start()
08-19 17:55:06.407  2760  2760 I bluedroid: get_profile_interface avrcp
,08-19 17:55:06.417  2760  2760 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-19 17:55:06.417  2760  2760 D Avrcp   : Initialize Media Controller
08-19 17:55:06.417  2760  2760 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-19 17:55:06.417  2760  2760 E Avrcp   : getActiveSessions
,08-19 17:55:06.417  2760  2760 D Avrcp   : pick active media Controller
08-19 17:55:06.417  2760  2760 D Avrcp   : Get the active Media Controller 
,08-19 17:55:06.417  2760  6555 D HeadsetStateMachine: Clear mHeadsetBrsf
08-19 17:55:06.417  2760  6555 D HeadsetStateMachine: map size, before remove : 0
08-19 17:55:06.417  2760  6555 D HeadsetStateMachine: map size, after remove: 0
,08-19 17:55:06.427  2760  2760 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-19 17:55:06.427  2760  2760 D A2dpStateMachine: make
,08-19 17:55:06.427  2760  6556 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-19 17:55:06.427  2760  2760 I bluedroid: get_profile_interface a2dp
,08-19 17:55:06.427  2760  6558 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-19 17:55:06.427  2760  2760 E bt-btif : warning : media task started media_task_refcnt 1 
,08-19 17:55:06.427  2760  2760 D A2dpService: mStartError = false
,08-19 17:55:06.437  2760  2760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@68341b0
,08-19 17:55:06.437  2760  2760 D HidService: Received start request. Starting profile...
08-19 17:55:06.437  2760  2760 D HidService: start()
08-19 17:55:06.437  2760  2760 I bluedroid: get_profile_interface hidhost
08-19 17:55:06.437  2760  2760 D HidService: setHidService(): set to: null
08-19 17:55:06.437  2760  2760 D HidService: mStartError = false
08-19 17:55:06.437  2760  2760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@68341b0
08-19 17:55:06.437  2760  2760 D HeadsetStateMachine: Try to query the phonestate on bind
,08-19 17:55:06.437  2760  6557 D A2dpStateMachine: Enter Disconnected: -2
08-19 17:55:06.437  1458  1474 I Telecom : BluetoothPhoneService: queryPhoneState
,08-19 17:55:06.437  1458  1458 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-19 17:55:06.437  1458  1458 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-19 17:55:06.437  1458  1474 I Telecom : BluetoothPhoneService: Result of Message : true
,08-19 17:55:06.437  2760  2760 D HealthService: Received start request. Starting profile...
,08-19 17:55:06.437  2760  2760 D HealthService: start()
,08-19 17:55:06.447  2760  2760 I bluedroid: get_profile_interface health
08-19 17:55:06.447  2760  2760 D HealthService: mStartError = false
08-19 17:55:06.447  2760  2760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@68341b0
,08-19 17:55:06.447  2760  2760 D HeadsetStateMachine: Proxy object connected
08-19 17:55:06.447  2760  2760 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-19 17:55:06.447  2760  6555 D HeadsetStateMachine: Disconnected process message: 11
,08-19 17:55:06.447  2760  2760 D PanService: Received start request. Starting profile...
,08-19 17:55:06.447  2760  2760 D PanService: start()
08-19 17:55:06.447  2760  2760 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-19 17:55:06.447  2760  2760 I bluedroid: get_profile_interface pan
08-19 17:55:06.447  2760  2760 D PanService: mStartError = false
,08-19 17:55:06.447  2760  2760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@68341b0
,08-19 17:55:06.457  2760  2760 D HeadsetPhoneState: sendDeviceDataStateChanged
08-19 17:55:06.457  2760  2760 D HeadsetPhoneState: Signal level : previous=0 curr=4
08-19 17:55:06.457  2760  6555 D HeadsetStateMachine: Disconnected process message: 18
,08-19 17:55:06.457  2760  2760 D BluetoothMapService: Received start request. Starting profile...
08-19 17:55:06.457  2760  2760 D BluetoothMapService: start()
,08-19 17:55:06.457  2760  2760 D BluetoothMapService: mStartError = false
08-19 17:55:06.457  2760  6556 D BluetoothMediaBrowser: no now playing list
08-19 17:55:06.457  2760  6556 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-19 17:55:06.457  2760  2760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@68341b0
08-19 17:55:06.457  2760  2760 E BluetoothAdapterService(109265328): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,08-19 17:55:06.457  2760  2760 D SapService: Received start request. Starting profile...
,08-19 17:55:06.457  2760  2760 D SapService: start()
08-19 17:55:06.457  2760  2760 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-19 17:55:06.457  2760  2760 I bluedroid: get_profile_interface sap
,08-19 17:55:06.457  2760  2760 D SapService: mStartError = false
08-19 17:55:06.457  2760  2760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@68341b0
,08-19 17:55:06.457  2760  2760 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-19 17:55:06.457  2760  2760 E BluetoothAdapterService(109265328): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
,08-19 17:55:06.457  2760  2760 E BluetoothAdapterService(109265328): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-19 17:55:06.457  2760  2760 E BluetoothAdapterService(109265328): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,08-19 17:55:06.457  2760  2760 E BluetoothAdapterService(109265328): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-19 17:55:06.467  2760  6555 D HeadsetStateMachine: Disconnected process message: 10
,08-19 17:55:06.467  2760  6555 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-19 17:55:06.467  2760  6555 D HeadsetStateMachine: Disconnected process message: 11
,08-19 17:55:06.467  1021  1034 D ActivityManager: getContentProviderImpl callerProcessName:com.android.bluetooth, calleePkgName: com.android.email
,08-19 17:55:06.467  1021  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:06.467  1021  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:06.467  1021  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:06.467  1021  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:06.487  1021  1034 I ActivityManager: Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=6562 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
08-19 17:55:06.487  6562  6562 E Zygote  : MountEmulatedStorage()
08-19 17:55:06.487  6562  6562 I libpersona: KNOX_SDCARD checking this for 10141
08-19 17:55:06.487  6562  6562 E Zygote  : v2
08-19 17:55:06.487  6562  6562 I libpersona: KNOX_SDCARD not a persona
08-19 17:55:06.487  6562  6562 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-19 17:55:06.487  6562  6562 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-19 17:55:06.487  6562  6562 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-19 17:55:06.507  6562  6562 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-19 17:55:06.507  6562  6562 D ActivityThread: Added TimaKeyStore provider
,08-19 17:55:06.527  6562  6562 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-19 17:55:06.527  6562  6562 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-19 17:55:06.527  6562  6562 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-19 17:55:06.527  6562  6562 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-19 17:55:06.587  1021  3874 D RCPManagerService: exchangeData() failure , invalid userId
,08-19 17:55:06.617  1021  1225 D RCPManagerService: exchangeData() failure , invalid userId
,08-19 17:55:06.627  2760  2760 E BluetoothAdapterService(109265328): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
08-19 17:55:06.627  2760  2760 E BluetoothAdapterService(109265328): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-19 17:55:06.627  1021  1125 I ActivityManager: Killing 6100:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
,08-19 17:55:06.637  2760  2816 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-19 17:55:06.637  2760  2816 I bluedroid: enable
,08-19 17:55:06.637  2760  2819 E bt-btif : Calling BTA_HhEnable
08-19 17:55:06.637  2760  2819 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-19 17:55:06.637  2760  2819 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-19 17:55:06.637  2760  2819 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
08-19 17:55:06.637  2760  2819 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
08-19 17:55:06.637  2760  2819 E BluetoothServiceJni: populateRssiValuesNative
08-19 17:55:06.637  2760  2819 I bluedroid: getModelRssiValues
08-19 17:55:06.637  2760  2819 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-19 17:55:06.637  2760  2819 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-19 17:55:06.637  1021  1021 D SettingsProvider: name = bluetooth_name
,08-19 17:55:06.637  2760  2819 D BluetoothAdapterProperties: Name is: Galaxy A3
,08-19 17:55:06.647  2760  2819 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-19 17:55:06.647  2760  2819 D BluetoothAdapterProperties: Scan Mode:20
08-19 17:55:06.647  2760  2819 D BluetoothAdapterProperties: Discoverable Timeout:120
08-19 17:55:06.647  2760  2819 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
08-19 17:55:06.647  2760  2819 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
08-19 17:55:06.647  2760  2819 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,08-19 17:55:06.647  2760  2819 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-19 17:55:06.647  2760  2819 E bt-btif : JVenable fails
,08-19 17:55:06.647  2760  2819 D bte_conf: Device ID record 1 : primary
08-19 17:55:06.647  2760  2819 D bte_conf:   vendorId            = 0075
08-19 17:55:06.647  2760  2819 D bte_conf:   vendorIdSource      = 0001
08-19 17:55:06.647  2760  2819 D bte_conf:   product             = 0100
08-19 17:55:06.647  2760  2819 D bte_conf:   version             = 0200
08-19 17:55:06.647  2760  2819 D bte_conf:   clientExecutableURL = 
08-19 17:55:06.647  2760  2819 D bte_conf:   serviceDescription  = 
08-19 17:55:06.647  2760  2819 D bte_conf:   documentationURL    = 
08-19 17:55:06.647  2760  2819 D bte_conf: bte_load_did_conf no section named DID2.
08-19 17:55:06.647  2760  2819 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-19 17:55:06.647  2760  2819 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-19 17:55:06.657  2760  2816 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-19 17:55:06.657  2760  2816 D BluetoothAdapterProperties: ScanMode =  20
08-19 17:55:06.657  2760  2816 D BluetoothAdapterProperties: State =  11
,08-19 17:55:06.657  6361  6361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:06.657  6361  6361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:06.697  1021  4075 D RCPManagerService: exchangeData() failure , invalid userId
,08-19 17:55:06.797  1021  1498 I art     : Explicit concurrent mark sweep GC freed 67966(3MB) AllocSpace objects, 15(240KB) LOS objects, 33% free, 22MB/34MB, paused 2.317ms total 153.350ms,
08-19 17:55:06.797  1021  1727 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-19 17:55:06.807  2760  2816 D BluetoothAdapterProperties: Setting state to 12
08-19 17:55:06.807  2760  2816 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-19 17:55:06.807  1021  1033 D RCPManagerService: exchangeData() failure , invalid userId
,08-19 17:55:06.807  2760  2819 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-19 17:55:06.807  2760  2819 D BluetoothAdapterProperties: Scan Mode:21
08-19 17:55:06.807  2760  2819 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-19 17:55:06.807  1021  1225 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-19 17:55:06.807  1021  1225 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-19 17:55:06.807  1021  1225 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-19 17:55:06.807  1021  1225 D SettingsProvider: selectionArgs: false
08-19 17:55:06.807  1021  1225 D SettingsProvider: selectionArgs: 1002
08-19 17:55:06.807  1021  1225 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-19 17:55:06.807  1021  1225 D SettingsProvider: ret = -1
,08-19 17:55:06.807  2760  2816 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-19 17:55:06.807  2760  2816 D BluetoothAdapterService: updateAdapterState state is 12
08-19 17:55:06.807  1021  1727 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-19 17:55:06.807  1021  1727 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-19 17:55:06.807  1021  1727 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:06.807  1021  1727 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:06.807  1021  1727 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:06.817  2760  2816 D BluetoothAdapterService: Autoconnection is available 
,08-19 17:55:06.817  2760  2816 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
,08-19 17:55:06.817  2760  2816 D BluetoothAdapterService: starting service from this receiver
,08-19 17:55:06.817  1021  1508 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:55:06.817  1021  1508 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-19 17:55:06.817  6361  6361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:55:06.817  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:06.817  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:55:06.817  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-19 17:55:06.817  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:55:06.817  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:06.817  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:06.817  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-19 17:55:06.817  4447  4457 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-19 17:55:06.817  2760  2760 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
08-19 17:55:06.817  2760  2760 I BluetoothPbapService: Handler(): got msg=1
,08-19 17:55:06.817  1021  1727 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-19 17:55:06.817  1021  1508 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:06.827  1021  1508 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:06.827  1021  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:06.827  2760  2816 I BluetoothAdapterState: Entering On State from state = 11
,08-19 17:55:06.827  1021  1050 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-19 17:55:06.827  1021  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-19 17:55:06.837  6228  6237 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-19 17:55:06.837  1021  1225 D RCPManagerService: exchangeData() failure , invalid userId
,08-19 17:55:06.837  1021  1050 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:06.837  1021  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:06.837  1021  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:06.837  4447  4455 D Bluetoothsap: onBluetoothStateChange: up=true
,08-19 17:55:06.837  4447  4455 D Bluetoothsap: Binding service...
,08-19 17:55:06.837  2760  6586 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-19 17:55:06.847  6361  6361 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:55:06.847  2760  6586 D BluetoothSocket: bindListen(): myUserId = 0
08-19 17:55:06.847  2760  6586 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-19 17:55:06.847  4447  4455 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-19 17:55:06.847  4447  4447 D BluetoothInputDevice: Proxy object connected
08-19 17:55:06.847  4447  4447 D HidProfile: Bluetooth service connected
,08-19 17:55:06.847  1021  1050 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-19 17:55:06.847  1021  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-19 17:55:06.847  1021  1125 D RCPManagerService: exchangeData() failure , invalid userId
,08-19 17:55:06.847  1021  1050 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:06.847  1021  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:06.847  1021  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-19 17:55:06.847  2760  6586 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-19 17:55:06.847  2760  6586 D BluetoothSocket: bindListen(), new LocalSocket 
08-19 17:55:06.847  2760  6586 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-19 17:55:06.847  2760  6586 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@39fa0f5
08-19 17:55:06.847  2760  6586 D BluetoothSocket: channel: 19
08-19 17:55:06.847  2760  6586 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-19 17:55:06.847  4447  4455 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-19 17:55:06.847  1681  4083 D BluetoothAdapter: onBluetoothStateChange: up=true
08-19 17:55:06.847  1681  4083 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-19 17:55:06.857  4447  4447 D Bluetoothsap: BluetoothSAP Proxy object connected
,08-19 17:55:06.857  6361  6361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:55:06.857  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:06.857  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:55:06.857  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-19 17:55:06.857  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:55:06.857  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:06.857  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:06.857  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-19 17:55:06.857  1179  1192 D BluetoothAdapter: onBluetoothStateChange: up=true
08-19 17:55:06.857  1179  1192 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-19 17:55:06.857  4447  4447 D SapProfile: Bluetooth service connected
,08-19 17:55:06.857  4447  4447 D Bluetoothsap: getConnectedDevices()
,08-19 17:55:06.857  1458  1466 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-19 17:55:06.857  1021  1050 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-19 17:55:06.857  1021  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-19 17:55:06.857  1021  1050 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:06.857  1021  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:06.857  1021  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:06.857  1458  1466 E BluetoothHeadset: BluetoothHeadset service is binded
,08-19 17:55:06.857  6496  6508 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-19 17:55:06.867  6496  6508 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-19 17:55:06.867  6228  6237 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-19 17:55:06.867  6361  6361 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:55:06.867  6228  6237 D BadgeProvider: sendNotify, [notify] : null
08-19 17:55:06.867  1476  1504 D BluetoothAdapter: onBluetoothStateChange: up=true
08-19 17:55:06.867  1476  1504 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-19 17:55:06.867  6228  6237 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-19 17:55:06.867  6228  6237 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-19 17:55:06.867  6228  6237 D BadgeProvider: update, [UpdateCount] : 1
08-19 17:55:06.867  1509  1509 D Launcher.Model: reloadBadges entered.
,08-19 17:55:06.867  1476  1723 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-19 17:55:06.867  1021  1050 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-19 17:55:06.867  1021  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-19 17:55:06.867  1021  1050 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:06.867  1021  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-19 17:55:06.867  1021  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:06.867  1476  1723 E BluetoothHeadset: BluetoothHeadset service is binded
,08-19 17:55:06.867  2760  2770 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-19 17:55:06.877  2760  2770 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-19 17:55:06.877  1021  1050 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-19 17:55:06.877  1021  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-19 17:55:06.877  1021  1050 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:06.877  1021  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:06.877  1021  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:06.877  1021  1050 D BluetoothPan: Binding service...
,08-19 17:55:06.877  2760  2760 D BluetoothA2dp: Proxy object connected
08-19 17:55:06.877  2760  2760 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-19 17:55:06.877  1021  1050 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-19 17:55:06.877  1021  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-19 17:55:06.887  4447  6462 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-19 17:55:06.887  1021  1021 D BluetoothPan: BluetoothPAN Proxy object connected
,08-19 17:55:06.887  4447  6462 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-19 17:55:06.887  1021  1050 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-19 17:55:06.887  1021  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-19 17:55:06.887  1021  1050 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:06.887  1021  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:06.887  1021  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:06.887  1729  1740 D BluetoothAdapter: onBluetoothStateChange: up=true
08-19 17:55:06.887  1729  1740 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-19 17:55:06.887  4447  4447 D BluetoothA2dp: Proxy object connected
08-19 17:55:06.887  4447  4447 D A2dpProfile: Bluetooth service connected
08-19 17:55:06.887  4447  4457 D BluetoothAdapter: onBluetoothStateChange: up=true
08-19 17:55:06.887  4447  4457 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-19 17:55:06.887  4447  4455 D BluetoothPan: Binding service...
,08-19 17:55:06.897  1021  1050 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-19 17:55:06.897  1021  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-19 17:55:06.897  1021  1050 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:06.897  1021  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:06.897  1021  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:06.897  6361  6375 D BluetoothAdapter: onBluetoothStateChange: up=true
08-19 17:55:06.897  4447  4447 D BluetoothPan: BluetoothPAN Proxy object connected
08-19 17:55:06.897  4447  4447 D PanProfile: Bluetooth service connected
,08-19 17:55:06.897  6361  6375 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-19 17:55:06.897  1458  1466 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-19 17:55:06.897  1021  1050 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-19 17:55:06.897  1021  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-19 17:55:06.897  1021  1050 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:06.897  1021  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:06.897  1021  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:06.907  1458  1466 E BluetoothHeadset: BluetoothHeadset service is binded
,08-19 17:55:06.907  1458  1474 D BluetoothAdapter: onBluetoothStateChange: up=true
08-19 17:55:06.907  1458  1474 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-19 17:55:06.907  4447  4457 D BluetoothMap: onBluetoothStateChange: up=true
,08-19 17:55:06.907  1021  1050 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-19 17:55:06.907  1021  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-19 17:55:06.907  1021  1050 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:06.907  1021  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:06.907  1021  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:06.907  1468  1481 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-19 17:55:06.907  1468  1481 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-19 17:55:06.907  1458  1466 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-19 17:55:06.907  1021  1050 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-19 17:55:06.907  4447  4447 D BluetoothMap: Proxy object connected
08-19 17:55:06.907  1021  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-19 17:55:06.907  4447  4447 D MapProfile: Bluetooth service connected
08-19 17:55:06.907  1021  1050 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:06.907  1021  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:06.907  1021  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:06.907  1458  1466 E BluetoothHeadset: BluetoothHeadset service is binded
08-19 17:55:06.917  4447  4447 D BluetoothMap: getConnectedDevices()
,08-19 17:55:06.917  2760  2998 D BluetoothAdapter: onBluetoothStateChange: up=true
08-19 17:55:06.917  2760  2998 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-19 17:55:06.917  1021  1050 D BluetoothAdapter: onBluetoothStateChange: up=true
08-19 17:55:06.917  1021  1050 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-19 17:55:06.917  1021  1050 D BluetoothA2dp: onBluetoothStateChange: up=true
08-19 17:55:06.917  1021  1050 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-19 17:55:06.917  1021  1050 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-19 17:55:06.917  1021  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-19 17:55:06.917  1021  1021 D BluetoothA2dp: Proxy object connected
08-19 17:55:06.917  4447  6462 D BluetoothPbap: onBluetoothStateChange: up=true
,08-19 17:55:06.917  1021  1050 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-19 17:55:06.917  1021  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-19 17:55:06.917  1021  1050 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:06.917  1021  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:06.917  1021  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:06.917  4447  4447 D BluetoothPbap: Proxy object connected
,08-19 17:55:06.917  4447  4447 D PbapServerProfile: Bluetooth service connected
,08-19 17:55:06.917  4447  4455 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-19 17:55:06.917  1021  1050 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-19 17:55:06.917  1021  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-19 17:55:06.927  1021  1050 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:06.927  1021  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:06.927  1021  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:06.927  4447  4447 D HeadsetProfile: Bluetooth service connected
,08-19 17:55:06.927  4447  4455 E BluetoothHeadset: BluetoothHeadset service is binded
08-19 17:55:06.927  1021  1050 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-19 17:55:06.927  1021  1050 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-19 17:55:06.927  1021  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-19 17:55:06.927  1021  1050 E BluetoothHeadset: BluetoothHeadset service is binded
08-19 17:55:06.927  1021  1050 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-19 17:55:06.927  1021  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-19 17:55:06.937  1458  1458 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@27775127, true,
,08-19 17:55:06.937  1179  1179 D BluetoothTile:  onBluetoothStateChange:
08-19 17:55:06.937  1458  1458 D BluetoothHeadset: registerMessageListener
,08-19 17:55:06.937  1179  1179 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-19 17:55:06.937  1179  1179 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-19 17:55:06.937  1179  1179 D BluetoothTile:  getBluetoothState : 12
,08-19 17:55:06.937  1179  1700 D BluetoothTile:  handleUpdatestate:false name:null
,08-19 17:55:06.947  1179  1700 D BluetoothTile:  handleUpdatestate:false name:null
,08-19 17:55:06.947  1935  1935 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-19 17:55:06.947  1021  1524 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-19 17:55:06.947  6361  6361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:06.957  2760  2777 D HeadsetService: registerMessageListener
,08-19 17:55:06.957  1021  1125 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-19 17:55:06.957  2760  2777 D HeadsetService: registerMessageListener
08-19 17:55:06.957  2760  6555 D HeadsetStateMachine: Disconnected process message: 70
08-19 17:55:06.957  2760  6555 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@20805e8a
,08-19 17:55:06.957  1179  1179 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-19 17:55:06.957  1179  1700 D BluetoothTile:  handleUpdatestate:false name:null
08-19 17:55:06.957  1021  1021 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:06.957  1021  1021 I InputMethodManagerService: [BT Setting State] State =12
08-19 17:55:06.957  1021  1021 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
08-19 17:55:06.957  1458  1458 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-19 17:55:06.957  1458  1458 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-19 17:55:06.957  6361  6361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:06.957  2760  6592 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-19 17:55:06.957  4447  4447 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:06.957  1458  1458 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-19 17:55:06.957  1458  1458 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-19 17:55:06.957  1458  1458 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-19 17:55:06.967  2760  6555 D HeadsetStateMachine: Disconnected process message: 9
,08-19 17:55:06.967  2760  6555 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-19 17:55:06.967  4447  4447 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-19 17:55:06.967  4447  4447 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-19 17:55:06.967  4447  4447 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-19 17:55:06.967  4447  4447 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-19 17:55:06.967   282  1019 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-19 17:55:06.967   282  1019 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-19 17:55:06.967   282  1019 V voice   : voice_set_parameters: exit with code(-2)
08-19 17:55:06.967   282  1019 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-19 17:55:06.967   282  1019 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-19 17:55:06.967   282  1019 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-19 17:55:06.967   282  1019 V audio_hw_primary: adev_set_parameters: exit
,08-19 17:55:06.967  2760  6555 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
08-19 17:55:06.967  2760  6592 D BluetoothSocket: bindListen(): myUserId = 0
08-19 17:55:06.967  2760  6592 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-19 17:55:06.967  2760  6592 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
,08-19 17:55:06.967  2760  6592 D BluetoothSocket: bindListen(), new LocalSocket 
08-19 17:55:06.967  2760  6592 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,08-19 17:55:06.977  2760  6592 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1c327cfb
08-19 17:55:06.977  2760  6592 D BluetoothSocket: channel: 5
,08-19 17:55:06.977  4447  4447 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-19 17:55:06.977  1021  1499 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-19 17:55:06.977  1021  1499 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-19 17:55:06.977  1021  1499 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:06.977  1021  1499 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:06.977  1021  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-19 17:55:06.987  1681  1681 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-19 17:55:06.997  4447  4447 D DockEventReceiver: finishStartingService: stopping service
,08-19 17:55:06.997  4447  4447 D BluetoothNotiBroadcastReceiver: onReceive
,08-19 17:55:06.997  1179  1179 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-19 17:55:06.997  1179  1179 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-19 17:55:07.007  2760  2760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@68341b0
08-19 17:55:07.007  2760  2760 D BtConfig.SecureMode: isSecureModeOn:false
,08-19 17:55:07.007  1021  1727 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-19 17:55:07.007  1021  1727 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
08-19 17:55:07.007  1021  1727 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:07.007  1021  1727 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:07.007  1021  1727 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:07.017  1021  1499 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-19 17:55:07.027  2760  6599 D BluetoothSocket: bindListen(): myUserId = 0
,08-19 17:55:07.027  2760  6599 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-19 17:55:07.027  2760  6599 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[85]}
,08-19 17:55:07.037  2760  6599 D BluetoothSocket: bindListen(), new LocalSocket 
08-19 17:55:07.037  2760  6599 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-19 17:55:07.037  2760  6599 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@9a1edd7
,08-19 17:55:07.037  2760  6599 D BluetoothSocket: channel: 12
08-19 17:55:07.037  2760  6599 I BtOppRfcommListener: Accept thread started.
,08-19 17:55:07.047  1021  1508 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,08-19 17:55:07.047  1021  1508 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-19 17:55:07.047  1021  1225 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-19 17:55:07.057  1021  1524 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-19 17:55:07.557   326   326 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-19 17:55:07.557   326   326 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-19 17:55:07.827   287   287 E SMD     : DCD OFF
,08-19 17:55:09.187  5446  5446 D FactoryTest: Not factory mode
,08-19 17:55:09.187  5446  5446 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-19 17:55:09.187  5446  5446 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-19 17:55:09.187  5446  5446 D MTPRx   : still no open session command from host, so toast
,08-19 17:55:09.187  5446  5446 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 ,
08-19 17:55:09.187  5446  5446 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-19 17:55:09.187  5446  5446 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:111298
08-19 17:55:09.187  1021  1727 E PersonaManagerService: inState():  stateMachine is null !!
08-19 17:55:09.187  1021  1727 I PersonaManagerService: PersonaId don't exist,
08-19 17:55:09.187  1021  1727 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-19 17:55:09.197  1021  1727 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
,08-19 17:55:09.197  1021  1727 W ActivityManager: userId = 0, bbcId = -10000,
08-19 17:55:09.197  1021  1727 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-19 17:55:09.197  1021  1727 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-19 17:55:09.207  1021  1727 W ActivityManager: mDVFSHelper.acquire(),
,08-19 17:55:09.217  1021  1727 D PersonaManager: isKioskContainerExistOnDevice,
,08-19 17:55:09.237  1021  1727 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-19 17:55:09.237  1021  1727 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-19 17:55:09.237  1021  1727 D InputDispatcher: Focused application set to: xxxx
,08-19 17:55:09.237  1021  1727 D InputDispatcher: Focus left window: 6361
,08-19 17:55:09.237  5446  5446 E MTPRx   : started activity for popup
,08-19 17:55:09.247  1021  1051 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
08-19 17:55:09.247  1021  1051 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-19 17:55:09.267  5446  5446 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,08-19 17:55:09.267  5446  5446 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,08-19 17:55:09.267  5446  5446 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-19 17:55:09.267  5446  5446 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-19 17:55:09.267  5446  5446 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-19 17:55:09.267  5446  5446 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-19 17:55:09.287  5446  5446 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-19 17:55:09.287  1021  3874 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-19 17:55:09.287  1021  3874 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-19 17:55:09.287  1021  3874 D InputDispatcher: Focused application set to: xxxx
,08-19 17:55:09.287  1021  3874 D InputDispatcher: Focus entered window: 6361
,08-19 17:55:09.287  1021  1051 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-19 17:55:09.287  1021  1524 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-19 17:55:09.297  1021  1524 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@6f9d350 attribute=null, token = android.os.BinderProxy@284aae1b
08-19 17:55:09.297  1021  1051 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-19 17:55:09.307  6361  6416 D BluetoothAdapter: disable()
,08-19 17:55:09.307  1021  1225 D SettingsProvider: name = bluetooth_on
,08-19 17:55:09.317  2760  2816 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-19 17:55:09.317  2760  2816 D BluetoothAdapterProperties: Setting state to 13
08-19 17:55:09.317  2760  2816 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-19 17:55:09.317  2760  2816 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-19 17:55:09.317  2760  2816 D BluetoothAdapterService: updateAdapterState state is 13
,08-19 17:55:09.317  1021  1125 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:55:09.317  1021  1125 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-19 17:55:09.317  1021  1125 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:09.317  1021  1125 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:09.317  1021  1125 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:09.327  2760  2760 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-19 17:55:09.327  2760  2760 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3bb3f6c4, channel: 19, state: LISTENING
08-19 17:55:09.327  2760  2760 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3bb3f6c4, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@39fa0f5, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2067f9admSocket: android.net.LocalSocket@32634e2 impl:android.net.LocalSocketImpl@42d9073 fd:FileDescriptor[80]
,08-19 17:55:09.327  2760  2760 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@32634e2 impl:android.net.LocalSocketImpl@42d9073 fd:FileDescriptor[80]
08-19 17:55:09.327  2760  2816 D BluetoothAdapterService: Autoconnection is available 
08-19 17:55:09.327  2760  2816 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
,08-19 17:55:09.327  2760  2816 D BluetoothAdapterService: terminating service from this receiver
,08-19 17:55:09.327  4447  4447 D BluetoothPbap: Proxy object disconnected
08-19 17:55:09.327  4447  4447 D PbapServerProfile: Bluetooth service disconnected
08-19 17:55:09.327  1021  1727 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-19 17:55:09.327  1021  1727 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:09.327  1021  1727 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:09.327  1021  1727 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:09.327  2760  2816 D BluetoothAdapterProperties: onBluetoothDisable()
,08-19 17:55:09.327  2760  2816 D BluetoothAdapterProperties: mDiscovering is false
,08-19 17:55:09.327  1021  1033 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-19 17:55:09.327  2760  2816 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-19 17:55:09.337  5446  5446 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-19 17:55:09.337  2760  2819 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-19 17:55:09.337  2760  2819 D BluetoothAdapterProperties: Scan Mode:20
,08-19 17:55:09.337  2760  2816 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-19 17:55:09.337  2760  2816 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-19 17:55:09.337  2760  2816 E bt-btif : cmd socket is not created
,08-19 17:55:09.337  2760  2816 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-19 17:55:09.337  2760  2820 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,08-19 17:55:09.347  6361  6361 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-19 17:55:09.347  2760  6599 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-19 17:55:09.347  6361  6361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:55:09.347  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:09.347  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:55:09.347  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-19 17:55:09.347  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-19 17:55:09.347  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:09.347  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:09.347  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:55:09.347  6361  6361 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-19 17:55:09.347  6361  6361 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:55:09.347  1021  1021 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:09.347  1021  1021 I InputMethodManagerService: [BT Setting State] State =13
,08-19 17:55:09.347  5446  5446 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-19 17:55:09.347  5446  5446 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-19 17:55:09.347  6361  6361 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-19 17:55:09.347  6361  6361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:55:09.347  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:09.347  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:55:09.347  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-19 17:55:09.347  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-19 17:55:09.347  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:09.347  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:09.347  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:55:09.347  6361  6361 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-19 17:55:09.347  6361  6361 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:55:09.357  1179  1179 D BluetoothTile:  onBluetoothStateChange:
,08-19 17:55:09.357  1179  1179 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-19 17:55:09.357  1179  1700 D BluetoothTile:  handleUpdatestate:false name:null
,08-19 17:55:09.357  1179  1700 D BluetoothTile:  handleUpdatestate:false name:null
,08-19 17:55:09.357  1179  1179 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-19 17:55:09.357  1179  1179 D BluetoothTile:  getBluetoothState : 13
,08-19 17:55:09.357  1179  1700 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-19 17:55:09.367  2760  2820 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-19 17:55:09.367  2760  2820 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-19 17:55:09.367  2760  2820 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-19 17:55:09.367  2760  2820 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-19 17:55:09.367  2760  2820 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-19 17:55:09.367  2760  2820 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-19 17:55:09.367  1935  1935 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-19 17:55:09.367  1021  1546 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-19 17:55:09.367  4447  4447 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-19 17:55:09.377  6361  6361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:09.377  1021  1125 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-19 17:55:09.377  1179  1179 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-19 17:55:09.377  1179  1179 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-19 17:55:09.377  2760  2760 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@23783a9, channel: 5, state: LISTENING
08-19 17:55:09.377  2760  2760 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@23783a9, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1c327cfb, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1976bd2emSocket: android.net.LocalSocket@4c6c0cf impl:android.net.LocalSocketImpl@6795a5c fd:FileDescriptor[82]
08-19 17:55:09.377  2760  2760 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@4c6c0cf impl:android.net.LocalSocketImpl@6795a5c fd:FileDescriptor[82]
08-19 17:55:09.377  2760  2760 I BtOppRfcommListener: stopping Accept Thread
08-19 17:55:09.377  2760  2760 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3a5bb165, channel: 12, state: LISTENING
,08-19 17:55:09.377  2760  2760 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3a5bb165, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@9a1edd7, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@22357e3amSocket: android.net.LocalSocket@38189aeb impl:android.net.LocalSocketImpl@1e6fc048 fd:FileDescriptor[85]
08-19 17:55:09.377  2760  2760 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@38189aeb impl:android.net.LocalSocketImpl@1e6fc048 fd:FileDescriptor[85]
,08-19 17:55:09.377  2760  6599 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-19 17:55:09.377  6361  6361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:09.377  4447  4447 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-19 17:55:09.387  1021  4073 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-19 17:55:09.387  1021  4073 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-19 17:55:09.387  1021  4073 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:09.387  1021  4073 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:09.387  1021  4073 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-19 17:55:09.387  6361  6361 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-19 17:55:09.387  6361  6361 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
08-19 17:55:09.387  6361  6361 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-19 17:55:09.387  6361  6361 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-19 17:55:09.397  2760  2760 V BluetoothOppManager: cleanUp...
,08-19 17:55:09.397  1681  1681 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-19 17:55:09.397  1021  4073 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-19 17:55:09.397  1021  4073 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-19 17:55:09.397  1021  1021 D PersonaManagerService: getPersonasForUser(): returning null!
08-19 17:55:09.397  1021  4073 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-19 17:55:09.397  1021  1021 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-19 17:55:09.407  4447  4447 D DockEventReceiver: finishStartingService: stopping service
,08-19 17:55:09.407  6361  6361 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-19 17:55:09.407  6361  6361 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-19 17:55:09.407  6361  6361 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2ce68ec2 time:111515
,08-19 17:55:09.407  4447  4447 D BluetoothNotiBroadcastReceiver: onReceive
,08-19 17:55:09.407  6361  6361 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1da1985e Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@4553cc3, 16908290=android.view.AbsSavedState$1@4553cc3}, android:focusedViewId=100}]}]
,08-19 17:55:09.407  6361  6361 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-19 17:55:09.407  6361  6361 V ActivityThread: updateVisibility : ActivityRecord{2b978f09 token=android.os.BinderProxy@2ce68ec2 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-19 17:55:09.407  6361  6361 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-19 17:55:09.417  6361  6361 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-19 17:55:09.417  1179  1179 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-19 17:55:09.417  1179  1179 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-19 17:55:09.427  1021  4074 D PersonaManager: isKioskContainerExistOnDevice,
,08-19 17:55:09.547  2760  2816 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-19 17:55:09.547  2760  2816 D BtConfig.SecureMode: isSecureModeOn:false
08-19 17:55:09.547  2760  2816 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
,08-19 17:55:09.547  2760  2816 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
08-19 17:55:09.547  2760  2816 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
08-19 17:55:09.547  2760  2816 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-19 17:55:09.547  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-19 17:55:09.547  2760  2816 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-19 17:55:09.547  1021  1499 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:55:09.547  1021  1499 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-19 17:55:09.547  1021  1499 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:09.547  1021  1499 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:09.547  1021  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:09.547  2760  2816 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-19 17:55:09.547  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-19 17:55:09.547  2760  2816 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-19 17:55:09.547  1021  1499 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:55:09.547  1021  1499 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-19 17:55:09.547  1021  1499 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:09.547  1021  1499 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:09.547  1021  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:09.547  2760  2816 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-19 17:55:09.547  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-19 17:55:09.547  2760  2816 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-19 17:55:09.547  2760  2760 D HeadsetService: Received stop request...Stopping profile...
08-19 17:55:09.547  1021  1034 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:55:09.547  1021  1034 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-19 17:55:09.557  1021  1034 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:09.557  1021  1034 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:09.557  1021  1034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:09.557  2760  2816 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-19 17:55:09.557  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-19 17:55:09.557  2760  2816 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-19 17:55:09.557  2760  2760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@68341b0
,08-19 17:55:09.557  1021  1728 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:55:09.557  1021  1728 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-19 17:55:09.557  1021  1728 W ActivityManager: userId = 0, bbcId = -10000,
08-19 17:55:09.557  1021  1728 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:09.557  1021  1728 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-19 17:55:09.557  1021  1021 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-19 17:55:09.557  2760  2816 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-19 17:55:09.557  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-19 17:55:09.557  2760  2816 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-19 17:55:09.557  4447  4447 D HeadsetProfile: Bluetooth service disconnected
08-19 17:55:09.557  1021  1498 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:55:09.557  2760  2760 D A2dpService: Received stop request...Stopping profile...
08-19 17:55:09.557  1021  1498 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-19 17:55:09.557  2760  6557 D A2dpStateMachine: Exit Disconnected: -1
,08-19 17:55:09.557  1021  1498 W ActivityManager: userId = 0, bbcId = -10000,
08-19 17:55:09.557  1021  1498 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:09.557  1021  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:09.567  2760  2816 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,08-19 17:55:09.567  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-19 17:55:09.567  2760  2816 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-19 17:55:09.567  1021  4074 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-19 17:55:09.567  1021  4074 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-19 17:55:09.567  1021  4074 W ActivityManager: userId = 0, bbcId = -10000,
08-19 17:55:09.567  1021  4074 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-19 17:55:09.567  1021  4074 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-19 17:55:09.567  2760  2760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@68341b0
,08-19 17:55:09.567  2760  2816 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-19 17:55:09.567  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-19 17:55:09.567  2760  2816 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-19 17:55:09.567  1021  1021 D BluetoothA2dp: Proxy object disconnected
08-19 17:55:09.567  1021  1021 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-19 17:55:09.567  1021  1034 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:55:09.567  1021  1034 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-19 17:55:09.567  1021  1034 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:09.567  1021  1034 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:09.567  1021  1034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:09.567  2760  2760 D HidService: Received stop request...Stopping profile...
,08-19 17:55:09.567  2760  2760 D HidService: Stopping Bluetooth HidService
08-19 17:55:09.567  2760  2760 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-19 17:55:09.577  2760  2760 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-19 17:55:09.577  2760  2760 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-19 17:55:09.577  2760  2760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@68341b0
08-19 17:55:09.577  4447  4447 D BluetoothA2dp: Proxy object disconnected
08-19 17:55:09.577  4447  4447 D A2dpProfile: Bluetooth service disconnected
,08-19 17:55:09.577  2760  2816 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-19 17:55:09.577  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-19 17:55:09.577  2760  2816 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-19 17:55:09.577  2760  2816 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-19 17:55:09.577  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-19 17:55:09.577  2760  2816 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-19 17:55:09.577  2760  2816 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
,08-19 17:55:09.577  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-19 17:55:09.577  2760  2816 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-19 17:55:09.577  2760  2816 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-19 17:55:09.577  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-19 17:55:09.577  2760  2816 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-19 17:55:09.577  2760  2816 D BluetoothAdapterState: Stopping profile services that were post enabled
08-19 17:55:09.577  4447  4447 D BluetoothInputDevice: Proxy object disconnected
08-19 17:55:09.577  4447  4447 D HidProfile: Bluetooth service disconnected
08-19 17:55:09.577  2760  2760 E BluetoothAdapterService(109265328): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,08-19 17:55:09.577  2760  2760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-19 17:55:09.577  2760  2760 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-19 17:55:09.577  2760  2760 D HealthService: Received stop request...Stopping profile...
08-19 17:55:09.577  2760  2760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@68341b0
,08-19 17:55:09.577  2760  2760 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-19 17:55:09.577  2760  2760 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-19 17:55:09.577  2760  2760 D PanService: Received stop request...Stopping profile...
,08-19 17:55:09.577  2760  2760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@68341b0
,08-19 17:55:09.577  2760  2760 D BluetoothMapService: Received stop request...Stopping profile...
08-19 17:55:09.577  1021  1021 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-19 17:55:09.577  4447  4447 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-19 17:55:09.577  4447  4447 D PanProfile: Bluetooth service disconnected
,08-19 17:55:09.577  2760  2760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@68341b0
,08-19 17:55:09.587  4447  4447 D BluetoothMap: Proxy object disconnected
08-19 17:55:09.587  4447  4447 D MapProfile: Bluetooth service disconnected
,08-19 17:55:09.587  2760  2760 E BluetoothAdapterService(109265328): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-19 17:55:09.587  2760  2760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-19 17:55:09.587  2760  2760 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-19 17:55:09.587  2760  2760 D BluetoothA2dp: Proxy object disconnected
08-19 17:55:09.587  2760  2760 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-19 17:55:09.587  2760  6558 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-19 17:55:09.587  2760  2760 I GKI_LINUX: GKI_exit_task 2 done
08-19 17:55:09.587  2760  2760 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-19 17:55:09.587  2760  2760 E BluetoothAdapterService(109265328): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-19 17:55:09.587  2760  2760 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-19 17:55:09.587  2760  2760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-19 17:55:09.587  2760  2760 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-19 17:55:09.587  2760  2760 D SapService: Received stop request...Stopping profile...
,08-19 17:55:09.587  2760  2760 D SapService: Stopping Bluetooth SapService
08-19 17:55:09.587  2760  2760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@68341b0
,08-19 17:55:09.587  2760  2760 E BluetoothAdapterService(109265328): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-19 17:55:09.587  2760  2760 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-19 17:55:09.587  2760  2760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-19 17:55:09.587  2760  2760 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-19 17:55:09.587  2760  2760 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-19 17:55:09.587  2760  2760 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-19 17:55:09.587  2760  2760 E BluetoothAdapterService(109265328): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-19 17:55:09.587  2760  2760 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-19 17:55:09.587  2760  2760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-19 17:55:09.587  2760  2760 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-19 17:55:09.587  2760  2760 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-19 17:55:09.587  2760  2760 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-19 17:55:09.587  4447  4447 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-19 17:55:09.587  4447  4447 D SapProfile: Bluetooth service disconnected
08-19 17:55:09.587  2760  2760 E BluetoothAdapterService(109265328): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,08-19 17:55:09.587  2760  2760 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-19 17:55:09.587  2760  2760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-19 17:55:09.587  2760  2760 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-19 17:55:09.587  2760  2760 E BluetoothAdapterService(109265328): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,08-19 17:55:09.587  2760  2760 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,08-19 17:55:09.587  2760  2760 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
,08-19 17:55:09.587  2760  2760 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-19 17:55:09.597  2760  2816 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-19 17:55:09.597  2760  2816 D BluetoothAdapterProperties: Setting state to 10
08-19 17:55:09.597  2760  2816 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-19 17:55:09.597  2760  2816 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-19 17:55:09.597  2760  2816 D BluetoothAdapterService: updateAdapterState state is 10
,08-19 17:55:09.597  4447  6462 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-19 17:55:09.597  2760  2816 D BluetoothAdapterService: Autoconnection is available 
08-19 17:55:09.597  2760  2816 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-19 17:55:09.597  2760  2816 I BluetoothAdapterState: Entering OffState
08-19 17:55:09.597  4447  4455 D Bluetoothsap: onBluetoothStateChange: up=false
,08-19 17:55:09.597  4447  4455 D Bluetoothsap: Unbinding service...
,08-19 17:55:09.597  1681  1691 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-19 17:55:09.597  1681  1691 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-19 17:55:09.597  1179  2382 D BluetoothAdapter: onBluetoothStateChange: up=false
08-19 17:55:09.597  1179  2382 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-19 17:55:09.597  6496  6508 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-19 17:55:09.597  6496  6508 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-19 17:55:09.597  1476  1725 D BluetoothAdapter: onBluetoothStateChange: up=false
08-19 17:55:09.597  1476  1725 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-19 17:55:09.597  2760  6590 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-19 17:55:09.597  4447  4457 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-19 17:55:09.597  1729  1740 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-19 17:55:09.597  1729  1740 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-19 17:55:09.607  4447  6462 D BluetoothAdapter: onBluetoothStateChange: up=false
08-19 17:55:09.607  4447  6462 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-19 17:55:09.607  6361  6375 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-19 17:55:09.607  6361  6375 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-19 17:55:09.607  6361  6375 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-19 17:55:09.607  6361  6375 D BluetoothLeAdvertiser: Exit stop advertising
,08-19 17:55:09.607  6361  6375 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-19 17:55:09.607  6361  6375 D BluetoothLeScanner: Exiting stopAllScan
,08-19 17:55:09.607  1458  1466 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-19 17:55:09.607  1458  1466 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-19 17:55:09.607  4447  4457 D BluetoothMap: onBluetoothStateChange: up=false
,08-19 17:55:09.607  1468  1746 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-19 17:55:09.607  1468  1746 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-19 17:55:09.607  2760  2777 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-19 17:55:09.607  2760  2777 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-19 17:55:09.607  1021  1050 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-19 17:55:09.607  1021  1050 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-19 17:55:09.607  1021  1050 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-19 17:55:09.607  4447  6462 D BluetoothPbap: onBluetoothStateChange: up=false
,08-19 17:55:09.617  1021  1021 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-19 17:55:09.617  1021  1021 I InputMethodManagerService: [BT Setting State] State =10
,08-19 17:55:09.617  1021  1021 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-19 17:55:09.617  1179  1179 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-19 17:55:09.617  1179  1179 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-19 17:55:09.617  1179  1179 D BluetoothTile:  getBluetoothState : 10
,08-19 17:55:09.627  1935  1935 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-19 17:55:09.627  1021  1546 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-19 17:55:09.627  1021  1498 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-19 17:55:09.627  4447  4447 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-19 17:55:09.627  1179  1179 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-19 17:55:09.627  6361  6361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:09.627  6361  6361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:09.637  4447  4447 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-19 17:55:09.637  1021  3874 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-19 17:55:09.637  1021  3874 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-19 17:55:09.637  1021  3874 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:09.637  1021  3874 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:09.637  1021  3874 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-19 17:55:09.637  1681  1681 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-19 17:55:09.647  4447  4447 D DockEventReceiver: finishStartingService: stopping service
,08-19 17:55:09.647  4447  4447 D BluetoothNotiBroadcastReceiver: onReceive
,08-19 17:55:09.647  1179  1179 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-19 17:55:09.647  1179  1179 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-19 17:55:10.747  1021  2833 D SSRM:n  : SIOP:: AP = 330
,08-19 17:55:10.827   287   287 E SMD     : DCD OFF
,08-19 17:55:12.207  1021  1046 W ActivityManager: mDVFSHelper.release()
,08-19 17:55:12.327  6361  6416 D io.jxcore.node.ConnectivityMonitor: stop,
08-19 17:55:12.327  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:55:12.557   326   326 I ServiceManager: Waiting for service AtCmdFwd...,
,08-19 17:55:13.297  1021  2852 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-19 17:55:13.557   326   326 I ServiceManager: Waiting for service AtCmdFwd...,
,08-19 17:55:13.827   287   287 E SMD     : DCD OFF,
,08-19 17:55:13.897  1021  1728 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-19 17:55:13.897  1021  1728 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4292, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-19 17:55:13.897  1021  1728 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-19 17:55:13.897  1021  1728 D BatteryService: stay LED for charging
,08-19 17:55:13.897  1021  1021 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-19 17:55:13.907  1021  1021 I MotionRecognitionService: Plugged
,08-19 17:55:13.907  1021  1021 I MotionRecognitionService: mGripSensorEnabled= false
,08-19 17:55:13.907  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-19 17:55:13.907  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-19 17:55:13.907  1441  1441 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-19 17:55:13.907  1441  1441 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-19 17:55:13.937  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-19 17:55:13.937  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-19 17:55:13.937  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-19 17:55:13.937  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-19 17:55:13.937  1179  1179 D SViewCoverView: level :100 plugged : 2
,08-19 17:55:14.557   326   326 I ServiceManager: Waiting for service AtCmdFwd...,
,08-19 17:55:15.327  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:55:15.327  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@12a07940 added. We now have 6 listener(s)
08-19 17:55:15.327  6361  6416 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-19 17:55:15.327  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:55:15.327  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1ac55079 added. We now have 7 listener(s)
08-19 17:55:15.327  6361  6416 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-19 17:55:15.337  6361  6416 I System.out: IsBluetoothEnabled
,08-19 17:55:15.337  6361  6416 D BluetoothAdapter: disable()
,08-19 17:55:15.337  1021  1727 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.,
,08-19 17:55:15.347  6361  6416 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:15.347  6361  6416 D BluetoothAdapter: enable()
,08-19 17:55:15.347  1021  1728 W ActivityManager: Permission Denial: getCurrentUser() from pid=6361, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-19 17:55:15.347  1021  1728 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-19 17:55:15.347  1021  1728 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6361, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-19 17:55:15.347  1021  1728 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-19 17:55:15.347  1021  1728 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-19 17:55:15.347  1021  1728 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-19 17:55:15.347  1021  1728 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-19 17:55:15.347  1021  1728 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-19 17:55:15.347  1021  1728 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-19 17:55:15.347  1021  1728 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-19 17:55:15.357  1021  1728 D SettingsProvider: name = bluetooth_on,
,08-19 17:55:15.357  1021  1050 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-19 17:55:15.357  1021  1050 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-19 17:55:15.367  1021  1050 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-19 17:55:15.367  2760  2816 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-19 17:55:15.367  2760  2816 D BluetoothAdapterProperties: Setting state to 11
08-19 17:55:15.377  2760  2816 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11,
08-19 17:55:15.377  2760  2816 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-19 17:55:15.377  2760  2816 D BluetoothAdapterService: updateAdapterState state is 11
08-19 17:55:15.377  2760  2816 D BluetoothAdapterService: Autoconnection is available 
08-19 17:55:15.377  2760  2816 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
08-19 17:55:15.377  2760  2816 D BtConfig.SecureMode: isSecureModeOn:false
08-19 17:55:15.377  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-19 17:55:15.377  2760  2816 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
08-19 17:55:15.377  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-19 17:55:15.377  2760  2816 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
08-19 17:55:15.377  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-19 17:55:15.377  1021  3874 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:55:15.377  2760  2816 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
08-19 17:55:15.377  1021  3874 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-19 17:55:15.377  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-19 17:55:15.377  2760  2816 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
08-19 17:55:15.377  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-19 17:55:15.377  2760  2816 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
08-19 17:55:15.377  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-19 17:55:15.377  2760  2816 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10,
08-19 17:55:15.377  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-19 17:55:15.377  2760  2816 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
08-19 17:55:15.377  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-19 17:55:15.377  2760  2816 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
08-19 17:55:15.377  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-19 17:55:15.377  2760  2816 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-19 17:55:15.377  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-19 17:55:15.377  2760  2816 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService,
08-19 17:55:15.377  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-19 17:55:15.377  2760  2816 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-19 17:55:15.377  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-19 17:55:15.377  2760  2816 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-19 17:55:15.377  2760  2816 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
08-19 17:55:15.377  2760  2816 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-19 17:55:15.377  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-19 17:55:15.377  2760  2816 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-19 17:55:15.377  1021  3874 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:15.377  1021  3874 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:15.377  1021  3874 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:15.377  2760  2816 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-19 17:55:15.377  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-19 17:55:15.377  2760  2816 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-19 17:55:15.387  1021  1021 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:15.387  1021  1021 I InputMethodManagerService: [BT Setting State] State =11
,08-19 17:55:15.387  2760  2760 D HeadsetService: Received start request. Starting profile...
08-19 17:55:15.387  2760  2760 D HeadsetService: start()
08-19 17:55:15.387  2760  2760 D HeadsetStateMachine: make
,08-19 17:55:15.387  2760  2760 E HeadsetStateMachine: # of Max HF connection is 2,
,08-19 17:55:15.387  1179  1179 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-19 17:55:15.397  1179  1179 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-19 17:55:15.397  1179  1179 D BluetoothTile:  getBluetoothState : 11
,08-19 17:55:15.397  1935  1935 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-19 17:55:15.397  4447  4447 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-19 17:55:15.397  1021  1524 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-19 17:55:15.397  6361  6361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:15.407  1179  1700 D BluetoothTile:  handleUpdatestate:false name:null
,08-19 17:55:15.407  1179  1179 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-19 17:55:15.407  1179  1700 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-19 17:55:15.407  1021  1125 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-19 17:55:15.407  1021  4073 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-19 17:55:15.407  1021  4073 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-19 17:55:15.407  1021  4073 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:15.407  1021  4073 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:15.407  1021  4073 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-19 17:55:15.407  1021  4075 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:55:15.407  1021  4075 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-19 17:55:15.407  1021  4075 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:15.407  1021  4075 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:15.407  1021  4075 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:15.407  1021  1033 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-19 17:55:15.407  1021  1033 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-19 17:55:15.417  2760  2816 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-19 17:55:15.417  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-19 17:55:15.417  2760  2816 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-19 17:55:15.417  1021  1033 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:15.417  1021  1033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:15.417  1021  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-19 17:55:15.417  2760  2760 I bluedroid: get_profile_interface handsfree
,08-19 17:55:15.417  1681  1681 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-19 17:55:15.417  1021  4074 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:55:15.417  1021  4074 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-19 17:55:15.417  1021  4074 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:15.417  1021  4074 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:15.417  1021  4074 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:15.417  1179  1179 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-19 17:55:15.427  2760  2816 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-19 17:55:15.427  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-19 17:55:15.427  2760  2816 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-19 17:55:15.427  1021  1728 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:55:15.427  1021  1728 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-19 17:55:15.427  1021  1728 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:15.427  1021  1728 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:15.427  1021  1728 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:15.437  2760  2816 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,08-19 17:55:15.437  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-19 17:55:15.437  2760  2816 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-19 17:55:15.437  4447  4447 D BluetoothNotiBroadcastReceiver: onReceive
,08-19 17:55:15.437  1021  4073 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-19 17:55:15.437  1021  4073 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-19 17:55:15.447  1021  4073 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:15.447  1021  4073 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:15.447  1021  4073 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:15.447  2760  2760 E DualScoManager: Dual Sco Manager already instantiated
,08-19 17:55:15.447  2760  2760 I DualScoManager: Set HeadsetServiceHelper
,08-19 17:55:15.447  2760  2760 D BluetoothAtMessage: createCMTIContentObservers
08-19 17:55:15.447  2760  2816 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,08-19 17:55:15.447  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-19 17:55:15.447  2760  2816 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-19 17:55:15.447  1021  1499 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-19 17:55:15.447  1021  1499 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-19 17:55:15.447  1021  1225 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,08-19 17:55:15.447  1021  1225 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-19 17:55:15.447  1021  1225 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-19 17:55:15.457  1021  1499 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:15.457  1021  1499 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-19 17:55:15.457  1021  1225 D SettingsProvider: selectionArgs: false
08-19 17:55:15.457  1021  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:15.457  1021  1225 D SettingsProvider: selectionArgs: 1002
08-19 17:55:15.457  1021  1225 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-19 17:55:15.457  1021  1225 D SettingsProvider: ret = -1
,08-19 17:55:15.457  2760  6614 D HeadsetStateMachine: Enter Disconnected: -2
,08-19 17:55:15.457  2760  2816 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
,08-19 17:55:15.457  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-19 17:55:15.457  2760  2816 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-19 17:55:15.467  1179  1179 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-19 17:55:15.467  1179  1179 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-19 17:55:15.467  1021  1033 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-19 17:55:15.467  1021  1033 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-19 17:55:15.467  1021  1033 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:15.467  1021  1033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:15.467  1021  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:15.467  2760  2816 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-19 17:55:15.467  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-19 17:55:15.467  2760  2816 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-19 17:55:15.467  2760  2816 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-19 17:55:15.467  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-19 17:55:15.467  2760  2816 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-19 17:55:15.467  2760  2816 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-19 17:55:15.467  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-19 17:55:15.467  2760  2816 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-19 17:55:15.467  2760  2816 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-19 17:55:15.467  2760  2816 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-19 17:55:15.467  2760  2816 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-19 17:55:15.467  2760  2816 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-19 17:55:15.467  2760  2760 D HeadsetService: mStartError = false
08-19 17:55:15.467  2760  2760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@68341b0
08-19 17:55:15.467  2760  2760 D HeadsetStateMachine: Try to query the phonestate on bind
,08-19 17:55:15.467  1458  1466 I Telecom : BluetoothPhoneService: queryPhoneState
,08-19 17:55:15.477  1458  1458 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-19 17:55:15.477  1458  1458 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-19 17:55:15.477  2760  6614 D HeadsetStateMachine: Clear mHeadsetBrsf
08-19 17:55:15.477  2760  6614 D HeadsetStateMachine: map size, before remove : 0
08-19 17:55:15.477  2760  6614 D HeadsetStateMachine: map size, after remove: 0
08-19 17:55:15.477  1458  1466 I Telecom : BluetoothPhoneService: Result of Message : true
,08-19 17:55:15.477  2760  2760 D HeadsetStateMachine: Proxy object connected
,08-19 17:55:15.477  2760  2760 D A2dpService: Received start request. Starting profile...
08-19 17:55:15.477  2760  2760 D A2dpService: start()
08-19 17:55:15.477  2760  2760 I bluedroid: get_profile_interface avrcp
,08-19 17:55:15.477  2760  2760 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-19 17:55:15.477  2760  2760 D Avrcp   : Initialize Media Controller
08-19 17:55:15.477  2760  2760 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-19 17:55:15.487  2760  2760 E Avrcp   : getActiveSessions
,08-19 17:55:15.487  2760  2760 D Avrcp   : pick active media Controller
08-19 17:55:15.487  2760  2760 D Avrcp   : Get the active Media Controller 
,08-19 17:55:15.487  2760  2760 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-19 17:55:15.487  2760  6615 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-19 17:55:15.487  2760  2760 D A2dpStateMachine: make
,08-19 17:55:15.497  2760  6615 D BluetoothMediaBrowser: no now playing list
,08-19 17:55:15.497  2760  6615 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-19 17:55:15.497  2760  2760 I bluedroid: get_profile_interface a2dp
,08-19 17:55:15.507  2760  6617 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-19 17:55:15.507  2760  2760 E bt-btif : warning : media task started media_task_refcnt 1 
,08-19 17:55:15.507  2760  2760 D A2dpService: mStartError = false
08-19 17:55:15.507  2760  2760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@68341b0
08-19 17:55:15.507  2760  2760 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-19 17:55:15.507  2760  6614 D HeadsetStateMachine: Disconnected process message: 11
,08-19 17:55:15.507  2760  6616 D A2dpStateMachine: Enter Disconnected: -2
08-19 17:55:15.507  2760  2760 D HidService: Received start request. Starting profile...
08-19 17:55:15.507  2760  2760 D HidService: start()
08-19 17:55:15.507  2760  2760 I bluedroid: get_profile_interface hidhost
08-19 17:55:15.507  2760  2760 D HidService: setHidService(): set to: null
08-19 17:55:15.507  2760  2760 D HidService: mStartError = false
08-19 17:55:15.507  2760  2760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@68341b0
08-19 17:55:15.507  2760  2760 D HeadsetPhoneState: sendDeviceDataStateChanged
08-19 17:55:15.507  2760  2760 D HeadsetPhoneState: Signal level : previous=0 curr=4
,08-19 17:55:15.507  2760  2760 D HealthService: Received start request. Starting profile...
08-19 17:55:15.507  2760  2760 D HealthService: start()
,08-19 17:55:15.507  2760  6614 D HeadsetStateMachine: Disconnected process message: 18
,08-19 17:55:15.507  2760  2760 I bluedroid: get_profile_interface health
08-19 17:55:15.507  2760  2760 D HealthService: mStartError = false
08-19 17:55:15.507  2760  2760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@68341b0
,08-19 17:55:15.507  2760  2760 D PanService: Received start request. Starting profile...
,08-19 17:55:15.507  2760  2760 D PanService: start()
08-19 17:55:15.507  2760  2760 D BluetoothPanServiceJni: initializeNative(L110): pan
08-19 17:55:15.507  2760  2760 I bluedroid: get_profile_interface pan
08-19 17:55:15.507  2760  2760 D PanService: mStartError = false
08-19 17:55:15.507  2760  2760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@68341b0
,08-19 17:55:15.507  2760  2760 D BluetoothMapService: Received start request. Starting profile...
08-19 17:55:15.507  2760  2760 D BluetoothMapService: start(),
,08-19 17:55:15.517  2760  2760 D BluetoothMapService: mStartError = false
,08-19 17:55:15.517  2760  2760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@68341b0
,08-19 17:55:15.517  2760  2760 D SapService: Received start request. Starting profile...
,08-19 17:55:15.517  2760  2760 D SapService: start()
08-19 17:55:15.517  2760  2760 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-19 17:55:15.517  2760  2760 I bluedroid: get_profile_interface sap
,08-19 17:55:15.517  2760  2760 D SapService: mStartError = false
,08-19 17:55:15.517  2760  2760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@68341b0
,08-19 17:55:15.517  2760  2760 E BluetoothAdapterService(109265328): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-19 17:55:15.517  2760  2760 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-19 17:55:15.527  2760  6614 D HeadsetStateMachine: Disconnected process message: 10
08-19 17:55:15.527  2760  6614 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-19 17:55:15.527  2760  6614 D HeadsetStateMachine: Disconnected process message: 11
,08-19 17:55:15.527  2760  2760 E BluetoothAdapterService(109265328): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
,08-19 17:55:15.527  2760  2760 E BluetoothAdapterService(109265328): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,08-19 17:55:15.527  2760  2760 E BluetoothAdapterService(109265328): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,08-19 17:55:15.527  2760  2760 E BluetoothAdapterService(109265328): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-19 17:55:15.537  2760  2760 E BluetoothAdapterService(109265328): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-19 17:55:15.547  2760  2760 E BluetoothAdapterService(109265328): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-19 17:55:15.547  2760  2816 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-19 17:55:15.547  2760  2816 I bluedroid: enable
,08-19 17:55:15.547  2760  2819 E bt-btif : Calling BTA_HhEnable
,08-19 17:55:15.557  2760  2819 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,08-19 17:55:15.557  2760  2819 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,08-19 17:55:15.557  2760  2819 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-19 17:55:15.557  2760  2819 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
08-19 17:55:15.557  2760  2819 E BluetoothServiceJni: populateRssiValuesNative
08-19 17:55:15.557  2760  2819 I bluedroid: getModelRssiValues
08-19 17:55:15.557   326   326 I ServiceManager: Waiting for service AtCmdFwd...
08-19 17:55:15.557  2760  2819 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-19 17:55:15.557  2760  2819 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-19 17:55:15.557  2760  2819 D BluetoothAdapterProperties: Name is: Galaxy A3
,08-19 17:55:15.557  1021  1021 D SettingsProvider: name = bluetooth_name
,08-19 17:55:15.567  6361  6361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:15.567  2760  2819 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-19 17:55:15.567  2760  2819 D BluetoothAdapterProperties: Scan Mode:20
,08-19 17:55:15.567  2760  2819 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-19 17:55:15.567  2760  2819 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
,08-19 17:55:15.567  2760  2819 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
08-19 17:55:15.567  2760  2819 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,08-19 17:55:15.567  2760  2819 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,08-19 17:55:15.567  2760  2819 E bt-btif : JVenable fails
,08-19 17:55:15.567  2760  2819 D bte_conf: Device ID record 1 : primary
,08-19 17:55:15.567  2760  2819 D bte_conf:   vendorId            = 0075
08-19 17:55:15.567  2760  2819 D bte_conf:   vendorIdSource      = 0001
,08-19 17:55:15.577  2760  2819 D bte_conf:   product             = 0100
08-19 17:55:15.577  2760  2819 D bte_conf:   version             = 0200
08-19 17:55:15.577  2760  2819 D bte_conf:   clientExecutableURL = 
08-19 17:55:15.577  2760  2819 D bte_conf:   serviceDescription  = 
08-19 17:55:15.577  2760  2819 D bte_conf:   documentationURL    = 
08-19 17:55:15.577  2760  2819 D bte_conf: bte_load_did_conf no section named DID2.
08-19 17:55:15.577  2760  2819 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-19 17:55:15.577  2760  2819 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-19 17:55:15.577  2760  2816 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-19 17:55:15.577  2760  2816 D BluetoothAdapterProperties: ScanMode =  20
08-19 17:55:15.577  2760  2816 D BluetoothAdapterProperties: State =  11
,08-19 17:55:15.577  1021  1499 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-19 17:55:15.577  2760  2816 D BluetoothAdapterProperties: Setting state to 12
,08-19 17:55:15.577  2760  2816 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-19 17:55:15.577  1021  1225 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-19 17:55:15.577  1021  1225 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-19 17:55:15.577  1021  1225 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-19 17:55:15.577  1021  1225 D SettingsProvider: selectionArgs: false
08-19 17:55:15.577  1021  1225 D SettingsProvider: selectionArgs: 1002
08-19 17:55:15.577  1021  1225 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-19 17:55:15.577  1021  1225 D SettingsProvider: ret = -1
,08-19 17:55:15.577  2760  2816 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-19 17:55:15.577  2760  2816 D BluetoothAdapterService: updateAdapterState state is 12
,08-19 17:55:15.577  1021  1225 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:55:15.577  2760  2819 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-19 17:55:15.577  1021  1225 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-19 17:55:15.577  2760  2819 D BluetoothAdapterProperties: Scan Mode:21
08-19 17:55:15.577  2760  2819 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-19 17:55:15.577  1021  1225 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:15.577  1021  1225 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:15.577  1021  1225 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:15.587  2760  2816 D BluetoothAdapterService: Autoconnection is available 
08-19 17:55:15.587  2760  2816 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-19 17:55:15.587  2760  2816 D BluetoothAdapterService: starting service from this receiver
,08-19 17:55:15.587  1021  1727 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-19 17:55:15.587  1021  1727 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-19 17:55:15.587  1021  1727 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:15.587  1021  1727 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-19 17:55:15.587  1021  1727 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:15.587  2760  2760 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
08-19 17:55:15.587  2760  2760 I BluetoothPbapService: Handler(): got msg=1
,08-19 17:55:15.587  4447  4457 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-19 17:55:15.587  1021  1225 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-19 17:55:15.597  2760  2816 I BluetoothAdapterState: Entering On State from state = 11
,08-19 17:55:15.597  1021  1050 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-19 17:55:15.597  1021  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-19 17:55:15.597  6361  6361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:55:15.597  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:15.597  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:55:15.597  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
,08-19 17:55:15.597  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:55:15.597  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:15.597  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:15.597  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:55:15.597  6361  6361 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:55:15.597  1021  1050 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:15.597  1021  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:15.607  1021  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:15.607  2760  6622 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-19 17:55:15.607  2760  6622 D BluetoothSocket: bindListen(): myUserId = 0
08-19 17:55:15.607  2760  6622 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-19 17:55:15.607  4447  4455 D Bluetoothsap: onBluetoothStateChange: up=true
08-19 17:55:15.607  4447  4455 D Bluetoothsap: Binding service...
,08-19 17:55:15.607  4447  4455 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-19 17:55:15.617  4447  4447 D BluetoothInputDevice: Proxy object connected
,08-19 17:55:15.617  2760  6622 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-19 17:55:15.617  1021  1050 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-19 17:55:15.617  2760  6622 D BluetoothSocket: bindListen(), new LocalSocket 
08-19 17:55:15.617  1021  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-19 17:55:15.617  2760  6622 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-19 17:55:15.617  2760  6622 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@a077ec0
08-19 17:55:15.617  4447  4447 D HidProfile: Bluetooth service connected
,08-19 17:55:15.617  1021  1050 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:15.617  1021  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:15.617  1021  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:15.617  2760  6622 D BluetoothSocket: channel: 19
08-19 17:55:15.617  2760  6622 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
08-19 17:55:15.617  4447  4455 D Bluetoothsap: bindService called to Bluetooth SAP Service
08-19 17:55:15.617  1681  1698 D BluetoothAdapter: onBluetoothStateChange: up=true
08-19 17:55:15.617  1681  1698 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-19 17:55:15.617  1179  1194 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-19 17:55:15.617  1179  1194 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-19 17:55:15.617  1458  1474 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-19 17:55:15.617  4447  4447 D Bluetoothsap: BluetoothSAP Proxy object connected
08-19 17:55:15.617  1021  1050 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-19 17:55:15.617  1021  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-19 17:55:15.617  1021  1050 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:15.617  1021  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:15.617  1021  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:15.617  1458  1474 E BluetoothHeadset: BluetoothHeadset service is binded
,08-19 17:55:15.617  6496  6506 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-19 17:55:15.617  6496  6506 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-19 17:55:15.617  4447  4447 D SapProfile: Bluetooth service connected
08-19 17:55:15.617  4447  4447 D Bluetoothsap: getConnectedDevices()
,08-19 17:55:15.617  1476  1723 D BluetoothAdapter: onBluetoothStateChange: up=true
08-19 17:55:15.617  1476  1723 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-19 17:55:15.627  1476  1725 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-19 17:55:15.627  1021  1050 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-19 17:55:15.627  1021  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-19 17:55:15.627  1021  1050 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:15.627  1021  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:15.627  1021  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
08-19 17:55:15.627  1476  1725 E BluetoothHeadset: BluetoothHeadset service is binded
,08-19 17:55:15.627  2760  2770 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-19 17:55:15.627  2760  2770 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-19 17:55:15.627  1021  1050 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-19 17:55:15.627  1021  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-19 17:55:15.627  1021  1050 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:15.627  1021  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:15.627  1021  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:15.627  1021  1050 D BluetoothPan: Binding service...
08-19 17:55:15.627  1021  1050 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-19 17:55:15.627  1021  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-19 17:55:15.637  1021  1021 D BluetoothPan: BluetoothPAN Proxy object connected
08-19 17:55:15.637  2760  2760 D BluetoothA2dp: Proxy object connected
08-19 17:55:15.637  2760  2760 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-19 17:55:15.637  4447  4457 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-19 17:55:15.637  4447  4457 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-19 17:55:15.637  1021  1050 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-19 17:55:15.637  1021  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-19 17:55:15.637  1021  1050 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:15.637  1021  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:15.637  1021  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:15.637  1729  1740 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-19 17:55:15.637  1729  1740 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-19 17:55:15.637  4447  6462 D BluetoothAdapter: onBluetoothStateChange: up=true
08-19 17:55:15.637  4447  6462 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-19 17:55:15.637  4447  4447 D BluetoothA2dp: Proxy object connected
08-19 17:55:15.637  4447  4457 D BluetoothPan: Binding service...
08-19 17:55:15.637  4447  4447 D A2dpProfile: Bluetooth service connected
,08-19 17:55:15.647  1021  1050 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-19 17:55:15.647  1021  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-19 17:55:15.647  1021  1050 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:15.647  1021  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:15.647  1021  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:15.647  4447  4447 D BluetoothPan: BluetoothPAN Proxy object connected
,08-19 17:55:15.647  6361  6369 D BluetoothAdapter: onBluetoothStateChange: up=true
08-19 17:55:15.647  6361  6369 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-19 17:55:15.647  4447  4447 D PanProfile: Bluetooth service connected
,08-19 17:55:15.647  1458  1466 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-19 17:55:15.647  1021  1050 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-19 17:55:15.647  1021  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-19 17:55:15.647  1021  1050 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:15.647  1021  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-19 17:55:15.647  1021  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:15.647  1458  1466 E BluetoothHeadset: BluetoothHeadset service is binded
,08-19 17:55:15.647  1458  6589 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-19 17:55:15.647  1458  6589 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-19 17:55:15.647  4447  4457 D BluetoothMap: onBluetoothStateChange: up=true
,08-19 17:55:15.657  1021  1050 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,08-19 17:55:15.657  1021  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-19 17:55:15.657  1021  1050 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:15.657  1021  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:15.657  1021  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:15.657  1468  1746 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-19 17:55:15.657  1468  1746 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-19 17:55:15.657  4447  4447 D BluetoothMap: Proxy object connected
08-19 17:55:15.657  4447  4447 D MapProfile: Bluetooth service connected
08-19 17:55:15.657  4447  4447 D BluetoothMap: getConnectedDevices()
,08-19 17:55:15.657  1458  1474 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-19 17:55:15.657  1021  1050 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-19 17:55:15.657  1021  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-19 17:55:15.657  1021  1050 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:15.657  1021  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:15.657  1021  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:15.657  1458  1474 E BluetoothHeadset: BluetoothHeadset service is binded
,08-19 17:55:15.657  2760  6593 D BluetoothAdapter: onBluetoothStateChange: up=true
08-19 17:55:15.667  2760  6593 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-19 17:55:15.667  1021  1050 D BluetoothAdapter: onBluetoothStateChange: up=true
08-19 17:55:15.667  1021  1050 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-19 17:55:15.667  1021  1050 D BluetoothA2dp: onBluetoothStateChange: up=true
08-19 17:55:15.667  1021  1050 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-19 17:55:15.667  1021  1050 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-19 17:55:15.667  1021  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-19 17:55:15.667  1021  1021 D BluetoothA2dp: Proxy object connected
,08-19 17:55:15.667  4447  6462 D BluetoothPbap: onBluetoothStateChange: up=true
,08-19 17:55:15.667  1021  1050 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,08-19 17:55:15.667  1021  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-19 17:55:15.667  1021  1050 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:15.667  1021  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:15.667  1021  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:15.677  4447  4447 D BluetoothPbap: Proxy object connected
,08-19 17:55:15.677  4447  4455 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-19 17:55:15.677  4447  4447 D PbapServerProfile: Bluetooth service connected
08-19 17:55:15.677  1021  1050 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-19 17:55:15.677  1021  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-19 17:55:15.677  1021  1050 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:15.677  1021  1050 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:15.677  1021  1050 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-19 17:55:15.677  4447  4455 E BluetoothHeadset: BluetoothHeadset service is binded
,08-19 17:55:15.677  1021  1050 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-19 17:55:15.677  1021  1050 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-19 17:55:15.677  1021  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-19 17:55:15.677  1021  1050 E BluetoothHeadset: BluetoothHeadset service is binded
,08-19 17:55:15.677  1021  1050 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-19 17:55:15.677  1021  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-19 17:55:15.677  1458  1458 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@13b19fd4, true
,08-19 17:55:15.677  1458  1458 D BluetoothHeadset: registerMessageListener
,08-19 17:55:15.687  4447  4447 D HeadsetProfile: Bluetooth service connected
,08-19 17:55:15.687  1179  1179 D BluetoothTile:  onBluetoothStateChange:
,08-19 17:55:15.687  1935  1935 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-19 17:55:15.687  1179  1179 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-19 17:55:15.687  1179  1179 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:15.687  1179  1179 D BluetoothTile:  getBluetoothState : 12
,08-19 17:55:15.687  6361  6361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:15.697  1021  3874 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-19 17:55:15.697  1021  1546 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-19 17:55:15.697  2760  6593 D HeadsetService: registerMessageListener
,08-19 17:55:15.697  1179  1179 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-19 17:55:15.697  2760  6593 D HeadsetService: registerMessageListener
,08-19 17:55:15.697  1179  1700 D BluetoothTile:  handleUpdatestate:false name:null
,08-19 17:55:15.697  2760  6614 D HeadsetStateMachine: Disconnected process message: 70
08-19 17:55:15.697  2760  6614 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@164fa7f9
,08-19 17:55:15.697  4447  4447 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-19 17:55:15.697  1458  1458 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-19 17:55:15.697  1458  1458 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-19 17:55:15.697  1021  1021 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-19 17:55:15.697  1021  1021 I InputMethodManagerService: [BT Setting State] State =12
08-19 17:55:15.697  1021  1021 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-19 17:55:15.707  1458  1458 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,08-19 17:55:15.707  1179  1700 D BluetoothTile:  handleUpdatestate:false name:null
08-19 17:55:15.707  1458  1458 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-19 17:55:15.707  4447  4447 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-19 17:55:15.707  1458  1458 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
08-19 17:55:15.707  4447  4447 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-19 17:55:15.707  4447  4447 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-19 17:55:15.707  4447  4447 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-19 17:55:15.707  2760  6614 D HeadsetStateMachine: Disconnected process message: 9,
08-19 17:55:15.707  2760  6614 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
08-19 17:55:15.707   282   282 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-19 17:55:15.707   282   282 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-19 17:55:15.707  1179  1700 D BluetoothTile:  handleUpdatestate:false name:null
08-19 17:55:15.707   282   282 V voice   : voice_set_parameters: exit with code(-2)
,08-19 17:55:15.707   282   282 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-19 17:55:15.707   282   282 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-19 17:55:15.707   282   282 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
,08-19 17:55:15.707   282   282 V audio_hw_primary: adev_set_parameters: exit
08-19 17:55:15.707  2760  6614 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-19 17:55:15.707  2760  6624 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-19 17:55:15.707  2760  6624 D BluetoothSocket: bindListen(): myUserId = 0
,08-19 17:55:15.717  2760  6624 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-19 17:55:15.717  2760  6624 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
08-19 17:55:15.717  2760  6624 D BluetoothSocket: bindListen(), new LocalSocket 
08-19 17:55:15.717  2760  6624 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-19 17:55:15.717  2760  6624 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@28ae933e
08-19 17:55:15.717  4447  4447 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-19 17:55:15.717  2760  6624 D BluetoothSocket: channel: 5
08-19 17:55:15.717  1021  1546 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-19 17:55:15.717  1021  1546 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-19 17:55:15.717  1021  1546 W ActivityManager: userId = 0, bbcId = -10000,
08-19 17:55:15.717  1021  1546 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:15.717  1021  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-19 17:55:15.717  1681  1681 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-19 17:55:15.727  4447  4447 D DockEventReceiver: finishStartingService: stopping service
,08-19 17:55:15.727  4447  4447 D BluetoothNotiBroadcastReceiver: onReceive
,08-19 17:55:15.727  1179  1179 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-19 17:55:15.727  1179  1179 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-19 17:55:15.737  2760  2760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@68341b0
,08-19 17:55:15.737  2760  2760 D BtConfig.SecureMode: isSecureModeOn:false
,08-19 17:55:15.737  1021  1508 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-19 17:55:15.737  1021  1508 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-19 17:55:15.737  1021  1508 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:15.737  1021  1508 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-19 17:55:15.737  1021  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-19 17:55:15.757  1021  3874 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-19 17:55:15.757  2760  6629 D BluetoothSocket: bindListen(): myUserId = 0
,08-19 17:55:15.757  2760  6629 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-19 17:55:15.767  2760  6629 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[88]}
08-19 17:55:15.767  2760  6629 D BluetoothSocket: bindListen(), new LocalSocket 
08-19 17:55:15.767  2760  6629 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-19 17:55:15.767  2760  6629 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3c7ca54a
08-19 17:55:15.767  2760  6629 D BluetoothSocket: channel: 12
08-19 17:55:15.767  2760  6629 I BtOppRfcommListener: Accept thread started.
,08-19 17:55:16.367  6361  6416 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:55:16.367  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:16.367  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:55:16.367  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-19 17:55:16.367  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:55:16.367  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:16.367  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:16.367  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:55:16.377  6361  6416 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:55:16.377  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-19 17:55:16.377  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3b1e51be added. We now have 8 listener(s)
,08-19 17:55:16.377  6361  6416 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-19 17:55:16.377  1021  4075 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-19 17:55:16.377  1021  4075 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-19 17:55:16.377  1021  4075 D SecContentProvider2: mCursor = null
,08-19 17:55:16.377  1021  4075 D WifiService: setWifiEnabled: false pid=6361, uid=10170
,08-19 17:55:16.387  1021  4075 D SettingsProvider: name = wifi_on
,08-19 17:55:16.387  6361  6416 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:16.387  1021  1225 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-19 17:55:16.387  1021  1225 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-19 17:55:16.387  1021  1225 D SecContentProvider2: mCursor = null
,08-19 17:55:16.387  1021  1225 D WifiService: setWifiEnabled: true pid=6361, uid=10170
,08-19 17:55:16.387  1021  1225 W ActivityManager: Permission Denial: getCurrentUser() from pid=6361, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-19 17:55:16.387  1021  1225 W WifiService: Failed getting userId using ActivityManagerNative
08-19 17:55:16.387  1021  1225 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6361, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-19 17:55:16.387  1021  1225 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-19 17:55:16.387  1021  1225 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-19 17:55:16.387  1021  1225 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-19 17:55:16.387  1021  1225 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-19 17:55:16.387  1021  1225 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-19 17:55:16.397  1021  1225 D SettingsProvider: name = wifi_on
,08-19 17:55:16.397  1021  1130 E WifiHW  : ##################### set firmware type 0 #####################
,08-19 17:55:16.557   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,08-19 17:55:16.727  1021  1048 D Tethering: interfaceAdded wlan0
,08-19 17:55:16.727  1021  1134 E Tethering: No numeric data
,08-19 17:55:16.737  1021  1134 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-19 17:55:16.737  1021  1134 D Tethering: clearTetheredNotification()
,08-19 17:55:16.737  1021  1127 D NtpTrustedTime: forceRefresh() from cache miss,
,08-19 17:55:16.737   277  1004 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-19 17:55:16.737  1179  1179 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-19 17:55:16.737   277  1004 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-19 17:55:16.737  1179  1179 D HotspotTile: updateTetherState():false, false
08-19 17:55:16.737   277  1004 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-19 17:55:16.747  1021  1127 V NetworkStats: performPollLocked(flags=0x1)
08-19 17:55:16.737   277  1004 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-19 17:55:16.747  1021  1127 D NtpTrustedTime: forceRefresh Fail.
,08-19 17:55:16.747  1021  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-19 17:55:16.747  1021  1127 V NetworkStats: performPollLocked() took 5ms
08-19 17:55:16.747  1021  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-19 17:55:16.747  1021  1048 D Tethering: interfaceLinkStateChanged wlan0, false
,08-19 17:55:16.747  1021  1048 D Tethering: interfaceStatusChanged wlan0, false,
,08-19 17:55:16.757  1021  1128 D NtpTrustedTime: forceRefresh() from cache miss
08-19 17:55:16.757  1021  1048 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-19 17:55:16.757  1021  1134 D Tethering: InitialState.processMessage what=4
08-19 17:55:16.757  1021  1128 D NtpTrustedTime: forceRefresh Fail.
08-19 17:55:16.757  1021  1134 E Tethering: No numeric data
08-19 17:55:16.757  1021  1134 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-19 17:55:16.757  1021  1134 D Tethering: clearTetheredNotification()
,08-19 17:55:16.757  1021  1048 D Tethering: interfaceAdded p2p0
,08-19 17:55:16.767  1021  1048 D Tethering: p2p0 is not a tetherable iface, ignoring,
,08-19 17:55:16.767  1021  1048 D Tethering: interfaceLinkStateChanged p2p0, false
08-19 17:55:16.767  1179  1179 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-19 17:55:16.767  1021  1048 D Tethering: interfaceStatusChanged p2p0, false
,08-19 17:55:16.767  1179  1179 D HotspotTile: updateTetherState():false, false
08-19 17:55:16.767   277  1008 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-19 17:55:16.767  1021  1127 V NetworkStats: performPollLocked(flags=0x1)
08-19 17:55:16.767  1021  1127 D NtpTrustedTime: forceRefresh() from cache miss
08-19 17:55:16.767   277  1008 D SoftapController: Softap fwReload - Ok
08-19 17:55:16.767  1021  1127 D NtpTrustedTime: forceRefresh Fail.
,08-19 17:55:16.777   277  1008 D CommandListener: Setting iface cfg
08-19 17:55:16.777   277  1008 D CommandListener: Trying to bring down wlan0
,08-19 17:55:16.777  1021  1048 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-19 17:55:16.777  1021  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-19 17:55:16.777  1021  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-19 17:55:16.777   277  1008 D CommandListener: Clearing all IP addresses on wlan0
,08-19 17:55:16.777  1021  1127 V NetworkStats: performPollLocked() took 6ms
,08-19 17:55:16.777  1021  1128 D NtpTrustedTime: forceRefresh() from cache miss
,08-19 17:55:16.777  1021  1128 D NtpTrustedTime: forceRefresh Fail.
,08-19 17:55:16.777  1021  1130 E WifiHW  : supplicant_name : p2p_supplicant
,08-19 17:55:16.787  1021  1130 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-19 17:55:16.807  4447  4447 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-19 17:55:16.807  6361  6361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:16.807  1021  1033 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-19 17:55:16.807  1021  1033 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-19 17:55:16.807  1021  1033 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:16.807  1021  1033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:16.807  1021  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-19 17:55:16.807  1179  1179 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-19 17:55:16.807  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-19 17:55:16.807  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-19 17:55:16.807  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:16.807  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:16.807  1179  1179 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-19 17:55:16.807  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:16.807  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:16.807  1179  1179 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-19 17:55:16.807  1179  1179 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-19 17:55:16.807  1631  1631 I Hs20UtilService: Starting #12
08-19 17:55:16.807  1631  1654 I Hs20UtilService: Message received 5011
08-19 17:55:16.807  1179  1700 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-19 17:55:16.807  1179  1179 D HotspotTile: onReceive : 2, 0
,08-19 17:55:16.817  6463  6463 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-19 17:55:16.817  6463  6463 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-19 17:55:16.817  6463  6463 D SecurityLogAgent: StateMachine : Current State = 1
08-19 17:55:16.817  6463  6463 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-19 17:55:16.827   287   287 E SMD     : DCD OFF,
,08-19 17:55:16.837  6643  6643 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-19 17:55:16.837  6643  6643 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-19 17:55:16.837  6643  6643 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-19 17:55:16.847  6643  6643 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
08-19 17:55:16.847   401   401 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6643
,08-19 17:55:16.847   401   401 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-19 17:55:16.847  6643  6643 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-19 17:55:16.847  6643  6643 I wpa_supplicant: ssSupport state is = 1
08-19 17:55:16.847  6643  6643 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
,08-19 17:55:16.847  6643  6643 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-19 17:55:16.847   401   401 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6643
08-19 17:55:16.847   401   401 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-19 17:55:17.007   401   401 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,08-19 17:55:17.017  6643  6643 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed,
,08-19 17:55:17.057  6643  6643 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-19 17:55:17.057  6643  6643 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-19 17:55:17.067  6643  6643 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-19 17:55:17.067   401   401 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6643
08-19 17:55:17.067   401   401 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
08-19 17:55:17.067  6643  6643 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-19 17:55:17.067  6643  6643 I wpa_supplicant: ssSupport state is = 1
08-19 17:55:17.067  6643  6643 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-19 17:55:17.067  6643  6643 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-19 17:55:17.067  6643  6643 E wpa_supplicant: SIM READ ERROR
08-19 17:55:17.067  6643  6643 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-19 17:55:17.067  6643  6643 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-19 17:55:17.067  6643  6643 E wpa_supplicant: SIM READ ERROR
08-19 17:55:17.067  6643  6643 I wpa_supplicant: Blacklist: Clear (all) ,
08-19 17:55:17.067  6643  6643 I wpa_supplicant: wpa_default_ap_write_once
08-19 17:55:17.067  6643  6643 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-19 17:55:17.067  6643  6643 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-19 17:55:17.067  6643  6643 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-19 17:55:17.067  6643  6643 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-19 17:55:17.067  6643  6643 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
,08-19 17:55:17.067  6643  6643 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-19 17:55:17.077  1021  1048 D Tethering: interfaceLinkStateChanged wlan0, false
08-19 17:55:17.077  1021  1048 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-19 17:55:17.077  1021  1048 D Tethering: interfaceStatusChanged wlan0, false
,08-19 17:55:17.167  6643  6643 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-19 17:55:17.337  6643  6643 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-19 17:55:17.337  6643  6643 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-19 17:55:17.347  6643  6643 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
,08-19 17:55:17.347   401   401 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6643
,08-19 17:55:17.347   401   401 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,08-19 17:55:17.347  6643  6643 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
,08-19 17:55:17.347  6643  6643 I wpa_supplicant: ssSupport state is = 1
08-19 17:55:17.347  6643  6643 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-19 17:55:17.347  6643  6643 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-19 17:55:17.367  6643  6643 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
,08-19 17:55:17.367   401   401 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6643
08-19 17:55:17.367   401   401 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,08-19 17:55:17.367  6643  6643 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
,08-19 17:55:17.367  6643  6643 I wpa_supplicant: ssSupport state is = 1
,08-19 17:55:17.367  6643  6643 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-19 17:55:17.367  6643  6643 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-19 17:55:17.367  1021  1048 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-19 17:55:17.367  6643  6643 E wpa_supplicant: SIM READ ERROR
,08-19 17:55:17.367  1021  1048 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-19 17:55:17.367  6643  6643 I wpa_supplicant: wpa_default_ap_write_once
,08-19 17:55:17.367  6643  6643 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
,08-19 17:55:17.367  6643  6643 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-19 17:55:17.367  1021  1048 D Tethering: interfaceLinkStateChanged p2p0, false
08-19 17:55:17.367  1021  1048 D Tethering: interfaceStatusChanged p2p0, false
,08-19 17:55:17.367  1021  1048 D Tethering: interfaceLinkStateChanged p2p0, false
,08-19 17:55:17.367  1021  1048 D Tethering: interfaceStatusChanged p2p0, false
,08-19 17:55:17.487  6643  6643 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-19 17:55:17.487  6643  6643 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-19 17:55:17.527  6643  6643 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,08-19 17:55:17.527  6643  6643 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-19 17:55:17.527  6643  6643 I wpa_supplicant: Skip scan - bUseNetwork false
,08-19 17:55:17.537  1021  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
08-19 17:55:17.537  1021  1130 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-19 17:55:17.537  6643  6643 I wpa_supplicant: HOTSPOT20_ENABLE called
,08-19 17:55:17.537  6643  6643 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-19 17:55:17.537  6643  6643 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-19 17:55:17.537  6643  6643 E wpa_supplicant: SIM READ ERROR
08-19 17:55:17.537  6643  6643 I wpa_supplicant: Blacklist: Clear (all) 
,08-19 17:55:17.547  6643  6643 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-19 17:55:17.557  6643  6643 I wpa_supplicant: Skip scan - bUseNetwork false
08-19 17:55:17.557   326   326 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-19 17:55:17.557  1021  1130 D WifiConfigStore: Loading config and enabling all networks 
,08-19 17:55:17.567  1179  1179 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
08-19 17:55:17.567  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-19 17:55:17.567  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-19 17:55:17.567  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-19 17:55:17.567  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:17.567  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:17.567  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-19 17:55:17.567  1179  1179 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-19 17:55:17.567  1179  1179 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-19 17:55:17.567  1179  1179 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-19 17:55:17.567  1179  1700 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-19 17:55:17.567  1179  1179 D HotspotTile: onReceive : 3, 0
,08-19 17:55:17.577  4447  4447 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-19 17:55:17.577  6361  6361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:55:17.577  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:17.577  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:55:17.577  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:55:17.577  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:55:17.577  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:17.577  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:17.577  6361  6361 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:55:17.577  6361  6361 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:55:17.587  1021  1130 E WifiConfigStore: Not a HS20
,08-19 17:55:17.587  1021  1125 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-19 17:55:17.587  1021  1125 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-19 17:55:17.587  1021  1125 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:17.587  1021  1125 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:17.587  1021  1125 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-19 17:55:17.587  1021  1130 D WifiNative-wlan0: callSECApiInt - ID [65],
08-19 17:55:17.587  1631  1631 I Hs20UtilService: Starting #13
,08-19 17:55:17.587  1631  1654 I Hs20UtilService: Message received 5011
,08-19 17:55:17.587  6463  6463 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-19 17:55:17.587  1021  1130 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-19 17:55:17.597  6463  6463 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-19 17:55:17.597  6463  6463 D SecurityLogAgent: StateMachine : Current State = 1
08-19 17:55:17.597  6463  6463 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-19 17:55:17.597  6643  6643 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-19 17:55:17.597  6643  6643 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-19 17:55:17.597  6643  6643 I wpa_supplicant: reset timer : RESET_TIMER 0
08-19 17:55:17.597  6643  6643 I wpa_supplicant: P2P: Current p2p state = IDLE
08-19 17:55:17.597  6643  6643 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-19 17:55:17.597  6643  6643 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-19 17:55:17.597  6643  6643 I wpa_supplicant: First Scan Start
,08-19 17:55:17.597  6643  6643 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-19 17:55:17.597  1021  1130 D WifiNative-wlan0: Setting external_sim to 1
,08-19 17:55:17.597  1021  1130 D WifiStateMachine: Setting OUI to DA-A1-19
08-19 17:55:17.597  1021  1130 I WifiNative-HAL: startHal
08-19 17:55:17.597  1021  1130 E wifi    : getStaticLongField sWifiHalHandle 0x9f38988c
08-19 17:55:17.597  1021  1130 I WifiNative-HAL: Could not start hal
,08-19 17:55:17.607  6329  6329 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-19 17:55:17.607  1021  1130 E WifiNative-wlan0: do suspend true,
,08-19 17:55:17.607  1021  1129 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-19 17:55:17.607  1021  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-19 17:55:17.607  1021  1021 D WifiScanningService: SCAN_AVAILABLE : 3
08-19 17:55:17.607  1021  1153 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-19 17:55:17.607  1021  1153 I WifiNative-HAL: startHal
08-19 17:55:17.607  1021  1153 E wifi    : getStaticLongField sWifiHalHandle 0x9e3499bc
08-19 17:55:17.607  1021  1153 I WifiNative-HAL: Could not start hal
08-19 17:55:17.607  1021  1153 E WifiScanningService: could not start HAL
,08-19 17:55:17.607  1021  1021 D RttService: SCAN_AVAILABLE : 3,
08-19 17:55:17.607  1021  1154 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-19 17:55:17.607  1021  1130 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-19 17:55:17.607  1021  1130 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-19 17:55:17.607  1021  1130 E WifiNative-wlan0: invaild command id : 215
08-19 17:55:17.617   277  1008 D CommandListener: Setting iface cfg
08-19 17:55:17.617   277  1008 D CommandListener: Trying to bring up p2p0
08-19 17:55:17.617  1021  1130 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-19 17:55:17.617  1021  1130 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-19 17:55:17.617  1021  1130 E WifiNative-wlan0: invaild command id : 215
,08-19 17:55:17.617  1021  1129 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-19 17:55:17.617  1021  1129 D WifiP2pService: P2pEnablingState
08-19 17:55:17.617  1021  1129 D WifiP2pService: P2pEnablingState{ what=147457 }
08-19 17:55:17.617  1021  1129 D WifiP2pService: P2p socket connection successful,
08-19 17:55:17.617  1021  1129 D WifiP2pService: P2pEnabledState
08-19 17:55:17.617  1021  1129 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-19 17:55:17.617  1021  1132 E ConnectivityService: updateNetworkInfo()
,08-19 17:55:17.617  6643  6643 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-19 17:55:17.617  1021  1051 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-19 17:55:17.617  1021  1021 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-19 17:55:17.617  1021  1051 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-19 17:55:17.617  6643  6643 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-19 17:55:17.617  1021  1051 D WifiDisplayController: disconnect
08-19 17:55:17.617  1021  1051 D WifiDisplayController: updateConnection
08-19 17:55:17.617  1021  1051 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-19 17:55:17.617  1021  1051 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-19 17:55:17.617  6643  6643 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,08-19 17:55:17.627  1021  1130 E WifiStateMachine: Failed to set frequency band 0
,08-19 17:55:17.627  1021  1051 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-19 17:55:17.627  1021  1051 D WifiDisplayAdapter: onP2pDisconnected
08-19 17:55:17.627  1021  1051 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-19 17:55:17.627  1021  1051 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-19 17:55:17.627  1021  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-19 17:55:17.627  1021  1130 D SecContentProvider2: mCursor = null
,08-19 17:55:17.627  1021  1129 D WifiNative-p2p0: p2pGetDeviceAddress
,08-19 17:55:17.627  1021  1129 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,08-19 17:55:17.627  1179  1179 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-19 17:55:17.627  1021  4074 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-19 17:55:17.627  1179  1179 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-19 17:55:17.637  4447  4447 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-19 17:55:17.637  4447  4447 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null,
08-19 17:55:17.637  1021  1129 D WifiP2pService: DeviceAddress: 0a:75:42
08-19 17:55:17.637  1021  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-19 17:55:17.637  1021  1051 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
08-19 17:55:17.637  1021  1051 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
08-19 17:55:17.637  1021  1051 D WifiDisplayController:  primary type: 10-0050F204-5
08-19 17:55:17.637  1021  1051 D WifiDisplayController:  secondary type: null
08-19 17:55:17.637  1021  1051 D WifiDisplayController:  wps: 0
08-19 17:55:17.637  1021  1051 D WifiDisplayController:  grpcapab: 0
,08-19 17:55:17.637  1021  1051 D WifiDisplayController:  devcapab: 0
08-19 17:55:17.637  1021  1051 D WifiDisplayController:  status: 3
08-19 17:55:17.637  1021  1051 D WifiDisplayController:  wfdInfo: null
08-19 17:55:17.637  1021  1051 D WifiDisplayController:  groupownerAddress: null
08-19 17:55:17.637  1021  1051 D WifiDisplayController:  GOdeviceName: null
08-19 17:55:17.637  1021  1051 D WifiDisplayController:  interfaceAddress: 
08-19 17:55:17.637  1021  1051 D WifiDisplayController:  SConnectInfo : null
08-19 17:55:17.637  1021  1130 D SecContentProvider2: mCursor = null
08-19 17:55:17.637  4447  4447 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-19 17:55:17.637  4447  4447 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-19 17:55:17.637  4447  4447 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-19 17:55:17.637  4447  4447 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-19 17:55:17.637  4447  4522 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-19 17:55:17.647  6431  6431 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null,
,08-19 17:55:17.647  6431  6431 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-19 17:55:17.647  6431  6431 D FileShare-Client: Outbound.stopDelayTimer - 
,08-19 17:55:17.647  6447  6447 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-19 17:55:17.657  1021  1129 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-19 17:55:17.657  1021  1129 D WifiP2pService: InactiveState
,08-19 17:55:17.657  1021  1129 D WifiP2pService: InactiveState{ what=143376 }
08-19 17:55:17.657  1021  1129 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-19 17:55:17.657  6643  6643 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-19 17:55:17.657  1021  1129 D WifiP2pService: InactiveState{ what=143376 }
08-19 17:55:17.657  1021  1129 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-19 17:55:17.747  1021  1048 D Tethering: interfaceLinkStateChanged p2p0, false
,08-19 17:55:17.747  1021  1048 D Tethering: interfaceStatusChanged p2p0, false
,08-19 17:55:17.747  1021  1048 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-19 17:55:18.407  6361  6416 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-19 17:55:18.407  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:18.407  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:55:18.407  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:55:18.407  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:55:18.407  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:18.407  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:18.407  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:55:18.407  6361  6416 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:55:18.417  6361  6416 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}],
,08-19 17:55:18.417  6361  6416 D io.jxcore.node.LifeCycleMonitor: onActivityResumed,
,08-19 17:55:18.417  6361  6416 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1da1985e Bundle[{}]
,08-19 17:55:18.427  6361  6416 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-19 17:55:18.427  6361  6416 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-19 17:55:18.427  6361  6416 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-19 17:55:18.427  6361  6416 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-19 17:55:18.427  6361  6416 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-19 17:55:18.427  6361  6416 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-19 17:55:18.437  6361  6416 I System.out: Running OutgoingSocketThread
,08-19 17:55:18.437  6361  6650 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1266)
,08-19 17:55:18.437  6361  6650 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 50827
,08-19 17:55:18.437  6361  6650 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-19 17:55:18.827  6643  6643 I wpa_supplicant: nl80211: Received scan results (24 BSSes),
08-19 17:55:18.827  6643  6643 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec,
08-19 17:55:18.827  6643  6643 I wpa_supplicant: Trying to associate with SSID '4E47373030'
,08-19 17:55:18.827  6643  6643 I wpa_supplicant: Trying to associate with  'G700'
08-19 17:55:18.827  6643  6643 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-19 17:55:18.827  6643  6643 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,08-19 17:55:18.827  1021  6648 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-19 17:55:18.857  1021  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-19 17:55:18.857  1021  1130 D SecContentProvider2: mCursor = null
,08-19 17:55:19.437  6361  6416 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1267)
,08-19 17:55:19.437  6361  6416 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1267)
,08-19 17:55:19.437  6361  6416 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1272)
,08-19 17:55:19.437  6361  6416 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-19 17:55:19.447  6361  6416 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1273)
,08-19 17:55:19.447  6361  6416 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-19 17:55:19.447  6361  6416 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fc4e21f added. We now have 2 listener(s)
,08-19 17:55:19.447  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-19 17:55:19.447  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-19 17:55:19.447  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-19 17:55:19.447  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-19 17:55:19.457  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b3e96c added. We now have 9 listener(s)
08-19 17:55:19.457  6361  6416 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-19 17:55:19.457  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-19 17:55:19.457  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-19 17:55:19.457  6361  6416 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-19 17:55:19.457  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:19.457  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:55:19.457  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:55:19.457  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:55:19.457  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:19.457  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:19.457  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:55:19.467  6361  6416 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
08-19 17:55:19.467  6361  6416 D io.jxcore.node.ConnectivityMonitor: start: OK
08-19 17:55:19.467  6361  6361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-19 17:55:19.467  6361  6416 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-19 17:55:19.467  6361  6416 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c69cbca added. We now have 3 listener(s)
08-19 17:55:19.467  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-19 17:55:19.467  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-19 17:55:19.467  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-19 17:55:19.467  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-19 17:55:19.467  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5f813b added. We now have 10 listener(s)
08-19 17:55:19.467  6361  6416 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-19 17:55:19.467  6361  6416 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:55:19.467  6361  6416 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:55:19.467  6361  6416 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:55:19.467  6361  6416 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-19 17:55:19.467  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:19.467  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-19 17:55:19.467  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-19 17:55:19.467  6361  6416 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fc4e21f removed from the list
08-19 17:55:19.467  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
,08-19 17:55:19.467  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b3e96c removed from the list
08-19 17:55:19.467  6361  6416 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:19.467  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:19.467  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:19.467  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:19.467  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:19.467  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:19.467  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-19 17:55:19.467  6361  6416 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b3e96c not in the list
08-19 17:55:19.467  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:19.467  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:19.477  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:19.477  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:19.477  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-19 17:55:19.477  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5f813b removed from the list
08-19 17:55:19.477  6361  6416 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:19.477  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:19.477  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:19.477  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
08-19 17:55:19.477  6361  6416 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c69cbca removed from the list
08-19 17:55:19.477  6361  6416 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-19 17:55:19.477  6361  6416 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29ac3058 added. We now have 2 listener(s)
08-19 17:55:19.477  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41",
08-19 17:55:19.477  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-19 17:55:19.477  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-19 17:55:19.477  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:55:19.477  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@311b95b1 added. We now have 9 listener(s)
08-19 17:55:19.477  6361  6416 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-19 17:55:19.477  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
08-19 17:55:19.487  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-19 17:55:19.487  6361  6416 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-19 17:55:19.487  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:19.487  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:55:19.487  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:55:19.487  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:55:19.487  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:19.487  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:19.487  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:55:19.487  6361  6416 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:55:19.487  6361  6416 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-19 17:55:19.487  6361  6361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-19 17:55:19.487  6361  6416 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-19 17:55:19.487  6361  6416 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c3af617 added. We now have 3 listener(s)
,08-19 17:55:19.497  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-19 17:55:19.497  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-19 17:55:19.497  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-19 17:55:19.497  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-19 17:55:19.497  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38dffa04 added. We now have 10 listener(s)
08-19 17:55:19.497  6361  6416 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-19 17:55:19.497  6361  6416 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-19 17:55:19.497  6361  6416 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-19 17:55:19.497  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-19 17:55:19.497  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-19 17:55:19.497  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-19 17:55:19.497  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-19 17:55:19.507  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-19 17:55:19.507  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-19 17:55:19.517  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-19 17:55:19.517  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-19 17:55:19.517  6361  6416 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-19 17:55:19.517  2760  2998 D BtGatt.GattService: registerClient() - UUID=67a0ff50-ee18-4d56-ba20-e182abdfb737
,08-19 17:55:19.567  2760  2819 D BtGatt.GattService: onClientRegistered() - UUID=67a0ff50-ee18-4d56-ba20-e182abdfb737, clientIf=6
,08-19 17:55:19.567  6361  6584 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-19 17:55:19.567  2760  6446 D BtGatt.GattService: start scan with filters,
08-19 17:55:19.567  2760  2999 D BtGatt.ScanManager: handling starting scan
,08-19 17:55:19.567  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-19 17:55:19.567  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-19 17:55:19.567  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-19 17:55:19.567  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-19 17:55:19.577  6361  6416 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-19 17:55:19.577  6361  6416 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-19 17:55:19.577  6361  6361 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-19 17:55:19.577  2760  2819 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-19 17:55:19.577  2760  2819 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-19 17:55:19.577  2760  2999 D BtGatt.ScanManager: allow scan with filters
08-19 17:55:19.577  2760  2999 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-19 17:55:19.577  2760  2999 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
,08-19 17:55:19.577  2760  2819 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15,
,08-19 17:55:19.577  2760  2819 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-19 17:55:19.577  2760  2999 D BtGatt.ScanManager: Starting BLE batch scan
,08-19 17:55:19.577  2760  2999 D BtGatt.ScanManager: configuring batch scan storage, appIf 6,
08-19 17:55:19.577  2760  2819 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-19 17:55:19.577  2760  2819 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-19 17:55:19.577  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-19 17:55:19.577  2760  2819 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-19 17:55:19.587  2760  2819 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-19 17:55:19.587  6361  6416 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-19 17:55:19.587  6361  6416 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-19 17:55:19.587  6361  6416 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-19 17:55:19.587  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:19.587  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-19 17:55:19.587  6361  6416 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-19 17:55:19.587  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-19 17:55:19.587  6361  6416 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-19 17:55:19.587  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-19 17:55:19.587  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-19 17:55:19.587  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-19 17:55:19.587  2760  6446 D BtGatt.GattService: stopScan() - queue size =1
08-19 17:55:19.587  2760  6591 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-19 17:55:19.587  2760  2999 D BtGatt.ScanManager: filter size is 1
,08-19 17:55:19.597  2760  2999 D BtGatt.ScanManager: delete FilterIndex - 6
,08-19 17:55:19.597  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-19 17:55:19.597  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-19 17:55:19.597  2760  2819 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-19 17:55:19.597  2760  2819 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-19 17:55:19.597  2760  2999 D BtGatt.ScanManager: stopping BLe Batch
08-19 17:55:19.597  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-19 17:55:19.597  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-19 17:55:19.597  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-19 17:55:19.597  6361  6416 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-19 17:55:19.607  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
08-19 17:55:19.607  6361  6416 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-19 17:55:19.607  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-19 17:55:19.607  2760  2819 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-19 17:55:19.607  2760  2819 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-19 17:55:19.607  2760  2999 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-19 17:55:19.607  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-19 17:55:19.607  2760  2819 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-19 17:55:19.607  2760  2819 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-19 17:55:19.607  6361  6361 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-19 17:55:19.607  6361  6361 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-19 17:55:19.607  6361  6361 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-19 17:55:19.607  6361  6416 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-19 17:55:19.607  6361  6416 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-19 17:55:19.607  6361  6416 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:55:19.607  6361  6416 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:19.607  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:19.607  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-19 17:55:19.607  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-19 17:55:19.607  6361  6416 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29ac3058 removed from the list
08-19 17:55:19.607  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:19.607  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@311b95b1 removed from the list
08-19 17:55:19.607  6361  6416 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:19.617  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:19.617  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:19.617  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:55:19.617  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-19 17:55:19.617  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:19.617  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-19 17:55:19.617  6361  6416 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@311b95b1 not in the list
08-19 17:55:19.617  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-19 17:55:19.617  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:55:19.617  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-19 17:55:19.617  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:19.617  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-19 17:55:19.617  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38dffa04 removed from the list
08-19 17:55:19.617  6361  6416 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-19 17:55:19.617  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:19.617  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:55:19.617  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-19 17:55:19.617  6361  6416 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c3af617 removed from the list
,08-19 17:55:19.627  6361  6416 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-19 17:55:19.627  6361  6416 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e64b270 added. We now have 2 listener(s)
,08-19 17:55:19.627  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-19 17:55:19.627  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-19 17:55:19.627  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-19 17:55:19.627  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:55:19.627  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de49e9 added. We now have 9 listener(s)
,08-19 17:55:19.627  6361  6416 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-19 17:55:19.627  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-19 17:55:19.637  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-19 17:55:19.637  6361  6416 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-19 17:55:19.637  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:19.637  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:55:19.637  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true,
08-19 17:55:19.637  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:55:19.637  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:19.637  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:19.637  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-19 17:55:19.637  6361  6416 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-19 17:55:19.637  6361  6416 D io.jxcore.node.ConnectivityMonitor: start: OK
08-19 17:55:19.637  6361  6416 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-19 17:55:19.637  6361  6416 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27f0910f added. We now have 3 listener(s)
,08-19 17:55:19.637  6361  6361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-19 17:55:19.637  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-19 17:55:19.637  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-19 17:55:19.637  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-19 17:55:19.637  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:55:19.637  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3a859c added. We now have 10 listener(s)
08-19 17:55:19.637  6361  6416 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-19 17:55:19.637  6361  6416 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-19 17:55:19.637  6361  6416 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-19 17:55:19.637  6361  6416 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-19 17:55:19.637  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-19 17:55:19.637  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-19 17:55:19.637  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-19 17:55:19.647  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-19 17:55:19.647  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-19 17:55:19.647  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-19 17:55:19.657  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-19 17:55:19.657  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-19 17:55:19.657  6361  6416 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-19 17:55:19.657  2760  2777 D BtGatt.GattService: registerClient() - UUID=47c615b0-13c9-4529-97c1-a8bb66dae634
,08-19 17:55:19.697  2760  2819 D BtGatt.GattService: onClientRegistered() - UUID=47c615b0-13c9-4529-97c1-a8bb66dae634, clientIf=6
,08-19 17:55:19.697  6361  6375 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-19 17:55:19.697  2760  6623 D BtGatt.GattService: start scan with filters
,08-19 17:55:19.707  2760  2999 D BtGatt.ScanManager: handling starting scan
,08-19 17:55:19.707  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-19 17:55:19.707  2760  2819 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-19 17:55:19.707  2760  2819 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-19 17:55:19.707  2760  2999 D BtGatt.ScanManager: allow scan with filters
,08-19 17:55:19.707  2760  2999 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-19 17:55:19.707  2760  2999 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
,08-19 17:55:19.707  2760  2819 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-19 17:55:19.707  2760  2819 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-19 17:55:19.707  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-19 17:55:19.707  2760  2999 D BtGatt.ScanManager: Starting BLE batch scan
,08-19 17:55:19.707  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-19 17:55:19.707  2760  2999 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-19 17:55:19.717  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-19 17:55:19.717  2760  2819 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-19 17:55:19.717  2760  2819 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-19 17:55:19.717  2760  2819 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-19 17:55:19.717  2760  2819 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-19 17:55:19.727  6361  6416 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-19 17:55:19.727  6361  6416 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-19 17:55:19.727  6361  6361 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-19 17:55:19.727  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-19 17:55:19.727  6361  6416 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-19 17:55:19.737  6361  6416 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-19 17:55:19.737  6361  6416 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:55:19.737  6361  6416 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:55:19.737  6361  6416 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-19 17:55:19.737  6361  6416 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:19.737  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:19.737  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-19 17:55:19.737  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-19 17:55:19.737  6361  6416 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e64b270 removed from the list
,08-19 17:55:19.737  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:19.737  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de49e9 removed from the list
08-19 17:55:19.737  6361  6416 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:19.737  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-19 17:55:19.737  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:19.737  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-19 17:55:19.737  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:19.737  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-19 17:55:19.737  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-19 17:55:19.737  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:19.737  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:19.737  6361  6416 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de49e9 not in the list
08-19 17:55:19.737  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-19 17:55:19.737  6361  6416 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-19 17:55:19.737  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-19 17:55:19.737  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-19 17:55:19.737  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-19 17:55:19.737  2760  6623 D BtGatt.GattService: stopScan() - queue size =1
,08-19 17:55:19.737  2760  2999 D BtGatt.ScanManager: filter size is 1
,08-19 17:55:19.737  2760  2999 D BtGatt.ScanManager: delete FilterIndex - 7
,08-19 17:55:19.737  2760  2819 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
08-19 17:55:19.737  2760  2819 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-19 17:55:19.747  2760  2999 D BtGatt.ScanManager: stopping BLe Batch
08-19 17:55:19.747  2760  2998 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-19 17:55:19.747  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-19 17:55:19.747  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-19 17:55:19.747  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-19 17:55:19.747  2760  2819 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
08-19 17:55:19.747  2760  2819 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-19 17:55:19.747  2760  2999 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-19 17:55:19.747  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-19 17:55:19.747  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-19 17:55:19.747  2760  2819 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-19 17:55:19.747  2760  2819 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-19 17:55:19.747  6361  6416 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-19 17:55:19.757  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-19 17:55:19.757  6361  6416 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-19 17:55:19.757  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-19 17:55:19.757  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:55:19.757  6361  6361 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-19 17:55:19.757  6361  6361 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-19 17:55:19.757  6361  6361 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-19 17:55:19.757  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:19.757  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:19.757  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:19.757  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3a859c removed from the list
08-19 17:55:19.757  6361  6416 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:19.757  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:19.757  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:19.757  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-19 17:55:19.757  6361  6416 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27f0910f removed from the list
08-19 17:55:19.757  6361  6416 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-19 17:55:19.757  6361  6416 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a385f88 added. We now have 2 listener(s)
,08-19 17:55:19.757  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-19 17:55:19.757  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-19 17:55:19.757  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-19 17:55:19.757  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-19 17:55:19.757  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@224c4d21 added. We now have 9 listener(s)
08-19 17:55:19.757  6361  6416 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-19 17:55:19.757  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-19 17:55:19.767  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-19 17:55:19.767  6361  6416 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-19 17:55:19.767  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:19.767  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:55:19.767  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:55:19.767  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:55:19.767  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:19.767  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:19.767  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:55:19.767  6361  6416 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:55:19.767  6361  6416 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-19 17:55:19.767  6361  6361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:19.767  6361  6416 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-19 17:55:19.767  6361  6416 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c6f9307 added. We now have 3 listener(s)
,08-19 17:55:19.777  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-19 17:55:19.777  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-19 17:55:19.777  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-19 17:55:19.777  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:55:19.777  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18b7ec34 added. We now have 10 listener(s)
08-19 17:55:19.777  6361  6416 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-19 17:55:19.777  6361  6416 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-19 17:55:19.777  6361  6416 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-19 17:55:19.777  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-19 17:55:19.777  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-19 17:55:19.777  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-19 17:55:19.777  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-19 17:55:19.787  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-19 17:55:19.787  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-19 17:55:19.797  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-19 17:55:19.797  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-19 17:55:19.797  6361  6416 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-19 17:55:19.797  2760  2777 D BtGatt.GattService: registerClient() - UUID=6510bd5b-1280-4a42-a8ca-bb10bfbbab39
,08-19 17:55:19.827   287   287 E SMD     : DCD OFF,
,08-19 17:55:19.837  2760  2819 D BtGatt.GattService: onClientRegistered() - UUID=6510bd5b-1280-4a42-a8ca-bb10bfbbab39, clientIf=6
,08-19 17:55:19.847  6361  6584 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-19 17:55:19.847  2760  6623 D BtGatt.GattService: start scan with filters
,08-19 17:55:19.847  2760  2999 D BtGatt.ScanManager: handling starting scan
,08-19 17:55:19.847  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-19 17:55:19.847  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-19 17:55:19.847  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-19 17:55:19.847  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-19 17:55:19.847  2760  2819 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
08-19 17:55:19.847  2760  2819 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-19 17:55:19.847  2760  2999 D BtGatt.ScanManager: allow scan with filters
08-19 17:55:19.847  2760  2999 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-19 17:55:19.847  2760  2999 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6
,08-19 17:55:19.847  2760  2819 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-19 17:55:19.847  2760  2819 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-19 17:55:19.847  2760  2999 D BtGatt.ScanManager: Starting BLE batch scan
08-19 17:55:19.847  2760  2999 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-19 17:55:19.847  6361  6416 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
08-19 17:55:19.847  6361  6361 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-19 17:55:19.847  6361  6416 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-19 17:55:19.847  2760  2819 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-19 17:55:19.847  2760  2819 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-19 17:55:19.857  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-19 17:55:19.857  2760  2819 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-19 17:55:19.857  2760  2819 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-19 17:55:19.867  6361  6416 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-19 17:55:19.867  6361  6416 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:55:19.867  6361  6416 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-19 17:55:19.867  6361  6416 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:19.867  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-19 17:55:19.867  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-19 17:55:19.867  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-19 17:55:19.867  6361  6416 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a385f88 removed from the list
,08-19 17:55:19.867  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:19.867  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@224c4d21 removed from the list
08-19 17:55:19.867  6361  6416 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:19.867  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-19 17:55:19.867  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:19.867  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-19 17:55:19.867  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:19.867  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-19 17:55:19.867  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:19.867  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:19.867  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-19 17:55:19.867  6361  6416 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@224c4d21 not in the list
08-19 17:55:19.867  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-19 17:55:19.867  6361  6416 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-19 17:55:19.867  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-19 17:55:19.867  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-19 17:55:19.867  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-19 17:55:19.867  2760  6593 D BtGatt.GattService: stopScan() - queue size =1
,08-19 17:55:19.867  2760  2999 D BtGatt.ScanManager: filter size is 1
,08-19 17:55:19.867  2760  2770 D BtGatt.GattService: unregisterClient() - clientIf=6
08-19 17:55:19.867  2760  2999 D BtGatt.ScanManager: delete FilterIndex - 8
,08-19 17:55:19.877  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-19 17:55:19.877  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-19 17:55:19.877  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-19 17:55:19.877  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-19 17:55:19.877  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-19 17:55:19.877  2760  2819 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-19 17:55:19.877  2760  2819 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-19 17:55:19.877  2760  2999 D BtGatt.ScanManager: stopping BLe Batch
,08-19 17:55:19.877  6361  6416 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-19 17:55:19.877  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-19 17:55:19.877  6361  6416 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-19 17:55:19.877  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-19 17:55:19.877  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:55:19.877  2760  2819 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-19 17:55:19.877  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:19.877  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:19.877  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:19.877  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18b7ec34 removed from the list
08-19 17:55:19.877  6361  6416 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:19.877  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:19.877  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:19.877  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-19 17:55:19.877  6361  6416 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c6f9307 removed from the list
,08-19 17:55:19.877  6361  6361 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-19 17:55:19.877  6361  6416 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-19 17:55:19.877  6361  6416 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a0197a0 added. We now have 2 listener(s)
,08-19 17:55:19.877  6361  6361 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-19 17:55:19.877  6361  6361 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-19 17:55:19.877  2760  2819 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-19 17:55:19.877  2760  2999 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-19 17:55:19.887  2760  2819 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-19 17:55:19.887  2760  2819 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-19 17:55:19.887  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-19 17:55:19.887  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-19 17:55:19.887  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-19 17:55:19.887  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:55:19.887  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a07f59 added. We now have 9 listener(s)
08-19 17:55:19.887  6361  6416 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-19 17:55:19.887  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-19 17:55:19.887  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-19 17:55:19.887  6361  6416 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-19 17:55:19.887  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-19 17:55:19.887  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-19 17:55:19.887  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-19 17:55:19.887  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-19 17:55:19.887  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-19 17:55:19.887  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-19 17:55:19.887  6361  6416 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-19 17:55:19.897  6361  6416 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-19 17:55:19.897  6361  6416 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-19 17:55:19.897  6361  6361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-19 17:55:19.897  6361  6416 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-19 17:55:19.897  6361  6416 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e9ddbff added. We now have 3 listener(s)
,08-19 17:55:19.897  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-19 17:55:19.897  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-19 17:55:19.897  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-19 17:55:19.907  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-19 17:55:19.907  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28788dcc added. We now have 10 listener(s)
,08-19 17:55:19.907  6361  6416 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-19 17:55:19.907  6361  6416 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-19 17:55:19.907  6361  6416 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-19 17:55:19.907  6361  6416 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-19 17:55:19.907  6361  6416 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:19.907  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-19 17:55:19.907  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-19 17:55:19.907  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-19 17:55:19.907  6361  6416 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a0197a0 removed from the list
08-19 17:55:19.907  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-19 17:55:19.907  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a07f59 removed from the list,
08-19 17:55:19.907  6361  6416 D io.jxcore.node.ConnectivityMonitor: stop
08-19 17:55:19.907  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-19 17:55:19.907  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:19.907  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:55:19.907  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-19 17:55:19.907  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-19 17:55:19.907  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-19 17:55:19.907  6361  6416 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a07f59 not in the list
08-19 17:55:19.907  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:19.907  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:55:19.907  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-19 17:55:19.907  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-19 17:55:19.907  6361  6416 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-19 17:55:19.907  6361  6416 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28788dcc removed from the list
08-19 17:55:19.907  6361  6416 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-19 17:55:19.907  6361  6416 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-19 17:55:19.907  6361  6416 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-19 17:55:19.907  6361  6416 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-19 17:55:19.907  6361  6416 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e9ddbff removed from the list
,08-19 17:55:19.907  6361  6416 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-19 17:55:19.907  6361  6416 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-19 17:55:19.907  6361  6416 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,08-19 17:55:19.917  6361  6416 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-19 17:55:19.917  6361  6416 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-19 17:55:19.917  6361  6416 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-19 17:55:19.917  6361  6655 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1280, name: My test thread name)
,08-19 17:55:19.917  6361  6655 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1280, thread name: My test thread name)
,08-19 17:55:19.917  6361  6655 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1280, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-19 17:55:19.927  1021  1048 D Tethering: interfaceLinkStateChanged wlan0, false
,08-19 17:55:19.927  1021  1048 D Tethering: interfaceStatusChanged wlan0, false
,08-19 17:55:19.927  1021  1048 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-19 17:55:19.927  6361  6656 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1282, name: My test thread name)
,08-19 17:55:19.927  6361  6656 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1282, thread name: My test thread name)
08-19 17:55:19.927  6361  6656 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1282, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-19 17:55:19.927  6361  6416 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-19 17:55:19.927  6361  6416 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-19 17:55:19.927  6361  6416 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-19 17:55:19.927  6361  6416 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-19 17:55:19.927  6361  6416 D com.test.thalitest.ThaliTestRunner: Total duration: 23242 ms
,08-19 17:55:19.927  6361  6416 I jxcore-log: Total number of executed tests:  80
08-19 17:55:19.927  6361  6416 I jxcore-log: 
,08-19 17:55:19.927  6361  6416 I jxcore-log: Number of passed tests:  80
08-19 17:55:19.927  6361  6416 I jxcore-log: 
08-19 17:55:19.927  6361  6416 I jxcore-log: Number of failed tests:  0
08-19 17:55:19.927  6361  6416 I jxcore-log: 
08-19 17:55:19.927  6361  6416 I jxcore-log: Number of ignored tests:  0
08-19 17:55:19.927  6361  6416 I jxcore-log: 
08-19 17:55:19.927  6361  6416 I jxcore-log: Total duration:  23242
08-19 17:55:19.927  6361  6416 I jxcore-log: 
,08-19 17:55:19.937  6361  6416 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-19 17:55:19.937  6361  6416 I jxcore-log: 
,08-19 17:55:19.937  6361  6416 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-19 17:55:19.937  6361  6416 I jxcore-log: 
08-19 17:55:19.937  6643  6643 I wpa_supplicant: CTRL-EVENT-ASSOC-REJECT bssid=F4.99.3E status_code=1
08-19 17:55:19.937  6643  6643 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
08-19 17:55:19.937  6643  6643 I wpa_supplicant: wlan0: State: ASSOCIATING -> DISCONNECTED
08-19 17:55:19.937  6643  6643 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=00.00.00 SSID=4E47373030
08-19 17:55:19.937  6361  6416 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-19 17:55:19.937  6361  6416 I jxcore-log: 
08-19 17:55:19.947  6361  6361 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-19 17:55:19.947  6361  6416 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-19 17:55:19.947  6361  6416 I jxcore-log: 
08-19 17:55:19.947  6361  6416 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-19 17:55:19.947  6361  6416 I jxcore-log: 
08-19 17:55:19.947  1021  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-19 17:55:19.947  1021  1130 D SecContentProvider2: mCursor = null
08-19 17:55:19.947  6361  6416 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-19 17:55:19.947  6361  6416 I jxcore-log: 
08-19 17:55:19.947  6361  6416 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-19 17:55:19.947  6361  6416 I jxcore-log: 
08-19 17:55:19.947  6361  6416 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-19 17:55:19.947  6361  6416 I jxcore-log: 
08-19 17:55:19.947  6361  6416 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-19 17:55:19.947  6361  6416 I jxcore-log: 
08-19 17:55:19.947  6361  6416 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-19 17:55:19.947  6361  6416 I jxcore-log: 
08-19 17:55:19.957  6361  6416 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-19 17:55:19.957  6361  6416 I jxcore-log: 
08-19 17:55:19.957  6361  6416 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-19 17:55:19.957  6361  6416 I jxcore-log: 
08-19 17:55:19.957  6361  6416 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-19 17:55:19.957  6361  6416 I jxcore-log: 
08-19 17:55:19.957  6361  6416 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-19 17:55:19.957  6361  6416 I jxcore-log: 
08-19 17:55:19.957  6361  6416 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-19 17:55:19.957  6361  6416 I jxcore-log: 
,08-19 17:55:19.957  6361  6416 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-19 17:55:19.957  6361  6416 I jxcore-log: 
08-19 17:55:19.957  6361  6416 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-19 17:55:19.957  6361  6416 I jxcore-log: 
08-19 17:55:19.957  6361  6416 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-19 17:55:19.957  6361  6416 I jxcore-log: 
,08-19 17:55:19.957  6361  6416 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-19 17:55:19.957  6361  6416 I jxcore-log: 
,08-19 17:55:19.957  6361  6416 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-19 17:55:19.957  6361  6416 I jxcore-log: 
,08-19 17:55:19.957  6361  6416 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-19 17:55:19.957  6361  6416 I jxcore-log: 
08-19 17:55:19.957  6361  6416 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-19 17:55:19.957  6361  6416 I jxcore-log: 
,08-19 17:55:19.957  6361  6416 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-19 17:55:19.957  6361  6416 I jxcore-log: 
,08-19 17:55:19.957  6361  6416 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-19 17:55:19.957  6361  6416 I jxcore-log: 
,08-19 17:55:19.967  6361  6416 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-19 17:55:19.967  6361  6416 I jxcore-log: 
08-19 17:55:19.967  6361  6416 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-19 17:55:19.967  6361  6416 I jxcore-log: 
,08-19 17:55:19.967  6361  6416 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-19 17:55:19.967  6361  6416 I jxcore-log: 
,08-19 17:55:19.967  6361  6416 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-19 17:55:19.967  6361  6416 I jxcore-log: 
,08-19 17:55:20.037  6643  6643 I wpa_supplicant: P2P: Current p2p state = IDLE,
08-19 17:55:20.037  6643  6643 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-19 17:55:20.037  6643  6643 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,08-19 17:55:20.047  1021  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-19 17:55:20.047  1021  1130 D SecContentProvider2: mCursor = null
08-19 17:55:20.047  6643  6643 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-19 17:55:20.047  6643  6643 I wpa_supplicant: nl80211: Received scan results (24 BSSes),
08-19 17:55:20.047  6643  6643 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-19 17:55:20.057  1021  6648 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700',
08-19 17:55:20.057  6643  6643 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-19 17:55:20.057  6643  6643 I wpa_supplicant: Trying to associate with  'G700',
08-19 17:55:20.057  6643  6643 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,08-19 17:55:20.057  6643  6643 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030,
,08-19 17:55:20.077  1021  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-19 17:55:20.077  1021  1130 D SecContentProvider2: mCursor = null
,08-19 17:55:20.107  6361  6361 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-19 17:55:20.107  6361  6416 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-19 17:55:20.107  6361  6416 I jxcore-log: 
,08-19 17:55:20.227  6657  6657 D AndroidRuntime: ,
08-19 17:55:20.227  6657  6657 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-19 17:55:20.227  6657  6657 D AndroidRuntime: CheckJNI is OFF,
08-19 17:55:20.227  6657  6657 D AndroidRuntime: readGMSProperty: start
08-19 17:55:20.227  6657  6657 D AndroidRuntime: readGMSProperty: already setted!!,
08-19 17:55:20.227  6657  6657 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-19 17:55:20.227  6657  6657 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-19 17:55:20.227  6657  6657 D AndroidRuntime: readGMSProperty: end
08-19 17:55:20.227  6657  6657 D AndroidRuntime: addProductProperty: start,
,08-19 17:55:20.257  6361  6361 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-19 17:55:20.257  6361  6416 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-19 17:55:20.257  6361  6416 I jxcore-log: 
,08-19 17:55:20.347  6657  6657 E AffinityControl: AffinityControl: registerfunction enter,
,08-19 17:55:20.377  6657  6657 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm,
,08-19 17:55:20.377  6361  6361 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-19 17:55:20.377  6361  6416 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-19 17:55:20.377  6361  6416 I jxcore-log: 
,08-19 17:55:20.397  1021  1225 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
08-19 17:55:20.397  1021  1225 D PackageManager: START PACKAGE DELETE: observer{961529607}
08-19 17:55:20.397  1021  1225 D PackageManager: pkg{<packageName>}
08-19 17:55:20.397  1021  1225 D PackageManager: user{0}
08-19 17:55:20.397  1021  1225 D PackageManager: caller{2000}
08-19 17:55:20.397  1021  1225 D PackageManager: flags{2}
08-19 17:55:20.397  1021  1225 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-19 17:55:20.397  1021  1060 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-19 17:55:20.397  1021  1225 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-19 17:55:20.397  1021  1225 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-19 17:55:20.397  1021  1225 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-19 17:55:20.397  1021  1060 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-19 17:55:20.397  1021  1060 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-19 17:55:20.397  1021  1060 D ApplicationPolicy: getApplicationUninstallationEnabled
08-19 17:55:20.397  1021  1060 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-19 17:55:20.397  1021  1060 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
,08-19 17:55:20.427  1021  1046 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
08-19 17:55:20.427  1021  1046 I ActivityManager: Killing 6361:com.test.thalitest/u0a170 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-19 17:55:20.507  1021  1046 I ActivityManager:   Force finishing activity ActivityRecord{368d871f u0 com.test.thalitest/.MainActivity t163}
,08-19 17:55:20.527  1021  1225 I WindowState: WIN DEATH: Window{2cba8bb8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-19 17:55:20.537   257   582 I SurfaceFlinger: id=12 Removed NainActivit (6/8)
,08-19 17:55:20.537   257   581 I SurfaceFlinger: id=12 Removed NainActivit (-2/8)
,08-19 17:55:20.547  1021  1060 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,08-19 17:55:20.547  1021  1060 I ActivityManager:   Force finishing activity ActivityRecord{368d871f u0 com.test.thalitest/.MainActivity t163 f}
08-19 17:55:20.547  1021  1060 W ActivityManager: Duplicate finish request for ActivityRecord{368d871f u0 com.test.thalitest/.MainActivity t163 f}
,08-19 17:55:20.547  1021  1225 D InputDispatcher: Focus left window: 6361
,08-19 17:55:20.557  1021  1051 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-19 17:55:20.557  1021  1051 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-19 17:55:20.587  1021  1060 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
08-19 17:55:20.597  1021  1046 D InputDispatcher: Focused application released
,08-19 17:55:20.607  5769  5769 I art     : Explicit concurrent mark sweep GC freed 1977(114KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 654us total 24.045ms
,08-19 17:55:20.617  1021  1102 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-19 17:55:20.627  1935  1935 E SamsungIME: mOCRHelper is null
,08-19 17:55:20.647  1021  1127 V NetworkStats: removeUidsLocked() for UIDs [10170]
08-19 17:55:20.647  1021  1127 V NetworkStats: performPollLocked(flags=0x3)
,08-19 17:55:20.647  1021  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-19 17:55:20.647  1021  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-19 17:55:20.647  1021  1127 V NetworkStats: performPollLocked() took 6ms
,08-19 17:55:20.667  1468  1468 D PersonaManager: isKioskContainerExistOnDevice
,08-19 17:55:20.667  2887  2887 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Aug 19 17:55:20 GMT+02:00 2016
,08-19 17:55:20.667  1468  1468 D RegisteredServicesCache: empty dynamic service
,08-19 17:55:20.687  1468  1468 D RegisteredComponentCache: Collect Tech packages for Knox
,08-19 17:55:20.687  1468  1468 D PersonaManager: isKioskContainerExistOnDevice
,08-19 17:55:20.707  1021  1128 D NtpTrustedTime: forceRefresh() from cache miss
,08-19 17:55:20.707   277  1004 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-19 17:55:20.707   277  1004 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,08-19 17:55:20.717   277  1004 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-19 17:55:20.717   277  1004 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,08-19 17:55:20.717  1021  1128 D NtpTrustedTime: forceRefresh Fail.
,08-19 17:55:20.747  1021  1021 I art     : Explicit concurrent mark sweep GC freed 66139(4MB) AllocSpace objects, 12(193KB) LOS objects, 33% free, 22MB/34MB, paused 2.744ms total 166.772ms
,08-19 17:55:20.747  1021  1498 I art     : WaitForGcToComplete blocked for 127.997ms for cause Explicit
,08-19 17:55:20.777  1021  2833 D SSRM:n  : SIOP:: AP = 320
,08-19 17:55:20.797  1021  1021 D RCPManagerService: PackageReceiver onReceive()
,08-19 17:55:20.797  1021  1021 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-19 17:55:20.797  1021  1021 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-19 17:55:20.797  1021  1021 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-19 17:55:20.797  1021  1021 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,08-19 17:55:20.807  1021  1021 I OTPFW   : ProvisionData::getAllEntries Enter
,08-19 17:55:20.807  1021  1021 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-19 17:55:20.897  1021  1021 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-19 17:55:20.897  1021  1021 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-19 17:55:20.897  1021  1021 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-19 17:55:20.897  1021  1021 V EnterpriseBillingPolicy: uID is 10170
08-19 17:55:20.897  1021  1021 V EnterpriseBillingPolicy: Removed Packageuid is0
08-19 17:55:20.897  1021  1021 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-19 17:55:20.897  1021  1021 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-19 17:55:20.897  1021  1021 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-19 17:55:20.897  1021  1021 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-19 17:55:20.897  1021  1021 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-19 17:55:20.897  1021  1021 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-19 17:55:20.907  1021  1021 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-19 17:55:20.907  1021  1021 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-19 17:55:20.907  1021  1165 D TaskPersister: removeObsoleteFile: deleting file=163_task.xml
08-19 17:55:20.907  1021  1021 V EnterpriseBillingPolicy: uID is 10170
08-19 17:55:20.907  1021  2833 D SSRM:bc : MSG_TYPE_APP_REMOVED::
08-19 17:55:20.907  1021  1021 V EnterpriseBillingPolicy: Removed Packageuid is0
08-19 17:55:20.907  1021  1021 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
08-19 17:55:20.907  1021  1021 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
08-19 17:55:20.907  1021  1021 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
08-19 17:55:20.907  1021  1021 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-19 17:55:20.907  1021  1021 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-19 17:55:20.907  1021  1021 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-19 17:55:20.907  1021  1021 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-19 17:55:20.907  1021  1021 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-19 17:55:20.937  1021  1498 I art     : Explicit concurrent mark sweep GC freed 10919(556KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 22MB/34MB, paused 3.951ms total 188.291ms
,08-19 17:55:20.937  1021  1060 I art     : WaitForGcToComplete blocked for 336.118ms for cause Explicit
08-19 17:55:20.937  1021  1034 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,08-19 17:55:20.937  1021  1508 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-19 17:55:20.937  1021  1034 D SecContentProvider2: mCursor = null
,08-19 17:55:20.937  1021  1508 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-19 17:55:20.937  1729  1898 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-19 17:55:20.947  1021  1508 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:20.947  1021  1508 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:20.947  1021  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-19 17:55:20.957  1021  1045 D EnterpriseDeviceManagerService: Package has changed for user 0
08-19 17:55:20.957  1021  1045 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
08-19 17:55:20.957  1021  1045 W TextServicesManagerService: no available spell checker services found
,08-19 17:55:20.957  2887  2887 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-19 17:55:20.967  1021  1125 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=22, mSplitNum[2]=32, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=42
,08-19 17:55:20.967  1021  1125 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-19 17:55:20.967  1021  1125 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-19 17:55:20.967  1021  1125 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:20.967  1021  1125 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:20.967  1021  1125 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:20.967  1021  1125 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:20.977  1021  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-19 17:55:20.977  2887  2887 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-19 17:55:20.977  2887  2887 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-19 17:55:20.977  1021  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-19 17:55:20.977  2887  2887 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-19 17:55:20.987  6672  6672 E Zygote  : MountEmulatedStorage()
08-19 17:55:20.987  6672  6672 I libpersona: KNOX_SDCARD checking this for 10090
,08-19 17:55:20.987  6672  6672 E Zygote  : v2
08-19 17:55:20.987  6672  6672 I libpersona: KNOX_SDCARD not a persona
,08-19 17:55:20.987  6672  6672 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-19 17:55:20.987  1021  1125 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6672 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a,
,08-19 17:55:20.987  6672  6672 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-19 17:55:20.987  6672  6672 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-19 17:55:20.997  1021  1046 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-19 17:55:20.997  2887  6671 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-19 17:55:20.997  1021  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
08-19 17:55:21.007  1021  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:21.007  1021  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:21.007  1021  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:21.007  1021  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:21.007  1021  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-19 17:55:21.007  2887  6671 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,08-19 17:55:21.017  6687  6687 E Zygote  : MountEmulatedStorage()
08-19 17:55:21.017  6687  6687 E Zygote  : v2
08-19 17:55:21.017  6687  6687 I libpersona: KNOX_SDCARD checking this for 10032
08-19 17:55:21.017  6687  6687 I libpersona: KNOX_SDCARD not a persona
,08-19 17:55:21.017  6687  6687 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-19 17:55:21.017  1021  1046 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=6687 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-19 17:55:21.017  1021  1046 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,08-19 17:55:21.027  6687  6687 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-19 17:55:21.027  6687  6687 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-19 17:55:21.027  1021  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:21.027  1021  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:21.027  1021  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:21.027  1021  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:21.027  6672  6672 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-19 17:55:21.027  2887  6671 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,08-19 17:55:21.037  6672  6672 D ActivityThread: Added TimaKeyStore provider
,08-19 17:55:21.037  2887  6671 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,08-19 17:55:21.037  6694  6694 E Zygote  : MountEmulatedStorage(),
,08-19 17:55:21.047  6694  6694 E Zygote  : v2
08-19 17:55:21.047  6694  6694 I libpersona: KNOX_SDCARD checking this for 10052
08-19 17:55:21.047  6694  6694 I libpersona: KNOX_SDCARD not a persona
,08-19 17:55:21.047  6694  6694 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-19 17:55:21.047  1021  1046 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=6694 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,08-19 17:55:21.047  1021  1046 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast,
,08-19 17:55:21.057  1021  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-19 17:55:21.057  6694  6694 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-19 17:55:21.057  1021  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:21.057  1021  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:21.057  1021  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:21.057  6694  6694 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-19 17:55:21.077  6687  6687 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-19 17:55:21.077  6687  6687 D ActivityThread: Added TimaKeyStore provider
,08-19 17:55:21.087  6694  6694 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-19 17:55:21.087  6694  6694 D ActivityThread: Added TimaKeyStore provider
,08-19 17:55:21.097  6717  6717 E Zygote  : MountEmulatedStorage(),
08-19 17:55:21.097  6717  6717 E Zygote  : v2
,08-19 17:55:21.097  6717  6717 I libpersona: KNOX_SDCARD checking this for 10098
08-19 17:55:21.097  6717  6717 I libpersona: KNOX_SDCARD not a persona
,08-19 17:55:21.097  6717  6717 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-19 17:55:21.097  6717  6717 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-19 17:55:21.097  6717  6717 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-19 17:55:21.107  1021  1045 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-19 17:55:21.107  1021  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-19 17:55:21.117  1021  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-19 17:55:21.117  1021  1046 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=6717 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-19 17:55:21.117  2887  6671 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,08-19 17:55:21.127  6717  6717 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-19 17:55:21.127  6717  6717 D ActivityThread: Added TimaKeyStore provider
,08-19 17:55:21.157  1021  1048 D Tethering: interfaceLinkStateChanged wlan0, false
,08-19 17:55:21.157  1021  1048 D Tethering: interfaceStatusChanged wlan0, false
,08-19 17:55:21.167  1021  1048 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-19 17:55:21.167  2887  6671 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,08-19 17:55:21.167  2887  6671 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,08-19 17:55:21.167  2887  2887 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-19 17:55:21.177  6643  6643 I wpa_supplicant: CTRL-EVENT-ASSOC-REJECT bssid=F4.99.3E status_code=1
,08-19 17:55:21.177  6643  6643 I wpa_supplicant: wlan0: Setting scan request: 0 sec 500000 usec
08-19 17:55:21.177  6643  6643 I wpa_supplicant: wlan0: State: ASSOCIATING -> DISCONNECTED
08-19 17:55:21.177  6643  6643 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=00.00.00 SSID=4E47373030
08-19 17:55:21.177  1021  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-19 17:55:21.177  1021  1060 I art     : Explicit concurrent mark sweep GC freed 7456(417KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 22MB/34MB, paused 7.338ms total 236.148ms
,08-19 17:55:21.177  1021  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-19 17:55:21.177  1021  1130 D SecContentProvider2: mCursor = null
,08-19 17:55:21.197  6672  6672 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,08-19 17:55:21.197  1021  1728 D ActivityManager: startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,08-19 17:55:21.197  6672  6672 D elm:15121: ELMEngine.ELMEngine( context ).
,08-19 17:55:21.197  1021  1728 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:21.197  1021  1728 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:21.197  1021  1728 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:21.197  1021  1728 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:21.197  6672  6672 D elm:15121: MDMBridge.setEnterpriseBridge()
,08-19 17:55:21.207  6687  6732 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-19 17:55:21.207  6687  6732 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-19 17:55:21.207  6733  6733 E Zygote  : MountEmulatedStorage()
,08-19 17:55:21.207  6733  6733 E Zygote  : v2
08-19 17:55:21.207  6733  6733 I libpersona: KNOX_SDCARD checking this for 1000
08-19 17:55:21.207  6733  6733 I libpersona: KNOX_SDCARD not a persona
,08-19 17:55:21.207  6733  6733 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-19 17:55:21.217  6733  6733 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-19 17:55:21.217  1021  1728 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=6733 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
08-19 17:55:21.217  1021  1728 I ActivityManager: Killing 6135:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
,08-19 17:55:21.227  6733  6733 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-19 17:55:21.227  1021  1524 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
08-19 17:55:21.227  1021  1524 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-19 17:55:21.227  1021  1524 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:21.227  1021  1524 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:21.227  1021  1524 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,08-19 17:55:21.237  1021  1728 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-19 17:55:21.237  1021  1728 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:21.237  1021  1728 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:21.237  1021  1728 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:21.237  1021  1728 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:21.237  6687  6732 D SPPClientService: PushLog.txt file is not deleted.
,08-19 17:55:21.237  6672  6672 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,08-19 17:55:21.247  6672  6672 D elm:15121: ElmAgentService : onCreate()
,08-19 17:55:21.247  6672  6746 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,08-19 17:55:21.247  6672  6746 D elm:15121: MainReceiver.listeningToPackageRemoved()
,08-19 17:55:21.247  6672  6746 D elm:15121: MDMBridge.getInstance()
08-19 17:55:21.247  6672  6746 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
08-19 17:55:21.247  6747  6747 E Zygote  : MountEmulatedStorage(),
08-19 17:55:21.247  6747  6747 E Zygote  : v2
08-19 17:55:21.247  6747  6747 I libpersona: KNOX_SDCARD checking this for 10032,
08-19 17:55:21.247  6687  6732 D SPPClientService: PushLog.txt file is not deleted.
08-19 17:55:21.247  6687  6732 D SPPClientService: ============PushLog. stop!
08-19 17:55:21.247  6747  6747 I libpersona: KNOX_SDCARD not a persona
,08-19 17:55:21.247  6747  6747 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-19 17:55:21.257  1021  1728 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6747 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-19 17:55:21.257  1021  1728 I ActivityManager: Killing 6119:com.google.android.partnersetup/u0a14 (adj 15): empty #21
,08-19 17:55:21.257  6747  6747 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-19 17:55:21.267  6747  6747 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-19 17:55:21.267  1021  1060 D PackageManager: delete codoeFile: 
,08-19 17:55:21.287  1021  1045 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-19 17:55:21.287  1021  1045 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-19 17:55:21.287  1021  1045 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-19 17:55:21.287  1021  1060 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
08-19 17:55:21.287  1021  1060 I AASA_removePackage: UID=10170 Target=com.test.thalitest
08-19 17:55:21.287  6733  6733 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-19 17:55:21.287  6733  6733 D ActivityThread: Added TimaKeyStore provider
08-19 17:55:21.287  1021  1060 D PackageManager: result of delete: 1{961529607}
,08-19 17:55:21.287  1021  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-19 17:55:21.287  1681  1681 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
08-19 17:55:21.287  1681  1681 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,08-19 17:55:21.297  6657  6657 D AndroidRuntime: Shutting down VM,
,08-19 17:55:21.297  6672  6746 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-19 17:55:21.297  6747  6747 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-19 17:55:21.297  1021  1060 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-19 17:55:21.297  1021  1060 D PackageManager: userId{-1}
08-19 17:55:21.297  1021  1060 D PackageManager: andCode{true}
,08-19 17:55:21.297  6747  6747 D ActivityThread: Added TimaKeyStore provider
,08-19 17:55:21.307  1021  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-19 17:55:21.307  6672  6672 D elm:15121: ElmAgentService : onDestroy().
,08-19 17:55:21.307  1021  1060 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-19 17:55:21.317  1021  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-19 17:55:21.317  1021  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-19 17:55:21.317  1021  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-19 17:55:21.317  1021  4075 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,08-19 17:55:21.317  1021  4075 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,08-19 17:55:21.327  1021  4075 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:21.327  1021  4075 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-19 17:55:21.327  1021  4075 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-19 17:55:21.327  1021  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-19 17:55:21.327  1021  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-19 17:55:21.327  1021  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-19 17:55:21.327  1021  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-19 17:55:21.327  1021  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-19 17:55:21.337  1021  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-19 17:55:21.337  1845  6768 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-19 17:55:21.337  1845  6768 D AccountUtils: Clearing selected account for com.test.thalitest
,08-19 17:55:21.337  1021  1033 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-19 17:55:21.337  1021  1033 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,08-19 17:55:21.337  1021  1033 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:21.337  1021  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-19 17:55:21.337  1021  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-19 17:55:21.347  1021  1045 D UsbSettingsManager: clearDefaults: com.test.thalitest
08-19 17:55:21.347  1021  4073 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-19 17:55:21.347  1021  4073 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,08-19 17:55:21.347  1021  4073 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:21.347  1021  4073 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-19 17:55:21.347  1021  4073 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
08-19 17:55:21.347  1021  1045 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-19 17:55:21.367  1021  1225 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-19 17:55:21.367  1021  1225 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:21.367  1021  1225 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-19 17:55:21.367  1021  1225 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-19 17:55:21.377  1021  1033 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
,08-19 17:55:21.377  1021  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:21.377  1021  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:21.377  1021  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:21.377  1021  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:21.387  6747  6772 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-19 17:55:21.387  6747  6772 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-19 17:55:21.387  6775  6775 E Zygote  : MountEmulatedStorage()
,08-19 17:55:21.387  6775  6775 E Zygote  : v2
08-19 17:55:21.387  6775  6775 I libpersona: KNOX_SDCARD checking this for 1000
08-19 17:55:21.387  6775  6775 I libpersona: KNOX_SDCARD not a persona
,08-19 17:55:21.397  6775  6775 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-19 17:55:21.397  1021  1033 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6775 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-19 17:55:21.397  1021  1033 I ActivityManager: Killing 6170:com.sec.pcw.device/1000 (adj 15): empty #21
,08-19 17:55:21.397  6775  6775 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-19 17:55:21.397  6747  6772 D SPPClientService: PushLog.txt file is not deleted.
08-19 17:55:21.397  1021  4074 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-19 17:55:21.397  6775  6775 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-19 17:55:21.397  1021  4074 W ActivityManager: userId = 0, bbcId = -10000
,08-19 17:55:21.397  1021  1727 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-19 17:55:21.397  1021  4074 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-19 17:55:21.397  1021  1727 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService; callingUser = 0; userId(target) = 0
08-19 17:55:21.397  1021  4074 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-19 17:55:21.397  6747  6772 D SPPClientService: PushLog.txt file is not deleted.
08-19 17:55:21.397  6747  6772 D SPPClientService: ============PushLog. stop!
08-19 17:55:21.397  1021  1727 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:21.397  1021  1727 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-19 17:55:21.397  1021  1727 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-19 17:55:21.407  6481  6481 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,08-19 17:55:21.417  1021  1033 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,08-19 17:55:21.417  1021  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:21.417  1021  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:21.417  1021  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:21.417  1021  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:21.427  6775  6775 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-19 17:55:21.427  1845  6768 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,08-19 17:55:21.427  6775  6775 D ActivityThread: Added TimaKeyStore provider
,08-19 17:55:21.437  6791  6791 E Zygote  : MountEmulatedStorage(),
08-19 17:55:21.437  6791  6791 I libpersona: KNOX_SDCARD checking this for 1000
08-19 17:55:21.437  6791  6791 E Zygote  : v2
08-19 17:55:21.437  6791  6791 I libpersona: KNOX_SDCARD not a persona
08-19 17:55:21.437  6791  6791 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-19 17:55:21.437  6791  6791 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-19 17:55:21.437  1021  1033 I ActivityManager: Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=6791 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-19 17:55:21.437  6791  6791 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-19 17:55:21.437  1021  1033 I ActivityManager: Killing 6186:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
,08-19 17:55:21.447  1021  1125 D ActivityManager: startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
,08-19 17:55:21.447  1021  1125 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
,08-19 17:55:21.447  1021  1125 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:21.447  1021  1125 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:21.447  1021  1125 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,08-19 17:55:21.457  1021  1727 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-19 17:55:21.457  1021  1727 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.util.PreferenceService; callingUser = 0; userId(target) = 0
,08-19 17:55:21.457  1021  1727 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:21.457  1021  1727 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-19 17:55:21.457  1021  1727 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-19 17:55:21.467   306   306 I art     : Explicit concurrent mark sweep GC freed 8720(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 612us total 29.407ms
,08-19 17:55:21.477  1021  4073 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,08-19 17:55:21.477  1845  1845 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-19 17:55:21.477  1021  4073 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:21.477  1845  1845 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-19 17:55:21.477  1021  4073 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:21.477  1021  4073 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:21.477  1021  4073 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:21.487  6481  6481 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
,08-19 17:55:21.487  6791  6791 D TimaKeyStoreProvider: TimaSignature is unavailable
08-19 17:55:21.487  6791  6791 D ActivityThread: Added TimaKeyStore provider
,08-19 17:55:21.487   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 766us total 19.070ms
08-19 17:55:21.487  6481  6481 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
,08-19 17:55:21.507  6657  6657 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-19 17:55:21.507   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 623us total 19.019ms
,08-19 17:55:21.517  6775  6775 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 ,
,08-19 17:55:21.527  6809  6809 E Zygote  : MountEmulatedStorage()
,08-19 17:55:21.527  6809  6809 E Zygote  : v2
08-19 17:55:21.527  6809  6809 I libpersona: KNOX_SDCARD checking this for 10039
08-19 17:55:21.527  6809  6809 I libpersona: KNOX_SDCARD not a persona
,08-19 17:55:21.527  6809  6809 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-19 17:55:21.527  1021  4073 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=6809 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a,
08-19 17:55:21.527  1021  1524 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-19 17:55:21.527  6809  6809 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-19 17:55:21.527  6809  6809 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-19 17:55:21.537  1021  1524 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:21.537  1845  6799 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
08-19 17:55:21.537  1021  1524 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-19 17:55:21.537  1845  6799 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
08-19 17:55:21.537  1021  1524 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-19 17:55:21.537  1845  6799 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
08-19 17:55:21.537  1845  6799 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,08-19 17:55:21.537  6481  6481 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
08-19 17:55:21.537  6481  6481 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
,08-19 17:55:21.537  6481  6481 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
08-19 17:55:21.537  6481  6481 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
08-19 17:55:21.537  6481  6481 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
08-19 17:55:21.537  6481  6481 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
08-19 17:55:21.537  6481  6481 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
08-19 17:55:21.537  6481  6481 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
08-19 17:55:21.537  6481  6481 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
08-19 17:55:21.537  6481  6481 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
08-19 17:55:21.537  6481  6481 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
08-19 17:55:21.537  6481  6481 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
08-19 17:55:21.537  6481  6481 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
08-19 17:55:21.537  6481  6481 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
08-19 17:55:21.537  6481  6481 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
08-19 17:55:21.537  6481  6481 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
08-19 17:55:21.537  6481  6481 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
08-19 17:55:21.537  6481  6481 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,08-19 17:55:21.547  6481  6481 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
08-19 17:55:21.547  6481  6481 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
08-19 17:55:21.547  6481  6481 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
,08-19 17:55:21.547  6481  6481 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
08-19 17:55:21.547  1021  1033 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-19 17:55:21.547  1021  1033 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:21.547  1021  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-19 17:55:21.547  1021  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-19 17:55:21.547  1845  6799 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
08-19 17:55:21.547  1845  6799 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,08-19 17:55:21.547  1845  6799 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,08-19 17:55:21.557  1021  1728 D ActivityManager: startService callerProcessName:com.android.keychain, calleePkgName: com.android.keychain
08-19 17:55:21.557  1021  1728 D ActivityManager: retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
,08-19 17:55:21.557  1021  1728 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:21.557  1021  1728 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:21.557  1021  1728 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,08-19 17:55:21.557  1021  1225 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-19 17:55:21.557  1021  1225 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,08-19 17:55:21.557  1021  1225 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:21.557  1021  1225 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-19 17:55:21.557  1021  1225 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-19 17:55:21.557  1021  1225 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:21.557  1021  1225 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:21.557  1021  1225 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:21.557  1021  1225 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:21.567  1845  6799 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
08-19 17:55:21.567  1845  6799 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,08-19 17:55:21.567  6809  6809 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-19 17:55:21.567  6809  6809 D ActivityThread: Added TimaKeyStore provider,
,08-19 17:55:21.577  6791  6791 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.,
,08-19 17:55:21.577  2760  2817 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-19 17:55:21.577  6481  6481 D BluetoothAdapter: cancelDiscovery
,08-19 17:55:21.587  6827  6827 E Zygote  : MountEmulatedStorage()
08-19 17:55:21.587  6827  6827 E Zygote  : v2
08-19 17:55:21.587  6827  6827 I libpersona: KNOX_SDCARD checking this for 10011
08-19 17:55:21.587  6827  6827 I libpersona: KNOX_SDCARD not a persona
08-19 17:55:21.587  1845  6799 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
08-19 17:55:21.587  1845  6799 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,08-19 17:55:21.587  1845  6799 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
08-19 17:55:21.587  1845  6799 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,08-19 17:55:21.587  1021  1225 I ActivityManager: Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=6827 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,08-19 17:55:21.587  6827  6827 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-19 17:55:21.587  6827  6827 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-19 17:55:21.597  1845  1845 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-19 17:55:21.597  1845  1845 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-19 17:55:21.597  6827  6827 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-19 17:55:21.597  1021  4073 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-19 17:55:21.607  1021  4073 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:21.607  1021  4073 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:21.607  1021  4073 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:21.607  1021  4073 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:21.627  6845  6845 E Zygote  : MountEmulatedStorage()
08-19 17:55:21.627  6845  6845 E Zygote  : v2
08-19 17:55:21.627  6845  6845 I libpersona: KNOX_SDCARD checking this for 1000
08-19 17:55:21.627  6845  6845 I libpersona: KNOX_SDCARD not a persona
,08-19 17:55:21.627  6845  6845 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-19 17:55:21.627  6845  6845 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-19 17:55:21.627  6809  6809 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-19 17:55:21.627  1021  4073 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6845 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-19 17:55:21.627  6809  6809 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-19 17:55:21.627  6809  6809 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-19 17:55:21.627  6845  6845 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-19 17:55:21.627  6809  6809 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
08-19 17:55:21.627  6809  6809 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-19 17:55:21.627  6809  6809 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-19 17:55:21.627  6809  6809 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-19 17:55:21.627  6827  6827 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-19 17:55:21.627  6827  6827 D ActivityThread: Added TimaKeyStore provider
,08-19 17:55:21.637  1021  4073 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,08-19 17:55:21.637  1021  4073 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:21.637  1021  4073 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:21.637  1021  4073 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:21.637  1021  4073 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:21.657  6845  6845 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-19 17:55:21.657  6845  6845 D ActivityThread: Added TimaKeyStore provider
,08-19 17:55:21.667  6860  6860 E Zygote  : MountEmulatedStorage()
08-19 17:55:21.667  1021  4073 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6860 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-19 17:55:21.667  6860  6860 E Zygote  : v2
08-19 17:55:21.667  6860  6860 I libpersona: KNOX_SDCARD checking this for 1000
08-19 17:55:21.667  6860  6860 I libpersona: KNOX_SDCARD not a persona
,08-19 17:55:21.667  6860  6860 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-19 17:55:21.677  6643  6643 I wpa_supplicant: P2P: Current p2p state = IDLE,
08-19 17:55:21.677  6643  6643 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-19 17:55:21.677  6643  6643 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-19 17:55:21.677  6643  6643 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-19 17:55:21.677  6860  6860 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-19 17:55:21.677  1021  1033 D LocationManagerService: getProviders()=[passive, gps]
08-19 17:55:21.677  6860  6860 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-19 17:55:21.677  1021  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-19 17:55:21.677  1021  1130 D SecContentProvider2: mCursor = null
,08-19 17:55:21.687  2760  6593 D BluetoothAdapterProperties: mDiscovering is false
08-19 17:55:21.687  2760  6593 E BluetoothAdapterService: This is not a scanning status. cancelDiscovery() will be not called.
,08-19 17:55:21.697  6481  6481 D BluetoothAdapter: cancelDiscovery = true
08-19 17:55:21.697  6481  6481 V PlaceDetection v1.0.19 : [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
,08-19 17:55:21.697  1021  1546 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-19 17:55:21.697  6481  6481 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
08-19 17:55:21.697  6481  6481 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-19 17:55:21.707  1021  1499 I ActivityManager: Killing 6209:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,08-19 17:55:21.707  6827  6827 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-19 17:55:21.707  6827  6827 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-19 17:55:21.707  1021  3874 D ActivityManager: getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
,08-19 17:55:21.717  1021  3874 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:21.717  1021  3874 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:21.717  1021  3874 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:21.717  1021  3874 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:21.727  6860  6860 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-19 17:55:21.727  6860  6860 D ActivityThread: Added TimaKeyStore provider
,08-19 17:55:21.737  6877  6877 E Zygote  : MountEmulatedStorage()
,08-19 17:55:21.737  6877  6877 E Zygote  : v2
08-19 17:55:21.737  6877  6877 I libpersona: KNOX_SDCARD checking this for 10014
08-19 17:55:21.737  6877  6877 I libpersona: KNOX_SDCARD not a persona
,08-19 17:55:21.737  1021  3874 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=6877 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
,08-19 17:55:21.737  6877  6877 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-19 17:55:21.737  6845  6845 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-19 17:55:21.737  6877  6877 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-19 17:55:21.737  6845  6845 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-19 17:55:21.737  6845  6845 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-19 17:55:21.747  6877  6877 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-19 17:55:21.767  1845  6834 W BaseAppContext: Using Auth Proxy for data requests.
,08-19 17:55:21.787  1845  6894 E SQLiteLog: (28) failed to open "/data/data/com.google.android.gms/databases/DocList.db" with flag (131138) and mode_t (0) due to error (30)
,08-19 17:55:21.797  1021  1728 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-19 17:55:21.807  1021  1728 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:21.807  6877  6877 D TimaKeyStoreProvider: TimaSignature is unavailable
08-19 17:55:21.807  1021  1728 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:21.807  1021  1728 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-19 17:55:21.807  1021  1728 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-19 17:55:21.807  6877  6877 D ActivityThread: Added TimaKeyStore provider
,08-19 17:55:21.807  6827  6827 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
08-19 17:55:21.807  6827  6827 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>,
,08-19 17:55:21.817  6845  6845 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true,
08-19 17:55:21.817  6845  6845 I PCWCLIENTTRACE_PushUtil: sales region : global
08-19 17:55:21.817  6845  6845 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-19 17:55:21.817  6845  6845 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,08-19 17:55:21.827  6898  6898 E Zygote  : MountEmulatedStorage(),
08-19 17:55:21.827  6898  6898 E Zygote  : v2
08-19 17:55:21.827  6898  6898 I libpersona: KNOX_SDCARD checking this for 10117
08-19 17:55:21.827  6898  6898 I libpersona: KNOX_SDCARD not a persona
,08-19 17:55:21.827  1845  6894 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.,
08-19 17:55:21.827  1845  6894 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-19 17:55:21.827  1845  6894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-19 17:55:21.827  1845  6894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-19 17:55:21.827  1845  6894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-19 17:55:21.827  1845  6894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-19 17:55:21.827  1845  6894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-19 17:55:21.827  1845  6894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-19 17:55:21.827  1845  6894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-19 17:55:21.827  1845  6894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878),
08-19 17:55:21.827  1845  6894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-19 17:55:21.827  1845  6894 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-19 17:55:21.827  1845  6894 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-19 17:55:21.827  1845  6894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-19 17:55:21.827  1845  6894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-19 17:55:21.827  1845  6894 E SQLiteDatabase: 	at com.google.android.gms.drive.database.c.getWritableDatabase(SourceFile:223)
08-19 17:55:21.827  1845  6894 E SQLiteDatabase: ,	at com.google.android.gms.drive.database.m.b(SourceFile:598)
08-19 17:55:21.827  1845  6894 E SQLiteDatabase: 	at com.google.android.gms.drive.database.m.a(SourceFile:592)
08-19 17:55:21.827  1845  6894 E SQLiteDatabase: 	at com.google.android.gms.drive.database.o.run(SourceFile:613)
08-19 17:55:21.827  1845  6894 E AndroidRuntime: FATAL EXCEPTION: Open database in background
08-19 17:55:21.827  1845  6894 E AndroidRuntime: Process: com.google.android.gms, PID: 1845
08-19 17:55:21.827  1845  6894 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-19 17:55:21.827  1845  6894 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-19 17:55:21.827  1845  6894 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-19 17:55:21.827  1845  6894 E AndroidRuntime: 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-19 17:55:21.827  1845  6894 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-19 17:55:21.827  1845  6894 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-19 17:55:21.827  1845  6894 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-19 17:55:21.827  1845  6894 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-19 17:55:21.827  1845  6894 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-19 17:55:21.827  1845  6894 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-19 17:55:21.827  1845  6894 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-19 17:55:21.827  1845  6894 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-19 17:55:21.827  1845  6894 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-19 17:55:21.827  1845  6894 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-19 17:55:21.827  1845  6894 E AndroidRuntime: 	at com.google.android.gms.drive.database.c.getWritableDatabase(SourceFile:223)
08-19 17:55:21.827  1845  6894 E AndroidRuntime: 	at com.google.android.gms.drive.database.m.b(SourceFile:598)
08-19 17:55:21.827  1845  6894 E AndroidRuntime: 	at com.google.android.gms.drive.database.m.a(SourceFile:592)
08-19 17:55:21.827  1845  6894 E AndroidRuntime: 	,at com.google.android.gms.drive.database.o.run(SourceFile:613)
08-19 17:55:21.827  6827  6827 I MultiDex: VM with version 2.1.0 has multidex support
08-19 17:55:21.827  6827  6827 I MultiDex: install
08-19 17:55:21.827  6827  6827 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-19 17:55:21.827  6860  6897 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_REMOVED
,08-19 17:55:21.837  1021  1728 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6898 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a,
08-19 17:55:21.837  6898  6898 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-19 17:55:21.837  1021  1728 I ActivityManager: Killing 6228:com.sec.android.provider.badge/u0a68 (adj 15): empty #21,
,08-19 17:55:21.837  6898  6898 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-19 17:55:21.837  6898  6898 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-19 17:55:21.837  6791  6791 W FileUtils: Failed to chmod(/data/data/com.samsung.android.sm/databases/history.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,08-19 17:55:21.847  6860  6897 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,08-19 17:55:21.847  6898  6898 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-19 17:55:21.847  6898  6898 D ActivityThread: Added TimaKeyStore provider
,08-19 17:55:21.857  1021  1125 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,08-19 17:55:21.867  1681  1698 I art     : Explicit concurrent mark sweep GC freed 14155(682KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 7MB/13MB, paused 1.232ms total 75.644ms
08-19 17:55:21.867  1021  1524 D ActivityManager: startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
08-19 17:55:21.867  1021  1524 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
,08-19 17:55:21.867  1021  1524 W ActivityManager: userId = 0, bbcId = -10000
08-19 17:55:21.867  1021  1524 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-19 17:55:21.867  1021  1524 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,08-19 17:55:21.867  6860  6860 D AcmsService: Enter Oncreate
08-19 17:55:21.867  6860  6860 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-19 17:55:21.867  6860  6860 D AcmsService: creating AcmsCore
08-19 17:55:21.867  6860  6860 D AcmsCore: AcmsCore.getAcmsCore() - Enter
08-19 17:55:21.867  6860  6860 D AcmsCore: AcmsCore
,08-19 17:55:21.877  1021  6913 E DropBoxManagerService: Can't write: system_app_crash
08-19 17:55:21.877  1021  6913 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop181.tmp: open failed: EROFS (Read-only file system)
08-19 17:55:21.877  1021  6913 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-19 17:55:21.877  1021  6913 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-19 17:55:21.877  1021  6913 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-19 17:55:21.877  1021  6913 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-19 17:55:21.877  1021  6913 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-19 17:55:21.877  1021  6913 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15780)
08-19 17:55:21.877  1021  6913 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-19 17:55:21.877  1021  6913 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-19 17:55:21.877  1021  6913 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-19 17:55:21.877  1021  6913 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-19 17:55:21.877  1021  6913 E DropBoxManagerService: 	... 5 more

```
